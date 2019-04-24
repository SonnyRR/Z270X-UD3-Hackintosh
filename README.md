<p align="center">
    <img src = "https://www.tonymacx86.com/images/tonymacx86-logo.png">
</p>

# Z270X-UD3-Hackintosh 
My Hackintosh repository.

Useful threads for GA-Z270X-UD3:
* [QuickTime's Kaby Lake i7-7700 Build:
GA-Z270X-UD3 - i7-7700 - GTX 960​](https://www.tonymacx86.com/threads/success-ga-z270x-ud3-i7-7700-gtx-960-16gb-samsung-evo-1tb.235935/)

* [GA-Z270X-UD3 with everything working and on-board video (I5 7600)](https://www.tonymacx86.com/threads/successful-installation-of-sierra-i5-7600-gigabyte-z270x-ud3.215025/)

* [corpnewt's vanilla Hackintosh guide](https://github.com/corpnewt/Hackintosh-Guide)

* [toleda's AppleHDA Realtek Audio guide](https://www.tonymacx86.com/threads/no-audio-devices-applehda-realtek-audio.234729/)

* [From Problems to Full Guide GA-Z270X-UD3 - i5-7600 - Geforce 1070Ti](https://www.tonymacx86.com/threads/from-problems-to-full-guide-ga-z270x-ud3-i5-7600-geforce-1070ti.251539/)

* [Hackintosher.com](https://hackintosher.com)

* [InsanelyMac Sierra / High Sierra / Mojave on mobos Serie 100 / 200 / 300 / SkyLake / KabyLake / CoffeeLake DSDT GUIDE](https://www.insanelymac.com/forum/topic/321872-guide-sierra-high-sierra-mojave-on-mobos-serie-100-200-300-skylake-kabylake-coffeelake-dsdt/)

# BIOS / UEFI Settings

📌 Loading optimized default settings are recommended before changing stuff.
 
* Fast Boot : Enabled
* Windows 8/10 Features : Other OS
* Storage Boot Option Control : UEFI
* VT-d : Disabled
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
