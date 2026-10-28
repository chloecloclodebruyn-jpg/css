# Color Vocabulary — Exercise 5.4

A beginner HTML and CSS project for learning five Spanish colour words. Each word appears in its matching colour above a corresponding image.

**Author:** Chloe de Bruyn  
**Technologies:** HTML5 and CSS3

## View the project

Download and extract the project, then open `index.html` in your browser. No installation, dependencies or build command is needed.

## Vocabulary

| Spanish | English | CSS selector |
| --- | --- | --- |
| Rojo | Red | `#red` |
| Azul | Blue | `#blue` |
| Anaranjado | Orange | `#orange` |
| Verde | Green | `#green` |
| Amarillo | Yellow | `#yellow` |

## Requirements completed

- Created `style.css`, connected by the starter HTML's existing stylesheet link.
- Used ID selectors to give each vocabulary heading its matching colour.
- Used `.color-title` to set all five vocabulary headings to `font-weight: normal`.
- Used the `img` element selector to set every image to 200px wide and 200px high.
- Preserved the supplied HTML without changes.

## CSS example

```css
#red {
  color: red;
}

.color-title {
  font-weight: normal;
}

img {
  height: 200px;
  width: 200px;
}
```

The stylesheet includes equivalent colour rules for blue, orange, green and yellow. The introductory headings keep their default weight because they do not have the `color-title` class.

## Project files

```text
color-vocab/
├── index.html
├── style.css
├── assets/
│   └── images/
│       ├── red.png
│       ├── blue.png
│       ├── orange.png
│       ├── green.png
│       └── yellow.png
├── goal.png
├── README.md
├── PORTFOLIO-EVIDENCE.md
└── evidence/
    ├── README.md
    └── source-checks.txt
```

`goal.png` is the supplied course target image, not a screenshot of the completed project. The original course solution folder is retained locally and excluded from the upload package.

## Learning outcomes

- Use ID selectors for individual elements.
- Use a class selector to share a style across related headings.
- Use an element selector to style all images.
- Apply colour, font weight and image dimensions through external CSS.
- Keep HTML content and CSS styling in separate files.

## Portfolio of evidence

[PORTFOLIO-EVIDENCE.md](PORTFOLIO-EVIDENCE.md) maps each requirement to its source evidence. [Source checks](evidence/source-checks.txt) record local verification. [Evidence instructions](evidence/README.md) explain which screenshots to collect.

Source checks passed. Browser screenshots and GitHub publication are pending.

## Upload to GitHub

1. Extract `5.4-Color-Vocab-GitHub.zip` from the parent Web Development Project folder.
2. Create a repository, for example `color-vocab`.
3. Select **Add file → Upload files** and upload everything inside the extracted `color-vocab` folder, preserving its subfolders.
4. Commit with a message such as `Complete Color Vocabulary CSS project`.

For an existing course repository, upload the whole `color-vocab` folder instead. Keep `assets/images` and its files together with the HTML and stylesheet.

## Optional GitHub Pages publication

For a dedicated repository with `index.html` at its root, open **Settings → Pages**, select **Deploy from a branch**, choose the branch containing the project and `/ (root)`, then save. Open the website URL GitHub provides after deployment and check the colours and images.

For a project inside an existing published course repository, visit its subfolder under the repository's website URL.

**Repository URL:** Pending  
**Live website URL:** Pending

## Credits

Completed by Chloe de Bruyn for learning and portfolio purposes. Starter HTML, colour images and goal image were supplied with the course exercise.
