# ClearCut AI

AI background remover that runs entirely in the browser. Ships as a **web app** (PWA) and an **Android APK** via Capacitor.

## Features

- Sign Up / Log In — accounts stored locally in IndexedDB
- Image history — saved on device, only visible to the user
- Real AI — RMBG-1.4 via Transformers.js (no API key)
- Dark mode — respects system preference
- Responsive — mobile, tablet, desktop
- PWA — installable, works offline after first load
- Android APK — built automatically via GitHub Actions

## Local Development

```bash
npm install
npm run serve
# open http://localhost:3000
npx cap add android
npx cap sync android
npm run build:apk
# APK at android/app/build/outputs/apk/debug/app-debug.apk

---

## 🚀 Tallaabooyinka Dhameystiran

**1. Samee folder-ka:**
```bash
mkdir Clear-cut-ai && cd Clear-cut-ai
mkdir -p www .github/workflows
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/victordev252-cloud/Clear-cut-ai.git
git push -u origin main --force
