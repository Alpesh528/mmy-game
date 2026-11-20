# MMY Game Information Website

Static, responsive five-page website for `mmyapk.com`, inspired by the provided IC7 screenshot (not a clone).

## Pages
- `index.html` — Homepage
- `about.html` — About Us
- `privacy-policy.html` — Privacy Policy
- `disclaimer.html` — Disclaimer
- `faq.html` — FAQ

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this directory and visit http://localhost:8000.

## Deploy to GitHub and Vercel
1. Create a GitHub repository.
2. Upload all files and the `assets/` folder to the repository root.
3. In Vercel, import the GitHub repository and choose Framework Preset **Other**. No build command is required.
4. Connect `mmyapk.com` in Vercel project settings, then apply the DNS records shown in that project's domain settings.

## Before publishing
- Replace illustrative SVG assets with images you own or have permission to use, if desired.
- Verify whether the site owner has permission to use the MMY Game name and logo.
- Confirm any official APK URL before adding a direct download button. Currently buttons point to the on-page download guidance.
- Verify privacy policy against actual hosting, analytics, cookies and contact methods.
- Review local legal requirements, especially for real-money gaming.
- If canonical URLs redirect to www or use trailing slashes, update them consistently.
