# Kathryn James McGraw — personal website

A static academic website ready for free hosting on GitHub Pages. No paid site builder is required. The only optional cost is a custom domain.

## Publish on GitHub Pages

1. Create a GitHub account if needed.
2. Create a new **public** repository, such as `kathryn-james-mcgraw`.
3. Upload every file and folder in this package to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)`, then click **Save**.
7. GitHub will publish the site at `https://YOUR-USERNAME.github.io/kathryn-james-mcgraw/`.

For the cleanest free address, name the repository `YOUR-USERNAME.github.io`. GitHub then publishes it at `https://YOUR-USERNAME.github.io/`.

## Connect a custom domain

After purchasing a domain such as `kathrynjamesmcgraw.com`:

1. In **Settings → Pages**, enter the domain under **Custom domain**.
2. Follow GitHub's DNS instructions at your domain registrar.
3. Enable **Enforce HTTPS** after GitHub verifies the DNS records.

GitHub Pages hosting is free. A `.com` domain usually has an annual registration and renewal fee set by the registrar.

## Replace the CV

Replace this file:

`files/Kathryn_James_McGraw_CV.pdf`

Keep the same filename and all links will continue working. If you use a different filename, update that filename in `index.html`, `research.html`, and `cv.html`.

## Replace the headshot

Replace:

`assets/headshot.jpg`

Keep the same filename, or update the image path in `index.html` and `about.html`.

## Edit text

- Homepage: `index.html`
- Research: `research.html`
- About: `about.html`
- CV page: `cv.html`
- Colors, spacing, fonts, and hover effects: `styles.css`

## Fonts

The website loads Cormorant Garamond for headings and Spectral for body text through Google Fonts. Both are free. If Google Fonts cannot load, the site falls back to Georgia.

## Color palette

- Navy: `#13294B`
- Red: `#CE1126`
- Dark red hover: `#A80D20`
- Warm ivory background: `#FBF9F5`
- Charcoal text: `#2D2A26`
- Warm gray borders: `#DDD8CF`
