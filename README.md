# myinnergame

The marketing landing page for **Inner Game Consulting**, serving `https://www.myinnergame.com` via GitHub Pages.

## Stack

A single self-contained `index.html`. No build step, no dependencies. Open it in any browser to preview locally. Brand alignment, design tokens, and copy decisions are documented in an HTML comment at the top of the file.

## Deploying

Pushes to `main` deploy automatically via GitHub Pages. Pages is configured to serve from the repo root on the `main` branch. The `CNAME` file routes the custom domain.

## Product screenshots

The four tool sections show grey skeleton placeholders until real screenshots are present. Drop these files into `assets/` and they replace the placeholders automatically — no code change needed:

| Filename | Tool |
| --- | --- |
| `assets/manifesto.png` | Strategy Manifesto |
| `assets/crm.png` | Inner Game CRM |
| `assets/dashboard.png` | Dashboard (also used in the hero laptop) |
| `assets/journal.png` | Mindset Journal |

Recommended: landscape ~16:10, populated views (not empty states). The apps are auth-gated, so screenshots come from a logged-in session.

## Updating copy

Edit `index.html`, commit, push. The page is one file — find-and-replace works for global changes.
