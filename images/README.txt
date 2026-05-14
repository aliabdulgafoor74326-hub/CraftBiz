CRAFT BIZ — Images Folder Guide
=================================
Open the README.txt inside each subfolder for exact filenames.

FOLDER MAP
----------
images/
  logo/          → Logo, brand assets, team photo
  icons/         → PWA app icons (icon-192.png, icon-512.png)
  hero/          → Landing page hero / banner image
  laser/         → Laser Cutting products   (3 products)
  cnc/           → CNC Milling products     (2 products)
  3d/            → 3D Printing products     (3 products)
  tshirt/        → T-Shirt, Cap, Tote Bag   (3 products)
  gifts/         → Corporate Gifts          (12 products)
  homedecor/     → Home Decor products      (3 products)
  wedding/       → Wedding Cards products   (2 products)
  resin/         → Resin & Art products     (2 products)
  stationery/    → Stationery & ID products (3 products)
  services/      → Service page banners & gallery images (one subfolder per category)
  blog/          → Blog post images

HOW TO ADD A PRODUCT IMAGE
---------------------------
1. Open the correct category folder above
2. Read its README.txt for the exact filename required
3. Rename your photo to match exactly (e.g. mug-printing.jpg)
4. Drop it in — Live Server auto-refreshes
5. If a file is missing, the website shows the emoji instead — nothing breaks

IMAGE SPECS (all product images)
----------------------------------
• Size:    800 × 600 px minimum (4:3 ratio)
• Format:  JPG, PNG, or WEBP
• Weight:  Under 300 KB per image
• Style:   Plain/light background · centred · good lighting

MULTIPLE IMAGES PER PRODUCT
-----------------------------
Each product can show up to 3 gallery images.
Add extra image paths to the imgs:[] array in the PRODUCTS section of index.html:
  imgs:["images/laser/acrylic-keychains.jpg",
        "images/laser/acrylic-keychains-2.jpg",
        "images/laser/acrylic-keychains-3.jpg"]
