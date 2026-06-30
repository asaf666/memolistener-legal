# memolistener-legal

Public legal pages for the Android app **המתמלל האוטומט (Memo Listener)** — package `com.memolistener.app`.

Hosted on GitHub Pages so the Play Console listing can point at a public URL.

## Pages

| Document | URL |
| --- | --- |
| Privacy policy | https://asaf666.github.io/memolistener-legal/privacy-policy/ |
| Accessibility statement | https://asaf666.github.io/memolistener-legal/accessibility/ |

## Source of truth

The text on these pages is copied **verbatim** from the app's bundled resources so the
hosted copy and the in-app copy never diverge (Play reviewers compare them):

- `privacy-policy/index.html` ← `app/src/main/res/raw/privacy_policy_he.txt`
- `accessibility/index.html` ← `app/src/main/res/raw/accessibility_statement_he.txt`

**On any change to the in-app text, update the matching page here in the same release.**

## Hosting

Plain static HTML; `.nojekyll` disables Jekyll so files are served exactly as written.
Enable Pages: repo **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.
