# Beast Mastery Hunter — Patch 12.1.5 (Midnight Season 2)

Compiled 2026-10-15 from Wowhead, Icy Veins, Method.gg, Maxroll and murlok.io. All pages were fetched through the Scrapling MCP server. This file summarizes the guides in its own words. Talent strings and stat lists are copied exactly as published. See [index.md](index.md) for fetch methods and status.

**Patch coverage:** Wowhead, Icy Veins, Method and Maxroll all label their BM pages **12.1.5**. murlok.io labels its data "Patch 12.1 / Season 2" but refreshes live every 8 hours.

Source shorthand used below:

| Tag | Page(s) | Patch / updated |
| --- | --- | --- |
| WH-OV | https://www.wowhead.com/guide/classes/hunter/beast-mastery/overview-pve-dps | Patch 12.1.5, updated 2026/10/13 |
| WH-TAL | https://www.wowhead.com/guide/classes/hunter/beast-mastery/talent-builds-pve-dps | Midnight Season 2 guide set (12.1.5); per-page date not captured |
| WH-ROT | https://www.wowhead.com/guide/classes/hunter/beast-mastery/rotation-cooldowns-pve-dps | Season 2 (12.1.5); per-page date not captured |
| WH-BIS | https://www.wowhead.com/guide/classes/hunter/beast-mastery/bis-gear | Season 2 (12.1.5); per-page date not captured |
| WH-ENC | https://www.wowhead.com/guide/classes/hunter/beast-mastery/enchants-gems-pve-dps | Season 2 (12.1.5); per-page date not captured |
| IV-TAL | https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-spec-builds-talents | 12.1.5, updated Oct 12, 2026 |
| IV-ROT | https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-rotation-cooldowns-abilities | 12.1.5, updated Oct 12, 2026 |
| IV-STAT | https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-stat-priority | 12.1.5, updated Oct 12, 2026 |
| IV-GEAR | https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-gear-best-in-slot | 12.1.5, updated Oct 12, 2026 |
| IV-ENC | https://www.icy-veins.com/wow/beast-mastery-hunter-pve-dps-gems-enchants-consumables | 12.1.5, updated Oct 12, 2026 |
| ME-TAL | https://www.method.gg/guides/beast-mastery-hunter/talents | Patch 12.1.5, updated 13 Oct 2026 |
| ME-STAT | https://www.method.gg/guides/beast-mastery-hunter/stats-races-and-consumables | Patch 12.1.5, updated 13 Oct 2026 |
| MX | https://maxroll.gg/wow/class-guides/beast-mastery-hunter-raid-guide | patch 12.1.5, updated October 10, 2026 |
| MU | https://murlok.io/hunter/beast-mastery/m+ | "Patch 12.1", Season 2, live data (updated ~10 h before fetch) |

The Wowhead BM sub-pages were fetched in a session before the date selector was found. Their individual "updated" dates were therefore not captured. The guide set header shows Patch 12.1.5, and the overview shows 2026/10/13.

---

## 1. Hero talents: Pack Leader vs Dark Ranger

**Consensus: play Pack Leader everywhere.**

- **WH-OV:** Pack Leader is the strongest hero tree in all situations right now. Dark Ranger's main selling point is defense: Smoke Screen.
- **WH-TAL:** Pack Leader is generally strongest. Dark Ranger has stronger defensives "but not much else."
- **IV-TAL:** BM plays Pack Leader in all content. Dark Ranger is tankier but far behind on damage everywhere and harder to play well. Its builds are listed only for people who like the playstyle.
- **ME-TAL:** Both Pack Leader builds (ST/Raid and AoE/M+) are marked "Recommended". The Dark Ranger builds are not.
- **MU (top 50 M+ players):** 49 Pack Leader, 1 Dark Ranger.
- **Disagreement (MX):** Maxroll's hero section calls the two trees very close on single target, with Pack Leader slightly ahead. It says Dark Ranger has better defense and is stronger in *pure AoE raid* scenarios. That paragraph still opens with "Patch 12.0 brought about…" and looks carried over from an older patch, even though the page is stamped 12.1.5. The other four sources disagree with it.

