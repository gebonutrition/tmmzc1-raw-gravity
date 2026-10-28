# TMMZC1 — Raw Gravity × Take My Muffin

Production-ready static landing built from the provided Desktop.dc.html / Mobile.dc.html visual references. Those `.dc.html` files are design references only and the generated `support.js` runtime is intentionally not included in production.

## Included
- Responsive desktop layout (up to 1200px) and mobile layout (390px centered)
- Product carousel with five provided images
- Continuous benefits ticker and product facts row
- A+ images in the specified desktop/mobile order and comparison table
- Amazon attribution URL on both purchase buttons
- Meta Pixel `1632582321547641`: PageView, ViewContent, InitiateCheckout, Lead, plus no-JavaScript PageView fallback
- `/api/subscribe` Klaviyo endpoint

## Vercel environment variables
Configure `KLAVIYO_API_KEY` and `KLAVIYO_LIST_ID` for Production and Preview. The values should be copied from the existing Raw Gravity Vercel project via Vercel's secure environment-variable settings; do not store them in this repository.

No TikTok pixel is installed because a TikTok Pixel ID was not supplied.

## Asset sources
All images in `assets/` are the assets supplied with the task.
