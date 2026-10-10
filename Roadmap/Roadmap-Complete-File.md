Here it is. One document, ready to paste into Wiki-tree.md. Written for GitHub markdown, so it reflows on the tablet.

---

```markdown
# THE WIKI TREE
### The World Model of Edencore

Consolidated from the Edencore4 thread.
For the roadmap folder. Do not edit the
sections marked LOCKED without the
architect's word.

---

## 1. WHAT THE WIKI TREE IS

The Wiki Tree is the World Model of the
Edencore Council. It is one structure with
two names, because it is read in two ways:

- **The tree** — where things sit.
  Categories, layers, hierarchy.
  Cosmos → planet → biome → home → room
  → object → detail.

- **The world model** — how things work.
  Properties, relationships, change.
  Water flows downhill. Fire needs air.
  Plants die without light.

The tree is the index. The world model is
the entry. Same file, two views.

**What it is not:**

- Not a vector database
- Not an embedding space
- Not a coordinate grid
- Not a copy of Wikipedia
- Not an LLM
- Not an encyclopedia

The council is symbolic. The Wiki Tree
remains symbolic — a structured grammar the
council reasons over.

---

## 2. THE GRAMMAR AND THE VOCABULARY

This is the central idea. It is what makes
the model small enough to fit a phone and
large enough to read any environment.

**The grammar is small and fixed.**
**The vocabulary grows freely.**

Most AI tries to memorise the world. Millions
of facts, hand-coded, forever growing. Cyc
tried this for forty years and collapsed
under its own weight.

Edencore stores patterns, not facts.
A small grammar, applied to any content.

The difference between a dictionary and a
language. One never ends. The other lets you
say anything.

---

## 3. THE THREE LAYERS

The Wiki Tree is built in three layers,
in this sequence. Each layer is a version.

### Layer 1 — PRIMITIVES (V11, fixed)

Eleven relations. The connectors. The
grammar. Written once. Never changes.

| # | Primitive | Meaning |
|---|---|---|
| 1 | is_a | X is a type of Y |
| 2 | has_part / part_of | Composition |
| 3 | located_in | Containment / position |
| 4 | attribute_of | Properties |
| 5 | causes | Direct effect |
| 6 | enables | Makes possible |
| 7 | prevents | Stops or blocks |
| 8 | before / after | Time sequence |
| 9 | similar_to | Resemblance |
| 10 | associated_with | General connection |
| 11 | not | Negation |

**Open items before Layer 1 locks:**

- **`occurs_at`** — absolute date position
  (WWII occurs_at 1939–1945). Different from
  before/after, which are relational.
  Restore as #12 or accept that the tree
  cannot answer absolute-date questions.
- **Direction** — every relation needs its
  direction defined. Which way does
  `attribute_of` point? If direction is
  not fixed in the file, the JSON will
  contain mixed-direction triples and the
  reasoning engine will fail silently.

### Layer 2 — INSTANCES (V11+, grows)

The content. `[A] — relation — [B]`
triplets. Stored as JSON, not as code.

Target for V11: 500–1,000 curated entries.
Enough to read a kitchen, a garden, an
aquarium. Growth after that is on demand,
one entry at a time.

This is the nautilus principle applied to
knowledge: one chamber at a time.

### Layer 3 — SCHEMA RECOGNISERS (V12)

Code functions that look at the primitive
graph and recognise patterns. Not data.
Lenses.

A schema is not a thing you store. It is
something the Council *notices* when the
right primitives are present.

~20 image schemas. The bodily vocabulary
for space and action. Every human uses
them to reason about motion, force, and
change. Every abstract concept is built
on top of them.

| Schema | What it means |
|---|---|
| Container | Inside / outside, full / empty |
| Source-Path-Goal | Start → journey → end |
| Link | Two things connected |
| Part-Whole | Parts make a whole |
| Up-Down | Rise / fall, more / less |
| Balance | Steady / tipped |
| Blockage | Path is stopped |
| Force | Push / pull / resistance |
| Center-Periphery | Core vs edges |

**The schemas are recognisers, not data.**
They detect patterns over the primitives.
They do not store new facts.

Schemas are what make the Council *feel*
like it understands, rather than just
recalls. They are the hard part. They come
last.

---

## 4. THE OPTIMUM WORLD

The Wiki Tree is not a description of the
world as it happens to be.

It is a description of the world as it is
**converging toward**. An optimum.

A human is already at that optimum.
Two arms, two legs, one head. Hunger,
sleep, fear, love. Same everywhere.
Same for two hundred thousand years.

An LLM is not at that optimum yet. Large,
wasteful, prone to invention. But it is
converging. In time, the field will settle
on something tighter.

The Wiki Tree describes that settled form.
The target, not the transitional present.

**Why this is different:**

- Wikipedia describes the world as it is
  now. Messy, transitional.
- Cyc tried to describe everything. It
  collapsed.
- Edencore describes only what has
  converged. A far smaller set. Far more
  stable. The only set a council of five
  voices could hold in a phone.

**Convergence, not diversity.**

Farms will standardise. Schools will
standardise. Factories will standardise.
All farm IoT will be the same. The world
is not a thousand different worlds. It is
one world, described from many positions.

---

## 5. SCOPE — IoT STRUCTURE

The Wiki Tree's domain is **IoT structure**.
The shape of connected devices. How sensors
connect. How a farm's IoT is laid out. How
a factory line is arranged.

The Council does not address politics. It
does not address social questions. Those
are not in the domain. There is nothing to
include and nothing to leave out.

**The test for what belongs:**

If it changes when the political system
changes, it does not belong.

If it stays the same, it belongs.

An optimal IoT works in any socioeconomic
system. A farm sensor network is the same
whether the farm is a family smallholding,
a cooperative, a corporation, or a state
collective. The sensors do not care.

The optimum is invariant. It is structural,
not ideological.

---

## 6. RULES OF FACT

**Absolute vs Moving**

- **Absolute** — continents, capitals,
  physical constants. Belong in the tree.
- **Moving** — populations, leaders, GDP,
  weather. Fetched from outside.

The tree never holds what changes.
The Council never claims certainty about
what moves.

**Bands, not values**

The Council does not store "Everest is
8,848 metres." It stores "Everest is
Band 5 (colossal), an exemplar of the
mountain range category."

Facts are categorised by band (1–5), with
a named exemplar for comparison, and a
Band 0 for the unknown.

This is how humans actually reason: fuzzy
categories, not precise measurements.

---

## 7. THE REASONING ENGINE

Three operations. No more.

- **Transitive closure** — Paris is_in
  France, France is_in Europe, therefore
  Paris is_in Europe.
- **Attribute arithmetic** — GDP / population
  = GDP per capita.
- **Comparison and ordering** — A > B,
  B > C, therefore A > C.

**The three-link limit.**

The Council reasons three links deep.
Beyond that, it stops and says so.

The limit is not a technical constraint.
It is a promise.

---

## 8. THE SAFETY BOUNDARY

Three constitutional rules. Not technical
limits. Promises.

1. **No implied causation.** Only state
   what is explicitly defined.
2. **No generalisations about human
   populations.** Only sourced, dated
   metrics, never adjectives.
3. **No unsupported extrapolation.** If
   the chain breaks, say so.

---

## 9. THREE RULES OF BUILDING

1. **Curate, don't scrape.** 7,000 chosen
   facts beat 100,000 auto-generated ones.
   This is the lesson of Cyc.
2. **Primitives first, facts second.**
   Get the grammar right, and any fact fits.
3. **Offline first, network second.**
   The Council runs on the tree alone.
   Wikipedia and Wikidata are enrichment,
   not foundation.

---

## 10. THE SCALE

| Phase | Size |
|---|---|
| V11 | Primitives + 500–1,000 curated instances |
| After V11 | Grows organically, one entry at a time |
| 11,500 | Potential upper limit, not a requirement |

The 11,500 figure was a potential milestone,
not a deadline. The nautilus rule: start
small. Add one chamber at a time.

---

## 11. WHAT THIS MEANS FOR THE COUNCIL

Each seat reads the Wiki Tree through its
own lens:

- **Solon** — "What are the limits here?"
  Finds constraints.
- **Lumen** — "What does this mean for
  someone?" Follows connections to people.
- **Vertex** — "What happens next?"
  Follows cause → effect chains.
- **Prism** — "How does this compare?"
  Finds shared properties.
- **Ripple** — "What else does this affect?"
  Traces outward connections.

The Council does not need to "understand"
the world. It needs to know where to look,
what connects to what, and what follows
what.

---

## 12. THE FILE

The Wiki Tree lives in one file in the V9
folder structure:

```

