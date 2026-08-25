# FloppyLauncher
An autohotkey program designed to launch applications on your computer via Floppy Diskette, Zip Diskette, or any other external media device.

This application requires at least (Autohotkey V2.0) and (_JXON.ahk). A copy of which will be included and linked to so the original developers get credit. This also does require you to have a functional floppy disk drive plugged into your PC, weather that be through a USB adapter or just a USB compatible drive.

Be sure to read the full read me to make sure you know how to set the files up properly to allow it to run on your system!

To start, unzip the Flops.zip where ever you would like the files to live on your PC. The launcher will create a desktop shortcut for itself later on in this process. Then, you will need to take and edit the files within DISK DATA and place them on the actual disk you plan to store the program data on. You will need to repeat this step for every disk you make to launch a program on your PC. Remember to edit the launch.bat and disk.json files to your specifications. Comments are included throughout to guide you through the process.

After these few steps, you may need to alter the drive path in the actual FloppyLauncher.ASH if you are using any other drive other than A:/. For most disk readers, this is what they should default too, but in the event you have 2 disk drives or are attempting to use this code to launch data on another forms of external media drive then you will need to change the drive letter in the launcher to match that on the media drive you are attempting to target. Once these steps have been completed, double click the FloppyLauncher.ASH to create the shortcut file on your desktop and you should hear you drive chirp as it attempts to read the disk data. From this point on, you should see the disk icon update any time you attempt to click the shortcut, however, clicking the shortcut WILL launch the program data you have stored on the disk. So, if you wish to avoid launching the disk data but still wish to update the icon and launcher shortcut, feel free to use the F9 Hotkey coded into the launcher for this exact purpose.

NOTE: You may still use the drive as any normal floppy disk drive, this should not impair its functionality unless you tamper with the CheckFloppy timer. Any empty disk or data disk without the launch.bat, disk.json, or NAME.ico the launcher is searching for will cause the launcher to return the error message box and should not damage any data already stored on the disk.
DO NOT TAMPER WITH THE _JXON FILE BY ANY MEANS!!!
This file is essential to the functionality of the code overall and should not be altered in any way.

The original _JXON GITHUB is linked below. Thank you so much to cocobelgica!
https://github.com/cocobelgica/AutoHotkey-JSON/blob/master/Jxon.ahk

