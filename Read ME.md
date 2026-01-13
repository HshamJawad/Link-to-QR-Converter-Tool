# 🔳 Link to QR Converter Tool (PWA)

A lightweight, offline-first **Progressive Web App (PWA)** that converts any URL into a high-quality, scannable QR code.  
Designed for **simplicity, reliability, and mobile usability**, with special handling for Android PWA landscape behavior.

---

## 🚀 Features

- 🔗 Convert any URL into a QR code instantly
- 🎨 Custom QR colors
- 📐 Adjustable QR size (Small / Medium / Large)
- 📥 Download QR as PNG with white border
- 📋 Copy QR image to clipboard
- 🌙 Dark mode toggle
- 📱 Mobile-first responsive design
- 📴 Works fully **offline** (PWA)
- 🏠 Installable on mobile home screen

---

## 📱 Mobile & PWA Behavior

This tool is optimized for **mobile and installed PWA usage**, including a known workaround for Android PWA rotation issues.

### ✅ Portrait Mode (Mobile)
- Compact single-column layout
- Generate button placed close to URL input
- Reduced white space for better usability

### ✅ Landscape Mode (Installed PWA)
- Desktop-like two-column layout
- Reliable orientation detection using JavaScript
- CSS-only solutions were intentionally avoided due to Android WebView limitations

---

## 🧠 Technical Note: Android PWA Landscape Fix

Some Android devices lock PWAs in portrait mode due to WebView limitations.

This project solves that by:
- Detecting real device orientation using:
  ```js
  window.innerWidth > window.innerHeight
Dynamically toggling layout classes:

pwa-portrait

pwa-landscape

Forcing layout reflow to ensure correct rendering in standalone mode

This approach is production-proven and commonly used in real-world PWA dashboards and offline tools.

🛠️ Tech Stack

HTML5

CSS3 (Flexbox, Media Queries)

Vanilla JavaScript

QRCode.js

Progressive Web App (Manifest + Service Worker)

No frameworks. No build tools. No backend.

📦 Installation (PWA)

Open the tool in Chrome (Android)

Tap “Add to Home Screen”

Launch from the home screen

Use online or offline

⚠️ If updating the app:

Uninstall the existing PWA

Refresh the browser version

Reinstall from the home screen

🔒 Privacy

No tracking

No analytics

No data collection

All processing happens locally on your device

📄 License

MIT License
You are free to use, modify, and distribute this tool with attribution.


⚠️ Disclaimer

This tool is provided “as is”, without warranty of any kind.
Users are responsible for validating QR codes before production or official use.

⭐ Contributing

This is a minimal, single-file utility.
Suggestions and improvements are welcome via GitHub issues or pull requests.

👤 Author

Husham Jawad Kadhim
TVET Curriculum Developer & Educational Technology Innovator

Note: On some Android devices, installed PWAs may remain in portrait mode due to system-level WebView limitations.

Enjoy using the tool! 🎉


---

## 📞 Support

**Email:** hshaam77@gmail.com  
**LinkedIn:** Husham Jawad Kadhim

