# No Peace on Earth: EU5 Mod Design

Oct 17, 2026 · @Misha

## Overview

The mod keeps EU5's 1337 start and 1837 end, so the Wars of Triclavianism become baked-in history and the Black Grail Plague replaces the Black Death nine years in. Every later date on the timeline becomes a scripted or semi-scripted turning point the player can accelerate, delay, or survive.

Start window: the game opens in the gap between the end of the Wars of Triclavianism (1306) and the Black Grail (1346). The default start is 1337, matching vanilla EU5; an optional early bookmark in 1307 shows the raw aftermath of the schism, at the cost of rebuilding 30 years of vanilla history.

Design pillars:

- **A war that never ended.** Since the Templars' Act of Ultimate Heresy opened the Gate of Hell at Jerusalem in 1099, the Faithful (Christendom and the Iron Sultanate) have fought a permanent front. Peace is a ceasefire, not a state.
- **Corruption as a second map layer.** Locations carry a Corruption value alongside control and prosperity. High corruption converts pops, spawns Grail rebels, and eventually flips a location to Hell-front wasteland.
- **Faith is a weapon.** Religions are military doctrines. Saints, relics and miracles are deployable resources, not flavour.
- **Industry through desperation.** Orichalcum Steel (1503) is the setting's gunpowder: it reshapes armies, economy and the balance of power.

EU5's six ages map cleanly onto the phases below:

| Vanilla age | Mod age | Years | Turning point |
| --- | --- | --- | --- |
| Traditions | Age of Plague | 1337–1429 | Black Grail, Corpse Wars, Jeanne d'Arc |
| Renaissance | Age of Iron | 1430–1545 | Orichalcum Steel, destruction of Antioch |
| Discovery | Age of Walls | 1546–1595 | Sword Congress of Vienna, walls of New Antioch |
| Reformation | Age of Woes | 1596–1666 | Year of Six Woes: Gibraltar falls |
| Absolutism | Age of Fleets | 1667–1805 | White Cliffs, fall of Templar Acre, Bloodied Cliffs |
| Revolutions | Age of Last Trenches | 1806–1837 | Invasion of Éire, endgame |

## Lore baseline

Lore fidelity is a hard requirement: canon dates and outcomes below are fixed, and anything not in canon is marked *(invented)* in this doc so it can be swapped out if the setting later fills the gap.

Canon timeline inside and around the game window. Checked on Oct 17, 2026 against the official Digital Rulebook timeline and the lore annals on trenchcrusade.com (see **Lore check** at the end for what changed and where each fact comes from):

| Year | Event |
| --- | --- |
| 1072 | Ominous signs, heretical cults multiply; the Knights Templar are founded (setting date, not the real 1118) |
| 1099 | First Crusade takes Jerusalem; the Templars commit the Act of Ultimate Heresy; the Gate of Hell opens and Jerusalem is destroyed |
| 1101 | Year of Three Battles: Heretics, reinforced by the Third Circle of Hell, conquer the Levant. The Fatimid Caliph dies fighting them; the Mamluks seize Egypt soon after |
| 1102 | Antioch fortified, becomes the centre of resistance |
| 1109 | The Great Sultanate of the Invincible Iron Wall of the Two Horns That Pierce the Sky forms, uniting the Islamic factions behind the Iron Wall |
| 1165 | The Old Man of the Mountain and his Hashashins hold Alamut; its siege lasts hundreds of years and it still stands |
| 1215–1306 | Wars of Triclavianism split the Church; the first papal "sacred processions" of refugees date from them |
| 1346–1353 | Beelzebub unleashes the Black Grail; the Corpse Wars begin |
| 1418 (821 AH) | Sultan Bayezid III commissions the Brazen Bull as living field artillery |
| 1429 | Jeanne d'Arc leads the combined forces of the Church at the Battle of Valence, destroys Grail Hegemon Yersinia Rex and drives the Black Grail from mainland Europe, ending the Corpse Wars. The surviving Grail priests storm Avignon the same year |
| 1477 | The City of Argos is taken by God, and is no more |
| 1503 | War Prophet Angelos, guided by Saint Eligius, discovers the formula for Orichalcum Steel |
| 1545 | A mysterious demonic weapon destroys Antioch; the garrison holds the crater |
| c. 1545–1573 | Constantinople falls to the legions of Kimaris, Marquis of Hell |
| 1559 | Sword Congress of Vienna orders Antioch rebuilt and fortified, funded by a yearly tithe from every Faithful nation |
| 1573 | After Byzantium's destruction, the Sacred Order of the Dragon halts the Infernal advance; a million Heretics impaled in the hills of Wallachia |
| 1595 | Walls of New Antioch completed |
| 1666 | Year of Six Woes: the Heretic Fleet captures Gibraltar, which becomes the Sea Fortress |
| 1670 | England begins the Fortress of the White Cliffs of Dover |
| 1703 | A small force of Hebrew Knights destroys the Templar stronghold at Acre |
| 1721 | Third Siege of New Antioch lifted by Sultan Ibrahim's army, Tughlaq warriors and a Papal relief fleet |
| 1805 | Battle of the Bloodied Cliffs: High Captain Ranga's Heretic fleet defeats England; the Prince of Wales changes sides mid-battle; Nelson dies covering the retreat and takes the Heretic flagship *Great Red Dragon* down with him |
| 1807 | The Heretic Basilisk Fleet invades Éire; High King Muiredach is slain at Waterford |
| 1809 | Domus Demetrius ("the Body Barn") built in the Amanus Mountains to process the Faithful dead |

Canon geography that constrains the map:

- **The Levant is Hell's.** Jerusalem is a destroyed city around the Gate ("Jerusalem-that-was"); the Heretics have held the Levant since 1101, and the Templars hold Acre until 1703. Ekron, near the coast, is Beelzebub's city, rebuilt by the Order of the Fly once the Grail is loosed. Hell's earthly holdings are split into **sixty-six domains** ruled by Heretic warlords, not one state.
- **Antioch is the Faithful's bastion** from 1102 until 1545, and New Antioch is the same city rebuilt, not a new site. A Templar fortress (pre-Heresy) stood in the nearby Amanus Mountains.
- **The Iron Sultanate lies behind the Iron Wall.** The Wall is anchored on the Taurus in the north and the Zagros in the east and runs across the Syrian plain to the Gulf. The site places the Sultan's court at **New Damascus** (Cairo's counterpart in diplomacy), with Baghdad's House of Wisdom inside the Wall; the ruler is styled Padishah of Rûm, and the Wall "manifested in the lands ruled by the Sultan of Rûm". Damascus is therefore Sultanate, not Heretic Levant.
- **Alamut lies outside the Wall**, near the Caspian, surrounded by Hell-held land and flanked by the Wall to east and west; the Sultanate protects it indirectly.
- **Egypt is a Mamluk Sultanate and stays Faithful** until 1276 AH (≈1859–60), when Mammon's cult of the Ten Golden Horns betrays it from within. For the whole game window it is an independent Muslim power that never accepts the Iron Sultanate's suzerainty and holds the Sinai line (victory at Bir al-Abed).
- **Avignon is the Black Grail's seat in Europe from 1429**, under a traitor cardinal who made himself Antipope; the Church contains it rather than retaking it.
- **Crete is Faithful**: its corpse caves receive the Church's dead (Domus Demetrius), and its saints' caves are holy sites.
- **The North has its own Hellmouth** on the Kola Peninsula (Ziminiar), opposed by the Kalmar Union, the Northern knightly orders and the Tsardom of Novgorod.
- **By 1914** fan sources say Hell holds the Middle East, North Africa, Anatolia, the Caucasus and the Balkans, with footholds in Northern Italy, Gibraltar, Córdoba, Avignon and Finland; the official site confirms Egypt (Domains of Mammon), Avignon, Gibraltar and Rijeka (1872 landing). The mod's 1337–1837 arc should trend toward that map, not away from it.

Canon gaps the mod fills *(invented)*: what Triclavianism actually teaches and who won its wars; who rules Anatolia in 1337; the six individual woes of 1666; anything about Joan's fate after 1429; when Paladin Engelier killed the other Grail Hegemon.

Canon inconsistencies to be aware of: the Ekron annal dates the Grail's release to 1436 (almost certainly a typo for 1346), and the Missionaries annal says Valence ended "sixty-six years" of war, which would start the Corpse Wars around 1363 rather than 1346. The mod follows the rulebook timeline (1346) and can treat 1346–1362 as the plague and 1363–1429 as open war.

## Pre-start: Wars of Triclavianism (1215–1306)

The Triclavian schism ended 31 years before game start, so it lives in the setup: split religions, scarred borders and grudges baked into opinions.

Canon only says the wars split the Church and killed millions. Backstory *(invented)*: the Church split over whether Christ was nailed with three nails (Triclavian) or four, a dispute that became a question of which relics and rites could hold back Hell. The Triclavians won militarily but never fully absorbed the losers.

What this sets up at 1337:

