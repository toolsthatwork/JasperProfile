# JasperProfile

<p align="center">
  <img src="assets/jasperprofile-avatar.png" alt="JasperProfile" width="180">
</p>

General-purpose PvE reaction, timeline, and opener profiles for xSalice AIO.

Profiles are being built for synced duty compatibility from early leveling through level 100. The profiles avoid forcing cap-only damage actions in timelines, and low-level safety fallbacks are added where the job kit changes heavily while leveling.

Profile files currently exist for all combat jobs:
- Tanks: Dark Knight, Gunbreaker, Paladin, Warrior
- Healers: Astrologian, Sage, Scholar, White Mage
- Melee DPS: Dragoon, Monk, Ninja, Reaper, Samurai, Viper
- Physical ranged DPS: Bard, Dancer, Machinist
- Magical ranged DPS: Black Mage, Pictomancer, Red Mage, Summoner

This package includes event reactions, timeline shells, and opener files for each supported combat job.

## Current Testing Status

Main public test profile:
- White Mage

Early test profiles:
- Warrior
- Summoner
- Scholar
- Paladin

Work-in-progress baseline profiles:
- Tanks: Dark Knight, Gunbreaker
- Healers: Astrologian, Sage
- Physical ranged DPS: Bard, Dancer, Machinist
- Magical ranged DPS: Black Mage, Pictomancer, Red Mage
- Melee DPS: Dragoon, Monk, Ninja, Reaper, Samurai, Viper

The work-in-progress profiles are present so they can be developed and tested, but they should be treated as baseline builds until they have been validated in synced duties and level 100 content.

Installation instructions are available in [INSTALLATION.md](INSTALLATION.md).

Recent profile updates are tracked in [CHANGELOG.md](CHANGELOG.md).

White Mage is healing-first for general PvE, with raise, MP, movement, DRK invulnerability recovery handling, and damage-when-safe behavior. Warrior and the other tank baselines include event-driven dungeon mitigation, emergency invuln support, raidwide and tankbuster mitigation, and optional co-tank support where available. DPS baselines focus on safe event automation such as mitigation, self-healing, reset toggles, optional cooldown holds, and movement quality-of-life.

Timeline profiles cover standard duty content for dungeons, trials, raids, alliance raids, Unreal, Extreme trials, Normal raids, Savage raids, and Chaotic alliance duties where available. General timelines are passive coverage shells and do not force scripted casts; dungeons, roulettes, and normal duties are handled by event reactions plus normal ACR priorities. Fight-specific scripted timelines should be split out separately when they are validated for Savage or similar content. Ultimate, PvP, Deep Dungeons, Treasure Hunt, Variant/Criterion/Another, field content, Gold Saucer, BLU-only Carnivale, and solo quest battles are excluded.

Openers do not use potions. Most starter opener files are intentionally empty until job-specific openers are validated in-game. Timeline profiles do not force potion, weave-toggle, or DPS actions.
