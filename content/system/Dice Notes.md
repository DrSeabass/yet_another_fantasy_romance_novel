# The Core  Mechanic

Let me just say up front this system is by a dice goblin for dice goblins.  It's not uncommon for a simple roll to need upwards of 7 dice of different sizes, and ideally different colors. I know it's chunky, but with that chunk comes distinct benefits:
* Rolling dice is fun.  Shut up -- it's a benefit.
* Different sources visibly contributing to the success of a roll is narratively cool
	* My lock pick was a piece of shit, but my wits and desire to save my friends really saved the day
	* My skill at the blade won the day, even though they gave me the dullest sword in the kingdom
* Consistency - Almost everything in this system resolves by adding dice
	* Want a buff?  More dice.
	* Contested roll? More dice.
	* Difficult Terrain? More dice?
	* Surprised by the enemy? More dice.
	* Fighting to impress the girl? More dice.
	* Fighting an already wounded enemy? More dice.
	* Group action? You better believe there's more dice.
* Everything that doesn't add dice still works by effecting interpretation of the dice
	* Changing target roll values to represent task complexity
	* Modeling depleting resources by changing die faces downward until replenishment

## Building Pools
When a player, npc, organization or basically anything sentient tries to achieve something, the first thing it does is go about building its dice pool.  A dice pool is composed of the following elements:
* The dice for the stat being used
* The dice for the skill being used
* The dice for the equipment being used
* The dice for any relevant relationships
* Any relevant buffs, enchantments, or enhancements

Think of each of these as a slot for a single element to fit into.  So, while it might make sense to swing a sword with all of your might, or to deftly maneuver your blade into an opponent, or to cleverly feint to gain an opening for the killing blow, you'll only ever be using your might stat, your finesse stat, or your intellect stat in the stat slot.

At any time, the player may opt not to fill a pool slot.  Mechanically, this makes no difference.  The player just has fewer dice to roll.  Similarly, if nothing fits into the slot, then it remains empty.  So, the impact of swinging a sword without training in sword fighting is that the character swinging the sword has fewer dice to roll. Similarly if for some reason a warrior needed to swing a sword _without appearing trained in using a blade_, it would have the same effect - the devious warrior would not add their sword skill to the roll.

Once the slots in the pool are filled, the dice are rolled, and we proceed to the next step, building successes.

## Building Groups
| Target Value | Name     | Example                                                                             |
| ------------ | -------- | ----------------------------------------------------------------------------------- |
| 5            | Trivial  | Donning your armor in a hurry, but not in an emergency                              |
| 7            | Easy     | Not breaking decorum when the Prince says something mildly insulting in passing     |
| 9            | Moderate | Striking an equally skilled opponent in combat                                      |
| 11           | Hard     | Gaining meaning from a partially burned book written in a language you kind of know |
| 13           | Heroic   | Eating a meal cooked for ten men by yourself                                        |
Before the player rolls, the game master will have set a target complexity for the given task.  Some example complexities and sample tasks are shown above.  Once the player has rolled their dice pool, they will be charged with building a set of groups from the values they roll.  Each group needs to be at least the target value to be counted towards the outcome.

So, for example, if your target value is 7 and you rolled 1,3,4,5,1, 7, 10, then you could build 4 groups, as in 10, 7, 5+1+1, 3+4.  Each of these groups pushes towards a desired outcome, typically either adding a wound to an enemy or adding a segment to a clock representing some more complicated task.

## Die Depletion
For each skill, stat, buff, relationship, item, or anything else that contributes to a die roll, we need to see if using it for this effort resulted in depleting it.  To deplete a die pool means to move it down one face size.

| Die Size | Depletes To |
| -------- | ----------- |
| d20      | d12         |
| d12      | d8          |
| d8       | d6          |
| d6       | d4          |
| d4       | Exhausted   |
A given stat, skill, or item depletes whenever a 1 is rolled anywhere in the pool unless using the pacing yourself mechanic described later in this section. When a consumable item is exhausted (a potion, a scroll, rations), it is destroyed.  When a durable item is exhausted, it is exhausted until it can be repaired or maintained.  Stats, skills, and relationships can similarly be rehabilitated by spending downtime, which we will discuss in the Downtime & Recovery sections.

## The Intermediate Big Example
1. Call the shot
	1. I'm going to attack the goblin with my sword
2. Set the target
	1. The goblin knows how to fight, but you're a skilled adventurer, 7 target.
	2. He is wearing armor, so you'll need at two raises to do real damage
3. Build your pool
	1. My zwei hander is a 2d6 weapon
	2. My zwei hander is a strength weapon, and my strength is 3d8
	3. My sword skill is 1d10
	4. I'm fighting to save my kid sister, which is a 4d6 relationship
	5. A mage gave me a spell of Guided Strike, adding 1d12 to my pool
	6. Therefore, my pool is 1d10 + 3d8 + 6d6 + 1d12
4. Roll the dice
	1. 1d10, sword skill - 1
	2. 3d8, strength stat - 5,7,8
	3. 2d6, zwei hander weapon - 5,3
	4. 4d6, sister relationship - 2,5,4,1
	5. 1d12, Guided Strike, 12
5. Build Groups
	1. 7, 5+2, 3+4, 5+1+1, 8, _5 + 1 which does not meet threshold_
	2. Count 7s, 5 successes
6. Compare to threshold
	1. 2 minimum to do damage, 3 beyond that
	2. You succeed, with three raises
7. Book keeping
	1. You rolled two ones, a d10 (your sword skill) and a d6 (your sister)
	2. The sword skill diminishes to a d8, you're getting desperate and sloppy as the fights progress.
	3. Your relationship with your sister decreases to a d4.  Motivation only goes so far.
	4. The Guided Strike spell depletes to a d10 worth of bonus. 

## Pacing Yourself
For any pool, when adding it to your roll, you may choose to add a subset of its dice to the pool.  For example, if your skill is 3d8, you may choose to roll only two d8.  For each dice set aside in this fashion, you may ignore a single '1' roll for purpose of step down.  So, in our example, if we had a skill of 3d8, and roll 2d8, getting a 1 and a 7, we do not step down the face value of our skill.  We would only step down the skill when rolling 1,1. 
* You may only pace yourself within a single skill, stat, or piece of equipment.  
* You may not pace yourself across skills, stats, or gear pieces
* You may not pace your use of consumables like potions or scrolls.

## Pushing Yourself
You may fix up to half your dice pool to its maximum value for any given roll.  For each die you fix in this way, you will step down a face value in the resolution step.  For example, if you have a pool of 4d8, you may choose to fix two dice as 8s and roll the remaining two, if the remaining two are:
* 6, 7 - you get a total roll of 6,7,8,8 and next time you roll this pool, you will roll d4s
* 1,4 - you get a total roll of 1,4,8,8 and the pool is depleted until replenished
* 1,1 - you get a total roll of 1,1,8,8 and the pool is depleted until replenished

* You may push yourself with stats or skills
* If you push a piece of equipment, the damage is permanent
	* For example, if you force a door with a sword, you will irrepairably harm the sword
	* Relying on the strength of the metal to block a blow rather than simply turning the blade harms the shield beyond repair
* You may not push yourself when using a consumable

## Botching and Building Momentum
Like many other tabletop systems, we incorporate the concept of exceptionally poor and exceptionally good rolls.

**Botched** A roll is botched when you fail to make any successful groupings and at least one skill, stat, or piece of equipment was deplinished.  In the event of a botch, the _player_ must take one additional cost from the roll, but it is the _player's_ choice which cost they incur:
* They may deplenish any piece of equipment used one (additional) step
* They may deplenish the skill used one (additional) step
* They may deplenish the stat used one (additional) step
* They may deplenish the relationship used one (additional) step.

**Building Momentum** 

When any character (yes, _even NPCs and GMPCs_) succeed at a task and build a group significantly larger than the target value, they generate _momentum_. Momentum acts as a buff but only lasts for the duration of the scene or fight.

Whenever a player makes a grouping that is larger than the target value by a certain amount, they generate a momentum die according to the following table:

| Exceeded Target By | Momentum Generated |
| ------------------ | ------------------ |
| 6                  | d4                 |
| 8                  | d6                 |
| 10                 | d8                 |
| 12                 | d10                |
| 20                 | d12*               |
*A d12 momentum die is extremely rare, usually the result of overwhelming strength or stacked buffs. It represents a truly heroic over-performance.

As an example, lets assume the party starts a brawl in a shady bar, and several hired thugs in the corner pull firearms.  The currently acting player decides they'll need cover, and tries to flip the nearest table: 
* The GM says this is a difficulty 9 task, needing 1 success.
* The player assembles their pool
	* Might (d10) based task to flip the table
	* Athletics (d6) because it's all about being strong
	* Finger-less (d4) Leather Gloves, wouldn't want to go to hell with a splinter in your hand
	* Liquid Courage (d4), the boys have been drinking, and this seems like a much better idea that diving for cover
* The player rolls well, getting an 8, 5, 4, and 3 respectively
* The player is now faced with a choice
	* group 8 + 3 and 5 + 4 for two successes
	* group 8 + 5 + 4 + 3 for 1 success, with 10 overkill, resulting in a d8 momentum die for the player during this combat scene.
Since flipping a table is a simple action, building momentum is likely more valuable than overachieving in the moment. In more complex scenes, such as combat or multi-step challenges,players may face real tension between immediate success and building long-term advantages within the scope of a scene.

Momentum die deplete like all other dice; when you roll a 1 on a momentum die, it steps down in face value.  If you roll a 1 on a d4 momentum die, you lose the momentum.

Momentum dice are also lost at the end of a scene or combat.  

## Boons and Banes
Boons and Banes, Advantages and Hinderances, Buffs and Debuffs, whatever you want to call them, they act like everything else in this system: More dice!

### Buffs
#TODO Commit to the name boon and bane throughout

A buff is added to the pool of dice to be rolled, and rolled as its own subgroup within the pool.  The buff dice act as any other dice in the pool.  They may be added to any other dice to form a group towards a target value.  If the buff is sufficiently strong, you can use buff dice exclusively to produce a group meeting the target value.

If any die in the buff rolls a 1, the buff is deplenished in the same way a stat would be.  If the base die size of the buff was a d8, and you rolled any 1s, next time you rolled relying on the buff you would be rolling d6s.  Once a buff is exhausted, it's gone, and comes off the character sheet.

If the source of the buff was an item that can regain charges, it can be replenished during long rests, as described in the **Long Rest** section.

### Debuffs
A debuff is added to the pool of dice to be rolled, and rolled as its own subgroup within the pool. Debuffs are not added to the players dice in order to form groups of the complexity value set by the DM.  Instead, each die acts as a new target group that the player must make from their dice.  Thus if the debuff is 3d6, and the player rolls them as 1, 2, and 3, the player must make one additional target group at 6 in order to succeed on their roll.

Additionally, debuffs deplete in the same was as other dice. If any die in the group comes up a 1, then the die size is reduced for the next roll.  In the above example, 3d6 would become 3d4 the next time the debuff was used in a roll.  Once a debuff is depeleted for d4 to exhausted, it comes off the player.

Debuffs are a great way to model magical debuffs, sprained ankles, your enemy deploying pocket sand, and all manner of transient issues that prevent a character from performing tasks.

Notes on debuffs:
These can really hinder a player, and you don't roll as many 1s as you might think.  At 3d6, you can expect the player to be debuffed through three checks.  At 2d6, it's closer to five checks.  That's a long time hindered!

## Contested Rolls
Sometimes it will make sense for their to be contested rolls.  These most frequently arise when some big bad has locked swords or wits with a player character.  While you _can_ resolve these situations using complexity and minimum success counts, contested rolls are another approach.

Contested rolls work by adding additional dice to the pool being rolled.  These contested dice can either _be overcome by player dice_, treating them as a temporary target group much like debuffs, or they _may be ignored by the player_ at the cost of suffering one depletion per unopposed contest dice, with the depletion being _the GM's choice_.

When using contested dice:
* Roll them alongside the original pool.  Either the player or the game master may roll them.
* Each die represents a target value that must be met or the consequence paid.
* If the GM rolls 1,3,5 on contested dice and the player rolls 2,4,2,5,5,7
	* The contested dice are cleared by a 2, a 4, and a 5, leaving 5 + 2, 7 
		* 2 groups
		* 0 depletions
	* 4 is used to clear 3, 1 and 5 are left uncontested, and the player groups 5+2, 5+2, 7
		* 3 groups
		* 2 depletions

Notes on Contested Rolls:
* They diminish the player's impact quickly
* Large dice value are swingy. A d20 is just as likely to roll a 1 as a 20.

Best Practices / Our Advice:
* Use these sparingly
	* The BBEG is a great place to bring in contested rolls
	* Environmental hazards that are swingy (icy floors, fluctuating energy field)
* Smaller dice are more reliable
	* 2d4 will always remove at least two dice, but is typically easier to overcome than 1d8

## Setting Difficulties
There are two levers the GM has when setting the difficulty for a roll.  They may set the **complexity of the task**, and they may set the **minimum number of groups**.  Task complexity represents exactly what it sounds like, how hard it is to do the thing.  Picking a simple lock is an easy task, say a target 7, but picking a lock designed by a master smith is much harder, likel a target 11.  Finally, picking a lock made by a long dead race with which the thief has no familiarity is an heroic feat, likely a target 13.

Minimum number of groups are useful when the task requires some degree of engagement to even begin with.  A simple lock that is just a padlock with a keyhole likely requires only one success group to move the needle (that is, there are 0 minimum groups).  However, a lock with multiple tumblers might require at least 1 group before we begin counting groups as successes.  A lock with two sets of tumblers in opposing directions might require 2.  Minimum number of groups is also useful for modeling striking highly armored targets.

Whenever using minimum number of groups ask yourself if you wouldn't be better served by a clock.  A clock persists across attempts and can be changed by multiple characters throughout a scene.  Minimum successes makes moving the needle on that clock harder, and are better for modeling tasks which require short-duration but high focus.

## Notes on Rolls

| Die Size | Expected Value | Rolls for 1 | Rolldown Duration |
| -------- | -------------- |------------ | ----------------- |
| d4       | 2.5            | 4           | 4                 |
| d6       | 3.5            | 6           | 10                |
| d8       | 4.5            | 8           | 18                |
| d10      | 5.5            | 10          | 28                |
| d12      | 6.5            | 12          | 40                |
## Resolution Summary (Quick Reference)

1. **Set Target**: GM defines complexity (5–13) and raises required.
2. **Build Pool**: One stat, one skill, one item, one relationship, plus bonuses.
3. **Roll Dice**: All at once.
4. **Build Groups**: Form totals meeting or exceeding target value.
5. **Count Raises**: Each group = one raise.
6. **Apply Outcome**: Meet or exceed raise requirement.
7. **Resolve Depletion**: Step down die pools if needed.

# Stats

