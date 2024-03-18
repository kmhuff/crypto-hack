TODO: edit out capitalization convention

# Rules

## Tasks

### Task Resolution

When a PC attempts to do something risky where the consequence for failure is interesting, the GM calls for a task.Tasks have a base difficulty from 0-10. PCs may reduce the difficulty through various methods (described below). The PC then rolls a d20. If they get higher than the adjusted difficulty x3, they succeed, otherwise they fail.

Here is a summary of the meaning of base task difficulties:

**Difficulty** **Description**
-------------- ---------------
0              A task that anyone could succeed at (no roll required)
1-3            A task that requires a little training to succeed at
4-6            A task that only trained professionals could succeed at
7-10           A task that only legendary masters could succeed at

Task difficulty can be adjusted by the PCs in 3 different ways. Adjusting task difficulty down is called "easing" a task.

* Effort: PCs may spend points from their stat pools to reduce difficulty (explained in more detail below). Each character has an effort limit that determines the total effort they can give to a task. It starts at 1 and can go no higher than 6.
* Skill: Experience doing similar tasks can reduce difficulty (explained in more detail below). No character can ease a single task by more than 2 ranks because of skill.
* Circumstance: Beneficial circumstances can reduce difficulty (explained in more detail below). No character can ease a single task by more than 2 ranks because of circumstance.

An experienced PC willing to spend time setting up and burn a lot of resources can reduce even a legendary level 10 task to a trivial 0 level.

### Attempting Tasks

Many Tasks can be attempted by anyone. These are called open Tasks. Some of these tasks might be very difficult to those without the right skill, effort, or circumstances, but they can at least be attempted. The Task "fight with a sword" can be attempted by anyone, but only certain people are any good at it.

In contrast, some Tasks cannot be attempted by anyone without the necessary skill, bloodline, cyberware, etc. These are called closed Tasks. In this case, the Task may only be attempted by a character that has a Scope explicitly permitting them to do so (more on Scopes in the Character Statements and Skill section). The Task "hack the computer with my brain" may only be attempted by a character with a Scope that allows mental hacking.

Which Tasks are open and which are closed is determined by the logic of the fictional setting you are playing in. Usually, this is fairly obvious, but when it's not, the GM makes the final ruling.

### Trivial and Impossible Tasks

If a task's difficulty is ever dropped below 1, the task is considered trivial, and no roll is required. Any PC that attempts it automatically succeeds. Most everyday tasks are trivial.

If a task's difficulty is 7 or greater even after adjusting its difficulty by Effort, Skill and Circumstance, the task is considered impossible, and no roll is required. Any PC that attempts it automatically fails.

### Failing Tasks

When a PC fails a task, it is often obvious what the consequence should be. If a PC fails a task to jump across a gap, for instance, they will fall into the gap. However, not all tasks are so clear-cut.

Most tasks have a hidden failure condition: they waste time. If a PC fails to pick a lock, for instance, they waste the Short Turn they spent making the attempt (see [Time Tracking]). Sometimes, this doesn't have much effect on the PCs. Other times, such as when the PCs are standing around in a monster-infested ruin wasting light while they could be attacked at any time, wasting time can be very significant.

### Performing Tasks Carefully

Sometimes, a PC wants to perform a task where the only consequence of failure is wasted time, but they aren't under any time pressure. In this case, a PC might be able to choose to take longer on the task in exchange for automatic success. If they meet the conditions to perform the task carefully and they choose to do so, a PC can spend a turn of one size longer than the original task in order to succeed automatically on the task.

If the task's difficulty is 3 or lower after reducing it by Skill and Circumstance, a PC may perform the task carefully in 1 longer turn. If the adjusted difficulty is 4-6, performing the task carefully will take 3 longer turns. If the adjusted difficulty is 7 or greater, the task cannot be performed carefully at all.

Notice that we're only adjusting the difficulty by Skill and Circumstance here, not Effort. A PC may not spend Effort on a task when performing it carefully.

