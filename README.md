========== SLIMROM for SAMSUNG I9300 ================
=============== IT'S VERY ALPHA =====================
send your bugs to artamonov @dog@ gmail.com

Goals: to create lightweight AOSP ROM for i9300

Changelogs for builds https://raw.githubusercontent.com/non1979/Slimroms_staff/master/changelog

Working:

	* wi-fi
	* mobile network and data 
	* camera and videorecorder.
	* gps 
	
Not working 

	* don't know yet
	
Temperately removed 

	* AdvancedDisplay
	* SMS (use Google SMS or Textra SMS insteed) 
	* AOSP browser (choose yout favorite from GP)
	
Features:

	* now it's clean SlimRom
	* Snap Camera from Lineage
	* 94kernel   smart settings for charging power and sound (ported from boeffla), on default tweaks are enabled 
	 more info on http://forum.xda-developers.com/showpost.php?p=64651867&postcount=3  (still in test)
	* ROM updates publish 1-4 times a week on androidfilehost.com 
	* SlimROM Theme (Substratum mod, it's a bit buggy and laggy for now, but usefull)

	
FAQ:

	* how to get root = install supersu
	https://download.chainfire.eu/1021/SuperSU/SR3-SuperSU-v2.79-SR3-20170114223742.zip  
	* Slimlauncher is awful = install Nova for example 
	* kernel is modified from Lineage , don't expect boeffla to run (but possible)
	* you can use all substratum theme with SlimROM, but it's a bit buggy now / no theme can color slimlauncher

Bugs and fixes:

	* MTP-host sometimes fails, freeze it in Titanium Backup 

In plans (not yet, fast to come):

	* OTA
	* Call recording
	* Adaway
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
