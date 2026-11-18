# Rinatta — domain-for-sale page

Dependency-free static landing page for `rinatta.com`, adapted from the original coming-soon design.

## Preserved visual identity

This change retains the existing dark blue-green palette, Helvetica/Georgia typography, radial nighttime background, delicate grid and circular metallic Rinatta emblem. The existing favicon and CNAME are unchanged.

## Sale information

- **Asking price:** $4,995 USD.
- **Asset offered:** the `rinatta.com` domain only, not an operating business, products or registered trademark rights.
- **Story:** an invented European-inspired name from Italian `ri-` (again/anew) + informal Norwegian `natta` (good night).
- **Potential applications:** Sleep Technology, Wellness/Relaxation and Bedding/Sleepwear.

## Important: checkout link still requires verification

The official Spaceship SellerHub Buy Now URL was not available to this change. We do not fabricate a purchase link.

Currently the two purchase CTAs **request a checkout link** by emailing the pre-existing `info@rinatta.com` address. The offer action also uses email. **Verify this inbox is operational before merging.**

After listing is confirmed in Spaceship:

1. Read `marketplace_listing_get` for `rinatta.com` using authenticated Spaceship MCP.
2. Verify listing status and the $4,995 Buy Now price.
3. Obtain the actual `cartLinks.buyNow` value and verify the HTTPS host and domain.
4. Update the two purchase CTAs in `index.html` to point to that official URL, and only then label them as direct Buy Now buttons.
5. Keep any negotiated offers under the seller's manual control.

## Preview and deployment

Open `index.html` in a browser or serve with a static server. Existing `CNAME` is `rinatta.com`; merging into `main` may deploy to the current site through GitHub Pages. No build process, JavaScript, DNS changes or additional services are required.
