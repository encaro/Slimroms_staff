========== SLIMROM for SAMSUNG I9300 ================
=============== IT'S VERY ALPHA =====================
send your bugs to artamonov @dog@ gmail.com

Goals: to create lightweight AOSP ROM for i9300

Based on android 7.1.1 r26, Slimrom and AOSP. 
Changelogs for builds https://raw.githubusercontent.com/non1979/Slimroms_staff/master/changelog

Working:

	* wi-fi
	* mobile network and data 
	* camera and videorecorder.
	* gps 
	
Not working 

	* don't know yet
	* videocalls for viber and whatapss (will be fix somewhen in LineageOS)
	
Removed 

	* AdvancedDisplay
	* SMS (use Google SMS or Textra SMS insteed) 
	* AOSP browser (choose yout favorite from GP)
	
Features:

	* It's clean SlimRom
	* Snap Camera from Lineage
	* 94kernel   smart settings for charging power and sound (ported from boeffla), on default tweaks are enabled 
	 more info on http://forum.xda-developers.com/showpost.php?p=64651867&postcount=3  (still in test)
	* ROM updates publish 1-4 times a week on androidfilehost.com 
	* Full OMS support, prebuild-substratum
	* Russian t9 for dialer 
	* auto mtp-usb 
	* Call recording
	* Adaway
	* Magisk as prebuild root (you can use supersu too) 

FAQ:

	* Slimlauncher is awful = install Nova for example 
	* kernel is modified from Lineage , boeffla kernel is suitable and usually work, but not tested by me
	http://kernel.boeffla.de/sgs3/boeffla-kernel-cm/cm14.0_download/Test/
	* you can use all substratum theme with SlimROM, but it's a bit buggy now / no theme can color slimlauncher
	* in case of SMS problems - change manually SMS center  https://forum.xda-developers.com/showthread.php?t=1916507
	* you can only import contact from sim, export is not supported (and never willbe - samsung proprietary code )

Bugs and fixes:

	* MTP-host sometimes fails, freeze it in Titanium Backup 
	* for substratum give memory permition on first boot, then reboot, and all problems will disappear  

In plans (not yet, fast to come):

	* OTA
	* more to come
	
	
How to Install ROM

- install new TWRP 3.0.2-2 https://yadi.sk/d/TipbEwTV32M6KN
- Reboot to recovery
- Install ROM  https://www.androidfilehost.com/?w=files&flid=166123
- Install gapps http://opengapps.org (choose pico 7.1 for ARM)

Update ROM

- Reboot to recovery
- Install ROM (if downloaded via OTA, saved in /OTAupdates.)
- Reboot
