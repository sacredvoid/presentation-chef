# Presentation Chef

Convert any content into stunning **Apple Keynote-style HTML presentations** with a single Claude Code command.

Cinematic animations, glassmorphism cards, ambient orb effects, staggered reveals, and premium design — all generated as a **single self-contained `.html` file** with zero dependencies.

Inspired by [ChronicleHQ](https://chroniclehq.com) and Apple's keynote presentation aesthetic.

## Installation

In Claude Code, run:

```
/install-plugin sacredvoid/presentation-chef
```

Or add the marketplace manually:

```
Add marketplace: sacredvoid/presentation-chef
Then install: presentation-chef
```

## Usage

Once installed, invoke the skill:

```
/presentation-chef
```

The skill will interactively guide you through:

1. **Content input** — Paste text, point to a markdown file, or describe a topic for AI-generated content
2. **Theme selection** — Choose from 5 built-in presets or get AI-suggested themes based on your content
3. **Design customization** — Override colors, fonts, and effects as needed
4. **Slide structure** — Review and approve the proposed slide layout
5. **Output** — Get a single `.html` file you can open in any browser

## Theme Presets

| Theme | Vibe | Best For |
|-------|------|----------|
| **Dark Cinematic** | Apple keynote aesthetic, ambient orbs, grain overlay | Portfolios, product launches, pitch decks |
| **Light Minimal** | Clean Chronicle-style white canvas | Reports, educational content, corporate presentations |
| **Warm Editorial** | Magazine-style with serif typography | Personal stories, creative work, thought leadership |
| **Neon Cyberpunk** | High-energy tech with neon accents | Startup pitches, tech demos, hackathon presentations |
| **Earth Organic** | Calm, natural with rounded aesthetics | Wellness, sustainability, nonprofit, educational |

All themes support full customization of colors, fonts, animations, and effects.

## Slide Types (13 built-in blocks)

- **Hero** — Big title with glow ring and ambient effects
- **Stats** — Animated count-up numbers with gradient text
- **Chapter** — Section divider with dramatic typography
- **Content Card** — Frosted glass card with rich text content
- **Feature Grid** — Hoverable chip grid for skills, tech stacks, features
- **Timeline** — Chronological journey with connected markers
- **Comparison** — Side-by-side with vertical divider
- **Quote** — Large testimonial/pullquote display
- **Image** — Full-bleed visual with text overlay
- **Data** — CSS-only animated bar charts
- **Split Screen** — 50/50 text and visual layout
- **List** — Icon + title + description achievement rows
- **CTA** — Call to action with pill-shaped links and availability badge

## Features

- **Single file output** — All CSS, JS, and content inline. Zero dependencies. Open anywhere.
- **Full navigation** — Keyboard (arrows, space, page up/down), mouse wheel, touch swipe, clickable dots
- **Cinematic transitions** — Scale + fade with spring easing (900ms)
- **Staggered reveals** — Elements animate in sequence per slide
- **Responsive** — Works on desktop, tablet, and mobile
- **Ambient effects** — Grain overlay, blurred color orbs with parallax, hero glow rings
- **Glassmorphism** — Backdrop-filter blur, semi-transparent borders, top highlight lines
- **Progress bar** — Gradient progress indicator at top of viewport
- **Loading screen** — Polished entry experience

## Example Output

The generated HTML looks like this when opened in a browser:

- Full-screen slide-by-slide navigation
- Dark/light themes with ambient atmospheric effects
- Frosted glass content cards
- Animated statistics with count-up numbers
- Responsive design that works on any device

## How It Works

Presentation Chef is a Claude Code **skill** — a set of instructions that tells Claude how to generate presentations. When you invoke `/presentation-chef`, Claude:

1. Gathers your content and design preferences interactively
2. Maps your content to the optimal slide types
3. Applies the selected theme's design tokens
4. Generates a complete, production-quality HTML file

No build step, no npm install, no framework — just a single HTML file.

## License

MIT
