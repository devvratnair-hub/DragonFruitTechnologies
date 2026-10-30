# Dragonfruit Technologies website

The public website and brand kit for **Dragonfruit Technologies**, founder-led Dayforce consulting from Calgary.

> Dayforce, seen from every side of the table.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The whole website: one self-contained page |
| `og-image.png` | The 1200 × 630 preview image shown when the site is shared on LinkedIn, email and chat |
| `brand/` | The logo kit: mark, simple mark, favicon, and light and dark lockups, as SVG and PNG |
| `source/` | The scripts that generate the logo and assemble the page |

## Deploy

Upload `index.html`, `og-image.png` and the `brand/` folder to the web root. Keep `brand/` next to `index.html`, because the page loads its favicon and app icon from there.

To publish with GitHub Pages, go to **Settings → Pages**, choose this branch and the root folder, then point the custom domain `www.dragonfruittechnologies.com` at it.

## Brand at a glance

The site is a dragon fruit cut open:

- **Night skin:** the top and bottom of the page are dark, because the flower blooms at night.
- **White flesh:** the middle of the page is calm white.
- **Black seeds:** small precise details.
- **Pitaya magenta:** the single bold accent.

| Token | Hex | Use |
| --- | --- | --- |
| Night | `#120C14` | Dark sections, header |
| Pitaya | `#E0115F` | Primary buttons, the mark's rind |
| Pitaya glow | `#FF5C93` | Accent text on dark |
| Pitaya ink | `#C20E52` | Small accent text on light |
| Bract green | `#8DC63F` | Leaf tips only, used sparingly |
| Flesh | `#FBF7F2` | Light sections |
| Seed | `#15101A` | Body text on light |

**Type:**

- Bricolage Grotesque for headings
- Geist for body text
- Geist Mono for labels

All three are loaded from Google Fonts.

**The mark** is the fruit seen from above:

- Seeds placed on the golden-angle spiral, the way real seed heads grow.
- A magenta rind.
- Seven scales rising like a flame, shading from magenta to leaf green.

**Brand line:** Rooted in grit · Rare by nature · Fierce by design · Flawless within.

## Content rule

Every claim on the site comes from Devvrat Nair's resume and founder profile. Don't add experience, clients, platforms or numbers that his record does not support.

## Rebuilding

`source/make_logo.py` regenerates the logo SVGs. It needs Python with `fontTools` and the Bricolage Grotesque font files from the `@fontsource/bricolage-grotesque` npm package.

`source/build.py` assembles the page from `source/template.html`.

---

Dayforce and ADP Workforce Now are trademarks of their respective owners. Dragonfruit Technologies is independent and not affiliated with or endorsed by them.
