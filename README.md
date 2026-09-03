# Veriton Technical Solutions

Static website for Veriton Technical Solutions. The site is intentionally dependency-free and can be hosted directly from GitHub Pages or any static file host.

## Structure

- `index.html` - the homepage and primary site content
- `404.html` - fallback page for unknown routes
- `Public/` - local images, icons, and other static assets
- `.gitignore` - local and generated files excluded from Git

## Run locally

Open `index.html` directly in a browser, or serve the repository root with any static HTTP server. For example, with Python installed:

```text
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing these files and the `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the site.

The homepage must remain named exactly `index.html` in lowercase because GitHub Pages uses a case-sensitive filesystem.
