```ds-statblock
name: Goblin Runner
ancestry:
- Goblin
- Humanoid
roles:
- Harrier
- Minion
level: 1
ev: 4
stamina: 8
immunities: []
weaknesses: []
speed: 6 (climb)
size: 1S
stability: 0
free_strike: 2
might: -2
intuition: 0
agility: 1
reason: 0
presence: -1
traits:
- name: Crafty
  effect: The runner doesn’t provoke opportunity attacks by moving.
abilities:
- name: Club
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Charge
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object per minion
  t1: 2 damage
  t2: 3 damage
  t3: '4 damage '

```
