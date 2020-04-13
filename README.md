# Cisco AMP for EndPoints
Researchs about Cisco Antimalware Software: Cisco AMP for EndPoints (AMP4E).

## Current Versions
Current versions of the software.
```
Microsoft Windows: 7.2.5 Build 11663
Apple macOS: 1.12.0 Build ?
Linux CentOS: 1.12.0 Build ?
```

## Downloads
Direct access to final, beta/unrelease downloads.

**Microsoft Windows**

* Stable
```
Link: https://upgrades.amp.cisco.com/fireAMP/windows/7.2.5.11663/Release-Logging/installer-univ-tcp.exe
Hash: 9ea11428cb8f0196cb96aac2b6c9698fb3cbf4deb813f339c78252468abce48e
Date: 03/27/2020
```

* Beta
```
Link: https://upgrades.amp.cisco.com/fireAMP/windows/7.2.1.11529/Release-Logging/installer-univ-tcp.exe
Hash: 5a24d51bb86040b4ebed6bb77b3ccb4480df2bb92982b82615b15e9eeac49b3b
Date: 12/18/2019
```

**Apple macOS**
* Stable
```
https://upgrades.amp.cisco.com/fireAMP/osx/1.1X.X.XXX/upgrade-amp-eu.xml
https://upgrades.eu.amp.cisco.com/fireAMP/osx/1.1X.X.XXX/upgrade-amp-eu.xml
```

* Beta
```
```

**Linux CentOS 6/7**
* Stable
```
https://upgrades.amp.cisco.com/fireAMP/linux/1.XX.X.XXX/upgrade-amp-eu.xml
https://upgrades.eu.amp.cisco.com/fireAMP/linux/1.XX.X.XXX/upgrade-amp-eu.xml
```

* Beta
```
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
