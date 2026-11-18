# Rinatta — domain-for-sale page

Dependency-free static landing page for `rinatta.com`, adapted from the original coming-soon design.

## Preserved visual identity

This change retains the existing dark blue-green palette, Helvetica/Georgia typography, radial nighttime background, delicate grid and circular metallic Rinatta emblem. The existing favicon and CNAME are unchanged.

## Sale information

- **Asking price:** $4,995 USD.
- **Asset offered:** the `rinatta.com` domain only, not an operating business, products or registered trademark rights.
- **Story:** an invented European-inspired name from Italian `ri-` (again/anew) + informal Norwegian `natta` (good night).
- **Potential applications:** Sleep Technology, Wellness/Relaxation and Bedding/Sleepwear.

## Official Spaceship Buy Now link

The seller confirmed the listing has status `on_sale` through the authenticated Spaceship MCP `marketplace_listing_get` tool. The returned `cartLinks.buyNow` value was:

`https://www.spaceship.com/marketplace/buy-now/uNrtw6VpMA6Lfl_MjnkqHo/rinatta.com`

Both on-page Buy Now buttons link directly to this Spaceship checkout and open in a new tab; no payment is collected on this site.

The **Make an offer** link still uses `info@rinatta.com` so the seller can handle negotiations personally. Verify this email inbox is operational before merging, or replace it with an official, validated marketplace negotiation link.

If the SellerHub listing is changed or recreated, retrieve the current `cartLinks.buyNow` again and update both button URLs. Do not assume links remain valid indefinitely.

## Preview and deployment

Open `index.html` in a browser or serve with a static server. Existing `CNAME` is `rinatta.com`; merging into `main` may deploy to the current site through GitHub Pages. No build process, JavaScript, DNS changes or additional services are required.
