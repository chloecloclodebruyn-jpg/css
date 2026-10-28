# css
# Adding CSS — Web Development Exercise 5.1

A beginner web development project demonstrating **inline**, **internal** and **external CSS**. Each example changes a heading’s text colour using a different method.

**Author:** Chloe de Bruyn  
**Technologies:** HTML5 and CSS3

## Project overview

The home page links to three examples:

| Example | CSS method | Expected result |
| --- | --- | --- |
| Inline | A `style` attribute on the heading | Blue heading |
| Internal | A `<style>` block in the HTML document head | Red heading |
| External | A separate CSS file linked from the HTML document | Green heading |

## Getting started

1. Download this repository using **Code → Download ZIP**, then extract it, or clone the repository.
2. Open `index.html` in your web browser.
3. Select each example to see how its CSS is applied.
4. Use your browser’s Back button to return to the home page.

No dependencies, installation or build tools are required.

## Project structure

```text
adding-css/
├── index.html
├── inline.html
├── internal.html
├── external.html
├── style.css
├── README.md
├── PORTFOLIO-EVIDENCE.md
└── evidence/
    └── README.md
```

## CSS examples

### Inline CSS

Written directly on the element in `inline.html`:

```html
<h1 style="color: blue;">Style Me in Blue!</h1>
```

### Internal CSS

Written inside the `<head>` of `internal.html`:

```html
<style>
  h1 {
    color: red;
  }
</style>
```

### External CSS

Linked inside the `<head>` of `external.html`:

```html
<link rel="stylesheet" href="style.css">
```

The rule is stored in `style.css`:

```css
h1 {
  color: green;
}
```

## What I learned

- How to apply CSS using three different methods.
- How the `color` property changes text colour.
- How an element selector such as `h1` targets headings.
- How to connect an HTML page to an external stylesheet.
- How to navigate between local pages using relative links.

## Verification and portfolio evidence

Source checks confirmed that all four HTML pages contain an HTML doctype, all local page and stylesheet links point to existing files, and each example contains its intended colour declaration.

Browser screenshots and public deployment evidence are pending. See [Portfolio of Evidence](PORTFOLIO-EVIDENCE.md) for the requirement mapping and verification record, and [Evidence Instructions](evidence/README.md) for the screenshot checklist.

## Upload to GitHub

1. Create a repository, for example `adding-css`.
2. Upload the files shown above to the repository root, keeping `index.html` at the root.
3. Commit the files with a message such as `Complete Adding CSS exercise`.

To include the project in an existing web development repository, upload the whole `adding-css` folder instead. Keep the HTML and CSS files together to preserve relative links.

## Publish with GitHub Pages

1. In your repository, open **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the branch containing your files and select `/ (root)`.
4. Save and wait for deployment to finish.
5. Open the website URL shown in Pages settings and check each example.

These steps assume this project’s `index.html` is at the repository root. If it is inside a course repository, visit the project’s subfolder under that repository’s published site.

A public website URL has not yet been verified. Add it here after publishing.

## Project notes

Created for learning and portfolio purposes as part of a web development course. The original course `Solution` folder is retained locally for reference and excluded from the GitHub upload ZIP.