- **Two Catholic-family faiths** *(names and split invented)*. Triclavian Orthodoxy (dominant, controls the Curia) and Quadriclavian remnants (tolerated heresy in pockets of southern France, Bohemia, the Rhineland).
- **Ruined buffer regions.** Languedoc and parts of Lombardy start with low prosperity, depopulated locations and high devastation.
- **Militant orders as estates.** The Templars are the arch-heretics of this world, so the Christian militant orders are the Hospitallers (canon: officially sanctioned, with whole armies), the Teutonic Order (canon: founded in the wake of the Heresy), the Order of Saint Lazarus and other loyal orders; they form a powerful Clergy sub-estate in France, Iberia, Prussia and the Mediterranean. Canon gives them the Oath of Penance imposed by the Council of Saints after the Templar betrayal: a knight is saved only by dying in battle against Hell, which suits a high-morale, low-loyalty-risk estate. The Sacred Order of the Dragon is canon from 1573 at the latest.
- **Sacred processions.** Papal bulls recognised refugee "sacred processions" during the Triclavian wars (canon); they can start as a small pilgrim/peasant estate flavour that grows into the Flagellant-style processions of Phase 1.
- **Opinion and claims.** Former Triclavian enemies start with negative opinion and historical rivalries; several minors hold old claims on each other.
- **History flavour.** Starting rulers get traits like Veteran of the Schism; a few locations get permanent modifiers such as Burned Cathedral or Martyrs' Field.

## Phase 1: Black Grail Plague and the Corpse Wars (1337–1353)

The Black Death situation is rebuilt as the Black Grail: Beelzebub's plague kills pops like vanilla, but the infected become his vessels.

**1337–1345, the calm before.** Europe fights the Hundred Years War and the Levantine front as normal. Event chain: Grail cultists seen in Kaffa, Constantinople and Messina; the player can investigate, burn suspects (stability cost) or ignore it.

**1346, the outbreak.** The plague enters through Black Sea ports, as the Black Death did, and spreads along trade routes.

- Infected locations lose pops each month; a share of the dead become a Risen pop type with no output and rising Corruption.
- At 50+ Corruption a location can spawn Grail rebels; at 100 it flips to the Black Grail tag.
- Countermeasures: quarantine (trade loss), purification by fire (devastation), relic processions (Clergy power, costs relics). Canon: there is no inoculation, and burning infected settlements is the only answer, so fire should be the strongest and most costly option and no cure tech should exist.
- Canon flavour: the Grail arrives as a nine-day swarm of hell-flies, locusts and scorpions out of a Hellgate, then lingers as infection; the infected rise as Thralls led by knights of the Order of the Fly. Beelzebub only unleashes it when he wins Hell's power struggles, so periodic flare-ups after 1429 are canon-friendly.

**1347–1353, the Corpse Wars.** The Black Grail host forms as a playable but AI-default tag in the Balkans and Italy, at war with everyone, led by Grail Hegemon Yersinia Rex in Beelzebub's name.

- Situation ends in 1353 either contained (Grail holds under 15 locations) or entrenched (Grail controls a region, Phase 2 starts harder).
- Survivors get the vanilla post-plague labour-scarcity effects, plus Corpse Levies: cheap undead-hunter militia units.

**Player hooks.** Plague doctors as a new advisor type; the Flagellant movement as a peasant-estate rebellion with crusade bonuses. Canon has a better fit: the first Procession of the Sacred Affliction formed at the onset of the Corpse Wars under the Prophet Solon (lepers turned away by towns, who emerged healed after seven days sealed in a tomb, then spread through Europe and North Africa). Use the Solon miracle as the event that creates the procession movement.

## Phase 2: Grail occupation and the Living Saint (1354–1429)

The Black Grail holds a corrupted heartland until 1429, when Jeanne d'Arc slays Yersinia Rex and drives the Grail off the mainland.

**1354–1410, the Grail Marches.** The Grail tag consolidates a dead zone (default *(invented)*: Hungary, the northern Balkans, Friuli). Bordering countries get the Grail March frontier law: higher fort upkeep, militarised peasants, permanent CB.

- The Hundred Years War continues but is weaker; both crowns lose manpower to the Grail front.
- The Curia calls repeated Grail Crusades: Curia-led coalitions with shared war score and relic rewards.

**1418, the Brazen Bull.** Sultan Bayezid III commissions the Brazen Bull (821 AH): a unique Iron Sultanate artillery unit unlocked by event. Canon says the Jabirean scientists laboured for centuries to perfect takwin (artificial creatures), so treat 1418 as the start of a long Sultanate tech line (Bulls, Lions of Jabir, the buraq gate guardians) rather than an instant unlock.

**1412–1429, the Living Saint.** Joan is born in Domrémy (1412) and gets a scripted rise.

- 1428: event chain (visions, Chinon, Orléans) gives France the Maid of Orléans general with unique Sanctified Army modifiers and a Corruption-purging aura.
- 1429: the Battle of Valence (canon). Joan leads the combined forces of the Church (France, the Holy Roman Empire and England fight together, so the Hundred Years War must pause into a Grail truce) and destroys Grail Hegemon Yersinia Rex. The Expulsion event fires if the coalition holds a set number of Grail locations. Remaining Grail mainland holdings collapse into rebels and wasteland.
- 1429, the Fall of Avignon (canon). The Grail's priests and heralds break the encirclement and turn south while the exhausted victors do not pursue. A traitor cardinal of Avignon opens the gates; the city becomes the Grail's European seat under the Antipope (Patriarch of Beelzebub). The Grail tag survives as a one-location enclave around Avignon with a Containment situation: France and the Church keep standing forces nearby, attempts to retake it feed the Grail, and Missionary bands and Temples of the Fly creep outward a little every year. This replaces the earlier *(invented)* Sicily/Crete retreat; Crete is Faithful in canon.
- Only two Grail Hegemons ever rise in canon (Yersinia Rex and one slain by Paladin Engelier), so later flare-ups must not spawn new Hegemons, except possibly one scripted Engelier event.
- Failure path: if France is too weak, Joan still appears but the Expulsion is a long war instead of a collapse. Canon fixes the outcome, so the failure path only delays it, never cancels it.
- Vanilla note: in 1337 the papacy sits in Avignon. Canon has the Pope in Rome with Avignon a bishopric, so move the Curia seat to Rome at game start.

**Aftermath** *(invented)*. Joan becomes a Living Saint character, a new religious figure who boosts Curia authority. Her fate (martyrdom, ascension, or rule) is an event choice with big long-term effects on France.

## Phase 3: Orichalcum Steel and the destruction of Antioch (1430–1545)

This age is an arms race: whoever masters Orichalcum Steel first gets an edge, and Hell answers by destroying Antioch in 1545.

**1430–1502, rebuilding.** Post-Grail Europe resettles wasteland. New colonisation mechanic inside Europe: Resettlement of corrupted locations, slow and expensive.

**1477, Argos.** God destroys the City of Argos: a one-off event that turns the location to wasteland and shakes every Faithful country's stability. Who held Argos and why is *(invented)*.

**1503, Orichalcum Steel.** Canon makes it a formula, discovered by War Prophet Angelos guided by Saint Eligius, not an ore, so it is an advance rather than a mined resource. Canon also mentions orichalcum alloys sold by the Franks to Mamluk Egypt centuries earlier, and later says England's "reserves of Orichalcum" ran out, so a rare orichalcum trade good can exist before 1503, with the formula turning it into a mass-producible steel.

- Advance: Orichalcum armour, artillery and fortifications; the canon property is resistance to missile weapons, so the main effect is a defence bonus against ranged and artillery damage.
- Discovery event: Angelos appears as a character for the most advanced Faithful country; others spread the formula via neighbours, trade or espionage, like vanilla institution spread.
- Burghers estate gains the Forge Guilds privilege line; refusing it caps your steel output.

**1520s–1545, the shadow over Antioch.** Antioch has been the Faithful's bastion since 1102. Warning events: tremors, silent bells, deserting garrisons.

- 1545: Antioch destroyed by a mysterious demonic weapon. The location becomes a crater that the Faithful garrison still holds despite lethal demonic essence (canon): a special fort with no economy and heavy attrition.
- c. 1545–1573: Constantinople falls to the legions of Kimaris, Marquis of Hell (canon, exact year unknown). Script it as a Heretic offensive that Byzantium cannot win, so the 1573 Dragon event has its trigger.
- Every Christian country takes a stability hit and gains the Antioch Must Rise modifier, feeding Phase 4.
- The Iron Sultanate gets a choice: aid the survivors (truce, opinion) or exploit the gap (war, risk Corruption).

## Phase 4: New Antioch and the Year of Six Woes (1546–1666)

Christendom rebuilds its bastion, then loses the sea gate to the Atlantic in a single catastrophic year.

**1559, the Sword Congress of Vienna.** An event in Vienna orders Antioch rebuilt and fortified, funded by a yearly tithe from every Faithful nation. The Congress becomes a standing body: Abyssinia (the Solomonic Empire) is canonically Africa's representative, so membership is not just Europe.

**1559–1595, the Walls of New Antioch.** A Great Project (EU5 monuments) on the ruins of Antioch itself.

- The canon tithe is "rarely in the form of coin": it arrives as supply trains of food, tools, ammunition, machinery, workers and engineers, convoyed past Heretic raiders. Model it as an automatic yearly contribution of goods and manpower from every Faithful country, with a trade-route/convoy risk; extra gold on top speeds it up. Completion is scripted for around 1595 but can come earlier or later.
- Abyssinia's canon contribution: an expeditionary force every seven years, crossing the Mediterranean because the Red Sea is Heretic-held.
- On completion the Principality of New Antioch regains its full strength. Canon walls have seventy-seven towers with anchorite shrines built in, and by 1914 have survived eight great sieges unbreached.
- The ruler is the Duke of New Antioch, nominal supreme commander of all Faithful forces (use Duke as the ruler title even though the state is a principality).
- Biggest contributor gains a Patron of the Walls bonus and influence over the Principality.

