# Muqtadir Aohon Mozumder — portfolio archive

This is a locally runnable copy of the publicly delivered frontend at:

https://portfolio-of-muqtadir-aohon.netlify.app/

The page implementation is kept in `index.html`; the gallery images and self-hosted fonts are stored under `assets/`.

## Run locally

From this directory, run:

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173/

The page is self-contained and does not require Google Fonts or another third-party stylesheet at runtime.

## Design notes

The interface uses a restrained CRT treatment as its single visual signature. Gallery images remain the focus; the previous boot screen, fake camera telemetry, animated mascot decorations, and duplicated chromatic effects were removed for faster access and a clearer portfolio hierarchy.
