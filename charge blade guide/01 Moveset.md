moveset data taken from [mhchargeblade.net](https://www.mhchargeblade.net)
TODO:
motion values
# While sheathed:
A -> Unsheathe weapon
f.A -> Sword: Forward Slash
B -> Axe: Draw Attack

--- 
# Sword: Weak Slash
> [!example]+ Inputs
> > [!example] A (from neutral)
> 
> > [!example]+ A | follow-up from (after):
> > Sword: Sliding Slash
> > Sword: Shield Thrust

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 12  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    3     |    3    |    3    |    4    |

A downward slash from left to right, builds a small amount of phial charge

---
# Sword: Return Stroke
> [!example]+ Inputs
> > [!example]+ A | follow-up from (after):
> > Sword: Weak Slash
> > Sword: Charge Phials
> > Roll (in Sword mode)
> > Climbing a ledge (in Sword mode)


| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 15  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    3     |    3    |    3    |    4    |

An upward slash that hits above your hunter

---

# Sword: Spinning Slash 
> [!example]+ Input
> > [!example]+ A | follow-up from (after):
> > Sword: Return Stroke
> > Sword: Charged Double Slash
> > Sword: Condensed Element Slash
> > Sword: Jumping Slash
> > Side hop
> > Slinger Burst (Sword)

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 30  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    9     |    9    |   10    |   11    |

A spinning strike that hits all around your character. Guard point at the end of the animation, while your character is holding the shield in front of them.

"roundslash"

--- 
# Sword: Forward Slash
> [!example]+ Input
> > [!example] A + B | from neutral
> 
> > [!example] f.A | from sheathed
>  
> > [!example] A OR B | after any Sword attack is deflected

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 20  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    3     |    3    |    3    |    4    |


A running horizontal strike done in the direction of your movement input. Can be used to quickly change movement directions.

---
# Sword: Charged Rising Slash

TODO

---
# Sword: Charged Double Slash
> [!example]+ Input
> > [!example] \[B] | from neutral (in Sword mode)
> 
> > [!example]+ \[B] | follow-up from (after):
> > any Sword attack except Sword: Charged Double Slash

First hit:

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 27  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    18    |   19    |   20    |   22    |
Second hit:

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 18  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    9     |    9    |   10    |   11    |

Builds a considerable amount of phial energy

--- 
# Sword: Charge Phials (Reload)
> [!example]+ Inputs
> > [!example] B + C | from neutral (in Sword mode)
> 
> > [!example]+ B + C | follow-up from (after):
> > any Sword action except Sword: Charge Phials

Stores the phial energy (heat) into the phials. Yellow heat gives 3 phials, red heat fully fills the phials. Overheat acts as red heat.

--- 
# Sword: Shield Thrust
> [!example]+ Input
> > [!example]+ A + B | follow-up from:
> > Sword: Charge Phials
> > any Sword attack except Sword: Shield Thrust

First hit:

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 12  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    1     |    1    |    1    |    1    |
Second hit:

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 8   |      |         |       | 1.00 | 1.00    | 1.00   |

When Shield is charged, does light phial explosions. Only builds charge when shield is not charged.

---
# Sword: Condensed Element Slash
> [!example]+ Input
> > [!example]+ \[A] | follow-up from (after):
> > Sword: Charge Phials

| Damage Type | MV  | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | --- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 60  |      |         |       | 1.00 | 1.00    | 1.00   |

|              | No Focus | Focus 1 | Focus 2 | Focus 3 |
| ------------ | :------: | :-----: | :-----: | :-----: |
| Charge Build |    9     |    9    |   10    |   11    |
Charges your sword. When your sword is charged, prevents overheating and gives sword attacks Mind's Eye property (cannot be deflected).

--- 
# Sword: Morph Slash
> [!example]+ Input
> > [!example] C + A | from neutral (in Sword mode)
> 
> > [!example]+ C + A | follow-up from (after):
> > any sword attack
> > Sword: Block reaction (small or medium knockback)

Type: Severing
MV: 50
Charge: 0

Morphs into Axe mode. Has a Guard Point at the beginning of the animation when the shield is visually in front of the Hunter.

--- 
# Axe: Draw Attack
> [!example]+ Input
> > [!example] C | from sheathed

Type: Severing
MV: 50
Charge: 0

functionally the same as Sword: Morph Slash, Guard Point and all

--- 
# Axe: Amped Element Discharge (AED)
> [!example]+ Input
> > [!example] A + B | from neutral (Axe mode)
> 
> > [!example]+ A + B | follow-up from (after):
> > Sword: Shield Thrust
> > Sword: Morph Slash
> > Sword: Block reaction (small or medium knockback)
> > Axe: Draw Attack
> > Axe: Overhead Slash
> > Axe: Dash Slash
> > Axe: Jumping Slash
> 
> > [!example] b.A | during Axe: Super Amped Element Discharge
> 
> > [!example]+ B | follow-up from (after):
> > Axe: Element Discharge II

Type: Severing
MV: 82
Charge: 0

- FINISH LATER
- does phial explosion
- ends in sword mode

---
# Axe: Super Amped Element Discharge (SAED)
> [!example]+ Inputs
> > [!example] A + B | shield is charged, from neutral (Axe mode)
> 
> > [!example]+ A + B | shield is charged, follow-up from (after):
> > Sword: Shield Thrust
> > Sword: Morph Slash
> > Sword: Block reaction (small or medium knockback)
> > Axe: Draw Attack
> > Axe: Overhead Slash
> > Axe: Dash Slash
> > Axe: Jumping Slash
> 
> > [!example]+ B | shield is charged, follow-up from (after):
> > Axe: Element Discharge II

| Damage Type | MV       | Stun | Exhaust | Mount | Part | Element | Status |
| ----------- | -------- | ---- | ------- | ----- | ---- | ------- | ------ |
| Severing    | 15,82,66 |      |         |       | 1.00 | 1.00    | 1.00   |

Powered up version of Axe: Amped Element Discharge which uses all of your phials, has longer range, and does more damage.

Phial explosion where axe hits on ground.

---
# Elemental Roundslash
> [!example]+ Inputs
> > [!example] C | During Axe: (Super) Amped Element Discharge

Type: Severing
MV: 30
Charge: 9 / 9 / 10 / 11

Charged shield using available stored phials. Every phial gets consumed, and adds 30s to the shield charge timer per phial. Guard point at end of animation, when shield is visibly in front of your Hunter.

Ends in Sword mode.

---
# Axe: Savage Axe Slash
> [!example]+ Inputs
> > [!example] D | During Axe: (Super) Amped Element Discharge

TODO

If phials are available, Axe becomes "chainsaw mode" or "savage axe mode"