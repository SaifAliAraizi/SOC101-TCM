References
- https://git-scm.com/
- https://github.com/MalwareCube/SOC101

Commands
********
Disable real-time protection

Set-MpPreference -DisableRealtimeMonitoring $true


Disable the scanning of network files

Set-MpPreference -DisableScanningNetworkFiles $true


Disable the blocking of files at first sight

Set-MpPreference -DisableBlockAtFirstSeen $true


Disable Windows Defender AntiSpyware

reg add "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f


![[2.1-configring-window.png]]
![[2.2-configring-window.png]]

Clone the course repository

git clone https://github.com/MalwareCube/SOC101.git


Next, extract each of the course ZIP files onto the desktop using the password below:

ZIP file password
murky-backboard-headache