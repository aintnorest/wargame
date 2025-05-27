# Core Rules

Working Game Title: Conflict

## Game Introduction & Goals

* Theme to be fleshed out later but to get a taste look in campaign.md
* Goals: A strategic wargame that is model-agnostic, where model size matters, and all decisions have a significant impact.

## Basic Luck Mechanic

Conflict uses a modified deck of cards. The deck comprises Aces, 1s, 2s, 3s, and Jacks of each suit and both jokers. Aces are worth 1, 2s are worth 2, 3s are worth 3, Jacks are worth -1,  A Red Joker is worth -2 and counts as any suit, and A Black Joker is worth +4 and counts as no suit.
  * Players flip two cards from the modified deck.
  * For ties suite dominance is  Spades (♠), Hearts (♥), Diamonds (♦), and Clubs (♣)
  * The result of the card flip is added to relevant character stats and modifiers to determine the success of an action (e.g., attacking, defending). The difference between the attacker's and defender's totals determines damage.
  
### Probability Calculations

  * **Deck Composition:**
    * 4 Aces (1 each of Spades, Hearts, Diamonds, Clubs)
    * 4 2s (1 each of Spades, Hearts, Diamonds, Clubs)
    * 4 3s (1 each of Spades, Hearts, Diamonds, Clubs)
    * 4 Jacks (-1 each of Spades, Hearts, Diamonds, Clubs)
    * 1 Red Joker (-2, counts as any suit)
    * 1 Black Joker (+4, counts as no suit)
    * Total cards: 18
  * **Possible Outcomes:**
    * Minimum sum: -3 (Red Joker + Jack)
    * Maximum sum: +7 (Black Joker + 3)
  * **Probability of Each Sum:**
    | Sum | Number of Ways | Probability (Percentage) |
    |:----|:---------------|:-------------------------|
    | -3  | 4              | 2.61%                    |
    | -2  | 6              | 3.92%                    |
    | -1  | 4              | 2.61%                    |
    | 0   | 20             | 13.07%                   |
    | 1   | 20             | 13.07%                   |
    | 2   | 23             | 15.03%                   |
    | 3   | 20             | 13.07%                   |
    | 4   | 22             | 14.38%                   |
    | 5   | 20             | 13.07%                   |
    | 6   | 10             | 6.54%                    |
    | 7   | 4              | 2.61%                    |
    
  * **Probability of a Specific Suit:**
    | Event                                                                                                           | Percentage (approx.) |
    |:----------------------------------------------------------------------------------------------------------------|:---------------------|
    | At Least One of Two Cards Counts as a Specific Suit (e.g., at least one of your two cards can count as a Heart) | 49.02%               |
    | Drawing One Card of a Specific Suit AND One Card of a Different Specific Suit (e.g., one Heart and one Spade)   | 15.69%               |
    | Drawing Two Cards of a Single Specific Suit (e.g., exactly two Hearts)                                          | 6.54%                |

    NOTE: Currently character creation uses the first and last to trigger abilities. I'm leaving the middle option because I may add it as an option for ability / effect purchasing.

## Core Mechanics

### Game Flow

*   **Round Structure:** A game is divided into a series of rounds. During each round, players alternate activating one model at a time, starting with the player who has initiative. A round ends when all models have had the opportunity to activate.
*   **Turn Structure:**

  1.  **Pass Activation (Optional):**
    If the opposing player has at least 2 more un-activated models than the active player, the active player may choose to pass their activation. If this option is chosen:
    *   The active player activates no model for this turn.
    *   The activation is immediately passed to the opposing player.
    *   The active player's turn ends.
  2.  **Choose and Declare Activation:**
    *   Select a friendly model that has not activated this round and declare it as the active model.
  3.  **Remove Exhaust Tokens:**
    *   Remove one **Exhaust Token** from each of the model's Actions.
  4.  **Perform Actions:**
    During the active model's activation, the player may perform the following actions in any order as long as the action doesn't have an exhausted token. After performing the action place an **Exhausted Token** on the action to indicate it's been used this turn:
    *   **One Move Action**
    *   **One Maneuver Action**
    *   **One Attack Action**
    *   **Use Any Ability Actions:**
  5.  **End of Turn:**
    At the end of the turn, perform the following steps in order:
    *   Place a token next to the active model to indicate it has activated this round.
    *   Pass the activation to the opposing player.
    *   The opposing player's turn begins.

