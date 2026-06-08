# VAMMalawiApp Landing Page

This is a minimal Bootstrap landing page for VAMMalawiApp. It provides download links for Android (APK) and iOS (App Store) and uses a dark theme with green buttons.

Files added:

- `index.html` — main landing page using Bootstrap CDN and `css/styles.css`.
- `css/styles.css` — custom styles (dark background, green buttons).

Placeholders and notes:

- The Android download link points to `/downloads/vammalawiapp.apk`. Replace this with your real APK path or a hosted URL.
- The App Store link is a placeholder `https://apps.apple.com/app/idXXXXXXXXX` — replace with your app's real App Store URL.
- A simple SVG phone mockup is used instead of image assets. Swap with real screenshots in `assets/` if desired.

How to preview locally:

1. Open `index.html` in a browser (double-click or run a simple static server). Example using Python 3 in the project directory:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Deployment:

- Host the site on any static hosting provider (Netlify, Vercel, GitHub Pages) or a simple web server.
- Make sure to upload the APK to your server if you want direct downloads, or point the Android button to a hosted URL.

Customization ideas:

- Add real screenshots in `assets/` and update `index.html`.
- Wire up analytics, terms/privacy links, or platform badges.
