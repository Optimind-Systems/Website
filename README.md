# Optimind Systems — Website

Static marketing site (plain HTML/CSS, no build step). Pages: `index.html` (Home), `services.html` (What We Do), `about.html` (About), `contact.html` (Contact).

## Publish to GitHub Pages

1. Create a new repository on GitHub (e.g. `optimind-site`).
2. Upload **all files in this folder** (including the `assets/` folder and the hidden `.nojekyll` file) to the repo root — either drag-and-drop in the GitHub web uploader or:
   ```
   git init
   git add .
   git commit -m "Publish Optimind site"
   git branch -M main
   git remote add origin https://github.com/<you>/optimind-site.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch **main**, folder **/(root)**, then **Save**.
5. Your site goes live at `https://<you>.github.io/optimind-site/` within a minute or two.

## Custom domain (optional)

In **Settings → Pages → Custom domain**, enter your domain (e.g. `optimindsystems.com`) and add the DNS records GitHub shows you at your registrar.

## Notes

- The client case study is anonymized ("a U.S. small-business lender"). Confirm the published figures before going live.
- The Contact page currently uses an email link (`mailto:`). To add a submitting form later, a service like Formspree works with static hosting.
