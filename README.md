# TideOrigin

A responsive static version of the existing TideOrigin site, prepared for GitHub Pages.

## Publish

In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/ (root)**. No dependencies or build step are needed.

The three views are `?page=home`, `?page=about`, and `?page=contact`, so all links work under a GitHub Pages project path and on a custom domain.

## Branding and content

- Edit `index.html` to update the text and email address.
- To add a logo, upload it under `assets/` and replace the header and footer brand text with an image. Keep `alt="TideOrigin"`.
- The ocean image currently uses the same external image URL as the existing tideorigin.com site. Its availability depends on that image host. For independent hosting, save an authorized copy into `assets/` and update the image path.
- The contact form opens the visitor's email client. The visitor must send the prepared email; there is no server-side message collection or simulated success message.

## Custom domain

The existing tideorigin.com deployment is not changed by creating this repository. Only switch DNS and add the Pages custom domain after the GitHub Pages URL is verified and a domain migration is intended.
