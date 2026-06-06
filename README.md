# QR Studio — GitHub Pages Website

A complete, lightweight, static website for the **QR Studio** mobile app (QR Scanner, QR Generator & Barcode Generator), built entirely with Markdown + Jekyll and ready to deploy on GitHub Pages.

## ✨ Features

- 100% static — no backend, no database, no analytics, no ads
- Mobile-friendly responsive design
- Dark mode support (auto-detect)
- SEO-friendly meta tags (via `jekyll-seo-tag`)
- Clean, professional typography
- Easy to customize — edit `.md` files only

## 📁 Folder Structure

```
.
├── _config.yml              # Jekyll / GitHub Pages config
├── _layouts/
│   └── default.html         # Base HTML layout
├── _includes/
│   ├── header.html          # Site header + nav
│   └── footer.html          # Site footer
├── assets/
│   ├── css/
│   │   └── style.css        # All site styles
│   └── images/              # Screenshots, badges, favicon
│       ├── favicon.png
│       ├── google-play-badge.svg
│       ├── app-store-badge.svg
│       ├── screenshot-scanner.png
│       ├── screenshot-generator.png
│       ├── screenshot-history.png
│       ├── screenshot-share.png
│       ├── screenshot-settings.png
│       └── screenshot-barcode.png
├── index.md                 # Home page
├── features.md              # Features page
├── privacy-policy.md        # Privacy policy
├── support.md               # Support / FAQ
├── changelog.md             # Release notes
├── README.md                # This file
├── Gemfile                  # Optional, for local development
└── LICENSE                  # MIT License
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `qrstudio.github.io` for a user/org site, or any name for a project site).
2. Push all the files from this folder to the `main` branch.
3. In your repo, go to **Settings → Pages**.
4. Under **Source**, choose `Deploy from a branch` and select `main` / `(root)`.
5. Wait a minute or two — your site will be live at the URL GitHub shows you.

That's it. No build step required.

## 🛠 Local Development (optional)

If you want to preview changes locally:

```bash
# Requires Ruby + Bundler
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## ✏️ Customization Checklist

Before going live, replace the following placeholders:

- [ ] `jayshah881994@gmail.com` — your real support email
  (in `index.md`, `features.md`, `privacy-policy.md`, `support.md`, `changelog.md`, `_config.yml`, `_includes/footer.html`)
- [ ] Google Play badge & link in `index.md` (and store SVG in `assets/images/`)
- [ ] App Store badge & link in `index.md` (and store SVG in `assets/images/`)
- [ ] Screenshots in `assets/images/` and `index.md`
- [ ] Favicon in `assets/images/favicon.png`
- [ ] `url` and `baseurl` in `_config.yml` (if using a project site, set `baseurl: "/your-repo-name"`)

## 📄 Pages Included

| Page | File | Description |
|------|------|-------------|
| Home | `index.md` | Hero, features, download buttons, screenshots |
| Features | `features.md` | Detailed feature breakdown |
| Privacy Policy | `privacy-policy.md` | Full privacy policy |
| Support | `support.md` | FAQ, troubleshooting, contact |
| Changelog | `changelog.md` | v1.0.0, v1.1.0, v2.0.0 release notes |

## 📜 License

MIT — see [LICENSE](LICENSE).
# QRCodeWEB
