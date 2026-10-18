# Art requests

Drop finished art in `art/` at the repo root, named as below, as **PNG with transparency** (32-bit RGBA). I convert it to DDS and wire it in. Until then the mod uses vanilla art as placeholders.

## Societal value: Piety vs Heresy

| File | Size | Shows | Placeholder now (vanilla) | Style example (vanilla) |
| --- | --- | --- | --- | --- |
| `piety_vs_heresy_left.png` | 128×128 | Piety: Heaven, the Faithful (a halo, three nails, a censer) | `spiritualist_vs_humanist_left.dds` | `main_menu/gfx/interface/icons/societal_values/spiritualist_vs_humanist_left.dds` |
| `piety_vs_heresy_right.png` | 128×128 | Heresy: Hell, the Fallen (the seven-headed serpent, an inverted cross, a fly) | `mysticism_vs_jurisprudence_left.dds` | any `*_right.dds` in the same folder |
| `monthly_towards_piety.png` | 64×64 | Small modifier icon, Piety side | `monthly_towards_spiritualist.dds` | `main_menu/gfx/interface/icons/modifier_types/monthly_towards_spiritualist.dds` |
| `monthly_towards_heresy.png` | 64×64 | Small modifier icon, Heresy side | `monthly_towards_humanist.dds` | same folder |

Vanilla paths are relative to `Steam/steamapps/common/Europa Universalis V/game/`. Vanilla societal icons are round medallions on a transparent background.

## Heretic government reforms

Portrait-shaped card illustrations, like vanilla's `main_menu/gfx/interface/icons/government_reforms/illustrations/military_order_reform.dds`.

| File | Size | Shows |
| --- | --- | --- |
| `npoe_legion_of_the_damned.png` | 64×90 | The Heretic Legion: damned soldiers of the Court |
| `npoe_pact_of_the_seven_seats.png` | 64×90 | A priest's pact with an archdevil of the seven seats |
| `npoe_order_of_the_fly.png` | 64×90 | A knight of the Order of the Fly (Black Grail) |

## Country flags

All new tags currently get a random generated flag. EU5 builds flags from layers (pattern + emblems), so the simplest route is **one full flag image per tag**, used as a single textured emblem over a solid base.

- Size **384×256** (3:2), PNG. Keep important detail away from the outer 5% (the frame crops it).
- Optional: name a two-colour scheme instead and I build it from vanilla emblems.

| Tag | Country | Canon / notes |
| --- | --- | --- |
| `THR.png` | Templar Heretics | Fallen Templars who opened the Gate in 1099; their colours are dark red and black |
| `HCD.png` | Tyrants of the Cedars | Heretic domain of Lebanon (pledged to Mammon) |
| `HLT.png` | Heretic Lords of Latakia | Heretic domain of the Syrian coast (pledged to Apollyon) |
| `HMB.png` | Lords of Moab | Heretic domain of Transjordan (pledged to Belphagor) |
| `BGH.png` | Black Grail Host | Beelzebub's horde; the black cup and flies |
| `KMR.png` | Legions of Kimaris | Marquis of Hell who takes Constantinople (1545–1573) |
| `HAR.png` | Heretic Admiralty | Hell's fleet at Gibraltar from 1666 |
| `NAT.png` | Principality of Antioch / New Antioch | Faithful bastion since 1102 |
| `NIZ.png` | Nizari Alamut | The fortress of Alamut |
| `JAL.png` *(optional)* | Iron Sultanate | Now uses the vanilla Jalayirid flag; the official map shows its banner (white field, dark emblem) |
