# craigmillard.github.io

This site is built with [Quarto](https://quarto.org/).

## Common Quarto Commands

### Render the Entire Site
```sh
quarto render
```

### Render a Single Page
```sh
quarto render arrangements.qmd
```

### Preview the Site Locally
```sh
quarto preview
```

### Clean Output Files
```sh
quarto clean
```

### Render Only the Posts Directory
```sh
quarto render posts/
```

## Deployment

All files in the `static` directory (including PDFs, images, `robots.txt`, and `sitemap.xml`) are automatically copied to the site root on render.

---

For more commands and options, see the