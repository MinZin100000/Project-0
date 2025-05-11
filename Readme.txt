Pre-requisites:

1- Unlocked bootloader. ( Check-out )

2- Recovery IMG. (Check links section end-thread)

3- USB debugging enabled:

- Go to settings -> My device -> All specs -> hit build number 7 times till you see message ( you are developer now..)
- Then go to settings -> Additional settings -> Developers options -> Toggle on "USB debugging".

4- Download Minimal ADB Fastboot & install it.

Steps for PE, Lineage, OrangeFox Recoveries:

1- Download the custom recovery IMG and save it on your PC.
2- re-name the IMG file to easy name such as: flash_me.img
3- copy the IMG file to the "Minimal ADB Fastboot" installation Dictionary.
4- Run "cmd-here.exe" as Administrator.
5- turn off your device and hold the "volume down + power" to enter fastboot mode.
6- once you booted in fastboot plug-in your device with usb cable to PC.
7- type in cmd (Don't use it for TWRP RECOVERY) :

Code:
 fastboot flash boot flash_me.img

This will keep you in fastboot after install done .

Type in cmd:
Code:
 fastboot reboot

when you hit enter press and hold the volume-UP button till you boot to the recovery otherwise if booted to system you need to repeat steps.
