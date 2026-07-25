# ✿ daily planner ✿

A cozy kawaii daily task organizer with a rice.place / neocities aesthetic.

**Features:**
- 📋 Task list (to-do + done) with progress bar — saves to localStorage
- 📝 Notepad with auto-save
- 🐾 AI sticker bot powered by Claude
- ✨ Fun facts box with floating fact bubbles

---

## Deploy to Netlify via GitHub

### 1. Fork / clone this repo

```bash
git clone https://github.com/YOUR_USERNAME/daily-planner.git
cd daily-planner
```

### 2. Create a Netlify site

Go to [app.netlify.com](https://app.netlify.com) and create a new site (you can use the **picstatic** site you already have).

### 3. Get your Netlify credentials

You need two values:

| Value | Where to find it |
|---|---|
| `NETLIFY_AUTH_TOKEN` | netlify.com → User Settings → Applications → **New access token** |
| `NETLIFY_SITE_ID` | Your site on Netlify → Site Configuration → **Site ID** |

### 4. Add secrets to GitHub

In your GitHub repo → **Settings → Secrets and variables → Actions → New repository secret**:

- `NETLIFY_AUTH_TOKEN` → paste your token
- `NETLIFY_SITE_ID` → paste your site ID

### 5. Push to main — done!

Every push to `main` auto-deploys to your Netlify URL.

```bash
git add .
git commit -m "update planner"
git push
```

---

## Local preview

Just open `index.html` in your browser — no build step needed, it's pure HTML/CSS/JS.

---

*made with spite, love, and too much caffeine. 2025-forever. ♡*
