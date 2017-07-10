# Bash-for-Windows
Add Bash via Powershell

Use PowerShell to enable your device

Run PowerShell with administrator privileges.
To enable sideloading, run this command:

PS C:\WINDOWS\system32> reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\AppModelUnlock" /t REG_DWORD /f /v "AllowAllTrustedApps" /d "1"

OR -

To enable developer mode, run this command:

PS C:\WINDOWS\system32> reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\AppModelUnlock" /t REG_DWORD /f /v "AllowDevelopmentWithoutDevLicense" /d "1"

If you only run the 1st command, it will turn on sideloading but not enable developer mode. You must run both

Once both commands are run, enter the following command

Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