For example, a thief PC is picking the lock on a safe that the group brought with them back to their hideout. Normally picking a lock takes a Short Turn, but the group is safe, so the PC decides to pick it carefully. The lock is old and rusted but still solid, a difficulty 4 task. The PC has a scope that applies to lockpicking, so the difficulty is eased by 1 rank because of Skill. The adjusted difficulty is 3 or lower, so the PC can automatically succeed in picking the lock if they take one Medium Turn instead of a Short Turn in the attempt.

## Attributes and Effort

Each PC has 4 attributes:

* Might: Strength and physical toughness
* Agility: Speed, coordination, and reflexes
* Insight: Perceptiveness and memory
* Willpower: Determination and force of personality

Each task is associated with a particular attribute. For example:

* Moving a boulder is a Might task
* Dodging an arrow is an Agility task
* Noticing a hidden foe is an Insight task
* Intimidating an enemy is a Willpower task

Each stat has two components: a Pool and an Edge.

* The Pool represents a character's raw potential in that stat
* The Edge represents a character's training or experience in using that stat.

For example, an experienced adventurer who never got much book learning and is partially deaf in one ear might have a low Insight Pool but a high Insight Edge.

PCs can apply effort to tasks by spending points from the Pool of the associated stat. The process works like this:

#. Spend 3 points from the Pool to apply the first level of effort
#. Add additional levels of effort by spending 2 Pool points each. You can only do this up to the PC's maximum effort value. A starting character has a maximum effort of 1, so can never perform this step.
#. Subtract the relevant Edge from the points you spend. So a PC with an Edge of 1 in the relevant skill can apply one level of effort for 2 Pool points, or two levels of effort for 4 Pool points.

Effort can also be applied to increase damage during combat. This is described in more detail below.

A PC's Pools also serve as their hit points. This is described in more detail below.

## Character Statements and Skill

TODO: Refactor to Scope-only approach

In addition to Attributes, characters are defined by a phrase known as a Statement. A few examples of Statements are:

* A Mad Alchemist who Deals with Organized Crime. This is a starting character.
* An Incredibly Gallant Knight-Captain who is Determined in the Face of Danger and Flies into Murderous Rages. This is a high-level character.

Each Statement is made of individual parts. These parts come in 3 varieties.

* Type: This can be considered the "core" or "class" of a character. It indicates a character's profession or focus. In the above examples, "Alchemist" and "Knight-Captain" were Types.
* Descriptor: This part of the Statement adds color and depth, often about a character's personality or mannerisms. In the above examples, "Mad" and "Incredibly Gallant" were Descriptors.
* Focus: This often represents a secondary area of focus for the character or the methods they use to do their primary focus. In the above examples, "Deals with Organized Crime", "Is Determined in the Face of Danger", and "Flies into Murderous Rages" were Foci.

### Scopes

Each Statement part comes with a Scope, a set of one or more actions that the Statement part allows the character to do or gives them bonuses to perform. Types typically have a Scope of 3 actions. Descriptors and Foci typically have Scopes of 1 action each. Here is an example of the Alchemist character's scopes:

* Descriptor "Mad"
  + Execute unconventional plans
* Type "Alchemist"
  + Create concoctions to disorient, confuse, or poison foes
  + Create concoctions to accelerate healing, cure diseases, or remove status effects
  + Create concoctions to alter behavior, such as inflaming anger or loosening tongues
* Focus "Deals with Organized Crime"
  + Find and make deals with shady criminal characters

Some Scopes can allow the character to attempt closed Tasks (see Attempting Tasks). For example, other characters in the Alchemist's party wouldn't even know where to start creating a poison (a closed Task), but anyone could try to execute an unconventional plan (an open Task).

When picking Scopes (more on this in the Character Creation section), Scopes that allow the character to perform closed Tasks should be narrower and more specific than others, for balance reasons. Don't create a Scope that lets the Wizard pull a trick out of their robes for literally every situation.

