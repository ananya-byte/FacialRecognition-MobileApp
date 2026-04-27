# 🤖 Facial Recognition Mobile App

An Android application that uses facial recognition to identify and label people in photos. This serves as the mobile counterpart to the [Event Gallery Organizer](https://github.com/ananya-byte/event-gallery-organizer) project, packaging the face detection and labelling logic into a standalone mobile experience.

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

---

## ✨ Features

- Real-time facial detection using the device camera
- Label and identify people across a photo collection
- Clean Android UI with intuitive navigation
- Integrates with the Event Gallery Organizer codebase

---

## 🗂 Project Structure

```
FacialRecognition-MobileApp/
├── event-gallery-organizer/   # Core gallery + face-label module
└── README.md
```

---

## 🛠 Setup

### Prerequisites
- Android Studio (latest stable)
- Android device or emulator running API 21+

### Installation

```bash
git clone https://github.com/ananya-byte/FacialRecognition-MobileApp.git
```

1. Open the project in Android Studio
2. Add your `google-services.json` to the `/app` directory
3. Sync Gradle dependencies
4. Run on a connected device or emulator

---

## 🔗 Related Projects

This app shares its core logic with [event-gallery-organizer](https://github.com/ananya-byte/event-gallery-organizer). For the full gallery organisation experience, see that repository.

---

## 💡 What I Learned

- Android camera integration and permissions handling
- Face detection using ML Kit on-device models
- Structuring reusable modules across Android projects
- Gradle multi-module project setup
