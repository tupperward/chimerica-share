---
statblock: inline
extends: Fungus-Leshy
aliases:
  - Myconid
---

```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Myconid"
level: "Creature 1"
alignment: "N"
size: "Small"
trait_03: "Fungus"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __darkvision__;"
languages: "Common, Druidic, Sylvan;  speak with plants (fungi only);"
skills:
  - name: "Skills"
    desc: "__Athletics__: +6 (1d20+6); __Nature__: +6 (1d20+6); __Stealth__: +8 (1d20+8); "
abilityMods: [2, 4, 2, -1, 2, 0]

abilities_mid:
  - name: "Verdant Burst"
    desc: " ([[healing]]);  When a myconid dies it releases a burst of healing spores that heal nearby fungus. Fungus in a 30ft diameter regain 2d8 (2d8) Hit Points, and the area sprouts fungi that make it difficult terrain."
abilities_bot:
  - name: "Spore Cloud"
    desc: "⬺ ([[poison]]);  A myconid can unleash a cloud of spores that irritates the eyes and throats of non-fungi creatures in a 15-foot emanation. Each creature must succeed at a DC 12 Fortitude save or take 1 [[conditions#persistent damage|persistent poison damage]]. A creature has its vision reduced as long as the [[conditions#persistent damage|persistent damage]] continues and can see only within 20 feet (or 10 feet, on a critical failure)."
  - name: "Spores"
    desc: "  A creature that takes damage from a myconid's spore pod [[Strike]] must attempt a saving throw with the same DC and effect as its Spore Cloud ability."

speed: 25 feet

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +6 (1d20+6); __Ref__: +8 (1d20+8); __Will__: +4 (1d20+4);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ fist +8 ([[agile]], [[finesse]]); __Damage__ 1d6 (1d6) bludgeoning"
  - name: Ranged
    desc: "⬻ spore pod +8 ([[range increment|range increment 30 feet]]); __Damage__ 1d6 (1d6) bludgeoning plus spores"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 16; __4th__ [[speak with plants]];"
sourcebook: "_Bestiary_, page 219."
```