As a corollary to this, consider narrower and more focused Types, such as Gloom Mage or Pyrokinetic instead of Wizard or Sorcerer.

### Statement Advancement

As a character gains power, their Statement grows longer or more complex. A character can choose to "boost" Statement parts they already possess or add new Statement parts that make sense for their story.

* "Incredibly Gallant" is an example of a boosted Descriptor.
* "Flies into Murderous Rages" is an example of an additional Focus added to the original Statement.

In addition to an improved skill bonus (see below), a boosted Statement part gains an additional Scope, or changed wording on one of its existing Scopes to allow it to apply to more situations.

For example, before the Knight-Captain chose to boost her "Gallant" Descriptor to "Incredibly Gallant", it had one scope: "Inspire courage in others". When she boosted the descriptor, she chose to add an additional Scope: "Banish magical fear or mental domination".

### Skill Bonuses

A character's Statement and Scopes determine what Tasks they gain Skill bonuses on. If either a Statement part or one of its Scopes applies to the Task, then it can benefit from that Statement's skill bonus.

Remember that characters may only attempt closed Tasks (see Attempting Tasks) if they have a Scope that allows them to do so. Having an appropriate Statement part doesn't get around this limitation. For example, none of the Alchemist's Scopes allow creating a strength potion (a closed Task), so the Alchemist can't do that, even though it seems like an Alchemist-y thing to do.

A Statement part that seems likely to help in the current situation eases the task by one rank. If the Statement part is boosted, it eases the task by 2 ranks. Only the best Statement part can apply to a single Task. For example:

* The Alchemist and his party are on the trail of a murderer. They need to track him down or figure out where he will strike next. Either the Alchemist's "Mad" Descriptor, or his "Deals with Organized Crime" Focus might seem relevant here, but he can only take a bonus of one of them to the Task, easing it by 1 rank.
* The Knight-Captain is trying to get the description of the band of monsters that attacked the town out of a panicking and near-catatonic civilian. She uses her "Incredibly Gallant" Descriptor to project an aura of safety to calm the civilian. Because this is a boosted Sentence part, the Task is eased by 2 ranks.

Skill bonuses cannot exceed 2 ranks.

## Circumstance

Beneficial circumstances can ease the difficulty of a check by up to 2 levels. Two different beneficial circumstances can stack or a single overwhelmingly beneficial circumstance can ease the check by 2 levels.

Some examples of circumstances easing a check follow:

* Being helped by an ally that knows what they're doing.
* Attacking an enemy that is hindered by distraction, a temporary status, etc.
* Referring to a rough map to find your way through a dangerous location.
* Offering a glass of a dignitary's favorite tea before engaging in a negotiation.

Some examples of overwhelming circumstances are:

* Attacking an enemy that is completely unaware of you.
* Using a detailed, up-to-date map with landmarks to find your way through a dangerous location.
* Using a character reference that your interlocutor trusts to convince them that you will keep your word.

Circumstances can also be detrimental to a Task. 2 detrimental circumstances may stack, or one circumstance can be overwhelmingly detrimental, exactly like beneficial circumstances. Detrimental circumstances are also limited to 2 ranks.

Merely having the tools needed to perform a Task does not count as a beneficial circumstance for the Task. In fact, lacking the tools necessary to perform a task would likely count as a detrimental circumstance.

## Time Tracking

**Immediate Turns**: Last 6 seconds. Combat is tracked in Immediate Turns.

**Short Turns**: Last 10 minutes. Site Exploration and Negotiation are tracked in Short Turns.

**Medium Turns**: Last 1 hour. Settlement Exploration and Mystery Solving are tracked in Medium Turns.

**Long Turns**: Last 8 hours. Wilderness Exploration is tracked in Long Turns. Usually, two Long Turns are used for activity during the day and one is used for sleep.

**Downtime Turns**: Last 1 week. Downtime is tracked in Downtime Turns.

Time is tracked at a certain scale depending on what the party is doing at the time. If the party is fighting, time is tracked in Immediate Turns. If they are exploring a location, it is tracked in Short Turns. 

