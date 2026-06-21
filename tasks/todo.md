# AI Educational Website — Todo

## Checklist
- [x] Create `index.html` with base HTML structure and CSS variables
- [x] Build navigation bar (sticky, frosted glass on scroll)
- [x] Build hero section (headline, CTAs, placeholder image)
- [x] Build stats bar (3 key numbers)
- [x] Build courses grid (3 cards with placeholder images)
- [x] create styles.css with modern agency aesthetics (extracted from index.html into standalone file)
- [x] Build feature / why-us section (2-col layout)
- [x] Build testimonial band (dark, full-width pull quote)
- [x] Build newsletter CTA section
- [x] Build footer
- [x] Add mobile responsive media queries
- [x] Add scroll-based nav JS behavior

## Review
Single file `index.html` created with embedded CSS and JS (no build step, no dependencies).

**What was built:**
- Dark-mode design system via CSS custom properties (violet accent #7C3AED, near-black surfaces)
- Syne (display) + Inter (body) from Google Fonts for a contemporary agency feel
- Nav: transparent → frosted-glass blur on scroll via a 4-line JS scroll listener
- Hero: full-viewport 2-col grid with radial gradient glow, gradient headline text, and a floating badge overlay on the image
- Stats bar: 3 large numbers with gradient text fill
- Courses grid: 3 cards with hover lift animation, tag badges, and instructor avatars
- Features: 2-col layout with icon tiles and descriptive copy
- Testimonial: centered dark band with pull-quote typography
- Newsletter: email input + submit CTA
- Footer: logo, nav links, copyright
- Fully responsive at 900px (single column) and 560px breakpoints
- All images via `placehold.co` — zero external image dependencies
