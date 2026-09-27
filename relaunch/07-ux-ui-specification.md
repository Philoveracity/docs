# 07 — UX / UI Specification

## Garrett Planes 4–5 — Skeleton and Surface

## 1. Skeleton principle

Do not begin with colors, effects, or decorative visuals.

First establish:

- layout
- hierarchy
- navigation
- content blocks
- interaction
- responsive behavior
- calls to action
- content relationships

## 2. Homepage skeleton

~~~text
┌─────────────────────────────────────────────┐
│ PHILOVERACITY       Works Research Ideas   │
│                    Company Explore          │
├─────────────────────────────────────────────┤
│                                             │
│                 LOVE OF TRUTH               │
│                                             │
│            TEACH PEOPLE TO FLY.             │
│                                             │
│  We build technologies that expand human    │
│  possibility.                               │
│                                             │
│              [ Explore the Work ]           │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│          DISCOVER TRUTH.                    │
│          GIVE IT FORM.                      │
│                                             │
│          Research → Works → Impact          │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│                    WORKS                    │
│                                             │
│      Focusa          UIAI Engine            │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│                  RESEARCH                   │
│                                             │
│    Questions / Experiments / Observatory    │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│              THE FIRST FLIGHT               │
│                July 4, 2008                │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│       THE HUMAN REMAINS HUMAN.              │
│       THE MACHINE REMAINS A MACHINE.        │
│                                             │
├─────────────────────────────────────────────┤
│                                             │
│                PHILOVERACITY                │
│               LOVE OF TRUTH                 │
└─────────────────────────────────────────────┘
~~~

This is a structural wireframe, not final copy or visual design.

## 3. Homepage requirements

The homepage should:

- establish identity immediately
- expose the mission
- expose actual Works
- expose Research
- offer a path into philosophy
- introduce the First Flight without requiring it
- maintain visual breathing room
- avoid overwhelming the visitor with navigation

## 4. Work page skeleton

~~~text
Title
Status
One-line capability

What becomes possible?

Demonstration

The limitation
The instrument
The capability

How it works

Evidence / results

Related research

Related ideas

Next
~~~

The primary question is always:

> What can a human do now that they couldn't do before?

## 5. Research page skeleton

~~~text
Research Area

Question

What we currently know

What we suspect

What we're testing

Experiments

Evidence

Related Works

Open questions
~~~

## 6. Experiment skeleton

~~~text
EXP-001

Question

Hypothesis

Method

Observation

Result

Interpretation

Limitations

What changed?

Next experiment
~~~

## 7. Paper skeleton

~~~text
P001

Title
Abstract
Status
Date

Body

Evidence
References

Related experiments
Related works
Related ideas
~~~

## 8. Observatory skeleton

The Observatory should feel like a live map of the frontier.

Possible filters:

- Known
- Observed
- Suspected
- Question
- Experiment
- Emerging
- Disproven
- Crystallized

A user should be able to understand not only conclusions, but epistemic status.

## 9. Navigation

Desktop:

- restrained global header
- Philoveracity mark
- five primary destinations
- optional utility action

Mobile:

- logo
- menu
- minimal utility

Avoid a large SaaS dashboard-style mega-navigation.

## 10. Surface direction

### Base

- deep neutral / near-black
- warm white
- restrained gray hierarchy

### Signal

Existing Philoveracity red.

Red should communicate:

- action
- selected state
- discovery
- emphasis
- experiment
- important transition

### Secondary highlight

Open design question.

Do not choose merely because it is fashionable. Test candidates against:

- accessibility
- print behavior
- dark/light surfaces
- scientific/institutional feel
- compatibility with existing red
- emotional meaning

## 11. Typography

Typography should balance:

**precision** — technical credibility

with:

**space** — philosophical depth

Avoid overly futuristic display fonts that make the company look like a game or cyberpunk brand.

## 12. Imagery

Prioritize:

- actual products
- prototypes
- real people
- real environments
- research artifacts
- physical materials
- machines
- interface details
- landscapes and scale

Use abstraction where it communicates an idea, not merely atmosphere.

## 13. Motion

Use motion to show:

- transformation
- causality
- discovery
- signal
- emergence
- movement from abstract to concrete

Avoid perpetual background motion.

## 14. Accessibility

The system must support:

- strong contrast
- reduced motion
- keyboard navigation
- semantic structure
- readable typography
- accessible interaction states
- screen-reader navigation

Red must never be the only indicator of state.

## 15. Responsive design

The information hierarchy should remain intact on mobile.

Do not simply stack desktop cards.

Mobile should be designed as a first-class reading and exploration experience.

## 16. Expression layer

After the five Garrett planes are complete, conduct an explicit Expression review.

Ask:

1. Does the site feel like Philoveracity?
2. Does it communicate Love of Truth without becoming abstract?
3. Does it demonstrate real technology?
4. Does it preserve human agency?
5. Does the visual language express invisible → visible?
6. Does the First Flight feel authentic rather than manufactured?
7. Could this site belong to a generic AI company?
8. Does the site make people curious about what Philoveracity will discover next?

The eighth question is especially important.

The website should not merely explain what Philoveracity has already done.

It should make the frontier feel alive.

## 17. Implementation boundary

The final UI specification should be translated into:

- route definitions
- content schemas
- reusable components
- responsive layouts
- design tokens
- content templates
- animation primitives
- accessibility requirements
- implementation tickets

No production implementation should begin until the structural skeleton has been reviewed.

## 18. Current implementation philosophy

> **Simplicity is always better.**

Build the smallest system capable of expressing the institutional model.

Do not build CMS complexity, animation infrastructure, research machinery, or interaction frameworks merely because the architecture can support them.

The website should remain an instrument for communicating and exploring Philoveracity—not become another product that Philoveracity has to maintain.
