# 🎓 [Smart Student Portal | Secure Notes Vault]()

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

Welcome to the **Secure Notes Vault**, a gamified file-sharing web application designed to reward student participation. By linking directly to live attendance databases, this portal treats lecture materials as an earned reward rather than a given right.

---

## ✨ System Capabilities

This portal connects securely to a central student database and an automated Google Drive folder to deliver files only to students who meet strict criteria.

* **🎮 Gamified Unlocking System:** When a student attempts to download lecture notes, the portal instantly audits their live attendance history. The Google Drive download links are **strictly locked** behind a 90% attendance requirement.
* **🚷 Blind-Firewall Security:** If a student's attendance is 90% or lower, they receive an "Access Denied" screen. The backend completely refuses to send the file URLs to their browser, meaning the secure files cannot be accessed even if the student tries to inspect the webpage's source code.
* **📂 Automated File Syncing:** Connects directly to a specific Google Drive folder. Whenever an administrator drops a new PDF or PPT into the Drive folder, it instantly and automatically appears on the eligible students' dashboard—no website updates required.

## 🛠️ Core Architecture
* **📱 Native App Experience:** Features a clean, glassmorphism-inspired UI with modern typography, smooth loading animations, and conditional UI rendering based on database state.
* **💬 Integrated Peer Support:** Features dynamic "Click-to-Chat" WhatsApp integration. One tap opens a pre-written WhatsApp message directed straight to the Class Representative (CR) for help with downloading issues.
* **☁️ 100% Free & Serverless:** Built entirely on GitHub Pages for the frontend and Google Apps Script + Google Drive for the backend, meaning it runs 24/7 with zero hosting costs.

---

## ©️ Copyright & Management

**Developed by:** Souravh Choursiya  
**Managed by:** Souravh Choursiya  

&copy; 2026 Souravh Choursiya. All rights reserved.