During each turn, each PC may take a single action appropriate to the activity the party is performing at the moment. For example, if the party is exploring the wilderness, each PC may take a single Wilderness Exploration action every turn. These actions include things like "Navigate the Wilderness", "Forage", and "Explore a Point of Interest'.

In addition to a single action at the current time scale, PCs may take any number of actions at a shorter time scale during a turn. For instance, the party Navigating the Wilderness (Long Turn) might engage in a Fight and rest to patch their wounds up afterwards (2 Short Turn actions). All that activity still takes one Long Turn.

If the party is partway through an action and an event forces them to take another of the same length, both the partially completed action and the forced action occur during the same turn. For instance, a party exploring a dungon might be Moving Carefully (Short Turn) for 1 room (of a maximum of 2) before they run into some monsters and start a Fight (Short Turn). Both the movement and the combat happen during the same Short Turn. However, if that party instead moved 2 rooms (the maximum for Moving Carefully) before running into the Fight, the movement would happen during one Short Turn and the combat would happen during the next.

An action never takes less than a turn, even if the sub-activities that make it up might imply that it did. For example, a party Exploring a Point of Interest descends into a dungeon and only spends 1 hour there (6 short turns). The "Explore a Point of Interest" action still takes the full 8-hour Long Turn.

On the other hand, if the sub-activities imply that the action took *more* time than its entire turn, the party must take the action again. If a party manages to explore a dungeon for more than 8 hours or fight for more than 10 minutes (both impressive feats), the action "spills over" into the next turn and the party members all automatically take it again.

## Damage

Damage dealt to a PC is applied to one of that PC's Pools, depending on the source.

* A slashing or stabbing attack targets the Might Pool.
* A bashing or bruising attack targets the Agility Pool.
* Mental attacks or assaults on the senses (pepper spray, flashbangs) target the Insight Pool.
* Intimidation or fear effects, magical or mundane, target the Willpower Pool.

These aren't the only types of damage a PC might face, but they should give you a good idea of what the various Pools are for.

When a Pool becomes entirely depleted, the PC loses the ability to attempt Tasks above level 0 from that Stat. A Might-depleted PC can barely drag themselves across the room, let alone lift something heavy, for instance. When all of a PC's pools are completely depleted, they die.

When a Pool is depleted, any damage that the PC takes to that pool overflows into the next-most logical Pool. Usually this means that physical attacks flow into the other physical pool and mental attacks flow into the other mental pool. This overflowing continues if there is more than one depleted pool. For example, a character with a depleted Might pool that takes a slashing attack (normally Might damage), would instead take the damage to Agility. If that character's Agility pool was also depleted, they would take the damage to Insight instead.

## Healing

Points in a pool can be restored back to their normal maximum trough rest. Each time you rest, recover a number of points equal to a d6 + your total stat Edges. These points can be divided among your Pools however you wish.

The first rest you take each day takes one Immediate Turn. The next rest takes one Short Turn. The third rest of the day takes one Long Turn. This final rest is assumed to be your sleep for the day.

A full day of rest restores 3d6 + 3 * your total stat Edges.

### Medicine and Magic Healing

If a character has already rested twice, a healer may attempt to grant them additional rests as an Insight Task that takes a Short Turn. The first additional rest is a difficulty 3 task, the second difficulty 5, the third difficulty 7, and the fourth difficulty 9. No more than 4 additional rests may be granted this way.

## Combat

Combat is played in a series of rounds, each of which lasts 1 Immediate Turn. At the start of combat, one PC may make an Agility task against the most agile opponent. If the PC succeeds, the PC party goes first. If the PC fails, the opponents go first. The PCs and their opponents may decide what order to act in within their side's turn.

Characters may draw weapons for free at the start of combat, but afterwards must take an Interact action to change weapons.

On a creature's turn, the creature can move an Immediate distance and take one action. While the action can be anything that it would take roughly 6 seconds to do, the most common options are outlined below.

