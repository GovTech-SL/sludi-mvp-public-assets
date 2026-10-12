# SLUDI MVP Public Assets

Public static assets used by the SLUDI MVP and its related interfaces. This repository contains only reusable assets; it has no application code or build process.

## Contents

| Directory | Contents |
| --- | --- |
| `common/` | Shared Barlow font files and background images. |
| `drp/` | Digital Registration Platform (DRP) logo and letterhead image. |
| `sludi/` | SLUDI logos and browser icons (favicon, application icon, and Apple touch icon). |

Each asset group includes a `usage.txt` file where a known consuming application or page has been recorded.

## GitHub Pages base URL

Assets published through GitHub Pages are available below this base URL:

`https://govtech-sl.github.io/sludi-mvp-public-assets/`

## Using an asset

Reference an asset using the GitHub Pages URL, or copy it into the consumer application's public/static directory. For example:

```html
<img src="https://govtech-sl.github.io/sludi-mvp-public-assets/sludi/images/logo.svg" alt="SLUDI">
```

```css
@font-face {
  font-family: "Barlow";
  src: url("https://govtech-sl.github.io/sludi-mvp-public-assets/common/fonts/Barlow/Barlow-Regular.ttf") format("truetype");
  font-weight: 400;
  font-style: normal;
}
```

If your application serves a copied version locally, replace the base URL with its local public path.

## Asset guidelines

- Keep shared files under `common/`; keep product-specific branding in its respective directory.
- Preserve the existing filenames when updating assets so consuming applications do not need path changes.
- Add or update the applicable `usage.txt` entry when an asset is adopted by another page or application.
- Check branding and licensing requirements with the asset owner before redistributing or modifying assets.
