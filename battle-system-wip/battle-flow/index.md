# [Battle System (WIP)](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/)

## [Battle Flow](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/)

- **[Return to Homepage](https://javascriptlearner815.github.io/ka-projects/)**
- **[Return to *Battle System (WIP)* Homepage](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/)**

*[Battle flow](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/)* is controlled in turns. [Enemies](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy/) are placed based on their position
in the [battle](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/battle/)'s corresponding [enemy map](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy-map/).

The [player](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/player/) plays first, choosing one of their unlocked and available [battle actions](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/).

Then, the [enemy or enemies](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy/) play their move(s) that're specified in their [enemy](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy/) IDs.

This turn-based combat system proceeds until either the [player](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/player/) successfully [flees](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/flee) or the [player](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/player/)/[enemy](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy/) [dies](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/).

## Table of Contents

1. [Battle Flow](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/) ⬅ You're Here
    1. [Starting a Battle](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/starting-a-battle/)
        1. [Positive](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/starting-a-battle/positive)
        1. [Neutral](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/starting-a-battle/neutral)
        1. [Negative](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/starting-a-battle/negative)
    1. [Battle Actions](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/)
        1. [Weapon](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/weapon)
        1. [Defend](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/defend)
        1. [Heal](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/heal)
        1. [Taunt](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/taunt)
        1. [Flee](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/flee)
        1. [Hint](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/hint)
        1. [Pass](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/pass)
        1. [Collect Weapon](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/battle-actions/collect-weapon)
    1. [Death](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/)
        1. [Normal](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/normal)
        1. [Mythic](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/mythic)
        1. [Super-Mythic](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/super-mythic)
        1. [K.O.](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/ko)
        1. [Fake](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/fake)
        1. [Fair](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/battle-flow/death/fair)
1. [Config](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/)
    1. [Player](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/player/)
    1. [Enemy Map](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy-map/)
    1. [Enemy](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/enemy/)
    1. [Battle](https://javascriptlearner815.github.io/ka-projects/battle-system-wip/config/battle/)
