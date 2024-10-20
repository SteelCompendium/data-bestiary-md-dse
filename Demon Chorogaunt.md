```ds-statblock
name: Demon Chorogaunt
ancestry:
- Demon
- Planar
roles:
- Boss
level: 3
ev: 36
stamina: 90
immunities: []
weaknesses:
- Holy 3
speed: '5'
size: 1M
stability: 2
free_strike: 4
might: 2
intuition: 2
agility: 2
reason: 2
presence: 2
traits:
- name: End Effect
  effect: At the end of their turn, the chorogaunt can take 5 damage to end one EoE
    effect affecting them. This damage can’t be reduced in any way.
- name: Lethe
  effect: While winded, the chorogaunt has an edge on attacks, and attacks have an
    edge against them.
- name: Soulsight
  effect: Each creature within 2 squares of the chorogaunt can’t be hidden from them.
abilities:
- name: Agonizing Harmony
  type: Action
  roll: 2d10 + 2
  cost: Signature
  keywords:
  - Area
  - Weapon
  distance: 5 burst
  target: Each enemy
  t1: 3 psychic damage
  t2: 5 psychic damage; slowed (EoT)
  t3: 7 psychic damage; slowed (INU ends)
  effects:
  - name: Effect
    effect: 'An ally within 10 squares of the chorogaunt can shift up to their speed. '
- name: Chaotic Entrancing Harmony
  type: Maneuver
  keywords:
  - Area
  distance: 10 burst
  target: Each enemy
  effects:
  - name: Effect
    effect: 'Each target slides 3, ignoring their stability. '
- name: I Thrive on Pain
  type: Triggered Action
  cost: 3 VP
  keywords:
  - Magic
  distance: Self
  target: Self
  trigger: The chorogaunt is targeted by an attack.
  effects:
  - name: Effect
    effect: 'Any damage from the attack is halved, and the chorogaunt gains an edge
      on all ability rolls until the end of their next turn. '
- name: Frightening Tones
  type: Villain Action 1
  keywords:
  - Ranged
  distance: Ranged 10
  target: Three enemies
  effects:
  - name: Effect
    effect: 'Each target either takes 5 psychic damage or is frightened of the chorogaunt
      (EoT). Each target gets to choose which to do. '
- name: Bully the Weak
  type: Villain Action 2
  keywords:
  - Magic
  - Ranged
  distance: Ranged 10
  target: One ally
  effects:
  - name: Effect
    effect: 'The chorogaunt kills the target, and each other ally gains an edge on
      attacks until the end of the round. You gain VP equal to the number of heroes. '
- name: Running Cacophony
  type: Villain Action 3
  keywords:
  - Magic
  distance: Self
  target: Self
  effects:
  - name: Effect
    effect: The chorogaunt shifts up to their speed, makes an Agonizing Harmony attack,
      shifts up to their speed, and makes a second Agonizing Harmony attack.

```
