# Clear-cut-ai
# ClearCut AI

AI background remover that runs entirely in the browser. Ships as a **web app** (PWA) and an **Android APK** via Capacitor.

## Features

- 🔐 **Sign Up / Log In** — accounts stored locally in IndexedDB
- 🖼️ **Image history** — saved on device, only visible to the user
- 🤖 **Real AI** — RMBG-1.4 via Transformers.js (no API key)
- 🌓 **Dark mode** — respects system preference
- 📱 **Responsive** — mobile, tablet, desktop
- 📦 **PWA** — installable, works offline after first load
- 🤖 **Android APK** — built automatically via GitHub Actions

## Local Development

```bash
npm install
npm run serve
# open http://localhost:3000
# 1. Fur workflow-ga
nano .github/workflows/main.yml

# 2. Ku beddel file-ka kore

# 3. Save, commit, push
git add .github/workflows/main.yml
git commit -m "Fix: replace setup-android with sdkmanager"
git push
