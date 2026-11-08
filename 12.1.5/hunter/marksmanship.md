# Marksmanship Hunter — Patch 12.1.5 (Midnight Season 2)

Compiled 2026-10-15 from Wowhead, Icy Veins, Method.gg, Maxroll and murlok.io via the Scrapling MCP server. This file summarizes the guides in its own words. Talent strings and stat lists are copied exactly as published. See [index.md](index.md) for fetch methods.

**Patch coverage:** Wowhead, Icy Veins and Method are on **12.1.5**. **Maxroll's MM guide is still on 12.1** (last updated August 6, 2026) and is flagged as outdated; it is used only where it agrees with newer sources. murlok.io labels its data "Patch 12.1 / Season 2" but refreshes live.

| Tag | Page | Patch / updated |
| --- | --- | --- |
| WH-OV | https://www.wowhead.com/guide/classes/hunter/marksmanship/overview-pve-dps | Patch 12.1.5, updated 2026/10/13 |
| WH-TAL | https://www.wowhead.com/guide/classes/hunter/marksmanship/talent-builds-pve-dps | updated 2026/10/13 |
| WH-ROT | https://www.wowhead.com/guide/classes/hunter/marksmanship/rotation-cooldowns-pve-dps | updated 2026/10/14 |
| WH-BIS | https://www.wowhead.com/guide/classes/hunter/marksmanship/bis-gear | updated 2026/10/13 |
| WH-ENC | https://www.wowhead.com/guide/classes/hunter/marksmanship/enchants-gems-pve-dps | updated 2026/10/13 |
| IV-TAL | https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-spec-builds-talents | 12.1.5, Oct 12, 2026 |
| IV-ROT | https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-rotation-cooldowns-abilities | 12.1.5, **Oct 14, 2026** |
| IV-STAT | https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-stat-priority | 12.1.5, Oct 12, 2026 |
| IV-GEAR | https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-gear-best-in-slot | 12.1.5, Oct 12, 2026 |
| IV-ENC | https://www.icy-veins.com/wow/marksmanship-hunter-pve-dps-gems-enchants-consumables | 12.1.5, Oct 12, 2026 |
| ME-TAL | https://www.method.gg/guides/marksmanship-hunter/talents | Patch 12.1.5, 13 Oct 2026 |
| ME-STAT | https://www.method.gg/guides/marksmanship-hunter/stats-races-and-consumables | Patch 12.1.5, 13 Oct 2026 |
| MX | https://maxroll.gg/wow/class-guides/marksmanship-hunter-raid-guide | **patch 12.1, updated August 6, 2026 — OUTDATED** |
| MU | https://murlok.io/hunter/marksmanship/m+ | "Patch 12.1", Season 2, live (~10 h before fetch) |

---

## 1. Hero talents: Sentinel vs Dark Ranger

**Consensus: Sentinel in all content.**

- **WH-OV:** Sentinel is optimal everywhere with current tuning. It wins on raw throughput, and its rotation is "core" Marksmanship with a smooth, predictable flow.
  - Dark Ranger relies on mechanics that were pruned in Midnight.
  - Its defensive, Smoke Screen, lets Exhilaration trigger your Survival of the Fittest wall on a ~1-minute cycle. Wowhead calls that the stronger defensive when used well.
  - It also brings Wailing Arrow, an AoE interrupt and silence once per Trueshot.
- **IV-TAL:** Sentinel in all content, "with no exceptions." Dark Ranger is a bit tankier, but Sentinel does more damage and is far easier to play.
- **ME-TAL:** all three Sentinel builds are marked Recommended. **MX (12.1):** Sentinel is better in all PvE; Dark Ranger is not recommended. **MU:** 48 Sentinel, 2 Dark Ranger among the top 50 M+ players.

**When to pick Dark Ranger:** only for its defense or utility (Smoke Screen, the Wailing Arrow silence), or if you prefer its proc-driven style.

## 2. Talent builds

