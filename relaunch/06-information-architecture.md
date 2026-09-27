# 06 — Information Architecture

## Garrett Planes 2–3 — Scope and Structure

## 1. Scope

The initial relaunch includes:

- institutional identity
- philosophy
- company history
- First Flight
- Works
- Research
- Ideas
- Experiments
- Papers
- Observatory
- portfolio entries
- product demonstrations
- responsive navigation
- search/discovery where justified
- contact/collaboration path

Later additions may include:

- interactive research tools
- public datasets
- community programs
- education / Flight School
- fellowship programs
- deeper laboratory interfaces

## 2. Proposed top-level navigation

Primary:

- **Works**
- **Research**
- **Ideas**
- **Company**
- **Explore**

The exact labels should be validated during skeleton design.

## 3. Sitemap

~~~text
/
├── works/
│   ├── focusa/
│   ├── uiai-engine/
│   └── ...
│
├── research/
│   ├── observatory/
│   ├── papers/
│   ├── experiments/
│   └── areas/
│
├── ideas/
│   ├── philosophy/
│   ├── flight-notes/
│   └── first-flight/
│
├── company/
│   ├── mission/
│   ├── principles/
│   └── history/
│
└── explore/
    ├── experiments/
    ├── demonstrations/
    └── ...
~~~

## 4. Content entities

### Work

Represents a built technology.

Fields:

- title
- status
- summary
- problem
- capability
- evidence
- demonstration
- technical details
- links
- related research
- related ideas
- date / version

### Research Area

Represents a continuing frontier.

Fields:

- title
- question
- description
- related papers
- experiments
- works
- status

### Experiment

Fields:

- experiment ID
- question
- hypothesis
- method
- observation
- result
- interpretation
- limitations
- next step
- status

### Paper

Fields:

- paper ID
- title
- abstract
- body
- date
- status
- references
- related research
- related experiments
- related works

### Idea

Fields:

- title
- thesis
- body
- date
- related principles
- related research
- related works

### Flight Note

Fields:

- title
- Above
- Below
- Flight
- date
- related items

### Principle

A persistent institutional belief.

Examples:

- Discover truth. Give it form.
- The human remains human.
- Technology is an instrument.
- Metaphysically open. Evidentially rigorous.

## 5. Relationship graph

The core graph:

~~~text
Question
   ↓
Research Area
   ↓
Experiment
   ↓
Evidence
   ↓
Discovery
   ↓
Work
   ↓
Human Capability
~~~

And:

~~~text
Idea
 ↓
Hypothesis
 ↓
Experiment
 ↓
Evidence
 ↓
Revision
~~~

A Work should be able to point back toward the research and evidence that informed it.

## 6. Observatory taxonomy

Each research item can have one or more states:

- Known
- Observed
- Suspected
- Question
- Experiment
- Emerging
- Disproven
- Crystallized

These are epistemic states, not marketing labels.

## 7. URL philosophy

URLs should be:

- short
- human-readable
- durable
- independent of implementation details

Avoid URLs that expose CMS-specific structures.

## 8. Navigation model

The global navigation should answer:

> Where can I see what they built?

→ Works

> What are they investigating?

→ Research

> What do they think?

→ Ideas

> Who are they?

→ Company

> What else can I explore?

→ Explore

## 9. Cross-linking

Every substantial content page should expose related material.

Example:

**Focusa**
→ related research
→ related experiments
→ related ideas
→ demonstrations

**Experiment**
→ resulting Work
→ related Paper
→ next experiment

This makes the site feel like an institutional knowledge system rather than a set of isolated pages.

## 10. Information hierarchy

The hierarchy should generally be:

**Institution → movement → artifact → evidence → deeper context**

rather than:

**navigation → marketing headline → CTA → feature grid**

## 11. Scope boundary

The first release should not attempt to build a complete research publishing platform.

The information model should be future-proof, but the initial implementation should remain simple.

Simplicity is preferred over ceremonial infrastructure.
