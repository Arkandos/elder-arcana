# Elder Arcana

# Elder Arcana

*By Arkandos*  
Elder Arcana is a fantasy tabletop roleplaying game about fantastical characters overcoming the odds. It plays out over long timescales, as months and possibly years pass on by and the world changes between adventures.  
While at its core a tactical combat game, there are many ways to express your character and explore outside of battles. Indeed, this is required to ensure that your fragile characters survive to see another sunrise. With exploding dice, death and destruction could strike at any moment.

Inspired by many ttrpgs around, but drawing heavily upon the systems of  Earthdawn and Ars Magica. Thank you to all my inspirations, and all the people who have helped me along the way.

# Core Rules

## Dice Mechanics

Most dice rolls in the game are Tests. Tests are  
(1d10 \+ attribute \+ ability rank) is your test result, which is compared to a target number (TN) or opposed test.  
1’s explode, roll again and double that roll (which cannot botch). If you roll another 1, quadruple the next roll instead. There is no limit on the number of times a roll can explode.  
10’s are potential botches of critical failures.

Equal or higher to the TN means a success, with every 5 above the TN means you have scored an additional success.

Rolling lower than the TN means you fail the test.

## Botches

Rolling a 10 means you potentially botch the test. This means you make a special botch roll, rolling a number of d10 decided by your GM (usually 1 but circumstances may call for more).  
Count how many 10’s you rolled. If you rolled no 10’s, you have not botched and the triggering test counts as if you had rolled a 0\.  
If you rolled one or more 10’s, the test has botched. It goes awry in the most catastrophic way, increasing in severity for every 10 rolled. For most types of test the **total** is reduced to 0, in addition to any negative effects that the botch may cause.

A botched attack may cause you to drop your weapon, a botched conversation may enrage the opposing part. A botched defense roll often spells certain doom, as the enemy’s attack hits your defense total of 0\.

## Bonus dice

Some abilities may grant bonus dice to a type of roll or test. They are listed as \+1d6, denoting how many and what size to roll. Bonus dice can never explode or botch. 

## Time

Time is an important resource in **Elder Arcana** and has some special definitions here. In encounters, time and the order of operations matters the most. An encounter round is 6 seconds, meaning there are 10 rounds per minute. While in exploration mode, most actions take one phase which is 10 minutes. Downtime which happens between adventures is measured in months.

## Order of Resolution

If there ever is a conflict between multiple effects occurring at the same time, resolve them in the following priority:

1) First resolve all negative effects that would apply  
2) Then resolve all positive effects that would apply  
3) If you need to resolve multiple effects at the same step, the affected character may choose the order to resolve them in. If affected by both a curse and a poison (both negative effects) at the start of their turn, the affected character may choose to resolve either of them first.

## Costs

Many effects in this game have an associated cost. A cost must be paid to use an effect.. If a cost lists “up to X”, you may choose to pay a cost of 0\.

## Ranges

While most ranges are defined as a number of meters, there are a number of special ranges used in this game.

* Melee: Anything you can touch with a Weapon, usually 1m away from yourself.  
* Close (X): Up to 5 \* the rank of X meters   
* Medium (X): Up to 30 \* the rank of X meters  
* Far (X): Up to 100 \* the rank of X meters  
* Sight: As far as you can see

## Relations

Sometimes the level of relation you have with NPCs may be important. Therefor the relations are codified in the following manner to help both players and GMs estimate how well an NPC thinks of you:  Hostile \- Negative \- Neutral \- Positive \- Friendly  
Improving a relation by 1 step moves it towards Friendly, reducing a relation by 1 step moves it towards Hostile.  
Hostile does not mean that they will attack you on sight, but they will actively work against you.

## Golden Rule

This rules reference is the definite source of rules. A specific mechanic may override these rules. If an effect forbids you from performing some act, that effect is absolute unless another effect specifically counteracts it. You must perform an act preceded by “must”, and may opt to ignore one preceded by “may”. Effects preceded by “then” or worded as “you may pay X to do Y” are only allowed if the preceding effect was true, or its cost paid (where applicable)

[Character creation]()

# Encounters {#encounters}

Encounters are stressful situations where time is of the essence. It could be a fight, escaping a collapsing building, or trying to catch a fleeing thief. While in an encounter, you have a certain number of [Actions](#actions) to take on your turn in [Initiative](#initiative) (see below)

## Initiative {#initiative}

Since the order of who goes when is important in an encounter, everyone involved makes an Initiative Test every round to see what order they act in. The highest test result goes first, taking their turn. Once they have completed their turn, the round continues in descending order until everyone has taken a turn. Then the next round begins, and everyone makes a new Initiative Test.

## Distance & Areas

Distances in **Elder Arcana** are measured in meters. Encounters take place on an ungridded map, where distances are measured point-to-point. This means you measure from your token’s edge, and another token is in range if its edge is within the measured distance.  
There are multiple types of area targeting in encounters. These include bursts (a circle with X radius), cones, lines, and Auras (X meters away from a creature). A creature is affected by an area if the center of their token is in the area (pending change depending on foundry implementation).

## Facing

Creatures have a directional facing in this game, which must be in an intercardinal direction. Whenever you take an action or end your movement, you may change your facing. In general, you must face in the direction of whatever you are affecting. If you attack a creature from behind, you flank them (see [Conditions](#conditions-&-modifiers))  
Once per round outside of your turn, you may change your facing. However, all enemies in your rear facing (before you change it) may make an [Opportunity Attack](#bookmark=kix.rp4ts154grgj) against you.

## Rally

Certain effects allow you to Rally against them, ending them on a successful test. At the end of your turn when you are affected by a Rally effect you may make an associated Test, ending it on a success.

## Actions {#actions}

During an encounter, the way you can act is limited. You can move a number of meters equal to your Speed called a [Stride](#bookmark=kix.ddmwuncdz2pi), but must use it all before or after taking an action (unless splitting movement, see [Stride](#bookmark=kix.ddmwuncdz2pi))  
During your turn, you can take a Major action and a Minor action.  
In place of a Major action, you may either [Stride](#bookmark=kix.ddmwuncdz2pi) again or take a Minor action.  
Outside of your turn, you can also take a Reaction during certain triggers.

**Stride \[Basic\]**  
Major Action.  
Effect: You move a number of meters up to your Speed. Before moving, you may spend 1 Health to split your movement up, being able to take actions in the middle of movement.

**Melee Strike \[Basic\] \[Weapon\]**  
Major Action.   
Melee Weapon, 1 enemy  
Attack: DEX+Brawl or DEX+Weapons(Melee) vs Physical Defense  
Effect: Success means you deal the Weapon damage to the target, with a \+1d6 bonus damage for every additional success. Brawl damage is 1d6+STR.

**Ranged Strike \[Basic\] \[Weapon\]**  
Major Action  
Ranged Weapon, 1 enemy  
Effect: Make a DEX+Weapons(Ranged) Test vs the Physical Defense of the target, taking a \-2 penalty if the target is within the second range of your Weapon. Success means you deal the Weapon damage to the target, with a \+1d6 bonus damage for every success.  
Ranged attacks may hit intervening creatures. Draw a line from you to the target. For every creature in the line other than the target, you take a \-2 penalty and risk hitting them. If you miss the target, compare your Test result (without the penalty) to the rear-most creature in the line as if you were targeting them instead.  
If that also misses, keep comparing to the next creature in the line, adding a \-2 penalty for each one.

**Dodge \[Evade\]**  
Free action (up to Brawl Rank times / round). 1 Health.  
Trigger: An attack would hit your Physical or Magic Defense  
Effect: Make a DEX+Brawl Test against the triggering attack total. Success means the attack misses you instead.  
Evade: You can only use one Evade ability against a particular effect.

**Change Stance**  
Free action when your turn starts.  
Effect: Choose one effect that lasts until the start of your next turn:
* Offensive: You gain a \+3 bonus to Melee attacks. You take a \-3 penalty to your Physical and Magic Defense.  
* Defensive: You get a \+3 bonus to Physical and Magic Defense. You take a \-3 penalty to all Tests.

**Channel \[Basic\]**  
Major Action. 1 Health.  
Effect: You regain 3+INT Weave.

**Quick Channel \[Basic\]**  
Minor Action. 1 Health.  
Effect: You regain 1d6-3 Weave (minimum 0\)

**Stand Up \[Basic\]**  
Major Action.  
Effect: You stand up from Prone.

**Kip Up \[Basic\]**  
Minor Action. 1 Health  
Effect: Make a DEX+Acrobatics \- Initiative penalty (6) Test. Success means you stand up from Prone. This Test ignores the penalty from being Prone.

**Stabilize \[Basic\]**  
Major Action.  
Melee, 1 dying creature.  
Effect: Make an INT+Medicine Test against the absolute value of the target's Health. Success means they stabilize and stop dying.

**Opportunity Attack**  
Reaction  
Melee Weapon, 1 enemy  
Trigger: An enemy moves away from your facing without shifting, or changes its facing out of turn while you face their rear.  
Effect: Make a [Melee Strike](#bookmark=kix.lzqxgyyiqpdl) against them.

**Guard \[Basic\]**  
Minor Action.  
Effect: Until the start of your next turn, enemies that move around you trigger an [Opportunity Attack](#bookmark=kix.rp4ts154grgj).

**Disengage \[Basic\]**  
Major Action.  
Effect: You shift a number of meters equal to your Speed. Shifting ignores most Reactions. You cannot move any more until the start of your next turn.

**Knockdown**  
Free action  
Trigger: You take a Wound and would fall Prone.  
Effect: Make a Strength Test against half the damage that caused the Wound. Success means you remain standing.   
Also known as a “Knockdown Test”.

# Exploration

Most of an adventure is played through in exploration mode. When counting time is important, it is counted in Phases (each Phase being 10 minutes). While exploring is certainly covered in exploration mode, it covers everything that takes longer than an Encounter, but shorter than Downtime.

One of the most common actions taken during Exploration is to spend a Recovery, rolling 1d10 \+ your Recovery value \+ Wound penalty (if any) and restoring that much Health.

You may rest once per day, taking 8 hours. After completing a rest, you refill your Weave and Mythos pools, and all your Recoveries. You also reduce your Wound severity (if any) by 1 step.

# Downtime

Downtime takes place whenever there is a significant amount of time without an ongoing adventure. Downtime is measured in months, and is where you can undertake long-term projects.

Advancing to the next Echelon is a common downtime project.

# Conditions & Modifiers {#conditions-&-modifiers}

**Flanking**  
When you attack an enemy from their rear facing, you gain a \+2 bonus and ignore their shield bonuses.

**Prone**  
You take a \-3 penalty to all Defenses and Tests.

**Blinded**  
\-4 to any Test that requires sight. When moving over uneven terrain, you may be required to make Acrobatics Tests or fall Prone.

**Staggered**  
Your Speed is halved and you cannot Shift. Whenever you take a Major or Minor action, lose 1 Health.

# Additional Effect

## Additional Successes

On a test, every 5 you roll above the target number gives an additional success. These can be spent on most effects to increase their efficacy. If multiple options are available, they are separated by semicolons. You can choose the same effect multiple times.  
When comparing a test result against multiple targets, the additional success effects are applied individually for each target. For example, comparing a result of 10 against two targets defenses that are 8 and 5 individually would mean you score 1 additional success against the second target.  
Example  
Additional Successes: Increase damage by 1d6; increase the penalties by 2\.

## Enhance X

Some powers can be improved by spending X (either Health or Weave) as noted in parenthesis before using them. If multiple options are available, they are separated by semicolons. You can select the same enhancement multiple times, paying the cost each time.  
Example  
Enhance Weave: Increase range by 10m (1); increase damage by 2 (1)

# Characters

# Characters

Player characters can come from a number of different species, and have a wide variety of attributes and abilities.

## Character Creation

1. Choose a [Kith](#kith) and note down its features.  
2. Choose your starting Attributes. Attribute bonuses from Kith are applied after your choices.  
3. Assign your starting Base Abilities.  
   1. Assign the numbers from the following array as the Rank of any [Base Ability](#base-abilities) you wish: 3, 3, 2, 2, 1, 1  
4. Spend 25 Experience on any [Adept Abilities]() of Tier 1, or Base Abilities.  
5. Spend 20 Art points on any Arts, and pick 3 powers from among those Arts.   
6. Spend 150 silver on starting [equipment]().

## Attributes

Every character has X number of attributes with scores from \-3 to \+3, starting out at 0\.

1. Strength	(STR)  
   1. Physical prowess, raw power. Strength improves the damage of your weapons, your carrying capacity, what equipment you can use, and adds to your Physical Defense.  
2. Dexterity 	(DEX)  
   1. Agility, finesse and quickness. Dexterity improves the accuracy of your weapons, your Speed, Initiative tests, and adds to your Physical Defense.  
3. Stamina	(STA)  
   1. Endurance, constitution. Stamina increases your Health, Rallies you against physical ailments, reduces the damage you take, and determines your daily Recoveries.  
4. Intelligence	(INT)  
   1. Analysis, observation. Intelligence improves the potential of your magic, the range of certain abilities, increases your Weave, and adds to your Magic Defense.  
5. Willpower	(WIL)  
   1. Determination, control. Willpower improves the potency of your magic, increases your Mythos, Rallies you against mystical ailments and adds to your Magic Defense.  
6. Presence	(PRE)  
   1. Charisma, communication. Presence influences others, and adds to your Mental Defense.

   

When assigning your starting Attributes, you have 10 points to spend. Costs increase to gain a higher attribute, but you may gain additional points by lowering an attribute. An attribute cannot be higher than \+3 nor lower than \-3 (except due to Kith modifiers)

| Attribute | Point cost |
| :---- | :---- |
| \+3 | 6 |
| \+2 | 3 |
| \+1 | 1 |
| 0 | 0 |
| \-1 | Gain 1 point |
| \-2 | Gain 3 points |
| \-3 | Gain 6 points |

## Statistics

Statistics are derived from your attributes and cannot be directly improved.  
Health: 20 \+ 2 \* Stamina  
	How much damage you can suffer before going unconscious or dying.  
Speed: 10 \+ Dexterity  
	How many meters you can move each [encounter round](#encounters).  
Initiative: 3 \+ Dexterity  
Physical Defense: 6 \+ Strength \+ Dexterity  
	How difficult you are to hit in physical combat  
Magic Defense: 6 \+ Intelligence \+ Willpower  
	How difficult you are to hit in magical combat  
Mental Defense: 6 \+ 2 \* Presence (or 1\*Presence if negative)  
	How difficult you are to manipulate  
Physical & Magic Armor: Stamina  
	Reduces the damage you take  
Weave pool: 3 \+ Intelligence. (Minimum 1\)  
	Used to pay for magical abilities. Refreshes every day. You can [Channel](#bookmark=id.588xy6c7n2bp) to regain Weave faster, but this costs Health.  
Mythos pool: 3 \+ Willpower.  
	Used to reroll Tests. Refreshes every day.  
Recoveries: 1 \+ Stamina (if positive)  
	Determines how many times per day you can heal damage.  
Recovery value:  1 \+ 2 \* Stamina (if positive).  
	Determines how much each Recovery spent heals you.

## Abilities

There are many abilities in Elder Arcana. Most tests involve adding one attribute score, and one ability rank. However this relation between them is not set in stone unless called for by an ability. Certain situations may call upon you to use a different attribute with the ability.  
Abilities are divided into Base Abilities (Tier 0), and Adept Abilities (Tier 1 and above). Anyone can use a Base Ability (even at Rank 0\) unless it has an \* next to its name, meaning that it can only be used if you have at least one Rank in that ability.  
Adept Abilities can only be used if you have at least one Rank in them.

## Base Abilities {#base-abilities}

Artistry\*  
	Creating works of art, performing or producing music  
Acrobatics  
	Jumping, climbing, recovering from falls  
Awareness  
	Noticing the hidden, reaction time  
Bargain  
	Haggling, negotiating  
Brawl \[Martial\]  
	Hand to hand combat, dodging enemy attacks  
Craft (Category)\*  
	(Categories:)  
	Creating new objects or structures  
Command  
	Leadership, coercion, intimidation.  
Charm  
	Enticing and endearing others to you  
Guile  
	Lying, deceiving, disguising.  
Insight  
	Understanding others' state of mind & emotions.  
Medicine\*  
	Treating wounds and ailments.  
Language  
	For every Rank, you speak and write one language.  
Lore (Category)\*  
	(Categories: Arcane, Divine, Faerie, History, Natural, Infernal)  
	Remembering esoteric or distant knowledge.  
Ride  
	Maneuvering a mount, staying mounted.  
Stealth  
	Moving without being noticed, blending in.  
Study\*  
	Research topics, examine behaviours and weaknesses.  
Survival\*  
	Overcome wilderness dangers, navigate.  
Traverse  
	Covers climbing, swimming, passing through hazardous terrain  
Trickery\*  
	Sleight of hand, pickpocketing, lockpicking.  
Weapons (Melee) \[Martial\]  
	Fighting with melee weapons (but not unarmed)  
Weapons (Ranged) \[Martial\]  
	Fighting with ranged and thrown weapons.  
Weaving\*  
	Casting spells

## Kith {#kith}

Kith attribute changes and maximums are applied after you have assigned your starting attributes. When assigning your starting Base Abilities, you may add one of the given numbers to the Kith starting abilities you have. For example, a Human could add a 2 from the array to their Acrobatics to get a Rank of 3\. You cannot increase a Rank above 3 in this way.

**Human**  
Despite their short lifespan, humans are a force to be reckoned with on Coret. They learn and adapt quicker than any other kith, and have a natural aptitude for riding. Humans can be found in almost any society, their adaptability makes them get along with most kith.  
	Attribute changes: 	none  
	Speed modifier:	none  
	Size:			Medium  
	Starting abilities:

* Acrobatics (1)  
* Language (2): Human \+ any other common language  
* Ride (1)

Special traits:

* Versatility: Choose one of the following ability pairs. The Ranks of the pair are always equal to the highest one. Acrobatics-Traverse, Artistry-Craft, Awareness-Study, Bargain-Trickery, Brawl-Stealth, Charm-Guile, Command-Survival, Insight-Language, Medicine-Lore(Natural), Weapons(Melee-Ranged)

**Dwarf**  
Dwarves are longlived, short, and sturdy. Nicknamed the children of the rock, most dwarven societies are underground. Dwarven craftsmen are renowned and a point of pride. Elves and dwarves are natural friends, both enjoying the beauty of craftsmanship.  
	Attribute changes:	\+1 STA, max STR & STA increased by 1\.  
	Speed modifier:	\-3  
	Size:			Medium  
	Starting abilities:

* Bargain (1)  
* Craft (1)  
* Language (1): Dwarven

	Special traits:

* Stubbornness: Equipment you wear cannot reduce your Initiative below 0, or Speed below 7\.  
* Hardy: \+2 bonus to Magic Armor, and \+4 to all tests to resist diseases & poison.

**Elf**  
Elves are tall and long lived, with eerily symmetrical faces. They are agile and perceptive, but their slim build leaves them vulnerable to the dangers of the world. Elves are adaptable, even if it takes multiple generations to fully acclimate. They live in the depths of ancient forests, in magnificent underground cities, and even at the bottom of the sea. Elves and dwarves are natural friends, both enjoying the beauty of craftsmanship.  
	Attribute changes: 	\+1 DEX and INT, max DEX & INT increased by 1\.  
				\-1 STA, min STA decreased by 1\.  
	Speed modifier: 	\+4  
	Size:			Medium  
	Starting abilities:

* Awareness (1)  
* Language (1): Elven  
* Survival (1)

	Special traits:  
	Choose 1:

* Nature’s Guise: Whenever you make a Stealth test in a natural environment, you gain Fortune.  
* Elder Eyes: You see twice as well as others. This more than doubles the distance you can see in low-light conditions, and quadruples the distance you can clearly see things.

**Giantblood**  
Giantbloods, or half-giants is a common term for all those who have heritage of the larger folk. Larger, stronger and tougher than the average kith, giantbloods are well renowned warriors that take pride in honor and valor. While less perceptive than the average kith, they are far more quickwitted than the giants they hail from. Giantbloods have a special kinship with sprites, sharing both humour and troubles of size.  
	Attribute changes:	\+2 STR, \+1 STA, max STR & STA increased by the same.  
				\-2 INT, \-1 DEX, min INT & DEX decreased by the same.  
	Speed modifier:	\+2  
	Size: 			Large  
	Starting abilities:

* Brawl (2)  
* Command (1)  
* Language (1): Giant

	Special traits:

* Tough Skin: \+2 Physical Armor.  
* Large and in Charge: You suffer a \-6 penalty to Stealth, but gain a \+2 to Melee attacks in any round you have moved 10 or more meters.   
  Your Melee range is doubled, and you add \+4 to any forced movements you cause.  
* Giant Defender: It takes an additional enemy to flank you.

**Sprite**  
Sprites are tiny winged humanoids about the size of a rabbit. They are quick, and have a special aptitude for influencing other kith. Sprites claim that it's due to their cute size and positive demeanor, but anyone knowledgeable about sprites knows that it is due to their faerie origins. Sprites are all glamour-clad, with some being true cognizant faeries and others just having strong faerie blood. Sprite societies are very uncommon, consisting of at most a couple of families. Giantbloods have a special kinship with sprites, sharing both humour and troubles of size.  
	Attribute changes:	\+2 DEX, \+1 PRE, max DEX & PRE increased by the same.  
				\-2 STR, \-1 STA, min STR & STA decreased by the same.  
	Speed modifier:	halved when not flying (see traits)  
	Size:			Tiny  
	Starting abilities:

* Acrobatics (1)  
* Language (1)	Any common language  
* Trickery (2)

	Special traits:

* Flight: You have a Fly Speed equal to your normal Speed, which costs 1 Health for every Phase you fly. You cannot fly higher than 2 meters above the ground.  
* Kithshaper: When using a social ability like Charm or Guile against other Kith, you gain a \+2 bonus.

**Mythkin**  
Mythkin is a catchall term for those individuals who have magic in their blood since birth. They seem to have fate’s favor, being blessed with a natural luck and resistance to hostile magic. Depending on the society, mythkin are praised as good luck charms or shunned as a magnet that draws luck away from others.  
	Attribute changes:	\+1 WIL, max WIL increased by 1\.  
Speed modifier:	none  
Size: 			Medium  
Starting abilities:

* Artistry (1)  
* Language (1) Any common language  
* Weaving (1)

	Special traits:

* Mythos mastery: Whenever you increase your Mythos pool, increase it by an additional 1 (including at character creation)  
* Magic Resistant: \+2 Magic Defense, \+2 Magic Armor

**Shifter**  
Shifter is the term for all those shapechangers that lurk among kith. Naturally distrusted, many societies pin blame for much illdoing on shifters. Some shifters take pride in their capabilities, while others hide in plain sight hoping to never be revealed. Shifter societies are rare (at least openly).  
	Attribute changes:	none (see traits)  
	Speed modifier:	none (see traits)  
	Size:			Medium  
	Starting abilities:

* Guile (1)  
* Language (2): Shifter \+ any other common language  
* Stealth (1)

	Special traits:

* Shapechanger: As a Major action you may spend 2 Weave to change how you look to any other type of Kith. You may become any Size between Small (-4 Speed, \-1 STR, \+2 Physical Defense) and Large (+2 Speed, \+2 Dmg, 3 temporary health/Echelon). Imitating a specific individual is a Presence+Guile Test.  
  As a Minor action, you may adjust your attributes, gaining a \+1 bonus to one attribute and a \-1 to its opposite. This lasts until you use this Minor action again. Opposed attributes: STR-INT, DEX-WIL, STA-PRE.

**Elementalkin**  
Elementalkin is the term for those attuned to one of the four elements. Thus there are air, earth, fire, and waterkin. Some owe their heritage to elementally attuned creatures, others to some transformative event. While some elementalkin see their fate as a curse, most feel empowered. Elementalkin have a humanlike build, and generally congregate in small nomadic societies.  
	Attribute changes:	none (see traits)  
	Speed modifier:	none (see traits)  
	Size:			Medium  
	Starting abilities:

* Language (1): Elemental tongue of type  
* Lore (Magic) (1)  
* Traverse (1)

	Special traits:

* Kin: Choose one type  
  * Air: \+1 INT, \-1 STA. \+4 Speed. You have Fortune when climbing, jumping, or landing.  
  * Earth: \+1 STR, \+1 STA. \-1 Speed. You have Fortune when climbing. \+2 bonus to Knockdown tests.  
  * Fire: \+1 PRE, \-1 STR. \+2 Speed. You have Fortune when jumping.  
    \+2 bonus to Recovery value.  
  * Water: \+1 DEX, \-1 WIL. You have Fortune while swimming, and have a swim speed equal to your speed. You can breathe under water for an hour without issue. \+2 Weave.

**Celestial**  
Celestial is the name for those with divine heritage, descendants of the gods and their kin. Just like the damned, they are visually a varied kin depending on their heritage. Celestials have the weakest of bloodlines, and several generations may lapse before the celestial traits re-emerge. Thus celestial groups are uncommon, and generally have little relation to each other.  
Other kith treat celestials either as proof of the gods presence, or as a painful reminder how mortals have been left behind.  
Attribute changes:	\+1 PRE, max PRE increased by the same.  
			\-1 STR, min STR decreased by the same.  
	Speed modifier:	none  
	Size:			Medium  
	Starting abilities:

* Charm (1)  
* Language (2): Celestial \+ any other common language  
* Lore (Divine) (1)

	Special traits:

* Indomitable: \+2 Mental defense  
* Infravision: You can see heat as if it was a shimmering aura. This can allow you to detect the outline of creatures in complete darkness, if their heat differs from the environment.

**Damned**  
The Damned are what those with infernal heritage are commonly called, carrying strong negative connotations in many cultures. While some have indeed been cursed, most are connected to infernals by blood. Just like celestials, they are visually a varied kin depending on their heritage. Damned often congregate together, finding comfort in shared discrimination.  
Other kith generally treat damned with suspicion, wondering what nefarious deeds they have been chosen to fulfill.  
	Attribute changes:	\+1 INT, \+1 PRE, max PRE increased by 1\.  
				\-1 DEX, min DEX decreased by 1\.  
	Speed modifier: 	none  
	Size: 			Medium  
Starting abilities:

* Command (1)  
* Language (2): Infernal \+ any other common language  
* Lore (Infernal) (1)

	Special traits:

* Temptation: You may regain Mythos points by indulging in sinful activities. Infernal Devotions are 1 step cheaper for you.  
* Infernal Damnation: Your defenses are reduced by 3 against Infernal creatures and powers.

## Health, recovery, wounds, and death

Health  
Health represents how much damage you can take before becoming unconscious, and eventually die. Whenever you suffer damage, reduce your health by the same amount. Some effects cost Health, which directly reduces your health by that amount.  
To recover Health, you use Recoveries. During an Exploration Phase, you may spend a Recovery to recover 1d10 \+ your recovery value Health.

Wounds  
Whenever you take damage in a single instance equal to a third or more of your maximum Health, your wounds increase in severity and you must make a [Knockdown](#bookmark=id.l3hixbco5di8) test. The severity of wounds increases from nothing \-\> Light \-\> Medium \-\> Heavy.

| Wound | Penalty |
| :---: | :---: |
| Light Wounds | \-1 |
| Medium Wounds | \-3 |
| Heavy Wounds | \-5 |

The Wound penalty is applied to all Tests, Defenses, and to Recovery rolls. Wounds are harder to heal than Health. Each day spent resting reduces the severity of your Wounds by 1 step.

Dying and Death  
Once your health reaches 0, you become unconscious and start dying. Every round, you must make a Stamina Test of (your absolute health). Success means you do not lose any more Health this round. Scoring an additional success means you Stabilize and are no longer dying.  Failure means you lose 1 Health. When your health reaches a negative value equal to half your maximum Health, you die. 

Defeated  
In general, NPCs do not become dying as player characters do. Instead, they are Defeated when they reach 0 Health and can no longer act.

# Abilities

Abilities  
Abilities are how you handle most of your interactions with the world, as Tests are comprised of 1d10 \+ an attribute \+ an ability Rank. Abilities have two numerical values, Rank and Tier.  
Rank determines how invested you are in an ability, while Tier sets restrictions on when you have access to it. At the start of the game, you can only access Base Abilities and Tier 1 Adept Abilities.

# Ability Advancement

During the game, you can unlock new Abilities and improve the Rank of your existing ones by spending experience. Once you have Rank 1 of an Adept Ability, you may use it.

| To purchase rank | Experience cost to raise from previous rank | Total Experience cost from rank 0 |
| :---- | :---- | :---- |
| 1 | 5 | 5 |
| 2 | 10 | 15 |
| 3 | 15 | 30 |
| 4 | 20 | 50 |
| 5 | 25 | 75 |
|  |  |  |

# Base Abilities

Acrobatics  
	Jumping, balance, recovering from falls  
Artistry\*  
	Creating works of art, performing or producing music  
Awareness  
	Noticing the hidden, reaction time  
Bargain  
	Haggling, negotiating  
Brawl \[Martial\]  
	Hand to hand combat, dodging enemy attacks  
Craft (Category)\*  
	(Categories:)  
	Creating new objects or structures  
Command  
	Leadership, coercion, intimidation.  
Charm  
	Enticing and endearing others to you  
Guile  
	Lying, deceiving, disguising.  
Insight  
	Understanding others' state of mind & emotions.  
Language  
	For every Rank, you speak and write one language.  
Lore (Category)\*  
	(Categories: Magic, Divine, Faerie, History, Natural, Infernal)  
	Remembering esoteric or distant knowledge.  
Medicine\*  
	Treating wounds and ailments.  
Ride  
	Maneuvering a mount, staying mounted.  
Stealth  
	Moving without being noticed, blending in.  
Study\*  
	Research topics, examine behaviours and weaknesses.  
Survival\*  
	Overcome wilderness dangers, navigate.  
Traverse  
	Covers climbing, swimming, passing through hazardous terrain  
Trickery\*  
	Sleight of hand, pickpocketing, lockpicking.  
Weapons (Melee) \[Martial\]  
	Fighting with melee weapons (but not unarmed)  
Weapons (Ranged) \[Martial\]  
	Fighting with ranged and thrown weapons.  
Weaving\*  
	Casting spells

# 

# Adept Abilities

Adept abilities can only be used once you have at least 1 Rank in them. They are sorted with general Abilities coming first, and then those that interact with other abilities in alphabetical order.

# Tier 1 Abilities

### **Maneuvers \[Enhance\] \[Body\]**

Tier 1\.   
Free action. 1 Health.  
Trigger: You hit with a Melee Strike and score 1+ additional success.  
Effect: The additional successes are spent on this Ability instead. Choose one of the effects below corresponding to the number of successes spent:

| Successes | Effect |
| :---: | :---: |
| 1 | Disarm: Make a DEX+Rank Test against their Physical Defense. Success disarms them of a 1h item, 2+ successes of a 2h item. |
| 1 | Shield Shatter: Make a separate damage roll against the target’s shield, adding this Rank. Success destroys it. |
| 1 | Observe: You learn one special maneuver that can be taken against the target |
| 2 | Trip: The target must make a Knockdown Test even if they did not suffer a Wound. Increase the TN of the Test by Rank. |

### **Quick Channel, Improved \[Esoteric\] \[Blood\]**

Tier 1\.   
Free action. 1 Health.  
Trigger: You use Quick Channel.  
Effect: The minimum amount of Weave you regain is Rank (up to 4). 

### **Strike First \[Body\] \[Blood\]**

Tier 1\.   
Free action. 1 Health.  
Effect: Add this Rank to the first Melee Strike you make this round against an opponent with lower Initiative than you.

### **Parry \[Enhance\] \[Force\] \[Blood\] \[Evade\]**

Tier 1\.   
Free action (up to Rank times / round). 2 Health.  
Trigger: An attack hits you.  
Effect: Make a DEX+Rank Test against the triggering attack result. Success means the attack misses you instead, and if your initiative is higher than the target you may counterattack. This is a Melee Strike using this Rank in place of the normal Rank.  
Evade: You can only use one Evade ability against a particular effect.

### **Weave Watcher \[Perceive\] \[Esoteric\]**

Tier 1\.  
Major Action. 1 Health.  
Effect: Make an INT+Rank Test. For Rank rounds, you can see the Weave as if it was material. The fainter or weaker a Weave is, the higher the required Test result is.  
While the Weave is visible to you, you may try to identify individual effects using Abilities like Weaving or Lore.

This Ability may be reversed, to make your Weaves harder to detect. Add this Rank to the TN to detect and identify them.

### **Acrobatic Defense \[Enhance\] \[Body\] \[Blood\]**

Tier 1\. Prerequisite: Acrobatics 1  
Minor Action. 1 Health.  
Effect: Make a DEX+Rank against the Physical Defense of all enemies engaged in Melee with you. You gain a \+2 bonus per success to Physical Defense against everyone you succeed against until the end of the round

### **Quickening \[Transmute\] \[Body\] \[Blood\]**

Tier 1\. Prerequisite: Acrobatics 1  
Free action. 1 Health.  
Effect: Add this Rank to your Initiative before making the Test.

### **Distract \[Create\] \[Illusion\]**

Tier 1\. Prerequisite: Artistry 1  
Minor Action. 1 Weave.  
Effect: Make a PRE+Rank Test against the Mental Defense of a creature you can see. Success means you can change the target’s facing (ignoring Reactions)

This Ability may be reversed, in which case you make a PRE+Rank Test against the Mental Defense of all creatures engaged in Melee with you. Success against all of them means you can change your facing without triggering Reactions.

### **Anticipate Enemy \[Perceive\] \[Illusion\] \[Blood\]**

Tier 1\. Prerequisite: Awareness 1  
Minor Action. 1 Health.  
Effect: Make an INT+Rank Test against the Magic Defense of an enemy with lower Initiative than you. Every success gives you a \+2 bonus to Physical Defense against them until the end of the round, and an equal bonus to your next attack against them this turn.  
You may repeat this effect (Rank \- 1\) times, paying the cost each time to target a different enemy.

### **Brawler’s Crush \[Transmute\] \[Body\]**

Tier 1\. Prerequisite: Brawl 1  
Effect: Your Brawling damage becomes (Rank \+ 1d6 \+ 2 \* STR).

### **Scare \[Control\] \[Mind\]**

Tier 1\. Prerequisite: Command 1\.  
Major or Minor Action (if you spend 2 Weave). 0-2 Weave.  
Effect: Choose a creature you can see, and make a PRE+Command Test against their Mental Defense. Success means they suffer a \-2 penalty to all Tests for Rank rounds.  
The target may Rally WIL (PRE+Rank) to end this effect.   
Additional Successes: Increase the penalty by \-2

### **Enamour \[Enhance\] \[Mind\]**

Tier 1\. Prerequisite: Charm 1  
1 Phase. 2 Weave.  
Effect: You spend time conversing with up to 10 individuals to improve their Relation towards you. Make a PRE+Charm Test against their Mental Defense. Success means your Relation improves by one step for Rank days. During this time, your Relation cannot improve above this level.

### **Beguile \[Control\] \[Mind\]**

Tier 1\. Prerequisite: Guile 1  
Major Action. 2 Weave.  
Effect: You attempt to make the mind of a target you can see more receptive to deception.  
Make a PRE+Rank Test against up to Rank targets Magic Defense. Success gives you a \+4 bonus to Guile Tests against them for 1 Phase. Failing by 5 or more means they become aware that you used this Ability against them.

### **Empath \[Perceive\] Mind\]**

Tier 1\. Prerequisite: Insight 1  
Major Action. 3 Weave.  
Effect: Make a WIL+Rank Test against the Mental Defense of a character within Medium range. For every success, you gain additional information about their emotional state, giving you a \+2 bonus to social tests against them within (10 \* Rank) minutes.

### **Bind Wound \[Create\] \[Body\]**

Tier 1\. Prerequisite: Medicine 1  
1 Phase. 3 Weave.  
Effect: You attempt to treat Wounds on yourself or a nearby ally. Make a DEX+Medicine Test and compare it to the table below. If you succeed to treat the Wounds, you cannot use this ability on them again until they have completed a rest.

| Wound severity | Result | Effect |
| :---: | :---: | :---: |
| Light Wounds | 8-Rank | The target ignores the Wound penalty until they have rested. |
|  | 12-Rank | The Wound is removed |
| Medium Wounds | 12-Rank | The target treats the Wound penalty as 1 step lower until they spend Health. |
|  | 15-Rank | If you Bind Wound on the target again after their next rest and get a 15+, their Wound Severity is reduced by 1 step. |
| Heavy Wounds | 15-Rank | The target treats the Wound penalty as 1 step lower until they spend Health. |
|  | 18-Rank | If you Bind Wound on the target again after their next rest and get a 18+, their Wound Severity is reduced by 1 step |

### **Adapt Language \[Perceive\] \[Mind\]**

Tier 1\.  
1 Phase. 3 Weave.  
Effect: You focus upon a spoken or written language you have access to and try to learn it. Make an INT+Rank (8) Test. Success means you know that Language until you rest. Failure means you cannot use this Ability on that language again until you have rested. You can have (Rank) adapted languages known at once.  
More obscure languages have higher target numbers.

### **Mounted Leaping \[Enhance\] \[Body\] \[Blood\]**

Tier 1  
Minor Action. 1 Health.  
Effect: You can effortlessly leap to mount from up to (Rank) meters away from your mount. While mounted, you can similarly make a dismounting leap up to (Rank) meters away.  
Special: When using Acrobatics to jump to or from your mount, you may pay this ability’s cost to add this Rank to the Test.

### **Defensive Riding \[Enhance\] \[Body\] \[Blood\] \[Evade\]**

Tier 1  
Free action (up to Rank times / round). 1 Health.  
Trigger: An attack would hit your or your mount’s Physical or Magic Defense  
Effect: Make a DEX+Rank Test against the triggering attack total. Success means the attack misses instead.  
Evade: You can only use one Evade ability against a particular effect.

### **Shadow Stalker \[Control\] \[Illusion\]**

Tier 1\. Prerequisite: Stealth 1\.  
Effect: Add this Rank to any Stealth Tests while you are in shadow. In deep shadows, you may turn virtually invisible to normal sight.

### **Study Flaws \[Perceive\] \[Blood\]**

Tier 1\. Prerequisite: Study 1  
Major Action. 1 Health.  
1 creature you can see.  
Effect: Make an INT+Study test against the target's Magic Defense. Success means the target suffers a (Rank) penalty to a defense of your choice until the end of the next round, increasing the penalty by 1 per success.

### **Trail Unseen \[Perceive\] \[Earth\] \[Blood\]**

Tier 1\. Prerequisite: Survival 1\.  
Major Action. 3 Health.  
Effect: You may follow a visible track beyond their normal limits. Make a WIL+Rank Test to follow the tracks, the TN increasing depending on how long ago they were made.  
Success means a faintly glowing trail appears to you where the tracks would normally have faded, being visible for Rank hours.

This Ability may be reversed, to instead conceal the tracks of yourself and up to (2 \* Rank) individuals. Make a WIL+Rank Test for every Rank hours spent, the result determining the difficulty and speed of following the tracks (if they are not outright eliminated).

### **Wall Walker \[Transmute\] \[Body\] \[Blood\]**

Tier 1\. Prerequisite: Traverse 1\.  
Major Action. 3 Health.  
Effect: Make a DEX+Rank (6) Test. Success means that you can climb on walls with your hands free, and suffer no penalties to fight while climbing. You may also add this Rank to Knockdown Tests while climbing. This effect lasts for 1 Phase.  
Additional Successes: Increase duration by 1 Phase; gain a \+2 bonus to climb

This Ability may be reversed, in which case you add this Rank to all Knockdown Tests for 1 Phase, but you cannot jump while it is in effect.

### **Lockwhisper \[Control\] \[Force\]**

Tier 1\. Prerequisite: Trickery 1\.  
Major Action. 2 Weave.  
Effect: You attempt to open a lock within Close range. Make a DEX+Rank Test to open the lock. Success means the lock opens, and you may as a Minor action open it at any point within Rank hours. You may try up to Rank times, which resets every time your Rank increases.

This Ability may be reversed, to instead lock something unlocked by making the same Test above. 1 additional success means the lock takes twice the normal time to open, while 2 additional successes means the lock cannot be unlocked in its usual way. This effect lasts for Rank Phases.

### **Thieving Hand \[Control\] \[Force\]**

Tier 1\. Prerequisite: Trickery 1\.  
Major Action. 2 Weave.  
Effect: You attempt to covertly steal an object that is up to Rank meters away. Make a DEX+Trickery Test. If successful, add this Rank to the TN to detect the theft.

This Ability may be reversed, in which case you add this Rank to the TN to steal from you for Rank hours.

### **Traphandling \[Control\] \[Force\] \[Blood\]**

Tier 1\. Prerequisite: Trickery 1\.  
1 Phase / Major Action. 0 / 2 Health.  
Effect: Make a DEX+Thievery Test to disable or control a trap. You may try up to Rank times, which resets every time your Rank increases. Botching a Test against a trap usually sets it off.

### **Mystic Edge \[Transmute\] \[Esoteric\] \[Blood\]** 

Tier 1\. Prerequisite: Weapons (Melee) 1  
Major Action. 2 Health.  
Effect: Make a Melee Attack, using this Rank in place of the normal Rank. It targets Magic Defense.

### **Piercing Missile \[Enhance\]** 

Tier 1\. Prerequisite: Weapons (Ranged) 1  
Reaction. 1 Weave.  
Trigger: You Defeat an enemy with a Ranged Strike.  
Effect: Draw a line from you through the target. Deal half the triggering damage to another creature in the same line within Medium range of the target.

### **Magic Ward \[Ward\] \[Esoteric\] \[Blood\] \[Evade\]**

Tier 1\. Prerequisite: Weaving 1  
Reaction. 1 Health.  
Trigger: An effect succeeds against your Magic Defense  
Effect: Make a WIL+Rank Test against the triggering result. Success means the effect is treated as if it did not succeed against your defense.  
Evade: You can only use one Evade ability against a particular effect.

# Tier 2 Abilities

### **Silent Whisper \[Create\] \[Illusion\] \[Blood\]**

Tier 2\.  
Free Action. 1 Health.  
You attempt to speak directly to up to Rank targets within (Rank \* 10)m. 

### **Disguise \[Enhance\] \[Illusion\]**

Tier 2\. Prerequisite: Guile 3  
Major Action. 2 Weave.  
Effect: You take on an illusory disguise to change your appearance. You may look like any Kith with up to 1 Size difference. This changes your appearance, smell and touch, but does not give any physicality where there is none. For example, a human disguising as an elf would appear to have pointed ears but when touched would phase through the illusion.  
Make 

# Arts of Arcana

# Arts of Arcana

Arts of Arcana, or simply “Arts” are the way you utilise the magic and power coursing through your body. Some are innate talents, or otherworldly gifts. Others are expressed by the magical weaving of spells into new shapes. Regardless of your methods, all player characters have access to Arts of Arcana which grant them supernatural powers beyond their abilities.

Arts of Arcana are split into two parts. The actual Art, which gives you access to a variety of effects you can accomplish during exploration, and Powers that can be unlocked and used much faster. Arts are unlocked by spending Art points, while Powers are gained by either increasing your Echelon, or spending Experience. You may choose your Powers from any of your unlocked Arts.

The Exploration Effects listed for an Art are suggestions for things you can accomplish using that Art, and not a definitive list. However, creating spectacular Art effects may require additional costs as negotiated with the GM. This could be a roll using the art where there is a risk it goes wrong, an expenditure of Health, binding Weave for an extended period or any combination thereof.  
In general, Exploration Effects can only directly affect things you are aware of. This means you cannot target a creature hiding behind a wall, but you could create a gust of wind that blows in their direction.

When an Art refers to a special Range, it always uses the Art Rank to determine the distance.

| Art Rank | Art points to raise from previous rank | Art points cost from rank 0 |
| :---- | :---- | :---- |
| 1 | 5 | 5 |
| 2 | 10 | 15 |
| 3 | 15 | 30 |
| 4 | 20 | 50 |
| 5 | 25 | 75 |

# Arts of Thaumaturgy

*Affecting the natural forces of the world: air, earth, fire, nature, and water.*

## Art of Air

*The elemental forces of weather, wind, and air.*

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Create or stop breezes within Medium range.Control bursts of wind within Close range. Predict natural weather for Rank days. |
| 2 | Create a mist that stretches out to Medium range while you focus. Control gentle weather like rain within Medium range. Cause an unnatural wind to circle a creature within Far range while you focus. |
| 3 | Control all winds within Close range. Create a thunderclap or spark within Medium range. Carry your voice to a place within Far range. Create unnatural gentle weather, like rain indoors. |

Air Powers T1  
**Slipstream \[Power\] \[Create\] \[Air\]**  
Minor Action. 1 Weave.  
Effect: Increase your Speed by (WIL \+ Rank) until the end of your turn.

**Battering Winds \[Power\] \[Spell\] \[Create\] \[Air\]**  
Major Action. 1-2 Weave.  
Range 30/60, 1 enemy  
Attack: INT+Weaving vs Physical Defense  
Effect: If you succeed, slide the target (WIL \* 2\) meters in one direction. If you spent 2 Weave, the target takes 2d6+WIL Physical damage.  
Additional Successes: Increase damage by 2; increase forced movement by 4m  
Enhance Weave: Affect an additional enemy (2); Increase damage by 2 (1)

### **Whistling Missile \[Power\] \[Create\] \[Air\]**

Minor Action. 1 Weave.  
Effect: Make a WIL+Rank Test (6). Success means your next Ranged Attack this turn may make a number of 90° turns equal to your Air Rank. You must still be aware of the target of the attack

## Art of Earth

*The elemental forces of earth, metal and acid.*  
Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Slowly move earthen or metal material within Close range while you focus.Create a thin layer of dirt or sand over a surface for a short time.Detect structural instabilities within view.Cause a rock to glow brightly while you focus. |
| 2 | Transform one type of loose earth to another, like dirt to mud for a long time.Create a moderate acid within Melee range while you focus. Create a large pile of loose earth or a large rock within Close range for a moderate time. |
| 3 | Quickly move a small amount of earth-based material within Medium range. Sense vibrations in the earth, enough to detect the presence of creatures within Medium range. |

Earth Powers T1  
**Silversheen \[Power\] \[Spell\] \[Enhance\] \[Earth\] \[Imbue\]**  
Major Action. 3 Weave.  
Melee, 1 Melee Weapon.  
Effect: Make an INT+Weaving (8) Test. Success means the target Weapon gains a \+2 bonus to attack for 1 Phase.  
Additional Successes: Increase duration by 1 Phase  
Imbue: An item can only have one imbuement.

**Acid Touch \[Power\] \[Spell\] \[Create\] \[Earth\]**  
Major Action. 1 Weave.  
Melee, 1 enemy.  
Attack: INT+Weaving vs Physical Defense  
Effect: 2d6+WIL Physical damage, and until the end of the next round, the target takes a \-2 penalty to Physical Armor.  
The target may Rally STR (5+Rank) to end this effect.  
Additional Successes: Increase duration by 2 rounds; Increase penalty by 2; Bounce to another target.

**Rumblestrike \[Power\] \[Control\] \[Earth\]**  
Major Action. 2 Weave.  
Melee, 1 enemy on the ground.  
Effect: Make a Melee Strike. On a Success, the target must make a Knockdown Test against (5 \+ Rank) or fall Prone.  
You may spend additional successes on the Melee strike on these effects:  
Additional Successes: Increase knockdown TN by 2; push the target 4m; force another target in Melee range to also make the Knockdown test.

## Art of Fire

The elemental forces of fire, heat, and light. Supernatural fires that are not created by igniting existing materials do not spread. Botched uses of Fire usually result in an unintended target or intensity.  
Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Igniting several easily combustible materials within Close range, like dry wood.Cause an existing small fire like a torch to flash and spark within Close range. Create a simple light or fire within Melee range that does not harm you while you focus. |
| 2 | Create a medium fire that burns without fuel or smoke for a long time within Close range.Ignite combustible material like wood within Close range. Change the color of fire or light for a long time. |
| 3 | Create a harmless fire in Melee range while you focus. Create bright moveable light within Medium range while you focus. Extinguish medium fires within Medium range. Move a small fire as you desire within Close range. |

Fire Powers T1  
**Flamebreath \[Power\] \[Spell\] \[Create\] \[Fire\]**  
Major Action. 3 Weave.  
(5 \+ INT)m long 45° Cone  
Effect: Make an INT+Weaving Test against the Magic Defense of all targets.  
Success deals 1d6+WIL+Rank Magic damage.  
Additional Successes: Increase damage by 2\.  
Enhance Weave: Increase the cone length by 2m (2); Increase cone angle by 45° (2)

**Ignite Missile \[Power\] \[Create\] \[Fire\]**  
Free Action. 1 Weave.  
Trigger: You make a Ranged Strike  
Effect: Increase the damage of the Strike by 1 \+ Rank. The attack ignites non-creatures it hits.

**Lanternlight  \[Power\] \[Spell\] \[Create\] \[Fire\]**  
Minor/Major Action. 1 / 2 Weave.  
Medium Range  
Effect: As Minor Action, you create a bright light at the target location. Make an INT+Weaving (8) Test to succeed.   
Additional Successes: increase light distance; you can move it as a Minor action.  
---

As a Major Action, place a (2 \+ WIL)m burst within range and make an INT+Weaving Test against all targets Magic Defense.  
Success means they are Blinded for 1 round.  
They may Rally WIL (5 \+ Rank) to end the effect.  
Additional successes: Increase the duration by 2 rounds; increase the Rally TN by 2\.  
Enhance Weave: Increase the burst size by 1m (2)

**Growing Combustion \[Power\] \[Spell\] \[Create\] \[Fire\]**  
Major Action. 2 Weave.  
30/60m, 1 enemy  
Attack: INT+Weaving vs Magic Defense  
Effect: The target starts burning, taking 1d6+WIL Magic damage. They continue burning as long as you keep Focusing on the effect.  
They may as a Minor action Rally WIL (5 \+ Rank) to end the effect early.  
Additional Successes: Increase the damage by 2; increase the Rally TN by 2; bounce to another target within 2m.

Focus (Major): The target burns until the end of your next turn. Make a new INT+Weaving Test against their Magic Defense. Each success increases the future damage rolls of this combustion by 1d6. Then the target takes 1d6+WIL Magic damage.  
Enhance Weave: Reduce the Focus cost to a Minor Action this round (1).

## Art of Nature

Plantlife and natural beasts. Beasts refer to all types of non-intelligent natural creatures. Nature can affect both dead and living plants. Nature botches can result in the target turning against you, or an unwanted transformation.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Create or destroy small harmless plants within Melee range. Slowly move a small plant within Close range while you focus. Detect if inanimate plants you can see are dangerous. |
| 2 | Learn the types of beasts and plants within Far range. Significantly weaken a moderate inanimate plant. Learn the motivations of a beast within Medium range. Empathically communicate with a beast in Close range. |
| 3 | Make one of your senses unhindered by plantlife. Quickly move a group of small plants within Medium range. Create simple plants or plant products like grass or fruits while you focus. Detect the presence and emotions of beasts or plants. Control a plant or beast’s toxicity while you focus. |

Nature Powers T1  
**Entangle \[Power\] \[Spell\] \[Create\] \[Nature\]**  
Major Action. 3 Weave.  
(1 \+ WIL)m burst Zone within (10 \* Rank)m, all creatures   
Effect: Make an INT+Weaving Test against the Physical Defense of all targets. Success means they are entangled. Entangled creatures have their Speed reduced to 0 until they escape.   
An entangled creature may attempt to escape as a Minor/Major Action by making a STR+Acrobatics (7 \+ Rank) Test, with a \+4 bonus if they used a Major Action.  
The Zone lasts for 2 rounds, and any creature that enters it is subject to the same effect as above (using the original Test result)  
Additional Successes: Increase escape TN by 2;  
Enhance Weave: Increase burst size by 1m (1); increase range by 10m (1); only Major actions can escape (3)

**Nature’s Sting \[Power\] \[Create\] \[Nature\]**  
Major Action. 2 Weave.  
Effect: You create a Nature’s Sting Toxin. It can be applied to any Weapon or projectile. A creature hit by an affected weapon is also hit by the Toxin if the attack deals damage (the toxin is then removed from the Weapon)  
When the toxin affects a creature, make a WIL+Rank Test opposed by the targets STA Test. Success means they are poisoned, losing 1d6 Health every round for Rank rounds.

**Woodward \[Power\] \[Ward\] \[Nature\]**  
Major Action. 3 Weave.  
Effect: Make a WIL+Rank (6) Test. Success means you gain 5 temporary Health and 1 Physical Armor for 10 rounds.  
Additional Successes: Increase the temporary Health by 2; increase the Physical Armor by 1; increase the duration by 10 rounds (1 minute).  
Enhance Weave: Increase the duration by 1 Phase (2); apply the effect to an ally within Melee range instead (1)

**Nature Strikes \[Power\] \[Enhance\] \[Nature\]**  
Major Action. 1 Weave.  
Effect: Make a Melee or Ranged Strike.  On a Success, you may push or pull the target (1+STR)m.   
You may spend additional successes on the Melee strike on these effects:  
Additional Successes: Increase the forced movement by 4m; make a Strike against another target within 2m

**Pummel \[Power\] \[Enhance\] \[Nature\]**  
Minor Action. 1 Weave.  
Close, 1 enemy.  
Effect: Make a WIL+Rank Test against the target’s Physical Defense. Success deals 1d6+WIL+Rank Physical damage, and you may slide them 2m in any one direction.  
Additional Successes: Increase the forced movement by 4m.

**Sprout Shield \[Power\] \[Enhance\] \[Nature\]**  
Major Action. 3 Weave.  
Effect: You either enhance an existing shield within Close range, or create a new shield.  
Make a WIL+Rank (6) Test. An existing shield is enhanced with \+2 Physical and Magic Defense. A new sprout Shield weighs 4, has 4/2 defenses. The effect lasts for Rank minutes.  
Additional Successes: Increase the duration by Rank minutes.  
Enhance Weave: Additional target (2); increase bonuses by 1 (2); increase duration by 1 Phase (3).

## Art of Water

The elemental forces of water and cold. Water refers to all three states: fluid, solid, and steam. Water botches usually result in the wrong target, losing control, or creating too much liquid.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Create or destroy a small amount of water within Melee range. Cosmetically change liquid within close range, like changing its colour or taste. Uncomfortably chill a small object. |
| 2 | Create enough water to fill a barrel. Control a moderate amount of water while you focus. Change the state of a moderate amount of water within Close range. |
| 3 | Detect contamination of liquid in Melee range. Move a small amount of water within Medium range, and change its state. Change water to be slightly unnatural, like cold steam or warm ice. Create a harmless natural liquid while you focus, like juice or olive oil. |

Water Powers T1  
**Waters of Life \[Power\] \[Spell\] \[Create\] \[Water\]**  
Major Action. 3 Weave.  
(1+WIL) radius burst within 30m, all creatures.  
Effect: Make an INT+Weaving (6) Test. Success means the targets may spend a Recovery with a \+4 bonus.  
Additional Successes: Increase bonus by 2; exclude a target from the burst; change the size of the burst by 1m  
Enhance Weave: Increase radius of burst by 1m (1); Increase bonus by 2 (2)

**Chill Touch \[Power\] \[Spell\] \[Create\] \[Water\]**  
Major Action. 1 Weave  
Melee, 1 enemy  
Attack: INT+Weaving vs Physical Defense  
Effect: 1d6+WIL Magic damage, and the target is Staggered for 1 round. If they were already Staggered, they take (2 \* Rank) additional damage.  
The target may Rally STR (5+Rank) to end this effect.  
Additional Successes: Increase duration by 2 rounds; increase damage by 1d6;

### **Whip of Meredor \[Power\] \[Create\] \[Water\]**

Major Action. 3 Weave  
Effect: Make a WIL+Rank (6) Test. Success creates the following Weapon you can use for 1 Phase. When attacking with it, you use WIL+Rank.  
Additional Successes: Increase duration by 1 Phase; increase range by 2m.

Whip of Meredor \[Weapon\]  
(2 \+ INT) \* 2m range. 4+1d6+1d6/WIL Physical Damage. a Target that takes damage is pushed (WIL+Rank)m.

Enhance Weave: Increase range before multiplication by 2 (2); increase damage by 2 (1); increase push distance by 2m (2)

### **Ice Slick \[Power\] \[Spell\] \[Create\] \[Water\]**

Major Action. 3 Weave  
(2+WIL)m radius burst within (20 \+ 2 \* INT)m, all creatures  
Attack: INT+Weaving vs Physical Defense  
Effect: Any target you succeed against must make a Knockdown (5 \+ Rank) Test.  
The burst becomes a Zone for 1 round. Anyone that is forcefully moved onto the Zone, or moves onto it with more than half their Speed must make the above Knockdown Test.  
Additional Successes: Increase the Knockdown TN by 2  
Enhance Weave: Increase the burst radius by 1m (1); increase the duration by 2 rounds (2); increase the Knockdown TN by 2 (2)

### **Parching Wave \[Power\] \[Spell\] \[Create\] \[Water\]**

Major Action. 3 Weave.  
(5 \+ INT)m long 45° Cone  
Effect: Make an INT+Weaving Test against the Magic Defense of all targets.  
Success deals WIL+Rank Magic damage, and gives them a \-2 penalty to Tests and Physical Defense for 1 round.  
Additional Successes: Increase damage by 1d6 against that target; increase the penalties by 2\.  
Enhance Weave: Increase the cone length by 2m (2); Increase cone angle by 45° (1); increase the penalties by 2 (2)

### **Glide \[Power\] \[Create\] \[Water\]**

Minor Action. 1 Weave  
Effect: You shift Rank meters. 

# Arts of Manipulation

## Art of Mind

Subtly influence the minds of others. Botches to use Mind may affect yourself, believe your effect worked when it did not, or make them aware of your attempts.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Detect the most prevalent emotion of a creature within Close range. Conceal your own emotions while you focus. Speak telepathically to a creature within Close range. |
| 2 | Make someone within Close range recognise you as someone else while you focus. Redirect someone’s emotion towards another creature in Close range while you focus. |
| 3 | Make a minor change to a recent memory within Melee range. Implant a harmless urge within Close range, like turning around. Speak telepathically to a creature within Medium range, and allow them to respond. Strengthen an existing emotion within Medium range, like increasing an angry person's anger. |

Mind Powers T1

**Mind Spike \[Power\] \[Spell\] \[Control\] \[Mind\]**  
Major Action. 2 Weave  
10/20m, 1 enemy  
Attack: INT+Weaving vs Magic Defense  
Effect: 1d6+WIL Magic damage, and the target suffers a \-2 penalty to Physical Defense until the end of the next round.  
Additional Successes: Increase damage by 2; increase penalty by 2;  
Enhance Weave: Increase both ranges by 10m (1); increase penalty by 2 (2); additional target (2); increase duration by 2 rounds (2)

**Pester \[Power\] \[Control\] \[Mind\]**  
Minor Action. 2 Weave  
10m, 1 enemy  
Attack: PRE+Rank vs Mental Defense  
Effect: The target suffers a \-2 penalty to Tests and Speed until the end of the next round.  
Additional Successes: Increase Speed penalty by 2;  
Enhance Weave: Increase range by 10m (1); additional target (1); increase duration by 2 rounds (2)  

**Fluster \[Power\] \[Control\] \[Mind\]**  
Minor Action. 1 Weave  
10m, 1 enemy  
Attack: PRE+Rank vs Mental Defense  
Effect: The target cannot take a Reaction this round.  
Additional Successes: Increase the duration by 1 round; additional target.  
Enhance Weave: Increase range by 10m (1); additional target (1); increase duration by 1 round (1)  

## Art of Force

Move things at range, and create fields of invisible force. Botches to use Force often result in the target being dropped, moved in the wrong direction or with too much force.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Slowly move an object no larger or heavier than a sword within Close range. Throw a small object from somewhere within close range. Hold a willing target floating within Melee range while you focus. Create a personal field to keep out mild weather like rain or wind. |
| 2 | Slowly lift a willing target straight up or down, up to close range. Quickly move an inanimate object no larger or heavier than a sword. Utilise a skill at range, like picking a lock but with some difficulty. |
| 3 | Create a stationary forcefield within Melee range that can protect against mundane dangers like storms or falling rocks. Quickly throw objects no larger or heavier than two-handed weapons within Medium range. Block out all non-extreme weather. Hold a willing target floating within Close range. |

Force Powers T1  
**Impetus Strike \[Power\] \[Control\] \[Force\]**  
Major Action. 1 Weave.  
Melee, 1 enemy.  
Effect: Make a Strike. On a Success, you must push the target 2m.  
You may spend additional successes on the Melee strike on these effects:  
Additional Successes: Increase push distance by 4m; also push another target within Rank meters of the original  
Enhance Weave: a target pushed into an obstacle takes 1d6 additional Physical damage (1); increase push distance by 2m (1)

**Force Drift \[Power\] \[Control\] \[Force\]**  
Minor Action. 1 Weave.  
You glide Rank meters in a straight line, which need not support you. This ignores difficult terrain.

**Redirect Momentum \[Power\] \[Control\] \[Force\] \[Evade\]**  
Reaction. 1 Weave.  
Trigger: An attack is made against you  
Effect: Make a DEX+Rank Test against the triggering attack result.  
Success means the attack misses you, and you can redirect it towards a different creature within (Rank \* 2)m of you.  
Additional Successes: Increase the redirect range by Rank meters.  
Evade: You can only use one Evade ability against a particular effect.

**Repel \[Power\] \[Spell\] \[Create\] \[Force\]**  
Major action. 2 Weave.  
(4 \+ WIL)m radius burst from you, all creatures  
Effect: Make an INT+Weaving Test against the target’s Physical Defense.  
Success deals 1d6+WIL Magic damage, and pushes them up to Rank meters.  
Additional Successes: Increase push distance by 2m; increase damage by 2\.  
Enhance Weave: Increase the burst radius by 1m (1); increase push distance by Rank meters (2)

## Art of Illusion

Illusions fool the senses, although fooling several senses at once is more difficult. Botches may create the wrong image, give you away, or cause you to be the only one that experiences them.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | A small moving illusion attached to a creature affecting one sense A small stationary illusion affecting two senses, like a small crackling fire  |
| 2 | A simple moving illusion affecting one sense like a patrolling guard within close range. Loud unintelligible noise within Medium range. Intelligible speech within Medium range as long as you focus. Visually disguise a willing creature within range as long as you focus. |
| 3 | Cover part of a creature with a 2-sense illusion. Small simple moving illusion within Medium range. |

Force Powers T1  
**Chameleon Cloak \[Power\] \[Spell\] \[Destroy\] \[Illusion\]**  
Major Action. 3 Weave.  
Effect: Make an INT+Weave (6) Test.  
Success means your Stealth Rank counts as equal to your Illusion Rank for 10 rounds (1 minute) unless already higher. If your Stealth Rank is equal or higher than your Illusion Rank, you gain a \+2 bonus to Stealth Tests for the same duration.  
Additional Successes: increase the duration by 10 rounds (1 minute); increase bonus regardless of rank by 1\.  
Enhance Weave: Increase the duration by 1 Phase (2); apply the effect to an ally within Melee range instead (1)

**Phantom Pain \[Power\] \[Spell\] \[Create\] \[Illusion\]**  
Major Action. 2 Weave.  
Range 30/60, 1 enemy  
Attack: INT+Weaving vs Magic Defense  
Effect: The target takes 2d6+WIL Magic damage, and the target takes a \-2 penalty to Tests until the end of the next round.  
Additional Successes: Increase damage by 2; increase duration by 1 round.  
Enhance Weave: Affect an additional enemy (2); Increase damage by 2 (1); at the start of your next turn, the target takes half the damage again (2)

**Distorting Blur \[Power\] \[Create\] \[Illusion\]**  
Major Action. 3 Weave.  
Effect: Make a WIL+Rank (6) Test.  
Success gives you a \+2 bonus to all defenses against attacks for (5 \+ Rank) rounds.  
Additional Successes: increase the duration by 2 rounds; shift Rank meters (up to your Speed max)  
Enhance Weave: Increase the duration by 1 Phase (2); additional target in Melee range (1); increase bonuses by 1 (1)

**Hidden Strike \[Power\] \[Destroy\] \[Illusion\]**  
Major Action. 2 Weave.  
Effect: Make a Melee Strike, with a \+Rank bonus if the target cannot detect invisible things. You may spend additional successes from the strike on these effects:  
Additional Successes: shift 1m; 1d6+2 additional damage.

**Sidestep \[Power\] \[Control\] \[Illusion\]**  
Free Action. 1 Weave.  
Trigger: An enemy makes an Opportunity Attack against you  
Effect: You gain a \+4 bonus to your defenses against it.

# Arts of Calling

## Art of Convoking

Call forth creatures to do your bidding. When you first gain Convoking, choose a plane to associate the art with. Imp refers to the weak creatures you may summon, who do not mindlessly follow your commands. Botches to use Convoking usually result in your Imps turning on you, drawing unwanted attention, or calling forth something beyond your control.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Sense the presence of associated spirits or portals. Detect if a creature you can see is summoned. |
| 2 | Summon a simple imp within Close range while you focus, only capable of the simplest of actions. Summon a stationary sentry with poor senses for a long time. |
| 3 | Detect the Origin or plane of origin of a creature in sight. Sense the direction of the nearest associated portal while you focus. Speak to an associated creature in sight range, or creature you have summoned within medium range. Summon a simple imp for a short time, or two simple imps while you focus. |

Convoking Powers T1  
**Harassing Spirit \[Power\] \[Spell\] \[Create\] \[Convoking\]**  
Major Action. 3 Weave.  
Range 10/20, 1 enemy  
Attack: INT+Weaving vs Magic Defense  
Success means the target takes 2d6+Rank Magic damage, and the spirit lingers for Rank rounds.  
At the start of your turn, the spirit deals 1d6+Rank Magic damage again.  
The target may Rally WIL (5+Rank) to end the effect.   
An attack that succeeds against the spirit's defenses of (10+Rank / 6+Rank) also ends the effect.

Additional Successes: Increase damage by 2; increase duration by 2 rounds.  
Enhance Weave: Increase duration by 2 rounds (1); If the target is defeated or otherwise ends the effect, repeat the attack against a different target within range for the remaining duration (1)

**Conjure Defender \[Power\] \[Spell\] \[Create\] \[Convoking\]**  
Major Action. 3 Weave.  
Effect: Make an INT+Weaving (6) Test. Success increases your shield bonus to Physical and Magic defense by 2 for (2+Rank) rounds (even if you do not use a shield).  
When you would become unconscious due to damage, reduce that damage by (5 \+ Rank) and this effect ends.  
Additional Successes: increase duration by 2 rounds.  
Enhance Weave: Increase duration by 1 Phase (2); target another friendly creature in Melee range instead (1); increase the damage reduction by Rank (1)

**Watching Eye \[Power\] \[Create\] \[Convoking\]**  
Minor Action. 1 Weave.  
Effect: Make a WIL+Rank Test in place of an INT+Awareness test.   
Enhance Weave: you may continue to replace Awareness tests for Rank rounds (1); you know the direction of any invisible creatures in line of sight for Rank rounds (2)

## Art of Necromancy

The fundamental forces of death and unlife. Botches might free spirits, cause them to hinder you, or reveal faulty information.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Make simple movements with a dead body part within Close range. Make superficial changes to a corpse in Melee range, like changing its colour or healing scars.Learn how long a corpse has been dead. |
| 2 | Ask how a corpse died, which it need not answer truthfully. Sense if a corpse has been resurrected or reanimated. Animate a simple Medium Undead within Close range while you focus. |
| 3 | Make complex movements with a dead body part within Close range. Sense the presence of nearby undead spirits. |

Necromancy Powers T1

# Arts of Mutation

## Art of Alteration

Manipulate inanimate material, usually incapable of affecting magical material. Botches may result in an unwanted transformation, problematic fault in the creation, or receiving faulty information.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Sense the composition of an object you touch. Write upon hard material like stone. Flavour, heat, or chill a small amount of matter while you focus. Halve or double the weight of a small object while you focus. |
| 2 | Harden or weaken a small amount of material for a long time. Turn an object reflective, or a reflective object into a one-way mirror for a long time. Transform a small amount of matter to a similar form, like copper to tin or water to ale for a long time. |
| 3 | Transform a moderate amount of matter to a similar form. Destroy mundane equipment within Medium range. Repair simple construction like a door. |

Alteration Powers T1

### **Weaken Armor \[Power\] \[Spell\] \[Destroy\] \[Alteration\]**

Major Action. 1 Weave.  
(2 \+ WIL)m radius burst within 20m, all creatures  
Attack: INT+Weaving vs Magic Defense  
Effect: The target takes a \-2 penalty to Physical Armor and Speed per success for 1 round.  
They may Rally STR (5+Rank) at the end of their turn to end the effect.  
Enhance Weave: Increase penalties by 2 (2); increase duration by Rank rounds (1); increase radius by 2m (2)

### **Word of Protection \[Power\] \[Enhance\] \[Alteration\]**

Minor action. 1 Weave.  
Effect: Make a WIL+Rank (6) Test. Success grants you a \+2 bonus to Physical Armor for Rank rounds.  
Additional Successes: Increase the bonus by 1; increase the duration by Rank rounds.   
Enhance Weave: Increase the duration by 1 minute (2); affect another creature in Melee range (1)

## Art of Shapeshifting

Transform creatures in a temporary fashion. Limbs created through shapeshifting cannot wield weapons or shields. Botches result in an unintended target, an unwanted form, or the inability to perform an action for a time.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Make cosmetic changes to a willing creature, like changing their skin or hair colour for a long time. Shift your senses to any part of your body. Transform a limb to a tool, or change the length of a limb. |
| 2 | Lengthen a limb to Close range while you focus.  Moderately enhance your agility, might, or tenacity like being able to lift heavier things or move through webs with ease. |
| 3 | Enhance your senses unnaturally, like working in the dark or underwater while you focus. Grow an additional appendage incapable of fine manipulation. Change your appearance while you focus. |

Shapeshifting Powers T1

# Arts of Knowledge

## Art of Augury

Ask higher powers for guidance, induce visions and dreams. Often vague or duplicitous and should not be taken at face value. Dream effects are active the next time you sleep, and require at least 1 hour of sleep. Botches might result in your senses being overwhelmed, drawing unwanted attention, or becoming unconscious.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Detect if a creature in Melee range is mostly virtuous or sinful. Learn a common secret of someone in Close range, like a nickname. |
| 2 | When you dream, have a perfect recollection of the last day.Ask a simple question, receive an answer of weal, woe, or unknown. Have a vision of what happens if you perform an action in the immediate future. |
| 3 | Allow one sense to detect if a creature is mostly virtuous or sinful while you focus. Detect if a group of creatures wishes to harm you while you focus. View your own location from above or below. |

Augury Powers T1

## Art of Farsight

Sense things beyond your normal senses. When using senses at a distance, you need to see the targeted point. Botches may result in your senses being overwhelmed, drawing unwanted attention, or receiving faulty information.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Shift your vision to somewhere in Melee range while you focus. Sense the current time of day. Predict natural events in the near future, like weather or floods. |
| 2 | Shift one sense to somewhere in Close range. Enhance a sense so it works at a longer distance while you focus. Share the senses of a willing creature while it remains in Medium range. |
| 3 | Shift all senses to somewhere in Close range while you focus. Enhance a sense like seeing in the dark. |

Farsight Powers T1

## Art of Memory

Manipulate your own and others memories. When modifying other’s memories, they may detect egregious changes as false. Botches usually result in a faulty memory, targeting the wrong creature, or receiving faulty information.

Tier 1 Exploration Effects

| Rank | Sample effects |
| :---- | :---- |
| 1 | Perfectly memorise a small detail like a sentence for a day. Detect if you have heard of something before, and where. Share an image you remember with a willing creature in Melee range. |
| 2 | Add a short memory to a creature while you focus. Add or remove a short memory in your own mind. Detect if a creature in Melee range has heard a name before. |
| 3 | Share one of your memories with a willing creature in Melee range. Make a minor change to a recent memory in Close range. Perfectly memorise a large amount of information like a book, for many days. |

Memory Powers T1

# Equipment

# Equipment

Mundane equipment is not strictly defined, but are instead part of different categories. When picking a piece of equipment, choose what form it takes. Costs are listed in silver pennies.

# Armors

| Armor | Cost | Physical Armor | Magic Armor | Initiative penalty | Weight | Examples |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Agile | 20 | 2 | 0 | 0 | 2 | Quilted / fur |
| Light | 40 | 4 | 0 | 1 | 4 | Hide |
| Medium | 100 | 4 | 1 | 2 | 5 | Ringmail |
| Medium (Full) | 120 | 5 | 2 | 3 | 6 | Helmet |
| Heavy | 1000 | 6 | 2 | 3 | 5 | Chainmail |
| Heavy (Full) | 1200 | 7 | 3 | 4 | 7 | Helmet |

# Shields

| Shield | Cost | Physical Defense | Magic Defense | Initiative penalty | Weight | Examples |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Light\* | 5 | 1 | 0 | 0 | 1 | Buckler |
| Medium | 20 | 2 | 0 | 1 | 2 | Heater |
| Heavy | 50 | 3 | 1 | 2 | 3 | Infantry |

\* While wearing a Light shield you can still hold another item in the same hand, but cannot use it to attack.

# Weapons

Mundane Weapons are not strictly defined, but are instead part of different categories. When picking a Weapon, choose what form it takes.

| Weapon | Hands | Min STR | Damage | Weight | Cost | Examples |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Brawling | n/a |  | 1d6+STR | n/a | n/a |  |
| Light Melee | 1 | \-3 | 1d6+STR\* | 0 | 5 | Dagger, sap |
| 1h Melee | 1 | 0 | 4+1d6+STR | 1 | 20 | Sword, mace |
| Heavy Melee | 2 | 1 | 4+1d6+1d4/STR | 2 | 40 | Greatsword, flail |
| Reach Melee\*\* | 2 | 0 | 4+1d6+ 2\*STR | 3 | 60 | Poleaxe, halberd |
|  |  |  |  |  |  |  |
| Light Ranged (2-10 / 11-20) | 1 | \-3 | 1d6+STR | 1 | 5 | Sling, javelin |
| Short-ranged (2-20 / 21-40) | 2 | \-1 | 2+1d6+STR | 2 | 15 | Shortbow |
| Long-ranged (2-40 / 41-80) | 2 | 2 | 6+1d4/STR | 2 | 60 | Longbow |

\* Only adds STR if positive  
\*\* Increases your Melee range by 1 meter. Enemies that approach from your front provoke an Opportunity Attack.

# Adventuring gear

While there is no need to detail every single thing you carry on you, some general equipment is good to lay down as a foundation. Most mundane gear is presented as kits in these rules, while they can obviously be sold piecemeal in the world.

| Gear | Cost | Weight |
| :---- | :---: | :---: |
| Adventuring Kit (Backpack, bedroll, torches, firemaking kit, waterskin) | 10 | 4 |
| Lantern | 20 | 1 |
| Medicine Kit (Bandages, herbal treatments, poison testing kit) | 50 | 2 |
| Rope (6m) | 10 | 2 |
| Traversal Kit(Rope, pitons, hammer, grappling hook, breathing sponge) | 25 | 5 |
| Torch (treated) | 0,5 | 0 |
| Rations (1 week) | 5 | 1 |

# Consumables

Consumable items are used up when used, unless they have “Charges”. If they do, they can be used that many times before being depleted.

### **Health Tincture \[Create\] \[Body\] \[Consumable\]**

Tier 1\.  Cost 50\.  
Major action.  
Effect: The next time this Phase that you spend a Recovery, you gain a \+8 bonus. This does not apply if the effect that allows you to spend a Recovery gives you a bonus.

### **Antitoxin \[Destroy\] \[Nature\] \[Consumable\]**

Tier 1\.  Cost 50\.  
Major action.  
Effect: You make a new Rally Test against a Toxin in your system with a \+5 bonus.

### **Medici Respite \[Control\] \[Body\] \[Consumable\]**

Tier 1\.  Cost 100\.  
Major action.  
Effect: Diseases you are affected by do not progress for 1 day.

### **Medici Touch \[Create\] \[Body\] \[Consumable\]**

Tier 1\.  Cost 200\.  
Major action.  
Effect: You lose 1 Recovery to cure a Wound. If you have no Recoveries left, this has no effect.

### **Healing Theriac \[Create\] \[Body\] \[Consumable\]**

Tier 1\.  Cost 300\.  
Major action.  
Effect: Your Wounds improve by 1 step. Then spend a Recovery with a \+8 bonus. If you have no Recoveries left, roll 1d10+1 and regain that much Health.

### **Severed Limb Salve \[Create\] \[Body\] \[Consumable\]**

Tier 1\. Cost 600\.  
Major action.  
Effect: When applied to a severed limb returned to its source, it reattaches and heals normally. However the target suffers Heavy Wounds, or if they already had Heavy Wounds their Health is set to 0\.

### **Sano Consano \[Create\] \[Body\] \[Consumable\]**

Tier 1\. Cost 600\.  
Major action.  
Effect: You are cured of permanent blindness or deafness.

### 

# Keywords

# Keywords

1. Bounce: An effect that bounces repeats against a different target. No target can be hit more than once by an effect or its bounces. A bounced effect cannot bounce again.  
2. Fortune / Misfortune: With Fortune you roll a Test twice and use the better result. With Misfortune you roll a Test twice and use the worse result. Fortune and Misfortune cancel each other out. When you spend Mythos to reroll a Fortune/Misfortune roll, only roll 1 additional time.

# Character advancement

# Character Advancement

As you complete adventures and perform heroic deeds, your prowess grows. You are rewarded with Experience and Art points, which you can spend to improve yourself. Once you have acquired a certain amount of Abilities and Arts, you may rise to the next Echelon.

Echelons are like levels of power, each representing a milestone of progress. Weavers may sometimes refer to each other by their Echelon, as a way to measure power. Your total Echelon is a combination of all your Echelon Ranks. Before you unlock your first Echelon, you are counted as being at Echelon 0\.

Every 3 Echelons count as a Tier. This means that once you reach Echelon 4, you can access abilities, arts, and Powers of Tier 2\. Once you reach E7, you can access Tier 3, etc.

Once you fulfill all the requirements to increase your Echelon, choose one of the paths below. You need not choose a single path, but can progress in any order of your choosing. However, each Echelon path is tracked separately.

Echelon requirements

| Echelon | Ability requirements | Art requirements |
| :---- | :---- | :---- |
| 1 | Four abilities at Rank 3, at least one of which is Tier 1 | \- |
| 2 | Five abilities at Rank 4 | One Art at Rank 2 |
| 3 |  |  |

 

# Echelon paths

Benefits marked with an \+ only apply your attribute if its positive

## Path of Valor

For every Rank you must find a suitable trainer.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | (4+STA\+) Health 1 Mental defense 1 Weave 1 Power 1 Initiative You can spend 1 Mythos to get a bonus d6 on any roll that directly takes you into danger, or against fear. | You have performed a heroic deed |
| 2 | (4+STA\+) Health 1 Physical defense 1 Weave 1 Speed | You have befriended or gained the respect of a valorous kith |
| 3 | (4+STA\+) Health 1 Weave 1 Power 1 Initiative \<Path benefit, maybe t2 ability?\> | You have bravely faced terrible danger. You have recovered a relic worthy of a tale. |
| 4 | (4+STA\+) Health 1 Magic defense  1 Speed | You have slain a mighty beast, or defeated a shrewd and evil Kith. You constantly wear an icon displaying your bravery. |

## 

## Path of Knowledge

For every Rank you must find a suitable source of information.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | 2 Health 1 Magic defense 2 Weave 1 Power You can spend 1 Mythos to get a bonus d6 on any roll to research or remember. | You have discovered a secret. |
| 2 | 2 Health 1 Mental defense 1 Weave 1 Power | You have befriended or gained the respect of a knowledgeable kith |
| 3 | 2 Health 2 Weave 1 Power \<Path benefit, maybe t2 ability?\> | You have uncovered lost or new knowledge. You have fully researched an enchanted item. |
| 4 | 2 Health 1 Magic defense  2 Magic armor 1 Initiative | You have created something permanent using Essence. You proudly display an icon showcasing your knowledge. |

## Path of Potency

For every Rank you must find a suitable source of power.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | 2 Health 1 Mental defense WIL Weave 1 Power You can spend 1 Mythos to get a bonus d6 on any roll to threaten or against confusion | You have encountered a source of power. |
| 2 | 2 Health 1 Magic defense 2 Weave | You have befriended or gained the respect of a kith with great power. |
| 3 | 2 Health 2 Weave 1 Power \<Path benefit, maybe t2 ability?\> | You have seized a source of power for yourself. You have fully attuned to an enchanted item. |
| 4 | 2 Health 1 Mental defense  2 Magic armor 1 Initiative | You have wielded a great amount of essence. You do not hide your power. |

## Path of Harmony

For every Rank you must find a suitable source of nature.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | 3 Health 1 Mental defense 1 Weave 1 Power You can spend 1 Mythos to get a bonus d6 on any roll to understand nature, or performing artistry | You have aided in the growth of the natural world. |
| 2 | 3 Health 1 Magic defense 2 Weave 1 Power 1 Initiative | You have befriended or gained the respect of a kith in harmony with nature. |
| 3 | 3 Health 1 Physical defense 1 Weave 1 Power \<Path benefit, maybe t2 ability?\> | You have brought life to desolation. You have destroyed an influence corrupting nature. |
| 4 | 2 Health 1 Mental defense  1 Physical & Magic armor | You have used essence to enhance nature. You incorporate nature in your being. |

## Path of Subterfuge

For every Rank you must find a suitable target to outwit.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | (4+STA\+) Health 1 Physical defense 2 Weave 1 Power 1 Initiative You can spend 1 Mythos to get a bonus d6 on any roll to disguise, or against traps | You have overcome a foe through underhanded tactics. |
| 2 | 3 Health 1 Magic defense 1 Weave 1 Speed 1 Initiative | You have befriended or gained the respect of a kith  well versed in subterfuge. |
| 3 | (4+STA\+) Health 1 Weave 1 Power 1 Speed \<Path benefit, maybe t2 ability?\> | You have avoided great danger and found an alternate path. You have acquired something of great value. |
| 4 | (4+STA\+) Health 1 Physical defense  1 Speed | You have performed a significant sabotage or set a great trap You hide your true nature and power. |

## Path of Tales

For every Rank you must find a suitable audience and tell a tale.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | (4+STA\+) Health 1 Mental defense 1 Weave 2 Powers 1 Initiative You can spend 1 Mythos to get a bonus d6 on any roll to endear, perform, or against fear. | You have experienced and told a worthy tale. |
| 2 | 3 Health 1 Magic defense 1 Power 1 Speed | You have befriended or gained the respect of a great storyteller. |
| 3 | (4+STA\+) Health 1 Weave 1 Power 2 Mythos \<Path benefit, maybe t2 ability?\> | You have survived an encounter with a terrible foe. You have revived an ancient tale. |
| 4 | (4+STA\+) Health 1 Physical defense  1 Initiative | You have slain a mighty beast, or defeated a shrewd and evil Kith. You have used essence to make a tale true. |

## Path of Travel

For every Rank you must find a suitable trainer from a faraway place.

| Rank | Benefit | Requirements |
| :---- | :---- | :---- |
| 1 | (4+STA\+) Health 1 Physical defense 1 Weave 1 Powers 1 Speed You can spend 1 Mythos to get a bonus d6 on any roll to track, navigate, or forage. | You have found a new path, or journeyed a great distance. |
| 2 | 3 Health 1 Magic defense 1 Speed | You have befriended or gained the respect of a seasoned traveller. |
| 3 | (4+STA\+) Health 1 Weave 1 Power 1 Initiative \<Path benefit, maybe t2 ability?\> | You have successfully tracked a significant foe. You have found a long lost place. |
| 4 | (4+STA\+) Health 1 Physical defense  1 Speed 1 Initiative | You have hunted down a great thief, or returned a powerful relic to its owner. You wear trinkets gathered from your journey. |

# Changelog

0.0.2  
Abilities

+ Silent Whisper (T2)

Arts

* Enchantment \-\> Mind