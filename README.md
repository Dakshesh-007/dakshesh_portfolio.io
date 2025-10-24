# Dakshesh T — Junior Data Scientist Portfolio

Hey — I'm Dakshesh. This is the source for my personal portfolio website where I share my projects, skills, education, and contact details. It's a lightweight, responsive single-page site built with semantic HTML and modern CSS — easy to host on GitHub Pages.

Live demo
- Hosted via GitHub Pages (if enabled): https://Dakshesh-007.github.io/dakshesh_portfolio.io

What’s in this repo
- index.html — main single-page portfolio.
- assets (optional) — images like `profile2.jpg` and other static files.
- styles are embedded in `index.html` for simplicity; everything needed to run is in that file.

Why this project
- A clean, modern portfolio to showcase data science projects, experience, and contact info.
- Built to be simple to edit and deploy quickly (ideal for GitHub Pages).

Tech stack
- HTML5
- CSS (modern layout and animations)
- Font Awesome for icons
- Google Fonts (Inter)

Quick local preview
Option A — VS Code (recommended)
1. Open the repo in VS Code.
2. Install and use the "Live Server" extension.
3. Click "Go Live" to preview the site.

Option B — Simple Python server
1. From the repo root, run:
   - Python 3: `python -m http.server 8080`
2. Open http://localhost:8080 in your browser.

How to customize (fast)
- Change the name or title: edit the `<title>` tag and `.logo` text in `index.html`.
- Replace profile image: swap `profile2.jpg` with your new image (same filename), or update the `<img src="">` path.
- Update links: edit the social links in the header (`linkedin`, `github`, email/contact cards).
- Add projects: find the Projects section in `index.html` and add/remove `.project-card` blocks. Use the modal data attributes to link the modal button to each project.

Tips for editing content
- All the styling is inline in `index.html` inside a `<style>` block. You can split it into a separate CSS file (`styles.css`) if you prefer.
- The theme toggle uses a `.dark-mode` class on `<body>` — adjust to change defaults or persist user preference with localStorage.
- Keep icons with Font Awesome classes (already included via CDN).

Accessibility & performance notes
- Images use `object-fit: cover` for consistent appearance. Add `alt` text to images where needed.
- If you add many projects, consider lazy-loading images (`loading="lazy"`) to improve initial load time.

Deploying to GitHub Pages
1. Push this repo to GitHub.
2. In repository Settings → Pages, choose the `main` branch and `/ (root)` folder.
3. Wait a minute and visit `https://<your-username>.github.io/dakshesh_portfolio.io`.

Contact
- LinkedIn: https://linkedin.com/in/dakshesht
- GitHub: https://github.com/Dakshesh-007
- Email: add your email into the contact section in `index.html` (or link a mailto: there)

License
This repo is open — use it freely and make it your own. I recommend adding a LICENSE file (MIT) if you want an explicit license.
