# Changelog

All notable changes to Castle Maze TD are listed here, newest first.

## 1.16 — October 28, 2026

### Added
- **Armor break levels.** Every armor reduction now uses one of 9 levels: −2, −4, −8, −12, −16, −24, −32, −48 and −64 armor. Armor loss from **different** levels adds up; two effects of the same level don't. This covers hits, auras and traps alike, and tower details show each one's level.

### Changed
- **The tower showcase moved to Blueprints.** The Blueprints panel now has **Towers** and **Traps** tabs. Tap a tower in the list, or swipe the big tower shown on the board, to see its recipe and what it does. Parts you already own are outlined in gold.
- **The Book of Records** now has **Game runs** and **Game modes** tabs (game modes are coming later). The Towers built tab is gone from here.
- **Armor values adjusted to fit the new levels:**
  - Plague Tower: −16 armor (was −15).
  - Risen Poet: −32 armor over a larger area (13×13 squares, was 9×9), and her Unveiling song now covers 9×9 squares (was 5×5).
  - Winter's Heart and Yaphet's Monolith auras: −32 armor (was −30).
  - Falconer's Roost, Healer's Abbey, Skyhunter Lodge and Robin's Woods: −12 armor on flyers (was −10).
  - Lord Ballista Tower: −48 armor per hit (was −64).
- The Acid trap's armor loss now follows the armor break level rules.

## 1.15 — October 28, 2026

### Added
- **Haste levels.** Every attack-speed boost now uses one of 7 levels: 20%, 30%, 40%, 50%, 60%, 80% and 100% faster. Boosts of **different** levels now add up; two boosts of the same level don't. Before, a tower only got the single strongest boost. Tower details show each boost's level.

### Changed
- **Stronger speed auras:**
  - War Drum Tower at Lord rank: 80% faster (was 70%).
  - Royal Banner Hall and Coral War Hall: 80% faster (was 60%).
  - Star of Winter: 80% faster (was 70%).
- **Risen Poet's reach is smaller.** Her armor strip now covers the area around her (9×9 squares), and her Unveiling song only strips immunities from enemies closest to her (5×5 squares). Both used to reach about 9.5 squares.

### Fixed
- **The installed game keeps working if the website goes down.** Before, if the site was taken down while your device was online, the game showed an error page instead of the saved copy. It now falls back to the saved game whenever the site doesn't answer properly.

## 1.14 — October 28, 2026

### Added
- **A second recipe for Crown Prince's Keep:** Kaminari-Homura + a Lord Cannon Tower + a Lord Alchemist Tower. This recipe builds from towers you've kept, so it doesn't need a single round. The original recipe (Cannon Towers of ranks 1 through 5) still has to be built from one round's new towers.
- **Traveling chain lightning.** Chain and forked lightning now leap visibly from enemy to enemy as a crackling ball, one hop every 0.75 seconds, instead of striking everything at once.
- **Aura rings.** Selecting a tower with auras shows each aura's reach as its own ring: a dashed line for the first, dashes with dots for the second, and dotted for any more.
- **New crews and art.**
  - **Winter's Heart:** an ice mage in frost robes under a slowly turning heart of ice, which shatters into shards on its freezing splash.
  - **Agate Tower:** a master ballista with a crossbowman on each side.

### Changed
- **Bard's Cathedral** now makes nearby towers attack 100% faster (was 70%) and deal 50% more damage. Its second, short-range speed boost is removed.
- **Traps ignore immunities.** The Snare Trap roots enemies whatever their immunities, and no immunity protects against a trap.
- **Traps can't be skipped.** A trap now catches an enemy that passes over it between steps, including one that blinks past.

## 1.13 — October 28, 2026

### Added
- **Risen Poet's Unveiling song.** Enemies within 9.5 squares of the Risen Poet lose their magic and physical immunity while they're in range, so every tower can hurt, slow and stun them. This is on top of her existing 30 armor strip.
- **New hand-drawn crews.**
  - **Bard's Cathedral** now has a trio: a bard on the lute, a flutist and a trumpeter, with notes drifting up from their instruments.
  - **Demon Hunter's Spire** now has an archer in black who levels a hand crossbow in each fist.
