# Wall Plate Finder

A lightweight, responsive configurator built for Shopify (RiteAV) that helps
customers find the exact custom wall plate, patch panel, or floor box they need
without digging through the catalog manually.

## What it does

- Add any number of **jacks** (CAT5E, CAT6, CAT6A/CAT7 shielded, HDMI, USB,
  RCA, COAX, F81, BNC, Speaker, Toslink, Phone, 3.5mm, Banana, Fiber LC/SC,
  DC Power, or Blank) and the tool tallies how many of each type you picked.
- Add up to 6 **gangs/outlets** (Outlet, Tamper Outlet, USB Outlet, Round
  Outlet, Brush, GFCI, or No Outlet) for plates that combine jacks with
  power outlets.
- Choose a plate **Type** (Wall Plate, Patch Panel, Floor Box) and **Color**
  (Black, Light Almond, White, Brown, Ivory, Wood, Stainless Steel).
- The title updates live as a plain-English summary (e.g. `4 CAT6 Wall Plate
  GFCI Black`) so customers can confirm what they're about to search for.
- Clicking **Search** builds a query from those selections and sends the
  customer straight to the matching RiteAV product search results.

## Why

Instead of a customer scrolling through hundreds of wall plate combinations,
they build the exact spec they need in a few clicks and land directly on the
closest matching product(s).

## Usage

Paste the contents of `wall_plate_configurator.html` into a Shopify
**Custom Liquid** block/section. It's self-contained - no external
dependencies, fully responsive, and works on mobile.