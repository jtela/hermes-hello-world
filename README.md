# Hello World

A responsive, accessible welcome page made with plain HTML and CSS. No JavaScript, external assets, or build step.

Repository: https://github.com/jtela/hermes-hello-world

Intended website: https://jtela.github.io/hermes-hello-world/

Publication and live verification are managed separately; this source does not claim that deployment is complete.

## Files

- `index.html` — semantic page and welcome message.
- `styles.css` — fluid layout, system fonts, and visible link focus.
- `.nojekyll` — static publishing marker.
- `README.md` — this guide.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ and stop the server with Ctrl+C.

The stylesheet uses a relative path, so the same files work at the website's project subpath. Python is only a local preview convenience, not a runtime dependency.