- The basic Archer Tower crew is now dressed in off-white.

## 1.12 — October 28, 2026

### Changed
- **Shadow Raven's aura reworked into a Dread aura.** Ravens no longer make nearby towers attack 30% slower. Instead, each living raven slows every *other* enemy on the map by 6.25%, adding up with each raven (capped at 95%).
- **Wave size only shrinks after a wave where an enemy actually got through.** Before, a clean wave could still shrink the next one if enemies had leaked in recent waves.
- Magic influence (Pearl Tower, Coral War Hall, Emerald Watch) now lists disarm and untouchable as the debuffs it blocks, since ravens no longer slow towers.

## 1.11 — October 27, 2026

### Added
- **Flawless wave bonus.** If no enemy gets through a wave, you earn a bonus of 10% of your gold, plus 1% per favor level. Favor 8 adds an extra 3%, for 20% in all. A "Flawless!" message shows how much you got, and the favor panel explains the bonus.
- **Slow levels.** Every slow in the game now uses one of 10 levels, from level 1 (20% slower) to level 10 (90% slower). Tower details show each slow's level.

### Changed
- **Slow stacking.** Each tower or trap counts once, using its strongest slow, and slows from different towers multiply together, even at the same level.
- **Slows strengthened** to fit the new levels:

  | Tower | 1.10 | 1.11 |
  |---|---|---|
  | Frost Trebuchet | 30% | 43% |
  | Frost Siege Engine | 40% | 59% |
  | Grand Champion's Citadel | 35% | 74% |
  | Dark Matter | 35% | 82% |
  | Ice Spire (aura) | 75% | 74% |
  | Frostbite Watch (aura) | 70% | 82% |
  | Star of Winter | 60% slow, 75% aura | 67% slow, 90% aura |
  | Falconer's Roost (flyers) | 45% | 51% |
  | Healer's Abbey (flyers) | 35% | 43% |
  | Skyhunter Lodge (flyers) | 65% | 67% |
  | Robin's Woods (flyers) | 65% | 74% |
  | Yaphet's Monolith (flyers) | 75% | 90% |

- The Mage Tower's frost slow by rank is now 20%, 28%, 36%, 43%, 51% and 59% (Elite, Master and Lord were 44%, 52% and 60%).
- Freezing splash now slows by 59% for 3 seconds (was 50%), and frost balls by 51% for 2 seconds (was 45%).

## 1.10 — October 27, 2026

### Added
- **The Risen Poet replaces Plague Fortress** as the Carved Tourmaline tower. She's a glowing woman in a Greek toga and laurel wreath, floating over her old gravestone and sounding a long herald's trumpet. She fires musical notes, and more notes drift over the ground where her mournful song strips 30 armor from enemies. Her stats are unchanged.

### Changed
- **Recipes for a selected tower are sorted from easiest to hardest**, left to right. Recipes whose pieces must all be built in a single round (secret and ultimate towers, and traps) come last.
- **Smarter resolution drop.** The game now only lowers its drawing resolution when it runs well under 30 frames a second, never goes below 1.5×, and steps back up once it runs smoothly again. Brief hitches, like switching apps or the board redrawing after a camera move, are ignored.

### Fixed
- **iPhone keyboard.** The game no longer stays scrolled out of place after the keyboard opens and closes (for example, when naming a tower).

## 1.9 — October 27, 2026

### Changed
- **Smoother performance, especially on iPhone and iPad.**
  - Panning and zooming are much smoother. While the camera moves, the game slides and scales the last picture of the board instead of redrawing it every frame, then redraws once you stop.
  - If the game is struggling to keep up, it automatically lowers its drawing resolution in small steps (from 2× down to 1×) to keep frames smooth.
  - The hand-drawn characters and farm animals are now prepared once as images instead of being redrawn from their vector art every frame.
  - Glows, fireflies and the hell portal's dark mist are drawn much more cheaply.
  - Towers, crews and enemies that are off screen are skipped.
  - Towers, walls and trees in front of a moving enemy are only redrawn when they actually overlap it.

## 1.8 — October 27, 2026

