Gen8ration NEXT!
========================================================================

Manifesto
------------------------------------------------------------------------

The goal of NEXT is to improve the diversity of the OU metagame by only doing
things that could plausibly be done between gens.

Specifically, the core rules of NEXT are:

1. no base stat changes
2. no removing from movepools or ability distribution
3. no typing changes (except on formes) or changes to the typechart
4. no buffing OU mons, except maybe tiny buffs to mons at the bottom of OU
5. no doing things that make zero sense flavor-wise
6. all Pokemon are usable, including dex cuts, Mega Evolutions, and Floette-E
7. Dynamax will be modified to fit in OU

What's left is mainly changes to how abilities and moves work, which is
most of what NEXT is about.

A good example is what Game Freak did by giving Ditto the Imposter ability.
This gave a Ditto a role in OU, while still making sense flavor-wise, and
without removing anything it used to have.

A good example of what NEXT changes is Cherrim. We have taken an interesting
idea (ability designed for Sunny Day support) and made it viable in OU.

This approach is in sharp contrast to many mods that do change many things on
NEXT's "don't change" list. The result is a metagame that feels a lot like
a new generation: existing OU threats stay mostly the same, but many new
threats and strategies are introduced.

And yes, we know that "no base stat changes" and "no typechart changes" have been broken. We're
still not doing it, because it's hard to constrain and hard to keep track of.

Recent changes
------------------------------------------------------------------------

A changelog for NEXT is available here:

https://github.com/smogon/pokemon-showdown/commits/master/data/mods/gennext

Changes
------------------------------------------------------------------------

Generation NEXT currently makes the following changes:

Mechanics changes:

- Dynamax and Gigantamax only last one turn. This makes Max and GMax moves usable without destroying the metagame.

- Baton Pass can't transfer stat boosts, but it can transfer trap and partial-trap moves.

- Freeze always thaws at the second turn. (Blizzard now has a 30% freeze chance.)

- Confusion's self-attack lasts every turn, but doesn't cancel the chosen move. Confusion lasts 3-5 turns.

- Each side can have its own weather or (not and) terrain, which lasts indefinitely. Most are nerfed to compensate.

Major changes:

- Moves with semi-invulnerable or charge turns have +1 priority on both turns.

- Moves with recharge turns only recharge if they KO the target, like the reverse of Generation 1.

- Primal Power is an 80 BP, 90 Acc Physical Rock-type move that all fossil Pokemon get. It raises a random stat on hit, and is Special if the user's Special Attack is higher. 

- Drives will change Genesect's typing immediately after switch-in, to Bug/Ice,
  Bug/Fire, Bug/Electric, or Bug/Water. However, Download will not activate for
  Genesect unless it holds a Drive.
  
- Move and ability incompatibilities are ignored, and unreleased abilities are released.

- Teleport has +6 priority instead of -6 priority.

- Explosion, Self-Destruct, and Misty Explosion always crit. Misty Explosion has 150 BP.

- Flower Gift now only boosts Sp. Def, but if Sunny Day is used while Cherrim
  is out, the next switch-in also receives +1 SpD

- All Quiver Dancers (except Smeargle) get an item named Gossamer Wing (Select
  "Stick" in the teambuilder). It makes them take half damage from Rock, Ice,
  and Electric moves if they are Flying type, prevents them from taking
  double SR damage, heals 1/16 after using a Status move, and makes Twister
  do 1.5x Damage.

- Swarm also makes the user take half damage from Rock, Ice, Electric moves,
  and Stealth Rock if they are Flying type.

- Relic Song switches Meloetta's SpA and Atk EVs, boosts, and certain natures,
  specifically: Modest <-> Adamant, Jolly <-> Timid, other natures are left
  untouched. It's now 60 base power +1 priority, with no secondary.

- Shuckle gets Berry Shell (select "Stick" in the teambuilder), which gives a
  50% boost to Defense and Sp. Def.

- Ambipom, Spinda, and Mr. Mime get Sketch as an egg move, allowing it to use
  exactly one move not normally in its learnset.

- Spinda gets V-Create, Superpower, Close Combat, Overheat, Leaf Storm, Draco
  Meteor.

- Echoed Voice now has 80 base power, hits once, and then, 2 turns later,
  hits again for 80 base power. It's like Doom Desire, except it still hits
  that first time.

