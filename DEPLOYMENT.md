# Farvez Portfolio Deployment

## Public HTML

Upload `parvez-portfolio-public-live-version.html` and the complete `assets` folder to the same web root. Rename the HTML file to `index.html` when the host requires a default entry page.

Works with cPanel/public_html, shared hosting, GitHub Pages, Netlify Drop, Cloudflare Pages, Firebase Hosting, Amazon S3, and similar static hosts.

## Public React

- Install: `pnpm install`
- Build: `pnpm build`
- Output directory: `dist`

Vercel and Netlify can detect the Vite project automatically. For another host, upload the generated `dist` directory.

## Editable Version

Keep the editable HTML or editable React project private. It includes local editing, color controls, save, photo replacement, and HTML export. Publish the exported public version for visitors.

## Assets

Do not separate or rename the `assets` directory. The map, project images, technology logos, fonts, and interface graphics use relative paths for domain-independent deployment.
