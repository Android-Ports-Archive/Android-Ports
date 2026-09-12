<div align="center">

# Flyme OS 10 Beta Port for Xiaomi Mi 8 & POCO F1

![Android](https://img.shields.io/badge/Android-13-3DDC84?style=for-the-badge&logo=android)
![FlymeOS](https://img.shields.io/badge/Flyme_OS-v10_Beta-00A7EA?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Beta_Port-warning?style=for-the-badge)
![Team](https://img.shields.io/badge/Ported_By-Android_Ports-blue?style=for-the-badge)

*Clean, fast, and heavily customized Flyme OS experience ported for dipper and beryllium.*

</div>

---

## 📱 Release Details
| Attribute | Details |
| :--- | :--- |
| **Supported Devices** | Xiaomi Mi 8 (`dipper`) / POCO F1 (`beryllium`) |
| **Android Version** | Android 13 |
| **ROM Base** | Flyme OS v10 (Beta) |
| **SELinux Status** | Permissive |
| **Encryption** | DFE (Disable Force Encryption) is already included |

---


## 💡 Important Notes & Post-Install Setup

* **Google Services & Play Store:** GMS is included but needs to be manually toggled on. 
  * Go to **Settings** -> **Accessibility** -> **Enable Google services**.
* **Pre-installed Apps:** **GCam** is set as the default camera app, and **YouTube Premium** is pre-included in this build.
* **Keyboard Switcher:** Two keyboards are included (Flyme OEM Keyboard & Gboard). 
  * You can switch between them in **Settings** -> **Time and language**.
* **Multi-Language Support:** Flyme OS ports often default to limited languages. For full multi-language support, flash the included Magisk module (linked in the downloads section below).

---

## 🐞 Bugs & Known Issues
* ❌ **Vibration/Haptics:** Currently non-functional or unstable across the system. 

---

## ⬇️ Downloads

| Device / Add-on | Codename | Download Link |
| :--- | :--- | :--- |
| **Xiaomi Mi 8** | `dipper` | **[Download Dipper ROM](https://sourceforge.net/projects/miui-port-dipper-f1/files/FlymeOS%20Dipper/)** |
| **POCO F1** | `beryllium` | **[Download POCO ROM](https://sourceforge.net/projects/miui-port-dipper-f1/files/FlymeOS%20Poco%20F1/)** |
| **Multi-Language Patch** | Magisk Module | **[Download Magisk Module](https://github.com/y3wad/Android-Ports/releases/tag/Module)** |

---

## 🛠️ Flashing Instructions

> 🛑 **IMPORTANT:** **Clean flash is strictly mandatory.** Do not attempt to dirty flash over a previous ROM. Ensure your device partitions are adequately sized (Repartition ROM).

1. Boot into your custom recovery (TWRP/OrangeFox).
2. **Repartition your ROM** (Ensure system partitions are properly sized for Android 13 ports).
3. Perform a **Clean Wipe** (Dalvik, Cache, System, Vendor, Data).
4. Flash the ROM `.zip` file.
   * *(Note: DFE is already included in the zip, so you do not need to flash a separate decrypt zip).*
5. Format Data (Type `yes`).
6. Reboot to System. 
7. *(Optional)* After the first boot, reboot to recovery and flash the Multi-language Magisk module if needed.

---

## 👏 Credits & Acknowledgements
* **Porting & Device Fixes:** `𝙰𝚗𝚍𝚛𝚘𝚒𝚍 𝙿𝚘𝚛𝚝𝚜` Team
