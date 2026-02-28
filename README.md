# RTS MVP (Browser)

A minimal single-player RTS-style prototype built with one `index.html` file (Canvas + vanilla JS).

## Local Run

1. Open `index.html` directly in your browser.
2. Pick difficulty (`easy`, `medium`, `advanced`).
3. Click **Spawn Unit (50)** to attack the enemy HQ.

## Deploy to GitHub Pages

1. Create a new public GitHub repo (for example `rts-mvp`).
2. From this folder, run:

```bash
git init
git add index.html README.md
git commit -m "Initial RTS MVP"
git branch -M main
git remote add origin https://github.com/<your-username>/rts-mvp.git
git push -u origin main
```

3. In GitHub, open the repo settings:
- `Settings` -> `Pages`
- `Source`: **Deploy from a branch**
- `Branch`: **main** and folder **/(root)**
- Save

4. Wait for deployment, then open:

`https://<your-username>.github.io/rts-mvp/`

## MVP Features

- One map, two HQ bases
- Resource income over time
- One unit type
- AI spawn pressure scales by difficulty
- Victory/defeat + restart flow