### Raid single-target
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Single Target **(Best)** | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAMD2AAAAAAAAAzYmZmFzYmZMDGTzYwYbZmZmZmZmZWwsMYGAAwYmZMAmptNYA2YmtZMA` |
| IV-TAL | Sentinel Single-Target | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAjZwGAAAAAAAAYGzYmFzYmZMDGTzYwYbZmZmZmZmZWYmlBzAAAGzMjBwM22gBYjZ2mxAA` |
| ME-TAL | Sentinel Single Target / Raid (Recommended) | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAMD2AAAAAAAAAzYGzwMmZGzgx0MGM2WmZmZmZmZmFmZZwMAAg5BmZGDgZajhBYjZ2mxA` |
| WH-TAL | Dark Ranger Single Target | `C4PAAAAAAAAAAAAAAAAAAAAAAYzsMwAmgZYbAzCAAAAAAAAYGzMzsYGzMjZwYaGDGbLzMzMzMzMzCmlBDAAwYmZMzMDIbwAsxMbzYA` |
| ME-TAL | Dark Ranger Single Target / Raid | `C4PAAAAAAAAAAAAAAAAAAAAAAYzsMwAmgZYbAzCAAAAAAAAYGzYGmxMzYGMmmxgx2yMzMzMzMzswMLDGAAg5BmZGzMzACDDwGzsNjB` |

IV says the single-target build keeps Volley and Explosive Shot, because the Season 2 tier set is built around them. Wowhead's ST tree takes the following:
- Explosive Shot with Unstable Trigger and Precision Detonation
- Kill Shot
- Bullseye and Feathered Frenzy
- Unerring Vision
- Bulletstorm with Accuracy By Volume
- Blood Fletching

### Raid AoE / cleave
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Raid AoE/Cleave **(Best)** | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAMD2AAAAAAAAAzYmZmFzYmZMDGTzYwsttNzMzMzMzMLYWGmBAAYMzMAYm22gBYjZ2mxA` |
| IV-TAL | Sentinel Raid AoE/Cleave | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGNWGQmBbAAAAAAAAgZMjZWMjZmxMYMNjBz222MzMzMzMzswMLDzAAAMmZGAMjtNYA2YmtZMA` |
| ME-TAL | Sentinel Cleave / Raid (Recommended) | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAMD2AAAAAAAAAzYGzwMmZGzgx0MGMbbbzMzMzMzMzCzsMMDAAw8AzMDAmpNGGgNmZbGD` |

IV-TAL builds the raid cleave version around Aspect of the Hydra and Light Ammo. You keep a single-target rotation while passively cleaving. The raid has heavy cleave, so IV says this is the build for most of it.

