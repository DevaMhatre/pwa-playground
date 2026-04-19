# 🎡 PWA Playground 

> A deep-dive into Progressive Web App architecture, built with pure Vanilla JS.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=flat-square)](https://devamhatre.github.io/pwa-playground/)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PWA](https://img.shields.io/badge/PWA-Ready-blueviolet?style=flat-square)](https://web.dev/progressive-web-apps/)

## 📖 The "Why" behind this project
I built this "Playground" to strip away the magic of modern frameworks and understand the **web's native power**. The goal was to master the PWA lifecycle—specifically how to take a standard web app and make it resilient, installable, and capable of working in "Lie-fi" (low connectivity) conditions.

## 🛠 Features & Implementations
- **Offline First:** Leveraged the **Cache API** to ensure the app remains functional without an internet connection.
- **Service Worker Mastery:** Implemented a custom `sw.js` to handle fetch events and resource caching.
- **Web App Manifest:** Hand-crafted `manifest.json` for a native-like installation experience on Android and iOS.
- **Zero Dependencies:** Built entirely with Vanilla JS to keep the footprint small and the performance high.

## 🧠 Learning Milestones
This project wasn't just about code; it was about understanding browser behavior:
* **Service Worker Scoping:** Learned why the directory structure is critical for worker registration.
* **Cache Strategies:** Experimented with "Cache First, then Network" to optimize load times.
* **UX for PWA:** Refining the splash screen, theme colors, and UI to feel like a native app once installed.

## 🚀 Getting Started
1. Clone the repo: `git clone https://github.com/devamhatre/pwa-playground.git`
2. Since this uses Service Workers, you'll need to run it through a local server (like Live Server in VS Code) for the PWA features to activate.
3. Open DevTools > Application > Service Workers to see the lifecycle in action.

---
*Developed by Deva Mhatre — exploring the future of the web.*
