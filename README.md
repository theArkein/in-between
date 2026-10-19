# In-Between

A card game for friends: two cards are dealt to every player, then you bet on whether the next card lands strictly between them. 3D table, sound effects, works on phones and laptops.

**Rules in short:** the ace is always low, bets are multiples of 5, a hit on one of your cards or landing outside costs the bet, and when the bank is emptied the round ends and every card is recollected and reshuffled. Anyone can leave at any time and keeps their net result but gives up any share of the bank.

## Play

Open the site, add the players, pick the boat and start. One screen is shared around the table (online play is planned).

## Publish on GitHub Pages

1. Create a **public** repository (GitHub Pages on a free account needs a public repository).
2. Upload everything in this folder to the root of the repository's `main` branch.
3. Open **Settings, Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the game is live at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Files

- `index.html`: the whole game (HTML, CSS and JavaScript in one file).
- `vendor/three.min.js`: three.js r128 (MIT licence, see `vendor/THREE-LICENSE.txt`), included so the game does not depend on a CDN.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

The page also loads two fonts from Google Fonts. If they cannot load, the game falls back to system fonts.
