<div align="center">
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/android/android.png" width="100" height="100" alt="Android Logo" />
  
  # 🎓 GradeMaster (Study-Mate)
  
  **Your ultimate academic companion for tracking classes, exams, assignments, and tasks.**
  
  <p align="center">
    <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
    <img src="https://img.shields.io/badge/Material%20UI-0081CB?style=for-the-badge&logo=material-design&logoColor=white" alt="Material UI" />
  </p>

  [Explore Features](#-features) • [Installation](#-getting-started) • [Tech Stack](#-tech-stack) • [Screenshots](#-screenshots)
</div>

<br/>

## 📖 Overview

**GradeMaster** (also known as *Study-Mate*) is a fully-featured native Android application designed to help students organize their academic lives efficiently. Say goodbye to scattered notes and missed deadlines. GradeMaster consolidates your classes, exam schedules, and daily tasks into one beautiful, easy-to-use platform powered by Firebase.

---

## ✨ Features

🔐 **Secure Authentication**
- Seamless Login and Registration using **Firebase Authentication**.
- Secure password handling with **BCrypt** encryption.
- Password recovery and reset functionality.

📚 **Class Management**
- Add, update, and organize all your classes in one place.
- Detailed views for each class including schedules and related resources.

📝 **Exam Tracking**
- Keep track of upcoming exams, dates, and corresponding subjects.
- Quick summary cards for immediate visibility.

✅ **Task & Assignment Board**
- Robust task management system.
- Add new tasks, update statuses, and never miss an assignment deadline.

🧮 **Built-in Study Tools**
- Integrated calculator fragment for quick calculations without leaving the app.

👤 **Personalized Profile**
- Manage personal details and app preferences directly from the Profile dashboard.

---

## 📱 Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="https://via.placeholder.com/250x500.png?text=Login+Screen" alt="Login Screen"></td>
      <td><img src="https://via.placeholder.com/250x500.png?text=Home+Dashboard" alt="Home Dashboard"></td>
      <td><img src="https://via.placeholder.com/250x500.png?text=Classes+List" alt="Classes List"></td>
    </tr>
    <tr>
      <td align="center"><b>Authentication</b></td>
      <td align="center"><b>Home Dashboard</b></td>
      <td align="center"><b>Class Management</b></td>
    </tr>
  </table>
</div>
<br/>
<div align="center">
  <table>
    <tr>
      <td><img src="https://via.placeholder.com/250x500.png?text=Task+Manager" alt="Tasks"></td>
      <td><img src="https://via.placeholder.com/250x500.png?text=Exam+Tracker" alt="Exams"></td>
      <td><img src="https://via.placeholder.com/250x500.png?text=Calculator" alt="Calculator"></td>
    </tr>
    <tr>
      <td align="center"><b>Task Manager</b></td>
      <td align="center"><b>Exam Tracker</b></td>
      <td align="center"><b>Integrated Calculator</b></td>
    </tr>
  </table>
</div>

> **Note:** Replace the placeholder image URLs above with actual screenshots of the application.

---

## 🛠️ Tech Stack

**Client:**
- **Language:** Java
- **Architecture:** Android Native (Activity/Fragment based)
- **UI Components:** XML Layouts, Material Design (`com.google.android.material:material`), ViewBinding
- **Animations:** Android GIF Drawable (`pl.droidsonroids.gif:android-gif-drawable`)

**Backend & Data:**
- **Database:** Firebase Realtime Database
- **Authentication:** Firebase Auth
- **Security:** BCrypt built-in integration

**Build System:**
- Gradle (Kotlin DSL `build.gradle.kts`)
- Minimum SDK: 24 (Android 7.0)
- Target SDK: 34 (Android 14)

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- **Android Studio** (Latest stable version recommended)
- **Java Development Kit (JDK)** 17 or higher
- An active **Firebase Project**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Study-Mate-Android-App.git
   ```

2. **Open in Android Studio:**
   Launch Android Studio and select `Open an existing Android Studio project`. Navigate to the cloned directory.

3. **Configure Firebase:**
   - Go to your [Firebase Console](https://console.firebase.google.com/).
   - Add an Android App with the package name: `com.example.grademaster`.
   - Download the `google-services.json` file.
   - Place `google-services.json` in the `app/` directory of this project.
   - Enable **Authentication** (Email/Password) and **Realtime Database** in your Firebase console.

4. **Sync Project with Gradle Files:**
   Allow Android Studio to download the necessary dependencies.

5. **Run the App:**
   Connect a physical Android device or start an emulator and click the **Run** button (▶) in Android Studio.

---


