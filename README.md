========== SLIMROM for SAMSUNG I9300 ================

=============== IT'S VERY ALPHA =====================

send your bugs to artamonov @  gmail.com

Goals: to create lightweight AOSP ROM for i9300

Based on android 7.1.2_r23, Slimrom and AOSP. 
Changelogs for builds https://raw.githubusercontent.com/non1979/Slimroms_staff/master/changelog

Working:

	* wi-fi
	* mobile network and data 
	* camera and videorecorder.
	* gps 
	

Features:

	* It's clean SlimRom
	* Snap Camera from Lineage
	* 94kernel   smart settings for charging power and sound (ported from boeffla), on default tweaks are enabled 
	 more info on http://forum.xda-developers.com/showpost.php?p=64651867&postcount=3  (still in test)
	* gcc 7.0.1 for kernel
	* ROM updates publish once a week on androidfilehost.com 
	* Full OMS support, prebuild-substratum
	* Russian t9 for dialer 
	* auto mtp-usb 
	* Call recording
	* Adaway
	* OTA updates
	* Jelly (lineage browser)
	
Removed 

	* AdvancedDisplay
	
FAQ:

	* how to get root = install supersu
	https://download.chainfire.eu/1021/SuperSU/SR3-SuperSU-v2.79-SR3-20170114223742.zip  
	* Slimlauncher is awful = install Nova for example , only some theme can color SlimLauncher : SwiftBlack, SwiftDark and so on
	* kernel is modified from Lineage , boeffla kernel is suitable 
	* http://kernel.boeffla.de/sgs3/boeffla-kernel-cm/cm14.0_download/Stable/
	* you can use all substratum theme with SlimROM
	* in case of SMS problems - change manually SMS center  https://forum.xda-developers.com/showthread.php?t=1916507
	* you can only import contact from sim, export is not supported (and never willbe - samsung proprietary code )

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
- use microG instead of GAPPS https://www.dropbox.com/s/ikgn8o8qph5ehqs/microG-Aroma-Installer%2B%2813.06.17%29.zip?dl=0
https://forum.xda-developers.com/android/apps-games/app-microg-gmscore-floss-play-services-t3217616
http://4pda.ru/forum/index.php?showtopic=724118&st=720#entry53394487
(use  Lucky Patcher by ChelpuS or Uret Patcher by Jasi2169 to activate android patches )
