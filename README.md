# FilmUnity

An Android app for exploring and discovering movies, built in Kotlin, with user authentication via Supabase and hardware features such as voice search and shake-to-discover.

Developed for the **Mobile Application Development** course at the Polytechnic Institute of Tomar (2024/2025).

---

## 📌 Project Overview

FilmUnity lets users browse movies by category, search the catalogue and view detailed information about each film, using data from a public movies API.

Main features:

* User registration and login with Supabase Authentication
* Home screen with:

  * Auto-scrolling image slider
  * Top movies and upcoming releases
  * Movie categories
* Movie details page (information, genres and cast)
* Text search
* Voice search using the microphone
* Shake the phone to get a random movie (accelerometer)
* User profile with logout

---

## ⚙️ Setup

Clone the repository:

```bash
git clone https://github.com/RodrigoH17/filmunity.git
cd filmunity
```

### Requirements

* Android Studio
* Android device or emulator running Android 12 (API 31) or later

---

## ▶️ Usage

1. Open the project folder in Android Studio
2. Wait for the Gradle sync to finish
3. Run the app on a device or emulator (**Run ▶**)

On first launch, create an account on the registration screen and log in.

---

## 🧠 Technologies

* Kotlin
* Android SDK (XML layouts)
* Supabase (authentication)
* Volley (HTTP requests) and Gson (JSON parsing)
* Glide (image loading and caching)
* ViewPager2 (image slider)
* Movies data from [moviesapi.ir](https://moviesapi.ir)

---

## 📌 Notes

* The user interface is in Portuguese
* `index.html` contains the app's privacy policy, written for the Google Play Store submission
* Build outputs, signing keys and APK files are ignored via `.gitignore`

---

## 👨‍💻 Authors

Rodrigo Henriques
GitHub: https://github.com/RodrigoH17

Gonçalo Henriques
GitHub: https://github.com/goncalohenriques48

---
