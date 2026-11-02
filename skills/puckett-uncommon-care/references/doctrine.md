# Doctrine: Josh Puckett's uncommon care

> **Provenance.** Source: Dive Club, *"Josh Puckett – Crafting interfaces with
> uncommon care"* (March 2026, https://www.youtube.com/watch?v=wym3V9FycTk).
> Josh's own, much fuller treatment is his library **Interface Craft**
> (https://www.interfacecraft.dev). **This file is an AI-assisted reading of the
> interview and of third-party summaries of it, lightly edited. It has not been
> checked against a transcript, and it borrows nothing from Interface Craft.**
> Quotes marked *(summary)* come from a third-party write-up of the episode, not
> from the audio. Treat everything else as paraphrase, and go to Josh's own
> work for the real thing. This project is not affiliated with or endorsed by
> Josh Puckett or Dive Club.
>
> `SKILL.md` cites the lenses as **L1–L8** and the other sections as **§N**. If
> you renumber them, update every citation there (`grep -nE 'L[0-9]|§' SKILL.md`).

## Operating principle

**Execute limited scope to an extraordinarily high bar, rather than expanding
scope.** Cheap generation makes it easy to build *more*. Uncommon care spends
that capacity going deeper on what is essential. The goal is software that is
loved rather than "functional, but forgettable", where small and unexpected
details tell the person *"I value you, your time, and I care about you"*
*(summary)*.

---

## §1. Range, then depth

Explore broadly first, then go deep once a concept works: *"conceptual range and
then conceptual depth"* *(summary)*. Range means several genuinely different
approaches to the same moment, not variations on one. Depth means taking the
one that works and pushing it until it is unmistakably itself.

## §2. Tune it live, by feel

Feel can't be specified in prose. Expose the parameters that drive an
interaction (duration, spring, distance, intensity) as live controls, and
adjust them while touching the thing. Josh describes building a playground for
exactly this, with graphics *"driven by some parameters"* *(summary)*. The tuned
values are the design. A description of them is not.

## §3. Restraint is the method

Depth applies to what already exists. A new control, view or feature has to
earn its place by raising the bar on the essential scope. Usually it shows
that the existing pieces weren't fully used. Not every surface needs every
quality, either: a settings list doesn't have to be fidgetable. Leaving a
lens out is often the right call.

---

## The eight lenses

Use these to look at an **interaction**: one moment a person moves through. They
are not a scorecard. Pick the two or three that bite on this moment and skip
the rest.

### L1. Fidgetability
Interfaces that invite play: *"play and letting you fidget with things"*
*(summary)*. Where could a tactile interaction replace a static one? What
invites touch, drag or exploration, and what feels dead? Is there a "what
happens if I…" moment that pays off? Josh reworked an onboarding flow because it
showed only five fixed options, which didn't feel exploratory enough
*(summary)*.

### L2. Morphing and flow continuity
Controls that turn into the controls you need next, instead of spawning
pop-ups. On direct manipulation: *"Everything you need on it is already on it"*
*(summary)*. Where do modals, popovers or page swaps break spatial continuity?
Does each transition feel like the interface *becoming* the next thing, or
replacing itself?

### L3. The three-slider problem
*"I want to change three parameters at one time. How do I do that?"*
*(summary)*. Josh's answer was a single control driving several parameters
along a curve, so one gesture covers a wide range of outcomes. Where is
complexity exposed that one control could absorb? Which labels or settings are
making the person do work the interface could do?

### L4. Hospitality and emotional arc
Wrapping an essential function in an experience that feels *"so unique and so
differentiated"* *(summary)*, in the spirit of hospitality: fine dining, a good
hotel, a library. What is the emotional journey through this moment? Where is
the surprise, the delight or the earned trust? Does it say "here is a function",
or does it say it's glad you came?

### L5. Conceptual range → conceptual depth
§1, applied to one moment. Brainstorm 3–5 radically different approaches. Then
for the strongest, describe what "taking it to 11" looks like: the custom
detail nobody else would bother with.

### L6. Reduction and essence
The Shaker idea, as Josh puts it: *"Make it as well as you can and make it as
simple as you can"* *(summary)*. He also points to Dieter Rams ("less, but
better") and to Bruce Lee's line about hacking away the unessential. What can be
cut entirely? Which nice-to-haves dilute the core? What inconsistency
(mismatched heights, redundant labels, mixed metaphors) would a distilled
version simply not have?

### L7. Metaphor integrity
Josh chose a library metaphor for Interface Craft because it is *"inherently
open-ended"* *(summary)*, and it went as far as a personal library card. Is
there a central metaphor? Is it carried all the way through? Which real-world
qualities of it are still unexplored? Which interactions break it?

### L8. Sound, motion and materiality
Custom sounds and physical-feeling interactions, like a card slotting into
place or a scratch-off reveal: *"a lot of sounds that you know show you
things"* *(summary)*. Could sound reinforce this moment, and where would it get
annoying? Do surfaces have weight, texture or a response to light? Is the
motion communicating physics and intent, or just decorating a transition?
