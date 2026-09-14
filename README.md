# NetWerk

A clean, one-page social media hub. Quick access to Facebook, Instagram, YouTube, TikTok, WeChat, and Telegram.

## Features

- Responsive grid (2 columns on mobile, 3 on larger screens)
- Official platform icons via Font Awesome
- “Open” links that open each platform in a new tab
- Privacy Policy, Terms of Use, and Terms & Conditions modals
- Modern dark theme with subtle gradients

## Deploy on Netlify

1. Push this folder to a GitHub repository (or drag-and-drop the folder on [Netlify Drop](https://app.netlify.com/drop)).
2. In Netlify: **Add new site → Import an existing project** (or use the drop zone).
3. Build settings can be left empty — this is a static site (no build command needed).
4. Publish directory: leave as root (or `/` if prompted).
5. Deploy. Your site will be live in seconds.

## Deploy on Render

1. Create a new **Static Site** on [Render](https://render.com).
2. Connect your Git repository (or upload the files).
3. Build Command: leave empty (or `echo "Static site"`).
4. Publish Directory: `.` (root of the project).
5. Deploy.

## Local preview

Just open `index.html` in a browser, or serve the folder with any static server:

```bash
npx serve .
```

## Files

- `index.html` – structure
- `styles.css` – styling
- `script.js` – modal logic for legal pages
