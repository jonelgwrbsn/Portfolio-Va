# Jonel Garban Portfolio — Vercel deployment

This folder is ready to deploy as a static Vercel site.

## CV action

The original CV PDF is unavailable, so every CV button now opens a pre-filled email asking Jonel for the latest CV. This prevents a broken download page.

To restore a direct download later, add the real PDF to this folder and update the CV link in `index.html`.

## Deploy

1. Upload this folder to a GitHub repository.
2. In Vercel, select **Add New → Project** and import that repository.
3. Choose the **Other** framework preset.
4. Leave the build command and output directory empty, then deploy.

Vercel serves `index.html` automatically and includes the `portfolio-assets` screenshots at their existing paths.
