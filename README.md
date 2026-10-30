# Calzado Nineteen (Wholesale Footwear Catalog)

A static product showcase for a wholesale shoe brand: a landing page and a catalog view with product photos.

## Why
A fast, zero-dependency page that lets buyers browse the current range on a phone, with photos organized by drop.

## Key features
- Brand landing page (`index.html`)
- Catalog view with product grid (`vitrina.html`)
- Organized product photo library (`assets/images/`)

## Stack
HTML, CSS and JavaScript. No build step.

## Structure
```
index.html        Landing page
vitrina.html      Catalog
grupos.json       Post-to-group mapping for the catalog images
assets/images/    Product and catalog photos
```

## How to run
Open `index.html` in a browser, or serve the folder with any static server:
```bash
python -m http.server 8000
```

## Status
Static site, complete for display. Contact details and pricing are hard-coded in the HTML. `grupos.json` contains contact-like data and should be reviewed before publishing.

Built by Monoga (https://github.com/Monoga2025)
