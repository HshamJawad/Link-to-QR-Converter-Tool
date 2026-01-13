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


---

## 📞 Support

**Email:** hshaam77@gmail.com  
**LinkedIn:** Husham Jawad Kadhim

