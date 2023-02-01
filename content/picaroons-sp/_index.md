---
weight: 2
title: "Picaroons (Single Page)"
platen:
  title_as_heading: true
  menu:
    flatten_section: true
---

> A Narrative Game of Adventure for Scoundrels

## About

Use this game text however you please, so long as you're not a bigot, fascist, or other piece of
dogshit. If you use it for your own work, attribution is appreciated but not required.

## Special Thanks

- Chris Bissette ([Twitter][1], [Itch][2], [Patreon][3], [Bandcamp][4], [Store][5])
- Dai Shugars ([Twitter][6], [Blog][7])
- Jared Sinclair ([Twitter][8], [Itch][9], [Store][10])
- Lucas Rolim ([Twitter][11], [Itch][12])
- Luke Gearing ([Twitter][13], [Blog][14], [Itch][15])
- Marcia ([Twitter][16], [Blog][17], [Itch][18])
- Micah Anderson ([Twitter][19], [Itch][20])
- Sean Richer ([Twitter][21], [DTRPG][22])

### Credits

<!-- vale Vale.Spelling = NO -->

- **Writing:** Mikey Lombardi ([Twitter][23], [LeanPub][24])
- **Art:** Anonymous dead person, [_Colección de láminas en color representando tipos de diversos países_][25]

<!-- vale Vale.Spelling = YES -->

### Friendly Sponsors

