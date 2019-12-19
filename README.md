# Cisco AMP for EndPoints
Researchs about Cisco Antimalware Software: Cisco AMP for EndPoints (AMP4E).

## Current Versions
Current versions of the software.
```
Microsoft Windows: 7.1.5 Build 11523
Apple macOS: 1.12.0 Build ?
Linux CentOS: 1.12.0 Build ?
```

## Downloads
Direct access to final, beta and unrelease downloads.
+ Microsoft Windows
```
https://upgrades.amp.cisco.com/fireAMP/windows/6.X.X.XXXXX/Release-Logging/installer-univ-tcp.exe
https://upgrades.eu.amp.cisco.com/fireAMP/windows/6.X.X.XXXXX/Release-Logging/installer-univ-tcp.exe
```

+ Apple macOS
```
https://upgrades.amp.cisco.com/fireAMP/osx/1.1X.X.XXX/upgrade-amp-eu.xml
https://upgrades.eu.amp.cisco.com/fireAMP/osx/1.1X.X.XXX/upgrade-amp-eu.xml
```

+ Linux CentOS 6/7
```
https://upgrades.amp.cisco.com/fireAMP/linux/1.XX.X.XXX/upgrade-amp-eu.xml
https://upgrades.eu.amp.cisco.com/fireAMP/linux/1.XX.X.XXX/upgrade-amp-eu.xml
```

## IPTray
For Microsoft Windows 10. Run in PowerShell.

Request
```
Get-ItemProperty -Path HKLM:\SOFTWARE\WOW6432Node\Microsoft\Windows\CurrentVersion\Run -name 'Immunet Protect'
```

Modification
```
Set-ItemProperty -Path HKLM:\SOFTWARE\WOW6432Node\Microsoft\Windows\CurrentVersion\Run -name 'Immunet Protect' -value '"C:\Program Files\Cisco\AMP\7.1.5\iptray.exe"'
```
