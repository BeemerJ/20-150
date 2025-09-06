# Character Stats and Progression

## Core Statistics

### Strength
- Affects:
  - Melee attack power
  - Accuracy with heavy weapons
  - Carry weight
  - Recovery time for certain weapons

### Endurance
- Affects:
  - Hit points
  - Negative effect saving throws
  - Carry weight
  - Hunger drainage rate

### Perception
- Affects:
  - Sneaking ability
  - Trap detection
  - Critical hit chance
  - Ranged weapon accuracy
  - Loot quality (slight bonus)

### Agility
- Affects:
  - Battle movement
  - Fleeing success rate
  - Dodging
  - Thirst drainage rate
  - Trap saving throws
  - General to hit bonus
  - Weapon reload speed

## Level Progression

### Experience and Levels
- Experience points are used for perk unlocking, NOT leveling up
- Each dungeon boss grants one level
- Level ups provide:
  - Rolled HP increase
  - Set amount of stat points

### Trait System
- Inspired by Risk of Rain's hybrid progression: RPG stats with item stacking and tradeoffs
- Traits can come from items and gear, further customizing builds
  - Leveling up can grant both positive and negative traits
  - For example, a "Walking Tank" trait might reduce movement speed but increase defense and scales between equipment / level.  
  - Walking Tank Example (From a unique Helmet): 

    > `Armour = Base Armour Value + (Level x 1.5) + Count.Obsidian Powder [Stackable Item that gives a +1% chance to block physical damage not including critical hits]`

    > `Movement Speed = Base Movement Speed - (Level x 1.3) - (Count.Obsidian Powder)`

### Perk System
- Perks can be chosen after resting at an inn
- Requirements must be met for perks to appear
- Example requirements:
  - Level-based: "Level 1 + 15 Tier I Pistol Kills + High enough Perception = Tier 1 Pistol Proficiency"
  - Stat-based: "25 Agility + 10 Spider Kills = Spider Combat Bonus"
- Perk balance system on items:
  - Negative perks lower overall value
  - Positive perks increase value
  - System aims for equilibrium with variables

## Survival Elements

### Hunger System
- Affects:
  - Endurance and damage taken
  - Has multiple thresholds for effects
- Can consume rancid food with debuff risks
- Gives incorrect danger warnings

### Thirst System
- Affects:
  - Attack damage
  - Hit chance
- Can drink contaminated water with debuff risks
- Hallucinations