## Distance in Combat

TODO: Remove Roughly

**Immediate Distance**: Roughly 10 ft. If you're this close to a creature, they can close the distance and hit you with a melee attack nearly instantly.
**Short Distance**: Roughly 50 ft. The distance that a creature can charge in an Immediate Turn.
**Medium Distance**: Roughly 150 ft. This is the maximum range that a creature with a ranged attack can attack without penalty.
**Long Distance**: Roughly 450 ft. Beyond this range, even ranged attacks cannot target creatures.

### Action: Clash

Combatants Clash when they engage in combat and attempt to injure one another.

A Clash has an attacker and a defender. Whether the PC is the attacker or the defender, the Clash is resolved as a Task against the enemy's difficulty. If the attacker wins the Clash, they deal their weapon's damage to the defender. If the defender wins, they take no damage, and they might deal their weapon's damage to the attacker depending on their weapon.

The attribute of the Task is determined by the table below:

**PC**                    **Attribute**
-----------------------   -------------
Attacker                  Determined by PC weapon
Defender, can retaliate   Determined by PC weapon
Defender, can't retaliate Determined by attack

A defender can retaliate if their weapon is the same range type as the attacker. Melee can retaliate against melee and ranged can retaliate against ranged.

An exception to this is melee weapons with reach, like polearms. Other melee weapons can't retaliate against reach weapons, but reach weapons can retaliate like normal. Reach weapons can retaliate against one another.

+--------------------+---------------------------------------------------+
|                    | **Defender**                                      |
+--------------------+--------------------+-----------------+------------+
| **Attacker**       | **Standard Melee** | **Reach Melee** | **Ranged** |
+--------------------+--------------------+-----------------+------------+
| **Standard Melee** | Y                  | Y               | N          |
+--------------------+--------------------+-----------------+------------+
| **Reach Melee**    | N                  | Y               | N          |
+--------------------+--------------------+-----------------+------------+
| **Ranged**         | N                  | N               | Y          |
+--------------------+--------------------+-----------------+------------+

#### Shields

A PC wielding a one-handed weapon in one hand and a shield in the other takes 2 less damage when they lose a clash.

#### Dual Wielding

A PC wielding two one-handed weapons may roll again if they lost the first Task of the Clash and are the attacker or capable of retaliation. This second Task uses the same Effort, Circumstances, and Skill as the first. If the PC succeeds on the second task, both the PC and the enemy deal their damage to one another. If they fail, only the enemy does damage.

#### Fencing

A PC wielding a one-handed weapon in one hand and nothing in the other takes a 1-level circumstance bonus to clash tasks thanks to the increased agility such a stance offers.

#### Unarmed or Magical Clashes

PCs can still clash if they have no weapons or if they rely on magic or psychic powers as a weapon.

A PC using magic or fists to clash uses a "stance" that functions as a weapon, and has all of a weapon's stats. For example, here's an example stance a traditional fireball-throwing wizard might have:

**Name**        **Attribute** **Damage Type** **Number of Hands** **Range Type** **Damage** **Special**
--------------- ------------- --------------- ------------------- -------------- ---------- -----------
Fireball Stance Insight       Fire            2                   Ranged         5 

See [Weapons] for an explanation of weapon stats.

Stances do not take up inventory slots. They represent knowledge a character possesses rather than something they have. PCs in a stance may also use their hands as if they are empty. Switching stances  still follows the same rules as switching weapons, however.

New stances are granted by scopes, at a rate of 2 stances for 1 scope. For instance, the scope that granted the above-mentioned Fireball Stance might be "May fight with sweeping gouts of flame or many precise rays of heat". This grants the above Fireball Stance, and also a Heat Ray Stance that deals damage and retaliates as two dual-wielded ranged weapons.

An unarmed clash is an open task in most settings. Unarmed characters have access to two stances:

**Name**        **Attribute** **Damage Type** **Number of Hands** **Range Type** **Damage** **Special**
--------------- ------------- --------------- ------------------- -------------- ---------- -----------
Agile Stance    Agility       Bludgeoning     2                   Standard Melee 4          Fencing
Powerful Stance Might         Bludgeoning     2                   Standard Melee 6

Characters that specialize in unarmed combat might have additional stances through their Scopes.

### Action: Stunt

Stunts are attempts by one combatant to reduce the effectiveness of another through the use of cleverness and dirty tricks. Things like tripping, disarming, pocket sand, and intimidation are all stunts.

Usually a stunt is resolved as a Task against the enemy's difficulty, though the GM has the right to change this in the case of unusual stunts. If the Task succeeds, the target suffers the stunt's negative effects. If it fails, nothing happens. Targets cannot perform a "retaliatory stunt".

Some enemies might be more difficult to affect with stunts than others. Quadrupedal creatures are more difficult to trip than bipeds, for instance, and ghosts can't be tripped at all. Usually, when a creature is more difficult to affect with a stunt, the Task is made at a 2-level penalty.

Similarly, it is usually difficult to affect the same enemy with a stunt multiple times. A 1-level penalty is applied to the stunt Task for each time this particular stunt has been used against an enemy before.

Stunts are meant to be expressions of player creativity, and they're certainly not limited to the examples presented here. GMs should adjudicate the negative effects of a novel stunt their players want to try, using the examples as a guide. As a catch-all, a 2-level penalty to Clash and Stunt Tasks until a condition is met is often appropriate.

The negative effects of multiple stunts don't stack, but they do apply multiple conditions that a target must clear before returning to full function.

**Trip**: Agility or Might task. A target takes a 2-level penalty to Clash and Stunt Tasks until they take a Move action to stand.

**Shove**: Might task. The target is forced backwards an immediate distance, potentially forcing them into environmental hazards such as traps or pits.

**Disarm**: Agility or Might task. The target's weapon lands on the ground within an immediate distance. A target takes a 2-level penalty to Clash Tasks until they retrieve a weapon (their old one or a new one).

**Pocket Sand**: Agility task. The target takes a 2-level penalty to Clash and Stunt Tasks until they take an Interact action to clear their eyes.

**Intimidate**: Willpower task. The target takes a 2-level penalty to Clash and Stunt Tasks made against the intimidator until the intimidator takes damage or suffers a stunt from any source.

**Sherlock Scan**: Insight task. The target takes a 2-level penalty to Clash and Stunt tasks from the scanner only until they take an interact action to fix whatever vulnerability the scanner noticed.

**Enraging Insult**: Insight or Willpower task. The target takes a 2-level penalty to Clash and Stunt tasks against all creatures other than the insulter until it takes damage or is subject to a stunt from a creature other than the insulter.

**Sleep Spell**: Insight task. The target can't act until it takes damage, is harshly jostled, or another creature takes an action to shake it awake.

### Actions: Wind Up and Release

These actions allow a combatant to "charge up" a particularly powerful attack or ability and release it on their next turn.

This charged ability can either be an area effect, targeting all creatures within an immediate distance of some origin point, or a focused effect, targeting a single creature with three separate actions. The user of the charged ability chooses one action (in the case of an area effect) or three actions (in the case of a focused effect) that the charged ability will use. These actions can be anything, but are most often Clash or Stunt.

Whether the charged ability is an area effect or a focus effect, which creatures are being targeted, and what actions are being used is determined when the user of the charged ability takes the Wind Up action.

Other creatures in the combat can tell that a creature is winding up a charged ability. A PC can hide the nature and target(s) of the charged ability from NPC opponents with a Willpower Task against the most observant opponent. If an NPC opponent is using a charged attack, the most observant PC may make an Insight Task against that NPC to determine the nature and target(s) of the attack.

The turn after a creature has taken the Wind Up action, it can take the Release action to unleash the charged ability. The creature can move an Immediate distance before taking the Release action, like normal. It may also move the origin of an area effect up to an Immediate distance as part of its movement. If it fails to use the Release action before the end of its turn, if the intended target has run away, for example, the charged ability is lost.

