# hex-forge Website

Landing page and privacy policy for the hex-forge iOS app.

**Live:** https://hex-forge.hexul.com

## Pages

- `/` - Landing page with app icon and App Store link
- `/privacy.html` - Privacy policy (required for App Store)
- `/beta-terms.html` - Beta testing license agreement

## Design

Theme inspired by the app icon:

| Element | Color |
|---------|-------|
| Background | Deep purple radial gradient (`#1a0a2e` to `#0d0517`) |
| Text | Light purple (`#f0e6ff`) |
| Headings | Gold metallic gradient (`#f5e6a3` to `#cd7f32`) |
| Accent | Gold (`#d4af37`) |
| Glow | Purple (`#8b5cf6`) |

Features:
- Animated purple glow on app icon
- Glassmorphism card for privacy policy
- Responsive design
- Favicon and Apple touch icon

## Hosting

- **Platform:** GitHub Pages
- **Domain:** hex-forge.hexul.com (CNAME)
- **SSL:** Automatic via GitHub

## DNS Setup

Add this record to your domain:

| Type | Name | Value |
|------|------|-------|
| CNAME | hex-forge | hex.github.io |

## Local Development

```bash
# Preview locally
python3 -m http.server 8000
open http://localhost:8000
```

## Deployment

Push to `main` branch. GitHub Pages auto-deploys.

```bash
git add .
git commit -m "Update"
git push
```

## Files

```
hex-forge-web/
├── index.html           # Landing page
├── privacy.html         # Privacy policy
├── beta-terms.html      # Beta testing agreement
├── style.css            # Styles
├── icon.png             # App icon (1024x1024)
├── app-store-badge.svg  # Official App Store badge
├── CNAME                # Custom domain config
└── README.md
```
