# App Images

Drop your app's images into this folder. The Markdown pages reference the following files:

## Required for production

| File | Used in | Purpose |
|------|---------|---------|
| `favicon.png` | All pages (via `_layouts/default.html`) | Browser tab icon |
| `google-play-badge.svg` | `index.md` | Google Play download button |
| `app-store-badge.svg` | `index.md` | App Store download button |
| `screenshot-scanner.png` | `index.md` | Scanner screen screenshot |
| `screenshot-generator.png` | `index.md` | Generator screen screenshot |
| `screenshot-history.png` | `index.md` | History screen screenshot |
| `screenshot-share.png` | `index.md` | Share screen screenshot |
| `screenshot-settings.png` | `index.md` | Settings screen screenshot |
| `screenshot-barcode.png` | `index.md` | Barcode screen screenshot |

## Free badge sources

- Google Play badge: <https://play.google.com/intl/en_us/badges/>
- App Store badge: <https://developer.apple.com/app-store/marketing/guidelines/#section-badges>

After dropping the files in this folder, no other changes are required — the `.md` files already point to the right relative paths.
