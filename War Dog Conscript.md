```ds-statblock
name: War Dog Conscript
ancestry:
- Humanoid
- War Dog
roles:
- Harrier
- Minion
level: 1
ev: 4
stamina: 8
immunities: []
weaknesses: []
speed: '7'
size: 1M
stability: 0
free_strike: 2
might: 1
intuition: 0
agility: 0
reason: 0
presence: 0
traits:
- name: Loyalty Collar
  effect: When the conscript dies, they explode, dealing 1d6 damage to each adjacent
    enemy.
abilities:
- name: Blade
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Charge
  - Melee
  - Ranged
  - Weapon
  distance: Reach 1 or Ranged 5
  target: One creature per minion
  t1: 2 damage
  t2: 3 damage
  t3: 4 damage
  effects:
  - name: Effect
    effect: 'If this ability is used as part of the Charge action, the conscript gains
      an edge on the power roll. '

```
