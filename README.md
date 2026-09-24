# 🕹️ Eck-Cade

A retro-arcade-style landing page with links out to all the grandkids' games — hosted wherever each game lives (its own site, itch.io, Scratch, GitHub Pages, etc.).

## How it works

- **[index.html](index.html)** — the whole site. It has the big blocky "ECK-CADE" title plus a grid of game cards. Each card is just a link (`<a class="game-card" href="...">`) to a game hosted somewhere else.
- **[assets/css/style.css](assets/css/style.css)** — the arcade theme (neon colors, bouncing block letters, CRT scanlines).
- **[assets/js/script.js](assets/js/script.js)** — just sets the footer's copyright year.

## Adding a new game link

Open `index.html` and copy/paste a new card inside `<section class="game-grid">`:

```html
<a class="game-card" href="https://the-game-url-goes-here" target="_blank" rel="noopener">
  <span class="emoji">👾</span>
  <h2>Space Blaster</h2>
  <p>Blast asteroids before they blast you!</p>
  <span class="by">by Alex</span>
</a>
```

Change the `href`, emoji, title, description, and "by" name, then save.

## Running locally

Just open `index.html` directly in a browser — no server needed.

