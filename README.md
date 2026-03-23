# Rehab Protocol PWA

Your patellar tendinopathy + golfer's elbow rehab tracker.

## Deploy to GitHub Pages (free, takes 5 min)

### 1. Create a GitHub repo
- Go to https://github.com/new
- Name it something like `rehab` or `rehab-tracker`
- Make it **public** (required for free GitHub Pages)
- Click **Create repository**

### 2. Upload files
- On the repo page, click **"uploading an existing file"**
- Drag in ALL files from this folder: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to **Settings** → **Pages** (left sidebar)
- Under "Source", select **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**
- Wait 1-2 minutes, your site will be live at: `https://YOUR-USERNAME.github.io/rehab/`

### 4. Install on your Android
- Open Chrome on your phone
- Go to `https://YOUR-USERNAME.github.io/rehab/`
- Tap the **three dots** menu (top right)
- Tap **"Add to Home Screen"** or **"Install app"**
- It now works like a native app, including offline

## Data
All your session data is stored locally on your phone via localStorage. It stays on your device — nothing is sent anywhere. If you clear browser data, you lose your sessions, so don't do that.

## Alternative: Cloudflare Pages (also free)
1. Go to https://pages.cloudflare.com
2. Connect your GitHub repo
3. Deploy — same result, slightly faster CDN
