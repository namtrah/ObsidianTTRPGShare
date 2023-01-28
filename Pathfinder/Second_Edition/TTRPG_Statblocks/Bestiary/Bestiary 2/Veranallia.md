---
noteType: pf2eMonster
aliases: "Veranallia"
tags: 
  - pf2e/creature/type/celestial
  - pf2e/creature/level/20
statblock: true
statblock-link: "#Veranallia"
name: "Veranallia"
hp: 475
ac: 45
modifier: 38
level: 20
---
### Veranallia
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B2"
name: "Veranallia"
level: "Creature 20"
alignment: "CG"
size: "Medium"
trait_03: "Azata"
trait_04: "Celestial"
perception:
  - name: "Perception"
    desc: "Perception +38; __darkvision__, __imprecise [[tremorsense]] 120__;"
languages: "Celestial, Draconic, Infernal;  speak with animals, speak with;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +34 (1d20+34); __Deception__: +36 (1d20+36); __Diplomacy__: +38 (1d20+38); __Intimidation__: +36 (1d20+36); __Medicine__: +36 (1d20+36); __Nature__: +34 (1d20+34); __Survival__: +38 (1d20+38); __Elysium lore__: +36 (1d20+36); "
abilityMods: [8, 6, 8, 6, 10, 8]

abilities_bot:
  - name: "Alter Weather"
    desc: "⬽ __Frequency__ three times per day  __Effect__  The veranallia dramatically alters weather patterns in the surrounding area, producing any of the results of a successful 9th-level control weather ritual."
  - name: "Rebirth"
    desc: " ([[divine]], [[necromancy]]); __Frequency__ once per day  __Effect__  The veranallia spends a minute to encase a creature that has been dead for no more than a year in a cocoon. After 24 hours, the creature is restored to life, and the cocoon explodes in a shower of colorful blossoms. If the veranallia's chooses, Rebirth can change the creature's ancestry or heritage, typically into an aasimar."
abilities_top:
  - name: Items
    desc: "+3 greater striking sickle;"

speed: 40 feet, fly 40 feet

ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__: +36 (1d20+36); __Ref__: +34 (1d20+34); __Will__: +38 (1d20+38);"
health:
  - name: HP
    desc: "475;  __Weaknesses__ cold iron 20, evil 20;"


attacks:
  - name: Melee
    desc: "⬻ sickle +39 ([[agile]], [[finesse]], [[trip]]); __Damage__ 1 (3d4+16) slashing plus 1 (4d6) cold and 1 (1d6) good"
  - name: Melee
    desc: "⬻ vine +39 ([[reach|reach 20 feet]]); __Damage__ 1 (4d12+16) bludgeoning plus 1 (1d6) good and [[Improved Grab]]"

spellcasting:
  - name: "Divine Innate Spells"
    desc: "DC 42, attack +32; __6th__ [[baleful polymorph]] (at will), [[tangling creepers]] (at will); __8th__ [[polar ray]] (at will), [[sunburst]] (at will); __9th__ [[nature's enmity]], [[regenerate]] (3), [[storm of vengeance]], [[tree stride]] (at will); __10th__ [[cataclysm]], [[primal phenomenon]] once per year, [[revival]]; __Constant__ __(9th)__ [[endure elements]], [[speak with animals]], [[speak with plants]], [[tongues]];"
sourcebook: "_Bestiary 2_, page 31."
```

### Encounter
```encounter-table
name: Veranallia
creatures:
  - 1: Veranallia
```