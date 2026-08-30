
```base
filters:
  and:
    - file.hasTag("powers")
    - '!file.hasTag("ability")'
    - '!file.hasTag("keywords/basic")'
views:
  - type: table
    name: All Powers
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: tier
        direction: ASC
  - type: table
    name: Air
    filters:
      and:
        - file.hasTag("art/air")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Alteration
    filters:
      and:
        - file.hasTag("art/alteration")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Augury
    filters:
      and:
        - file.hasTag("art/augury")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Blood
    filters:
      and:
        - file.hasTag("art/blood")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Body
    filters:
      and:
        - file.hasTag("art/body")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Convoking
    filters:
      and:
        - file.hasTag("art/convoking")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Earth
    filters:
      and:
        - file.hasTag("art/earth")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Esoteric
    filters:
      and:
        - file.hasTag("art/esoteric")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Farsight
    filters:
      and:
        - file.hasTag("art/farsight")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Fire
    filters:
      and:
        - file.hasTag("art/fire")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Force
    filters:
      and:
        - file.hasTag("art/force")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Illusion
    filters:
      and:
        - file.hasTag("art/illusion")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Memory
    filters:
      and:
        - file.hasTag("art/memory")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Mind
    filters:
      and:
        - file.hasTag("art/mind")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Nature
    filters:
      and:
        - file.hasTag("art/nature")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Necromancy
    filters:
      and:
        - file.hasTag("art/necromancy")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Shapeshifting
    filters:
      and:
        - file.hasTag("art/shapeshifting")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Thaumaturgy
    filters:
      and:
        - file.hasTag("art/thaumaturgy")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Warding
    filters:
      and:
        - file.hasTag("art/warding")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC
  - type: table
    name: Water
    filters:
      and:
        - file.hasTag("art/water")
    order:
      - file.name
      - tier
      - art
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: art
        direction: ASC

```
