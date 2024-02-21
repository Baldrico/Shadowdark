## Aboleth
```statblock
name: Aboleth
layout: Shadowdark Monster
image: [[Aboleth.png]]
description: Enormous, antediluvian catfish covered in slime and tentacles. They hate all intelligent beings.
ac: 16
hp: 39
actions:
  - name: Tentacle x2
    desc: (near) +5 (1d8 + curse)
  - name: Tail x1
    desc: +5 (3d6)
mv: near (swim)
stats: [+4,-1,+3,+4,+2,+2]
alignment: Chaotic
level: 8
traits:
  - name: Curse
    desc: DC 15 CON or target gains a magical curse, turning into a deep one over 2d10 days.
  - name: Enslave
    desc: In place of attacks, one creature within far DC 15 WIS or aboleth controls for 1d4 rounds.
  - name: Telepathic
    desc: Read the thoughts of all creatures within far.
```

## Acolyte
```statblock
name: Acolyte
layout: Shadowdark Monster
image: [[Acolyte.png]]
description: A religious trainee who knows basic rites and rituals.
ac: 12
hp: 4
actions:
  - name: Mace x1
    desc: +1 (1d6)
  - name: Spell x1
    desc: +2,
mv: near 
stats: [+1,-1,+0,-1,+2,+0]
alignment: Lawful
level: 1
spells:
  - name: Healing Touch (WIS Spell)
    desc: DC 11. Heal one creature within close for 1d4 HP.
```

# Angels

Angels are the divine host of lawful and neutral gods. They appear as winged, beautiful humanoids who radiate light and are suffused with their gods' energies and symbols.

Seraphim are the lowest sphere of angel and often walk among mortals. Domini are their lords, and the powerful principi govern over the domini. Above all stand the mighty archangels.


## Angel, Seraph
```statblock
name: Angel, Seraph
layout: Shadowdark Monster
image: [[Angel, Seraph.png]]
description: Beautiful, luminous humanoids with white-feathered wings.
ac: 14 (chainmail)
hp: 14
actions:
  - name: Longsword x2
    desc: +3 (1d8)
mv: near (fly)
stats: [+3,+1,+1,+2,+3,+3]
alignment: Lawful
level: 3
traits:
  - name: Bless 
    desc: 3/day, touch one target to give it a luck token.
```

## Angel, Domini
```statblock
name: Angel, Domini
layout: Shadowdark Monster
image: [[Angel, Domini.png]]
description: Winged, flawless humans glowing with bronze sunlight.
ac: 17 (plate mail + shield)
hp: 42
actions:
  - name: Bastard Sword x3
    desc: +7 (1d8)
  - name: Horn x1
    desc: <see below>
mv: near (fly), 
stats: [+4,+1,+2,+3,+4,+4]
alignment: Lawful
level: 9
traits:
  - name: Horn
    desc: All enemies in near DC 15 CHA or paralyzed 1d4 rounds.
```

## Angel, Principi
```statblock
name: Angel, Principi
layout: Shadowdark Monster
image: [[Angel, Principi.png]]
description: Serene humans sculpted from alabaster. Golden orbs for eyes.
ac: 16 ( +1 plate mail )
hp: 53
actions:
  - name: Silvered Bastard Sword x3
    desc: +9 (1d10)
mv: double near (fly)
stats: [+4,+2,+4,+4,+4,+4]
alignment: Lawful
level: 11
traits:
  - name: Moonlight Aura
    desc: Hostile spells targeting the principi are DC 15. 
  - name: Truesight
    desc: Can see all invisible creatures and objects.
```

## Archangel
```statblock
name: Archangel
layout: Shadowdark Monster
image: [[Archangel.png]]
description: A radiant being with a crown of fire, snowy wings, golden armor, and a blazing greatsword.
ac: 18 (_+3 plate mail_)
hp: 76
actions:
  - name: Flaming Greatsword x3
    desc: +10 (2d12)
mv: double near (fly)
stats: [+5,+2,+4,+4,+5,+5]
alignment: Lawful
level: 16
traits:
  - name: Command
    desc: DC 18 CHA to resist an archangel's command.
  - name: Crown of Fire
    desc: Hostile spells targeting the archangel are extreme (DC 18) to cast.
```

## Ape, Snow
```statblock
name: Ape, Snow
layout: Shadowdark Monster
image:
description: White-haired, carnivorous gorillas that stalk the high mountains and live in caves.
ac: 13
hp: 19
actions:
  - name: Fist x2
    desc: +4 (1d6)
  - name: Rock x1
    desc: (far) +4 (2d6)
mv: near (climb)
stats: [+3,+1,+1,-2,+1,+0]
alignment: Neutral
level: 4
traits:
  - name: Thick Fur
    desc: Cold immune.
```

## Ape
```statblock
name: Ape
layout: Shadowdark Monster
image:
description: Hooting, omnivorous apes that live in trees.
ac: 12
hp: 10
actions:
  - name: Fist x1
    desc: +2 (1d6)
  - name: Rock x1
    desc: (far) +2 (1d4)
mv: near (climb)
stats: [+2,+2,+1,-2,+1,+0]
alignment: Neutral
level: 2
```

## Ankheg
```statblock
name: Ankheg
layout: Shadowdark Monster
image:
description: Horse-sized, rust-brown insects. They burrow vast, underground warrens into the bedrock.
ac: 14
hp: 14
actions:
  - name: Bite x1
    desc: +4 (1d6)
  - name: Acid Spray x1
    desc: (near) +4 (2d6)
mv: near (burrow)
stats: [+2,+2,+1,-2,+1,-2]
alignment: Neutral
level: 3
```

## Animated Armor
```statblock
name: Animated Armor
layout: Shadowdark Monster
image: [[Animated Armor.png]]
description: An old suit of armor magically animated by a vengeful spirit.
ac: 15
hp: 11
actions:
  - name: Longsword x1
    desc: +3 (1d8)
mv: near
stats: [+3,-1,+2,-1,+1,+0]
alignment: Chaotic
level: 2
traits:
  - name: Statue
    desc: When standing still, looks exactly like a suit of armor.
```

## Apprentice
```statblock
name: Apprentice
layout: Shadowdark Monster
image:
description: A cloaked magician with a thin, freshly bound spellbook.
ac: 11
hp: 3
actions:
  - name: Dagger x1
    desc: (close/near) +1 (1d4)
  - name: Spell x1
    desc: +2,
mv: near
stats: [-1,+1,-1,+2,+0,+0]
alignment: Neutral
level: 1
spells:
  - name: Beguile (INT Spell)
    desc: DC 11. Focus. One target in near of LV 2 or less is stupefied for the duration.
  - name: Magic Bolt (INT Spell)
    desc: DC 11. 1d4 damage to one target within far.
```

## Archmage
```statblock
name: Archmage
layout: Shadowdark Monster
image:
description: A wizened magic-user crackling with arcane power.
ac: 12
hp: 44
actions:
  - name: Spell x2
    desc: +7,
mv: near
stats: [-1,+2,-1,+4,+2,+1]
alignment: Lawful
level: 10
spells:
  - name: Death Bolt (INT Spell)
    desc: DC 15. One target of LV 9 or less within near DC 15 CON or go to 0 HP.
  - name: Enervate (INT Spell)
    desc: DC 14. Focus. One target within near is stupefied for the duration.
  - name: Fireblast (INT Spell)
    desc: DC 14. 4d6 damage to all within a near-sized cube within far.
  - name: Float (INT Spell)
    desc: Self. DC 14. Fly double near for 5 rounds.
  - name: Mithralskin (INT Spell)
    desc: Self. DC 14. AC becomes 18 for 5 rounds.
  - name: Void Step (INT Spell)
    desc: Self and up to 4 willing targets. DC 15. Teleport up to 100 miles.
```

## Assassin
```statblock
name: Assassin
layout: Shadowdark Monster
image:
description: A black-cloaked, skulking killer.
ac: 15 (leather)
hp: 38
actions:
  - name: Poisoned Dagger x2
    desc: (close/near) +6 (2d4)
mv: near (climb)
stats: [+2,+4,+2,+2,+3,+3]
alignment: Chaotic
level: 8
traits:
  - name: Execute
    desc: Deals x3 damage against surprised targets.
```

## Azer
```statblock
name: Azer
layout: Shadowdark Monster
image:
description: Dwarves with bronze, metallic skin and flames in place of hair. Gifted blacksmiths.
ac: 15
hp: 15
actions:
  - name: Flaming Warhammer x2
    desc: +3 (1d10, ignites flammables)
  - name: Crossbow x1
    desc: (far) +0 (1d6)
mv: near
stats: [+3,+0,+2,+0,+0,+0]
alignment: Lawful
level: 3
traits:
  - name: Impervious
    desc: Fire immune.
```

## Badger
```statblock
name: Badger
layout: Shadowdark Monster
image:
description: Fierce, clawed burrowers with black-and-white face stripes.
ac: 11
hp: 5
actions:
  - name: Claw x2
    desc: +2 (1d4)
mv: near (burrow)
stats: [+2,+0,+1,-3,+1,-2]
alignment: Neutral
level: 1
traits:
  - name: Rage
    desc: 1/day, immune to morale checks,+1d4 damage (3 rounds).
```

## Bandit
```statblock
name: Bandit
layout: Shadowdark Monster
image: [[Bandit.png]]
description: Hard-bitten rogue in tattered leathers and a hooded cloak.
ac: 13 (leather + shield)
hp: 4
actions:
  - name: Club x1
    desc: +1 (1d4)
  - name: Shortbow x1
    desc: (far) +0 (1d4)
mv: near
stats: [+1,+0,+0,-1,+0,-1]
alignment: Chaotic
level: 1
traits:
  - name: Ambush
    desc: Deal an extra die of damage when undetected.
```

## Basilisk
```statblock
name: Basilisk
layout: Shadowdark Monster
image:
description: Massive, muscled lizards with six legs and gray, tough hide.
ac: 14
hp: 25
actions:
  - name: Bite x2
    desc: +4 (2d6 + petrify)
mv: near
stats: [+3,+1,+3,-3,+1,-3]
alignment: Neutral
level: 5
traits:
  - name: Petrify
    desc: Any creature that touches the basilisk or meets its gaze, DC 15 CON or petrified.
```

## Bat, Giant
```statblock
name: Bat, Giant
layout: Shadowdark Monster
image: [[Bat, Giant.png]]
description: Leathery, eagle-sized mammal with a taste for flesh.
ac: 12
hp: 9
actions:
  - name: Bite x1
    desc: +2 (1d6)
mv: near (fly)
stats: [-1,+2,+0,-3,+1,-3]
alignment: Neutral
level: 2
```

## Bat, Swarm
```statblock
name: Bat, Swarm
layout: Shadowdark Monster
image:
description: A whirling cloud of screeching, bloodthirsty bats.
ac: 12
hp: 18
actions:
  - name: Bite x3
    desc: +2 (1d6)
mv: near (fly)
stats: [-3,+2,+0,-3,+1,-3]
alignment: Neutral
level: 4
```

## Bear, Brown
```statblock
name: Bear, Brown
layout: Shadowdark Monster
image: [[Bear, Brown.png]]
description: A hulking, swaying brute with claws as long as a finger.
ac: 13
hp: 25
actions:
  - name: Claw x2
    desc: +4 (1d8)
mv: near (climb) 
stats: [+4,+1,+3,-2,+1,-2]
alignment: Neutral
level: 5
traits:
  - name: Crush
    desc: Deals an extra die of damage if it hits the same target with both claws.
```

## Bear, Polar
```statblock
name: Bear, Polar
layout: Shadowdark Monster
image:
description: A mighty, white bear that thrives in arctic environments.
ac: 13
hp: 34
actions:
  - name: Claw x2
    desc: +6 (2d6)
mv: near (climb)
stats: [+4,+1,+3,-2,+1,-2]
alignment: Neutral
level: 7
traits:
  - name: Crush
    desc: Deals an extra die of damage if it hits the same target with both claws.
  - name: Thick Fur
    desc: Cold immune.
```

## Beastman
```statblock
name: Beastman
layout: Shadowdark Monster
image: [[Beastman.png]]
description: A cave hominid with scraggly fur and a stone-tipped spear.
ac: 12 (leather)
hp: 5
actions:
  - name: Spear x1
    desc: (close/near) +2 (1d6 + 1)
mv: near
stats: [+2,+1,+1,-2,+1,-1]
alignment: Chaotic
level: 1
traits:
  - name: Brutal
    desc: +1 damage with melee weapons (included).
```

## Berserker
```statblock
name: Berserker
layout: Shadowdark Monster
image:
description: Howling, battleraging warriors.
ac: 12 (leather)
hp: 10
actions:
  - name: Greataxe x1
    desc: +2 (1d10)
  - name: Spear x1
    desc: (close/near) +2 (1d6)
mv: near
stats: [+2,+1,+1,+0,+1,+0]
alignment: Neutral
level: 2
traits:
  - name: Rage
    desc: 1/day, immune to morale checks,+1d4 damage (3 rounds).
```

## Boar
```statblock
name: Boar
layout: Shadowdark Monster
image: [[Boar.png]]
description: Ornery wild pig with bristly, russet hair and yellowed tusks.
ac: 12
hp: 14
actions:
  - name: Tusk x2
    desc: +3 (1d6)
mv: near
stats: [+3,+0,+1,-2,+1,-2]
alignment: Neutral
level: 3
traits:
  - name: Gore
    desc: Deals an extra die of damage if it hits the same target with both tusks.
```

## Black Pudding
```statblock
name: Black Pudding
layout: Shadowdark Monster
image:
description: A black, ice-cold mass of sludge.
ac: 9
hp: 30
actions:
  - name: Tentacle x3
    desc: +4 (2d6)
mv: near (climb)
stats: [+2,-1,+3,-4,-3,-4]
alignment: Neutral
level: 6
traits:
  - name: Impervious
    desc: Only damaged by fire.
  - name: Corrosive
    desc: Wood or metal that touches the ooze dissolves on a d6 roll of 1-3.
```

## Brain Eater
```statblock
name: Brain Eater
layout: Shadowdark Monster
image:
description: Purple, gaunt humanoids with squidlike heads and four face tentacles. They live in complex, alien societies underground and eat humanoid brains.
ac: 14 (leather)
hp: 36
actions:
  - name: Tentacle x4
    desc: +5 (1d8 + latch)
  - name: Mind Blast x1
    desc: OR Mind Control x1
mv: near
stats: [+2,+3,+0,+4,+2,+4]
alignment: Chaotic
level: 8
traits:
  - name: Hear Thoughts
    desc: Can hear the surface thoughts of all intelligent creatures within near.
  - name: Latch
    desc: Tentacles attach to hit targets, automatically hitting the next round (DC 12 STR on turn to remove 1d4 tentacles). If all four remain latched onto the same humanoid target for 1 round, the target's brain is ripped out and devoured.
  - name: Mind Blast
    desc: Fills a near-sized cube extending from brain eater. DC 15 INT or 3d6 damage and paralyzed 1d4 rounds.
  - name: Mind Control
    desc: One target in near DC 15 CHA or brain eater controls for 1d4 rounds.
```

## Bugbear
```statblock
name: Bugbear
layout: Shadowdark Monster
image:
description: Brutish, bat-eared goblinoids covered in brown fur.
ac: 13 (leather + shield), 
hp: 14
actions:
  - name: Spiked Mace x2
    desc: +3 (1d6)
mv: near
stats: [+3,+0,+1,-1,+0,-2]
alignment: Chaotic
level: 3
traits:
  - name: Stealthy
    desc: ADV on checks to sneak and hide.
```

## Bulette
```statblock
name: Bulette
layout: Shadowdark Monster
image:
description: A hulking, shark-sized lizard with a steely, arrow-shaped carapace and a massive gullet.
ac: 17
hp: 40
actions:
  - name: Bite x3
    desc: +5 (2d6)
  - name: Leap x1
    desc: <see below>
mv: near (burrow)
stats: [+5,+1,+4,-3,+1,-2]
alignment: Neutral
level: 8
traits:
  - name: Leap
    desc: Jump up to near in height and double near in distance, then make 2 bite attacks.
```

## Camel
```statblock
name: Camel
layout: Shadowdark Monster
image:
description: Ornery, tan-furred desert beasts.
ac: 10
hp: 12
actions:
  - name: Hoof x1
    desc: +3 (1d6)
  - name: Spit x1
    desc: (near) +0 (1d4)
mv: double near
stats: [+3,+0,+3,-2,+1,-3]
alignment: Neutral
level: 2
```

## Cave Brute
```statblock
name: Cave Brute
layout: Shadowdark Monster
image: [[Cave Beast.png]]
description: A hulking, insectoid beast with long mandibles, four eyes, and thick arms covered in bristles.
ac: 14
hp: 28
actions:
  - name: Claw x2
    desc: +5 (1d8)
  - name: Mandible x1
    desc: +5 (1d10)
mv: near (burrow)
stats: [+4,+1,+1,-3,+1,-3]
alignment: Neutral
level: 6
traits:
  - name: Bewilder
    desc: Creatures within near that see the cave brute's eyes, DC 12 CHA at start of their turn or dazed and no action.
```

## Cave Creeper
```statblock
name: Cave Creeper
layout: Shadowdark Monster
image: [[Cave Creeper.png]]
description: Chittering, green centipedes the size of horses. Their grasping tentacles are coated in a paralytic venom.
ac: 12
hp: 18
actions:
  - name: Bite x1
    desc: +3 (1d6)
  - name: Tentacles x1
    desc: +3 (1d8 + toxin)
mv: near (climb)
stats: [+2,+2,+0,-3,+1,-3]
alignment: Neutral
level: 4
traits:
  - name: Toxin
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Centaur
```statblock
name: Centaur
layout: Shadowdark Monster
image:
description: Herd-dwelling beings with the upper body of a human and lower body of a horse.
ac: 12 (leather)
hp: 14
actions:
  - name: Spear x2
    desc: (close/near) +2 (1d6)
  - name: Longbow x1
    desc: (far) +1 (1d8)
mv: double near
stats: [+2,+1,+1,+0,+2,+1]
alignment: Neutral
level: 3
```

## Centipede, Giant
```statblock
name: Centipede, Giant
layout: Shadowdark Monster
image:
description: Blood-red, feathery centipedes the size of a human arm. Their bite injects a burning poison that cramps muscles.
ac: 11
hp: 4
actions:
  - name: Bite x1
    desc: +1 (1d4 + poison)
mv: near (climb)
stats: [-3,+1,+0,-4,-3,-4]
alignment: Neutral
level: 1
traits:
  - name: Poison
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Centipede, Swarm
```statblock
name: Centipede, Swarm
layout: Shadowdark Monster
image:
description: A crawling mass of weaving, sinuous centipedes.
ac: 11
hp: 18
actions:
  - name: Bite x3
    desc: +1 (1d4 + poison)
mv: near (climb)
stats: [-3,+1,+0,-4,-3,-4]
alignment: Neutral
level: 4
traits:
  - name: Poison
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Chimera
```statblock
name: Chimera
layout: Shadowdark Monster
image:
description: A monstrous beast with a half-goat, half-lion body, wide dragon wings, and the heads of a goat, lion, and dragon.
ac: 16
hp: 49
actions:
  - name: Rend x4
    desc: +7 (2d8)
  - name: Fire Breath x1
    desc: <see below>
