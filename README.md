# Windows 11 - USB & Network Adapter Optimization

PowerShell script designed for quick and easy optimization of advanced device configuration settings, including:

- Intel(R) Wi-Fi 6E AX210 160MHz  
  `PCI\VEN_8086&DEV_2725&SUBSYS_00248086&REV_1A\4&1E1F98A2&0&00E8`

- Realtek Gaming 2.5GbE Family Controller  
  `PCI\VEN_10EC&DEV_8125&SUBSYS_E0001458&REV_05\01000000684CE00000`

This script also disables USB power saving (USB Selective Suspend).

---

## How to run

1. Open Windows Terminal or PowerShell as Administrator.
2. Allow script execution:
   ```powershell
   Set-ExecutionPolicy Unrestricted
   .\WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b.ps1


2. Alternative:
   Try the executable / GUI version (WinUI 3) from the link below.



What this script changes


### USB


- Disable USB Selective Suspend


### All network adapters


- Disable Windows network adapter power management


### Intel Wi‑Fi 6E AX210 160MHz


- Disable device power management

- Set MIMO Power Save Mode to `No SMPS`

- Set Transmit Power to `Highest`

- Set Roaming Aggressiveness to `Lowest`

- Enable Throughput Booster

- Disable U-APSD support


### Realtek Gaming 2.5GbE / RTL8125


- Disable EEE / Green Ethernet / Gigabit Lite

- Disable Interrupt Moderation

- Disable Power Saving Mode

- Set Receive / Transmit buffers to `4096`

- Disable or optimize Wake-on-LAN settings

- Set Speed & Duplex to `2.5 Gbps Full Duplex`

- Enable Priority and VLAN priority handling



## Downloads


1. PowerShell script

[https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/main/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b.ps1](https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/main/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b.ps1)

2. Executable / GUI version (WinUI 3, RAR archive)

[https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/46f8788fbe791a6e954b5683a9ebe94a2aa03a24/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b_WINUI3.rar](https://github.com/aurenhexliner/WIN11_SET_ADV_DEV_OPT_V4/blob/46f8788fbe791a6e954b5683a9ebe94a2aa03a24/WIN11_SET_ADV_DEV_OPT_NET_USB_PWR_V4b_WINUI3.rar)
