---
file_basename: draconian-malice
file_dpath: monster/draconians
item_id: draconian-malice
item_name: Draconian Malice
name: Draconian Malice
scc: mcdm.monsters.v1/monster.draconians/draconian-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any draconian's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 👤 **Guarding Gale (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> A draconian acting this turn flaps their wings and creates a mighty gale. Each creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the draconian is pushed up to 4 squares, and if they have M < 2, they are knocked [prone](scc:mcdm.heroes.v1/condition/prone).

> 🔳 **Breath Weapon (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic**            |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 4 x 2 line within 1** | **🎯 Each enemy in the area** |
>
> **Special:** The damage dealt by this ability matches a damage type the draconian has immunity to.
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage
> - **12-16:** 10 damage
> - **17+:** 13 damage

> ❇️ **Scaleshatter Burst (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic** |             **Free maneuver** |
> |-----------------|------------------------------:|
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage
> - **12-16:** 13 damage
> - **17+:** 16 damage
>
> **Effect:** The draconian's scales shatter from battle damage. The draconian has damage weakness 5 but can take two turns per round until the end of the encounter.
