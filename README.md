# दीप शिल्प स्टुडिओ | Deep Shilp Studio

A warm, premium storefront for a handcrafted candle studio, with Marathi-first branding and WhatsApp ordering.

## Brand identity

- **Marathi name:** दीप शिल्प स्टुडिओ
- **English name:** Deep Shilp Studio
- **Marathi tagline:** हातांनी घडवलेले सौंदर्य, प्रकाशाची उब.
- **English tagline:** Handcrafted with love. Made to glow.
- **Palette:** warm ivory, earthy terracotta, muted gold, cocoa brown
- **Typography:** Noto Sans Devanagari for Marathi; Playfair Display and DM Sans for editorial English typography

## Features

- Responsive storefront with collection, brand story, custom-order form, and cinematic candle photography.
- Marathi and English product names/descriptions, editable from the storefront.
- WhatsApp order messages include the required Marathi opening, product name, price, variant, and quantity.
- Custom order enquiries open WhatsApp with the visitor's request.
- Product-photo preview and an editable cinematic AI image prompt, plus a local approval checkbox.
- SEO title, description, Open Graph metadata, and mobile theme colour.

## Run locally

Open `index.html` in a browser or serve this repository with any static web host (GitHub Pages, Netlify, etc.). No build step is required.

## Configure WhatsApp ordering

Open **Store Settings** in the footer and enter the business WhatsApp number with country code, digits only (for India, use `91` followed by the mobile number). The number is stored in that browser's local storage.

**For production:** replace the local-only setting with a clearly configured public business number or a site-level configuration before launch. Do not ask customers to enter a number; this is the shop's destination number.

## Product editing and photography

The product edit controls and approval checkbox are browser-local convenience features. They do not write back to GitHub and do not publish uploaded images. To make permanent changes for all visitors, edit `index.html` and commit the changes. Use the generated image prompt in your preferred image-generation tool, review the output, and commit the approved image asset before switching the product image URL.

## Brand guardrails

- Use **दीप शिल्प स्टुडिओ** prominently and **Deep Shilp Studio** for English SEO.
- Keep Marathi typography Unicode-compatible.
- Never use the previous brand name in the storefront.
