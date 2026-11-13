# Hello Fredbear

A mod for **Hello Neighbor** (Steam): **you are Fredbear**, and Nicky is the one sneaking into your house. Built on
[Hello Nicky](https://github.com/AvanindraPatil/HelloNicky): Nicky works through each act's puzzles on his own, on his
way to your basement. Catch him first.

<!-- video / screenshots here -->

## What's in it
- Fredbear from the **Fredbear Runaway** mod: his own body, walk, run and animations, seen through his eyes (F4 = behind him)
- Acts 1, 2 and 3
- Nicky hides in wardrobes and under beds, throws things through windows to escape and knocks your cameras down
- Your tools: tomatoes, glue, a vacuum, bear traps and up to 10 security cameras with a monitor
- Fredbear's own activities in the house (TV, sofa, armchair, bed)
- Several catches: a slap, a hush, an ear pinch, a tackle, the waist grab, with Fredbear's jumpscare scream
- The Act 1 films with Fredbear (and Aaron), and the Act 3 ending with end credits

## Requirements
- Hello Neighbor on Steam (Windows), the full game.
- **Fredbear Runaway** (the Hello Neighbor Mod Kit mod by Sdalt), installed the normal way in
  `<Hello Neighbor>\HelloNeighbor\Mods\FredbearRunaway`. This mod does **not** include Fredbear: his body, animations and
  sounds are loaded from your Fredbear Runaway while the game runs. The installer checks it first and installs nothing if
  it is missing or incomplete. Keep it installed while you play Hello Fredbear.

## Install
1. Install Fredbear Runaway first.
2. Download `HelloFredbear-1.0.0.zip` from [Releases](../../releases) and unzip it anywhere (keep the folder until you uninstall).
3. Close Hello Neighbor and double-click **`Install.bat`**. It finds the game through Steam (or asks for its folder) and
   checks Fredbear Runaway.
4. Start Hello Neighbor from Steam as usual. New Game starts Act 1; Select Act has Acts 1 to 3 unlocked.

The installer adds [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (the mod loader) unless you already have it, and the mod.
No game file is changed, and Fredbear Runaway is not touched. If Hello Nicky is installed, it is switched off while Hello
Fredbear is installed. **Uninstall:** double-click `Uninstall.bat`. It removes the mod (and UE4SS if this installer put it
there) and switches Hello Nicky back on.

## Keys
| Key | What it does |
|---|---|
| Q / R / V / B | tomato / glue / vacuum (hold, or tap to toggle) / bear trap (3 at most) |
| F | check the wardrobe or bed you face (Nicky hiding there is caught) |
| X | put a security camera on the wall you look at (10 at most) |
| Z | camera monitor on / off; Left / Right arrow or X = next camera |
| G / H | use nearby furniture (TV, sofa, bed, armchair); G again = get up |
| T | Fredbear's look-around |
| F4 | Fredbear's eyes / behind him |
| F3 | on-screen text (what Nicky is up to) on / off |
| F9 | restart the round |
| Shift+F9 | jump to the Act 3 basement finale |
| F6 | Nicky's round on / off |
| F8 | the whole mod on / off (back to the normal game) |

## Trouble?
- "Fredbear Runaway is not installed" when installing: install it into `<Hello Neighbor>\HelloNeighbor\Mods\FredbearRunaway`
  (holding `FredbearRunaway.uplugin` and `Content\Paks\WindowsNoEditor\FredbearRunaway.pak`), then run `Install.bat` again.
- Known issue: a rare crash during play (seen once in testing). If it happens, please attach
  `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\fredbear_lua.prev.log` and `fredbear_phase.txt` (before restarting the
  game) to an issue.
- Mods that also change the Neighbor or the player (Hello Playtime, Tom & Jerry, ...) fight with this one: use one at a time.
- Logs: `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\fredbear_lua.log` and `ue4ss\UE4SS.log` in the same folder.
- A game update can break UE4SS mods. Tested with the Steam version of November 2026 and Fredbear Runaway 1.0.

## Credits
- Made by **Gaming with ACK**.
- Fredbear (body, animations, sounds): from **Fredbear Runaway** by **Sdalt**, not included here; loaded from your own install.
- Aaron's 3D model: ["Aaron Peterson Search Rescue"](https://sketchfab.com/3d-models/aaron-peterson-search-rescue-8ffdde502c044df2801a77a65b359747) by **[Crazy Hello Neighbor Fan](https://sketchfab.com/helloneighborgameplay)** (Sketchfab Free Standard licence), re-rigged and animated; shipped only inside the built pak.
- Everything else you see and hear is Hello Neighbor's own content, loaded from your installed game.
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT).
- Built with the help of an AI coding agent (Claude Code, Anthropic).

The mod's code is under the MIT licence. Unofficial fan mod, not affiliated with or endorsed by tinyBuild, Dynamic Pixels
or the makers of Fredbear Runaway.
