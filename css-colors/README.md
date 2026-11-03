# CSS Colors — Exercise 6.0

**Author:** Chloe de Bruyn  
**Completed locally:** 3 November 2026

Open `index.html` in a browser. No installation or build step is required.

## Walk through the CSS

The internal stylesheet lives inside `<style>` in the HTML head. Each element selector chooses the HTML element to style. `color` sets text colour; `background-color` sets the background.

```css
body {
  background-color: antiquewhite;
}

h1 {
  color: whitesmoke;
  background-color: darkseagreen;
}

h2 {
  color: #FAF8F1;
  background-color: #C58940;
}
```

1. `body` gives the page an antiquewhite background.
2. `h1` makes “Hello” whitesmoke on darkseagreen.
3. `h2` makes “World” #FAF8F1 on #C58940.

Named colours are written without quotation marks. Hex colours start with `#`; each pair of digits represents red, green or blue. For example, #C58940 contains C5 red, 89 green and 40 blue. A semicolon ends each declaration, and braces group declarations for one selector.

The heading backgrounds extend across the available width because headings are block elements by default.

## Portfolio of evidence

See [PORTFOLIO-EVIDENCE.md](PORTFOLIO-EVIDENCE.md) and the [evidence folder](evidence/README.md). `goal.png` is the course target, not a screenshot of the completed work. The supplied `solution.html` remains locally and is excluded from the upload ZIP.

## Share to GitHub

The parent folder contains `6.0-CSS-Colors-GitHub.zip`. Extract it, then upload the contents of `css-colors/` into a dedicated repository (suggested name: `css-colors`). To add it to an existing course repository, upload the entire `css-colors` folder instead. Preserve the evidence subfolder.

Suggested commit message: `Complete CSS Colors exercise 6.0 with portfolio evidence`.

After upload, record the repository URL and commit identifier in `PORTFOLIO-EVIDENCE.md`. GitHub upload is pending; no repository or public site has been created by this task.

## Credits

Course starter HTML, goal image and reference solution were supplied with the exercise. CSS implementation and portfolio preparation are for Chloe de Bruyn’s learning record.
