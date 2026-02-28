# City Theater RTS MVP (Browser)

Original browser RTS MVP inspired by classic base-vs-base strategy games.
Built as a single `index.html` file (Canvas + vanilla JS) for easy static hosting.

## Play Locally

1. Open `index.html` in your browser.
2. Choose a city theater and difficulty.
3. Build mixed forces: `Harvester`, `Soldier`, `Tank`, `Helicopter`, and `Patrol Boat` (coastal maps).
4. Select one unit or a group and issue commands.

## Controls

- Left click unit: single select
- Shift + left click unit: add/remove from current selection
- Left-click drag box: select multiple units
- Left click or right click map/node/enemy HQ: command selected group
- `Restart`: reset match with selected city/difficulty

## Gameplay Loop

- Two resources: `water` and `materials`
- Harvesters gather from resource nodes and return cargo to HQ
- Army branch: `Soldier`, `Tank`
- Air Force branch: `Helicopter`
- Navy branch: `Patrol Boat` (available on coastal theaters)
- Combat units engage enemy units/base automatically in range
- Destroy the enemy HQ to win

## City Theaters

- Miami Coast
- Phoenix Basin
- Seattle Port

Each city has a unique resource-node distribution and visual theme.

## Deploy to GitHub Pages

```bash
git add index.html README.md
git commit -m "City theater RTS MVP"
git push origin main
```

In GitHub repo settings:
- `Settings` -> `Pages`
- `Source`: **Deploy from a branch**
- Branch: **main** / **(root)**

Site URL pattern:
`https://<your-username>.github.io/rts-mvp/`

## Legal/Attribution

- Original game inspired by RTS genre conventions
- Not affiliated with Command & Conquer
- No Google Maps imagery or tiles used
- City layouts are handcrafted schematics with OSM-style public-geography influence
