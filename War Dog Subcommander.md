~~~ds-statblock
name: War Dog Subcommander
ancestry:
- Humanoid
- War Dog
roles:
- Support
level: 2
ev: 12
stamina: 25
immunities: []
weaknesses: []
speed: '5'
size: 1M
stability: 0
free_strike: 3
might: ''
intuition: ''
agility: ''
reason: ''
presence: ''
traits:
- name: The Iron Saint Does Not Recognize Retreat
  effect: Each ally within 5 squares of the subcommander adds 3 to their stability.
- name: Loyalty Collar
  effect: When the subcommander dies, they explode, dealing 1d6 damage to each adjacent
    enemy.
abilities:
- name: Command Saber
  type: Action
  roll: 2d10 + 1
  cost: Signature
  t1: 3 damage
  t2: 5 damage
  t3: 7 damage
  effects:
  - name: '**Keywords**'
    effect: Attack, Melee, Weapon
  - name: '**Distance**'
    effect: Reach 1
  - name: '**Target**'
    effect: 'One creature or object '
  - name: '**Effect**'
    effect: 'One ally of the subcommander within 5 squares of them can make a free
      strike against the target. '
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