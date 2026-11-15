# UNILEATHER React Landing Page

## Run locally

```bash
npm install
npm run dev
```

## Functional calls to action

- Header and hero Shop Now / Explore Jackets buttons scroll to the product section.
- Navigation links scroll to their matching sections; the mobile menu closes after navigation.
- Color cards filter the recommended jackets by Chocolate or Black.
- View All Jackets resets the product filter.
- Clicking a product card/image opens a full-screen image viewer; the complete source image is shown uncropped with `object-fit: contain`. Press Escape or click outside to close it. The viewer also includes Add to Cart.
- Add to Cart updates the order summary and quantity controls update/remove items.
- WhatsApp checkout opens a pre-filled order message including item quantities and totals.
- Favorite buttons toggle the saved state and show a confirmation.
- Style guide cards change the active styling tip; View Style Tips advances to the next tip.
- Review arrows and dots switch the visible customer reviews.
- Support and contact CTAs open WhatsApp with a pre-filled support message.
- Watch Video opens a modal with links to leather-jacket styling videos and the on-page Style Guide.
- Footer social icons open Facebook sharing, Instagram, and YouTube styling search.

## Store settings to customize

Open `src/main.jsx` and update:

- `WA_NUMBER`: WhatsApp number in international format without `+` (currently `8801974446003`).
- `SOCIAL_LINKS.instagram`: replace with your actual Instagram profile URL.
- `SOCIAL_LINKS.youtube`: replace with your brand's YouTube channel URL if available.
- Product names and prices in the `products` array.
- Delivery fee in the `delivery` calculation.

All product and style images are stored locally in `public/images/`.

## Note

This is a frontend demo. WhatsApp checkout sends the order details to your WhatsApp; it does not create a database order or process online payment. Replace the example customer reviews with verified customer feedback before publishing.
