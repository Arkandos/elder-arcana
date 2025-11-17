## Attributes
Every character has X number of attributes with scores from \-3 to \+3, starting out at 0\.
1. Strength (STR)
	1. Physical prowess, raw power. Strength improves the damage of your weapons, your carrying capacity, what equipment you can use, Rally against physical ailments, Knockdown tests and adds to your Physical Defense.  
2. Dexterity (DEX)  
	1. Agility, finesse and quickness. Dexterity improves the accuracy of your weapons, your Speed, Initiative tests, and adds to your Physical Defense.  
3. Stamina (STA)  
	1. Endurance, constitution. Stamina increases your Health, reduces the damage you take, and determines your daily Recoveries.  
4. Intelligence (INT)  
	1. Analysis, observation. Intelligence improves the potential of your magic, the range of certain abilities, increases your Weave, and adds to your Magic Defense. 
5.  Willpower (WIL)  
	1. Determination, control. Willpower improves the potency of your magic, increases your Mythos, Rallies you against mystical ailments and adds to your Magic Defense.  
6. Presence	(PRE)
	1. Charisma, communication. Presence influences others, and adds to your Mental Defense.

When assigning your starting Attributes, you have 10 points to spend. Costs increase to gain a higher attribute, but you may gain additional points by lowering an attribute. An attribute cannot be higher than \+3 nor lower than \-3 (except due to [[Rules/Characters/Kith/index|Kith]] modifiers)

| Attribute | Point cost    |
| :-------- | :------------ |
| \+3       | 6             |
| \+2       | 3             |
| \+1       | 1             |
| 0         | 0             |
| \-1       | Gain 1 point  |
| \-2       | Gain 3 points |
| \-3       | Gain 6 points |
## Statistics
Statistics are derived from your attributes and cannot be directly improved.  

| Statistic                    | Value                                                       | Description                                                                                                                |
| ---------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Health                       | 20 + <br>2 * STA                                            | How much damage you can suffer before going unconscious or dying.                                                          |
| Speed                        | 10 + DEX                                                    | How many meters you can move each [[Rules/Encounters/index\|round]].                                                       |
| Initiative                   | 3 + DEX                                                     | How fast your reactions are in stressful [[Rules/Encounters/index\|Encounters]]                                            |
| Physical Defense             | 6 +<br>STR+DEX                                              | How difficult you are to hit in physical combat                                                                            |
| Magic Defense                | 6 +<br>INT+WIL                                              | How difficult you are to hit in magical combat                                                                             |
| Mental Defense               | 6 + PRE                                                     | How difficult you are to manipulate emotionally                                                                            |
| Physical & <br>Magical Armor | STA +<br>[[Rules/Characters/Equipment/index#Armors\|Armor]] | Reduce the damage you take by this amount.                                                                                 |
| Weave pool                   | 3 + INT<br>(min 1)                                          | Used to pay for magical abilities. Refreshes every day. You can [[Channel]] to regain Weave faster, but this costs Health. |
| Mythos pool                  | 3 + WIL                                                     | Used to reroll Tests. Refreshes every day.                                                                                 |
| Recoveries                   | 1 + STA$^+$                                                 | Determines how many times per day you can heal damage.                                                                     |
| Recovery<br>value            | 1 +<br>2 + STA$^+$                                          | Determines how much each Recovery spent heals you.                                                                         |

## Abilities
There are many Abilities in Elder Arcana. Most tests involve adding one [[#Attributes|Attribute]] score, and one Ability Rank. However this relation between them is not set in stone unless called for by an ability. Certain situations may call upon you to use a different Attribute with the Ability.  
Abilities are divided into [[Rules/Characters/Abilities/Tier 0/index|Base Abilities]] (Tier 0), and Adept Abilities (Tier 1 and above). Anyone can use a Base Ability (even at Rank 0\) unless it has an \* next to its name, meaning that it can only be used if you have at least one Rank in that ability.  
Adept Abilities can only be used if you have at least one Rank in them.

# Encumbrance
If your total weight exceeds your carrying capacity, you are encumbered. 

| STR | Carrying capacity |     | Strength | Carrying capacity |
| --- | ----------------- | --- | -------- | ----------------- |
| 0   | 15                |     | 0        | 15                |
| +1  | 20                |     | -1       | 13                |
| +2  | 25                |     | -2       | 11                |
| +3  | 30                |     | -3       | 9                 |
| +4  | 40                |     | -4       | 7                 |
| +5  | 55                |     | -5       | 6                 |

|            Total Weight            |    Encumbrance     |                                        Effect                                         |
| :--------------------------------: | :----------------: | :-----------------------------------------------------------------------------------: |
|        Up to carry capacity        |    Unencumbered    |                                         None                                          |
| Between capacity and 150% capacity |     Encumbered     |              Speed halved, [[Conditions & Modifiers#Battered\|Battered]]              |
|      More than 150% capacity       | Heavily encumbered | Speed is 2 (or less), all defenses reduced to 2, can only take movement related Tests |