**1573, the Order of the Dragon.** Byzantium has fallen to the Heretics by now (canon); the Sacred Order of the Dragon halts their advance in Wallachia. Event for the Wallachian or Hungarian owner, with a large one-off Heretic casualty battle.

**1596–1665, the long ceasefire.** Wealth from the colonies and steel grows; heresy grows with it. A Heretic faith (Court of the Seven-Headed Serpent) spreads through ports and underground lodges, mostly in Mediterranean and Atlantic trade cities. Canon model for this: Mammon's Ten Golden Horns in Mamluk Egypt, a secret lending society that tattooed debt contracts on its clients' skins and turned the indebted poor into a fifth column. Reuse that pattern (debt, merchant estate, hidden cult) for the port lodges. Late 16th century also brings the Demetrian Order of Reclamation (canon) after Paladin Gérin's descent into Hell, a natural Clergy event.

**1666, the Year of Six Woes.** Canon only names the climax: Heretics seize Gibraltar in a surprise raid and gain the Atlantic. The other five woes are *(invented)*, a cascade during the same year where each woe hits a different system:

1. Fire: a great city burns (London by default, echoing 1666).
2. Plague: a Grail flare-up in a port.
3. Schism: a heretic uprising inside a Christian realm.
4. Famine: crop failure across a region.
5. Betrayal: a key ruler or general defects.
6. The Fall of Gibraltar *(canon)*: the Heretic Fleet seizes the strait and turns Gibraltar into the Sea Fortress, creating the Heretic Admiralty tag *(name invented)*. Canon still uses Gibraltar as the Heretic fleet's home port in the 19th century (the fleet retreats there from Éire).

Six woes give the setting its Reformation equivalent: countries that keep stability through all six get a big legitimacy bonus; those that do not may face civil war.

## Phase 5: Atlantic heresy war and the Bloodied Cliffs (1667–1837)

With Gibraltar lost, the war goes oceanic: Heretic fleets raid the Atlantic and colonies, culminating in England's naval defeat in 1805.

**1667–1780, the Atlantic front.**

