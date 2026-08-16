# Muqtadir Aohon Mozumder — local reconstruction

This is a local copy of the publicly delivered frontend at:

https://portfolio-of-muqtadir-aohon.netlify.app/

The page implementation is kept in `index.html`; the gallery images are stored under `assets/`.

## Run locally

From this directory, run:

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173/

The original page loads its Google Fonts stylesheet remotely, so an internet connection keeps typography identical to the deployment.
