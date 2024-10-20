```ds-statblock
name: Human Brawler
ancestry:
- Human
- Humanoid
roles:
- Brute
level: 1
ev: 16
stamina: 40
immunities:
- Magic 2
- Psionic 2
weaknesses: []
speed: '5'
size: 1M
stability: 0
free_strike: 4
might: 1
intuition: 0
agility: 0
reason: 0
presence: 0
traits:
- name: Shoot the Hostage
  effect: The brawler takes half damage from attacks if they have an enemy grabbed.
    They then apply the remaining damage to the grabbed enemy.
abilities:
- name: Haymaker
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
  t1: 4 damage
  t2: 7 damage; grabbed
  t3: 10 damage; grabbed
  effects:
  - name: Effect
    effect: 'The target takes a bane on attempts to escape the grab, and the brawler
      gains an edge on attacks against the grabbed target. '
- name: Throw
  type: Maneuver
  cost: 1 VP
  keywords:
  - Melee
  distance: Reach 1
  target: One creature grabbed by the brawler
  effects:
  - name: Effect
    effect: 'The brawler pushes the creature they have grabbed 5 squares. This breaks
      the grab. '

```
