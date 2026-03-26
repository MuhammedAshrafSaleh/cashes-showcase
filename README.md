# 🏗️ Cashes — Decoration Company Management App

<p align="center">
  <img src="screenshots/Splash Screen.jpeg" alt="ZMZM Decoration" width="200"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Enabled-orange?logo=firebase&logoColor=white" />
  <img src="https://img.shields.io/badge/State%20Management-BLoC-purple" />
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web-green" />
  <img src="https://img.shields.io/badge/Language-Arabic-yellow" />
</p>

---

## 📖 About

**Cashes** is a full-featured mobile management application built for decoration and finishing companies. It enables team members to manage projects, track expenses, generate invoices, and stay updated with real-time notifications — all from one place.

The app is tailored for **ZMZM Decoration** and supports a fully Arabic interface with RTL layout.

---

## ✨ Features

- 🔐 **Secure Authentication** — Login, Register, and Forgot Password via Firebase Auth
- 🏠 **Project Dashboard** — View all active projects with total amounts at a glance
- ➕ **Project Management** — Create and organize projects easily
- 💰 **Cash Tracking** — Add, edit, and delete cash entries per project
- 🧾 **Invoice Generation** — Generate professional invoices with PDF export
- 🖼️ **Invoice Image Attachments** — Attach and view invoice images per project
- 🖨️ **Invoice Printing** — Print invoices with company branding (Zmzm / DS templates)
- 🔔 **Notifications** — Real-time alerts when team members add or edit entries
- 👥 **User Management** — View all registered users in the system
- 📶 **Connectivity Monitoring** — Detects internet status in real time

---
 
## 📸 Screenshots
 
### Authentication
 
| Splash Screen | Login | Register | Forgot Password |
|:-:|:-:|:-:|:-:|
| <img src="screenshots/Splash Screen.jpeg" width="160"/> | <img src="screenshots/Login Page.jpeg" width="160"/> | <img src="screenshots/Register Page.jpeg" width="160"/> | <img src="screenshots/Forget Password Page.jpeg" width="160"/> |
 
### Projects
 
| Home / All Projects | Add Project | Project Details |
|:-:|:-:|:-:|
| <img src="screenshots/All Projects Screen.jpeg" width="160"/> | <img src="screenshots/Add Project Screen.jpeg" width="160"/> | <img src="screenshots/Home Page.jpeg" width="160"/> |
 
### Cash & Invoices
 
| Cash Entries | Add Cash | Invoice List | Invoice Images |
|:-:|:-:|:-:|:-:|
| <img src="screenshots/Cashes Screen.jpeg" width="160"/> | <img src="screenshots/Add Cash To Project.jpeg" width="160"/> | <img src="screenshots/Invoices Screen .jpeg" width="160"/> | <img src="screenshots/Images Invoices Screen.jpeg" width="160"/> |
 
### Printing & Reports
 
| Print Invoice | Print Options |
|:-:|:-:|
| <img src="screenshots/Print Invoice.jpeg" width="160"/> | <img src="screenshots/Print Invoice Widget.jpeg" width="160"/> |
 
### Team & Notifications
 
| All Users | Notifications |
|:-:|:-:|
| <img src="screenshots/Users Screen.jpeg" width="160"/> | <img src="screenshots/Notifications Screen.jpeg" width="160"/> |
 
---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **Flutter** | Cross-platform UI framework (Dart) |
| **Firebase Auth** | User authentication & session management |
| **Cloud Firestore** | Real-time cloud database |
| **Firebase Storage** | Image and file storage |
| **Flutter BLoC** | State management pattern |
| **pdf + printing** | PDF invoice generation & printing |
| **image_picker** | Camera & gallery image selection |
| **flutter_image_compress** | Image optimization before upload |
| **connectivity_plus** | Internet connectivity detection |
| **flutter_localizations** | Arabic language & RTL support |
| **persistent_bottom_nav_bar** | Bottom navigation bar |
| **flutter_slidable** | Swipe-to-delete/edit list items |
| **open_filex** | Open PDF files on device |
| **uuid** | Unique ID generation |

---

## 📁 Project Structure

```
cashes/
├── lib/                  # Main application source code
├── assets/
│   ├── images/           # App icons and images
│   └── fonts/            # Cairo Arabic font family
├── screenshots/          # App screenshots for documentation
├── android/              # Android platform configuration
├── ios/                  # iOS platform configuration
├── web/                  # Web platform configuration
├── windows/              # Windows platform configuration
├── linux/                # Linux platform configuration
├── macos/                # macOS platform configuration
└── pubspec.yaml          # Project dependencies
```

---

## 🌍 Platform Support

| Platform | Status |
|----------|--------|
| Android | ✅ Supported |

---

## 👤 Developer

**Muhammed Ashraf Saleh**

[![GitHub](https://img.shields.io/badge/GitHub-MuhammedAshrafSaleh-black?logo=github)](https://github.com/MuhammedAshrafSaleh)

---

## 📄 License

This project is proprietary and not licensed for public use.

---

<p align="center">Built with ❤️ using Flutter & Firebase for ZMZM Decoration</p>
