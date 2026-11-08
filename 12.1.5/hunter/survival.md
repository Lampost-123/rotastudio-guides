# Survival Hunter — Patch 12.1.5 (Midnight Season 2)

Compiled 2026-10-15 from Wowhead, Icy Veins, Method.gg, Maxroll and murlok.io via the Scrapling MCP server. This file summarizes the guides in its own words. Talent strings and stat lists are copied exactly as published. See [index.md](index.md) for fetch methods.

**Patch coverage:** Wowhead, Icy Veins, Method and Maxroll all label their SV pages **12.1.5**. murlok.io says "Patch 12.1 / Season 2" but refreshes live.

**Caution:** some Method SV text looks stale despite its 14 Oct 2026 date. It mentions Butchery, Draught of Rampant Abandon and Flamefang Pitch as current. Wowhead's own Pack Leader priority still lists Flamefang Pitch, which Wowhead's overview says was removed in Season 2. Treat those lines as leftovers.

| Tag | Page | Patch / updated |
| --- | --- | --- |
| WH-OV | https://www.wowhead.com/guide/classes/hunter/survival/overview-pve-dps | Season 2 (12.1.5), updated 2026/10/13 |
| WH-TAL | https://www.wowhead.com/guide/classes/hunter/survival/talent-builds-pve-dps | updated 2026/10/13 |
| WH-ROT | https://www.wowhead.com/guide/classes/hunter/survival/rotation-cooldowns-pve-dps | updated 2026/10/13 |
| WH-BIS | https://www.wowhead.com/guide/classes/hunter/survival/bis-gear | updated 2026/10/13 |
| WH-ENC | https://www.wowhead.com/guide/classes/hunter/survival/enchants-gems-pve-dps | updated 2026/10/13 |
| IV-TAL | https://www.icy-veins.com/wow/survival-hunter-pve-dps-spec-builds-talents | 12.1.5, Oct 12, 2026 |
| IV-ROT | https://www.icy-veins.com/wow/survival-hunter-pve-dps-rotation-cooldowns-abilities | 12.1.5, Oct 12, 2026 |
| IV-STAT | https://www.icy-veins.com/wow/survival-hunter-pve-dps-stat-priority | 12.1.5, Oct 12, 2026 |
| IV-GEAR | https://www.icy-veins.com/wow/survival-hunter-pve-dps-gear-best-in-slot | 12.1.5, Oct 12, 2026 |
| IV-ENC | https://www.icy-veins.com/wow/survival-hunter-pve-dps-gems-enchants-consumables | 12.1.5, Oct 12, 2026 |
| ME-TAL | https://www.method.gg/guides/survival-hunter/talents | Patch 12.1.5, 14 Oct 2026 |
| ME-STAT | https://www.method.gg/guides/survival-hunter/stats-races-and-consumables | Patch 12.1.5, 14 Oct 2026 (partly stale text) |
| MX | https://maxroll.gg/wow/class-guides/survival-hunter-raid-guide | patch 12.1.5, updated October 7, 2026 |
| MU | https://murlok.io/hunter/survival/m+ | "Patch 12.1", Season 2, live (~10 h before fetch) |

---

## 1. Hero talents: Sentinel vs Pack Leader

**Consensus: Sentinel, for both AoE and single target.**

- **WH-OV:** Sentinel is the go-to in Season 2 for both ST and AoE.
  - Pack Leader is close, but downtime hurts it more, and the Boar can be parried or miss without you controlling it.
  - Sentinel also has the better mobility and defensive kit.
  - Defensives: Sentinel's Don't Look Back is proc/RNG based. Pack Leader's Shell Cover is more controllable because it is tied to Survival of the Fittest.
  - Utility: Pack Leader has Masterful Call, an external speed boost. Sentinel has Conditioning, a self speed boost.
- **IV-TAL:** Sentinel for all content. Pack Leader has marginally more priority-target damage, but Sentinel does more on big pulls and is tankier and easier.
- **ME-TAL:** after the 12.1 Pack Leader changes, Sentinel outperforms it in all PvE content. Don't Look Back arguably beats Shell Cover, which Method says mostly stacks defensives.
- **MX:** Sentinel is recommended. **MU:** 43 Sentinel, 7 Pack Leader among the top 50 M+ players.

