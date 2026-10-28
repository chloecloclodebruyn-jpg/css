# Portfolio of Evidence — Color Vocabulary 5.4

**Author:** Chloe de Bruyn  
**Prepared:** 28 October 2026  
**Status:** CSS implementation and local source checks complete; browser screenshots and GitHub upload pending.

## Objective

Style the supplied Spanish colour vocabulary page using external CSS only. Match each vocabulary heading to its meaning, use normal font weight for the colour titles and size all images to 200 × 200 pixels.

## Requirement mapping

| Requirement | Source evidence | Expected browser result |
| --- | --- | --- |
| External stylesheet | `index.html` already links to `./style.css`; file created | CSS loads |
| Red heading | `#red { color: red; }` | Rojo is red |
| Blue heading | `#blue { color: blue; }` | Azul is blue |
| Orange heading | `#orange { color: orange; }` | Anaranjado is orange |
| Green heading | `#green { color: green; }` | Verde is green |
| Yellow heading | `#yellow { color: yellow; }` | Amarillo is yellow |
| Normal title weight | `.color-title { font-weight: normal; }` | All five vocabulary headings use normal weight |
| Image size through CSS | `img { height: 200px; width: 200px; }` | All five images measure 200 × 200 CSS pixels |
| Preserve HTML | Starter `index.html` left unchanged | Supplied structure and content retained |

The HTML's original TODO comments remain as the task specification. The requirements are implemented in `style.css`.

## Verification performed

Python HTML and CSS source inspection confirmed all five colour declarations and matching headings, the shared normal font weight, the image size declarations and five image elements. All stylesheet and image references resolve to existing files. The HTML bytes were compared before and after implementation and are unchanged.

All nine recorded source checks passed; see `evidence/source-checks.txt`. The upload ZIP was also checked for integrity, expected file membership and byte-for-byte agreement with the packaged source files.

Source checks do not establish visual rendering or successful hosting. Browser testing and screenshots remain pending.

## Visual evidence to collect

Follow `evidence/README.md` to capture the page, CSS source and computed image dimensions. Compare the rendered project with the supplied `goal.png`; the goal image is a course reference, not a screenshot of this implementation.

## GitHub evidence record

- Repository URL: Pending
- Upload commit identifier: Pending
- Repository file list screenshot: Pending
- Commit screenshot: Pending
- Browser result screenshots: Pending
- Live website URL, if published: Pending
- Successful deployment screenshot, if published: Pending

## Reflection

ID selectors provide a separate colour for each vocabulary word. The shared class applies normal font weight to all five colour headings without changing the introductory headings. The image element selector applies the same dimensions to every colour image. External CSS keeps the styling separate from the supplied HTML.

## Submission package

`5.4-Color-Vocab-GitHub.zip` is saved in the parent Web Development Project folder. It contains the project inside `color-vocab/`, including the source code, five colour images, supplied goal image, README and evidence documents. The course solution folder is excluded.
