CRAFT BIZ — PWA App Icons
==========================
These icons are used when the website is installed as an app on mobile.
They are referenced in manifest.json.

  icon-192.png   → App icon at 192 × 192 px  (required)
  icon-512.png   → App icon at 512 × 512 px  (required)
  icon-180.png   → Apple Touch Icon (optional but recommended)

HOW TO CREATE
-------------
1. Start with your logo on a white or brand-colour background
2. Make it square: 512 × 512 px minimum
3. Export as PNG
4. Resize to 192 × 192 and 512 × 512 versions
5. Drop both here — they will be picked up automatically by manifest.json

QUICK TOOL
----------
Use https://realfavicongenerator.net to generate all icon sizes at once
from a single source image.

NOTE: Move icon files from here → images/ root once generated,
because manifest.json currently references "images/icon-192.png"
and "images/icon-512.png" (one folder up from here).