- 1670: England begins the Fortress of the White Cliffs, a Great Project on the Dover coast that protects English coastal locations from raids.
- The Heretic Admiralty raids trade, colonial coasts and convoys. Colonial nations gain a Corsair Threat modifier that scales with Admiralty fleet strength.
- 1703: Hebrew Knights destroy the Templar stronghold at Acre: event that removes or cripples the Templar Heretic tag's hold on the coast.
- 1721: the Third Siege of New Antioch, lifted by a joint relief of Sultan Ibrahim's army, Tughlaq warriors and a Papal fleet (canon). This makes it the setting's showcase Christian–Muslim coalition: the event should fire as an Iron Sultanate + Papal + Indian-sultanate relief. The Tughlaqs (Delhi's dynasty in 1337) are canonically still around in 1721, so keep the Delhi Sultanate alive and give it a reason to send troops west.
- Retaking Gibraltar is a Curia-backed holy war goal; while it stays lost, Mediterranean-Atlantic trade suffers a heavy toll. Canon still has Gibraltar Heretic in 1914, so the AI never pushes for it and a player win is a deliberate divergence.
- Heresy spreads to colonies via ships, giving New World conversion a dark twin.

**1780–1805, the build-up.** England becomes the leading naval power against the Admiralty. Event chain introduces Admiral Horatio Nelson as a unique admiral.

**1805, the Battle of the Bloodied Cliffs.** A scripted fleet engagement off the English coast against High Captain Ranga's Heretic fleet.

- Canon outcome: the Prince of Wales betrays England and switches sides mid-battle; Nelson's rearguard and the sacrifice of HMS *Bellerophon* save the remnant, which limps into Portsmouth; Nelson dies but sinks Ranga's flagship *Great Red Dragon*, so an immediate invasion of Britain is averted. Afterwards England loses its overseas territories and Heretic raids hit the English coast. Script: a Prince of Wales defection event (heir turns traitor, takes ships), then large losses of ships, naval tradition and overseas subjects, plus a long Coastal Raids situation. Canon later builds the Moving Fortress of Britannia (1907) as the answer, so a post-1805 English recovery project fits the trend.
- Players can prepare: enough ships, Orichalcum-armoured hulls and a high-skill admiral turn defeat into a costly draw that keeps Nelson alive. This is a deliberate divergence from canon, available only to a human England.

**1806–1837, the Last Trenches.** 1807: the Heretic Basilisk Fleet invades Éire and High King Muiredach is slain at Waterford (canon), so Ireland should be a united High Kingdom by then. Canon continues the war for decades (the fall of Gaillimh/Galway, Irish resistance under the Fianna, an Irish Hellgate) and ends it in a Heretic defeat when the Irish Hellgate collapses and the fleet retreats to Gibraltar, so the Éire war should still be open in 1837. Endgame crisis. Victory conditions by bloc: Christendom holds New Antioch and keeps the Heretics off the European mainland; the Sultanate holds the Iron Wall; heretics or the Grail control a set share of Europe's coasts.

## Map redraw

Keep the vanilla geography and location grid; change the map through ownership, wasteland, renamed locations and location modifiers rather than redrawing coastlines.

| Area | Change | Purpose |
| --- | --- | --- |
| Coastal Levant (Lebanon, Palestine, to the Sinai edge) | Heretic-held since 1101: Hell-front belt with permanent devastation and no development | The eternal front since 1099 |
| Jerusalem | Destroyed city around the Gate of Hell ("Jerusalem-that-was"); impassable or wasteland | The Gate |
| Ekron | Beelzebub's city; Grail holy site once the plague starts | Phase 1 onward |
| Acre | Templar stronghold until 1703 | Phase 5 event |
| Antioch | Faithful bastion from 1102; ruined 1545; New Antioch on the same site from 1559 | Phases 3–4 |
| Iron Wall (Taurus to Zagros, across the Syrian plain to the Gulf) | Fortified line of location modifiers on the Sultanate's western edge; Damascus inside it | Sultanate front |
| Sinai / Egyptian border | Mamluk-held Faithful front (Bir al-Abed) | Mamluk front |
| Alamut (Alborz, near the Caspian) | Nizari Assassin enclave outside the Wall, surrounded by Hell-held land; untakeable fortress | Sultanate ally |
| Avignon | Grail enclave from 1429 under the Antipope; slowly spreading corruption | Phase 2 onward |
| Kola Peninsula | Northern Hellmouth: periodic incursion spawns | Northern front |
| Hungary, N. Balkans, Friuli | Grail Marches: corruptible, convert to wasteland if lost *(invented)* | Phase 1–2 |
| Languedoc, Lombardy | Triclavian war scars: low prosperity, ruined buildings | Pre-start |
| Gibraltar strait | Strategic sea zone with a passage toll; flips to the Heretics in 1666 | Phase 4–5 |
| Argos | Destroyed by God in 1477 | Phase 3 |
| Hell-gates | Off-map or impassable portal locations (Jerusalem; others *(invented)*) | Grail and demon spawns |

New modifiers:

- **Hell-Front** location modifier: defender bonus, attrition, no economy (stands in for trench terrain).
- **Corrupted** location modifier with a 0–100 scale.
- **Consecrated Ground** on shrine locations: blocks corruption, boosts morale.

Renames: keep real place names for Europe (they ground the setting); rename only what the lore changes, e.g. Antioch to New Antioch after 1595, and Jerusalem to the Gate of Hell.

## Countries

Most European tags stay with themed renames; new tags carry the setting's factions.

**New and repurposed tags**

| Tag | Appears | Government | Role |
| --- | --- | --- | --- |
| Templar Heretics *(name invented; Heretic Legion faction)* | 1337, Levant with Acre as capital | Infernal order, Heretic faith | Holds the Levant and the Gate; at war with all Faithful. Canon splits Hell's earth into sixty-six warlord domains, so consider several smaller Heretic tags (one per warlord/Sin) that sometimes fight each other; canon says only Hell's infighting keeps New Antioch alive |
| Principality of Antioch / New Antioch | 1337, Antioch | Theocratic principality ruled by a Duke *(government invented, title canon)* | Christian bastion of the front; ruined 1545, rebuilt 1559–1595 |
| Iron Sultanate | 1337, behind the Iron Wall; capital Damascus ("New Damascus") | Sultanate with alchemist (House of Wisdom) and engineer estates; ruler styled Padishah of Rûm | Faithful co-belligerent behind the Iron Wall, never fully trusted ("the infidels who unleashed Gog and Magog") |
| Nizari Alamut | 1337, Alamut | Theocratic order under the Old Man of the Mountain | Assassin enclave; Sultanate protects it in exchange for services |
| Black Grail Host | 1346 (plague) | Demonic horde under Grail Hegemon Yersinia Rex, serving Beelzebub | Phase 1–2 antagonist; from 1429 an Avignon enclave under the Antipope; returns in flare-ups |
| Heretic Admiralty *(name invented)* | 1666 (Gibraltar) | Pirate state of the Serpent cult | Phase 5 antagonist |

**Renamed and reshaped tags**

| Vanilla | Mod name | Change |
| --- | --- | --- |
| Papal States | Holy See *(full name invented)* | Leads the Curia, calls Grail Crusades, sends the 1721 relief fleet |
| Holy Roman Empire | Holy Roman Empire | Emperor must defend the Grail Marches |
| France | Kingdom of France | Jeanne d'Arc arc, Sanctified Army |
| England | Kingdom of England | Naval arc: White Cliffs, Nelson, Bloodied Cliffs |
| Byzantium | Byzantium | Falls to the Heretics before 1573 (canon) |
| Mamluks (Egypt) | Mamluk Sultanate | Canon: Faithful, independent of the Iron Sultanate, holds the Sinai line, rich Mediterranean trade with heavy merchant debt; loses its Levant holdings to the Heretics and Damascus to the Sultanate at setup. Seed the Ten Golden Horns (Mammon cult) as a slow late-game situation; canon fall is c. 1859, after the end date |
| Ethiopia | Solomonic Empire of Abyssinia | Staunch Faithful; Sword Congress member, seven-yearly expeditions to New Antioch |
| Novgorod | Novgorod | Canon Tsardom of Novgorod survives to 1914 and fights the Northern Hellmouth with the Kalmar Union |
| Delhi | Delhi Sultanate (Tughlaq) | Canon Tughlaq warriors help lift the 1721 siege |

Rename rule of thumb: rename where the country's role changes, not just for flavour, so the map stays readable.

## Cultures and religions

Religion carries most of the setting; cultures change only where the war created new peoples.

**Religions**

| Religion | Group | Key mechanic |
| --- | --- | --- |
| Triclavian Orthodoxy *(name invented)* | Christian | Curia, Grail Crusades, saints and relics |
| Quadriclavian Remnant *(invented)* | Christian | Tolerated heresy; bonus to fortification and martyrdom events |
| Eastern Orthodoxy | Christian | Unchanged core, gains relic mechanics |
| Sultanate Islam | Islamic | Alchemy and engineering bonuses, uneasy alliance with Christendom |
| Heretic Legion faith | Infernal | State faith of the Templar Heretics; the Templars' Act of Ultimate Heresy |
| Cult of the Black Grail | Infernal | Beelzebub's faith; spreads by plague and Corruption, not missionaries |
| Court of the Seven-Headed Serpent | Infernal | The seven deadly sins; spreads through ports and secret lodges; Heretic Admiralty state faith. Canon: the Court is Hell's War Council in the Iron City of Dis, seven archdevils (one per Sin) voting by majority and constantly deposed; only Mammon (Greed) has held his seat for the whole war, and Beelzebub leaves Gluttony's seat empty. Model a rotating "ruling Head" that changes Heretic bonuses every few decades |
| Nizari Isma'ili | Islamic | Alamut's faith; Sultanate ulema consider it heretical, which explains Alamut being outside the Wall |

**New cultures** *(all invented)*

| Culture | Where | Origin |
| --- | --- | --- |
| Antiochene | Antioch, later New Antioch | Crusader descendants of the bastion, survivors of 1545 |
| Marcher | Grail Marches | Mixed resettlers of plague-cleared land |
| Corsair | Gibraltar, Atlantic ports | Heretic sailors after 1666 |

Risen and Corrupted are pop states, not cultures, so they stay on top of any culture and can be purged or redeemed.

## Mechanics

Reuse EU5's existing systems wherever possible; each item below names the vanilla system it extends.

| System | Vanilla base | Mod use |
| --- | --- | --- |
| Corruption | Location modifiers + pop conversion | 0–100 per location; drives rebels, conversion, wasteland flips |
| Black Grail Plague | Black Death situation | Undead pops, Grail tag spawn, contained vs entrenched end |
| Grail Crusades | Catholic Church + Crusade IOs | Coalition wars with shared rewards and relics |
| Walls of New Antioch | Great Projects | Yearly Faithful tithe plus extra contributions, restores the Principality |
| Year of Six Woes | Event chains + situation | Six linked shocks in 1666, ending with Gibraltar |
| Holy Orders | Clergy estate | Militant sub-estate with troops and fort privileges |
| Forge Guilds | Burghers estate | Orichalcum production privileges |
| Orichalcum Steel | Advances | Unit, fort and ship upgrades, resistance to missile and artillery damage |
| Saints and relics | Characters + religious mechanics | Living Saints as unique characters, relics as spendable resource |
| Heretic Admiralty raids | Naval/piracy mechanics | Scaling raids on Atlantic trade and colonies |

Societal value to add: **Zeal vs Pragmatism**, deciding how hard a country leans on faith over steel. High Zeal favours relics and crusades; high Pragmatism favours forges, trade and tolerance (including closer ties with the Sultanate).

## Build order

Ship in playable slices, each one a complete era, so testing stays manageable.

1. **Setup slice (1337 start).** Religions (including the Heretic Legion faith), renamed tags, Levant Hell-front held by the Templar Heretics, Principality of Antioch, Iron Sultanate in place of the Jalayirids. No new mechanics yet.
2. **Plague slice (to 1429).** Corruption system, Black Grail Plague situation, Grail tag, Brazen Bull, Joan of Arc chain.
3. **Steel slice (to 1545).** Orichalcum advance, Forge Guilds, Argos, Antioch destruction.
4. **Walls slice (to 1666).** Sword Congress, Great Project, Order of the Dragon, Serpent faith, Six Woes.
5. **Fleet slice (to 1837).** Heretic Admiralty, White Cliffs, Acre, raids, Nelson and Bloodied Cliffs, endgame conditions.

### Slice 1 status vs lore

Built so far, and what the lore check changed:

| Built | Lore status | Action |
| --- | --- | --- |
| Catholic renamed Triclavian Orthodoxy; Quadriclavian pockets in Languedoc, Bohemia, Rhineland | Names and doctrine invented; consistent with canon | Keep |
| Opening event | Said 1095 and the First Crusade finding the Gate; canon is 1099 and the Templars' Act of Ultimate Heresy | Fixed |
| Mamluks renamed Iron Sultanate | Wrong: the Sultanate is behind the Iron Wall | Moved to the Jalayirids. **Recheck (Oct 17):** the official site puts the court at New Damascus, so Damascus (Mamluk in vanilla 1337) should go to the Sultanate, with the Wall line running west of it; Baghdad stays inside as the House of Wisdom city. Also check that the Heretic Levant transfer did not hand Damascus to the Templars |
| Order of the Trench released in Palestine and Lebanon, holding Jerusalem | Wrong: the Levant is Heretic since 1101, and the Christian bastion is Antioch | Replaced: Templar Heretics (THR, Heretic Legion faith in the new Infernal group) get every Mamluk location in the Levant except Antioch's province, capital Acre, all pops converted, at war with Antioch and the Mamluks from day one |
| — | Antioch is the Faithful's bastion since 1102 | Added: Principality of Antioch (tag NAT; ANC is vanilla Ancona) released on the 4 Mamluk locations of Antioch's province (Afrin is Cilician in 1337), Catholic monarchy with a French Catholic noble pop over the Armenian Miaphysite population, Bastion of Antioch modifier |
| Warden of the Gate for Jerusalem's owner | Wrong once the Levant is Heretic | Removed; replaced by Bastion of Antioch |
| Hell-Front modifier on the whole Levant area | Canon | Kept on the Heretic Levant; Antioch's province excluded |
| — | Iron Wall fortified since 1109 | Added: Great Iron Wall location modifier (defence, garrison, hostile attrition) on every Iron Sultanate location that borders another country. In 1337 the Jalayirids are a thin strip, so Baghdad itself is frontier |
| — | Wars of Triclavianism scars (pre-start section) | Added: severe prosperity penalty across Languedoc and Lombardy at game start; ruined buildings and depopulation not done yet |
| Text overrides via `localization/replace/english/` | Unverified until now | Verified in game: Jalayirids show as Iron Sultanate, Catholicism as Triclavian Orthodoxy |
| Templars vs Antioch war | Pillar: peace with Hell is only a ceasefire | 10-year AI run: the AI made peace around 1340. Added a yearly check: when the truce lapses (5–10 years), the Templars declare war on Antioch and the Mamluks again. Verified: war resumed in 1346; Antioch held all 10 years |
| Templar state collapsed by c. 1350 (50-year run) | Levant must stay Hell's | Cause 1: French primary culture over Levantine pops, so separatist revolts (Hims, Latakia, Halab broke away). Stopgap: Templars accept Levantine and Syriac cultures, plus Dominion of the Gate (−separatism, +control); verified no revolts. Replace with the planned Legionnaire culture (mod-content.md) |
| Templars still lost land to Egypt (1342–1344) | Canon front is a trench stalemate | Added Legions of the Third Circle (military buff), then made the front itself near-untakeable: Hell-Front now +50% defence, 4 hostile attrition, +100% garrison; Walls of Antioch on Antioch's province. 50-year verification run in progress |
| Burned Cathedral (Albi), Martyrs' Field (Béziers) | Sites *(invented)*, echoing the Albigensian Crusade | Added and verified at game start |
| Templar and Antioch cores | — | Only on land the Mamluks actually hand over, so no claims on Bedouin or Cilician land |
| Templar state conquered despite buffs and forts (dead by 1340 once the Iron Sultanate joined the war) | Heretic land must never change hands | Land only changes hands at the peace table, so: Templars get `blocked_from_peace` (in Dominion of the Gate), so no treaty can ever be signed with them; and an `ai_scripted_expansion_score` rule with `never_attack` stops every non-Infernal AI from planning wars against Infernal countries ("no one wants this land but the Fallen"). Backstops for scripted conquest outside peace deals (e.g. Timur's occupation pulse): the Great War event returns Faithful-held Templar-core Hell-Front land each month, and France's yearly watch re-releases the Templars from their cores if they ever die. Long-run verification in progress |
| One Templar state for the whole Levant | Canon: Hell is not united (sixty-six warlord domains); fan maps checked Oct 17 show the Levant Heretic but no internal borders | Split into four domains, all Heretic Legion faith and Legionnaire culture, each set up by `npoe_setup_heretic_domain`: Templar Heretics (THR, Palestine with Acre and the Gate), Tyrants of the Cedars (HCD, Lebanon), Heretic Lords of Latakia (HLT, Syrian coast), Lords of Moab (HMB, Transjordan); the three non-Templar names are *(invented)*. All Heretic rules now apply to any Infernal country. The domains are bound in the Court of the Seven-Headed Serpent, a leaderless international organization ("the Court sits in Dis"): members can never declare war on each other, but with no mutual-defence law they do not help each other either; an AI rule also stops Infernal countries planning wars on each other. Each domain makes war on its Faithful neighbours; Latakia declares on Antioch explicitly on day one because neighbour data is not ready yet. Verified at game start (34 PASS) |
| Heretic rulers | Canon names one Heretic lord in the window: Cobar, First Tyrant of the Sixty-six (1106) | Each domain gets a named undying ruler with the Undying trait plus the Undying character modifier (`is_immortal = yes`, +500 life expectancy), verified immortal in game, both re-granted yearly to any new Heretic ruler: Cobar, First Tyrant of the Sixty-six (Cedars, canon name); Bertrand the Unburied (Templars), Hugues of the Locusts (Latakia), Balak of Moab (Moab) *(invented)*. Yersinia Rex is Undying too, until Jeanne d'Arc destroys him in 1429 |
| Black Grail (slice 2, first piece) | Canon: 1346–1353 Beelzebub unleashes the Black Grail; the Corpse Wars begin; Grail Hegemon Yersinia Rex | Vanilla Black Death kept as the plague engine, renamed The Black Grail. From 1347 the Black Grail Host (BGH) rises from up to two plague-struck locations per Grail Marches area (Transdanubia, North and South Alföld, Slavonia, Croatia, Bosnia, Serbia; at most 14), by 1350 regardless, under Yersinia Rex, pops converted to the Black Grail, war on every neighbour through location adjacency (a country created mid-tick has no neighbour data). Not a Court member. Until the Battle of Valence it is protected like the Heretic domains (no peace, no Faithful armies on its land, no AI war plans against it, via `npoe_is_untouchable_hell`) and carries Host of Beelzebub (+15% discipline, +30% morale, +150% manpower, +50% defence); all its land has Dead Lands (+100% defence, +300% garrison, 6 hostile attrition, +200% hostile movement cost), refreshed yearly for 13 months so it lapses when land leaves the Grail (verified in a forced test, 1338–1340), since canon has the Faithful fail to drive it out before Jeanne d'Arc; it can only grow through Corruption. After 1429 the protection lapses. Verified: rose in 1348 and held land through 1352 |
| Iskenderun (al-Iskandarun) | Mamluk in vanilla 1337; would be a cut-off exclave once the Levant is Heretic; port on the Gulf of Alexandretta next to Antioch (canon New Antioch is relieved by sea; fan maps place New Antioch near Iskenderun) | Handed to the Principality of Antioch at game start as its port (5 locations now). Cilicia, which holds the rest of the Adana province, was the alternative; the canon bastion took priority |
| Released countries made subjects | Hell answers to no earthly overlord | `create_country_from_cores_in_our_locations` can leave the new country a subject of its releaser (the Black Grail ended up under Croatia). Every scripted release (four Heretic domains, Antioch, Alamut, the Grail at rising and at Valence, Templar revival) now runs `npoe_make_independent` (`overlord = { cancel_subject = ... }`). Verified: all independent at game start and after a forced Grail rising |
| Prophet Solon | Canon: the first Procession of the Sacred Affliction formed at the onset of the Corpse Wars under the Prophet Solon (lepers sealed seven days in a tomb, emerged healed) | Event when the Grail rises, for a random Christian realm bordering it (place *(invented)*): Procession of the Sacred Affliction for 25 years (+10% morale, +10% manpower, religious influence) |
| Corruption (pillar) | Canon: the Grail spreads by plague and corruption, not missionaries; from 1429 its missionary bands creep outward from Avignon a little every year | Location variable `npoe_corruption` 0–100, tracked in a global list. Yearly: +5 on every location bordering Grail land, once per location however many Grail locations it touches (so it also creeps out of Avignon after 1429, and does not snowball: a first test at +10 per adjacent Grail location turned land over within four years), −5 where no longer next to the Grail. 25+: Corrupted (unrest, prosperity loss); 50+: Deeply Corrupted (worse); 100: the location falls to the Grail. Pop conversion runs through EU5's movement system: the Cult of the Black Grail movement (spawned at the Host's capital when it rises) spreads the Black Grail faith to Christian and Muslim pops, ×2 at Corruption 25+, ×3 at 50+, ×1.5 where plague is present, ×1.2 next to Grail-majority land. Countermeasure: Purification by Fire (country action, 25 gold, on an owned location with Corruption 25+): −60 Corruption, a fifth of the people burned, severe prosperity loss, stability hit, and 10 years of +200% resistance to the Grail cult; AI uses it at 50+. Canon: no inoculation, fire is the only answer, so no cure exists. Not yet: quarantine, relic processions, Consecrated Ground, Risen pops, Grail rebels |
| Corpse Wars outcome (1353) | Doc: contained under 15 Grail locations, else entrenched | Yearly check from 1353 sets contained or entrenched; while entrenched every realm bordering the Grail gets the Grail March footing (defence, peasant levies, manpower), refreshed yearly. Verified: a 20-year run ended the Corpse Wars with the Grail contained |
| Brazen Bull (1418) | Canon: Sultan Bayezid III commissions the Brazen Bull as living field artillery (821 AH) | Event for the Iron Sultanate in 1418 unlocks the Brazen Bull, a unique artillery unit with melee punch (+30% damage done, −20% taken). The event names "the Sultan", not Bayezid III, since the in-game ruler is the game's own |
| Jeanne d'Arc and Valence (1412–1429) | Canon: Living Saint; at the Battle of Valence (1429) she leads the combined forces of the Church, destroys Grail Hegemon Yersinia Rex and drives the Grail from mainland Europe; the same year the Grail's priests take Avignon through a traitor cardinal, and the Church contains it | France events from its yearly pulse: 1412 Jeanne born at Vaucouleurs (no Domrémy location; Vaucouleurs is the neighbouring town), under Heaven's Protection (immortal) until 1431; 1428 the Maid of Orléans: Living Saint trait, Sanctified Army for 10 years; 1429 Battle of Valence: Yersinia Rex killed, every Grail mainland location returned to a Christian realm with a claim on it (else a Christian neighbour), Avignon becomes the Grail enclave under an undying Antipope (name *(invented)*), blocked from peace with the Antipope's Walls. Grail truce: if France and England are at peace in 1429 they get a mutual truce; no script effect can end a running war, so an ongoing Hundred Years War continues. Verified with a forced Valence at game start: Yersinia dead, mainland freed, Avignon the Grail enclave under the Antipope. Not yet: Joan as an actual army commander |
| Slice 3 turning points | Canon: 1477 Argos taken by God; 1503 War Prophet Angelos, guided by Saint Eligius, discovers Orichalcum Steel (resists missile weapons); 1545 a demonic weapon destroys Antioch and the garrison holds the crater | From France's yearly pulse at the canon dates. 1477: Argos loses 95% of its people and gets Taken by God (no production, no growth); every Christian realm loses stability. 1503: France gets Orichalcum Steel (+10% defence, +10% heavy infantry power; discoverer France *(invented)*, after Saint Eligius, the French patron of smiths), then 10% a year it spreads to any Christian or Muslim realm bordering a holder (canon: Franks sold orichalcum to Mamluk Egypt). 1545: Antioch loses 90% of its people and becomes the Crater of Antioch, still held by the Principality; every Christian realm loses stability and gets Antioch Must Rise for 50 years; the Iron Sultanate chooses to aid the survivors or let Christendom carry its own burden. Verified with a forced 3-year test |
| Legions of Kimaris (c. 1550–1573) | Canon: c. 1545–1573 Constantinople falls to the legions of Kimaris, Marquis of Hell; 1573 the Sacred Order of the Dragon halts the Infernal advance in Wallachia | 1550 *(year invented within the canon window)*: a Hellgate on the Asian shore releases the Legions of Kimaris (tag KMR) at Üsküdar, a Court domain (patron Apollyon *(invented)*) ruled by the undying Kimaris, Marquis of Hell. Every Thracian location of whoever holds Constantinople is marked for a 25-year scripted offensive. 1573: the Order of the Dragon event for Wallachia's ruler lifts the markers and grants the Sacred Order of the Dragon (+15% morale, +5% discipline, +15% defence) for 50 years. Forced test in progress |
| No Ilkhanate | Canon: the Great Sultanate united the Islamic factions in 1109; the fan 1914 map shows it over Persia and Iraq | At game start every member of the vanilla Ilkhanate organization (the Jalayirid, Sutayid, Borjigid, Kartid and Huleguid successor states) folds into the Iron Sultanate (Muslim-held land only) and the Ilkhanate is destroyed. Alamut is released afterwards and stays independent (canon: outside the Wall). The vanilla Jalayirid event flavor_chb.1 (1338–1343), which splits the Chobanids off at Tabriz, is blocked by removing its required character Hasan Kuchak at game start (a test run saw the Chobanid horde rise). Verified at game start (46 PASS) |
| Grail Crusades | Canon: the Curia calls Grail Crusades; vanilla crusades target any non-Christian kingdom, so the Pope crusaded against the Faithful Iron Sultanate in a test | `is_valid_target_for_crusade` overridden (copy of vanilla `scripted_triggers/religion_triggers.txt`, one change): the target must follow the Black Grail. The Court's Heretic land cannot be entered, so it is no target. The Grail can now be fought before 1429 (the no-step rule and the monthly sweep cover only the Court's domains) but still not taken: it stays blocked from peace until Valence and the AI never plans wars of conquest against it |
| Sword Congress and New Antioch (1559, 1595) | Canon: the Sword Congress of Vienna orders Antioch rebuilt with a yearly tithe from every Faithful nation; walls of New Antioch completed 1595 (seventy-seven towers with anchorite shrines, never breached) | 1559 event for Vienna's ruler doubles the Tithe for Antioch. 1595 event for the Principality: crater and old walls removed, Walls of New Antioch (+300% defence, +600% garrison, 12 hostile attrition, +400% hostile movement cost) on Antioch's province, Antiochene Catholic refugees resettle the city, and the scripted country name Principality of New Antioch applies. Verified with a forced test |
| Constantinople fallback (1572) | Canon: Constantinople has fallen before 1573 | If the Legions of Kimaris have not taken it by 1572, the city and every marked Thracian location fall to them and become Hell-Front. Verified with a forced test; in a 5-year AI test the one-location Legions took nothing on their own |
| Year of Six Woes (1666) | Canon: the Heretic Fleet takes Gibraltar, which becomes the Sea Fortress; the other five woes are *(invented)* | Dispatched from the late-1665 pulse, two months apart: fire (London: Great Fire, a tenth of the people), plague (Marseille +60 Corruption), schism (a Christian kingdom: Serpent Lodges Revealed, severe stability loss), famine (Andalusia: −50% food for 5 years), betrayal (a Christian king murdered), Gibraltar (canon: the Heretic Admiralty, tag HAR, name *(invented)*, Court of the Serpent state faith per the doc, Sea Fortress, Hell-Front, sworn to the Court). Verified with a forced test: all six landed, the Admiralty at war with Morocco |
| White Cliffs (1670) | Canon: England begins the Fortress of the White Cliffs of Dover | Event to Dover's owner: Dover gets Fortress of the White Cliffs (+150% defence, +300% garrison, attrition 4); the owner's other coastal locations in Great Britain get Under the Cliffs' Guns (+50% defence, +100% garrison) and are spared Admiralty raids. A Great Project building is not used (EU5 modding of those not explored yet) |
| Heretic Admiralty raids | Doc: raids on Atlantic trade, colonial coasts and convoys | Yearly while the Admiralty exists: one raid on a non-European coast and one anywhere outside the Cliffs. Heretic Raid on the location for 5 years (prosperity, unrest, 5% of its people carried off); its owner gets Corsair Threat (−10% sea trade, −5% naval morale) for 5 years. Not yet: scaling with Admiralty fleet strength. Verified |
| Fall of Templar Acre (1703) | Canon: a small force of Hebrew Knights destroys the Templar stronghold at Acre | Acre loses Templar Stronghold, gets Ruins of Acre, 60% of its people die; the Templars get Stronghold Fallen (−15% morale, −5% discipline, −25% manpower, 25 years) and move their capital inland. Canon says the Templars hold Acre only until 1703, so Acre passes to the neighbouring domain, the Tyrants of the Cedars (Hell's land never passes to the Faithful). The Hebrew Knights are event text, not a tag. Verified in a forced test |
| Third Siege of New Antioch (1721) | Canon: lifted by Sultan Ibrahim's army, Tughlaq warriors and a Papal fleet | Every Antioch location held by the enemy is retaken and infernal armies in it destroyed; Antioch gets Relief of New Antioch (10 years); the Iron Sultanate, the Papal States and Delhi (if they exist) get Reliever of New Antioch, prestige and mutual +75 opinion with Antioch. Not yet: keeping the Delhi Sultanate alive to 1721 |
| Bloodied Cliffs (1805) | Canon: Ranga's Heretic fleet defeats England; the Prince of Wales defects; Nelson dies and sinks the Great Red Dragon | Event to London's owner: half its navy destroyed, the heir (the Prince of Wales) defects to the Heretic Admiralty (killed if the Admiralty does not exist; verified in a forced test), The Bloodied Cliffs (30 years: naval morale, ship building, sea trade, war exhaustion), navy tradition and prestige losses, non-European subjects released, Coastal Raids on its British coasts for 30 years; a quarter of the Admiralty's navy sunk with the Great Red Dragon. Not yet: Nelson as a unique admiral, the human-England draw path |
| Basilisk Fleet in Éire (1807) | Canon: the Basilisk Fleet invades Éire; High King Muiredach is slain at Waterford; the war goes on for decades | Waterford's ruler is killed and the location goes to the Heretic Admiralty with Basilisk Beachhead and Hell-Front (untouchable, like all Hell's land); the Admiralty declares war on Waterford's former owner, and blocked_from_peace keeps the war open to 1837. Not yet: a united Irish High Kingdom by 1807, Galway, the Fianna, the Irish Hellgate |
| Phase 5 verification | — | Forced test (all five events at game start, Admiralty raised): White Cliffs, Acre (still Templar, capital moved), Third Siege relief, Bloodied Cliffs, Waterford to the Admiralty with the Éire war declared, and raids all PASS |
| Damascus Megalopolis | The Sultan's court, the great city behind the Iron Wall | Damascus is set to the Megalopolis rank at game start (self-check PASS); New Damascus gets the rank too if the court moves |
| Joan as commander (1428) | Canon: the Maid leads the Faithful to Valence | The Maid event gives Joan +50 military skill and puts her at the head of one of France's armies (an army without a commander if there is one). Verified: she is a general |
| Horatio Nelson (1780) | Canon: Nelson dies at the Bloodied Cliffs in 1805, sinking the Great Red Dragon | 1780 event to London's owner creates Nelson (military 90) and gives him a fleet; the Bloodied Cliffs kill him. Verified both. Not yet: the human-England path where he survives |
| Trebizond and the Pontus | Canon: the Theme of Chaldia, a Christian state on the Black Sea | At game start Trebizond takes every location with Pontic Greek pops (Sinop and Samsun to Rize) plus its own cores, from the Sultanate and anyone else. Trebizond gets Theme of Chaldia (separatism −40%, heathen tolerance +1, monthly control), since Canik separatists rose in two runs. Crimea is excluded: Theodoro, Kaffa and the other Crimean Greek towns stay with their 1337 owners. Taman (Matrega area, Trebizond's in vanilla) stays Trebizond's. Verified (self-check) |
| Defenders of Antioch | Canon: from 1559 the Sword Congress of Vienna funds New Antioch with a yearly tithe from every Faithful nation, and the Duke of New Antioch is nominal supreme commander of all Faithful forces | International organization led by Antioch (name *(invented)*: canon's body is the 1559 Sword Congress), with every Christian realm a member. The Tithe for Antioch payment sends about 1% of each member's monthly income plus manpower to Antioch every month. No mutual defence, so Christendom is not dragged into every Heretic war. Disbands if Antioch is destroyed, ready to be refounded as the Sword Congress in 1559. Verified at game start |
| Walls of Antioch | Canon: never breached by siege | Deliberately overpowered: +200% defence, +500% garrison, +100% garrison growth, 10 hostile attrition, +300% hostile movement cost; Antioch falls only to the scripted 1545 weapon |
| Cilicia and Kilis | Canon-silent on Cilicia; historically the Crusaders' staunchest Christian ally beside Antioch, destroyed by the Mamluks in 1375, which cannot happen here (Egypt is cut off by the Heretic Levant); Kilis is a stranded Mamluk vassal holding Afrin inside Antioch's province | Both fold into the Principality of Antioch at game start (now 20+ locations, the Taurus passes included). Kilis is excluded from the inner-Syria handover to the Sultanate. The folded realms lose their cores and Antioch accepts Armenian culture, after a 24-year run showed Cilicia revolting back into existence (1350s, 5 locations lost). Verified |
| City names | Canon names Jerusalem-that-was | Every language variant of the Jerusalem name is overridden, since the game shows the owner's language (Jerusalem displayed as Al-Quds under the Levantine-speaking Templars). Verified |
| Heretic lords' cultures | The lords of Hell are not the converted Levantine populace | Each ruler is created with his own culture: Bertrand and Hugues French (Templar-born), Kimaris and Yersinia Rex Infernal (a ruler-only culture for demon lords *(invented)*), the Antipope French (canon traitor cardinal of Avignon), Cobar, Balak and the High Admiral Levantine *(invented)*. Domains keep Legionnaire as primary culture (it ended the separatist revolts). Verified |
| Heretic sub-religions | Canon: Heretic priests pledge to a favoured archdevil of the Court; seats are the seven Sins; named heads are Eligos (Pride, the highest seat), Apollyon (Wrath), Belphagor (Sloth), Mammon (Greed, held almost without break); Beelzebub (Gluttony) scorns the Court for the Black Grail; Lust and Envy heads unnamed | Six religious schools of the Heretic Legion faith (EU5's sub-religion mechanic, as Nizari is a school of Shia): Eligos, Apollyon, Belphagor, Mammon, and Seat of Lust / Seat of Envy with no invented devil names; no Gluttony school (the Black Grail is its own faith). Patron per domain *(invented)*: Templars Eligos, Cedars Mammon, Latakia Apollyon, Moab Belphagor. Heretic sub-cultures not added: canon has none (the Wretched, Anointed and Trench Ghosts are troop types, not peoples) |
| Expansion | Hell expands only where the timeline says | Timur-style conquest removed. Hell armies made strong instead (Legions of the Third Circle: discipline +15%, morale +30%, manpower +100%, siege +25%, faster recovery). Scripted conquest framework: `npoe_open_hell_offensive` marks a target country's land in an area for N years and has a domain declare war; a Heretic occupation of marked land hands it over (`npoe_hell_takes_marked_land`). Peace stays impossible, so nothing else changes hands. Timeline offensives (e.g. Constantinople c. 1545–1573 by Kimaris's legions) to be wired in their slices |
| Heretic land rules | Hell takes land, never gives it | Templars have `auto_conquer_at_war` (Timur's mechanic): what they occupy, they own, and it becomes Hell's (`npoe_claim_for_hell`: claim, Hell-Front, free pops converted). Guards in `npoe_hell_takes_land` send captures straight back: Iron Wall and Alamut always, Walls of Antioch until 1545, Mamluk land until 1859. No one else may stand on Heretic land: `on_location_occupied`/`on_siege_won` undo any non-Infernal occupation and destroy the army, and the monthly Great War event destroys any non-Infernal unit still on Heretic land; Hell-Front also gives +500% hostile movement cost. Every Templar border location gets the Bulwark of the Pit (+50% defence, +100% garrison), refreshed yearly |
| Iron Sultanate split apart in a "Rivaling Warlord" civil war | The Sultanate is a stable realm since 1109 | Cause: vanilla Jalayirids are a steppe horde, which has horde civil wars. Fix: changed to a monarchy (cognatic primogeniture) with Unity of the Wall (−20% separatism, +control). Long-run verification in progress |
| 1337 map redraw (Map redraw table) | Doc map | Done and verified at game start: the Iron Sultanate is one block from Damascus across the Syrian plain (Hauran, Tadmur, Deir) through Iraq to Basra on the Gulf and up Upper Mesopotamia to the Taurus, absorbing the Bedouin, Artuqid and Kurdish minors there (Christian Cilicia keeps its two locations); Jerusalem renamed Jerusalem-that-was, Gate of Hell modifier, 90% of its people gone; Acre gets Templar Stronghold; Mamluk locations bordering the Templars get the Sinai Line; Nizari Alamut (tag NIZ, Shia with the vanilla Nizari school, blocked from peace) released on Rudbar, the Alamut valley, with the Alamut fortress modifier. Ekron, Avignon, the Grail Marches, Kola, Gibraltar and Argos wait for their dates. Languedoc and Lombardy have the prosperity scars but not ruined buildings |
| Slice 1 content from mod-content.md | Per catalogue | Added and verified at game start: Legionnaire culture (all free Templar pops; slaves keep their culture and faith, and the game refuses culture changes for slaves) and Antiochene culture (Antioch's primary culture and noble pop), replacing the accepted-culture stopgap; Veteran of the Schism, Branded of the Legion and Wall-Born ruler traits (script-granted, re-granted yearly to new Templar and Sultanate rulers); Azebs, Janissaries, Wall Artillery, Heretic Legionnaires units (load cleanly; recruiting not tested); Court of the Serpent, Black Grail (from 1346), Cult of Mammon, Path of the Beast in the Infernal group. Script keys keep the `npoe_` prefix, not the catalogue's `gt_` |
| Yearly war re-declaration | Pillar: peace is only a ceasefire | Replaced by the Great War situation (`npoe_great_war`), modelled on vanilla hundred_years_war: started at game start, map mode Fallen vs Faithful of the front, ends only if the Templar Heretics are destroyed. Monthly it fires a hidden Templar event (as hundred_years_war does; declaring inside the situation tick silently fails) with a 10% chance to declare on Antioch, the Mamluks or the Iron Sultanate once a truce has lapsed. Verified: the event declared war on the Iron Sultanate in a 1-year run |
| Iron Sultanate capital | Official site: the Sultan's court is at New Damascus (Baghdad's House of Wisdom inside the Wall); the "New" implies the old city was lost, site unknown; fan maps draw it at the real Damascus; fan wikis also list Baghdad | Capital at Damascus, which keeps its own name in 1337: "New" implies the old city was lost. When Hell takes Damascus, the court moves to Mosul *(invented site)*, or else another non-Levant Sultanate city, which is renamed New Damascus (`rename_location`) and becomes the capital. Baghdad stays the House of Wisdom city. Verified in a forced test (Damascus handed to the Templars: the court moved to Mosul and stayed there 1338–1340) |
| Templars hold Damascus, Homs, Hama, Aleppo | Wrong after the Oct 17 lore check: Damascus is the Iron Sultanate's capital; the Heretic belt is the coastal Levant | Changed: the Mamluk parts of the Damascus, Homs, Aleppo and Ayntab provinces (16 locations) go to the Iron Sultanate, capital Damascus. Templars keep Palestine, Lebanon, Latakia and Transjordan (26 locations). The Syrian block is not yet connected to the Jalayirid lands in Iraq: Bedouin states (FDL, AAL, AMR) hold the plain between |

Remaining for slice 1 from the lore check: move Damascus to the Iron Sultanate; move the Curia seat from Avignon to Rome; give the Mamluks the Sinai front modifier; release a Nizari Alamut tag.

**Canon audit of the built mod (Oct 17, 2026)**

Fixed in this audit:
- The Pope now sits in Rome at game start (vanilla 1337 has the Papal capital at Avignon; canon has the Supreme Pontiff in Rome and Avignon as a bishopric).
- The Black Grail is kept out of the Court of the Serpent and out of the "Hell does not fight Hell" AI rule: canon has Beelzebub scorn the Court and wage a private war on all life.

Consistent with canon (no change): Jerusalem-that-was and the Gate; Templar stronghold at Acre; Heretic coastal Levant; Antioch as the Faithful bastion; New Damascus as the Sultanate's court; Mamluk Egypt Faithful and independent with the Sinai line; Nizari Alamut; Cyprus and Trebizond Christian; the Court's named heads and their Sins; Black Grail enabled from 1346; Azebs, Janissaries, Wall Artillery, Heretic Legionnaires.

Open canon tensions, kept on purpose or awaiting a decision:
- Canon says only Hell's infighting keeps New Antioch alive, but the domains are at peace with each other by design. Model the infighting politically instead (the planned rotating ruling Head of the Court) rather than as wars.
- Rûm, resolved (Anatolia part revised: Byzantium takes back its cores and Greek coasts, see below): the Sultanate is the Turkish continuation of the Sultanate of Rûm (fan lore; canon: the Padishah, Sultan Bayezid III, Janissaries, Azebs). Its ruling culture is changed from the vanilla Mongol Jalayirid culture to Turkish, and it absorbs every Muslim-held location in the Anatolia region (the Turkish beyliks, the Ottomans included: canon unites the Islamic factions in 1109 and its 1418 Sultan bears the Ottoman name Bayezid). Christian Byzantium, Trebizond (canon Theme of Chaldia), Cilicia, Cyprus and Genoa keep their Anatolian land; Iskenderun still goes to Antioch. The Great Iron Wall stays on the heartland borders outside Anatolia (canon: anchored on the Taurus, across the Syrian plain to the Gulf), so Anatolia is the Sultanate's unwalled march, which fits it falling to Hell by 1914 on the fan maps. AI rules stop the Iron Sultanate and Christian realms planning wars on each other (canon co-belligerents; Byzantium falls to Kimaris, not to the Sultanate). Verified at game start (43 PASS).
- The Antioch ruler is titled Duke (canon) while the state stays a Principality: a mod copy of vanilla `customizable_localization/country_ranks.txt` adds an entry for NAT (ruler title "Duke", rank "Principality"). Verified in the names log.
- The `court_of_the_serpent` religion overlaps with the Court organization and the archdevil schools; consider folding it into Heretic Legion schools and giving the Heretic Admiralty a school instead.
- Invented, flagged: Triclavian/Quadriclavian names and doctrine, the three non-Templar domain names and their patrons, Legionnaire and Antiochene cultures, Veteran of the Schism and Wall-Born traits, Burned Cathedral and Martyrs' Field sites.

Remaining for slice 1: starting opinions and rivalries between former Triclavian enemies; a Great War situation panel with real content (currently the default layout only); the 1307 bookmark (optional). Byzantium, Papal States and HRE keep their names, so no renames are needed.

Implementation notes:

- Check the current EU5 modding wiki for exact folder names and script syntax before starting; the game is recent and patches still move things.
- Encoding (verified in error.log): script files under `common/` and `events/` and localization must be UTF-8 with BOM; `main_menu/setup/1337/*.txt` must be UTF-8 without BOM, or the whole file is rejected.
- Testing: `eu5.exe -skip -observe` loads straight into a 1337 game as a spectator; add `-handsoff -timed_handsoff=<months>` to let the AI run and exit. `npoe_front_report` logs one `NPOE YEAR` line per year (Antioch held or lost, war or peace). `npoe_self_check` writes `NPOE PASS/FAIL` lines to `logs/debug.log`; game errors go to `logs/error.log`.
- War declarations (`declare_war_with_cb`) made inside the game tick (situation `on_monthly`, yearly/monthly pulse on_actions) are silently dropped; they work at `on_game_start` and inside events. Fire a hidden event and declare there, as vanilla hundred_years_war does (`npoe_events.10`, `npoe_events.11`). Scripted offensives opened from the Great War situation must go through an event too.
- A country created by script has no neighbour data until the next tick: find its neighbours through `every_owned_location` → `every_neighbor_location` → `owner`. Inside scripted effects `root` is the caller's root, not the current country: `save_scope_as` first.
- Character immortality is the `is_immortal = yes` character modifier (put it in a trait's `modifier` block); `immortal = yes` as a trait field does not parse.
- Countries released by script inherit the releaser's government, culture and laws; set them explicitly after release. Location-in-province trigger is `province_definition = province_definition:<name>`.
- Prefer replacing vanilla situations and events over adding parallel ones, so AI behaviour stays coherent.
- Every scripted date should have an AI-safe fallback trigger so the timeline survives player divergence.
- Canon sources: the timeline in the official Digital Rulebook (Sept 2026, on trenchcrusade.com/rules) and the lore annals at trenchcrusade.com/lore. Fan wikis and Trench Companion are secondary. The rules team is preparing a 1.1 rulebook, so re-check the timeline when it ships.
- Trench Crusade is an existing setting by its creators; keep this as a non-commercial fan mod and credit them.

## Lore check (Oct 17, 2026)

Checked against trenchcrusade.com: the Digital Rulebook timeline and all 80 lore annals.

**Confirmed as written:** 1072, 1099, 1101, 1102, 1109, 1165, 1215–1306, 1346–1353, 1418, 1429, 1477, 1503, 1545, 1559, 1573, 1595, 1666, 1670, 1703, 1805 (Ranga, Nelson), 1807.

**Corrected:**

- Egypt: canon is not silent. The Mamluks rule a Faithful Egypt from the early 1100s to c. 1859 (Mamluk Faris annal).
- Iron Sultanate capital: New Damascus per the site, not Baghdad (Mamluk Faris, Lions of Jabir, Iron Sultanate annals).
- Grail retreat in 1429: Avignon, not Sicily or Crete. Crete is Faithful (Missionaries of the Black Grail, Temples of the Fly, Domus Demetrius).
- 1721 relief: Sultan Ibrahim's army and Tughlaq warriors as well as the Papal fleet (rulebook).
- Templars: canon does not call them founders of the Heretic Legions; it says only that they committed the Ultimate Heresy and held Acre. Wording removed.

**Added detail:** Battle of Valence; the Antipope of Avignon; Saint Eligius; Kimaris and the fall of Constantinople; the tithe paid in goods; Abyssinia at the Sword Congress; the Duke of New Antioch; Prince of Wales' betrayal and *Great Red Dragon*; Basilisk Fleet and High King Muiredach; Ten Golden Horns; Alamut's position; Northern Hellmouth; the Court of the Seven-Headed Serpent as Hell's council; Oath of Penance; Prophet Solon; Domus Demetrius (1809); only two Hegemons ever.

**Not found on the official site (keep as fan-sourced):** the 1914 holdings in Anatolia, the Caucasus, the Balkans, Córdoba and Finland as a list. Finland does face the Northern Hellmouth on the site, but not a named foothold.

- Black Grail faith, kin to the Heretics: canon makes Beelzebub, Lord of Flies, one of the Seven Princes of Hell. The Black Grail faith therefore stays in the infernal group with the Heretic Legion, and the two faiths (and the Court of the Serpent) hold each other as kindred. Hell and the Grail don't plan wars on each other, and the Grail's war-on-neighbours event skips infernal realms. The Grail is still its own Host: it isn't in the Court of the Serpent IO, and it isn't untouchable after Valence.
- Full country names: vanilla `country_name_construction.txt` wraps Muslim (and most other) realms as "<dynasty> <rank> of <name>", which gave "<dynasty> Sultanate of Iron Sultanate". A mod copy of the file lists the mod's tags (JAL, NAT, THR, NIZ, HCD, HLT, HMB, BGH, KMR, HAR) under the Papal States' name-only rule, since their names are already full names. Verified: the Sultanate's long name is "Iron Sultanate".
- Absorbed realms and revolts: a 24-year run (v8) showed old cores reviving absorbed realms. The Injuids rose against the Iron Sultanate, Slavonia against the Black Grail and, earlier, Cilicia against Antioch. Fixed in the shared effects: land joining the Sultanate, land folded into Antioch or taken by Trebizond, and land rising for or rotting to the Grail all drop the previous owner's core. The same run had Miaphysite Zealots start a civil war against Catholic Antioch, so the Bastion of Antioch now carries tolerance_heretic +3, religious_unity_importance −50% and separatism −50% (all the Faithful stand together on the walls; v9 saw Antakya separatists rise in 1350).
- Rebels, root cause: EU5 treats land handed over by script as conquered and not yet integrated, and separatism comes from exactly that. All game-start transfers to the Sultanate, Antioch, Trebizond and the Heretic domains are now set to full (core) integration, and so is Grail land, every year. The realms where revolts kept coming back (Bastion of Antioch, Theme of Chaldia, Host of Beelzebub) also carry −0.01 monthly rebel growth and +0.1 pop-join-rebels threshold; Antioch also has −0.02 religious rebel growth. The Sultanate's Unity of the Wall has half that (v12, with all the other fixes, saw only one rising, at Qazvin).
- Iron Sultanate as an empire: set to the empire rank at game start (canon: the Padishah of Rûm rules from the Taurus to the Gulf). The empire rank's +1 government size, +2 culture capacity and +3 diplomatic capacity let it hold all its land; the name override keeps it shown as "Iron Sultanate". Its Unity of the Wall modifier also carries −0.005 monthly rebel growth and +0.05 pop-join-rebels threshold. Verified at game start (54 PASS). Note: the empire rank multiplies AI conquest desire ×4; the AI never-attack rules still stop it planning wars on Christians and on Hell.
- Byzantium takes back its Anatolian Themes (user decision): at game start every Anatolian location that is a Byzantine core (vanilla lists the Themes lost 1270–1331: Bithynia, Biga, Karasi, Saruhan, Smyrna, Aydin, Mugla) or a coast with a Greek majority goes to Byzantium (except the Turkish south coast: the Antalya, Alaiye and Icel provinces stay with the Sultanate), with cores, the old owner's core removed, and full integration. Trebizond then takes the Pontus, Iskenderun goes to Antioch, and Cilicia folds into Antioch as before. Byzantium gets The Restored Themes (separatism −30%, heathen tolerance +1, slower rebels). It holds them until Hell comes for it: Kimaris rises at Üsküdar in 1550 and Constantinople falls in 1572. The rest of Muslim Anatolia (Konya, Ankara, the interior) stays the Sultanate's northern march.

**Lore check (Oct 18)**, this session's changes against canon (official site, Digital Rulebook, then this doc):

| Change | Canon | Verdict |
|---|---|---|
| Black Grail faith kindred to the Heretic Legion | Beelzebub is one of the Seven of the Court but leaves Gluttony's seat empty | Fits: kin faith in the infernal group, still its own Host outside the Court IO |
| Dead Lands on Grail land | Silent | *(invented)* gameplay, so the Faithful cannot occupy the whole Grail before Valence (canon fixes 1429 as the turning point) |
| Damascus Megalopolis; New Damascus founded when Hell takes Damascus | The court is at New Damascus; "New" implies the old city was lost | Fits the user's reading (Damascus in 1337, New Damascus later); Megalopolis rank *(invented)* |
| Iron Sultanate as an empire | Ruler styled Padishah of Rûm | Fits: an imperial title |
| Byzantium takes back its Anatolian cores and Greek coasts | Silent on 1337 Anatolia (listed canon gap); Byzantium destroyed by Kimaris c. 1545–1573; fan maps: Hell holds Anatolia by 1914 | *(invented)*, user decision. **Fixed:** the 1550 Kimaris offensive now marks all Byzantine land (or the City holder's Thracian and Anatolian land) and 1572 seizes it all, so Byzantium is destroyed as canon requires |
| Antalya, Alaiye, Icel to the Sultanate | Silent | *(invented)*, user decision |
| Trebizond holds the Pontus, not Crimea | Theme of Chaldia | Fits |
| White Cliffs 1670, Third Siege 1721, Bloodied Cliffs 1805, Éire 1807, Nelson, Joan as general | Dated canon events | Fit. **Fixed:** the Prince of Wales now defects (joins the Heretic Admiralty) instead of dying |
| Fall of Templar Acre 1703 | Templars hold Acre "until 1703" | **Fixed:** Acre now leaves the Templars (to the Tyrants of the Cedars, since Hell's land never passes to the Faithful) |
| Antioch's ruler titled Duke | Duke of New Antioch | Fits |
| Admiralty raids, Corsair Threat | Doc design | *(invented)*; the Admiralty name is invented |

Still open against canon: Ireland is not a united High Kingdom by 1807; the Delhi Sultanate is not kept alive to 1721; Ekron (Beelzebub's city, rebuilt by the Order of the Fly) is not scripted.