- Confusion now deals 30 base power damage every attack, but does not stop
  the attack. It now lasts 3-5 turns.

- Parental Bond now deals half damage on both hits, but confers perfect
  accuracy like all multi-hit moves.

- Life Orb now behaves much more consistently as normal recoil. Reckless
  will boost every move if Life Orb is held, and Rock Head will negate Life
  Orb recoil.

- Twister is now a 80 base power Flying move with a 30% confusion chance

- Floette-Eternal-Flower is released.

New mechanic: Signature Pokémon:

- Certain moves have a Signature Pokémon associated with them. A move will
  deal 1.5x its usual damage when used by its Signature Pokémon. Some of these
  moves also receive other changes that apply to all Pokémon using the move -
  those changes are listed in parentheses.

  - Flareon: Fire Fang (20% burn, 30% flinch, 100% accuracy)

  - Walrein: Ice Fang (20% freeze, 30% flinch, 100% accuracy)

  - Luxray: Thunder Fang (20% paralysis, 30% flinch, 100% accuracy)

  - Drapion: Poison Fang (65 base power, 100% toxic poison, 30% flinch)

  - Seviper: Poison Tail (60 base power, 60% toxic poison)

  - Muk: Sludge (60 base power, 100% poison)

  - Weezing: Smog (75 base power, 100% poison, 100% accuracy)

  - Rapidash: Flame Charge (60 base power)

  - Darmanitan: Flame Wheel

  - Eelektross: Spark

  - Hitmontop: Triple Kick

  - Kingdra: BubbleBeam (30% -1 Spe)

  - Galvantula: Electroweb (60 base power, 100% accuracy)

  - Skarmory: Steel Wing (60 base power, 100% accuracy, 50% +1 Def)

  - Beautifly: Giga Drain

  - Glaceon: Icy Wind (60 base power, 100% accuracy)

  - Swampert: Mud Shot (60 base power, 100% accuracy)

  - Kyurem: Glaciate (80 base power, 100% accuracy)

  - Octillery: Octazooka (75 base power, 90% accuracy, 100% -1 accuracy)

  - Serperior: Leaf Tornado (75 base power, 90% accuracy, 100% -1 accuracy)

  - Weavile: Ice Shard

  - Sharpedo: Aqua Jet

  - Hitmonchan: Mach Punch

  - Banette: Shadow Sneak

  - Masquerain: Surf (10% -1 Spe)

  - Snorlax: Snore (100 base power)

  - Persian: Slash (60 base power 30% -1 Def)

- Again, note that while the Signature Pokémon will get the 1.5x damage boost,
  all Pokémon will get the other changes to the move listed above.

New mechanic: Intrinsics:

- Pokémon that previously get Levitate are now immune to Ground intrinsically, although
  Mold Breaker still bypasses this immunity. Instead, many of them get new abilities
  in addition to their Ground immunity:

  - Azelf: Steadfast

  - Bronzong: Heatproof

  - Claydol: Filter

  - Cryogonal: Ice Body

  - Eelektross: Poison Heal

  - Flygon: Compoundeyes, Sand Rush

  - Hydreigon: Sheer Force

  - Mesprit: Serene Grace

  - Mismagius: Cursed Body

  - Rotom (all formes): Trace

  - Unown: Shadow Tag

  - Uxie: Synchronize

  - Weezing: Aftermath

New: Type-specific items:

- Big Root: also acts like Leftovers + Shell Bell for Grass types

- Black Sludge: heals 1/8 per turn for pure Poison types

- Focus Band: breaks on first hit, but allows pure Fighting types to survive
  that hit with 1 HP (so basically it'd be a Focus sash that stays intact
  after residual damage); does nothing for other Pokémon

- Wise Glasses: 1.2x Special damage for pure Psychic types

- Muscle Band: 1.2x Physical damage for pure Fighting types

Minor move changes:

- Parabolic Charge now has 40 base power, but gives -1 SpA, -1 SpD to the
  target and +1 SpA, +1 SpD to the user

- Draining Kiss now has 40 base power, but gives -1 SpA, -1 Atk to the
  target and +1 SpA, +1 Atk to the user

- Defend Order and Heal Order now have +1 priority

- Rock Throw now removes Stealth Rock from the user's side of the field,
  and has 100% accuracy

