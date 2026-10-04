# Dose Standard — Phase 1

Working-name prototype for a premium but accessible home-coffee store.

## What Phase 1 includes
- Conversion-first fixed navigation
- Scroll-controlled stainless espresso-machine hero concept
- Portafilter enter / rotate / lock sequence
- Extraction reveal
- Shop-by-ritual merchandising
- Best-seller cards with lightweight basket interaction
- £5 Shelf conversion block
- Responsive mobile treatment
- Cloudflare Workers + Vite configuration

## Important visual rule
The current machine/products are CSS concept geometry only. They are **not intended as final production imagery**. Production should use:
1. real espresso-machine photography/video or licensed/commissioned source material;
2. authentic supplier product photography;
3. purpose-built 3D models only where interaction requires them;
4. AI visuals only for concept work, not inventory credibility.

## Local development
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```

## Cloudflare deployment
After authenticating Wrangler with the intended Cloudflare account:
```bash
npm run deploy
```

The project uses Cloudflare's current Vite/Workers static-assets approach. No Shopify dependency exists in Phase 1.

## Next implementation phase
- Replace working name after naming/domain checks
- Add real hero asset/model pipeline
- Add product catalogue data model
- Add search/filter UI
- Add cart persistence
- Add Stripe Checkout + Cloudflare Worker backend
- Evaluate open-source commerce backend once requirements justify it
