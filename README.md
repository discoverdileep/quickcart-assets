# QuickCart assets

Public images for the QuickCart POC (`discoverdileep/sdd-quickcart-poc`), served through jsDelivr:

```
https://cdn.jsdelivr.net/gh/discoverdileep/quickcart-assets@v1.0.0/products/<file>.png
```

`products/` holds one 800×800 PNG per product in the API examples (`specs/api/openapi.yaml`), named `<id>-<name>.png`.
They are rendered from the `ProductArt` illustrations in the QuickCart design canvas, each on its tile tint from the SCR-01 web frame.

Releases are full semantic-version git tags (`v1.0.0`, `v1.1.0`, …): jsDelivr does not resolve a short tag like `v1`. Never move a tag; publish changed images under a new tag and update the URLs in the spec.
