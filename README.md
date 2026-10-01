# North Point Services — static site preview

Side-project rebuild preview of **northpointsmn.com** for North Point Services Co. (Lakeville, MN). Local files only — not deployed publicly.

## How to open

**Option A — open the file directly**

1. Open this folder in your file manager or terminal.
2. Double-click (or open in a browser) `index.html`.

Absolute path to the home page:

```
/workspace/north-point-preview/index.html
```

**Option B — local static server**

From this directory:

```bash
cd /workspace/north-point-preview
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit: http://127.0.0.1:8765/

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| Services | `services.html` |
| About | `about.html` |
| Contact | `contact.html` |

Shared assets: `css/styles.css`, `js/main.js`.

## Notes

- Contact form is UI-only (no backend). Phone and email links are clickable (`tel:` / `mailto:`).
- Business facts in the copy match the provided brief; do not treat this as the live production site.

## Photos
Stock architecture imagery (Pexels, license-clear) lives in `images/`. UI chrome stays black/white/grey; photos use mild CSS desaturation. No staff/people portraits — exteriors, roofs, interiors only.
