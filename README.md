# meep-public-pages

Public-facing static pages for the Meep mobile app, hosted via GitHub Pages.

## Live URLs

Once GitHub Pages is enabled on this repo (see setup below), the pages will be available at:

- Landing: `https://<your-username>.github.io/meep-public-pages/`
- Privacy Policy: `https://<your-username>.github.io/meep-public-pages/privacy.html`

Use the Privacy Policy URL in your App Store Connect listing.

## Files

- `index.html` — simple landing page linking to the legal pages
- `privacy.html` — the privacy policy served to users and app store reviewers

## Updating the privacy policy

1. Edit `privacy.html`.
2. Update the "Last updated" date near the top.
3. Commit and push to `main` — GitHub Pages will redeploy automatically within ~1 minute.

## Enabling GitHub Pages

After pushing to GitHub:

1. Go to the repo on github.com.
2. **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Branch: `main`, folder: `/ (root)`.
5. Save. Pages will build and publish at the URL above.
