# Gather — Venue Portfolio

A standalone venue planning dashboard. No installation or build is required.

## Publish with GitHub Pages

1. Create a public repository named `venue-portfolio` on GitHub.
2. Choose **Add file → Upload files** and upload `index.html`, `ashford-pricing.png`, and this README to the repository root. Upload the extracted files, not the ZIP or its enclosing folder. The optional `.nojekyll` file bypasses Jekyll processing.
3. Commit the files to `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/ (root)**, then **Save**.
6. When deployment completes, open the address shown on that Pages screen, normally `https://YOUR-USERNAME.github.io/venue-portfolio/`.

## Edit or preview

Edit `index.html` with your code editor. For a local preview, run `python3 -m http.server 8000` in this folder and open `http://localhost:8000`.

## Data and backups

Shortlists, added venues, checklist answers and budget inputs are saved in each visitor’s browser, not in GitHub. They are not shared across devices or visitors. The **Export workspace** button downloads JSON data, not website source code. Back up data before moving to the GitHub Pages address; browser storage does not migrate between website addresses. This version does not provide a JSON import control.

This package contains the existing dashboard source and pricing image; it does not include any visitor’s browser-saved data. Venue pricing remains subject to the qualifications displayed in the dashboard.

## Files

- `index.html`: layout, styles, JavaScript, and initial venue data
- `ashford-pricing.png`: supplied pricing guide
- `.nojekyll`: optional GitHub Pages setting
- `README.md`: these instructions