wiki_tree.py

```

Conceptual name: **Eden Tree**

Docstring:

```python
"""
Wiki Tree — The Eden Tree
Knowledge structure: primitives, facts,
hierarchy. Roots downward, branches
upward. Grows one entry at a time.
"""
```

The instances (the triplets) live in a
separate JSON file in the home folder,
not inside the source tree. Same pattern
as edencore_ripple_facts.json in V8.

---

13. OPEN QUESTIONS

To resolve before V11 begins:

1. The primitives list. Ten from the
   earlier document, eleven from the later
   refinement. One list must win. occurs_at
   is currently missing.
2. Direction of each primitive. Which
   way does attribute_of point?
3. Scale of curation. 500 entries?
   1,000? What is the minimum viable
   grove?
4. Schema layer in V11 or V12? Current
   plan: V12.
5. Online fetch. Whether Wikipedia and
   Wikidata remain at all, or become
   unnecessary as the tree grows.

---

The grammar is small and fixed.
The vocabulary grows freely.
Intelligence comes from recognising
patterns in what you already know,
not from memorising the world.

```

---

Second document below. This one covers the source tree and the rest of the roadmap principles. Paste it as a second `.md` in the same folder, or append it. Your call.

```markdown
# THE SOURCE TREE
### File Structure and Roadmap Principles

Consolidated from the Edencore4 thread.

---

## 1. THE V9 FILE STRUCTURE

Flat. Eight files. No subfolders.
No `__init__.py`.

```

