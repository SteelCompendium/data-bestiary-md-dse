~~~ds-statblock
name: War Dog Commando
ancestry:
- Humanoid
- War Dog
roles:
- Ambusher
- Minion
level: 1
ev: 5
stamina: 8
immunities: []
weaknesses: []
speed: '5'
size: 1M
stability: 0
free_strike: 2
might: ''
intuition: ''
agility: ''
reason: ''
presence: ''
traits:
- name: Loyalty Collar
  effect: When the commando dies, they explode, dealing 1d6 damage to each adjacent
    enemy.
abilities:
- name: Daggers
  type: Action
  roll: 2d10 + 1
  cost: Signature
  t1: 2 damage
  t2: 4 damage
  t3: 5 damage
  effects:
  - name: '**Keywords**'
    effect: Attack, Melee, Ranged, Weapon
  - name: '**Distance**'
    effect: Reach 1 or Ranged 5
  - name: '**Target**'
    effect: 'One creature per minion '
  - name: '**Effect**'
    effect: 'The commando can use the Hide maneuver, even if observed. '

~~~