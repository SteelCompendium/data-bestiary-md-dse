~~~ds-statblock
name: War Dog Eviscerite
ancestry:
- Humanoid
- War Dog
roles:
- Harrier
level: 1
ev: 10
stamina: 20
immunities: []
weaknesses: []
speed: '7'
size: 1M
stability: 0
free_strike: 3
might: ''
intuition: ''
agility: ''
reason: ''
presence: ''
traits:
- name: Loyalty Collar
  effect: When the eviscerite dies, they explode, dealing 1d6 damage to each adjacent
    enemy.
abilities:
- name: Chainsaw Whip
  type: Action
  roll: 2d10 + 1
  cost: Signature
  t1: 3 damage
  t2: 5 damage; pull 1
  t3: 7 damage; pull 2
  effects:
  - name: '**Keywords**'
    effect: Attack, Melee, Weapon
  - name: '**Distance**'
    effect: Reach 3
  - name: '**Target**'
    effect: 'One creature or object '
  - name: '**Effect**'
    effect: 'The eviscerite can grab a target pulled adjacent to them by this ability. '
- name: Posthumous Promotion
  type: Maneuver
  effects:
  - name: '**Keywords**'
    effect: Magic, Ranged
  - name: '**Distance**'
    effect: Ranged 10
  - name: '**Target**'
    effect: One war dog with a loyalty collar
  - name: '**Effect**'
    effect: 'The target’s loyalty collar detonates, killing them instantly. '

~~~