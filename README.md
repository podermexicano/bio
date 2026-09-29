# Jose Aparicio — Personal Website

A responsive three-page static portfolio for Jose Aparicio.

## Pages

- `index.html` — home and profile links
- `science.html` — scientific work and publication profiles
- `art.html` — Jovial Jar art practice and links

## Preview locally

Open `index.html` directly in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository and upload **the contents of this folder** to the repository root. `index.html` should appear at the top level of the repository—not inside another folder.
2. Commit the files to the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will publish the site at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` after a short build.

All internal links are relative, so the site works both at a GitHub user domain and within a repository subdirectory. The included `.nojekyll` file tells GitHub Pages to serve the files directly without Jekyll processing.

## Publish with another web host

Upload all files in this folder to the host's public web directory. Keep the files together so the links to `styles.css` and `script.js` continue to work.

The site uses Google Fonts when online and falls back to system sans-serif fonts if they are unavailable.

## Photography credits

- Homepage portrait supplied by Jose Aparicio.
- Science portrait from Jose Aparicio's ResearchGate profile.
- Ceramics table and exhibition display images from Jovial Jar.

The ResearchGate and Jovial Jar images are loaded from their original published sources; an internet connection is required for them to display. Source links are included in the visible captions on the site.
