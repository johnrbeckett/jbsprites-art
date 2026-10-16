# jbsprites-art

Full-size source sheets for [jbsprites](https://github.com/johnrbeckett/jbsprites). Private.

- `<family>/originals/<NN>-<name>.png` with its grid JSON: the sheets `scripts/make_sprites.py` in jbsprites cuts into 160 px sprites.
- `<family>/overrides/<id>-source.png`: editable sources for hand-corrected sprites. The served webp lives in jbsprites under `<family>/overrides/`.

Kept apart from jbsprites so its release tags stay small enough for jsDelivr (50 MB package limit). Split out 2026-10-16, before jbsprites v10; tags v1 to v9 there still carry the sheets.
