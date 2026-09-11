# Kodchi Studio — Official Website

Static HTML + CSS + JavaScript site designed for GitHub Pages.

## Files

- `index.html` — main page
- `style.css` — all styling and responsive layout
- `script.js` — language switcher, localStorage, menu, lightbox and GitHub configuration
- `logo.png` — optional logo (replace the placeholder if you have one)
- `favicon.ico` — optional favicon
- `KodchiStudio.exe` — place the real Windows executable here
- `assets/` — optional screenshots/assets

## Important

The download buttons already point directly to:

`KodchiStudio.exe`

No external download service is used.

### GitHub

Open `script.js` and change:

`const GITHUB_URL = "https://github.com/your-username/kodchistudio";`

to the real repository URL.

## GitHub Pages

1. Create a GitHub repository.
2. Upload all website files to the repository root.
3. Put `KodchiStudio.exe` in the same root directory as `index.html`.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select your main branch (usually `main`) and `/ (root)`.
7. Save and wait for deployment.

## Screenshots

You can later replace the placeholder gallery cards with real images in `assets/`.
For example:
- `assets/screenshot1.png`
- `assets/screenshot2.png`
- `assets/screenshot3.png`

Then update the corresponding gallery HTML in `index.html`.

## SEO

The site includes title, description and Open Graph metadata. For Google discovery, submit the deployed site to Google Search Console and keep publishing/updating useful official content. A custom domain can also help establish a stable official web address.
