# FreeToolsHub

> A curated directory of **free, no-login, no-paywall** tools across every genre — software, media, fun, learning, finance, utilities, writing, and more.

**Live site:** https://amogha-a-nadiger.github.io/freetoolshub/

## What is this?

FreeToolsHub is a single-page directory that lists 335+ tools you can use **right now** without creating an account, paying a subscription, or hitting a free-tier wall. Every tool is verified to be truly free.

## Features

- **Circular category navigation** — pick a category, expand it, browse the cards
- **Instant search** — filter by name or description across all tools
- **Glassmorphism dark UI** — monochrome dark theme, no accent colors, clean glass cards
- **No login, no paywall** — every listed tool is free forever
- **Request a tool** — missing something? Email us and we'll try to find it
- **Responsive** — works on phone, tablet, and desktop

## Categories

| Category | Examples |
|----------|----------|
| Software | AI image gens, code tools, converters, design tools |
| Media | Video editors, audio tools, image editors, screen recorders |
| Fun | Games, generators, meme makers, entertainment |
| Learning | Courses, tutorials, references, practice platforms |
| Libraries | Open-source libs, APIs, datasets, documentation |
| Finance | Calculators, trackers, crypto tools, budgeting |
| Utilities | PDF tools, compressors, formatters, file converters |
| Writing | Grammar checkers, editors, prompt tools, text generators |

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS (no frameworks, no build step)
- **Data:** `tools.json` — flat array of `{ name, desc, cat, url }`
- **Hosting:** GitHub Pages (static, free)
- **Fonts:** Space Grotesk, Inter, Fraunces via Google Fonts CDN

## Run Locally

```bash
cd freetoolshub
python -m http.server 8484
# Open http://localhost:8484
```

## Add a Tool

Edit `tools.json` and append an entry:

```json
{ "name": "Tool Name", "desc": "Short description", "cat": "Software", "url": "https://example.com" }
```

Categories: `Software`, `Media`, `Fun`, `Learning`, `Libraries`, `Finance`, `Utilities`, `Writing`

## Request a Tool

Missing a free tool? [Request it here](mailto:amoghanadiger321@gmail.com?subject=Free%20Tool%20Request) — we'll try to find it.

## Contact

- Email: amoghanadiger321@gmail.com
- GitHub: https://github.com/Amogha-A-Nadiger/freetoolshub

## License

Open source. Contributions welcome.