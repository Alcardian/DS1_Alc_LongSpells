# Alcardian's Long Spells
## Description
### Alcardian's Long Spells
A small spell mod that increases spell duration & adds some smaller changes

### Features:
* Changed duration on most buffs & summons to 3600 seconds (1h). 
* Added "updates_on_transformed = false;" to non-LOA buffs to prevent spell from playing its effects on transformed creatures. Same as non-modded/unchanged LOA buffs have. 
* Increased XP from "Healing Wind" to better match "Battle Healing"

### Notes:
Remember that there is an **Unsummon** (default keybind: U) & **Untransform** (default keybind: Y) action, check keybinds ingame. Can be useful if summon gets stuck or you want to exit transformation early.

### Requirements:
Only host in multiplayer needs the mod for it to be enabled. Mod doesn't break compatibility with non-modded game clients.


### Installation instructions:
* Unzip `Alcardian_LongSpells_<ds/dsloa>.zip`
* Copy `Alcardian_LongSpells_<ds/dsloa>.dsres` to Resources folder

### Patch notes
#### 1.1.0
* Long duration changed from 7200 seconds (2h) to 3600 seconds (1h) due to low level annoyance with things like using `Orb of Fire` & then learning `Orb of Acid`.
* Increased duration of buffs & summons excluded in 1.0.0
* Charm duration set to 900 seconds (15min). Was not included in 1.0.0

#### 1.0.0
* Duration Set to 7200 seconds (2h) for buff & summon spells.
  * Doesn't increase duration for (don't know how I want to handle them);
    * Mana Balance
    * Life Balance
    * Harmony
    * Convert
    * Convert Combat
    * Summon Helper (exception for scroll, set to 300s)
    * Bubberjack's Orb of Poultry.

## Dev notes
* Folder path for files: world\contentdb\templates\regular\interactive
  * Include for LOA: "spl_spell.gas" & "dsx_spl_spell.gas"
  * Include for DS (non-LOA): "spl_spell.gas"

### TODO
* Look into "Influence & control" spell category

