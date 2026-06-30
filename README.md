Note: This README is available in both English and French. / Ce README est disponible en anglais et en français.

# 🇬🇧 English Version

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

<br>
<hr>
<br>

# 🇫🇷 Version Française

## ⚡ ExodSync - Synchronisation Excel vers Entra ID
**ExodSync** est une application bureau autonome conçue pour automatiser et sécuriser la gestion des comptes Microsoft 365 (Entra ID). Elle fait le pont intelligemment entre votre base locale (Excel/CSV) et votre locataire Azure.

🌐 **Site Officiel :** [exodsync.com](https://exodsync.com/)  
📖 **Documentation Officielle :** [exodsync.com/docs.html](https://exodsync.com/docs.html)

[![Télécharger ExodSync Windows](https://img.shields.io/badge/T%C3%A9l%C3%A9charger-ExodSync_Windows-blue?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NDggNTEyIiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTAgOTMuN2wxODMuNi0yNS4zdjE3Ny40SDBWOTMuN3ptMCAzMjQuNmwxODMuNiAyNS4zVjI2OC40SDB2MTQ5Ljl6bTIwMy44IDI4TDQ0OCA0ODBWMjY4LjRIMjAzLjh2MTc3Ljl6bTAtMzgwLjZ2MTgwLjFINDQ4VjMyTDIwMy44IDY1Ljd6Ii8+PC9zdmc+)](https://github.com/M365-Manager/ExodSync/releases/latest/download/ExodSync-Windows.zip)
[![Télécharger ExodSync macOS](https://img.shields.io/badge/T%C3%A9l%C3%A9charger-ExodSync_macOS-black?style=for-the-badge&logo=apple&logoColor=white&cache=bust1)](https://github.com/M365-Manager/ExodSync/releases/latest/download/ExodSync-macOS.zip)

---

## 🌟 Fonctionnalités Principales
- **Privacy by Design (RGPD) :** Zéro serveur intermédiaire. ExodSync est un client lourd 100% local. Les données institutionnelles passent directement de votre machine à l'API Graph Microsoft.
- **Réconciliation à Deux Niveaux (Dual-Matching & Fallback) :** L'algorithme associe les comptes d'abord par l'adresse e-mail générée, puis les sécurise via une empreinte cryptographique (hash).
- **Autonomie "Zero-Touch" :** Synchronisation silencieuse et automatisée en arrière-plan, sans pop-up Microsoft.
- **Moteur Instantané :** L'algorithme traite et associe des milliers de comptes de manière instantanée.
- **Gestion des Rôles (RBAC B2B) :** Définissez des Administrateurs, Gestionnaires de données et Administrateurs de mots de passe.
- **Support Natif Excel & CSV :** Lecture directe sans conversion.
- **Contrôle Qualité (Pre-flight) :** Détection et purge instantanées des lignes invalides avant toute synchronisation.
- **Architecture Propre :** Compilé nativement pour des performances maximales, une sécurité absolue et zéro fausse alerte Antivirus. Les configurations locales sont chiffrées et cachées en toute sécurité sur votre système.

---

## ⚙️ Configuration Azure & Installation
Pour un guide complet étape par étape sur la configuration de l'application dans votre portail Microsoft Azure, veuillez consulter la documentation sur notre site officiel :

👉 **[Guide et Documentation ExodSync](https://exodsync.com/docs.html)**

### Installation rapide :
1. Rendez-vous dans la section **[Releases](../../releases/latest)**.
2. Téléchargez le fichier **`ExodSync-Windows.zip`** (ou Mac).
3. Dézippez le fichier dans le dossier de votre choix.
4. Lancez `ExodSync.exe` (Windows) ou le `.app` sur Mac.
5. *Note Windows :* L'application fonctionne sous forme de dossier autonome. Vos paramètres seront sauvegardés de manière invisible par le système pour garder votre dossier propre.

---

## ©️ Propriété Intellectuelle et Licence
Ce logiciel est une œuvre propriétaire. Le code source est fermé et compilé nativement.
Il est strictement interdit de rétro-concevoir (reverse-engineer), décompiler, revendre ou modifier ce logiciel. 

Veuillez consulter notre [Contrat de Licence Utilisateur Final (CLUF)](https://exodsync.com/eula.html) pour les termes exacts.