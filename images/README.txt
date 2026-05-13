CRAFT BIZ — Product Images Guide
==================================
Each category folder holds the product images for that section.
The website automatically loads images when you drop them in.

FOLDER STRUCTURE
----------------
images/
  laser/          → Laser Cutting products (3 images)
  cnc/            → CNC Milling products (2 images)
  3d/             → 3D Printing products (3 images)
  tshirt/         → T-Shirt Printing products (2 images)
  gifts/          → Corporate Gifts products (4 images)
  homedecor/      → Home Decor products (3 images)
  wedding/        → Wedding Cards products (2 images)
  resin/          → Resin & Art products (2 images)
  stationery/     → Stationery & ID products (3 images)

HOW TO ADD AN IMAGE
-------------------
1. Open the folder for the right category (e.g. images/laser/)
2. Read the README.txt inside that folder for the exact filename
3. Rename your image to match EXACTLY (e.g. acrylic-keychains.jpg)
4. Drop it in the folder
5. Refresh the browser — the image shows automatically

IMAGE SPECS
-----------
• Size:   800 × 600 px minimum (4:3 ratio recommended)
• Format: JPG, PNG, or WEBP
• Size:   Under 300 KB per image for fast loading
• Style:  Plain/light background, good lighting, product centred

ADDING EXTRA IMAGES (for the product detail gallery)
------------------------------------------------------
You can add up to 3 images per product. Add the extra paths to the
imgs:[] array in the PRODUCTS section inside page 1.html.

Example (product #3 with 3 images):
  imgs:[
    "images/laser/acrylic-keychains.jpg",
    "images/laser/acrylic-keychains-2.jpg",
    "images/laser/acrylic-keychains-3.jpg"
  ]

FALLBACK
--------
If an image file is missing, the website automatically shows
the emoji icon instead — so nothing breaks.
