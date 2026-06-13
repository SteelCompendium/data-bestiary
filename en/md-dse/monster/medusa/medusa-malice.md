---
file_basename: medusa-malice
file_dpath: monster/medusa
item_id: medusa-malice
item_name: Medusa Malice
name: Medusa Malice
scc: mcdm.monsters.v1/monster.medusa/medusa-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of a medusa's turn, you can spend Malice to activate one of the following features.

> 🏹 **Weakening Glare (4 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **- Magic, Ranged, Strike** |     **Main action** |
> |-----------------------------|--------------------:|
> | **📏 Ranged 10**            | **🎯 One creature** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage; [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
> - **12-16:** 10 damage; [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
> - **17+:** 12 damage; [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)

> ☠️ **Solo Action (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The medusa takes an additional main action on their turn. They can use this feature even if they are [dazed](scc:mcdm.heroes.v1/condition/dazed).

> 🏹 **Ssstop and Lisssten (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |        **Main action** |
> |-------------------|-----------------------:|
> | **📏 Ranged 10**  | **🎯 Three creatures** |
>
> **Power Roll + 4:**
>
> - **≤11:** I < 2 the target is charmed
> - **12-16:** I < 3 the target is charmed
> - **17+:** I < 4 the target is charmed
>
> **Effect:** At a time of the medusa's choosing, a charmed creature moves up to their speed and makes a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against an enemy of the medusa's choice as a free triggered action. The creature is then no longer charmed.

> 🔳 **Shatter Victims (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The medusa causes three stone statues within 10 squares of them to each shatter in a 2-cube explosion. Each enemy in one of those areas makes a **Might test**. An enemy [restrained](scc:mcdm.heroes.v1/condition/restrained) or [slowed](scc:mcdm.heroes.v1/condition/slowed) by the medusa's Petrify ability has a double bane on the test.
>
> - **≤11:** 12 damage; vertical [push](scc:mcdm.heroes.v1/movement/forced-movement) 3; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 10 damage; vertical [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 6 damage
