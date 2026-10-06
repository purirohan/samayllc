# Samay LLC website

https://samay.llc, built by GitHub Pages with Jekyll (no local build step needed).

| Path | Page |
|---|---|
| `/` | Home |
| `/apps/` | Apps |
| `/consulting/` | Consulting |
| `/about/` | About, with company details |
| `/contact/` | Contact |
| `/privacy/` | Website privacy policy |
| `/snaprecaller/` | SnapRecaller site, copied from the app repo (`AppStore/website/`); the App Store Marketing URL |
| `/snaprecaller/support.html`, `/snaprecaller/privacy.html` | App Store Support and Privacy Policy URLs |
| `/brand/` | Logo files |

- `_layouts/default.html` holds the shared header menu and footer, and `_includes/logo.svg` holds the logo.
- `assets/site.css` styles the company pages; the SnapRecaller pages keep their own stylesheet.
- Every page has `<meta name="robots" content="noindex">`, so search engines leave it out.
- To preview locally: `jekyll build`, then serve `_site/`.
