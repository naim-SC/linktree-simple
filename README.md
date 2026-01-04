Nimzz Connect - Single File Bio Link Page
A modern, lightweight single HTML file bio link page (Linktree alternative) with embedded CSS and JavaScript. No dependencies, no build tools — just one file ready to customize and deploy.
Live Demo: Open index.html directly (or deploy your own copy)
Features
Real-time clock (Indonesia time zones: WIB/WITA/WIT)
Session runtime counter
Visitor counter (using LocalStorage)
Dark/Light theme toggle (persisted across visits)
WhatsApp links (personal chat, channels, groups)
Social media buttons (Instagram, Twitter/X, GitHub, etc.)
Portfolio/quick actions section
Smooth animations and glassmorphism effects
Fully responsive (mobile-first design)
SEO-friendly meta tags
Zero external dependencies (~20KB total size)
Everything is contained in a single index.html file — perfect for quick personal bio pages.
Quick Start
Download or clone this repo.
Open index.html in your browser — it works instantly offline!
Customize (see below).
Deploy to any static hosting.
No installation required.
Customization
All changes are made directly in index.html.
Personal Info
Edit around lines 180-190:
<img src="YOUR_PHOTO_URL" alt="Nimzz">
<h1>Nimzz</h1>
<p class="bio">Your bio/description here. Passionate developer & creator.</p>
WhatsApp Links
Replace phone numbers (international format, no + or 00):
<a href="https://wa.me/628xxxxxxxxxx" ...>Personal Chat</a>
Social Media Links
Search for href="https:// and replace URLs (around lines 270-320).
Theme Colors
Edit CSS variables at the top (lines 10-20):
:root {
    --primary: #6f42c1;      /* Main color */
    --primary-light: #9d7ddb;
    --primary-dark: #5a32a3;
}
Add/Remove Buttons
Duplicate or delete <a class="btn"> blocks in the links section.
Deployment (1-Click Options)
Platform
Steps
Time
Vercel
Import repo → Deploy (recommended for speed)
~1 min
Netlify Drop
Drag & drop index.html to https://app.netlify.com/drop
~30 sec
GitHub Pages
Settings → Pages → Source: main branch / root → Save
~2 min
Cloudflare Pages
Connect GitHub repo → Build command: none
~2 min
Any static host works — just upload the single file!
Tips
Use a valid image URL for your photo (host on GitHub, Imgur, etc.).
Test on mobile — fully responsive out of the box.
Theme persistence requires browser LocalStorage (doesn't work in incognito without allowance).
License
MIT License — Free to use, modify, and share.
Feel free to fork and make it your own!
�

Made with ❤️ by Nimzz
January 2026 • Version 1.0