### Mythic+
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Mythic+ **(Best)** | `C4PAAAAAAAAAAAAAAAAAAAAAAwGMwMGzYZAMD2AAAAAAAAAzYmZGbzYmZMDLjpZMYW22mZmZmZmZmFmZZYGAAAPwYMAMTbgBYjZ2mxA` |
| IV-TAL | Sentinel Mythic+ | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGNWGQmBbAAAAAAAAgZMzMjtZMzMmhlx0MGMLbbzMzMzMzMzCzsMMDAAgHYMGAmxGYA2YmtZMA` |
| ME-TAL | Sentinel AoE / Trick Shots (Recommended) | `C4PAAAAAAAAAAAAAAAAAAAAAAwGMwMGNWGAzgNAAAAAAAAwMmZmhZMzMmBjpZMYW22mZmZmZmZmFmZZYGAAg5BGzAgZabDGgNmZbGD` |
| WH-TAL | Dark Ranger Mythic+ | `C4PAAAAAAAAAAAAAAAAAAAAAAYzsMwAmgZYbAzCAAAAAAAAYGzMzYbGzMjZYZMNjBzymZMzMzMzMLMzywMAAAegxYmZmBEwAsxMbzYA` |
| ME-TAL | Dark Ranger AoE / Mythic+ | `C4PAAAAAAAAAAAAAAAAAAAAAAYzsMwAmgZYLwsAAAAAAAAAmxMzMMjZmxMYMNjBzymZMzMzMzMLMzywMAAAzDMmxMzMgsBDwGzsNjB` |

The M+ builds take Trick Shots and Light Ammo, swapping Arcane Shot for Multi-Shot as the Precise Shots spender. They drop Kill Shot and add Tranquilizing Shot, Misdirection, Kodo Tranquilizer, Intimidation and Emergency Salve (WH-TAL).

### Delves (bonus)
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Sentinel Delves | `C4PAAAAAAAAAAAAAAAAAAAAAAwGMwMGzYZAMD2AAAAAAAAAzYmZGMmZGzMMmGGMLbbzMzMzMzMzCmthZAAAmZMGAmpNsMDwGzsNjB` |
| IV-TAL | Sentinel Delves | `C4PAAAAAAAAAAAAAAAAAAAAAAwCMwMGzYZAjZwGAAAAAAAAYGzMzgxMzYmhx0wgZZbbmZmZmZmZWwsNMDAAwMjxAwM2wyMAbMz2MG` |
| WH-TAL | Dark Ranger Delves | `C4PAAAAAAAAAAAAAAAAAAAAAAYzsMwAmgZYbAzCAAAAAAAAYGzMzgxMzYmhx0wgZZzMmZmZmZmFMbDzAAAMzYMzMzACWmBYjZ2mxA` |

**Tenacious note (IV-TAL, ME-TAL):** every listed build takes Tenacious (+5% HP, 3% DR). IV puts the cost at 0.6–1.7% DPS in 12.1.5; Method says about 1%. Drop it only if you want pure max damage.

## 3. Rotation

**Core loop (WH-ROT, IV-ROT):**
- Cast Aimed Shot and Rapid Fire on cooldown. Both grant Precise Shots, so follow every one with a spender: Arcane Shot on single target, Multi-Shot on 2+ with Trick Shots or Hydra.
- Add Explosive Shot (cast twice via Unstable Trigger) and Volley on cooldown.
- Steady Shot is the filler, and it can be cast while moving. "Always Be Casting."
- **12.1.5 change:** Rapid Fire no longer spends Precise Shots for you. Sentinel spends Precise Shots before each generator again, except inside Trueshot. Dark Ranger still casts Rapid Fire on cooldown regardless.

### Opener (IV-ROT)
- **Sentinel ST:** Hunter's Mark → Aimed Shot ~2.5 s pre-pull → Explosive Shot ×2 → Volley → Trueshot with potion, trinket and racials → Rapid Fire → Arcane Shot → Aimed Shot → Arcane Shot → priority.
- **Dark Ranger ST:** Aimed Shot pre-pull → Black Arrow → Explosive Shot ×2 → Volley → Trueshot + potion/trinket → Aimed Shot → Black Arrow → priority.
- **Sentinel AoE (Trick Shots):** Aimed Shot pre-pull → Explosive Shot → Explosive Shot on a second target → Volley → Trueshot + potion → Multi-Shot → Rapid Fire → Multi-Shot → Aimed Shot.
- **Dark Ranger AoE:** Aimed Shot pre-pull → Explosive Shot → Volley → Aimed Shot → Black Arrow → Trueshot + potion → Rapid Fire → Aimed Shot → Black Arrow.

### Single-target priority — Sentinel
WH-ROT and IV-ROT largely agree.
1. Use on-use trinkets inside Trueshot.
2. Explosive Shot on cooldown, twice with Unstable Trigger. With Tactical Reload instead, skip it if Lock and Load is already up.
3. Volley on cooldown.
4. Trueshot on cooldown. Save the final one of the fight for 30 Bullseye stacks.
   - IV: delay it up to 15 s so Explosive Shot lands just before.
   - IV: press it on a target *without* Sentinel's Mark, because Feathered Frenzy applies one.
5. Moonlight Chakram with about 5 s left on Trueshot.
6. During Trueshot, Aimed Shot when you have no Precise Shots.
7. Rapid Fire on cooldown when you have no Precise Shots to spend, or while Trueshot is up.
8. Kill Shot to spend Precise Shots. IV adds: when Deathblow procs.
9. Arcane Shot to spend Precise Shots.
10. Aimed Shot on cooldown, preferring Sentinel's-Marked targets.
11. Moonlight Chakram, then Steady Shot.

### Single-target priority — Dark Ranger
1. Trinkets in Trueshot.
2. Black Arrow if you have Precise Shots.
3. Explosive Shot ×2, then Volley.
4. In Trueshot, Aimed Shot without Precise Shots if Black Arrow is ready or Aimed Shot is near 2 charges.
5. Trueshot, saving the last one for 30 Bullseye.
6. Rapid Fire on cooldown.
7. Wailing Arrow on cooldown.
8. Arcane Shot to spend Precise Shots.
9. Aimed Shot, then Black Arrow, then Steady Shot.

IV notes that Wailing Arrow and Trueshot both grant a Black Arrow proc. Use Wailing Arrow when no other guaranteed proc is coming, usually after a Rapid Fire → Black Arrow combo.

### AoE priority (IV-ROT)
- **Without Trick Shots** (Hydra raid cleave): play the single-target rotation, spending Precise Shots on Multi-Shot from 2 targets.
- **Sentinel, Trick Shots:**
  1. Explosive Shot ×2, spread across two targets unless there is a priority target. The tier set's cooldown reduction scales with tick count.
  2. Volley.
  3. Trueshot on an unmarked target.
  4. Moonlight Chakram right before Trueshot expires.
  5. Multi-Shot to spend Precise Shots or to activate Trick Shots. A mouseover macro is recommended; prefer targets without Sentinel's Mark.
  6. Rapid Fire with Trick Shots up.
  7. Aimed Shot with Trick Shots up, preferring marked targets.
  8. Moonlight Chakram, then Steady Shot.
- **Dark Ranger, Trick Shots:**
  1. Explosive Shot ×2, then Volley.
  2. Aimed Shot if it is near 2 charges.
  3. Black Arrow with Precise Shots.
  4. Multi-Shot if Trick Shots is down.
  5. Trueshot.
  6. Rapid Fire.
  7. Wailing Arrow if Black Arrow is not ready.
  8. Multi-Shot to spend Precise Shots.
  9. Aimed Shot, then Black Arrow, then Steady Shot.

**Wowhead gap:** WH-ROT's AoE and opener tabs are JavaScript-rendered and did not load. Icy Veins covers them.

## 4. Stat priority

| Source | Priority (as published) |
| --- | --- |
| WH-OV | Critical Strike >>> Mastery > Versatility > Haste (cheat sheet: Agility, Crit, Mastery, Versatility, Haste) |
| WH-BIS | Crit > Mastery > Versatility > Haste |
| IV-STAT | Critical Strike > Mastery > Versatility > Haste. "Crit is king, with Mastery pretty close behind." Haste is worst by some margin. |
| ME-STAT | Weapon Damage > Agility > Crit > Mastery > Versatility > Haste |
| MU (top-50 M+ average) | Critical Strike (+1505) > Mastery (+1175) > Haste (+301) > Versatility (+219) |

**Agreement:** Crit first and Mastery second everywhere. **Minor disagreement:** the guides rank Versatility over Haste. Top M+ players' gear averages slightly more Haste than Vers, which is likely an itemization effect, not a recommendation. Wowhead's rule of thumb is "Does it have Crit on it?"

## 5. Best-in-slot gear, trinkets, embellishments, tier set

### Overall BiS (WH-BIS)
| Slot | Item | Source |
| --- | --- | --- |
| Weapon | Caustic Repose Greatbow | Ula'tek |
| Head | Skulking Viper's Weeping Fangs (catalyst) | Nek'zali the Soulcoiler head |
| Neck | Aqirbane Reliquary | Ula'tek |
| Shoulders | Jaws of the Skulking Viper (catalyst) | The Coiled Altar |
| Cloak | Silken Voodoo Drape | The Coiled Altar |
| Chest | Skulking Viper's Scuteplate (catalyst) | Ula'tek |
| Wrist | Farstrider's Plated Bracers | Crafted |
| Gloves | Skulking Viper's Hidepiercers (catalyst) | Kith'ix |
| Belt | Farstrider's Trophy Belt | Crafted |
| Legs | Skulking Viper's Coiled Legwraps (catalyst) | The Coiled Altar |
| Boots | Boots of the Reckless Wayfarer | The Lost Explorers |
| Rings | Apex Brute's Claw Ring (Sszorak), Band of the Swarmcaller (Kith'ix) | |
| Trinkets | Voracious Heart of Ula'tek, Font of Venomous Rage | Ula'tek |

- **Catalyst targets (WH-BIS):** Crown of the Eternal Fang (head), Soulslither Spaulders, Awoken Dreadfang Cuirass, Aberrant Commander's Gauntlets, Cuisses of the Uncoiled Union. Catalyzed pieces keep their stats in 12.1. IV: you want Crit and Mastery on what you catalyze.
- **M+ targets (WH-BIS):** Sinseared Repeater, Resonant Bellowstone, Lustrous Golden Plumage, Graft of the Domanaar, Charged Sandstone Band, Signet of Snarling Servitude.
- **Bonus rolls (IV-GEAR):** Heroic Ula'tek first (Greatbow, Reliquary, Cuirass, Heart, Font), then Kith'ix (Gauntlets, Band of the Swarmcaller, Tendril).
- **Ascendant Venomstones (12.1.5):** Weapon, then Heart, then other trinket, then neck.
- **Crest priority (WH-BIS):** Weapon > Trinkets > Head/Chest/Legs > Shoulder/Gloves/Belt/Boots > Rings/Neck > Cloak/Bracer. Upgrade a Myth-track weapon immediately.

### Trinkets
| Tier | Wowhead (raid) | Icy Veins |
| --- | --- | --- |
| S | Voracious Heart of Ula'tek, Font of Venomous Rage | Voracious Heart of Ula'tek (on-use), Font of Venomous Rage (on-use; BiS alongside Heart) |
| A | Twisted Horror's Tendril, Zul'jin's Guillotine Technique | Twisted Horror's Tendril (best Font substitute until a 344 Font), Zul'jin's Guillotine Technique |
| B | Lustrous Golden Plumage, Keeper's Seething Core, Vile Vial of Volatile Venom, Gebbo's Bottomless Bag | Lustrous Golden Plumage (best Heart substitute without Mythic Ula'tek), Keeper's Seething Core, Vile Vial, Gebbo's Bag |

- Both sources agree: Heart with Trueshot, plus Font. Font deals its own damage, so stacking it with Heart is fine, and it can far outperform its sim on damage-amp fights.
- MU: Heart 48/50, Font 40/50.

### Tier set — Skulking Viper's Ambush (WH-BIS)
- **2-piece:** Explosive Shot lasts 1.0 s longer and deals 5% more damage.
- **4-piece:** Aimed Shot and Rapid Fire deal 5% more damage. Each Explosive Shot burst cuts their cooldowns by 0.5 s.
- **Rotation impact:** spread your two Unstable Trigger Explosive Shots across two targets on 2+ targets.

### Embellishments and crafting
- **WH-BIS and IV-GEAR:** two Arcanoweave Lining on Farstrider's Trophy Belt and Farstrider's Plated Bracers is the season-long BiS. Craft them with Crit/Mastery.
  - IV recommends a Thalassian Missive of the Peerless.
  - Wowhead picks the belt over the cloak because a 344 cloak exists. Boots are "basically as good."
- **Alternative:** Aln'hara Sprigshot with Hunter's Ritual Stone gives more week-1 power, but a Myth Greatbow from bonus rolls may replace it within weeks. Farstrider's Reinforced Faulds is a good early legs craft.
- **MU:** Arcanoweave Lining 95%.

## 6. Enchants, gems, consumables

**Enchants**

| Slot | Wowhead and Icy Veins (agree) | Method (differs) |
| --- | --- | --- |
| Weapon | Rite of the Hash'ey | Acuity of the Ren'dorei |
| Head | Empowered Hex of Leeching | Empowered Rune of Avoidance |
| Shoulders | Silvermoon's Mending | Amirdrassil's Grace |
| Chest | Mark of the Worldsoul | Mark of the Worldsoul |
| Legs | Forest Hunter's Armor Kit | Forest Hunter's Armor Kit |
| Boots | Shaladrassil's Roots | Lynx's Dexterity |
| Ring | Eyes of the Eagle | Eyes of the Eagle |

- **MU (M+ usage) is split:** helm Avoidance 25 vs Leeching 22, shoulders Amirdrassil's 30 vs Silvermoon's 18, boots Lynx 25 vs Shaladrassil 21. The weapon is Rite of the Hash'ey on 45/50.
- Wowhead explains Rite of the Hash'ey: it grants your highest secondary while you are above 80% HP, which logs show is 80–85% of raid time.

**Gems (WH-ENC and IV-ENC agree; ME-STAT gives the short version)**
- **5+ sockets:** 1× Powerful Eversong Diamond, plus one each of Flawless Deadly Peridot, Flawless Deadly Amethyst and Flawless Deadly Lapis. Fill the rest with Flawless Masterful Garnet. This maxes the diamond's crit-damage effect.
- **Fewer sockets:** Indecipherable Eversong Diamond with Flawless Masterful Garnet everywhere else.
- Wowhead words the threshold as "more than 4 sockets."

**Consumables**

| Type | Wowhead / Icy Veins | Method |
| --- | --- | --- |
| Flask | Flask of the Shattered Sun | Flask of the Shattered Sun (Crit) or Flask of the Magisters (Mastery) |
| Combat potion | Potion of Recklessness, synced with Trueshot (Light's Potential if Crit is not yet your highest stat). Second potion on 5+ min fights: **Liquid Luster** ~10 s before the execute Trueshot | Potion of Recklessness, then **Light's Potential** as the second potion at fight end |
| Health potion | Concentrated Silvermoon Health Potion | same |
| Weapon buff | Thalassian Phoenix Oil | same |
| Augment rune | Void-Touched Augment Rune | same |
| Food | Harandar Celebration or Silvermoon Parade feast; Hearty Royal Roast | same |

**Disagreement on the second potion:** Wowhead and Icy Veins use Liquid Luster, because Bullseye already gives lots of Crit in execute. Method uses Light's Potential.

**Races:**
- WH-OV and ME-STAT: Dwarf (crit-damage racial plus Stoneform) and Tauren.
- MU: Dwarf on 24/50.

## 7. Notable changes in 12.1.x

**Patch 12.1.5 (WH-OV):**
- **Unload removed.** The new talent **Blood Fletching** takes its place: a critical Aimed Shot leaves a Master Marksman bleed at double damage, and for 4 s the target takes extra bleed damage from each of your abilities.
- Rapid Fire no longer fires an Arcane Shot at the start and end of its channel.
- You must spend Precise Shots manually again. As Sentinel, spend them before every generator, though munching one with Rapid Fire inside Trueshot is fine. Nothing changes for Dark Ranger.

**Patch 12.1 (WH-OV): the biggest rework of the three specs.**
- **Explosive Shot returns** as a core ability. It lasts 3 s and explodes every second, dealing 50% splash within 8 yd, reduced beyond 5 targets.
  - New **Unstable Trigger** allows a second cast within 3 s. It is a choice node against **Tactical Reload** (the old Shrapnel Shot, which now grants Lock and Load).
  - **Precision Detonation** adds +1 s.
- **Rapid Fire now out-damages Aimed Shot per cast.**
- Talent changes:
  - Bulletstorm: Rapid Fire buffs your next Aimed Shot by 20%.
  - Windrunner Quiver: Rapid Fire +10% damage and a 30% Lock and Load chance.
  - Deathblow was reworked.
  - Accuracy By Volume is the old Incendiary Ammunition.
  - Aspect of the Hydra no longer affects Arcane Shot.
  - Eagle's Accuracy is now a single point.
- **Removed:** Double Tap and Headshot.
- **Tuning:**
  - Multi-Shot +72%
  - Kill Shot and Steady Shot +50%
  - Rapid Fire +44%
  - Arcane Shot +38%
  - Aimed Shot and Volley +20%
- **MX (12.1 notes):** for Dark Ranger, Bleak Arrows damage +300%, Withering Fire's Black Arrow −40%, and Through the Eyes redesigned to +10% Kill Shot/Black Arrow damage.
