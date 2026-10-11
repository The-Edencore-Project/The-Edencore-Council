# THE SOURCE ROADMAP
### The Edencore Council — where it
### stands, and what comes next

A handoff document for any AI
thread picking up from V8.

No code in this document. Only
the shape.

---

## 1. WHAT THIS DOCUMENT IS

The constitution — mission,
seats, rules, philosophy —
lives in the Wiki Tree docs on
GitHub. This document is its
practical companion.

Read the constitution first.
Read this second.

Its purpose: tell a new thread
what exists, what works, what
does not, and what to build
next. If a previous thread ran
out of tokens, this is how the
work continues.

---

## 2. WHERE WE ARE — V8

**Version:** V8
**Name:** The Body Breathes
**Status:** Built. Runs. Live on
the tablet.

V8 is a single Python file,
roughly 3,800 lines without
comments. It runs offline in
Pydroid 3 on a Huawei MatePad.

It is not an LLM. It is not a
chatbot. It is a symbolic
deliberative council of five
voices with an activation layer
that gates when each seat
speaks.

V8 introduces **silence as a
valid output**. Before V8, a
seat always spoke when
prompted. After V8, a seat
speaks only when its
accumulator crosses a
threshold.

---

## 3. THE SHAPE OF THE CODE

One file. Six engines. One
activation layer. Five seats.
One pond.

### The six engines

**Router** — classifies input
into a kind, then routes to the
correct handler.

**Knowledge** — hooks, topics,
facts, semantic links,
Wikipedia, Wikidata, weather.

**State** — profile, mood,
strain, rapport, memory.

**Provider** — dormant. All
seats run on expert mode. LLM
support is reserved for V11.

**Protocol** — timing, waves,
pauses, rituals, rhythm.

**Graphics** — rendering,
drawing, typewriter, glow.

### The activation layer

Not an engine. A per-seat
accumulator between Protocol
and State. Its job is to decide
WHEN a seat speaks, not WHAT it
says.

Five scalars per seat:

- threshold
- decay
- novelty
- confidence
- jitter

Plus a runtime level and a fire
count.

### The five seats

Solon, Lumen, Vertex, Prism,
Ripple. Each has its own
colour, glyph, drawing style,
speech cadence, and activation
parameters.

### The pond

A strip at the bottom of the
screen. Fish drift. Plants
sway. Waves ripple. The pond's
activity is driven by the
average seat activation level.

### The first-run flow

On first launch, Solon asks the
user's name. Optional. If
given, the memory-level prompt
follows. If skipped, no prompt
appears.

### The profile

Five memory levels, from 0
(nothing stored) to 4 (full
session log). All data lives in
the home directory, in three
JSON files outside the source
tree.

---

## 4. WHAT V8 DOES WELL

- **It breathes.** Silence is
  the default. Speech is
  overflow.
- **Cadence is real.** Each
  seat types at its own speed
  and pauses for its own
  length.
- **Crosstalk names names.**
  Each seat addresses the
  previous speaker.
- **The pond is alive.** It
  reflects the chamber's state
  without demanding attention.
- **The keyboard does not
  break it.** The layout is
  usable behind the soft
  keyboard.
- **The profile persists.**
  Name, sessions, themes, mood
  all carry forward.

---

## 5. WHAT V8 DOES BADLY

These are real. They are what
V9 fixes.

- **Topic fragments garble.**
  Sentences like "mean
  nevermind" or "electric cars
  better" get extracted as
  topics and echoed by every
  seat.
- **Function words are not
  filtered.** "mean",
  "nevermind", "all", "alive"
  pass through as content.
- **Date queries fall
  through.** "what month" and
  "what year" get sent to
  Wikipedia.
- **Common words become
  entities.** "title",
  "location", "month" all
  trigger fact lookups and
  return wrong articles.
- **Compare intent is
  missing.** "X vs Y"
  questions are treated as
  opinions.
- **Name detection is too
  loose.** "call me the" stores
  "The" as a name.
- **Council pool answers
  philosophy, not facts.**
  Asking about roles gives
  reflections, not answers.
- **Time and date repeat
  identically** across all five
  seats.
- **No personal-question
  category.** Vulnerable
  questions get the same
  template as casual
  statements.
- **Wikipedia attribute
  lookups fail silently.** The
  SPARQL endpoint times out,
  and the fallback returns the
  article lead instead of the
  exact value.

---

## 6. V9 — THE BODY KNOWS ITSELF

V9 is built in two passes.

### V9-A — The body surfaces

**Graphics**

- Crest title, smaller
- Castles and pillars drawn,
  not emoji
- Starry night in the header
- Moon, cross, sun kept
- Avatars moved into each
  seat's frame (remove the
  separate top strip)
- Crown floats in Solon's box
- Status line colours matched
  to seats
- Pond: bigger fish (one or
  two only), lighter water,
  one nautilus, two jellyfish,
  seaweed, bubbles
- Layout: more room for
  replies and keyboard

