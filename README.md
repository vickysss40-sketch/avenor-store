# AVENOR storefront — starter build

A responsive AVENOR storefront prototype with a metallic wordmark treatment, custom campaign hero art, and an auto-scrolling featured-product rail.

## Run locally
Open `index.html` in a browser. Product filtering, search, size selection, cart quantity changes, wishlist, and responsive navigation work in the browser. Cart and wishlist persist in localStorage.

## Important launch status
This is a **front-end prototype**, not a production commerce system. The checkout is intentionally a preview and does not create orders or collect payments. Login is a placeholder. Product photos are remote editorial placeholders and must be replaced with AVENOR-owned product photography before launch.

## Production integrations still required
1. Supabase: Auth, Postgres tables, Storage, row-level security.
2. Admin dashboard: secure role-based product, size/stock, order and coupon management.
3. Razorpay: server-created orders, signature verification, webhook reconciliation. Never expose secret keys in browser code.
4. Shipping provider: Shiprocket or chosen courier API, server-side label and tracking integration.
5. Email: transactional order confirmation, dispatch, password reset and newsletter provider.
6. Policies: shipping, returns, privacy, terms, contact details, GST/invoice and product size/fit information.
7. Production hardening: validation, rate limiting, anti-abuse, accessibility, SEO, analytics, backups and end-to-end testing.

## Suggested deployment
For this static preview, create a Render Static Site and set the publish directory to the folder containing `index.html`. For the production app, use a Next.js frontend plus server-side API routes/functions and Supabase; deploy the app with environment variables configured in the hosting dashboard.


## V3 navigation and footer update
- Header now includes Home, New Arrivals, Men's Apparel dropdown, Women's Apparel dropdown, Weightlifting Gear and Combat Equipments.
- Apparel dropdowns route into the relevant product category filters.
- Footer includes Quick Links, Top Selling, Policies, Blog/Journal, About, Contact and Return/Exchange placeholders.
- Oversized AVENOR wordmark added to the footer.
- Weightlifting and combat categories are clearly marked as future capsules until actual products are supplied.
- Policy and contact links are informational placeholders; publish reviewed legal copy and verified business contact details before launch.


## V4 colour refresh
- Updated visual palette to deep forest green, soft sage, warm ivory and muted clay accents.
- Applied palette consistently across header, hero, product cards, dropdowns, cart, modals and footer.


## V4 fresh color palette
- Deep pine green: #173B35
- Soft mint / paper: #F4F7F2
- Sage: #BBDCC8
- Electric soft lime accent: #D9EF72
The new palette updates navigation, buttons, marquee, product cards, story section, drawers, modals and footer.
