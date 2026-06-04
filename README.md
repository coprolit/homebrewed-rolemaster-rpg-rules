# RM lite hack
A homebrewed, heavily streamlined and simplified compilation of Rolemaster RPG (and related systems) rules.



## Combat Actions
Types of combat actions: proactive actions, reactive actions, interupt actions.

### Proactive Action
Action a character can attempt on his Turn.

### Interupt Action
Delayed, conditional Action stated on the characters' turn. 
Upon triggered, Interupt actions halt an opponent’s Turn at any point.
If no change in the tactical situation, the opponent continues the Turn after the character’s is completed.
If unable to achieve the original declaration, the opponent’s MP is wasted.

### Reactive Action
Action a character can attempt at any time during the Combat Round as a response to a Proactive Action (e.g. as an opportunity attack or response to an imminent threat).

A character can defend against a foe when attacked by taking cover and/or making a defensive Action to increase their DB:
Attempt a Percentage Maneuver, add result to DB.

#### Dodge
Against Ranged attacks, halve any DB increase.
Dodging is not possible against area attacks.

Difficulty: `Extremely Hard` (-30).
Use appropiate Movement skill, e.g. `Running`, `Swimming`, `Climbing` or `Acrobatics` skill.

176+ `Absolute Success`: Defender can immediately move up to 10'.

**Example:** Bob has 50 in `Running`. He attempts a 75% (-25) Dodge against an incoming melee attack and rolls 50. 50 (roll) + 50 (skill) - 25 (activity) - 30 (EH maneuver) = 45. Bob adds 40 to DB.

**Example:** Bob has 80 in `Acrobatics`. He attempts a 100% Dodge against an incoming melee attack and rolls 75. 75 (roll) + 80 (skill) - 30 (EH maneuver) = 125. Bob adds = 100 to DB.

#### Parry
Against Melee attacks.
Halve any DB increase, if defender is parrying unarmed against someone with a weapon.

Difficulty: `Extremely Hard` (-30).
Use `Weapon` or `Shield` skill.

176+ `Absolute Success`: Defender can immediately perform a counter-attack against the attacker. That attack cannot be defended against.

#### Block
Against Melee and Ranged attacks if using a suitable object, e.g. shield, or environment cover.

Diificulty: `Hard` Maneuver (-10). Use Shield skill.

176+ `Absolute Success`: Reduce Critical severity by one of any Criticals scored against defender.

## The Combat Round
A combat round is measured as `100%` activity (5 seconds).

During the round, combatants can perform actions up to `100%` activity. Each action cost an amount of `%` to represent the time, effort and concentration required to perform that action.

Actions that require skill checks can be performed more quickly at a penalty of `-1` for each 1% less that the normal cost, down to a minimum of half the normal cost.

| Attack actions | Cost |
|:-|-:|
Ranged Attack | 75%
Thrown Attack | 100%
Melee | 100%
Dodge/Block/Parry | 100%

| Movement actions | Cost
|:-|-:|
Walk / x1 BMR | 25%
Jog / x2 BMR | 50%
Run / x3 BMR | 75%
Sprint / x4 BMR | 100%
Mount | 100%
Dismount | 50%
Prone <-> Stand | 25%

| Other actions | Cost |
|:-|-:|
Perception | 50% |

| Equipment actions | Cost | _ |
|:-|-:|:-|
Draw weapon/ammo/item | 25% |
Draw ammo and load | 25%
Sheath weapon/ammo/item | 50% |
Get item from ground | 75% |
Drop item | 0 |
Shift item to other hand | 25% |
Apply first aid	| 200% |	per hit/round
Pick Lock / Disarm Trap | 500% |

Eat or drink (medicals) | 2 |
Power supply reload	| 8 |
Misc. Static Action	| 8+ |

Orientation Maneuver | 0 | Result is a delay (penalty to initiative): Failure = can perform no actions in round, Partial success = -20, Near success = -10, Success = 0

# Notes
Critical tables replace generic double-damage with specific, unpredictable, narrative-driven outcomes that escalate the severity of wounds: Serious Injuries, Bleeding and Stunning.

A "lite" hack for the notoriously crunchy Rolemaster involves ditching all the weapon tables and percentage-based round trackers. 
Streamline combat by having players roll `1d100 + OB - DB`, resolving damage against a generic difficulty chart, and rolling on just 3 general Critical Tables.

### The Streamlined Mechanic (d100 Resolution)
#### One Roll Does It All:
Instead of a complex matrix, all checks are `1d100 + OB - DB`.

#### Open-Ended Rolls:
Keep the signature open-ended rolls. Any roll of 96+ means you roll again and add it to the total. Rolls of 01–05 mean you roll again and subtract from the total.

#### Combat Math:
`1d100 + OB - DB`. If the total is greater than 100, the attacker scores a hit. The difference between the result and 100 equals the Concussion Damage dealt.

Partial Success (76-100): Target has been knocked off balance (gets some temporary debuff, e.g. staggered, knocked back, knocked prone).
Absolute Succes (176+): double crits

#### Armor Simplified:
Instead of tracking 20 different Armor Types, group them into four distinct tiers:
- None (AT 1): Flat -0 DB
- Light (AT 5): Flat -10 DB
- Medium (AT 10): Flat -20 DB
- Heavy (AT 15–20): Flat -30 DB

Designer Note: Armor subtracts its value directly from damage (Phil: should subtract Critical severity instead). A 30-point hit against Medium Armor becomes a 10-point hit.

#### Combat Flow:
A "declaration phase" usually bogs Rolemaster down. Instead, simplify combat turns:
Players declare how much of their Offensive Bonus (OB) they want to use for parrying. If a player puts \(30\) points into parrying, they add \(30\) to their Defensive Bonus (DB) but lose \(30\) from their attack roll.Roll initiative or act simultaneously.

#### Criticals & Bleeding:
Instead of hundreds of weapon charts, use three basic Critical Hit Tables when an attack causes a critical:
- Slash/Edge: Causes Heavy Bleeding.
- Puncture: Causes Organ Damage/Stuns.
- Concussion/Crush: Causes Knockouts/Stuns.

Draw an "A", "B", "C", "D", or "E" severity critical depending on the attack roll.
_the Mythras approach where critical hits allow characters to choose which combat move(s) to apply to their attack, subsequent to the roll. So they can do extra damage, inflict a number of disadvantages on the enemy, recover from their own disadvantages, etc., according to their own perception of what is most appropriate to the situation._

#### On roll over vs under
https://www.skeletoncodemachine.com/p/roll-over-under
