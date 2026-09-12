<div align="center">

# MIUI 14 Port for Xiaomi Mi 8 (dipper) & POCO F1 (beryllium)

![Android](https://img.shields.io/badge/Android-13-3DDC84?style=for-the-badge&logo=android)
![MIUI](https://img.shields.io/badge/MIUI-14-FF6700?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)
![Team](https://img.shields.io/badge/Ported_By-Android%20Ports%20Team-blue?style=for-the-badge)

*Stable MIUI 14 experience based on Android 13 ported for dipper and beryllium.*

</div>

> ⚠️ **IMPORTANT:** Clean flash is **strictly mandatory**. Do not report boot issues if you did not follow the exact partition wipe procedure below.

---

## 📱 Release Details
| Attribute | Details |
| :--- | :--- |
| **Supported Devices** | Xiaomi Mi 8 (`dipper`) / POCO F1 (`beryllium`) |
| **Android Version** | Android 13 |
| **ROM Base** | MIUI 14 (Stable Release) |
| **Release Date** | 20/05/2023 |
| **Maintainer** | Android Ports Team |

---


## 💡 Important Notes & Tips
* **Power Menu Fix:** Disable the Google Assistant power button shortcut in MIUI settings to restore the standard power/reboot menu.
* **Pet Widgets (Cat & Dog):** Add widgets exclusively via **App Vault** and allow required background asset downloads to finish.
* **Recovery:** Use the recommended custom recovery for your specific device.

---

## 🐞 Bugs & Workarounds

| Issue | Affected Device | Status / Workaround |
| :--- | :--- | :--- |
| **Face Unlock** | Both (`dipper` / `beryllium`) | Uses RGB front camera; IR hardware face unlock is disabled |
| **NFC** | `dipper` only | Non-functional |
| **Mi Cloud** | Both (`dipper` / `beryllium`) | Non-functional |
| **Super Icons** | Both (`dipper` / `beryllium`) | Visual glitches / unstable behavior |
| **Stock Video Recording** | `beryllium` only | Fails on stock camera (**Workaround:** Use GCam) |
| **MicroSD Card** | `beryllium` only | Storage card not detected |

---

## ⬇️ Downloads

| Device | Codename | Download Link |
| :--- | :--- | :--- |
| **Xiaomi Mi 8** | `dipper` | **[Download Dipper ROM](https://sourceforge.net/projects/miui-port-dipper-f1/files/miui%2014%20android%2013%20Xiaomi%20eu%20dipper/Dipper_Miui14_A13_V1_Stable.zip/download)** |
| **POCO F1** | `beryllium` | **[Download POCO ROM](https://sourceforge.net/projects/miui-port-dipper-f1/files/miui%2014%20android%2013%20Xiaomi%20eu%20Beryllium/Beryllium_Miui14_A13_V1_Stable.zip/download)** |

---

## 🛠️ Flashing Instructions

> 🛑 **Required Wipe:** Skipping partition wipes will cause bootloops or persistent system bugs.

1. Boot into recommended custom recovery (TWRP / OrangeFox).
2. Go to **Wipe** > **Advanced Wipe**.
3. Select and wipe the following partitions:
   * `System`
   * `Vendor`
   * `System_EXT` / `Cust`
   * `Dalvik / ART Cache`
   * `Cache`
   * `Data`
4. Flash the ROM `.zip` for your specific device model.
5. Format Data (Type `yes`) if required by your encryption status.
6. Reboot to System.

---

## 👏 Credits & Acknowledgements
* **Porting & Device Fixes:** Android Ports Team
