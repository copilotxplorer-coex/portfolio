# 🚀 Portfolio — Web3 & AI Developer

> Minimal Professional Portfolio Website with Dark Theme

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen) 
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

- 🎨 **Minimal Dark Theme** — Professional & clean design
- ⚡ **Smooth Animations** — Scroll reveal, typing effect, counters
- 📱 **Fully Responsive** — Mobile, tablet & desktop
- 🎯 **Project Filter** — Filter by category (Web3, AI, Web, Game)
- 💡 **Cursor Glow Effect** — Interactive mouse-follow gradient
- 📧 **Contact Form** — Ready to integrate with backend
- 🚀 **One-click Deploy** — GitHub Pages & Railway ready

## 🛠 Tech Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- Express.js (for Railway deployment)
- Font Awesome Icons
- Google Fonts (Inter + JetBrains Mono)

## 📂 Project Structure

```
portfolio-web3-dev/
├── index.html          # Main HTML
├── style.css           # All styles (dark theme)
├── script.js           # Interactions & animations
├── server.js           # Express server (Railway)
├── package.json        # Node.js config
├── Procfile            # Railway process file
├── railway.toml        # Railway config
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

---

## 🚀 Deployment Guide

### Option 1: GitHub Pages (Free Static Hosting)

```bash
# 1. Create GitHub repo
git init
git add .
git commit -m "🚀 Initial portfolio deploy"

# 2. Create repo on GitHub, then push
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main

# 3. Enable GitHub Pages
# Go to: Settings → Pages → Source → Deploy from branch → main → / (root) → Save
# Your site: https://YOUR_USERNAME.github.io/portfolio/
```

### Option 2: Railway (Node.js Server)

```bash
# Method A: Railway CLI
npm install -g @railway/cli
railway login
railway init
railway up

# Method B: GitHub Integration
# 1. Push code to GitHub (see above)
# 2. Go to https://railway.app
# 3. New Project → Deploy from GitHub Repo
# 4. Select your repo → Deploy
# Railway auto-detects Node.js and runs `npm start`
```

### Option 3: Local Development

```bash
# Install dependencies
npm install

# Start server
npm start

# Open http://localhost:3000
```

---

## 🎨 Customization

### Update Personal Info
Edit `index.html`:
- Change name, title, description
- Update project cards with your real projects
- Replace social links & email
- Modify work experience timeline

### Change Theme Colors
Edit `style.css` `:root` variables:
```css
:root {
    --accent: #6c63ff;        /* Main accent color */
    --gradient: linear-gradient(135deg, #6c63ff, #3b82f6, #06b6d4);
}
```

### Add Real Project Images
Replace `<div class="project-placeholder">` with:
```html
<img src="your-image.jpg" alt="Project Name">
```

---

## 📄 License

MIT License — Free to use and modify.

---

**Built with ♥ by Aisarayut K.**
