# JasperProfile

<p align="center">
  <img src="assets/jasperprofile-avatar.png" alt="JasperProfile" width="180">
</p>

JasperProfile is a public xSalice AIO profile package for PvE reactions, passive duty coverage, and lightweight opener support.

> Credit where it belongs: Arche provided the general reaction groundwork and wide coverage that helped shape these event profiles. JasperProfile adds Jasper's public-duty safety layer, job controls, xSalice cleanup, and roulette-focused tuning.

## Credits And Lineage

Thank you to Arche for the general reaction groundwork and broad profile coverage behind these public event profiles.

That work took real setup, coverage, and testing time, and the public package should be clear about that lineage. JasperProfile then reshapes the package around Jasper's public-duty safety defaults, job-specific controls, xSalice compatibility cleanup, general roulette testing, and ongoing profile polish.

The public timelines and openers stay broad and passive; encounter-specific optimization belongs outside this public package until it is separately validated. A short standalone credit note is also available in [CREDITS.md](CREDITS.md).

Profiles are tuned for synced duty compatibility from early leveling through level 100. Timeline files avoid forcing cap-only damage actions, and low-level safety fallbacks are included where a job's kit changes heavily while leveling.

Profile files currently exist for all combat jobs:
- Tanks: Dark Knight, Gunbreaker, Paladin, Warrior
- Healers: Astrologian, Sage, Scholar, White Mage
- Melee DPS: Dragoon, Monk, Ninja, Reaper, Samurai, Viper
- Physical ranged DPS: Bard, Dancer, Machinist
- Magical ranged DPS: Black Mage, Pictomancer, Red Mage, Summoner

Each supported combat job has an event profile, a passive timeline file, and an opener file.

## Current Testing Status

Reference public test profile:
- White Mage

Every combat job now has a working beta profile. White Mage remains the reference-tested profile; the other jobs are playable public beta profiles that still need more duty-by-duty tuning.

The non-WHM profiles focus on conservative event automation: mitigation and emergency self-healing are enabled where appropriate, cooldown holds and Sprint quality-of-life toggles stay optional, and passive timelines let normal ACR priorities drive damage flow.

Installation instructions are available in [INSTALLATION.md](INSTALLATION.md).

Recent profile updates are tracked in [CHANGELOG.md](CHANGELOG.md).

White Mage is healing-first for general PvE, with DRK invulnerability recovery handling, cleanse support, synced emergency fallbacks, and damage-when-safe behavior. Tanks include event-driven dungeon mitigation, emergency invulnerability support, raidwide and tankbuster tools, and optional co-tank support where available. DPS profiles focus on practical automation such as mitigation, self-healing, reset guards, optional cooldown holds, and movement quality-of-life.

Timeline profiles mark standard duty coverage for dungeons, trials, raids, alliance raids, Unreal, Extreme trials, Normal raids, Savage raids, and Chaotic alliance duties where available. These files are coverage maps, not scripted rotations; dungeons, roulettes, and normal duties are handled by event reactions plus normal ACR priorities. Fight-specific scripted timelines should be split out separately when they are validated for Savage or similar content. Ultimate, PvP, Deep Dungeons, Treasure Hunt, Variant/Criterion/Another, field content, Gold Saucer, BLU-only Carnivale, and solo quest battles are excluded.

Openers do not use potions. Most starter opener files are intentionally empty until job-specific openers are validated in game. Timeline profiles do not force potion, weave-toggle, or DPS actions.
