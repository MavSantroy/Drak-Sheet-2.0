# Drak-Sheet-2.0

Drakudai Hero Sheet list of needs and wants

We can work on the style of the sheet, but the general theme I have is pretty close... though I would like it to be more like looking at a glass "clip-board" type of scifi theme.

--------------------------------------------

0. the grid sections should have a part (and currently does) that displays your current life cord and raw energy.

RE = Life Cord (Life Energy) @ 100 = 1 Raw Energy (RE). 200 Life Energy = 2 RE, etc.

@500 Life Energy bonus 1 RE

@1000 Life Energy bonus 2 RE

@2000 Life Energy bonus 3 RE

@3000 Life Energy bonus 4 RE

@4000 Life Energy bonus 5 RE

@5000 Life Energy bonus 6 RE

@6000 Life Energy bonus 7 RE

@7000 Life Energy bonus 8 RE

@8000 Life Energy bonus 9 RE

@9000 Life Energy bonus 10 RE

@10000 Life Energy bonus 2 Quirks +5 RE

1. Edit Psionics TAB

There should be 12 buttons on the top border of the Edit Psionics tab. These buttons should reveal, for the entire page

-- Buttons for Psionics --

Body Discipline
Causation
Clairvoyance
Deflection
Energy Communion
Molecular Alteration
Pyrokinesis
Subatomic Alteration
Telekinesis
Anti Psionics
Life Cord

2. Each psionic should have repeating fields under them. The buttons for the repeating fields should be accessible (revealed or usable) on the Character Tab (actions tab).

I'm not sure how this would work. Drop downs to select available abilities?  

We can talk about this on.

The repeating fields should have a button and a couple of fields that are considered for the roll:

All of the reaptting fields should have a damage/attack section of fields.  After that is basically just a bunch of descriptions that can be filled in and spit out when rolled (even if the damage section is blank for instance Telekinesis may have a damage section for a telekinetic blast.  But if not used as an attack for damage, but lifting an object may need to now how much weight can be listed or range, etc. 

So we need to be able to fill the name field & the description fields for anything outsdie of the attack fields.
	
	Psionic Level
	Rawn Energy being used
	Damge Dice field
	Damage Bonus	
	Damage Multiplier
	Difficulty Rating (DR = DC for D&D 5e)
	

--------------------------------------------------------
--------------------------------------------------------
--------------------------------------------------------

3. Inventory

Inventory is probably going to be the hardest.  This will also be the item creation tab.

a). There should be 5 buttons on this page (similar to psionics). 
	1). Weapons
	2). Armor
	3). Shields
	4). Artifacts
	5). Equipment

Weapons: Repeating fields

-------------------------------------
UNDERSTANDING ITEM CREATION

*** 
The following applies to all items. The only difference is that the items have different values for everything, and Drakudai is very arbitrary, there is no real senese of balance. Additionally, the items will have different names and the purpose of fields, but the calculations remain the same. 
***

To understand how this works, you'll probably need to understand how item creation works.

Everything has an overall tech level, gun, sword, ship, armor, etc.  Each of these items have specific properties.  Each property has bonus based on an arbitrary cost in tech levels.

For example, a pistol may have 2 properties (they have more, but for this example).

Damage 
Penetration +

How do we determine the Tech Level of the wepaon? We add up all the Tech Levels invested into the various properties.

Penetration + is a very strong property/ability, so let's say each +1 costs 16 Tech Levels.

Damage is not a big deal. It may cost 2 Tech Levels per dice increase.

At this rate, a Tech Level 64 weapon would have x amount of damage dice, and at most +3 Penetration Plus.

There are three fields for each property. 

	1). The result (the actual bonus or dice to be rolled). (this should be an 		auto calc BUT can be overridden by writing in the properties stats.)
	2). The cost per bonus in Tech Levels
	3). The bonus amount for each quantity of Tech Levels. And Tech Levels.

The item should also show the total amount of Tech Levels, which determines the overal Tech Level.

----------------------------------------

