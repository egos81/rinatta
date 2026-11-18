# Rinatta.com — domain acquisition landing page

A dependency-free static site for selling the **domain name only**. This revision keeps the original Rinatta palette and circular brand emblem while replacing the crowded, multi-section page with one clear offer.

## Buyer journey

- Understand **Rinatta.com** in the hero.
- See the **$4,995 USD** fixed Buy Now price.
- Click **Buy the domain** to open the verified Spaceship SellerHub cart link.
- Or click **Make an offer** to send an offer to the existing, seller-confirmed working inbox `info@rinatta.com`.
- A compact strip explains the authentic invented-name origin: Italian `ri-` (“again/anew”) + informal Norwegian `natta` (“good night”).

The domain only is for sale; there is no bundled business, product or trademark.

## Verified payment link

`https://www.spaceship.com/marketplace/buy-now/uNrtw6VpMA6Lfl_MjnkqHo/rinatta.com`

The domain listing was reported `on_sale` by the owner's authenticated Spaceship MCP check. If the listing is recreated, verify the cart link again.

## Design and deployment

The page uses the existing dark blue-green color system, radial background, metallic circular ring, favicon and `CNAME`. The stylesheet is referenced as `styles.css?v=3` to force the browser to request updated CSS instead of reusing a stale cached asset.

Files: `index.html`, `styles.css`, `favicon.svg`, `CNAME`.

Static HTML/CSS only. GitHub Pages deploys from `main`; merging a PR may publish it automatically.

## QA

Required before and after deployment: verify the two CTA destinations, price, page responsiveness, and updated stylesheet; verify live page contains a styled primary button and neither the old “Coming Soon” content nor the previous long sector sections.
