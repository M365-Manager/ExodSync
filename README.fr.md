🌍 **Lire en :** [Français](README.fr.md) | [English](README.md)

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
