# SnipEX Aura Releases

Windows installers for **SnipEX Aura**, the fully animated SnipEX client.

**[Download the latest release](https://github.com/PeterDenali/SnipEX-Aura-Releases/releases/latest)**

| Package | Use |
| --- | --- |
| `SnipEX-Aura-<version>-win-x64-Setup.exe` | Guided installer (recommended). Per-user, no administrator rights. |
| `SnipEX-Aura-<version>-win-x64.msi` | MSI for managed deployment. |
| `*.sha256` | SHA-256 checksums for verifying downloads. |

- **Requirements:** Windows 10 1809 or later, x64. macOS is not available yet.
- **Works alongside SnipEX:** SnipEX Aura pauses its own snippet expansion while the standard SnipEX app is running, so abbreviations never expand twice.
- **Unsigned:** the packages are unsigned while review is pending, so SmartScreen may show **More info → Run anyway**.
- **Update manifest:** [`manifest.json`](manifest.json) and [`manifests/windows-x64.json`](manifests/windows-x64.json) describe the latest Windows release.

Standard SnipEX releases live in [SnipEX-Releases](https://github.com/PeterDenali/SnipEX-Releases). This repository contains release packages only, not source code.
