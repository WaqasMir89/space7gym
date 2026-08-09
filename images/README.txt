SPACE7 GYM — PHOTO SLOTS
========================

The site is pre-wired to show photos automatically. Just drop your image files
in this folder with the exact filenames below (JPG/PNG/WebP, any size — they
are cropped to fit). Until a file exists, a branded placeholder tile is shown
instead, so the site never looks broken.

  images/gym-floor.jpg          -> About section (portrait 4:5, ~800x1000)
  images/trainer-arsalan.jpg    -> Trainer card (portrait 3:4, ~700x900)
  images/trainer-habiba.jpg     -> Trainer card (portrait 3:4, ~700x900)
  images/trainer-saad.jpg       -> Trainer card (portrait 3:4, ~700x900)
  images/gallery-1.jpg          -> Gallery tile (tall, ~600x800)
  images/gallery-2.jpg          -> Gallery tile (square-ish, ~600x600)
  images/gallery-3.jpg          -> Gallery tile (wide, ~1200x600)
  images/gallery-4.jpg          -> Gallery tile (square-ish, ~600x600)
  images/gallery-5.jpg          -> Gallery tile (wide, ~1200x600)
  images/gallery-6.jpg          -> Gallery tile (square-ish, ~600x600)

Tips
----
- Sizes are suggestions only; object-fit:cover crops automatically.
- Keep filenames lower-case, no spaces (use dashes).
- Renaming a file here? Update the matching <img src="images/..."> in index.html.
- Recommended: compress to under ~300KB each (e.g. https://squoosh.app) so the
  static site stays fast on mobile data.
