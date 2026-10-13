# Yongfeng Global Trading — Custom Sportswear & Team Jerseys

Responsive English-first B2B catalogue built with plain HTML, CSS and JavaScript. No build step or server is required.

## Included
- Mobile-responsive layout and navigation
- Six editable product entries, category filters and product-detail modal
- Email enquiry form that creates a `mailto:` draft
- Optional WhatsApp shortcut
- Basic SEO and social metadata
- Local SVG placeholder illustrations

## Before publishing
1. Edit `products.js`.
2. Put your real business email in `email`.
3. Put your real WhatsApp number in `whatsapp` in international format, digits only (country code + number). Leave blank if not ready.
4. Review product copy and replace the SVG illustrations with your own product photos when available.
5. After publishing, optionally set `websiteUrl` to the final URL.

The contact details are intentionally blank. The form does not save submissions to a server; it opens the visitor's email application, so it needs a configured recipient email and an email app. For server-side form submissions, connect a form service later.

Illustrations and product data are placeholders. They do not imply verified stock, certifications, MOQ, delivery times, or performance specifications.

## Deploy with GitHub Pages
1. Sign in to GitHub and create a new repository, e.g. `evercrest-sportswear`.
2. For GitHub Free, use a **Public** repository for GitHub Pages.
3. Unzip this package on your computer.
4. In the repository, choose **Add file → Upload files**.
5. Upload the **contents** of the unzipped folder, not the enclosing folder. `index.html` must be at the repository root.
6. Commit to branch `main`.
7. Go to **Settings → Pages**.
8. Under **Build and deployment**, select **Deploy from a branch**.
9. Select branch `main` and folder `/(root)`, then click **Save**.
10. Wait for deployment; the published address appears in Settings → Pages.

Typical project-site URL: `https://YOUR-GITHUB-USERNAME.github.io/evercrest-sportswear/`. Use the actual URL shown by GitHub, not this example.

## Files
- `index.html`: content and SEO
- `styles.css`: design and responsive styles
- `products.js`: contact settings and product catalogue
- `script.js`: filters, modal, navigation, and enquiry behavior
- `assets/images/`: logo and local placeholder illustrations
