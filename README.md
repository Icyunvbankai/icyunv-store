# ICYUNV Store

Mobile-first streetwear store app for the **ICYUNV** clothing label. UI mockups generated with [Stitch](https://stitch.withgoogle.com) (project: "ICYUNV Streetwear Store") — exported 2026-10-07, then finished with real product artwork and tiered pricing.

Neon acid-punk aesthetic: near-black `#0A0A0B`, neon green `#39FF14`, magenta `#FF2EA6`. Brand line: **"Zero Filler. All Value."**

## Pricing

| Item | Price |
|---|---|
| Lightweight tee | **$29** |
| Heavyweight tee | **$35** |
| Distressed heavyweight tee | **$45** |
| Hoodie | **$49** |
| Sweats | **$49** |
| Hat | **$35** |

The product detail screen prices tees dynamically: Standard Light → $29, Heavyweight Boxy → $35, Heavyweight + Distressed finish → $45.

## Screens

| Screen | Folder |
|---|---|
| Home & Drops — drop hero, countdown, product rail | `screens/icyunv_home_drops/` |
| Shop — filterable catalog grid | `screens/icyunv_shop_collection/` |
| Product Detail — gallery, size/fit/finish, tiered pricing | `screens/icyunv_product_detail/` |
| Cart | `screens/icyunv_cart/` |
| Checkout — Google Pay button (UI mockup, no real processing) | `screens/icyunv_checkout_flow/` |
| Order Confirmation | `screens/icyunv_order_confirmation/` |
| Lookbook — ZONA DEIECTUS editorial | `screens/icyunv_lookbook/` |
| About & Story | `screens/icyunv_about_story/` |

Each screen folder has `index.html` (self-contained mockup) and `preview.png`. Real product artwork lives in `images/` (ZONA DEIECTUS collection: Fallen Choir, SINS, Build Something, Ice Angel, Train Fight).

Design tokens: `design-system/DESIGN.md`.

## Status

UI mockups — checkout is explicitly labeled UI MOCKUP with no real payment processing. Real Google Pay merchant integration is separate follow-up work.