When a PC is taking the Release action, they may commit effort once for all Tasks rolled as part of the Release, but must roll for each Task separately. If the Tasks that will be rolled as part of the Release use different attributes, use the attribute with the lowest Edge when committing effort.

When making a Strike as part of a Release, the defender may never retaliate, no matter their weapon.

### Action: Move

A combatant taking this action may move a Short distance in addition to the Immediate distance that they may already move each turn.

### Action: Interact

A catch-all action for interacting with items or the environment. An environmental interaction that harms or hinders an enemy is probably a Stunt rather than an Interact. Examples of interact actions:

* Switching weapons
* Drinking a potion
* Pulling a lever
* Opening/closing a door

### Action: Other

If a PC or enemy wants to attempt an action not explicitly covered above, the GM should use the above actions as a guidline to adjudicate the effects. The answer to "can I do X?" should almost never be "no". However, the GM should inform the asking player about any consequences to their action that their character would be aware of.

## Site Exploration

Site exploration occurrs in a series of rounds, each of which last one Short Turn. During each round, each PC selects a single Site Exploration Action, which are resolved simultaneously. 

### Rooms in Sites

Unlike in combat, distances in sites are measured abstractly in the form of rooms. Rooms in a site don't have to be literal rooms, they just must be small enough that the party can interact with all the object in the room more or less freely. A room should always be smaller than a Medium distance in any direction. Particularly large areas of a site may be broken up into multiple rooms. Inevitably, rooms wil be different sizes, but smaller and larger rooms will average out over time.

### Resource Management in Sites

Most sites have an element of time pressure adding urgency and difficulty to exploration. The classic example of this is light in a fantasy dungeon. Each torch carried by the party takes up inventory space so they may only bring so many, and each torch lasts only 6 Short Turns. Other settings might have other sources of time pressure. For instance, a science fiction setting might require the party to manage oxygen levels in their suits. An enemy fortress might be well-lit and have plenty of air, but frequent and aggressive patrols by soldiers (see below for more on enemy movement).

Resources like light or air deplete at the end of each Short Turn. Running out of these resources has consequences, usually ending the exploration quickly. For example:

**Light**: The party flees the dungeon in a stumbling panic. For each Short Turn that it would take to exit the dungeon while Moving Quickly, each PC must make a Task with an attribute and difficulty dependent on the current dungeon. If they fail, they lose one random item from their inventory and take damage of a type and amount dependent on the current dungeon.

**Air**: At the end of each Short Turn, every PC without air takes 12 Might damage from suffocation.

GMs are encouraged to think up new resources that are appropriate to the setting of their game or the specific sites that the PC party is exploring.

### Enemy Movement in Sites

In most sites, potentially hostile creatures will move from room to room periodically, rather than sitting in one place for the PC party to encounter them. The GM might use one of several methods for modeling this movement, discussed in [Modeling Enemy Movement]. This movement occurs at the end of each turn. If potentially hostile creatures enter the room where the PCs currently are, the party may be forced into a negotiation or a fight.

### Fleeing in Sites

On the PCs' turn in combat, some or all of them may choose to flee instead of acting. Only PCs that are able to take a Move action may flee, though the party is free to leave unfortunate comrades behind. Combat continues until every PC has fled, died, been captured, or is otherwise out of the fight. On the next short turn, fleeing PCs must take the Move Quickly action to get away from the site of the combat.

Enemy combattants might or might not choose to pursue fleeing PCs. Cautious enemies or enemies that took significant losses or damage in the combat are less liely to pursue.

Enemy combattants may also attempt to flee from the PCs. They might choose to flee in response to the combat going badly for them or an intimidating display from the PCs. GMs are encouraged to use the morale mechanics found in [Enemy Morale] to decide when enemies try to flee or surrender.

### Action: Move Carefully

TODO

### Action: Move Quickly

TODO

### Action: Search

TODO

### Action: Fight

