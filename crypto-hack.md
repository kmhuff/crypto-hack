---
title: The Crypto Hack
author: Kurtis Huff
date: 18 March 2024
header-includes: |
    \usepackage[textwidth=12.1cm,textheight=22cm]{geometry}
---

# Rules

## Tasks

### Task Resolution

When a PC attempts to do something risky where the consequence for failure is interesting, the GM calls for a task. Tasks have a base difficulty from 0-10. PCs may reduce the difficulty through various methods (described below). The PC then rolls a d20. If they get higher than the adjusted difficulty x3, they succeed, otherwise they fail.

Here is a summary of the meaning of base task difficulties:

**Difficulty** **Description**
-------------- ---------------
0              A task that anyone could succeed at (no roll required)
1-3            A task that requires a little training to succeed at
4-6            A task that only trained professionals could succeed at
7-10           A task that only legendary masters could succeed at

Task difficulty can be adjusted by the PCs in 3 different ways.

* Effort: PCs may spend points from their stat pools to reduce difficulty (explained in more detail below). Each character has an effort limit that determines the total effort they can give to a task. It starts at 1 and can go no higher than 6.
* Skill: Experience doing similar tasks can reduce difficulty (explained in more detail below). No character can ease a single task by more than 2 ranks because of skill.
* Circumstance: Beneficial circumstances can reduce difficulty (explained in more detail below). No character can ease a single task by more than 2 ranks because of circumstance.

An experienced PC willing to spend time setting up and burn a lot of resources can reduce even a legendary level 10 task to a trivial 0 level.

### Attempting Tasks

Many tasks can be attempted by anyone. These are called open tasks. Some of these tasks might be very difficult to those without the right skill, effort, or circumstances, but they can at least be attempted. The task "fight with a sword" can be attempted by anyone, but only certain people are any good at it.

In contrast, some tasks cannot be attempted by anyone without the necessary skill, bloodline, cyberware, etc. These are called closed tasks. In this case, the task may only be attempted by a character that has a scope explicitly permitting them to do so (more on scopes in the [Scopes and Skill] section). The task "hack the computer with my brain" may only be attempted by a character with a scope that allows mental hacking.

Which tasks are open and which are closed is determined by the logic of the fictional setting you are playing in. Usually, this is fairly obvious, but when it's not, the GM makes the final ruling.

### Trivial and Impossible Tasks

If a task's difficulty is ever dropped below 1, the task is considered trivial, and no roll is required. Any PC that attempts it automatically succeeds. Most everyday tasks are trivial.

If a task's difficulty is 7 or greater even after adjusting its difficulty by Effort, Skill and Circumstance, the task is considered impossible, and no roll is required. Any PC that attempts it automatically fails.

### Failing Tasks

When a PC fails a task, it is often obvious what the consequence should be. If a PC fails a task to jump across a gap, for instance, they will fall into the gap. However, not all tasks are so clear-cut.

Most tasks have a hidden failure condition: they waste time. If a PC fails to pick a lock, for instance, they waste the short turn they spent making the attempt (see [Time Tracking]). Sometimes, this doesn't have much effect on the PCs. Other times, such as when the PCs are standing around in a monster-infested ruin wasting light while they could be attacked at any time, wasting time can be very significant.

### Performing Tasks Carefully

Sometimes, a PC wants to perform a task where the only consequence of failure is wasted time, but they aren't under any time pressure. In this case, a PC might be able to choose to take longer on the task in exchange for automatic success. If they meet the conditions to perform the task carefully and they choose to do so, a PC can spend a turn of one size longer than the original task in order to succeed automatically on the task.

If the task's difficulty is 3 or lower after reducing it by Skill and Circumstance, a PC may perform the task carefully in 1 longer turn. If the adjusted difficulty is 4-6, performing the task carefully will take 3 longer turns. If the adjusted difficulty is 7 or greater, the task cannot be performed carefully at all.

Notice that we're only adjusting the difficulty by Skill and Circumstance here, not Effort. A PC may not spend Effort on a task when performing it carefully.

For example, a thief PC is picking the lock on a safe that the group brought with them back to their hideout. Normally picking a lock takes a short turn, but the group is safe, so the PC decides to pick it carefully. The lock is old and rusted but still solid, a difficulty 4 task. The PC has a scope that applies to lockpicking, so the difficulty is eased by 1 rank because of Skill. The adjusted difficulty is 3 or lower, so the PC can automatically succeed in picking the lock if they take one medium turn instead of a short turn in the attempt.

