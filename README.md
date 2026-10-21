# TVC Deals storefront

A responsive React storefront built with Vite and Lucide icons.

## Development

Requires Node.js 22 or newer.

```sh
npm ci --cache /workspace/.npm-cache
npm run dev -- --port 5173
```

Production: `npm run build`. Serve the build with `npm run preview`.

Features include category filtering, product search, sorting, quick-view dialogs, saved favorites, and a shopping bag with quantity controls. The bag and favorites persist in local storage. Layouts adapt to desktop and mobile.

Products, ratings, prices, and policies are illustrative. Checkout does not accept payments or place orders. Newsletter signup does not transmit data. Connect a product catalog, order/payment service, and email provider before launch.

## Demo assets

Images are served locally to avoid external image-host dependencies. Sample image sources:

- https://github.com/WebDesignMastery/FurniShop_29-06-24
- https://github.com/Tvang93/CookwareWebsite
- https://github.com/tech2etc/Build-and-Deploy-Ecommerce-Website
- https://github.com/bedimcode/responsive-landing-page-headphones
- https://github.com/codewith-salman/Skin-Care-Products-Website

Replace demonstration product images with your licensed product photography before publishing a commercial store. Fonts: Manrope (Google Fonts) and DM Sans (Google Fonts, distributed in Ovi/DummyJSON). Font license: SIL Open Font License.
