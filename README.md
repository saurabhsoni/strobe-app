# Strobe Light Web App

A full-screen strobe light app with customizable colors and frequencies.

## Features

### Strobe Types
- **Black & White** - Classic alternating strobe
- **Colorful** - Rainbow cycling (7 colors)
- **Police** - Red and blue alternating

### Frequencies
- **Fast** - 0.1 seconds (10 flashes/sec)
- **Medium** - 0.5 seconds (2 flashes/sec)
- **Slow** - 1 second (1 flash/sec)

### Controls
- Tap screen to show/hide controls while strobing
- Touch-optimized for mobile
- Auto-fullscreen on mobile devices

## Local Testing

```bash
cd /root/clawd/strobe-app
python3 -m http.server 3001
```

Open http://localhost:3001

## Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd /root/clawd/strobe-app
vercel --prod
```

Or push to GitHub and connect to Vercel for auto-deployment.

## Warning

⚠️ **Photosensitivity Warning**: This app produces rapid flashing lights that may trigger seizures in people with photosensitive epilepsy. Use with caution.