TODO

### Action: Interact

TODO

## Wilderness Exploration

TODO

## Settlement Exploration

TODO

## Mystery Solving

TODO

## Negotiation

TODO

## Downtime

TODO

## Encumbrance and Equipment

TODO

### Cyphers

TODO

### Artifacts

TODO

### Light Sources

TODO

### Air Sources

TODO

### Weapons

TODO

#### Base Weapon Stats

**Number of Hands** **Range Type** **Damage**
------------------- -------------- ----------
1                   Standard Melee 4
1                   Reach Melee    2
1                   Ranged         3
2                   Standard Melee 6
2                   Reach Melee    4
2                   Ranged         5

#### Weapon Special Abilities

**Fencing**: A two-handed weapon with this property is treated as though the weilder is weilding a one-handed weapon in one hand and nothing in the other (see [Fencing]). Weapons with this ability usually deal damage as a one-handed weapon.

#### Example Weapon Chart: Fantasy Setting

**Name**          **Attribute** **Damage Type** **Number of Hands** **Range Type** **Damage** **Special**
----------------- ------------- --------------- ------------------- -------------- ---------- -----------
Dagger/Shortsword Agility       Piercing        1                   Standard Melee 4
Longsword         Agility       Slashing        1                   Standard Melee 4
Axe               Might         Slashing        1                   Standard Melee 4
Morningstar       Might         Bludgeoning     1                   Standard Melee 4
Shortspear        Agility       Piercing        1                   Reach Melee    2
Hand Crossbow     Agility       Piercing        1                   Ranged         3
Greatsword        Might         Slashing        2                   Standard Melee 6
Warhammer         Might         Bludgeoning     2                   Standard Melee 6
Spear             Agility       Piercing        2                   Reach Melee    4
Crossbow          Agility       Piercing        2                   Ranged         5
Bow               Might         Piercing        2                   Ranged         5

### Armor

## NPCs

TODO

## Allies

TODO

## Vehicles and Mounts

TODO

## Scale

TODO

# Characters

## Creation

TODO

## Advancement

TODO: Add increased healing efficiency

There are a number of ways that characters can become more powerful over the course of a campaign. Each of these advancement benefits may only be taken a certain number of times.

* **Increasing Capabilities**: You gain 1 point to add to one of your stat Pools (your choice). Limit 20x.
* **Moving Toward Perfection**: You add 1 point to one of your stat Edges (your choice). Limit 5x.
* **Extra Effort**: Your maximum Effort score increases by 1. Limit 5x.
* **Special Training**: You increase your experience and general capability. This benefit applies one of the below effects, determined by how you got it. Limit 5x.
  + **Improved Skills**: Boost one of your existing character statement elements.
  + **Diverse Skills**: Add a new non-boosted Descriptor or Focus element to your character statement.
  + **Armor Training**: Lower the Agility cost for wearing armor by 1.
  + **Improved Recovery**: Add 2 to your recovery rolls.
* **New Ability**: Gain a new ability that relates to one of the elements of your character statement. Limit 5x.

These advancement benefits are not acquired with experience points, like in other RPGs. Instead, they are rewards for engaging with the world in specific ways, normally completing side quests and helping NPCs.

The GM decides what exactly merits an advancement benefit in the campaign. How exactly the GM should do this is discussed in the Game Mastering section.

# Game Mastering

## Running the Crypto Hack

### Modeling Enemy Movement

TODO

### Enemy Morale

TODO

## Designing Settings for the Crypto Hack

### Designing Character Scopes

TODO: closed scopes grant one action, open scopes grant multiple from a single action class, etc

## Designing Content for the Crypto Hack

### Everything is a Puzzle

TODO

### Puzzle Design Fundamentals

TODO

### Combats

TODO

### Puzzles

TODO

### Social Challenges

TODO

### Dungeons

TODO

### Wilderness

TODO

### Mysteries

TODO

## NPCs and Creatures

TODO

## Rewards and Character Advancement

TODO
