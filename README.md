# X96_Air_Hard_Brick_and_Short_Pin_Location
X96 Air Hard Brick and Short Pin Location

I once hard bricked my X96 Air and I had to find the short pin location through trial & error. So I created this repository as a reminder for me if it happens again in the future.

## My X96 Air board looks like this:

![X96 Air Board](https://i.ibb.co/p1Tqc6d/IMG-20221212-121352.jpg)

![X96 Air Board](https://i.ibb.co/1zdZq3n/IMG-20221212-121813.jpg)

## The short pin location is circled in red below
![enter image description here](https://i.ibb.co/q1spG7t/X96-Air-short-pin.jpg)

[Full Size Image](https://ibb.co/WKyf9Gb)

You can use a screwdriver or a tweezer to short them. 
1. Tutorial on how to unbrick your device (In Indonesian) https://www.youtube.com/watch?v=15nl3m7GsWs (Don't use the firmware in that video to flash your X96 Air)
2. The firmware that I used is [[v9] Aidan's Rom (X96 Max Plus A100) [S905X3] [ATV9].img](https://androidfilehost.com/?fid=2981970449027575443)
3. If you wanna flash openwrt on X96 Air, you can use OpenWrt ROOter Firmware for S905X3. Download [Here](https://www.mediafire.com/file/qetwo79gtctib31/ROOter-GoldenOrb-2022-08-26-s905x3_k5.10.138_2022.08.26.img.gz/file)
```
OpenWrt ROOter Latest Build: 2022-08-26
Changelog 2022-08-26:
- set argon as default theme
- raspi 4 support usb boot
- add kernel support multipath tcp/mptcpv0 (except amlogic STB)
- add turbo acc
- add lua-neturl
- include wss clash core 
- add driver wifi & ethernet
- rtl8723bu (tismart wifi)
- r8101
- r8152-vendor
- r8125
- r8168
Changelog 2022-06-30:
- bug fixes
- update rooter packages
- add rooter gps & gpoint
- add aria2 & ariang
- add vnstat
- new splash at 192.168.1.1/splash.html
- etc
```
```
WiFi SSID 1    : ROOter 2G
WiFi SSID 2    : ROOter 5G
WiFi Password  : rooter2017

Router/LuCI IP : 192.168.1.1
LuCI Username  : root
LuCI Password  : radenku.com
```
By default, the WiFi is off, enable it through `Luci - Wireless` or with the command `wifi up`
Credit for the OpenWrt Build: [radenku.com](https://radenku.com/firmware-rooter-goldenorb-stb-amlogic/)

Don't flash OpenWrt Firmware on your bricked X96 Air right away! Flash the Android Firmware first then proceed to flash OpenWrt to your SD card
