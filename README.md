# Cele's Study Planner — Android Project

This is a native Android WebView wrapper for the Cele's Study Planner PWA.

---

## 📦 What's inside
- Your full PWA (index.html, manifest.json, sw.js, icons) bundled in `app/src/main/assets/www/`
- A native Android WebView Activity that loads it
- Proper back-button navigation support
- LocalStorage & DOM Storage enabled (your app data persists)
- Portrait-locked orientation (matches your PWA manifest)
- Theme color `#C04F68` (rose) applied to status bar

---

## 🛠 How to Build the APK

### Option A — Android Studio (Recommended)
1. Download & install [Android Studio](https://developer.android.com/studio)
2. Open Android Studio → **Open an Existing Project** → select this `CelePlanner` folder
3. Wait for Gradle sync to finish (~2-3 min first time)
4. Go to **Build → Build Bundle(s) / APK(s) → Build APK(s)**
5. APK will be at: `app/build/outputs/apk/debug/app-debug.apk`

### Option B — Command Line (if you have Android SDK)
```bash
cd CelePlanner
chmod +x gradlew
./gradlew assembleDebug
```
APK output: `app/build/outputs/apk/debug/app-debug.apk`

### Option C — Online (No install needed)
1. Upload this zip to [Appetize.io](https://appetize.io) to test in browser, OR
2. Use [GitHub Actions](https://github.com) — push this project and add a build workflow

---

## 📱 Install on your Android Phone
Once you have the APK:
1. Transfer APK to your phone (USB, Google Drive, email, etc.)
2. On your phone: **Settings → Security → Allow Unknown Sources** (or "Install Unknown Apps")
3. Open the APK file and tap **Install**

---

## 📋 App Details
- **Package ID:** `com.cele.planner`
- **App Name:** Cele's Planner
- **Min Android:** 5.0 (API 21) — supports ~99% of devices
- **Target Android:** 14 (API 34)
- **Version:** 1.0

---

## ✏️ Want to update the app content?
Just replace the files inside `app/src/main/assets/www/` with your updated HTML/JS/CSS and rebuild.
