# AdSells

Desktop prototype for a marketplace of physical and digital advertising placements.

## Development

```sh
npm install
npm run dev
npm run build
```

TypeScript, Vite, HTML and CSS. Static deployment from `dist/`. Designed for desktop widths of 1280 px and up.

## Included

- Purchase catalog with search, categories, location, price, favorites, sorting and averages grouped by billing period.
- Seller dashboard, offer creation and editing, JPEG/PNG/WebP uploads with client-side compression.
- Editable profile name, photo, location and biography; clearly marked sample reviews.
- Demo booking and escrow flow, evidence submission, revision requests, resubmission, approval and simulated payout.
- Local browser persistence under `adsells-v1`. No authentication or backend database.

## Demo boundaries

All sellers, reviews, offers and payments are sample data. The role switch intentionally exposes both sides of the same demo transaction. No real payment, financial custody, social-network validation or public listing submission occurs. Hosting is owner-private.

Listing photographs are illustrative stock images downloaded from Unsplash. Profile photos are user-supplied; the initial avatar uses an initial.

## Verified

- TypeScript validation and production Vite build.
- Desktop visual inspection of catalog and profile in the browser.
- Search empty state and weekly average (120 + 150) / 2 = 135 USD.
- Booking confirmation requires the conditions checkbox.
- Reserve > submit evidence > request revision > resubmit > approve > simulated payout.
- Create an offer; seller and catalog averages recalculate.
- Edit profile and reload; profile, listing and transaction persist.

Image-upload processing is implemented but was not exercised through the browser during this pass.