- Rapid Spin now has 30 base power

- Rock Throw and Rapid Spin remove hazards before fainting from Rocky
  Helmet etc. And double in power if they remove hazards.

- All moves' accuracy is rounded up to the nearest multiple of 10%
  (including Jump Kick)

- Charge Beam and Rock Slide are now 100% accurate

- Blue Flare has 30% burn chance, Fire Blast has 20% burn chance and is
  80% accurate

- Focus Blast has 30% accuracy (use HP Fighting unless you have No Guard)

- Close Combat has been nerfed: it now gives -2 Def, -2 SpD

- Moves that were originally perfect accuracy have their base power increased
  to 90 (this includes Aerial Ace, Disarming Voice, and Aura Sphere, among
  others)

- Scald and Steam Eruption's damage is no longer affected by weather:
  instead, they get 60% burn chance in sun

- High Jump Kick now has 100 base power

- Shadow Ball now has 90 base power and 30% -SpD

- Multi-hit moves are now all perfect-accuracy

- Silver Wind, Ominous Wind, and AncientPower have a 100% chance of raising
  one of Def/SpA/SpD/Spe at random, rather than a 10% chance of raising every
  stat

- Twineedle has a new base power of 50

- Tri Attack now hits 3 times and has a base power of 30

- Strength now has a 30% chance of raising user's Atk

- Cut and Rock Smash are 50 base power and now have a 100% chance of
  lowering foe's Def

- Psycho Cut's Base Power is now 90

- Drill Peck, Needle Arm, Attack Order, and Leaf Blade's Base
  Powers are now 100

- Stomp and Steamroller now have 100 Base Power and perfect accuracy to
  reflect their thematic status as counters to Minimize

- Bide is now a +1 priority move that gives the user Endure (the user
  survives all move damage with at least 1 HP) for its duration. Bide fails
  if the user has 1 HP when it's used, or if the user's last move used was
  Bide.

- Withdraw gives +1 SpD as well as +1 Def

- Muddy Water is now 85 base power and 100% accurate

- Leech Life is now 75 base power

- Sound-based moves are no longer affected by immunities (ghosts can hear
  things)

- Bonemerang, Bone Club and Bone Rush are no longer affected by immunities 
  (you can throw a bone to hit birds), Bone Rush nerfed to 20 base power 
  since it should never be viable

- Wing Attack and Power Gem are now like Dual Chop: 40 base power, 2-hit

- Autotomize now gives +3 Speed

- Zoroark gets a significantly wider movepool. It now learns: Ice Beam, Giga
  Drain, Earthquake, Stone Edge, Superpower, X-Scissor

- If Illusion is active, Night Daze now displays as a random non-Status move
  in the copied Pokémon's moveset

- Selfdestruct and Explosion are now 200 and 250 base power autocrit moves,
  respectively, and they are both perfect-accuracy

- Acid and Acid Spray aren't affected by immunities

- Protect does not protect Substitutes (with passive healing being more
  common, Sub/Protect stalling could be overpowered) and Substitutes increase
  accuracy against them to 100%

- Dizzy Punch is 90 base power, 50% confusion chance

- Sacred Sword now has 95 base power

- Egg Bomb is now 40 base power autocrit

- Minimize only increases evasion by one stage

- Double Team takes 25% of user's max HP (like Substitute)

Minor learnset changes:

- Azumarill gets Belly Drum with no incompatibilities

- Mantine gets many new moves: Recover, Whirlwind, Baton Pass, Wish, Soak,
  Lock-On, Acid Spray, Octazooka, Stockpile

- Masquerain gets Surf

- Butterfree, Beautifly, Masquerain, and Mothim get Hurricane

- Roserade gets Sludge

- Meloetta gets Fiery Dance

- Galvantula gets Zap Cannon

- Virizion gets Horn Leech

- Scolipede and Steelix get Coil

- Lumineon, Ampharos, and Lanturn get Tail Glow

- Rotom formes learn more things:
  - Rotom-Wash: BubbleBeam
  - Rotom-Fan: Hurricane, Twister
  - Rotom-Frost: Frost Breath
  - Rotom-Heat: Heat Wave
  - Rotom-Mow: Magical Leaf

