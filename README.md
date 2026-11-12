# Etsy Crochet Pattern Intelligence — GitHub Pages website

This is the standalone static website for an independent private crochet pattern research project. It uses plain HTML, CSS, JavaScript, and a locally stored SVG mark. It has no backend, API calls, external runtime dependencies, API keys, or database access.

## Preview locally

Open `index.html` directly in a browser, or start a simple local server from this folder:

```powershell
cd "D:\ETSY INTEKGENCY-CODEX -PROJECT\etsy-crochet-intelligence\github-website"
py -m http.server 8000
```

Then visit `http://localhost:8000`. Press `Ctrl+C` in PowerShell to stop the local server.

## Publish with GitHub Pages

1. Sign in to GitHub and select **New repository**.
2. Choose a repository name, for example `etsy-crochet-pattern-intelligence`. For a private research project, choose **Private** unless you intend the site files to be public. GitHub Pages availability for private repositories depends on your GitHub plan and organization settings.
3. Create the repository. You can initialize it with a README or leave it empty.
4. Open this `github-website` folder on your computer. Upload its **contents** to the root of the GitHub repository: `index.html`, `style.css`, `script.js`, `.nojekyll`, `README.md`, and the `assets` folder containing `logo.svg`. Keep the folder structure intact.
5. On GitHub, open the repository and select **Settings → Pages**.
6. Under **Build and deployment**, set **Deploy from a branch**. Select the branch containing the files (usually `main`) and the `/(root)` folder, then select **Save**.
7. Wait for the Pages deployment to finish. The Pages settings page will show the published HTTPS URL. A project site commonly has the form `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`; use the exact URL GitHub displays.

You can also publish by pushing the contents of this folder to a Git repository rather than using the browser upload interface. Do not upload the parent research project's database, API credentials, or unrelated files to the website repository.

## Update the site later

Edit the HTML, CSS, JavaScript, or files under `assets`, then upload or commit and push the changed website files to the same branch. GitHub Pages automatically rebuilds the site after each update. Check the Actions or Pages area for deployment status.

## Before publishing

- Replace `hello@your-domain.example` in `index.html` with an email address you control, or change the contact text/link.
- The website uses no Etsy branding. Keep the independent-project disclaimer in the footer.
- The site contains no Etsy API keys, secrets, database connections, or backend functionality.
- GitHub Pages publishes static site files to visitors. Do not add private project data to this folder.

## Files

- `index.html` — accessible page structure and metadata
- `style.css` — responsive design and reduced-motion support
- `script.js` — mobile navigation, footer year, and light reveal animation
- `assets/logo.svg` — original crochet-inspired project mark
- `.nojekyll` — disables Jekyll processing for direct static file delivery
