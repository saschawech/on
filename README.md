# ON - Self-Hosted Website

This is a self-hosted website, no longer dependent on Webflow's CDN or infrastructure.

## Structure

- `*.html` - Website pages (index, 401, 404, datenschutz, impressum, home-copy)
- `css/` - All CSS files (normalize, webflow, custom site styles)
- `js/` - JavaScript files (jQuery, webflow)
- `images/` - Images and icons
- `fonts/` - Custom fonts

## Running Locally

You can serve this site using any static web server. For example:

### Using Python:
```bash
python3 -m http.server 8000
```

### Using Node.js:
```bash
npx serve
```

### Using PHP:
```bash
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

Upload all files to any static hosting provider:
- GitHub Pages
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any traditional web server (Apache, Nginx, etc.)

## Assets

All assets are self-contained:
- CSS: normalize.css, webflow.css, on-workspace.webflow.css
- JavaScript: jQuery 3.5.1, webflow.js
- Images: Team photos, backgrounds, icons (favicon, webclip, LinkedIn, etc.)
- Fonts: TWKEverett family (Bold, Light, Medium, Regular)

No external dependencies or CDN links required.
