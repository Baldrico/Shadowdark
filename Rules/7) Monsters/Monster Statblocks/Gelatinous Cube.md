---
alias: 
---

```statblock
name: Gelatinous Cube
layout: Shadowdark Monster
image: [[Gelatinous Cube.png]]
description: A translucent cube of slime that silently mows through tunnels.
ac: 11
hp: 24
actions:
  - name: Touch x1
    desc: +4 (1d8 + toxin + engulf)
mv: near
stats: [+3,+1,+2,-4,+1,-4]
alignment: Neutral
level: 5
traits:
  - name: Engulf
    desc: DC 12 STR or trapped inside cube. Touch attack auto-hits engulfed targets each round. DC 12 STR on turn to escape. Fail checks if paralyzed.
  - name: Rubbery
    desc: Half damage from stabbing weapons.
  - name: Toxin
    desc: DC 15 CON or paralyzed 1d4 rounds.
```