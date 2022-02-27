# Awesome Bluetooth Security (BR, EDR, LE, and Mesh)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This list links to useful references for anyone working with Bluetooth BR/EDR/LE or Mesh security.  

Submit a PR if something is missing!

### To Do

- Add list of useful research papers and whitepapers
- Add list of useful articles
- Add list of useful books

------

## Contents

- [Notable Vulnerabilities](#notable_vulnerabilities)
- [Conference Talks](#conference_talks)
- [Bluetooth Security Tools](#bluetooth_security_tools)
- [Primary Reference Materials](#primary_references)
- [Useful Sites](#useful_sites)

------

## <a name="notable_vulnerabilities"></a>Notable Vulnerabilities

| Vulnerability name | Conference & Year published | Vulnerability website URL | Paper URL | Video URL | SIG Notice | Technology Impacted | Related CVE |
| :---- | :---------- | :------------------------------- | :----------- | :------ | :------ | :------ | :----------- |
| BlueBorne | Black Hat Europe 2017 | [Site](https://www.armis.com/blueborne/) | [Paper](https://info.armis.com/rs/645-PDC-047/images/BlueBorne%20Technical%20White%20Paper_20171130.pdf) | [Video](https://www.youtube.com/watch?v=LLNtZKpL0P8) | No Notice | BR/EDR | CVE-2017-8628, CVE-2017-0781, CVE-2017-0782, CVE-2017-0783, CVE-2017-0785, CVE-2017-14315, CVE-2017-1000250, CVE-2017-1000251, CVE-2017-14315, CVE-2017-1000410 |
| Bleedingbit | 2018 | [Site](https://www.armis.com/bleedingbit/) | [Paper](https://info.armis.com/rs/645-PDC-047/images/Armis-BLEEDINGBIT-Technical-White-Paper-WP.pdf) | [Video](https://www.youtube.com/watch?v=pZpAUapKvGY) | No Notice | LE | CVE-2018-7080, CVE-2018-16986 |
| Fixed Coordinate Invalid Curve Attack | 2018 | [Site](https://www.cs.technion.ac.il/~biham/BT/) | [Paper](https://www.cs.technion.ac.il/~biham/BT/bt-fixed-coordinate-invalid-curve-attack.pdf) | No Video | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/bluetooth-technology/bluetooth-security/bluetooth-sig-security-update/) | BR/EDR/LE | CVE-2018-5383 |
| SweynTooth | 2019 | [Site](https://asset-group.github.io/disclosures/sweyntooth/) | [Paper](https://asset-group.github.io/disclosures/sweyntooth/sweyntooth.pdf) | [Video](https://www.youtube.com/watch?v=Iw8sIBLWE_w) | No Notice | LE | CVE-2019-16336, CVE-2019-17060, CVE-2019-17061, CVE-2019-17517, CVE-2019-17518, CVE-2019-17519, CVE-2019-17520, CVE-2019-19192, CVE-2019-19193, CVE-2019-19194, CVE-2019-19195, CVE-2019-19196, CVE-2020-10061, CVE-2020-10069, CVE-2020-13593, CVE-2020-13594, CVE-2020-13595 |
| KNOB | USENIX 2019 | [Site](https://knobattack.com/)   | [Paper](https://www.usenix.org/system/files/sec19-antonioli.pdf) | [Video](https://www.youtube.com/watch?v=v9Xg9XcnNh0) | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/bluetooth-technology/bluetooth-security/reporting-security/statement-key-negotiation-of-bluetooth/) | BR/EDR  |  CVE-2019-9506 |
| BIAS | IEEE S&P 2020 | [Site](https://francozappa.github.io/about-bias/) | [Paper](https://francozappa.github.io/about-bias/publication/antonioli-20-bias/antonioli-20-bias.pdf) | [Video](https://www.youtube.com/watch?v=fASGU7Og5_4) | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/bluetooth-technology/bluetooth-security/bias-vulnerability/) | BR/EDR | CVE-2020-10135 |
| Pairing Method Confusion | 2020 | [Site](https://github.com/maxdos64/BThack) | [Paper](https://www.computer.org/csdl/proceedings-article/sp/2021/893400a213/1mbmHzm2Q6c) | No Video | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/bluetooth-technology/bluetooth-security/method-vulnerability/) | BR/EDR/LE | CVE-2020-10134 |
| BlueFrag | 2020 | [Article](https://insinuator.net/2020/04/cve-2020-0022-an-android-8-0-9-0-bluetooth-zero-click-rce-bluefrag/) | No Paper | No Video | No Notice | Android | CVE-2020-0022 |
| Spectra | Black Hat USA 2020 | [Abstract](https://www.blackhat.com/us-20/briefings/schedule/index.html#spectra-breaking-separation-between-wireless-chips-20005) | TBD | [Video](https://www.youtube.com/watch?v=GZd66uVGKn8) | No Notice | WiFi+BT modules | CVE-2019-15063, CVE-2020-10367, CVE-2020-10368, CVE-2020-10369, CVE-2020-10370 |
| BLURtooth | 2020 | No site | No Paper | No Video | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/bluetooth-technology/bluetooth-security/blurtooth/) | BR/EDR+LE | CVE-2020-15802 |
| BLESA | WOOT 2020 | [Site](https://www.usenix.org/conference/woot20/presentation/wu) | [Paper](https://www.usenix.org/system/files/woot20-paper-wu-updated.pdf) | [Video](https://www.youtube.com/watch?v=wIWZaSZsRc8) | No Notice | LE | CVE-2020-9770 |
| BleedingTooth | 2020 | [Site](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00435.html) | [Writeup](https://google.github.io/security-research/pocs/linux/bleedingtooth/writeup) | [Video](https://www.youtube.com/watch?v=qPYrLRausSw) | No Notice | Linux | CVE-2020-12351, CVE-2020-12352, CVE-2020-24490 |
| BlueMirror | WOOT 2021 | [Site](https://kb.cert.org/vuls/id/799380) | [Paper](https://ieeexplore.ieee.org/abstract/document/9474325) | [Video](https://www.youtube.com/watch?v=Ai5-IrCI3kg) | [Multiple SIG Notices](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/reporting-security/) | BR/EDR/LE/Mesh | CVE-2020-26555, CVE-2020-26556, CVE-2020-26557, CVE-2020-26558, CVE-2020-26559, CVE-2020-26560 |
| InjectaBLE | IEEE DSN 2021 | [Site](https://github.com/RCayre/injectable-firmware) | [Paper](https://archivesic.ccsd.cnrs.fr/LAAS-TSF/hal-03193297v2) | No Video | [SIG Notice](https://www.bluetooth.com/learn-about-bluetooth/key-attributes/bluetooth-security/injectable/) | LE | CVE-2021-31615 |
| BrakTooth | 2021 | [Site](https://asset-group.github.io/disclosures/braktooth/) | [Paper](https://asset-group.github.io/disclosures/braktooth/braktooth.pdf) | [Video](https://www.youtube.com/watch?v=F7VjuOiUsNk) | No Notice | BR/EDR | CVE-2021-28135, CVE-2021-28136, CVE-2021-28139, CVE-2021-28155, CVE-2021-31717, CVE-2021-31609, CVE-2021-31611, CVE-2021-31612, CVE-2021-31613, CVE-2021-31785, CVE-2021-31786, CVE-2021-31610, CVE-2021-34143, CVE-2021-34144, CVE-2021-34145, CVE-2021-34146, CVE-2021-34147, CVE-2021-34148, CVE-2021-34149, CVE-2021-34150 |

------

## <a name="conference_talks"></a>Conference Talks

### 2003

- DEF CON 11 - Bruce Potter - Bluetooth - The Future of Wardriving [Video](https://www.youtube.com/watch?v=T-8m0jBdLF0)

### 2005

- 22C3 - Marcel Holtmann, Martin Herfurt, Adam Laurie: Bluetooth Hacking - The State of The Art [Video](https://www.youtube.com/watch?v=ynjZOIu_HqQ)

### 2006

- 23C3 - Thierry Zoller, Kevin Finistere: Bluetooth Hacking Revisited [Video](https://www.youtube.com/watch?v=DLMsLIZp5ww)

### 2007

- DeepSec 2007 - Marcel Holtmann: New Security Model of Bluetooth 2.1 [Video](https://www.youtube.com/watch?v=jXtDhQTqhKg)

### 2009

- DEF CON 17 - Dominic Spill, Michael Ossmann, and Mark Steward - Bluetooth Smells like Chicken [Video](https://www.youtube.com/watch?v=Ru8RshSVkGI)  
- Shmoocon 2009 - Bluetooth-Ossman.m4v [Video](https://www.youtube.com/watch?v=KPp4TjJVJb8)  

### 2010

- Shmoocon 2010 - Michael Ossmann - Bluetooth Keyboards: Who Owns Your Keystrokes? [Video](https://www.youtube.com/watch?v=X0RUN6SB6c8)  
- DEF CON 18: Breaking Bluetooth by Being Bored 1/3 [Video](https://www.youtube.com/watch?v=Ibia1Bn2Er8)  

### 2011

- ShmooCon 2011: Project Ubertooth: Building a Better Bluetooth Adapter [Video](https://www.youtube.com/watch?v=KSd_1FE6z4Y)  
- DeepSec 2011 - Tommi Makila & Jukka Taimisto: Intelligent Bluetooth Fuzzing - Why bother? [Video](https://www.youtube.com/watch?v=Rvzrr_jfH64)

### 2012

- Ruxcon 2012: Bluetooth Packet Sniffing Using Project Ubertooth - Dominic Spill [Video](https://www.youtube.com/watch?v=HU5qi7wimAM)
- Toorcon 2012 - Hacking Bluetooth Low Energy: I Am Jack's Heart Monitor [Video](https://www.youtube.com/watch?v=4POOiVrdnX8)
- DEF CON 20: Passive Bluetooth Monitoring in Scapy [Video](https://www.youtube.com/watch?v=FruyviVhvR8)

### 2013

- USENIX WOOT 2013 - Mike Ryan - Bluetooth: With Low Energy Comes Low Security [Video](https://www.youtube.com/watch?v=Mo-FsEmaqpo)  
- ShmooCon 9 - How Smart Is Bluetooth Smart? [Video](https://www.youtube.com/watch?v=0FfvLxW_cZg)  
- Blackhat USA 2013 - Bluetooth Smart: The Good, the Bad, the Ugly, and the Fix! [Video](https://www.youtube.com/watch?v=SoH11fi-FcA)  
- DeepSec 2013 - Veronica Valeros & Sebastian Garcia: Uncovering your Trails - Privacy Issues of Bluetooth Devices [Video](https://www.youtube.com/watch?v=j3fWjpxZFQE)

### 2014

- CanSecWest 2014: Outsmarting Bluetooth Smart [Video](https://www.youtube.com/watch?v=dYj6bpDzID0)  
- DEF CON 22 - The NSA Playset Bluetooth Smart Attack Tools [Video](https://www.youtube.com/watch?v=_Z4gYyrKVFM)  
- DEF CON 22 - Grant Bugher - Detecting Bluetooth Surveillance Systems [Video](https://www.youtube.com/watch?v=85uwy0ACJJw)  

### 2015

- DEF CON 23 - Mike Ryan and Richo Healey - Hacking Electric Skateboards [Video](https://www.youtube.com/watch?v=JZ3EB68v_B0)  

### 2016

- DEF CON 24 - Anthony Rose, Ben Ramsey - Picking Bluetooth Low Energy Locks a Quarter Mile Away [Video](https://www.youtube.com/watch?v=KrOReHwjCKI)  
- DEF CON 24 - Realtime Bluetooth Device Detection with Blue Hydra [Video](https://www.youtube.com/watch?v=p5AnZHY7g1M)  
- DEF CON 24 Internet of Things Village Damien Cauquil Btlejuice The Bluetooth Smart Mitm Framework [Video](https://www.youtube.com/watch?v=lcn07TclnS0)  
- Blackhat USA 2016 - Gattacking Bluetooth Smart Devices - Introducing a New BLE Proxy Tool [Video](https://www.youtube.com/watch?v=uKqdb4lF0XU)  
- Hack.lu 2016 - Damiel Cauquil - BtleJuice: the Bluetooth Smart Man In The Middle Framework [Video](https://www.youtube.com/watch?v=G08fh5Sa7TU)  
- EMF16 - Michael Ossmann - My Ubertooth Year [Video](https://www.youtube.com/watch?v=8lGCKO13zuo)  

### 2018

- DEF CON 26 - Damien Cauquil - You had better secure your BLE devices [Video](https://www.youtube.com/watch?v=VHJfd9h6G2s)  
- 35C3 - Dennis Mantz and Jiska Classen - Dissecting Broadcom Bluetooth [Video](https://www.youtube.com/watch?v=4_nI9ok7iQg)  
- MRMCD2018 - Dennis Mantz and Jiska Classen - A Deep Dive into Bluetooth Controller Firmware [Video](https://www.youtube.com/watch?v=iYPPOMQOev0)

### 2019

- DEF CON 27 - Damien Cauquil - Defeating Bluetooth Low Energy 5 PRNG for Fun and Jamming [Video](https://www.youtube.com/watch?v=wkIdpK7mAk4)  
- USENIX Security '19 - Pallavi Sivakumaran - A Study of the Feasibility of Co-located App Attacks against BLE [Video](https://www.youtube.com/watch?v=C1TNuxSCz9Y)  
- RSA 2019 - Mike Ryan - Bluetooth Reverse Engineering: Tools and Techniques [Video](https://www.youtube.com/watch?v=gCQ3iSy6R-U)  
- Hardwear.io USA 2019 - Mike Ryan - Bluetooth Hacking: Tools And Techniques [Video](https://www.youtube.com/watch?v=8kXbu2Htteg)  
- Hardwear.io Netherlands 2019 - Sultan Qasim Khan - Sniffle: A low-cost sniffer for Bluetooth 5 [Video](https://www.youtube.com/watch?v=nClZzdvGlKg)  
- MRMCD2019 - Dennis Mantz and Jiska Classen - Playing with Bluetooth [Video](https://www.youtube.com/watch?v=uwkR8bcni38)
- BruCON 0x0B - Damien Cauquil - Defeating Bluetooth Low Energy 5 PRNG for fun and jamming [Video](https://www.youtube.com/watch?v=rtaSCqngvqU)  
- Hack.LU 2019 - Damien Cauquil - Defeating Bluetooth Low Energy 5 PRNG For Fun And Jamming [Video](https://www.youtube.com/watch?v=4TaimqlQCew)  
- CyberCamp19 - Pablo González - Audit and hacking to Bluetooth Low-Energy (BLE) devices [Video](https://www.youtube.com/watch?v=v4YxIlNyiSI)

### 2020

- Hardwear.io Virtual Con 2020 - Daniele Antonioli - From Bluetooth Standard to Standard Compliant 0-days [Video](https://www.youtube.com/watch?v=ZVSbF11uxuk)  
- DEF CON 28 - Jiska Classen and Francesco Gringoli - Spectra — New Wireless Escalation Targets  [Video](https://www.youtube.com/watch?v=GZd66uVGKn8)
- DEF CON 28 - Maxine Filcher - The Basics Of Breaking BLE v3 [Video](https://www.youtube.com/watch?v=X2ARyfjzxhY)
- USENIX WOOT 2020 - Jianliang Wu - BLESA: Spoofing Attacks against Reconnections in Bluetooth Low Energy [Video](https://www.youtube.com/watch?v=wIWZaSZsRc8)
- USENIX WOOT 2020 - Dennis Heinze, Jiska Classen, Matthias Hollick - ToothPicker: Apple Picking in the iOS Bluetooth Stack [Video](https://www.youtube.com/watch?v=hwJX1F11peU)
- USENIX 2020 - Yue Zhang - Breaking Secure Pairing of Bluetooth Low Energy Using Downgrade Attacks [Video](https://www.youtube.com/watch?v=vcv6agrH4J8)
- Ekoparty 2020 - Cecilia Pastorino and Dan Borgogno - Bluetooth Low Energy Hacking 101 [Video](https://www.youtube.com/watch?v=2sirVrJpI30)
- rC3 2020 - Jiska Classen - Exposure Notification Security [Video](https://www.youtube.com/watch?v=w9yuTZzsP_w)

### 2021

- CCC #DiVOC2020 - Jiska Classen - Finding Eastereggs in Broadcom's Bluetooth Random Number Generator [Video](https://www.youtube.com/watch?v=cxlxc4Yc3tQ)
- CCC #DiVOC2020 - Jan Ruge - No PoC? No Fix! - A sad Story about Bluetooth Security [Video](https://www.youtube.com/watch?v=7tIQjPjjJQc)

------

## <a name="bluetooth_security_tools"></a>Bluetooth Security Tools

### Linux Utilities & Tools

- BlueZ (l2ping, gatttool, hciconfig, hcidump, hcitool, sdptool, bccmd, bluetoothctl, etc.) [Link](http://www.bluez.org/)

### Scanners & Sniffers

- BTLEmap [Github](https://github.com/seemoo-lab/BTLEmap)
- Sniffle [Github](https://github.com/nccgroup/sniffle)
- Bettercap [Github](https://github.com/bettercap/bettercap)
- sparrow-wifi [Github](https://github.com/ghostop14/sparrow-wifi)
- bluelog [Github](https://github.com/MS3FGX/Bluelog)
- btsniffer [Github](https://github.com/bsnet/btsniffer)
- Blue Hydra [Github](https://github.com/pwnieexpress/blue_hydra)
- btlesniffer [Github](https://github.com/scipag/btle-sniffer)
- btscanner [Link](https://manpages.ubuntu.com/manpages/bionic/man1/btscanner.1.html)
- BT Audit [Link](https://trifinite.org/trifinite_stuff_btaudit.html)
- redfang [Gitlab](https://gitlab.com/kalilinux/packages/redfang)
- bleah (deprecated, replaced by Bettercap) [Github](https://github.com/evilsocket/bleah)

### Exploit Tools

- Btlejack [Github](https://github.com/virtualabs/btlejack)
- crackle [Github](https://github.com/mikeryan/crackle)
- btcrack [Github](https://github.com/mikeryan/btcrack)
- BLE-Replay [Github](https://github.com/nccgroup/BLE-Replay)
- BLESuite-CLI [Github](https://github.com/nccgroup/BLESuite-CLI)
- BlueMaho [Gitlab](https://gitlab.com/kalilinux/packages/bluemaho)
- BlueDiving [Sourceforge](http://bluediving.sourceforge.net/)
- Blooover [Link](https://trifinite.org/trifinite_stuff_blooover.html)
- l2ping (BlueSmack DoS) [Link](https://trifinite.org/trifinite_stuff_bluesmack.html)
- hidattacl [Link](https://mulliner.org/bluetooth/hidattack.php)

### OBEX Attack Tools

- obexstress [Download](http://bluetooth-pentest.narod.ru/software/obexstress.py)
- bluesnarfer [Gitlab](https://gitlab.com/kalilinux/packages/bluesnarfer)
- nOBEX [Github](https://github.com/nccgroup/nOBEX)

### Fuzzing

- Toothpicker [Github](https://github.com/seemoo-lab/toothpicker)
- bss (unsupported) [Github](https://github.com/hllhll/BluetoothStackSmasher)
- Defensics (Commercial) [Link](https://www.synopsys.com/software-integrity/security-testing/fuzz-testing.html)

### Firmware Analysis

- InternalBlue [Github](https://github.com/seemoo-lab/internalblue)
- Frankenstein [Github](https://github.com/seemoo-lab/frankenstein)
- Nexmon [Github](https://github.com/seemoo-lab/nexmon/tree/bluetooth-wip)

### Man-in-the-middle & Packet Injection

- BtleJuice [Github](https://github.com/DigitalSecurity/btlejuice)
- Gattacker [Github](https://github.com/securing/gattacker)
- BTLE (for SDRs) [Github](https://github.com/JiaoXianjun/BTLE)
- (Unsupported) Btproxy [Github](https://github.com/conorpp/btproxy)

### Device Spoofing

- Spooftooph [Gitlab](https://gitlab.com/kalilinux/packages/spooftooph)
- Bluefog [Github](https://github.com/MS3FGX/Bluefog)

### Ping & Signal Strength Tools

- blue_sonar [Github](https://github.com/ZeroChaos-/blue_sonar)
- BlueRanger [Gitlab](https://gitlab.com/kalilinux/packages/blueranger)

### Denial of Service

- Blue Deauth [Github](https://github.com/its0x08/blue-deauth)

### Honeypot

- bluepot [Github](https://github.com/andrewmichaelsmith/bluepot/)

### Android Apps

- nRF Connect for Mobile [Google Play](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp)

### Hardware

- Nordic Semiconductor nRF-51 Development Kit [Link](https://www.nordicsemi.com/Software-and-Tools/Development-Kits/nRF51-DK)
- Sena UD-100 (~$39) [Link](http://www.senanetworks.com/ud100-g03.html)
- Ubertooth One (~$120) [Link](https://greatscottgadgets.com/ubertoothone/)
- Ellisys Bluetooth Tools [Link](https://www.ellisys.com/products/btcompare.php)
- Frontline Bluetooth Tools [Link](http://www.fte.com/products/default.aspx)

### Other

- Wireshark: Protocol analyzer and packet capture [Link](https://www.wireshark.org/)
- Frontline Wireless Protocol Suite (Windows only) [Link](http://www.fte.com/support/wps-download.aspx?demo=802.11&iid=1y)
- Uberducky (BLE-triggered rubber ducky) [Github](https://github.com/mikeryan/uberducky)
- CarWhisperer: Bluetooth sniffer for in-vehicle connections [Link](https://trifinite.org/trifinite_stuff_carwhisperer.html)
- BLEBoy: BLE testing platform [Github](https://github.com/nccgroup/BLEBoy)

------

## <a name="primary_references"></a>Primary Reference Materials

Bluetooth Core Specifications [Link](https://www.bluetooth.com/specifications/bluetooth-core-specification/)

NIST Special Publication (SP) 800-121 revision 2 [Link](https://www.nist.gov/publications/guide-bluetooth-security-1)

------

## <a name="useful_sites"></a>Useful Sites

- List of Bluetooth bugs [Link](http://bluetooth.lol/)
- Bluetooth arsenal tool list [Github](https://github.com/0x90/bluetooth-arsenal)
- trifinite Bluetooth info [Link](https://trifinite.org/trifinite_stuff.html)
- Mike Ryan's Bluetooth info [Link](https://lacklustre.net/bluetooth/)
- Colin Mulliner's Bluetooth info [Link](https://mulliner.org/bluetooth/)
- BlackArch Linux tool list [Link](https://blackarch.org/bluetooth.html)
- Bluetooth pen test framework [Link](http://bluetooth-pentest.narod.ru/)