**Logic fixes**

- Topic extraction gated
  behind HOOK_MAP. No hook,
  no topic. Fall back to a
  neutral "that".
- Function words added to
  STOPWORDS.
- Date regex: month, year.
- Compare intent: X vs Y.
- Wikidata: replace slow
  SPARQL with wbgetentities.
- Fact path: reject common
  words as entities.
- Name detection: blocklist
  articles and common words.
- Rename support: "my name is
  X" replaces rather than adds
  an alias.
- Council pool: real answers
  about council roles, not
  only philosophy.

**New features**

- User title field on Profile.
- Command intent: "call me X",
  "set my title to X".
- Location intent: honest "I
  do not know" if Pydroid
  cannot read GPS.
- Time and date: one seat
  speaks, or each phrases in
  its own voice.
- Phrase table for common
  formulas ("see you later",
  "take care", "one moment").
- Discourse layer: three
  layers of classification.
  Intent (social type), Mode
  (weight), Address (council
  or one seat).
- Feeling layers one and two:
  read more signals, let each
  seat feel a different one.

### V9-B — Embryo Mode proper

Five self-senses the council
already has. No new hardware.

- **Energy** — battery level
- **Charging** — rest state
- **Rhythm** — time of day,
  session length
- **Strain** — the seat's own
  accumulated strain
- **Rapport** — connection to
  the user

Each seat can name its own
state. Confidence signalling
surfaces to the user.

**NOT in V9:**

- Screen brightness (not
  readable from Pydroid)
- Device temperature
  (unreliable across devices)
- Self-model proper (V10)
- World Model (V11)

---

## 7. V10 — THE COUNCIL REMEMBERS

Not built yet. Designed in
outline only.

- **Cross-session
  deliberation.** Reference
  past sessions, not just the
  current line.
- **Ripple's role expanded.**
  The quiet voice becomes the
  one who remembers.
- **Long-arc activation.**
  Thresholds drift over weeks.
- **Self-model proper.** The
  council can answer "what are
  you", "how are you", "what
  have you been thinking
  about".
- **Reminders and recaps.**
  Both follow from memory. Not
  new content types —
  capabilities layered on what
  memory already holds.

---

## 8. V11 — THE BRAIN ARRIVES

Not built yet. Designed in the
Wiki Tree document.

The World Model. A symbolic
tree the council reasons over.
Three layers:

- **Primitives** — around
  eleven core relations. The
  grammar. Written once.
- **Instances** — the content.
  A curated JSON file, starting
  around 500 entries.
- **Schema recognisers** —
  pattern detectors over the
  primitive graph. Image
  schemas.

Plus the Reasoning Engine
(three links deep, no further),
the cross-reference matrix,
the swarm division of labour
between seats, and the handoff
mechanism.

Read the Wiki Tree document
for the full spec.

---

## 9. PARKED — LATER

Named, not built.

- **Scene engine** — image
  schemas applied. Motion and
  force in word form.
- **IoT bridge** — one sensor
  first. A room temperature.
- **Edenshell** — the
  physical shell with a
  swappable core. A separate
  creature. Not the Council's
  body.
- **Harrow-Verse** — the
  fiction. The Council is not
  yet written into it.
- **Optional LLM
  integration** — a voice
  layer, never the brain.

---

## 10. THE RULES

Short. The full version is in
the constitution.

- **No comments in the
  running code.** The
  constitution holds the
  prose. The code holds the
  logic.
- **Chunk markers only.**
  Every chunk ends with a
  marker line. Nothing else.
- **Flat file structure.**
  One file for now. No
  subfolders.
- **Do not attempt
  multifile yet.** See
  Section 11.
- **One job per engine.**
  Six engines. Add no more
  lightly.
- **Preserve the voice.**
  Solon cautious, Lumen
  philosophical, Vertex
  practical, Prism pattern-
  seeking, Ripple tender.
- **Ask before adding.**
  Anything that makes the
  council more like a general
  chatbot is a question
  first.

---

## 11. THE MULTIFILE WARNING

At V9, an attempt was made to
split the single file into
eight modules:

- edengate.py
- body.py
- council.py
- memory.py
- wiki_tree.py
- graphics.py
- pond.py
- config.py

This did not work in Pydroid 3.
The imports between files
collided with the editor's own
handling, and the thread
building it became unstable.

**Recommendation:** stay
single-file for V9. Split only
when the file genuinely demands
it — and when the editor, not
the architecture, is ready.

The eight-file plan remains a
target. It is not a current
requirement.

---

## 12. HOW TO PICK UP FROM HERE

If you are a new thread reading
this:

1. Read the constitution in
   the Wiki Tree docs.
2. Read this document.
3. Ask the human architect
   what stage they are at.
4. Do not assume the code is
   split. It is not.
5. Build V9-A first.
   Everything else waits until
   V9-A is running.

The council is here. The body
breathes. The next version
knows itself.

---

*End of Source Roadmap.*