Modem and network restart daemon for connecting  with proto Modemmanager,Openwrt. An alternative to Watchcat and the "10-report-down" script.

Dependence: modemmanager luci-proto-modemmanager.

Disable script execution /usr/lib/ModemManager/connection.d/10-report-down.

Move script "modem-watchdog"   to "/usr/bin/modem-watchdog" и chmod +x/usr/bin/modem-watchdog.

Place the file "modem-watchdog(etcinit.d)"  in "/etc/init.d/modem-watchdog" , rename to "modem-watchdog" ,  chmod +x /etc/init.d/modem-watchdog.
