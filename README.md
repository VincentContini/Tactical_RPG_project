# Tactical RPG project

A tactical RPG made with Godot 4 by Vincent CONTINI.
Inspired by the Fire Emblem series.

## Ideas

### Story

- **Main character** -> Fights in a Revolution as a low-ranking officer

- The Revolution is lead by 2 commanders giving contradictory orders
    - **Commander #1** -> Driven by strong morals, believes in the inherent dignity of all human beings and in the sanctity of life, they embody these beliefs to the extreme. Maybe extend their beliefs to animals, or even monsters? Their stubbornness can cause them to take irrationnal descisions that risk bringing the Revolution to a tragic end.
    - **Commander #2** -> Driven by his experience as a high-ranking military officer, believes that the end justifies the means. They are determined to bring the Revolution to victory, and are convinced it stands no chance to prevail by fighting fair and following a strict moral code.
    - The one whose morals are the furthest from the player's becomes the final boss when the Revolution succeeds and the absence of a common ennemy splits the Revolutionnists
    - *In gameplay* -> For every map, both commanders of the Revolution give the player orders (either a victory condition or a side objective to complete). Each order the player follows make the respective commander's trust in the avatar grow, each order that the player ignores weakens it. At the end of the game the commander that trusts the avatar the least will turn against the player and become the final boss. (If it's close, maybe a scene where both try to convince the avatar and the player gets to choose who to support?)
    - There also are global orders:
        - *commander #1* -> Spare the ennemies that don't have any weapon or tome equipped
        - *commander #2* -> Don't let an injured ennemy recieve healing from a healer
    - Every playable character leans toward one of the two commanders. The ones leaning towards the commander that betrays the Revolution need to be at a high enough support level with the avatar to stay in the player's army. Supports must include the avatar trying to convince them or at least making them see the merit of the opposing commander's way of leading the Revolution.

### Maps

- A map where the ennemy forces villagers without any military training to fight the player's army.
    - The villagers are reinforcments that spawn along with an ennemy boss behind de player as they progress through the map.
    - The player needs to force their way forward and take the ennemy's original position before the villagers can catch up and engage combat.
    - Commander #1 orders to save the villagers. Killing a single one of them means the order wasn't followed.
    - *If a villager dies* -> Commander #2 orders to get rid of the remaining villagers to avoid retaliation from them.
    - If the ennemy boss commanding the villagers die, the remaining villagers will flee. (Make the boss squishy so it can get one rounded to avoid involuntary counterattacks on the villagers)
    - Villagers are weak but get a skill that boost them when they attack an ennemy that doesn't counterattack (Either a stacking bonus each turn they attack without counter or a straight up damage buff like FE Fates' *Opportunist*)
    - Make the target position ennemy phase focused so leaving a tank behind to stall the villagers has a big enough opportunity cost.
    - consequences of the map depending on orders followed/villagers killed :
        - *No villagers have been killed* -> Nearby villages are supportive of the Revolution. Grants access to the traditionnal villager trainee unit in addition to the villages' shops.
        - *Not all villagers have been killed* -> Nearby villages don't actively fight the Revolution. Grants access to the villages' shops. Villagers that haven't been killed will return as stronger ennemies in the next chapters.
        - *All villagers have been killed* -> Nearby villages are against the Revolution. Deny access to the villages' shops.

### System

**Follow up attacks**
- Not limited to 2? Maybe only available to fast classes like swordmaster?
- Damage reduced for each follow up attack beyond 2

**Mounted and flying deployement limit**
- The player's army has a limited number of mounts of each species.
- The player can't deploy more *cavaliers/pegasus knights/wyvern* riders than they have *horses/pegasi/wyverns*
- Horses, wyverns, pegasus are available to purchase (unlimited?) (expensive?)

### Classes

**Mage class line**
- *Base classe : **Mage***
- *Promotion #1: **Arcanist*** -> Master of magic, traditionnal glass cannon mage, maybe with utility (healing/supporting magic)
- *Promotion #2: **Warden*** -> Hybrid class, gets bonuses when alternating between weapons and spells
    - gets to choose between swords, melee, (lances?), (axes?) upon promotion
    - On spell use: enhances next physical attacks depending on element until next spell use.
        - fire -> increased damage dealt
        - thunder -> increased crit
        - wind -> increased avoid
        - earth -> reduced damage taken
        - water -> increased hit
        - dark -> life drain
        - light -> effectivenes against {monsters/cursed creatures/demonic beings}

### Tutorials

- Mounts deployement limit -> first pegasus knight and first cavalier join on the same map. One of them brings the other's mount alongside their own mid-battle, which allows for the other to join the battle.


## Files

The project uses Godot Engine.


## Contributions and licenses