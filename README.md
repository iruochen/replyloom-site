# Publish the ReplyLoom privacy site with GitHub Pages

The Chrome Web Store needs a stable public privacy-policy URL. The extension source code does not need to be public.

Recommended setup:

1. Create a separate **public** GitHub repository named `replyloom-site`.
2. Copy `index.html` and `privacy.html` from this folder into the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

The privacy-policy URL will normally be:

`https://YOUR_GITHUB_USERNAME.github.io/replyloom-site/privacy.html`

Open that URL in a private/incognito browser window before entering it in the Chrome Web Store dashboard.
