# مختبر شفرة قيصر — Caesar Cipher Lab

An Arabic, right-to-left educational web app recovered from the original project.

## Run

Open `index.html` in a modern browser. No installation, build step, or external dependencies are needed.

For local HTTP preview, run `python -m http.server 8000` from this directory and visit http://localhost:8000.

## Features

- Live encryption and decryption with shifts from 1 to 25.
- Uppercase and lowercase Latin letters; other characters remain unchanged.
- Alphabet substitution map, reverse operation, example, and reset.
- Copy output (requires browser clipboard permission; manual copying is supported).
- Four decoding challenges with hints and answer feedback.
- Responsive Arabic interface and offline operation.

## Tests

With Node.js installed, run:

```sh
node test.cjs
```

Tests cover all 25 shifts, round trips, mixed case, non-Latin characters, alphabet mapping, mode reversal, reset, empty input, and all four challenges. These are logic and simulated-DOM checks, not a full browser test.

## Hosting

The app is a static page and can be served by any static host. To use GitHub Pages, select **Settings → Pages → Deploy from a branch → main → / (root)**. Uploading the source does not itself enable Pages.

Caesar Cipher is an educational historical cipher and is not suitable for protecting sensitive data.