- Monkey's Paw Games ([Twitter][26], [Itch][27], [Store][28])
- Sivad's Sanctum ([Twitter][29], [Itch][30])
- Zeshio Illustration ([Yol'Najj Forest Zine][31], [Patreon][32], [Twitter][33], [Itch][34])

## Playing Picaroons

You're a picaroon, a rogue who relies on your wits and skills to get into and out of trouble.

### Basics

This section details everything you need to know to get playing.

#### Hit Dice and Hit Points

You have hit dice (HD) which represent vaguely how lucky and resilient you are. The bigger your HD,
the less likely you are to get yourself killed on your adventures. HD have a die size and count, and
marks. You start play with 1d6 as your HD.

Roll your HD to set your current hit points (HP). Your HP is a counter to how close you are to your
luck running out. For more information about what happens when you hit 0 HP, see
[At 0 HP][1].

#### Domains

Domains are free-form and represent an area you've chosen to focus in. They may be skills, topics,
backgrounds, special items, whatever. Domains have a die size, marks, and trick slots. Domains
always start as d6 with 0 marks and 1 trick slot.

Your starting HP determines the number of domains you have:

|     HP      |   1   |   2   |   3   |   4   |   5   |   6   |
| :---------: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Domains** |   5   |   4   |   3   |   2   |   1   |   0   |

#### Tricks { #tricks-basics }

Each trick slot holds one single trick. Tricks are always specific to their domain. They make the
probable automatic, the unlikely probable, or the impossible possible. Tricks have a die size and
count, marks, and uses per scene. Tricks start at 1d6 with 0 marks and 1 use per scene.

You don't need to fill trick slots for your domains immediately, you may pick or create them later.
For more information, see [Tricks](#tricks).

#### Debt

Picaroons start out broke. To take on debt to a patron, faction, or institution, roll 2d6. The lower
result die is the number of domains you get from your guarantor. The higher result die is how many
d6x100 silver of debt you need to clear.

```details { summary="Example: Taking on Debt" }
You've decide to take on debt from Big Tony, who runs a definitely safe and licensed academy for
adventurers, to get a little schooling.

You roll 2d6. The dice show 1 and 4.

You gain one domain. You roll 4d6 and get 11. You owe Big Tony 1100 silver for the privilege of
attending his academy.
```

Picaroons can _always_ seek more debt.

#### Tests

When an outcome is uncertain, test by rolling 1d6. On a result of 5 or higher, unless otherwise
stated, you succeed.

When an outcome is contested, all sides test by rolling 1d6. Higher results beat lower results.

If any domains are relevant to the uncertain or contested action, you may roll the die for one of
your relevant domains and take the best result.

#### Marks

Whenever you roll your HD, domain die, or trick dice, mark the appropriate section for every die
that shows its maximum (e.g. 6 on a d6, 8 on a d8). You can spend your marks when you rest. For more
information, see [Resting](#resting).

### Resting

Whenever you take the time and space to relax in relative safety for at least one week, you are
resting. After you rest, you may fill or swap out any of your tricks.

#### Recovering HP

Whenever you rest, roll your HD. If the result is higher than your current HP, that's your new
total. Otherwise, +1 to your current HP, up the combined face value of your HD.

```details { summary="Example: Resting at 3HP with 2d6 HD" }
Roll 2d6. If the result is 2 or 3, increase your current HP to 4. If it's higher, set your current
HP to the result.
```

#### Spending Marks

After you rest, you may spend your marks.

If you have at least as many marks as the size of their associated die, you may spend that many
marks to increase your die size one step.

In addition to increasing a die size, you may spend marks to:

| Dice Type |     Marks to Spend      | Effect                     |
| :-------: | :---------------------: | :------------------------- |
|    HD     |            2            | Mark a domain              |
|    HD     |      Domain Count       | Gain a new domain          |
|    HD     | 3x Companion Slot Count | Gain a companion slot      |
|    HD     |      Combined Max       | Add another die            |
|  Domain   |            2            | Mark a trick               |
|  Domain   |   3x Trick Slot Count   | Gain a trick slot          |
|   Trick   |      Combined Max       | Add another die            |
|   Trick   |  3x Current Use Count   | Gain another use per scene |

##### Increase Die Size

If you have 3d6 HD, you must spend 6 marks to increase your HD to 3d8.

If your domain is a d10, you must spend 10 marks to increase it to a d12.

##### HD Marks to Mark a Domain

You must spend 2 HD marks to mark any one domain.

If you spend 6 marks, you could mark a domain 3 times, mark 3 domains once each, or mark a domain
once and another twice.

##### HD Marks to Gain a Domain

If you have 3 domains, you must spend 3 marks to gain a new domain.

##### HD Marks to Gain a Companion Slot

If you have 2 companion slots, you must spend 6 marks to add a third companion slot.

##### HD Marks to Increase Die Count

If you have 1d6 HD, you must spend 6 marks to increase your HD to 2d6.

If you have 3d8 HD, you must spend 24 marks to increase your HD to 4d8.

##### HD Marks to Mark a Trick

You must spend 2 domain marks to mark any trick in that domain.

If you spend 6 marks, you could mark a trick 3 times, mark 3 tricks once each, or mark a trick once
and another twice.

##### Domain Marks to Gain a Trick Slot

If you have 3 trick slots for this domain, you must spend 9 marks to gain a new trick slot.

##### Trick Marks to Increase Die Count

If your trick's dice are 2d6, you must spend 12 marks to increase them to 3d6.

If your trick's dice are 4d12, you must spend 48 marks to increase them to 5d12.

##### Trick Marks to Increase Use Count

If you can use your trick 1/scene, you must spend 3 marks to increase your use count to 2/scene.

If you can use your trick 3/scene, you must spend 9 marks to increase your use count to 4/scene.

### Tricks

Tricks are always specific to their domain. They make the probable automatic, the unlikely probable,
or the impossible possible. Tricks have a die size and count, marks, and uses per scene. Tricks
start at 1d6 with 0 marks and 1 use per scene.

Tricks add new mechanisms or modify the existing mechanisms in a limited way. They may be spells,
extraordinary abilities, functions of magic items, reflections of preternatural skill, or anything
else that makes sense to you.

Tricks may be limited by a trigger or they may be used whenever you please, as long as you have at
least one use left in the scene.

#### Example Tricks

There is no limit on what a trick can be or do, so long as you and the folks at your table agree to
it. The tricks listed below are examples, not the totality of possible tricks.

##### Burning Blade

Roll the trick dice whenever you please. Add your result to your damage for the rest of the scene.

##### Call Lightning

While outside, pick a point you can see and roll the trick dice. You deal result damage to
everything nearby.

##### Castigate

Roll the trick dice when rebuking someone. Any attempts to interact with you for the rest of the
scene require a test to beat the highest die in your result.

##### Darken Sky

Roll the trick dice while attacking at range. Add your result to your test to hit.

##### Disappear

Roll the trick dice whenever you please. For the rest of the scene, Any attempts to spot you for the
rest of the scene require a test to beat the highest die in your result.

##### Encyclopedic

Roll the trick dice whenever trying to recall information related to your domain. You know as many
facts as your result about the topic.

##### Fly

Roll the trick dice whenever you please. For result turns, move yourself and/or anything you choose
freely through space. Count an extra turn for each entity flown.

##### Knit Flesh

Roll the trick dice whenever you please. Your target regains result HP.

##### Rage

Roll the trick dice whenever you please. For the rest of the scene, add your result to any
aggressive/physical action, and subtract it from any defensive/mental action.

##### Reflect

Roll the trick dice whenever you're holding your shield and defending against a magical attack. Use
your result as your roll for the contest. If you win the contest, the attack affects the caster.

##### Riposte

Roll the trick dice when defending against a melee attack. Deal your result as damage to the
attacker.

##### Shatter

Roll the trick dice when attacking an item. Add your result to the damage.

##### Summon

Roll the trick dice to raise one or more entities. Your trick dice are their HD and your result is
their HP. You may split the trick dice between multiple entities, rolling separately for each.

##### Telepathy

Roll the trick dice whenever you want to convey a message. You can wordlessly transmit result words
to anyone you can see.

##### Uncanny Block

Roll the trick dice when defending. Add your result to your contested roll.

### Action & Combat

Action scenes are any points in the game where who's doing what and when matters to the table.
They include chases, fights, infiltrations, etc.

#### Taking actions

In an action scene, participants declare up to two actions in order from lowest HD to highest. Where
there are ties, agree who goes first or roll off. Resolve all actions simultaneously as makes
sense.

#### Distances

Distances are tracked as zones: adjacent, nearby, distant, and far. Participants can move anywhere
nearby as an action or distant as two actions.

#### Attacks

Attacks are always contested. In melee, the highest result is the damage dealt to the participant
with the lowest result. At range, if the shooter's result is lower, they miss.

#### At 0 HP

When you drop to 0 HP, choose one immediately:

``````tabs { #WhenDying }

```tab { name="Carry On" }
Transfer your current marks to a loved one. You died, but live on in them.
```

```tab { name="Save Self" }
Test. If successful, you return to 1 HP but are unable to participate for the rest of the scene.
```

```tab { name="Use It" }
Sacrifice 1 HD to get back into it. Reroll your remaining HD. You're back in action with result HP.
```

```tab { name="Wait It Out" }
Roll your HD. Unless someone renders first aid in result rounds, you die.
```
``````

You can spend an action to give first aid to someone else, testing to bring them back to 1 HP. If
rendering first aid after the combat scene ends, no test is required if you have a relevant domain.

### Companions & Hirelings

You can have as many companions as you have companion slots, if you can convince them to follow you.
Companions are picaroons in their own right.

You can have as many hirelings as you can afford and convince to work with you. Hirelings are
temporary followers who expect at least weekly remuneration. They expect daily remuneration if you
ask them to face danger. This table indicates how they're priced in silver:

| Feature |               Cost               |
| :------ | :------------------------------: |
| HD      |     +1 per die and die step      |
| Domains |         +1 per die step          |
| Tricks  | +1 per die, die step & extra use |

```details { summary="Examples" .info }
If a hireling's HD is 2d6, they expect at least 2s. If their HD is 2d8, 4s.

If a hireling has two domains, one at d6 and one at d10, they expect at least 4s.

If a hireling has a trick at 2d8 they can use 3 times per scene, they expect at least 6s.

A hireling with 2d8 HD, a d6 domain and a d10 domain, and a 2d8 trick with 3 uses per scene expects
at least 14s per week.
```

#### Sample Hirelings

Unless noted, hirelings can use tricks once per scene.

##### Yan

``````columns { #yan-hd-and-pay }
```column
HD: 2d6
```

```column
Pay: 6s
```

```column
&nbsp;
```
``````

> A skilled cook with a short temper, an iron stomach, and endless resourcefulness. Yan uses
> their foot-long knife to prepare meals, even when the dish fights back.

|  Domains   |    Tricks    | Effect                                                     |
| :--------: | :----------: | :--------------------------------------------------------- |
| Chef (d10) | Make Do (d6) | Prepare result meals from random detritus available nearby |

##### Diya

``````columns { #diya-hd-and-pay }
```column
HD: 3d6
```

```column
Pay: 10s
```

```column
&nbsp;
```
``````

> An unremarkable mercenary in shoddy gear with a sweet smile and long drawl. Diya's body count
> is stacked at least thrice her height. No one will duel her anymore.

|     Domains     |     Tricks      | Effect                             |
| :-------------: | :-------------: | :--------------------------------- |
| Sellsword (2d8) | Heartrend (2d6) | On hit, add result to damage total |

##### Frankie

``````columns { #frankie-hd-and-pay }
```column
HD: d6
```

```column
Pay: 10s
```

```column
&nbsp;
```
``````

> A fast talker in clothes that cost as much as a new fountain. If you want it, Frankie has it or
> can get it. He drives a hard bargain and has a way of getting what he wants.

|       Domains       |       Tricks       | Effect                                   |
| :-----------------: | :----------------: | :--------------------------------------- |
|    Merchant (d6)    | Haggle d8, 3/scene | Reduce price by result                   |
| Rooftop Runner (d8) |  Clamber Up (2d6)  | Climb any surface result yards with ease |

## Picaresques

Start your first (or any) session in media res.

Roll 1d6 or choose:

1. [**Goblin Thieves**](#1-goblin-thieves)
1. [**Before the Petrified Sorcerer**](#2-before-the-petrified-sorcerer)
1. [**When the Gendarmes Laid Low**](#3-when-the-gendarmes-laid-low)
1. [**She Won't Let You Sleep**](#4-she-wont-let-you-sleep)
1. [**The Old Man & the Bath**](#5-the-old-man--the-bath)
1. [**In Search of the Silver Lily**](#6-in-search-of-the-silver-lily)

### 1. Goblin Thieves

The local farmers have hired you (100s, if successful), to Do Something about the goblins who keep
sneaking into town and stealing pigs. You've been lying in wait and have jumped into the road to
accost the returning raiding party (1d6 goblins, one in a Fancy Hat).

The goblins are (d6):

| Result | Mien                                            |
| :----: | :---------------------------------------------- |
|   1    | Utterly Surprised                               |
|   2    | Scrambling to flee in all directions            |
|  3--4  | Wary, fingers gripping pilfered kitchenware     |
|   5    | Confused, chattering & arguing about what to do |
|   6    | Hostile, approaching with murder in their eyes  |

For the rest of the adventure, reference [Alex Damaceno][gt-01]'s _The Goblin Caves_, which you'll
find on [itch][gt-02] and wherever quality adventures are sold.

### 2. Before the Petrified Sorcerer

You're chasing down the corrupt guard captain. The town council is paying good silver (500/1000) for
him dead or alive. He stands before a 7' mage statue, bejeweled rapier drawn and cape tattered. The
sun is setting as shadows lengthen.

He is (1d6):

| Result | Mien                                         |
| :----: | :------------------------------------------- |
|   1    | Begging for his life and freedom             |
|   2    | Muttering something to himself, eyes darting |
|  3--4  | Flustered, putting on a brave face           |
|   5    | Determined, reaching for a flask on his hip  |
|   6    | Pointing his sword, darkness seeping from it |

For the rest of the adventure, reference [Lucas Rolim][btps-01]'s _Petrified Sorcerer_, which
you'll find on [itch][btps-02] and wherever quality adventures are sold.

### 3. When the Gendarmes Laid Low

The court found you guilty on the word of a filthy rich merchant for crimes you might have
committed. 1d6 gendarmes step into the tavern you're in as the world rumbles. They glance at each
other, lock eyes with you, and are crushed flat when the wall collapses.

The tavern patrons are (d6):

| Result | Mien                                              |
| :----: | :------------------------------------------------ |
|   1    | Stunned, perfectly still and staring              |
|   2    | Laughing and pointing at the hated gendarmes      |
|  3--4  | Startled from their places, looking at each other |
|   5    | Staring upward at the creaking ceiling            |
|   6    | In motion, checking on each other calmly          |

For the rest of the adventure, reference [Chris Bissette][wgdll-01]'s _The Calamitous Creation of
the Guild of Mechanised Artistry_, which you'll find on [itch][wgdll-02],
[Loot The Room][wgdll-03], and wherever quality adventures are sold.

### 4. She Won't Let You Sleep

You offended her, somehow. It's been 1d6 days since you last slumbered, and 1d6 hours since the sun
set. You've found her, singing lullabies to herself in her cottage deep in the woods. At last,
perhaps, you can lift this damned curse.

She is (d6):

| Result | Currently                                         |
| :----: | :------------------------------------------------ |
|   1    | Stitching silver thread into her black cat's hide |
|   2    | Reading an ancient tome by candlelight            |
|  3--4  | Playing an incomprehensible board game, alone     |
|   5    | Arranging flowers into a writhing wreathe         |
|   6    | Sharpening a copper blade, slow & smooth          |

After the picaroons finally get to sleep, reference [M.A. Guax][swlys-01]'s _Above the Monkey God_
for the rest of the adventure, which you'll find on [itch][swlys-02] and wherever quality
adventures are sold.

### 5. The Old Man & the Bath

An ancient man seeks to bathe in healing waters long rumored and never seen. He promised you
enormous wealth (600s up front, 1800s on return) to keep him safe on his quest. Two months of travel
and hardship and you've found them, at last. The man slips, fully clothed, into a pool of dark
bubbling water.

Then he (1d6):

| Result | Consequence                                       |
| :----: | :------------------------------------------------ |
|   1    | Slips under the surface, never to return          |
|   2    | Melts, screaming and flailing, after mere seconds |
|  3--4  | Arises, strong and proud, frenetic and glowing    |
|   5    | Blinks, confused, as apparently nothing happens   |
|   6    | Transforms, a lion's head erupting from his skull |

For the rest of the adventure, reference [Noora Rose][tomtb-01]'s _Saffron DOOMCRAWL_, which you'll
find on [itch][tomtb-02] and wherever quality adventures are sold.

### 6. In Search of the Silver Lily

A young woman with bulging eyes was calling out for help. She promised you her weight in silver for
the petals of a magic flower if you'd just retrieve it from a cave known as The Mudfish's Maw. She
handed you a map and now, two weeks later, you can see the cave. You also see a tiger stalking a
hat-wearing frog.

The frog is (1d6):

| Result | Mien                                               |
| :----: | :------------------------------------------------- |
|   1    | Blowing multicolored bubbles which rise lazily     |
|   2    | Hopping up and down, dancing and splashing         |
|  3--4  | Ribbiting away, the tune jaunty and hopeful        |
|   5    | Fiddling with their hat, adjusting the way it sits |
|   6    | Chewing, talking to itself with a full mouth       |

For the rest of the adventure, reference [Sin Posadas][issl-01]'s _Hark! Says the Frog Magus_,
which you'll find on [itch][issl-02] and wherever quality adventures are sold.

<!-- Reference Links -->
[1]: https://twitter.com/pangalactic
[2]: https://loottheroom.itch.io/
[3]: https://www.patreon.com/loottheroom
[4]: https://chrisbissette.bandcamp.com/
[5]: https://loottheroom.uk/shop
[6]: https://twitter.com/daishugars
[7]: https://daishugars.com/
[8]: https://twitter.com/infinite_mao
[9]: https://s-jared.itch.io/
[10]: https://spearwitch.com/
[11]: https://twitter.com/rolimllucas
[12]: https://lucasrolim.itch.io/
[13]: https://twitter.com/LukeGearing
[14]: https://lukegearing.blot.im/
[15]: https://lukegearing.itch.io/
[16]: https://twitter.com/TraverseFantasy
[17]: https://chiquitafajita.blogspot.com/
[18]: https://traversefantasy.itch.io/
[19]: https://twitter.com/micaholism
[20]: https://micah-anderson.itch.io/bastards
[21]: https://twitter.com/HypatiasAngst
[22]: https://www.drivethrurpg.com/browse/pub/14216/Orbital-Intelligence-LLC
[23]: https://twitter.com/BigFnMikey
[24]: https://leanpub.com/u/michaeltlombardi
[25]: https://www.oldbookillustrations.com/titles/coleccion-de-laminas-en-color-representando-tipos-de-diversos-paises/
[26]: https://twitter.com/monkeyspawgames
[27]: https://monkeys-paw-games.itch.io/
[28]: https://monkeyspawgames.com/
[29]: https://twitter.com/sivads_sanctum
[30]: https://sivads-sanctum.itch.io
[31]: https://zeshio.itch.io/yolnajjforest
[32]: https://www.patreon.com/zeshio
[33]: https://twitter.com/zeshio
[34]: https://zeshio.itch.io
[btps-01]: http://twitter.com/rolimllucas
[btps-02]: https://lucasrolim.itch.io/petrified-sorcerer
[gt-01]: https://twitter.com/GnarledMonster
[gt-02]: https://gnarledmonster.itch.io/the-goblin-caves
[issl-01]: https://twitter.com/diwataMANILA
[issl-02]: https://diwatamnl.itch.io/hark-says-the-frog-magus
[swlys-01]: https://twitter.com/maguaxRPG
[swlys-02]: https://maguax.itch.io/above-the-monkey-god
[tomtb-01]: https://twitter.com/rosesonhergrave
[tomtb-02]: https://monkeys-paw-games.itch.io/saffron
[wgdll-01]: https://twitter.com/pangalactic
[wgdll-02]: https://loottheroom.itch.io/mech-art
[wgdll-03]: https://loottheroom.uk/product/the-calamitous-creation-of-the-guild-of-mechanical-artistry
