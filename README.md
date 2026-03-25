# DinglMaryam — GitHub Pages Setup Guide

## 📁 Files in This Package

| File | Purpose |
|------|---------|
| `index.html` | Landing page (Saint Mary image + scripture) |
| `prayers.html` | Prayers: Psalm · Kidan · Liturgy |
| `books.html` | Books: Early Fathers · Contemporary |
| `kids.html` | Kids: Books · Games · Language · Scripture |
| `saints-life.html` | Saint's Life: Saint of the Day |
| `styles.css` | Shared stylesheet (do not delete) |

---

## 🚀 How to Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Account
1. Go to https://github.com
2. Sign up with the username **DinglMaryam**

### Step 2 — Create a Repository
1. Click the **+** icon (top-right) → **New repository**
2. Name it exactly: `DinglMaryam.github.io`
3. Set visibility to **Public**
4. Click **Create repository**

### Step 3 — Upload Your Files
1. In the new repo, click **Add file** → **Upload files**
2. Drag and drop ALL 6 files from this folder:
   - `index.html`
   - `prayers.html`
   - `books.html`
   - `kids.html`
   - `saints-life.html`
   - `styles.css`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to repo **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `Deploy from a branch`
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**

### Step 5 — Your Site is Live! 🎉
Your site will be available at:
👉 **https://DinglMaryam.github.io**

(It may take 1–2 minutes to go live after saving.)

---

## 🖼️ Adding the Saint Mary Image

Open `index.html` and find this section (around line 30):

```html
<!-- Replace the placeholder below with your image -->
<div class="icon-placeholder">🕊️</div>
```

**Option A — Use an online image URL:**
Replace the `<div class="icon-placeholder">` with:
```html
<img class="icon-img" src="YOUR_IMAGE_URL_HERE" alt="Saint Mary" />
```

**Option B — Upload an image file:**
1. Add your image file (e.g. `saint-mary.jpg`) to the repo
2. Replace with:
```html
<img class="icon-img" src="saint-mary.jpg" alt="Saint Mary" />
```

---

## ✏️ Adding Content to Each Page

Each subsection has a `<div class="subsection-content">` block.
Replace or add to the text inside those blocks with your actual content.

Look for the gold-bordered placeholder tags like:
```
✦ Add Your Psalm Content Here
```
These are your edit markers — replace them with real content whenever you're ready.
