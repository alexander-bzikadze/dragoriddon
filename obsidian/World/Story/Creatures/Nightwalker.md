```statblock
name: Nightwalker
size: Huge
type: Undead
alignment: Chaotic Evil
ac: 14
hp: 297
hit_dice: 22d12+154
speed: 40 ft., fly 80 ft.
stats: [22, 19, 24, 6, 9, 8]
saves:
  - constitution: 13
damage_resistances: Acid, Cold, Fire, Lightning, Thunder, Bludgeoning, Piercing, and Slashing from non-magical attacks
damage_immunities: Necrotic, Poison
condition_immunities: Exhaustion, Frightened, Grapple, Paralyzed, Petrified, Poisoned, Prone, Restrained
senses: Darkvision 120ft., Passive Perception 9
cr: 20
traits:
  - name: Annihilating Aura
    desc: Any creature ending its turn within 30ft. of the Nightwalker must make a DC 21 Constitution saving throw, taking 4d6 necrotic damage on a failed save. Furthermore, the Nightwalker has advantage on attack rolls against the creature until the start of its next turn. Undead creatures are immune.
  - name: Life Eater
    desc: If a creature is reduced to 0 hit points by the Nightwalker, it dies instantly and can only be revived using a wish spell.
actions:
  - name: Multiattack
    desc: The Nightwalker makes two attacks, either two with its Enervating Focus or one with Enervating Focus and one with Finger of Doom.
  - name: Enervating Focus
    desc: "Melee Weapon Attack: +12 to hit, reach 15ft., one target. Hit: 28 (5d8+6) necrotic damage. The target must succeed on a DC 21 Constitution saving throw or its hit point maximum is reduced by the damage taken, lasting until the target finishes a long rest or benefits from a Greater Restoration spell."
    attack_bonus: 12
  - name: Finger of Doom (Recharge 6)
    desc: "Ranged Spell Attack: 300ft., one target. The target must succeed on a DC 21 Wisdom saving throw or take 26 (4d12) necrotic damage and become frightened and paralyzed until the end of the Nightwalker's next turn. If the saving throw is successful or the effect ends for the target, it is immune to the Nightwalker's Finger of Doom for the next 24 hours."
```
