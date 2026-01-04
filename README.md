# Nimzz Connect

Single-file bio link page — a lightweight Linktree alternative built entirely in one HTML file with embedded CSS and JavaScript.

**Live Preview** (open directly):  
https://raw.githack.com/naim-SC/linktree-simple/main/index.html

## Features

- Real-time Indonesian clock (WIB/WITA/WIT)
- Session runtime and visitor counter (LocalStorage-based)
- Dark/light theme toggle (persisted)
- WhatsApp links (personal, channels, groups)
- Social media and portfolio sections
- Smooth CSS animations and glassmorphism effects
- Fully responsive (mobile-first)
- SEO-friendly with proper meta tags
- Zero external dependencies (~20KB total)

Everything runs in a **single `index.html` file** — no build tools needed.

## Quick Start

1. Download or clone the repo.
2. Open `index.html` in any browser — works offline instantly.
3. Customize (see below).
4. Deploy anywhere.

## Customization

Edit directly in `index.html`:

### Personal Info (~lines 180-190)
```html
<img src="YOUR_PHOTO_URL" alt="Nimzz">
<h1>Nimzz</h1>
<p class="bio">Your short bio here. Developer | Creator | etc.</p>
WhatsApp Links
Use international format (no + or spaces):
<a href="https://wa.me/628xxxxxxxxxx">Personal Chat</a>
Social Links
Replace URLs in the buttons section (~lines 270-320).
Theme Colors (~lines 10-20)
:root {
    --primary: #6f42c1;       /* Main color */
    --primary-light: #9d7ddb;
    --primary-dark: #5a32a3;
}
Add/remove buttons by copying/deleting <a class="btn"> blocks.
Deployment
One-click options (free & instant):
Vercel: Import repo → deploy (fastest edge network)
Netlify Drop: Drag & drop index.html to https://app.netlify.com/drop
GitHub Pages: Settings → Pages → Source: main branch/root
Any static host works — just upload the file
Notes
Photo: Use a direct URL (GitHub raw, Imgur, etc.)
Theme persistence: Requires LocalStorage (disabled in strict incognito)
Tested on desktop, tablet, and mobile
License
MIT License — free to use, modify, and distribute.
�

Made with ❤️ by Nimzz
January 2026 • v1.0
�
```