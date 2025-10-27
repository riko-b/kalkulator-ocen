# 🎓 Grade Calculator – mgr Agnieszka Makuła-Broda

A simple web-based grade calculator for teachers.  
It automatically converts test points into percentages and grades according to custom thresholds.  
Works fully in the browser and can be installed as a **PWA (Progressive Web App)** on desktop or mobile.

🔗 **Live app:**  
👉 [https://riko-b.github.io/kalkulator-ocen/](https://riko-b.github.io/kalkulator-ocen/)

---

## ✨ Features

- Set the **maximum score** and **grading thresholds** (percentage or point-based)  
- Supports **1–6** or **1–5** grading scales  
- Editable **grade names** (e.g. “good”, “pass”)  
- **Auto-calculation** – live results as you type  
- Keyboard shortcuts: **Enter** (calculate) and **Ctrl+Enter** (global calculate)  
- **Animated spinner** visible only during auto-calculation  
- **Quick results table** for all possible scores  
- **LocalStorage** saving (settings persist after refresh)  
- Fully functional **offline (PWA)** mode after first load  

---

## 📲 Install as an App (PWA)

### 🔹 Android / Windows
1. Open:  
   👉 [https://riko-b.github.io/kalkulator-ocen/](https://riko-b.github.io/kalkulator-ocen/)
2. In your browser menu (⋮), choose **“Install App”** or **“Add to Home Screen”**.

### 🔹 iPhone / iPad (Safari)
1. Open the page in Safari.  
2. Tap **Share → Add to Home Screen**.

---

## ⚙️ Editing thresholds and settings

1. In the **“Grade thresholds”** section, enter the minimum values for each grade (in % or points).  
2. You can also rename grades (e.g. “Pass”, “Fail”).  
3. Click **“Save settings”** to keep them permanently in your browser.  
4. Use **“Restore defaults”** to reset everything.

---

## 💾 Data storage

All data (thresholds, scale, names, auto-calc, etc.) is stored locally in your browser (`localStorage`).  
No data is uploaded or sent anywhere.

---

## 🌐 Offline use (PWA)

The app includes:
- `manifest.webmanifest` – PWA configuration  
- `sw.js` – service worker for offline caching  

This allows the app to work **completely offline** after the first launch.  
It can be opened like a native mobile app.

---

## 🧩 Updating the app

1. Modify `index.html` or any other file in the repository.  
2. Commit your changes.  
3. GitHub Pages will automatically deploy a new version (within 1–2 minutes).  
4. After refreshing, users will automatically get the latest version.

---

## 📧 Author

Created for:  
**mgr Agnieszka Makuła-Broda**

GitHub repository: [riko-b/kalkulator-ocen](https://github.com/riko-b/kalkulator-ocen)

---

_© 2025 Educational project. Free to use and modify for teaching purposes._
