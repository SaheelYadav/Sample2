# Lumiza Creations Website

A responsive, single-page static website for Lumiza Creations.

## Deploy to Cloudflare Pages

This repository is ready for Cloudflare Pages as a static HTML site. No framework build step is required.

1. In the Cloudflare dashboard, open **Workers & Pages**.
2. Choose **Create application** → **Pages** → **Connect to Git**.
3. Connect/authorize GitHub if Cloudflare shows **Missing git connection**.
4. Select `SaheelYadav/Sample2` and the `main` branch.
5. Set the build configuration:
   - **Framework preset:** None
   - **Build command:** leave empty
   - **Build output directory:** `/` (repository root)
6. Save and deploy.

The entry point is `index.html` at the repository root. Every new commit to `main` can trigger a new deployment once the Git integration is connected.

## Notes

- Google Fonts and some image assets are loaded from external URLs, so those resources require internet access.
- The enquiry form prepares a WhatsApp message in the browser; it does not submit to a server or store enquiries in a database.
- Review placeholder imagery, awards, partner logos, and contact details before public launch.
