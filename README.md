# Rehab Protocol PWA

Knee-only patellofemoral pain syndrome (PFPS) rehab tracker.

The protocol uses staged hip- and knee-targeted strengthening, symptom-guided load management, daily-life pain tracking, and a flare option available from every phase. It is educational support and does not replace an individualized assessment by a physical therapist or other qualified clinician.

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
All your session data is stored locally on your phone via localStorage. It stays on your device — nothing is sent anywhere. On first load, this PFPS rewrite permanently removes the prior misdiagnosis-era history and starts fresh under `rehab-pfps-v1`. After that one-time reset, new PFPS sessions persist normally. If you clear browser data, you lose those sessions.

## Alternative: Cloudflare Pages (also free)
1. Go to https://pages.cloudflare.com
2. Connect your GitHub repo
3. Deploy — same result, slightly faster CDN
