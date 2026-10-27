# Storefront

Public-facing product catalog/storefront site for Meridian Communications —
separate from the internal `InventoryManagement` (IMS) admin tool, since this
one is customer-facing with a different audience, hosting, and auth model.

## Status

Not yet built. A Figma mockup is in progress, modeled loosely on the EPCOM
storefront layout: product search, an all-products catalog organized by
category (CCTV/surveillance, access control, two-way radios, GPS tracking,
residential security), and a "Contact Us" CTA in place of a cart/checkout —
this isn't an e-commerce site, it's a browse-then-contact catalog.

## Planned

- Tech stack: TBD
- Will likely read product/category data from the IMS system (`InventoryManagement`
  repo) via an API, rather than duplicating that data here
- Figma mockup link: TBD (will add once the mockup is in a shareable state)
