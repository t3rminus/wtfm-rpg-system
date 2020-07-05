# WTFM RPG System
A simple system for roleplaying games, using a single six-sided die (D6).

### Character Creation
Each character gets 2 points to allocate into the following skills.
One skill can be made negative to gain an additional point, if desired.
- **Will**: Convincing someone of something, avoiding being influenced (Charisma/Constitution)
- **Thaumaturgy/Technology**: Depending on the setting, casting spells, identifying the properties of objects, or using unfamiliar devices (Intelligence/Wisdom)
- **Force**: Feats of strength, attacking (Strength)
- **Movement**: Being sneaky, moving quickly, acrobatics (Dexterity)

For Example:
```
-- Ken --
Will: 2
Thaum: -1
Force: 0
Move: 1
```


### Health & Death
Characters can sustain maximum 2 wounds… after that they’re dead.
Each wound counts as -1 in all skills until it is healed by finding something or someone to heal it.
Be sure to keep track of wound points.

If your character is wearing armour and sustains a wound, the armour will negate the wound only once, and becomes unusable afterward. The armour must be repaired or replaced.


### Skill Checks
Rolls are only made using a six-sided die (D6). Make a skill check when your GM requires it, for instance to perform an action, attack an enemy or cast a spell. The DM will tell you which skill to roll. Roll a D6, add your character's points, subtract any wounds, and look at the result:

```
6   = great success (The action succeeds with benefits)
4-5 = success (The action succeeds)
2-3 = failure (The action fails)
1   = great failure (The action fails with penalties)
```

For example: If Ken was attacking an enemy, he'd roll a D6, add his Force stat (0 in this case, so nothing is added), and subtract any wounds (if Ken is healthy, this roll is entirely based on chance).
Your GM might decide from the following outcomes:

```
6   = Ken knocks the enemy out in one hit, allowing them to be interrogated later
4-5 = Ken wounds the enemy, but they duck and take cover.
2-3 = Ken misses the enemy, and they duck and take cover.
1   = Ken misses the enemy, and they run off to warn their teammates.
```

**Rolling two 1’s in a row is an automatic wound.** If you roll a 1, keep track of it until you roll something else.
