WINDOWS 11 - USB & NETWORK ADAPTER OPTIMIZATION

PowerShell script prepared for easy and quick optimization
of advanced devices configuration settings:

- Intel(R) Wi-Fi 6E AX210 160MHz 
  (PCI\VEN_8086&DEV_2725&SUBSYS_00248086&REV_1A\4&1E1F98A2&0&00E8)

- Realtek Gaming 2.5GbE Family Controller
  PCI\VEN_10EC&DEV_8125&SUBSYS_E0001458&REV_05\01000000684CE00000

Additionally disables the USB power saving feature 
(USB Selective Suspend)


HOW TO RUN:

Run script from Windows Terminal or PowerShell as administrator. Check rights to execute script first: 
Go to (Windows Settings -> System -> Advanced -> Terminal -> Powershell) and check option to run scripts without signing.


About all features:

USB:
  - USB Selective Suspend -> Disabled

ALL NETWORK ADAPTERS:
  - Windows network adapter power management -> Disabled

INTEL:
  - Intel Wi-Fi 6E AX210 160MHz
  - Device power management -> Disabled
  - MIMO Power Save Mode -> No SMPS
  - Transmit Power -> Highest
  - Roaming Aggressiveness -> Lowest
  - Throughput Booster -> Enabled
  - U-APSD support -> Disabled

REALTEK:
  - Realtek Gaming 2.5GbE / RTL8125
  - EEE / Green Ethernet / Gigabit Lite -> Disabled
  - Interrupt Moderation -> Disabled
  - Power Saving Mode -> Disabled
  - Receive / Transmit Buffers -> 4096
  - Wake-on-LAN related options -> Disabled / optimized
  - Speed & Duplex -> 2.5 Gbps Full Duplex
  - Priority & VLAN -> Priority Enabled
