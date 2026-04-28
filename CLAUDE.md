# antonsimanenko.com

Personal landing page / business card site, deployed via GitHub Pages at antonsimanenko.com.

## Structure

Single file: `index.html` — no build step, no dependencies beyond Google Fonts CDN.

## Stack

- Vanilla HTML/CSS/JS
- JetBrains Mono font (Google Fonts)
- GitHub Pages for hosting (this repo auto-deploys on push to `main`)
- `CNAME` file points the domain to `antonsimanenko.com`

## Design principles

- Minimal, monospace aesthetic
- White background, `#555` text, `#C59D33` accent (gold links)
- Content centered at ~45% vertical, max-width 540px
- EN/RU language switcher — both versions maintained in sync
- "Last updated" badge top-right — bump to current date on every meaningful edit
- Use `&nbsp;` to keep brand names and short pairs from breaking across lines

## Workflow

Edit `index.html`, commit, push to `main` → GitHub Pages deploys automatically (usually ~1 min).

## About Anton (subject of the page)

Creative director, tech-enthusiast, educator. Positioning: **helping teams and corporations become more productive with AI**.

### Main project (current)

**ИИЧАВО / ICHV** — [ichv.ai](https://ichv.ai). AI consulting & transformation firm. Three pillars: **объясняем / обучаем / внедряем** (explain / train / implement). Services include executive lectures, manufacturing workshops, 3-week prompting bootcamps, 6-week AI-tools bootcamps, SupaSearch knowledge base deployment, custom AI simulators.

### Active clients (via ICHV)

Яндекс Go, СИБУР, The Edgers, OKKAM, Partsdirect, PASHA Holding.

### Side projects

- **Промпти / Prompty Trainer** — [supalab.ai/prompty](https://supalab.ai/prompty). Prompt-training simulator for large teams.
- **PLAI Cube** — [plaicube.ai](https://plaicube.ai). AI toy in development.

### Contact

Telegram [@liquid_lockheed](https://t.me/liquid_lockheed).

## Copy / tone notes

- First-person, friendly, slightly playful ("Beep boop" / "Бип-буп" opener).
- Three short paragraphs: who I am → what I do + clients + side projects → CTA to talk.
- Keep EN and RU roughly parallel in structure; RU uses non-breaking spaces between brand parts (e.g. `PASHA&nbsp;Holding`, `PLAI&nbsp;Cube`).
- Brand naming: in RU prefer `ИИЧАВО`, `«Промпти»`; in EN use `ICHV`, `Prompty Trainer`.
