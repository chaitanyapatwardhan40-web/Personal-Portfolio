# Chaitanya Patwardhan — portfolio site

A static site: no build step, no framework, one HTML file.

Live: https://personal-portfolio-azure-three-88.vercel.app/
Repo: https://github.com/chaitanyapatwardhan40-web/Personal-Portfolio

| File | What it is |
|---|---|
| `index.html` | The whole site (screenshots and videos are embedded inside it). Must keep this exact name. |
| `Chaitanya_Patwardhan_Resume.pdf` | Linked from the "Résumé (PDF)" button. Replace it when your résumé changes, keep the filename. |
| `og-image.png` | The 1200×630 preview card LinkedIn shows when the link is shared. |
| `vercel.json` | Clean URLs and caching headers for Vercel. |
| `images/` | Source files kept for editing; not needed by the page. |

## Updating the site

Edit `index.html` (or replace it), then on GitHub: **Add file → Upload files**, drag the changed file(s) in, **Commit changes**. Vercel redeploys within a minute.

## If the Vercel project is renamed

The `<head>` of `index.html` has `og:url`, `og:image`, `twitter:image` and a `canonical` link pointing at the live address (look for the `SITE URL` comment). Update those four tags to the new address and re-upload, otherwise LinkedIn cannot load the preview card. Then paste the link into https://www.linkedin.com/post-inspector/ to refresh LinkedIn's cache.

## LinkedIn

Add the site URL under Contact info → Website, in the Featured section, and mention it in About.
