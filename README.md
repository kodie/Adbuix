![](/Adbuix/logo1.jpg?raw=true)
# Adbuix

**NOTE: This project is no longer being maintained and is simply here for archival purposes.**

Adbuix was a project that I worked on from 2009 to 2010 when I was 20 years old. It was written in something called [Gambas](http://gambas.sourceforge.net) which is basically Visual Basic for Linux.

I recently purchased an enclosure for an old 3.5" IDE hard drive that I've had lying around forever and came across the source code for Adbuix so I decided to go ahead and put it up on GitHub.

Even though the project was never finished, a lot of people did find it useful and it was even featured on the [XDA-Developers Front Page](https://www.xda-developers.com/adbuix-v0-0-1-a-gui-for-adb-on-linux/)!

You can view the discussion thread here: https://forum.xda-developers.com/showthread.php?t=641385

## About
Adbuix is a Graphic User Interface (GUI) for the Android Debug Bridge (ADB) on the Linux Operating System.

It eliminates the work of remembering commands or typing out directory paths when using ADB to modify files on your Android device.

Take this command for an example:
```
#adb -s emulator-5554 push /home/user/Desktop/Application.apk /system/app/Application.apk
```

That is a command that you would have to type out in a terminal to copy an application from your computer desktop to your Android device.

With Adbuix, you click the file you want to copy, click the folder you want to copy it to, and click the copy button. It's that easy!

## Known Bugs
* When using the program with an emulator instead of an actual device, in the file manager, folders have file icons instead of folders, but everything works as expected.

## Compatibility

### Operating Systems
* Ubuntu 8.04 (Hardy Heron) - Crashes with a "segmentation fault".
* Ubuntu 9.10 (Karmic Koala) - Works fine.
* Ubuntu 10.04 BETA 1 (Lucid Lynx) - Works fine.

### Devices
* HTC Dream w/ CyanogenMod - Works fine.
* HTC Tattoo w/ Stock Rom - Works fine.
* HTC Tattoo w/ Open Eclair - Works fine.

## Future Features
* Partition Manager
* Shell Console
* Image Flashing
* Rom Flashing
* Rythmbox Integration
* Much Much More...

## Download
**Adbuix v0.1.1:**

http://kodieg.com/dl/adbuix_0_1_1.deb (Released 5/06/2010) (UNSTABLE)

(Right Click, Save Link As...)


**Adbuix Updater Bash Script v1.0.1:**

http://kodieg.com/dl/adbuixupdate.sh (Released 3/26/2010)

(Right Click, Save Link As...)

## How to Install
Download the Adbuix Debian Package above and run it. Adbuix should be added to your main programs menu under "Other".

## How to Update
Open up a terminal and type "/usr/share/adbuix/update.sh", or just download the package again.

## ChangeLog
```
[3] v0.1.1 - 5/06/2010 - 376.4KB
 - Fixed bug where program would crash when started if logs folder wasn't there. (Thanks HorusUK)

[2] v0.1.0 - 4/25/2010 - 376.3KB
 - Added menu bar on main window.
 - Added buttons for some future features in the main window.
 - Added shutdown function to reboot window.
 - Added logging system.
 - Added device log import system.
 - Added "Discuss Adbuix" menu option.
 - Added "Author" tab in about window.
 - Changed main window look.
 - Changed reboot window look.
 - Fixed "restart server & refresh" button crash bug.
 - Fixed desktop shortcut name and icon.
 - Disabled "Check for updates" feature until I fix it.
 - Disabled "Online Help" feature until I finish the help page.
```
Official changelog here: http://kodieg.com/dl/adbuix_changelog.txt

## Screenshots
![Main Screen](/assets/adbuix_main.png?raw=true "Main Screen")
![Devices Screen](/assets/adbuix_devices.png?raw=true "Devices Screen")
![App Manager](/assets/adbuix_appmanager.png?raw=true "App Manager")
![File Manager](/assets/adbuix_filemanager.png?raw=true "File Manager")

## Thank You!
Thank you for trying out my program. Please feel free to reply in this thread any comments, suggestions, questions, bug reports, ect. and i will respond to you as soon as i can. :D
