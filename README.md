# 🚀 ejudge_tracker

A lightweight, mobile-first web dashboard for tracking **Algocode** and **Ejudge** standings. It displays your live rank, solved task count, and automatically recommends the easiest unsolved problem to tackle next based on overall submission stats.

---

## ✨ Features

- **📊 Live standings tracking** — displays your exact rank, total solved problems, and penalty points.
- **🎯 Smart problem recommendation** — automatically highlights the most solved problem by peers that you haven’t solved yet.
- **📱 Mobile & PWA ready** — optimized for smartphone browsers with a zero-clutter UI.
- **💾 Local caching** — instantly loads your stats offline from browser cache before fetching updates.

---

## 🛠️ Setup

### 1. Clone or download the repository

```bash
git clone [https://github.com/your-username/ejudge_tracker.git](https://github.com/your-username/ejudge_tracker.git)
```

### 2. Set your name

Open `index.html` and change `TARGET_NAME` to match your exact name in the standings:

```javascript
const TARGET_NAME = "Your Full Name";
```

### 3. Deploy to GitHub Pages

1. Push your code to a public GitHub repository.
2. Go to **Settings** → **Pages**.
3. Under **Branch**, select `main` (or `master`) and `/ (root)`.
4. Click **Save**.

### 4. Add to phone

1. Open your GitHub Pages link in a mobile browser.
2. Tap **Share** on iOS Safari, or the **three-dot menu** on Android Chrome.
3. Select **Add to Home Screen**.
