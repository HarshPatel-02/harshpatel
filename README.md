# Harsh Patel · AI Developer portfolio

Personal portfolio of Harsh Patel, AI Developer at Kode Creators. A single static page (no build step) with a dark glass design, a particle-robot hero, filterable projects, and a contact form that opens the visitor's email app.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site: markup, styles and scripts in one file |
| `404.html` | Not-found page that GitHub Pages shows for broken links |
| `Images/icons/*-t.png` | Project logos (transparent) used on the project cards |
| `Images/og-image.jpg` | 1200×630 preview image for links shared on LinkedIn, WhatsApp, Slack, etc. |
| `resume.pdf` | **Add this yourself.** The Resume / Download resume buttons link to it |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Deploy on GitHub Pages

The repository `HarshPatel-02/harshpatel` already has GitHub Pages turned on, serving the `main` branch from the root. The live site is `https://harshpatel-02.github.io/harshpatel/`.

- **Branches:** `main` is the live site. `dev` holds the redesigned portfolio (tag `v1`). Merge `dev` into `main` when you are ready to publish it.
- **Before publishing:** add your resume as `resume.pdf` in the repository root.
- **If the address changes** (for example a custom domain or a renamed repository), update it in `index.html` in these tags: `og:url`, `og:image`, `twitter:image`, `canonical` and the JSON-LD `url`/`image`.

## Editing

- Change a project logo: replace the file in `Images/icons/` and keep the same name.
- Colours, fonts and spacing are defined at the top of the `<style>` block in `index.html` (`:root`).
- After editing, check the page at phone width (about 390px) as well as desktop.
