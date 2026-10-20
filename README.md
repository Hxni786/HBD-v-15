# 💌 A Love Letter For You ♥ — Bubu & Dudu Edition

<p align="center">
  <img src="gifs/hero.gif" alt="Bubu and Dudu Couple" width="300" style="border-radius: 20px; box-shadow: 0 10px 30px rgba(232, 86, 127, 0.3);" />
</p>

<p align="center">
  <strong>A premium, romantic, and interactive love letter web experience featuring Bubu & Dudu.</strong><br>
  Built with vanilla modern web technologies, procedural animations, glassmorphism UI, and ambient Web Audio.
</p>

<p align="center">
  <a href="https://instagram.com/the.cipher.stack"><img src="https://img.shields.io/badge/Instagram-@the.cipher.stack-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram @the.cipher.stack"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License: MIT">
</p>

---

## 📖 Overview

**A Love Letter For You** is a bespoke, luxury-styled digital greeting experience created to express heartfelt love and birthday wishes. It blends aesthetic typography, gentle animations, responsive glassmorphic cards, and adorable **Bubu & Dudu** animations into an unforgettable interactive journey.

---

## ✨ Features

- 💌 **Wax-Sealed 3D Envelope Animation** — An interactive envelope with smooth CSS 3D flap opening, animated wax seal, and letter extraction.
- 🐻 **Bubu & Dudu Curated Moments** — Integrated local GIF collection with dual-layer fallback systems to ensure smooth, offline-ready playback.
- 📜 **Typewriter Love Letter** — Realistic character-by-character typing animation with a blinking cursor and custom recipient support.
- 💐 **Blooming Vector Bouquet** — Hand-crafted SVG bouquet with animated stem growth paths and blossom rotation.
- 💓 **Interactive Love Meter** — A responsive progress gauge with shimmering lights and explosive radial heart bursts.
- 💫 **Reasons & Promises Carousels** — Thoughtfully curated romantic reasons and promises with smooth transition physics.
- 🎵 **Synthesized Ambient Music** — Built-in ambient harmonic Cmaj7 pad created with the **Web Audio API** (no external audio files required).
- ✨ **Particle Physics & Confetti** — Canvas-driven gradient background orbs, floating emoji sparks, mouse-cursor trails, and celebratory confetti cannons.
- 📱 **Fully Responsive & Dark Mode Ready** — Optimized for iOS, Android, and Desktop with automatic system theme adaptation.
- 🔗 **Instant Personalization via URL** — Customize the recipient, sender, and custom message on the fly using query parameters.

---

## 🎬 Live Preview & How to Run

### Option 1: Direct File Open
Simply double-click [`A love letter for you.html`](A%20love%20letter%20for%20you.html) to open it directly in any modern web browser (Chrome, Safari, Edge, Firefox, Brave).

### Option 2: Local HTTP Server (Recommended)
Using Python:
```bash
# Python 3
python -m http.server 8000
```
Then visit:
```text
http://localhost:8000/A%20love%20letter%20for%20you.html
```

Using Node.js:
```bash
npx serve .
```

---

## 🔗 URL Customization Guide

You can personalize this love letter without editing any code! Simply add query parameters to the URL:

| Parameter | Type | Description | Default | Example |
| :--- | :--- | :--- | :--- | :--- |
| `to` | `string` | Name of your loved one / recipient | `My Love` | `?to=Angelica` |
| `from` | `string` | Your name / signature | *(None)* | `?from=Alex` |
| `msg` | `string` | Custom personal love message | *(Curated poem)* | `?msg=You+mean+the+world+to+me` |

### 💡 Example Custom Links:
```text
A love letter for you.html?to=Sarah&from=David
```
```text
A love letter for you.html?to=Honey&from=Your+Bubu&msg=Happy+Birthday+to+my+one+and+only!
```

---

## 📁 Project Structure

```text
├── A love letter for you.html   # Main application (HTML5, CSS3, JS ES6+)
├── README.md                    # Project documentation
└── gifs/                        # High-resolution Bubu & Dudu animation suite
    ├── hero.gif                 # Bubu & Dudu couple animation
    ├── kiss.gif                 # Sweet kisses animation
    ├── hug1.gif                 # Warm hug animation
    ├── goodnight.gif            # Sleep & snuggle animation
    ├── love_heart.gif           # Heart celebration animation
    ├── propose.gif              # Rose & flower animation
    ├── cuddle.gif               # Sweet cuddle animation
    ├── playful.gif              # Playful moments animation
    ├── together.gif             # Together forever animation
    ├── sweet.gif                # Gentle moments animation
    ├── affection.gif            # Affectionate gestures animation
    └── hearts.gif               # Fluttering hearts animation
```

---

## 🛠️ Built With

- **HTML5 & Modern Web Standards** — Clean semantic structure and full mobile viewport scaling.
- **Pure Modern CSS3** — CSS custom properties, backdrop-filter glassmorphism, keyframe physics, and fluid typography (`clamp()`).
- **Vanilla JavaScript (ES6+)** — Zero heavy external frameworks or dependencies; lightweight and lightning-fast.
- **Web Audio API** — Real-time polyphonic audio synthesis with low-frequency oscillators (LFO) for ambient soothing soundscapes.
- **HTML5 Canvas** — Hardware-accelerated particle animation for floating orbs and opening confetti explosions.

---

## 👨‍💻 Author & Connect

Developed and crafted with love by **The Cipher Stack**.

<p align="left">
  <a href="https://instagram.com/the.cipher.stack" target="_blank">
    <img src="https://img.shields.io/badge/Follow-@the.cipher.stack-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Follow on Instagram" />
  </a>
</p>

- 📸 **Instagram:** [@the.cipher.stack](https://instagram.com/the.cipher.stack)
- 💬 Connect for collaborations, creative frontend projects, and tech design inquiries.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to customize and share it with your special someone! ♥