**When to pick Pack Leader:** on priority-target-heavy fights, if you prefer its Kill Command / beast-summon playstyle (IV), or if you want Masterful Call as group utility (WH).

## 2. Talent builds

IV-TAL says Survival runs variants of its AoE build everywhere except truly pure single-target fights. If Lethal Calibration's Boomstick cooldown reduction does nothing on a fight, take Razor Edge instead.

### Raid single-target
| Source | Build | Import string |
| --- | --- | --- |
| IV-TAL | Sentinel Single-Target | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgtZMzMGzyAAAAAAwMmxMLmxYGzgx0MAAAADAmx2yMzsYMzMjZmBAzYZDGDjNDAA` |
| ME-TAL | Sentinel Single Target | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMGWgNYGGawyMmZGzMLDAAAAAAzYGzssNjxMmBPgpZAAAAGAMjllZmZxYmxYmZAmZDYYMM2MAA` |
| ME-TAL | Pack Leader Single Target | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMGWIbwMM0glZMzMmZWGAAAAAAmxMmZZbGjZMDeATzAAAAMAYGLLzMzixMjxMDgZ2AmFjhxmBA` |

### Raid AoE / cleave (Wowhead's general "Raid" build)
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Raid **(Best)** | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgNjZmxwyAAAAAAwMmZmhZMmxMYMNDAAAwAgZstMzMLmZmZGzMzAwMWAjxMWMAA` |
| IV-TAL | Sentinel Raid AoE/Cleave | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgNjZmxwyAAAAAAwMmxMLmxYGzgx0MAAAADAmxyyMzswMzMjZmBAzYZDGjZmNDAA` |
| WH-TAL | Pack Leader Raid | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMGWIbwMM0gFjZmxMWGAAAAAAmZmZmhZMmxMYMNDAAAwAgZssMzMLMzMzYmxAmZDAjxMWMAA` |
| ME-TAL | Pack Leader AoE | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMGWILwMM0gFzMzMzMWGAAAAAAmxMzMLbzYMjZwYaGAAAgBAPwYZZm5BWYmZwYMgZ2AYGjZmNDA` |
| ME-TAL | Sentinel AoE | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxYGLDgZC2mZmZmZMbzDAAAAAAYGzMzYbGjZMDGTzAAAAMAwYZZmxCmZmxYmBgZsBGjZmNDA` |

IV-TAL says the raid AoE/cleave build drops the single-target build's Bombardier package for Mongoose Fury and Twin Fangs. You gain a lot of cleave for a small ST loss, so it is the most-used build across the raid.

### Mythic+
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Mythic+ **(Best)** | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgtZmZmxMz28AAAAAAAmxMzMMjxMmBjpZAAAAGAgltZGLzYmZGjZGAmxGWMGmZxAA` |
| WH-TAL | Sentinel Mythic+ Pre Tier-set **(Best)** | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgtZmZmxMz2MAAAAAAmxMzMMjxMmBjpZAAAAGAgltZGbzYmxYMzAwM2wixwMLGAA` |
| IV-TAL | Sentinel Mythic+ | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxYGLDgZGYbmZmZmxsNPAAAAAAgZMzMjtZMmxMsMmmBAAAYAgxyyMjFMzMegxYAYGbgxYmZzAAA` |
| WH-TAL | Pack Leader Mythic+ (Wowhead lists the identical string for "Mythic+ Pre Tier-set") | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMG2ILwMM0gFzMzMzMWGAAAAAAmZmZmhZMmxMYMNDAAAwAgHYssMzYhZmZGzMGwMbAYMmZWMAA` |

