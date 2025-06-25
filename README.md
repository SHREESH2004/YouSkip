
<h1 align="center">🚫 YouSkip — Skip YouTube Ads Instantly</h1>

<p align="center">
  <em>Because life's too short to wait through unskippable ads.</em>
</p>




<p align="center">
  <img src="https://img.shields.io/chrome-web-store/v/your-extension-id?label=Chrome%20Web%20Store&color=blue&style=for-the-badge">
  <img src="https://img.shields.io/badge/Built%20With-JavaScript%20%7C%20Chrome%20API-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/UX-Ad%20free%20experience-success?style=for-the-badge">
</p>

---



## 🎯 What is YouSkip?

**YouSkip** is a lightweight, no-BS **Chrome Extension** that detects and **skips YouTube ads** (both skippable and auto-plays) — automatically.

🔊 No sound tricks.  
🕹️ No manual clicking.  
💨 Just pure, smooth, uninterrupted video.


Working Video:

https://www.linkedin.com/posts/shreesh-sanyal_adfreeviewing-activity-7266873349304131584-MuCV?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEQfcz4B5Og0CfeuW2qS7o1-O5hql5j9Xhw




## ⚙️ Features

- ⏩ **Auto-Skip Skippable Ads**
- ❌ **Bypass Non-Skippable Intros**
- 🔍 **Works on YouTube & embedded players**
- 🧠 **Smart Detection** using DOM observation
- 💾 **Tiny footprint** – fast and memory efficient
- 🎨 **Minimal UI** – clean toggle & settings popup

---

## 🛠️ How It Works

The extension injects a lightweight content script into YouTube pages. It listens for DOM changes, identifies ad containers, and triggers one of the following:

- Clicks the **"Skip Ad"** button if present
- Mutes & fast-forwards **non-skippable ads**
- Hides **banner ads** and overlays

---

## 🧪 Tech Stack

| Layer        | Tech                |
|--------------|---------------------|
| 🔌 Extension | Chrome Extension API |
| ⚙️ Scripts    | JavaScript (ES6)     |
| 👁️ DOM Watch | MutationObserver     |
| 💄 Styling   | Tailwind (Popup UI)  |

---

## 📦 Installation

### 🧩 From Chrome Web Store (Recommended)

> Coming Soon to Chrome Web Store! 🔗

### 🛠️ Manual Installation

1. Clone the repo

```bash
git clone https://github.com/yourusername/youskip-extension.git
cd youskip-extension
````

2. Open **Chrome → Extensions (chrome://extensions)**
3. Enable **Developer Mode**
4. Click **Load Unpacked** and select the project folder
5. You're all set! 🎉

---

## 📂 File Structure

```
youskip-extension/
├── manifest.json          # Extension config
├── background.js          # (Optional) background tasks
├── content.js             # DOM-based ad detection & skipping
├── popup/
│   ├── popup.html         # Popup UI
│   └── popup.js
└── assets/                # Icons, logos
```

---

## 🖼 Preview

<p align="center">
  <img src="https://your-image-link.com/popup-preview.png" width="400" alt="YouSkip Popup" />
  <br/>
  <em>One-click toggle. Ad-free joy. ✨</em>
</p>

---

## 🧩 Upcoming Features

* ⏲️ Ad-block analytics & stats
* 🧠 AI-enhanced ad pattern detection
* 🌙 Dark/light popup themes
* 🔄 Auto-update checker

---

## 🤝 Contributing

PRs welcome! To contribute:

```bash
# Fork & clone the repo
git checkout -b feature/your-feature
git commit -m "feat: added your feature"
git push origin feature/your-feature
```

Then open a Pull Request 🙌

---

## 📜 License

Licensed under the [MIT License](LICENSE).