## Attributes and Effort

Each PC has 4 attributes:

* Might: Strength and physical toughness
* Agility: Speed, coordination, and reflexes
* Insight: Perceptiveness and memory
* Willpower: Determination and force of personality

Each task is associated with a particular attribute. For example:

* Moving a boulder is a might task
* Dodging an arrow is an agility task
* Noticing a hidden foe is an insight task
* Intimidating an enemy is a willpower task

Each stat has two components: a pool and an edge.

* The pool represents a character's raw potential in that stat
* The edge represents a character's training or experience in using that stat.

For example, an experienced adventurer who never got much book learning and is partially deaf in one ear might have a low insight pool but a high insight edge.

PCs can apply effort to tasks by spending points from the pool of the associated stat. The process works like this:

#. Spend 3 points from the pool to apply the first level of effort
#. Add additional levels of effort by spending 2 pool points each. You can only do this up to the PC's maximum effort value. A starting character has a maximum effort of 1, so can never perform this step.
#. Subtract the relevant edge from the points you spend. So a PC with an edge of 1 in the relevant skill can apply one level of effort for 2 pool points, or two levels of effort for 4 pool points.

Effort can also be applied to increase damage during combat. This is described in more detail below.

A PC's pools also serve as their hit points. This is described in more detail below.

## Scopes and Skill

In addition to attributes, characters are defined by a number of scopes that define what they are good at and what they might be able to do that most others can't. A few examples of scopes are:

* Craft poisons for use in combat (Combat).
* Fight with one-handed standard melee weapons (Combat).
* Avoid or resist physical attacks (Combat).
* Pick locks and disassemble delicate machinery (Exploration).
* Hack into computer systems (Exploration).
* Be stealthy (Exploration).
* Magically manipulate fire (Exploration).
* Track creatures through the wilderness (Exploration).
* Use animal magic to assist in wilderness travel (Exploration).
* Find and interact with professional criminals (Negotiation).
* Read emotions and thoughts (Negotiation).
* See glimpses of the past (Exploration).

As you can see, scopes are made up of two parts: action descriptions and type. In order for a scope to apply to an action, the action must match both the action descripton and the type. If a character wants to both use fire as a weapon in combat (obviously Combat type) and manipulate it in more complex ways outside of combat (probably Exploration type), they need to have two scopes. The three types correspond to the three types of challenges characters will most frequently face in the game, combat, exploration, and negotiation.

GMs are generally responsible for creating most of the scopes that will be relevant to their campaign. If a player wants to create a character concept that isn't covered by the existing list of scopes provided by the GM, they should work with the GM to create the scopes that they need. GMs are entitled to say no to a player request for a scope if it doesn't fit the setting or if they feel it would be imbalanced in some way, but they are encouraged to work with players to fulfil requests. More about creating scopes in [Creating Character Scopes].

Some scopes can allow the character to attempt closed tasks (see [Attempting Tasks]). For example, other characters in an alchemist's party wouldn't even know where to start creating a poison (a closed task), but anyone could try to avoid or resist a physical attack (an open task). A scope only allows characters to attempt closed tasks if they meet both its description and its type.

Characters start with 5 scopes. More on this in [Creation].

### Scope Advancement

As characters gain in power, they can gain additional scopes or empower the ones they already have. Scopes that are empowered this way are called "boosted". Boosted scopes grant additional [Skill Bonuses]. Characters can gain a total of 5 new or boosted scopes over the course of their story. More on how new or boosted scopes are acquired in [Advancement].

### Skill Bonuses

