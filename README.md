# Harsh Patel · AI Developer portfolio

Personal portfolio of Harsh Patel, AI Developer at Kode Creators. A single static page (no build step) with a dark glass design, a particle-robot hero, an animated finance-agent workflow, filterable projects, and a contact form that opens the visitor's email app.

Live site: https://harshpatel-02.github.io/harshpatel/

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site: markup, styles and scripts in one file |
| `404.html` | Not-found page that GitHub Pages shows for broken links |
| `Images/icons/*-t.png`, `Images/icons/rag-t.svg` | Project logos (transparent) used on the project cards |
| `Images/icons/*.png` | White-background versions of the same logos (not used by the page) |
| `Images/og-image.jpg` | 1200×630 preview image for links shared on LinkedIn, WhatsApp, Slack, etc. |
| `resume.pdf` | **Add this yourself.** The Resume / Download resume buttons link to it |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |
| `.gitignore` | Keeps system files, editor folders, logs and local design-tool files out of git |
| `PRODUCT.md` | Who the site is for, confirmed skills and projects, and what must never be claimed |
| `DESIGN.md`, `.impeccable/` | The design system (colours, type, components) and design-tool settings |

## Branches

| Branch | What it holds |
|---|---|
| `main` | **The live site.** GitHub Pages publishes it automatically on every push. Holds only what the site needs: `index.html`, `404.html`, the images and `.gitignore` |
| `dev` | Everything: the site plus README, PRODUCT, DESIGN and design-tool settings. Do your work here |

Tag `v1` marks the first AI-developer redesign on `dev`.

## Everyday workflow

```
git checkout dev            # work on dev
git add .
git commit -m "what you changed"
git push                    # saves to GitHub; the live site does not change
```

To publish to the live site, bring only the site files from `dev` to `main`:

```
git checkout main
git checkout dev -- index.html 404.html Images
git commit -m "Publish: what you changed"
git push                    # GitHub Pages rebuilds the live site in about a minute
git checkout dev
```

Commit as `HarshPatel-02` so GitHub credits the right account (`git config --global user.name "HarshPatel-02"`).

## Before publishing

- Add your resume as `resume.pdf` in the repository root, on `main` as well as `dev`.
- If the address changes (a custom domain or a renamed repository), update it in `index.html` in these tags: `og:url`, `og:image`, `twitter:image`, `canonical` and the JSON-LD `url`/`image`.

## Editing

- Change a project logo: replace the file in `Images/icons/` and keep the same name.
- Colours, fonts and spacing are defined at the top of the `<style>` block in `index.html` (`:root`).
- Project facts and skills must match `PRODUCT.md`; never add metrics, client names or tools that were not used.
- After editing, check the page at phone width (about 390px) as well as desktop.