mv: double near (fly)
stats: [+5,+4,+4,-3,+2,-1]
alignment: Chaotic
level: 10
traits:
  - name: Fire Breath
    desc: Fills a near-sized cube extending from chimera. DC 15 DEX or 4d6 damage.
```

## Chuul
```statblock
name: Chuul
layout: Shadowdark Monster
image:
description: Brown, horse-sized lobster bugs with tentacles and pincers.
ac: 15
hp: 25
actions:
  - name: Pincer x2
    desc: +4 (1d8 + grab)
mv: near (swim)
stats: [+3, D -1,+3,-1,+1,-2]
alignment: Chaotic
level: 5
traits:
  - name: Grab
    desc: DC 15 STR or held in pincer. DC 15 STR on turn to break free.
```

## Cloaker
```statblock
name: Cloaker
layout: Shadowdark Monster
image:
description: A midnight blue manta ray with a bony tail and crescent-shaped maw above its belly. It swoops through deep, lightless caverns.
ac: 13
hp: 28
actions:
  - name: Lash x3
    desc: +4 (1d8)
  - name: Screech x1
    desc: <see below>
mv: near (fly)
stats: [+2,+3,+1,+1,+1,+0]
alignment: Chaotic
level: 6
traits:
  - name: Phantoms
    desc: 1/day, in place of attacks. Create 3 illusory duplicates that disappear when hit. Determine randomly if an attack hits cloaker or illusions.
  - name: Screech
    desc: Enemies within double near DC 15 WIS or DISADV on attacks and checks 1d4 rounds.
```

## Cockatrice
```statblock
name: Cockatrice
layout: Shadowdark Monster
image:
description: A molting, lizard-chicken hybrid with a crimson, razorlike crest.
ac: 11
hp: 14
actions:
  - name: Bite x1
    desc: +1 (1d4 + petrify)
mv: near (fly)
stats: [-2,+1,+1,-3,+1,-3]
alignment: Neutral
level: 3
traits:
  - name: Petrify
    desc: DC 12 CON or petrified.
```

## Couatl
```statblock
name: Couatl
layout: Shadowdark Monster
image:
description: A human-sized snake with scales made of jewels and a corona of iridescent feathers.
ac: 16
hp: 42
actions:
  - name: Bite x3
    desc: +6 (2d6 + poison)
mv: near (fly)
stats: [+2,+3,+2,+4,+4,+5]
alignment: Lawful
level: 9
traits:
  - name: Change Shape
    desc: In place of attacks, transform into any similarly-sized creature.
  - name: Poison
    desc: DC 15 CON or fall into natural, deep sleep for 1d8 hours.
  - name: Restore
    desc: In place of attacks, touch one creature to remove a curse, affliction, or heal 3d8 HP.
```

## Crab, Giant
```statblock
name: Crab, Giant
layout: Shadowdark Monster
image:
description: A wagon-sized, armored crab with two crushing pincers.
ac: 15
hp: 24
actions:
  - name: Pincer x2
    desc: +4 (1d8 + crush)
mv: near (swim)
stats: [+3,+0,+2,-3,+0,-3]
alignment: Neutral
level: 5
traits:
  - name: Crush
    desc: DC 15 STR or target takes 1d8 damage.
```

## Crocodile
```statblock
name: Crocodile
layout: Shadowdark Monster
image: [[Crocodile.png]]
description: Fat, scaly reptiles with stumpy legs and long, thrashing tails.
ac: 14
hp: 20
actions:
  - name: Bite x2
    desc: +3 (1d8)
mv: near (swim)
stats: [+3,+1,+2,-2,+1,-2]
alignment: Neutral
level: 4
```

## Cultist
```statblock
name: Cultist
layout: Shadowdark Monster
image: [[Cultist.png]]
description: A cloaked, wild-eyed zealot chanting the guttural prayers of a dark god.
ac: 14 (chainmail + shield)
hp: 9
actions:
  - name: Longsword x1
    desc: +1 (1d8)
  - name: Cast Spell x1
    desc: +2,
mv: near
stats: [+1,-1,+0,-1,+2,+0]
alignment: Chaotic
level: 2
traits:
  - name: Fearless
    desc: Immune to morale checks.
spells:
  - name: Deathtouch (WIS Spell)
    desc: DC 12. 2d4 damage to one creature within close.
```

## Cyclops
```statblock
name: Cyclops
layout: Shadowdark Monster
image:
description: Reclusive, one-eyed giants towering 20' high. They live simply on remote farmlands.
ac: 11 (leather)
hp: 38
actions:
  - name: Greatclub x2
    desc: +7 (2d8)
  - name: Rock x1
    desc: (far) +5 (1d12)
mv: double near
stats: [+5,+0,+2,-1,-2,+0]
alignment: Chaotic
level: 8
```

## Darkmantle
```statblock
name: Darkmantle
layout: Shadowdark Monster
image: [[Darkmantle.png]]
description: A floating, black octopus with rows of red eyes and a webbed skirt of tentacles.
ac: 13
hp: 4
actions:
  - name: Bite x1
    desc: +3 (1d4)
  - name: Darkness x1
    desc: <see below>
mv: near (fly)
stats: [-2,+3,+0,-3,+0,-3]
alignment: Neutral
level: 1
traits:
  - name: Darkness
    desc: Extinguish all light sources in near.
```

## Deep One
```statblock
name: Deep One
layout: Shadowdark Monster
image:
description: Cultish, amphibious fish-people with bulbous eyes. They lurk in deep water and sunless caverns.
ac: 13
hp: 10
actions:
  - name: Spear x2
    desc: (close/near) +2 (1d6)
mv: near (swim)
stats: [+2,+1,+1,-2,+0,-2]
alignment: Chaotic
level: 2
traits:
  - name: Sunblind
    desc: Blinded in bright light.
```

# Demons

Demons are Chaos incarnate, born from the violent roil and madness of the Dark Realms. They watch from the liminal space between worlds, hoping to find a way into the Light Realms to wreak destruction.

Most demons are utterly unique in their powers and can take any form. However, some lesser demons share a common appearance and set of abilities. The most recognized of these lesser demons are listed here.


## Demon, Balor
```statblock
name: Demon, Balor
layout: Shadowdark Monster
image:
description: Colossal, horned bat-beasts wreathed in the flames of hell itself. Their mighty swords and cracking whips of fire can slice through stone.
ac: 19
hp: 77
actions:
  - name: Greatsword x3
    desc: +10 (2d12 + hellfire)
  - name: Fire Whip x1
    desc: (near) +10 (2d6 + grab)
mv: double near (fly)
stats: [+6,+2,+5,+4,+3,+4]
alignment: Chaotic
level: 16
traits:
  - name: Impervious
    desc: Fire immune. Only damaged by magical sources.
  - name: Grab
    desc: DC 18 STR or target bound in whip. 2d6 damage per round held, DC 18 STR on turn to break free. In place of fire whip attack, balor can fling a grabbed target double near on its turn.
  - name: Hellfire
    desc: DC 18 DEX or 2d8 damage per round until flames extinguished.
```

## Demon, Glabrezu
```statblock
name: Demon, Glabrezu
layout: Shadowdark Monster
image:
description: Horse-headed, fanged creatures who walk upright and have four arms; two shriveled, and two ending in hulking pincers.
ac: 15
hp: 40
actions:
  - name: Pincer x2
    desc: +7 (2d8 + crush)
mv: near
stats: [+4,+1,+4,+3,+2,+2]
alignment: Chaotic
level: 8
traits:
  - name: Crush
    desc: DC 15 STR or target takes 2d8 damage.
```

## Demon, Dretch
```statblock
name: Demon, Dretch
layout: Shadowdark Monster
image:
description: Green, pig-faced demons with thick claws and an oily stench.
ac: 12
hp: 11
actions:
  - name: Claw x1
    desc: +2 (1d6) or 1 gas
mv: near
stats: [+2,+0,+2,-2, W -1,-3]
alignment: Chaotic
level: 2
traits:
  - name: Gas
    desc: All in near DC 12 CON or blinded for 1d4 rounds.
```

## Demon, Marilith
```statblock
name: Demon, Marilith
layout: Shadowdark Monster
image:
description: Hissing, armored women with six limbs and the lower bodies of giant snakes. Six whirling blades flash in their hands.
ac: 17 (plate mail)
hp: 43
actions:
  - name: Longsword x6
    desc: +7 (1d8)
mv: near (climb)
stats: [+5,+4,+3,+3,+3,+4]
alignment: Chaotic
level: 9
traits:
  - name: Parry
    desc: Trade 2 longsword attacks next round to deflect a melee attack that would hit.
```

## Demon, Vrock
```statblock
name: Demon, Vrock
layout: Shadowdark Monster
image:
description: Wagon-sized, filthy vultures with four limbs, midnight-blue skin, and a rash of mangy feathers.
ac: 14
hp: 24
actions:
  - name: Talons x2
    desc: +4 (1d8)
  - name: Screech x1
    desc: <see below>
mv: near (fly)
stats: [+2,+2,+2,-1,+1,+0]
alignment: Chaotic
level: 5
traits:
  - name: Carrion Mist
    desc: Each time vrock is hit, 3:6 chance of carrion mist in near-sized cube centered on vrock. All enemies DC 15 CON or violent vomiting 1d4 rounds.
  - name: Screech
    desc: All enemies in double near DC 12 WIS or DISADV on checks and attacks for 1d4 rounds.
```

# Devils

Devils are the vile reflection of angels, forming the unholy hosts of chaotic gods and sovereign archdevils. Their endless wars rage across the blasted layers of hell, fed by the constant influx of evil souls that turn into devils.


Tiny imps and beautiful cubi secure humanoid souls with promises of power or delight. Barbed and horned devils are hell's cruel soldiers; darkly angelic erinyes are its generals. Wicked archdevils rule over all.


## Archdevil
```statblock
name: Archdevil
layout: Shadowdark Monster
image:
description: A stunningly beautiful, horned human with burning, red eyes and a halo of seven black stars. Two stitched-up gashes weep blood from its shoulder blades.
ac: 19
hp: 76
actions:
  - name: Iron Sceptre x4
    desc: +10 (3d10)
  - name: Soulbind x1
    desc: <see below>
mv: far (teleport)
stats: [+5,+4,+4,+5,+4,+7]
alignment: Chaotic
level: 16
traits:
  - name: Impervious
    desc: Fire immune. Only damaged by magical sources.
  - name: Crown of Darkness
    desc: All hostile spells are reflected at caster with a spellcasting check less than 20.
  - name: Soulbind
    desc: All targets within near DC 20 CHA or fall under control of archdevil for 1d4 rounds. DC 20 CHA on turn to end the effect.
```

## Devil, Barbed
```statblock
name: Devil, Barbed
layout: Shadowdark Monster
image:
description: Lanky, green-mottled fiends bristling with hooked spines.
ac: 13
hp: 14
actions:
  - name: Spine x2
    desc: (near) +3 (1d6 + barb)
  - name: Fire Blast x1
    desc: (far) +3 (1d8)
mv: near
stats: [+2,+3,+1,+1,+1,+1]
alignment: Chaotic
level: 3
traits:
  - name: Barb
    desc: Each spine sticks, dealing 1d4 damage each round. DC 12 STR check on turn to remove.
```

## Devil, Cubi
```statblock
name: Devil, Cubi
layout: Shadowdark Monster
image:
description: Entrancing humanoids with bat wings and devilish charm.
ac: 14
hp: 29
actions:
  - name: Kiss x1
    desc: +4 (1d6 + drain)
  - name: Charm x1
    desc: <see below>
mv: near (fly)
stats: [+2,+4,+2,+3,+2,+5]
alignment: Chaotic
level: 6
traits:
  - name: Change Shape
    desc: In place of attacks, transform into any similarly-sized humanoid.
  - name: Charm
    desc: One humanoid in near DC 15 CHA or bewitched by cubi for 1d6 hours.
  - name: Drain
    desc: The target takes 1d6 WIS damage. A target reduced to 0 WIS this way swears its soul to an archdevil.
```

## Devil, Erinyes
```statblock
name: Devil, Erinyes
layout: Shadowdark Monster
image:
description: Raven-winged, resplendent beings in polished, black armor and helms with curved horns.
ac: 17 ( _+1 plate mail_ )
hp: 43
actions:
  - name: Greatsword x3
    desc: +8 (1d12)
  - name: Longbow x2
    desc: (far) +8 (1d8 + poison)
mv: double near (fly)
stats: [+4,+4,+3,+4,+4,+5]
alignment: Chaotic
level: 9
traits:
  - name: Poison
    desc: DC 15 CON or target's eyes go jet black and it turns on its allies for 1d4 rounds. DC 15 WIS on turn to end effect.
```

## Devil, Horned
```statblock
name: Devil, Horned
layout: Shadowdark Monster
image:
description: Iron-scaled hellions as big as ogres with weighty ram horns, lashing tails, and leathery wings. They are opportunistic and craven in battle.
ac: 16
hp: 35
actions:
  - name: Burning Trident x2
    desc: (near) +7 (2d6)
  - name: Fire Blast x1
    desc: (far) +4 (2d8)
mv: double near (fly)
stats: [+5,+2,+4,+2,+1,+2]
alignment: Chaotic
level: 7
traits:
  - name: Iron Hide
    desc: Half damage from non-magical weapons.
```

## Devil, Imp
```statblock
name: Devil, Imp
layout: Shadowdark Monster
image:
description: Cat-sized, red devils with oversized wings and tail, tiny horns, and cowardly demeanors.
ac: 13
hp: 9
actions:
  - name: Stinger x1
    desc: +3 (1d4 + poison)
mv: near (fly)
stats: [-2,+3,+0,+1,+0,+2]
alignment: Chaotic
level: 2
traits:
  - name: Impervious
    desc: Fire immune. 
  - name: Contract
    desc: Can grant mighty boons and patronage on behalf of an archdevil in exchange for a sworn soul. ADV on related Charisma checks.
  - name: Poison
    desc: DC 12 CON or fitful sleep for 1d4 hours.
```

# Dinosaurs

## Pterodactyl
```statblock
name: Pterodactyl
layout: Shadowdark Monster
image:
description: Long-beaked beasts with wide, triangular wings. Large enough to carry off a human.
ac: 14
hp: 20
actions:
  - name: Beak x2
    desc: +4 (1d8 + grab)
mv: double near (fly)
stats: [+2,+4,+2,-2,+1,-3]
alignment: Neutral
level: 4
traits:
  - name: Grab
    desc: DC 15 STR or held. DC 15 STR on turn to break free.
```

## Tyrannosaurus
```statblock
name: Tyrannosaurus
layout: Shadowdark Monster
image:
description: Towering, bipedal lizards with a massive head, jaws, and neck.
ac: 13
hp: 44
actions:
  - name: Bite x3
    desc: +8 (2d12)
mv: double near
stats: [+5,+1,+4,-3,+1,-3]
alignment: Neutral
level: 9
```

## Triceratops
```statblock
name: Triceratops
layout: Shadowdark Monster
image:
description: Plodding herbivores with a wide, bony skull frill and three horns.
ac: 17
hp: 35
actions:
  - name: Horns x2
    desc: +6 (1d10)
  - name: Charge x1
    desc: <see below>
mv: near
stats: [+4,-1,+4,-3,+1,-3]
alignment: Neutral
level: 7
traits:
  - name: Charge
    desc: Move up to double near in straight line and make 1 horn attack. If hit, x3 damage.
```

## Brachiosaurus
```statblock
name: Brachiosaurus
layout: Shadowdark Monster
image:
description: Colossal, long-necked tree grazers. Slow and peaceful.
ac: 13
hp: 57
actions:
  - name: Stomp x3
    desc: +7 (2d10)
mv: double near
stats: [+6,-1,+3,-3,+1,-3]
alignment: Neutral
level: 12
```

## Plesiosaurus
```statblock
name: Plesiosaurus
layout: Shadowdark Monster
image:
description: Aquatic reptiles as big as elephants. Flat flippers and narrow, toothy maws on long necks.
ac: 13
hp: 30
actions:
  - name: Bite x2
    desc: +5 (2d8)
mv: double near (swim)
stats: [+4,+3,+3,-3,+1,-3]
alignment: Neutral
level: 6
```

## Velociraptor
```statblock
name: Velociraptor
layout: Shadowdark Monster
image:
description: Fast, turkey-sized raptors with vicious toe claws. Pack hunters.
ac: 13
hp: 10
actions:
  - name: Claw x1
    desc: +3 (1d6)
mv: double near
stats: [-1,+3,+1,-2,+1,-3]
alignment: Neutral
level: 2
traits:
  - name: Clever
    desc: +1d4 damage when attacking with surprise.
```

## Djinni
```statblock
name: Djinni
layout: Shadowdark Monster
image:
description: Azure-blue, jovial humanoids made of air and roiling wind. Infused with potent magic.
ac: 14
hp: 48
actions:
  - name: Scimitar x3
    desc: +7 (1d12)
  - name: Whirlwind x1
    desc: <see below>
mv: double near (fly)
stats: [+4,+4,+3,+4,+3,+3, ]
alignment: Neutral
level: 10
traits:
  - name: Impervious
    desc: Only damaged by magical sources.
  - name: Whirlwind
    desc: Transform into a lashing tornado. All enemies within near DC 18 DEX or thrown 2d100 feet in a random direction.
  - name: Wish
    desc: Cast [[Wish]] once a week for a mortal, no spellcasting check.
```

## Doppelganger
```statblock
name: Doppleganger
layout: Shadowdark Monster
image:
description: Gray, featureless humanoids that delight in sowing chaos.
ac: 12
hp: 20
actions:
  - name: Dagger x1
    desc: (close/near) +2 (1d4)
mv: near
stats: [+1,+2,+2,+1,+0,+4]
alignment: Chaotic
level: 4
traits:
  - name: Change Shape
    desc: In place of attacks, transform into any similarly-sized humanoid.
  - name: Telepathy
    desc: Can secretly hear the surface thoughts of all humanoids within near.
```

# Dragons

Dragons are winged, formidable reptiles who carry the ancient magic of the land in their blood. Evil dragons are vain and cunning, while good dragons are noble and sagacious. They can live for many thousands of years.

All dragons love treasure and hoard it in their remote, well-protected lairs deep within their favored environ. A dragon's lair has its level x 100 in gold pieces and 1d4 items from the 80-100 range on its treasure table.


## Dragon, Desert
```statblock
name: Dragon, Desert
layout: Shadowdark Monster
image:
description: The smell of ozone precedes this desert-dwelling dragon. Its dazzling scales of brass and lapis lazuli shimmer in the baking heat.
ac: 17
hp: 61
actions:
  - name: Rend x3
    desc: +9 (2d10)
  - name: Lightning Breath x1
    desc: <see below>
