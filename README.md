# Sky Web Solutions — PHP frontend matched GitHub Pages edition

This package copies **index.html, styles.css and app.js from the previously prepared PHP version**, retaining its appearance and interactions. Only root-relative asset paths and the PHP-dependent contact submission are adapted for static hosting.

## Publish
1. Create a public GitHub repository named `sky-web-solutions`.
2. Upload **all files from this ZIP directly into the repository root**, including `.github/workflows/deploy.yml` (do not upload the ZIP itself).
3. Use the `main` branch.
4. In Settings > Pages, select **GitHub Actions**.
5. Check Actions for a successful deployment. Your site should appear at `https://YOUR-USERNAME.github.io/sky-web-solutions/`.

## Limitations
GitHub Pages cannot run PHP. The contact form now opens the visitor's email application; they must press Send. All other PHP frontend visuals and demos are preserved. If you require server-side email, host the PHP package on a PHP-enabled server instead.
