# QuickADB

## a Python based GUI for ADB &amp; Fastboot commands
Simple GUI created in Python in effort to make ADB &amp; Fastboot commands faster and easier for both beginners and experts. 

## FEATURES

Built-in SDK Platform Tools version 1.0.41 to execute the commands. The terminal also starts from the same directory as the platform tools, so you can execute any command without having the folder added to your PATH.

Logs section to keep track of the output.

ADB Section to execute the most needed ADB commands, including a quick Pull/Push feature.

Fastboot section to reboot into different modes and checking getvar variables. Supports locking and unlocking the bootloader. (****Command availability varies by device manufacturer.****)

Flashing section to flash 24 different partitions via fastboot. Supports ".img" and ".bin" files.

[V2.0.0] Advanced tab. Automatic driver installers, payload dumper powered by [@ssut's payload-dumper-go](https://github.com/ssut/payload-dumper-go), ADB debloater, Magisk installer and more.
## NOTES

**Always** keep an eye on the logs while flashing an image. If you get a faulty output, please use the terminal and flash the image manually before rebooting your device.

Kaspersky and 6 unknown vendors flag QuickADB as trojan. This is a false-positive alert. It happens because the program was compiled with PyInstaller, so it doesn't have a signature.

This software uses ssut's payload-dumper-go for payload extraction functionality, which is licensed under the Apache License 2.0.

### [Buy Me a Coffee](https://buymeacoffee.com/fl0w)

### [View XDA Thread](https://xdaforums.com/t/tool-quickadb-a-gui-to-execute-adb-fastboot-commands.4690673/) 


![toolV2 0 1](https://github.com/user-attachments/assets/d9c1230d-c6f3-490e-a609-c45251812038)



