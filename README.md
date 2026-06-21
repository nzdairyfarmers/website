NZ Dairy Farmers — Static website for Cloudflare Pages

This repository now contains a small static site you can deploy to Cloudflare Pages.

Included files:
- index.html
- about.html
- contact.html
- styles.css
- assets/logo.svg

Deploy to Cloudflare Pages:
1. Go to Cloudflare dashboard → Pages → Create a project.
2. Connect your GitHub account and choose the repository: nzdairyfarmers/website.
3. For a simple static site use:
   - Framework preset: None
   - Build command: leave empty
   - Build output directory: (leave empty or set to "/")
4. Create the project and deploy. Cloudflare will publish the site from the repository root.

Notes:
- If you want the site on a branch other than the default, configure the Pages project to use that branch.
- Edit the files in the repository to update content; Cloudflare Pages redeploys on each push.
