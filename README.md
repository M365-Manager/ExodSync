🌍 **Read in:** [English](README.md) | [Français](README.fr.md)

## ⚡ ExodSync - Excel to Entra ID Provisioning
**ExodSync** is a standalone desktop application designed to automate and secure the management of Microsoft 365 (Entra ID) accounts. It intelligently bridges the gap between your local database (Excel/CSV) and your Microsoft Azure tenant.

🌐 **Official Website:** [exodsync.com](https://exodsync.com/en/)  
📖 **Official Documentation:** [exodsync.com/en/docs.html](https://exodsync.com/en/docs.html)

[![Download ExodSync Windows](https://img.shields.io/badge/Download-ExodSync_Windows-blue?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NDggNTEyIiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTAgOTMuN2wxODMuNi0yNS4zdjE3Ny40SDBWOTMuN3ptMCAzMjQuNmwxODMuNiAyNS4zVjI2OC40SDB2MTQ5Ljl6bTIwMy44IDI4TDQ0OCA0ODBWMjY4LjRIMjAzLjh2MTc3Ljl6bTAtMzgwLjZ2MTgwLjFINDQ4VjMyTDIwMy44IDY1Ljd6Ii8+PC9zdmc+)](https://github.com/M365-Manager/ExodSync/releases/latest/download/ExodSync-Windows.zip)
[![Download ExodSync macOS](https://img.shields.io/badge/Download-ExodSync_macOS-black?style=for-the-badge&logo=apple&logoColor=white&cache=bust1)](https://github.com/M365-Manager/ExodSync/releases/latest/download/ExodSync-macOS.zip)

---

## 🌟 Key Features
- **Privacy by Design (GDPR Compliant):** Zero intermediate servers. ExodSync is a 100% local thick client. Institutional data flows directly from your machine to the Microsoft Graph API.
- **Dual-Level Reconciliation (Matching & Fallback):** The algorithm first matches accounts by their generated email address, then anchors them using a unique cryptographic hash.
- **Zero-Touch Autonomy:** Fully automated, silent background synchronization .
- **Instantaneous Engine:** Processes and matches thousands of accounts instantly without UI freezes.
- **B2B Role-Based Access Control:** Define Administrators, Data Managers, and Password Administrators with tailored UIs.
- **Native Excel & CSV Support:** Read data directly without conversion.
- **Pre-flight Data Validation:** Instant detection and purging of invalid rows before any synchronization.
- **Clean Architecture:** Natively compiled for maximum performance, ultimate security, and zero false-positive Antivirus alerts. Local configurations are encrypted and safely hidden on your system.

---

## ⚙️ Azure Configuration & Installation
For a complete step-by-step guide on how to register ExodSync in your Microsoft Azure Portal, and how to use the software, please refer to our official website documentation:

👉 **[ExodSync Documentation Guide](https://exodsync.com/en/docs.html)**

### Quick Installation:
1. Go to the **[Releases](../../releases/latest)** section.
2. Download **`ExodSync-Windows.zip`** (or Mac).
3. Unzip the file into a directory of your choice.
4. Run `ExodSync.exe` (Windows) or the `.app` on Mac.
5. *Note for Windows:* The application runs as a standalone folder. All configurations will be safely stored in a hidden system vault to keep your installation clean.

---

## ©️ Intellectual Property and License
This software is a proprietary work. The source code is closed and natively compiled.
It is strictly forbidden to reverse-engineer, decompile, resell, or modify this software.

Please refer to the [End User License Agreement (EULA)](https://exodsync.com/en/eula.html) for exact terms.
