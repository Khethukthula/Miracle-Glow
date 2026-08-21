# Miracle & Glow 🌹🕯️

A handcrafted rose and scented candle e-commerce website built for **Miracle & Glow**, based in Pretoria, South Africa.

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero banner, about preview, bestsellers, testimonials |
| `shop.html` | Full product catalogue with cart and checkout |
| `about.html` | Brand story, mission, and values |
| `contact.html` | Contact form with EmailJS integration |
| `soon.html` | Coming soon placeholder for social media links |

---

## Features

### Shop
- 16 products across two categories: Roses 🌹 and Candles 🕯️
- Filter by category (All / Roses / Candles)
- Pagination — 8 products per page, resets on filter change
- Lazy loading on product images for performance

### Ribbon & Add-On Customisation (Roses only)
- Clicking "Add to Cart" on a rose opens a customisation modal
- 24 ribbon colour options to choose from (required before adding)
- 7 optional add-ons with individual prices:
  - LED Fairy Lights — R95
  - Premium Glass Vase — R250
  - Clear Acrylic Display Box — R180
  - Scented Floral Spray — R60
  - Faux Crystal Center Pins — R80
  - Handwritten Calligraphy Card — R50
  - Decorative Glitter Dusting — R30
- Live price update as add-ons are selected

### Cart
- Persistent cart using `localStorage` — survives page refresh
- Shows item breakdown: product name, ribbon colour, each add-on
- Quantity controls and item removal
- Ribbon colour can be changed directly from the checkout summary

### Checkout
- Delivery information form with front-end validation:
  - Full name, email format, SA WhatsApp number, address, city, 4-digit postal code
- Card payment is intentionally disabled — orders are confirmed via WhatsApp/email
- On submission, order details are sent silently in the background


## Tech Stack

- Plain HTML, CSS, JavaScript — no framework or build tool required
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [EmailJS](https://www.emailjs.com/) for serverless email delivery
- `localStorage` for cart persistence

---

## Contact & Business Info

- **Email:** hello@miracleglow.co.za
- **WhatsApp / Phone:** +27 69 194 4529
- **Location:** Pretoria, South Africa
- **Website:** [miracleglow.co.za](https://miracleglow.co.za)

```bash
# Using VS Code Live Server extension — right-click index.html > Open with Live Server

---

&copy; 2026 Miracle & Glow. Made with 💕 in South Africa.
