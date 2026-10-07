# bearings-site

Public support and privacy pages for the Bearings iOS app, served by
GitHub Pages. This is the one public repo under `fvzl`, on purpose:
App Store Connect needs both URLs to be reachable by anyone.

- `index.html` — Support URL
- `privacy.html` — Privacy Policy URL. Source text lives in the private
  app repo at `docs/app-store/privacy-policy.md`; keep the two in step.

Static HTML and one stylesheet. No scripts, fonts or other third-party
requests, so the privacy page itself collects nothing.
