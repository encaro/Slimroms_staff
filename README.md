========== SLIMROM for SAMSUNG I9300 ================

send your bugs to artamonov @  gmail.com

Goals: to create lightweight AOSP ROM for i9300

Based on android 7.1.2_r36, Slimrom and AOSP. 
Changelogs for builds https://raw.githubusercontent.com/non1979/Slimroms_staff/master/changelog

Working:

	* wi-fi
	* mobile network and data 
	* camera and videorecorder.
	* gps 
	

Features:

	* It's clean SlimRom
	* Snap Camera from Lineage
	* 94kernel   smart settings for charging power and sound and some CPU governor (ported from boeffla) 
	* arm-linaro gcc 7.1.1:20170720  for kernel
	* ROM updates publish once a week on androidfilehost.com 
	* Full OMS support, prebuild-substratum
	* Russian t9 for dialer 
	* auto mtp-usb 
	* Call recording
	* Adaway
	* OTA updates
	* Phonograph for music
	* Jelly (lineage browser)
	* some kernel improvement, thanks to A$teroid and Lord boeffla

		

FAQ:

	* how to get root = install supersu
	https://download.chainfire.eu/1021/SuperSU/SR3-SuperSU-v2.79-SR3-20170114223742.zip  
	* Slimlauncher is awful = install Nova for example , only some theme can color SlimLauncher : SwiftBlack, SwiftDark and so on
	* kernel is modified from Lineage , boeffla kernel is suitable 
	* http://kernel.boeffla.de/sgs3/boeffla-kernel-cm/cm14.0_download/
	* you can use all substratum theme with SlimROM
	* in case of SMS problems - change manually SMS center  https://forum.xda-developers.com/showthread.php?t=1916507
	* you can only import contact from sim, export is not supported (and never willbe - samsung proprietary code )
	A many things from boeffla kernel is ported,  you should use Kernel Aduitor (KA) to manage it.
	- many governor for CPU policy, for battery frendly use "zzmoove / 1100Mhz as max CPU / -50mV CPU Voltage"
	- smart settings for charging power and sound === in KA in init.d section edit 94kernel as you want, then ran it in KA 
	 more info on http://forum.xda-developers.com/showpost.php?p=64651867&postcount=3 


Bugs and fixes:

	* MTP-host sometimes fails, freeze it in Titanium Backup 
	
	
How to Install ROM

- install new TWRP 3.0.2-2 https://yadi.sk/d/TipbEwTV32M6KN
- Reboot to recovery
- Install ROM  https://www.androidfilehost.com/?w=files&flid=166123
- Install gapps http://opengapps.org (choose pico 7.1 for ARM)
- Install supersu , if needed https://download.chainfire.eu/1016/SuperSU/UPDATE-SuperSU-v2.79-20161211114519.zip 

Update ROM

- Reboot to recovery
- Install ROM (if downloaded via OTA, saved in /OTAupdates.)
- Install supersu , if needed
- Reboot

Reccomendation 
- use microG instead of GAPPS https://forum.xda-developers.com/android/development/microg-unofficial-installer-t3432360
