# Grail & Trench: Content Catalogue

Oct 17, 2026 · @Misha · companion to `mod-design.md`

This file lists the new traits, cultures, religions, research (EU5 advances) and units. Lore rules are the same as in the design doc: anything from trenchcrusade.com is marked *(canon)*, anything made up is marked *(invented)*, and numbers are first-pass balance targets to tune in testing.

Naming convention for script keys: `gt_` prefix (for example `gt_trait_schism_veteran`), so mod content is easy to grep and never collides with vanilla.

---

## 1. Traits

### Ruler and character traits

| Trait | Type | Source | Effect (first pass) | How it is gained |
| --- | --- | --- | --- | --- |
| Veteran of the Schism | Military | *(invented, from canon Wars of Triclavianism)* | +1 military skill, +10% opinion malus toward former Triclavian enemies | Starting rulers and generals born before 1306 |
| Penitent Knight | Military | *(canon: Oath of Penance)* | +15% morale of led army, +10% shock; character can only die "well" in battle, otherwise −prestige on death | Generals from a Holy Order estate |
| Living Saint | Religious | *(canon: Jeanne d'Arc, Living Saint)* | +25% morale, purges 2 Corruption/month in the army's location, +Curia authority | Unique: Jeanne d'Arc 1428; rare event-only after that |
| Grail-Touched | Health | *(canon: Black Grail infection)* | −2 health per year, −20% opinion from the Clergy; can turn into Grail Thrall on death | Plague events; living in a 50+ Corruption location |
| Plague Survivor | Health | *(invented)* | Immune to further Grail-Touched events, +5% manpower recovery | Survive a Grail infection event |
| Marked by Fire | Personality | *(invented, from canon "burning is the only answer")* | +50% effect of Purification by Fire, −stability on use is halved, −1 diplomatic skill | Order a location burned 3+ times |
| Visionary of the Synod | Learning | *(canon: Synod of Strategic Prophecy, later era)* | +10% advance progress in Faith and Steel trees | Clergy advisors after the Synod advance |
| Steel-Wise | Administrative | *(invented)* | +10% Orichalcum output, +Burghers satisfaction | Rulers of countries with Forge Guilds privilege |
| Wall-Born | Military | *(invented)* | +20% fort defence, +10% artillery damage | Iron Sultanate rulers and generals |
| Takwin Master | Learning | *(canon: takwin, Jabirean alchemists)* | −15% cost of takwin units, +research speed for Alchemy tree | Iron Sultanate scholars |
| Fida'i Trained | Intrigue | *(canon: Alamut assassins)* | +50% success of assassination plots, immune to plots against self | Alamut characters, Sultanate spymasters |
| Debt-Bound | Negative | *(canon: Ten Golden Horns contracts)* | −20% income, hidden: can defect to the Mammon cult in a Betrayal event | Rulers who take loans from a lodge |
| Heretic-Tempted | Negative | *(invented)* | −2 stability yearly while unrevealed; reveals into a defection event | Hidden trait, Serpent cult spread events |
| Branded of the Legion | Infernal | *(canon: Heretic Legion brand)* | +20% shock, +morale, −opinion with all Faithful | All Heretic Legion rulers and generals |
| Anointed | Infernal | *(canon: the Anointed of the Legions)* | +3 military skill, +30% shock; character health −1 per year | Rare Heretic generals |
| Herald of the Fly | Infernal | *(canon: Heralds of Beelzebub)* | Army spreads Grail Corruption +3/month | Black Grail generals |
| Antipope | Infernal unique | *(canon: Antipope of Avignon)* | Missionary bands spawn yearly, +Corruption spread in nearby French locations | Grail ruler of Avignon from 1429 |
| Turncoat Heir | Negative unique | *(canon: Prince of Wales at Bloodied Cliffs)* | Hidden until 1805; defects with a share of the fleet | English heir around 1805 |

### Admiral and general traits

| Trait | Source | Effect |
| --- | --- | --- |
| Rearguard Hero | *(canon: Nelson's last stand)* | Fleet retreats lose 50% fewer ships; on death, sinks the enemy flagship |
| Corsair Captain | *(invented)* | +25% blockade and raid efficiency |
| Dragon's Impaler | *(canon: Order of the Dragon, 1573)* | +Heretic casualties, enemy morale −10% after a won battle |
| Siege-Breaker | *(canon: relief of New Antioch 1721)* | +25% damage when attacking a besieging army |

---

## 2. Cultures

Most European and Middle Eastern cultures stay vanilla. New cultures appear only where the war created new peoples.

| Culture | Group | Where | Source | Starting and spread |
| --- | --- | --- | --- | --- |
| Antiochene | Levantine Latin | Antioch, later New Antioch | *(invented; canon city is many-tongued)* | Primary culture of the Principality; absorbs any volunteer pops that settle there |
| Marcher | Central European | Grail Marches (Hungary, N. Balkans, Friuli) | *(invented)* | Created by Resettlement of corrupted land after 1429 |
| Corsair | Infernal maritime | Gibraltar, Heretic Atlantic ports | *(invented)* | Appears with the Heretic Admiralty in 1666 |
| Legionnaire | Infernal | Heretic Levant | *(invented, canon "citizens of the damned")* | Converted Levantine pops of the Heretic domains |
| Fianna | Gaelic | Éire | *(canon: the Fianna resistance)* | Event culture for Irish resistance after 1807; militia bonuses |
| Varangian Remnant | Norse-Greek | New Antioch | *(canon: last of the Varangian Guard serve in New Antioch)* | Small pop group released after the fall of Constantinople |
| Mamluk Faris | Egyptian | Egypt, later the High Atlas | *(canon: Mamluk exiles after Egypt's fall)* | Starts as the Mamluk ruling class; becomes a desert culture only if Egypt falls |

Cultural traditions to add:

- **Bastion Tradition** (Antiochene): +fort defence, +volunteer manpower.
- **Burn and Rebuild** (Marcher): faster Resettlement, cheaper rebuilt buildings.
- **Sea Wolves** (Corsair): naval raid and blockade bonuses.
- **Every Pockmark a Sign** (any culture with a Sacred Affliction procession, *(canon: Prophet Solon)*): plague deaths reduce Clergy power less, processions give morale.

Pop states, not cultures: **Risen** (Grail undead) and **Corrupted** (cult converts) stay on top of any culture and can be purged or redeemed, as in the design doc.

---

## 3. Religions

Expanded from the design doc table, with mechanics per faith.

### Christian group

| Religion | Source | Head / authority | Key mechanics |
| --- | --- | --- | --- |
| Triclavian Orthodoxy | Name *(invented)*; Church canon | Supreme Pontiff in Rome; Council of Saints *(canon)* | Curia, Grail Crusades, saints and relics as spendable resources, Holy Orders estate, Council of Saints consultations (big one-off bonus, kills a Clergy advisor) |
| Quadriclavian Remnant | *(invented)* | None | Tolerated heresy; +fortification and martyrdom events; can be absorbed by the Curia or rise as a rebellion |
| Eastern Orthodoxy | Vanilla | Patriarch of Constantinople, later in exile | Gains relic mechanics; loses its seat with Constantinople (c. 1545–1573) and gets a Patriarch in Exile modifier |
| Solomonic (Ethiopian) | *(canon: House of Solomon, Ark at Axum)* | Emperor of Abyssinia | Ark of the Covenant relic in Axum: permanent +morale, +Curia-like influence over Sword Congress votes |

### Islamic group

| Religion | Source | Key mechanics |
| --- | --- | --- |
| Sultanate Sunni (Faith of the Wall) | *(canon: Iron Sultanate)* | Alchemy and engineering bonuses; Hijrah of the Wall events pull pops from outside into Sultanate lands; uneasy co-belligerence with the Church (no alliances, but shared-war-score defensive pacts against Hell) |
| Mamluk Sunni | Vanilla Sunni, renamed | Independent of the Sultanate (canon: Mamluks never recognised its suzerainty); trade and merchant power bonuses, but the Merchant Debt mechanic grows over time |
| Nizari Isma'ili | *(canon: Alamut)* | Assassination and espionage bonuses; Seal of Solomon relic makes Alamut immune to Corruption and demonic units |

### Infernal group *(new)*

Infernal religions cannot be converted to by missionaries; they spread through Corruption, debt, plague or conquest.

| Religion | Patron | Source | Key mechanics |
| --- | --- | --- | --- |
| Heretic Legion faith | The ruling Head of the Serpent | *(canon)* | State faith of the Templar Heretics and Heretic domains; ritual sacrifice gives manpower and morale at the cost of pops |
| Court of the Seven-Headed Serpent | Seven archdevils, one per Sin | *(canon: Hell's War Council)* | Every 25–40 years a vote picks the ruling Head (Wrath, Envy, Lust, Pride, Sloth, Gluttony, Greed); each Head gives all Infernal countries a different bonus. Greed (Mammon) never loses his seat *(canon)* |
| Cult of the Black Grail | Beelzebub | *(canon)* | Spreads by plague and Corruption only; Thralls instead of normal pops; refuses the Court (Gluttony seat stays empty *(canon)*) |
| Cult of Mammon (Ten Golden Horns) | Mammon | *(canon)* | Spreads through debt in trade cities; hidden until revealed; contract-bound pops rise as ghouls when the cult strikes |
| Path of the Beast | The Beast | *(canon: Book XIV)* | Pagan-like faith of fallen northern and Irish pops; spreads near Hellmouths |

---

## 4. Research (advances)

EU5 advances are grouped by age. Four new trees run alongside vanilla; each entry gives its age, what it unlocks and its canon anchor.

### Faith tree

| Advance | Age | Unlocks | Source |
| --- | --- | --- | --- |
| Relic Processions | Plague | Relic Procession countermeasure; relics as resource | *(invented)* |
| Sacred Affliction | Plague | Procession units; plague deaths give Clergy power | *(canon: Prophet Solon)* |
| Rites of Penance | Plague | Penitent Knight units; Holy Orders privileges | *(canon: Oath of Penance)* |
| Consecrated Ground | Iron | Shrine building that blocks Corruption | *(invented)* |
| Anointing Oil Fire | Iron | Purification by Fire costs less devastation | *(canon: holy anointing oil flamethrowers)* |
| Order of Reclamation | Walls | Demetrian monks: battles in your land no longer raise Corruption | *(canon: late 16th century)* |
| Anchorite Shrines | Walls | Fort building upgrade: +garrison, never surrenders | *(canon: anchorites in New Antioch's walls)* |
| Strategic Prophecy | Fleets | Synod of Strategic Prophecy: warning events before Heretic offensives | *(canon: Synod)* |

### Steel tree

| Advance | Age | Unlocks | Source |
| --- | --- | --- | --- |
| Orichalcum Alloys | Plague | Orichalcum as a rare trade good | *(canon: Frankish alloys sold to Egypt)* |
| Formula of Angelos | Iron (1503) | Orichalcum Steel; Forge Guilds privileges; Orichalcum armour | *(canon: 1503, Saint Eligius)* |
| Orichalcum Artillery | Iron | Artillery upgrade: +damage, +resistance to counter-battery | *(invented)* |
| Orichalcum Ramparts | Walls | Forts resist artillery | *(invented)* |
| Armoured Hulls | Fleets | Ship upgrade: −damage from cannon | *(invented)* |
| Great Forges | Fleets | Industrial building: steel output ×2, pollution-style Corruption +1 | *(invented)* |

### Alchemy tree (Islamic countries only)

| Advance | Age | Unlocks | Source |
| --- | --- | --- | --- |
| Artillery House | Plague | Sultanate artillery bonuses | *(canon: Royal Artillery House)* |
| Takwin | Plague (1418) | Brazen Bull unit | *(canon: Bayezid III, 821 AH)* |
| Lions of Jabir | Iron | Takwin light cavalry | *(canon)* |
| Automaton Steeds | Iron | Mamluk automaton cavalry | *(canon: Dar al-'Ilm, Cairo)* |
| Buraq Guardians | Walls | Great Gate building: huge garrison, detects spies | *(canon: buraq takwin at the Four Gates)* |
| Storm Engines | Fleets | Weather control: −enemy attrition immunity in Sultanate lands | *(canon: House of Wisdom gale machines)* |

### Infernal tree (Infernal countries only)

| Advance | Age | Unlocks | Source |
| --- | --- | --- | --- |
| Valley of Tears | Plague | Legion recruitment through pilgrimage to the Gate | *(canon)* |
| Goetic Rites | Plague | Sacrifice decisions | *(canon: goetic magic)* |
| Choristers | Iron | Chorister unit | *(canon)* |
| Artillery Witches | Iron | Witch artillery | *(canon)* |
| Infernal Weapon | Iron (1545) | Scripted one-shot used on Antioch | *(canon: 1545)* |
| Sea Hags | Woes | Naval mines and coastal bombardment | *(canon: naval Artillery Witches)* |
| Behemoth Hulls | Fleets | Behemoth capital ship | *(canon: Behemoth Capital Ships)* |

---

## 5. Units

Units fit EU5's infantry, cavalry, artillery and ship categories. The setting's 1914 units are moved back to their period equivalents.

### Faithful (Christian)

| Unit | Category | Age | Source | Notes |
| --- | --- | --- | --- | --- |
| Corpse Levy | Infantry (militia) | Plague | *(invented)* | Cheap undead hunters; bonus vs Risen |
| Procession of the Sacred Affliction | Infantry (irregular) | Plague | *(canon)* | No upkeep, high morale, spread disease to both sides |
| Penitent Knights | Cavalry (heavy) | Plague | *(canon: Crusader Knights)* | Holy Orders only; top shock, no retreat |
| Hospitaller Host | Infantry (heavy) | Plague | *(canon: Knights Hospitaller)* | Order estate levy |
| Sanctified Army | Army modifier | Plague (1428) | *(canon: Jeanne d'Arc)* | France only; purges Corruption |
| Orichalcum Men-at-Arms | Infantry | Iron | *(invented)* | −50% damage from missile fire |
| Flame Wagons | Artillery (support) | Iron | *(canon ancestor: anointing-oil flamethrower tanks)* | Burns Corruption, causes devastation |
| Sacred Order of the Dragon | Cavalry | Walls (1573) | *(canon)* | Wallachia/Hungary only; terror effect on enemy morale |
| Antiochene Garrison | Infantry (garrison) | Walls | *(canon: New Antioch standing army)* | Bonus defending forts |
| Abyssinian Expedition | Infantry (mercenary-like) | Walls | *(canon: seven-yearly expeditionary force)* | Arrives at New Antioch every seven years |
| Hakkapeliitta | Cavalry (light) | Woes | *(canon: Finnish light cavalry)* | Nordic only; forest and winter bonuses |
| Knights of St George | Infantry (marines) | Fleets | *(canon: England)* | England only; boarding bonus |
| Orichalcum Ship of the Line | Ship (heavy) | Fleets | *(invented)* | Needed for the Bloodied Cliffs divergence |

### Iron Sultanate and other Islamic powers

| Unit | Category | Age | Source | Notes |
| --- | --- | --- | --- | --- |
| Azebs | Infantry (light) | Plague | *(canon)* | Skirmishers, feigned flight: −casualties on retreat |
| Janissaries | Infantry (elite) | Plague | *(canon)* | Sultanate household troops; counter-charge bonus |
| Sultanate Sappers | Support | Plague | *(canon)* | Faster sieges, trap-laying defence bonus |
| Wall Artillery | Artillery (static) | Plague | *(canon)* | Fort-only, very long range |
| Brazen Bull | Artillery (living) | Plague (1418) | *(canon)* | Mobile heavy artillery that also fights in melee |
| Lions of Jabir | Cavalry (light) | Iron | *(canon)* | Flank harassment |
| Mamluk Automaton Faris | Cavalry (heavy) | Iron | *(canon)* | Mamluks only; no attrition in desert |
| Fida'i Assassins | Special | Plague | *(canon: Alamut)* | Not an army unit: an action that kills enemy generals |

### Infernal

| Unit | Category | Age | Source | Notes |
| --- | --- | --- | --- | --- |
| Heretic Legionnaires | Infantry | Plague | *(canon)* | Standard Heretic line |
| Yoke Fiends and Wretched | Infantry (slave) | Plague | *(canon)* | Cheap, low morale, driven by fiends |
| War Beasts | Cavalry | Plague | *(canon)* | Possessed creatures; terror effect |
| Grail Thralls | Infantry (undead) | Plague | *(canon)* | No upkeep, spawned from dead pops, spread Corruption |
| Knights of the Order of the Fly | Cavalry (heavy) | Plague | *(canon)* | Grail elite |
| Yersinia Rex | Unique general | Plague | *(canon)* | Grail Hegemon; dies in 1429 |
| Missionary Band | Special | Plague (1429) | *(canon)* | Not an army: spreads the Grail cult around Avignon |
| Anointed | Infantry (elite) | Iron | *(canon)* | Highest shock in the game, loses health over time |
| Choristers | Support | Iron | *(canon)* | Lowers enemy morale |
| Artillery Witches | Artillery | Iron | *(canon)* | Mobile artillery |
| Naval Raiders | Infantry (marines) | Woes | *(canon)* | Coastal raid specialists |
| Behemoth | Ship (capital) | Fleets | *(canon)* | Floating fortress-city; carries raiders |
| Great Red Dragon | Unique ship | Fleets | *(canon: Ranga's flagship, 1805)* | Heretic Admiralty flagship |

---

## Build order hooks

Where each item enters the slices in `mod-design.md`:

| Slice | Content from this file |
| --- | --- |
| 1 Setup | Veteran of the Schism, Branded of the Legion, Wall-Born; Antiochene and Legionnaire cultures; all religions; Azebs, Janissaries, Wall Artillery, Heretic Legionnaires |
| 2 Plague | Grail traits, Living Saint, Penitent Knight; Faith tree to Rites of Penance; Takwin; Corpse Levy, Processions, Grail units, Brazen Bull |
| 3 Steel | Steel tree to Orichalcum Ramparts; Lions of Jabir, Automaton Faris; Infernal Weapon; Orichalcum infantry and Flame Wagons |
| 4 Walls | Marcher, Varangian Remnant; Anchorite Shrines, Order of Reclamation, Buraq Guardians; Order of the Dragon, Abyssinian Expedition; Court of the Serpent votes |
| 5 Fleets | Corsair, Fianna; Armoured Hulls, Behemoth Hulls, Sea Hags; Knights of St George, Naval Raiders, Great Red Dragon; Turncoat Heir, Rearguard Hero |
