Modem and network restart daemon for connecting with proto Modemmanager,Openwrt. An alternative to Watchcat and standart script  "/usr/lib/ModemManager/connection.d/10-report-down"

disable "/usr/lib/ModemManager/connection.d/10-report-down"

Move script "modem-watchdog" to /usr/bin/modem-watchdog

chmod +x/usr/bin/modem-watchdog

Place the file "modem-watchdog(etcinit.d)" in /etc/init.d/modem-watchdog , rename to "modem-watchdog" ,

chmod +x /etc/init.d/modem-watchdog

/etc/init.d/modem-watchdog enable

/etc/init.d/modem-watchdog start
