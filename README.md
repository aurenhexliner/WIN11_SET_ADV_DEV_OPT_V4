WINDOWS 11 - USB & NETWORK ADAPTER OPTIMIZATION

PowerShell script prepared for easy and quick optimization
of advanced devices configuration settings:

- Intel(R) Wi-Fi 6E AX210 160MHz

     PCI\VEN_8086&DEV_2725&SUBSYS_00248086&REV_1A\4&1E1F98A2&0&00E8

- Realtek Gaming 2.5GbE Family Controller

    PCI\VEN_10EC&DEV_8125&SUBSYS_E0001458&REV_05\01000000684CE00000

Additionally disables the USB power saving feature 
(USB Selective Suspend)

----------

HOW TO RUN:

1. Run script from Windows Terminal or PowerShell as administrator. Check rights to execute script first:
   Go to:
      Windows Settings -> System -> Advanced -> Terminal -> Powershell (check option to run scripts without signing).
   Open Windows Terminal as administrator and set execution policy to "Unrestricted" typing:
      Set-ExecutionPolicy Unrestricted
   Run script:
      ./WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b.ps1
      
2. Just try EXEcutable/GUI version (WinUI 3) - RAR archive:
   https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/46f8788fbe791a6e954b5683a9ebe94a2aa03a24/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b_WINUI3.rar

----------

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

----------

DOWNLOAD:

1. PowerShell .ps1 script
   https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/main/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b.ps1
   
3. Executable, GUI version (WinUI 3) - RAR archive
   https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/46f8788fbe791a6e954b5683a9ebe94a2aa03a24/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b_WINUI3.rar
