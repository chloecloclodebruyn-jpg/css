# Portfolio of Evidence — 5.1 Adding CSS

Author: Chloe de Bruyn  
Prepared: 28 October 2026  
Status: Code and source checks complete locally; browser screenshots, GitHub upload and publication pending.

## Aim

Demonstrate inline, internal and external CSS, and navigate between examples using relative HTML links.

## Requirement evidence

| Requirement | Source evidence | Expected browser result |
| --- | --- | --- |
| Index links to three examples | `index.html`: anchors to `inline.html`, `internal.html`, `external.html` | Three working links |
| Inline CSS | `inline.html`: `style="color: blue;"` on `h1` | Blue heading |
| Internal CSS | `internal.html`: `h1 { color: red; }` inside a head `<style>` block | Red heading |
| External CSS | `external.html`: stylesheet link to `style.css` | External stylesheet loads |
| External rule | `style.css`: `h1 { color: green; }` | Green heading |
| Standalone HTML pages | All four HTML files contain a doctype and document structure | Each page opens directly in a browser |

## Verification performed

Source checks run on 28 October 2026:

- PASS — All four HTML files include the HTML doctype.
- PASS — All local page and stylesheet link targets exist.
- PASS — Inline heading declares blue text.
- PASS — Internal stylesheet declares red heading text.
- PASS — External page links to `style.css`, which declares green heading text.
- PASS — GitHub ZIP contains the project code and documentation, with no course solution files.

These are source and package checks. Browser rendering and live hosting have not been verified.

## Manual browser checks to complete

1. Open `index.html` and confirm three example links appear.
2. Open each link and confirm the heading colour matches the table above.
3. Use the browser Back button to return to the index between examples.
4. Save screenshots using the filenames in `evidence/README.md`.
5. Repeat the navigation checks on the published site if using GitHub Pages.

## GitHub evidence record

Fill these fields after uploading; no repository or deployment is currently claimed.

- Repository URL: Pending
- Upload commit identifier: Pending
- Published website URL (if using Pages): Pending
- Deployment result (if using Pages): Pending
- Browser screenshots: Pending

## Reflection

Inline CSS applies a declaration directly to an element. Internal CSS keeps rules within one HTML document. External CSS stores rules in a separate file that can be linked from multiple pages. This exercise uses the `color` property and an `h1` selector to demonstrate the different placement methods.

## Submission package

`5.1-Adding-CSS-GitHub.zip` is saved in the parent Web Development Project folder. It includes the completed exercise and documentation inside `adding-css/`. The original course `Solution` folder is excluded from this package.