- Starters get a new ability option
  - Venusaur: Leaf Guard
  - Charizard: Flame Body
  - Blastoise: Shell Armor
  - Meganium: Harvest
  - Typhlosion: Magma Armor
  - Feraligatr: Strong Jaw
  - Sceptile: Limber
  - Blaziken: Reckless
  - Swampert: Hydration
  - Torterra: Weak Armor
  - Infernape: No Guard
  - Empoleon: Ice Body
  - Serperior: Own Tempo
  - Emboar: Sheer Force
  - Samurott: Technician
  - Chesnaught: Battle Armor
  - Delphox: Magic Guard
  - Greninja: Pickpocket

- Crawdaunt's Hidden Ability is now Tough Claws (this is because of a
  nerf to Adaptability which is discussed below)

Minor ability changes:

- Static, Poison Point, and Cute Charm now always activate on
  contact.

- Weak Armor reduces incoming move damage by 1/10 of the user's max HP
  and increases the user's Speed for the first hit after switch-in (and
  does not activate again until the next switch-in) instead of its
  previous effect

- Shell Armor and Battle Armor reduce incoming move damage by 1/10 of
  the user's max HP in addition to their crit negation (also, Shell
  Armor is removed when using Shell Smash)

- Magma Armor reduces incoming move damage by 1/10 of the user's max HP,
  provides immunity to Hail and freeze, and provides a one-time immunity
  to Water and Ice, after which it turns into Battle Armor

- Prism Armor reduces incoming move damage by 1/10 of the user's max HP in addition to its normal effects.

- Adaptability is now 1.33x to non-STAB moves instead of to STAB moves

- Shadow Tag now lasts only one turn

- Static and Poison Point have a 100% chance of activating

- Speed Boost does not activate on turns Protect, Detect, Endure, etc
  are used

- Telepathy grants Imprison on switch-in

- Compound Eyes and Keen Eye now grant 1.6x accuracy (this replaces Keen
  Eye's previous effect)

- Victory Star grants 1.5x accuracy (but only for the user)

- Solid Rock and Filter now reduce damage of SE moves by 1/2, not 1/4

- Iron Fist now grants a 1.33x boost to punching moves

- Outrage, Thrash, and Petal Dance don't lock if the user has Own Tempo

- Stench now grants a 40% flinch chance

- Slow Start now only lasts 3 turns instead of 5

- Truant will only activate if a move succeeds (e.g. not if it misses, fails,
  or is Protected against), and will heal the user by 33% during its Truant
  turn

- Clear Body and White Smoke prevents all stat lowering (relevant: the Regis'
  Superpower, Metagross' Hammer Arm, and Torkoal's Overheat)

- Thick Fat grants half damage from Fighting

- Aftermath no longer requires contact, and is buffed to deal 1/3 of the
  foe's max HP

- Cursed Body works like Aftermath now, but instead of dealing damage, it
  causes the foe to be Cursed (like Ghost-type Curse)

- Gluttony allows a Pokémon to use a Berry twice

- Heatproof now grants the user immunity to Fire and burns

- Guts, Quick Feet, and Toxic Boost take half damage from poisoning

- Guts, Quick Feet, and Flare Boost take half damage from burns

- Sand Veil grants 20% damage reduction in sand (this replaces Sand Veil's
  usual effect)

- Water Veil grans 12.5% damage reduction out of rain and 25% damage
  reduction in rain, in addition to its usual effect

- Multiscale decreases damage by 1/3 rather than 1/2 (Sorry, Dragonite,
  this is in exchange for a usable physical Flying STAB from a buffed
  Aerial Ace)

Minor item changes:

- Zoom Lens now grants 1.6x accuracy

- Wide Lens now grants 1.3x accuracy

Bans:

- The OU banlist (i.e. Pokémon considered Uber) is now:
  - Every Pokémon with over 600 BST except Slaking, Regigigas, and Hoopa-Unbound
  - Deoxys (all formes)
  - Darkrai
  - Shaymin-Sky

- The following clauses are in effect:
  - OHKO Clause
  - Sleep Clause
  - Soul Dew is banned

Specifically, differences from regular OU:

- unbanned: Aegislash, Blaziken, Genesect, Landorus, Gengarite, Kangaskhanite,
  Lucarionite, Mawilite, Salamencite

- banned: Hoopa-Unbound, Kyurem, Kyurem-Black

- There is no Moody Clause or Evasion Clause