**When to pick each:**
- **Pack Leader:** default for raid ST, raid cleave, M+ and delves. It is simpler. Bestial Wrath makes your next Kill Command fire a 30-yd Stampede, so aim it through the pack.
- **Dark Ranger:** only if you want more survivability. Smoke Screen links Exhilaration and Survival of the Fittest. Wailing Arrow gives an AoE interrupt/silence. Expect a DPS loss.

## 2. Talent builds

Wowhead notes that Solitary Companion loses roughly 10% damage against Animal Companion and is never viable competitively (WH-TAL).

### Raid single-target
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Pack Leader Raid **(Best)** | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGGzsMzwMmZYYmxYmxMzYGzwMzYGzghmBAAAAMDAAAzMzMAzsRYYWAbDAD` |
| IV-TAL | Pack Leader Single-Target | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwwMsBAgZYMzyMDzYmhhZGjZGzMjZMziZmxMmBjpZAAAAAzAAAwYmZAmZjxGMLgtBgB` |
| ME-TAL | Pack Leader Single Target / Raid (Recommended) | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGGzsMzwMmZYYmxYmxMzYmZGmxYGzgx0MAAAAgZAAAYMzMDYmNCDzCYbAYA` |
| WH-TAL / ME-TAL | Dark Ranger Raid / ST | `C0PAAAAAAAAAAAAAAAAAAAAAAYzsNwAGwMsBZsAAgZMjZWMDzYmxMMzYYGzMjZMDzMjZMDGaGAAAAwMAAAMzMzgZGQYYWAbDAD` |

Wowhead's raid build skips Beast Cleave, Kill Cleave and Wild Thrash. It takes Dire Beast, Dire Command, Huntmaster's Call and Wildspeaker, plus every defensive and movement node (WH-TAL).

### Raid AoE / cleave
| Source | Build | Import string |
| --- | --- | --- |
| IV-TAL | Pack Leader Raid AoE/Cleave | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGmZmlZGzMzMjZGMzYmhZGzYmFzMjZMDGTzAAAAAAAAgxMzAMzGZDmFw2AwA` |

IV-TAL says this keeps the full Beast Cleave package from the M+ build and takes Thrill of the Hunt over Training Expert. It is the build for most of the raid, because most bosses have something to cleave. Wowhead lists a "Raid Cleave" tab, but its import table gives only the single-target raid string. The cleave variant could not be extracted from the static page.

### Mythic+
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL / ME-TAL | Pack Leader Mythic+ **(Best)** / AoE-M+ (Recommended) — identical string | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsBzwQDbAAYGPwMzsMzwMzMjZGMzYmhZGzMzYbmZYMDLDNDAAAAAAAAmHYMzAmZjAmFw2AwA` |
| IV-TAL | Pack Leader Mythic+ | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGzMzs8AzYmZmZMzgZGzMMzYmZGbzMjZMDLjpZAAAAAAAAgHYMGwMbEwsA2GAA` |
| WH-TAL / ME-TAL | Dark Ranger Mythic+ | `C0PAAAAAAAAAAAAAAAAAAAAAAYzsNwAGwMsBZsAAgZGzMziZYGmxMjZmZYGzMjZmZsNzMMmhlhmBAAAAMDAAAzDMmZYmBEwsA2GAA` |

The M+ builds add Beast Cleave, Kill Cleave, Wild Thrash, Laceration and Razor Sharp. They also add utility: Tranquilizing Shot, Kodo Tranquilizer, Emergency Salve and Guttural Roar (WH-TAL). IV ranks the flexible points from most to least disposable: Misdirection, then Kodo Tranquilizer, then Emergency Salve. Emergency Salve is only useful in some dungeons.

