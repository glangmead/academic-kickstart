---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "D&D Adventure System House Rules"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2024-09-07T21:06:01-04:00
lastmod: 2024-09-07T21:06:01-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

The following is a list of ideas I gathered for adding flavor and tactics to D&D board games in the Adventure Game system. Personally we own [Tomb of Annihilation](https://shop.wizkids.com/products/dungeons-dragons-tomb-of-annihilation-adventure-system-board-game-standard-edition).

Environment

- outdoors in Chult there might be a tropical storm
  - PCs get Exhaustion 1, and do a DC 10 Constitution check or gain Exhaustion 2
  - Exhaustion 1: ability checks have disadvantage
  - Exhaustion 2: speed halved
- With black triangles, roll D2 and either draw an Encounter card or draw a monster

Saving throws for any traps (or trap encounters, like hidden tripwire, hail of traps)

  - maybe roll 11+ like in the base rules, but with advantage if AC 15 or less)
  
Enemy mechanics adapted from their stat blocks

- Saving throws for PCs
  - Firenewt: flame breath (dexterity, D2 if AC 15 or less)
  - Su-monster: psychic crush (wisdom, D2 for druid, wizard)
- Velociraptors gain advantage for their attacks if another veloci is adjacent to it or flanking the target.
- Yuan-Ti broodguard can roll with advantage on melee attacks but PCs roll with advantage against them as well. Roll a D2 when at the start of their turn to decide if they are adopting this tactic. If so, mark them with a token so that the next hero attack has advantage, then remove the token.
- Zorbo: magic resistance, roll with disadvantage for any magical attacks on it

4e rules to bring in

* **Flanking**: get on opposite sides with an ally, and you can get combat advantage. Might be negated if one of you can't attack or perhaps other statuses.
* **Aid**: if you are in melee range, roll against DC10 and if you succeed, deal no damage but an ally gets +2 to their attack roll, until your next turn. You can do the same with an ability, and the ally gets +2 against the same ability check.
* **Opportunity** actions are allowed against an opponent *on the opponent's turn* if 
  * the opponent leaves a square adjacent to you (not counting shift/teleport/push/pull/slide)
  * the opponent uses a ranged or area power
  * you are able to make a melee attack and see the enemy
  * (if those hold, the opportunity action is one action you get during the current character/monster's turn)

[From web](https://docs.google.com/document/d/10CqWFWROhWVDhvtRBiAoO0G14j9wBDzuRouAw1X4Sbo/edit)

- **General**
  - When rolling d20, 20 is always a success, 1 is always a failure regardless of the modifiers
    - the rulebook actually says a 20 deals +1 damage
  -   When heroes are moved by an encounter/trap/monster, they go to the monster movement squares (or Ambush squares if there are no movement squares) 
  -   Active Environment cards can be canceled by spending the regular amount of XP
  -   Heroes can level up to level 4.
  -   Level 3 (and 4) heroes' all At-Wills deal an extra point of damage on an even roll that hits
  -   Level 3 (and 4) heroes may replace their fixed At-Will with another of their At-Wills
  -   Hero level is the maximum cap on how many Advancement Tokens can be equipped for an adventure. You may "own" an unlimited number of Advancement Tokens. (the chevron shaped tokens like "Reroll")
  -   Multiple similar Advancement Tokens cannot be spent during one attack
  -   Disadvantage can be removed by spending an Attack Action
* **Automated Difficulty Scaling**
  -   If you did not use a Healing Surge (HS) and you already have only one/adventure, increase the number of tiles in the following adventures by +1.
  - If you lose the game and you have additional tiles in play, instead of adding a HS, remove 2 extra tiles from play. If you only have 0-1 extra tiles in play, then add the HS as usual in addition to removing the possible extra tile.
* **Exploration**
  * Warrior types (Defensive Approach): Monsters from the newly explored tile make all attacks at disadvantage against the hero until your next hero phase
  * Rogue types (Find Traps): If the revealed tile has a trap, get a free disarm before it activates, all traps make attack rolls at a disadvantage against the hero until your next hero phase
  * Spell casters (Divination): Cost to discard an encounter is halved, round up (so 5 XP -> 3 XP), encounter attacks (excluding traps) are made at disadvantage against your hero
  * All heroes (Stealth): Hero must roll their AC or higher (rogues roll with advantage). If successful, place a stunned marker on a newly revealed monster (thematically the monster is surprised by the hero’s approach, high AC has correlation to armor usage, which is why the roll is versus their AC).
* **Treasure**
  * You only get a treasure card when your hero kills a monster during your hero phase.
  * A treasure item already in play may be given/taken to/from another adjacent willing hero using the attack action
* **Monsters**
  * Monsters avoid squeezing, if possible, when following their tactics
  * When duplicate monsters are drawn, place the card on top of an existing monster card (they only activate once during the villain phase).
  * Villains: Remove (round down(HP/10)) *(5 - # heroes) HPs from villains. 
    * So villains that initially have 10-19 HP, have one less HP for each "missing" hero (compared to a full party of five), villains with 20-29 HP two HP less for each missing hero. 
    * Example: Villain has 16 HP and there are 3 heroes in play. Villain starts play with 1*(5-3)=2 HP removed -> 14 HP.
* **Tomb of Annihilation**
  * Druid’s Call Lightning: When used on a Dungeon Tile (indoors), make all attack rolls with Disadvantage
  * Mage’s Mage Armor sets the AC to 17 until discharged (on a roll of 17-20)
  * Bard’s Inspire Courage ability works on 2 heroes on the tile (bard can benefit from the advantage)
  * Hidden outpost, each hero may benefit from the bonus only once. 
  * Lich Necromancer (4XP) Tactics:
    * If the Lich Necromancer is the only Monster you control, place a new Monster on its tile.
    * If Lich Necromancer is adjacent to a hero, cast Vampiric Touch/Bestow Curse/Ice Storm/Magic Missile
    * If the Lich Necromancer is within 2 tiles of a Hero, it attacks the closest Hero with a ray of fire.
    * Otherwise, pass this card to the player on your right
