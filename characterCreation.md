# Character Creation Guide

## Point Buy System
Characters are created using a point-buy system. Points can be spent on:
- Base Stat Improvements
- Attack Actions (maximum 4)
- Ability Actions
- Reaction Actions (WIP)

## Base Stats

### Size Categories
Choose your model's size category first. This determines your starting stats:

| Size Category | Base Size | Size Value | Strides | Wounds | Influence | Attack Reach |
|:--------------|:----------|:-----------|:--------|:-------|:----------|:-------------|
| Tiny          | < 25mm    | 0.5        | 8       | 0^     | 0"        | 0"           |
| Small         | 25-32mm   | 1          | 5       | 1      | 0"        | 0"           |
| Medium        | 40-50mm   | 2          | 3       | 1      | 1"        | 1"           |
| Large         | 60-80mm   | 3          | 2       | 1      | 3"        | 2"           |
| Huge          | 90-120mm  | 4          | 1       | 2      | 4"        | 4"           |
| Gargantuan    | 130-150mm | 5          | 1       | 2      | 5"        | 6"           |

^ must pay for wounds

### Stat Improvements
Spend points to improve your base stats up to their maximum values:

**Strides** (Movement Speed)
- Cost varies by size:
  - Tiny: 1 points per +1
  - Small: 2 points per +1
  - Medium: 3 points per +1
  - Large: 4 points per +1
  - Huge/Gargantuan: 5 points per +1
- Maximum: Base Strides + 3

**Wounds** (Health Points)
- Progressive cost:
  1. First wound: 1 point
  2. Second wound: 2 points
  3. Third wound: 3 points
  4. Fourth wound: 4 points
  5. Fifth wound: 5 points
  6. Sixth wound: 6 points
  7. Seventh wound: 7 points
- Maximum: Base Wounds + 5

**Influence** (Control Range)
- Cost: 5 points per +1"
- Maximum: Base Influence + 2"

**Attack Reach** (Melee Range)
- Cost: 4 points per +1"
- Maximum: Base Attack Reach + 3"

**Resistances** (Physical/Energy/Psyche)
All models start with a value of 1 in two resistance types of your choice, and a value of 0 in the remaining resistance type. You can spend points to increase resistances up to a maximum of 5 in each. The cost increases progressively as the value rises:

- Resistance 2: 3 points  
- Resistance 3: 5 points  
- Resistance 4: 8 points  
- Resistance 5: 12 points  

**Maximum:** 5 in any resistance type.

## Action Types
Each character can purchase up to 8 actions (NOTE: I want this to fit on a card so maybe less):

### Available Actions
- Attack Actions (1-4)
- Ability Actions (0-4)
- Reaction Actions (0-2)

### Exhaustion Option
When purchasing any action, you may choose to make it more taxing:
- Action inflicts 2 Exhaust Tokens (instead of 1)
- Reduces purchase cost by 2 points
- Cannot reduce cost below 1 point
- Must be decided at purchase

### Ability Actions
Special traits that grant unique advantages. Each can be purchased once unless specified.

- For abilities that grant bonuses, bonuses only last until start of model's next activation

**Abilities**
| Ability               | Description                                           | Cost |
|:----------------------|:------------------------------------------------------|:-----|
| Blink                 | 6" teleport, requires LOS                             | 6    |
| Effect Resistance     | Remove one effect within 4" + reach at activation end | 8    |
| Evasion               | +2 defense vs ranged attacks                          | 6    |
| Fearsome Aura         | -1 to attacks within 2"+influence                     | 5    |
| Hard to Hit           | -2 to attacks from beyond 6"                          | 8    |
| Hardened              | -1 wound from all attacks                             | 12   |
| Immovable             | +2 size vs push/throw                                 | 8    |
| Relentless            | Two maneuvers per activation                          | 8    |
| Supernatural Strength | +1 size for push/throw                                | 6    |
| Teleport              | 4" teleport, no LOS needed                            | 8    |
| Titanic Strength      | +2 size for push/throw                                | 10   |
| Unmovable             | +1 size vs push/throw                                 | 4    |

### Reaction Actions
*Work in Progress*
Allows response to enemy actions outside normal activation. Each has:
- Specific trigger condition
- Action cost
- Effect

