<details open>
<summary><h2>🇬🇧 English</h2></summary>

## ⚡ ExodSync — Excel & CSV to Microsoft Entra ID
**ExodSync** is a native **Windows 10 / 11 (64-bit)** desktop application designed to provision and synchronize Microsoft 365 / Entra ID user accounts safely from standard Excel or CSV exports. Every synchronization goes through an interactive **Dry-Run preview** with human validation before any change is sent to Microsoft Graph.

🌐 **Official Website:** [exodsync.com](https://exodsync.com/en/)  
📖 **Official Documentation:** [exodsync.com/en/docs.html](https://exodsync.com/en/docs.html)

[![Download ExodSync Windows](https://img.shields.io/badge/Download-ExodSync_Windows-blue?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NDggNTEyIiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTAgOTMuN2wxODMuNi0yNS4zdjE3Ny40SDBWOTMuN3ptMCAzMjQuNmwxODMuNiAyNS4zVjI2OC40SDB2MTQ5Ljl6bTIwMy44IDI4TDQ0OCA0ODBWMjY4LjRIMjAzLjh2MTc3Ljl6bTAtMzgwLjZ2MTgwLjFINDQ4VjMyTDIwMy44IDY1Ljd6Ii8+PC9zdmc+)](https://github.com/M365-Manager/ExodSync/releases/latest)

---

## 🌟 Key Features
- **100% Local & GDPR-Friendly:** Zero third-party cloud intermediary and zero telemetry. ExodSync communicates directly from your Windows workstation to Microsoft Graph API.
- **Smart Identity Matching:** Links your Excel or CSV rows to existing Microsoft Entra ID accounts using pseudonymized SHA-256 anchors, preventing duplicates and handling homonyms cleanly.
- **Human-in-the-Loop Preview (*Dry-Run*):** Synchronization is always manual and supervised. Inspect creations, attribute updates, conflicts, and reversible soft-deletions step by step—protected by a 15% mass-deletion safety lock—before confirming execution.
- **High-Speed `$batch` Engine:** Synchronize hundreds or thousands of user accounts and directory attributes in seconds with automatic Dead-Letter Queue (DLQ) retry for transient errors.
- **100% Microsoft Entra ID RBAC:** Interactive delegated sign-in (MFA compatible, zero local passwords) aligned with native Microsoft directory roles:
  - **Global Administrator:** Full access, including *Settings* and multi-organization profiles.
  - **User Administrator:** Synchronization (*Dashboard*, *Active Users*, *Manual Links*, *History*) without access to *Settings*.
  - **Password Administrator / Helpdesk Administrator:** Restricted to *Active Users* for password resets only.
- **Direct Excel & CSV Support:** Import standard `.xlsx`, `.xls`, or `.csv` exports without manual reformatting, with isolated synchronization sub-profiles (e.g., Students vs. Staff).
- **Responsive Optimistic UI:** Instant local interface feedback during interactive actions while keeping full alignment with your Microsoft Entra ID directory.
- **Verified Mandatory Updates:** Built-in currency check via `https://exodsync.com/version.json` (with GitHub Releases fallback) and mandatory cryptographic **SHA-256** verification of every installer.

---

## Quick Installation (Windows 10 / 11 64-bit)

You can download the latest official installer using the badge above or from the **[Releases](../../releases/latest)** page.

1. Download **`Install_ExodSync_Windows.exe`** from the [Releases page](https://github.com/M365-Manager/ExodSync/releases/latest).
2. Launch the setup wizard:
   - Double-click **`Install_ExodSync_Windows.exe`** to install ExodSync on Windows 10 or Windows 11 (64-bit).
   - *Note:* If Microsoft Defender SmartScreen displays a warning, click **"More info"**, then **"Run anyway"**.

## Microsoft Entra ID Configuration & First Steps

To connect ExodSync to your Microsoft 365 tenant using interactive delegated sign-in, follow our illustrated step-by-step setup guide:

**[Read the Official Documentation & Setup Guide](https://exodsync.com/en/docs.html)**

---

## ©️ Intellectual Property and License
This software is a proprietary work. The source code is closed and natively compiled.
Reverse engineering, decompiling, reselling, or modifying this software is prohibited except where expressly permitted by applicable law for interoperability.

Please refer to the [End User License Agreement (EULA)](https://exodsync.com/en/eula.html) for full legal terms.

</details>

<br>
<hr>
<br>

<details>
<summary><h2>🇫🇷 Français</h2></summary>

## ⚡ ExodSync — Excel & CSV vers Microsoft Entra ID
**ExodSync** est une application de bureau native pour **Windows 10 / 11 (64-bit)** conçue pour créer et synchroniser en toute sécurité vos comptes utilisateurs Microsoft 365 / Entra ID depuis vos exports Excel ou CSV. Chaque opération repose sur une **prévisualisation humaine interactive (*Dry-Run*)** avant tout envoi vers Microsoft Graph.

🌐 **Site Officiel :** [exodsync.com](https://exodsync.com/)  
📖 **Documentation Officielle :** [exodsync.com/docs.html](https://exodsync.com/docs.html)

[![Télécharger ExodSync Windows](https://img.shields.io/badge/T%C3%A9l%C3%A9charger-ExodSync_Windows-blue?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NDggNTEyIiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTAgOTMuN2wxODMuNi0yNS4zdjE3Ny40SDBWOTMuN3ptMCAzMjQuNmwxODMuNiAyNS4zVjI2OC40SDB2MTQ5Ljl6bTIwMy44IDI4TDQ0OCA0ODBWMjY4LjRIMjAzLjh2MTc3Ljl6bTAtMzgwLjZ2MTgwLjFINDQ4VjMyTDIwMy44IDY1Ljd6Ii8+PC9zdmc+)](https://github.com/M365-Manager/ExodSync/releases/latest)

---

## 🌟 Fonctionnalités Principales
- **100 % Local & Conforme RGPD :** Aucun serveur tiers intermédiaire et zéro télémétrie. ExodSync dialogue directement depuis votre poste Windows vers l'API Microsoft Graph.
- **Rapprochement Intelligent des Identités :** Relie vos lignes Excel ou CSV aux comptes Microsoft Entra ID existants par ancrage pseudonymisé SHA-256, évitant les doublons et gérant proprement les homonymes.
- **Prévisualisation Humaine (*Dry-Run*) :** La synchronisation est toujours manuelle et supervisée. Vérifiez étape par étape les créations, mises à jour d'attributs, conflits et suppressions réversibles vers la corbeille Entra ID — protégées par un verrou de sécurité à 15 % — avant validation.
- **Moteur `$batch` Haute Performance :** Synchronisez des centaines ou milliers de comptes et d'attributs en quelques secondes, avec file de relance (DLQ) intégrée en cas d'erreur transitoire.
- **RBAC 100 % Microsoft Entra ID :** Connexion interactive déléguée (compatible MFA, zéro mot de passe applicatif local) alignée sur les rôles natifs Microsoft :
  - **Administrateur général :** Accès complet incluant les *Paramètres* et la gestion multi-établissements.
  - **Administrateur d'utilisateurs :** Synchronisation (*Tableau de Bord*, *Utilisateurs actifs*, *Liaisons Manuelles*, *Historique*) sans accès aux *Paramètres*.
  - **Administrateur de mots de passe / Support technique :** Accès restreint à *Utilisateurs actifs* uniquement pour réinitialiser les mots de passe.
- **Fichiers Excel & CSV Standards :** Lisez directement vos exports `.xlsx`, `.xls` ou `.csv` sans retraitement préalable, avec sous-profils isolés (ex. Élèves vs Personnel).
- **Interface Optimiste Réactive :** Retour visuel immédiat lors de vos actions interactives tout en restant fidèlement synchronisé avec l'annuaire Microsoft Entra ID.
- **Mises à Jour Obligatoires Vérifiées :** Contrôle de version via `https://exodsync.com/version.json` (avec repli GitHub Releases) et vérification cryptographique **SHA-256** obligatoire de chaque installeur.

---

## Installation Rapide (Windows 10 / 11 64-bit)

Vous pouvez télécharger la dernière version officielle via le bouton en haut de cette page ou depuis la section **[Releases](../../releases/latest)**.

1. Téléchargez **`Install_ExodSync_Windows.exe`** depuis la [page des Releases](https://github.com/M365-Manager/ExodSync/releases/latest).
2. Lancez l'assistant d'installation :
   - Double-cliquez sur **`Install_ExodSync_Windows.exe`** pour installer ExodSync sur Windows 10 ou Windows 11 (64-bit).
   - *Note :* Si l'écran Microsoft Defender SmartScreen apparaît, cliquez sur **« Informations complémentaires »**, puis sur **« Exécuter quand même »**.

## Configuration Microsoft Entra ID & Premiers Pas

Pour relier ExodSync à votre tenant Microsoft 365 en authentification interactive déléguée, suivez notre guide complet illustré :

**[Consulter la Documentation Officielle et le Guide de Démarrage](https://exodsync.com/docs.html)**

---

## ©️ Propriété Intellectuelle et Licence
Ce logiciel est une œuvre propriétaire. Le code source est fermé et compilé nativement.
Il est interdit de rétro-concevoir (*reverse-engineer*), décompiler, revendre ou modifier ce logiciel, sous réserve des exceptions impératives prévues par la loi applicable à des fins d'interopérabilité.

Veuillez consulter notre [Contrat de Licence Utilisateur Final (CLUF)](https://exodsync.com/eula.html) pour l'intégralité des conditions juridiques.

</details>
