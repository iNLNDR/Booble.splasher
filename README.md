# 🐧 Bobble Splasher

A clean, arcade-style bubble shooter starring **Pip the penguin**, who turns the launcher crank as you aim. It's made for phones held upright and works with touch. You can play it in any browser and install it to your home screen.

## Features
- 100 stages across 5 worlds: Snowy Shore, Candy Cove, Sakura Hills, Coral Deep and Aurora Night.
- **Endless mode**: new rows keep pushing down faster and faster.
- Special bubbles: 🌈 Rainbow, 💣 Bomb, ⭐ Star and 🪨 Rock.
- The game gets harder as you go: more colors, faster ceiling drops, a shorter aim guide, and no landing preview after world 1.
- Earn up to 3 stars per stage. Progress saves in your browser.
- Chiptune music and sound effects made live with WebAudio, so there are no audio files.
- Works offline once installed as a PWA.

## Controls
| Action | Touch | Keyboard |
|---|---|---|
| Aim | Drag (the aim turns at a steady speed) or hold the arrow buttons | ← → |
| Shoot | Tap anywhere or press Shoot | Space / ↑ |
| Swap bubbles | Tap NEXT or Pip's feet | X / Shift |
| Pause | II button | Esc / P |

In **Settings** you can switch aiming to *Instant* (the aim jumps to your finger) and shooting to *Tap or lift* (lifting your finger after a drag also shoots).

## Put it on GitHub Pages
1. Create a new **public** repository on GitHub, for example `bobble-splasher`.
2. Upload every file in this folder, keeping the `icons/` folder, to the repository root. You can use **Add file → Upload files**.
3. Go to **Settings → Pages**. Under *Build and deployment*, pick **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
4. Wait about a minute. Your game will be live at `https://<your-username>.github.io/bobble-splasher/`.
5. On your phone, open that link and use **Add to Home Screen**. It then launches fullscreen like an app.

## Files
- `index.html`: the whole game (engine, art, levels and audio in one file)
- `manifest.webmanifest`, `sw.js`, `icons/`: make the game installable and playable offline
- `.nojekyll`: tells GitHub Pages to serve the files as they are

All art is drawn in code at startup. There are no image or sound files, and nothing is copied from other games.