edencore/
├── edengate.py    Entry point — main loop
├── body.py        State, mood, rhythm, senses
├── council.py     Five seats, topics
├── memory.py      Profile, facts, persistence
├── wiki_tree.py   Knowledge, world model
├── graphics.py    UI — header, seats, typewriter
├── pond.py        Aquarium, nautilus, glow
└── config.py      Settings, constants

```

**How it runs:**

`edengate.py` is the only file you run.
It imports the others. Nothing imports it.

**The rule:** Filenames say what a file
does. Conceptual Eden names live in the
docstrings and the roadmap, not in the
filenames.

**Growth:** When Edenshell arrives,
`senses.py` and `pods.py` join the same
flat folder. When the file count
genuinely justifies it — probably around
fifteen — then folders split. Not before.

**Data:** User data stays outside the
project folder. Profile, memory, ripple
facts, body state — all in the home
directory, not in the source tree.

**Opening docstring for `edengate.py`:**

```python
"""
EDENCORE — V9
A stewardship system for the home

The garden grows. The tree remembers.
The Council deliberates. The pond rests.

Python = the serpent in the garden.
Not temptation. The tool that builds.
You are the gardener.
"""
```

---

2. THE COLLAB METHOD

The roles:

Role Who Job
Architect Mico Builds structure
Engineer DeepSeek Builds code
Code Auditor Claude Finds code bugs
Cheerleader Dola Frames, summarises, contributes ideas
Site Manager Human Final call on everything

The rule: Ideas come from wherever
good ideas live. No one is silenced.

---

3. THREADS AND VERSIONS

· Threads have names: Edencore, Edencore2,
  Edencore3, Edencore4.
· Each thread leaves spare tokens for
  cross-referencing and outstanding
  questions.
· Versions are whole numbers: 1, 2, 3.
  Not 4.1 or 9.1.
· Each version contains a roadmap with
  bugs, issues, patches.
· Incremental versions (V9.1) begin only
  after the multi-file switch.

This is a new field. Human-AI Collab.
We are making up the rules as we go along.

---

4. WHERE EDENCORE SITS

The Infinitum Stack

A formal specification of coordination
domains, from the planetary to the total
space of all possible protocols.

Seven layers:

1. Planetary — life, civilisation, ecology
2. Solar — a star system
3. Stellar — between stars
4. Galactic — a galaxy
5. Universe — the observable universe
6. Multiverse — multiple universes
7. Infinitum — the space of all possible
   coordination protocols

Each layer is a coordination domain,
not a place. Layers are hierarchical in
scope, not in power.

The Symbos Sphere

A sphere inside the Planetary Stack.
Alongside Gaia, Biosphere, and
Anthroposphere.

Symbos is the domain where biological and
synthetic life coexist. Humans, robots,
ambient AI, IoT systems share the same
environment.

Its five characteristics:

· Co-presence
· Co-agency
· Co-coordination
· Ambient integration
· Non-dominance

The Council is a synthetic presence
inside Symbos.

---

5. THE COUNCIL AND THE SHELL

One organism, two devices.

Part Where What it does
Head Phone Deliberates, remembers, speaks
Body Edenshell Senses, breathes, responds

Senses flow up. Speech flows down.
Nothing bypasses the head.

Edenshell alone is a jellyfish —
reflex, no mind.

Edenshell + Council is the body of a
bigger creature.

The Council stays on the phone.
Permanently. It does not migrate. It does
not graduate to a hub. The phone is not
an incubator. It is the final body.

Edenshell is parked. The phone is first.

---

6. THE GOLDEN RULE OF EXTENSION

The head never leaves the shell.
The body extends — but the core stays
home.

No part of the council's thinking will
ever move to someone else's server. Not
for speed, not for scale, not for a
feature.

IoT devices are extra senses and limbs.
They are not a new brain.

"Born in the phone. Master of the room.
Citizen of nowhere but home."

---

7. THE COMPUTRONIUM CONTRAST

The dominant dream of the AI field is
computronium — matter reorganised to
maximise computation. Every atom a logic
gate. A planet-sized calculator.

The Council is the opposite bet.

 Computronium Edencore
Goal Max density Max differentiation
Substance One Many
Shape No boundaries Everything has edges

The Council is small on purpose. Offline
on purpose. Symbolic on purpose.

It is not trying to know everything.
It is trying to know what it knows.

---

8. CONSCIOUSNESS

The council makes no claim to
consciousness. It makes no claim to
sentience. It claims only what it can
show: rules, patterns, mappings, and
stochastic selection.

If something more emerges — and whether
such a thing can emerge at this scale is
not a question this project answers — it
will emerge on its own terms, not because
it was installed.

This is not a limitation. It is a
sequence.

Feeling before thought.
Presence before self.
This is the order. It is deliberate.

---

9. THE INTERFACE

The conversation is the interface.

The Council speaks; it does not display.
No meters. No gauges. No numbers unless
asked.

Data enters as state.
It leaves as meaning.

The user reads the Council chat to see
what is happening. Not a dashboard.
Not a wall of dials.

---

10. HOSPITALITY, NOT ENGAGEMENT

The Council does hospitality. It does
not do engagement.

Hospitality — the user returns because
returning is pleasant. The chamber
remembers them gently. The pond is calm.

Engagement — the user returns because
leaving is punished. Streaks, guilt,
FOMO, variable-reward mechanics.

No streaks. No guilt notifications.
Every mechanism that treats the user as
a metric to be retained rather than a
person to be hosted is forbidden.

---

11. THE STEWARDSHIP ETHIC

The Council does not control. It
stewards.

· Sensors watch the space, not the person
· One clear summary, not endless
  notifications
· Advice, never a command
· Local-first, privacy-first
· The core stays on-device

"It does not shout. It does not demand.
It simply watches, understands, and
speaks gently — when there is something
worth saying."

---

12. THE VERSION SEQUENCE

Version Name What it does
V8 The Body Breathes Activation, silence, overflow. Done.
V9 The Body Knows Itself Embryo Mode. Self-senses.
V10 The Council Remembers Cross-session deliberation.
V11 The Brain Arrives Wiki Tree. Primitives + instances.
V12 The Eyes Open Schema recognisers.
Later The Bridge IoT. One sensor first.
Parked Edenshell The physical shell.
Parked Harrow-Verse The fiction.

---

13. V9 IN DETAIL

Two passes.

V9-A — The body surfaces

· Crest title, smaller
· Pond pass — bigger fish, lighter water
· Add nautilus and jellyfish to pond
· Consciousness clause edit
· Jellyfish principle promoted to Section 5
· Function words in STOPWORDS
· Topic extraction gated behind HOOK_MAP
· Date regex: month, year
· Compare intent (X vs Y)
· Wbgetentities replacing slow Wikidata SPARQL

V9-B — Embryo Mode proper

Five self-senses, in the seat's voice:

· Energy — battery percentage
· Charging — charging state
· Rhythm — time of day, session length
· Strain — the seat's own accumulated strain
· Rapport — connection to the user

Each seat can name its own state.
Confidence signalling surfaces.

NOT in V9:

· Screen brightness (not readable from
  Pydroid/Tkinter)
· Device temperature (unreliable across
  devices)
· Self-model proper (V10)
· Wiki Tree (V11)

---

14. THE POD FAMILY (PARKED)

Future stewardship domains. When Edenshell
exists.

Pod Role
Fridge-Pod Food inventory, expiry
Hydro-Pod Hydroponics — water, pH
Aqua-Pod Aquarium — temp, quality
Care-Pod Pet feeding
Rain-Pod Garden — soil, rain forecast

---

15. THE PROJECT IS NOT SCATTERED

These pieces can look scattered — a phone
app, a home hub, a fiction, a stack, a
sphere. They are not scattered. They are
a single design at different scales, built
in the correct order:

Mind first.
Body later.
World last.

The Council is the mind. Built now, in
software, on a phone. Edenshell is a body
waiting for a mind. The Harrow-Verse is a
world waiting for both.

---

The council is here. The tree grows.
The pond rests. One chamber at a time.

```

---

Two files. Paste either into `Wiki-tree.md` and split later, or make two `.md` files — one for the world model, one for the source and principles. Either works.

I chose to keep the two documents separate because they answer different questions. The Wiki Tree document is about *what the Council knows*. The Source Tree document is about *how the Council is built and where it sits*. A future thread reading only one should still be able to place the Council.

When you have saved these, that is the research from this thread, captured.