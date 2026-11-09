# Dr. Paul Heltzer Investigation — Tamara Holder Law

Static GitHub Pages landing page (HTML + CSS only, no PHP) for the Tamara
Holder Law campaign investigating Dr. Paul Heltzer, modeled on the firm's
existing doctorinvestigation.com page (the Dr. Mark Mulholland campaign)
and built on the latest generated framework files (the Massachusetts
Tobacco build's index.html / css/style.css skeleton — same framework
lineage as the damage claims page).

## Files

- `index.html` — the page
- `css/style.css` — all styling

## Framework carried over unchanged

- MTAA CIPA block script
- Meta Pixel 1238664640565416 (with ViewContent track)
- MTAA form embed nf_14bb49f057af4602b5676b8892df3c32 in the hero form card
- Overflow form card: hangs past the hero (negative bottom margin) and the
  form frame scrolls internally (`overflow: auto`) when the embed runs tall
- Footer legal links to justicehelpnow.com privacy policy / disclaimer

## Palette (sampled live from doctorinvestigation.com, 2026-11-09)

- Mid blue #284e84 — top bar, section titles, footer, parallax overlays
- Deep blue #1e3a5f / black #2f2f2f — hero gradient, header background
- Gold #a89158 — CTA buttons and accents; hover #6f5932
- Light gold #d8ad67 — highlights on dark backgrounds
- Pale blue #cbddf4 — results band
- Dark red #920b0e — form heading ("FREE CASE REVIEW")
- Headlines in the sample's bold sans-serif (Inter/Arial) throughout

CSS is identical to the framework except color values and heading
font-family values (verified by diff).

## Content

- Hero: "Were You a Patient of Dr. Paul Heltzer?" — 17-women lawsuits,
  free/confidential review, (877) 674-2009
- About the Investigation: October 2024 multi-plaintiff complaint by 17
  women, filings through late 2026; alleged unwanted touching (flicking,
  pinching, or rubbing nipples/nipple piercings; digital penetration),
  prolonged pelvic exams, inappropriate sexualized/personal comments,
  abuse of authority; Staten Island University Hospital (SIUH) and
  Northwell Health also named (failure to protect patients / safety
  protocols)
- Allegation cards (parallax section)
- Firm record: "We've Secured Hundreds of Millions of Dollars for
  Hundreds of Women" (the firm's claim from its own page)
- FAQs, including the defense's position (claims contested as
  unverified; patients cited who spoke to his character) and the $3.5
  million 2022 medical malpractice settlement from prior cases
- Tamara Holder bio from the firm's page (Fox News analyst, Fabio Ortega
  case, testified before Congress)
- Disclaimer: sponsor line verbatim from the firm's page, plus a note
  that the conduct described is alleged in civil lawsuits and has not
  been proven in court

## Placeholders to replace

- `images/REPLACE-LOGO.png` — firm logo (header + footer)
- `images/attorney-photo-1.jpg` — Tamara Holder photo
- `images/REPLACE-TEAM-IMAGE.jpg` — team photo
- `images/REPLACE-HOSPITAL-IMAGE.jpg` — side image in About section
- `YOUR-IMAGE-URL-HERE` — hero parallax background (css/style.css)
- `YOUR-IMAGE-URL-HERE-2` — allegations-section parallax background

## Notes

- Phone (877) 674-2009 is the number displayed on doctorinvestigation.com
  (header, consultations card, and footer areas) and appears in the
  header, results band, and footer.
- The form embed is the current framework MTAA embed; swap the iframe
  `src` when a campaign-specific form exists.
