# Destination photos

Drop a photo in here using the exact filename below and it appears on the site
automatically — no code change needed. Until a file exists, that card falls back
to its "photo to be added" placeholder, so nothing ever looks broken.

| Card        | Filename            |
|-------------|---------------------|
| Japan       | `japan.jpg`         |
| South Korea | `south-korea.jpg`   |
| Taiwan      | `taiwan.jpg`        |
| Thailand    | `thailand.jpg`      |
| Singapore   | `singapore.jpg`     |
| China       | `china.jpg`         |
| Vietnam     | `vietnam.jpg`       |

## What to supply

- **Shape:** the slot is 4:3 and the photo is cropped to fill it from the centre,
  so keep the subject away from the edges.
- **Size:** around 800×600 is plenty. Larger just costs visitors bandwidth.
- **Format:** `.jpg`. To use `.webp` or `.png` instead, update the `src` on the
  matching `<img>` in `index.html`.
- **Weight:** aim under ~200 KB each. Seven large photos noticeably slow the page.

## Licensing

Use photos you own or that are licensed for commercial use — this is a
commercial site. Unsplash, Pexels, and Wikimedia Commons all have suitable
options; check the specific licence on each image, as it varies per photo.

## Changing the alt text

Each `<img>` in `index.html` has a generic `alt` describing the country. Once you
know what the photo actually shows, make it specific — "Fushimi Inari shrine gates
at dawn" beats "Street scene in Japan" for both screen readers and search.
