# Quick Deploy to Vercel

## Option 1: Deploy via Vercel Dashboard (Easiest)

1. Go to **https://vercel.com/new**
2. Click **"Import Project"**
3. Select **GitHub** and find `saurabhsoni/strobe-app`
4. Click **Deploy**
5. Done! Your app will be live at `strobe-app.vercel.app`

## Option 2: Deploy via CLI

```bash
# Install Vercel CLI (if not already installed)
npm i -g vercel

# Login to Vercel
vercel login

# Deploy
cd /root/clawd/strobe-app
vercel --prod
```

## Option 3: Deploy to Netlify

1. Go to **https://app.netlify.com/drop**
2. Drag and drop the `/root/clawd/strobe-app` folder
3. Done! Live in seconds

## Option 4: Deploy to GitHub Pages

```bash
cd /root/clawd/strobe-app

# Create gh-pages branch
git checkout -b gh-pages
git push origin gh-pages

# Enable in GitHub repo settings:
# Settings → Pages → Source: gh-pages branch
```

Your app will be live at: `https://saurabhsoni.github.io/strobe-app`

## Test Locally

```bash
cd /root/clawd/strobe-app
python3 -m http.server 8080
```

Open: http://localhost:8080

---

**GitHub Repo**: https://github.com/saurabhsoni/strobe-app

**Features**:
- ⚡ 3 strobe types (Black & White, Colorful, Police)
- ⏱️ 3 frequencies (Fast, Med, Slow)
- 📱 Mobile-optimized with fullscreen
- 👆 Tap to toggle controls

⚠️ **Warning**: Contains rapid flashing lights
