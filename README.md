
# 🛠️ Codedu Service Booking App

A modern, full-stack **Service Booking Application** built using **Flutter** and **Firebase**.
This application acts as a seamless bridge between service providers and clients, offering real-time booking management, reactive state handling, and optimized backend integration.

---

## 🌟 Key Features

### 🔐 Secure Authentication

* Hybrid login system:

  * Email & Password authentication
  * One-tap Google Sign-In
* Reactive password visibility toggle
* Real-time form validation
* Secure session management via Firebase Auth

---

### 📅 Booking & Dashboard

#### 🧑‍🔧 Dynamic Service Listing

* Professionals categorized by expertise:

  * Electricians
  * Plumbers
  * Technicians
  * and more...
* Real-time updates powered by Cloud Firestore

#### 📌 Appointment Tracking

* Full CRUD functionality:

  * Create booking
  * View appointments
  * Update schedule
  * Cancel services

#### ⚡ Optimized Firestore Queries

* Composite indexing for high-performance data retrieval
* Efficient filtering and real-time sync

---

## 🚀 Advanced Features (Bonus)

### 🌙 Adaptive Dark Mode

* Fully responsive theme system
* Automatically adapts to:

  * System theme
  * User preference

### 📦 Offline Caching

* Powered by **GetStorage**
* Professional listings are serialized and cached locally
* Allows browsing services without active internet

---

## 🛠️ Technical Stack

| Component        | Technology                  |
| ---------------- | --------------------------- |
| Frontend         | Flutter (Dart)              |
| State Management | GetX                        |
| Backend          | Firebase (Auth & Firestore) |
| Local Storage    | GetStorage                  |
| Android NDK      | 27.0.12077973               |

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/azharsha001/codedu_service_booking.git
cd codedu_service_booking
```

---

### 2️⃣ Install Dependencies

```bash
flutter pub get
```

---

### 3️⃣ Firebase Configuration

* Place your `google-services.json` inside:

  ```
  android/app/
  ```
* Add your SHA-1 fingerprints (Debug & Release) to Firebase Console
* Enable Google Sign-In inside Firebase Authentication

---

### 4️⃣ Environment Setup

* Ensure `build.gradle.kts` references the correct `upload-keystore.jks`
* Configure signingConfigs properly for release builds

---

## 📱 Build for Production

To generate a signed production APK:

```bash
flutter build apk --release
```

---

## 🏗️ Project Architecture

* Reactive architecture using **GetX**
* Clean separation of:

  * UI
  * Controllers
  * Services
* Cloud-first backend with Firebase integration
* Offline-first enhancement using local caching

---

## 👨‍💻 Author

**Azharsha**
Junior Flutter Developer
Focused on Reactive Architecture & Cloud Integration

---

