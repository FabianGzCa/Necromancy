# Combat Design

This document defines the fundamental combat goals of **Necromancy**.

It is not intended to establish final statistics, timings, costs, or numerical values.

Its purpose is to determine what kind of decisions the system should produce and what conditions must be met for playing as a Necromancer to be interesting.

---

## Combat Fantasy

The player should feel like a master of death who uses defeated creatures as tactical tools.

The Necromancer's power does not come exclusively from the player's own actions or exclusively from their summons.

The identity of the combat style emerges from the interaction between both.

The player reads the situation, deploys the appropriate creatures, takes advantage of the opportunities they create, and decides how many resources they are willing to commit.

---

## Combat Goals

Necromancy combat should satisfy the following goals.

### Active Player Participation

The player must participate meaningfully throughout the encounter.

Summoning correctly should provide an advantage, but it should not replace the player's own actions.

### Meaningful Summon Choices

Choosing a creature should depend on the situation.

There should not be a single summon that is always the optimal answer.

### Resource Commitment

Summoning should represent a decision.

Using power now should modify the options available later.

### Adaptation

Encounters should produce situations that force the player to modify their initial plan.

### Preparation

Decisions made before combat should influence the options available during the encounter.

### Skill Expression

Two players with the same repertoire should be able to achieve different results depending on:

* their decisions;
* their positioning;
* their timing;
* their resource management;
* their knowledge of creatures and enemies.

---

## Player Role

The Necromancer should not function as a commander completely separated from combat.

The player remains a direct participant in the encounter.

Summons should complement the player's actions.

The final design must determine exactly what tools the player has in addition to summoning creatures.

These tools could relate to aspects such as:

* positioning;
* personal attacks;
* abilities;
* applying status effects;
* enemy control;
* interactions with the player's own summons.

These possibilities are not yet considered final design decisions.

The fundamental rule is:

> The player's actions and the summons' actions should benefit each other.

---

## Summon Roles

Creatures should primarily be differentiated by their tactical function rather than only by their statistics.

Possible conceptual categories include:

### Offensive

Creatures whose main purpose is to apply pressure or deal damage.

### Defensive

Creatures capable of protecting the player or temporarily absorbing enemy attention.

### Control

Creatures specialized in modifying enemy movement, positioning, or behavior.

### Support

Creatures that temporarily expand the tactical possibilities of the player or other summons.

### Specialized

Creatures that are particularly useful against specific situations, enemies, or types of encounter.

These categories are design tools and do not necessarily need to exist as visible classes for the player.

A single creature may partially fulfill more than one role.

---

## Every Creature Should Have Value

A more powerful creature should not automatically make all previous creatures irrelevant.

This does not mean that every creature needs to have equal power.

Creatures can retain value through differences in:

* cost;
* speed;
* survivability;
* function;
* availability;
* synergies;
* specialization;
* associated risk.

Progression should provide new possibilities and combinations rather than exclusively replacing older creatures with numerically superior versions.

---

## Resource Decisions

### Mana

Mana primarily represents available capacity.

Using a summon should reduce the immediate or future options available through that resource.

The design needs to determine whether mana:

* is consumed;
* is reserved;
* regenerates during combat;
* is recovered when a creature disappears;
* uses a combination of these behaviors.

The choice should be based on which model produces better decisions, not solely on which one appears most thematically appropriate.

### Soul Corruption

Soul Corruption represents accumulated risk.

It should avoid becoming simply a second mana bar.

To justify its existence, it must create different decisions.

For example:

* mana could limit how much the player can do;
* corruption could modify how much the player should do.

If testing shows that both resources essentially produce the same decision, Soul Corruption should be reconsidered.

---

## Encounter Flow

A conceptual encounter structure could be:

```text
Read Situation
    ↓
Choose Initial Response
    ↓
Deploy Summon
    ↓
Fight Alongside Summons
    ↓
Observe Enemy Response
    ↓
Manage Resources
    ↓
Adapt
    ↓
Commit More Power or Conserve
    ↓
Resolve Encounter
```

This structure must be evaluated through prototypes.

The objective is for the player to repeatedly move through small cycles of:

> observe → decide → act → evaluate → adapt.

---

## Enemy Interaction

Enemies must recognize the presence of summons in some way.

If every enemy completely ignores the army, summons may become little more than additional sources of damage.

If every enemy always attacks summons, they may become excessively efficient defensive tools.

The correct behavior will likely depend on the context, enemy, and type of summon.

These interactions should be designed to create understandable decisions and avoid overly simple dominant strategies.

---

## Failure and Recovery

Making a mistake should not automatically eliminate every possibility of recovery.

Losing a summon may reduce the player's available options and increase pressure, but there should still be room to react.

The system should avoid negative spirals such as:

```text
One Mistake
    ↓
Loss of Summon
    ↓
Loss of Resources
    ↓
Reduced Ability to Recover
    ↓
More Summon Losses
    ↓
Unavoidable Defeat
```

The appropriate degree of recovery must be determined through testing.

---

## Anti-Passive Design

The primary design threat to the system is:

> The player summons creatures and waits while they complete the encounter.

The system should prevent this through its fundamental interactions rather than through artificial penalties alone.

Solutions should aim to make active player participation naturally increase the effectiveness of their creatures.

A good result would be:

> Summons are powerful when the player knows how to take advantage of them.

Rather than:

> Summons are deliberately useless when the player is not attacking.

---

## Counterplay and Weaknesses

The Necromancer needs situations where their usual decisions are not automatically optimal.

Enemies and encounters could require adaptation through factors such as:

* mobility;
* area damage;
* target priority;
* enemies resistant to particular functions;
* direct pressure on the player;
* spaces where certain creatures are less effective.

These possibilities should be designed without creating enemies whose sole purpose is to completely invalidate the class.

---

## Combat Readability

The player should be able to understand:

* which summons are active;
* what they are doing;
* when they are in danger;
* how many resources are committed;
* what is causing Soul Corruption;
* when an important decision has produced a consequence.

The complexity of the system should exist in its decisions rather than in interpreting confusing information.

---

## Prototype Questions

The first combat prototype should primarily help answer:

1. Is fighting alongside a summon enjoyable?
2. Does the player have enough reasons to participate personally?
3. Is there a meaningful decision about when to summon?
4. Does losing a summon change the encounter in an interesting way?
5. Do enemies react reasonably to both the player and the creature?
6. Does the summon feel like a tactical tool or simply additional damage?
7. Can we create two creature types that produce clearly different decisions?

If the prototype cannot answer these questions positively, adding more creatures, progression, or resources will not solve the fundamental problem.
