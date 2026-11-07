# PRD — FreeToolsHub

## Product Vision
A single, fast, dark-themed directory where anyone can find and open any free tool that requires no login — across every genre (dev, design, media, productivity, AI, writing, finance, learning, utilities, etc.). No accounts, no paywalls, no friction. Just links.

## Goals
- Aggregate and organize free no-login tools from across the internet
- Make discovery instant: search + filter by genre + tag
- Zero friction: every link opens the tool directly, no signup
- Feel like a curated catalog, not a blog or marketing site

## Target Users
Everyone — students, developers, designers, writers, freelancers, hobbyists. No technical knowledge assumed.

## User Stories
- As a user, I can search by tool name or keyword
- As a user, I can filter by genre/category
- As a user, I can see a short description + direct link for each tool
- As a user, I can copy/share a tool link
- As a user, I can suggest a new tool (future)

## Features
- Category grid: Software, Media, LLMs/AI, QoL, Fun, Writing, Dev, Design, Productivity, Finance, Learning, Utilities, and more
- Search across names + descriptions + tags
- Tool cards: name, one-line description, genre tag, direct "Open" link
- Glass cards on dark background (transparent bg + blur)
- No gradients, no purple/pink/wired-blue accents
- Responsive: mobile-first (375px+)
- Fast: vanilla HTML/CSS/JS, no frameworks

## Functional Requirements
- Static site (GitHub Pages), no backend, no database
- All tool data in a JSON file (tools.json) — easy to extend
- Client-side search & filter
- Each card: name, description, category, URL, optional icon/emoji

## Non-Functional Requirements
- Dark theme only
- Glass cards: rgba bg + backdrop-filter blur
- Total page weight < 500KB
- Lighthouse-friendly: fast load, accessible

## User Flows
Landing → see genre grid + search bar → filter/search → click card → opens tool in new tab

## Edge Cases
- Empty search results → friendly empty state with suggestion
- Tool link dead → (future) health check; for now trust curated list
- Mobile: cards stack, search sticky

## Success Metrics
- User finds a tool in < 10 seconds
- Page loads < 2s on mobile

## Out of Scope (v1)
- User accounts, ratings, reviews
- Backend/database
- Tool submission form (manual PR for now)

## Style System
- Dark theme, no gradients, NO accent colors at all — monochrome dark + glass
- No purple, pink, or wired-blue accents (and no accent colors in general)
- Glass cards: transparent bg + slight blur (glassmorphism), neutral borders
- Fonts: Space Grotesk (display) + Inter (body) or similar
