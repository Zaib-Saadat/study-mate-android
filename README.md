# 📚 Study Mate

A collaborative Android application designed to help students organize their studies, manage tasks, and stay productive — powered by Firebase.

---
##  Screenshots
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/a99fa4ec-a766-4dd3-a27e-0266d95dd55e" />

---
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/0f622c57-0725-4beb-bd1f-adfa59ba2ffc" />

---
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/366513e5-0271-4507-8c89-120832d5a098" />

---
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/0a0ecf43-eefd-48c4-8758-eeb0cfe15f37" />

---
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/048780de-01e1-4fb9-8470-b308a421132b" />

---
<img width="540" height="1230" alt="image" src="https://github.com/user-attachments/assets/24d9413d-ff74-402a-a7d2-7ff89cb834d8" />


---
## ✨ Features

- 🔐 **User Authentication** — Secure sign-up and login via Firebase Auth
- ☁️ **Cloud Database** — Real-time data sync using Firebase Firestore
- 🖼️ **Profile Images** — Smooth image loading with Glide & CircleImageView
- 📱 **Modern UI** — Clean, responsive design using Material Design components
- ⚡ **Fast & Lightweight** — Optimized for Android 7.0+ (API 24+)

---

## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|--------------------------------------|
| Language     | Java                                 |
| Platform     | Android (minSdk 24, targetSdk 34)    |
| Auth         | Firebase Authentication              |
| Database     | Firebase Firestore                   |
| Image Loading| Glide 4.16 + CircleImageView 3.1     |
| UI           | Material Design, ConstraintLayout    |
| Build System | Gradle (Kotlin DSL)                  |

---

## 🚀 Getting Started

### Prerequisites

- Android Studio (latest stable)
- JDK 11+
- A Firebase project (see setup below)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/study-mate.git
   cd study-mate
   ```

2. **Firebase Setup**
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project (or use an existing one)
   - Add an Android app with package name `com.example.studymate`
   - Download `google-services.json` and place it in the `/app` directory
   - Enable **Authentication** (Email/Password) and **Firestore Database**

3. **Open in Android Studio**
   - Open the project root folder
   - Let Gradle sync complete
   - Run on an emulator or physical device (Android 7.0+)

---

## 📁 Project Structure

```
StudyMate/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/studymate/
│   │       └── res/
│   ├── build.gradle.kts
│   └── google-services.json
├── build.gradle.kts
├── settings.gradle.kts
└── gradle/
    └── libs.versions.toml
```

---

## 🔑 Environment & Security

> ⚠️ **Important:** Never commit your `google-services.json` or any API keys to a public repository.

- Add `google-services.json` to your `.gitignore`
- Use Firebase Security Rules to restrict Firestore access per user

---

## 👨‍💻 Authors

| Name | GitHub |
|------|--------|
| Tayyab Mehmood | [@Tayyab-Mehmood](https://github.com/Tayyab-Mehmood) |
| Zaib Saadat | [@Zaib-Saadat](https://github.com/Zaib-Saadat) |

---

## 📄 License

This project is for educational purposes. Feel free to fork and build upon it.

---

<p align="center">Made with ❤️ for students, by students</p>
