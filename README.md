# 🇬🇧 Life in the UK – Offline Practice Quiz

> A fully offline Progressive Web App (PWA) with 3,258 practice questions for the Life in the UK citizenship test.  
> Use it directly in your browser via GitHub Pages, install it as a PWA on your iPhone, or download the HTML file and run it locally.

🔗 **Live App: https://hsinghvicode.github.io/life-in-the-uk-quiz/**

---

## 📋 What's Inside

A **single HTML file** with **3,258 questions** across three practice modes — all embedded directly, no server calls needed.

| Mode | Questions | Source |
|------|-----------|--------|
| 📋 **Normal** | 408 | Original 17 official-style tests (Tests 1–17) |
| 🔥 **Hard** | 1,098 | AI-generated from original Q+A+Explanations |
| 📚 **New Tests** | 1,752 | Questions from Tests 1–40 + sub-chapter tests (3.x, 4.x, 5.x) |

### ✨ Features

- ✅ **Fully offline** – works with zero internet after first visit or download
- 📲 **PWA installable** – add to iPhone home screen, opens like a native app
- 🔀 **Shuffled every session** – questions appear in random order
- 📊 **Live score tracker** – correct/wrong count + % with pass mark at 75%
- 📈 **Progress bar** – shows how far through the quiz you are
- ◀ **Previous button** – go back and review your answer
- 💡 **Explanations** – shown after every answer (correct or wrong)
- ☑️ **Multi-select support** – "select all that apply" questions use checkboxes
- ⭐ **Mark for Review** – bookmark tricky questions and practice them separately
- 🌙 **Dark / Light mode** – toggle or follows your system preference
- 📱 **Mobile-first design** – optimised for iPhone screen sizes

---

## 📱 Option 1 — Install as a PWA (Recommended)

No download needed. Works like a native app from your home screen.

1. Open **Safari** on your iPhone
2. Go to 👉 **https://hsinghvicode.github.io/life-in-the-uk-quiz/**
3. Tap the **Share** button (box with arrow at the bottom of Safari)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **"Add"** in the top right
6. The 🇬🇧 UK Quiz icon appears on your home screen
7. Open it — runs **full screen, completely offline** ✅

> **Note:** The first visit must be online so the app can cache itself locally. After that it works with no internet at all.

---

## 📲 Option 2 — Download & Use with HTML Viewer App

If you prefer to keep the file fully local on your device without any hosting:

### Step 1 – Download the HTML Viewer App
1. Open the **App Store** on your iPhone
2. Search for **"HTML Viewer"**
3. Download and install it (free)

### Step 2 – Get the HTML file onto your iPhone

**Option A – via Safari (Easiest)**
1. Open this GitHub repo in Safari on your iPhone
2. Tap `index.html` → tap the **Raw** button
3. Tap the **Share** icon → **Save to Files**
4. Save it to a folder of your choice (e.g. On My iPhone)

**Option B – via AirDrop from Mac**
1. Clone or download the repo on your Mac
2. AirDrop `index.html` to your iPhone
3. When prompted, tap **Save to Files**

**Option C – via iCloud Drive**
1. Download `index.html` to your Mac
2. Move it to your iCloud Drive
3. Access it on iPhone via the Files app

### Step 3 – Open in HTML Viewer
1. Open the **HTML Viewer** app
2. Tap the **folder icon** to browse files
3. Find and tap `index.html`
4. It opens instantly — fully offline, no internet needed ✅

---

## 💻 Option 3 — Run Locally on Desktop

```bash
git clone https://github.com/hsinghvicode/life-in-the-uk-quiz.git
cd life-in-the-uk-quiz
open index.html   # Mac
# or double-click index.html in Finder / File Explorer
```

> ⚠️ Service workers (offline caching) don't work on `file://` URLs. For full PWA support use the hosted GitHub Pages URL. The quiz itself works fine in any browser either way.

---

## 🎮 How to Use the Quiz

1. **Choose a mode** using the buttons at the top:
   - 📋 Normal → 408 original questions
   - 🔥 Hard → 1,098 harder generated questions
   - 📚 New Tests → 1,752 questions from tests 1–40

2. **Read the question**, select your answer(s), tap **Check Answer**

3. Correct answer highlights green ✅, wrong in red ❌, explanation appears below

4. Tap **Next ▶** to continue or **◀ Prev** to go back

5. **⭐ Mark for Review** – tap on any question to save it to your review list

6. **⭐ Review button** (top bar) – opens your saved questions list and lets you practice only those

7. **↺ Begin Again** – resets score and reshuffles all questions

---

## 📁 Repository Structure

```
├── index.html            ← Entire quiz app (3,258 questions embedded)
├── manifest.json         ← PWA metadata (name, icons, theme)
├── service-worker.js     ← Offline caching logic
├── icon-192.png          ← App icon (home screen)
├── icon-512.png          ← App icon (splash screen)
└── README.md
```

---

## 📚 Question Sources

All questions sourced from [lifeintheuktestweb.co.uk](https://lifeintheuktestweb.co.uk), a free public practice resource for the official Life in the UK test.

---

## ⚠️ Disclaimer

This app is for **practice purposes only**. It is not affiliated with or endorsed by the UK Home Office or any official testing body. Always refer to the official [Life in the UK Test handbook](https://www.gov.uk/life-in-the-uk-test) for authoritative study material.

---

## 🏁 Good luck with your test! 🇬🇧
