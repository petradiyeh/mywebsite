# Petra Radiyeh — Documentary Photography Portfolio Website

## Purpose
Portfolio website supporting Petra's application to the **MA Visual Anthropology program at the University of Manchester**. The site showcases documentary photography work across three series.

## Series
1. **In Transit** — B&W documentary study of public intimacy on urban transit systems (London, Toronto, Mexico City). 21 curated images, fully built with narrative sequencing.
2. **Park** — Placeholder page, awaiting photos and description.
3. **Common Grounds** — B&W street photography documenting shared public spaces (Toronto, Latin America). All 101 photos included with Magnum-style asymmetric layout.

## Design Direction
- **Homepage**: Inspired by UI-2 reference (bold sans-serif typography, clean white space, three series cards in a row, large contact section). See `UI -2.jpg` in the parent folder.
- **About page**: Inspired by UI-1 reference (vertical journey timeline with organic winding path). Shows Petra's journey: Libya (1996-2011) → Syria (2011-2012) → Egypt (2012-2013) → Lebanon (2014-2021) → Canada (2021-today). See `UI -1.jpg` in the parent folder.
- **Series pages**: Magnum Photos-inspired asymmetric layout (reference: Sergio Larrain's page on magnumphotos.com). Alternates between full-width singles, weighted two-column pairings, and offset/centered images to create visual rhythm and narrative sequencing. NOT a uniform grid.
- **Overall aesthetic**: Clean, minimal, generous whitespace, B&W photography, professional. Fonts: Inter (sans-serif) + Playfair Display (serif for headings on inner pages).

## Photo Arrangement Philosophy
Images on series pages are sequenced as a narrative arc, not randomly displayed:
- Open with a strong contemplative portrait (sets tone)
- Move through solitude → intimacy/connection → fatigue/rest → joy → closing image
- Alternate layout sizes (full-width, two-col, offset, narrow-center) to create rhythm
- Pair images that are in dialogue (e.g., two detail shots of hands side by side)
- Close with something emotionally resonant

## Site Structure
```
website/
├── index.html              # Homepage (UI-2 style)
├── in-transit.html         # In Transit series page (Magnum-style layout, 21 photos)
├── common-grounds.html     # Common Grounds series page (Magnum-style layout, 101 photos)
├── park.html               # Park series (placeholder)
├── about.html              # About page (UI-1 style journey timeline)
├── style.css               # Shared stylesheet
├── README.md               # This file
├── memory.md               # Project log and progress tracker
└── images/
    ├── in-transit/         # 21 curated B&W photos (DSC* = Sony, R* = Ricoh GR)
    └── common-grounds/     # 101 B&W street photos
```

## In Transit — Curated Image Sequence
The 21 selected images are arranged in this order on the series page:

1. `DSC07849.jpg` — Older woman in profile (hero/opener, full-width)
2. `DSC01914.jpg` + `DSC00296.jpg` — Two solitary figures (two-col)
3. `DSC01782.jpg` — Mother and daughter smiling (offset-right)
4. `DSC05570.jpg` + `DSC02060.jpg` — Hands/intimacy details (weighted-left two-col)
5. `DSC01621.jpg` — Children on the Tube (full-width)
6. `DSC02591.jpg` + `DSC05909.jpg` — Fatigue/rest (two-col)
7. `DSC04271.jpg` — Child laughing (narrow-center)
8. `R0000389.jpg` + `R0000451.jpg` — Generations (weighted-right two-col)
9. `R0000624.jpg` — Woman reading with flowers (offset-left)
10. `DSC06462.jpg` — Two guys with basketballs (full-width)
11. `DSC01104.jpg` + `DSC05882.jpg` — Detail and play (two-col)
12. `R0000255.jpg` — Man lit by phone in darkness (narrow-center)
13. `DSC06713.jpg` + `DSC04844.jpg` — Youth observing (weighted-left two-col)
14. `R0000814.jpg` — Couple embracing on platform (full-width, closing)
15. `DSC06959.jpg` — Children on platform (offset-right, final)

## Common Grounds — All 101 Photos
All photos from the Common Grounds folder are included, arranged in an asymmetric Magnum-style grid alternating full-width, two-column, weighted, offset, and narrow-center layouts. Photos are in filename sort order — Petra may want to resequence for narrative flow.

## About Page — Journey Timeline
The About page uses a UI-1 inspired vertical timeline showing Petra's journey:
- Libya (1996–2011) — starting point
- Syria (2011–2012)
- Egypt (2012–2013)
- Lebanon (2014–2021)
- Canada (2021–today)

Features an organic winding SVG path connecting the entries, minimal typography on a light gray background.

## Items Still Needing Attention
- [ ] Add Instagram handle to homepage contact section
- [ ] Add Park series photos and description
- [ ] Add series description text for Common Grounds
- [ ] Consider curating/resequencing Common Grounds photos for stronger narrative
- [ ] Consider image optimization for web (compression, responsive srcset)
- [ ] Decide on hosting (GitHub Pages, Netlify, Squarespace, etc.)
- [ ] Add alt text descriptions to Common Grounds images

## How to Preview Locally
Open terminal in the website folder and run:
```
start index.html
```

## UI Reference Files
Located in the parent folder (`Lightroom Saved Photos/`):
- `UI -1.jpg` — Timeline/journey layout reference (PRIMARY for About page)
- `UI -2.jpg` — Homepage design reference (PRIMARY for front page)
- `UI -3.jpg` — Portrait photography site reference
- `UI -4.jpg` — Documentary filmmaker portfolio reference (used for original About page, now replaced by UI-1 timeline)

## Technical Notes
- Shared CSS in `style.css`, About page has additional inline styles for timeline
- Fonts loaded via Google Fonts CDN (Inter + Playfair Display)
- Responsive design with breakpoints at 900px and 600px
- Images use `loading="lazy"` for performance
- No JavaScript dependencies — pure HTML/CSS
- About page timeline uses inline SVG for the organic winding path
