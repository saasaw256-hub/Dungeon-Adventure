# Dungeon Adventure

A polished 2D fantasy dungeon browser game made with vanilla HTML, CSS and JavaScript. No build tools or server are required.

## Features
- 20 levels with increasing monster difficulty.
- Boss battles on levels 5, 10, 15 and 20, each with a displayed health bar.
- Five playable heroes: Knight, Ranger, Mage, Guardian and Rogue.
- Different starting health, attack, defence and special abilities for each class.
- Seven regular monster types, coins, healing potions, XP and boss rewards.
- Boss victories permanently improve the hero.
- Automatic local save and continue option.

## Controls
- WASD or arrow keys: move
- Space: attack nearby monsters
- E: class special ability
- Q: use a healing potion
- P: pause/resume

## Run locally
Extract the ZIP and open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Sign in to https://github.com/ and create a new **public** repository, e.g. `dungeon-adventure`.
2. Open the repository and choose **Add file → Upload files**.
3. Extract this ZIP on your computer. Upload `index.html`, `style.css`, `game.js` and `README.md` into the repository's root folder (not a nested folder).
4. Click **Commit changes**.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then click **Save**.
8. Wait for publication. Your URL will look like `https://YOUR-USERNAME.github.io/dungeon-adventure/`.

Progress is stored in local browser storage on that device/browser. It does not sync across devices. The canvas art is drawn in code, so no separate image assets are needed.
