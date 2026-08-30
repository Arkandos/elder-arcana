*Does not include Tier 0 abilities*
```base
filters:
  and:
    - file.hasTag("ability")
views:
  - type: table
    name: All Abilities
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: tier
        direction: ASC
  - type: table
    name: Tier 1
    filters:
      and:
        - file.hasTag("ability/tier1")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
      - tags
    sort:
      - property: attributes
        direction: ASC
  - type: table
    name: Tier 2
    filters:
      and:
        - file.hasTag("ability/tier2")
    order:
      - file.name
      - tier
      - action
      - cost
      - attributes
      - tags

```
