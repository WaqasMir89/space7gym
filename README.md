# space7gym

Static single-page site for **Space7 Gym** — Gulshan-e-Maymar, Karachi.

## Theme: Mission Control 🚀

Full revamp (Aug 2026). The site is 100% static — one `index.html`, no build step,
no framework. Everything (styles, scripts, schedule data) lives in that file.

### Design language
- **Deep space palette** — navy `#05060f` base, electric cyan `#3ee6ff` primary,
  solar amber `#ffb454` secondary, nebula magenta accents.
- **Typography** — Orbitron (display), Space Grotesk (body/UI), IBM Plex Mono (HUD labels).
- **Motifs** — twinkling starfield canvas, orbiting planet illustration with SMIL
  orbit dots, HUD corner brackets, mono `SYS//` section labels, ghost outline numbers,
  scrolling ticker strip, blinking "online" telemetry dots.
- Fully responsive (1024 / 860 / 600 breakpoints) and `prefers-reduced-motion` aware.

## Before publishing — search for `EDIT:` in index.html

1. **LOGO** — the SVG mark is a recreation (planet + ring + 7). Swap for the real logo.
2. **PHONE** — placeholder `+92 300 0000000` in contact + footer.
3. **PRICES** — placeholder PKR amounts in the membership plans.
4. **SCHEDULE** — sample timetable in the JS (`var schedule = {...}`).
5. **PHOTOS** — `class="ph"` placeholder tiles (gym, trainers, gallery). Drop in real photos.
6. **TESTIMONIALS** — sample reviews, clearly marked.
7. **CONTACT FORM** — client-side only; wire to Formspree/Netlify (see comment near `<form>`).

Brand colors live in `:root` (--cyan, --amber, etc.) — change them in ONE place.
