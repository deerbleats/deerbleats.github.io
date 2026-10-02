# deerbleats.github.io

Static personal page based on **Massively by HTML5 UP**, with the original
CCA 3.0 attribution retained in the HTML, CSS and JavaScript. Third-party
scripts, styles, Sass sources, fonts and images remain unchanged.

## Editing and preview

Edit the personal content in `index.html`. The contact links are formatted
across lines *inside tags*, so editing them does not insert visible whitespace
between the linked icons. Link destinations, image dimensions, text, script
order and `CNAME` are unchanged. There is no build step or package installation.

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open `http://127.0.0.1:8765/` and stop the server with Ctrl-C when done.
This command only previews locally; it does not publish the site.

## Existing limitations

The page links to `NFC.html`, which is not included in this repository. Some
heading/container tags are unbalanced and browsers repair the markup. These
existing behaviors were retained rather than changing the DOM during source
cleanup. External Google Fonts availability may affect font rendering.