### Attack Creation Guide

#### Base Attack Template

- **Name**: Strike
- **Type**: Choose (Physical, Energy, or Psyche)
- **Range**: 0" + Attack Reach
- **Target Type**: Single
- **Attack Strength**: 1
- **Effects**: None
- **Cost**: 0

#### Attack Construction Rules
1. Maximum 4 attacks per character
2. Minimum 1 attack per character
3. Each 2 points of Attack Strength requires purchasing 1 effect
4. All attacks can use the Exhaustion Option

**Exhaustion Option**
- Action inflicts 2 Exhaust Tokens instead of 1
- Reduces purchase cost by 2 points
- Cannot reduce cost below 1 point
- Must be decided at purchase

#### Target Types and Costs

**Single Target** (Base Type)
- Attack Strength:
  - Strength 2: 2 points
  - Strength 3: 4 points
  - Strength 5: 6 points
  - Strength 6: 8 points
- Range (Added to attack reach):
  - 3": 1 point
  - 4": 2 points
  - 5": 3 points
  - 6": 4 points
  - 7": 5 points
  - 8": 6 points
  - 9": 7 points

**Area Attack**
- Description: Affects all models touching the area
- Area Diameter:
  - 2": 1 point
  - 3": 2 points
  - 4": 4 points
- Range to Center (Added to attack reach):
  - 2": 1 point
  - 4": 2 points
  - 6": 4 points
  - 8": 8 points
- Attack Strength:
  - Strength 2: 5 points
  - Strength 3: 10 points
  - Strength 5: 15 points
  - Strength 6: 20 points

**Breakthrough**
- Description: 1" wide line that can't start inside bases
- Length:
  - 2": 1 point
  - 3": 2 points
  - 4": 3 points
  - 5": 4 points
  - 6": 5 points
- Attack Strength:
  - Strength 2: 5 points
  - Strength 3: 10 points
  - Strength 5: 15 points
  - Strength 6: 20 points

**Ricochet**
- Description: Hits multiple targets in sequence
- Number of Targets:
  - 2 targets: 1 point
  - 3 targets: 2 points
  - 4 targets: 4 points
- Range Between Targets:
  - 2": 1 point
  - 3": 2 points
  - 4": 4 points
- Initial Range (Added to attack reach):
  - 2": 1 point
  - 4": 2 points
  - 6": 4 points
  - 8": 8 points
- Attack Strength:
  - Strength 2: 5 points
  - Strength 3: 10 points
  - Strength 5: 15 points
  - Strength 6: 20 points

#### Movement Effects
| Effect            | Description                                | Always | Match Suit | Both Suits |
|:------------------|:-------------------------------------------|:-------|:-----------|:-----------|
| Displace Attacker | Move attacker within 1" of target          | 6      | 4          | 1          |
| Displace Defender | Move target within 1" of original position | 5      | 3          | 0          |
| Knockback         | Push target 1" directly away               | 4      | 2          | 0          |

#### Temporary Effects
| Effect          | Description               | Always | Match Suit | Both Suits |
|:----------------|:--------------------------|:-------|:-----------|:-----------|
| Hinder          | -1 defense                | 3      | 2          | 0          |
| Prone           | Target knocked prone      | 3      | 2          | 0          |
| Reduce Energy   | -1 Energy Resistance      | 2      | 1          | 0          |
| Reduce Physical | -1 Physical Resistance    | 2      | 1          | 0          |
| Reduce Psyche   | -1 Psyche Resistance      | 2      | 1          | 0          |
| Slow            | -1 movement speed (min 1) | 4      | 2          | 0          |
| Weaken          | -1 attack strength        | 3      | 2          | 0          |

**Effect Duration:** Temporary effects last until removed.
**Effect Stacking:** Temporary Effects can stack up to 3 times on a single target.

#### Damage Effects
| Effect           | Description               | Always | Match Suit | Both Suits |
|:-----------------|:--------------------------|:-------|:-----------|:-----------|
| Damage Over Time | 1 wound at activation end | 5      | 3          | 1          |
| Critical Strike  | +1 wound if damaged       | -      | 3          | 1          |
| Null Strike*     | No damage dealt           | -3     | -          | -          |

*Requires at least one Always effect