### Changed
- **Traps can go on prop squares again.** Shops, stalls, training dummies and garden beds no longer block traps (this undoes the 1.7 restriction). A trap on one of those squares replaces the prop.
- **Clearer messages when a trap can't be placed:** "A trap is already on that square", "Traps can't go on a waypoint", or "Traps can't go on your towers or walls".

## 1.7 — October 27, 2026

### Added
- **Lord rank.** A new sixth rank above Master, reached only by upgrading (two Masters, or four Elites). It's never rolled. Lord towers hit far harder; the Lord Archer Tower covers the whole board.
- **Victory scene.** When you win, the camera flies to the hell portal. It shakes, blazes and crumbles to mossy rubble, and a burst of golden light turns its scorched land into a flowering wood full of fireflies.
- **Hand-drawn characters.**
  - The crews of the Archer, Crossbow, Mage, Alchemist and Militia towers are new hand-drawn figures that aim and animate as they attack.
  - Villagers and the king now walk around the castle. They dance and cheer while it stands strong, and panic when it's in trouble.
  - The War Drum Tower gets a band that grows with each rank: snare drummer, trumpeter, bass drummer, horn player and banner bearer.
  - Cannon and Ballista towers are redrawn by rank, and Lords get battle-worn siege engines.
  - Farm animals (cows, sheep and chickens) are redrawn; they bob as they walk and graze.
- **Lakes and forests.**
  - Two still lakes sit in the open grass, with reeds, lily pads and glinting water. They're scenery: you can build on them, and enemies wade across. A saved run whose maze already crosses the lakes keeps them switched off.
  - Pine trees and leafy trees are scattered across open ground. Pines near the hell portal burn, and more catch fire as its scorched land spreads.
- **Magic influence.** Pearl Tower, Coral War Hall and Emerald Watch now shield nearby towers from enemy debuffs.
- **Slow and poison tints.** Slowed enemies turn light blue, poisoned ones turn green, and both turn purple. Poisoned enemies trail little green bubbles.
- **Recipes in Towers built.** The list is grouped by kind of recipe and ordered by difficulty, and each tower shows its recipe as small portraits.

### Changed
- **Slows reworked.**
  - Slows from different towers, traps and auras now stack by multiplying: two 50% slows leave 25% speed. The same source re-applying only refreshes its slow.
  - Slows can't push an enemy below 2 squares a second (naturally slower enemies keep their own speed).
  - To balance this, many slows are weaker: Frost Trebuchet 30% (was 35%), Ice Spire 75% (was 85%), Frostbite Watch 70% (was 85%), Star of Winter 60% slow with a 75% ice aura (was 75% and 90%), Grand Champion's Citadel and Dark Matter 35% (was 50%), Yaphet's Monolith 75% on flyers (was 90%).
  - Flyer slows changed: Falconer's Roost 45% (was 50%), Healer's Abbey 35% (was 50%), Skyhunter Lodge 65% (was 60%), Robin's Woods 65% (was 80%).
- **Cleave is now pure damage.** No armor, resistance or immunity reduces or blocks the Cannon Tower's splash.
- **Grand Astronomer's Tower** now also lands critical strikes.
- Traps can no longer be placed on squares with a building or prop (shops, stalls, training dummies, garden beds).
- The trap you're about to place is always drawn on top, so hills and buildings never hide it.

## 1.6 — October 24, 2026

### Added
- **A market town around the Wishing Well.**
  - Timber-framed shops and market stalls now ring the town square: a baker, smith, tavern, inn, and fruit, cloth, potion and fish sellers.
  - Strings of pennants run from the well's roof out to the shops and flutter in the breeze.
  - The shops are scenery on open squares. Building a tower or wall there replaces them as usual.

### Changed
- **New town square ground.** Packed earth with a few worn, dark flagstones replaces the grey paving, so grey stone towers stand out on it.
- The Wishing Well's description now reads: "The wishing well in the heart of town, ringed by shops and market stalls. The townsfolk gather here to celebrate."

## 1.5 — October 24, 2026

### Added
- **Sign the Book of Records.** When a run ends, won or lost, you sign it with a five-letter name, arcade style: tap ▲ ▼ on each letter, or type it. The game remembers your last name for next time.
- **Dark Matter** replaces Obsidian Keep as the secret Obsidian tower. It's a floating black planet with a violet glow and a ring of dust that hurls huge dark-matter orbs. Its stats are unchanged.

