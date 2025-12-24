# Dark War Text Generator

A simple static HTML page for generating text.

## Deployment to Cloudflare Pages

This is a static HTML site that can be deployed directly to Cloudflare Pages.

### Files Required for Deployment

- `index.html` - Your main HTML file
- `wrangler.toml` - Configuration file that tells Cloudflare to serve static assets
- `package.json` - Basic package file (optional but helps with build process)

### Deploy Instructions

1. **Commit and push these files to GitHub:**
   ```bash
   git add .
   git commit -m "Add Cloudflare Pages configuration"
   git push
   ```

2. **Cloudflare will automatically deploy** - The `wrangler.toml` file configures the deployment to serve your static HTML files.

### Alternative: Remove Build Command

If you prefer not to use `wrangler deploy`, you can:
1. Go to Cloudflare Dashboard → Pages → Your Project
2. Navigate to **Settings** → **Builds & deployments**
3. Clear the **Build command** field (leave it empty)
4. Save changes

