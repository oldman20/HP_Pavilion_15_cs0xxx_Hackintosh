# HP Pavilion 15 cs0xxx Hackintosh with OpenCore

## Overview
- **Download the latest zipped EFI [here](https://github.com/vietthai2512/HP_Pavilion_15_cs0101TX_Hackintosh/releases).**
- macOS version: **Ventura** **13**
- OpenCore version: **0.9.4**

 <summary><strong>macOS Monterey</strong></summary>

![screenshot](images/Monterey-2021-11-02.png)

<summary><strong>OpenCore Boot Menu</strong></summary>

![screenshot](images/OpenCore068-background.png)

<details>
 <summary><strong>macOS Big Sur</strong></summary>

![screenshot](images/Big-Sur-2020-11-26.png)

</details>

<details>
 <summary><strong>macOS Catalina</strong></summary>

![screenshot](images/Catalina-2020-11-15.png)

 </details>

## Hardware Specifications

| Category | Detail |
|:----:|:----:|
| Product name | HP Pavilion - 15-cs0xxx |
| Microprocessor | Intel® Core™ i5-8250U (1.6 GHz base frequency, up to 1.8 GHz with Intel® Turbo Boost Technology, 6 MB cache, 4 cores)|
| IGPU | Intel® UHD Graphics 620 |
| Memory | 8GB DDR4-2400 SDRAM (2 x 4 GB) |
| Drives | Toshiba 1 TB 5400 rpm SATA & Samsung 970 Evo 250GB NVMe M.2 |
| Display | 15.6" diagonal FHD SVA anti-glare WLED-backlit (1920 x 1080) |
| Keyboard | Full-size island-style keyboard with numeric keypad, PS/2 |
| Pointing device | HP Imagepad with multi-touch gesture support, PS/2 |
| Wireless connectivity | Intel® 802.11a/b/g/n/ac (1x1) Wi-Fi® and Bluetooth® 4.2 Combo (Intel® Dual Band Wireless-AC 3168) |
| Network interface | Integrated 10/100/1000 GbE LAN (Realtek RTL8111) |
| Expansion slots | 1 multi-format SD media card reader |
| External ports | 2 USB 3.1 Gen 1 (Data transfer only); 1 HDMI 1.4; 1 headphone/microphone combo; 1 USB 3.1 Type-C™ Gen 1 (Data Transfer Only); 1 RJ-45 |

## Current issues

- ~~Sleep: DarkWake from Normal Sleep [CDN] : due to XHC HDAS/ Using AC (Charge:0%)~~ Fixed.
- ~~iMessages and FaceTime~~ Continuity services aren't working, waiting for a new version of AirportItlwm.
- ~~HDMI (not tested yet)~~ <details><summary>Fixed</summary>![screenshot](images/HDMI-working.jpg)</details>

## Note

- Generate your own MLB, SystemSerialNumber, SystemUUID (<https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo>)

## https://github.com/KrolSeb/HP-Pavilion-Gaming-15-dk00xxxx-Hackintosh-OpenCore
