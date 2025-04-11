# 📘 School Management App

[![Flutter](https://img.shields.io/badge/Built%20With-Flutter-blue)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)](https://firebase.google.com/)
[![Isar](https://img.shields.io/badge/Offline%20DB-Isar-yellowgreen)](https://isar.dev)
[![Razorpay](https://img.shields.io/badge/Payments-Razorpay-lightgrey)](https://razorpay.com/)
[![Cloudinary](https://img.shields.io/badge/Image%20Storage-Cloudinary-blueviolet)](https://cloudinary.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📱 Overview

**School Management App** is a full-featured, Flutter-based cross-platform application designed to streamline academic, administrative, and canteen workflows in educational institutions. It includes dedicated modules for **students**, **teachers**, and **admin**, each with role-specific dashboards, navigation, and UI.

The app supports both **online** and **offline-first** usage. It uses **Firebase** for cloud data handling, **Isar** for local offline persistence, and **Cloudinary** for media hosting. The **canteen module** offers a Swiggy-like experience, powered by **Razorpay** for seamless payment processing.

---

## 🛠️ Tech Stack

- **Flutter & Dart**
- **Firebase (Auth, Firestore)**
- **Isar** (local database for offline functionality)
- **Cloudinary** (for image storage)
- **Razorpay** (for payment integration)
- **Android Studio** (development IDE)
- **Figma** (UI/UX design)
- **Provider** (state management)

---

## 🔑 Features

- 🔐 **Biometric Authentication** (Fingerprint)
- 👤 **Role-based Login & UI** for students, teachers & admins
- 📋 **Academic Records Dashboard** with detailed student info
- 📅 **Leave Management System** with offline request/approval
- 📝 **Homework Module**: Teachers assign & students upload attachments
- 🏫 **School Info Page** editable by admin only
- 📄 **Legal Pages**: Privacy Policy & Terms & Conditions
- 🍴 **Canteen Module**:
  - Menu selection
  - Cart & order summary
  - Online payments via Razorpay
  - Offline draft orders with retry logic
  - PDF receipt generation & download
  - Payment history tracking

---

## 🌐 Offline Support

- Add/edit data while offline using **Isar**
- Submit leave requests, academic records, homework, etc. offline
- Auto-sync when reconnected
- Draft saving for failed or offline payments

---

## 📸 Media & Assets

- Users can update profile photos (stored securely in Cloudinary)
- Admin manages global school content and settings

---

## 📦 Installation

1. Clone the repository  
   `git clone https://github.com/muhammedshehzad/School-Management-Application-New.git`

2. Navigate to the project folder  
   `cd school-management-app`

3. Get dependencies  
   `flutter pub get`

4. Run the app  
   `flutter run`

---

