# REFUGEE: 1963

A choice-based survival game set in an alternate-history fractured India.

## Story

1947: Mountbatten crashed. No independence.
1959: Britain left after 12-year fight.
1963: Seven factions. India broken.

Find your family in 60 days.

## Play Now

**[Play the Game](game-with-images.html)**

Open `game-with-images.html` in your browser, or host on GitHub Pages.

## Features

- **6 Origins**: Farmer, Teacher, Merchant, Soldier, Doctor, Priest
- **6 Skills**: Combat, Survival, Speech, Stealth, Medicine, Trade
- **6 Factions**: Lion Guardians, Dravida Alliance, People's Front, Deccan Coalition, Union Remnant, Free Ports
- **Reputation System**: Your choices affect faction relationships
- **Multiple Endings**: 6+ different endings based on your journey

## How to Play

1. Choose your origin (affects starting stats and skills)
2. Travel across fractured India
3. Build trust with factions (helping one may anger their enemies)
4. Collect 3 clues to find your family
5. Survive 60 days

### Tips

- Rest when HP is low
- Keep food above 2 to avoid starvation
- Build trust with 1-2 factions max
- Use skills often to level up
- Vilified/Hated factions (-3 trust) attack on sight!

## Files

| File | Description |
|------|-------------|
| `game-with-images.html` | Main game (with images) |
| `skills.html` | Skills demo |
| `reputation.html` | Reputation demo |
| `game-logic.js` | PDF game logic (for Adobe Acrobat version) |

## Running Locally

### Option 1: Direct Open
Just open `game-with-images.html` in Firefox (Chrome blocks local images)

### Option 2: Python Server
```bash
cd refugee-1963
python -m http.server 8000
```
Then open `http://localhost:8000/game-with-images.html`

### Option 3: VS Code Live Server
Install Live Server extension, right-click HTML file, "Open with Live Server"

## GitHub Pages

1. Go to Settings → Pages
2. Source: Deploy from branch → main → / (root)
3. Your site will be live at `https://yourusername.github.io/repo-name/`

## Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks)
- Works offline
- Responsive design

## License

Free to use, modify, and distribute.
