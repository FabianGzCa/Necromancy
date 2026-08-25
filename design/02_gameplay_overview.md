# Gameplay Overview

This document describes how **Necromancy** is experienced from the player's perspective and how its main gameplay systems interact with each other.

Its purpose is not to define numerical values or final balance rules, but to establish the overall structure of the experience before implementation begins.

---

## Gameplay Loop

Necromancy's main gameplay loop revolves around exploration, acquiring new souls, preparing an army, and using it strategically during combat.

An initial version of the loop is:

```text
Explore
    ↓
Defeat Enemies
    ↓
Capture Souls
    ↓
Expand Soul Collection
    ↓
Prepare Army
    ↓
Enter Combat
    ↓
Summon and Manage Creatures
    ↓
Manage Mana and Soul Corruption
    ↓
Adapt to the Encounter
    ↓
Defeat Stronger Enemies
    ↓
Acquire More Valuable Souls
    ↓
Explore Further
```

This loop should not be interpreted as a rigid sequence.

Because of Hytale's sandbox nature, players can engage with Necromancy to different degrees and freely alternate between this experience and other gameplay styles.

The main intention is for exploration and combat to provide new strategic possibilities, while those new possibilities allow the player to face progressively more demanding situations.

---

## Core Resources

There are currently three main conceptual resources.

### Souls

Souls represent creatures that the player has captured and can later use as summons.

They are simultaneously:

* a collectible resource;
* a combat tool;
* a form of progression;
* a reward for exploring and facing new creatures.

### Mana

Mana limits how much power the Necromancer can maintain during combat.

Summons should require a significant enough mana investment that deploying a creature has consequences for the options available afterward.

The exact consumption, reservation, and regeneration rules still need to be defined and tested.

### Soul Corruption

Soul Corruption represents the risk associated with excessive use of necromancy.

Its purpose is to introduce a second dimension of resource management.

Mana primarily answers:

> How much power can I use?

Soul Corruption should primarily answer:

> How much risk am I willing to take in order to use that power?

Its exact values, sources, and consequences are still to be defined.

---

## Soul System

When defeating certain creatures, the player can obtain their souls.

These souls allow new creatures to be added to the Necromancer's repertoire.

The system aims to directly connect progression with:

* exploration;
* combat;
* discovering creatures;
* facing more dangerous enemies.

Obtaining a powerful creature should not depend solely on leveling up or unlocking an abstract ability.

The player must interact with the world to find and defeat it.

The chance of capturing a soul may depend on different factors, including the player's contribution to defeating the enemy.

The exact capture rules have not yet been defined.

### Soul Storage

Souls will be stored in a dedicated system with limited capacity.

The player will be able to own more souls than they can use simultaneously, forcing them to decide which ones they want to prepare for a particular adventure.

Storage capacity may increase through progression.

The exact limits must still be determined through design and testing.

---

## Summoning

Summoned creatures should not function as permanent pets.

Their primary purpose is to act as tactical tools during combat situations.

Each summon should provide some specific value, for example:

* offensive pressure;
* control;
* protection;
* distraction;
* support;
* specialized utility.

Not every creature needs to be equally powerful, but every creature should have a valid reason to be used.

Summons:

* can die;
* can be attacked by enemies;
* consume resources;
* should not resolve encounters independently of the player;
* must require decisions about when and why to use them.

The maximum number of simultaneous summons and their costs have not yet been defined.

---

## Preparation

Preparation is an important part of the Necromancer's identity.

The player will be able to own a larger collection of souls than the selection immediately available during an adventure.

Before entering dangerous situations, the player will need to decide which creatures they want to have available.

A station, altar, or another necromancy-related element could be used to organize this selection.

The intention is to create questions such as:

> What type of enemies do I expect to encounter?

> Do I need damage, protection, control, or a specialized creature?

> Which creatures justify the cost they represent?

The player should not be able to freely replace their entire repertoire at any moment, as this would remove much of the strategic value of preparation.

The exact implementation of this system is still to be defined.

---

## Progression

Necromancer progression should primarily relate to progressively mastering death and interacting with the world.

Initially, the player should have few options and control relatively weak creatures.

As they progress, they will be able to:

* discover new souls;
* access new creatures;
* learn new rituals;
* increase their preparation capacity;
* expand their strategic options;
* control progressively more powerful creatures.

Increasing power should also introduce additional decisions or risks.

Progression should not consist solely of increasing statistics.

Ideally, it should expand the player's available decision space.

---

## Combat

The player must actively participate during encounters.

The Necromancer fantasy revolves around commanding and taking advantage of an army of creatures, but the player should not become a spectator.

During combat, the player will need to make decisions related to:

* when to summon;
* which creature to use;
* how much mana to commit;
* how much corruption risk to accept;
* how to react when a summon dies;
* when to conserve resources;
* how to personally complement the actions of their creatures.

Summons should create opportunities for the player, not replace them.

The exact model for active Necromancer participation still needs to be designed and will be one of the primary goals of Combat Design.

---

## Risk and Consequences

Using necromancy should provide power in exchange for committing resources or accepting risks.

Potential consequences include:

* loss of resources;
* increased Soul Corruption;
* reduced options for the remainder of the encounter;
* the need to modify the original plan;
* reduced defensive capability.

The goal is not to punish the player for using their class.

Risk should create interesting decisions.

A consequence should only remain if it forces the player to consider alternatives and improves the combat experience.

---

## Open Design Questions

The following questions still need to be resolved through design, prototyping, and testing:

* What actions does the Necromancer personally perform while their creatures fight?
* How do we prevent summons from completing encounters without meaningful player participation?
* How exactly does mana work while summons are active?
* How does Soul Corruption increase and decrease?
* What consequences does Soul Corruption produce?
* How many creatures can remain active simultaneously?
* How are summons selected and controlled during combat?
* What exactly happens when a summon dies?
* How is a weak creature functionally differentiated from a powerful creature?
* How do creatures obtained during early progression remain valuable?
* What parts of preparation can be modified during an adventure?
* How is all this information communicated without creating an excessively complex interface?

These questions do not all need to be resolved before the first prototype.
