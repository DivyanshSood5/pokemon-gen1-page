# Pokemon Gen I — HTML/CSS Showcase

A visually rich, animated Pokemon showcase page built with pure HTML & CSS as part of a learning assignment.

## Preview

| Slide 1 — Pikachu | Slide 2 — Charizard |
|---|---|
| Yellow split-panel layout | Orange split-panel layout |
| Pokeball → open → Pikachu animation | Charizard swoops in on scroll |
| Electric sparks & lightning bolts | Fire ember particles |
| Glassmorphism stats card | Glassmorphism stats card |

## Features

- **Pokeball opening animation** — ball flies in, shakes, opens, Pikachu emerges
- **Scroll-snap slides** — full-page vertical snap between Pikachu and Charizard
- **Scroll-triggered animations** — Charizard and all text animate in on scroll
- **Glassmorphism stats card** — frosted glass card with base stats, animated fill bars, type badges
- **Electric particles** — lightning bolts and sparks float around Pikachu
- **Fire embers** — glowing ember particles rise behind Charizard
- **Glitch effect** — Pokémon name gets a red/cyan glitch slice periodically
- **Poppins typography** — weights 400 / 500 / 600 / 700 / 800
- **Scroll nav dots** — fixed dots on the right track the active slide

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure, accessibility (aria labels, roles) |
| CSS3 | Animations, keyframes, glassmorphism, scroll-snap, custom properties |
| Vanilla JS | IntersectionObserver for scroll animations, hamburger toggle |
| Google Fonts | Poppins font family |

## Project Structure

```
A1/
├── assets/
│   ├── Old_Pikachu.png
│   ├── charizard.png
│   ├── pokeball.png
│   ├── pokeballopen.png
│   └── pokemonlogo.png
├── pokemon.html
├── pokemon.css
├── .gitignore
└── README.md
```

## Getting Started

Just open `pokemon.html` in any modern browser — no build step needed.

```bash
open pokemon.html
```

## Pokemon Stats

### Pikachu — #0025
| Stat | Value |
|---|---|
| Type | Electric |
| Height | 0.4 m |
| Weight | 6.0 kg |
| Ability | Static |
| Base Total | 320 |

### Charizard — #0006
| Stat | Value |
|---|---|
| Type | Fire / Flying |
| Height | 1.7 m |
| Weight | 90.5 kg |
| Ability | Blaze |
| Base Total | 534 |

## License

For educational purposes only. Pokémon and all related assets are property of Nintendo / Game Freak / The Pokémon Company.
