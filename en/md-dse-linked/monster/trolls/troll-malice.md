---
features:
    - body: One troll acting this turn spews out a half-digested meal in a 5 x 1 line within 1 square of them. Each troll in the area regains 3 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina). Each enemy in the area makes a **Might test**.
      cost: 3 Malice
      icon: "\U0001F533"
      name: Foul Spew
      power_roll:
        tiers:
            high: 6 acid damage
            low: 12 acid damage; [dazed](scc:mcdm.heroes.v1/condition/dazed) (EoT)
            mid: 10 acid damage; [weakened](scc:mcdm.heroes.v1/condition/weakened) (EoT)
    - body: Each troll in the encounter can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to them, and regains [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to the damage dealt.
      cost: 5 Malice
      icon: "\U0001F5E1"
      name: Emergency Meal
    - body: Each [winded](scc:mcdm.heroes.v1/rule.health/winded) troll in the encounter disgorges the contents of their stomach onto the ground around them, creating a 1 burst of foul vomitus that lasts until the end of the encounter. Each non-troll who enters this area for the first time in a round or starts their turn there takes 5 acid damage. Each troll in the area has a double edge on power rolls.
      cost: 7 Malice
      icon: ❇️
      name: Bloody Banquet
file_basename: troll-malice
file_dpath: monster/trolls
flavor: At the start of any troll's turn, you can spend Malice to activate one of the following features.
item_id: troll-malice
item_name: Troll Malice
kind: malice
name: Troll Malice
scc: mcdm.monsters.v1/monster.trolls/troll-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any troll's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 🔳 **Foul Spew (3 [Malice](../../rule/monster/malice.md))**
>
> One troll acting this turn spews out a half-digested meal in a 5 x 1 line within 1 square of them. Each troll in the area regains 3 [Stamina](../../rule/health/stamina.md). Each enemy in the area makes a **Might test**.
>
> - **≤11:** 12 acid damage; [dazed](../../condition/dazed.md) (EoT)
> - **12-16:** 10 acid damage; [weakened](../../condition/weakened.md) (EoT)
> - **17+:** 6 acid damage

> 🗡 **Emergency Meal (5 [Malice](../../rule/monster/malice.md))**
>
> Each troll in the encounter can make a [free strike](../../feature/common/main-actions/free-strike.md) against a creature [adjacent](../../rule/combat/adjacent.md) to them, and regains [Stamina](../../rule/health/stamina.md) equal to the damage dealt.

> ❇️ **Bloody Banquet (7 [Malice](../../rule/monster/malice.md))**
>
> Each [winded](../../rule/health/winded.md) troll in the encounter disgorges the contents of their stomach onto the ground around them, creating a 1 burst of foul vomitus that lasts until the end of the encounter. Each non-troll who enters this area for the first time in a round or starts their turn there takes 5 acid damage. Each troll in the area has a double edge on power rolls.
