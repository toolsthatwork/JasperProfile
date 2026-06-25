# JasperProfile

<p align="center">
  <img src="assets/jasperprofile-avatar.png" alt="JasperProfile" width="180">
</p>

General-purpose PvE profiles for xSalice AIO.

Currently available:
- White Mage
- Warrior

This package includes:
- `events/WhiteMage/Jasper_WHM_Events.json`
- `timelines/WhiteMage/Jasper_WHM_Timeline.json`
- `openers/WhiteMage/Jasper_WHM_DPS_Opener.json`
- `events/Warrior/Jasper_WAR_Events.json`
- `timelines/Warrior/Jasper_WAR_Timeline.json`
- `openers/Warrior/Jasper_WAR_DPS_Opener.json`

Installation instructions are available in [INSTALLATION.md](INSTALLATION.md).

White Mage is healing-first for general PvE, with raise, MP, movement, and damage-when-safe behavior. Dungeons and routine duties are primarily event-driven. The timeline profile covers standard 4/8/24-player PvE duties, including Normal, Hard, Extreme, Unreal, Savage, Alliance, and Chaotic entries, while excluding Ultimate.

Warrior is the first tank baseline. It includes event-driven dungeon mitigation, Bloodwhetting recovery, emergency Holmgang, raidwide and tankbuster mitigation, optional co-tank support, and passive timeline coverage.

Openers do not use potions. Timeline profiles do not force potion, weave-toggle, or DPS actions.
