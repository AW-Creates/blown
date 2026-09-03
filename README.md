# BL·OWN

A directory, review platform, and marketplace for Black-owned businesses — think Yelp + Angie's List + Etsy, with a tiered ownership-verification system built in.

**Tagline:** Certified BL·OWN — Black-Owned. Verified. Found.

## Brand system

- **Wordmark:** BL·OWN, paired with the tagline on first-touch surfaces (nav, splash, email footer) so the acronym reads clearly.
- **Mark:** a circular embossed "seal" with a checkmark — doubles as both the logo and the verification badge shown on every business profile.
- **Palette:** Graphite (dark) and Ivory (light), sharing one CSS custom-property token system so both themes stay in sync. See `mockups/current/` for the live toggle implementation.
- **Type:** Fraunces (display/serif) + Space Grotesk (wordmark) + Public Sans (body).
- **Verification tiers:** Self-Attested → Verified → NMSDC-Certified, shown as a badge on every listing.

## Structure

```
mockups/
  current/              finalized HTML mockups (dual theme, animated)
    landing-page.html
    search-discovery.html
    business-profile.html
  archive/               earlier exploration rounds, kept for reference
```

Every file in `mockups/` is a self-contained HTML file — open directly in a browser, no build step needed.

## Status

Early-stage design exploration. Not yet connected to a real backend, auth, or database.

## Next steps

- Data model / schema (businesses, users, reviews, verification records)
- Business owner signup + verification flow
- Auth
- Payments/booking for the marketplace layer (phase 3)
