# ⭐ StarHub Arcade — Online Play & Offline Download Platform (with Auto-APK Builder)

Yeh package aapke **StarHub Arcade & App Store Platform** ko:
1. **Live Online Browser Play** (Star Catcher Deluxe, QuickStreak Habit Tracker, aur Cosmic Match Puzzle)
2. **Instant Offline Download (.html)** (bina internet ke kisi bhi phone/computer par chalne wali file)
3. **Device Installation (PWA)** (Chrome/Edge se seedha phone ke Home Screen par app ki tarah install)
4. **Automatic Android `.apk` Generation on GitHub** (`.github/workflows/build-apk-and-pages.yml` ke zariye)

ke liye bilkul tayyar rakhta hai.

## 🚀 GitHub Par Upload Kar Ke APK Aur Live Website Kaise Banayein (3 Easy Steps)

1. GitHub (https://github.com/new) par ek naya Public repository banayein (jaise `starhub-arcade`).
2. Is ZIP folder ki saari files (`index.html`, `manifest.json`, `sw.js`, `package.json`, `capacitor.config.json`, aur `.github/workflows/build-apk-and-pages.yml`) apne GitHub repository mein upload (commit) kar dein.
3. Repository ke **Settings -> Pages** mein ja kar **Source** ko **GitHub Actions** par set karein.
   - GitHub ka cloud server khud-ba-khud **Android SDK + Capacitor** chala kar aapki `StarHub-Arcade-Android.apk` file compile karega aur aapki live website (`https://<your-username>.github.io/starhub-arcade/`) bhi publish kar dega!
