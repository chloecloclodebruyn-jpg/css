# CSS Selectors — Exercise 5.3

A beginner HTML and CSS project demonstrating five ways to select HTML elements and apply styles.

**Author:** Chloe de Bruyn  
**Technologies:** HTML5 and CSS3

## View the project

Download and extract this project, then open `index.html` in a web browser. No installation, dependencies or build command is required.

## Selectors demonstrated

| Selector type | Code | Effect |
| --- | --- | --- |
| Element | `p` | Makes all paragraphs red |
| Class | `.note` | Sets all elements with the `note` class to 20px |
| ID | `#id-selector-demo` | Makes the element with that ID green |
| Attribute | `li[value="4"]` | Makes the list item with value 4 blue |
| Universal | `*` | Centres text on all elements |

```css
p {
  color: red;
}

.note {
  font-size: 20px;
}

#id-selector-demo {
  color: green;
}

li[value="4"] {
  color: blue;
}

* {
  text-align: center;
}
```

The original `ol` rules are preserved in `style.css`. All five elements with the `note` class receive the 20px font size, including the paragraph and the four list items.

## Files

```text
css-selectors/
├── index.html
├── style.css
├── goal.png
├── README.md
├── PORTFOLIO-EVIDENCE.md
└── evidence/
    ├── README.md
    └── source-checks.txt
```

`goal.png` is the supplied course reference image. It is not a screenshot of the completed project. The original course solution folder remains available locally and is excluded from the GitHub package.

## Learning outcomes

- Select elements by tag name, class, ID and attribute value.
- Apply a shared declaration using the universal selector.
- Use `color`, `font-size` and `text-align` properties.
- Connect HTML to an external stylesheet.
- Preserve existing CSS while adding new rules.

## Portfolio of evidence

See [PORTFOLIO-EVIDENCE.md](PORTFOLIO-EVIDENCE.md) for requirement mapping and verification results. See [evidence/README.md](evidence/README.md) for the browser and GitHub screenshot checklist.

Source checks passed. Browser rendering, screenshots and GitHub deployment are pending.

## Add to GitHub

1. Extract `5.3-CSS-Selectors-GitHub.zip` from the parent Web Development Project folder.
2. Create a repository such as `css-selectors`.
3. Select **Add file → Upload files** and upload the contents of the extracted `css-selectors` folder.
4. Commit with a message such as `Complete CSS Selectors exercise`.

For an existing course repository, upload the whole `css-selectors` folder instead. Preserve the relative paths between HTML, CSS and evidence files.

## Optional GitHub Pages publication

With the project files at the repository root, open **Settings → Pages**, choose **Deploy from a branch**, select the branch containing your files and `/ (root)`, then save. Open the URL GitHub provides after deployment and verify the page.

If this exercise is a subfolder of an existing published course repository, open that subfolder beneath the repository's site URL.

**Repository URL:** Pending  
**Live website URL:** Pending

## Credits

Completed by Chloe de Bruyn for learning and portfolio purposes. Starter HTML, list styling and reference image were supplied with the course exercise.
