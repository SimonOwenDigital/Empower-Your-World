# J01 Make AI Adoption Safe: visual overview of the PUBLIC pack (v1.0)

This is a one-page, interactive overview of the free J01 PUBLIC pack, built around the six questions of the Risk Spine. It shows real pages from the pack, follows one synthetic use case (Wyreld Co.'s CatalogueAgent) through all six stages, and includes a private "weakest link" self-check. It then points visitors to the download, to registration, and to the "Register your interest" form.

## Files

| File | What it is |
|---|---|
| `index.html` | The overview as a standalone page. It loads the images from `img/` next to it. |
| `squarespace-code-block.html` | The same overview as one block of code to paste into a website (for example a Squarespace Code Block). It loads the images from this repository through the jsDelivr CDN, pinned to the release tag `j01-overview-v1.0`. |
| `img/` | Twelve pages from the six module Knowledge Editions in the PUBLIC pack: one overview page and one CatalogueAgent worked-example page per stage. |
| `J01_PUBLIC_Overview_v1.0.zip` | All of the above in one download. |

## Using it on a website

1. Paste the whole of `squarespace-code-block.html` into an HTML/code block.
2. If the site header stays fixed at the top of the screen while you scroll, set `--j01o-top` on the line `<div id="j01o" style="--j01o-top:0px">` to the header's height (for example `80px`). That keeps the section bar visible below it.

The block is about 32 KB. Its styles are scoped to `#j01o`, so they do not change the rest of the site.

## What it collects

Nothing. The self-check runs in the visitor's browser and is never stored or sent. The page links to:

- the J01 Journey page, with tracking parameters (`utm_source=j01-overview`);
- the PUBLIC zip on downloads.empoweryour.world;
- a Microsoft Form.

It loads the Inter font from Google Fonts.

## Updating it

When the Knowledge Editions change, replace the images in `img/`. Then publish under a new tag and update the tag in `squarespace-code-block.html`, so the pinned images change together.

## Use terms

Free to learn from and to share unmodified, with attribution to Simon Owen / EmPOWER Your World. Delivering J01 as a service needs a licence. This is a learning resource, not legal, regulatory or professional advice. Wyreld Co. and CatalogueAgent are synthetic, and the examples claim no observed outcome.
