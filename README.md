# Westchester Dental Landing Page

Responsive dental implant landing page built with HTML, CSS, and JavaScript.

## Local preview

From the repository root:

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Open http://127.0.0.1:4173 in your browser.

## Files

- `dist/index.html`: page layout, styles, and assessment interaction.
- `dist/assets/westchester-family-dental.webp`: practice exterior photo.

The assessment is a browser-only preview. It does not submit or store leads on a server. Google review information is static content supplied for the design, not a live Google integration. Fonts load from Google Fonts.

For static hosting, publish the `dist` directory.
