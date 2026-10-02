# Gawade Multispeciality Hospital — V2

This V2 keeps the clean Gajanan Hospital information architecture while aligning the visual identity more closely with Gawade Hospital.

## V2 changes
- Gawade-inspired blue / aqua palette with warm orange call-to-action accents.
- Real Gawade Hospital logo loaded from the current public hospital website, with a local fallback.
- Rich desktop hero using the hospital place photograph referenced by the current hospital website.
- Actual public doctor photographs for the lead doctors and several specialists, with graceful fallbacks.
- Real service imagery referenced from Gawade Hospital public service pages.
- Embedded Google Maps location plus direct Google Maps / review links.
- Google review module showing the 4.8 / 201-review snapshot displayed on the current hospital website at build time. Ratings can change.
- English / Marathi toggle with persistent language selection for patient-facing navigation and core content.
- Responsive desktop, tablet and mobile layouts.
- WhatsApp appointment flow remains on +91 9766334466 as shown by the hospital website.

## Important production note
The hospital/doctor/department photographs are referenced from the existing public Gawade Hospital website rather than duplicated into this ZIP. Before production launch, the hospital should provide approved original image files so they can be stored locally in `/assets` and no longer depend on the current WordPress site.

## Deployment
Upload the contents of this folder to Cloudflare Pages, Netlify, GitHub Pages or another static host. `index.html` is the entry point.
