# Certified — links page

The companion site for the book *Certified: What it actually takes to get your
veteran-owned business through SBA certification*.

**Live at:** https://sdvosb-guide.github.io

## What this is

Every QR code and printed URL in the book points **directly** at a government
page — no link shortener, nothing tracked. The cost of that choice is that a
printed code cannot be repointed when an agency moves a page.

This site is the backstop: one address, printed in the book's front matter,
listing the current location of every source. When a `.gov` URL moves, this page
gets edited instead of the book getting reprinted.

It also hosts the free worksheet pack.

## Contents

| File | What it is |
|---|---|
| `index.html` | The links page |
| `Certified-Worksheets.pdf` | Free worksheet pack — free to copy and distribute |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Do not hand-edit index.html

It is generated from the book manuscript by `build/build_links_page.py` in the
book's (private) repository, so the page cannot drift from what the book
actually cites. Edit the manuscript, regenerate, and copy the output here.

## Publishing

GitHub Pages, serving from the repository root on the default branch.
