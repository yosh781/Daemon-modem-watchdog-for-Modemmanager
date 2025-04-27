 This service is needed in a scenario where the modem hangs up and there is no connection. This can be due to ISP reconnections, due to modem overheating, 
due to modem firmware ....


Modem and network restart daemon for connecting with proto Modemmanager,Openwrt. An alternative to Watchcat. 


Move script "modem-watchdog" to /usr/bin/modem-watchdog

chmod +x /usr/bin/modem-watchdog

Place the file "modem-watchdog(etcinit.d)" in /etc/init.d/modem-watchdog , rename to "modem-watchdog" ,

chmod +x /etc/init.d/modem-watchdog

/etc/init.d/modem-watchdog enable

/etc/init.d/modem-watchdog start
