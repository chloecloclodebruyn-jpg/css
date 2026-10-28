# Portfolio of Evidence — CSS Selectors 5.3

**Author:** Chloe de Bruyn  
**Prepared:** 28 October 2026  
**Status:** Implementation and source checks complete locally. Browser evidence and GitHub upload pending.

## Objective

Complete the five tasks in the supplied CSS Selectors exercise using an external stylesheet, while retaining the original ordered-list styling.

## Requirements and source evidence

| Task | Evidence in style.css | Target in index.html | Expected result |
| --- | --- | --- | --- |
| 1. Element selector | `p { color: red; }` | Paragraph | Red paragraph |
| 2. Class selector | `.note { font-size: 20px; }` | Paragraph and four list items | All five use 20px text |
| 3. ID selector | `#id-selector-demo { color: green; }` | List item 3 | Green text |
| 4. Attribute selector | `li[value="4"] { color: blue; }` | List item 4 | Blue text |
| 5. Universal selector | `* { text-align: center; }` | All elements | Centred text |
| Preserve supplied styling | Original `ol` declarations retained | Ordered list | Original list spacing and marker positioning retained |

The starter HTML contains the assignment's original TODO comments as a record of the task requirements; all five tasks are implemented in `style.css`.

## Verification

Python source inspection checked each selector and required declaration, confirmed the original ordered-list declarations, counted the matching class, ID and attribute targets, and confirmed the linked stylesheet exists. All checks passed. The recorded output is in `evidence/source-checks.txt`.

The ZIP was checked for integrity and expected file membership after packaging. It includes the exercise code, supplied goal image and documentation; it excludes the course solution folder.

These checks verify source declarations and file references. They do not establish rendered appearance or successful public deployment.

## Visual evidence pending

Follow `evidence/README.md` to capture the completed page, CSS source and optional computed styles. Compare the rendered page with `goal.png`, which is the supplied course target image and is not a completion screenshot.

## GitHub evidence record

- Repository URL: Pending
- Upload commit identifier: Pending
- Repository files screenshot: Pending
- Commit screenshot: Pending
- Live website URL, if published: Pending
- Successful deployment screenshot, if published: Pending
- Completed browser screenshot: Pending

## Reflection

Element selectors target a tag type. Class selectors apply reusable styles across different elements. An ID selector targets an element with a specific ID. Attribute selectors match an attribute and its value. The universal selector applies a declaration to every element. The paragraph and list items share the note class, so the same font-size declaration applies across both tag types.

## Downloadable submission

`5.3-CSS-Selectors-GitHub.zip` is saved in the parent Web Development Project folder. Extract it and upload the contents of `css-selectors/` to a dedicated GitHub repository, or upload the folder into an existing course repository.
