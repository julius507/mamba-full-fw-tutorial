File Contents
01. flash_erase.exe - software for open adb enable modem to boot in usbmode.
02. balong_usbdload and fastboot erase full.exe - software for usbloader and erase all partition.
03. B525s-65a_Update_11.191.61.00.74_WebUI_21.100.52.00.03.exe - firmware and flasher (Update Wizard) for modem.
04. NVRAM Writer.exe - restoring nvram details of your modem.

Default WiFi Configuration
2.4GHz WiFi SSID: HUAWEI-B525-0000
5GHz WiFi SSID: HUAWEI-B525-5G-0000
2.4GHz and 5GHz WiFi Password: 00000000000

Model: B525s-65a
Software Version: 11.191.61.00.74
Web UI Version: 21.100.52.00.03

Main features: No borloloy, clean build and clean install. Base on stock firmware or firmware1.bin in optus ota update.

* Fix nvram image for bands and hardware configs of B525s-65a version. (Note: For B525s-65a only! Do not flash in B525s-95a and B525s-23a, nvram is not made for that version.)
* Change networks type name.
4G+ - LTE CA (4G+)
4G - LTE (4G)
3.5G - DC-HSPA+ (3G) / HSPA+ (3G)
3G - HSPA (3G) / HSUPA (3G) / HSDPA (3G) / UMTS (3G)
2G - GPRS (2G) / GSM (2G)
* Add mobile number, wan ip and signal information in homepage.
* Fix 51566 (DITO) network name and apn auto configuration.
* Working in HUAWEI HiLink (Mobile WiFi) and HUAWEI AI Life application, tested in iOS and Android.
* Enable SMS center number and validity in SMS.
* Enable Phonebook.
* Enable all bands and multi selector in 4G, 3G and 2G. (Default bands in optus firmware is 1,3,7,8,28 and 40 only.)
* Enable VoLTE.
* Enable L2TP and PPTP VPN client. (Working, tested on my server.)
* Enable WiFi Hardware in 2.4GHz (b/g/n) and 5GHz (a/n/ac).
* Enable DNS server manually in DHCP.
* Enable VoIP menu.
* Enable Bridge Mode.
* Add more details in device information.
* Enable set manually in time service settings.
* Enable USSD.
* Working USB Printer and Samba Server in USB. (Samba server is working in all file system, tested on my UGreen Enlosure with 1TB [NTFS File System].)
* Add BusyBox v1.31.0 /system/bin/busybox-armv7.
* Add kpatch.ko module in startup to enable writing in nvram or datalock is set to 0 /system/xbin/kpatch.ko.
* Enable adbd in startup for adb connect in modem ip address /system/xbin/adbd.
* Add atc for AT Commands /system/xbin/atc.
* No disconnection issue in router like MikroTik (RouterOS).
* Same speed in WiFi (wlan / Wireless LAN) and Ethernet port or via cable.