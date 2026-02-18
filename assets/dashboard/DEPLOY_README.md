# Deploy Bundle

This bundle is a static-site payload for the election dashboard.

## Contents
- `dashboard.html` (entrypoint)
- `plot_2026.html`
- `figure/` (iframe apps + Plotly runtime)
- `data/` (all runtime `.js` + `.json` datasets and boundary files)
- `font/` + `assets/`
- `MANIFEST.txt` and `MANIFEST.sha256`

## Host Requirements
- Serve as static files with the bundle root as web root.
- Keep `dashboard.html`, `figure/`, `data/`, `font/`, `assets/` at the same relative paths.
- Avoid frame-blocking headers (`X-Frame-Options: DENY`) because dashboard uses iframes.
- Use same-origin hosting for `dashboard.html` and its iframe/data assets.

## Verify Integrity
Run:

```bash
cd deploy_dashboard_bundle
shasum -a 256 -c MANIFEST.sha256
```
