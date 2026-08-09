# space7gym

Static single-page site for **Space7 Gym** — Gulshan-e-Maymar, Karachi.

## Theme: Mission Control 🚀 (brand red)

Full revamp (Aug 2026). The site is 100% static — one `index.html`, no build step,
no framework. Everything (styles, scripts, schedule data) lives in that file.

### Design language
- **Brand palette** — near-black `#070708` base, brand red `#e8232c` primary with
  `#ff343d` glow and `#a50f17` deep shadow (original Space7 brand colors).
- **Typography** — Orbitron (display), Space Grotesk (body/UI), IBM Plex Mono (HUD labels).
- **Motifs** — twinkling starfield canvas, orbiting red-giant planet illustration,
  HUD corner brackets, mono `SYS//` section labels, ghost outline numbers,
  scrolling ticker strip, blinking "online" telemetry dots.
- Fully responsive (1024 / 860 / 600 breakpoints) and `prefers-reduced-motion` aware.

### Photos
Drop real photos into `images/` with the exact filenames listed in
`images/README.txt` — they appear automatically (placeholder tiles show until then).

## Before publishing — search for `EDIT:` in index.html

1. **LOGO** — the SVG mark is a recreation (red planet + ring + 7). Swap for the real logo.
2. **PHOTOS** — add files to `images/` (see `images/README.txt`).
3. **PHONE** — placeholder `+92 300 0000000` in contact + footer.
4. **PRICES** — placeholder PKR amounts in the membership plans.
5. **SCHEDULE** — sample timetable in the JS (`var schedule = {...}`).
6. **TESTIMONIALS** — sample reviews, clearly marked.
7. **CONTACT FORM** — client-side only; wire to Formspree/Netlify (see comment near `<form>`).

Brand colors live in `:root` (--red, etc.) — change them in ONE place.
