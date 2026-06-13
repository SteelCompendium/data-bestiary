---
features:
    - body: The [undead](scc:mcdm.monsters.v1/rule.keyword/undead) activates a [Malice](scc:mcdm.monsters.v1/rule.monster/malice) feature available to [undead](scc:mcdm.monsters.v1/rule.keyword/undead) of level 9 or lower.
      cost: 2-7+ Malice
      icon: ⭐️
      name: Prior Malice Features
    - body: The [undead](scc:mcdm.monsters.v1/rule.keyword/undead) attempts to rend the vitality of their foes. Each enemy within 5 squares of the [undead](scc:mcdm.monsters.v1/rule.keyword/undead) makes a **Might test**.
      cost: 7 Malice
      icon: ❇️
      name: Death Tax
      power_roll:
        tiers:
            high: 5 corruption damage
            low: 10 corruption damage; the target loses 2 [Recoveries](scc:mcdm.heroes.v1/rule.health/recoveries)
            mid: 8 corruption damage; the target loses 1 [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
      sections:
        - label: Effect
          text: A target who has fewer [Recoveries](scc:mcdm.heroes.v1/rule.health/recoveries) than they would lose is also [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends).
        - label: Special
          text: This ability can't be used by a [minion](scc:mcdm.monsters.v1/rule.organization/minion).
flavor: At the start of any level 10 undead's turn, you can spend Malice to activate one of the following features.
kind: malice
level: 10
name: Undead Malice (Level 10 Malice Features)
scc: mcdm.monsters.v1/monster.undead.4th-echelon/undead-malice-level-10-malice-features
type: featureblock
---

At the start of any level 10 [undead](../../../rule/keyword/undead.md)'s turn, you can spend [Malice](../../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Prior [Malice](../../../rule/monster/malice.md) Features (2-7+ [Malice](../../../rule/monster/malice.md))**
>
> The [undead](../../../rule/keyword/undead.md) activates a [Malice](../../../rule/monster/malice.md) feature available to [undead](../../../rule/keyword/undead.md) of level 9 or lower.

> ❇️ **Death Tax (7 [Malice](../../../rule/monster/malice.md))**
>
> The [undead](../../../rule/keyword/undead.md) attempts to rend the vitality of their foes. Each enemy within 5 squares of the [undead](../../../rule/keyword/undead.md) makes a **Might test**.
>
> - **≤11:** 10 corruption damage; the target loses 2 [Recoveries](../../../rule/health/recoveries.md)
> - **12-16:** 8 corruption damage; the target loses 1 [Recovery](../../../rule/health/recoveries.md)
> - **17+:** 5 corruption damage
>
> **Effect:** A target who has fewer [Recoveries](../../../rule/health/recoveries.md) than they would lose is also [weakened](../../../condition/weakened.md) (save ends).
>
> **Special:** This ability can't be used by a [minion](../../../rule/organization/minion.md).