mv: double near (fly)
stats: [+5,+3,+3,+4,+5,+5]
alignment: Lawful
level: 13
traits:
  - name: Stormblood
    desc: Electricity immune.
  - name: Lightning Breath
    desc: A straight line (5' wide) extending double near from dragon. DC 15 DEX or 4d8 damage (DISADV on check if wearing metal armor).
  - name: Mirage
    desc: 1/day, in place of attacks Create 3 illusory duplicates that disappear when hit. Determine randomly if an attack hits dragon or illusions.
```

## Dragon, Fire
```statblock
name: Dragon, Fire
layout: Shadowdark Monster
image:
description: Blood-red scales cover the hide of this mighty, volcanic wyrm. Leaping flames glow at the back of its throat.
ac: 18
hp: 80
actions:
  - name: Rend x4
    desc: +11 (2d12)
  - name: Fire Breath x1
    desc: <see below>
mv: double near (fly)
stats: [+6,+5,+4,+4,+4,+5]
alignment: Chaotic
level: 17
traits:
  - name: Fireblood
    desc: Fire immune.
  - name: Fire Breath
    desc: Fills a double near-sized cube extending from dragon. DC 15 DEX or 6d10 damage.
```

## Dragon, Forest
```statblock
name: Dragon, Forest
layout: Shadowdark Monster
image:
description: The smell of wet loam follows this dragon. Its jade scales bristle with barbed thorns.
ac: 16
hp: 58
actions:
  - name: Rend x3
    desc: +8 (2d8)
  - name: Poison Breath x1
    desc: <see below>
mv: double near (fly)
stats: [+4,+3,+4,+3,+3,+4]
alignment: Neutral
level: 12
traits:
  - name: Animate Plants
    desc: 1/day, in place of attacks. Vines grab at all enemies within double near of dragon. DC 15 DEX or unable to move 1d4 rounds.
  - name: Poison Breath
    desc: Fills a near-sized cube extending from dragon. DC 15 CON or 3d8 damage.
```

## Dragon, Frost
```statblock
name: Dragon, Frost
layout: Shadowdark Monster
image:
description: Prismatic ice lines the horns, spines, and wings of this pearly dragon. Clouds of steam hiss from its ice-rimed jaws.
ac: 17
hp: 68
actions:
  - name: Rend x4
    desc: +9 (2d10)
  - name: Ice Breath x1
    desc: <see below>
mv: double near (fly), 
stats: [+4,+3,+5,+3,+4,+3]
alignment: Neutral
level: 14
traits:
  - name: Frostblood
    desc: Cold immune.
  - name: Ice Breath
    desc: Fills a double near-sized cube extending from dragon. DC 15 DEX or 4d8 damage and frozen for 1 round.
```

## Dragon, Sea
```statblock
name: Dragon, Sea
layout: Shadowdark Monster
image:
description: A warm sea breeze blows around this amphibious, gold-scaled wyrm. A beard of tendrils covers its snout, and a blue mane billows along its neck.
ac: 17
hp: 76
actions:
  - name: Rend x4
    desc: +10 (2d10)
  - name: Steam Breath x1
    desc: OR Water Spout x1
mv: double near (fly, swim)
stats: [+5,+6,+4,+4,+5,+5]
alignment: Lawful
level: 16
traits:
  - name: Steam Breath
    desc: Fills a double near-sized cube extending from dragon. DC 15 DEX or 4d12 damage.
  - name: Water Spout
    desc: Fills a near-sized cube within far. DC 15 STR or creatures inside flung 2d100 feet in a random direction.
```

## Dragon, Swamp
```statblock
name: Dragon, Swamp
layout: Shadowdark Monster
image: [[Dragon, Swamp.png]]
description: This black, wingless beast slithers through dank swamps.
ac: 16
hp: 58
actions:
  - name: Rend x3
    desc: +8 (2d10)
  - name: Smog Breath x1
    desc: <see below>
mv: double near (burrow, swim)
stats: [+5,+3,+4,+4,+3,+3]
alignment: Chaotic
level: 12
traits:
  - name: Smog Breath
    desc: Fills a near-sized cube extending from dragon. DC 15 CON or 2d10 damage and blinded for 1 round.
```

# Drow

Lithe, subterranean elves with ebon skin, white hair, and red eyes that see in the dark. They are stealthy and cunning.

Drow live in strikingly decadent, matriarchal societies centered around the worship of their cruel spider-demon goddess.


## Drow
```statblock
name: Drow
layout: Shadowdark Monster
image:
description: A graceful, shadowy elf that pounces like a spider.
ac: 16 (mithral chainmail)
hp: 9
actions:
  - name: poison dart x1
    desc: (near) +3 (1d4 + poison)
  - name: Longsword x1
    desc: +1 (1d8)
mv: near
stats: [+0,+3,+0,+1,+1,+1]
alignment: Chaotic
level: 2
traits:
  - name: Poison
    desc: DC 15 CON or sleep.
  - name: Sunblind
    desc: Blinded in bright light.
```

## Drow, Priestess
```statblock
name: Drow, Priestess
layout: Shadowdark Monster
image:
description: A statuesque female drow with a crown of metal spider webs and an imperious gaze.
ac: 16 (mithral chainmail)
hp: 28
actions:
  - name: Snake Whip x3
    desc: (near) +4 (1d8 + poison)
  - name: Spell x1
    desc: +4,
mv: near
stats: [+2,+3,+1,+3,+4,+3]
alignment: Chaotic
level: 6
traits:
  - name: Poison
    desc: DC 15 CON or paralyzed 1d4 rounds.
  - name: Sunblind
    desc: Blinded in bright light.
spells:
  - name: Snuff (WIS Spell)
    desc: DC 12. Extinguish all light sources (even magical) within near.
  - name: Summon Spiders (WIS Spell)
    desc: DC 14. Summon 2d4 loyal giant spiders that appear within near. They stay for 5 rounds.
  - name: Web (WIS Spell)
    desc: DC 13. A near-sized cube of webs within far immobilizes all inside it for 5 rounds. DC 15 STR on turn to break free.
```

## Drow, Drider
```statblock
name: Drow, Drider
layout: Shadowdark Monster
image:
description: A monstrosity with the body of a giant spider and torso of a drow.
ac: 16 (mithral chainmail)
hp: 29
actions:
  - name: Longsword x3
    desc: +3 (1d8)
  - name: Longbow x2
    desc: (far) +3 (1d8 + poison)
mv: near (climb)
stats: [+3,+3,+2,+2,+2,+0]
alignment: Chaotic
level: 6
traits:
  - name: Poison
    desc: DC 15 CON or paralyzed 1d4 rounds.
  - name: Sunblind
    desc: Blinded in bright light.
```

## Druid
```statblock
name: Druid
layout: Shadowdark Monster
image:
description: A wizard of the wilds holding a knotted staff and wearing a mossy cloak of deep viridian.
ac: 11
hp: 31
actions:
  - name: Staff x1
    desc: +0 (1d4)
  - name: Spell x2
    desc: +5,
mv: near
stats: [+0,+1,+0,+4,+3,+0]
alignment: Neutral
level: 7
spells:
  - name: Barkskin (INT Spell)
    desc: Self. DC 13. AC becomes 15 for 5 rounds.
  - name: Conjure Flames (INT Spell)
    desc: DC 12. One target in far takes 2d6 damage.
  - name: Imbue (INT Spell)
    desc: Self. DC 13. Staff becomes a +3 magic weapon for 10 rounds.
  - name: Summon Bear (INT Spell)
    desc: DC 14. Summon a loyal brown bear that appears within near. It stays for 5 rounds.
  - name: Thunderclap (INT Spell)
    desc: DC 13. Fills a near-sized cube extending from druid. Creatures within are thrown 2d20 feet in a random direction.
```

## Dryad
```statblock
name: Dryad
layout: Shadowdark Monster
image: [[Dryad.png]]
description: A coy, emerald-skinned fey covered in leaves. It bonds with and protects a tree.
ac: 13
hp: 19
actions:
  - name: Staff x1
    desc: -1 (1d4)
  - name: Charm x1
    desc: <see below>
mv: near
stats: [-1,+2,+1,+1,+3,+4]
alignment: Neutral
level: 4
traits:
  - name: Charm
    desc: Near, one creature, DC 14 CHA or friendship for 1d8 days. Meld. Step inside bonded tree.
```

## Duergar
```statblock
name: Duergar
layout: Shadowdark Monster
image:
description: Gray-skinned, greedy dwarves with bald pates and white beards. They dwell in somber castles deep within the earth filled with stolen treasures and enslaved prisoners.
ac: 15 (chainmail + shield)
hp: 12
actions:
  - name: War Pick x1
    desc: +2 (1d6)
mv: near
stats: [+2,+0,+3,+0,-1,-1]
alignment: Chaotic
level: 2
traits:
  - name: Enlarge
    desc: 1/day,+1d6 damage on melee attacks and ADV on STR checks for 3 rounds.
  - name: Invisibility
    desc: 1/day, turn invisible for 3 rounds. Ends if duergar attacks.
  - name: Sunblind
    desc: Blinded in bright light.
```

## Dung Beetle, Giant
```statblock
name: Dung Beetle, Giant
layout: Shadowdark Monster
image: [[Dung Beetle, Giant.png]]
description: A trundling, barrel-sized beetle with a T-shaped horn.
ac: 13
hp: 10
actions:
  - name: Horn x1
    desc: +1 (1d4 + knock)
mv: near
stats: [+1,-1,+1,-3,-1,-3]
alignment: Neutral
level: 2
traits:
  - name: Knock
    desc: DC 9 STR or pushed a close distance and fall down.
```

## Efreeti
```statblock
name: Efreeti
layout: Shadowdark Monster
image:
description: Blood-red, towering humanoids formed of lava and ash. Short, black horns and snarling grins.
ac: 15
hp: 43
actions:
  - name: Scimitar x3
    desc: +8 (2d10)
  - name: Fire Bolt x2
    desc: (far) +5 (2d6)
mv: near (fly)
stats: [+5,+2,+3,+3,+2,+3]
alignment: Chaotic
level: 9
traits:
  - name: Impervious
    desc: Only damaged by magical sources. Fire immune.
  - name: Wall of Flame
    desc: 1/day, 20' high curtain of fire, double near length. Touching it deals 4d8 damage. Lasts 2d4 rounds.
  - name: Wish
    desc: Cast [[Wish]] once a week for a mortal, no spellcasting check.
```

# Elementals
 
Elementals are semi-humanoid beings of pure energy that speak rudimentary Primordial. Earth and air are anathema to each other, as are fire and water.

Lesser elementals are LV 6 and their slam deals 2 dice of damage. Greater elementals are LV 9 and their slam deals 3 dice of damage.


## Elemental, Air
```statblock
name: Elemental, Air
layout: Shadowdark Monster
image:
description: A howling tornado of wind.
ac: 16
hp: 29/42
actions:
  - name: Slam x3
    desc: +7 (2d6/3d6)
  - name: Whirlwind x1
    desc: <see below>
mv: double near (fly)
stats: [+3,+5,+2,-2,+1,-2]
alignment: Neutral
level: 6/9
traits:
  - name: Impervious
    desc: Only damaged by magical sources.
  - name: Whirlwind
    desc: All within close DC 15 DEX or flung 2d20 feet in random direction.
```

## Elemental, Earth
```statblock
name: Elemental, Earth
layout: Shadowdark Monster
image:
description: A thundering pillar of earth.
ac: 17
hp: 31/44
actions:
  - name: Slam x3
    desc: +7 (2d8/3d8)
  - name: Avalanche x1
    desc: <see below>
mv: near (burrow)
stats: [+5,+0,+4,-2,+1,-2]
alignment: Neutral
level: 6/9
traits:
  - name: Impervious
    desc: Only damaged by magical sources.
  - name: Avalanche
    desc: All within close DC 15 STR or entombed for 1d4 rounds under mounds of earth.
```

## Elemental, Fire
```statblock
name: Elemental, Fire
layout: Shadowdark Monster
image:
description: A roaring column of flames.
ac: 15
hp: 30/43
actions:
  - name: Slam x3
    desc: +6 (2d10/3d10)
  - name: Inferno x1
    desc: <see below>
mv: near (fly)
stats: [+4,+3,+3,-2,+1,-2]
alignment: Neutral
level: 6/9
traits:
  - name: Impervious
    desc: Only damaged by magical sources. Fire immune.
  - name: Inferno
    desc: All within near DC 15 DEX or 3d8 damage.
```

## Elemental, Water
```statblock
name: Elemental, Water
layout: Shadowdark Monster
image:
description: A crashing vortex of water.
ac: 15
hp: 29/42
actions:
  - name: Slam x3
    desc: +6 (2d6/3d6)
  - name: Whirlpool x1
    desc: <see below>
mv: double near (swim)
stats: [+4,+2,+2,-2,+1,-2]
alignment: Neutral
level: 6/9
traits:
  - name: Impervious
    desc: Only damaged by magical sources.
  - name: Whirlpool
    desc: All within close DC 15 STR or immobilized inside water elemental (treat as underwater). DC 15 STR on turn to escape.
```

## Elephant
```statblock
name: Elephant
layout: Shadowdark Monster
image:
description: Mighty mammals with tough hide, flappy ears, and a trunk.
ac: 14
hp: 34
actions:
  - name: Tusks x2
    desc: +6 (1d8)
mv: near
stats: [+5,+0,+3,-2,+1,+0]
alignment: Neutral
level: 7
traits:
  - name: Charge
    desc: Move up to double near in straight line and make 1 tusks attack. If hit, x3 damage.
```

## Elf
```statblock
name: Elf
layout: Shadowdark Monster
image:
description: Ethereal, ageless fey-people infused with ancient magic.
ac: 13
hp: 9
actions:
  - name: Longsword x1
    desc: +1 (1d8)
  - name: Longbow x1
    desc: (far) +3 (1d8) 
mv: near
stats: [+0,+3,+0,+1,+1,+1]
alignment: Lawful
level: 2
traits:
  - name: Feyblood
    desc: ADV on DEX checks while in the natural wilds.
```

## Ettercap
```statblock
name: Ettercap
layout: Shadowdark Monster
image: [[Ettercap.png]]
description: Bipedal, eight-eyed spiderfolk with spindly legs and purple fur.
ac: 12
hp: 14
actions:
  - name: Bite x2
    desc: +2 (1d6)
  - name: Poison Web x1
    desc: (near) +2
mv: near (climb)
stats: [+0,+2,+1,+0,+0,-1]
alignment: Chaotic
level: 3
traits:
  - name: Poison Web
    desc: One target stuck in place and 1d4 damage/round. DC 12 DEX on turn to escape.
```

## Fairy
```statblock
name: Fairy
layout: Shadowdark Monster
image: [[Fairy.png]]
description: Miniature fey folk with fluttering moth or butterfly wings.
ac: 13
hp: 4
actions:
  - name: Needle x1
    desc: +3 (1 + poison)
mv: near (fly)
stats: [-2,+3,+0,+1,+0,+1]
alignment: Neutral
level: 1
traits:
  - name: Poison
    desc: DC 12 CON or fall into deep sleep for 1d4 hours.
```

## Frog, Giant
```statblock
name: Frog, Giant
layout: Shadowdark Monster
image:
description: Human-sized frogs with warty skin and long, sticky tongues.
ac: 12
hp: 10
actions:
  - name: Bite x1
    desc: +2 (1d6)
  - name: Tongue x1
    desc: <see below>
mv: near (swim)
stats: [+2,+2,+1,-3,+0,-3]
alignment: Neutral
level: 2
traits:
  - name: Tongue
    desc: 1 creature in near DC 12 DEX or pulled to close range.
```

## Gargoyle
```statblock
name: Gargoyle
layout: Shadowdark Monster
image:
description: Leering, winged fiends that look like stone statues. They can hold perfectly still for long stretches of time.
ac: 16
hp: 20
actions:
  - name: Claw x2
    desc: +3 (1d6)
mv: near (fly)
stats: [+3,+1,+2,+0,+1,-1]
alignment: Chaotic
level: 4
traits:
  - name: Impervious
    desc: Only damaged by magical sources.
```

## Gelatinous Cube
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

## Ghast
```statblock
name: Ghast
layout: Shadowdark Monster
image:
description: Greater ghouls who retain the intelligence they had in life.
ac: 11
hp: 20
actions:
  - name: Claw x2
    desc: +4 (1d8 + paralyze)
mv: near
stats: [+3,+1,+2,+0,+0,+2]
alignment: Chaotic
level: 4
traits:
  - name: Undead
    desc: Immune to morale checks.
  - name: Carrion Stench
    desc: Living creatures DC 12 CON the first time within near or DISADV on attacks and spellcasting for 5 rounds.
  - name: Paralyze
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Ghoul
```statblock
name: Ghoul
layout: Shadowdark Monster
image:
description: Gray-skinned, slavering undead with whipping tongues and flat, reptilian faces.
ac: 11
hp: 11
actions:
  - name: Claw x1
    desc: +2 (1d6 + paralyze)
mv: near
stats: [+2,+1,+2,-3,-1,+0]
alignment: Chaotic
level: 2
traits:
  - name: Undead
    desc: Immune to morale checks.
  - name: Paralyze
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Ghost
```statblock
name: Ghost
layout: Shadowdark Monster
image: [[Ghost.png]]
description: A wavering spirit with a face contorted in rage or sadness.
ac: 13
hp: 27
actions:
  - name: Death Touch x2
    desc: +5 (1d8 + life drain)
  - name: Possess x1
    desc: <see below>
mv: near (fly)
stats: [-2,+3,+0,+0,+0,+4]
alignment: Chaotic
level: 6
traits:
  - name: Greater Undead
    desc: Immune to morale checks. Only damaged by silver or magical sources. 
  - name: Incorporeal
    desc: In place of attacks, become corporeal or incorporeal.
  - name: Life Drain
    desc: 1d4 CON damage. Death if reduced to 0 CON.
  - name: Possess
    desc: Must be corporeal. One target, close range. Contested CHA check. If ghost wins, it inhabits target's body and controls it for 2d4 rounds.
```

# Giants

Giants once ruled the earth long ago, warring with dragons for supremacy over the seas and skies. But the weariness of eons eventually caused their glorious societies to erode. Now, they live in reclusive clans, wary of outsiders and withdrawn from the younger civilizations.

Hill and goat giants are brutish louts who ally with goblinkind. Fire giants build enclaves in volcanoes, frost giants in frozen wastes. Stone giants live deep underground, while cloud giants occupy lofty mountain castles. Mighty storm giants dwell in majestic, deep-sea strongholds.

## Giant, Cloud
```statblock
name: Giant, Cloud
layout: Shadowdark Monster
image:
description: Pale, angular giants with blue-gray hair, light eyes, and silk robes. They do not allow outsiders into their enclaves.
ac: 15 (leather)
hp: 48
actions:
  - name: Morningstar x3
    desc: +9 (2d10)
mv: double near
stats: [+5,+4,+3,+3,+3,+3]
alignment: Neutral
level: 10
traits:
  - name: Alert
    desc: ADV on checks to detect sneaking or hiding creatures.
```

## Giant, Fire
```statblock
name: Giant, Fire
layout: Shadowdark Monster
image:
description: Bulky, muscled giants with coppery skin and red hair. Heavily armored in iron plate mail studded with bronze rivets.
ac: 15 (plate mail)
hp: 44
actions:
  - name: Greatsword x3
    desc: +9 (2d12)
mv: double near
stats: [+6,+0,+4,+1,+2,+1]
alignment: Chaotic
level: 9
traits:
  - name: Fireblood
    desc: Fire immune.
```

## Giant, Frost
```statblock
name: Giant, Frost
layout: Shadowdark Monster
image:
description: Blue-skinned warriors with broad shoulders and braided hair. They sound war horns during their frequent raids to pillage nearby settlements.
ac: 14 (chainmail)
hp: 44
actions:
  - name: Greataxe x3
    desc: +8 (2d10)
mv: double near
stats: [+5,+1,+4,+2,+3,+2]
alignment: Chaotic
level: 9
traits:
  - name: Frostblood
    desc: Cold immune.
```

## Giant, Stone
```statblock
name: Giant, Stone
layout: Shadowdark Monster
image:
description: Lean, sinewy giants with stony skin and deep-set eyes. They are quiet and poised, often sitting motionless for days at a time.
ac: 17
hp: 40
actions:
  - name: Greatclub x2
    desc: +7 (2d8)
  - name: Boulder x1
    desc: (far) +7 (2d10)
mv: double near
stats: [+4,+2,+4,+1,+1,-1]
alignment: Neutral
level: 8
traits:
  - name: Stone Hide
    desc: Half damage from stabbing and cutting weapons.
```

## Giant, Goat
```statblock
name: Giant, Goat
layout: Shadowdark Monster
image:
description: Highland-dwelling, barbaric giants with goatlike legs, horns, and horizontal pupils.
ac: 12 (leather)
hp: 39
actions:
  - name: Greatclub x2
    desc: +7 (2d8)
  - name: Boulder x1
    desc: (far) +7 (2d10)
mv: double near (climb)
stats: [+4,+1,+3,-2,+0,-2]
alignment: Chaotic
level: 8
```

## Giant, Storm
```statblock
name: Giant, Storm
layout: Shadowdark Monster
image:
description: Regal titans with sea-green skin, flowing white hair, and thundering voices. They breathe water as easily as air.
ac: 15 (mithral chainmail)
hp: 58
actions:
  - name: Greatsword x3
    desc: +10 (2d12)
  - name: Lightning Bolt
    desc: <see below>
mv: double near (swim)
stats: [+6,+2,+4,+3,+4,+4]
alignment: Lawful
level: 12
traits:
  - name: Stormblood
    desc: Electricity immune.
  - name: Lightning Bolt
    desc: 3/day, 5' wide line extending far from giant. All creatures in line DC 15 DEX or 5d10 damage. DISADV on check if in water.
```

## Giant, Hill
```statblock
name: Giant, Hill
layout: Shadowdark Monster
image:
description: Fleshy hulks with leathery skin and broad, sloping foreheads. Cruel, boorish, and dim-witted.
ac: 11 (leather)
hp: 34
actions:
  - name: Greatclub x2
    desc: +6 (2d8)
  - name: Boulder x1
    desc: (far) +6 (2d10) 
mv: double near
stats: [+4,+0,+3,-2,-2,-2]
alignment: Chaotic
level: 7
```

## Gibbering Mouther
```statblock
name: Gibbering Mouther
layout: Shadowdark Monster
image:
description: Crawling masses of slime with dozens of screeching, lipless mouths and wet eyeballs.
ac: 8
hp: 21
actions:
  - name: Bite x2
    desc: +3 (1d8 + latch)
mv: near (climb, swim)
stats: [+2,-2,+3,-3,+0,-3]
alignment: Neutral
level: 4
traits:
  - name: Gibbering
    desc: Creatures within near DC 12 WIS on turn or take a random action (see table below)
  - name: Latch
    desc: Attach to bitten target; bites auto-hit next round. DC 12 STR on turn to tear off.
```

| d8  | action                   |
|:---:| ------------------------ |
| 1-3 | do nothing               |
| 4-5 | move in random direction |
| 6-7 | attack nearest creature  |
|  8  | flee.                    |

## Gladiator
```statblock
name: Gladiator
layout: Shadowdark Monster
image:
description: Veteran warriors seasoned in arena fights to the death.
ac: 16 (chainmail + shield)
hp: 15
actions:
  - name: Longsword x2
    desc: +3 (1d8)
  - name: Spear
    desc: (close/near) +3 (1d6)
mv: near
stats: [+2,+1,+2,+0,+0,+1,]
alignment: Neutral
level: 3
```

## Gnoll
```statblock
name: Gnoll
layout: Shadowdark Monster
image:
description: Barbaric, opportunistic hyena-folk who range in large packs.
ac: 12 (leather)
hp: 10
actions:
  - name: Spear x1
    desc: (close/near) +1 (1d6)
  - name: Longbow x1
    desc: (far) +1 (1d8)
mv: near
stats: [+1,+1,+1,-1,+0,-1]
alignment: Chaotic
level: 2
traits:
  - name: Rage
    desc: 1/day, immune to morale checks,+1d4 damage (3 rounds).
```

## Gnome, Deep
```statblock
name: Gnome, Deep
layout: Shadowdark Monster
image: [[Gnome, Deep.png]]
description: Gray-skinned, white-haired fey the size of halflings. They hunt for gems and rare cave flora.
ac: 14 (leather + shield)
hp: 14
actions:
  - name: Pick x1
    desc: +3 (1d6)
  - name: Dart x1
    desc: (near) +2 (1d4)
mv: near
stats: [+2,+1,+1,+1,+1,+1]
alignment: Lawful
level: 3
traits:
  - name: Stone Meld
    desc: 2/day, underground only. Turn invisible for 3 rounds.
```

# Goblins

Goblins are the smallest and most numerous of the goblinoids, often serving hobgoblins, bugbears, or even hill giants as replaceable lackeys.

They live in filthy, subterranean warrens built of scavenged materials. The [[Goblin Boss]] rules by cruelty and strength, and the [[Shaman]] wields cryptic sorcery.


## Goblin
```statblock
name: Goblin
layout: Shadowdark Monster
image: [[Goblin.png]]
description: A short, hairless humanoid with green skin and pointy ears.
ac: 11
hp: 5
actions:
  - name: Club x1
    desc: +0 (1d4)
  - name: Shortbow x1
    desc: (far) +1 (1d4)
mv: near
stats: [+0,+1,+1,-1,-1,-2]
alignment: Chaotic
level: 1
traits:
  - name: Keen Senses
    desc: Can't be surprised.
```

## Goblin, Boss
```statblock
name: Goblin, Boss
layout: Shadowdark Monster
image:
description: A scarred goblin with knotted muscles and a crown of iron.
ac: 14 (chainmail)
hp: 20
actions:
  - name: Spear x1
    desc: (close/near) +3 (1d6)
mv: near
stats: [+2,+1,+2,-1,+0,+1]
alignment: Chaotic
level: 4
traits:
  - name: Keen Senses
    desc: Can't be surprised.
```

## Goblin, Shaman
```statblock
name: Goblin, Shaman
layout: Shadowdark Monster
image:
description: A swaying, chanting goblin wearing necklaces of teeth and a robe of musty rat pelts.
ac: 12 (leather)
hp: 19
actions:
  - name: Staff x1
    desc: +0 (1d4)
  - name: Spell x1
    desc: +3,
mv: near
stats: [+0,+1,+1,+0,+2,+1]
alignment: Chaotic
level: 4
traits:
  - name: Keen Senses
    desc: Can't be surprised.
spells:
  - name: Bug Brain (WIS Spell)
    desc: DC 13. Near range, one target. Target's INT drops to 1 for 1d4 rounds.
  - name: Skitter (WIS Spell)
    desc: DC 12. Self. Climb like a spider for 5 rounds.
  - name: Stink Bomb (WIS Spell)
    desc: DC 12. One target within far 2d4 damage and DC 12 CON or DISADV on next check/attack.
```

# Golems

Creatures constructed from various materials and imbued with a rudimentary sentience.

Making a golem requires rare, expensive materials and a series of complicated rituals.


## Golem, Clay
```statblock
name: Golem, Clay
layout: Shadowdark Monster
image:
description: A towering, faceless humanoid shaped from glistening clay.
ac: 14
hp: 40
actions:
  - name: Slam x3
    desc: +6 (1d8)
mv: near
stats: [+4,+0,+4,-2,+0,-2]
alignment: Neutral
level: 8
traits:
  - name: Golem
    desc: Immune to damage from fire, cold, electricity, or non-magical sources. Healed by acid.
  - name: Curse
    desc: Slam damage can only be healed by level 5+ priest.
```

## Golem, Flesh
```statblock
name: Golem, Flesh
layout: Shadowdark Monster
image:
description: A ghastly monstrosity made of sewn-together corpses.
ac: 9
hp: 35
actions:
  - name: Slam x3
    desc: +6 (1d8)
mv: near
stats: [+4,-1,+4,-1,+1,-3]
alignment: Neutral
level: 7
traits:
  - name: Golem
    desc: Immune to damage from fire, cold, or non-magical sources. Healed by electricity.
  - name: Berserk
    desc: When at or below 20 HP,+1 slam attack and slams deal double damage.
```

## Golem, Iron
```statblock
name: Golem, Iron
layout: Shadowdark Monster
image:
description: A bulky iron suit that squeals and sparks with each step.
ac: 19
hp: 49
actions:
  - name: Slam x3
    desc: +8 (2d8)
  - name: Poison Breath x1
    desc: <see below>
mv: near
stats: [+5,-1,+4,-2,+0,-2]
alignment: Neutral
level: 10
traits:
  - name: Golem
    desc: Immune to damage from cold or non-magical sources. Healed by fire.
  - name: Poison Breath.
    desc: All within near, DC 15 CON or 8d6 damage.
```

## Golem, Stone
```statblock
name: Golem, Stone
layout: Shadowdark Monster
image: [[Golem, Stone.png]]
description: A wide-limbed, lumbering statue that shakes the ground.
ac: 18
hp: 40
actions:
  - name: Slam x3
    desc: +6 (1d10)
  - name: Slow x1
    desc: <see below>
mv: near
stats: [+4,-1,+4,-2,+0,-2]
alignment: Neutral
level: 8
traits:
  - name: Golem
    desc: Immune to damage from fire, cold, electricity, or non-magical sources.
  - name: Slow
    desc: Far range, one target. DC 15 CON or speed halved 1d4 rds.
```

## Gorgon
```statblock
name: Gorgon
layout: Shadowdark Monster
image:
description: A snorting bull made entirely of iron plating. A cloud of green fog billows from its nostrils.
ac: 18
hp: 33
actions:
  - name: Gore x2
    desc: +6 (2d8)
  - name: Charge x1
    desc: or Petrifying Breath x1
mv: double near
stats: [+4,+0,+2,-3,+1,-3]
alignment: Chaotic
level: 7
traits:
  - name: Charge
    desc: Move up to double near in straight line and make 1 gore attack. If hit, x3 damage.
  - name: Petrifying Breath
    desc: Fills a near-sized cube extending from gorgon. DC 15 CON or petrified (gorgons immune).
```

## Gorilla
```statblock
name: Gorilla
layout: Shadowdark Monster
image:
description: Mighty, jungle-dwelling apes.
ac: 12
hp: 20
actions:
  - name: Rend x2
    desc: +5 (2d6)
mv: near (climb)
stats: [+4,+2,+2,-1,+1,-1]
alignment: Neutral
level: 4
```

## Gray Ooze
```statblock
name: Grey Ooze
layout: Shadowdark Monster
image:
description: Slick puddles the color of stone.
ac: 11
hp: 9
actions:
  - name: Tentacle x1
    desc: +2 (1d6)
mv: near (climb)
stats: [+1,+1,+0,-4,-3,-4]
alignment: Neutral
level: 2
traits:
  - name: Impervious
    desc: Immune to damage from acid, cold, or fire.
  - name: Corrosive
    desc: Nonmagical metal that touches the ooze dissolves on a d6 roll of 1-3.
```

## Grick
```statblock
name: Grick
layout: Shadowdark Monster
image: [[Grick.png]]
description: A huge worm with four suckered tentacles and a snapping beak.
ac: 14
hp: 19
actions:
  - name: Beak x1
    desc: +3 (1d8)
  - name: Tentacle x1
    desc: +3 (1d6 + grab)
mv: near (climb)
stats: [+3,+2,+1,-3,+1,-3]
alignment: Neutral
level: 4
traits:
  - name: Camouflage
    desc: Hard to see in cave terrain or rocks.
  - name: Grab
    desc: Target is immobilized. DC 15 Strength check on turn to break free.
```

## Griffon
```statblock
name: Griffon
layout: Shadowdark Monster
image:
description: Winged hunters with the head of an eagle and body of a lion. Their favored food is horses.
ac: 12
hp: 19
actions:
  - name: Rend x2
    desc: +4 (1d10)
mv: double near (fly)
stats: [+4,+2,+1,-3,+1,-1]
alignment: Neutral
level: 4
```

## Grimlow
```statblock
name: Grimlow
layout: Shadowdark Monster
image:
description: A tall, oval-shaped mammal. A giant, half-moon maw hides on its belly beneath its gray fur.
ac: 12
hp: 43
actions:
  - name: Bite x3
    desc: +6 (2d8)
  - name: Grab x1
    desc:  
mv: near
stats: [+4,+2,+3,-3,+1,-2]
alignment: Neutral
level: 9
traits:
  - name: Grab
    desc: One target in near DC 15 STR or wrapped in grimlow's tongue and pulled into its mouth. Bite attacks automatically hit the target. Can only grab 1 target at a time. DC 15 STR on turn to break free.
```

## Guard
```statblock
name: Huard
layout: Shadowdark Monster
image:
description: A sentry equipped with sturdy weapons and armor.
ac: 15 (chainmail + shield)
hp: 4
actions:
  - name: Spear x1
    desc: (close/near) +1 (1d6)
  - name: Longsword x1
    desc: +1 (1d8)
mv: near
stats: [+1,+0,+0,+0,+1,+0]
alignment: Lawful
level: 1
```

# Hags

Sinister crones who rose out of the black bogs of the Unseelie realms long ago. They are wretched beings of hatred and evil, suffused with cursed magic.

Sea hags haunt dank ocean caves and grottoes. Night hags are drawn to places of depravity and woe, while weald hags fester in deep, boggy woods.


## Hag, Weald
```statblock
name: Hag, Weald
layout: Shadowdark Monster
image: [[Hag, Weald.png]]
description: Eyes dark as moonless nights, skin made of rotting wood, hair of tangled roots and vines.
ac: 14
hp: 28
actions:
  - name: Claw x2
    desc: +4 (1d8)
  - name: Drink Pain x1
    desc: <see below>
mv: near
stats: [+3,+2,+1,+1,+2,+3]
alignment: Chaotic
level: 6
traits:
  - name: Drink Pain
    desc: Near range. DC 12 CHA to deal 2d4 damage to a creature; regain that many HP.
  - name: Shapechange
    desc: Instantly change to look like any other humanoid.
```

## Hag, Night
```statblock
name: Hag, Night
layout: Shadowdark Monster
image:
description: A purple-skinned, stooped woman with stringy, white hair and a mouth full of iron teeth.
ac: 14
hp: 37
actions:
  - name: Bite x2
    desc: +6 (1d10)
  - name: Blind x1
    desc: <see below>
mv: near
stats: [+4,+2,+1,+2,+3,+3]
alignment: Chaotic
level: 8
traits:
  - name: Blind
    desc: One target within near DC 15 CHA or blinded for 1d4 days.
  - name: Shapechange
    desc: Instantly change to look like any other humanoid.
```

## Hag, Sea
```statblock
name: Hag, Sea
layout: Shadowdark Monster
image:
description: A green, sunken-faced woman. Seaweed hair and oozing flesh.
ac: 15
hp: 28
actions:
  - name: Claw x2
    desc: +4 (1d8)
mv: near (swim)
stats: [+2,+3,+1,+1,+2,+2]
alignment: Chaotic
level: 6
traits:
  - name: Shapechange
    desc: Instantly change to look like any other humanoid.
  - name: Terrify
    desc: A creature who first sees her true form DC 15 CHA or DISADV on attacks 1d4 rounds.
```

## Harpy
```statblock
name: Harpy
layout: Shadowdark Monster
image:
description: Horrific, winged women with vulture-like lower bodies. They keen a hypnotic song.
ac: 13
hp: 14
actions:
  - name: Claw x2
    desc: +3 (1d6)
  - name: Song x1
    desc: <see below>
mv: near (fly)
stats: [+1,+3,+1,+0,+0,+1]
alignment: Chaotic
level: 3
traits:
  - name: Song
    desc: Enemies who can hear within double near DC 12 CHA or dazed and drawn to harpy for 1d4 rounds. Immune for 1 day if passed check.
```

## Hell Hound
```statblock
name: Hell Hound
layout: Shadowdark Monster
image:
description: Black wolfhounds with red eyes and jaws dripping with flames.
ac: 13
hp: 19
actions:
  - name: Bite x2
    desc: +4 (1d8)
  - name: Fire Breath x1
    desc: <see below>
mv: double near
stats: [+2,+1,+1,-2,+1,-3]
alignment: Chaotic
level: 4
traits:
  - name: Impervious
    desc: Fire immune. 
  - name: Fire Breath. 
    desc: Fills a near-sized cube extending from hell hound. DC 15 DEX or 3d8 damage. Cannot use again for 1d4 rounds.
```

## Hippogriff
```statblock
name: Hippogriff
layout: Shadowdark Monster
image:
description: Fierce, winged creatures with the lower body of a horse and upper body of a giant eagle.
ac: 13
hp: 14
actions:
  - name: Rend x2
    desc: +3 (1d8)
mv: double near (fly)
stats: [+3,+3,+1,-3,+1,-2]
alignment: Neutral
level: 3
```

## Hippopotamus
```statblock
name: Hippopotamus
layout: Shadowdark Monster
image:
description: Ornery river-beasts as large as cows with round, purple bodies and bulbous snouts.
ac: 12
hp: 24
actions:
  - name: Bite x2
    desc: +4 (1d10)
mv: near (swim)
stats: [+4,+0,+2,-3,+0,-3]
alignment: Neutral
level: 5
traits:
  - name: Stumpy
    desc: ADV on STR checks to grab or drag other creatures.
```

## Hobgoblin
```statblock
name: Hobgoblin
layout: Shadowdark Monster
image: [[Hobgoblin.png]]
description: A sturdy, tall goblin with russet skin. Militant and strategic.
ac: 15 (chainmail + shield)
hp: 10
actions:
  - name: Longsword x1
    desc: +3 (1d8)
  - name: Longbow x1
    desc: (far) +0 (1d8)
mv: near
stats: [+3,+0,+1,+2,+1,+1,]
alignment: Chaotic
level: 2
traits:
  - name: Phalanx
    desc: +1 to attacks and AC when in close range of an allied hobgoblin.
```

## Horse
```statblock
name: Horse
layout: Shadowdark Monster
image:
description: Powerful, swift herd animals that roam open plains.
ac: 11
hp: 11
actions:
  - name: Hooves x1
    desc: +3 (1d6)
mv: double near
stats: [+3,+1,+2,-3,+1,-2]
alignment: Neutral
level: 2
```

## Hydra
```statblock
name: Hydra
layout: Shadowdark Monster
image:
description: A towering, amphibious reptile with a bouquet of snake heads writhing on long necks.
ac: 15
hp: 
actions:
  - name: Bite x1
    desc: (near) +6 (1d8)
mv: near (swim)
stats: [+5,+1,+2,-2,+1,-2]
alignment: Neutral
level: 
traits:
  - name: Heads
    desc: Choose how many heads the hydra has. Each is level:2, ac:15, hp:11, and can make 1 bite attack. A killed head sprouts into two new heads at the start of the hydra's turn unless cauterized beforehand. The hydra's level is all the heads combined.
```

## Invisible Stalker
```statblock
name: Invisible Stalker
layout: Shadowdark Monster
image:
description: Intelligent creatures made of flowing air. Often bound to the bidding of evil sorcerers for their peerless tracking ability.
ac: 13
hp: 29
actions:
  - name: Pummel x3
    desc: +4 (1d6)
mv: near (fly)
stats: [+2,+3,+2,+2,+1,+0]
alignment: Neutral
level: 6
traits:
  - name: Bound
    desc: A secret, mundane contingency (such as the touch of a feather) ends the invisible stalker's magical servitude.
  - name: Invisible
    desc: Naturally invisible. Tracking. Can always sense the direction of its chosen quarry.
```

## Jellyfish
```statblock
name: Jellyfish
layout: Shadowdark Monster
image:
description: Hand-sized, purple sea jellies with stinging tentacles.
ac: 11
hp: 1
actions:
  - name: Sting x1
    desc: +1 (1 + toxin)
mv: close (swim)
stats: [-4,+1,+0,-4,+1,-4]
alignment: Neutral
level: 0
traits:
  - name: Toxin
    desc: DC 9 CON or paralyzed 1d4 rounds.
```

## Knight
```statblock
name: Knight
layout: Shadowdark Monster
image: [[Knight.png]]
description: A warrior in shining plate mail and the surcoat of a knightly order.
ac: 17 (plate mail + shield)
hp: 14
actions:
  - name: Bastard Sword x2
    desc: +3 (1d8)
mv: near
stats: [+3,+0,+1,+0,+0,+1]
alignment: Lawful
level: 3
traits:
  - name: Oath
    desc: 3/day, ADV on a roll made in service of knight's order.
```

## Kobold
```statblock
name: Kobold
layout: Shadowdark Monster
image: [[Kobold.png]]
description: Puny, scaled coyote-lizards that dwell underground.
ac: 13 (leather)
hp: 1
actions:
  - name: Spear x1
    desc: (close/near) +0 (1d6)
mv: near
stats: [-2,+2,+0,-1,+0,-1]
alignment: Chaotic
level: 0
traits:
  - name: Dodge
    desc: 1/day, an attack that would hit misses instead.
```

## Kobold, Sorcerer
```statblock
name: Kobold, Sorcerer
layout: Shadowdark Monster
image:
description: A scaly dog-lizard painted with colorful stripes and rattling a hefty leg bone strung with beads and feathers.
ac: 13 (leather)
hp: 13
actions:
  - name: Club x1
    desc: +1 (1d4)
  - name: Spell x1
    desc: +2,
mv: near
stats: [-2,+2,+0,-1,+1,+2]
alignment: Chaotic
level: 3 
traits:
  - name: Dodge
    desc: 1/day, an attack that would hit misses instead.
spells:
  - name: Scorpion Sting (CHA Spell)
    desc: DC 11. Near range, one target. 1d6 damage and target has DISADV on next attack roll or check.
  - name: Spider Swarm (CHA Spell)
    desc: DC 12. A spider swarm appears within near. Stays 1d4 rounds. Follows sorcerer's commands.
```

## Kraken
```statblock
name: Kraken
layout: Shadowdark Monster
image:
description: Primordial, tentacled leviathans the size of war galleons. They live in the lightless depths of the deep ocean.
ac: 18
hp: 80
actions:
  - name: Tentacles x4
    desc: (near) +9 (2d12)
  - name: Storm x1
    desc: <see below>
  - name: Lightning Bolt x1d4
    desc: <see below>
mv: double near (swim)
stats: [+6,+3,+4,+4,+3,+4]
alignment: Chaotic
level: 17
traits:
  - name: Impervious
    desc: Electricity immune.
  - name: Crush
    desc: Tentacle attacks deal double damage against objects.
  - name: Lightning Bolt
    desc: Straight line (5' wide) extending far from kraken. DC 15 DEX or 6d6 damage.
  - name: Storm
    desc: Seas become violently turbulent in 1 mile radius around kraken. Lasts 2d4 rounds. Seaborne vessels have a 1:6 chance of capsizing each round.
```

## Leech, Giant
```statblock
name: Leech, Giant
layout: Shadowdark Monster
image: [[Leech, GIant.png]]
description: A glossy black, blood-drinking slug as large as a cat.
ac: 9
hp: 10
actions:
  - name: Bite x1
    desc: +1 (1d4 + attach)
mv: near (swim)
stats: [+1,-1,+1,-3,-1,-3]
alignment: Neutral
level: 2
traits:
  - name: Attach
    desc: Attach to target; bite auto-hits next round. DC 12 STR on turn to tear off.
```

## Leprechaun
```statblock
name: Leprechaun
layout: Shadowdark Monster
image:
description: Impish fey who favor green garb and love fooling "tall folk" with promises of gold.
ac: 13
hp: 19
actions:
  - name: Spell x1
    desc: +4,
mv: near
stats: [+1,+3,+1,+2,+1,+3]
alignment: Neutral
level: 4
traits:
  - name: Alert
    desc: Cannot be surprised.
  - name: Slippery
    desc: Hostile spells targeting the leprechaun are DC 15 to cast.
spells:
  - name: Fool's Gold (CHA Spell)
    desc: DC 12. Close. One small object or small group of similar objects. Turn objects into silver or gold pieces. Lasts 1 day.
  - name: Illusion (CHA Spell)
    desc: DC 11. Create a convincing visual and or auditory illusion within near. Lasts until dismissed.
  - name: Invisibility (CHA Spell)
    desc: DC 12. Self. Become invisible for 2d4 rounds.
```

## Lich
```statblock
name: Lich
layout: Shadowdark Monster
image:
description: A wizard who has completed a necromantic ritual to become a mighty, undead sorcerer. Its withered body is draped in moldering, silk robes, and red marshlights burn in its eyes.
ac: 16
hp: 62
actions:
  - name: Touch x2
    desc: +6 (2d8 + paralysis)
  - name: Cast Spell x2
    desc: +7,
mv: near
stats: [+3,+1,+4,+4,+3,+3]
alignment: Chaotic
level: 13
traits:
  - name: Supreme Undead
    desc: Immune to morale checks. Only damaged by magical sources.
  - name: Phylactery
    desc: Can't be killed while spirit vessel (an object) is intact. 
  - name: Paralysis
    desc: DC 15 CON or paralyzed 1d4 rounds.
spells:
  - name: Flight (INT Spell)
    desc: Self. DC 13. Fly double near for 5 rounds.
  - name: Null (INT Spell)
    desc: Self. DC 14. Hostile spells targeting lich are DC 18 to cast. Lasts 1d4 rounds.
  - name: Shadow Leap (INT Spell)
    desc: Self. DC 14. Teleport up to 100 miles.
  - name: Sigil of Doom (INT Spell)
    desc: DC 15. One target of LV 9 or less within near DC 15 CON or go to 0 HP.
  - name: Wither (INT Spell)
    desc: DC 14. 4d8 damage to enemies within a near-sized cube centered on lich.
```

## Lion
```statblock
name: Lion
layout: Shadowdark Monster
image:
description: Tawny great cats that hunt in open plains. Males have manes.
ac: 12
hp: 15
actions:
  - name: Rend x2
    desc: +4 (1d8)
mv: near
stats: [+4,+2,+2,-3,+1,-3]
alignment: Neutral
level: 3
```

## Lizardfolk
```statblock
name: Lizardfolk
layout: Shadowdark Monster
image:
description: Crocodilian humanoids with scaly faces, claws, and tails. They dwell in swamps and rivers.
ac: 14 (leather + shield)
hp: 11
actions:
  - name: Spear x1
    desc: (close/near) +2 (1d6)
mv: near (swim)
stats: [+1,+1,+2,-1,+1,-2]
alignment: Chaotic
level: 2
```

## Mage
```statblock
name: Mage
layout: Shadowdark Monster
image:
description: Trained wizards who are often members of a sorcerous order.
ac: 11
hp: 27
actions:
  - name: Cast Spell x1
    desc: +5,
mv: near
stats: [-1,+1,+0,+3,+1,+0]
alignment: Lawful
level: 6
spells:
  - name: Arcane Armor (INT Spell)
    desc: Self. DC 12. AC 16 for 2d4 rounds.
  - name: Blast (INT Spell)
    desc: DC 12. Far, one target. 2d6 damage.
  - name: Cancel (INT Spell)
    desc: DC 13. End one spell affecting a target within near.
  - name: Levitate (INT Spell)
    desc: DC 12. Close. Focus. Hover near for duration, vertical movement only.
  - name: Snare (INT Spell)
    desc: DC 13. Focus. One humanoid target within near paralyzed for duration.
```

## Mammoth
```statblock
name: Mammoth
layout: Shadowdark Monster
image:
description: Massive, shaggy elephants with tusks that reach the ground.
ac: 15
hp: 44
actions:
  - name: Tusks x2
    desc: +7 (1d12)
mv: near
stats: [+5,+0,+4,-2,+1,+0]
alignment: Neutral
level: 9
traits:
  - name: Thick Fur
    desc: Cold immune.
  - name: Charge
    desc: Move up to double near in straight line and make 1 tusks attack. If hit, x3 damage.
```

## Manta Ray, Giant
```statblock
name: Manta Ray, Giant
layout: Shadowdark Monster
image:
description: Swooping manta rays as large as longboats. Gentle and intelligent enough to be trained.
ac: 13
hp: 37
actions:
  - name: Sting x2
    desc: +5 (1d12 + poison)
mv: double near (swim)
stats: [+3,+3,+1,-2,+1,-3]
alignment: Neutral
level: 8
traits:
  - name: Poison
    desc: DC 15. CON or drop to 0 hit points in 1d4 rounds.
```

## Manticore
```statblock
name: Manticore
layout: Shadowdark Monster
image:
description: Human-faced lions with bat wings and cruelly spiked tails. They speak halting Thanian and love devouring human flesh.
ac: 14
hp: 29
actions:
  - name: Rend x2
    desc: +6 (2d6)
  - name: Tail Spike x2
    desc: (far) +4 (1d8)
mv: double near (fly)
stats: [+4,+2,+2,-2,+1,-2]
alignment: Chaotic
level: 6
traits:
  - name: Spikes
    desc: Manticores have 4d6 tail spikes. They regrow each day.
```

## Mastiff
```statblock
name: Mastiff
layout: Shadowdark Monster
image:
description: Muscled guard dogs with fierce loyalty to their pack or owners.
ac: 11
hp: 4
actions:
  - name: Bite x1
    desc: +1 (1d6)
mv: near
stats: [+1,+1,+0,-2,+1,-2]
alignment: Neutral
level: 1
```

## Medusa
```statblock
name: Medusa
layout: Shadowdark Monster
image:
description: Immortal women with coiling snakes for hair and scaled skin.
ac: 14
hp: 38
actions:
  - name: Snake Bite x1
    desc: +6 (1d6 + poison)
mv: near
stats: [+2,+1,+2,+2,+3,+4]
alignment: Chaotic
level: 8
traits:
  - name: Godborn
    desc: Hostile spells targeting the medusa are DC 15 to cast.
  - name: Petrify
    desc: Any creature (including medusa) who looks directly at medusa, DC 15 CON or petrified.
  - name: Poison
    desc: DC``` 15 CON or go to 0 HP.
```

## Merfolk
```statblock
name: Merfolk
layout: Shadowdark Monster
image:
description: Ocean dwellers with human upper bodies and long fish tails.
ac: 11
hp: 9
actions:
  - name: Spear x1
    desc: (close/near) +2 (1d6)
mv: near (swim)
stats: [+1,+1,+0,+0,+1,+1]
alignment: Lawful
level: 2
```

## Mimic
```statblock
name: Mimic
layout: Shadowdark Monster
image:
description: Beasts that look like objects.
ac: 12
hp: 23
actions:
  - name: Bite x2
    desc: +5 (1d8 + stick)
mv: near
stats: [+2,+0,+1,-2,+0,-3]
alignment: Neutral
level: 5
traits:
  - name: Stick
    desc: DC 15 STR or adhere to target; auto-hit with bite. DC 15 STR on turn to remove.
```

## Minotaur
```statblock
name: Minotaur
layout: Shadowdark Monster
image: [[Minotaur.png]]
description: Ferocious bull-men with hooves and curved horns. They live in mazelike tunnels.
ac: 14 (chainmail)
hp: 34
actions:
  - name: Greataxe x2
    desc: +6 (1d10)
  - name: Horns x1
    desc: +6 (1d12)
mv: near
stats: [+4,+1,+3,+1,+2,+1]
alignment: Chaotic
level: 7
traits:
  - name: Charge
    desc: In place of attacks, move up to double near in a straight line and make 1 horn attack. If hit, x2 damage.
```

## Moose
```statblock
name: Moose
layout: Shadowdark Monster
image: [[Moose.png]]
description: A towering, brown-haired grazer with weighty, flat antlers.
ac: 11
hp: 19
actions:
  - name: Antler x2
    desc: +3 (1d6)
mv: double near
stats: [+3,+0,+1,-2,+0,-2]
alignment: Neutral
level: 4
```

## Mordanticus the Flayed
```statblock
name: Mordanticus the Flayed
layout: Shadowdark Monster
image:
description: A skinless mummy-lich wearing a crown set with nine bright gems. Once the head of the ancient, wizardly order of Gehemna, Mordanticus now lives in secret within the sanctum of Gehemna's reigning archmage. He has served as an advisor and historian for centuries, but an enduring enchantment prevents him from speaking of two topics... his origins, and The Ten-Eyed Oracle.
ac: 17
hp: 89
actions:
  - name: Rot Touch x1
    desc: +8 (1d10 + necrosis) AND
  - name: Spell x3
    desc: +8,
mv: near
stats: [+4,+4,+4,+5,+4,+5]
alignment: Neutral
level: 19
traits:
  - name: Legendary Undead
    desc: Immune to morale checks. Only damaged by magical sources. Hostile spells targeting Mordanticus are DC 18 to cast.
  - name: Crown of Gehemna
    desc: 3/day, cause a spell being cast within far to fail.
  - name: Necrosis
    desc: DC 15 CON or go to 0 HP. Healing spells are DC 15 to cast on target while at 0 hp due to this effect.
  - name: Phylactery
    desc: Cannot be killed while spirit vessel (a diamond) is intact.
spells:
  - name: Absorb (INT Spell)
    desc: DC 13. Near, one target. Target loses the ability to cast one random spell until completing a rest, and Mordanticus regains a lost spell of the same tier or less.
  - name: Banish (INT Spell)
    desc: DC 14. All extradimensional creatures within near DC 15 CHA or sent back to their home planes.
  - name: Bind (INT Spell)
    desc: DC 12. One humanoid in far paralyzed 1d4 rounds.
  - name: Blast (INT Spell)
    desc: DC 14. One creature in near takes 5d8 damage.
  - name: Phase (INT Spell)
    desc: DC 13. Self. Teleport up to one mile.
  - name: True Name (INT Spell)
    desc: DC 15. Near. Learn the _True Name_ of target.
```
> [!quote]
> “Long have I held the weighty secrets of Gehemna, an age-old litany inscribed upon my weary soul."
>- _Mordanticus the Flayed_


## Mummy
```statblock
name: Mummy
layout: Shadowdark Monster
image:
description: A desiccated, linen-wrapped zombie. It was created with an intricate embalming ritual used only upon the most worthy warriors or rulers.
ac: 13
hp: 47
actions:
  - name: Rot Touch x3
    desc: +8 (1d10 + necrosis)
mv: near
stats: [+3,+0,+2,+3,+2,+3]
alignment: Chaotic
level: 10
traits:
  - name: Supreme Undead
    desc: Immune to morale checks. Only damaged by magical sources.
  - name: Desiccated
    desc: Can be damaged by fire. Takes x2 damage from it.
  - name: Necrosis
    desc: DC 15. CON or drop to 0 HP. Healing spells are DC 15 to cast on target while at 0 HP due to this effect.
```

## Mushroomfolk
```statblock
name: Mushroomfolk
layout: Shadowdark Monster
image:
description: Lumbering humanoids with spongy, elongated bodies and toadstools on their heads.
ac: 13
hp: 15
actions:
  - name: Slam x2
    desc: +2 (1d6),
mv: near
stats: [+2,-1,+2,+0,+1,+0]
alignment: Neutral
level: 3
traits:
  - name: Sunblind
    desc: Blinded in bright light.
  - name: Telepathic
    desc: Speak mentally with creatures within double near.
```

## Naga
```statblock
name: Naga
layout: Shadowdark Monster
image:
description: Magic-wielding cobras towering ten feet high. Once a dominant species, they are now rare and reclusive, bitter to the last.
ac: 16
hp: 43
actions:
  - name: Bite x2
    desc: +7 (2d6 + poison) AND
  - name: Spell x1
    desc: +7,
mv: near (climb)
stats: [+4,+1,+3,+2,+2,+4]
alignment: Chaotic
level: 9
traits:
  - name: Poison
    desc: DC 15 CON or paralyzed 1d4 rounds.
spells:
  - name: Agony (CHA Spell)
    desc: DC 14. One target in near takes 3d8 damage.
  - name: Hypnotize (CHA Spell)
    desc: DC 13. Focus. One target in near range who can see naga is helplessly stupefied for duration.
  - name: Whispers (CHA Spell)
    desc: DC 12. Hostile spells cast on one target in near are DC 9 for 1d4 rounds.
```

## Naga, Bone
```statblock
name: Naga, Bone
layout: Shadowdark Monster
image:
description: Mindless, skeletal husks of nagas reanimated by sorcery.
ac: 13
hp: 31
actions:
  - name: Bite x2
    desc: +5 (2d6)
mv: near (burrow, climb)
stats: [+3,+2,+4,-3,+0,+4]
alignment: Chaotic
level: 6
traits:
  - name: Greater Undead
    desc: Immune to morale checks. Only damaged by silver or magical sources.
```

## Nightmare
```statblock
name: Nightmare
layout: Shadowdark Monster
image:
description: Black warhorses with flaming manes, hooves, and eyes.
ac: 13
hp: 29
actions:
  - name: Hooves x2
    desc: +5 (1d8)
mv: double near (fly)
stats: [+3,+3,+2,-1,+1,-2]
alignment: Chaotic
level: 6
traits:
  - name: Impervious
    desc: Nightmare and its rider immune to fire.
```

## Obe-Ixx Of Azarumme
```statblock
name: Obe-Ixx Of Azarumme
layout: Shadowdark Monster
image:
description: A pale, angular woman in translucent plate mail fashioned from giant scorpion chitin. Obe-Ixx, daughter of Azarumme, rose up from the prehistoric barbarian tribes of Tal-Yoolo conquer all in her path. One day, she stood at the steps of an obsidian ziggurat deep within the trackless jungle. Forty nights later, Obe-Ixx emerged as the ur-vampire, bloodlust made flesh. Her dynasty would rise and fall again and again over the coming millennia._

ac: 18 (+3 plate mail)
hp: 76
actions:
  - name: Greatsword x4
    desc: (near) +11 (1d12 + 2 + Moonbite properties) AND
  - name: Bite x1
    desc: +9 (1d8 + blood drain) AND
  - name: Charm x1
    desc: <see below>
mv: near (climb, fly)
stats: [+5,+3,+4,+3,+4,+5]
alignment: Chaotic
level: 16
traits:
  - name: Legendary Undead
    desc: Immune to morale checks. Only damaged by magical sources. Hostile spells targeting Obe-Ixx are DC 18 to cast.
  - name: Blood Drain
    desc: Obe-Ixx heals 2d8 HP, target permanently loses 1d6 CON. At 0 CON, target dies and rises as a loyal vampire or vampire spawn (Obe-Ixx chooses).
  - name: Charm
    desc: One humanoid target who can see Obe-Ixx within near, DC 15 CHA or under Obe-Ixx's control for 1d4 days.
  - name: Dire Shapechange
    desc: In place of attacks, turn into a giant bat, dire wolf, or back into regular form.
  - name: Moonbite Properties
    desc: +2 greatsword, thrown weapon, returns after being thrown. Spells to heal damage it inflicts are DC 15 to cast
  - name: Ur-Vampire
    desc: Must sleep in sarcophagus at least once per moon cycle or loses 2d8 HP per day that cannot heal until sleeping in sarcophagus. Takes 3d8 damage each round while in direct sunlight. Cannot be killed unless pierced through heart while at 0 HP with a wooden stake carved from a tree from the Tal-Yool jungle.
```
> [!quote]
> “By this blade, the empire of Azarumme shall rise again!"
> -Obe-Ixx of Azarumme

## Ochre Jelly
```statblock
name: Ochre Jelly
layout: Shadowdark Monster
image: [[Ochre Jelly.png]]
description: An orange puddle of quivering slime.
ac: 9
hp: 20
actions:
  - name: Tentacle x2
    desc: +3 (1d6)
mv: near (climb)
stats: [+2,-1,+2,-4,-3,-4]
alignment: Neutral
level: 4
traits:
  - name: Split
    desc: If cut or chopped, split into two smaller oozes (divide remaining HP between both). Can split up to four times.
```

## Octopus, Giant
```statblock
name: Octopus, Giant
layout: Shadowdark Monster
image:
description: Octopi as large as sailing skiffs.
ac: 13
hp: 23
actions:
  - name: Tentacle x2
    desc: (near) +4 (1d8 + grab)
mv: near (swim)
stats: [+3,+3,+1,-2,+1,-3]
alignment: Neutral
level: 5
traits:
  - name: Grab
    desc: DC 15 STR or immobilized. Tentacle auto-hits each round. DC 15 STR on turn to break free.
  - name: Ink
    desc: In place of attacks, ink cloud blinds all in near for 1d4 rounds.
```

## Ogre
```statblock
name: Ogre
layout: Shadowdark Monster
image: [[Ogre.png]]
description: A massive, dim-witted brute with tusks and a heavy frame. Often lords over goblins or orcs.
ac: 9
hp: 30
actions:
  - name: Greatclub x2
    desc: +6 (2d6)
mv: near
stats: [+4,-1,+3,-2,-2,-2]
alignment: Chaotic
level: 6
```

## Oni
```statblock
name: Oni
layout: Shadowdark Monster
image:
description: Cunning and sorcerous ogre-demons with shaggy white hair, blue skin, and yellow eyes.
ac: 11
hp: 33
actions:
  - name: Glaive x1
    desc: (near) +6 (1d10)
  - name: Spell x1
    desc: +5,
mv: near
stats: [+5,+1,+2,+2,+1,+3]
alignment: Chaotic,
level: 7
traits:
  - name: Shapeshift
    desc: In place of attacks, turn into any humanoid or back into original form.
spells:
  - name: Fade (CHA Spell)
    desc: DC 13. Self. Become invisible for 1d4 rounds.
  - name: Hellfrost (CHA Spell)
    desc: DC 13. All within near-sized cube extending from oni 3d6 damage.
  - name: Mist (CHA Spell)
    desc: DC 13. Self. Turn into mist that can fly double near. Lasts 2d4 rounds.
```

## Orc
```statblock
name: Orc
layout: Shadowdark Monster
image: [[Orc.png]]
description: A tusked, tall humanoid with gray skin and pointed ears.
ac: 15 (chainmail + shield)
hp: 4,
actions:
  - name: Greataxe x1
    desc: +2 (1d8)
mv: near,
stats: [+2,+0,+0,-1,+0,-1]
alignment: Chaotic
level: 1
traits:
  - name: Rage
    desc: 1/day, immune to morale checks,+1d4 damage (3 rounds).
```

## Orc, Chieftain
```statblock
name: Orc, Chieftain
layout: Shadowdark Monster
image:
description: An imposing orc with scars crisscrossing its body.
ac: 14 (chainmail)
hp: 19
actions:
  - name: Greataxe x2
    desc: +4 (1d10)
mv: near
stats: [+2,+1,+1,-1,+0,-1]
alignment: Chaotic
level: 4
traits:
  - name: Rage
    desc: 1/day, immune to morale checks,+1d4 damage (3 rounds).
```

## Otyugh
```statblock
name: Otyugh
layout: Shadowdark Monster
image:
description: Stumpy, three-legged beasts with barbed tentacles and vast mouths. Drawn by rot and filth.
ac: 13
hp: 35
actions:
  - name: Tentacles x2
    desc: +5 (1d8) AND
  - name: Bite x1
    desc: +5 (1d10 + disease)
mv: near
stats: [+4,-1,+4,-2,+0,-3]
alignment: Neutral
level: 7
traits:
  - name: Disease
    desc: DC 15 CON or infected. DC 15 CON each day or lose 1d6 HP (can't heal). Ends on success.
```

# Outsiders

Alien horrors from the frozen, outer reaches of the cosmos or the Chaos-infused Dark Realms.

Outsiders were born from the nightmares of gods and are unsettling to all other creatures.


## Primordial Slime
```statblock
name: Primordial Slime
layout: Shadowdark Monster
image:
description: A mass of clear ooze strobing with sick pulses of violet light.
ac: 9
hp: 30
actions:
  - name: Tentacle x2
    desc: +4 (1d10 + dissolve)
mv: near (climb)
stats: [+3,+2,+3,-4,-3,-4,]
alignment: Chaotic
level: 6
traits:
  - name: Impervious
    desc: Only harmed by fire.
  - name: Dissolve
    desc: One random piece of non-magical gear the target carries is destroyed.
```

## Void Spawn
```statblock
name: Voidspawn
layout: Shadowdark Monster
image:
description: Scythe-like limbs jut from a purple bulb as big as an ogre. Its lower half is a nest of tentacles.
ac: 13
hp: 34
actions:
  - name: Scythe x2
    desc: +6 (1d10) AND
  - name: Tentacles x1
    desc: +6 (1d12 + toxin)
mv: near (fly)
stats: [+4,+1,+3,+0,+1,-1]
alignment: Chaotic
level: 7
traits:
  - name: Impervious
    desc: Immune to cold. Toxin. DC 12 CON or paralyzed for 1d4 rounds.
```

## Void Spider
```statblock
name: Void Spider
layout: Shadowdark Monster
image:
description: Pale, horse-sized arachnids that become ghostly and intangible.
ac: 13
hp: 23
actions:
  - name: Bite x2
    desc: +4 (1d8 + poison)
mv: near (climb)
stats: [+3,+3,+1,-1,+1,-2]
alignment: Chaotic,
level: 5
traits:
  - name: Impervious
    desc: Immune to cold.
  - name: Phase
    desc: Once per round, become corporeal or incorporeal.
  - name: Poison
    desc: DC 12 CON or drop to 0 HP in 1d4 rounds.
```

## Rime Walker
```statblock
name: Rime Walker
layout: Shadowdark Monster
image:
description: Human-shaped beings formed from black space ice. Their eyes are two flickering, white lights.
ac: 16
hp: 43
actions:
  - name: Claw x4
    desc: +8 (1d12)
mv: near (fly)
stats: [+4,+4,+3,+2,+2,+2]
alignment: Chaotic
level: 9
traits:
  - name: Impervious
    desc: Immune to cold.
  - name: Ice Aura
    desc: Enemies within near of rime walker DC 12 CON at start of turn or lose action.
```

## Owlbear
```statblock
name: Owlbear
layout: Shadowdark Monster
image:
description: Cantankerous bears with owl eyes, beaks, and feathers.
ac: 13
hp: 30
actions:
  - name: Claw x2
    desc: +5 (1d10)
mv: near (climb)
stats: [+4,+1,+3,-2,+2,-3]
alignment: Neutral
level: 6
traits:
  - name: Crush
    desc: Deals an extra die of damage if it hits the same target with both claws.
```

## Panther
```statblock
name: Panther
layout: Shadowdark Monster
image:
description: Supple large cats with blue-black fur. Stealthy hunters.
ac: 14
hp: 14
actions:
  - name: Rend x2
    desc: +3 (1d6)
mv: near (climb)
stats: [+3,+4,+1,-2,+1,-3]
alignment: Neutral
level: 3
```

## Peasant
```statblock
name: Peasant
layout: Shadowdark Monster
image: [[Peasant.png]]
description: A commoner in worn clothes.
ac: 10
hp: 4
actions:
  - name: Club x1
    desc: +0 (1d4)
mv: near
stats: [+0,+0,+0,+0,+0,+0]
alignment: Lawful
level: 1
```

## Pegasus
```statblock
name: Pegasus
layout: Shadowdark Monster
image:
description: Winged horses with noble bearings and pearly white coats.
ac: 12
hp: 15
actions:
  - name: Hooves x2
    desc: +3 (1d6)
mv: double near (fly)
stats: [+3,+2,+2,-3,+1,+0]
alignment: Neutral
level: 3
```

## Phoenix
```statblock
name: Phoenix
layout: Shadowdark Monster
image:
description: Huge, soaring eagles made of searing flames. Intelligent and imbued with immortal magic.
ac: 16
hp: 60
actions:
  - name: Rend x4
    desc: +8 (2d12)
mv: double near (fly)
stats: [+3,+4,+2,+3,+3,+3]
alignment: Lawful
level: 13
traits:
  - name: Impervious
    desc: Immune to fire. Only damaged by magical sources.
  - name: Explosion
    desc: Upon death, creatures within double near of phoenix DC 18 DEX or 10d6 damage.
  - name: Heat Aura
    desc: Creatures within near of phoenix at start of turn DC 15 CON or 2d6 damage.
  - name: Rebirth
    desc: A red-hot egg remains after death. Phoenix hatches from it in 1d4 days.
```

## Piranha, Swarm
```statblock
name: Piranha, Swarm
layout: Shadowdark Monster
image:
description: A school of flat, silvery fish with vicious fangs.
ac: 12
hp: 13
actions:
  - name: Bite x2
    desc: +2 (1d6)
mv: near (swim)
stats: [-2,+2,+0,-3,+0,-3]
alignment: Neutral
level: 3
traits:
  - name: Savage
    desc: ADV on attacks against creatures below half their HP.
```

## Pirate
```statblock
name: Pirate
layout: Shadowdark Monster
image:
description: Seafaring scoundrels who live to steal and hoard treasure.
ac: 12 (leather)
hp: 4
actions:
  - name: Cutlass x1
    desc: +1 (1d6)
  - name: Dagger x1
    desc: (close/near) +1 (1d4)
mv: near
stats: [+1,+1,+0,+0,+0,+0]
alignment: Chaotic
level: 1
```

## Priest
```statblock
name: Priest
layout: Shadowdark Monster
image:
description: A respected member of a clergy who leads holy rituals and rites.
ac: 15 (chainmail + shield)
hp: 23
actions:
  - name: Mace x2
    desc: +3 (1d6)
  - name: Spell x1
    desc: +3,
mv: near
stats: [+1,+0,+1,+0,+2,+1]
alignment: Lawful
level: 5
spells:
  - name: Anoint (WIS Spell)
    desc: DC 12. Close. One weapon or armor becomes a magic +2 version for 10 rounds.
  - name: Healing Touch (WIS Spell)
    desc: DC 11. Heal one creature within close for 2d4 HP.
  - name: Holy Flame (WIS Spell)
    desc: DC 13. Self. Weapons ignite in magic flames and deal an additional 1d6 damage for 5 rounds.
  - name: Rebuke (WIS Spell)
    desc: DC 13. Focus. Chaotic creatures cannot attack priest or come within near range for duration.
```

## Purple Worm
```statblock
name: Purple Worm
layout: Shadowdark Monster
image:
description: A massive worm as tall as a castle keep. Has a rotating maw and is covered in purple chitin.
ac: 18
hp: 57
actions:
  - name: Bite x2
    desc: +9 (2d12 + swallow) AND
  - name: Sting x1
    desc: +9 (1d10 + poison)
mv: double near (burrow)
stats: [+5,+1,+3,-3,+1,-3]
alignment: Neutral
level: 12
traits:
  - name: Poison
    desc: DC 15 CON or go to 0 HP.
  - name: Swallow
    desc: On a natural attack roll of 18-20, target is swallowed. Total darkness inside and 2d10 damage per round. Worm regurgitates all swallowed if dealt at least 20 damage in one round to the inside of its gullet.
```

## Rakshasa
```statblock
name: Rakshasa
layout: Shadowdark Monster
image:
description: Demonic illusionists whose true form is of a humanlike great cat with backwards hands.
ac: 16
hp: 39
actions:
  - name: Claw x2
    desc: +6 (1d8),
mv: near
stats: [+1,+3,+3,+3,+3,+4]
alignment: Chaotic
level: 8
traits:
  - name: Impervious
    desc: Only damaged by magical sources. Immune to hostile spells of 3rd tier or lower.
  - name: Mesmerism
    desc: Can read the minds of all creatures within near. Can instantly take on the illusory appearance of any humanoid.
  - name: Weakness
    desc: A crossbow bolt under the effects of the holy weapon spell kills the rakshasa.
```

## Rat
```statblock
name: Rat
layout: Shadowdark Monster
image:
description: Rangy, plague-carrying rodents that infest underground places.
ac: 10
hp: 1
actions:
  - name: Bite x1
    desc: +0 (1 + disease)
mv: near
stats: [-3,+0,+1,-3,+1,-3]
alignment: Neutral
level: 0
traits:
  - name: Disease
    desc: DC 9 CON or 1d4 CON damage (can't heal while ill). Repeat check once per day; ends on success. Die at 0 CON.
```

## Rat, Giant
```statblock
name: Rat, Giant
layout: Shadowdark Monster
image: [[Rat, Giant.png]]
description: Cunning rats as large as cats. Mangy fur and wormlike tails.
ac: 11
hp: 5
actions:
  - name: Bite x1
    desc: +1 (1d4 + disease)
mv: near
stats: [-2,+1,+1,-2,+1,-2]
alignment: Neutral
level: 1
traits:
  - name: Disease
    desc: DC 12 CON or 1d4 CON damage (can't heal while ill). Repeat check once per day; ends on success. Die at 0 CON.
```

## Rat, Dire
```statblock
name: Rat, Dire
layout: Shadowdark Monster
image:
description: Child-sized, savage rats bristling with bony face and spine ridges.
ac: 12
hp: 10
actions:
  - name: Bite x1
    desc: +2 (1d6 + disease)
mv: near
stats: [+1,+2,+1,-2,+1,-2]
alignment: Neutral, 
level: 2
traits:
  - name: Disease
    desc: DC 12 CON or 1d4 CON damage (can't heal while ill). Repeat check once per day; ends on success. Die at 0 CON.
```

## Rat, Swarm
```statblock
name: Rat, Swarm
layout: Shadowdark Monster
image:
description: A screeching tidal wave of clawing and biting rats.
ac: 10
hp: 28
actions:
  - name: Bite x4
    desc: +0 (1 + disease)
mv: near
stats: [-3,+0,+1,-3,+1,-3]
alignment: Neutral
level: 6
traits:
  - name: Disease
    desc: DC 9 CON or 1d4 CON damage (can't heal while ill). Repeat check once per day; ends on success. Die at 0 CON.
```

## Rathgamnon
```statblock
name: Rathgamnon
layout: Shadowdark Monster
image:
description: A pearl-white lion with feathered wings that stands twenty feet tall. Rathgamnon is [[Madeera the Covenant]]'s mightiest servant; his blank eyes see far into the depths ofime and space. He spends all eternity watching the whirl of the stars from the highest mountain in the realm of mortals, waiting for the celestial alignments that prophesy epochs of weal and woe, titanic changes to the balance of power in the cosmos, or threats to the laws of reality itself.
ac: 17
hp: 89
actions:
  - name: Rend x2
    desc: (near) +9 (2d10) AND
  - name: Spell x2
    desc: +8,
mv: double near (fly)
stats: [+5,+3,+4,+5,+6,+5]
alignment: Lawful
level: 19
traits:
  - name: Legendary
    desc: Only damaged by magical sources. Hostile spells targeting Rathgamnon are DC 18. to cast.
  - name: Roar
    desc: In place of attacks, all creatures who can hear within far DC 18 CHA or be rendered blind and speechless for 1d4 days.
spells:
  - name: Abjure (WIS Spell)
    desc: DC 13. Self. End any hostile magical effects affecting Rathgamnon.
  - name: Abolish (WIS Spell)
    desc: DC 13. One target in far takes 5d8 damage.
  - name: Anchor (WIS Spell)
    desc: DC 14. One target in far DC 18 STR or bound and anchored by chains of golden runes for 1d4 rounds.
  - name: Gate (WIS Spell)
    desc: DC 14. Open a portal at a point within near to another location on any plane. Lasts 1d6 rounds or until dismissed.
  - name: Portent (WIS Spell)
    desc: DC 14. Lasts 2d4 rounds. One target in near has advantage or disadvantage on all attack rolls and checks.
  - name: Time Stop (WIS Spell)
    desc: DC 15. Self. Time freezes for everyone except Rathgamnon for 1d4 rounds. Everything that occurs during the time freeze happens simultaneously when the spell ends.
```
> [!quote]
> “The stars told me of your arrival here many eons ago, long before the first of your people walked the earth."
> -Rathgamnon

## Reaver
```statblock
name: Reaver
layout: Shadowdark Monster
image: [[Reaver.png]]
description: A knight in blackened armor riddled with cruel barbs.
ac: 17 (plate mail + shield)
hp: 28,
actions:
  - name: Bastard Sword x3
    desc: +4 (1d8 + 2)
mv: near
stats: [+3,+0,+1,+0,+0,+2]
alignment: Chaotic
level: 6
traits:
  - name: Bloodlust
    desc: +2 damage with melee weapons (included).
```

## Remorhaz
```statblock
name: Remorhaz
layout: Shadowdark Monster
image:
description: Massive, blue centipedes with neck hoods and red-hot spine spikes. Dwell in arctic climates.
ac: 16
hp: 47
actions:
  - name: Bite x3
    desc: +7 (2d6 + swallow)
mv: near (burrow)
stats: [+5,+1,+2,-3,+1,-3]
alignment: Neutral
level: 10
traits:
  - name: Impervious
    desc: Immune to cold and fire.
  - name: Melt
    desc: Non-magical metal objects that touch the remorhaz melt on a d6 roll of 1-3.
  - name: Swallow
    desc: On a natural attack roll of 18-20, target is swallowed. Total darkness inside and 2d10 damage per round. Remorhaz regurgitates all swallowed if dealt at least 20 damage in one round to the inside of its gullet.
```

## Rhinoceros
```statblock
name: Rhinoceros
layout: Shadowdark Monster
image:
description: Gray-skinned bulls with single nose horns. Dwell in grasslands.
ac: 14
hp: 25
actions:
  - name: Horn x2
    desc: +4 (1d8)
mv: near
stats: [+4,-1,+3,-3,+0,-3]
alignment: Neutral
level: 5
traits:
  - name: Charge
    desc: Move up to double near in straight line and make 1 horn attack. If hit, x3 damage.
```

## Roc
```statblock
name: Roc
layout: Shadowdark Monster
image:
description: Dragon-sized hawks that nest in remote mountains.
ac: 15
hp: 69
actions:
  - name: Rend x4
    desc: +9 (2d10 + grab)
mv: double near (fly)
stats: [+5,+3,+2,-2,+2,-2,]
alignment: Neutral
level: 15
traits:
  - name: Grab
    desc: DC 18 STR or target held. DC 18 STR on turn to break free.
```

## Roper
```statblock
name: Roper
layout: Shadowdark Monster
image:
description: Ravenous monstrosities that look like cave rocks when their single eye and maw are closed.
ac: 14
hp: 31
actions:
  - name: Tendril x4
    desc: (double near) +4 (1d6 + grab) AND
  - name: Bite x1
    desc: +4 (2d8)
mv: close (climb)
stats: [+3,-2,+4,-1,+2,+1,]
alignment: Neutral,
level: 6
traits:
  - name: Impervious
    desc: Can only be damaged by magical sources.
  - name: Grab
    desc: DC 15 STR or target trapped in tendril. Tendril auto-hits target next round. DC 15 STR on turn to break free.
  - name: Pull
    desc: In place of a tendril attack, pull a grabbed target a near distance.
  - name: Tendrils
    desc: Four total. AC 18 each. 4+ damage to one severs it.
```

## Rot Flower
```statblock
name: Rot Flower
layout: Shadowdark Monster
image:
description: Carnivorous flowers as large as a human. They reek of carrion.
ac: 9
hp: 10
actions:
  - name: Bite x1
    desc: +1 (1d4 + toxin)
mv: none
stats: [+1,-3,+1,-4,-3,-4]
alignment: Neutral
level: 2
traits:
  - name: Toxin
    desc: DC``` 12 CON or unconscious for 1d4 rounds.
```

## Rust Monster
```statblock
name: Rust Monster
layout: Shadowdark Monster
image: [[Rust Monster.png]]
description: A mud-brown insect as big as a wolf with two feathery antennae. Consumes metal.
ac: 13
hp: 19
actions:
  - name: Claw x2
    desc: +3 (1d6)
mv: near (climb)
stats: [+2,+3,+1,-3,+1,-3]
alignment: Neutral
level: 4
traits:
  - name: Corrosive
    desc: Metal that touches the rust monster is destroyed on a d6 roll of 1-3.
```

## Sahuagin
```statblock
name: Sahuagin
layout: Shadowdark Monster
image:
description: Humanoids with sea-green skin, webbed limbs, and shark teeth. Vicious hunters.
ac: 14 (leather + shield)
hp: 9,
actions:
  - name: Trident x2
    desc: (near) +1 (1d6)
mv: near (swim)
stats: [+1,+1,+0,-1,+0,-1]
alignment: Chaotic
level: 2
traits:
  - name: Half-Amphibious
    desc: Must be submerged in water every 4 hours or suffocates.
```

## Salamander
```statblock
name: Salamander
layout: Shadowdark Monster
image:
description: Fire-colored lizardfolk with long tails. Flame-like frills run down their backs.
ac: 13
hp: 24
actions:
  - name: Flaming Spear x2
    desc: (close/near) +4 (1d6, ignites flammables)
  - name: Iron Longbow x1
    desc: (far) +2 (1d8)
mv: near
stats: [+2,+0,+2,-1,+1,-1]
alignment: Chaotic
level: 5
traits:
  - name: Impervious
    desc: Fire immune.
  - name: Heat Aura
    desc: Creatures in close DC 12 CON on turn or 1d8 damage.
```

## Scarab, Swarm
```statblock
name: Scarab, Swarm
layout: Shadowdark Monster
image: [[Scarab, Swarm.png]]
description: A chittering cloud of iridescent, oval-shaped beetles.
ac: 13
hp: 14
actions:
  - name: Bite x2
    desc: +3 (1d6),
mv: near (fly)
stats: [-1,+3,+1,-3,+0,-3]
alignment: Neutral
level: 3
```

## Scarecrow
```statblock
name: Scarecrow
layout: Shadowdark Monster
image:
description: Ragged clothes and a painted burlap head stuffed with straw. Possessed by a malicious spirit.
ac: 12
hp: 15
actions:
  - name: Claws x2
    desc: +2 (1d6)
  - name: Scream x1
    desc: <see below>
mv: near
stats: [+2,+2,+2,+0,+0,+2]
alignment: Chaotic
level: 3
traits:
  - name: Scream
    desc: Creatures who hear in double near DC 12 CHA or paralyzed for 1d4 rounds.
```

## Scorpion
```statblock
name: Scorpion
layout: Shadowdark Monster
image:
description: Desert-dwelling arachnids with pincers and curved tail stingers.
ac: 11
hp: 1
actions:
  - name: Sting x1
    desc: +1 (1 + poison)
mv: near (climb)
stats: [-4,+1,+0,-4,+0,-4]
alignment: Neutral
level: 0
traits:
  - name: Poison
    desc: DC 9 CON or go to 0 HP.
```

## Scorpion, Giant
```statblock
name: Scorpion, Giant
layout: Shadowdark Monster
image:
description: Chitin-plated scorpions as big as camels.
ac: 14
hp: 13
actions:
  - name: Claw x1
    desc: +2 (1d6 + grab) AND
  - name: Sting x1
    desc: +2 (1d4 + poison)
mv: near (climb)
stats: [+2,+2,+0,-4,+0,-4]
alignment: Neutral
level: 3
traits:
  - name: Grab
    desc: DC 12 STR or target held. DC 12 STR on turn to break free.
  - name: Poison
    desc: DC 12 CON or go to 0 HP.
```

## Shadow
```statblock
name: Shadow
layout: Shadowdark Monster
image:
description: Flitting, sentient shadows in the vague shape of a human.
ac: 12
hp: 15
actions:
  - name: Touch x2
    desc: +2 (1d4 + drain)
mv: near (fly)
stats: [-4,+2,+2,-2,+0,-1]
alignment: Chaotic
level: 3
traits:
  - name: Drain
    desc: Target takes 1 STR damage. At 0 STR, target dies and becomes a shadow.
```

## Shambling Mound
```statblock
name: Shambling Mound
layout: Shadowdark Monster
image:
description: Fetid piles of slimy vegetation animated to life by lightning.
ac: 14
hp: 20
actions:
  - name: Slam x2
    desc: +3 (1d6 + engulf)
mv: near
stats: [+3,-2,+2,-3,+0,-3]
alignment: Neutral
level: 4
traits:
  - name: Impervious
    desc: Fire immune. Healed by electricity.
  - name: Engulf
    desc: If a target is hit by both slams in same round, it is pulled into shambling mound's body and suffocates in 2d4 rounds. DC 15 STR on turn to escape.
```

## Shark
```statblock
name: Shark
layout: Shadowdark Monster
image:
description: Bloodthirsty apex predators of the sea. Gray, torpedo-like body.
ac: 11
hp: 15
actions:
  - name: Bite x1
    desc: +3 (1d10)
mv: near (swim)
stats: [+3,+1,+2,-3,+1,-3]
alignment: Neutral
level: 3
```

## Shark, Megalodon
```statblock
name: Shark, Megalodon
layout: Shadowdark Monster
image:
description: Primordial sharks the size of whales. Savage hunters.
ac: 13
hp: 38
actions:
  - name: Bite x3
    desc: +7 (2d8)
mv: double near (swim)
stats: [+5,+1,+2,-3,+1,-3]
alignment: Neutral
level: 8
traits:
  - name: Fearless
    desc: Immune to morale checks.
```

## Siren
```statblock
name: Siren
layout: Shadowdark Monster
image:
description: Baleful fey with dove wings and iridescent fish scales. Their singing entrances listeners
ac: 12
hp: 18
actions:
  - name: Claw x2
    desc: +2 (1d6)
  - name: Song x1
    desc: <see below>
mv: near (swim, fly)
stats: [+0,+2,+0,+2,+2,+4]
alignment: Chaotic
level: 4
traits:
  - name: Song
    desc: Enemies who can hear within double near DC 15 CHA or paralyzed 1d4 rounds. Immune for 1 day if passed check.
```

## Skeleton
```statblock
name: Skeleton
layout: Shadowdark Monster
image: [[Skeleton.png]]
description: A bleach-boned skeleton with red pinpoints of light in its eyes.
ac: 13 (chainmail)
hp: 11
actions:
  - name: Shortsword x1
    desc: +1 (1d6)
  - name: Shortbow x1
    desc: (far) +0 (1d4)
mv: near
stats: [+1,+0,+2,-2,+0,-1]
alignment: Chaotic
level: 2
traits:
  - name: Undead
    desc: Immune to morale checks.
```

## Smilodon
```statblock
name: Snilodon
layout: Shadowdark Monster
image:
description: Prehistoric tigers with long canine fangs. They hunt in grasslands and ice fields.
ac: 12
hp: 14
actions:
  - name: Bite x2
    desc: +3 (1d6)
mv: near
stats: [+3,+2,+1,-3,+1,-3]
alignment: Neutral
level: 3
```

## Snake, Giant
```statblock
name: Snake, Giant
layout: Shadowdark Monster
image: [[Snake, Giant.png]]
description: An enormous, mottled serpent that can swallow a cow whole.
ac: 12
hp: 23
actions:
  - name: Bite x2
    desc: +4 (1d6) AND
  - name: Constrict x1
    desc: (near)
mv: near (climb)
stats: [+3,+2,+1,-2,+0,-2]
alignment: Neutral
level: 5
traits:
  - name: Constrict
    desc: Contested STR to hold target immobile for one round.
```

## Snake, Cobra
```statblock
name: Snake, Cobra
layout: Shadowdark Monster
image:
description: A weaving serpent with a neck hood and lethal venom.
ac: 12
hp: 4
actions:
  - name: Bite x1
    desc: +2 (1 + poison)
mv: near
stats: [-3,+2,+0,-3,+0,-3]
alignment: Neutral
level: 1
traits:
  - name: Poison
    desc: DC 18 CON or go to 0 HP with a death timer of 1.
```

## Snake, Swarm
```statblock
name: Snake, Swarm
layout: Shadowdark Monster
image:
description: A roiling wave of snakes darting and flowing across the ground.
ac: 12
hp: 19
actions:
  - name: Bite x3
    desc: +2 (1d4 + poison)
mv: near
stats: [-3,+2,+1,-3,+0,-3]
alignment: Neutral
level: 4
traits:
  - name: Poison
    desc: DC 12 CON or go to 0 HP in 1d4 rounds.
```

## Soldier
```statblock
name: Soldier
layout: Shadowdark Monster
image: [[Soldier.png]]
description: An armed footsoldier trained in the ways of battlefield combat.
ac: 15 (chainmail + shield)
hp: 10
actions:
  - name: Longsword x1
    desc: +2 (1d8)
  - name: Crossbow x1
    desc: (far) +1 (1d6)
mv: near
stats: [+1,+0,+1,+0,+0,+0]
alignment: Lawful
level: 2
```

## Sphinx
```statblock
name: Sphinx
layout: Shadowdark Monster
image:
description: A winged, leonine oracle who can see into time and space and often speaks in riddles. Lives in isolated mountains.
ac: 16
hp: 42
actions:
  - name: Claw x3
    desc: +7 (1d10)
  - name: Spell x2
    desc: +5,
mv: double near (fly)
stats: [+4,+1,+2,+4,+4,+3]
alignment: Lawful
level: 9
traits:
  - name: Roar
    desc: In place of attacks, all creatures who can hear within far DC 18 CHA or paralyzed 1d4 rounds.
spells:
  - name: Gate (WIS Spell)
    desc: DC 14. Open a portal at a point within near to another location on any plane. Lasts 1d6 rounds or until dismissed.
  - name: Omens (WIS Spell)
    desc: DC 12. Self. ADV on all actions for 1d4 rounds.
  - name: Riddle (WIS Spell)
    desc: DC 12. One target in far DC 15 INT or stupefied 1d4 rounds.
  - name: Time Bend (WIS Spell)
    desc: DC 14. One target in near frozen in time for 1d4 rounds.
  - name: Unmake (WIS Spell)
    desc: DC 13. One target in far takes 3d8 damage.
```

## Spider
```statblock
name: Spider
layout: Shadowdark Monster
image:
description: Silent, web-weaving arachnids with a flesh-dissolving venom.
ac: 11
hp: 1
actions:
  - name: Bite x2
    desc: +1 (1 + poison)
mv: near (climb)
stats: [-4,+1,+0,-4,+0,-4]
alignment: Neutral
level: 0
traits:
  - name: Poison
    desc: DC 9 CON or take 1d4 damage.
```

## Spider, Giant
```statblock
name: Giant, Spider
layout: Shadowdark Monster
image: [[Spider, Giant.png]]
description: Bulbous abdomen and eight, spindly legs. Dwells high in trees or caves and ambushes prey, capturing them to eat later.
ac: 13
hp: 13
actions:
  - name: Bite x1
    desc: +3 (1d4 + poison)
mv: near (climb)
stats: [+2,+3,+0,-2,+1,-2]
alignment: Neutral
level: 3
traits:
  - name: Poison
    desc: DC 12 CON or paralyzed 1d4 hours.
```

## Spider, Swarm
```statblock
name: Spider, Swarm
layout: Shadowdark Monster
image: [[Spider, Swarm.png]]
description: A scurrying carpet of spiders.
ac: 13
hp: 9
actions:
  - name: Bite x1
    desc: +3 (1d4 + poison)
mv: near (climb)
stats: [-1,+3,+0,-3,+1,-3]
alignment: Neutral
level: 2
traits:
  - name: Poison
    desc: DC 12 CON or paralyzed 1d4 rounds.
```

## Stingbat
```statblock
name: Stingbat
layout: Shadowdark Monster
image:
description: Darting, orange insect-bat with four wings and needlelike beak.
ac: 12
hp: 4
actions:
  - name: Beak x1
    desc: +2 (1d4 + blood drain)
mv: near (fly)
stats: [-2,+2,+0,-2,+0,-2]
alignment: Neutral
level: 1
traits:
  - name: Blood Drain
    desc: Attach to bitten target; auto-hit the next round. DC 9 STR on turn to remove.
```

## Strangler
```statblock
name: Strangler
layout: Shadowdark Monster
image:
description: A gray-skinned, gaunt creature with four ropy limbs tipped in sucker-lined claws.
ac: 12
hp: 14
actions:
  - name: Claws x2
    desc: +2 (1d6)
mv: near (climb)
stats: [-2,+2,+1,-2,+0,-2]
alignment: Chaotic
level: 3
traits:
  - name: Stealthy
    desc: ADV on DEX checks to sneak and hide.
  - name: Strangle
    desc: Deals x2 damage against surprised creatures.
```

## The Ten-Eyed Oracle
```statblock
name: The Ten-Eyed Oracle
layout: Shadowdark Monster
image:
description: A floating mass of rubbery skin crusted with barnacles. Its ten eyestalks writhe like snakes, and a deep, circular scar mars its central body, blinding what was once a largeye above a lipless maw. The Ten-Eyed Oracle stalks the Shadowdark, burbling mad prophesies and somehow moving freely between the lightless fathoms of the earth. The keepers of the deep lore suspect The Ten-Eyed Oracle was once a benevolent ally of mankind, but an unknown calamity drove it to insanity and reckless hatred.
ac: 17
hp: 85
actions:
  - name: Eyestalk Ray x2d4
    desc: <see below>
mv: near (fly)
stats: [+4,+5,+4,+5,+4,+4]
alignment: Chaotic
level: 18
traits:
  - name: Legendary
    desc: Only damaged by magical sources. Hostile spells targeting The Ten-Eyed Oracle are DC 18 to cast.
  - name: Eyestalk Ray
    desc: Each ray can shoot once per round and target one creature or an object up to 1,000 pounds (up to four on same target).
```
<br>

| d10 | Ray          | Effect                                              |
|:---:| ------------ | --------------------------------------------------- |
| 1.  | Charm        | DC 15 CHA or become ally for 1d4 rounds.            |
| 2.  | Hold         | DC 15 STR or paralyzed 1d4 rounds.                  |
| 3.  | Sleep        | DC 15 WIS or asleep 1d4 rounds.                     |
| 4.  | Polymorph    | DC 15 INT or turned into vermin for 1d4 rounds.     |
| 5.  | Cancel       | DC 15 DEX or all magical effects on target end.     |
| 6.  | Confusion    | DC 15 WIS or attack a random ally within near.      |
| 7.  | Telekinesis  | DC 15 STR or hover target up to double near.        |
| 8.  | Disintegrate | DC 15 DEX or 5d8 damage (object destroyed).         |
| 9.  | Petrify      | DC 15 CON or petrified.                             |
| 10. | Death        | DC 15 CON or drop to 0 hp: with a death timer of 1. |


>[!quote]
>“The moon runs red into the sea, and the whispers of
> the watchers in darkness proclaim: Your time has come!"
> - _The Ten-Eyed Oracle_

## The Tarrasque
```statblock
name: The Tarrasque
layout: Shadowdark Monster
image:
description: A colossal, four-legged reptile with crocodilian jaws, amber scales, and a diamond-hard, spiked carapace. It towers overhead like a mountain, able to swallow entire villagesn one gulp. The tarrasque hibernates deep in the earth or at the bottom of the sea for centuries, only awakening long enough to fill its vast belly in an indiscriminate rampage of terror and destruction. There is only one tarrasque, and it is the most dreaded creature to walk the earth.
ac: 22
hp: 140
actions:
  - name: Thrash x4
    desc: (near) +13 (3d10 + sever) AND
  - name: Bite x1
    desc: (near) +13 (5d10 + sever + swallow)
mv: triple near (burrow, swim)
stats: [+7,+2,+5,-3,+1,-3]
alignment: Neutral
level: 30
traits:
  - name: Legendary
    desc: Only damaged by magical sources. Hostile spells targeting the tarrasque are DC 18 to cast.
  - name: Deep Dweller
    desc: Immune to harm from fire and cold. Amphibious.
  - name: Permanent Death
    desc: Cannot be permanently killed unless a _wish_ spell is cast on it while it is at 0 HP.
  - name: Rampage
    desc: In place of attacks, move far in a straight line and make one bite attack. On a hit, triple damage.
  - name: Reflective Carapace
    desc: Immune to rays, blasts, or bolts of energy. 1:6 chance these are reflected back at their originator.
  - name: Regeneration
    desc: Regains 4d10 lost hp at the beginning of its turn.
  - name: Sever
    desc: On a natural attack roll of 18+, the attack also severs a random limb (see table below)
  - name: Swallow
    desc: DC 18 STR or swallowed whole. Total darkness inside and 4d10 damage per round. Tarrasque regurgitates all swallowed if dealt at least 30 damage in one round to the inside of its gullet.
```
|1d6| Limb|
|:-:|-|
|1|Head|
|2-4|Arm|
|5-6|Leg|

>[!quote] 
>“RRRRRRAAAAAAAAAAAAAAAAGHHHHHH!"
>- _The Tarrasque_

## The Wandering Merchant
```statblock
name: The Wandering Merchant
layout: Shadowdark Monster
image:
description: A cheerful merchant who appears to be a hale, middle-aged human man with a handlebar mustache. He wears a white shirt, breeches, and leather apron, and he hauls a towering backpack bursting at the seams. Few know the merchant's true nature and origins, though some theorize he is an immortal being or a god (they are not entirely incorrect). The Wandering Merchant always has something useful, far-flung, or incredible to sell at a reasonable price, and there's no telling when or where he'll show up next...
ac: 16 (mithral chainmail)
hp: 71
actions:
  - name: +3 Vorpal Bastard Sword x4
    desc: +9 (1d10 + lop)
mv: near
stats: [+3,+3,+4,+3,+4,+5]
alignment: Lawful
level: 15
traits:
  - name: Legendary
    desc: Only damaged by magical sources. Hostile spells targeting The Wandering Merchant are DC 18 to cast.
  - name: Amulet of Rahm-Hotep
    desc: In place of attacks, teleport to a random location in the multiverse.
  - name: Bottomless Bag
    desc: Contains 200 gear slots in magical sub-pockets. Weighs as much as a normal backpack. The Wandering Merchant can summon it to himself from anywhere by snapping his fingers.
  - name: Dice of Truth
    desc: A set of three six-sided dice whose rolls cannot be magically or mundanely altered in any way.
  - name: Lop
    desc: On a natural attack roll of 18-20, behead the target.
  - name: Reckoning
    desc: Any creature who steals from The Wandering Merchant develops a curse. Over the next 2d8 days, that creature turns into a cockatrice. This curse can only be lifted by a _wish_ spell or by returning the stolen goods.
  - name: Strange Lands
    desc: The Wandering Merchant does not suffer any ill effects from the natural environment he does not wish to suffer.
```

>[!quote]
>“Fancy meeting you here, at the bottom of a pit trap!
> I just so happen to have this lovely rope for sale..."
> - _The Wandering Merchant_

## Thief
```statblock
name: Thief
layout: Shadowdark Monster
image:
description: A cat burglar in a black cloak.
ac: 13 (leather)
hp: 13
actions:
  - name: Dagger x1
    desc: (close/near) +2 (1d4)
  - name: Shortsword x1
    desc: +0 (1d6)
mv: near
stats: [+0,+2,+0,+0,+0,+1]
alignment: Neutral
level: 3
traits:
  - name: Stealthy
    desc: ADV on DEX checks to sneak and hide.
  - name: Backstab
    desc: Deal x2 damage against surprised creatures.
```

## Thug
```statblock
name: Thug
layout: Shadowdark Monster
image:
description: A bruised and boorish ruffian.
ac: 13 (leather + shield)
hp: 4
actions:
  - name: Shortsword x1
    desc: +1 (1d6)
mv: near
stats: [+1,+0,+0,-1,+1,-1]
alignment: Chaotic
level: 1
```

## Treant
```statblock
name: Treant
layout: Shadowdark Monster
image:
description: Peaceful, slow-moving trees with merry eyes and tremulous voices. They protect the forest.
ac: 14
hp: 38
actions:
  - name: Slam x3
    desc: +8 (1d10)
  - name: Rock x1
    desc: (far) +8 (2d12)
mv: near
stats: [+4,-1,+2,+2,+3,+1]
alignment: Neutral
level: 8
traits:
  - name: Animate Tree
    desc: 2/day. In place of attacks, one tree within near awakens as a treant ally without this ability. Reverts back in 1 day.
```

## Troll
```statblock
name: Troll
layout: Shadowdark Monster
image: [[Troll.png]]
description: Green, lanky giants with warty skin and territorial rage. Lair in deep forests and swamps.
ac: 12
hp: 24
actions:
  - name: Claw x2
    desc: +4 (1d6) AND
  - name: Bite x1
    desc: +4 (1d10)
mv: near
stats: [+3,+2,+2,-1,+0,-1]
alignment: Chaotic
level: 5
traits:
  - name: Regenerate
    desc: Regains 2d6 HP on its turn unless its wounds are cauterized with fire or acid.
```

## Troll, Frost
```statblock
name: Troll, Frost
layout: Shadowdark Monster
image:
description: Rime-covered trolls with blue skin and flinty, black eyes. They stalk arctic lands and frozen boreal forests.
ac: 13
hp: 34
actions:
  - name: Claw x2
    desc: +5 (1d8)
  - name: Bite x1
    desc: +5 (1d12)
mv: near
stats: [+3,+2,+3,-1,+0,-1]
alignment: Chaotic
level: 7
traits:
  - name: Impervious
    desc: Cold and fire immune.
  - name: Regenerate
    desc: Regains 2d6 HP on its turn unless its wounds are cauterized with acid.
```

## Unicorn
```statblock
name: Unicorn
layout: Shadowdark Monster
image: [[Unicorn.png]]
description: A silvery horse with a flowing mane and a single spiral horn.
ac: 12
hp: 20
actions:
  - name: Hooves x1
    desc: +3 (1d6)
mv: double near
stats: [+3,+2,+2,+1,+2,+3]
alignment: Lawful
level: 4
traits:
  - name: Healing Horn
    desc: A touch heals 2d6 HP or ends one curse or disease.
```

## Vampire
```statblock
name: Vampire
layout: Shadowdark Monster
image:
description: Pale, blood-drinking undead of supreme power and wickedness. They loathe sunlight and protect their coffins at all costs.
ac: 15
hp: 52
actions:
  - name: Bite x3
    desc: +7 (1d8 + blood drain)
  - name: Charm x1
    desc: <see below>
mv: near (climb)
stats: [+4,+3,+3,+1,+3,+4]
alignment: Chaotic
level: 11
traits:
  - name: Supreme Undead
    desc: Immune to morale checks. Only damaged by magical sources.
  - name: Blood Drain
    desc: Vampire heals 2d6 HP and target permanently loses 1d4 CON. At 0 CON, target dies and rises as vampire or vampire spawn (vampire chooses).
  - name: Charm
    desc: One humanoid target who can see vampire within near, DC 15 CHA or under vampire's control for 1d4 days.
  - name: Shapechange
    desc: In place of attacks, turn into a bat, wolf, or back into regular form.
  - name: Vampire
    desc: Must sleep in a coffin daily or loses 2d6 HP each day that can't be healed until resting in coffin. Takes 3d8 damage each round while in direct sunlight. Cannot be killed unless pierced through heart with a wooden stake while at 0 HP.
```

## Vampire Spawn
```statblock
name: Vampire Spawn
layout: Shadowdark Monster
image:
description: Lesser, feral vampires born from the bite of their vampiric sires. Bloodthirsty and savage. They rarely leave a victim alive.
ac: 13 (leather)
hp: 25
actions:
  - name: Bite x2
    desc: +4 (1d8 + blood drain)
mv: near (climb)
stats: [+3,+2,+3,-1,+1,+2]
alignment: Chaotic
level: 5
traits:
  - name: Greater Undead
    desc: Immune to morale checks. Only damaged by silver or magical sources.
  - name: Blood Drain
    desc: Vampire heals 2d6 HP and target permanently loses 1d4 CON. At 0 CON, target dies and rises as a vampire spawn.
  - name: Vampire
    desc: Must sleep in a coffin daily or loses 2d6 HP each day that can't be healed until resting in coffin. Takes 3d8 damage each round while in direct sunlight. Cannot be killed unless pierced ```through heart with a wooden stake while at 0 HP.
```

## Violet Fungus
```statblock
name: Violet Fungus
layout: Shadowdark Monster
image:
description: Child-sized, creeping fungi with neon purple caps. Their whiplike roots decompose living flesh.
ac: 7
hp: 9
actions:
  - name: Tendril x2
    desc: (near) +0 (1d4)
mv: close
stats: [-3,-2,+0,-4,-3,-4]
alignment: Neutral
level: 2
```

# Viperians

A fallen and scattered civilization of snake-people who built their blood-soaked dynasties with sorcery and cunning. Their descendants fight for scraps of faded grandeur in the decaying ruins of their forgotten cities.

Small circles of viperian wizards practice ancient magic and lead their enclaves. Viperian ophids are rare and much more snakelike than their brethren, serving as esteemed guardians and warriors.


## Viperian
```statblock
name: Viperian
layout: Shadowdark Monster
image:
description: Lithe, snake-headed people with cobra hoods and emerald green scales covering their bodies.
ac: 13
hp: 13
actions:
  - name: Scimital x2
    desc: +2 (1d6)
  - name: Javlin x1
    desc: (close/far) +2 (1d4)
mv: near
stats: [+1,+1,+0,+0,+1,+0]
alignment: Chaotic
level: 3
```

## Viperian, Ophid
```statblock
name: Viperian, Ophid
layout: Shadowdark Monster
image:
description: A giant anaconda body merges into a humanoid torso with a large snake head. It wears golden torcs and strings of glittering moonstones.
ac: 14
hp: 28
actions:
  - name: Falchion x3
    desc: +5 (1d10)
  - name: Longbow x2
    desc: (far) +3 (1d8)
mv: near (climb)
stats: [+4,+2,+1,+1,+1,+1,]
alignment: Chaotic
level: 6
traits:
  - name: Impervious
    desc: Can only be harmed by magical sources.
```

## Viperian, Wizard
```statblock
name: Viperian, Wizard
layout: Shadowdark Monster
image:
description: Thin viperians with scales tinged in black. They wear silk robes and silver, serpentine jewelry.
ac: 13
hp: 37
actions:
  - name: Dagger x1
    desc: (close/near) +2 (1d4)
  - name: Spell x2
    desc: +5,
mv: near
stats: [+0,+1,+0,+3,+1,+1]
alignment: Chaotic
level: 8
spells:
  - name: Hiss (INT Spell)
    desc: DC 12. End one spell within far.
  - name: Summon Cobra (INT Spell)
    desc: DC 13. Summon 1d4 loyal cobras that appear within near. They leave in 1d4 rounds.
  - name: Venom (INT Spell)
    desc: DC 12. One target in far takes 2d8 damage.
  - name: Whispers (INT Spell)
    desc: DC 14. Focus. All enemies within near of viperian wizard have DISADV on spellcasting checks for the duration.
```

## Vulture
```statblock
name: Vulture
layout: Shadowdark Monster
image:
description: Scavenger birds with black feathers, hunched backs, and bald heads.
ac: 10
hp: 5
actions:
  - name: Tear x1
    desc: +1 (1d4)
mv: near (fly)
stats: [+1,+0,+1,-3,+1,-3]
alignment: Neutral
level: 1
traits:
  - name: Carrion Tracker
    desc: Can track dead flesh unerringly within a mile.
```

## Wasp, Giant
```statblock
name: Wasp, Giant
layout: Shadowdark Monster
image: [[Wasp, Giant.png]]
description: Man-sized wasps with glossy, yellow-striped abdomens.
ac: 13
hp: 9
actions:
  - name: Sting x1
    desc: +3 (1d6 + venom)
mv: near (fly)
stats: [+1,+3,+0,-3,+0,-3]
alignment: Neutral
level: 2
traits:
  - name: Venom
    desc: DC 9 CON or go to 0 HP.
```

## Werewolf
```statblock
name: Werewolf
layout: Shadowdark Monster
image: [[Werewolf.png]]
description: A bipedal, wolf-faced humanoid covered in brown fur.
ac: 12
hp: 20
actions:
  - name: Rend x2
    desc: +3 (1d6)
mv: double near
stats: [+3,+2,+2,+0,+1,+0]
alignment: Chaotic
level: 4
traits:
  - name: Impervious
    desc: Only damaged by silver or magic sources.
  - name: Lycanthropy
    desc: If 12 or more damage from the same werewolf, contract lycanthropy.
```

## Wererat
```statblock
name: Wererat
layout: Shadowdark Monster
image:
description: A slinking, rat-faced humanoid covered in mangy fur.
ac: 13 (leather)
hp: 14
actions:
  - name: Bite x2
    desc: +2 (1d6)
mv: near (climb)
stats: [+1,+2,+1,-1,+1,-1]
alignment: Chaotic
level: 3
traits:
  - name: Impervious
    desc: Only damaged by silver or magic sources.
  - name: Lycanthropy
    desc: If 12 or more damage from the same wererat, contract lycanthropy.
```

## Wight
```statblock
name: Wight
layout: Shadowdark Monster
image: [[Wight.png]]
description: A pale, armored undead warrior with sinister intelligence.
ac: 14 (chainmail)
hp: 15
actions:
  - name: Bastard Sword x1
    desc: +3 (1d10)
  - name: Life Drain x1
    desc: +3,
mv: near
stats: [+3,+1,+2,+1,+0,+3]
alignment: Chaotic
level: 3
traits:
  - name: Greater Undead
    desc: Immune to morale checks. Only damaged by silver or magical sources.
  - name: Life Drain
    desc: 1d4 CON damage. Death if reduced to 0 CON.
```

## Will-O'-Wisp
```statblock
name: Will-O'-Wisp
layout: Shadowdark Monster
image: [[Will-O_-Wisp.png]]
description: A bobbing marsh light animated by an evil spirit. It tries to lead the living into danger.
ac: 13
hp: 10
actions:
  - name: Life Drain x1
    desc: +3,
mv: near (fly)
stats: [-3,+3,+1,-1,-1,-2]
alignment: Chaotic
level: 2
traits:
  - name: Life Drain
    desc: 1d4 CON damage. Death if reduced to 0 CON.
```

## Wolf
```statblock
name: Wolf
layout: Shadowdark Monster
image: [[Wolf.png]]
description: A giant canine with a gray pelt, yellow eyes, and dripping jaws.
ac: 12
hp: 10
actions:
  - name: Bite x1
    desc: +2 (1d6)
mv: double near
stats: [+2,+2,+1,-2,+1,+0]
alignment: Neutral
level: 2
traits:
  - name: Pack Hunter
    desc: Deals +1 damage while an ally is close.
```

## Wolf, Dire
```statblock
name: Wolf, Dire
layout: Shadowdark Monster
image:
description: A massive wolf with spines of black bone along its brow ridge and back.
ac: 12
hp: 19
actions:
  - name: Bite x2
    desc: +4 (1d8)
mv: double near
stats: [+3,+2,+1,-1,+1,+0]
alignment: Neutral
level: 4
traits:
  - name: Pack Hunter
    desc: Deals +1 damage while an ally is close.
```

## Wolf, Winter
```statblock
name: Wolf, Winter
layout: Shadowdark Monster
image:
description: Sinister, white-pelted wolves with piercing blue eyes. From the fey realms of eternal winter.
ac: 12
hp: 23
actions:
  - name: Bite x2
    desc: +4 (1d6)
  - name: Frost Breath x1
    desc: <see below>
mv: double near,
stats: [+3,+2,+1,+0,+1,+0]
alignment: Chaotic
level: 5
traits:
  - name: Impervious
    desc: Cold immune.
  - name: Frost Breath
    desc: Fills a near-sized cube extending from winter wolf. DC 15 DEX or 3d8 damage. Cannot use again for 1d4 rounds.
```

## Worg
```statblock
name: Worg
layout: Shadowdark Monster
image:
description: Bat-faced wolves that speak Goblin and often serve as war mounts for goblinkind.
ac: 11
hp: 14
actions:
  - name: Bite x1
    desc: +3 (1d6)
mv: double near
stats: [+2,+1,+1,-2,+1,-2]
alignment: Chaotic
level: 3
```

## Wraith
```statblock
name: Wraith
layout: Shadowdark Monster
image:
description: A shadowy spirit seething with anger and malice. Its presence is unsettling to animals.
ac: 14
hp: 36
actions:
  - name: Death Touch x3
    desc: +6 (1d10 + life drain)
mv: near (fly)
stats: [-4,+4,+0,+0,+0,+3]
alignment: Chaotic
level: 8
traits:
  - name: Greater Undead
    desc: Immune to morale checks. Only damaged by silver or magical sources.
  - name: Incorporeal
    desc: In place of attacks, become corporeal or incorporeal.
  - name: Life Drain
    desc: 1d4 CON damage. Death if reduced to 0 CON.
```

## Wyvern
```statblock
name: Wyvern
layout: Shadowdark Monster
image:
description: Dragon-cousins with a large tail stinger, mottled lizard skin, and leathery wings.
ac: 15
hp: 37
actions:
  - name: Rend x2
    desc: +6 (1d8) AND
  - name: Stinger x1
    desc: +6 (1d6 + poison)
mv: double near (fly)
stats: [+4,+2,+1,-3,+1,-3]
alignment: Neutral
level: 8
traits:
  - name: Poison
    desc: DC 15 CON or take 2d10 damage.
```

## Zombie
```statblock
name: Zombie
layout: Shadowdark Monster
image:
description: Lurching and decomposed undead that hunt in mobs.
ac: 8
hp: 11 
actions:
  - name: Slam x1
    desc: +2 (1d6)
mv: near
stats: [+2,-2,+2,-2,-2,-3]
alignment: Chaotic
level: 2
traits:
  - name: Undead
    desc: Immune to morale checks.
  - name: Relentless
    desc: If zombie reduced to 0 HP by a non-magical source, DC 15 CON to go to 1 HP instead.
```