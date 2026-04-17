# VEYRA EMPIRE — Public Assets

Public image assets for the VEYRA EMPIRE script distribution system.

This is the **only** VEYRA EMPIRE repo that is publicly visible. It contains no
code, no script sources, and no secrets — only imagery referenced by the
self-serve install page at `<proxy-url>?page=install`.

## Files

| File | Used by |
|------|---------|
| `bg-install.jpg` | Install page background (cityscape at sunset) |

## Why public?

The install page is a browser-loaded HTML page. Browsers can't authenticate to
GitHub to fetch private raw files, so any image referenced via `<img src>` or
CSS `background-image` must come from a publicly reachable URL. Keeping these
assets in a standalone public repo lets us version them in git without mixing
them into the gated `scripts` or `proxy` repos.