### Delves (bonus)
| Source | Build | Import string |
| --- | --- | --- |
| WH-TAL | Pack Leader Delves | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGPwMzsMzwMzMjZGMzYmhZmZGzwMzwYmhx0MAAAAAAAAYMmBYmNCWmZBsNAM` |
| IV-TAL | Pack Leader Delves | `C0PAAAAAAAAAAAAAAAAAAAAAAAMmxwCsAzwQDbAAYGzMzs8AzYmZmZMzgZGzMMzYmZGMGzYmhx0AAAAAAAAAzMGDYmNCWmZBsNAA` |
| WH-TAL | Dark Ranger Delves | `C0PAAAAAAAAAAAAAAAAAAAAAAYzsNwAGwMsBZsAAgZGzMziZYGmxMjZmZYGzMzMjZYmZYMzwYaGAAAAwMAAAMGzgZGQwyMLgtBA` |

IV's Dark Ranger strings were in collapsed sections that the static fetch did not return. Use the Wowhead/Method Dark Ranger strings instead.

**Omnium Folio (IV-TAL):** Rune of Unleashed Fire, Rune of Void-Tainted Shell, Rune of Lingering, Rune of Masterful Cunning (Mastery is the safe pick) and Rune of Overload. Wowhead's Folio table did not render statically.

## 3. Rotation

### Opener (IV-ROT)
- **Pack Leader ST:** Hunter's Mark → Barbed Shot → potion/trinket/racials → Barbed Shot → Bestial Wrath → Kill Command → Cobra Shot → Barbed Shot → Kill Command → priority list.
- **Dark Ranger ST:** Hunter's Mark → Barbed Shot → potion/trinket/racials → Barbed Shot → Bestial Wrath → Kill Command → Black Arrow → Kill Command → priority list.
- **Pack Leader M+ AoE:** pre-pot Liquid Luster while gathering. Open with Wild Thrash, then Barbed Shot → Kill Command → Cobra Shot → Kill Command. When Wild Thrash is about 1 GCD from ready: Bestial Wrath → Wild Thrash for a 2-second AoE burst.
- **Pack Leader raid AoE:** Barbed Shot ×2 → potion → Wild Thrash → Bestial Wrath → Kill Command → Cobra Shot → Kill Command.
- **Dark Ranger AoE:** Black Arrow → potion → Bestial Wrath (Wild Thrash first if Black Arrow did not activate Beast Cleave) → Wild Thrash → Kill Command → Barbed Shot → Kill Command → Black Arrow → Kill Command.

### Single-target priority — Pack Leader
Both sources agree on the outline. IV adds tier-set and charge-banking detail.
1. Barbed Shot if Bestial Wrath is ready within ~3 s, or Barbed Shot is about to reach 2 charges.
2. Bestial Wrath on cooldown.
3. (IV) Wild Thrash if more than 1 target.
4. Kill Command if Howl of the Pack Leader is ready.
5. Kill Command with Nature's Ally up. IV says bank a charge if Bestial Wrath is due within 3 s, or Howl within 4 s with only 1 charge left.
6. Cobra Shot with Cobra Fang. IV says at 4 stacks; WH says whenever Cobra Fang is active.
7. Barbed Shot.
8. Cobra Shot (IV: unless Bestial Wrath is less than 1 GCD away).

**Tier note (IV-ROT):** Pack Leader casts Cobra Shot ahead of Barbed Shot at 3 Cobra Fang stacks. Dark Ranger does it at 4.

### Single-target priority — Dark Ranger
1. Barbed Shot if Bestial Wrath is coming off cooldown.
2. Bestial Wrath.
3. Kill Command with Nature's Ally (IV: bank a charge if Bestial Wrath is due within 4 s).
4. Black Arrow. IV says during Withering Fire (the first 10 s of Bestial Wrath), unless Kill Command is about to cap.
5. Wailing Arrow. IV says when Withering Fire is within 2 GCDs of ending; WH says anywhere after Black Arrow and Barbed Shot.
6. Cobra Shot at 4 Cobra Fang, or during Bestial Wrath unless Barbed Shot is near 2 charges.
7. Barbed Shot, then Cobra Shot.

### AoE priority — Pack Leader (IV-ROT)
1. Wild Thrash right after Bestial Wrath, or whenever Beast Cleave is down.
2. Barbed Shot if about to reach 2 charges.
3. Bestial Wrath on cooldown, ideally with Beast Cleave active.
4. Wild Thrash on cooldown. Hold it if Bestial Wrath will be ready before Beast Cleave expires.
5. Kill Command on cooldown. Ignore Nature's Ally on 4+ targets or when Howl is ready.
6. Cobra Shot with Cobra Fang and Beast Cleave both up.
7. Barbed Shot, then Cobra Shot as filler (unless Wild Thrash is under 1 GCD away).

### AoE priority — Dark Ranger (IV-ROT)
Black Arrow to activate Beast Cleave before Bestial Wrath on 3+ targets → Bestial Wrath with Beast Cleave → Wild Thrash after Bestial Wrath or when Beast Cleave is down → Kill Command with Nature's Ally → Barbed Shot near 2 charges → Black Arrow during Withering Fire → Wailing Arrow as Withering Fire ends → Barbed Shot → Black Arrow → Cobra Shot.

**Key concepts (WH-ROT, IV-ROT):**
- Use Bestial Wrath on cooldown. It has a 30 s cooldown and lasts 15 s, and most of your damage lands inside it.
- Enter it with 2 Kill Command charges.
- Never cast two Kill Commands back to back. Weave a filler so Nature's Ally buffs each one.
- Keep the pet on the priority target so Bloodshed applies.
- Line up stat trinkets, potions and racials with Bestial Wrath.
- **Gap:** Wowhead's AoE and opener tabs are rendered by JavaScript and did not come through. Icy Veins covers them.

## 4. Stat priority

| Source | Context | Priority (as published) |
| --- | --- | --- |
| WH-OV | Pack Leader, all situations | Weapon Damage > Agility > Mastery > Critical Strike > Haste > Versatility |
| WH-OV | Dark Ranger single-target | Weapon Damage > Agility > Critical Strike > Mastery > Haste > Versatility |
| WH-OV | Dark Ranger AoE | Weapon Damage > Agility > Mastery > Critical Strike > Haste > Versatility |
| IV-STAT | Single-target | Mastery > Haste > Critical Strike > Versatility |
| IV-STAT | Mythic+ | Mastery > Critical Strike > Versatility > Haste |
| ME-STAT | Single Target | Weapon Damage > Agility > Mastery > Haste => Crit > Versatility |
| ME-STAT | AoE | Weapon Damage > Agility > Mastery > Crit > Vers = Haste |
| MU | Top-50 M+ average | Mastery (+1292) > Critical Strike (+1291) > Haste (+295) > Versatility (+244) |

**Disagreement:** all sources put Mastery first. On single target, Icy Veins and Method put Haste just ahead of Crit, while Wowhead puts Crit ahead of Haste. For M+ or all-round play, everyone has Crit second. Wowhead notes that Ula'tek raid gear carries heavy Crit, which shifts your personal priority. Sim yourself on Raidbots.

IV-STAT diminishing-returns breakpoints:
- Mastery and Crit: 1380 / 1840 / 2300
- Haste: 1320 / 1760 / 2200
- Versatility: 1620 / 2160 / 2700

## 5. Best-in-slot gear, trinkets, embellishments, tier set

### Overall BiS (WH-BIS, single-target focus)
| Slot | Item | Source |
| --- | --- | --- |
| Weapon | Caustic Repose Greatbow | Ula'tek |
| Head | Skulking Viper's Weeping Fangs (tier) | The Twin Fangs |
| Neck | Aqirbane Reliquary | Ula'tek |
| Shoulders | Jaws of the Skulking Viper (tier) | The Coiled Altar |
| Cloak | Silken Voodoo Drape | The Coiled Altar |
| Chest | Skulking Viper's Scuteplate (tier) | Ula'tek |
| Wrist | Farstrider's Plated Bracers | Leatherworking |
| Gloves | Skulking Viper's Hidepiercers (tier) | Kith'ix |
| Belt | Farstrider's Trophy Belt | Leatherworking |
| Legs | Skulking Viper's Coiled Legwraps (tier) | The Coiled Altar |
| Boots | Sabatons of Coruscating Energy | Temple of Sethraliss |
| Rings | Vile Alchemist's Band (Vashnik the Malignant), Band of the Swarmcaller (Kith'ix) | |
| Trinkets | Twisted Horror's Tendril (Kith'ix), Voracious Heart of Ula'tek (Ula'tek); Font of Venomous Rage situationally | |

For M+, Wowhead suggests swapping some Haste/Mastery pieces for Crit/Mastery, for example on crafted gear.

**Catalyst targets:** In 12.1 the Catalyst keeps the item's stats and effects.

| Slot | Wowhead | Icy Veins (raid) | Icy Veins (M+ only) |
| --- | --- | --- | --- |
| Head | Venomcast Effigy | Crown of the Eternal Fang (Nek'zali) | Sethraliss' Fanged Helm |
| Shoulders | Soulslither Spaulders | Soulslither Spaulders | Jangling Felpaulets |
| Chest | Awoken Dreadfang Cuirass | Awoken Dreadfang Cuirass | Loa-Blessed Chestguard |
| Gloves | Aberrant Commander's Gauntlets | Aberrant Commander's Gauntlets | Galerattle Gauntlets |
| Legs | Cuisses of the Uncoiled Union | Cuisses of the Uncoiled Union | Legguards of the Awakening Brood |

IV advises against holding back the 4-piece to chase perfect stats.

**Key drops (IV-GEAR):**
- Raid: Caustic Repose Greatbow and Aqirbane Reliquary (both Venomcursed), Twisted Horror's Tendril, Voracious Heart of Ula'tek, Aberrant Commander's Gauntlets, Band of the Swarmcaller, Apex Brute's Claw Ring.
- M+ (WH-BIS): Ancestral Amani Recurve, Sickening Signet of Atroxus, Charged Sandstone Band, Lustrous Golden Plumage.
- Bonus rolls: IV says spend Nebulous Voidcores on Heroic Ula'tek first.
- Ascendant Venomstones (new in 12.1.5): Weapon, then trinkets, then neck.

### Trinkets
| Tier | Wowhead (raid list) | Icy Veins |
| --- | --- | --- |
| S | Twisted Horror's Tendril, Voracious Heart of Ula'tek, Font of Venomous Rage | Voracious Heart of Ula'tek (on-use), Twisted Horror's Tendril, Lustrous Golden Plumage (on-use) |
| A | Keeper's Seething Core, Zul'jin's Guillotine Technique, Lustrous Golden Plumage, Vile Vial of Volatile Venom, Gebbo's Bottomless Bag, Freightrunner's Flask | Keeper's Seething Core, Zul'jin's Guillotine Technique, Freightrunner's Flask, Vile Vial, Gebbo's Bag, Void Execution Mandate |
| B | Vashnik's Sanguine Rancor, Tattered Amani War Banner, Resonant Bellowstone, Ruby Whelp Shell, Darkmoon Dominion: Hunt | Tattered Amani War Banner, Lightspire Core, Resonant Bellowstone, Vashnik's Sanguine Rancor, Darkmoon Dominion: Hunt, Magister's Alchemist Stone |

- **Disagreement:** Wowhead puts **Font of Venomous Rage** in S tier. Icy Veins puts it in C tier, but notes it often beats its sim when timed with damage amps or priority targets.
- Both sources pair Tendril with Heart as the optimal setup.
- Wear only one stat on-use trinket (IV).
- MU (M+ usage): Heart 48/50, Gebbo's Bottomless Bag 19, Keeper's Seething Core 15, Font 10.

### Tier set — Skulking Viper's Ambush (WH-BIS, IV-ROT)
- **2-piece:** Barbed Shot makes your pets Stomp one extra time at 50% effectiveness, for 4 Stomps per Barbed Shot with Animal Companion. Wowhead puts it at +1.5% ST and +4% AoE.
- **4-piece:** each Stomp makes your next Cobra Shot either benefit from Beast Cleave at 30% or deal +20% to the primary target. It stacks up to 4. Wowhead puts it at +3% ST and +7% AoE. Rotation effect: Cobra Shot moves up the priority at high stacks.

### Embellishments and crafting
- **WH-BIS:** Arcanoweave Lining, Hunter's Ritual Stone and Darkmoon Sigil: Hunt. Hunter's Ritual Stone works on a bow despite its tooltip. Switch to the Sigil if that gets fixed.
  - Early crafts: Aln'hara Sprigshot with Hunter's Ritual Stone, then Farstrider's Trophy Belt or Reinforced Faulds with Arcanoweave Lining.
  - Craft with Mastery/Crit using a Thalassian Missive of the Fireflash.
- **IV-GEAR:** the long-term BiS crafts are Farstrider's Trophy Belt and Farstrider's Plated Bracers with Arcanoweave Lining, Crit/Mastery and a Thalassian Missive of the Peerless.
  - A crafted Aln'hara Sprigshot gives more week-1 power but is likely replaced by a Myth Greatbow.
- **Disagreement on missive:** Wowhead says Fireflash; Icy Veins says Peerless.
- **MU:** Arcanoweave Lining is on 99% of the top 50; Hunter's Ritual Stone on 1%.

## 6. Enchants, gems, consumables

**Enchants:** Wowhead and Icy Veins agree. MU usage matches.

| Slot | Enchant |
| --- | --- |
| Weapon | Rite of the Hash'ey |
| Head | Empowered Rune of Avoidance |
| Shoulders | Amirdrassil's Grace |
| Chest | Mark of the Worldsoul |
| Legs | Forest Hunter's Armor Kit |
| Boots | Lynx's Dexterity |
| Rings | Eyes of the Eagle (WH, IV, MU at 100%) — **Method lists Enchant Ring - Zul'jin's Mastery** |

**Gems:**
- **WH-ENC:** 1× Powerful Eversong Diamond, plus one each of Flawless Deadly Amethyst, Flawless Masterful Lapis, Flawless Masterful Garnet and Flawless Masterful Peridot. Fill the rest with Flawless Deadly Amethyst or Flawless Quick Amethyst, per your sim.
- **IV-ENC and ME-STAT:** 1× Indecipherable Eversong Diamond, with Flawless Deadly Amethyst in every other socket.
- **MU:** Indecipherable 34 vs Powerful 16 among the top 50.
- **Disagreement:** Wowhead prefers the Powerful diamond with a mixed gem set. Icy Veins and Method use the simpler Indecipherable plus all Deadly Amethyst.

**Consumables:**

| Type | Wowhead | Icy Veins | Method |
| --- | --- | --- | --- |
| Flask | Flask of the Magisters | Flask of the Magisters (sim; any secondary flask can win) | Flask of the Shattered Sun (Crit) or Flask of the Magisters (Mastery) |
| Combat potion | Raid: Light's Potential. Near-BiS gear with low Vers: Potion of Recklessness. M+: Liquid Luster | Default: Potion of Recklessness (only if Mastery is your highest stat, else Light's Potential). M+: Liquid Luster | Liquid Luster (6 s pre-pull) or Potion of Recklessness |
| Health potion | Concentrated Silvermoon Health Potion | same | same |
| Augment rune | Void-Touched Augment Rune | same | same |
| Weapon buff | Thalassian Phoenix Oil | same | same |
| Food | Harandar Celebration feast; Royal Roast | Harandar Celebration / Silvermoon Parade; Hearty Royal Roast | Harandar Celebration, Silvermoon Parade; Hearty Royal Roast |

**Disagreement on the raid potion:** Wowhead defaults to Light's Potential and moves to Recklessness later. Icy Veins defaults to Recklessness and falls back to Light's Potential.

**Races:**
- WH-OV: Tauren, Dwarf, Orc or Troll. Orc's Command racial adds pet damage.
- ME-STAT: Dwarf for Alliance, Tauren or Orc for Horde.
- MU: Dwarf is most played (31/50).

## 7. Notable changes in 12.1.x

From WH-OV ("With Patch 12.1… no fundamental changes"):
- Bestial Wrath burst trimmed. Piercing Fangs became a simple Kill Command crit-damage boost. Bloody Frenzy's effect was halved. Withering Fire's Black Arrows now fire at 30% effectiveness.
- **Wild Instincts removed.** Heart of the Pack was redesigned as a flat boost to basic pet attacks.
- Several Cobra Shot talents were nerfed to offset the new tier set.
- **Beast Cleave** now lasts 10 s and cleaves for 55% of pet damage. Kill Cleave now cleaves for only 20% of Kill Command damage.
- Lethal Barbs gives a random chance at extra Focus from Auto Shot instead of a guaranteed amount.
- Through the Eyes is now a flat Black Arrow damage increase.
- Auto Shot damage was increased hugely. Base rotational abilities were buffed to compensate.

Other sources:
- **MX (12.1 dev notes):** steady-state damage was raised via Kill Command, Cobra Shot and Barbed Shot. Beast Cleave duration was increased. For Dark Ranger, Bleak Arrows damage went up 300% and Withering Fire's Black Arrow damage went down 40%.
- **12.1.5 specifically:** no BM-specific class changes were found. Icy Veins' changelogs say "Reviewed for Patch 12.1.5" (12 Oct 2026). The new 12.1.5 systems are gear-side: Ascendant Venomstones and a free Nebulous Voidcore from Orin Straylight (IV-GEAR).
