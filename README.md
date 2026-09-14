# AURA Complete HTML Website

This package contains the website code AND every local image, video, audio and Virtual Try On garment asset referenced by the code.

## Important folder rule
Keep the `assets` folder beside `index.html`. Do not upload only the HTML files. The expected structure is:

```
index.html
about.html
categories.html
product.html
blog.html
...
assets/
  styles.css
  app.js
  tryon.js
  campaign-hero.webp
  ...
```

## Deployment
Upload the entire contents of this folder to the web root for `aura.io.vn`. The included `CNAME` contains `aura.io.vn`. Camera access requires HTTPS or localhost.

## Assets
See `assets/manifest.json` for the exact files referenced by the code. All referenced local assets were checked at build time.

## Fonts
Anton and Poppins are loaded from Google Fonts with system fallbacks in CSS. Font files are not bundled locally.

Build audit result: 0 missing referenced local assets.

## Homepage refinement

The homepage now uses newly created HD campaign assets instead of screenshot crops. The Live Try On hero action sits below the image, collection and product imagery uses full-image containment, Featured Product stripes were removed, Feedback uses an AURA-branded shoe visual, and the footer uses a responsive code-rendered AURA logo.

The visual guide is a newly rendered 1920 x 1080 H.264 animation with four complete steps. It autoplays silently, loops, remains controllable, and is displayed at its original 16:9 ratio without cropping.

## About Us refinement

The About Us hero now uses an original 1536 x 1024 AURA shopping bag image with the whole bag visible. The Story and Mission panels use balanced padding, and the old team collage has been replaced by six scalable illustrated leadership figures with the requested names and roles.

The AURA Story is a new 1920 x 1080 H.264 kinetic film with narration, a separate audio player and a nearby transcript. The video, poster, bag and team figures use full-image containment so their compositions are not cropped. The About Us footer now matches the Homepage footer and uses the large responsive AURA wordmark.

## Product Categories and product detail refinement

The category hero now uses a complete AURA edit with the orange shoe restored. Tailoring and knitwear cards use sharp palette-matched garments with no scan stripes, while the cobalt heel, Poppy mini bag and orange sunglasses each have their own full-frame product asset. The Category Guide is concise and uses four new supporting visuals that are not reused elsewhere.

Each product detail view now shows one flat product view, one full model view and a product-specific 1920 x 1080 commercial film. The film fades between the complete product and worn look with an original cheerful instrumental bed. Product galleries and Blog media use containment so footwear, bags, glasses and visual guides remain fully visible.

## Contact and Smart Mirror refinement

Contact now uses a 1920 x 1080 AURA studio commercial with products, models and two team introduction cards, plus six consistent human figure cards using the About Us names and roles. Enterprise now has a prominent FOR PHYSICAL RETAIL badge, an interactive colour-changing mirror demo, and a full-frame Smart Mirror guide covering Bluetooth pairing, look selection, reflection and turn-around styling. All page endings share the large AURA logo panel used on Home.
