# Veriton Technical Solutions

Static website for Veriton Technical Solutions.

## Structure

All files served by Vercel live in `public/`:

- `public/index.html` is the homepage.
- `public/site.css` contains the shared styles.
- `public/logo.svg` is the site icon and brand mark.
- The remaining HTML files are the legal and error pages.

There is no build step. In Vercel, set the project root to this repository (`VeritonTest`), leave the framework preset as **Other**, and leave the build command empty. Vercel will serve `public/` as the static site directory.
