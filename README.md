Windows OS tools/scripts you need to flash an extracted ROM for Motorola devices. It contains adb.exe, 2 supporting .dll's, flashboot.exe, and 3 different scripts to flash extracted ROM's directly to the device.

I have merely taken RootJunky's repo and updated the adb.exe and fastboot.exe with versions I captured from the Lenovo Smart Recovery tool on 7-24-2020.

These files should confirm the proper version of fastboot.exe to use for the Moto G6 XT1925-6 (and similar devices). There are many articles telling users to use mflashboot.exe. You will see that this version of fastboot contains some of the functionalities of mflashboot that flashboot did not previously feature. (Compare the older versions of ".\flashboot.exe --help" with ".\mflashboot.exe --help" that you can find around the web.)
