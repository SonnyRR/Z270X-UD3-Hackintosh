<p align="center">
    <img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/MacOS_wordmark_%282017%29.svg/512px-MacOS_wordmark_%282017%29.svg.png">
</p>

# 🍎 Z270X-UD3 Hackintosh 
A Hackintosh (a portmanteau of "Hack" and "Macintosh") is a computer that runs Apple's Macintosh operating system macOS on computer hardware that is not authorized for the purpose by Apple. This can also include running Macintosh software on hardware it is not originally authorized for. 

Useful threads for GA-Z270X-UD3:
* [QuickTime's Kaby Lake i7-7700 Build: GA-Z270X-UD3 - i7-7700 - GTX 960​](https://www.tonymacx86.com/threads/success-ga-z270x-ud3-i7-7700-gtx-960-16gb-samsung-evo-1tb.235935/)

* [GA-Z270X-UD3 with everything working and on-board video (I5 7600)](https://www.tonymacx86.com/threads/successful-installation-of-sierra-i5-7600-gigabyte-z270x-ud3.215025/)

* [corpnewt's vanilla Hackintosh guide](https://github.com/corpnewt/Hackintosh-Guide)

* [toleda's AppleHDA Realtek Audio guide](https://www.tonymacx86.com/threads/no-audio-devices-applehda-realtek-audio.234729/)

* [From Problems to Full Guide GA-Z270X-UD3 - i5-7600 - Geforce 1070Ti](https://www.tonymacx86.com/threads/from-problems-to-full-guide-ga-z270x-ud3-i5-7600-geforce-1070ti.251539/)

* [Hackintosher.com](https://hackintosher.com)

* [InsanelyMac Sierra / High Sierra / Mojave on mobos Serie 100 / 200 / 300 / SkyLake / KabyLake / CoffeeLake DSDT GUIDE](https://www.insanelymac.com/forum/topic/321872-guide-sierra-high-sierra-mojave-on-mobos-serie-100-200-300-skylake-kabylake-coffeelake-dsdt/)

# OS Tested
* macOS High Sierra 10.13.1 (Avoid this and 10.13.0 due to security issues)
* macOS High Sierra 10.13.6
* macOS Mojave 10.14.4
* macOS Mojave 10.14.6

# BIOS / UEFI Settings

📌 Loading optimized default settings are recommended before changing stuff or see my UEFI profile.
 

* Fast Boot : Enabled
* Windows 8/10 Features : Other OS
* Storage Boot Option Control : UEFI
* VT-d : Disabled/Enabled (if I want virtualization)
* XHCI Handoff : Enabled (In USB Configuration)
* DVMT Pre-Allocated : 128M (64M?)
* ErP : Enabled (Disabled for High Sierra)
* Platform Power Management : Disabled

I do not use iGFX, AMD All the way.

# Other
* SMBIOS : iMac18,1 for < 10.12.6 else use latest iMac18 definitions.
* Intel Core i7-7700K FakeCPUID : 0x0506E3 (for spoofing before 10.12.6).
* Intel® HD Graphics 630 : 0x19168086 (for spoofing before 10.12.6).
* Disable SIP by changing CsrActiveConfig string value to "0x67".
