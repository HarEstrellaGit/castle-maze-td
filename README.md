# Castle Maze TD

A medieval tower defense game where you build the maze. Enemies pour out of a hell portal, march past five landmarks across the kingdom, and storm your castle. Every tower you place blocks their path, so the longer you make the road, the longer your towers have to bring them down. Survive all 50 waves to win.

**Play it here:** https://harleyestrella.github.io/castle-maze-td/

Works best on an iPhone or iPad held sideways. It also runs in any modern desktop browser.

## Install it on your iPhone or iPad

1. Open the link above in **Safari** while you're online.
2. Tap **Share**, then **Add to Home Screen**. Keep **Open as Web App** turned on.
3. Open the game once from the new **Castle Maze** icon while still online.

After that it runs full screen and plays offline, even in airplane mode. Your run is saved on that device.

## How to play

**The path.** Enemies leave the hell portal and pass the church, the wishing well, the graveyard, the elder tree and the barracks, in that order, before reaching the castle.

**Losing health.** An enemy that reaches the castle costs health:
- An unhurt enemy costs half the wave number.
- A boss costs wave × wave ÷ 10 (90 on wave 30).
- Wounded enemies cost less, but always at least 1.

**Building.** Every round you place **5 towers**. Their type and rank are random.
- Towers block walking enemies, so use them to stretch the maze.
- Keep one tower. The other four turn into walls that still block.
- Two identical new towers upgrade the one you keep by a rank.
- Ranks go Recruit, Trained, Veteran, Elite, Master. The top rank, **Lord**, can only be reached by upgrading (two Masters, or four Elites).

**Advanced towers and traps.** The right sets of towers combine into advanced towers. Pairs build traps you can place on any open square. The **blueprint** button lists every recipe.

**Gold.** Spend gold on **favor** (the crown button) to get higher-ranked towers. Walls can be torn down for free between waves.

**Waves.**
- Waves have 10 enemies.
- After wave 10, killing them quickly makes later waves bigger (up to 15). Letting them through makes waves smaller (down to 5).
- Boss waves are a single boss. A bigger wave size gives the boss more health (15 enemies means 50% more). Bosses never get weaker.

## Controls

| Action | How |
|---|---|
| Place a tower | Tap a square to select it, then tap it again or press **Build** |
| See an enemy's stats | Tap the enemy |
| Zoom | Pinch (side panels slide aside past 5× zoom) |
| Look around | Drag |
| Tilt the view | Slide two fingers up or down |
| Book of Records and Towers built | Book button |
| Menu, volume, new game | ☰ button |

Your run saves automatically between waves.

## Updating the game (for the maintainer)

1. Upload the new `index.html` (replacing the old one).
2. Open `sw.js` and bump the version, for example `castle-maze-v9` → `castle-maze-v10`.
3. Add the changes to `CHANGELOG.md`.

Installed copies pick up the update the next time they're opened online. If an old version still shows, close the app and open it again.

## Files

| File | What it does |
|---|---|
| `index.html` | The whole game |
| `sw.js` | Saves the game on the device so it plays offline |
| `manifest.webmanifest` | App name, icon and full-screen settings for the Home Screen |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | App icons |
| `CHANGELOG.md` | What changed in each version |

## Credits

Created by Harley Estrella.
