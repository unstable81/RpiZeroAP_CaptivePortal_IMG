# RpiZeroAP_CaptivePortal_IMG
Raspberry Pi Zero W - With RaspberryPi Lite OS Running HOSTAP &amp; DNSMASQ &amp; APACHE2

This project is not my own I got bits from all over, I just wanted a place to put my final take on it

This little Raspberry Pi Zero W will boot up headless, create a Open Wifi hotspot (all editable in the /etc/dnsmasq.conf and /etc/hostapd/hostapd.conf)
to login let the RPi boot until you see the wifi network (Facebook **Free Wifi**) login and wait for the Captive Portal to load. Now you can access via SSH using 192.168.0.1
with username: pi and password: raspberry

You wont be able to update the pi or download anything until you disable the IP Redirect, this is done in the /etc/dnsmasq.conf file just change address=/#/192.168.0.1
 to #address=/#/192.168.0.1
 
 If you use this a Captive Portal like its setup inside this image, you just burn the image chuck it in the raspberry pi zero w and watch as people join the network, the signup page
 will redirect back to 192.168.0.1 but you could always add another wifi adapter and sit near by sharing your mobile internet.
 The login details from the captive portal are stored in /var/www/html/Auth.txt
 
 I'm using my version to share movies to all the family and friends that we go camping with. this Facebook was just to trick the inlaws so please dont hate on me for the low quality 
 portal lol
 
 Anyway enjoy and I probably cant help with trouble shooting as I borrowed all my information from others as I have only been playing with linux and RPi for about 2 weeks
 
 :)
 

