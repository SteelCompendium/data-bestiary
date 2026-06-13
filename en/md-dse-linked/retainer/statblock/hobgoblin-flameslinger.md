---
agility: 0
ev: '-'
file_basename: hobgoblin-flameslinger
file_dpath: retainer/statblock
free_strike: 5
immunities:
    - Fire 4
intuition: 1
item_id: hobgoblin-flameslinger
item_name: Hobgoblin Flameslinger
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 1
name: Hobgoblin Flameslinger
organization: Retainer
presence: 3
reason: 2
role: Controller
scc: mcdm.monsters.v1/retainer.statblock/hobgoblin-flameslinger
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "48"
type: statblock
---

| Goblin, Hobgoblin, Humanoid, Infernal |         -          |      Level 4      |  Controller Retainer  |         EV -         |
|:-------------------------------------:|:------------------:|:-----------------:|:---------------------:|:--------------------:|
|            **1M**<br>Size             |   **5**<br>Speed   | **48**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|            **1M**<br>Size             |   **5**<br>Speed   | **48**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|        **Fire 4**<br>Immunity         | **- **<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+1**<br>Might            |  **0**<br>Agility  | **+2**<br>Reason  |  **+1**<br>Intuition  |  **+3**<br>Presence  |

> 🏹 **Fire Curse (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 5 fire damage
> - **12-16:** 9 fire damage
> - **17+:** 12 fire damage; A < STRONG the target is burning (save ends)
>
> **Effect:** A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

> 🏹 **Fuel for the Fire**
>
> | **Magic, Ranged** |     **Main action** |
> |-------------------|--------------------:|
> | **📏 Ranged 10**  | **🎯 One creature** |
>
> **Effect:** Until the end of the flameslinger's next turn, the target has fire weakness equal to the flameslinger's level. If the target is the flameslinger's mentor, they instead have fire immunity equal to the flameslinger's level.

> ⭐️ **Infernal Ichor**
>
> When the flameslinger is reduced to 0 [Stamina](../../rule/health/stamina.md), they spray buring blood. Each creature [adjacent](../../rule/combat/adjacent.md) to the flameslinger takes 3 fire damage.

######## Level 7 Retainer Advancement Ability

> 🔳 **Unholy Attraction (Encounter)**
>
> | **Area, Magic, Ranged** |               **Main action** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; pull 1
> - **12-16:** 12 damage; pull 2
> - **17+:** 16 damage, pull 4
>
> **Effect:** A target who is pulled [adjacent](../../rule/combat/adjacent.md) to the flameslinger and who has P < AVERAGE is knocked [prone](../../condition/prone.md).

######## Level 10 Retainer Advancement Ability

> ❇️ **Fire Spiral (Encounter)**
>
> | **Area, Magic** |               **Main action** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage; [push](../../movement/forced-movement.md) 2
> - **12-16:** 12 damage; [push](../../movement/forced-movement.md) 3
> - **17+:** 16 damage; [push](../../movement/forced-movement.md) 5
>
> **Effect:** If the flameslinger's mentor is within 10 squares of the flameslinger, the mentor can be the source of the burst instead of the flameslinger.