### Delves (bonus)
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Delves | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxoxyAYmgtZmZmZmZ2mBAAAAAwMzMzMMjhxMDjpZAAAAGAgltZGLDzMGjxAwM2gZMMziBA` |
| IV-TAL | Sentinel Delves | `C8PAAAAAAAAAAAAAAAAAAAAAAMWgBmxYGLDgZGYbmZmZmxsNPAAAAAAgZMzMDGjZMzwYaAAAAAAGLLzMWwMzMzYMAMjNsMjxMzmBAAA` |
| WH-TAL | Pack Leader Delves | `C8PAAAAAAAAAAAAAAAAAAAAAAMgxMG2ILwMM0gFzMzMzMWGAAAAAAmZmZmhZMMmZYMNDAAAwAgHYssMzYhZmZGjxAmZDgZMmZWMAA` |

IV's Pack Leader strings sat in collapsed sections that the static fetch did not return. Use Wowhead's or Method's Pack Leader strings instead.

## 3. Rotation

**Core concept (WH-ROT, IV-ROT):**
- Kill Command grants 2 Tip of the Spear stacks via Primal Surge. The loop is Kill Command → two "Tipped" abilities → repeat ("Always Be Tipping").
- Never overcap Focus or Tip stacks, and don't sit on 2 Kill Command charges.
- Keep Wildfire Bomb and Boomstick on cooldown.
- Every 2nd Raptor Strike becomes Raptor Swipe (Apex). A Raptor Swipe must be Tipped; a plain Raptor Strike does not need to be.
- Without Twin Fangs, Takedown must be cast with **at least 2** Tip stacks, because the pet's hit lands about 1 s later (IV). Twin Fangs instead lets you cast Takedown at 0 Tip, and Takedown then grants 3 stacks.

### Opener (IV-ROT)
The static page shows each opener variant but not which hero/talent toggle it belongs to, so the mapping below is inferred.
- **Variant with Kill Command before Takedown** (fits Pack Leader, which wants Tip stacks and a Howl beast in Takedown): Wildfire Bomb ~1 s pre-pull → Kill Command → potion/trinket/racials → Takedown → Kill Command → Wildfire Bomb ×2 → Boomstick → Raptor Strike → priority.
- **Variant with Takedown immediately** (fits Twin Fangs builds, which can Takedown at 0 Tip): Wildfire Bomb pre-pull → Takedown + potion → Wildfire Bomb → Kill Command → Boomstick → Wildfire Bomb → Raptor Strike → Kill Command → Raptor Strike → priority.
- **Two short Boomstick-first variants:**
  - Wildfire Bomb → Kill Command → potion → Boomstick → Kill Command → Takedown → Wildfire Bomb.
  - Wildfire Bomb → Boomstick + potion → Takedown → Wildfire Bomb.
- **AoE:** Takedown with potion, then Bombs, Kill Command and Boomstick. The Sentinel variant fits Moonlight Chakram in right after Takedown.

### Single-target priority — Pack Leader
1. Hunter's Mark if missing (WH).
2. Kill Command when a Howl of the Pack Leader beast is ready, without wasting Tip stacks.
3. Kill Command once before Takedown to max Tip stacks. Then spend Tip on spenders until you are out of Tip or Focus, and cast Takedown with 2+ Tip.
4. Wildfire Bomb on cooldown, or within 5 s of 2 charges (IV).
5. Boomstick on cooldown.
6. Raptor Swipe / Raptor Strike.
7. Kill Command.

WH-ROT still lists "Flamefang Pitch" after Takedown, but Wowhead's overview says that talent was removed in Season 2. Ignore that line.

### Single-target priority — Sentinel
1. Hunter's Mark if missing.
2. Kill Command when you have no Tip stacks left. Stop generating extra stacks right before Takedown.
3. Boomstick on cooldown.
4. Wildfire Bomb if the target has Sentinel's Mark, or Bomb is 4–6 s from full recharge. IV says within 4 s.
5. Kill Command once before Takedown.
6. Takedown with 2+ Tip stacks, or at 0 Tip with Twin Fangs.
7. Moonlight Chakram, early in Takedown, because it deals its damage slowly (IV).
8. Raptor Swipe, then Raptor Strike.
9. Kill Command as filler, though IV prefers Takedown if it is available.

**Wowhead gap:** WH-ROT's AoE and opener tabs are JavaScript-rendered and did not load.

### AoE priority (IV-ROT)
- **Pack Leader:**
  1. Kill Command below 2 Tip if Howl is ready, or Takedown is about to come up.
  2. Takedown with 2+ Tip (0 with Twin Fangs).
  3. Wildfire Bomb if about to reach 2 charges.
  4. Boomstick.
  5. Wildfire Bomb.
  6. Raptor Strike / Swipe, which must be Tipped.
  7. Kill Command.
- **Sentinel:**
  1. Takedown, then Kill Command when out of Tip.
  2. Boomstick.
  3. Wildfire Bomb, preferring Sentinel's-Marked targets.
  4. Kill Command before Takedown, then Takedown.
  5. Moonlight Chakram.
  6. Raptor Strike / Swipe.
  7. Kill Command.
- **Wildfire Bomb aiming:** the bomb explodes in a small circle around the target *and* in a cone behind it relative to you. Throw it "through" the target to hit mobs behind.

**Cooldown notes:**
- **Takedown:** 1:30, or 1:00 with 2 points of Savagery. It lasts only 8 s, so pack your big hitters inside it.
- **Sentinel:** Takedown turns into Moonlight Chakram. With Stalk and Strike, dump your Bombs first, because Chakram cuts Bomb's cooldown by 10 s.
- **Pack Leader:** Takedown procs Howl. Your first Kill Command inside it launches a Stampede line from your position, so aim it.

## 4. Stat priority

| Source | Context | Priority (as published) |
| --- | --- | --- |
| WH-OV | Both hero trees | Mastery > Critical Strike >= Haste > Versatility |
| WH-BIS | General | Mastery > Crit = Haste > Versatility |
| IV-STAT | All builds | Mastery > Critical Strike > Haste > Versatility (Crit and Haste close enough to treat as interchangeable) |
| ME-STAT | Single Target | Agility > Mastery > Critical Strike = Haste > Versatility |
| ME-STAT | AoE | Agility > Mastery > Haste > Critical Strike > Versatility |
| MU | Top-50 M+ average | Mastery (+1199) > Critical Strike (+907) > Haste (+849) > Versatility (+98) |

**Agreement:** Mastery is clearly first and Versatility clearly last. **Minor disagreement:** Method puts Haste ahead of Crit for AoE; everyone else treats them as roughly equal.

Wowhead warns that Potion of Recklessness picks your *highest* secondary. You want Mastery or Crit to be highest when you pop it. Gems, food and enchants can tweak this.

## 5. Best-in-slot gear, trinkets, embellishments, tier set

### Overall BiS (WH-BIS)
| Slot | Item | Source |
| --- | --- | --- |
| Main hand (DW) | Aman'muso, Warlord's Vengeance | The Coiled Altar |
| Off hand (DW) | Zatha'tek, Breath of Corruption | Ula'tek |
| Two-hand (alt) | Maze-roa, Warlord's Fury | The Coiled Altar |
| Head | Skulking Viper's Weeping Fangs (catalyzed Sethraliss' Fanged Helm) | Temple of Sethraliss |
| Neck | Aqirbane Reliquary | Ula'tek |
| Shoulders | Jaws of the Skulking Viper (catalyzed Soulslither Spaulders) | The Coiled Altar |
| Cloak | Silken Voodoo Drape | The Coiled Altar |
| Chest | Awoken Dreadfang Cuirass | Ula'tek |
| Wrist | Farstrider's Plated Bracers | Crafted |
| Gloves | Skulking Viper's Hidepiercers (catalyzed Aberrant Commander's Gauntlets) | Kith'ix |
| Belt | Farstrider's Trophy Belt | Crafted |
| Legs | Skulking Viper's Coiled Legwraps (catalyzed Cuisses of the Uncoiled Union) | The Coiled Altar |
| Boots | Boots of the Reckless Wayfarer | The Lost Explorers |
| Rings | Apex Brute's Claw Ring (Sszorak), Band of the Swarmcaller (Kith'ix) | |
| Trinkets | Voracious Heart of Ula'tek (Ula'tek), Zul'jin's Guillotine Technique (The Coiled Altar) | |

Wowhead prioritizes "cantrip" (proc) items first and then balances stats.

**Two-hand vs dual wield (sources mostly agree):**
- **WH-BIS:**
  - Maze-roa (2H) is the most well-rounded weapon: about 0.4% behind the best DW set on single target, but about 1% ahead on AoE.
  - Aman'muso + Zatha'tek (DW) is about +0.4% on ST and loses as targets increase.
  - Abyssal Broodfiend's Bardiche starts winning when you regularly fight 3+ targets, and pairs well with Twisted Horror's Tendril in M+.
- **IV-GEAR:**
  - Overall and raid: 2H Maze-roa, 0.9% better than DW.
  - M+: DW with two Sharpened Lightwood Slashers, 0.2% better than 2H.
  - Without Maze-roa the two setups sim within a fraction of a percent, so wear the best weapons you have.
- **ME-TAL:** after the 12.1 Lethal Barbs change, Pack Leader is no longer bound to DW; both options are viable.
- **MU (M+ usage):** Maze-roa 19, Abyssal Broodfiend's Bardiche 14, Aman'muso 8.

**Key drops and rolls:**
- Raid (WH): Maze-roa, Aqirbane Reliquary, Zul'jin's Guillotine Technique, Awoken Dreadfang Cuirass.
- M+ (WH): Sepulchral Construct's Gloves, Sethraliss' Fanged Helm, Sickening Signet of Atroxus, Victor's Flashfrozen Blade.
- Bonus rolls (IV): Heroic Ula'tek (Cuirass, Reliquary, Heart), then Coiled Altar (Maze-roa, Guillotine), then Kith'ix (Gauntlets, Band of the Swarmcaller).
- Ascendant Venomstones: Weapon, then Heart, then other trinket, then neck.

### Trinkets
| Tier | Wowhead (raid) | Icy Veins |
| --- | --- | --- |
| S | Zul'jin's Guillotine Technique, Voracious Heart of Ula'tek, Twisted Horror's Tendril | Voracious Heart of Ula'tek (on-use), Zul'jin's Guillotine Technique |
| A | Keeper's Seething Core, Gebbo's Bottomless Bag | Freightrunner's Flask (on-use), Tattered Amani War Banner (on-use) |
| B | Lustrous Golden Plumage, Lightspire Core, Freightrunner's Flask, Vile Vial of Volatile Venom | Lustrous Golden Plumage, Vile Vial, Twisted Horror's Tendril (best Guillotine substitute), Void Execution Mandate, Keeper's Seething Core |

- **Both:** Heart + Guillotine is optimal.
  - Use Heart with Takedown, but don't hold it more than 20 s (IV).
  - Wowhead's version: Heart has a 90 s cooldown, so it lines up with every other Takedown.
- **Disagreement on Tendril:** Wowhead rates it S tier and exceptional in add-heavy fights and M+. Icy Veins rates it B tier.
- **MU (M+):** Heart 32, Guillotine 28, Keeper's Seething Core 22.

### Tier set — Skulking Viper's Ambush (WH-BIS, IV-ROT)
- **2-piece:** Mongoose Fury also increases Wildfire Bomb damage by 10%.
- **4-piece:** each Boomstick blast extends Mongoose Fury by 1.0 s, and Mongoose Fury's effects are increased by 10%.
- Wowhead's page labels both bonuses "4pc," which is a typo; Icy Veins clarifies 2-set and 4-set.
- **Rotation impact:** none (IV). Sentinel gains slightly more because of Sentinel's Mark Bomb interactions (WH).

### Embellishments and crafting
- **WH-BIS:** Hunter's Ritual Stone (weapon only), Arcanoweave Lining and Adorned Fang.
  - Raider craft order: Farstrider's Plated Bracers + Arcanoweave Lining, then Farstrider's Trophy Belt + Arcanoweave Lining, then Masterwork Sin'dorei Band.
  - M+ craft order: Blood Knight's Impetus + Hunter's Ritual Stone, then Farstrider's Trophy Belt + Arcanoweave Lining, then Masterwork Sin'dorei Band.
- **IV-GEAR:** the armor pair is the long-term play. A crafted weapon is about +8% over a starting M+ weapon early on.
  - Armor: Crit/Mastery with a Thalassian Missive of the Peerless.
  - Weapon: Haste/Mastery with a Thalassian Missive of the Feverflare.
- **MU:** Arcanoweave Lining 90%, Hunter's Ritual Stone 5%.

## 6. Enchants, gems, consumables

**Enchants: the sources disagree here.**

| Slot | Wowhead | Icy Veins | Method (likely partly stale) | murlok M+ usage (top 50) |
| --- | --- | --- | --- | --- |
| Weapon | Rite of the Hash'ey | Rite of the Hash'ey | Acuity of the Ren'dorei | Rite of the Hash'ey 44 |
| Head | Empowered Rune of Avoidance | Empowered Hex of Leeching | Empowered Hex of Leeching | Rune of Avoidance 33 / Hex of Leeching 12 |
| Shoulders | Amirdrassil's Grace | Silvermoon's Mending | Silvermoon's Mending | Amirdrassil's Grace 35 / Silvermoon's Mending 12 |
| Chest | Mark of the Worldsoul | Mark of the Worldsoul | Mark of the Rootwarden | Mark of the Worldsoul 50 |
| Legs | Forest Hunter's Armor Kit | Forest Hunter's Armor Kit | Forest Hunter's Armor Kit | Forest Hunter's Armor Kit 50 |
| Boots | Lynx's Dexterity | Shaladrassil's Roots | Shaladrassil's Roots | Lynx's Dexterity 33 / Shaladrassil's Roots 15 |
| Rings | Eyes of the Eagle | Eyes of the Eagle | Zul'jin's Mastery | Eyes of the Eagle 100 |

The helm, shoulder and boot picks are a straight split between throughput-adjacent and defensive options. Top M+ players mostly match Wowhead.

**Gems:**
- **WH-ENC and IV-ENC:** 1× Indecipherable Eversong Diamond, with Flawless Deadly Amethyst everywhere else.
  - Wowhead's edge case: if Crit and Mastery are nearly tied, swap some gems to Flawless Quick Amethyst so Potion of Recklessness picks Mastery.
- **ME-STAT (differs):** Powerful Eversong Diamond plus Flawless Deadly Amethyst.
- **MU:** Indecipherable 46/50.

**Consumables**

| Type | Wowhead | Icy Veins | Method (likely partly stale) |
| --- | --- | --- | --- |
| Flask | Fleeting Flask of the Magisters | Flask of the Magisters | Flask of the Magisters |
| Combat potion | Potion of Recklessness (all content) | Potion of Recklessness (the only DPS potion worth using) | Draught of Rampant Abandon |
| Health potion | Concentrated Silvermoon Health Potion | same | same |
| Augment rune | Void-Touched Augment Rune | same | same |
| Weapon buff | Thalassian Phoenix Oil | Thalassian Phoenix Oil (both weapons if DW) | Thalassian Phoenix Oil / Refulgent Weightstone |
| Food | Loa's Gathering. You can snapshot its stat by unequipping items; Silvermoon Parade performs about the same | Harandar Celebration or Silvermoon Parade feast; Hearty Royal Roast | Silvermoon Parade |

MX lists Potion of Recklessness as its current recommendation, with Light's Potential as the alternative.

**Races:**
- WH-OV: Human, Troll and Gnome are S tier for raw DPS, but only by 0.2–0.5%.
- ME-STAT: Pandaren and Mechagnome.
- MU: Dwarf 12, Night Elf 9.

## 7. Notable changes in 12.1.x

**Season 2 / 12.1 (WH-OV):**
- The general gameplay loop is unchanged. Primal Surge moved up the tree, which opens new build options.
- **Removed:** Flamefang Pitch.
- **New:**
  - **Bombardier**, a passive Wildfire Bomb buff.
  - A revamped **Grenade Juggler** with lots of cooldown reduction.
  - **Razor Edge**, a passive Raptor Strike / Raptor Swipe buff.

**12.1 Pack Leader changes (MX, ME-TAL):**
- Hogstrider now lasts 1 minute (was 20 s) and is cancelled when a raid encounter or M+ run starts.
- Lethal Barbs now gives auto-attacks a very high chance to generate 3 Focus. Method says this freed Pack Leader from dual wield.
- Method says these changes are why Sentinel now leads.

**12.1.5 (MX patch notes):**
- Fixed Strike as One's bonus damage from Raptor Swipe (Rank 3) not working while Aspect of the Eagle was active.
- Fixed Raptor Swipe having extra range while Aspect of the Eagle was active.
- No other SV-specific 12.1.5 changes were found. Icy Veins pages say "updated for 12.1.5" without listing class changes.
