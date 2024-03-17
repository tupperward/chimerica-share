---
statblock: true
name: Dib Halfling-Chewer
extends: Goblin Warrior
statblock: inline
---
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Dib Halfling-Chewer"
level: "Creature -1"
alignment: "CE"
size: "Small"
trait_03: "Goblin"
trait_04: "Humanoid"
modifier: 2
perception:
  - name: "Perception"
    desc: "Perception +2; __darkvision__;"
languages: "Goblin, Common "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +5 (1d20+5); __Athletics__: +2 (1d20+2); __Nature__: +1 (1d20+1); __Stealth__: +5 (1d20+5); "
abilityMods: [0, 3, 1, 0, -1, 1]

abilities_bot:
- name: "Knee-Bar"
  desc: "⬻ Melee [[6. Mechanics/Rules/Actions/grapple|grapple]] attack. +4 to hit. 3 bludgeoning damage. Dib can maintain the knee bar indefinitely, but can take no move actions and is considered prone while doing so."
abilities_mid:
  - name: "Goblin Scuttle"
    desc: "⬲ __Trigger__ A goblin ally ends a move action adjacent to the warrior. __Effect__  The goblin warrior [[Step|Steps]]."
abilities_top:
  - name: Items
    desc: "dogslicer, leather armor, shortbow (10 arrows);"

speed: 25 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +5 (1d20+5); __Ref__: +7 (1d20+7); __Will__: +3 (1d20+3);"
hp: 6
health:
  - name: HP
    desc: "6; "


attacks:
  - name: Melee
    desc: "⬻ dogslicer +8 ([[agile]], [[backstabber]], [[finesse]]); __Damage__ 1d6 (1d6) slashing"
  - name: Ranged
    desc: "⬻ shortbow +8 ([[deadly|deadly 1d10]], [[range increment|range increment 60 feet]], [[reload|reload 0]]); __Damage__ 1d6 (1d6) piercing"

sourcebook: "_Bestiary_, page 180."
```