* Characters have six stats:
	* Might - how much you can lift, how hard you punch
	* Finesse - How's your balance? Fine motor skills?
	* Grit - Can you shake off a punch? Hold your liquor?
	* Intellect - Are you book smart?
	* Wits - What about street smart, or wise to the world?
	* Presence - How are you with people?
* There are no derived stats.
* There are no hit points.
* There are no magic points or mind points or mana

Each stat is represented by a die size and count.  If you're really strong, but don't have much staying power, you might have 4d4 might.  If you're medium smart, and really good at staying focused, you might have 1d12 intellect.

| Stat      | # of Dice | Max Face | Current Face |
| --------- | --------- | -------- | ------------ |
| Might     | 2         | d4       | exhausted    |
| Finesse   | 2         | d6       | d4           |
| Grit      | 1         | d4       | d4           |
| Intellect | 3         | d8       | d6           |
| Wits      | 3         | d8       | d6           |
| Presence  | 2         | d6       | d4           |
The above is a sample statblock for a wizard character.  They're a bit of a glass canon: they're weak, they can't take a hit, but they do have a little grace (probably from all that delicate hand motion).  Intellectually though, they're a powerhouse, rolling large quantities of dice for any task requiring intellect, wits, or presence.

However, you see in the third column, they aren't current at the top of their game.  Whether by direct damage or exertion, some of their stats have been _depleted_.  Might started off as rolling 2d4, but something happened, and now the character has exhausted their might.  _This means that when rolling a test that relies on might, they add no dice to their pool._ We'll talk about tests at length in a bit.

Exhaustion isn't the first step though.  Our wizard has also depleated their finesse pool.  Maybe an orc managed to catch their hand with a club, making all of those fancy somatic portions of a spell hard to pull off with one shattered wrist.  They aren't down and out yet though, after all, they have two hands.  Instead of rolling 2d6 when using their finesse to a test, they roll 2d4.  If they deplete their finesse again _then_ it will be exhausted.

## Getting Conked Out
Whenever you lift a log, kick a puppy, or get smacked with a sword by its owner, you'll run the risk of depleting your stat dice.  Here are the situations where that might happen:

* Any time you roll a 1 on a stat die, you may reduce the face size, from a 12 to a 10, a 10 to an 8, an 8 to a 6, a 6 to a 4.  If you roll a 1 on a d4 and the die is diminished, that stat pool is _exhausted_.
* Whenever you're hit, by an attack, by a spell, by the environment, you'll be struck with a defecit of successes (we'll talk about rolls next).  Each point of deficit reduces a die by one step.  So if you have a 3 step deficit on a d10 stat, it goes from a d10 to a d4.
	* You can't overflow damage in this way.  If you take 3 points of deficit on a d4, d6, or d8 stat, each will be exhausted, but no other stat is changed.

Since you don't have hitpoints in this system, depleted stat dice are how we determine if you're KOed.  Here's how that works:
* Every time a stat is exhausted, your character is hindered
	* When no pools are exhausted you're hale.
	* When one pool is exhausted, you are hindered by 1d4 per roll
	* When two pools are exhausted, you are hindered by 2d6 per roll
	* When three pools are exhausted, you are hindered by 3d8 per roll
	* Beyond 3 pools, your character loses conciousness

Treat these hinderences as contested roll dice, described in the "Contested rolls" section.
# Combat
## Martial Combat
### Determining Initiative
* Initiative is rolled per combatant
* Enemies have a fixed die pool
* DMPCs roll as characters
* Characters may roll
	* Wits or finesse for the stat
	* Any combat skill (including magic skills like 'casting' or 'psionics')
	* Any item meant to alert the group (e.g. air horns, signal whistles, flares)
	* Any buff affecting alertness or character speed
* Target complexity is 7 for both groups
* Any combatant failing to make any groups loses their action this round
* Initiative score is the number of successfully made groups
* In any subsequent round, a character may choose to reroll their initiative check to change their order
	* This does not consume their action, unless they get 0 successes, in which case they do not go this turn
* In any round, a character may delay their action, chosing to go after any specific character in the rotation order.  This alters their initiative to the 'chosen' value  on subsequent rounds.
* Initiative rolls deplenish skills, stats, and items as all other rolls.

### Action Economy

* Every combatant gets one major action per round, unless they have a trait, magical item, buff, etc that explicitly grants them an extra major action.  Major actions include
	* Attacking an enemy combatant
	* Throwing a grenade
	* Casting a spell
	* A complicated piloting maneuver (e.g. driving on a windy road)
	* Intimidating someone to get them to lay down their weapons
* Every combatant gets one minor action per round, unless they have a trait, magical item, buff, etc that explicitly grants them an extra minor action. Minor actions include
	* Moving finesse die size * 5 meters (e.g. 20 meters for a d4 finesse, 30 for a d6)
		* If a character's finesse is depleted, they may move 5 meters.
	* Opening an unlocked door
	* Throwing the switch, Igor!
	* Readying a weapon
	* Handing someone a potion
* All actions by a character are taken at the same time.
* Each character may take their major and their minor action in any order
* Each character may take two minor actions in lieu of a major action
* Minor actions should never require a roll
* Minor actions should never directly impact a clock
* Major actions should always require a roll

### Killin Monsters
Opponents come in two varieties, a **simplified stat block** and a **fully statted GMPC**.
A fully statted character piloted by the GM behaves according to the same rules as characters, for being KOed and for all other checks.

#### Simplified Stat Block Characters
A simplified stat block character has:
* An initiative pool.
* A to hit complexity class & minimum success
	* They may have several of these to represent different types of attack, e.g. claws and a breath weapon.
* A to defend complexity class & minimum success
	* If a character fails to get the minimum successes when defending against a monster attack, they take up to the minimum success number of depletions to the rolled stat.
* A number of wounds that they can take before defeat (typically 1-4)
	* Each success group (above the minimum) on an attack inflicts a wound

#### Fully Statted Enemies
A fully stated oponent is built in exactly the same way that any player character is built.

- All sources of damage will specify targets
	- Pools should prefer general to specific, to preserve player options
		- Equipment over "Breastplate" or "Shield"
		- Physical over Grit or Finesse
		- Mental over Will or Intellect
	- Sometimes it makes sense to specify a singular target
		- A "harm health" spell is going to target grit directly
		- A "dull blades" spell is going to target "swords, daggers, axes" or "bladed weapons"
- Preserve player choice where possible
	- When the player strikes an enemy, they get to choose which of the applicable pools are harmed
	- When an enemy strikes the player, the player gets to choose which pools are harmed.
- "Damage dealt" is always determined by the number of success groups on the roll
	- It is always the total number of successes on the roll
		- There are no "minimum successes" in opposed rolls
		- Minimum successes are meant as abstractions to simplify the opposition rolls
	- So, if you form 3 success groups on a damage check targeting "Armor, physical" you may step down three dice related to armor or physical damage
- All combat rolls between a player character and a fully statted opponent must be contested rolls
	- The aggressor rolls their combat roll, including
		- Relevant stat
		- Relevant skill
		- Relevant item or ability
		- Any relevant buffs and debuffs
	- The Defender rolls their defense roll, including
		- Relevant defense stat (finesse to dodge, grit to shake off, will for spell resistance)
		- Relevant defense stat
		- Relevant armor or gear
		- Any relevant buffs and debuffs
	- Depletion happens as normal on both sides of the roll.  
	- A defender may opt to forgo their defense roll
	- Any successes the aggressor gets over the defender may be applied to any dice the defender rolled (to reduce the die size by 1 face type), or any category listed as the weapon or ability damage
	- Any successes the defender gets over the aggressor may be applied to any dice the aggressor rolled in the attack.
		- The defender's target value is the same as the aggressors.
		- A defender's die is only useful for grouping in this way if there are no dice the attacker has to overcome it (e.g. it is higher than all other unassigned attacker dice)

## Social Combat

Occaisionally, you may find yourself in a position where your characters need to use their words, rather than their fists, to effect the desired outcome.  There are two ways this can be modeled: a single check (via raw presence, intimidation, persuasion, and so on), or a longer social conflict with turns and clocks as described in the rest of this section.

Before moving on, we should reiterate that there's nothing wrong with a simple single roll social check.  They're good for all sorts of situations: quick negotiations, bluffing your way past gaurds, haggling for the price of goods with a merchant.  The social combat rules here should be used only when the negotiation in question is painfully relevant to the plot and you want to model the back and forth nature of arguments inside of the game to build tension.

### Summary of Approach
* The GM sets a tug-of-war clock between all parties desired outcomes
* The GM sets a duration for the conflict in terms of number of turns
* The GM sets a initial disposition for the argument
* The GM should communicate the duration, initial disposition, and possible outcomes of the argument to players.
* Each party nominates a subset of the group to speak
* The GM sets speaker order per turn
	* manually if it is obvious
	* via martial combat initiative rules if not
* Every round, every social combatant speaks
* Each time speaking, the speaker may
	* Present Evidence
	* Make an argument
	* Refute an argument
	* Bolster an argument
* At the end of social combat, the GM looks at the arguments left on the board
	* The GM sums up the total arguments for and against each position
	* The totals are compared against the tug of war clock to determine the final resolution of the social combat

### Components of a Social Combat Roll

Social combat checks are slightly different than skill checks from before.  Each check either:
* Introduces a new argument
* Bolsters an existing argument
* Detracts from an existing argument

The pool is still built in pieces:
* A **stat**, must be one of intellect, wits, or presence
* A **skill**, likely speech, persuasion, intimidation, law, etc.
* A **relationship**, with the party being argued with or a motivation to seek an outcome
* **Evidence**, artifacts, witnesses, contemporaneous notes that reinforce the point the character is making.

Unlike other rolls, social combat rolls may rely on one or more pieces of evidence.  Each roll **may only introduce one piece of evidence**, but once evidence is in the battlefield, it must be used in any subsequent roll for which it is relevant.  If the evidence reinforces your point, it acts as a buff (which cannot deplete).  If the evidence refutes or detracts from your point, it acts as a debuff (which does not deplete).

Once the pool is constructed, social rolls proceed as all other rolls.  A target complexity is set, along with minimum successes, and the player rolls 'dem bones.

### The Player Makes an Argument
When making an argument the player:

* States the nature of the argument they want to make:
	* "I couldn't have been there, I was off seducing your mother last night."
* States the evidence that they intend to introduce:
	* Evidence has quality or believability
		* "Here's your mother, who will affirm this is true" is likely 2d8
		* "Here is a letter from your mother, thanking me for a night of passion" is less, maybe 2d6 or 2d4 depending on how believable the letter is
	* The GM ultimately adjucates the die size of the evidence
* States the skill to be used
* States the relationship to be used

The GM sets a target complexity and minimum number of groups for the argument being made.  Complexity score should literally reflect complexity -- how nuanced is the argument being made?

Minimum groups should start at 1 and increase if:

* There are arguments counter to this one already in play
* The argument is particularly offensive to one or more of the parties

The player then rolls. 

Independent of success, the evidence enters into the social battlefield and must be dealt with by all parties in subsequent rolls.

If the player succeeds, the argument enters the field with a strength equal to the number of groups above the minimum made by the roll.

### The Player Refutes an Argument Being Made
This is done as a defensive roll, with the players having a chance to refute the argument as it is being made.  The gm:

* States the nature of the argument
* States what evidence, if any, is being introduced as part of the argument
* Sets a complexity and minimum number of successes to defend
	* the minum number of successes is the maximum strengh of the argument on the field
	* Complexity should reflect how hard it is to argue against the argument being submitted
* The player rolls to defend against the argument.
	* This roll is the same as all other social combat rolls
	* This includes the ability to submit one new piece of evidence in defense
	* If the defense is successful
		* the argument is refuted before it enters the field
		* The _player_ chooses wheter or not GM submitted evidence enters the field
		* The player's new evidence (if any) enters the field
	* If the defense fails
		* the argument enters the field with strength equal to the number of additional groupings the player would have needed to make to sucessfully defend.
		* _The GMs_ evidence, if any, automatically enters the field
		* The _GM_ decides if the player's evidence, if any, enters the field.

### Notes on Evidence
* Evidence typically accumulates throughout the course of the argument.
* Conflicting evidence can be left in play if the players and GM so desire
* Alternatively, the players and GM can opt to 'resolve' any group of conflicting evidence
* Resolution happens by comparing first face sizes, then die counts
	* If faces do not match, both die faces are reduced by one until the lesser piece of evidence is exhausted.
	* If faces do match but dice count does not, reduce dice count by one until the lesser piece of evidence is exhausted.
	* Some Examples:
		* A - 3d6 and B - 3d4 reduces to A - 3d4
		* A - 3d6 and B - 2d6 reduces to A - 1d6
		* A - 3d4 and B - 3d4 reduces to no evidence

Add back into main summary document when you fix the repo state tomorrow

## Magic

### Casting Stats and Skills

Magic in this system follows the same core mechanics as all other actions, with some specific structures for how casters build their pools.

#### Casting Stats

When casting a spell, the caster uses stat depending on the nature of the magic:

- **Intellect** - for studied, formulaic magic requiring precise understanding
- **Wits** - for intuitive, instinctive magic or split-second improvisation
- **Presence** - for magic drawn from force of will or channeling external powers
- **Grit** - for blood magic drawn from the caster's life force

#### Casting Skills

Casting skills represent training in specific magical traditions or schools. The granularity depends on the setting and genre conventions:

* ***Simple Setting:**
	- Magic (covers all spellcasting)
* ***Moderate Complexity:**
	- Arcane (wizardry, learned magic)
	- Divine (clerical magic, granted by deities)
	- Primal (druidic, nature magic)
	- Psionic (mental powers)
* ***High Complexity:**
	- Evocation (destructive energy)
	- Abjuration (protective magic)
	- Illusion (deception and glamours)
	- Necromancy (death and undeath)
	- etc.

Like all skills, casting skills deplete when you roll a 1, making sustained magical combat taxing.

#### Casting Pool Construction

When casting a spell, build your pool as normal:

- One **casting stat** (Intellect, Wits, or Presence)
- One **casting skill** (matching the spell's school)
- Up to one **implement or component** (staff, wand, material components)
- Up to one **relationship** (to a deity, mentor, familiar, etc.)
- Any relevant **buffs** (blessings, magical enhancements, prepared rituals)

### Spell Structure

Each spell has the following attributes:

* **Complexity:** The target number for forming groups (typically 7-13) 
* **Minimum Groups:** How many groups must be formed before the spell takes effect (typically 1-2) 
* **Range:** How far the spell can reach (Touch, 20m, 40m, Line of Sight, etc.) 
* **Casting Stat:** Which stat(s) can be used (Int, Wits, Presence) 
* **Casting Skill:** Which skill(s) apply (Arcane, Evocation, etc.)
* **Effect Scaling:** What happens based on groups above the minimum:
	- 0 groups above minimum: Baseline effect
	- 1-5+ groups above minimum: Progressively stronger effects

### Spell Examples

#### Template
|                    |     |
| ------------------ | --- |
| Complexity         |     |
| Minimum Groups     |     |
| Range              |     |
| Casting Stat       |     |
| Casting Skill      |     |
| 0 Groups Above Min |     |
| 1 Group Above Min  |     |
| 2 Groups Above Min |     |
| 3 Groups Above Min |     |
| 4 Groups Above Min |     |
| 5 Groups Above Min |     |

#### Magic Missile

|                    |                                        |
| ------------------ | --- |
| Complexity         | 7                                      |
| Minimum Groups     | 1                                      |
| Range              | 40m                                    |
| Casting Stat       | Intellect or Wits                      |
| Casting Skill      | Arcane                                 |
| 0 Groups Above Min | 1 depletion, target's choice           |
| 1 Group Above Min  | 2 depletions, target's choice          |
| 2 Groups Above Min | 3 depletions starting with Finesse     |
| 3 Groups Above Min | 4 depletions, caster's choice          |
| 4 Groups Above Min | 5 depletions, caster's choice          |
| 5 Groups Above Min | 6 depletions, add "Stunned" 1d6 debuff |

#### Flame Gout

|                    |                                                             |
| ------------------ | ----------------------------------------------------------- |
| Complexity         | 9                                                           |
| Minimum Groups     | 2                                                           |
| Range              | 20m                                                         |
| Casting Stat       | Intellect or Presence                                       |
| Casting Skill      | Evocation                                                   |
| 0 Groups Above Min | 1 depletion to target's choice of physical stats/armor      |
| 1 Group Above Min  | 2 depletions to target                                      |
| 2 Groups Above Min | 2 depletions to target + 1 depletion to one adjacent target |
| 3 Groups Above Min | As above + "On Fire" 1d4 debuff to all affected targets     |
| 4 Groups Above Min | As above + debuff increases to 2d6                          |
| 5 Groups Above Min | As above + debuff increases to 2d8                          |

**Notes:** Area effect improves with success. The "On Fire" debuff depletes normally over subsequent rounds.

#### Chain Lightning

|                    |                                                             |
| ------------------ | ----------------------------------------------------------- |
| Complexity         | 9                                                           |
| Minimum Groups     | 2                                                           |
| Range              | 30m                                                         |
| Casting Stat       | Intellect or Presence                                       |
| Casting Skill      | Evocation                                                   |
| 0 Groups Above Min | 2 depletions to primary target                              |
| 1 Group Above Min  | As above + chain to 1 adjacent enemy (1 depletion)          |
| 2 Groups Above Min | As above + chain to 2 additional enemies (1 depletion each) |
| 3 Groups Above Min | As above + primary target takes 3 depletions                |
| 4 Groups Above Min | As above + all chained targets take 2 depletions            |
| 5 Groups Above Min | As above + "Paralyzed" 1d4 debuff to primary target         |

**Notes:** Rewards clustered enemies. Positioning matters. Lightning chains to closest adjacent enemies first.

#### Shield

|                    |                                                                       |
| ------------------ | --------------------------------------------------------------------- |
| Complexity         | 7                                                                     |
| Minimum Groups     | 1                                                                     |
| Range              | Self or Touch                                                         |
| Casting Stat       | Intellect                                                             |
| Casting Skill      | Abjuration                                                            |
| 0 Groups Above Min | Add 1d6 buff to defense rolls for this scene                          |
| 1 Group Above Min  | Buff increases to 2d6                                                 |
| 2 Groups Above Min | Buff increases to 2d8                                                 |
| 3 Groups Above Min | Buff increases to 3d8                                                 |
| 4 Groups Above Min | As above + reflect 1 depletion back to attacker on successful defense |
| 5 Groups Above Min | As above + buff becomes 3d10                                          |

**Notes:** Buff depletes normally when rolling 1s. Higher initial investment creates longer-lasting protection. Lost at end of scene if not depleted.

#### Teleport

|                    |                                                               |
| ------------------ | ------------------------------------------------------------- |
| Complexity         | 11                                                            |
| Minimum Groups     | 3                                                             |
| Range              | Line of Sight (self and touched allies)                       |
| Casting Stat       | Intellect or Wits                                             |
| Casting Skill      | Arcane                                                        |
| 0 Groups Above Min | Teleport self up to 30m to visible location                   |
| 1 Group Above Min  | As above, range increases to 60m                              |
| 2 Groups Above Min | As above + may bring one touched ally                         |
| 3 Groups Above Min | As above + may bring two touched allies                       |
| 4 Groups Above Min | As above + teleport to memorized location (not line of sight) |
| 5 Groups Above Min | As above + may bring three touched allies                     |

**Notes:** High complexity reflects difficulty. Minimum 2 groups makes this unreliable under pressure. Excellent utility, poor combat reliability.

### Spell Acquisition

Spells are learned through study from tomes, possibly alongside instruction from teachers. Learning a spell is modeled as filling a clock through successful study sessions.

#### Learning Clocks

The complexity of the spell determines the clock size:

| Spell Complexity | Clock Segments |
| ---------------- | -------------- |
| 7 (Simple)       | 3 segments     |
| 9 (Moderate)     | 5 segments     |
| 11 (Hard)        | 7 segments     |
| 13 (Heroic)      | 10 segments    |

#### Study Sessions

Each study session is a skill check using:

- **Stat:** Intellect or Wits
- **Skill:** The casting skill the spell uses (Evocation for Fireball, etc.)
- **Equipment:** The tome or teaching materials
- **Relationship:** With a teacher (if learning from one)
- **Target Complexity:** The spell's casting complexity (modified by method)
- **Minimum Groups:** Usually 0, but 1+ for advanced or secret spells

Each group formed above the minimum advances the clock by 1 segment. When the clock fills, the spell is learned at 1d4 proficiency for that spell's complexity and minimum groups.

Study sessions can be attempted once per long rest and represent a full day of dedicated work.

##### Method 1: Self-Study from Tome

**Tome as Equipment:** Tomes are treated as equipment for the purpose of the study roll:

|Tome Quality|Dice|Typical Cost|
|---|---|---|
|Common Spellbook|1d6|50-100g|
|Well-Written Grimoire|2d6|500-1000g|
|Master's Notes|2d8|2000-5000g|
|Ancient Artifact|3d8|Quest reward|

- Tomes deplete on 1s (pages damaged, ink fades, binding weakens)
- When tome is exhausted, it cannot be used for study until repaired
- No relationship dice available
- Ancient tomes may increase complexity by +2 due to archaic language

##### Method 2: Teacher-Guided Study

**Teacher as Relationship:** Teachers provide relationship dice for study rolls:

|Teacher Level|Relationship|Cost per Session|
|---|---|---|
|Hedge Wizard|1d6|10g|
|Guild Instructor|2d8|50g|
|Archmage Mentor|3d10|200g+|

- Reduces spell complexity by 2 (teacher explains difficult concepts)
- Teacher relatioship may be delpeted intsead of tome
	- Relationships only take time to heal in most situations
	- Thus, this is 'cheaper' and 'safer' for rare tomes
- May require additional costs: favors, membership dues, quests
- May provide additional reward by deepening relationship with teacher
- Teachers may only be available at specific times or locations

##### Failed Study Sessions

- **Failed Session (0 groups, no depletion):** 
	- Clock doesn't advance
	- No depletions 
	- Gain momentum for next study session
		- if you had no momentum, go from 0 to 1d4
		- If you had 1d4 momentum, go to 1d6
		- 1d6 -> 1d8, and so on
- **Botched Study (0 groups + depletion):**
	- Clock doesn't advance
	- Tome is slightly damaged or relationship with teacher is strained
		- Either counts as 1 depletion of the relevant asset
	- And One of
	    - You have to take a day break to recompose yourself due to frustration
	    - Tome or teacher takes additional depletion step
	    - Minor miscast causes accident (GM's discretion)

##### Example: Learning Fireball

###### Scenario: Poor Wizard Self-Studies

* Spell Learning Description
	- Spell: Fireball (Complexity 9, 5-segment clock)
	- Pool: 3d8 Intellect + 1d6 Evocation + 2d6 Tome = 3d8 + 3d6
	- Cost: 500g for tome, multiple days
* Session 1
	- Rolls: 7,6,2 (Int) + 5,3,1 (Evocation + Tome)
	- Forms groups: 7, 6+3, 5+2+2 = 3 groups
	- Clock advances 3 segments (3/5 complete)
	- Evocation depletes to 1d4
- Session 2
	- Pool now: 3d8 Int + 1d4 Evocation + 2d6 Tome
	- Rolls: 8,7,1 (Int) + 3 (Evocation) + 2,1 (Tome)
	- Forms groups: 8+1, 7+3 = 2 groups
	- Clock advances 2 segments (5/5 COMPLETE!)
	- Learns Fireball with Complexity 9, Minimum Groups 1
	- Intellect depletes to 3d6, Tome to 2d4

###### Scenario: Wealthy Wizard Studies with Archmage

* Spell Learning Description
	- Spell: Fireball (Complexity 9 → 7 with teacher, 5-segment clock)
	- Pool: 3d8 Int + 1d6 Evocation + 2d6 tome + 3d10 Mentor = 3d8 + 3d6 + 3d10
	- Cost: 200g per session, potential favor owed
- Session 1
	- Rolls: 8,6,5 (Int) + 4 (Evocation) + 2,4 (Tome) + 10,9,7 (Mentor)
	- Forms groups: 10, 9, 8, 7, 6+4 = 5 groups
	- Clock fills immediately (5/5 COMPLETE!)
	- Learns Fireball with Complexity 9, Minimum Groups 1
	- No depletion (no 1s rolled)

#### Improving Spell Mastery

Once learned, spells start with their base complexity and minimum groups. Through repeated practice in dangerous situations, casters reduce these values, making spells easier and more reliable to cast.

##### Practice Advancement
* Track successful casts in dangerous or stressful situations
	* Things that Count
		* Casting in Combat
		* Casting as part of a test or competition
		* Creating Wine for a foreign dignitary
		* Casting a spell to prove your worth to spare yourself from execution
		* Willing a flower into being to woo the queen so she will release your friend from jail
	* Things that Don't
		* Practice casting during downtime does not count
		* Lighting a fire at camp, creating water or food with no time pressure
		* Willing a flower into being to woo a pretty lady
* Milestones start at 10 casts and double every time
	* So 10, 20, 40, 80, 160, etc.
	* Each passed milestone may either
		* Reduce Complexity by 2
		* Reduce minimum groups by 1
	* You can't make a spell completely trivial to cast this way
		* Complexity can never be less than 1
		* Minimum groups can never be less than 1
		* Thus you must always roll at least one die to cast a spell

##### Example Progression

* ***Fireball - Novice Caster**
	- Complexity: 9
	- Minimum Groups: 1
* ***Fireball - Practiced Caster (10 casts)**
	- Complexity: 7
	- Minimum Groups: 1
* ***Fireball - Master Caster (20 casts)**
	- Complexity: 5
	- Minimum Groups: 1

##### Notes on Mastery

- Your casting **skill** determines your die pool (improves with XP)
- Spell **mastery** determines how reliably you cast specific spells
- A master with depleted casting skills can still cast signature spells more easily than a novice at full strength
- This reflects muscle memory and deep familiarity with specific magical formulae
- A prodigy can cast spells well beyond their mastery with a little luck
- Different casters can have different mastery levels for the same spell

### Spell Customization

The spell list provides templates. GMs and players can create variations:

- **Elemental variants:** Ice Storm uses same template as Flame Gout with cold damage
- **Range adjustments:** Increase complexity by 2 for double range
- **Creative applications:** Using Magic Missile to trigger traps from safety may increase complexity at GM's discretion

Spell effects should always use the existing mechanical framework: depletions to pools, debuffs, buffs, and contested rolls. Avoid creating special-case mechanics.

### Channeled Spells

Some powerful spells require sustained focus over multiple rounds, making them vulnerable to disruption but offering tremendous effects when completed.

#### Channeled Spell Attributes

In addition to standard spell attributes, channeled spells have:

- **Channeling Clock:** How many segments must be filled before the spell completes
- **Interrupt Difficulty:** The contested dice rolled when someone attempts to disrupt the spell

#### Channeling Mechanics

##### Initiation (Starting Round)
- Caster announces channeled spell and begins casting
	- Part of announcing the spell is setting the desired clock size in segments
	- The clock must be at least the minimum clock size for the channeled spell
	- It cannot be larger that the described ceiling of spell effects
- Uses major action
- Rolls normally: Stat + Skill + Implements + Relationship + Buffs
- Each group above minimum adds 1 segment to the channeling clock
- Depletion occurs as normal

##### Continuation (Subsequent Rounds)
- Caster uses major action to continue channeling
- Rolls again with same pool (affected by any depletion from previous rounds)
- Each group above minimum adds segments to the clock
- Continues until clock fills or spell is interrupted
- Caster may move using minor action but cannot take other major actions

##### Interruption
- Any time caster takes damage, forced movement, or is targeted by an interrupt action
- Roll the interrupt difficulty die as a contested dice for each group above minimum the adversary got
- Caster must overcome these contested dice or allow them to deplete pools
- If caster chooses to allow depletion from uncontested dice, the spell is interrupted
- On interruption
	- channeling clock resets
	- spell effect lost
	- Caster receives a debuff based on filled segments
		- Filled 3 or fewer segments - no debuff
		- Filled 4-5 segments --> 1d4
		- Filled 6-7 segments --> 1d6
		- Filled 7-8 segments --> 1d8
		- Filled 9-12 segments --> 1d12
		- Filled 13+ segments --> 1d20

##### Completion (Final Round)
- When clock fills, spell resolves immediately
- Effect determined by total segments accumulated in the clock

#### Interrupting Channeled Spells

On their turn, any combatant can use their major action to attempt to interrupt a channeled spell using the following methods:
- **Direct Attack**
    - Make a normal attack roll against the channeling caster
    - If any depletions would be dealt, the caster must make an interrupt check
    - Add the interrupt difficulty dice as contested dice to the caster's defense
- **Counterspell**
    - Enemy caster makes their own casting roll
    - Complexity determined by counterspell template and caster's practice
- **Forced Movement**
    - Shove, grapple, pull, or otherwise move the caster
    - If successful, caster must make interrupt check as described above
- **Environmental Disruption**
    - Create hazards that force the caster to move or take damage
    - If caster takes any action other than channeling or takes damage, triggers interrupt check

#### Channeled Spell Templates
##### Meteor Swarm

|                      |                                                                              |
| -------------------- | ---------------------------------------------------------------------------- |
| Complexity           | 11                                                                           |
| Minimum Groups       | 2                                                                            |
| Channeling Clock     | 8 segments                                                                   |
| Range                | 100m                                                                         |
| Casting Stat         | Intellect or Presence                                                        |
| Casting Skill        | Evocation                                                                    |
| Interrupt Difficulty | d6                                                                           |
| 8 Segments           | 4 depletions to all enemies in 30m radius                                    |
| 10 Segments          | 5 depletions + 2d6 "Burning" debuff to all targets                           |
| 12 Segments          | 6 depletions + 2d8 "Burning" debuff + difficult terrain created              |
| 14 Segments          | 7 depletions + 3d8 "Burning" + difficult terrain + 2 depletions to all armor |
| 16 Segments          | 8 depletions + 3d10 "Burning" + terrain destroyed + ongoing fire hazard      |

**Notes:** Requires minimum 2-3 rounds to cast. Extremely vulnerable to interruption. Party must protect caster. Devastating area effect when successful.

##### Mass Heal

|                      |                                                                        |
| -------------------- | ---------------------------------------------------------------------- |
| Complexity           | 9                                                                      |
| Minimum Groups       | 1                                                                      |
| Channeling Clock     | 6 segments                                                             |
| Range                | 20m radius centered on caster                                          |
| Casting Stat         | Presence                                                               |
| Casting Skill        | Divine                                                                 |
| Interrupt Difficulty | 2d4                                                                    |
| 6 Segments           | Restore 1 die step to one stat for all allies in range                 |
| 8 Segments           | Restore 2 die steps to one stat for each ally                          |
| 10 Segments          | Restore 3 die steps to one stat OR 1 step to three stats for each ally |
| 12 Segments          | Restore one depleted stat pool completely for all allies               |
| 14 Segments          | As above + remove all debuffs from all allies                          |

**Notes:** Easier to channel than offensive magic due to lower interrupt difficulty. Battlefield positioning crucial - caster must remain within range of injured allies throughout channeling.

##### Summoning Circle

|                      |                                                                              |
| -------------------- | ---------------------------------------------------------------------------- |
| Complexity           | 13                                                                           |
| Minimum Groups       | 3                                                                            |
| Channeling Clock     | 12 segments                                                                  |
| Range                | 10m                                                                          |
| Casting Stat         | Intellect or Wits                                                            |
| Casting Skill        | Arcane                                                                       |
| Interrupt Difficulty | 3d6                                                                          |
| 12 Segments          | Summon minor creature (simplified stat block, 2 wounds, one attack type)     |
| 14 Segments          | Summon moderate creature (simplified stat block, 4 wounds, two attack types) |
| 16 Segments          | Summon major creature (simplified stat block, 6 wounds, special ability)     |
| 18 Segments          | Summon elite creature (fully statted GMPC with standard stats)               |
| 20 Segments          | Summon legendary creature (fully statted GMPC with enhanced stats)           |

**Notes:** Extremely difficult and time-consuming. Very high interrupt difficulty reflects the complexity of maintaining an otherworldly connection. Summoned creature persists for the duration of the scene. The creature acts on the caster's initiative but requires no action from the caster to command.

##### Wall of Force

|                      |                                                                                                      |
| -------------------- | ---------------------------------------------------------------------------------------------------- |
| Complexity           | 9                                                                                                    |
| Minimum Groups       | 1                                                                                                    |
| Channeling Clock     | 5 segments                                                                                           |
| Range                | 40m                                                                                                  |
| Casting Stat         | Intellect                                                                                            |
| Casting Skill        | Abjuration                                                                                           |
| Interrupt Difficulty | 2d4                                                                                                  |
| 5 Segments           | Create 10m long, 3m tall barrier of force. Blocks physical passage and ranged attacks.               |
| 7 Segments           | Increase to 20m long, 5m tall                                                                        |
| 9 Segments           | As above + barrier has 1d8 "structural integrity" that must be depleted to break through             |
| 11 Segments          | 30m long, 5m tall, 2d8 structural integrity                                                          |
| 13 Segments          | 40m long, 10m tall, 3d8 structural integrity + reflects one ranged attack per round back at attacker |

**Notes:** Barrier persists for the scene or until destroyed. Can be shaped as straight wall, curve, or dome (enclosing area reduces effective length by half). Useful for controlling battlefield and protecting allies.

# Rest and Replenishment
* #TODO Resting in secure situations needs some notes
	* Camp preparation is skipped
* #TODO We need something to deal with _half rations_ style situations

Groups of characters can expect two short rests and one long rest per day.  A short rest represents, well, a short rest, say a 10-15 minute breather on a several mile hike.  A long rest happens once a day, typically at night, when making camp or returning to their safe house after a score.

## A Short Rest
A short rest allows a player to replenish any one of their die pools completely, or increase any two die pools by a single step (unless that character has a feature that improves the effectiveness of rest).

For example, if a player has delpeted their sword skill from a d12 to a d4, and depleted their sneaking skill from a d6 to a d4, they may choose to either:
* Replensih their sword skill to a d12, but leave their sneaking skill at a d4
* Replenish their sword skill to a d6, and replenish their sneaking skill to a d6

## A Long Rest
A **Long Rest** represents the party’s full downtime between major exertions: a night’s sleep at camp, a return to a hideout, or quiet hours after a dangerous mission. Long Rests restore resources and offer moments of character interaction and choice.

A Long Rest is broken into **four scenes**, each inviting a spotlight or mechanical effect:

### Camp Preparation

Who sets up the fire? Who tends to wounds? Who scouts the perimeter? Who feeds the horses?

**Each character chooses one:**

- **Repair** one piece of gear (restore a depleted item die)
- **Ply their trade** Restore a depleted stat or skill die, or move one tick up on each of skill and stat die (must be relevant to making camp)
	- A fighter might chop wood with an axe
		- This could loosen their muscles (complete replenishment of might die)
		- It could hone their ability with their battle axe (complete replenishment of axe fighting)
		- It could help both a little (one step up on each of axe and might dies)
- **Scout Ahead** to gain assets when traveling overland and avoiding ambush
- **Aid Another** grant someone else an extra heal or repair benefit
- **Rest** If unconscious, a player may not help set up camp, and instead recover up to two steps in across any completely depleted stat pools.
- In a secure location that is
	- Owned by the characters
		- "camp preparation" can mean stronghold maintenance
	- Not Owned by the players
		- unchanged from above.  Actions still need to narratively make sense

### The Meal

Food is a mechanical resource. Meals consumed here trigger recovery.

- If the party **eats rations or fresh food**, all characters:
    - Replenish stats or skills
	    - either one stat completely
	    - or one skill completely 
	    - or any combination of two stats or skills by one step
    - AND Replenish relationships
	    - either any one relationship with a person who is present completely
	    - or any one relationship with a person who is absent one step
	    - or any two relationships with people who are present each one step
- If **no food is eaten**, only the social benefits of "The Meal" step are gained.

### A Quiet Moment

Every character gets one scene or reflection, solo or with another character.

- A conversation with another present character
	- Either Replenishes **a relationship** die pool completely
	- Or establishing a new relationship at 1d4
- Reflect on someone far away (a friend, the king who sent them on the mission, etc)
	- Replenishes a relationship die pool by one step for someone who isn't here
- Rest or Meditate or Stretch or Practice, whatever narratively makes sense for
	- Either recovering one skill completely
	- Or recovering one stat completely
	- Or recovering any two skills or stats by a single die size
- Spend XP to train or advance


### Watches & Rest

- **Choose a watch order**
* Characters sleep in shifts, which may or may not go uninterrupted.
* For each shift of uninterrupted sleep up to 3, a character may replenish a single skill or stat by one step
* A shift of sleep is 2 hours.
* On each character's shift
	* The GM decides if there will be a disturbance, and of what sort
		* We recommend using a depletion die model for selecting random encounters
		* When the encounter die is 'exhausted', select a random event or combat from your tables
		* For areas which are friendly, either don't roll or start with a d12.
		* For hostile areas (enemy cities, haunted woods, troll filled caverns), roll a d4.
		* General wilderness travel is a d8.
	* Independent of whether or not there is, the GM should call for a notice check from the player currently standing watch
	* On a failure
		* if the party was about to be attacked, they are surprised
		* If there was something interesting to notice, it goes unobserved
		* If nothing was going to happen, it goes unnoticed
	* On a success
		* If the party was about to be attacked, combat begins without the surprise round
		* If there was something interesting to notice, it is observed. 
			* It is up to the watchman if they wake the party.
		* If nothing occurred, the watch passes unceremoniously
* Treat secure locations as not requiring watches
	* In a secure location you get 4 replenishments max instead of 3

# Experience points and Advancement

## Earning XP

* **Session Participation**
	- Each session where you actively participated: 1 XP
	- This is automatic and rewards showing up and engaging
* **Character Arcs (Primary Driver)**
	- At character creation and during play, define a Character Arc
	- Arcs are structured personal stories
		- They must have
			- An opening
			- A climax
			- A resolution
		- They may have
			- Steps in the middle
	- Each arc step costs 1 XP to define
	- Each arc step awards 2XP points on completion
	- An arc which is completed successfully awards an additional 4XP
	- An arc which is completed unsuccessfully awards an additional 2XP
	- A player may start an arc at any time
	- When starting an arc, the player must
		- Define the opening
		- Call a shot on the intended climax (e.g. bringing the villain to justice)
			- Critically this must not be the way the arc climaxes or resolves
			- If, along the way the player were to discover 'the villain' was framed, they can still succeed in their arc.  However, now they are "bringing those truly responsible to justice"
	- At each completed step of the arc, the player must define the next arc step
		- Thus, 1 of the 2 XP awarded for step completion must be spent on an arc
		- Save that the character is closing out some arc
		- However, in this case, it makes sense to open a new arc
* **Meaningful Failure**
	- When a botch meaningfully advances the story: 1 XP
	- GM discretion, but should be obvious when failure creates interesting complications
	- Rewards embracing risk and interesting failure
	- When learning information that runs counter to the character's understanding of a relationship, you may choose to deplete its pool one step as if you had rolled a 1 when relying on the relationship. Once per session, you may gain 1 xp when you do this.

### Character Arcs

Character arcs are personal story goals broken into achievable steps. They drive narrative, reward progress, and communicate to the DM (and the rest of the table), what you'd like your character to work towards in the shared fiction of the game.

#### Arc Structure
1. Pay 2 XP to start an arc
2. Define the arc's
	1. Theme (shorthand for you and the table to talk about it)
	2. Start (this is the opening step, and half of the opening XP cost)
	3. End Goal (this is your intended climax step, and half of the opening XP cost)
3. Complete the current step through play
	1. Each step completed awards 2 XP
	2. When completing a step, define the next logical step for the arc
	3. Pay 1 XP as always to define the arc step, unless the next step is the climax which is predefined.
	4. On completing the climax, the next defined step must be the resolution.  Please note, the resolution is always the final step.
4. Finishing the arc
	1. When you have finished the resolution step, look at the arc's theme, climax, and resolution
	2. Decide with the DM if this was a successful arc or the arc ended in failure
		1. Ultimately, the DM is the arbiter
		2. However, it is a character arc so weigh their input heavily.
	3. Successfully completed arcs award 4 XP
	4. Arcs that end in failure award 2 XP

#### Arc Guidelines
- Steps should be specific and observable
- Each step should require 1-3 sessions of focused effort
- Arcs should matter to your character, not just be convenient
- You can pursue multiple arcs, but XP only comes from completed steps
- You can abandon an arc, but gain no XP for incomplete steps

##### XP Economy for a typical 4-step arc
- Start arc: -2 XP
- Complete opening → define intermediate: +2 XP, -1 XP = +1 XP (total: -1 XP)
- Complete intermediate → move to climax: +2 XP, -0 XP = +2 XP (total: +1 XP)
- Complete climax → define resolution: +2 XP, -1 XP = +1 XP (total: +2 XP)
- Complete resolution: +2 XP (total: +4 XP)
- Arc success bonus: +4 XP (total on success: **+8 XP net**)
- Arc failure bones: +2XP (total on failure: **+6XP net**)

#### Arc Examples

##### _Revenge_
1. Learn who killed your mentor
2. Track down their current location
3. Confront them publicly
4. Defeat or expose them

#####  _Redemption_
1. Acknowledge past wrongs to someone affected
2. Make meaningful restitution
3. Face consequences of your past actions
4. Earn forgiveness or acceptance from those you wronged

#####  _Mastery_
1. Find a teacher or rare text for the skill/spell you seek
2. Prove yourself worthy of the teaching
3. Complete the training or study
4. Demonstrate mastery in a critical moment

#####  _Mystery_
1. Discover the mystery exists
2. Find the first real clue
3. Uncover the truth
4. Deal with the consequences of knowing

#####  _Leadership_
1. Be given or seize responsibility
2. Face your first major test as leader
3. Overcome a challenge to your authority
4. Prove yourself to your followers



### Spending XP

#### Stats
- Add 1 die to a stat pool: 6 XP
- Increase all dice in a stat pool by one size: 6 XP
- Maximum: 4 dice per stat, d12 maximum die size
- **Capstone Advancement:** Reaching either 4 dice OR d12 (whichever comes first) requires a character arc representing the breakthrough needed to transcend normal limits

#### Skills
- Learn new skill at 1d4: 3 XP
- Add 1 die to a skill pool: 3 XP
- Increase all dice in a skill pool by one size: 4 XP
- Maximum: 3 dice per skill, d12 maximum die size
* **Capstone Advancement:** Reaching either 3 dice OR d12 (whichever comes first) requires a character arc representing the intensity of training needed for mastery

#### Relationships
- Establish new relationship at 1d4: At character creation or via character arc.
- Add 1 die to relationship: 2 XP
- Increase all dice in relationship by one size: 3 XP
- Maximum: 4 dice per relationship, d10 maximum die size
- Number of relationships is capped at the max of intellect, wits, or presence
- **Capstone Advancement:** Reaching either 4 dice OR d10 (whichever comes second) requires a character arc representing the depth of bond needed for such profound connection

#### Spells (for casters)
- Begin learning a new spell: 2 XP
- You still must fill the learning clock through study
- XP represents dedicating mental space to the new spell
- **Forbidden/Legendary Spells:** Learning particularly dangerous, forgotten, or powerful spells (complexity 11+, or GM discretion) requires a character arc and cannot be learned through routine study alone
- In a low-magic setting, consider
	- Treating "learning magic is real" as an arc
	- Identifying a teacher (or source of instruction) as an arc
	- Casting your first spell as an arc
	- Subsequent non-legendary spells as normal


### Usage-Based Skill Progression

* In addition to upgrades via spending XP directly, skills improve through repeated use in dangerous or meaningful situations. 
* Track successful uses of each skill.
* Progression milestones begin at 20 uses
* The size of the milestone triples each time
* Notes
	* When going up a level in a skill, whether via purchase or use, the threshold of total uses to get a free upgrade changes.
	* This incentivizes players to invest free-floating XP in already trained skills and to allow lower skills to progress naturally
	* Initial XP investment is required to start learning via use
	* Assuming a heavy skill is used about 10 times a session and one game a week...
		* Going from 1 to 2 is two weeks of play
		* Going from 2 to 3 is a month and a half of weekly play
		* Going from 3 to 4 is four or five months of weekly play
		* Going from 4 to 5 is a little over a year of weekly play
		* Going from 5 to 6 is a little over three years of weekly play

| Advancements away from 1d4 | Total Uses to Upgrade | Example Results |
| -------------------------- | --------------------- | --------------- |
| 1                          | 20 Total Uses         | 1d6, 2d4        |
| 2                          | 60 Total Uses         | 1d8, 2d6, 3d4   |
| 3                          | 180 Total Uses        | 1d10, 2d8, 3d6  |
| 4                          | 540 Total Uses        | 1d12, 2d10, 3d8 |
| 5                          | 1620 Total Uses       | 2d12, 3d10      |
| 6                          | Max Level             | 3d12            |
### Equipment

* Equipment doesn't upgrade
* Equipment is acquired through:
	- Purchase (if available and affordable)
	- Looting defeated enemies
	- Quest rewards
	- Finding in dungeons/ruins
	- Gifts from patrons or allies
	- Crafting
- When equipment is exhausted through depletion, it must be repaired in order to function.

| Equipment Quality       | Fully Repaired Dice Pool |
| ----------------------- | ------------------------ |
| Improvised              | 1d4                      |
| Basic / Cheap           | 2d4                      |
| Common                  | 1d6                      |
| Professional            | 2d6                      |
| Fine Quality            | 1d8                      |
| Masterwork              | 2d8                      |
| Heirloom / Extrordinary | 1d10                     |
| Legendary / Relic       | From 2d10 - 3d12         |


### Starting Characters
- 30 XP to distribute
	- #TODO This feels 'weak' for a standard fantasy hero
	- #TODO Consider Replacement
	- #TODO Readjust Point Buy Amount, but the schedule 'feels good'
		- Fixed allotment of  (for stats and skills)
			- 1 x 2d8 
			- 1 x 1d8
			- 2 x 1d6 
- Base stats are 1d4 across the board
- No stat may start above 3d8
- No skill may start above 2d8
- Begin with 3 significant relationships
	- #TODO Needs adopted for solo first play
	- One with another player character at 1d8
	- One with an NPC you create, at 1d6
	- One with an NPC made by another player at 1d4
	- In solo play
		- Take 3 relationships with 3 NPCs, one at 1d8, one at 1d6, one at 1d4
- Define your first character arc.  This arc is defined for free.
- Some Common Distributions
	- Broad Skill Heavy
		- 3 stat improvements (3x6 = 18 pts)
		- 4 skills at 1d4 (4 x 3 = 12 pts)
	- Deep Skill Heavy
		- 1 skill at 1d8 (3 + 4 = 7)
		- 1 Skill at 1d10 (3 + 4 + 4 = 11)
		- 2 Stat Improvements (2 x 6 = 12)
	- 

### Advancement During Play

#### When to Spend XP
- Between sessions (always allowed)
- During long rests (if it makes fictional sense)
    - Stats and relationships: probably yes
    - Skills: requires training or practice scene
    - Spells: requires access to learning materials

#### Fictional Justification
- Stat increases
	- physical training
	- overcoming limits
	- revelations
	- magical or technological intervention
- Skill increases
	- practice
	- instruction
	- epiphanies from experience
- New skills
	- instruction
	- observation
	- experimentation
- Relationships
	- must have interacted with the person/group significantly
- Spells
	- access to tome
	- teacher
	- repeatedly witnessed the magic

### XP Economy

#### Expected Earnings Per Session
- Session participation: 1 XP (automatic)
- Arc step completion: +1 XP net (after paying for next step)
    - Active arc pursuit typically completes 1 step every 1-3 sessions
- Meaningful failures: ~1 XP per session (varies with playstyle and risk-taking)
- **Typical total: 2-4 XP per session**

#### Understanding Arc Investment

Arcs are investments that pay dividends upon completion. A typical 4-step arc follows this economy (already detailed in Arc Guidelines):

- Initial investment: -2 XP
- You remain "in debt" until completing your intermediate step
- Breaking even: after climax completion (+2 XP total)
- Profit: resolution and success bonus (+8 XP total)

This structure incentivizes commitment. Starting multiple arcs without completing them drains XP. Seeing arcs through to resolution creates surplus XP for character advancement.

#### Pacing Benchmarks

With typical earnings of 2-4 XP per session:

- Major stat advancement (6 XP): every 2-3 sessions
- Learning new skill (3 XP): every 1-2 sessions
- Advancing existing skill: every 1-2 sessions OR wait for usage-based progression
- New relationship: requires character arc (no XP shortcut)
- Completing a 4-step arc: 4-8 sessions depending on focus

#### Strategic Spending

- **XP purchases = breadth:** New skills, mental stats for relationship capacity, physical stats for survivability
- **Usage-based progression = depth:** Your most-used skills will naturally become your best skills
- **Early investment accelerates mastery:** Spending 3 XP to advance a skill you use frequently puts you closer to the next usage-based milestone (20→60→180 uses)
- **Arc-locked improvements:** Capstone advancements (4 dice, d12 in stats/skills) and new relationships require story investment, not just XP

#### Campaign Timeframes
Assuming characters start from modest beginnings,

- Short campaign (10-15 sessions)
	- 20-60 XP earned
	- enough to specialize and complete 1-2 arcs
- Medium campaign (20-30 sessions)
	- 40-120 XP earned
	- significant specialization, multiple arcs
- Long campaign (40+ sessions)
	- 80-160+ XP earned
	- approaching mastery in primary areas with 5-10 completed arcs

# Crafting System

## Overview

Crafting in this system models the creation and modification of equipment, consumables, and other useful items through extended effort. Like spell learning, crafting uses **clocks** that fill through successful skill checks. Unlike spell learning, crafting consumes materials and can result in partial successes or salvageable failures.  The guiding principles are:

- Crafting uses the same dice pool mechanics as everything else
- Quality of materials acts as equipment dice in your pool
- Tools can be depleted through use or botches
- Failed attempts don't waste all materials, but progress is lost
- Master craftsmen can be leveraged as relationships
- Complex items require larger clocks and more successes per segment

## Crafting Clocks

The complexity of the item determines both the clock size and the crafting difficulty:

| Item Complexity | Clock Segments | Target Complexity | Example Items                               |
| --------------- | -------------- | ----------------- | ------------------------------------------- |
| Simple          | 3 segments     | 7                 | Basic repairs, simple tools, torches        |
| Common          | 5 segments     | 9                 | Standard weapons/armor, basic potions       |
| Professional    | 7 segments     | 9                 | Fine weapons, quality armor, useful potions |
| Fine Quality    | 10 segments    | 11                | Superior equipment, magical components      |
| Masterwork      | 12 segments    | 11                | Exceptional items, complex mechanisms       |
| Extraordinary   | 15 segments    | 13                | Heirloom-quality, minor magical items       |
| Legendary       | 20+ segments   | 13                | Artifacts, major magical items, relics      |

## Building Your Crafting Pool

When attempting a crafting check, build your pool from:

- **Stat:** Usually Intellect (for precision) or Finesse (for dexterity), occasionally Might (for forging/heavy work)
- **Skill:** Appropriate crafting skill (Blacksmithing, Alchemy, Enchanting, etc.)
- **Tools:** Your workshop, forge, alchemy lab, or portable toolkit
- **Materials:** Quality of raw materials acts as additional equipment dice
- **Relationship:** Master craftsmen, guild connections, divine patrons (for holy items)
- **Buffs:** Blessings, inspiration, magical enhancements to workspace

### Tools as Equipment

| Tool Quality          | Dice Pool | Notes                                                                               |
| --------------------- | --------- | ----------------------------------------------------------------------------------- |
| Improvised            | 1d4       | Found objects, makeshift workspace                                                  |
| Basic Toolkit         | 2d4       | Portable, limited functionality, available wherever commerce happens                |
| Professional Workshop | 2d6       | Dedicated space with proper tools, available some large towns, all major cities     |
| Master's Workshop     | 2d8       | Everything needed, highest quality, some major cities, hermitages with rare masters |
| Legendary Forge       | 3d8       | Ancient facility or blessed workspace, some hermitages, dangerous places            |
- Tools deplete on 1s as normal equipment
- When tools are exhausted, they need repair before further use
- Portable toolkits can be used anywhere but are smaller dice
- Fixed workshops require access (your shop, a guild, a patron's facilities)

### Materials as Equipment

Materials represent the quality of raw components. Better materials make crafting easier and enable higher-quality results:

| Material Quality | Dice Pool | Notes                                                                                                               |
| ---------------- | --------- | ------------------------------------------------------------------------------------------------------------------- |
| Scrap/Found      | 1d4       | Salvaged materials, questionable quality, available anywhere                                                        |
| Basic/Common     | 2d4       | Standard materials, available where commerce happens                                                                |
| Quality          | 2d6       | Good materials from reliable sources, available in any large town and some small villages                           |
| Superior         | 2d8       | Rare materials, exceptional purity, available in some large towns and all major cities                              |
| Exotic           | 2d10      | Rare elements, magical components, available near point of extraction, centers of use, and major commerce hubs only |
| Legendary        | 3d10      | Dragon scales, meteoric iron, divine gifts, only as quest or arc rewards                                            |
- Material dice DO deplete on 1s, representing waste, errors, or contamination
- When materials deplete to exhausted, they're consumed and cannot be recovered
- Multiple quality levels of materials can exist in your inventory
- You choose which materials to commit when starting the project

## The Crafting Process

### Declaration Phase

Before rolling any dice, establish:
- **What you're making** (determines clock size and complexity)
- **What materials you're committing** (locks in material dice, sets cost)
- **What tools you're using** (locks in tool dice)
- **Time investment** (one crafting session per long rest)
- **Assistance** (up to one other person can aid)

Once declared, materials are committed. If the project fails, see "Failed Crafting Attempts."

### Crafting Session
- Uses a major activity slot during long rest (occupies one of the four rest scenes)
- Make a crafting roll using your assembled pool
- Target complexity based on item complexity (see table above)
- Minimum groups typically 0, but increases for:
    - Especially intricate work (+1 minimum)
    - Attempting something beyond your skill level (+1-2 minimum)
    - Rushing the work (+1 minimum)
- Each group formed above minimum advances the clock by 1 segment
- Depletion occurs as normal on any 1s rolled

### Continuation
- Continue making crafting rolls during subsequent long rests
- Must have access to the same workspace and materials
- Can switch tools if needed (but risks new tool depletion)
- When clock fills, item is complete at the quality level attempted

### Completion
When the crafting clock fills:
- Item is created at the declared quality level
- Remaining materials (if any) are returned to inventory
- Tools remain at their current depletion state
- Character gains usage toward skill advancement (counts as meaningful use)
- Character may immediately begin a new crafting project next rest

## Failed Crafting Attempts

### Failed Session (0 groups, no depletion)

- Clock doesn't advance
- No resources lost
- Gain momentum for next crafting session
    - 0 momentum → 1d4
    - 1d4 → 1d6
    - 1d6 → 1d8, etc.
- Represents careful work that doesn't quite gel, but teaches something

### Botched Crafting (0 groups + depletion)

The player must choose ONE of the following consequences:
- **Material Waste:** Materials deplete one additional step
- **Tool Damage:** Tools deplete one additional step
- **Lost Progress:** Lose one filled segment from the clock (if any)
- **Contamination:** Next crafting session has target complexity +2
- **Frustration**: The craftsman must use the next long rest for some other task
- **Minor Mishap:** GM determines minor narrative consequence (small fire, ruined workbench, etc.)

### Abandoned Projects

If you abandon a project before completion:

- Recover 50% of uncommitted materials (round down in quality)
- All committed materials are lost
- Clock progress is lost
- May salvage components worth 25% of material costs (at scrap quality)

## Assisting Others

During the "Camp Preparation" scene of a long rest, a character may choose to **Aid Another's Crafting Project** instead of their normal rest action. This represents being a second pair of hands, fetching tools, or maintaining the workspace.

**Assistance Mechanics:**
- Assistant doesn't roll dice directly
- Instead, assistant's relevant skill (if any) acts as an additional buff to the primary crafter's pool
    - No relevant skill: 1d4 buff ("holding the pieces")
    - 1 die skill: 1d6 buff
    - 2 dice skill: 1d8 buff
    - 3+ dice skill: 1d10 buff
- Assistant's buff can deplete on 1s as normal
- Assistant gains partial credit toward skill usage (counts as half a use for progression)
- Multiple assistants don't stack - only one person can meaningfully help at a time

## Special Crafting Rules

### Repairing Equipment

* Repairing depleted equipment is run as a simple skill check.
* It requires the crafting skill to make the item to repair the item
* Difficulty & Minimum  are set by the items quality as follows

| Quality                   | Difficulty | Minimum Groups |
| ------------------------- | ---------- | -------------- |
| Improvised                | 2          | 0              |
| Basic & Common            | 5          | 1              |
| Professional              | 7          | 1              |
| Fine Quality & Masterwork | 9          | 2              |
| Heirloom                  | 11         | 2              |
| Legendary                 | 13         | 3              |
### Magical Crafting

Creating magical items follows the same process. 

- Requires Enchanting, Artifice, or similar magical crafting skill
- Must have access to magical materials (typically Exotic or Legendary quality)
- Often requires a specific spell to be cast during crafting (acts as buff)
- May require relationship with magical patron, deity, or ancient spirit
- Legendary magical items may require a character arc representing the dedication and breakthrough needed

### Equipment Modification 
Modification should only be used to add a property to an item, like adding spikes to a club, enchanting a sword with fire, or putting a long distance scope onto a rifle that came with iron sights. Modifications change something about the nature of the object that can manifest as a change to minimum groupings, target value modifications, or additional damage types that weren't part of the original weapon. To modify equipment, start a new crafting project: 
- Use the base item's dice as material dice
- If material dice exhaust, the base item is destroyed
- Clock size and complexity of the desired outcome as if crafting from scratch
	- Example: Enchanting a flaming sword
		- 2d6 sword uses it as 2d6 material dice
		- Success creates a 2d6 flaming sword
		- Failure may destroy the original.
- Only Professional and lower quality items may be modified
- Fine quality and up items must be created as intended from the start

### Consumable Creation

Potions, scrolls, poisons, alchemical items:

- Use smaller clocks (typically 3-5 segments)
- Lower complexity (usually 7-9)
- Cheaper materials (typically 10-50g for basic consumables)
- Often creates multiple doses based on groups above minimum
    - 0 groups above min: 1 dose
    - 1-2 groups above min: 2 doses
    - 3-4 groups above min: 3 doses
    - 5+ groups above min: 4 doses
- If the character 'knows the recipe', reflect this by lowering the complexity.

## Examples of Crafting Projects

### Simple: Repairing Leather Armor (3 segments, complexity 7)

**Declaration:**
- Item: Restore 1d6 leather armor currently at 1d4
- Materials: Basic leather scraps (2d4, 10g)
- Tools: Basic leatherworking kit (2d4)
- Stat: Finesse
- Skill: Leatherworking (1d6)

**Session 1:**
- Pool: 2d8 Finesse + 1d6 Leatherworking + 2d4 Tools + 2d4 Materials = 2d8 + 1d6 + 4d4
- Rolls: 7,3 (Finesse) + 4 (Skill) + 3,2,1,3 (Tools/Materials)
- Forms groups: 7, 4+3, 3+2+2 = 3 groups (clock fills immediately!)
- Leather armor restored to 1d6
- Tools deplete to 2d4 → "cracked" (become 1d4 next time, still usable)
- Materials exhausted (all scraps used)

### Common: Crafting a Longsword (5 segments, complexity 9)

**Declaration:**
- Item: New longsword (targeting 1d6 quality)
- Materials: Quality steel (2d6, 150g)
- Tools: Professional forge (2d6)
- Stat: Might (for the heavy hammering work)
- Skill: Blacksmithing (2d8)

**Session 1:**
- Pool: 3d8 Might + 2d8 Blacksmithing + 2d6 Forge + 2d6 Steel = 5d8 + 4d6
- Rolls: 8,7,2 (Might) + 7,1 (Skill) + 5,4 (Forge) + 6,3 (Steel)
- Forms groups: 8+2, 7+3, 7, 6+4, 5 = 5 groups, all 5 fill the clock!
- But rolled 1 on skill, Blacksmithing depletes from 2d8 → 2d6
- Sword complete at 1d6 quality!

_Note: This was exceptionally lucky. Most 5-segment projects take 2-3 sessions._

### Professional: Crafting Superior Chainmail (7 segments, complexity 9)

**Declaration:**
- Item: Superior chainmail (2d6 quality)
- Materials: Superior steel (2d8, 1500g)
- Tools: Professional forge (2d6)
- Stat: Might + Finesse (alternating sessions for heavy work and fine links)
- Skill: Armor smithing (2d6)
- Relationship: Master Armorer (1d8, learning from retired craftsman)

**Session 1:**
- Pool: 3d8 Might + 2d6 Armor smithing + 2d6 Forge + 2d8 Steel + 1d8 Master = 5d8 + 4d6
- Rolls: 8,5,4 + 6,3 + 5,2 + 7,6 + 7 = many dice
- Forms groups: 8+3, 7+5, 7+2, 6+4, 6, 5 = 6 groups? (No, complexity is 9, so need 9+)
- Actually: 8+4+2, 7+3, 7+5, 6+6 = 4 groups (4/7 segments)
- Master relationship depletes to 1d6 (rolled a 1 somewhere, master is getting tired of helping)

**Session 2:**
- Switch to Finesse for detail work
- Pool: 2d6 Finesse + 2d6 Armor smithing + 2d6 Forge + 2d8 Steel + 1d6 Master
- Gets 2 more groups (6/7 segments)

**Session 3:**
- Final polish and assembly
- Gets 2 groups (8/7 segments - 1 extra group wasted)
- Chainmail complete at 2d6 quality!

### Masterwork: Enchanted Flaming Sword (12 segments, complexity 11)

**Declaration:**
- Item: Masterwork longsword with permanent flame enchantment
- Materials: Meteoric iron (2d10, quest reward) + Elemental fire essence (2d8, 5000g)
- Tools: Legendary Forge of the First Smiths (3d8, quest access)
- Stat: Intellect (for the magical precision needed)
- Skill: Artifice (2d8, magical crafting)
- Relationship: Fire Elemental Pact (2d6)
- Buff: Blessing of the Forge God (1d10, granted during character arc)

**Sessions 1-5:**
- Multiple crafting sessions over several long rests
- Successfully fills 12-segment clock despite high complexity
- Several close calls with depletion
- Forge relationship deepens through the work (increases to 2d8)
- Fire Elemental Pact depletes then recovers through story events

**Result:**
- Flaming longsword complete at 2d8 quality
- Deals fire damage (acts as separate weapon effect, not included in base pool)
- Becomes signature weapon, player starts new character arc involving its legacy

# Travel & Environmental Hazards

## Overview

Travel between locations involves time, resources, and risk. This system doesn't concern itself with terrain generation or discovering what's on the map—use existing sandbox generators for that. Instead, it models the physical toll of the journey: forced marches, dwindling supplies, and hostile environments.

**Guiding Principles:**
- Travel uses existing mechanics (clocks, skill checks, contested rolls)
- Resource scarcity creates growing debuffs
- Environmental hazards use the same framework
- Integration with long rest mechanics

## Journey Structure

When embarking on a journey, establish:
- **Distance:** How many days of travel at normal pace
- **Terrain:** Affects pace and encounter frequency (use your preferred sandbox system)
- **Supplies:** Food and water for the journey
- **Pace:** Normal, slow (cautious), or forced march

### Travel Pace

| Pace   | Daily Progress | Effects                                                                                    |
| ------ | -------------- | ------------------------------------------------------------------------------------------ |
| Slow   | 75% distance   | Advantage on navigation and notice checks (add 1d6 buff), reduce encounter die by one step |
| Normal | 100% distance  | No modifiers                                                                               |
| Forced | 150% distance  | Risk exhaustion, increase encounter die by one step                                        |

### Daily Travel Routine

Each travel day follows this structure:
1. **Morning:** Declare pace, check supplies
2. **Travel:** Make progress, potential encounters
3. **Evening Camp:** As per long rest rules (see "Watches & Rest")
4. **Resource Consumption:** Each character consumes one day's rations and water

## Growing Debuffs: The Scarcity System

Unlike damage that depletes dice, environmental hazards create **growing debuffs** that worsen over time. These debuffs start small and escalate until addressed.

### Core Mechanics

* **Initial Exposure:**
	- When first exposed to a hazard (no sleep, no food, no air, forced march), gain a 1d4 debuff
	- This debuff applies to all rolls as normal (creates additional target groups to overcome)
* **Growth Triggers:**
	- **Max Face Roll:** Whenever you roll the maximum value on any die in the debuff (4 on d4, 6 on d6, etc.), the debuff grows one step
		- This may seem harsh, but imagine you are fighting hard having not had days of water, or underwater without access to air
		- The continued exertion is going to tax you and expend already scarce resources
		- When resources are present, the debilitating effects of scarcity remain, however **the debuff does not grow on a max-face roll**.
	- **Continued Exposure:** Each additional period of exposure (day without food, additional forced march, another hour without air) also grows the debuff one step
		- Exposure continues even if the character is unconscious, so being knocked out doesn't save you from, say, drowning 
		- **Partial Exposure** If you are consuming half rations of water or food, double the duration for automatic growth
* **Growth Progression:**
	- 1d4 → 1d6 → 1d8 → 1d10 → 1d12 → Death
	- Once a debuff reaches d12 and would grow again, the character dies or becomes permanently incapacitated
	- Having multiple growing debuffs at d12 isn't fatal.  It is dangerous, but you aren't dead _yet_.
* **Recovery:**
	- Growing debuffs cannot be depleted through normal means (rolling 1s does nothing)
	- They can only be removed by addressing the underlying need
	- When the need is met, the debuff immediately reduces by one step
	- Full recovery requires multiple periods of addressing the need (one rest removes one step)
- **Multiple Growing Debuffs:**
	- Different hazards create separate debuffs (hunger + exhaustion = two debuffs)
	- Each tracks and grows independently
	- Both apply to all rolls

## Examples
### Forced Marches

#### Pushing the Pace

When traveling at forced march pace (150% normal progress), each character makes an endurance check at the end of the day:

* **The Roll**
	* **Pool:** Grit (stat) + Athletics or Survival (skill) + relevant gear 
	* **Complexity:
	* ** 7 **Minimum Groups:** 1
* **Results:**
	- **Success:** No exhaustion gained
	- **Failure (0 groups, no depletion):** Gain "Exhaustion" 1d4 debuff (or grow existing exhaustion by one step)
	- **Botch (0 groups + depletion):** Gain/grow exhaustion AND one additional consequence:
	    - Deplete armor or gear one additional step
	    - Twist ankle: gain "Injured" 1d4 debuff
	    - Fall behind: arrive 2 hours after rest of party
	    - Consume double rations (body burning resources)
	- **NOTE** This makes d10 exhaustion "the danger zone"
		- You can fail your forced march roll, moving up to a d12
		- You can roll a 10 on the d10 debuff, moving past d12 to incapacitated
- **Exhaustion Debuff:**
	- Applies to all subsequent rolls
	- Grows on max face rolls during any check
	- Grows one step for each additional day of forced march
	- Only recovers through rest (see below)

#### Recovery from Exhaustion

* **Short Rest:** No effect on exhaustion (too brief to matter)
* **Long Rest with Normal Activity:**
	- Reduces exhaustion by one step (d6 → d4)
	- Can be combined with other long rest recovery
- **Long Rest with Complete Rest:**
	- If character takes "Rest" action during Camp Preparation AND during Quiet Moment
	- Reduces exhaustion by two steps (d8 → d4)
	- Sacrifices most other recovery options

### Hunger & Thirst

* **Each character requires:**
	- **Food:** 1 ration per day (represents ~2000 calories, preserved trail food)
	- **Water:** Access to clean water (assume 2-3 liters, easily available in most terrain)
* **Going Without Food**
	* Hunger increases at the rate of every other day, so...
	* **Day 1 Without Food:**
		- No immediate effect (body has reserves)
	- **Day 2 Without Food:**
		- Gain "Hunger" 1d4 debuff at end of day
	- **Day 4,6,8... Without Food:**
		- Every other day, "Hunger" grows one step automatically (d4 → d6 → d8...)
		- Additionally grows on any max face roll
		- At d12, character is dying of starvation
		- If eating half rations, extend schedule out to 3, 6, 9, etc.
- **Going Without Water**
	- Water deprivation is more dangerous than hunger, and proceeds in half days
	- **12 Hours Without Water**
		- No immediate effect in temperate conditions
		- In hot/dry conditions, proceed immediately to next stage
	- **24 Hours Without Water:**
		- Gain "Thirst" 1d4 debuff
		- Each additional 12 hours grows it one step
		- At d12, character is dying of dehydration
		- Half rations, extend schedule out to each additional day on half water ration
- **Procuring Water & Food During Travel**
	* **When to Forage:**
		- Uses minor action during travel day (represents gathering while moving)
		- Uses major action if party stops to forage more thoroughly
	- **The Foraging Roll:**
		- **Pool:** Wits + Survival + relevant gear
		- **Complexity:** 7-11 depending on terrain (see table below)
		- **Minimum Groups:** 0
	- **Results:**
		- Each group above minimum provides ONE of the following (player's choice):
		    - 1 day's food for one person
		    - Water source for entire party (for that day)
		- **Exceptional Success (5+ groups):** Player may count one group as:
		    - 3 days' food for one person (found large game, honey, fruit trees)
		    - Permanent water source (spring, reliable stream - mark on map)
	- **Terrain Complexity:**

| Terrain Type            | Complexity | Notes                              |
| ----------------------- | ---------- | ---------------------------------- |
| Fertile Forest/Farmland | 7          | Abundant food and water            |
| Plains/Light Forest     | 9          | Moderate resources                 |
| Mountains/Dense Jungle  | 9          | Resources exist but hard to access |
| Desert/Tundra           | 11         | Scarce resources                   |
| Wasteland/Blighted Land | 13         | Nearly barren                      |

* **Water Purification:**
	- Rivers, streams, springs, and rain are automatic clean water sources
	- Stagnant water, swamps, or questionable sources require purification
	- Intellect + Survival check, complexity 7
	- Failure: risk disease (GM introduces "Illness" growing debuff starting at 1d4)
- **Example:** 
	- The party travels through plains (complexity 9).
	- Mira the ranger makes a foraging check during the day's travel, rolling 4 groups above minimum.
	- She chooses: 
		- 2 days food for herself
		- 1 day food for the fighter
		- secures water for the whole party for today.
* **Recovery from Hunger and Thirst**
	* In general, recovery from a growing debuff should happen on the same cadence as the debuff grew naturally
	* So, for food, each day of eating normally reduces the face size by 1 until it is reduced from a d4 and depletes
	* For water, every 12 hours with access reduces the debuff by a step
	* Remember, when resources are present, the debuff can not grow on a max-face roll.
	* You cannot increase the speed of recovery by eating / drinking / etc more.
		* In real life, overeating after starvation and water poising are not unheard of.

### Other Environmental Hazards

The growing debuff system models many hazards. Here are quick templates:

#### Suffocation/Drowning
* **Initial:** Holding breath, complexity 7 Grit check each round
- Success: Continue holding breath
- Failure: Gain "Suffocating" 1d4 debuff 
- Each subsequent round without air: grows one step automatically
- At d12: unconscious, death follows in 1-2 rounds
* **Recovery:** Access to air reduces by one step every round as you 'catch your breath'

#### Extreme Temperatures
* **Inadequate Clothing/Shelter:**
- After 1 hour exposed: Grit check, complexity 9
- Failure: Gain "Hypothermia" / "Heat Stroke" 1d4 debuff as appropriate
- Each additional hour: grows one step
- At d12: death from exposure
* **Recovery:** Warmth (shelter, temperature regulation, appropriate clothes) reduces by one step per hour

### Toxic Atmosphere (Poison Gas, Radiation, etc.)

* **Initial Exposure:**
	- Gain "Poisoned" or "Irradiated" 1d4 debuff
	- Each hour of exposure: grows one step
	- Also grows on max face rolls
* **Recovery:**
	- Must leave hazardous area
	- Minor toxins: reduce at one step per hour after cessation of exposure
	- Moderate toxins: reduce one step per day after leaving
	- Severe toxins/radiation: require medical treatment to begin recovery
	- Magical/alchemical cure may remove immediately (GM discretion)

### Using the Template

**For any scarcity or hazard:**
1. Decide growth frequency (each day? each hour? each round?)
2. Decide what removes it (rest? medicine? leaving the area?)
3. Let max face rolls accelerate the problem

## GM Guidelines

* **Growth Frequency:**
	- Rounds: Immediate danger (suffocation, drowning)
	- Hours: Acute hazards (extreme cold, toxic gas)
	- Days: Chronic deprivation (hunger, radiation)
- **Be Generous with Resources:**
	- Don't make travel a resource-tracking slog
	- Abstract when journey is safe
	- Focus on scarcity when it creates interesting choices
- **If these rules aren't interesting to the party, for heaven's sake don't use them.**

# Vehicles & Mounts

## Overview

Vehicles and mounts are statted like characters or monsters, with pools that can be depleted through use or damage. The quality of the mount/vehicle AND the skill of the rider/pilot both contribute to success. Exceptional piloting provides substantial benefits to actions taken from or with the vehicle.

**Core Principle:** Piloting/riding is a separate action that generates momentum and buffs for other actions taken that round.

## Vehicle & Mount Statistics

### Standard Stat Block

Like characters, vehicles and mounts have:

* **Stats (as dice pools):**
	- **Might:** Carrying capacity, pulling power, raw force
	- **Finesse:** Maneuverability, handling, agility
	- **Grit:** Durability, ability to take damage
	- **Wits:** Only for intelligent mounts (trained warhorses, dragons, etc.)
- **Additional Attributes:**
	- **Handling Complexity:** Target number for piloting checks (5-13)
	- **Capacity:** Number of riders/crew + cargo weight
	- **Speed:** Movement per round/day (expressed as multiplier of base human movement)
	- **Special Abilities:** Flight, amphibious, extreme terrain capability

### Example Stat Blocks

#### Riding Horse (Common Quality)

| Attribute           | Value                              |
| ------------------- | ---------------------------------- |
| Might               | 3d6                                |
| Finesse             | 2d6                                |
| Grit                | 2d6                                |
| Wits                | 1d4                                |
| Handling Complexity | 7                                  |
| Capacity            | 1 rider + 50kg gear                |
| Speed               | 2x human walking, 4x human running |

#### Warhorse (Professional Quality)

| Attribute           | Value                              |
| ------------------- | ---------------------------------- |
| Might               | 3d8                                |
| Finesse             | 2d8                                |
| Grit                | 3d8                                |
| Wits                | 1d6                                |
| Handling Complexity | 7                                  |
| Capacity            | 1 rider + armored rider + 40kg     |
| Speed               | 2x human walking, 4x human running |

#### Wagon (Basic)

| Attribute           | Value                          |
| ------------------- | ------------------------------ |
| Might               | 1d4 (wagon itself)             |
| Finesse             | 1d4                            |
| Grit                | 2d6                            |
| Handling Complexity | 9                              |
| Requires            | 2 draft animals to pull        |
| Capacity            | 4 passengers + 500kg cargo     |
| Speed               | 1x human walking (when pulled) |

#### Motorcycle (Professional)

| Attribute           | Value             |
| ------------------- | ----------------- |
| Might               | 2d6               |
| Finesse             | 3d8               |
| Grit                | 2d6               |
| Handling Complexity | 9                 |
| Capacity            | 1 rider + 20kg    |
| Speed               | 10x human running |

#### Fighter Jet (Extraordinary - requires advanced tech setting)

| Attribute           | Value                             |
| ------------------- | --------------------------------- |
| Might               | 3d10                              |
| Finesse             | 3d10 (advanced autopilot assists) |
| Grit                | 3d8                               |
| Handling Complexity | 7 (computerized flight control)   |
| Capacity            | 1-2 crew                          |
| Speed               | 100x+ human running               |
| Special             | Weapon systems, ejection seat     |

## Piloting & Riding Checks

### When to Roll

Make a piloting/riding check when:
- Performing a difficult maneuver (sharp turn, jump, evasive action)
- Taking a major action with the vehicle (charging, strafing run, ramming)
- Operating in hazardous conditions (combat, rough terrain, bad weather)
- Maintaining control after taking damage

Routine travel at normal pace requires no checks.

### The Piloting Roll

* **Pool Construction:**
	- **Stat:** Wits (for situational awareness) or Finesse (for precision handling)
	- **Skill:** Riding, Driving, Piloting (as appropriate)
	- **Vehicle/Mount:** Add the vehicle's Finesse pool (represents how responsive it is)
	- **Relationships:** Bond with trained animal, familiarity with specific vehicle
	- **Buffs/Debuffs:** Terrain difficulty, weather, damage to vehicle
- **Complexity:** Use the vehicle's Handling Complexity (typically 7-11)
- **Minimum Groups:** Usually 0, but increases for:
	- Extreme maneuvers (+1-2)
	- Hazardous conditions (+1)
	- Damaged vehicle/injured mount (+1 per depletion level)

### Results of Piloting Checks
* **Success (meets minimum groups):**
	- Maneuver succeeds
	- Vehicle responds to commands
	- Generate piloting momentum (see below)
* **Failure:**
	- Maneuver fails or is incomplete
	- May trigger hazard (GM discretion): skid, stumble, loss of position
	- No momentum generated
- **Botch:**
	- Maneuver fails badly
	- Vehicle/mount takes damage OR rider takes damage OR both
	- Possible loss of control (additional check to avoid crash/fall)

### Piloting Momentum
* **Each group above minimum generates piloting momentum for that round:**

| Groups Above Minimum | Momentum Effect                                           |
| -------------------- | --------------------------------------------------------- |
| 1                    | 1d4 buff to one action taken from/with vehicle this round |
| 2                    | 2d4                                                       |
| 3                    | 2d6                                                       |
| 4                    | 3d6                                                       |
| 5+                   | 3d8                                                       |

* Vehicle momentum uses multiple smaller dice and expires quickly, unlike scene-lasting momentum from exceptional combat rolls
	* This is to model the mercurial nature of vehicular combat, dogfighting, etc.
	* Things change _quickly_, in this model round to round.
	* The advantages for excellent piloting can be substantial.
* **Momentum applies to:**
	- Attacks made by the rider/pilot
	- Attacks made by passengers/gunners
	- Defensive maneuvers (acts as buff to defense rolls)
	- Intimidation or other actions leveraging the vehicle's presence
- **Momentum expires at the end of the round** (unlike momentum from extraordinary rolls in combat, which lasts the scene).

## Combat from Vehicles & Mounts

### Action Economy

**Rider/Pilot Major Action Options:**

* **Piloting maneuver** (generates momentum for others)
* **Attack while piloting** 
	* If the weapon is vehicle mounted and facing in the direction of drive, use the piloting check directly to attack
		* Examples
			* Hidden guns in the headlight of a car, you shoot at what's in front of you by putting it in front of you with the driving skill
			* Forward facing canon on an aircraft, you shoot at what's in front of you by putting it there with a piloting check
			* Jousting, you fix the lance and run at the other guy using the horse
	* If the weapon is not mounted or does not face in the direction of drive, requires multi-tasking
		- Declare you're splitting your attention
		- Make piloting check at +2 complexity
			- Every group you make over minimum counts as a buff as normal
			- Every group you fail to make below minimum acts as a debuff using the same progression as the buff table
		- Make attack check normally, using generated buffs or debuffs.
		- Examples
			- firing out the driver window of a car
			- using a shotgun while on a motorcycle
			- Firing a bow from the back of a horse
			- dropping a stick of dynamite from a hang glider
- **Attacking Another Vehicle / Pilot / Occupant**
	- As attacking while piloting, but the pilot of the other craft must roll their **piloting skill and relevant vehicle stats** to contest your piloting roll.
	- See the [[short_form_writing/thoughts_on_solo/Customsystem/Dice Notes#Contested Rolls|Contested Rolls]] section for details.
	- When deciding how to absorb uncontested contest dice, the participant making depletion decisions may choose to deplete either the vehicle or the pilot.
* **Charge/Ram** (vehicle itself is the weapon, use simple piloting check)
	* **Pool:** Pilot's Wits + Piloting Skill + Vehicle's Might + Vehicle's Finesse (for accuracy)
	- **Complexity:** Target's defense or 9, whichever is higher
	- **Effect:** Each success group depletes target's choice of stats/armor
	- **Cost:** Vehicle takes 1 depletion to Grit per X successes generated (minimum 1), based on size difference

| Size Comparison     | X Value | Example                              |
| ------------------- | ------- | ------------------------------------ |
| Vehicle much larger | 4       | Semi vs pedestrian, dragon vs horse  |
| Vehicle larger      | 2       | Car vs motorcycle, warhorse vs rider |
| Same size           | 1       | Car vs car, horse vs horse           |
| Vehicle smaller     | 0.5     | Motorcycle vs car, rider vs elephant |
* **Passenger/Gunner Actions:**
	- Act normally but benefit from pilot's momentum
	- Make attacks using their own pools + pilot's momentum buff
		- They use the pilots most recent momentum buff
			- So, if the passenger acts before the pilot, they use the buff from the last round (possibly none as the vehicle 'isn't in motion')
			- If they act after the pilot, they use the buff that was rolled this round
	- Examples
		- Manning cannons on an airship
		- Firing out of the passenger or rear window of a moving vehicle
		- Running the gun emplacement on the back of a military vehicle


## Damage to Vehicles & Mounts

### Taking Damage
* When a vehicle or mount is targeted:
	- Attacks against them work as normal contested rolls
	- Depletions reduce their stat pools
	- When any stat is exhausted, vehicle/mount becomes hindered (as per character rules)
	- When 3+ stats exhausted, vehicle is disabled/mount collapses
* Some vehicles have critical systems that can be targeted:
	- **Wheels/Legs:** Depleting Finesse immobilizes
	- **Engine/Heart:** Depleting Might reduces power
	- **Armor/Hide:** Depleting Grit makes vulnerable
	- In general, the idea is that the GM may rule specific targeted attacks hit specific stats.

### Repair & Healing
* **Vehicles:**
	- Use crafting rules (see Crafting chapter)
	- Complexity based on vehicle quality
	- Requires tools and parts
- **Mounts:**
	- Use Medicine or Animal Handling skill
	- Treated like healing a character
	- Requires rest and care (follows long rest recovery rules)
	- Veterinary supplies act as equipment dice

# Factions & Organizations

## Overview

Factions are organizations of any size, from a small adventuring party to a nation-state. They act in the world, pursue goals, and interact with each other and with player characters. Factions provide quest hooks, make the world feel alive, and offer players access to resources beyond what they can carry themselves.

**Core Principles:**
- Factions use the same dice pool mechanics as characters
- Resources deplete through use and conflict
- Leadership determines how many actions a faction can take
- Factions pursue arcs that create consequences in the game world
- Player interaction happens through relationships and quests

## Faction Turns

* Factions take the more frequent of
	* one turn per session (typically resolved between sessions) 
	* once every 2 weeks of in-game time
* During a faction turn, the faction may:
	- Take actions equal to the number of leaders it has
	- Rest and recover depleted resources (see Faction Rest)
	- Progress on faction arcs
	- Respond to events in the world

## Faction Statistics

### Standard Faction Stat Block

Like characters, factions have dice pools representing their capabilities:

* **Resources (dice pools that deplete):**
	- **Personnel:** Nameless workers, guards, servants, soldiers (e.g., "Guards 3d6", "Scholars 2d8")
	- **Facilities:** Buildings, workshops, strongholds, special locations (e.g., "Fortress 2d8", "Forge 2d6", "Library 1d10")
	- **Assets:** Vehicles, supplies, consumables, equipment stockpiles (e.g., "War Chest 3d6", "Armory 2d8")
	- **Influence:** Political capital, reputation, connections (e.g., "Court Favor 2d6", "Street Cred 1d8")
- **Leadership:**
	- Individuals (fully statted NPCs or PCs)
	- Sub-factions (other factions that report to this one)
	- Leadership count determines faction size and action economy (1-5 leaders)
- **Relationships:**
	- With other factions (e.g., "Allied with The Crown 2d6")
	- With key individuals (e.g., "Enemies with Lich Theron 1d8")
- **Goals:**
	- Current faction arcs being pursued
	- Long-term objectives (which should be supported by current arcs)

### Faction Size by Leadership

| Leadership Count | Faction Size | Examples                                                |
| ---------------- | ------------ | ------------------------------------------------------- |
| 1                | Small        | Adventuring party, small merchant operation, local gang |
| 2                | Medium       | Guild chapter, town militia, criminal syndicate         |
| 3                | Large        | Major guild, city government, regional army             |
| 4                | Very Large   | Kingdom, major religion, trading empire                 |
| 5                | Massive      | Empire, international alliance, dominant church         |

* **Mixing Individuals and Sub-factions:** A large corporation might have:
	- CEO (individual)
	- Marketing Division (sub-faction)
	- Logistics Division (sub-faction)
	- International Branch (sub-faction)
- A kingdom might have:
	- The King (individual)
	- The Royal Army (sub-faction)
	- The Mage Council (sub-faction)

### Example Faction Stat Blocks

#### The Iron Hawks (Small Adventuring Party Faction)

* **Leadership:** 1
	- Captain Mira Stonefist (PC)
- **Resources:**
	- Camp Supplies: 2d4
	- Reputation in Local Towns: 1d6
- **Relationships:**
	- Allied with Merchant Guild: 1d6
	- Suspicious of City Watch: 1d4
* **Current Goals:**
	- Arc: Clear the Western Mines of undead (step 2 of 4)

#### The Velvet Guild (Medium Thieves' Guild)

* **Leadership:** 2
	- Shadowmaster Vex (NPC - 2d8 Wits, 2d6 Stealth)
	- The Fence Network (sub-faction, handles goods movement)
- **Resources:**
	- Safehouse Network: 2d6
	- Thieves & Cutpurses: 3d6
	- Informants: 2d6
	- Stolen Goods Stockpile: 2d4
- **Relationships:**
	- At War with City Watch: 1d4 (hostile)
	- Cooperates with Beggars' Union: 1d8
- **Current Goals:**
	- Arc: Establish operations in the Dockside District (step 3 of 5)

#### The Kingdom of Aldrath (Very Large Nation)

* **Leadership:** 4
	- Queen Elara the Just (NPC - fully statted)
	- The Royal Army (sub-faction)
	- The Court of Mages (sub-faction)
	- High Priest Dalmar (NPC - fully statted)
- **Resources:**
	- National Treasury: 3d10
	- Royal Fortresses: 3d8
	- Spy Network: 2d8
	- Provincial Militias: 3d6
	- Diplomatic Corps: 2d6
- **Relationships:**
	- Allied with Merchant Confederacy: 2d8
	- Cold War with Northern Empire: 1d6 (tense)
	- Protects the Iron Hawks: 1d4 (minor favor owed)
- **Current Goals:**
	- Arc: Secure the Northern Border (step 4 of 6)
	- Arc: Root out corruption in the merchant class (step 1 of 4)

## Faction Actions

During each faction turn, a faction may take one action per leader. Each action must be led by someone—either an individual leader or a designated sub-faction.

**Common Faction Actions:**

- Attack or undermine another faction
- Replenish a resource
- Recruit new personnel or leadership
- Build or acquire new facilities/assets
- Complete a step in a faction arc
- Send aid to individuals or other factions
- Craft items or research at scale
- Establish new relationships

### Resolution Methods

#### Quick Resolution (Off-Camera)
When the action happens off-screen, use faction dice to resolve:

1. **Build the Pool:**
    - Relevant resources (Personnel, Facilities, Assets, Influence)
    - Leader's stats and skills (if individual) OR sub-faction's resources (if delegated)
    - Relevant relationships
    - Any provided buffs or contested rolls from opposing factions
2. **Set Complexity & Minimum Groups:**
    - GM determines as for any skill check (typically 7-11)
    - More complex actions require more groups
3. **Roll and Resolve:**    
    - Count groups above minimum
    - Advance clocks, deplete enemy resources, or achieve narrative goals
    - Depletion happens on 1s as normal

#### Player Character Resolution
When a PC is doing a quest for the faction, that step resolves through play using normal character rules. The faction might lend resources to the PC for the quest (see Requesting Aid).

### Example Faction Action

**The Velvet Guild attacks City Watch operations:**
- **Action:** Shadowmaster Vex leads thieves to burn Watch supply depot
- **Pool:** 2d8 Vex's Wits + 2d6 Vex's Stealth + 3d6 Thieves & Cutpurses + 2d6 Informants (for intel)
- **Opposed By:** City Watch rolls 3d6 Guards + 2d6 Patrols as contested dice
- **Complexity:** 9 (heavily guarded target)
- **Minimum Groups:** 1
- **Result:** Guild rolls well, forms 3 groups, overcomes contested dice
    - Depot burned (narrative success)
    - One success used to deplete City Watch's "Supply Stockpile" resource by one step
    - Rolled a 1 on Informants die - Informants deplete from 2d6 to 2d4 (some captured or went to ground)
    - Attacked another faction, decreasing relationship with attacked faction

## Resource Depletion & Recovery

### When Resources Deplete

* **During Quick Resolution:**
	- Any 1 rolled on a resource die depletes that resource one step (d6→d4, etc.)
	- Attacking factions may target specific resources (each success depletes by one step)
* **When Lent to Others:**
	- If a faction lends resources to a player or delegates to a leader, those resources are committed
	- Resources may be fully or partially committed
		- You may not split singular resources "Your forge, your infirmary, you"
		- You may spilt your guard and send some of them with a leader or player, provided you have multiple dice to split
			- If you have a 1d8 mercenary resource, you can't partially lend them
			- If you have a 2d4 mercenary resource, you may lend half of them as 1d4
	- Committed resources deplete as normal
	- When the loan ends, the undepleted portion of the committed resource returns
	- The depleted portion can be restored as normal once returned.
- **When Exhausted:**
	- Like character stats, exhausted resources leave the faction vulnerable
	- Personnel exhausted = fewer people to take actions
	- Facilities exhausted = can't use them for actions or prerequisites
	- When ALL resources are exhausted, the faction dissolves or becomes inactive

## Faction Relationships

Faction relationships work exactly like character relationships:

* **Creating Relationships:**
	- Start new relationships through faction arcs or in-fiction negotiation
	- Can be established at 1d4 through significant interaction
	- Or purchased with faction XP (2 XP for 1d4 relationship)
- **Using Relationships:**
	- Add relationship dice to actions involving that faction
	- Acts as diplomatic leverage, shared intelligence, borrowed resources
	- Depletes on 1s as normal
- **Growing Relationships:**
	- Spend faction XP (2 XP to add 1 die, 3 XP to increase all dice one step)
	- Complete faction arcs that involve cooperation
	- Maximum: 4 dice per relationship, d10 maximum die size
* **Examples:**
	- "The Iron Hawks have 1d6 relationship with Merchant Guild" (friendly terms, occasional favors)
	- "The Velvet Guild has 1d4 relationship with City Watch" (hostile, but informants remain)
	- "Kingdom of Aldrath has 2d8 relationship with Merchant Confederacy" (strong alliance, trade treaty)

## Faction Arcs & Progression

Factions pursue arcs just like characters, earning XP and advancing their capabilities.

### Earning Faction XP

- **Completing Arc Steps:**
	- +2 XP per step completed (paid after defining next step)
	- -1 XP to define next step (net +1 XP per step)
- **Arc Completion:**
	- Successfully completed arc: +4 XP
	- Failed/abandoned arc: +2 XP
- **PC Contribution:**
	- When PCs complete a quest FOR the faction, faction earns bonus XP (1-3 XP, GM discretion)

### Spending Faction XP

* **Resources:**
	- Add 1 die to a resource pool: 3 XP
	- Increase all dice in a resource pool by one step: 4 XP
	- Create new resource at 1d4: 3 XP
	- Maximum: 4 dice per resource, d12 maximum die size
- **Leadership:**
	- Recruit new individual leader: Requires arc + investment (no XP shortcut)
	- Integrate sub-faction as leader: Requires negotiation/conquest + 5 XP to formalize
	- Promote from within: 4 XP (existing personnel becomes individual leader, leader gets stat block, personnel depletes 1 step)
- **Relationships:**
	- Establish new relationship at 1d4: 2 XP (or via arc)
	- Add 1 die to relationship: 2 XP
	- Increase all dice in relationship by one step: 3 XP
	- Maximum: 4 dice per relationship, d10 maximum die size
- **Strongholds & Facilities:**
	- Acquiring a stronghold: Use crafting clock system OR via arc OR purchase (GM sets price)
	- Upgrading stronghold: Use crafting rules or spend XP (4 XP per die increase)
	- Adding rooms/facilities: Each is a separate resource (3 XP for 1d4, or use crafting)

### Faction Arcs as Quest Hooks
Faction arcs should create visible consequences in the game world. When designing faction arcs, consider:

* **Arc Steps Requiring PC Intervention:**
	- Step 3 of Velvet Guild's "Establish Dockside Operations" might require PCs to eliminate a rival gang
	- Step 5 of Kingdom's "Secure Northern Border" might need PCs to retrieve an ancient defensive artifact
- **Arc Steps Creating Complications:**
	- Faction pursuing "Monopolize Grain Trade" creates food scarcity
	- Faction pursuing "Summon Ancient Power" unleashes dangerous magic
- **Failed Arc Steps:**
	- If faction fails an arc step during quick resolution, it might become a crisis requiring PC intervention
	- Or it might simply advance a rival faction's goals

## Requesting Aid from Factions

When PCs ask a faction for help (resources, personnel, information, etc.):

* **The Request Roll:**
	- **Pool:** Presence + Diplomacy/Persuasion + Relationship with Faction + any relevant buffs
	- **Complexity:** 7-11 based on the request's difficulty and faction's current situation
	    - Small favor (information, entry to location): 7
	    - Moderate favor (loan of resources, minor military support): 9
	    - Major favor (commit significant resources, take risks): 11
	- **Minimum Groups:** 0-2 based on how stressed the faction is
- **Modifiers:**
	- Faction currently at war or in crisis: +2 complexity
	- Request aligns with faction goals: -2 complexity
	- PC has completed recent quests for faction: Add 1d6 buff
- **Results:**
	- **Success:** Faction agrees, lends requested resources or provides aid
	- **Partial Success:** Faction agrees but with conditions, or provides less than requested
	- **Failure:** Faction refuses, may suggest alternative
	- **Botch:** Faction refuses AND relationship depletes one step
- **Loaned Resources:** When a faction lends resources to PCs:
	- Resources committed (effectively one step lower for faction)
	- When PCs complete the task or return the resources, faction rolls that resource once
	- On any 1s, the resource depletes permanently (damaged, lost, or consumed)

## Strongholds as Faction Resources

Strongholds are facilities that serve as a faction's base of operations. Not all factions need a stronghold, but many have them.
* **Stronghold as Resource:**
	- Treated like any other facility resource (e.g., "Hilltop Fortress 2d8")
	- Has a physical location in the game world players can visit
	- Can be depleted through siege, disaster, or neglect
	- When exhausted, the stronghold is destroyed or uninhabitable
- **Prerequisite for Other Facilities:** Many faction resources require a stronghold to exist:
	- "Infirmary 1d6" requires a stronghold with medical facilities
	- "Barracks 2d6" requires a stronghold with space for soldiers
	- "Library 1d8" requires a stronghold with secure storage
- **Acquiring a Stronghold:**
	- Via faction arc ("Establish a Base")
	- Through crafting system (large project, many segments)
	- Through conquest or negotiation (defeat another faction, claim theirs)
	- Through purchase (GM sets price, typically very expensive)
	- Quest reward (for PCs only)
* **Upgrading Strongholds:**
	- Spend faction XP to increase stronghold dice (4 XP per step)
	- Use crafting system to add new rooms/facilities
	- Complete faction arcs that involve expansion

## GM Guidelines

* **Frequency of Faction Turns:** Don't feel obligated to run every faction every turn. Focus on:
	- Factions pursuing active arcs
	- Factions in conflict with each other or PCs
	- Factions the PCs have strong relationships with
- **Generating Consequences:** If you can't immediately see how a faction's goals create interesting complications, consider:
	- Not statting that faction (just treat it as narrative background)
	- Changing the faction's goals to something that matters more
	- Waiting until the faction becomes relevant before giving it mechanics
- **Balancing Faction Resources:**
	- Small factions: 2-4 resources, mostly d4-d6
	- Medium factions: 4-6 resources, mostly d6-d8
	- Large factions: 6-8 resources, including d8-d10
	- Massive factions: 8+ resources, including d10-d12
- **Player Faction Control:** If the PCs ARE the leadership of a faction:
	- Players decide which actions to take
	- Players can delegate actions (GM rolls using quick resolution)
	- Players can personally undertake actions (resolved through play)
	- GM adjudicates results of quick resolution fairly
- **When Factions Die:** When all resources are exhausted, the faction dissolves:
	- Leadership might scatter to other factions
	- Some assets might be claimed by victors
	- Relationships might persist (but at lower values)
	- Consider if remnants form a new, smaller faction

## Examples of Play

### Example 1: Between-Session Faction Turn

_The Velvet Guild takes its turn between sessions._

* **GM prepares:**
	- Velvet Guild has 2 leaders, so gets 2 actions
	- Currently pursuing arc step: "Bribe the Harbor Master"
- **Action 1 - Shadowmaster Vex leads bribery attempt:**
	- Pool: 2d8 Wits + 2d6 Stealth + 2d4 Stolen Goods (the bribe) + 2d6 Informants (finding leverage)
	- Complexity 9 (the Harbor Master is cautious)
	- Rolls 3 groups above minimum - success!
	- Arc step completes, Guild earns 2 XP, spends 1 XP to define next step
	- Rolled a 1 on Stolen Goods - depletes to exhausted (bribe was expensive)
- **Action 2 - The Fence Network handles recruitment:**
	- Delegating to sub-faction
	- Pool: Fence Network resources + 2d4 Gold (from faction treasury)
	- Complexity 7 (recruiting street criminals is easy)
	- Success! Add new resource "Pickpockets 1d4"
- **GM notes for next session:**
	- Guild now has Harbor Master bribed (new relationship? or just narrative flag)
	- Guild is low on goods and gold
	- New pickpockets might get into trouble, creating a hook

### Example 2: PCs Request Aid

_The Iron Hawks need help assaulting a bandit fort and ask the City Militia for support._

* **Captain Mira makes the request:**
	- Pool: 2d6 Presence + 1d6 Diplomacy + 1d6 Relationship with Militia
	- Complexity 9 (significant military commitment)
	- Minimum 1 (Militia is currently stretched thin dealing with unrest)
- **Rolls 2 groups above minimum - success!**
	- GM: "Commander Brass agrees. He'll send a squad of militia fighters to support your assault—20 soldiers under Lieutenant Kade."
- **Mechanics:**
	- Militia lends "Soldiers 2d6" resource to the PCs for this mission
	- While committed, Militia treats Soldiers as 2d4 for other actions
	- When mission completes, GM rolls 2d6 for the soldiers
	    - If any 1s come up, soldiers deplete (casualties, desertions)
	    - Otherwise, they return home intact

### Example 3: Faction vs. Faction Conflict

_The City Watch launches a raid on Velvet Guild safehouses._

* **City Watch Action (quick resolution):**
	- Led by Watch Captain (individual leader)
	- Pool: 2d8 Captain's Might + 2d6 Tactics Skill + 3d6 Guards + 2d6 Informants
	- Targeting Guild's "Safehouse Network 2d6"
	- Complexity 9
	- Velvet Guild rolls 2d6 Safehouse Network + 2d6 Thieves as contested dice
- **GM rolls both:**
	- Watch: Gets 4 groups above minimum after overcoming contested dice
	- Decides to spend successes depleting Guild resources
	    - 2 successes deplete Safehouse Network: 2d6 → 2d4
	    - 2 successes deplete Thieves: 3d6 → 3d4
	    - Watch rolled 1 on Informants - depletes to 2d4 (some informants exposed)
- **Consequences for next session:**
	- Guild is weakened, might need PC help
	- Watch is gaining upper hand, but losing intelligence assets
	- Velvet Guild might retaliate, escalating the war

# Setting Definition Checklist
This is a setting agnostic system.  It's really just meant to be question resolution mechanics for a number of situations that exist at various scales that are common to RPGS, and especially games focused on exploration and survival in austere circumstances.  You might be asking yourself "Where's the spell list?" or "What about items?".  You'll need those.  The mechanics of this system don't provide them, but they do support them.  When designing your setting, here are the blanks we think you'll want to fill in:

## Core Mechanical Definitions

### Skills Available
- Complete list of skills that exist in this setting
- Which stats each skill typically pairs with
- Starting proficiency limits

### Equipment Catalog
- Weapons with dice pools and costs
- Armor with dice pools and costs
- Tools and kits with dice pools and costs
- Vehicles/mounts with full stat blocks and costs
- Consumables (potions, rations, etc.) with effects and costs

### Economy
- Currency system and denominations
- Starting wealth by background/origin
- Cost of living (meals, lodging, services)
- Availability by location type (hamlet vs. city)

## Magic & Supernatural
### Magic System (if present)
- List of casting skills and what they cover
	- Psionics, mutations, technology-as-magic, etc.
- Complete spell list with stat blocks
- Material components and costs
- Restrictions (who can cast, cultural attitudes)

### Divine/Miraculous Powers (if present)
- Pantheon or spiritual forces
- How divine casting differs from arcane
- Miracle list with stat blocks
- Requirements for divine favor
- Relationship mechanics with deities

## Character Creation Framework

### Origins/Ancestries
- Available species/peoples
- Any mechanical differences (special abilities, stat adjustments)
- Cultural context

### Backgrounds
- Social class, profession, or origin story options
- Starting equipment packages
- Suggested starting relationships
- Initial relationship with key factions

### **Starting Parameters**
- Standard starting XP (you say 30)
- Starting wealth
- Mandatory starting relationships
- First arc requirements

## World & Geography

### **Major Locations**
- Key cities, regions, nations
- Travel times between locations
- Terrain types and their mechanical impacts

### **Languages**
- What languages exist
- Who speaks what
- Does language matter mechanically? (If yes, define how)

### **Factions**
- Major organizations PCs might interact with
- Full faction stat blocks for important ones
- Common faction types (guilds, governments, etc.)

## Bestiary & Opposition

### **Common Enemies**
- Bandits, guards, wildlife, monsters
- Simplified stat blocks for mooks
- Fully-statted blocks for major threats
- Scaling guidance by threat level
- Loot Tables

### **NPCs**
- Generic stat blocks by role (merchant, guard, noble, etc.)
- Named important NPCs with full stats
- Quick generation guidelines

## Environmental & Hazard Context
- Setting-specific dangers (radiation zones, cursed forests, etc.)
- Growing debuff templates for setting hazards
- Environmental conditions and their effects

## Campaign Guidance

### **Typical Adventures**
- What do characters do in this setting?
- Common adventure hooks and structures
- Expected power progression

### **Integration Hooks**
- Why do PCs work together?
- Common starting scenarios
- Suggested first character arcs

### **Death & Replacement**
- What happens at death?
- Resurrection availability (if any)
- How to integrate new PCs mid-campaign
