THE THREE LAYERS

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