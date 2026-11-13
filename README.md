# Hello Fredbear

A mod for **Hello Neighbor** where you play as Fredbear. Built on
[Hello Nicky](https://github.com/AvanindraPatil/HelloNicky)

<!-- video / screenshots here -->

## Requirements
- Hello Neighbor on Steam (Windows)
- **Fredbear Runaway** (the Hello Neighbor Mod Kit mod by Sdalt), added the normal way in
  `<Hello Neighbor>\HelloNeighbor\Mods\FredbearRunaway`. This mod does **not** include Fredbear: his body, animations and
  sounds are loaded from your Fredbear Runaway while the game runs. The installer checks it first and installs nothing if
  it is missing or incomplete. Keep it in the Mods while you play Hello Fredbear.

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
- "Fredbear Runaway is not installed" when installing: D it into `<Hello Neighbor>\HelloNeighbor\Mods\FredbearRunaway`
  (holding `FredbearRunaway.uplugin` and `Content\Paks\WindowsNoEditor\FredbearRunaway.pak`), then run `Install.bat` again.
- Mods that also change the Neighbor or the player (Hello Playtime, Tom & Jerry, ...) fight with this one: use one at a time.
- Logs: `<Hello Neighbor>\HelloNeighbor\Binaries\Win64\fredbear_lua.log` and `ue4ss\UE4SS.log` in the same folder.

## Credits
- Made by **Gaming with ACK**.
- Fredbear (body, animations, sounds): from **Fredbear Runaway** by **Sdalt**, not included here; loaded from your own download.
- Aaron's 3D model: ["Aaron Peterson Search Rescue"](https://sketchfab.com/3d-models/aaron-peterson-search-rescue-8ffdde502c044df2801a77a65b359747) by **[Crazy Hello Neighbor Fan](https://sketchfab.com/helloneighborgameplay)** (Sketchfab Free Standard licence), re-rigged and animated; shipped only inside the built pak.
- Everything else you see and hear is Hello Neighbor's own content, loaded from your installed game.
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT).
- Built with the help of an AI coding agent.

The mod's code is under the MIT licence. Unofficial fan mod, not affiliated with or endorsed by tinyBuild, Dynamic Pixels
or the makers of Fredbear Runaway.
