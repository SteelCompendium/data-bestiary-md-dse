~~~ds-statblock
name: Time Raider Archon
ancestry:
- Humanoid
- Time Raider
roles:
- Harrier
- Minion
level: 3
ev: 8
stamina: 15
immunities:
- Psychic 3
weaknesses: []
speed: '7'
size: 1M
stability: 0
free_strike: 2
might: ''
intuition: ''
agility: ''
reason: ''
presence: ''
traits:
- name: Foresight
  effect: The archon doesn’t take a bane on attacks against concealed creatures.
abilities:
- name: Brutal Flail
  type: Action
  roll: 2d10 + 2
  cost: Signature
  t1: 2 damage
  t2: 4 damage
  t3: '5 damage; dazed (EoT) '
  effects:
  - name: '**Keywords**'
    effect: Attack, Melee, Psionic, Weapon
  - name: '**Distance**'
    effect: Reach 1
  - name: '**Target**'
    effect: 'One creature or object per minion '

~~~