If a scope applies to an action (i.e. the action matches both the scope's description and its turn length), the character gains a skill bonus on that action. Normal scopes grant a skill bonus of 1 rank. Boosted scopes grant a skill bonus of 2 ranks.

Only the best scope can apply to a single task.

Skill bonuses cannot exceed 2 ranks.

## Circumstance

Beneficial circumstances can ease the difficulty of a check by up to 2 levels. Two different beneficial circumstances can stack or a single overwhelmingly beneficial circumstance can ease the check by 2 levels.

Some examples of circumstances easing a check follow:

* Being helped by an ally (see [Action: Aid]).
* Attacking an enemy that is hindered by distraction, a temporary status, etc.
* Referring to a rough map to find your way through a dangerous location.
* Offering a glass of a dignitary's favorite tea before engaging in a negotiation.

Some examples of overwhelming circumstances are:

* Attacking an enemy that is completely unaware of you.
* Using a detailed, up-to-date map with landmarks to find your way through a dangerous location.
* Using a character reference that your interlocutor trusts to convince them that you will keep your word.

Circumstances can also be detrimental to a task. 2 detrimental circumstances may stack, or one circumstance can be overwhelmingly detrimental, exactly like beneficial circumstances. Detrimental circumstances are also limited to 2 ranks.

Merely having the tools needed to perform a task does not count as a beneficial circumstance for the task. In fact, lacking the tools necessary to perform a task would likely count as a detrimental circumstance.

## Time Tracking

**Immediate Turns**: Last 6 seconds. Combat is tracked in immediate turns.

**Short Turns**: Last 10 minutes. Site Exploration and Negotiation are tracked in short turns.

**Medium Turns**: Last 1 hour. Settlement Exploration and Mystery Solving are tracked in medium turns.

**Long Turns**: Last 8 hours. Wilderness Exploration is tracked in long turns. Usually, two long turns are used for activity during the day and one is used for sleep.

**Downtime Turns**: Last 1 week. Downtime is tracked in downtime turns.

Time is tracked at a certain scale depending on what the party is doing at the time. If the party is fighting, time is tracked in immediate turns. If they are exploring a location, it is tracked in short turns. 

During each turn, each PC may take a single action appropriate to the activity the party is performing at the moment. For example, if the party is exploring the wilderness, each PC may take a single Wilderness Exploration action every turn. These actions include things like "Navigate the Wilderness", "Forage", and "Explore a Point of Interest'.

In addition to a single action at the current time scale, PCs may take any number of actions at a shorter time scale during a turn. For instance, the party Navigating the Wilderness (long turn) might engage in a Fight and rest to patch their wounds up afterwards (2 short turn actions). All that activity still takes one long turn.

If the party is partway through an action and an event forces them to take another of the same length, both the partially completed action and the forced action occur during the same turn. For instance, a party exploring a dungon might be Moving Carefully (short turn) for 1 room (of a maximum of 2) before they run into some monsters and start a Fight (short turn). Both the movement and the combat happen during the same short turn. However, if that party instead moved 2 rooms (the maximum for Moving Carefully) before running into the Fight, the movement would happen during one short turn and the combat would happen during the next.

An action never takes less than a turn, even if the sub-activities that make it up might imply that it did. For example, a party Exploring a Point of Interest descends into a dungeon and only spends 1 hour there (6 short turns). The "Explore a Point of Interest" action still takes the full 8-hour long turn.

On the other hand, if the sub-activities imply that the action took *more* time than its entire turn, the party must take the action again. If a party manages to explore a dungeon for more than 8 hours or fight for more than 10 minutes (both impressive feats), the action "spills over" into the next turn and the party members all automatically take it again.

## Damage

Damage dealt to a PC is applied to one of that PC's pools, depending on the source.

* A slashing or stabbing attack targets the might pool.
* A bashing or bruising attack targets the agility pool.
* Mental attacks or assaults on the senses (pepper spray, flashbangs) target the insight pool.
* Intimidation or fear effects, magical or mundane, target the willpower pool.

These aren't the only types of damage a PC might face, but they should give you a good idea of what the various pools are for.

When a pool becomes entirely depleted, the PC loses the ability to attempt tasks above level 0 from that Stat. A might-depleted PC can barely drag themselves across the room, let alone lift something heavy, for instance. When all of a PC's pools are completely depleted, they die.

When a pool is depleted, any damage that the PC takes to that pool overflows into the next-most logical pool. Usually this means that physical attacks flow into the other physical pool and mental attacks flow into the other mental pool. This overflowing continues if there is more than one depleted pool. For example, a character with a depleted might pool that takes a slashing attack (normally might damage), would instead take the damage to agility. If that character's agility pool was also depleted, they would take the damage to insight instead.

## Healing

Points in a pool can be restored back to their normal maximum trough rest. Each time you rest, recover a number of points equal to a d6 + your recovery bonus. These points can be divided among your pools however you wish. A starting character's recovery bonus is 1 and it can be improved over time. For more about improving your recovery bonus, see [Advancement].

The first rest you take each day takes one immediate turn. The next rest takes one short turn. The third rest of the day takes one long turn. This final rest is assumed to be your sleep for the day.

A full day of rest restores 3d6 + 3 * your recovery bonus.

### Medicine and Magic Healing

If a character has already rested twice, a healer may attempt to grant them additional rests as a task that takes a short turn. The first additional rest is a difficulty 3 task, the second difficulty 5, the third difficulty 7, and the fourth difficulty 9. No more than 4 additional rests may be granted this way.

## Universal Actions

These actions can be performed by PCs at any time and aren't limited to a particular context. They might take a fixed turn size or they might be able to be taken in multiple different turn sizes.

### Action: Aid

Give aid to an ally through expertise, magic, or just an additional hand. Attempt a task with a difficulty equal to the difficulty of your ally's task. Take a one-rank circumstance bonus on the task because you are just helping, not performing the task yourself. If you succeed, grant your ally a circumstance bonus on their task equal to your skill bonus on the task you just made. This action matches the turn size of the action that you are aiding.

For example, a bard in a party of fantasy adventurers has the scope Silver Tongue Magic (infuse words with magic (Negotiation)). This scope is boosted, so tasks to which it is relevant benefit from a 2-rank skill bonus. The party's fighter is trying to persuade a local lord to give the party aid. The bard decides to use Silver Tongue Magic to aid the fighter, who has many strengths but isn't the most diplomatic sort. The difficulty of the fighter's task is 5, so the bard must succeed at a difficulty 4 task to aid (5 - 1 circumstance). The bard's Silver Tongue Magic skill bonus takes off an additional 2 ranks, making the task difficulty 2. The bard decides to roll that and gets an 8, succeeding on the task. The figher now benefits from the bard's 2 ranks of Silver Tongue Magic skill as a circumstance bonus on his task.

You can aid yourself in many tasks by taking the time to set up and make your task easier for yourself. Note that each aid action takes as much time as the original action, so doing this will cause you to take, at best, twice as long to complete your task.

In combat, you can take the aid action as normal, but you can also take it off your turn to aid an ally defending against a strike or stunt. You must forfeit your next turn if you do this, however.

## Combat

Combat is played in a series of rounds, each of which lasts 1 immediate turn. At the start of combat, one PC may make an agility task against the most agile opponent. If the PC succeeds, the PC party goes first. If the PC fails, the opponents go first. The PCs and their opponents may decide what order to act in within their side's turn.

Characters may draw weapons for free at the start of combat, but afterwards must take an interact action to change weapons.

On a creature's turn, the creature can move an Immediate distance and take one action. While the action can be anything that it would take roughly 6 seconds to do, the most common options are outlined below.

### Distance in Combat

TODO: Remove Roughly

**Immediate Distance**: Roughly 10 ft. If you're this close to a creature, they can close the distance and hit you with a melee attack nearly instantly.

**Short Distance**: Roughly 50 ft. The distance that a creature can charge in an immediate turn.

**Medium Distance**: Roughly 150 ft. This is the maximum range that a creature with a ranged attack can attack without penalty.

**Long Distance**: Roughly 450 ft. Beyond this range, even ranged attacks cannot target creatures.

### Action: Clash

Combatants clash when they engage in combat and attempt to injure one another.

A clash has an attacker and a defender. Whether the PC is the attacker or the defender, the clash is resolved as a task against the enemy's difficulty. If the attacker wins the clash, they deal their weapon's damage to the defender. If the defender wins, they take no damage, and they might deal their weapon's damage to the attacker depending on their weapon.

The attribute of the task is determined by the table below:

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

A PC wielding two one-handed weapons may roll again if they lost the first task of the clash and are the attacker or capable of retaliation. This second task uses the same Effort, Circumstances, and Skill as the first. If the PC succeeds on the second task, both the PC and the enemy deal their damage to one another. If they fail, only the enemy does damage.

#### Fencing

A PC wielding a one-handed weapon in one hand and nothing in the other takes a 1-level circumstance bonus to clash tasks thanks to the increased agility such a stance offers.

#### Unarmed or Magical Clashes

PCs can still clash if they have no weapons or if they rely on magic or psychic powers as a weapon.

A PC using magic or fists to clash uses a "stance" that functions as a weapon, and has all of a weapon's stats. For example, here's an example stance a traditional fireball-throwing wizard might have:

```{=latex}
\newlength{\extraspace}
\setlength\extraspace{4cm}
\setlength\columnwidth{\columnwidth + \extraspace}
\setlength\LTleft{-0.5\extraspace + \tabcolsep}
```

**Name**        **Attribute** **Damage Type** **Number of Hands** **Range Type** **Damage** **Special**
--------------- ------------- --------------- ------------------- -------------- ---------- -----------
Fireball Stance Insight       Fire            2                   Ranged         5 

```{=latex}
% restore old columnwidth, table placement
\setlength\columnwidth{\linewidth - 4cm}
\LTleft=\fill
```

See [Weapons] for an explanation of weapon stats.

Stances do not take up inventory slots. They represent knowledge a character possesses rather than something they have. PCs in a stance may also use their hands as if they are empty. Switching stances  still follows the same rules as switching weapons, however.

New stances are granted by scopes, at a rate of 2 stances for 1 scope. For instance, the scope that granted the above-mentioned Fireball Stance might be "May fight with sweeping gouts of flame or many precise rays of heat". This grants the above Fireball Stance, and also a Heat Ray Stance that deals damage and retaliates as two dual-wielded ranged weapons.

An unarmed clash is an open task in most settings. Unarmed characters have access to two stances:

**Name**        **Attribute** **Damage Type** **Number of Hands** **Range Type** **Damage** **Special**
--------------- ------------- --------------- ------------------- -------------- ---------- -----------
Agile Stance    Agility       Bludgeoning     2                   Standard Melee 4          Fencing
Powerful Stance Might         Bludgeoning     2                   Standard Melee 6

Characters that specialize in unarmed combat might have additional stances through their scopes.

### Action: Stunt

Stunts are attempts by one combatant to reduce the effectiveness of another through the use of cleverness and dirty tricks. Things like tripping, disarming, pocket sand, and intimidation are all stunts.

Usually a stunt is resolved as a task against the enemy's difficulty, though the GM has the right to change this in the case of unusual stunts. If the task succeeds, the target suffers the stunt's negative effects. If it fails, nothing happens. Targets cannot perform a "retaliatory stunt".

Some enemies might be more difficult to affect with stunts than others. Quadrupedal creatures are more difficult to trip than bipeds, for instance, and ghosts can't be tripped at all. Usually, when a creature is more difficult to affect with a stunt, the task is made at a 2-level penalty.

Similarly, it is usually difficult to affect the same enemy with a stunt multiple times. A 1-level penalty is applied to the stunt task for each time this particular stunt has been used against an enemy before.

Stunts are meant to be expressions of player creativity, and they're certainly not limited to the examples presented here. GMs should adjudicate the negative effects of a novel stunt their players want to try, using the examples as a guide. As a catch-all, a 2-level penalty to clash and stunt tasks until a condition is met is often appropriate.

The negative effects of multiple stunts don't stack, but they do apply multiple conditions that a target must clear before returning to full function.

**Trip**: Agility or might task. A target takes a 2-level penalty to clash and stunt tasks until they take a move action to stand.

**Shove**: Might task. The target is forced backwards an immediate distance, potentially forcing them into environmental hazards such as traps or pits.

**Disarm**: Agility or might task. The target's weapon lands on the ground within an immediate distance. A target takes a 2-level penalty to clash tasks until they retrieve a weapon (their old one or a new one).

**Pocket Sand**: Agility task. The target takes a 2-level penalty to clash and stunt tasks until they take an interact action to clear their eyes.

**Intimidate**: Willpower task. The target takes a 2-level penalty to clash and stunt tasks made against the intimidator until the intimidator takes damage or suffers a stunt from any source.

**Sherlock Scan**: Insight task. The target takes a 2-level penalty to clash and stunt tasks from the scanner only until they take an interact action to fix whatever vulnerability the scanner noticed.

**Enraging Insult**: Insight or willpower task. The target takes a 2-level penalty to clash and stunt tasks against all creatures other than the insulter until it takes damage or is subject to a stunt from a creature other than the insulter.

**Sleep Spell**: Insight task. The target can't act until it takes damage, is harshly jostled, or another creature takes an action to shake it awake.

### Actions: Wind Up and Release

These actions allow a combatant to "charge up" a particularly powerful attack or ability and release it on their next turn.

This charged ability can either be an area effect, targeting all creatures within an immediate distance of some origin point, or a focused effect, targeting a single creature with three separate actions. The user of the charged ability chooses one action (in the case of an area effect) or three actions (in the case of a focused effect) that the charged ability will use. These actions can be anything, but are most often clash or stunt.

Whether the charged ability is an area effect or a focus effect, which creatures are being targeted, and what actions are being used is determined when the user of the charged ability takes the wind up action.

Other creatures in the combat can tell that a creature is winding up a charged ability. A PC can hide the nature and target(s) of the charged ability from NPC opponents with a willpower task against the most observant opponent. If an NPC opponent is using a charged attack, the most observant PC may make an insight task against that NPC to determine the nature and target(s) of the attack.

The turn after a creature has taken the wind up action, it can take the release action to unleash the charged ability. The creature can move an Immediate distance before taking the release action, like normal. It may also move the origin of an area effect up to an Immediate distance as part of its movement. If it fails to use the release action before the end of its turn, if the intended target has run away, for example, the charged ability is lost.

When a PC is taking the release action, they may commit effort once for all tasks rolled as part of the release, but must roll for each task separately. If the tasks that will be rolled as part of the release use different attributes, use the attribute with the lowest edge when committing effort.

When making a clash as part of a release, the defender may never retaliate, no matter their weapon.

### Action: Move

A combatant taking this action may move a Short distance in addition to the Immediate distance that they may already move each turn.

### Action: Interact

A catch-all action for interacting with items or the environment. An environmental interaction that harms or hinders an enemy is probably a stunt rather than an interact. Examples of interact actions:

* Switching weapons
* Drinking a potion
* Pulling a lever
* Opening/closing a door

### Action: Flee

A combattant may only take this action if they could have taken a move action. The combattant immediately flees the battle. Combat continues without the fleeing combattant, until one side or the other has fled, surrendered, died, or otherwise is unable to continue fighting.

If the combat occurred in a site, the fate of the fleeing characters is determined as described in [Fleeing in Sites]. If the combat did not occurr in a site (if, for example, it occurred in the wilderness, or a city), the fleeing combattants are assumed to get away clean. If the other side wants to pursue, they must take an action to track down the fleers.

### Action: Other

If a PC or enemy wants to attempt an action not explicitly covered above, the GM should use the above actions as a guidline to adjudicate the effects. The answer to "can I do X?" should almost never be "no". However, the GM should inform the asking player about any consequences to their action that their character would be aware of.

## Negotiation

Negotiations occurr when the PCs are trying to convince an NPC to do something for them, and the NPC has reasons that they don't want to do it. The PCs must overcome the NPC's objections to get them to agree to whatever the PCs want them to do. Negotiation occurrs in a series of rounds, each of which last one short turn. During each round, the PCs speak to the NPC, or other NPCs in the vicinity, attempting to find out the primary NPC's objections and address them. Each PC may only take 1 action in a round. After each PC has taken their action, the round ends and a new one begins.

### Objections

Objections define a negotiation challenge. If an NPC doesn't have objections to something the PCs want them to do, it is not a negotiation. The NPC just immediately answers "yes" to the PC request. Once all objections that an NPC has to a PC request are overcome, the NPC will agree to the request.

Objections come in two flavors, soft and hard. Soft objections can either be addressed or countered with an incentive. Hard objections must be addressed. They represent objections that the NPC takes very seriously and is willing to take risks for.

For example, the PCs are trying to bribe a guard into letting them into the city without telling the authorities. The guard has a soft objection that they could get in trouble with their superiors for doing this. They also have a hard objection that the PCs are suspicious characters who might want to hurt the people of the city. The soft objection can be overcome by offering the incentive of money (a bribe). The hard objection can only be overcome by addressing it and assuring the guard of the PCs' good intentions somehow.

An objection doesn't have to be overcome immediately, and it doesn't necessarily have to be overcome through the negotiation system. For instance, in the case of a party trying to convince a merchant to bring them north, one of the merchant's objections might be "there's goblins on the road, it's too dangerous right now." The party can overcome that objection through negotiation by promising to provide protection, but they could also overcome the objection by just going out and killing the goblins, removing the problem.

### Patience

Most NPC don't have the patience to sit around arguing endlessly. An NPC will cut off the negotiation after a fixed number of rounds. If the PCs haven't overcome all of the NPC's objections by the time that they run out of patience, the negotiation is a failure. Depending on the situation, the PCs might or might not be able to try to persuade the NPC again later.

### Action: Promise

Attempt to overcome an NPC's objection by promising to deal with that objection sometime in the future. This action can overcome hard objections.

There is nothing preventing the PC from promising something that they don't intend to deliver on.

If the promise is good enough to address the NPC's problem and the NPC trusts the PCs to follow through, the NPC can accept the promise right away. However, if the promise doesn't address the NPC's concern to their satisfaction or they don't trust the PCs to fulfil their promise, they might reject the promise. If this happens, the PC that made the promise can attempt a social task with a difficulty determined by the NPC and the PC's approach to persuade them to accept the promise anyway. They can also offer additional proof or collateral to convince the NPC to trust them.

If the NPC rejects the promise and the PC is unable to convince them otherwise, the action is over and the objection is not overcome. Another PC can try to overcome the objection with a different promise, however.

### Action: Offer Incentive

Attempt to overcome an NPC's objection by offering the NPC something that they want. This action can only overcome soft objections.

There is nothing reventing a PC from offering an incentive that can't or don't intend to deliver.

If the incentive is good enough that the NPC feels that it outweighs the objection, the NPC can accept the incentive right away. Howver, if the NPC feels that incentive is to stingy when weighed against the objection, or if they suspect the PC of lying about the incentive, they might reject the PC's offer. If this happens, the PC that offered the incentive can either make another offer or attempt to persuade the NPC to accept the incentive anyway. Persuading the NPC is a task with an attribute determined by the PC's approach and a difficulty determined by the NPC and the PC's approach.

If the NPC rejects the incentive and the PC is unable to convince them otherwise, the action is over and the objection is not overcome. Another PC can try to overcome the same objective with a different incentive, however.

### Action: Make an Emotional Appeal

Attempt to overcome an NPC's objection by attempting to persuade the NPC that giving in is the right thing to do. This action can only overcome soft objections.

This appeal varies in effectiveness wildly depending on how receptive the NPC is to the PC's emotional argument. If the appeal matches the NPC's morality strongly, they might automatically accept it, overcoming the objection. If the appeal is more marginal, the PC could use a social task to persuade the NPC to accept the emotional argument anyway. If the argument isn't compelling to the NPC at all, no social skill can change that.

### Action: Threaten

Attempt to overcome all of an NPC's soft objections at once by threatening them or something they value. This action cannot overcome hard objections.

The PC attempting the threat must attempt a willpower task with a difficulty determined by the NPC and the PC's approach. If they succeed, all of an NPC's soft objections are overcome at once. However, whether the task succeeds or fails, the NPC will be resentful of being threatened, which might impact future negotations. PCs should deploy threats with care.

### Action: Other

If a PC attempts an action that isn't exactly described by one of these options, GMs should use them as a guide for adjudicating the effects.

## Site Exploration

Site exploration occurrs in a series of rounds, each of which last one short turn. During each round, each PC selects a single Site Exploration Action, which are resolved simultaneously.

### Rooms in Sites

Unlike in combat, distances in sites are measured abstractly in the form of rooms. Rooms in a site don't have to be literal rooms, they just must be small enough that the party can interact with all the object in the room more or less freely. A room should always be smaller than a Medium distance in any direction. Particularly large areas of a site may be broken up into multiple rooms. Inevitably, rooms wil be different sizes, but smaller and larger rooms will average out over time.

### Resource Management in Sites

Most sites have an element of time pressure adding urgency and difficulty to exploration. The classic example of this is light in a fantasy dungeon. Each torch carried by the party takes up inventory space so they may only bring so many, and each torch lasts only 6 short turns. Other settings might have other sources of time pressure. For instance, a science fiction setting might require the party to manage oxygen levels in their suits. An enemy fortress might be well-lit and have plenty of air, but frequent and aggressive patrols by soldiers (see below for more on enemy movement).

Resources like light or air deplete at the end of each short turn. Running out of these resources has consequences, usually ending the exploration quickly. For example:

**Light**: The party flees the dungeon in a stumbling panic. For each short turn that it would take to exit the dungeon while Moving Quickly, each PC must make a task with an attribute and difficulty dependent on the current dungeon. If they fail, they lose one random item from their inventory and take damage of a type and amount dependent on the current dungeon.

**Air**: At the end of each short turn, every PC without air takes 12 might damage from suffocation.

GMs are encouraged to think up new resources that are appropriate to the setting of their game or the specific sites that the PC party is exploring.

### Enemy Movement in Sites

In most sites, potentially hostile creatures will move from room to room periodically, rather than sitting in one place for the PC party to encounter them. The GM might use one of several methods for modeling this movement, discussed in [Modeling Enemy Movement]. This movement occurs at the end of each turn. If potentially hostile creatures enter the room where the PCs currently are, the party may be forced into a negotiation or a fight.

### Fleeing in Sites

On the PCs' turn in combat, some or all of them may choose to flee instead of acting. Only PCs that are able to take a Move action may flee, though the party is free to leave unfortunate comrades behind. Combat continues until every PC has fled, died, been captured, or is otherwise out of the fight. On the next short turn, fleeing PCs must take the Move Quickly action to get away from the site of the combat.

Enemy combattants might or might not choose to pursue fleeing PCs. Cautious enemies or enemies that took significant losses or damage in the combat are less liely to pursue.

Enemy combattants may also attempt to flee from the PCs. They might choose to flee in response to the combat going badly for them or an intimidating display from the PCs. GMs are encouraged to use the morale mechanics found in [Enemy Morale] to decide when enemies try to flee or surrender.

### Action: Move Carefully

The PCs move slowly through the site, but remain careful and watchful for danger and opportunity. The PCs move up to 2 rooms. While they are moving, they can each describe something that they are doing at the same time, which can range from simply remaining on-guard and watchful to doing something specific, like repeatedly casting a spell.

Most traps are immediately obvious to a party moving carefully. It might not be obvious that a particular dungeon feature *is* a trap, and even obvious traps might have non-obvious triggers. Still, a party moving carefully will never blunder into a trap with no chance to avoid it at all.

Similarly, parties moving carefully usually recieve some hint that an ambush is present before they trigger it, whether that be a smell, a sound, or something else.

### Action: Move Quickly

The PCs move quickly trough the site, but are far more vulnerable to dangerous happenstances than when they are moving slowly. The PCs move up to 4 rooms, but will blunder into any traps and ambushes in their path.

### Action: Search

The PCs carefully comb the current room for hidden treasures or features.

Features in a site can either be observed, hidden, or secret. Observed features are obvious on a cursory examination of the room. The GM will tell the party about all of a room's observed features the instant they enter, no need to search. Hidden features aren't obvious without taking a bit of time and effort to look, but they aren't deliberately hidden, either. Any PC that takes the Search action in a room will find all of its Hidden features. Secret features were deliberately hidden away by previous inhabitants and take effort to find. A PC taking the search action can describe exactly how they search, if they want. If the course they describe would uncover the secret feature, they discover it.

### Action: Fight

The PCs engage in combat against hostile creatures. Refer to [Combat] to resolve a fight.

### Action: Interact

This is a catch-all action for various tasks that take a short turn within a site. Some examples of interact actions include:

* Healing a companion.
* Having a discussion or negotiation (see [Negotiation]).

## Wilderness Exploration

TODO

## Mystery Solving

TODO

## Settlement Exploration

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

There are a number of ways that characters can become more powerful over the course of a campaign. Each of these advancement benefits may only be taken a certain number of times.

* **Increasing Capabilities**: You gain 1 point to add to one of your stat pools (your choice). Limit 20x.
* **Moving Toward Perfection**: You add 1 point to one of your stat edges (your choice). Limit 5x.
* **Extra Effort**: Your maximum effort score increases by 1. Limit 5x.
* **Deepening Resillience**: Your recovery bonus increases by 1. Limit 5x.
* **Special Training**: You increase your experience and general capability. This benefit applies one of the below effects, determined by how you got it. Limit 5x.
  + **Improved Skills**: Boost one of your existing scopes.
  + **Diverse Skills**: Add a new non-boosted scope to your character.
  + **Armor Training**: Lower the agility cost for wearing armor by 1.
  + **Resillience Training**: Add 2 to your recovery bonus.

These advancement benefits are not acquired with experience points, like in other RPGs. Instead, they are rewards for engaging with the world in specific ways, normally completing side quests and helping NPCs.

The GM decides what exactly merits an advancement benefit in the campaign. How exactly the GM should do this is discussed in the Game Mastering section.

# Game Mastering

## Running the Crypto Hack

### Modeling Enemy Movement

TODO

### Enemy Morale

TODO

## Designing Settings for the Crypto Hack

### Creating Character Scopes

Action descriptions should be specific enough to not apply to everything, but vague enough to apply to multiple different actions.

TODO: Expand

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
