# PDF Send — website

Public site for the **PDF Send** Android app (Share Over Wi-Fi).

This repository holds **only the website**. The app's source code is not published here.

| Page | Purpose |
|------|---------|
| `index.html` | Landing page — also usable as the "Website" field in the Play listing |
| `privacy.html` | Privacy policy — **required** by Google Play |

## Live URLs

After GitHub Pages is enabled (Settings → Pages → Deploy from a branch → `main` → `/root`):

- Site: `https://bytedroid1.github.io/pdfsend/`
- **Privacy policy: `https://bytedroid1.github.io/pdfsend/privacy.html`** ← paste this into Play Console

## Updating the policy

`privacy.html` is kept in sync with `PRIVACY.md` in the app project. When the app's data
handling changes, update both, bump the "Last updated" date, and push.
