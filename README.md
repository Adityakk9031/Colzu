# Colzu

**Colzu** is a Flutter-based e‑commerce mobile app for buying clothes and apparel. It includes user authentication integrated with Firebase and a simple shopping flow (browse products, add to cart, checkout). This repository contains the Flutter source code, assets, and configuration needed to run the app locally or on a device.

---

## 🔎 Project Overview

* **Platform:** Flutter (Android / iOS)
* **Backend:** Firebase (Authentication, Firestore / Realtime DB — depending on your implementation)
* **Purpose:** Demo e‑commerce app for clothing where users can sign up / sign in and purchase items.

---

## ✨ Key Features

* Firebase Authentication (email/password). (Google sign-in / social providers can be added via Firebase Console.)
* Product listing and detailed product pages.
* Add to cart and basic checkout flow.
* Persistent user sessions using Firebase.
* Responsive UI built with Flutter widgets.

---

## 📸 Screenshots

Gallery of images (from the repository):

![Colzu - 1](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image9.jpeg)

![Colzu - 2](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image8.jpeg)

![Colzu - 3](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image7.jpeg)

![Colzu - 4](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image6.jpeg)

![Colzu - 5](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image5.jpeg)

![Colzu - 6](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image4.jpeg)

![Colzu - 7](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image3.jpeg)

![Colzu - 8](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image2.jpeg)

![Colzu - 9](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image1.jpeg)

![Colzu - 10](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image10.jpeg)

![Colzu - 11](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image11.jpeg)

![Colzu - 12](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image12.jpeg)

![Colzu - 13](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image13.jpeg)

![Colzu - 14](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image14.jpeg)

![Colzu - 15](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image15.jpeg)

![Colzu - 16](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image16.jpeg)

![Colzu - 17](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image17.jpeg)

![Colzu - 18](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image18.jpeg)

![Colzu - 19](https://github.com/Adityakk9031/Colzu/blob/5ec1e5b71178850beed53d75f02319f0304da030/image19.jpeg)

---

## 🛠️ Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/Adityakk9031/Colzu.git
cd Colzu
```

2. **Install dependencies**

```bash
flutter pub get
```

3. **Configure Firebase**

* Create a Firebase project at [https://console.firebase.google.com](https://console.firebase.google.com).
* Enable **Authentication** (Email/Password). Optionally enable Google sign‑in or other providers.
* Create a Firestore or Realtime Database to store products/orders if your app uses them.
* Download and place platform files:

  * **Android:** `google-services.json` → `android/app/`
  * **iOS:** `GoogleService-Info.plist` → `ios/Runner/`
* Initialize Firebase in your Flutter app (usually in `main.dart`) with `Firebase.initializeApp()`.

4. **Run the app**

```bash
flutter run
```

> If you target web: run `flutter run -d chrome` after configuring Firebase web settings in the console and adding the Firebase SDK config.

---

## 🧩 Common Packages (check `pubspec.yaml`)

* `firebase_core`
* `firebase_auth`
* `cloud_firestore` or `firebase_database`
* `provider`, `bloc`, or `riverpod` (state management)
* `flutter_stripe` or other payment SDK (if checkout/payments are implemented)

---

## 📁 Suggested Folder Structure

```
/lib
  /models
  /screens
  /widgets
  /services   # e.g., firebase_service.dart
  /providers  # state management
  main.dart
/assets
  /images
  /fonts
```

---

## 🤝 Contributing

Contributions are welcome! If you want to add features or fix bugs:

1. Fork the repository
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add feature"
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

Please include clear descriptions and, if relevant, screenshots.

---

## 📄 License

This project is open for your use. Add a LICENSE file if you want to specify terms (e.g., MIT).

---

## 📬 Contact

Aditya Kumar Singh — [adityakumarsingh9031@gmail.com](mailto:adityakumarsingh9031@gmail.com)


