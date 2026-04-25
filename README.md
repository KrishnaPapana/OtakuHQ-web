# OtakuHQ — GitHub Pages

Public website for the OtakuHQ Chrome extension. Serves as the homepage and privacy policy host required by the Chrome Web Store.

## Pages

| File | URL (after publishing) | Purpose |
|---|---|---|
| `index.html` | `https://<user>.github.io/otakuhq/` | Landing page — feature overview, permissions summary, about |
| `privacy-policy.html` | `https://<user>.github.io/otakuhq/privacy-policy.html` | Full privacy policy |
| `styles.css` | — | Shared stylesheet for both pages |

## Publish with GitHub Pages

1. Push this folder's contents to a GitHub repository (e.g. `otakuhq`)
2. Go to **Settings → Pages**
3. Set source to the branch and folder containing these files
4. GitHub will publish to `https://<your-github-username>.github.io/otakuhq/`

## Use in Chrome Web Store

In the Chrome Developer Dashboard, set:

- **Homepage URL**: `https://<your-github-username>.github.io/otakuhq/`
- **Privacy Policy URL**: `https://<your-github-username>.github.io/otakuhq/privacy-policy.html`
- **Support URL**: your GitHub repository's Issues page or the homepage URL above