### Changed
- **The Leaderboard is now the Book of Records**, with a new book icon on its button. Every finished run is recorded, longest runs first, then highest damage.
- **Tower range is a circle again**, still measured from the edge of the tower's square (the range plus half a square from its center). Range outlines are circles to match.
- **Towers built** now also counts towers recorded in finished runs and towers standing on the board right now.
- Locked towers in the Towers built view now grey out reliably on iPhone.

### Fixed
- On phones, the end-of-run panel no longer overlaps the title.

## 1.4 — October 24, 2026

### Added
- **Towers built collection.** The Leaderboard has a new **Towers built** tab showing every advanced tower and how many you've built.
  - Towers you've built are in full color. The rest stay greyed out until you build them for the first time.
  - Tap one, or swipe the big turning tower on the board (or use the arrows), to look through them all. Tap × to go back to the runs list.
  - Your collection is remembered across runs on that device.

### Changed
- The Volcano's advanced tower is renamed **Dragon's Perch** (was Dragon's Forge).

### Fixed
- A trap's mark on the ground no longer freezes on screen between waves.
- A sprung trap's effect now plays faster at 2× and 3× speed, matching the trap itself.

## 1.3 — October 24, 2026

### Added
- **The Elder Tree replaces the Mine** as the fifth landmark. It's a huge gnarled tree with an enchanted forest around it: moss, ferns, glowing toadstools and roots that arch in and out of the hills. Its wide crown hangs with swaying, glowing vines, fireflies drift around it, and it has its own sound of rustling leaves and fairy chimes.
- **Special wave warnings.** Before a wave with Invisible, Magic immune or Physical immune enemies, a large red warning appears for about 5 seconds, so you know to prepare.
- **Living landmarks.**
  - The church bell swings in its tower.
  - The barracks banner ripples in the wind.
  - Mist drifts around the top of the middle mountain.

### Changed
- **Tower range is measured from the edge of the tower's square**, not its center, so every tower reaches about half a square farther. Auras and other tower-to-tower effects work the same way.
- Range outlines are now rounded squares that match the real reach.

### Fixed
- Enemies walking over hills no longer flicker or get cut off.

## 1.2 — October 24, 2026

### Fixed
- **Panning to the edges.** You can now drag the board far enough to bring every edge square out from under the side panels, so squares along the left and right edges are easy to see and tap.

## 1.1 — October 24, 2026

### Added
- **More room when zoomed in.** Past 5× zoom, the side panels slide most of the way off screen so the board fills the view. Zoom back out and they slide back in. The default view now fits the whole board between the panels.
- **Icons in the top bar.** Health, Gold and Wave now show a heart, a gold coin and a war banner instead of text labels.
- **Version number** at the top of the How to play panel, so you can tell which version a device is running.

### Changed
- **Kaminari-Homura (Antique Bloodstone)** now strikes once a second for 50 damage, with a 25% chance to fork lightning, while its burning aura keeps damaging everything nearby. Before, it only had the aura. Its strike keeps the tower's own range, separate from the aura.
- **Crown Prince's Keep (The Crown Prince)** now also strikes once a second (25% chance to fork lightning, and it poisons), on top of its huge burning aura.
- Range circles for these two towers now show the aura's size.

### Fixed
- **Sound on iPhone and iPad.**
  - Sound now plays with the silent switch on, like other games.
  - The first tap reliably starts the audio.
  - Sound comes back after you switch away from the game and return.
- **Tooltips from the left panel** now line up with the panel's edge, clear of the iPhone camera cutout, and always show above both side panels.
- **Barracks hall** now sits flat on the ground.
- **Waypoint buildings** (church, wishing well, graveyard, mine, barracks) no longer get cut off by raised ground squares next to them.

## 1.0 — October 24, 2026

First release on GitHub Pages.

- Installs to the iPhone or iPad Home Screen and runs full screen.
- Plays offline after the first launch.
- Landscape only: holding the device upright shows a "turn your device sideways" screen.
- App icon and Home Screen name ("Castle Maze").
