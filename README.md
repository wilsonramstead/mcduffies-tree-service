# McDuffie's Tree Service — Demo Website

Demo marketing site built for **McDuffie's Tree Service**, a solo-operator tree
service based in Gibsonton, FL (South Hillsborough County). Built demo-first as a
sales pitch by Wilson Innovations.

## Business facts used
- **Name:** McDuffie's Tree Service (operator: Shawn — used only in review quotes)
- **Area:** Serving Gibsonton, Riverview & South Hillsborough (no street address shown — listed address is residential)
- **Phone / Text:** (813) 965-6341 — `tel:+18139656341` and `sms:+18139656341`
- **Google:** a perfect 5.0★ across 121 reviews
- **Hours:** open 7 days a week, 7:00 AM – 5:00 PM
- **Services:** palm pruning, tree trimming, tree removal, debris/dead-frond cleanup
- **Estimates:** free — "text a photo, get a quote" (reviews confirm text/photo contact)

## Design
- **Fonts:** Arvo (display) + Lato (body) via Google Fonts
- **Palette:** flannel red (`#A8322A`), timber brown (`#4A3526`), cream (`#F6EEDF`) — a
  hardworking, one-crew look; gold used only for star ratings
- Sticky header with a call button always visible (down to 390px); the long brand name
  wraps cleanly on narrow screens. **No** fixed bottom call bar.
- Call **and** text CTAs paired throughout (operator receives texts).
- Sections: hero, trust strip, services, "text a photo, get a quote", CTA band,
  real Google reviews, service area + hours, footer.

## Build/compliance notes
- `noindex` meta present with a removal comment for go-live.
- Open Graph + Twitter tags with **absolute** image URL; `twitter:card` = `summary_large_image`.
- `LocalBusiness` JSON-LD with services, area served, hours, and aggregate rating.
- Semantic HTML, descriptive alt text, AA contrast, lazy-loaded imagery,
  reduced-motion-aware reveal animations. Works from `file://`.
- Overflow guardrails: `overflow-x:clip`, `min-width:0` on grid/flex children,
  longhand vertical padding on wrap containers.
- No contact forms, prices, emails, licensing claims, founding years, or 24/7 claims.
- Photos: Unsplash, palm/Florida-tree topical, verified HTTP 200 and globally unique
  across all sibling builds.

## Deploy
Static single-page site. Hosted on GitHub Pages:
`https://wilsonramstead.github.io/mcduffies-tree-service/`

---
Website by [Wilson Innovations](https://wilsoninnovations.net).
