
```base
filters:
  and:
    - file.hasTag("powers")
    - '!file.hasTag("ability")'
    - '!file.hasTag("keywords/basic")'
views:
  - type: cards
    name: All Powers
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Air
    filters:
      and:
        - file.hasTag("art/air")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Alteration
    filters:
      and:
        - file.hasTag("art/alteration")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
    cardSize: 200
  - type: cards
    name: Augury
    filters:
      and:
        - file.hasTag("art/augury")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Blood
    filters:
      and:
        - file.hasTag("art/blood")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Body
    filters:
      and:
        - file.hasTag("art/body")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Convoking
    filters:
      and:
        - file.hasTag("art/convoking")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Earth
    filters:
      and:
        - file.hasTag("art/earth")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Esoteric
    filters:
      and:
        - file.hasTag("art/esoteric")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Farsight
    filters:
      and:
        - file.hasTag("art/farsight")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Fire
    filters:
      and:
        - file.hasTag("art/fire")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Force
    filters:
      and:
        - file.hasTag("art/force")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Illusion
    filters:
      and:
        - file.hasTag("art/illusion")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Memory
    filters:
      and:
        - file.hasTag("art/memory")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Mind
    filters:
      and:
        - file.hasTag("art/mind")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Nature
    filters:
      and:
        - file.hasTag("art/nature")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Necromancy
    filters:
      and:
        - file.hasTag("art/necromancy")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Shapeshifting
    filters:
      and:
        - file.hasTag("art/shapeshifting")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Thaumaturgy
    filters:
      and:
        - file.hasTag("art/thaumaturgy")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Warding
    filters:
      and:
        - file.hasTag("art/warding")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC
  - type: cards
    name: Water
    filters:
      and:
        - file.hasTag("art/water")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
    sort:
      - property: art
        direction: ASC

```
