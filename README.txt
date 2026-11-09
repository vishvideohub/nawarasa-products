NAWARASA PRODUCTS — website source
==================================

Deployed by Cloudflare Pages from this repository's root (nawarasa.pages.dev).
Push to `main` and the site rebuilds automatically.

FILES
-----
index.html             The whole site: markup, CSS and JS in one file.
img/                   Photos. Referenced by index.html, cached for a year.
og.jpg                 1200x630 preview shown when the link is shared.
apple-touch-icon.png   180x180 icon for "Add to Home Screen" on iPhone.
_headers               Cloudflare cache rules. Do not rename.


SETTING PRICES
--------------
Open index.html and find the PRODUCTS block near the top of the <script>
at the bottom of the file:

    watalappan:{ name:"වටලප්පන්", category:"සාම්ප්‍රදායික රස", price:null },

Replace null with the price in rupees, e.g. price:350

That one change shows the price on the product card, adds line maths to the
order bag, shows a total above the send button, and puts a total in the
WhatsApp message. Any product left as null keeps saying "මිල විමසන්න", and
mixing priced with unpriced products is fine — the total only appears once
every product in the bag has a price.


REPLACING A PHOTO
-----------------
Drop the new file in img/ using the SAME filename. Crop it to 3:2 first
(e.g. 900x600) — the layout expects that shape. If you change the filename,
update the matching <img src> AND its width/height attributes in index.html,
or the page will jump around while loading.


TYPOGRAPHY
----------
Headings use Abhaya Libre, a Sinhala serif. Body text uses Noto Sans Sinhala.
Small Latin labels use DM Sans. All three load from Google Fonts; Abhaya
Libre ships a separate Sinhala subset, so only what is needed downloads.


THEME
-----
The site follows the visitor's phone or computer light/dark setting, and the
sun/moon button in the header overrides it. The choice is remembered per
browser; switching back to match the system clears the override.

Colours are CSS variables at the top of the <style> block. Edit the :root
block for light. Dark is declared TWICE on purpose — once under
@media (prefers-color-scheme: dark) and once under :root[data-theme="dark"]
— so a change to one must be made to the other.


ORDERING
--------
Orders are composed as a WhatsApp message from the customer's bag and
details. There is no payment processing and no server; nothing is stored
anywhere except in the customer's own browser.

    077 807 7332 -> https://wa.me/94778077332
    076 110 5232 -> https://wa.me/94761105232


KNOWN TODO
----------
- Product photos are illustrative stock images. Replace them in img/ with
  real photos of your own products, cropped to 3:2.
- Prices are not set yet (see above).
