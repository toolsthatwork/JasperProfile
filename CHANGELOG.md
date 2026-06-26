# Changelog

## Unreleased

- Split Bard Warden's Paean into default-on self and party cleanse branches, and removed the single-target gate from Red Mage, Pictomancer, and Summoner raidwide mitigation helpers.
- Tightened role defaults after the full job smoke pass: Gunbreaker mitigation now has explicit combat guards, healer fallback heals avoid out-of-combat spending, and Reaper/Samurai self-heals require combat.
- Changed White Mage's Misery-ready Afflatus Rapture branch to cast Rapture directly when party healing is needed.
- Lowered Summoner Rekindle MT automation to 70% HP so it is less likely to spend on light tank damage.
- Promoted all combat jobs to working beta coverage while keeping White Mage as the reference-tested profile.
- Added optional out-of-combat Sprint quality-of-life toggles to White Mage, Astrologian, Sage, and Reaper.
- Polished Reaper baseline toggles with enabled mitigation, Arcane Crest naming, OnWipe opener labeling, and reset toggle cleanup.
- Cleaned misleading event labels for Bard, Black Mage, Machinist, Monk, Astrologian, and Sage.
- Tightened White Mage lily-overcap events so they require real HP recovery targets, and cleaned the WHM passive timeline shell.
- Added Warrior Raw Intuition fallback to the Bloodwhetting helper for synced content.
- Gated Summoner Rekindle MT behind main-tank HP so it is not spent immediately on combat start.
- Polished White Mage emergency healing so Afflatus Solace is used immediately for low tank/party HP even when Afflatus Misery is ready, and restored Divine Caress post-AOE under the AOE mitigation toggle.
- Converted the WHM general timeline to a passive shell: all remaining scripted timeline sequences were removed so roulettes/general duties rely on events and ACR priorities.
- Retuned White Mage for DPS flow: removed forced GCD-heal timeline calls and made ST Regen/Cure/Cure II emergency-only.
- Added a level-sync support pass for early leveling through level 100 duty sync.
- Added Esuna support to White Mage, Astrologian, and Scholar event profiles.
- Added Scholar low-level Succor emergency fallback before Concitation is learned.
- Added Red Mage very-low-threshold Vercure emergency fallback for synced/general content.
- Added Paladin and Dark Knight stance helpers using the same on-wipe stance pattern as the existing tank baselines.
- Added baseline event, timeline, and opener profile files for every combat job.
- Added public testing status notes: White Mage is the main test profile, Warrior/Summoner/Scholar/Paladin are early test profiles, and the remaining jobs are work-in-progress baselines.
- Added passive timeline coverage for standard PvE duty content while excluding Ultimate, PvP, Deep Dungeons, Treasure Hunt, Variant/Criterion/Another, field content, Gold Saucer, BLU-only Carnivale, and solo quest battles.
- Updated White Mage DRK invulnerability handling so Walking Dead remains healable and Undead Rebirth is treated as recovered.
- Added White Mage low-level emergency Cure and Medica fallbacks for Conjurer and synced-down White Mage content.
- Documented the available jobs and current profile scope in the README and installation guide.
