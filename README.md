# NEXORA website starter

A responsive dark anime/cosmic-inspired single-page website. It has no build step.

## Preview locally
Open `index.html` in a modern browser.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a **public** repository such as `nexora-site`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then Save.
5. Wait for deployment. The URL will be similar to `https://YOUR-USERNAME.github.io/nexora-site/`.

Alternative: try Netlify Drop at https://app.netlify.com/drop/ and upload this folder, subject to the host's current account/plan requirements.

## Important limits
- Search, category filters, responsive layout and animations work in the browser.
- Login/signup forms are visual demos only: they do not create accounts, store passwords or authenticate users.
- The admin preview opens with Ctrl+Shift+A. It is not authenticated or secured and must not be used for real administration.
- The announcement preview only appears in the current browser session; it is not shared/persisted.
- For real user accounts, connect a provider such as Supabase (https://supabase.com/) or Firebase and configure secure policies.
- For shared admin controls and persistent data, add a database and server-side authorization. Never put secret keys in front-end code.
