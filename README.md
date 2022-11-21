# WinActivate - Cleaned up Mirror of [rany2/winactivate](https://github.com/rany2/winactivate)
This is a mirror of [rany2/winactivate](https://github.com/rany2/winactivate), with precompiled binaries included, and the folder structure cleaned up. Original description: Easy-to-use Windows HWID/KMS38 Activation Script.

## Usage
Run "winactivate.cmd" as an administrator, usually by right-clicking it and clicking on "Run as Administrator" - this is just a quicker way of running the PowerShell script that is doing the actual patching.

## How can I activate Windows 10 Enterprise LTSC 2021 using HWID?
You can't. You'll first have to switch the edition to **Windows 10 IoT Enterprise LTSC 2021**. To do this with WinActivate, run the following command:
```batch   
 winactivate.cmd -ProductKey QPM6N-7J2WJ-P88HH-P3YRH-YY74H
```
## Credits
- [Integrated Patcher 3 (slc.dll)](https://github.com/Gamers-Against-Weed/Integrated_Patcher_3)
