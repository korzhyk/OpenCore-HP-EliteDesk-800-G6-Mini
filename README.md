# Hackintosh on [HP G6 800 Mini](https://support.hp.com/document/c06707841) via [OpenCore](https://github.com/acidanthera/OpenCorePkg)

![About this mac](https://github.com/korzhyk/OpenCore-HP-EliteDesk-800-G6-Mini/assets/1100134/9c0fb81f-02d0-41c6-9a9b-796abf0aadc2)

_macOS Supported:_ **13+**

This is light configuration to run macOS smoothly. With Chime sound at boot. 🔉

## 📠 Hardware configuration

| **Component**    | **Model**                                     |
| ---------------- | --------------------------------------------- |
| CPU              | Intel Core i5 10500T & UHD630                 |
| Motherboard      | Intel Q470 vPro (DAF93MB36B0 Rev.B)           |
| RAM              | 2×16GB SAMSUNG 2666MHz (M471A2K43DB1)         |
| Audio Chipset    | ALC3205-CG                                    |
| Ethernet         | Intel I219-LM                                 |
| WiFi & Bluetooth | Intel(R) Wi-Fi 6 AX210 160MHz + Bluetooth 5.0 |
| SSD              | SK hynix PC300 NVME 512GB                     |

## ⚙️ UEFI Settings

- _Main_ → Apply Factory Defaults and Exit → [**Yes**]
- _Advanced_ → Boot Options → Fast Boot [**unCheck**]

<details>
<summary>🤔

## Optional UEFI settings

</summary>

- _Advanced_ → Boot Options → Audio Alerts During Boot [**unCheck**] (loud audio)
- _Advanced_ → HP Sure Recover → HP Sure Recover [**unCheck**]
- _Advanced_ → System Options → USB Type-C Connector System Software Interface (UCSI) [**unCheck**]
- _Advanced_ → System Options → HP Application Driver [**unCheck**]
- _Advanced_ → Built-in Device Options → Wake on WLAN [**Check**] (no sure if this will work)
- _Advanced_ → Remote Management Options → Intel Active Management Technology (AMT) [**unCheck**]
</details>

<details>
<summary>🕸️

## USB ports map

</summary>

![usb-port-map](https://github.com/korzhyk/OpenCore-HP-EliteDesk-800-G6-Mini/assets/1100134/5d0d8f79-c258-473f-a6dc-05a3d9a524b3)
![hackintool-usb](https://github.com/korzhyk/OpenCore-HP-EliteDesk-800-G6-Mini/assets/1100134/847fdbfa-ff26-40a3-a83e-d948fa6bed27)

</details>
