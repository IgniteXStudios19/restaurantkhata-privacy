# Restaurant Sales & Expenses — privacy policy

This repository exists for one reason: to host the privacy policy for the
**Restaurant Sales & Expenses** Android app at a stable, public URL, because
Google Play requires a reachable privacy policy URL before a release can be
submitted.

It is public deliberately. A privacy policy is meant to be readable by anyone.
The app's source lives in a separate, private repository.

- `index.html` — the policy. Self-contained: no web fonts, no CDN, no
  analytics, no external request of any kind.
- `.nojekyll` — tells GitHub Pages to serve the file as-is rather than running
  it through Jekyll.

**The source of truth is `docs/privacy/index.html` in the app repository**,
which is kept in step with `docs/privacy-policy.md` and checked against what
the build actually does. When the app changes, that file changes, and the
change is copied here. A privacy policy that has drifted from the build is
worse than none, because it is a promise that is no longer true.
