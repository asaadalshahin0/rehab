# Rehab Protocol PWA

Local-only tracker with two independent pathways:

- Right knee: patellofemoral pain syndrome (PFPS), using staged hip- and knee-targeted strengthening.
- Right forearm: chronic pronator teres strain, using comfortable rotation, isometrics, supported pronation loading, longer-lever strengthening, and graded return to work or sport.

Both pathways use symptom-guided load management, daily-life pain tracking, and an always-available flare phase. The content is general education, not a diagnosis or individualized medical plan. Persistent symptoms, loss of function, or possible neurologic symptoms need assessment by a qualified clinician.

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
All your session data is stored locally on your phone via localStorage. It stays on your device — nothing is sent anywhere. Existing PFPS knee progress remains under `rehab-pfps-v1`; the forearm track is added alongside it without resetting knee history. If you clear browser data, you lose those sessions.

## Clinical basis

The forearm progression was authored conservatively from current clinician-facing and patient-education sources:

- [Mass General Brigham rehabilitation protocol for medial/lateral epicondylalgia](https://www.massgeneral.org/assets/MGH/pdf/orthopaedics/sports-medicine/physical-therapy/rehabilitation-protocol-for-medial-lateral-epicondylitis.pdf): pain-free active motion, early isometrics, progressive concentric/eccentric pronation-supination, and criteria-based return to function.
- [AAOS therapeutic exercise program](https://orthoinfo.aaos.org/globalassets/pdfs/a00790_therapeutic-exercise-program-for-epicondylitis_final.pdf): staged forearm pronation/supination from supported/no weight toward longer-lever light loading, advancing only after repeated pain-stable sessions.
- [Frimley Health NHS isometric wrist exercises](https://www.fhft.nhs.uk/patients-and-visitors/patient-information-library/isometric-wrist-exercises): clinician-reviewed blocked pronation and wrist isometrics.
- [NCBI Bookshelf overview of pronator teres anatomy and clinical significance](https://www.ncbi.nlm.nih.gov/books/NBK580564/): distinction between local muscle symptoms and possible median-nerve involvement such as numbness, weakness, or clumsiness.
- [University Hospitals Coventry and Warwickshire hand guidance](https://www.uhcw.nhs.uk/self-care/hand/): worsening pain, grip-affecting tingling/numbness, and urgent sudden loss of power or feeling.

## Alternative: Cloudflare Pages (also free)
1. Go to https://pages.cloudflare.com
2. Connect your GitHub repo
3. Deploy — same result, slightly faster CDN
