# Regal Collision Ltd.

Public website for Regal Collision Ltd., a collision repair and auto body shop in Richmond, BC.

The site is plain HTML and CSS. It does not use tracking scripts. It is meant to be published with GitHub Pages at [www.regalcollisionltd.com](https://www.regalcollisionltd.com).

## Pages

- `index.html` — home
- `privacy/index.html` — privacy policy (`/privacy`)
- `CNAME` — custom domain `www.regalcollisionltd.com`

## Add gallery photos

Save real shop photos in `images/gallery/`. Use these exact file names:

- `01-before.jpg` and `01-after.jpg` — the comparison slider
- `02-before.jpg` and `02-after.jpg`
- `03-before.jpg` and `03-after.jpg`

JPG files work as-is. If a photo is a PNG, either save it as JPG with the name above, or change that frame’s file name in `index.html`.

Refresh the site after the files are in the folder. Until a file is there, that frame stays a placeholder. Do not use stock photos of cars that are not this shop’s work.

To add another pair, copy one before/after block in `index.html` and use the next number (`04-before.jpg`, `04-after.jpg`).

Design notes for this version are in `design-notes.md`.

## Credential logos

The home page shows the I-CAR Gold Class logo, saved at `images/badges/icar.png`.

The ICBC badge is commented out in `index.html` and is not shown. Do not publish it until ICBC gives written approval. After that approval, uncomment the placeholder and save the official file as `images/badges/icbc.png`. Do not download or copy logos from the web. Use only a file ICBC gives you.
