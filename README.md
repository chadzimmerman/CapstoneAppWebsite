# EdVue Webpage & Mobile App

This repository contains a **simple one-page website** designed to host a downloadable version of the **EdVue mobile app**, the capstone project for **Chad Zimmerman** at Western Governors University (WGU).

## Website

The website is intentionally minimal and built with **plain HTML**. Its purpose is solely to provide users a straightforward way to download the Android APK for the EdVue app.

- The main page includes a **download button** linking directly to the `.apk` file.
- The `.apk` file is stored in the `downloads/` folder, and the HTML page references it locally.
- No backend framework (like Django or Node.js) is required for this site; it can be hosted as a static webpage anywhere.

Example of the download button:

```html
<a
  href="downloads/com.companyname.wgumauimobileapplication-Signed.apk"
  download
>
  <button>Download Android App</button>
</a>
```

---

## EdVue Mobile App

**EdVue** is a mobile application built in **C# using .NET MAUI**, designed as a capstone project to demonstrate proficiency in mobile development. The app provides functionality for students to track their academic progress and manage tasks efficiently.

### Features:

- **Multi-platform support**: Android (iOS planned)
- **User-friendly interface**: Intuitive navigation and responsive UI
- **Academic tracking**: Log assignments, grades, and progress metrics
- **Notifications**: Reminders for upcoming deadlines or important tasks
- **Offline access**: Core features available without an internet connection

The APK included in this repository (`com.companyname.wgumauimobileapplication-Signed.apk`) represents the **current stable build** of the app, ready to be installed on Android devices.

---

## Getting Started

1. Clone or download this repository.
2. Open the `index.html` file in a browser or host using a local server (e.g., VS Code GoLive).
3. Click the **Download Android App** button to download and install the EdVue APK on your device.

---

## Notes

- This site is intentionally **lightweight** and serves as a simple distribution method for the EdVue app.
- The mobile app is the main focus of the capstone project; the website exists purely as a hosting mechanism.

---
