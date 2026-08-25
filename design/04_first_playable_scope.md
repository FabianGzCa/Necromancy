# First Playable Scope

This document defines the scope of the first playable version of **Necromancy**.

Its purpose is not to represent the final content of the mod.

The goal of the first prototype is to determine whether the core combat idea works before investing time in secondary systems, content, or extensive progression.

---

## Prototype Goal

The first prototype should allow us to test the following hypothesis:

> Actively fighting alongside summoned creatures can create a distinct, strategic, and interesting experience without turning the player into a spectator.

If this core idea does not work, the remaining systems should be reconsidered before expanding the project further.

---

## Required Gameplay

The prototype should support the following basic sequence:

```text
Obtain or Receive a Summon
    ↓
Enter Combat
    ↓
Choose When to Summon It
    ↓
Fight Alongside It
    ↓
Enemy Reacts to Both Player and Summon
    ↓
Summon Consumes or Commits a Resource
    ↓
Summon Survives or Dies
    ↓
Player Adapts
    ↓
Encounter Ends
```

The complete progression gameplay loop does not need to be implemented yet.

---

## Minimum Summon Set

The prototype should use a very small number of creatures.

Initially:

**Two types of summons are enough.**

They should have clearly different functions.

For example, conceptually:

* one creature focused on offensive pressure;
* one creature focused on protection, control, or another distinct form of utility.

The specific creatures should be selected according to what is realistically available during implementation.

The objective is not to demonstrate content variety.

The objective is to demonstrate that choosing between different creatures can produce different decisions.

---

## Player Participation

The player must personally participate in combat.

The prototype should allow us to observe whether a useful relationship exists between:

* player actions;
* summon actions;
* enemy behavior.

A complete set of exclusive Necromancer abilities does not need to be designed yet.

If the basic player + summon gameplay does not work, adding additional abilities could hide the problem rather than solve it.

---

## Mana

The prototype needs some simple way of limiting summons.

The initial implementation can be deliberately simple.

It only needs to allow us to evaluate:

> Does the existence of a cost change when the player decides to summon?

The final mana model will be decided after observing the prototype's behavior.

---

## Soul Corruption

Soul Corruption is **not required for the first version of the prototype**.

It is a conceptually important system, but it introduces a second resource-management layer before we have determined whether the basic combat interaction works.

It should be introduced once there is a clear reason to test the additional decisions it is intended to create.

This allows us to separate two questions:

1. Is managing summons with a limited resource interesting?
2. Does adding Soul Corruption improve those decisions further?

---

## Soul Capture

The complete randomized soul-capture system is also unnecessary for validating the initial combat experience.

During the first prototype, souls can be obtained through a temporary or simplified mechanism.

The capture system should be designed when we need to test the gameplay loop of:

> fight → capture → collect → prepare.

---

## Preparation System

It is not necessary to initially implement:

* the final altar;
* the final interface;
* a complete specialized inventory;
* slot progression.

To test preparation, a simple way of selecting which summons are available is sufficient.

The temporary interface can be replaced later.

---

## Progression

The first prototype does not need:

* skill trees;
* multiple tiers;
* custom bosses;
* dozens of creatures;
* complete progression;
* extensive unlock systems.

Progression should be designed around a combat system that has already demonstrated that it can be enjoyable.

---

## UI and Visuals

The prototype's interface and visual presentation can be temporary.

The priorities should be:

1. functionality;
2. readability;
3. iteration speed.

It is not necessary to immediately create:

* the final radial menu;
* final animations;
* complex visual effects;
* custom models;
* final portfolio presentation.

These elements should be developed once the interactions they represent are sufficiently stable.

---

## Initial Test Scenario

The first test scenario should be small and repeatable.

It should allow us to observe:

* combat without a summon;
* combat with a summon;
* differences between two types of summons;
* enemy behavior;
* losing a summon;
* resource management;
* direct player participation.

Ideally, the same encounter should be repeatable multiple times so that different decisions can be compared.

---

## Success Questions

After testing, we should be able to answer:

### Combat

* Is fighting alongside the creatures enjoyable?
* Does the player still feel responsible for the outcome?
* Does the summon create decisions or merely add damage?
* Is there a clear situation where choosing not to summon is better?

### Summons

* Do the two types of creatures produce different behavior?
* Does the player understand when each one is useful?
* Does losing a creature matter without being excessively frustrating?

### Enemies

* Do enemies react appropriately to multiple targets?
* Can they continue applying pressure to the player despite the presence of summons?
* Can summons easily exploit enemy AI behavior?

### Resources

* Does the cost of summoning produce decisions?
* Does the player understand how much of the resource they are committing?
* Does the resource recover too quickly or too slowly?

### Identity

Finally:

> Does this feel like the beginning of a Necromancer, or simply normal combat accompanied by an allied NPC?

This will be one of the most important criteria for deciding the next iteration.

---

## Explicitly Out of Scope

The first playable version does not need to include:

* the complete Soul Corruption system;
* the complete soul collection system;
* final progression;
* a skill tree;
* a complete economy;
* endgame content;
* custom bosses;
* a complete ritual system;
* the final interface;
* a large number of summons;
* final balance;
* final assets;
* extreme optimization;
* exhaustive technical documentation.

These elements can be introduced later if the core system proves worth developing further.

---

## Next Step After the Prototype

Once a first playable version exists, the process will be:

```text
Implement
    ↓
Playtest
    ↓
Observe Problems
    ↓
Record Results
    ↓
Change Design
    ↓
Test Again
```

From that point onward, documentation should primarily reflect real decisions obtained through iteration rather than speculative design alone.