### Movement

  * **Base Strides and Splitting Movement:** A model has a number of Strides, as determined by its Size Category and character creation. Each Stride can be up to the length of the model's base diameter. Models that are two sizes larger than a piece of terrain can move over it if their base can reach the other side; this costs 1 Stride.
  * **Climb:** If a model's base can fit on top of a piece of terrain, and the terrain size is greater than or equal to the model's size, the model can climb the terrain. To climb, a model loses a number of Strides equal to the terrain size divided by the model size, rounded up. The model is then placed within 1/2" of the edge from where it climbed. For example, a size 1 model climbing size 4 terrain would lose 4 Strides.
  * **Prone:** A model that is prone may spend 1 stride to stand up. A prone model spends 2 strides to move 1 stride. A prone model counts as one size category smaller for determining cover. Attacking a prone model that is base to base gains a +1 attack strength. A model may fall prone at any time.

### Attack

Each character has a number of attacks consisting of the following stats:
* **Attack Type:** Physical, Energy, or Psyche
* **Target Type:** One of the following:
  * Single Target: Attacks one model within range
  * Area: Affects all models touching a circular area
  * Breakthrough: Affects models in a 1" wide line
  * Ricochet: Chain attack that hits multiple targets in sequence
* **Range:** Distance from attacker to target(s), added to Attack Reach
* **Attack Strength:** Base power of the attack (1-6)
* **Effects:** Optional modifiers that trigger in one of three ways:
  * Always: Effect happens on every successful hit
  * Match Suit: Effect triggers if either attack card matches target's suit
  * Both Suits: Effect triggers if both attack cards match target's suit

For more information on attack construction and types of effects that can be added, refer to the [Character Creation document](characterCreation.md#attack-creation-guide).

### Maneuvers

* **Disengage:**
  * Cost: Half max Strides, rounded up.
  * Restrictions: None.
  * Description: Move up to max Strides away from an engaged enemy model without normal engagement restrictions.
* **Charge:**
  * Cost: Max Strides
  * Restrictions: None.
  * Description: Move up to max Strides in a straight line. +1 attack bonus on first attack against target engaged at the end of the charge. If that attack deals damage, Push (Momentum) may be used.
* **Run:**
  * Cost: Max Strides
  * Restrictions: Cannot attack.
  * Description: Double max Strides. +1 to Defense until the start of the model's next turn.
* **Take Cover:**
  * Cost: 1 Stride.
  * Restrictions: None.
  * Description: Increase cover level by one step. This lasts until the start of the model's next turn or until the model moves.
* **Focused Attack:**
  * Cost: Max Strides
  * Restrictions: None.
  * Description: +2 bonus to next attack.
* **Brace:**
  * Cost: Half max Strides, rounded up.
  * Restrictions: None.
  * Description: Count as one size larger for defending against pushes or throws until the start of the model's next turn.
* **Climb:**
  * Cost: Reduce Strides
  * Restrictions: Cannot climb terrain larger than own size.
  * Description: Reduce remaining Strides by 1 for each size category the terrain is larger than the model (min 0).
* **Interact:**
  * Cost: 1 Stride.
  * Restrictions: Must be in base-to-base contact.
  * Description: Interact with objective or terrain.
* **Shake**
  * Cost: None.
  * Restrictions: None.
  * Description: remove 1 temporary condition token.
* **Shift:**
  * Cost: None.
  * Restrictions: None.
  * Description: 1-inch move; does not prevent other actions.
* **Aid:**
  * Cost: 1 Stride.
  * Restrictions: None.
  * Description: +1 attack bonus to friendly model within the model's Influence against an enemy model within the model's Attack Reach.
* **Throw (Terrain):**
  * Cost: Lose attack or movement.
  * Restrictions: Target terrain must be at least two sizes smaller and within reach.
  * Description: Throw terrain. Thrown terrain moves in a straight line from the thrower. Range = (Your Size - Terrain Size - 1) inches. Thrown terrain is destroyed.
* **Throw (Model):**
  * Cost: Lose attack or movement.
  * Restrictions: Target model must be at least two sizes smaller and in base-to-base contact.
  * Description: Throw enemy model. Thrown models move in a straight line from the thrower. Range = (Your Size - Target Size - 1) inches. The target becomes prone.

### Strategic Placement

* **Engagement:** While within the Attack Reach of one or more enemy models, a model cannot end its movement at a distance greater than its starting distance from the closest engaging enemy, unless using the Disengage maneuver.
* **Attack Reach:** Determined by Size Category. Represents the zone within which a model can make melee attacks or interact with objectives.
* **Influence:** Determined by Size Category. Represents the radius around a model within which it exerts control for zone objectives. For zone control, a model is considered to be within the zone if any part of its Base Influence is within the zone.
* **Flanking:** A model is considered to have attacked an enemy from behind if the attacking model is positioned in the target model's rear arc. The rear arc is defined as the half of the target model's base that is opposite the attacking model's front arc. An attacking model gains a +1 bonus to their attack roll when flanking.
* **High Ground:** If a model attacks an enemy from a terrain feature that is at least two size categories higher than the target, the attacking model gains a +1 bonus to their attack roll.
* **Cover:**
  * No Cover: Clear LOS.
  * Partial Cover (+1 to defense roll): Terrain Size = Character Size - 1.
  * Full Cover (+2 to defense roll): Terrain Size <= Character Size - 2.
  * Obscured (No LOS): Terrain Size >= Character Size.

### Interactions

* **Push:** Push target directly away by half the size difference (min 1"). Cannot push targets more than one size larger.
* **Falling:**
  *   A model falls when it is moved to a position where it is no longer supported by the terrain it started on top of. This can occur due to a Push, Throw, or terrain destruction.
  *   **Falling Damage:**
      *   The falling model immediately becomes Prone.
      *   The model suffers damage equal to the height fallen in size categories (minimum 1) + size of the model falling (rounded down, minimum 0). For example, falling from a terrain feature that is Size 3 deals 3 damage.
      *   Falling damage is considered Physical damage.
  *   **Terrain on Impact:** If a falling model lands on a piece of terrain, that terrain is subject to the "Terrain Interaction" rules as if the model were thrown at it.
  *   **Models on Impact:** If a falling model lands on another model, both models become Prone and each suffers a point of Physical damage per size category of the other model. The smaller model is displaced by it's owner so no part of it's base is touching the other model, must be a legal placement.
* **Terrain Interaction:**
  * If terrain is impacted by a model or another piece of terrain, it is destroyed if the size of the thrown object is greater than the size of the impacted terrain, unless it is reinforced terrain.
  * When terrain impacts models or reinforced terrain, the attack value is equal to the Size of the thrown terrain (Physical attack).
  * **Reinforced Terrain:**
    * Wounds = size value X 2
    * Can only be damaged by Physical and Energy attacks, or thrown objects.
    * Resistance equal to Size in both Physical & Energy
  * **General Destructible Terrain Rules:** Some terrain leaves effects on destruction; these effects are determined during terrain placement.

### Combat Resolution
  1. Declare Target and Attack.
  2. Attacker flips two cards (A=1, 2=2, 3=3, J=-1, Red Joker = -2, Black Joker = +4) and sums. Adds Attack Skill and attack bonuses. (Total Attack Value)
  3. Defender flips two cards and sums. Adds relevant Resistance and defense bonuses. (Total Defense Value)
  4. If Total Attack Value > Total Defense Value: Hit. Damage = Difference.
  5. If Total Attack Value <= Total Defense Value: Miss.
  6. Apply Damage (reduce Wounds).
  7. Apply Attack Effects.

## Temporary Conditions
The following conditions can be inflicted by attacks and abilities. They can each stack up to 3 times:

* **Slow**
  * Target's movement speed is reduced by 1 (minimum of 1)
  * Lasts until the start of the target's next activation
  * Multiple instances stack

* **Weak**
  * Target's attack strength is reduced by 1
  * Lasts until the start of the target's next activation
  * Multiple instances stack

* **Hindered**
  * Target's defense is reduced by 1
  * Lasts until the start of the target's next activation
  * Multiple instances stack

* **Damage Over Time**
  * Target suffers 1 wound at the end of its activation
  * Multiple instances stack

* **Reduced Resistance (Physical/Energy/Psyche)**
  * Target's specified resistance is reduced by 1
  * Lasts until the start of the target's next activation
  * Multiple instances stack