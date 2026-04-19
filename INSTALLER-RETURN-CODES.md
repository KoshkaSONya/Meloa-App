# Meloa Installer Return Codes

This document describes the exit/return codes used by the Meloa installer (`Meloa-Setup-0.2.6-x64.exe`).

## Standard Return Codes

| Return Code | Meaning                              | Description |
|-------------|--------------------------------------|-----------|
| **0**       | Success                              | Installation completed successfully |
| **1**       | General failure                      | Installation failed (unspecified error) |
| **1602**    | User cancelled                       | The user cancelled the installation |
| **1618**    | Another installation in progress     | Another installer is already running |
| **1638**    | Application already installed        | A version of Meloa is already installed |
| **112 / 1632** | Disk space full                   | Not enough free disk space |
| **3010 / 1641** | Reboot required                   | A restart is required to complete installation |
| **1603**    | Fatal error                          | Critical error during installation |

## Notes
- The most important code for Microsoft Store is **0** = successful installation.
- Any non-zero code means the installation did **not** complete successfully.
- If you encounter an error, please report the return code to us.

Last updated: April 2026
