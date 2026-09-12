<div align="center">

# HyperOS Mi Pad Edition (Beta 2) for POCO

![HyperOS](https://img.shields.io/badge/HyperOS-Mi_Pad_Edition-333333?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Beta_2-warning?style=for-the-badge)
![Team](https://img.shields.io/badge/Ported_By-Android_Ports-blue?style=for-the-badge)

*A unique tablet-optimized HyperOS experience adapted for POCO.*

</div>

---

## 📱 Release Details
| Attribute | Details |
| :--- | :--- |
| **Supported Device** | POCO |
| **ROM Base** | HyperOS (Mi Pad Edition) |
| **Build Status** | Beta 2 |
| **Recommended Recovery** | OrangeFox 12.1 |

---

## 💡 Important Notes & Post-Install Setup

* **Google Play Store:** Play Store and Google Mobile Services (GMS) are disabled by default. 
  * **To enable:** Go to **Settings** > **Account & Sync** > **Basic Google Services** > toggle **Enable**.
* **Keyboard:** The native Xiaomi Keyboard is included and enabled by default.
* **Custom Kernels:** 🛑 **Do NOT change the kernel.** Flashing a custom kernel will break hardware features like the fingerprint scanner. Stick to the included stock kernel.
* **DFE:** Flashing Disable Force Encryption (DFE) is completely **optional** for this build.

---

## 🐞 Bugs & Known Issues

* ❌ **Face Unlock:** Currently non-functional.

---

## ⬇️ Downloads

| File Type | Download Link |
| :--- | :--- |
| **HyperOS Beta 2 ROM** | **[Download ROM Here](https://www.mediafire.com/file/7gm5r9cg64id11i/HyperOS_1.0.3.0_MIPAD_POCO_F1.zip/file)** |

---

## 🛠️ Flashing Instructions

> ⚠️ **MIGRATING FROM NOTHING OS?**
> If you are currently on the Nothing OS port, you **must** flash back to a Stock MIUI ROM before attempting to install this HyperOS build. Proceeding without reverting to stock will cause installation failures.

**Standard Clean Flash Process:**
1. Boot into **OrangeFox 12.1** (Highly Recommended).
2. Wipe relevant partitions (Dalvik, Cache, System, Vendor, Data).
3. Flash the **latest device Firmware**.
4. Flash the ROM `.zip` file.
5. Format Data (Type `yes`).
6. Reboot to System.

> 🛑 **CRITICAL STEP:** You must perform a **Hard Reboot** (hold the physical power button down until the device restarts) once immediately after the first successful boot to system.

---

## 👏 Credits & Acknowledgements
* **Ported by:** [@s_AngelGR](https://t.me/s_AngelGR)
* **Adapted for POCO by:** [@y3wad](https://t.me/y3wad)
* **Base OS Credits:** Poco OS Team