Weapon Fields
- Damage Dice (follows a dice progression chart. You'll see some of it in the sheet already... if not I have it)
- Damage bonus
- Damage Multiplier
- P+ (penetration_plus)
- RF (rapid fire, is a multiplier... but the multiplier varies and is based on dice... its another dice roll field... similar to 1D4*1D8... this would be the 1D8 section
- Range
- Ammunition / Charges (from this the Rapid Fire subtracts from)
- Bonus to Hit

-----------------------------------------

Armor Fields
- HP Dice (follows a dice progression chart. You'll see some of it in the sheet already... if not I have it)
- HP Bonus
- HP Multiplier
- P+ (penetration_plus) (base 1)
- Damage Reduction
- Weight (unsure how to calculate this, probably based on TL and HP. The higher the tech Level, the less the weight is per HP.  So maybe something like: Weight = ((HP/10) / TL) Guessing here.
- Defense Score
- Con Score (for armor only)

IF POWERED
- Str Bonus
- Dex Bonus
- Con (Armor only, not for user)
- Hard Points (mount points) (mods can be mounted later... probably will fill in the misc fields so as to make it easy)
- CDS (Computer_Defense_Score)
- Movement
- Size Reduction (starting at large)
I'm sure there is more, but that's good for now

-------------------------------------------

Shields
Repeating Fields

(this is something that would be mounted on a hardpoint or a vest, or whatever. Shields can only run for a few seconds (unless directly powered by a significant power source 10kw/h) So if they run off of a battery, then the battery has to be able to deliver at least 10kw of power (I'm not worrying about capacitors vs batteries).

Drop Down to select which type of shield.

	1. Static Shield (HP Based Shield, follows the Armor fields except the part 	below "IF POWERED"). additionally they have a seize of 10 feet diameter. 	There is now way to reduce it.

	2. Deflector. 

	3. Hard Shields, similar to static shields, but lowered HP for higher P+ and 	smaller field.


1. Static Shields. HP Based shield. Same fields as the Armor fields. It's size though should be 10 feet diameter. 10kw/h

2. Deflector. The fields are less than armor.  Ranged_Defense_Bonus (only ranged weapons are affected). Minimum Tech Level 80. Unit size starts at huge (unwearable). No other fields in this one. 20kw/h power

3. Hard Shields are the same as static shields but the shield size is 5' diameter. Minimum Tech Level is 64. 30kw/hr power

-------------------------------------------------

Artifacts
Repeatings fields
Artifacts can effect ANYTHING. Core Attribute, skills, abilities, life energy, ability levels, knowledge, even damage from weapons, range, etc.

Artifacts are much like magical talismans.

I'm not sure how to deal with this one.

--------------------------------------------------

Equipment
Repeating fields

These things effect knowledges, skills and core attribute (genetic engineering, cybernetics, computers, VI (skills & knowledges).

Fields:

Misc I'm guessing is probably the best way?

This should also have a notes section for each item


--------------------------------------------------

More on notes:

This should also be a good place to keep track of contacts known, locations, etc.

--------------------------------------------------
--------------------------------------------------
--------------------------------------------------

4. Progression.

Each skill falls under "how dificult is it to learn?". Each level costs ability points, and the amount of ability points progressively get more difficult until it hits a certain cost, and then resets.  So the easy progression tree would be 1, 2, 3, 4, 1.

There is an impossible progression tree, which just continues as 1 - 256.  

I have the code for how to do this on an older sheet. But I couldn't figure out how to make it work with this new one.  I've uploaded the old sheet, labeled OLD in the repository.

Additionally, I would like the option to be able to add a 2nd progression tree option. There are specific points where they can choose to have some feature, or they come accross an instructor who can teach that ability fast and with "less ability points". So some kind of checkbox that reveals all of the progression calculations? 

We can talk about this some more too.

Psionics should have a primary progression that grants a +1 to all success rolls and DR (Difficult Rating = Dice Checks) when it is upgraded per the standard progression when Ability Points are put in. It should have repeating fields under it that are treated like abilities with a full of arrays that are it's own roll. Each of these "sub"abilities should gain a +1 (to hits and DRs) from the master psionic going up in a level, but also the individual "sub"abilities from it's own progression.

Think of it this way: The psionic itself unlocks skills and abilities within it's genre, and there are two ways of improving the abilities: Increase the master psionic OR increase individual abilities under it... Or do both.


