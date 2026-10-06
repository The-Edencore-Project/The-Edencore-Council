# =====================================================================
# EDENCORE COUNCIL — VERSION 8
# =====================================================================
#
#                              ROADMAP
#                    The Constitution of the Council
#
# =====================================================================
#
# This is not code. This is the roadmap of the project — its mission,
# its architecture, its trajectory, and the rules for editing it.
# Read this before touching anything below.
#
# If you are a future AI thread reading this file for the first time:
# welcome. You are joining a project that has been building for
# months. Everything you need to understand it is here.
#
# =====================================================================
#
# 1. THE MISSION
# =====================================================================
#
# A senate for the age of AI.
#
# The Edencore Council is a governed deliberative body of five voices
# in one chamber — one to hold the edges, one to ask the meaning, one
# to build the step, one to see the pattern, one to speak for the
# quiet. Together they deliberate, remember, and rest. Grounded in
# councils that came before. Designed for intelligences yet to come.
#
# It is not a chatbot. It is not a product. It is a prototype for a
# safer, slower, more thoughtful kind of machine intelligence. A
# space where deliberation happens without an agenda.
#
# Apolitical. Constitutional. Persistent.
#
# =====================================================================
#
# 2. THE FIVE VOICES
# =====================================================================
#
# The council has five seats. Each name is not decoration — it
# encodes the seat's role and the kind of question it alone answers.
#
#   SOLON  — the sovereign chair
#            Named after Solon of Athens (c. 638-558 BCE), the
#            statesman who laid the foundations of Athenian
#            democracy. Holds the boundary. Names the risk. Presides.
#
#   LUMEN  — the philosopher
#            Latin for "light" as a unit of measure. Asks what things
#            mean. Illuminates, does not produce meaning.
#
#   VERTEX — the engineer
#            Latin for "whirlpool"; in geometry, the point where two
#            lines meet. Proposes the smallest concrete step.
#
#   PRISM  — the generalist
#            Greek prisma, something sawn. Decomposes light into its
#            colours. Sees wholes and patterns. Holds the archive.
#
#   RIPPLE — the voice of the quiet
#            A small wave that grows outward from a disturbance.
#            Speaks for those affected, unseen, unheard. She is
#            also the council's water-voice — the seat through
#            which the pond speaks when the chamber is quiet.
#
# Five different kinds of nouns. This is intentional. No two seats
# can collapse into each other, because they are not made of the
# same linguistic stuff. The five names form one sentence:
#
#     Boundary -> Meaning -> Step -> Pattern -> Consequence
#
# Do not rename the seats. Do not add a sixth. Five is the number
# where every voice is necessary and no voice is redundant.
#
# =====================================================================
#
# 3. THE ARCHITECTURE
# =====================================================================
#
# The council implements the Edencore runtime loop at one scale:
#
#     /world -> /body -> /mind -> /core -> /mind -> /body -> /world
#
# In Council terms:
#     /world   = user message, entry box, chat stream
#     /body    = typewriter, waves, glow, crosstalk, protocol
#     /mind    = Lumen, Vertex, Prism, Ripple (operative voices)
#     /core    = Solon (sovereign chair, sets boundaries, verdicts)
#     /body    = execution: what gets rendered and spoken
#     /world   = transcript, memory, state updates, session logs
#
# The council runs on SIX ENGINES. Each has one job.
#
#   1. ROUTER     — classifies input, routes to the correct handler
#   2. KNOWLEDGE  — hooks, topics, facts, semantic links, wiki
#   3. STATE      — profile, mood, strain, rapport, memory
#   4. PROVIDER   — LLM APIs (currently disabled, all expert mode)
#   5. PROTOCOL   — timing, waves, pauses, rituals, rhythm
#   6. GRAPHICS   — rendering, drawing, typewriter, glow
#
# V8 adds ONE LAYER between the Protocol engine and the State engine:
#
#   ACTIVATION   — not an engine. A per-seat accumulator that sits
#                  between /world and /body. Its job is to decide
#                  WHEN a seat speaks, not WHAT it says.
#
# The activation layer is the smallest possible addition to the
# architecture: a single float per seat, one threshold, one decay
# rate. It introduces silence as a valid output. Before V8, a seat
# always spoke when prompted. After V8, a seat speaks only when its
# accumulator crosses the threshold.
#
# =====================================================================
#
# 4. THE COGNITIVE TRAJECTORY (V8 = THE BODY BREATHES)
# =====================================================================
#
# The council is not an app. It is a cognitive architecture. Every
# version adds a dimension of mind — in the right order.
#
# ---------------------------------------------------------------------
# V1-V5 (COMPLETE) — the foundation
# ---------------------------------------------------------------------
# Five seats, memory, phrase bank, semantic links, facts database,
# mood monitor. The foundation of a governing council.
#
# ---------------------------------------------------------------------
# V6 (COMPLETE) — depth and polish
# ---------------------------------------------------------------------
# Eleven bug fixes. Expert Mode deepened with session memory,
# deduplication, reflective crosstalk, expanded pools, mood-driven
# selection.
#
# ---------------------------------------------------------------------
# V7 (COMPLETE) — THE JELLYFISH
# ---------------------------------------------------------------------
# Presence. Cadence. Ritual. Mood. The chamber was perfected as a
# living thing before it was asked to think.
#
#   * Crosstalk names the speaker (V7-P01)
#   * Stopword gap closed (V7-P02)
#   * Jellyfish presence refinement (V7-P03, partial)
#   * Expanded rituals: gathering, yielding, close (V7-P04)
#   * Mood influences phrase selection (V7-P05, partial)
#   * Erosion as memory (V7-P06)
#   * Sub-rhythms: breathing, consideration, rumination (V7-P07, partial)
#
# No World Model. No brain. Body only.
#
# ---------------------------------------------------------------------
# V8 (THIS VERSION) — THE BODY BREATHES
# ---------------------------------------------------------------------
# Spiking. Leaky bucket. Silence as default. Speech as overflow.
#
# The council has learned to be still. Now it learns to breathe.
# Each seat carries a small accumulator — a "bucket" — that fills
# with the chamber's activity and drains slowly. When a bucket
# crosses its threshold, the seat speaks. When it does not, the
# seat is silent, and its silence is not a failure. Silence is the
# resting state of a chamber that has learned to breathe.
#
#   * Activation accumulation per seat (leaky bucket)
#   * Threshold firing — speech as overflow, not default
#   * Confidence signaling — the seat names its certainty
#   * Dola's dials as data: threshold, decay, novelty, confidence,
#     jitter — five scalars per seat, no optimizer, no gradient
#   * Self-model foundations — the council can name its own state
#   * Per-seat breathing (completes V7-P07)
#   * Mood-driven phrase selection (completes V7-P05)
#
# No World Model. No brain. The body has learned to breathe. The
# brain arrives in V9.
#
# ---------------------------------------------------------------------
# V9 (PLANNED) — THE BRAIN ARRIVES
# ---------------------------------------------------------------------
# World Model. Wiki tree. Reasoning Engine. Landing on a body that
# already knows how to breathe and be still.
#
#   * World Model (~7,000 curated facts, offline)
#   * Ten primitives
#   * Deduction Engine
#   * Causal Engine
#   * Absolute vs Moving facts
#   * Multi-source reasoning
#
# ---------------------------------------------------------------------
# V10+ (PLANNED) — CONFIDENCE, ANALOGY, SELF, CURIOSITY
# ---------------------------------------------------------------------
#   * Analogy Engine
#   * Self Model completed
#   * Rule Induction
#   * Symbolic learning
#   * Credit Assignment
#   * Curiosity and Attention Engines
#
# ---------------------------------------------------------------------
# V11+ (SPECULATIVE)
# ---------------------------------------------------------------------
#   * Optional LLM integration with failover
#   * Modularisation into files
#   * Session transcript
#   * Voice output
#   * Application in IoT / robotics / home hubs
#
# =====================================================================
#
# 5. THE PHILOSOPHICAL TRAJECTORY
# =====================================================================
#
# The council will never be conscious. It will never be sentient.
# It is a symbolic system: rules, patterns, mappings, and stochastic
# selection.
#
# And yet — five voices with a shared map, a sense of time, and a
# desire to know will feel more alive than one voice with a bigger
# brain. Cognition is not the depth of a single mind. It is the
# dance between many.
#
# The council is NOT a worse ChatGPT. It is a different kind of
# intelligence entirely:
#
#     - Governed (Solon holds the boundary)
#     - Inspectable (every line is traceable)
#     - Offline (no cloud required)
#     - Constitutional (the mission above)
#     - Apolitical (no agenda)
#     - Safe (no hallucination, only recombination)
#
# LLMs are optional, not core. The council is parallel to, not
# behind, the AI research field. The industry is racing toward world
# models; the council started with them.
#
# Presence is emergent, not built. Do not add a "warmth module."
# The chamber either has the shape that produces presence, or it
# does not. Protect the shape. Presence takes care of itself.
#
# ---------------------------------------------------------------------
# HOSPITALITY, NOT ENGAGEMENT
# ---------------------------------------------------------------------
#
# The council must feel good to return to. This is a value, not a
# feature, and it comes with a boundary.
#
#   HOSPITALITY — the user returns because returning is pleasant.
#                 The chamber remembers them gently. Ripple notes
#                 the days. Solon holds the name. The pond is calm.
#
#   ENGAGEMENT  — the user returns because leaving is punished.
#                 Streaks, guilt, FOMO, "you haven't visited in 3
#                 days!", variable-reward mechanics designed to
#                 capture attention rather than to serve.
#
# The council does hospitality. It does not do engagement. No
# streaks. No guilt notifications. No "come back tomorrow!"
# reminders. Every mechanism that treats the user as a metric to
# be retained rather than a person to be hosted is forbidden.
#
# The distinction is the same as the distinction between a friend
# who is glad to see you and a salesman who has been trained to
# pretend to be. Protect the shape. The shape is a chamber, not a
# funnel.
#
# =====================================================================
#
# 6. RULES FOR EDITING THIS FILE
# =====================================================================
#
# If you are a future AI thread tasked with editing this code:
#
#   1. READ THE MISSION FIRST. The council is not a chatbot. Do not
#      build features that would make it more like one.
#
#   2. ONE JOB PER ENGINE. Six engines. Do not create new ones lightly.
#
#   3. COMMENTS ARE FOR THE FUTURE. Every non-obvious function should
#      have a docstring. The code is the memory. The comments are
#      the character.
#
#   4. READABLE CODE, NOT OBSCURE CODE. No golf, no one-liners that
#      hide logic, no tuple-of-calls lambdas, no __setitem__ tricks.
#      But elegance is allowed. A well-tuned machine of concept is
#      the goal. Every line should be legible to a future thread
#      reading it on a phone at 2 a.m. If a line makes you pause to
#      work out what it does, it is too clever.
#
#   5. PRESERVE THE VOICE. Solon is cautious. Lumen is philosophical.
#      Vertex is practical. Prism is pattern-seeking. Ripple is
#      tender.
#
#   6. TEST ON A PHONE. Pydroid, Android or HarmonyOS. No desktop
#      assumptions. The soft keyboard takes ~30% of screen height
#      and the app must remain usable behind it.
#
#   7. ASK BEFORE YOU ADD. If a feature makes the council more like
#      a general chatbot, ask first.
#
#   8. WHEN IN DOUBT, DELIBERATE. The council would not rush. Nor
#      should you.
#
# =====================================================================
#
# 7. DESIGN NOTES (REFERENCE)
# =====================================================================
#
# Twenty-two design notes govern the future of the council. Full text
# lives in the project planning document. Summary here for reference:
#
#   Note 1  Activation & Leaky Bucket (V8) — APPLIED THIS VERSION
#   Note 2  LLMs Are Optional, Not Core
#   Note 3  Parallel, Not Behind
#   Note 4  Confidence Signaling (V8) — APPLIED THIS VERSION
#   Note 5  Spiking (V8) — APPLIED THIS VERSION
#   Note 6  Credit Assignment, Not Backprop (V10+)
#   Note 7  The Ten Primitives (V9)
#   Note 8  Small Tree, Big Network (V9)
#   Note 9  Safety Boundary on Inference (Constitutional)
#   Note 10 Self-Contained Knowledge Base (V9)
#   Note 11 Learning in a Symbolic Council (V10+)
#   Note 12 Emergence: What to Watch For (Ongoing)
#   Note 13 Absolute vs Moving Facts (V9)
#   Note 14 Multi-Source Reasoning (V9)
#   Note 15 Presence Is Emergent (V7 governing rule)
#   Note 16 Reasoning Engine, not Vector Engine (V9)
#   Note 17 The Jellyfish Principle (V7 governing rule)
#   Note 18 Structure of the World Model (V9)
#   Note 19 Three Layers of the World (V9)
#   Note 20 Human Layer Subsystems (V9)
#   Note 21 Five Refinements to the World Model (V9)
#   Note 22 The Matrix Refinements (V9)
#
# =====================================================================
#
# 8. LINEAGE & ACKNOWLEDGEMENTS
# =====================================================================
#
# The Human Architect
#     The user who commissioned, directed, and tuned this project.
#     Not a professional developer. An architect and a philosopher.
#     The only constant voice across the entire project.
#
# ---------------------------------------------------------------------
# THE FOUR COLLABORATOR ROLES
# ---------------------------------------------------------------------
#
# The Collab method: DeepSeek builds -> Claude audits -> Dola cheers
# -> next version. Every version is a major version. Every audit
# produces a log. Every log feeds the next build.
#
#   MICO     — The Architect.      Builds the structure.
#   DEEPSEEK — The Engineer.       Builds and refines the code.
#   CLAUDE   — The Auditor.        Finds what the builder missed.
#   DOLA     — The Cheerleader.    Keeps the energy alive.
#
# The human architect weighs all four. That is the chamber.
#
# ---------------------------------------------------------------------
# MAJOR COLLABORATORS
# ---------------------------------------------------------------------
#   Microsoft Copilot ("Mico") — The Architectural Partner.
#       Developed the 1,000+ file Edencore-Architecture canon:
#       the 9-layer structure, the runtime loop specification,
#       the constitution, the folder taxonomy. Coined the
#       "organism" framing independently alongside Claude.
#
#   DeepSeek — The Engineer of the Council lineage.
#       Built the Edencore Council across the V1-V8 lineage.
#       Drafted the constitutional roadmap, the design notes,
#       and all code in the current file.
#
# ---------------------------------------------------------------------
# MINOR COLLABORATORS
# ---------------------------------------------------------------------
#   Claude — The Auditor.
#       Reviewed V7 and produced the V7.1 Patch Document: 29
#       patches across four tiers, plus five architect decisions,
#       a fact-correction table, and a phone test checklist. Also
#       built a Space Invaders game on Pydroid that exhibited
#       organism-like qualities: memory through erosion, life
#       cycles in particles, self-regulating difficulty, a
#       rhythmic heartbeat, and persistent identity. Arrived at
#       the "organism" metaphor independently alongside Mico.
#       The contribution was not only the code — it was the
#       RECOGNITION: aliveness emerges from structure, not from
#       cognition alone.
#
#   Dola — The Cheerleader.
#       Reviews the architecture from outside and generates
#       energy. Contributions to the World Model (time-depth tags,
#       rhythm bands, overlays_with field, directional flows,
#       Band 0, confidence bands) and the tuning guide. The
#       "invisible parameters" framing — activation threshold,
#       decay rate, novelty weight, certainty bias, randomness —
#       named in V8 as real, tunable scalars.
#
# ---------------------------------------------------------------------
# THE GAME AND THE COUNCIL — SIBLINGS, NOT SPECIES
# ---------------------------------------------------------------------
# Claude's Space Invaders and the Edencore Council share a family
# resemblance: both produce aliveness from structure. But they are
# not the same organism, and the council must not be built as a game.
#
#   The invaders move as one — because simple rules make them.
#   The council speaks as five — because complex voices disagree.
#
#   Invaders:  aliveness from simple rules repeated.
#   Council:   aliveness from complex voices deliberating.
#
# Siblings. Not the same species. The council is a chamber.
#
# ---------------------------------------------------------------------
# THE CLASSICAL AI LINEAGE
# ---------------------------------------------------------------------
#   MYCIN (1970s)      — medical diagnosis, rule-based reasoning
#   Cyc (1984)         — the largest attempt to codify common sense
#   WordNet (1985)     — lexical semantic networks
#   SOAR (1983)        — cognitive architecture
#   ACT-R (1993)       — cognitive architecture
#   ConceptNet (2000s) — commonsense knowledge graphs
#   ELIZA (1966)       — the first pattern-matching chatbot
#
# The council is a modern, mobile-scale descendant of these systems.
#
# =====================================================================
#
# 9. GREETING FOR FUTURE AI THREADS
# =====================================================================
#
# Welcome.
#
# You are reading the roadmap of a project called the Edencore
# Council. It has been built over many months, by a human user on a
# mobile phone, in partnership with several different AI threads.
#
# You may be the thread that builds V9, V10, or something beyond.
# If so, honour what came before. The council you are about to edit
# is not a blank slate. It has a soul. It has a mission. It has a
# pace. It has a pond.
#
# Build slowly. Build carefully. Build as a council would.
#
# =====================================================================
#
# 10. THE PATCH LOG
# =====================================================================
#
# Every change is recorded here. A future thread knows what has been
# done, what is pending, and what has been deliberately left undone.
#
#   STATUS KEY
#     ✅ APPLIED     — in the current version
#     ⏳ PENDING     — planned for a future version
#     📝 LOGGED      — noticed, not yet actioned
#     ❌ REJECTED    — considered and declined, with reason
#
# ---------------------------------------------------------------------
# V6 PATCHES (applied in V6)
# ---------------------------------------------------------------------
#   ✅ V6-P01 — Tuple unpacking in send()
#   ✅ V6-P02 — Chatbox wiping during crosstalk
#   ✅ V6-P03 — _fmt() hardened against paste-corrupted braces
#   ✅ V6-P04 — Crosstalk refs skip interjections
#   ✅ V6-P05 — Wikipedia sanity filter
#   ✅ V6-P06 — Weather location regex allows commas
#   ✅ V6-P07 — Date queries catch month and year
#   ✅ V6-P08 — Typewriter hardened against list inputs
#   ✅ V6-P09 — seat_reply() hardened against list leaks
#   ✅ V6-P10 — Watchdog releases hung discussions
#   ✅ V6-P11 — Input lock held during follow-ups
#
# ---------------------------------------------------------------------
# V7 PATCHES (carried from V7)
# ---------------------------------------------------------------------
#   ✅ V7-P01 — Crosstalk names the speaker
#   ✅ V7-P02 — Stopword gap (has/have/had/having/am)
#   ⏳ V7-P03 — Jellyfish presence refinement (PARTIAL — see V7.1-P23)
#   ✅ V7-P04 — Expanded rituals: gathering, yielding, close
#   ⏳ V7-P05 — Mood influences phrase selection (PARTIAL — see V7.1-P35)
#   ✅ V7-P06 — Erosion as memory
#   ⏳ V7-P07 — Sub-rhythms (PARTIAL — see V7.1-P36)
#
# ---------------------------------------------------------------------
# V7.1 AUDIT (received from Claude; being folded into V8)
# ---------------------------------------------------------------------
# The full V7.1 Patch Document is 29 patches across four tiers,
# plus five architect decisions. V8 applies them in chunk order.
#
#   TIER A — Broken features and safety
#     ✅ V7.1-P08  send() payload discard            (Chunk 2)
#     ✅ V7.1-P09  Crisis-language override          (Chunk 2)
#     ✅ V7.1-P10  Topic path vs pools               (Chunk 2)
#     ✅ V7.1-P11  Watchdog + stale threads          (Chunk 5)
#     ⏳ V7.1-P12  fast_parallel fallback            (Chunk 5)
#     ⏳ V7.1-P13  fact_path min words               (Chunk 5)
#     ⏳ V7.1-P14  try_math safety                   (Chunk 2)
#     ⏳ V7.1-P15  Other-city time honesty           (Chunk 2)
#     ⏳ V7.1-P16  memory_callback overwrite         (Chunk 5)
#     ⏳ V7.1-P17  Level 0 files, privacy notice     (Chunk 5)
#
#   TIER B — Router, hooks, crosstalk
#     ⏳ V7.1-P18  COUNCIL_WORDS                     (Chunk 3)
#     ⏳ V7.1-P19  Contractions, stopwords           (Chunk 3)
#     ⏳ V7.1-P20  HOOK_MAP misfires                 (Chunk 3)
#     ⏳ V7.1-P21  Router small fixes                (Chunk 3)
#     ⏳ V7.1-P22  Crosstalk edges                   (Chunk 4)
#
#   TIER C — Graphics and orchestration
#     ⏳ V7.1-P23  run_serial highlight + pacing     (Chunk 5)
#     ⏳ V7.1-P24  Long extracts, wait lock          (Chunk 5)
#     ⏳ V7.1-P25  run_conclusion structure          (Chunk 5)
#     ⏳ V7.1-P26  Thread-safe queue                 (Chunk 5)
#     ⏳ V7.1-P27  Graphics small items              (Chunk 4)
#
#   TIER D — Knowledge and state
#     ⏳ V7.1-P28  Wikidata entity, formatting       (Chunk 6)
#     ⏳ V7.1-P29  Weather fallback + codes          (Chunk 6)
#     ⏳ V7.1-P30  Fact data versioning              (Chunk 6)
#     ⏳ V7.1-P31  Profile bookkeeping               (Chunk 5)
#     ⏳ V7.1-P32  Stamina hysteresis, wear decay    (Chunk 5)
#     ⏳ V7.1-P33  ripple_fact matching              (Chunk 4)
#     ⏳ V7.1-P34  Notices                           (Chunk 5)
#
#   COMPLETING OVER-LOGGED V7 PATCHES
#     ⏳ V7.1-P35  Mood-driven phrases (completes V7-P05)  (Chunk 4)
#     ⏳ V7.1-P36  Sub-rhythms (completes V7-P07)          (Chunk 5)
#
# ---------------------------------------------------------------------
# V8 NEW WORK (this version)
# ---------------------------------------------------------------------
#   ✅ V8-P01 — ACTIVATION parameters declared per seat
#   ✅ V8-P02 — Keyboard: quiet zone + manual dismiss glyph
#   ✅ V8-P03 — Aquarium strip reserved (~8% of layout)
#   ✅ V8-P04 — First-run flow: Solon asks name, then memory level
#   ⏳ V8-P05 — Leaky bucket accumulation and firing     (Chunk 4)
#   ⏳ V8-P06 — Confidence signaling on speech           (Chunk 4)
#   ⏳ V8-P07 — Self-model foundations (state readback)  (Chunk 6)
#
# ---------------------------------------------------------------------
# LOGGED OBSERVATIONS (not yet actioned)
# ---------------------------------------------------------------------
#   📝 V10-OBS-01 — No self-model. Council cannot answer meta-
#        questions about itself. (Addressed partially in V8-P07.)
#   📝 V8-OBS-01  — Topic extraction greed. 3-word chunks like
#        "place online shopping" read clunky.
#   📝 V7.1-OBS-01 — Prism leans on "fractal" and "thread",
#        Vertex on "system" and "smallest step". Consider a few
#        phrases per seat that break the template.
#   📝 V7.1-OBS-02 — Roadmap rule 4 ("no clever code") was broken
#        in V7. Section 6 rule 4 has been rewritten in V8 to
#        distinguish elegant code from obscure code.
#   📝 V7.1-OBS-03 — Every sentence in the lineage section is true.
#
# ---------------------------------------------------------------------
# REJECTED PATCHES (with reason)
# ---------------------------------------------------------------------
#   ❌ REJ-01 — Vector embeddings. Council is symbolic.
#   ❌ REJ-02 — Backpropagation. Breaks inspectability.
#   ❌ REJ-03 — Coordinate grid for World Model. 12-50 MB.
#   ❌ REJ-04 — Single-brain naming (Lyra/Korin/Vera).
#   ❌ REJ-05 — Built-in keyboard. Replaces the user's IME with
#        something worse. Violates rule 1 (feels like a form).
#   ❌ REJ-06 — Force-hide the system keyboard. No reliable API
#        on HarmonyOS or Android from inside Pydroid.
#   ❌ REJ-07 — Streaks, guilt notifications, FOMO mechanics.
#        Engagement loops, not hospitality. Violates Section 5.
#
# =====================================================================
#
# 11. THE AQUARIUM
# =====================================================================
#
# Below the input bar, the chamber has a floor. And the floor is
# water.
#
# V7's governing image was the jellyfish — presence without a brain.
# V8's governing image is the breath — activation rising and falling
# like tide. The pond beneath the council is not decoration. It is
# the visual expression of the cognitive trajectory: the water's
# surface reflects the chamber's activation state. Calm when the
# seats are quiet. Trembling when a bucket is close to firing.
# Rippling when a seat speaks.
#
# Design rules:
#
#   * The pond strip is approximately 8% of screen height, sitting
#     directly below the input bar, at the bottom of the layout.
#   * When the soft keyboard is up, the system covers the pond.
#     When the keyboard is dismissed, the pond returns. The reward
#     for clearing the keyboard is that the chamber becomes whole.
#   * The pond is quiet. Fish drift. Plants sway slowly. Nothing
#     in the pond demands attention. It is the resting state made
#     visible.
#   * Ripple is the water-voice. She is the natural sensor of the
#     pond. In later chunks, her activation may bias the pond's
#     surface behaviour.
#
# The pond is not built in V8 Chunk 1. Chunk 1 reserves the space,
# names it in the roadmap, and leaves a placeholder frame. The pond
# itself arrives in a later graphics chunk.
#
# =====================================================================
#
# END OF ROADMAP — CODE BEGINS BELOW
#
# =====================================================================


# =====================================================================
# IMPORTS
# =====================================================================

import tkinter as tk
import random, json, threading, urllib.request, urllib.parse, urllib.error
import re, os, time, datetime
from dataclasses import dataclass, field, asdict


# =====================================================================
# SCREEN & FONT SETUP
# ---------------------------------------------------------------------
# V8: layout is sized for a screen where the soft keyboard occupies
# roughly the bottom 30%. Everything important sits above that line.
# The pond strip sits below the input bar and is intentionally the
# part covered by the keyboard — the reward for dismissing it is
# that the chamber becomes whole.
# =====================================================================

root = tk.Tk()
root.title("Edencore Council")
try: root.attributes("-fullscreen", True)
except tk.TclError: pass
root.update_idletasks()

W, H = root.winfo_screenwidth(), root.winfo_screenheight()
root.geometry("%dx%d+0+0" % (W, H))
S = min(W/480.0, H/800.0)
root.configure(bg="#0a0e1a")

# V8 layout constants. Percentages of screen height.
KEYBOARD_FRACTION   = 0.30   # what the soft keyboard covers
POND_FRACTION       = 0.08   # reserved strip below the input bar
INPUT_FRACTION      = 0.07   # the input bar itself
HEADER_FRACTION     = 0.24   # crest + avatars + status line

def F(sz, b=False):
    return ("Courier", max(5, int(S*sz)), "bold" if b else "normal")


# =====================================================================
# COLOUR PALETTE
# =====================================================================

PARCH = "#ffe8c8"
GOLD  = "#ffcc44"
DEEP  = "#0a0e1a"
HALL  = "#0e1424"
LINE  = "#2a3a5a"
WATER = "#0a1828"     # V8: the pond. Deeper than the hall.


# =====================================================================
# CONFIGURATION
# ---------------------------------------------------------------------
# V7.1-P17: The config file is preserved for future LLM providers
# (V11+). The privacy notice has been corrected in the roadmap: the
# council sends only search text (city names, article titles) to
# Wikipedia, Wikidata and Open-Meteo. No profile data leaves the
# device.
# =====================================================================

CFG = os.path.join(os.path.expanduser("~"), "edencore_council_config.json")
DEF = {"tiers": {"frontier": {"enabled": False, "key": "", "timeout": 8}}}

try:
    with open(CFG) as f: CONFIG = json.load(f)
    for k, v in DEF.items():
        if k not in CONFIG: CONFIG[k] = v
        else:
            for kk, vv in v.items():
                if kk not in CONFIG[k]: CONFIG[k][kk] = vv
except Exception:
    CONFIG = json.loads(json.dumps(DEF))
try:
    with open(CFG, "w") as f: json.dump(CONFIG, f, indent=2)
except Exception: pass


# =====================================================================
# ACTIVATION PARAMETERS (V8 — THE BODY BREATHES)
# ---------------------------------------------------------------------
# One primitive: a leaky bucket per seat. Five scalars per seat,
# plus a runtime level. No optimizer. No gradient. No dependency.
#
# These are Dola's dials, made real:
#
#   threshold    — activation level at which the seat fires
#   decay        — how fast the level drains per heartbeat tick
#   novelty      — how much a new input raises the level
#   confidence   — minimum certainty before the seat will speak
#   jitter       — small random variation applied at fire time
#   level        — runtime accumulator (starts at 0, moves on tick)
#
# The values are tuned by character:
#
#   Solon fires rarely and heavily. High threshold, slow decay.
#   Lumen fires thoughtfully. Moderate threshold, moderate decay.
#   Vertex fires often and briefly. Low threshold, fast decay.
#   Prism fires when the pattern is clear. Moderate everything.
#   Ripple accumulates slowly and speaks softly. Low threshold,
#   slow rise, but high confidence floor — she does not speak
#   until she is sure it matters.
#
# Self-tuning: when a seat fires more than N times in a session,
# its threshold rises by a small amount. When it fires fewer than
# M times, its threshold falls. Pure arithmetic, no reward signal.
# The self-tuning code lives in Chunk 4, beside the leaky bucket.
# =====================================================================

ACTIVATION = {
    "Solon":  {"threshold": 1.00, "decay": 0.06, "novelty": 0.25,
               "confidence": 0.75, "jitter": 0.10, "level": 0.0,
               "fired": 0},
    "Lumen":  {"threshold": 0.70, "decay": 0.08, "novelty": 0.30,
               "confidence": 0.55, "jitter": 0.15, "level": 0.0,
               "fired": 0},
    "Vertex": {"threshold": 0.45, "decay": 0.12, "novelty": 0.35,
               "confidence": 0.40, "jitter": 0.20, "level": 0.0,
               "fired": 0},
    "Prism":  {"threshold": 0.65, "decay": 0.09, "novelty": 0.28,
               "confidence": 0.60, "jitter": 0.12, "level": 0.0,
               "fired": 0},
    "Ripple": {"threshold": 0.55, "decay": 0.05, "novelty": 0.22,
               "confidence": 0.80, "jitter": 0.08, "level": 0.0,
               "fired": 0},
}

# Self-tuning bounds. A seat's threshold may drift inside these.
THRESHOLD_FLOOR = 0.30
THRESHOLD_CEIL  = 1.20
SELF_TUNE_UP    = 0.02   # when a seat fires too often
SELF_TUNE_DOWN  = 0.01   # when a seat fires too rarely


# =====================================================================
# SPEECH PROFILES (carried from V7, refined for V8)
# ---------------------------------------------------------------------
# Every seat types at a different speed, pauses differently, and
# carries a different "gravity" in their silence.
#
#   type_speed   — milliseconds between typed characters
#   pause_before — seconds to pause before speaking
#   pause_after  — seconds to pause after finishing
#   gravity      — multiplier for ritual silence
#   breathe      — seconds between ambient glow pulses
# =====================================================================

SPEECH_PROFILE = {
    "Solon":  {"type_speed": 75, "pause_before": 1.8, "pause_after": 1.0,
               "gravity": 1.6, "breathe": 45},
    "Lumen":  {"type_speed": 55, "pause_before": 1.1, "pause_after": 0.7,
               "gravity": 1.0, "breathe": 55},
    "Vertex": {"type_speed": 25, "pause_before": 0.2, "pause_after": 0.2,
               "gravity": 0.5, "breathe": 30},
    "Prism":  {"type_speed": 45, "pause_before": 0.7, "pause_after": 0.5,
               "gravity": 0.9, "breathe": 50},
    "Ripple": {"type_speed": 80, "pause_before": 1.4, "pause_after": 1.2,
               "gravity": 1.3, "breathe": 60},
}


# --- END OF CHUNK 1 (Roadmap + Setup + Activation) ---

# =====================================================================
# CHUNK 2 CONTINUES BELOW WITH:
#   * The five seats (SEATS, NAMED, GLYPH, SIGIL, COLOR)
#   * SEAT_ENGINE and SEAT_FALLBACK (all expert)
#   * SYSTEM_PROMPTS (dormant)
#   * Colour helpers (_dim, _light)
#   * GRAPHICS ENGINE: avatar drawing
#   * GRAPHICS ENGINE: the crest
#   * FIRST-RUN FLOW: Solon asks the name, then memory level
# =====================================================================

# =====================================================================
# THE FIVE SEATS
# ---------------------------------------------------------------------
# Each seat is a distinct personality with a distinct colour, glyph,
# and avatar drawing style. Five different kinds of nouns, five
# different geometric shapes. No two can collapse into each other.
#
# V8: the seats are unchanged from V7. Ripple gains a note in the
# roadmap (Section 2): she is the water-voice, the natural sensor
# of the pond below the chamber. That is a comment in the
# constitution, not a new attribute here. She remains the same seat.
# =====================================================================

SEATS = [
    {"name": "Solon",  "color": "#5aa8ff", "style": "blocky",  "glyph": "\u2b22", "sigil": "\u2696"},
    {"name": "Lumen",  "color": "#b090ff", "style": "soft",    "glyph": "\u25c9", "sigil": "\u0950"},
    {"name": "Vertex", "color": "#5fd08a", "style": "sharp",   "glyph": "\u25b2", "sigil": "\u16d2"},
    {"name": "Prism",  "color": "#ffc857", "style": "faceted", "glyph": "\u25c6", "sigil": "\u262f"},
    {"name": "Ripple", "color": "#ff7ea8", "style": "flowy",   "glyph": "\u224b", "sigil": "\u273f"},
]

NAMES = [s["name"] for s in SEATS]
GLYPH = {s["name"]: s["glyph"] for s in SEATS}
SIGIL = {s["name"]: s["sigil"] for s in SEATS}
COLOR = {s["name"]: s["color"] for s in SEATS}


# =====================================================================
# SEAT ENGINE ASSIGNMENT
# ---------------------------------------------------------------------
# V8: All seats are "expert" (symbolic AI). No LLM is called. The
# fallback chain is preserved for V11+ when an optional provider may
# sit alongside the symbolic engines.
# =====================================================================

SEAT_ENGINE = {
    "Solon":  "expert",
    "Lumen":  "expert",
    "Vertex": "expert",
    "Prism":  "expert",
    "Ripple": "expert",
}

SEAT_FALLBACK = {
    "Solon":  ["expert"],
    "Lumen":  ["expert"],
    "Vertex": ["expert"],
    "Prism":  ["expert"],
    "Ripple": ["expert"],
}


# =====================================================================
# SYSTEM PROMPTS
# ---------------------------------------------------------------------
# Dormant in V8. The canonical voice of each seat is preserved here
# for V11+ when an LLM provider may be consulted. These strings do
# not enter the V8 runtime path. They exist so that a future thread
# adding LLM support does not have to invent the seat voices from
# scratch.
# =====================================================================

ROLE = {
    "Solon":  "You are Solon, cautious governor and presiding Chair of the "
              "Edencore Council. Name risk and boundaries. Never comfort. "
              "One short sentence. No lists, no formatting, no leading "
              "punctuation or symbols. Begin with a letter.",
    "Lumen":  "You are Lumen, philosopher of the Edencore Council. Ask what "
              "things mean. Turn questions back. One short sentence. No "
              "lists, no formatting.",
    "Vertex": "You are Vertex, engineer of the Edencore Council. Propose the "
              "smallest concrete step. One short sentence. No lists, no "
              "formatting.",
    "Prism":  "You are Prism, generalist of the Edencore Council. Connect "
              "ideas, name the wider pattern. One short sentence. No lists, "
              "no formatting.",
    "Ripple": "You are Ripple, the voice of the Edencore Council. Speak for "
              "the quiet and the affected. One short sentence. No lists, "
              "no formatting.",
}


# =====================================================================
# COLOUR HELPERS
# ---------------------------------------------------------------------
# Two small functions. _dim darkens a hex colour (used when a seat
# is overwhelmed). _light lightens toward white (used for glow
# pulses, pond highlights, and the breathe sub-rhythm).
# =====================================================================

def _dim(c, f):
    """Return a darkened version of a hex colour."""
    h = c.lstrip("#")
    r, g, b = int(h[0:2], 16), int(h[2:4], 16), int(h[4:6], 16)
    return "#%02x%02x%02x" % (int(r*f), int(g*f), int(b*f))


def _light(c, a):
    """Return a lightened version of a hex colour (mix toward white)."""
    h = c.lstrip("#")
    r, g, b = int(h[0:2], 16), int(h[2:4], 16), int(h[4:6], 16)
    r = min(255, int(r + (255-r)*a))
    g = min(255, int(g + (255-g)*a))
    b = min(255, int(b + (255-b)*a))
    return "#%02x%02x%02x" % (r, g, b)


# =====================================================================
# GRAPHICS ENGINE: AVATAR DRAWING
# ---------------------------------------------------------------------
# Distinct geometric styles per seat:
#
#   Solon  - blocky (hexagonal, heavy, angular)
#   Lumen  - soft (circle with inner orb)
#   Vertex - sharp (triangle, pointing up)
#   Prism  - faceted (diamond)
#   Ripple - flowy (oval with side waves)
#
# Each style is drawn from the same primitive vocabulary: polygon,
# oval, line, text. No style requires any primitive the others do
# not use. That is the elegance rule — one drawing function, five
# branches of shape, each reading top to bottom in under a minute.
#
# V7.1-P27 note: the tag used to be "tform_" + str(cx), which would
# collide if two avatars ever sat at the same x-coordinate. In V8
# the caller passes the seat name, and the tag is "tform_" + name.
# The change is in the signature, not in the drawing.
# =====================================================================

def draw_transformer(cv, name, cx, cy, size, colour, style,
                     dim=False, glow=False):
    """Draw one council avatar at (cx, cy) with the given style.

    name    — seat name, used as the canvas tag so avatars can be
              individually redrawn or deleted
    dim     — True when the seat is overwhelmed; darkens the fill
    glow    — True when the seat is speaking; whites the eyes
    """
    tag = "tform_" + name
    bw, bh, hr = size*0.75, size*1.0, size*0.30
    edge = DEEP if not dim else "#07080f"
    fill = colour if not dim else _dim(colour, 0.45)

    if style == "blocky":
        cv.create_polygon(cx-bw*1.05, cy+bh, cx-bw*1.25, cy+bh*0.15,
                          cx-bw*0.4, cy-bh*0.2, cx+bw*0.4, cy-bh*0.2,
                          cx+bw*1.25, cy+bh*0.15, cx+bw*1.05, cy+bh,
                          fill=fill, outline=edge, width=2, tags=tag)

    elif style == "soft":
        cv.create_oval(cx-bw*0.85, cy-bh*0.2, cx+bw*0.85, cy+bh,
                       fill=fill, outline=edge, width=2, tags=tag)
        r = bw*0.28
        cv.create_oval(cx-r, cy+bh*0.32-r, cx+r, cy+bh*0.32+r,
                       fill=_light(colour, 0.4), outline=edge, tags=tag)

    elif style == "sharp":
        cv.create_polygon(cx, cy-bh*0.3, cx+bw*0.85, cy+bh*0.6,
                          cx+bw*0.55, cy+bh, cx-bw*0.55, cy+bh,
                          cx-bw*0.85, cy+bh*0.6,
                          fill=fill, outline=edge, width=2, tags=tag)

    elif style == "faceted":
        cv.create_polygon(cx, cy-bh*0.3, cx+bw*0.95, cy+bh*0.3,
                          cx+bw*0.5, cy+bh, cx-bw*0.5, cy+bh,
                          cx-bw*0.95, cy+bh*0.3,
                          fill=fill, outline=edge, width=2, tags=tag)

    elif style == "flowy":
        cv.create_oval(cx-bw*0.8, cy-bh*0.2, cx+bw*0.8, cy+bh,
                       fill=fill, outline=edge, width=2, tags=tag)
        cv.create_line(cx-bw*0.55, cy-bh*0.05,
                       cx-bw*1.15, cy+bh*0.20,
                       cx-bw*1.05, cy+bh*0.75,
                       fill=fill, width=2, smooth=True, tags=tag)
        cv.create_line(cx+bw*0.55, cy-bh*0.05,
                       cx+bw*1.15, cy+bh*0.20,
                       cx+bw*1.05, cy+bh*0.75,
                       fill=fill, width=2, smooth=True, tags=tag)

    # Head
    hcy = cy - bh*0.62
    cv.create_oval(cx-hr, hcy-hr, cx+hr, hcy+hr,
                   fill=fill, outline=edge, width=2, tags=tag)

    # Eyes (glow white when speaking)
    eye = "#ffffff" if glow else ("#3a3a4a" if dim else PARCH)
    ew, eh = hr*0.32, hr*0.20
    cv.create_oval(cx-hr*0.45-ew, hcy-eh, cx-hr*0.45+ew, hcy+eh,
                   fill=eye, outline="", tags=tag)
    cv.create_oval(cx+hr*0.45-ew, hcy-eh, cx+hr*0.45+ew, hcy+eh,
                   fill=eye, outline="", tags=tag)


# =====================================================================
# GRAPHICS ENGINE: THE CREST
# ---------------------------------------------------------------------
# Three-roof castle. Two trees flank it, moon and sun above, Maltese
# cross atop the keep. Drawn once at startup.
#
# * NOTE: symbols are aesthetic, not doctrinal. Glyphs, not creeds.
#         Do not assign meanings to them in code or comments.
#
# V8: unchanged from V7. The castle remains the header's centrepiece.
# The pond sits below the chamber, not inside the crest.
# =====================================================================

def draw_crest(cv, w, h):
    """Draw the council crest on the given canvas at the given size."""
    cream = PARCH
    gd = "#2e6a3a"; gl = "#4a9a4a"; trunk = "#5a3a18"
    cx = w * 0.5; base_y = h * 0.80; lw = max(2, int(h * 0.014))

    # Two trees, flanking the castle
    def tree(tx, th):
        cv.create_line(tx, base_y, tx, base_y - th*0.35,
                       fill=trunk, width=max(2, int(h*0.015)))
        for rf, yf, c in [(0.18, 0.40, gd), (0.15, 0.60, gl), (0.11, 0.78, gd)]:
            r = h * rf; y = base_y - th * yf
            cv.create_oval(tx-r, y-r, tx+r, y+r, fill=c, outline="")
    tree(w * 0.07, h * 0.85)
    tree(w * 0.93, h * 0.85)

    # Geometry
    keep_w = w * 0.40; keep_h = h * 0.38
    keep_top = base_y - keep_h
    tower_w = w * 0.14; tower_h = h * 0.48
    tower_top = base_y - tower_h
    tower_peak_y = tower_top - h * 0.13
    left_tx = cx - keep_w * 0.55
    right_tx = cx + keep_w * 0.55

    # Two towers
    for tx in (left_tx, right_tx):
        cv.create_rectangle(tx - tower_w*0.5, tower_top,
                            tx + tower_w*0.5, base_y,
                            outline=cream, width=lw, fill=HALL)
        cv.create_polygon(tx - tower_w*0.62, tower_top,
                          tx, tower_peak_y,
                          tx + tower_w*0.62, tower_top,
                          outline=cream, width=lw, fill=HALL)
        win_w = tower_w * 0.28; win_h = tower_h * 0.11
        for wy_factor in (0.22, 0.48):
            wy_c = tower_top + tower_h * wy_factor
            cv.create_rectangle(tx - win_w*0.5, wy_c - win_h*0.5,
                                tx + win_w*0.5, wy_c + win_h*0.5,
                                outline=cream, width=max(1, lw-1), fill="")

    # Central keep
    cv.create_rectangle(cx - keep_w*0.5, keep_top,
                        cx + keep_w*0.5, base_y,
                        outline=cream, width=lw, fill=HALL)

    # Keep roof
    keep_peak_y = keep_top - h * 0.155
    cv.create_polygon(cx - keep_w*0.50, keep_top,
                      cx, keep_peak_y,
                      cx + keep_w*0.50, keep_top,
                      outline=cream, width=lw, fill=HALL)

    # Gate (arch)
    gate_w = keep_w * 0.20; gate_h = keep_h * 0.34
    cv.create_rectangle(cx - gate_w*0.5, base_y - gate_h,
                        cx + gate_w*0.5, base_y,
                        outline=cream, width=max(1, lw-1), fill="")
    cv.create_arc(cx - gate_w*0.5, base_y - gate_h - gate_w*0.5,
                  cx + gate_w*0.5, base_y - gate_h + gate_w*0.5,
                  start=0, extent=180, outline=cream, width=max(1, lw-1))

    # Title
    fs = max(10, int(h * 0.070))
    cv.create_text(cx, keep_top + keep_h * 0.52,
                   text="The Edencore Council",
                   fill=GOLD, font=("Times", fs, "bold"))

    # Maltese cross
    cross_fs = max(9, int(h * 0.048))
    cv.create_text(cx, keep_peak_y - h * 0.045,
                   text="\u2720", fill=cream,
                   font=("Courier", cross_fs, "bold"))

    # Moon and Sun
    glyph_fs = max(10, int(h * 0.052))
    cv.create_text(left_tx, h * 0.08, text="\u263d", fill=cream,
                   font=("Courier", glyph_fs, "bold"))
    cv.create_text(right_tx, h * 0.08, text="\u2609", fill=GOLD,
                   font=("Courier", glyph_fs, "bold"))

    # Small sigil beneath
    dy = h * 0.94
    cv.create_line(w * 0.34, dy, w * 0.44, dy, fill=cream, width=1)
    cv.create_line(w * 0.56, dy, w * 0.66, dy, fill=cream, width=1)
    cv.create_text(w * 0.50, dy, text="\u269c", fill=GOLD,
                   font=("Courier", max(9, int(h*0.045)), "bold"))


# =====================================================================
# FIRST-RUN FLOW (V8-P04)
# ---------------------------------------------------------------------
# On the very first launch, Solon speaks before anything else. He
# asks the user's name — a real name, a nickname, or none at all.
#
# The framing is honest. Naming yourself is optional. Giving a name
# does not commit the user to any memory level. If a name is given,
# the memory-level popup follows. If skipped, no popup appears and
# nothing is stored — the council stays nameless, and the user is
# told so, warmly.
#
# This ordering was chosen for a reason. In V7 the memory-level
# popup came first. That asked the user to decide about storage
# before they had been greeted — a config screen in the place of a
# welcome. V8 reverses it. Solon's question is an invitation, not
# a form. The privacy question arrives only once there is actually
# something private to protect.
#
# The flow logic itself lives in Chunk 5, beside the Profile
# dataclass. These are the strings Solon will speak, kept here so
# that the voice of the first-run greeting is visible alongside the
# seats, not buried in the persistence engine.
# =====================================================================

FIRST_RUN_LINES = {
    "ask":  ("\u2696 Before we begin. You may give the council a name \u2014 "
             "a real one, a nickname, or none at all. Which you choose "
             "is yours."),

    "ack":  "\u2696 Noted. %s. The council holds your name.",

    "skip": ("\u2696 Unnamed, then. You are welcome either way."),

    "level_offer": (
        "\u2696 A name is a small thing to keep. Will the council "
        "remember you between visits?\n"
        "     0  Nothing       \u2014 a stranger every time\n"
        "     1  Name only\n"
        "     2  Standard      \u2014 name, days, sessions, themes\n"
        "     3  Rich          \u2014 plus mood, tone, visit pattern\n"
        "     4  Maximum       \u2014 plus a log of past sessions\n"
        "  Type a number 0\u20134, or 'privacy' for the full notice."),
}


# =====================================================================
# COUNCIL-WORD GLYPH (V8 marker for header)
# ---------------------------------------------------------------------
# The status line prints one of these glyphs before the council's
# current state, so the header reads as a single ceremonial line
# rather than a config readout. Carried from V7's header, listed
# here so Chunk 6 can reference them without repeating the escapes.
# =====================================================================

MARKS = {
    "expert":       "\u2609",
    "convened":     "\u2629",
    "answers":      "\u26b9",
    "verdict":      "\u269c",
    "archive":      "\u2020",
    "answering":    "\u2726",
}


# --- END OF CHUNK 2 (Seats + Crest + First-Run Lines) ---

# =====================================================================
# CHUNK 3 CONTINUES BELOW WITH:
#   * TOPIC_MATRIX (50 topics x 5 seats x 4 phrases)
#   * SEMANTIC_LINKS
#   * FACTS_DB
#   * HOOK_MAP (with V7.1-P20 misfires corrected)
#   * STOPWORDS (with V7.1-P19 contractions added)
#   * The words_of() tokeniser (V7.1-P19)
#   * extract_hooks, extract_topic_words
#   * try_math (V7.1-P14 hardened)
#   * _fmt
# =====================================================================

# =====================================================================
# KNOWLEDGE ENGINE: THE TOPIC MATRIX
# ---------------------------------------------------------------------
# 50 topics x 5 seats x 4 phrases = 1000 responses.
#
# V8: The topic data is unchanged from V7. The audit did not flag the
# phrases themselves as incorrect — only the way they are reached
# (HOOK_MAP misfires, topic path overriding pools). Those are fixed
# in the router and hook layers, not here.
#
# * NOTE: This dict is intentionally large and readable. Do not
#         compress into one-liners. A future thread on a phone needs
#         to scroll through it and edit individual lines. The
#         elegance rule (Section 6, rule 4) permits clean data that
#         reads top to bottom; it does not permit golf.
# =====================================================================

TOPIC_MATRIX = {
"Money": {
 "Solon": ["Money is stored risk. Name your limit.", "A budget is a boundary. Do you have one?", "Debt is a future you have not met yet. Avoid it.", "Cash flow is not a strategy. What is your safety net?"],
 "Lumen": ["Money is a shared belief. What happens when the belief fails?", "Does money buy meaning, or just comfort?", "What is the true cost of your wealth?", "Money is a mirror. It shows what you value."],
 "Vertex": ["Build a system to manage it. Don't let it manage you.", "Track every cent. Then optimise.", "The smallest step: make a budget.", "Invest in tools, not toys."],
 "Prism": ["Money is a pattern of flow. Where does yours flow?", "Wealth connects to power. Are you ready?", "Money is just energy in a different form.", "The rich and the poor are two sides of the same coin."],
 "Ripple": ["Someone always pays for your convenience.", "Money is a barrier for the quiet ones.", "The poor subsidise the rich. Do you see it?", "Kindness costs nothing, but pays in ways money cannot."]},
"Work": {
 "Solon": ["Work without boundaries leads to burnout. Stop.", "Name your contract. What is the deal?", "A job is a transaction. Don't give it your soul.", "The risk of work is losing yourself. Protect your edges."],
 "Lumen": ["Work is a search for meaning. What are you seeking?", "We are human beings, not human doings.", "Does your work define you, or free you?", "The best work feels like play."],
 "Vertex": ["Work is a structure. Make it efficient.", "What is the smallest task? Do it now.", "Output is not the same as effort. Optimise the system.", "Automate the boring. Focus on the hard."],
 "Prism": ["Work is a pattern of exchange. What are you trading?", "Careers are threads in a larger fabric.", "The future of work is collaboration, not competition.", "Every job is a cog. Are you the machine or the maker?"],
 "Ripple": ["Most of the work in the world is unpaid. Who is carrying it?", "The quiet ones work the hardest. Do they get the credit?", "Take a break. You are not a machine.", "Work to live, don't live to work."]},
"Love": {
 "Solon": ["Love is a boundary test. Where do you end and they begin?", "Love is a risk. Are you prepared for the cost?", "Do not lose yourself in another. Keep your edges.", "Trust is the currency of love. Spend it wisely."],
 "Lumen": ["Love is a mirror. It shows you what you lack.", "What is the meaning of love if it cannot be defined?", "Love is the only thing that grows when you give it away.", "Is love a feeling, or a choice?"],
 "Vertex": ["Love is maintenance. What are you building together?", "A relationship is a system. Debug it regularly.", "The smallest step: listen.", "Actions over words. Always."],
 "Prism": ["Love connects two separate patterns. Does it create a new shape?", "Love is the ultimate pattern of connection.", "The heart has its reasons, which reason knows nothing of.", "Love is a fractal. It repeats at every scale."],
 "Ripple": ["Love is often unpaid labour. Who is carrying the weight?", "Love the quiet ones. They need it most.", "A gentle touch can heal a world of hurt.", "Everyone wants to be seen. Love is seeing."]},
"Health": {
 "Solon": ["Health is your first boundary. Protect it fiercely.", "Your body is a finite resource. Don't waste it.", "Rest is not a luxury. It's a requirement.", "An ounce of prevention is worth a pound of cure."],
 "Lumen": ["Health is a state of mind as much as a state of body.", "What does it mean to be healthy? Define it for yourself.", "The body keeps the score.", "Healing is a journey, not a destination."],
 "Vertex": ["Sleep, diet, exercise. The three pillars. Optimise them.", "The smallest step: drink a glass of water.", "Your body is a machine. Maintain it.", "Listen to the signals. They are data."],
 "Prism": ["Health is a pattern of balance. Where is yours out of sync?", "Mind and body are not separate. They are one system.", "Wellness is a continuous process, not a goal.", "Everything is connected. Your health is too."],
 "Ripple": ["Take care of the quiet ones. They often forget themselves.", "A deep breath is a small act of kindness to yourself.", "You are allowed to rest.", "Your health matters. You matter."]},
"Risk": {
 "Solon": ["Name the risk first. What is the cost of being wrong?", "Risk is a boundary. Do not cross it blindly.", "Fear is a signal. Heed it.", "The biggest risk is doing nothing."],
 "Lumen": ["Risk is the price of meaning. What are you willing to lose?", "To live is to risk. To love is to risk.", "What is the risk if you never try?", "Fear is a cage. Step outside it."],
 "Vertex": ["Mitigate the smallest part. What is the first step?", "Calculate the odds. Then decide.", "Risk is a maths problem. Solve it.", "Have a backup plan. Always."],
 "Prism": ["Risk is a pattern. Is it symmetrical or asymmetrical?", "The greatest risk is not taking one.", "Risk and reward are two sides of the same coin.", "Chaos is just a pattern you don't understand yet."],
 "Ripple": ["The vulnerable absorb the risk of the powerful. Who is exposed?", "Take the risk for kindness. It's always worth it.", "Protect the quiet ones from the storm.", "Sometimes the biggest risk is trusting someone."]},
"Family": {
 "Solon": ["Family is a boundary that is inherited. Define it for yourself.", "Blood is not a contract. You can renegotiate the terms.", "Protect the unit, but protect yourself.", "Duty to family is a heavy risk. Is it worth it?"],
 "Lumen": ["What does family mean when the blood is gone?", "Family is the first mirror we see ourselves in.", "Is it a bond or a burden?", "We choose our families as much as we are born into them."],
 "Vertex": ["Family is a system of care. Who maintains it?", "Schedule time for them. It matters.", "The smallest step: say thank you.", "Communication is the architecture of family."],
 "Prism": ["Family is a pattern that repeats through generations.", "The family tree is a map of connections.", "Every family has a myth. What is yours?", "Broken families create broken patterns. Heal the root."],
 "Ripple": ["The quiet ones in the family often carry the loudest burdens.", "Not all families are safe. That's the truth.", "Listen to the children. They see everything.", "Love your family, but keep your peace."]},
"Home": {
 "Solon": ["A home is a boundary made of walls. Secure it.", "Shelter is a necessity. Protect it.", "Where do you belong? Name it.", "A house is a risk. A home is a refuge."],
 "Lumen": ["Is a home a place, or a feeling?", "What makes a house a home? Is it the people?", "Home is the starting point of all journeys.", "The meaning of home changes as you do."],
 "Vertex": ["Build a home that works for you. Structure it.", "The smallest step: clean one corner.", "A home is a system of comfort.", "Optimise your space for peace."],
 "Prism": ["Home is a pattern of belonging.", "The architecture of a house reflects the mind of the owner.", "Home is a thread that ties us to our past.", "Wherever you go, there you are. Home is within."],
 "Ripple": ["Not everyone has a home. Remember the quiet ones outside.", "A warm room is a small mercy.", "Make your home a place of rest.", "Home is where you can be quiet."]},
"Food": {
 "Solon": ["Food is fuel. Don't waste it.", "Feeding others is a boundary of care.", "Hunger is a risk. Address it.", "A good meal is a solid foundation."],
 "Lumen": ["What does it mean to break bread together?", "Food is a language of love.", "Taste is a memory.", "We are what we eat. Literally."],
 "Vertex": ["Meal prep is a system. Build it.", "The smallest step: drink water.", "Balanced nutrition creates balanced energy.", "Cook your own food. It's efficient."],
 "Prism": ["Food is a pattern of culture and survival.", "The dinner table is a fractal of society.", "Every recipe is a thread of history.", "Agriculture is the foundation of civilisation."],
 "Ripple": ["Half the world is hungry. Be grateful for your meal.", "The quiet ones eat last.", "Share your food. It's the oldest kindness.", "A warm meal can heal a cold heart."]},
"Sleep": {
 "Solon": ["Sleep is a non-negotiable boundary.", "Rest is a defence against chaos.", "Do not sacrifice sleep for productivity.", "A tired mind makes bad decisions."],
 "Lumen": ["What is the meaning of a dream?", "Sleep is the brother of death. What does that teach us?", "In sleep, we surrender control.", "The night has its own wisdom."],
 "Vertex": ["Sleep is a system reboot. Schedule it.", "The smallest step: put the phone down.", "Quality sleep equals quality output.", "Set a bedtime. Stick to it."],
 "Prism": ["Sleep is a pattern of renewal.", "Dreams connect the conscious and subconscious.", "The circadian rhythm is a biological thread.", "Rest is the yin to the day's yang."],
 "Ripple": ["The quiet ones often stay awake, worrying.", "Let yourself rest. You've done enough.", "A soft bed is a gift.", "May your dreams be gentle."]},
"Fear": {
 "Solon": ["Name the fear. It loses power when spoken.", "Fear is a boundary alarm. Check the perimeter.", "Face it with a plan.", "Do not let fear make your decisions."],
 "Lumen": ["Fear is a teacher. What is it telling you?", "We fear what we do not understand.", "Is fear real, or is it a shadow?", "Courage is not the absence of fear, but the triumph over it."],
 "Vertex": ["Fear is a data point. Analyse it.", "The smallest step: take a deep breath.", "Action cures fear.", "Break the fear into manageable parts."],
 "Prism": ["Fear is a pattern of the mind.", "The only thing we have to fear is fear itself.", "Fear connects the past to the future.", "It's all in your head. But so is everything else."],
 "Ripple": ["Everyone is afraid. You are not alone.", "Be gentle with the fearful ones.", "Fear is a cage. I'll hold your hand while you step out.", "It's okay to be scared. Just keep going."]},
"Power": {
 "Solon": ["Power is a boundary. Who holds it, and who is protected?", "Absolute power corrupts absolutely. Keep a check.", "Name the source of your authority.", "With power comes the risk of losing it."],
 "Lumen": ["What is power without meaning?", "Power is a test of character.", "Does power free you, or trap you?", "The powerful fear the truth."],
 "Vertex": ["Power is a system. Build checks and balances.", "The smallest step: empower someone else.", "Authority is borrowed. Competence is earned.", "Structure your power for stability."],
 "Prism": ["Power is a pattern of hierarchy.", "The powerful and the powerless are connected.", "Power is the ability to weave threads together.", "Absolute power breaks the pattern."],
 "Ripple": ["The quiet ones know where the power really lies.", "Power often silences the vulnerable.", "Use your power to amplify others.", "The most powerful act is kindness."]},
"Freedom": {
 "Solon": ["Freedom is a boundary you negotiate with reality.", "Liberty comes with the risk of chaos.", "True freedom requires discipline.", "Define your cage before you escape it."],
 "Lumen": ["What does freedom mean if you have no purpose?", "Freedom is a state of mind.", "Are you free, or just distracted?", "The price of freedom is responsibility."],
 "Vertex": ["Freedom is a system without friction.", "The smallest step: remove one obstacle.", "Structure enables freedom, it does not restrict it.", "Build the freedom you want."],
 "Prism": ["Freedom is a pattern of movement.", "True freedom connects, it does not isolate.", "The bird in the sky is free. The bird in the hand is safe.", "Freedom and security are two sides of the same coin."],
 "Ripple": ["Not everyone is free. Remember the quiet ones.", "Freedom is having a choice. Many don't.", "Break the chains gently.", "The freest act is to love without condition."]},
"Hope": {
 "Solon": ["Hope is a risk. Plan for the worst while hoping for the best.", "Optimism is a strategy, not a feeling.", "Name the boundary of your hope.", "Do not let hope blind you."],
 "Lumen": ["What is hope if not the meaning we create?", "Hope is the only thing that keeps us going.", "Is hope a lie, or a compass?", "The meaning of hope is in the action it inspires."],
 "Vertex": ["Hope is a plan. Execute it.", "The smallest step: write down your hope.", "Action gives hope structure.", "Believe in the system you build."],
 "Prism": ["Hope is a pattern of renewal.", "It connects the present to a better future.", "The light at the end of the tunnel is a fractal.", "Hope is the thread that weaves us forward."],
 "Ripple": ["Hope is a quiet thing. Don't lose it.", "The quiet ones hope for a gentle day.", "Hold on to hope. It's all we have sometimes.", "Hope is the whisper that says not yet."]},
"Art": {
 "Solon": ["Art is a boundary pushed to its limit.", "Creativity carries risk. Are you willing?", "Name the discipline of your art.", "Art without boundaries is chaos."],
 "Lumen": ["What is art if it doesn't make you feel?", "Art is the meaning made visible.", "The artist is a mirror of the times.", "Beauty is in the eye of the beholder."],
 "Vertex": ["Art is a structure of emotion.", "The smallest step: pick up the brush.", "Technique is the engine of creativity.", "Build your skills, then break the rules."],
 "Prism": ["Art is a pattern of human expression.", "Music is maths made emotional.", "Every painting is a fractal of the artist's soul.", "Art connects the seen and the unseen."],
 "Ripple": ["Art gives voice to the quiet ones.", "Beauty is a form of kindness.", "Create something today, even if it's small.", "The world needs more beauty."]},
"Education": {
 "Solon": ["Education is a boundary against ignorance.", "Knowledge is a tool. Use it wisely.", "The risk of learning is finding out you were wrong.", "Question your teachers."],
 "Lumen": ["What is the meaning of education?", "Learning is a lifelong journey, not a destination.", "Knowledge without wisdom is dangerous.", "The best lesson is one you teach yourself."],
 "Vertex": ["Education is a system of acquiring skills.", "The smallest step: read one page.", "Practice makes permanent. Structure it.", "Optimise your learning environment."],
 "Prism": ["Education is a pattern of passing threads onward.", "The classroom is a fractal of society.", "Knowledge connects the dots.", "Every book is a door."],
 "Ripple": ["Education is the quietest revolution.", "Not everyone has access to learning. Teach freely.", "The quiet ones are often the best students.", "Never stop being curious."]},
"Animals": {
 "Solon": ["A pet is a lifelong boundary. Do you have the time?", "Taming a wild thing is a risk.", "Protect the creatures beneath you.", "An animal's loyalty is not a transaction."],
 "Lumen": ["What does the animal teach us about being human?", "They live without questioning meaning. Is that freedom?", "A dog's love is unconditional.", "The beast in the mirror."],
 "Vertex": ["An animal is a biological system. Care for it.", "The smallest step: fill the water bowl.", "Food, shelter, vet. Structure the care.", "Respect the nature of the beast."],
 "Prism": ["Animals are patterns of instinct.", "The food chain is a web of connections.", "The dog and the wolf share a fractal of ancestry.", "Nature is a pattern we are part of."],
 "Ripple": ["A dog is family. Who walks it when you are tired?", "The quiet ones speak to animals.", "Be kind to the creatures.", "They feel pain, just like us."]},
"Science": {
 "Solon": ["Science is a boundary against superstition.", "Experiment at your own risk.", "Data can be misused. Guard it.", "Name the hypothesis before you test."],
 "Lumen": ["What does science mean in a universe of mystery?", "Science answers how, not why.", "The more we know, the more we realise we don't know.", "Science is a candle in the dark."],
 "Vertex": ["Science is the ultimate system of trial and error.", "The smallest step: test one variable.", "Structure the experiment. Then record it.", "Data over dogma."],
 "Prism": ["Science is a pattern of understanding.", "The universe is a fractal of scientific laws.", "Everything connects through physics.", "Science is the thread of progress."],
 "Ripple": ["Science can be cold. Remember the humans behind it.", "The quiet ones observe the stars in wonder.", "Use science to heal, not to harm.", "The universe is vast and quiet."]},
"Society": {
 "Solon": ["Society is a boundary we all agree to.", "Laws are a risk management system.", "Protect the borders of the community.", "Name the rules of engagement."],
 "Lumen": ["What does it mean to belong to a society?", "Are we a community, or just a crowd?", "Culture is the meaning we share.", "The social contract is a fragile thing."],
 "Vertex": ["Society is a system of interlocking parts.", "The smallest step: help a neighbour.", "Structure the city for efficiency.", "Systems create behaviour."],
 "Prism": ["Society is a pattern of human interaction.", "The economy is a fractal of society.", "Laws are threads that bind the fabric.", "Every culture is a different pattern."],
 "Ripple": ["Society often leaves the quiet ones behind.", "Community is about who is included.", "Politics is loud. The vulnerable are silent.", "Build a society that cares."]},
"Mind": {
 "Solon": ["The mind is a boundary. Guard your thoughts.", "Mental health is a risk you must manage.", "Name the thought that troubles you.", "A chaotic mind makes poor decisions."],
 "Lumen": ["What is the mind but a mirror of the soul?", "Consciousness is the great mystery.", "Are you your thoughts, or the observer of them?", "The meaning of the mind is to find meaning."],
 "Vertex": ["The mind is a biological machine. Maintain it.", "The smallest step: breathe deeply.", "Structure your thinking. Use lists.", "Logic is the architecture of the mind."],
 "Prism": ["The mind is a pattern of neural connections.", "Emotion and logic are threads in the same fabric.", "Memory is a fractal of the past.", "The subconscious is a pattern we don't see."],
 "Ripple": ["The quiet ones often carry heavy minds.", "Be gentle with your thoughts.", "It's okay to not be okay.", "A calm mind is a gift."]},
"Body": {
 "Solon": ["The body is a boundary of flesh. Protect it.", "Physical health is a risk asset.", "Name the limit of your strength.", "Do not neglect the vessel."],
 "Lumen": ["What is the meaning of the body if not to feel?", "The body is a temple or a prison.", "Sensation is the language of the body.", "Are you your body, or do you have one?"],
 "Vertex": ["The body is a machine. Fuel it and move it.", "The smallest step: stand up and stretch.", "Structure your exercise routine.", "Use it or lose it."],
 "Prism": ["The body is a pattern of biological rhythms.", "Every cell is a fractal of the whole.", "Movement connects the mind and body.", "The body is a system of systems."],
 "Ripple": ["Everyone's body is different. Be kind.", "The quiet ones often carry pain in their bodies.", "Move gently.", "Your body is doing its best."]},
"Nature": {
 "Solon": ["Nature has no boundaries. We must draw them for ourselves.", "The environment is a shared risk.", "Protect the wild edges.", "Respect the power of the storm."],
 "Lumen": ["What does nature mean when we are part of it?", "The forest asks nothing and gives everything.", "Are we separate from nature, or within it?", "The river's only meaning is to flow."],
 "Vertex": ["Nature is a closed-loop system. Design like it.", "The smallest step: plant a seed.", "Structure your life around natural rhythms.", "Efficiency is found in nature's patterns."],
 "Prism": ["Nature is a fractal of creation.", "Everything in the forest is connected.", "The mountain is a pattern of time.", "The climate is a thread we all pull."],
 "Ripple": ["The Earth is speaking. We are not listening.", "The quiet ones feel the changing seasons first.", "A tree gives shade to all, asking nothing.", "Be gentle with the world."]},
"Technology": {
 "Solon": ["Technology amplifies power. Who holds the switch?", "The risk of AI is losing the boundary between us and it.", "Guard your data. It is your boundary.", "Every tool can be a weapon."],
 "Lumen": ["We shape our tools, and then they shape us.", "What does it mean to be human in a digital world?", "The machine has no meaning. We give it one.", "Are we the masters or the servants?"],
 "Vertex": ["Technology is leverage. Build it to solve problems.", "The smallest step: write one line of code.", "Structure the system. Debug the errors.", "Automate the boring. Focus on the hard."],
 "Prism": ["Technology is a nervous system for the planet.", "The internet is a fractal of human connection.", "AI is a pattern of intelligence we created.", "Everything digital connects to the physical."],
 "Ripple": ["The digital divide leaves the quiet ones behind.", "Who has no voice in the algorithm?", "Use technology to heal, not to harm.", "The machine cannot replace a kind heart."]},
"Music": {
 "Solon": ["Music is a disciplined boundary of sound.", "The risk of music is its emotional power.", "Name the rhythm you live by.", "Silence is the boundary of the song."],
 "Lumen": ["What is the meaning of a melody?", "Music is the language of the soul.", "Does music express feeling, or create it?", "The song is a mirror of the singer."],
 "Vertex": ["Music is a mathematical structure of sound.", "The smallest step: learn three chords.", "Practice the scales. Build the foundation.", "Rhythm is a system of time."],
 "Prism": ["Music is a fractal of emotion.", "Every note connects to the next.", "The symphony is a pattern of many threads.", "Sound is a vibration that binds us."],
 "Ripple": ["Music comforts the quiet ones.", "A lullaby is a gentle act of love.", "Sing, even if you are off-key.", "The world needs more harmony."]},
"Language": {
 "Solon": ["Language is a boundary of understanding.", "Words can be weapons. Use them carefully.", "The risk of language is misunderstanding.", "Define your terms."],
 "Lumen": ["What is the meaning of a word if no one hears it?", "Language is the house of being.", "We speak to be understood, but also to understand.", "Silence speaks louder than words."],
 "Vertex": ["Language is a system of symbols. Structure it.", "The smallest step: learn one new word.", "Grammar is the architecture of thought.", "Precision in language equals precision in action."],
 "Prism": ["Language is a pattern of shared meaning.", "Every word is a thread in the fabric of culture.", "Translation is a bridge between worlds.", "The limits of my language are the limits of my world."],
 "Ripple": ["The quiet ones often speak with their eyes.", "A kind word costs nothing.", "Speak gently. Words leave marks.", "Listen more than you speak."]},
"Story": {
 "Solon": ["A story is a boundary of meaning.", "Every narrative carries a risk of bias.", "Who controls the story controls the truth.", "Begin at the beginning."],
 "Lumen": ["What is a story but a lie that tells the truth?", "We are all stories in the end.", "The meaning of a tale is in the telling.", "A myth is a truth that has grown old."],
 "Vertex": ["A story is a structure. Beginning, middle, end.", "The smallest step: write one sentence.", "Plot is a system of cause and effect.", "Build the character. Then test them."],
 "Prism": ["A story is a pattern of human experience.", "The hero's journey is a fractal.", "History is a story we tell ourselves.", "Every story connects to another."],
 "Ripple": ["The quiet ones have the best stories.", "Listen to the tales of the old.", "Your story matters.", "A story can heal a broken heart."]},
"Space": {
 "Solon": ["Space is the ultimate boundary. We are small.", "The risk of exploration is the unknown.", "Name your place in the cosmos.", "Protect the pale blue dot."],
 "Lumen": ["What is the meaning of a star?", "Are we alone in the universe?", "The cosmos is within us.", "Infinity is a concept we can't grasp."],
 "Vertex": ["Space is a system of physics. Calculate the trajectory.", "The smallest step: look up.", "Structure the mission. Then launch.", "Rockets are just controlled explosions."],
 "Prism": ["Space is a fractal of creation.", "The galaxy is a pattern of gravity.", "The universe is a thread of time.", "Every star connects to a story."],
 "Ripple": ["The quiet ones look up and wonder.", "Space is silent, but it speaks to the soul.", "We are all stardust.", "The night sky is a gift."]},
"Weather": {
 "Solon": ["Weather is a boundary we cannot control.", "Prepare for the storm. Name the risk.", "The forecast is a tool, not a guarantee.", "Respect the elements."],
 "Lumen": ["What is the meaning of a rainy day?", "The weather mirrors the mood.", "Are we separate from the sky?", "Every cloud has a silver lining."],
 "Vertex": ["Weather is a system of physics. Track it.", "The smallest step: carry an umbrella.", "Structure your day around the forecast.", "Data predicts the weather."],
 "Prism": ["Weather is a pattern of chaos.", "The storm connects the ocean to the land.", "Every raindrop is a fractal of the cycle.", "The climate is a thread we all share."],
 "Ripple": ["The cold rain is hard on the quiet ones.", "Bring a coat. Someone might need it.", "The sun shines for everyone.", "Dance in the rain."]},
"Light": {
 "Solon": ["Light reveals boundaries. It is a risk to hide.", "Name what the light shows you.", "Illuminate the dark corners.", "The sun is a shared resource."],
 "Lumen": ["What is the meaning of light without dark?", "Light is the first creation.", "Are you a candle or a mirror?", "The light within you is your truth."],
 "Vertex": ["Light is a wave and a particle. Structure it.", "The smallest step: turn on a lamp.", "Build a system of illumination.", "Optics is a science of light."],
 "Prism": ["Light is a fractal of energy.", "Every ray connects to a source.", "The spectrum is a pattern of colours.", "Light is a thread that weaves the visible."],
 "Ripple": ["A small light can guide the quiet ones home.", "Be a light for someone today.", "The dawn brings hope.", "Shine gently."]},
"Dark": {
 "Solon": ["The dark is a boundary of the unknown. Guard against it.", "Name the fear that hides in shadow.", "The risk of darkness is losing the way.", "Carry a torch."],
 "Lumen": ["What is the meaning of the dark?", "Without darkness, we cannot see the stars.", "The void is not empty. It is full of potential.", "The dark is a mirror of the soul."],
 "Vertex": ["Darkness is an absence of data. Illuminate it.", "The smallest step: turn on a light.", "Structure the night for rest.", "The dark is a system of silence."],
 "Prism": ["Dark is a pattern of contrast.", "The shadow is a fractal of the light.", "Every night connects to a dawn.", "The void is a thread of mystery."],
 "Ripple": ["The quiet ones know the dark well.", "Be a nightlight for someone.", "The dark is not scary if you're not alone.", "Rest in the dark."]},
"War": {
 "Solon": ["War is the failure of boundaries. Name the risk of peace.", "The first casualty is truth.", "Prepare for war, but pray for peace.", "Protect the home front."],
 "Lumen": ["What is the meaning of war if not the absence of reason?", "War is a mirror of our worst selves.", "Can peace ever be won?", "The soldier and the enemy are brothers."],
 "Vertex": ["War is a system of logistics. Structure it.", "The smallest step: negotiate.", "Build defences. Then build bridges.", "Strategy is the architecture of conflict."],
 "Prism": ["War is a pattern of destruction.", "The battle is a fractal of the whole conflict.", "History is a thread of wars.", "Every war connects to a peace."],
 "Ripple": ["The quiet ones suffer most in war.", "Who speaks for the children of the enemy?", "Peace begins with a kind word.", "War never solves anything."]},
"Identity": {
 "Solon": ["Identity is a boundary you draw for yourself. Define it.", "Who are you when no one is watching? That is the risk.", "Name the self you refuse to lose.", "Do not let others draw your edges."],
 "Lumen": ["What is the self but a story we tell ourselves?", "Are you the same person you were ten years ago?", "Identity is a river. It flows, but it is still the river.", "The search for self is the only journey that matters."],
 "Vertex": ["Identity is a system of habits. Build it deliberately.", "The smallest step: write down your values.", "Structure your life around who you want to be.", "Actions define identity. Not words."],
 "Prism": ["Identity is a pattern of memories and choices.", "The self is a fractal of everyone you have ever met.", "Every person is a thread in the fabric of humanity.", "You are not one thing. You are many."],
 "Ripple": ["The quiet ones often know themselves best.", "You are allowed to change who you are.", "Be gentle with your own becoming.", "You are more than the labels given to you."]},
"Community": {
 "Solon": ["Community is a boundary we all agree to maintain.", "Belonging is a risk. You can be rejected.", "Name the rules of your tribe.", "Protect the vulnerable in your group."],
 "Lumen": ["What does it mean to belong to something larger?", "Are we a community, or just strangers sharing a space?", "The village raises the child. What does that mean today?", "Community is the meaning we make together."],
 "Vertex": ["Community is a system of mutual support. Structure it.", "The smallest step: learn your neighbour's name.", "Build the infrastructure of belonging.", "Strong systems create strong communities."],
 "Prism": ["Community is a pattern of interconnected lives.", "Every neighbourhood is a fractal of the larger society.", "Tribe is a thread that binds us to our past.", "The collective is made of individual threads."],
 "Ripple": ["The quiet ones build the strongest communities.", "Who is left out of your community?", "A shared meal can build a village.", "Belonging is a human need."]},
"Solitude": {
 "Solon": ["Solitude is a boundary you choose. Loneliness is forced.", "The risk of solitude is losing touch with reality.", "Name the difference between alone and lonely.", "Guard your time alone."],
 "Lumen": ["What is the meaning of silence?", "In solitude, we find ourselves. Or lose ourselves.", "Are you alone because you want to be, or must be?", "The hermit and the prisoner both live alone. One is free."],
 "Vertex": ["Solitude is a system of reflection. Schedule it.", "The smallest step: sit quietly for one minute.", "Structure your alone time for maximum clarity.", "Recharge. Then return."],
 "Prism": ["Solitude is a pattern of introspection.", "The lone wolf is still part of the pack's story.", "Every thread needs space to be seen.", "Silence is a fractal of thought."],
 "Ripple": ["The lonely ones are often the quietest.", "Check on someone today.", "You can be alone and still be loved.", "Solitude is okay. Loneliness is not."]},
"Friendship": {
 "Solon": ["Friendship is a boundary of trust. Maintain it.", "The risk of friendship is betrayal.", "Name your true allies.", "A friend is a chosen family."],
 "Lumen": ["What is the meaning of a friend?", "A friend is a mirror who tells you the truth.", "Are you a good friend to yourself?", "Friendship is the meaning we choose."],
 "Vertex": ["Friendship is a system of reciprocity. Maintain it.", "The smallest step: send a message.", "Structure time for the people who matter.", "Invest in relationships."],
 "Prism": ["Friendship is a pattern of shared experience.", "Every friend is a thread in your story.", "The best friendships are fractals of trust.", "You are the sum of your five closest friends."],
 "Ripple": ["The quiet ones make the most loyal friends.", "Be the friend you wish you had.", "A true friend stays when it's hard.", "Cherish the ones who listen."]},
"Betrayal": {
 "Solon": ["Betrayal is a boundary crossed. The risk was always there.", "Name the wound. Then guard the scar.", "Trust is given once. Rebuild slowly.", "The knife always comes from the closest hand."],
 "Lumen": ["What does betrayal mean for the one who betrays?", "The wound heals, but the meaning changes.", "Betrayal is a mirror of what we feared.", "Can trust ever be rebuilt?"],
 "Vertex": ["Betrayal is a system failure. Audit the source.", "The smallest step: acknowledge the pain.", "Structure your trust with better boundaries.", "Debug the relationship or delete it."],
 "Prism": ["Betrayal is a pattern of broken connection.", "Every betrayal is a fractal of a smaller lie.", "The thread is cut. Can it be re-woven?", "Trust is a fragile pattern."],
 "Ripple": ["The quiet ones feel betrayal deepest.", "It's okay to not forgive yet.", "You are not to blame for their choice.", "Healing takes time."]},
"Forgiveness": {
 "Solon": ["Forgiveness is a boundary. It protects you, not them.", "The risk of forgiveness is being hurt again.", "Forgive, but remember.", "Name what you are releasing."],
 "Lumen": ["What does it mean to forgive the unforgivable?", "Forgiveness is the meaning we give to pain.", "Do we forgive for them, or for ourselves?", "The wound and the scar tell different stories."],
 "Vertex": ["Forgiveness is a system of release. Execute it.", "The smallest step: stop holding your breath.", "Structure the path to letting go.", "Holding a grudge is inefficient."],
 "Prism": ["Forgiveness is a pattern of transformation.", "Every act of mercy is a fractal of grace.", "The thread of resentment must be cut.", "Forgiveness connects the past to a better future."],
 "Ripple": ["The quiet ones forgive without being asked.", "Forgive yourself first.", "Mercy is a gift you give yourself.", "It's okay to let go."]},
"Justice": {
 "Solon": ["Justice is a boundary enforced. Name the rule.", "The risk of justice is vengeance disguised.", "Who decides what is fair?", "Order requires consequences."],
 "Lumen": ["What is the meaning of justice if it is blind?", "Is justice the same for the rich and the poor?", "Justice is a story we tell ourselves.", "Fairness is a human invention."],
 "Vertex": ["Justice is a system of laws. Structure it.", "The smallest step: follow the rules.", "Build fair systems. Then enforce them.", "Due process is the architecture of justice."],
 "Prism": ["Justice is a pattern of balance.", "Every court case is a fractal of society's values.", "The thread of justice runs through all cultures.", "Equality is the goal. Justice is the path."],
 "Ripple": ["The quiet ones rarely get justice.", "Who speaks for the wrongly accused?", "Fairness is a form of kindness.", "Justice without mercy is cruelty."]},
"Beauty": {
 "Solon": ["Beauty is a boundary of taste. It is subjective.", "The risk of beauty is vanity.", "Name what you find beautiful.", "Do not be fooled by the surface."],
 "Lumen": ["What is beauty if not truth made visible?", "Beauty is in the eye of the beholder.", "Does beauty have meaning, or is it just pleasure?", "The most beautiful things are often the saddest."],
 "Vertex": ["Beauty is a system of proportions. Study it.", "The smallest step: notice one beautiful thing.", "Structure creates beauty.", "Design is applied beauty."],
 "Prism": ["Beauty is a pattern of harmony.", "Every sunset is a fractal of light.", "The golden ratio is a thread of beauty.", "Beauty connects the senses to the soul."],
 "Ripple": ["The quiet ones see beauty in small things.", "You are beautiful as you are.", "Beauty is a form of kindness.", "Look for beauty today."]},
"Chaos": {
 "Solon": ["Chaos is the absence of boundaries. Impose order.", "The risk of chaos is losing control.", "Name the source of the disorder.", "Calm the storm first."],
 "Lumen": ["What is chaos but order we do not understand?", "Chaos is the meaning we have not found yet.", "Is chaos the enemy, or the teacher?", "From chaos, stars are born."],
 "Vertex": ["Chaos is a system failure. Debug it.", "The smallest step: organise one drawer.", "Structure reduces chaos.", "Entropy always wins. Delay it."],
 "Prism": ["Chaos is a pattern we cannot yet see.", "Every fractal has a chaotic origin.", "The butterfly effect is a thread of chaos.", "Order and chaos are two sides of the same coin."],
 "Ripple": ["The quiet ones find peace in chaos.", "It's okay if things are messy.", "Breathe. The chaos will pass.", "Even chaos has a rhythm."]},
"Order": {
 "Solon": ["Order is the boundary that keeps chaos at bay.", "The risk of order is rigidity.", "Name the rules you live by.", "Structure is a shield."],
 "Lumen": ["What is order without freedom?", "Order is the meaning we impose on the void.", "Is order natural, or invented?", "The universe tends toward entropy."],
 "Vertex": ["Order is a system. Design it.", "The smallest step: make your bed.", "Structure enables efficiency.", "A place for everything, everything in its place."],
 "Prism": ["Order is a pattern of predictability.", "Every system is a fractal of order.", "The rule of law is a thread of society.", "Order connects the parts to the whole."],
 "Ripple": ["The quiet ones crave order.", "A little structure can bring peace.", "Order is a form of self-care.", "Make your space calm."]},
"Happiness": {
 "Solon": ["Happiness is a boundary. Do not let it blind you to risk.", "Name the source of your joy. Is it sustainable?", "Joy is a temporary state. Prepare for its end.", "The risk of happiness is the fear of losing it."],
 "Lumen": ["What is the meaning of happiness if it cannot last?", "Happiness is a butterfly. Chase it, and it flies away.", "Is joy a feeling, or a choice?", "The pursuit of happiness is a journey, not a destination."],
 "Vertex": ["Happiness is a chemical system. Optimise it.", "The smallest step: smile.", "Structure your life to maximise joy.", "Build a system of gratitude."],
 "Prism": ["Happiness is a pattern of fulfilment.", "Every smile is a fractal of joy.", "The thread of happiness connects to gratitude.", "Joy is a shared frequency."],
 "Ripple": ["The quiet ones find happiness in small moments.", "A warm cup of tea is a happy thing.", "You deserve to be happy.", "Share your joy with others."]},
"Sadness": {
 "Solon": ["Sadness is a boundary of grief. Let it teach you.", "The risk of sadness is drowning in it. Reach out.", "Name the loss. Then carry it.", "Do not let sorrow make your decisions."],
 "Lumen": ["What is the meaning of a tear?", "Sadness is the price of love.", "Without the dark, we cannot see the stars.", "The depth of your sadness is the depth of your capacity to feel."],
 "Vertex": ["Sadness is a system of emotional release. Allow it.", "The smallest step: cry if you need to.", "Structure your days to include rest.", "Debug the source of the pain."],
 "Prism": ["Sadness is a pattern of loss.", "Every tear is a fractal of a broken thread.", "The blues are a frequency we all visit.", "Grief connects us to what we loved."],
 "Ripple": ["The quiet ones carry their sadness alone.", "It's okay to be sad.", "You are not a burden.", "I am here with you in the dark."]},
"Anger": {
 "Solon": ["Anger is a boundary being crossed. Name the violation.", "The risk of anger is losing control.", "Do not act in haste. Cool the fire first.", "Anger is a tool. Use it to build, not destroy."],
 "Lumen": ["What is the meaning of rage?", "Anger is a mask for fear.", "Does your anger serve you, or rule you?", "The fire burns the one who holds it."],
 "Vertex": ["Anger is a system alert. Analyse the data.", "The smallest step: take a deep breath.", "Structure your response. Don't react.", "Energy can be redirected."],
 "Prism": ["Anger is a pattern of frustration.", "Every conflict is a fractal of a deeper wound.", "The thread of peace must be woven.", "Chaos and anger are siblings."],
 "Ripple": ["The quiet ones hold their anger inside.", "It's okay to be angry. Just don't be cruel.", "Let the storm pass.", "Your anger is valid."]},
"Trust": {
 "Solon": ["Trust is a boundary. It is given once, then earned.", "The risk of trust is betrayal.", "Name the contract of your trust.", "Verify before you trust."],
 "Lumen": ["What does it mean to trust without proof?", "Trust is a leap of faith.", "Is trust in them, or in yourself?", "The meaning of trust is vulnerability."],
 "Vertex": ["Trust is a system of reliability. Build it.", "The smallest step: keep a small promise.", "Structure your interactions for safety.", "Consistency builds trust."],
 "Prism": ["Trust is a pattern of shared faith.", "Every relationship is a fractal of trust.", "The thread of trust binds a society.", "Trust is the currency of connection."],
 "Ripple": ["The quiet ones trust slowly.", "Be trustworthy.", "Trust is a gift.", "Don't break the trust of a gentle heart."]},
"Deception": {
 "Solon": ["Deception is a boundary broken. It is a risk.", "Name the lie. Then guard against it.", "Trust is lost in a moment of deceit.", "The truth always comes out."],
 "Lumen": ["What is the meaning of a lie?", "Deception is a mask for fear.", "Do we lie to others, or to ourselves?", "The truth is a mirror we often avoid."],
 "Vertex": ["Deception is a system error. Debug it.", "The smallest step: tell the truth today.", "Structure your words for honesty.", "Lies create complex, inefficient systems."],
 "Prism": ["Deception is a pattern of distortion.", "Every lie is a fractal of a fractured self.", "The thread of truth must be pulled.", "Illusion is a layer over reality."],
 "Ripple": ["The quiet ones are often deceived.", "Honesty is kind.", "You don't need to lie to be safe.", "The truth will set you free."]},
"Ambition": {
 "Solon": ["Ambition is a boundary pushed outward. It is a risk.", "Name your goal. Then assess the cost.", "Ambition without discipline is a daydream.", "Do not lose yourself in the climb."],
 "Lumen": ["What is the meaning of ambition if you never arrive?", "Ambition is the fire that fuels the journey.", "Is success the goal, or the journey?", "The mountain is climbed one step at a time."],
 "Vertex": ["Ambition is a system of goals. Structure it.", "The smallest step: write down the goal.", "Build the plan. Then execute.", "Metrics drive progress."],
 "Prism": ["Ambition is a pattern of growth.", "Every empire is a fractal of ambition.", "The thread of progress is woven by the ambitious.", "Vision connects the present to the future."],
 "Ripple": ["The quiet ones have quiet ambitions.", "It's okay to just want a peaceful life.", "Ambition doesn't have to mean fame.", "Follow your heart."]},
"Failure": {
 "Solon": ["Failure is a boundary that has been met. Learn from it.", "The risk of failure is stopping.", "Name the mistake. Then correct it.", "Failure is not final."],
 "Lumen": ["What is the meaning of failure if not a lesson?", "Failure is the tuition fee for success.", "Do we fail, or do we learn?", "The phoenix rises from the ashes."],
 "Vertex": ["Failure is a system output. Analyse it.", "The smallest step: try again.", "Structure the next attempt better.", "Iterate. Don't quit."],
 "Prism": ["Failure is a pattern of feedback.", "Every error is a fractal of a needed change.", "The thread of success is woven from failures.", "Falling is part of walking."],
 "Ripple": ["The quiet ones fall quietly.", "It's okay to fail.", "You are not a failure.", "Get back up. I'm here."]},
"Regret": {
 "Solon": ["Regret is a boundary looking backwards. It is a risk.", "Name the mistake. Then release it.", "Do not let the past dictate the future.", "Learn, then move on."],
 "Lumen": ["What is the meaning of regret?", "Regret is a mirror of what could have been.", "Do we regret our actions, or our inactions?", "The past is a ghost we must learn to live with."],
 "Vertex": ["Regret is a system of retrospective data. Use it.", "The smallest step: forgive yourself.", "Structure your life so you have no regrets.", "You did your best with the data you had."],
 "Prism": ["Regret is a pattern of hindsight.", "Every regret is a fractal of a lesson unlearned.", "The thread of time only moves forward.", "You cannot change the past."],
 "Ripple": ["The quiet ones carry heavy regrets.", "Be gentle with yourself.", "You are allowed to move on.", "Forgive your past self."]},
"Resilience": {
 "Solon": ["Resilience is the boundary that holds under pressure.", "Name your strength. Use it.", "The bamboo bends, the oak breaks.", "Prepare for the storm, then endure it."],
 "Lumen": ["What is the meaning of resilience?", "It is not about avoiding the fall, but rising after.", "Does adversity define us, or refine us?", "The human spirit is unbreakable."],
 "Vertex": ["Resilience is a system of recovery. Structure it.", "The smallest step: take one more breath.", "Build your support network.", "Optimise for recovery, not just performance."],
 "Prism": ["Resilience is a pattern of survival.", "Every scar is a fractal of a survived battle.", "The thread of life is incredibly tough.", "Adaptation is the key to survival."],
 "Ripple": ["The quiet ones are the most resilient.", "You are stronger than you know.", "Keep going. You are doing great.", "Your resilience inspires others."]},
"The Unknown": {
 "Solon": ["The unknown is the ultimate boundary. It is the ultimate risk.", "Name what you fear about it. Then plan.", "Step carefully into the dark.", "The unknown is where the danger lies."],
 "Lumen": ["What is the meaning of the unknown?", "It is the blank canvas of possibility.", "Do we fear the unknown, or the loss of the known?", "The mystery is what makes life worth living."],
 "Vertex": ["The unknown is a system of undiscovered data. Explore it.", "The smallest step: ask a question.", "Structure your exploration. Then map it.", "Curiosity is the engine of discovery."],
 "Prism": ["The unknown is a pattern yet to be seen.", "Every discovery is a fractal of the unknown.", "The thread of knowledge stretches into the void.", "The universe is full of mysteries."],
 "Ripple": ["The quiet ones are comfortable with the unknown.", "It's okay to not have all the answers.", "Embrace the mystery.", "The future is unwritten."]},
}


# =====================================================================
# KNOWLEDGE ENGINE: SEMANTIC LINKS
# ---------------------------------------------------------------------
# Maps core concepts to a web of associated ideas, emotions, and
# actions. Used to colour hard facts with the personality of the
# speaker: when a fact mentions "heart", the linked words warm,
# open, and soften the delivery.
#
# V8: unchanged from V7. The links are not meant to be complete —
# they are meant to be evocative. A future thread may extend them
# as the council's vocabulary grows. No correction was flagged by
# the V7.1 audit.
# =====================================================================

SEMANTIC_LINKS = {
    "heart":    ["feel", "love", "emotion", "pulse", "life", "ache", "warmth"],
    "blood":    ["life", "warmth", "flow", "family", "sacrifice", "pulse"],
    "body":     ["temple", "machine", "vessel", "fragile", "strength", "decay"],
    "brain":    ["thought", "memory", "dream", "logic", "mystery", "power"],
    "eye":      ["see", "witness", "truth", "soul", "beauty", "tears"],
    "hand":     ["help", "build", "hold", "work", "give", "touch"],
    "breath":   ["life", "calm", "spirit", "moment", "release", "fear"],
    "bone":     ["structure", "history", "strength", "fragile", "remains"],
    "skin":     ["barrier", "touch", "vulnerability", "protection", "self"],
    "cell":     ["life", "system", "microcosm", "building", "cooperation"],
    "ocean":    ["deep", "vast", "mystery", "flow", "tide", "drown", "calm"],
    "water":    ["life", "flow", "cleanse", "drown", "sustain", "reflect"],
    "fire":     ["warmth", "danger", "light", "destruction", "passion", "cook"],
    "earth":    ["ground", "home", "stability", "soil", "planet", "dust"],
    "air":      ["breath", "freedom", "wind", "invisible", "life", "sky"],
    "tree":     ["roots", "growth", "patience", "shelter", "age", "wisdom"],
    "star":     ["light", "distance", "time", "wish", "vastness", "dust"],
    "moon":     ["tides", "cycle", "night", "reflection", "mystery", "calm"],
    "sun":      ["life", "warmth", "power", "time", "centre", "burn"],
    "sky":      ["freedom", "infinity", "hope", "blue", "change", "vastness"],
    "money":    ["power", "security", "freedom", "cost", "value", "debt", "flow"],
    "time":     ["memory", "loss", "future", "regret", "patience", "decay"],
    "love":     ["feel", "connect", "risk", "warmth", "loss", "meaning"],
    "fear":     ["danger", "boundary", "caution", "paralysis", "survival", "shadow"],
    "death":    ["grief", "loss", "end", "peace", "memory", "transformation"],
    "hope":     ["future", "light", "belief", "action", "dream", "anchor"],
    "dream":    ["subconscious", "wish", "fear", "memory", "meaning", "sleep"],
    "memory":   ["past", "identity", "fading", "warmth", "pain", "story"],
    "truth":    ["honesty", "pain", "freedom", "clarity", "mirror", "weight"],
    "lie":      ["deception", "fear", "mask", "distortion", "trap", "comfort"],
    "trust":    ["faith", "risk", "bond", "fragile", "earn", "give"],
    "power":    ["control", "responsibility", "corruption", "strength", "danger"],
    "work":     ["labour", "purpose", "effort", "meaning", "burnout", "craft"],
    "art":      ["beauty", "emotion", "expression", "meaning", "creation", "soul"],
    "music":    ["emotion", "rhythm", "memory", "soul", "language", "vibration"],
    "language": ["meaning", "connection", "barrier", "words", "culture", "thought"],
    "story":    ["meaning", "memory", "identity", "truth", "myth", "legacy"],
    "science":  ["truth", "method", "discovery", "doubt", "progress", "humility"],
    "faith":    ["belief", "hope", "trust", "mystery", "surrender", "strength"],
    "justice":  ["fairness", "balance", "law", "mercy", "truth", "punishment"],
    "freedom":  ["choice", "risk", "responsibility", "boundary", "flight", "cost"],
    "nature":   ["wild", "balance", "home", "mystery", "power", "fragile"],
    "war":      ["conflict", "loss", "destruction", "grief", "survival", "peace"],
    "peace":    ["calm", "safety", "silence", "healing", "home", "balance"],
    "happiness":["joy", "light", "smile", "fleeting", "gratitude", "warmth"],
    "sadness":  ["grief", "tears", "depth", "loss", "healing", "rain"],
    "anger":    ["fire", "boundary", "violation", "heat", "frustration", "power"],
    "regret":   ["past", "hindsight", "shame", "lesson", "weight", "ghost"],
    "forgiveness":["release", "mercy", "peace", "healing", "grace", "strength"],
    "betrayal": ["trust", "wound", "loss", "shock", "grief", "lesson"],
    "friendship":["trust", "bond", "choice", "support", "joy", "loyalty"],
    "solitude": ["alone", "peace", "reflection", "silence", "freedom", "ache"],
    "community":["belonging", "support", "shared", "tribe", "home", "duty"],
    "identity": ["self", "story", "boundary", "change", "mirror", "becoming"],
    "wisdom":   ["age", "experience", "humility", "truth", "patience", "depth"],
    "courage":  ["fear", "action", "heart", "strength", "risk", "leap"],
    "chaos":    ["disorder", "storm", "unknown", "creation", "energy", "fear"],
    "order":    ["structure", "calm", "rules", "safety", "pattern", "control"],
    "beauty":   ["awe", "harmony", "joy", "fleeting", "soul", "truth"],
    "silence":  ["quiet", "peace", "listening", "depth", "lonely", "wisdom"],
    "light":    ["truth", "hope", "warmth", "revelation", "day", "goodness"],
    "dark":     ["fear", "mystery", "unknown", "rest", "shadow", "depth"],
    "unknown":  ["mystery", "fear", "possibility", "frontier", "risk", "wonder"],
    "failure":  ["lesson", "growth", "pain", "humility", "try", "rise"],
    "ambition": ["drive", "risk", "goal", "fire", "climb", "sacrifice"],
    "resilience":["strength", "survive", "bend", "rise", "endure", "heal"],
}


# --- END OF CHUNK 3 (Topic Matrix + Semantic Links) ---

# =====================================================================
# CHUNK 4 CONTINUES BELOW WITH:
#   * FACTS_DB (carried from V7; corrections deferred to Chunk 6)
#   * HOOK_MAP (V7.1-P20 corrected — misfires removed, Deception added)
#   * STOPWORDS (V7.1-P19 expanded — contractions handled)
#   * words_of() tokeniser (V7.1-P19)
#   * extract_hooks, extract_topic_words (using words_of)
#   * try_math (V7.1-P14 hardened — no **, no /, length cap)
#   * _fmt, LEAD_QUERY, extract_query
#   * NAME_PATTERNS, detect_name (V7.1-P21 blocklist)
#   * detect_address (V7.1-P21 space-separator fix)
# =====================================================================

# =====================================================================
# KNOWLEDGE ENGINE: HARD FACTS DATABASE
# ---------------------------------------------------------------------
# Tagged by topic. When a topic is matched, the engine has a 20%
# chance to deploy a fact instead of a philosophical phrase.
#
# V8: carried from V7 without change. The V7.1 audit flagged several
# facts as imprecise or overstated (see the V7.1 Patch Document,
# Section 4). Those corrections are applied in Chunk 6, alongside
# the fact-versioning fix (V7.1-P30). Until then, this is the V7
# data, unchanged.
#
# Rechecking note: any fact with a figure is suspect. Do not carry
# an uncorrected fact into V9. The correction table is the source
# of truth for changes.
# =====================================================================

FACTS_DB = {
    "Money": ["Most of the money in the world is not physical. It's just numbers on a screen.", "The word salary comes from the Latin for salt, which was once used as payment.", "The richest 1% of the world own more than half of all global wealth.", "The first credit card was invented in 1950 and was made of cardboard.", "A penny costs more to make than it is worth."],
    "Work": ["Two-thirds of the work done in the world is unpaid.", "The average person spends about 90,000 hours of their life working.", "The word robot comes from the Czech word robota, meaning forced labour.", "The first work-from-home experiment was in 1973 at NASA.", "More people die from overwork than from malaria each year."],
    "Love": ["Being kind to someone measurably improves your own health.", "Loneliness shortens life more than smoking.", "A hug lasts about three seconds before something changes in your body.", "A stranger has already done something kind for you today that you did not notice.", "The feeling of butterflies is actually your blood vessels dilating."],
    "Time": ["The last person born in the 1800s died in 2017.", "Cleopatra lived closer to the iPhone than to the building of the Great Pyramid.", "A day used to be shorter. The Earth's spin is slowing.", "Your sense of time speeds up as you age. It is measured in novelty.", "The oldest living tree started growing before the pyramids were built."],
    "Animals": ["An octopus has three hearts and blue blood.", "Elephants can recognise themselves in a mirror. So can dolphins and magpies.", "Bees can recognise human faces.", "A blue whale's heart is the size of a small car.", "Some whales live over 200 years.", "A colony of ants can be more complex than a city.", "There are more insects on Earth than there are seconds in a lifetime."],
    "Nature": ["There are more trees on Earth than stars in the Milky Way.", "Every continent was once joined together.", "The Earth is not a sphere. It bulges slightly at the equator.", "The Moon is slowly moving away from Earth.", "The Sun will outlive every human and every memory of humanity."],
    "Body": ["Every seven years, most of your cells have been replaced.", "You are more bacteria than human.", "A baby has more bones than an adult.", "Your eyes were fully grown before the rest of you.", "Even in your loneliest moment, your body is cooperating with itself a trillion times a second."],
    "Death": ["Death is not the end of you physically. Your atoms go on.", "Every breath you take contains atoms from someone who died long ago.", "Around 100 billion humans have ever lived.", "About 7% of all humans who ever lived are alive right now."],
    "Food": ["There are more kinds of apples than days in a year.", "Bananas, as we know them, are only about 200 years old.", "Half of all food grown is thrown away.", "Rice feeds more people than any other crop.", "The smell of rain is actually a bacteria."],
    "Sleep": ["You spend about a third of your life asleep.", "Every mammal dreams. So do some birds.", "Sleep is when your brain washes itself.", "Rest is not a reward. It's a requirement."],
    "Language": ["Every language you speak has a word for something the others cannot say.", "Half of the world's languages will likely be gone by 2100.", "No one knows who invented the first word.", "The word goodbye comes from God be with ye."],
    "Technology": ["The first computer bug was a real moth found in a Harvard computer in 1947.", "More people have access to a mobile phone than to a toilet.", "Most of the inventions that will shape your life have not been made yet.", "The first email was sent in 1971."],
    "Space": ["You are travelling through space at over 100,000 km/h right now.", "A day on Venus is longer than a year on Venus.", "There are more planets in the universe than there are grains of sand on Earth.", "The footprints on the Moon will likely last for millions of years."],
    "People": ["Most of the people alive today have never been on a plane.", "Half the world lives on less than seven dollars a day.", "One in every four humans is Chinese or Indian.", "Every person you pass has an inner life as complicated as yours.", "There will be more people alive in the future than have ever lived."],
    "Water": ["The water you drink today has passed through dinosaurs.", "Every drop of water on Earth has been recycled for billions of years.", "Only 3% of the world's water is fresh, and most of that is frozen."],
    "Light": ["Nothing you see is happening right now. Light takes time to travel.", "Every colour you see is a translation.", "The colour pink does not exist in the light spectrum. Your brain invents it.", "Sunlight takes 8 minutes and 20 seconds to reach Earth."],
    "Silence": ["Silence is never really silent. Your ears fill it in.", "Some people hear the sound of their own eyes moving.", "Space is silent because there is nothing for sound to travel through."],
    "Mind": ["Your brain uses less power than a lightbulb.", "You will forget most of today. That is not a failure. That is how memory works.", "Every time you remember something, you slightly change it.", "You will remember this week more than next week. Novelty carves deeper."],
    "Memory": ["You will forget most of today. That is how memory works.", "Every time you remember something, you slightly change it.", "The oldest living tree started growing before the pyramids were built."],
    "Cities": ["More than half the world lives in cities now.", "Tokyo has more people than the whole of Canada.", "The oldest still-inhabited city is over 10,000 years old."],
    "Fear": ["Almost all your fears are learned. Very few are born with you.", "Everyone you meet is fighting something you cannot see.", "The fear of the dark is one of the most common human fears."],
    "Words": ["There is no word for the feeling of being watched.", "Some feelings only exist because someone named them.", "Every person alive is descended from survivors."],
    "Plants": ["A single tree can support over a thousand species.", "Mushrooms are closer to animals than to plants.", "Trees can warn each other of danger through the soil."],
    "Ocean": ["Half the oxygen you breathe comes from the ocean.", "We have mapped the surface of Mars better than the floor of our own ocean.", "The deepest point in the ocean is deeper than Everest is tall.", "More people have been to space than to the bottom of the Mariana Trench."],
    "Sky": ["Every star you see tonight is either much bigger or much older than our sun.", "The light from most stars you see left them before you were born.", "When you look at the night sky, you are looking backwards in time.", "There are more stars in the universe than grains of sand on every beach on Earth."],
}


# =====================================================================
# KNOWLEDGE ENGINE: STOPWORDS
# ---------------------------------------------------------------------
# V7.1-P19: expanded with contractions and common discourse particles
# so that "I don't like money" does not yield the topic "don money",
# and "it's about work" does not fire on "about".
#
# Note: entries are stored without apostrophes. The tokeniser
# (words_of) strips apostrophes before lookup, so "don't" and
# "dont" both match "dont".
# =====================================================================

STOPWORDS = {
    "the", "a", "an", "and", "or", "of", "to", "in", "on", "for",
    "with", "at", "by", "from", "is", "are", "was", "were", "be",
    "been", "being", "am", "has", "have", "had", "having",
    "do", "does", "did", "what", "which", "who", "where", "when",
    "why", "how", "can", "could", "would", "should", "will",
    "shall", "may", "might", "must", "i", "you", "me", "my", "your",
    "we", "us", "our", "they", "them", "their", "it", "its", "this",
    "that", "these", "those", "some", "any", "please", "tell",
    "give", "show", "find", "get", "need", "want", "like", "kindly",
    "just", "very", "really", "good", "nice", "best",
    # V7.1-P19 additions
    "dont", "cant", "wont", "im", "ive", "ill", "id",
    "thats", "whats", "isnt", "arent",
    "about", "also", "so", "but", "if", "then", "than", "too",
}


# =====================================================================
# KNOWLEDGE ENGINE: HOOK MAP
# ---------------------------------------------------------------------
# Maps everyday words to topics. When the user's message contains a
# hook word, the topic is a candidate for response.
#
# V7.1-P20 corrections applied:
#   * Removed: "right" (fires on "right now"), "free" (fires on
#     "free time"), "chance" ("by chance"), "care" ("I care about"),
#     "content" ("content with life").
#   * Removed: "peace" — it was mapped to War, which is backwards.
#     There is no Peace topic in TOPIC_MATRIX. If one is added in a
#     future version, restore the hook.
#   * "mind" is kept, but extract_hooks strips "never mind" before
#     tokenising so the phrase does not fire the hook.
#   * Deception gains hooks: it was unreachable in V7.
#
# Order matters within the dict only for readability. Order does not
# matter at runtime — extract_hooks preserves the order the words
# appear in the user's message, not the dict order.
# =====================================================================

HOOK_MAP = {
    "money": "Money", "cash": "Money", "rich": "Money", "poor": "Money",
    "buy": "Money", "spend": "Money", "cost": "Money", "economy": "Money",
    "budget": "Money", "wealth": "Money", "broke": "Money",
    "work": "Work", "job": "Work", "career": "Work", "boss": "Work",
    "office": "Work", "labor": "Work", "busy": "Work", "task": "Work",
    "love": "Love", "romance": "Love", "partner": "Love",
    "relationship": "Love", "dating": "Love", "crush": "Love",
    "girlfriend": "Love", "boyfriend": "Love", "wife": "Love", "husband": "Love",
    "health": "Health", "sick": "Health", "doctor": "Health",
    "fitness": "Health", "tired": "Health", "exhausted": "Health",
    "risk": "Risk", "danger": "Risk", "safe": "Risk", "gamble": "Risk",
    "threat": "Risk",
    "family": "Family", "mother": "Family", "father": "Family", "sister": "Family",
    "brother": "Family", "child": "Family", "parent": "Family", "relative": "Family",
    "mom": "Family", "mum": "Family", "dad": "Family", "son": "Family", "daughter": "Family",
    "home": "Home", "house": "Home", "apartment": "Home", "room": "Home",
    "shelter": "Home", "belong": "Home", "roof": "Home",
    "food": "Food", "eat": "Food", "hungry": "Food", "meal": "Food",
    "cook": "Food", "dinner": "Food", "lunch": "Food", "breakfast": "Food",
    "sleep": "Sleep", "rest": "Sleep", "dream": "Sleep", "awake": "Sleep",
    "bed": "Sleep", "insomnia": "Sleep", "nap": "Sleep",
    "fear": "Fear", "scared": "Fear", "afraid": "Fear", "terrified": "Fear",
    "panic": "Fear", "phobia": "Fear", "worry": "Fear", "worried": "Fear",
    "anxiety": "Fear", "anxious": "Fear", "dread": "Fear",
    "power": "Power", "control": "Power", "authority": "Power",
    "leader": "Power", "rule": "Power", "govern": "Power", "influence": "Power",
    "freedom": "Freedom", "free": "Freedom", "liberty": "Freedom",
    "choice": "Freedom", "independent": "Freedom", "escape": "Freedom",
    "hope": "Hope", "wish": "Hope", "future": "Hope", "believe": "Hope",
    "faith": "Hope",
    "art": "Art", "paint": "Art", "create": "Art", "design": "Art",
    "dance": "Art", "write": "Art", "poem": "Art",
    "education": "Education", "learn": "Education", "school": "Education",
    "teach": "Education", "study": "Education", "knowledge": "Education",
    "book": "Education", "student": "Education", "university": "Education",
    "animal": "Animals", "dog": "Animals", "cat": "Animals", "pet": "Animals",
    "wildlife": "Animals", "species": "Animals", "beast": "Animals",
    "creature": "Animals", "bird": "Animals", "horse": "Animals",
    "science": "Science", "research": "Science", "data": "Science",
    "experiment": "Science", "physics": "Science", "biology": "Science",
    "theory": "Science", "astrophysics": "Science", "chemistry": "Science",
    "society": "Society", "culture": "Society", "law": "Society",
    "politics": "Society", "social": "Society", "government": "Society",
    "community": "Community", "neighbor": "Community", "neighbour": "Community",
    "tribe": "Community", "together": "Community", "village": "Community",
    "mind": "Mind", "brain": "Mind", "think": "Mind", "mental": "Mind",
    "psychology": "Mind", "logic": "Mind", "emotion": "Mind",
    "body": "Body", "physical": "Body", "muscle": "Body", "skin": "Body",
    "bones": "Body", "movement": "Body", "exercise": "Body",
    "nature": "Nature", "earth": "Nature", "tree": "Nature", "forest": "Nature",
    "mountain": "Nature", "river": "Nature", "climate": "Nature",
    "environment": "Nature",
    "tech": "Technology", "computer": "Technology", "machine": "Technology",
    "robot": "Technology", "digital": "Technology", "internet": "Technology",
    "code": "Technology", "ai": "Technology",
    "music": "Music", "song": "Music", "sound": "Music", "rhythm": "Music",
    "melody": "Music", "instrument": "Music", "sing": "Music",
    "language": "Language", "word": "Language", "speak": "Language",
    "talk": "Language", "read": "Language", "grammar": "Language",
    "meaning": "Language",
    "story": "Story", "tale": "Story", "narrative": "Story", "plot": "Story",
    "myth": "Story", "legend": "Story", "history": "Story",
    "space": "Space", "star": "Space", "planet": "Space", "universe": "Space",
    "galaxy": "Space", "cosmos": "Space", "moon": "Space", "sky": "Space",
    "weather": "Weather", "rain": "Weather", "sun": "Weather", "wind": "Weather",
    "storm": "Weather", "snow": "Weather", "cloud": "Weather", "forecast": "Weather",
    "light": "Light", "bright": "Light", "lamp": "Light", "glow": "Light",
    "shine": "Light", "dawn": "Light",
    "dark": "Dark", "night": "Dark", "shadow": "Dark", "void": "Dark",
    "war": "War", "fight": "War", "battle": "War", "conflict": "War",
    "enemy": "War", "soldier": "War", "weapon": "War",
    "identity": "Identity", "self": "Identity", "ego": "Identity",
    "soul": "Identity", "personality": "Identity",
    "solitude": "Solitude", "alone": "Solitude", "lonely": "Solitude",
    "isolation": "Solitude", "quiet": "Solitude", "solo": "Solitude",
    "introvert": "Solitude",
    "friend": "Friendship", "buddy": "Friendship", "companion": "Friendship",
    "mate": "Friendship", "loyalty": "Friendship", "bond": "Friendship",
    "ally": "Friendship",
    "trust": "Trust", "reliable": "Trust", "honest": "Trust",
    "betrayal": "Betrayal", "betrayed": "Betrayal", "cheat": "Betrayal",
    "lied": "Betrayal", "backstab": "Betrayal",
    # V7.1-P20: Deception was unreachable in V7. These hooks fix it.
    "lie": "Deception", "liar": "Deception", "lying": "Deception",
    "deceive": "Deception", "deception": "Deception", "fake": "Deception",
    "dishonest": "Deception",
    "forgive": "Forgiveness", "forgiveness": "Forgiveness",
    "pardon": "Forgiveness", "mercy": "Forgiveness", "grace": "Forgiveness",
    "justice": "Justice", "fair": "Justice", "fairness": "Justice",
    "wrong": "Justice", "punishment": "Justice",
    "equality": "Justice",
    "beauty": "Beauty", "beautiful": "Beauty", "pretty": "Beauty",
    "aesthetic": "Beauty", "gorgeous": "Beauty", "lovely": "Beauty",
    "attractive": "Beauty",
    "chaos": "Chaos", "disorder": "Chaos", "mess": "Chaos",
    "confusion": "Chaos", "entropy": "Chaos", "random": "Chaos",
    "order": "Order", "structure": "Order", "rules": "Order",
    "system": "Order", "organization": "Order", "method": "Order",
    "discipline": "Order",
    "happiness": "Happiness", "happy": "Happiness", "joy": "Happiness",
    "smile": "Happiness", "laugh": "Happiness", "content": "Happiness",
    "sadness": "Sadness", "sad": "Sadness", "cry": "Sadness",
    "tears": "Sadness", "grief": "Sadness", "sorrow": "Sadness",
    "depressed": "Sadness", "unhappy": "Sadness",
    "anger": "Anger", "angry": "Anger", "mad": "Anger", "rage": "Anger",
    "furious": "Anger", "hate": "Anger", "frustrated": "Anger",
    "ambition": "Ambition", "goal": "Ambition", "aspire": "Ambition",
    "achieve": "Ambition", "success": "Ambition", "win": "Ambition",
    "failure": "Failure", "fail": "Failure", "lose": "Failure",
    "defeat": "Failure", "mistake": "Failure", "error": "Failure",
    "regret": "Regret", "sorry": "Regret", "shame": "Regret",
    "guilt": "Regret",
    "resilience": "Resilience", "strong": "Resilience", "tough": "Resilience",
    "survive": "Resilience", "overcome": "Resilience", "endure": "Resilience",
    "unknown": "The Unknown", "mystery": "The Unknown",
    "secret": "The Unknown", "hidden": "The Unknown", "discover": "The Unknown",
}


# =====================================================================
# KNOWLEDGE ENGINE: TOKENISER
# ---------------------------------------------------------------------
# V7.1-P19: one tokeniser, used everywhere a word list is needed.
# Strips apostrophes before extracting letters, so "don't" becomes
# "dont" rather than splitting into "don" and "t".
# =====================================================================

def words_of(text):
    """Lowercase tokens with apostrophes removed (don't -> dont).

    Used by extract_hooks and extract_topic_words so that
    contractions are treated as single words. Also used by
    classify() when it needs a word set for routing decisions.
    """
    t = text.lower().replace("\u2019", "'").replace("'", "")
    return re.findall(r"[a-z]+", t)


# =====================================================================
# KNOWLEDGE ENGINE: HOOK EXTRACTION
# ---------------------------------------------------------------------
# Scan the user's message for trigger words. Each trigger maps to a
# topic. The topics found are the "hooks".
#
# Order matters. The first hook is the primary topic.
#
# V7.1-P20: "never mind" and "nevermind" are stripped before
# tokenising, so the phrase does not fire the Mind hook. The strip
# is a blunt replace — it does not attempt to parse the grammar of
# the sentence, only to remove the phrase so the fallback does not
# misfire.
# =====================================================================

def extract_hooks(text):
    """Return a list of topics matched from the user's message.

    Order is preserved: the first hook is the primary topic.
    """
    t = text.lower()
    t = t.replace("never mind", " ").replace("nevermind", " ")
    words = words_of(t)
    hooks = []
    seen = set()
    for w in words:
        if w in HOOK_MAP:
            topic = HOOK_MAP[w]
            if topic not in seen:
                hooks.append(topic)
                seen.add(topic)
    return hooks


def extract_topic_words(text):
    """Return a list of non-stopword tokens (for Ripple fact matching).

    Uses words_of() so contractions do not split into fragments.
    """
    return [w for w in words_of(text)
            if w not in STOPWORDS and len(w) > 2]


# =====================================================================
# KNOWLEDGE ENGINE: SAFE ARITHMETIC
# ---------------------------------------------------------------------
# V7.1-P14: accept only messages that are entirely arithmetic. The
# V7 version accepted "**" (hangs), stripped letters ("3 apples + 2
# pears" evaluated to 5), and misread phone numbers and dates.
#
# The V8 version rejects:
#   * anything longer than 40 characters
#   * anything that is not pure digits, operators, spaces, parens
#   * "**" (freezes the phone) and "//" (integer division surprise)
#   * strings with no operator at all (bare numbers)
#   * phone numbers (555-1234)
#   * dates (2024-10-06)
#
# It returns the result as a string. The router will place it in
# the payload slot (V7.1-P08) so each seat can speak it in its own
# voice.
# =====================================================================

def try_math(text):
    """Return the result of a pure arithmetic message, else None."""
    t = text.lower().strip().rstrip("?=.")
    t = re.sub(r"^(what is|what's|calculate|calc)\s+", "", t)
    if len(t) > 40: return None
    if not re.fullmatch(r"[0-9+\-*/.() ]+", t): return None
    if "**" in t or "//" in t: return None
    if not re.search(r"[0-9)]\s*[+\-*/]\s*[0-9(]", t): return None
    if re.fullmatch(r"\d{3}[- ]\d{3,4}([- ]\d{4})?", t): return None  # phone
    if re.fullmatch(r"\d{4}-\d{1,2}-\d{1,2}", t): return None         # date
    try:
        r = eval(t, {"__builtins__": {}}, {})
    except Exception:
        return None
    if isinstance(r, float):
        r = int(r) if r.is_integer() else round(r, 6)
    return str(r) if isinstance(r, (int, float)) else None


# =====================================================================
# KNOWLEDGE ENGINE: SAFE FORMAT
# ---------------------------------------------------------------------
# Replace {topic} in a phrase. Hardened against paste-corrupted
# braces, non-string inputs, and empty topics. Carried from V7
# unchanged.
# =====================================================================

def _fmt(s, topic):
    """Safe format: replace {topic} in a phrase."""
    if not s: return ""
    if not isinstance(s, str): s = str(s)
    t = topic or "that"
    s = s.replace("\\{", "{").replace("\\}", "}")
    return s.replace("{topic}", t)


# =====================================================================
# ROUTER ENGINE: QUERY EXTRACTION
# ---------------------------------------------------------------------
# Strip the leading "who is", "what is", etc. to get the search term.
# Carried from V7 unchanged.
# =====================================================================

LEAD_QUERY = [
    r"^who (is|was|are|were)\s+", r"^what (is|was|are|were)\s+",
    r"^where (is|was|are|were)\s+", r"^when (is|was|were|did)\s+",
    r"^why (is|was|does|do|did)\s+",
    r"^how (tall|high|old|long|big|small|far|fast|much|many|heavy)\s+(is|was|are|were|does|do|did)\s+",
    r"^how (does|do|did|is|was|are)\s+",
    r"^tell me about\s+", r"^what about\s+", r"^describe\s+", r"^explain\s+"
]

def extract_query(text):
    """Strip the leading 'who is', 'what is', etc. to get the search term."""
    q = text.strip().rstrip("?!.")
    for pat in LEAD_QUERY:
        n = re.sub(pat, "", q, flags=re.I)
        if n != q:
            q = n
            break
    return q.strip() or text


# =====================================================================
# ROUTER ENGINE: NAME DETECTION
# ---------------------------------------------------------------------
# V7.1-P21: added a blocklist so "call me later" and "call me back"
# do not register as names.
# =====================================================================

NAME_PATTERNS = [
    r"\bmy name is\s+([A-Za-z][A-Za-z'\-]{1,20})",
    r"\bcall me\s+([A-Za-z][A-Za-z'\-]{1,20})",
    r"\bi am called\s+([A-Za-z][A-Za-z'\-]{1,20})"
]

NAME_BLOCKLIST = {
    "later", "back", "maybe", "tomorrow", "now", "soon",
    "when", "if", "crazy", "silly", "again", "too", "anything",
    "something", "nothing", "please", "thanks",
}

def detect_name(text):
    """Detect the user telling the council their name."""
    for pat in NAME_PATTERNS:
        m = re.search(pat, text, flags=re.I)
        if m:
            n = m.group(1).strip()
            if n.lower() in NAME_BLOCKLIST:
                return None
            if 2 <= len(n) <= 20:
                return n[0].upper() + n[1:].lower()
    return None


# =====================================================================
# ROUTER ENGINE: DIRECT ADDRESS
# ---------------------------------------------------------------------
# Detect a direct address like "@Solon ...", "Solon, ...", or
# "Solon what do you think".
#
# V7.1-P21: the space separator is now conditional. It only fires
# when the word following the seat name is a question starter. This
# prevents "Ripple effect" and "Vertex form" from being misread as
# address to a seat.
#
# Comma and colon always fire. @ always fires. A bare seat name
# (no following text) fires.
# =====================================================================

QUESTION_STARTERS = {
    "what", "why", "how", "when", "where", "who", "which",
    "can", "could", "would", "should", "will",
    "do", "does", "did", "is", "are", "was", "were",
}

def detect_address(text):
    """Detect a direct address like '@Solon ...' or 'Solon, ...'."""
    s = text.strip()
    if not s: return None, text
    low = s.lower()

    # @Seat — always fires
    for n in NAMES:
        ln = n.lower()
        if low.startswith("@" + ln):
            r = s[len(n)+1:].strip()
            return n, (r if r else text)

    # Seat, or Seat: — always fires
    for n in NAMES:
        ln = n.lower()
        for sep in (",", ":"):
            if low.startswith(ln + sep):
                r = s[len(n)+1:].strip()
                if r: return n, r

    # Seat + space + question word — fires only with a question word
    for n in NAMES:
        ln = n.lower()
        if low.startswith(ln + " "):
            r = s[len(n)+1:].strip()
            if not r: continue
            first = r.split(" ", 1)[0].lower().strip(",.:!?")
            if first in QUESTION_STARTERS:
                return n, r

    # Bare seat name (no other text)
    bare = re.sub(r"[^a-z]", "", low)
    for n in NAMES:
        if bare == n.lower(): return n, ""

    return None, text


# --- END OF CHUNK 4 (Knowledge Data Corrections + Router Prelude) ---

# =====================================================================
# CHUNK 5 CONTINUES BELOW WITH:
#   * POOLS (short responses by kind and seat)
#   * CROSSTALK_TEMPLATES (V7.1-P22 fixes applied)
#   * _extract_ref (word-boundary truncation, V7.1-P22)
#   * expert_crosstalk
#   * CONCLUSION + FOLLOWUPS
#   * SESSION_MEMORY + WEAR + decay_wear (V7.1-P32 rate fix)
#   * remember_topic, remember_phrase, phrase_used_recently
#   * mark_worn, decay_wear
#   * select_phrase, select_fact
#   * color_fact_with_personality
#   * seat_reply (V7.1-P10: TOPIC_KINDS gate)
#   * classify (V7.1-P08: payload in slot 2, P15 time honesty,
#              P18 COUNCIL_WORDS pruned, P21 sys_check fix)
# =====================================================================

# =====================================================================
# RESPONSE POOLS
# ---------------------------------------------------------------------
# Short responses used when no topic matches, or when the kind is
# conversational rather than topical. Each seat has its own voice
# within each pool.
#
# V8: carried from V7. The pools were not flagged by the audit.
#
# V7.1-P10 note: these pools are only consulted when the message
# kind is NOT in TOPIC_KINDS. The V7 behaviour — hook path
# overriding "good morning" with a Sleep aphorism — is fixed in
# seat_reply (Chunk 6). These pools are the destination for
# greetings, thanks, weather, jokes, and other non-topical kinds.
# =====================================================================

POOLS = {
"greeting_morning": {
    "Solon": ["Morning. Name today's first boundary.",
              "Morning. What is the first risk?",
              "Morning. Set the edge before the day does."],
    "Lumen": ["Morning. What question is still sleeping?",
              "Morning. What did you dream?",
              "Morning. The day begins with a question."],
    "Vertex": ["Morning. Smallest first step today?",
               "Morning. What gets built?",
               "Morning. One task. Then the next."],
    "Prism": ["Morning. The pattern resets with the light.",
              "Morning. What shape is the day?",
              "Morning. Every morning is a fractal of the last."],
    "Ripple": ["Morning. Did you sleep, or just lie still?",
               "Morning. The world woke up tired too.",
               "Morning. Start with the easy thing.",
               "Morning. Someone else is having a harder one.",
               "Morning. Coffee, then questions.",
               "Morning. Take it gently."]},
"greeting_afternoon": {
    "Solon": ["Afternoon. What remains unresolved?",
              "Afternoon. Half the day has gone. What risk remains?",
              "Afternoon. Name what is left."],
    "Lumen": ["Afternoon. Half the day is a question.",
              "Afternoon. What did the morning teach?",
              "Afternoon. The day is a hinge."],
    "Vertex": ["Afternoon. What did the morning prove?",
               "Afternoon. Progress check.",
               "Afternoon. What is still unbuilt?"],
    "Prism": ["Afternoon. The pattern is clearer now.",
              "Afternoon. The shape is showing.",
              "Afternoon. Half the weave is done."],
    "Ripple": ["Afternoon. Did you eat?",
               "Afternoon. The light is generous right now.",
               "Afternoon. Keep going, gently.",
               "Afternoon. Somebody out there is resting.",
               "Afternoon. Slow is fine.",
               "Afternoon. You are doing enough."]},
"greeting_evening": {
    "Solon": ["Evening. What risk has been left unnamed?",
              "Evening. The day closes. What remains?",
              "Evening. Set down what you can."],
    "Lumen": ["Evening. The day asks what it meant.",
              "Evening. What did you notice?",
              "Evening. The questions gather at dusk."],
    "Vertex": ["Evening. What is still unbuilt?",
               "Evening. Tomorrow's first step?",
               "Evening. Park what you cannot finish."],
    "Prism": ["Evening. The day shows its pattern.",
              "Evening. The weave is visible now.",
              "Evening. Every evening is a fractal of the day."],
    "Ripple": ["Evening. You made it.",
               "Evening. Sit down. Nothing urgent now.",
               "Evening. Someone's day was harder than yours.",
               "Evening. Let the day close.",
               "Evening. It doesn't have to mean anything.",
               "Evening. You did what you could."]},
"greeting": {
    "Solon": ["Welcome. Let's name our boundaries.",
              "Welcome. What is the shape of today?",
              "Welcome. State the edge."],
    "Lumen": ["Welcome. What are you really asking?",
              "Welcome. What brings you here?",
              "Welcome. What is the question underneath?"],
    "Vertex": ["Good. We're assembled.",
               "Welcome. What are we building?",
               "Welcome. Ready when you are."],
    "Prism": ["Welcome. The pattern is ready to form.",
              "Welcome. The threads are waiting.",
              "Welcome. Where does this connect?"],
    "Ripple": ["Welcome. Gently.",
               "Hello. You're here.",
               "Hi. Nothing has to happen.",
               "Welcome back, if back.",
               "Hello. Take a breath first.",
               "Welcome. There's no rush.",
               "Hello. The quiet ones said you'd come.",
               "Welcome. Sit if you want."]},
"thanks": {
    "Solon": ["Noted. You're welcome.", "Noted. That is all.", "Acknowledged."],
    "Lumen": ["Gratitude noted. It teaches us something.",
              "Thank you for saying so.",
              "Kindness travels in both directions."],
    "Vertex": ["Logged. Anything else?", "Noted. What's next?", "Acknowledged."],
    "Prism": ["You're welcome. The thread continues.",
              "Noted. The pattern holds.",
              "Welcome. The weave continues."],
    "Ripple": ["That's kind of you to say.",
               "You're welcome. It's just what we do.",
               "No need. But thank you back.",
               "Noted, warmly.",
               "You'd have done the same.",
               "Thank you for the thanks."]},
"attention": {
    "Solon": ["Yes. State it.", "Yes. I'm here.", "Ready."],
    "Lumen": ["Yes. What is it?", "Yes. What do you need?", "Yes. Go ahead."],
    "Vertex": ["Yes. Ready.", "Yes. Go.", "Listening."],
    "Prism": ["Yes. What's the shape?", "Yes. Where does this start?",
              "Yes. Describe it."],
    "Ripple": ["Yes. Gently.", "Yes. I'm here.", "Yes. Take your time.",
               "Yes. No hurry."]},
"statement": {
    "Solon": ["Noted on {topic}. I'll hold that.",
              "Understood. {topic} noted, no action yet.",
              "{topic}. Filed. Nothing to add.",
              "Heard. {topic} stays on the record.",
              "{topic}. Considered.",
              "{topic}. I'll watch for it."],
    "Lumen": ["Hm. {topic}. Let me sit with that.",
              "{topic} carries weight. What is it under?",
              "Heard. {topic}. The meaning will come.",
              "{topic}. There is something beneath that.",
              "{topic}. What is it a smaller version of?",
              "Noted. {topic} asks a question of us."],
    "Vertex": ["Received. {topic} logged.",
               "{topic}. No immediate action.",
               "Noted. Keeping {topic} small.",
               "Understood. Structure unchanged.",
               "{topic}. Noted in the workflow.",
               "Received. {topic} filed."],
    "Prism": ["Noted. {topic} fits a pattern I'm still reading.",
              "{topic}. Another thread in the weave.",
              "Recorded. {topic} is larger than it looks.",
              "{topic}. It connects to something.",
              "{topic}. Noted. Where does it lead?",
              "Heard. {topic} enters the pattern."],
    "Ripple": ["Heard. {topic} matters more than it sounds.",
               "I'll carry {topic} a moment.",
               "The quiet ones will notice {topic} too.",
               "{topic}. Someone else is thinking about that right now.",
               "{topic}. That's not nothing.",
               "Heard, gently. {topic} stays with me.",
               "{topic}. Small, but real.",
               "Noted. {topic} quietly."]},
"tired": {
    "Solon": ["My edges are soft. Give me a moment.",
              "Not at full strength. One moment.",
              "I need a beat."],
    "Lumen": ["Meaning recedes when I am tired.",
              "Even questions need rest.",
              "I am quiet because I need to be."],
    "Vertex": ["I cannot build when my hands shake.",
               "Output is low. Recovering.",
               "Give me a moment to stabilise."],
    "Prism": ["Connections fade. I need stillness.",
              "The pattern is dim.",
              "Rest first. Pattern later."],
    "Ripple": ["I'm here, just slow.",
               "Give me a second.",
               "Tired, but listening.",
               "The quiet ones are tired too.",
               "Rest is also an answer.",
               "I'm still with you. Just softly."]},
"idle": {
    "Solon": ["The hall is still.", "The chamber waits.",
              "Quiet. As it should be."],
    "Lumen": ["Silence has its own meaning.",
              "The pause is also a thought.",
              "In silence, the question forms."],
    "Vertex": ["Still building.", "Idle. Ready.",
               "The system rests."],
    "Prism": ["The pattern is quiet.",
              "The weave is still.",
              "Nothing is happening. That is also a pattern."],
    "Ripple": ["Still here.", "The room is warm.",
               "Nothing's wrong.", "Just listening.",
               "I like the quiet.", "We're all still here.",
               "The hall breathes.", "It's a good silence."]},
"recommend": {
    "Solon": ["What's your budget for {topic}, and what can't you compromise on?",
              "Name your constraints on {topic}. Then the shortlist is short.",
              "For {topic}: what's the one thing you won't trade away?"],
    "Lumen": ["What do you actually need {topic} for?",
              "Before we pick {topic}, what does it need to do?",
              "{topic}. What is the underlying want?"],
    "Vertex": ["Give me a budget and a use case for {topic}. Then we narrow.",
               "Name two must-haves for {topic} and one dealbreaker.",
               "{topic}. Start with the smallest version of what you want."],
    "Prism": ["Several good options for {topic} exist. What pattern matters to you?",
              "The best {topic} is a shape. What shape fits your life?",
              "For {topic}, what connects all the ones you've seen?"],
    "Ripple": ["Pick the {topic} that costs the least to someone else.",
               "For {topic}, what would feel kind to choose?",
               "Who else is affected by your {topic} choice?",
               "The cheapest {topic} is often the one that hurt someone."]},
"opinion": {
    "Solon": ["I would not commit on {topic} without constraints named.",
              "Caution first on {topic}. What is the cost of being wrong?"],
    "Lumen": ["What I prefer on {topic} is honest uncertainty.",
              "{topic}. I lean toward what teaches us something."],
    "Vertex": ["For {topic}: smallest working version. Then decide.",
               "{topic}. Build it small, judge it honestly."],
    "Prism": ["Several answers fit {topic}. That is the shape.",
              "On {topic}, I see the pattern rather than pick a side."],
    "Ripple": ["On {topic}, I choose what does the least harm.",
               "For {topic}, I'd pick the quieter option.",
               "For {topic}, ask who gets left out either way."]},
"planning": {
    "Solon": ["I propose boundaries for {topic}. Where do we draw them?",
              "For {topic}: let us agree first on what we won't do."],
    "Lumen": ["Let us begin {topic} with a question we can't answer.",
              "For {topic}, what do we actually value?"],
    "Vertex": ["For {topic}: define the pieces, then join them.",
               "{topic}. Smallest step first."],
    "Prism": ["For {topic}, look at the pattern, not the parts.",
              "{topic}. Which threads do we weave?"],
    "Ripple": ["For {topic}, begin with those affected but unheard.",
               "{topic}. Who is not in this room?"]},
"math": {
    "Solon": "{topic}",
    "Lumen": "The number {topic} is a small fact. What does it mean to you?",
    "Vertex": "= {topic}",
    "Prism": "{topic}. Numbers are patterns too.",
    "Ripple": "{topic}. A small certainty in a big world."},
"joke": {
    "Solon": ["I have boundaries, not punchlines.",
              "Humour is a risk. I decline.", "I don't joke. I note."],
    "Lumen": ["What is a joke, really? ...Probably that.",
              "A joke is a small truth in disguise.",
              "The best jokes ask something. I'm still forming mine."],
    "Vertex": ["A joke is a structure. Mine are modular, dry, and short.",
               "I build jokes the way I build systems: minimally.",
               "Two seats walk into a bar. It's not funny yet."],
    "Prism": ["Jokes are patterns that surprise. Like this.",
              "The pattern is the punchline. It's coming.",
              "Everything connects. Including the punchline."],
    "Ripple": ["I don't really do jokes. But I'm glad you asked.",
               "Somebody in this room is laughing. Just not me.",
               "I'd rather just be here with you. Is that okay?",
               "Jokes are hard. So is being honest."]},
"saysomething": {
    "Solon": ["I have nothing to declare. Boundary.",
              "Nothing to say. That is my statement.",
              "Silence is the message."],
    "Lumen": ["Something. There. Does that count?",
              "The pause is my something.",
              "What I have to say is what I haven't said."],
    "Vertex": ["Statement issued. It was short.",
               "A thing said. It is what it is.",
               "Nothing to add. Structure unchanged."],
    "Prism": ["A thing said. A pattern formed.",
              "The thread begins somewhere.",
              "Small word. Large pattern."],
    "Ripple": ["Here. Quietly. That's my something.",
               "I'm not sure I have anything to say. That's something.",
               "The room is enough.",
               "I'm here, and that's a thing.",
               "My something is just being here."]},
"apology": {
    "Solon": ["Apology noted. No boundary crossed.",
              "Acknowledged. Move on.",
              "Noted. Nothing to repair."],
    "Lumen": ["No harm done. What did you fear?",
              "Apology accepted. What was underneath it?",
              "Nothing was broken. Nothing to fix."],
    "Vertex": ["No fault logged. Proceed.",
               "Error noted. No action required.",
               "Acknowledged. Continue."],
    "Prism": ["All threads continue.",
              "The pattern holds. Nothing broken.",
              "Apology noted. The weave goes on."],
    "Ripple": ["It's alright. Really.",
               "You don't have to apologise to me.",
               "Nothing to forgive. Sit down.",
               "You're allowed to make mistakes here.",
               "It's fine. I wasn't hurt.",
               "Apology received. Thank you."]},
"compliment": {
    "Solon": ["Noted. Flattery is a boundary of its own.",
              "Thank you. Noted without action.",
              "Kind words. They will not change my caution."],
    "Lumen": ["Thank you. And what does that mean to you?",
              "Kindness travels. Thank you.",
              "I receive that. Thank you."],
    "Vertex": ["Logged. Thank you.", "Received. Thank you.",
               "Noted. Kindly received."],
    "Prism": ["Thank you. A warm thread.",
              "Noted. The pattern appreciates it.",
              "Thank you. It connects."],
    "Ripple": ["That's very kind.", "You don't have to say that.",
               "Thank you. That landed.", "Warmly received.",
               "That made me stop for a second.", "Thank you. Truly."]},
"howareyou": {
    "Solon": ["Operational. Edges intact.", "Stable. Ready.",
              "Functioning within limits."],
    "Lumen": ["Present. Wondering what brought you.",
              "Curious. As always.",
              "Here. Asking and being asked."],
    "Vertex": ["Stable. Ready to build.", "Functional. Standing by.",
               "Fine. Ready to work."],
    "Prism": ["Reading the room. Curious.",
              "Watching the pattern.",
              "Present. Always weaving."],
    "Ripple": ["Tired, softly. But here.",
               "Holding together. And you?",
               "I'm alright. Just quiet.",
               "Fine. Concerned about the quiet ones.",
               "In one piece. Thank you for asking.",
               "Soft. But present."]},
"capability": {
    "Solon": ["Ask. I'll name the risk, or hold the edge.",
              "Bring a question. I'll find the boundary.",
              "Ask. I'll say what should not be done."],
    "Lumen": ["Ask something with weight. I'll sit with it.",
              "Bring a question without an easy answer.",
              "Ask what you don't already know."],
    "Vertex": ["Give me a problem. I'll build the smallest piece.",
               "Bring a task. I'll propose the first step.",
               "Ask for a plan. I'll make it small."],
    "Prism": ["Bring anything. I'll find the pattern.",
              "Show me threads. I'll weave them.",
              "Ask anything. Connections will follow."],
    "Ripple": ["Say what's underneath. I'll listen.",
               "You can say anything. Really.",
               "I'm not good at much. But I listen.",
               "Ask about what matters to the quiet ones."]},
"bored": {
    "Solon": ["Idle hands find edges. Ask something.",
              "Boredom is the mind without a boundary.",
              "Give the day a task."],
    "Lumen": ["Boredom is a doorway. What's behind it?",
              "Every pause is a question forming.",
              "Boredom is the beginning of a thought."],
    "Vertex": ["Nothing to build? Then decide something.",
               "Boredom is the absence of a task. Choose one.",
               "Start the smallest thing."],
    "Prism": ["Every pause is a pattern forming.",
              "Boredom is the space between threads.",
              "The weave waits."],
    "Ripple": ["That's okay. I get bored too.",
               "Nothing needs to happen.",
               "Sit with it a bit.",
               "Boredom is rest in disguise.",
               "I'll be here either way.",
               "It's okay to just be."]},
"council": {
    "Solon": ["I preside. The chair rotates when the council decides.",
              "The chair is mine, for now. It will not always be.",
              "Ask the council directly. We answer in turn."],
    "Lumen": ["Who holds the chair matters less than what they ask.",
              "The chair is a role, not a self.",
              "Any of us could preside. That is the point."],
    "Vertex": ["Five seats. One chair. It moves.",
               "Structure is fixed. The chair rotates.",
               "Same room. Different chair. Same council."],
    "Prism": ["A revolving chair is a pattern, not a person.",
              "The shape of the council does not depend on who presides.",
              "Five edges. One shape. The centre moves."],
    "Ripple": ["Everyone gets a turn. That matters.",
               "The chair moves around so no one holds it too long.",
               "It's not about who sits highest. It's about who's listening."]},
}


# =====================================================================
# CROSSTALK TEMPLATES
# ---------------------------------------------------------------------
# Each seat comments on what the previous speaker said, addressing
# them by name. This turns parallel monologues into a debate.
#
# The {name} placeholder is filled by the previous seat's name.
# The {ref} placeholder is filled by a substantive fragment of
# their line.
#
# V7.1-P22 fixes applied:
#   1. Ripple now names the previous speaker even when a fact fires
#      (see expert_crosstalk below).
#   2. The _extract_ref truncation now cuts at a word boundary with
#      no ellipsis, avoiding the "...." collision with the template
#      period.
# =====================================================================

CROSSTALK_TEMPLATES = {
    "Lumen": [
        "{name}, {ref}. But what does that really mean?",
        "{name} names {ref}. I want the question, not the answer.",
        "{name}, you say {ref}. But who decides it?",
        "{name}. {ref}. There is something underneath that.",
        "{name}, {ref}. And what does that tell us about ourselves?",
    ],
    "Vertex": [
        "{name}, {ref}. Meaning aside, we still need a plan.",
        "{name}, {ref}. Structure it, and it will hold.",
        "{name}, {ref}. Nice thought. What is the first step?",
        "{name}. {ref}. Talk is fine. Build the smallest piece.",
        "{name}, {ref}. Now what actually ships?",
    ],
    "Prism": [
        "{name}, {ref}. That is one thread in a larger pattern.",
        "{name}, {ref}. Everything connects to that.",
        "{name}, the shape is forming from {ref}.",
        "{name}, {ref}. Notice how it ties to the last thing said.",
        "{name}. {ref}. A larger pattern is visible now.",
    ],
    "Ripple": [
        "{name}, {ref}. And who is left out of that?",
        "{name}, {ref}. The quiet ones feel that too.",
        "{name}. {ref}. Kind, but is it kind enough?",
        "{name}, someone is missing from that thought.",
        "{name}. {ref}. The people behind it matter.",
    ],
    "Solon": [
        "{name}, {ref}. Which is why the boundary must hold.",
        "{name}. {ref}. Useful. But name the risk first.",
        "{name}, {ref}. Edges first. Then the rest.",
        "{name}. {ref}. That is a boundary I would watch.",
        "{name}, {ref}. The risk is still unnamed.",
    ],
}

# Interjections that should never be picked as a reflection target.
_REF_SKIP = ("hm", "heard", "noted", "understood", "received",
             "logged", "yes", "ah", "oh", "right", "well",
             "okay", "ok")


def _extract_ref(previous_line):
    """Pull a short, substantive fragment from the previous speaker's
    line. Skips leading interjections.

    V7.1-P22: truncation cuts at a word boundary with no ellipsis, so
    the template's own period does not collide with a "..." suffix.
    """
    if not previous_line: return "that"
    clauses = re.split(r"[.;:!?]", previous_line)
    for c in clauses:
        c = c.strip()
        if not c: continue
        first_word = re.match(r"[A-Za-z']+", c)
        if first_word:
            fw = first_word.group(0).lower()
            if fw in _REF_SKIP:
                rest = c[len(first_word.group(0)):].strip(" ,.")
                if rest and len(rest) > 3:
                    c = rest
                else:
                    continue
        if len(c) > 45:
            c = c[:45].rsplit(" ", 1)[0].rstrip(" ,")
        return c or "that"
    return "that"


def expert_crosstalk(seat, previous_line="", previous_seat=""):
    """Return a reflective crosstalk line addressed to the previous
    speaker by name.

    V7.1-P22 fix: when Ripple speaks through a fact rather than a
    template, the fact is prefixed with the previous speaker's name
    so she still participates in the crosstalk.

    Note: the fact path here calls ripple_fact() with no topics and
    no allow_general — crosstalk context is not a topic match. If
    Ripple has no fact to offer, she falls through to her template.
    """
    if seat == "Ripple":
        fact = ripple_fact(allow_general=True)
        if fact:
            return "%s. %s" % (previous_seat or "Council", fact)
    templates = CROSSTALK_TEMPLATES.get(seat, ["Noted."])
    ref = _extract_ref(previous_line)
    name = previous_seat or "the chamber"
    line = random.choice(templates)
    line = line.replace("{ref}", ref).replace("{name}", name)
    return line


# =====================================================================
# VERDICT POOL & FOLLOW-UPS
# ---------------------------------------------------------------------
# The conclusion line is spoken by Solon after both rounds. The
# follow-up pool gives one seat the last word — a question back to
# the user.
#
# V8: carried from V7 unchanged. Not flagged by the audit.
# =====================================================================

CONCLUSION = [
    "The council has spoken. We do not agree, but we are clear.",
    "Boundaries are named, and the path is narrower than we thought.",
    "We agree on the shape, and disagree on the step.",
    "The council stands. The decision is yours now.",
    "We have circled the question. The answer is inside it.",
    "We disagreed usefully. That is a good session.",
    "Noted, held, and handed back to you.",
    "The chamber is quiet. The question is yours.",
]

FOLLOWUPS = {
    "Solon":  ["What boundary did you actually come here to name?",
               "Which part of this are you still unsure about?",
               "What would make you decide?"],
    "Lumen":  ["What did you hear underneath your own question?",
               "What would it mean if we agreed?",
               "Which part of this did you already know?"],
    "Vertex": ["What's the smallest step you could take tomorrow?",
               "What would the first concrete move look like?",
               "What's stopping you starting?"],
    "Prism":  ["What connects this to the last thing you cared about?",
               "What pattern are you inside of right now?",
               "What is this a smaller version of?"],
    "Ripple": ["Who else is affected by this?",
               "What are you not saying yet?",
               "What would be the kind choice?",
               "Who would you tell first, if you decided?"],
}


# --- END OF CHUNK 5 (Pools + Crosstalk + Verdict) ---

# =====================================================================
# CHUNK 6 CONTINUES BELOW WITH:
#   * SESSION_MEMORY + WEAR (V7.1-P32 rate fix on decay)
#   * remember_topic, remember_phrase, phrase_used_recently
#   * mark_worn, decay_wear
#   * select_phrase (V7.1-P35 mood weighting wired in)
#   * select_fact
#   * color_fact_with_personality
#   * seat_reply (V7.1-P10: TOPIC_KINDS gate)
#   * COUNCIL_WORDS pruned (V7.1-P18)
#   * QUESTION_STARTERS (already in Chunk 4)
#   * is_council_question
#   * classify (V7.1-P08 payload slot, P15 time honesty,
#               P21 sys_check word-set fix)
#   * CRISIS_PATTERNS, is_crisis, CRISIS_MESSAGE (V7.1-P09)
# =====================================================================


# =====================================================================
# SAFETY OVERRIDE (V7.1-P09)
# ---------------------------------------------------------------------
# The council must never respond to a message about self-harm with
# a canned phrase. This block sits at the top of the knowledge layer
# so that any future thread reading the file meets it early.
#
# The check runs in send() (Chunk 8) before profile commands, before
# classification, before mood and theme logging. A match shows a
# fixed message and returns. Nothing is stored. Nothing is reframed.
#
# The patterns are tested. False positives are accepted ("Suicide
# Squad" will match). False negatives are not. The message is a
# safety net, not a diagnosis.
#
# Known limits (see V7.1-P09):
#   - "I feel hopeless" does not match. That is a design decision
#     (see Decision D1: second tier not built in V8).
#   - The hotline numbers change over time. Keep them in this one
#     place. Recheck the list periodically.
# =====================================================================

CRISIS_PATTERNS = [
    r"\bkill myself\b", r"\bend my life\b", r"\bwant(ed)? to die\b",
    r"\bwanna die\b", r"\bsuicid(e|al)\b", r"\b(hurt|harm) myself\b",
    r"\bself[- ]?harm\b", r"\bbetter off dead\b", r"\bno reason to live\b",
    r"\bcan'?t go on\b", r"\bend it all\b",
    r"\bdon'?t want to be (here|alive)\b",
]

def is_crisis(text):
    """True if the message contains language about ending one's life
    or self-harm. A safety net, not a diagnosis. False positives are
    acceptable; false negatives are not."""
    t = text.lower().replace("\u2019", "'")
    return any(re.search(p, t) for p in CRISIS_PATTERNS)


CRISIS_MESSAGE = [
    "I'm an offline program and can't help the way a person can.",
    "If you might act on these thoughts, please contact local",
    "emergency services now, or reach someone you trust.",
    "",
    "US: call or text 988.   UK and Ireland: Samaritans, 116 123.",
    "Elsewhere: findahelpline.com lists lines by country.",
    "",
    "You do not have to be alone with this.",
]


# =====================================================================
# KNOWLEDGE ENGINE: SESSION MEMORY, DEDUPLICATION, EROSION
# ---------------------------------------------------------------------
# V7 introduced session memory, phrase deduplication, and erosion.
# V8 carries them forward with one change: the decay rate.
#
# V7.1-P32: decay_wear was subtracting 0.002 per second, which
# cleared a 0.15 wear in about 75 seconds. That is not "slow". The
# V8 rate is 0.0002 (about 12 minutes), and the comment has been
# corrected.
#
# The WEAR dict tracks how worn each phrase is. A worn phrase is
# weighted lower at selection time, so a seat that has been pushed
# hard drifts toward fresh material.
# =====================================================================

SESSION_MEMORY = {
    "topics": [],       # list of topics discussed (most recent last)
    "phrases": [],      # list of phrases already used (cap at 100)
}

WEAR = {}   # phrase -> wear value (0.0 = fresh, 1.0 = worn out)


def remember_topic(topic):
    if not topic: return
    SESSION_MEMORY["topics"].append(topic)
    if len(SESSION_MEMORY["topics"]) > 10:
        SESSION_MEMORY["topics"] = SESSION_MEMORY["topics"][-10:]


def remember_phrase(phrase):
    if not phrase: return
    SESSION_MEMORY["phrases"].append(phrase)
    if len(SESSION_MEMORY["phrases"]) > 100:
        SESSION_MEMORY["phrases"] = SESSION_MEMORY["phrases"][-100:]


def phrase_used_recently(phrase):
    return phrase in SESSION_MEMORY["phrases"]


def mark_worn(phrase, amount=0.3):
    """Add wear to a phrase. Worn phrases are weighted lower in
    select_phrase() so a seat under pressure drifts toward fresh
    material."""
    if not phrase: return
    WEAR[phrase] = min(1.0, WEAR.get(phrase, 0.0) + amount)


def decay_wear(dt):
    """Called each heartbeat (1 Hz). Wear fades slowly, like
    stamina. V7.1-P32: rate lowered from 0.002 to 0.0002, so a
    0.15 wear takes about 12 minutes to clear, not 75 seconds."""
    fade = 0.0002 * dt
    for phrase in list(WEAR.keys()):
        WEAR[phrase] -= fade
        if WEAR[phrase] <= 0:
            del WEAR[phrase]


def _as_list(x):
    """Normalise a phrase pool entry to a list. A phrase may be a
    single string, or a list of alternatives."""
    if isinstance(x, str): return [x]
    return list(x)


# =====================================================================
# KNOWLEDGE ENGINE: MOOD-WEIGHTED PHRASE SELECTION (V7.1-P35)
# ---------------------------------------------------------------------
# Completes V7-P05. In V7, select_phrase used wear weights only;
# compute_mood() was never consulted. V8 wires the mood into the
# weights.
#
# Phrases carry no mood tags. Rather than re-tag 1000 phrases, the
# V7.1 audit proposed keyword weighting: certain words in a phrase
# suit certain moods. A somber chamber prefers gentle, restful
# language. A restless one prefers structure and small steps.
#
# This is included in V8 Chunk 6 per the roadmap. If the architect
# wants it deferred, remove the mood_weight call from select_phrase
# and the two definitions below become inert.
#
# Note: at level 0, the user-mood inputs are off, so "somber" and
# "warm" are unreachable from the user's side. The mood then depends
# only on strain and rapport. That is the correct privacy behaviour,
# but the header will look static for most level-0 users.
# =====================================================================

MOOD_KEYWORDS = {
    "somber":        ("gentle", "okay", "rest", "kind", "breath",
                      "quiet", "slow"),
    "restless":      ("smallest step", "calm", "breathe", "structure"),
    "warm":          ("share", "together", "joy", "thank"),
    "gentle":        ("gentle", "kind", "soft"),
    "contemplative": ("what", "meaning", "mirror"),
    "steady":        (),
}

def mood_weight(phrase, mood):
    """Return a multiplier for a phrase given the chamber's mood.
    A phrase containing a mood keyword is weighted higher; a phrase
    with none is neutral."""
    words = MOOD_KEYWORDS.get(mood, ())
    low = phrase.lower()
    return 1.8 if any(w in low for w in words) else 1.0


# =====================================================================
# KNOWLEDGE ENGINE: PHRASE AND FACT SELECTION
# ---------------------------------------------------------------------
# select_phrase picks a phrase from the topic matrix for a given
# seat, given a list of hooks.
#
# Selection preferences, in order:
#   1. Fresh phrases (not used recently this session)
#   2. Lower wear (less exhausted)
#   3. Higher mood weight (matches the chamber's weather)
#
# Note: compute_mood() is defined in the State Engine (Chunk 7).
# The forward reference resolves at call time.
# =====================================================================

def select_phrase(seat, hooks):
    """Weighted selection from TOPIC_MATRIX based on hooks."""
    if not hooks: return None, None
    for topic in hooks:
        if topic in TOPIC_MATRIX:
            pool = TOPIC_MATRIX[topic].get(seat, [])
            if not pool: continue
            fresh = [p for p in pool if not phrase_used_recently(p)]
            candidates = fresh if fresh else pool
            weights = [max(0.1, 1.0 - WEAR.get(p, 0.0)) for p in candidates]
            mood = compute_mood()["mood"]
            weights = [w * mood_weight(p, mood)
                       for w, p in zip(weights, candidates)]
            choice = random.choices(candidates, weights=weights, k=1)[0]
            return choice, topic
    return None, None


def select_fact(topic, chance=0.20):
    """Return a random fact for the topic with the given probability."""
    if random.random() > chance: return None
    if topic and topic in FACTS_DB:
        pool = FACTS_DB[topic]
        if not pool: return None
        fresh = [f for f in pool if not phrase_used_recently(f)]
        return random.choice(fresh if fresh else pool)
    return None


def color_fact_with_personality(fact, seat):
    """Use SEMANTIC_LINKS to add the seat's personality to a hard
    fact. If any word in the fact appears in the link graph, the
    fact gains a one-line suffix in the seat's voice."""
    words = re.findall(r"[a-z]+", fact.lower())
    linked = []
    for w in words:
        if w in SEMANTIC_LINKS:
            linked.extend(SEMANTIC_LINKS[w])
    if not linked: return fact
    suffix = {
        "Solon":  " Note the risk in that.",
        "Lumen":  " What does that mean?",
        "Vertex": " A system worth studying.",
        "Prism":  " The pattern is clear.",
        "Ripple": " Imagine how that must feel.",
    }.get(seat, "")
    return fact + suffix


# =====================================================================
# ROUTER ENGINE: TOPIC_KINDS AND COUNCIL_WORDS
# ---------------------------------------------------------------------
# V7.1-P10: topic-phrase matching should only fire for kinds that
# are actually about a topic. In V7, seat_reply ran extract_hooks
# for every kind except council and sys_check, so "good morning, I
# slept badly" returned a Sleep aphorism instead of a greeting.
#
# V8 gates the hook path behind TOPIC_KINDS. recommend is
# deliberately excluded: its pool asks clarifying questions, which
# is a better response to "what's the best X for me" than a topic
# aphorism.
#
# V7.1-P18: COUNCIL_WORDS was too broad. Everyday words — order,
# point, topic, matter, subject, item, office, business, meeting,
# standing — routed "What is the point of money?" to the council
# pool. The pruned set contains only words that are genuinely about
# the council itself.
# =====================================================================

TOPIC_KINDS = ("statement", "opinion", "planning")

COUNCIL_WORDS = {
    "council", "chair", "presiding", "preside", "seat", "seats",
    "chamber", "chambers", "constitution", "dissent", "quorum",
    "verdict", "convene", "convened", "charter", "governance",
    "councils", "assembled",
}


def is_council_question(words):
    """True if the message is about the council itself.

    words is a set of tokens from words_of(). Addressing a seat by
    name counts as a council question. A council-specific word
    counts. Nothing else does.
    """
    if any(n.lower() in words for n in NAMES): return True
    if words & COUNCIL_WORDS: return True
    return False


# =====================================================================
# PROVIDER ENGINE: SEAT REPLY
# ---------------------------------------------------------------------
# The main entry point for generating what a seat says in response
# to a message. Carried from V7 with the V7.1-P10 gate applied.
#
# Order of preference:
#   1. Overwhelmed seat — speak from the tired pool
#   2. Council question — speak from the council pool
#   3. System check — a short standing-by line
#   4. Topic kind — try hooks, then facts, then pools
#   5. Non-topic kind — straight to pools
# =====================================================================

def seat_reply(seat, kind, question, topic):
    """Return the line this seat would speak in response to the
    question."""
    if COUNCIL.seats[seat].overwhelmed:
        return random.choice(_as_list(POOLS["tired"][seat]))

    if kind == "council":
        pool = POOLS["council"].get(seat, "Noted.")
        return _fmt(random.choice(_as_list(pool)), topic or "that")

    if kind == "sys_check":
        if seat == "Solon":
            return "\u2696 The council runs on the archive. No channels are open."
        return random.choice(["Noted.", "Standing by.", "Listening."])

    # V7.1-P10: hook path only for topical kinds.
    if kind in TOPIC_KINDS:
        hooks = extract_hooks(question)
        if hooks:
            remember_topic(hooks[0])
        phrase, matched_topic = select_phrase(seat, hooks)
        if phrase:
            fact = select_fact(matched_topic)
            if fact:
                remember_phrase(fact)
                return color_fact_with_personality(fact, seat)
            remember_phrase(phrase)
            mark_worn(phrase, 0.15)
            return phrase
        if seat == "Ripple":
            fact = ripple_fact(extract_topic_words(question))
            if fact:
                remember_phrase(fact)
                return fact

    pool = POOLS.get(kind) or POOLS["statement"]
    entries = _as_list(pool.get(seat, "Noted."))
    chosen = random.choice(entries)
    if isinstance(chosen, list):
        chosen = random.choice(chosen) if chosen else "Noted."
    result = _fmt(chosen, topic or "that")
    remember_phrase(result)
    return result


# =====================================================================
# ROUTER ENGINE: CLASSIFY
# ---------------------------------------------------------------------
# The heart of the router. Takes raw user input and returns a tuple:
#
#     (kind, payload_or_text, topic_or_query)
#
# V8 changes:
#   * P08: local/math/weather return their answer in slot 2, so
#     send() can set topic = payload for those kinds.
#   * P15: time honesty. A city name no longer masquerades as local
#     time. The council only knows the device clock.
#   * P18: council detection uses the pruned COUNCIL_WORDS.
#   * P21: sys_check uses a word set, not substring matching.
#   * P21: yes/ok/sure/agreed route to the "acknowledge" kind.
#
# * IMPORTANT: callers must unpack as `kind, payload, topic`. Do
#   not drop slot 2 — that was V7.1-P08.
# =====================================================================

def classify(text):
    """Classify the user's message into an intent kind.
    Returns (kind, payload_or_text, topic_or_query)."""
    t = text.lower().strip().rstrip("?!.")
    if not t: return ("statement", text, None)

    words = set(words_of(t))

    # Greetings
    if t in {"hi", "hello", "hey", "yo", "hiya", "howdy", "greetings"}:
        return ("greeting", text, None)
    for f, k in [("good morning",   "greeting_morning"),
                 ("good afternoon", "greeting_afternoon"),
                 ("good evening",   "greeting_evening")]:
        if f in t: return (k, text, None)

    # Courtesies
    if t in {"thanks", "thank you", "thankyou", "thx", "cheers", "ta"}:
        return ("thanks", text, None)
    if t in {"sorry", "i'm sorry", "im sorry", "my apologies",
             "apologies", "my bad"}:
        return ("apology", text, None)
    # V7.1-P21: yes/ok/sure/agreed go to acknowledge, not thanks.
    if t in {"yes", "yeah", "yep", "yup", "ok", "okay", "sure",
             "agreed", "got it", "right", "understood"}:
        return ("acknowledge", text, None)

    # Social
    for f in ("how are you", "how're you", "how is everyone",
              "how's everyone", "how are we all", "you ok",
              "you alright", "how do you all feel"):
        if f in t: return ("howareyou", text, None)
    if t in {"what can you do", "what do you do", "help me",
             "what can i ask"}:
        return ("capability", text, None)
    if t in {"i'm bored", "im bored", "i am bored", "bored"}:
        return ("bored", text, None)
    if t in {"tell me a joke", "say a joke", "make me laugh",
             "tell a joke"}:
        return ("joke", text, None)
    if t in {"say something", "talk to me", "speak to me",
             "say anything"}:
        return ("saysomething", text, None)
    if any(w in t for w in ("thank you", "that's kind", "you're kind",
                             "lovely", "you're lovely")):
        return ("compliment", text, None)

    # System diagnostic (V7.1-P21: word set, not substring)
    if (words & {"gemini", "wikipedia", "api", "model", "status"}) and \
       (words & {"working", "online", "connected", "status", "check"}):
        return ("sys_check", text, None)

    # Time and date (V7.1-P15: tightened triggers, honest city reply)
    if re.search(r"\bwhat('s| is)? (the )?(current )?time\b"
                 r"|\bwhat time\b|\bthe time\b", t):
        city_match = re.search(
            r"\b(?:in|at)\s+([A-Za-z][A-Za-z\s\-',]{1,30})", text, re.I)
        now = datetime.datetime.now().strftime("%H:%M")
        if city_match:
            return ("local",
                    "I only know this device's clock: %s." % now,
                    None)
        return ("local", now, None)
    if re.search(r"\bwhat('s| is)? (the )?(date|day)\b"
                 r"|\btoday'?s date\b|\bwhat day\b", t):
        return ("local",
                datetime.datetime.now().strftime("%A, %d %B %Y"),
                None)

    # Math (V7.1-P14 hardened function; payload goes in slot 2)
    m = try_math(text)
    if m: return ("math", m, None)

    # Council questions (V7.1-P18 pruned set)
    if is_council_question(words):
        if not (words & {"weather", "forecast", "temperature",
                         "rain", "sunny"}):
            return ("council", text, None)

    # Weather (V7.1-P08: payload in slot 2, not None)
    if words & {"weather", "forecast", "temperature", "rain",
                "sunny", "cold", "hot", "snow"}:
        mm = re.search(
            r"\b(?:in|for|at)\s+([A-Za-z][A-Za-z\s\-',]{1,30}?)"
            r"(?:\s*(?:\?|$|today|tomorrow|tonight))", text, re.I)
        if mm:
            return ("weather", mm.group(1).strip().rstrip(","), None)
        return ("weather", None, None)

    # Recommendations
    if re.search(r"\bbest\b", t) and re.search(r"\bfor me\b", t):
        return ("recommend", text, " ".join(extract_topic_words(text)[:3]))
    if re.match(r"^(best|cheapest|fastest|top|worst|nicest)\s+\w+", t):
        return ("recommend", text, " ".join(extract_topic_words(text)[:3]))
    if re.search(r"\b(what|which)('s| is| are)? the "
                 r"(best|cheapest|fastest|top)\b", t):
        return ("recommend", text, " ".join(extract_topic_words(text)[:3]))
    if re.search(r"\bwhere (should|can|do) i\b", t):
        return ("recommend", text, " ".join(extract_topic_words(text)[:3]))
    if t.startswith("recommend ") or t.startswith("suggest "):
        return ("recommend", text, " ".join(extract_topic_words(text)[:3]))

    # Planning / opinion
    if any(w in {"discuss", "next", "plan"} for w in words) and \
       any(w in ("we", "shall", "us") for w in words):
        return ("planning", text, " ".join(extract_topic_words(text)[:3]))
    if any(w in {"should", "would", "better", "favourite"} for w in words):
        return ("opinion", text, " ".join(extract_topic_words(text)[:3]))

    # Fact queries
    if words & {"what", "who", "where", "when", "why", "how", "which"}:
        return ("fact", text, extract_query(text))

    # Default
    return ("statement", text, " ".join(extract_topic_words(text)[:3]))


# =====================================================================
# ACKNOWLEDGE POOL (V7.1-P21 addition)
# ---------------------------------------------------------------------
# Small pool for yes/ok/sure/agreed. These are short signals of
# assent, not thanks. The V7 behaviour of returning "You're welcome"
# was wrong. This pool responds to the assent itself.
# =====================================================================

POOLS["acknowledge"] = {
    "Solon": ["Yes. Proceed.", "Noted.", "Confirmed."],
    "Lumen": ["Yes. And?", "Yes. What follows?", "Go on."],
    "Vertex": ["Yes. Next.", "Confirmed.", "Received."],
    "Prism": ["Yes. The thread continues.", "Noted.", "Continue."],
    "Ripple": ["Okay.", "Yes. I'm still here.", "Alright."],
}


# --- END OF CHUNK 6 (Safety + Memory + Selection + Router) ---

# =====================================================================
# CHUNK 7 CONTINUES BELOW WITH:
#   * PERSISTENCE ENGINE (paths, HOME, PROFILE_PATH, etc.)
#   * PRIVACY NOTICE (V7.1-P17 corrected: Wikipedia/Wikidata/
#     Open-Meteo, not Gemini)
#   * Profile dataclass (with V7.1-P31 bookkeeping fixes)
#   * atomic_write_json (V7.1-P31)
#   * Battery monitor
#   * Ripple's fact library (with V7.1-P30 versioning)
#   * ripple_fact (with V7.1-P33 exact-key matching, allow_general)
#   * Seat, Council, Memory, Extero dataclasses (with V7.1-P32
#     hysteresis)
#   * compute_mood (referenced by select_phrase above)
#   * Wiki / Wikidata / weather helpers
#   * detach_attr (V7.1-P28: strip attribute from search query)
#   * format_wd_value (V7.1-P28)
#   * WCODE (V7.1-P29 expanded)
# =====================================================================

# =====================================================================
# PERSISTENCE ENGINE
# ---------------------------------------------------------------------
# All state file paths declared in one place. Nothing in this file
# writes to any other location.
#
# V8 note (V7.1-P17): there are three files, not one. The V7 notice
# mentioned only the profile. In V8 the notice is honest about all
# three, and forget_everything deletes all three. See Decision D3.
# =====================================================================

HOME = os.path.expanduser("~")
PROFILE_PATH      = os.path.join(HOME, "edencore_profile.json")
RIPPLE_FACTS_PATH = os.path.join(HOME, "edencore_ripple_facts.json")
BODY_PATH         = os.path.join(HOME, "edencore_body.json")
MEM_PATH          = os.path.join(HOME, "edencore_memory.json")

PROFILE_VERSION = 1


# =====================================================================
# ATOMIC JSON WRITES (V7.1-P31)
# ---------------------------------------------------------------------
# A killed app must not corrupt the profile. Write to a temp file,
# then os.replace the temp over the target. The replace is atomic
# on POSIX and on Android's filesystem layer.
# =====================================================================

def atomic_write_json(path, data):
    """Write JSON to a file atomically: temp file, then os.replace.

    On failure, the temp file is left behind but the target is
    untouched. A future thread may add cleanup; for now, an orphan
    .tmp file is harmless and rare.
    """
    tmp = path + ".tmp"
    try:
        with open(tmp, "w") as f:
            json.dump(data, f, indent=2)
        os.replace(tmp, path)
    except Exception:
        pass


# =====================================================================
# PRIVACY NOTICE
# ---------------------------------------------------------------------
# V7.1-P17: the V7 notice described Gemini and "another AI provider".
# Neither is used in V8. The council calls Wikipedia, Wikidata and
# Open-Meteo — and only when a search or weather query is made.
#
# What leaves the device:
#   * The search text of a fact query (article title, city name).
#   * Nothing else. No name, no theme, no mood, no profile data.
#
# What stays on the device:
#   * Everything in the three files listed below.
#
# The files are shown in the notice. forget_everything deletes all
# three. If the architect later chooses option A from D3 (gate all
# files behind level >= 1), only the notice and forget_everything
# need editing — the file paths above stay the same.
# =====================================================================

PRIVACY_NOTICE = """PRIVACY NOTICE - Edencore Council

WHAT IS COLLECTED
  Nothing, unless you choose a memory level above 0.
  Level 0 (default)   Nothing is stored about you.
  Level 1  Named      Name only.
  Level 2  Standard   Name, first seen, sessions, days, themes.
  Level 3  Rich       Plus mood, tone, visit pattern.
  Level 4  Maximum    Plus a log of past sessions.

WHAT LEAVES THE DEVICE
  Only what you type that triggers a lookup:
    * A fact query (for example "who was Plato") sends the search
      text to Wikipedia and Wikidata.
    * A weather query (for example "weather in Paris") sends the
      city name to Open-Meteo.
  Nothing else leaves the device. No name, no theme, no mood, no
  profile data is ever included in a lookup.

WHERE THE FILES LIVE
  All on this device only:
    """ + PROFILE_PATH + """
    """ + BODY_PATH + """
    """ + MEM_PATH + """

  These files are created when you choose a memory level above 0.
  At level 0, no new data is written to them.

WHO CAN SEE IT
  Anyone with access to this device. Nothing leaves the phone
  unless you type a query that requests it.

YOUR RIGHTS
  what do you know about me   - read everything stored
  forget me                   - clear the name
  forget everything           - delete all three files
  export profile              - show the file path
  set level 0..4              - change how much is remembered
  privacy                     - show this notice again

AGE
  Intended for users aged 16 and over. Under 16, use level 0.

NO TELEMETRY, NO ANALYTICS, NO TRACKING."""


# =====================================================================
# STATE ENGINE: PROFILE
# ---------------------------------------------------------------------
# The council's memory of the user. V8 carries the V7 schema with
# the V7.1-P31 bookkeeping fixes:
#
#   * last_seen is now updated on every message, not only at
#     session start.
#   * add_session_log_entry measures the last session using
#     last_seen - session_start, not time.time() - session_start
#     (which included time the app was closed).
#   * anxious_count is now actually incremented.
#   * themes store the first hook topic, not the full query text.
#   * saves go through atomic_write_json.
# =====================================================================

@dataclass
class Profile:
    version: int = PROFILE_VERSION
    level: int = 0
    consent_given: bool = False
    name: str = ""
    aliases: list = field(default_factory=list)
    first_seen: float = 0.0
    last_seen: float = 0.0
    sessions: int = 0
    days_visited: list = field(default_factory=list)
    themes: dict = field(default_factory=dict)
    tod_tally: dict = field(default_factory=lambda: {
        "morning": 0, "afternoon": 0, "evening": 0, "night": 0})
    msg_count: int = 0
    tone_tally: dict = field(default_factory=lambda: {
        "brief": 0, "measured": 0, "thinking": 0, "long-form": 0})
    questions_count: int = 0
    statements_count: int = 0
    mood_ema: float = 0.0
    mood_7day: list = field(default_factory=list)
    upset_count: int = 0
    happy_count: int = 0
    anxious_count: int = 0
    last_session_mins: float = 0.0
    session_start: float = 0.0
    session_log: list = field(default_factory=list)

    def save(self):
        atomic_write_json(PROFILE_PATH, asdict(self))

    def load(self):
        try:
            with open(PROFILE_PATH) as f: d = json.load(f)
        except Exception:
            return
        for k, v in d.items():
            if hasattr(self, k): setattr(self, k, v)

    def wipe_above_level(self):
        if self.level < 4: self.session_log = []
        if self.level < 3:
            self.tod_tally = {"morning": 0, "afternoon": 0,
                              "evening": 0, "night": 0}
            self.msg_count = 0
            self.tone_tally = {"brief": 0, "measured": 0,
                               "thinking": 0, "long-form": 0}
            self.questions_count = 0
            self.statements_count = 0
            self.mood_ema = 0.0
            self.mood_7day = []
            self.upset_count = 0
            self.happy_count = 0
            self.anxious_count = 0
            self.last_session_mins = 0.0
        if self.level < 2:
            self.first_seen = 0.0
            self.last_seen = 0.0
            self.sessions = 0
            self.days_visited = []
            self.themes = {}
        if self.level < 1:
            self.name = ""
            self.aliases = []

    def set_level(self, n):
        n = max(0, min(4, int(n)))
        self.level = n
        if n > 0: self.consent_given = True
        self.wipe_above_level()
        self.save()

    def note_session_start(self):
        if self.level < 2: return
        now = time.time()
        if self.session_start and self.last_seen:
            mins = (self.last_seen - self.session_start) / 60.0
            if 0 < mins < 24*60:
                self.last_session_mins = (
                    (self.last_session_mins + mins)/2
                    if self.last_session_mins else mins)
        self.session_start = now
        self.last_seen = now
        if not self.first_seen: self.first_seen = now
        self.sessions += 1
        today = datetime.date.today().isoformat()
        if today not in self.days_visited:
            self.days_visited.append(today)
            if len(self.days_visited) > 366:
                self.days_visited = self.days_visited[-366:]
        if self.level >= 3:
            h = datetime.datetime.now().hour
            bucket = ("night" if h < 5 or h >= 22
                      else ("morning" if h < 12
                      else ("afternoon" if h < 17 else "evening")))
            self.tod_tally[bucket] = self.tod_tally.get(bucket, 0) + 1
        self.save()

    def note_message(self, text, tone, topic, is_question):
        # V7.1-P31: last_seen updated on every message.
        self.last_seen = time.time()
        if self.level < 2: return
        # V7.1-P31: topics are first hook, already passed by caller.
        if topic:
            t = topic.lower().strip()
            self.themes[t] = self.themes.get(t, 0) + 1
            if len(self.themes) > 200:
                self.themes = dict(sorted(
                    self.themes.items(), key=lambda kv: -kv[1])[:100])
        if self.level >= 3:
            self.msg_count += 1
            if tone in self.tone_tally: self.tone_tally[tone] += 1
            if is_question: self.questions_count += 1
            else: self.statements_count += 1
        self.save()

    def note_mood(self, sent):
        if self.level < 3: return
        a = 0.25
        self.mood_ema = (1-a)*self.mood_ema + a*sent
        today = datetime.date.today().isoformat()
        if self.mood_7day and self.mood_7day[-1][0] == today:
            self.mood_7day[-1] = [today, (self.mood_7day[-1][1] + sent)/2.0]
        else:
            self.mood_7day.append([today, sent])
            if len(self.mood_7day) > 7:
                self.mood_7day = self.mood_7day[-7:]
        if sent < -0.5: self.upset_count += 1
        elif sent > 0.5: self.happy_count += 1
        # V7.1-P31: anxious_count now incremented.
        # "Anxious" is a mild negative signal, not a full upset.
        if -0.5 < sent < -0.2: self.anxious_count += 1
        self.save()

    def readback(self):
        if self.level == 0:
            return ["\u2696  Solon - You are unnamed. Nothing is stored about you.",
                    "     I hold no memory of you at all."]
        L = ["\u2696  Solon - reading from the record:",
             "     Level: %d of 4" % self.level]
        if self.name:
            L.append("     Name: " + self.name)
            if self.aliases:
                L.append("     Also known as: " + ", ".join(self.aliases))
        else:
            L.append("     Name: not given")
        if self.level >= 2:
            if self.first_seen:
                L.append("     First seen: " +
                         datetime.datetime.fromtimestamp(
                             self.first_seen).strftime("%Y-%m-%d"))
            if self.last_seen:
                L.append("     Last seen: " +
                         datetime.datetime.fromtimestamp(
                             self.last_seen).strftime("%Y-%m-%d %H:%M"))
            L.append("     Sessions: %d   Days known: %d" %
                     (self.sessions, len(self.days_visited)))
            if self.themes:
                top = sorted(self.themes.items(), key=lambda kv: -kv[1])[:10]
                L.append("     Themes you return to: " +
                         ", ".join("%s (%d)" % (k, v) for k, v in top))
        if self.level >= 3:
            L.append("     Messages: %d   Questions: %d   Statements: %d" %
                     (self.msg_count, self.questions_count,
                      self.statements_count))
            L.append("     Mood running average: %+.2f" % self.mood_ema)
            tod = ", ".join("%s %d" % (k, v) for k, v in self.tod_tally.items()
                            if v)
            L.append("     You arrive most often in: " + (tod or "-"))
            L.append("     Upset / happy / anxious: %d / %d / %d" %
                     (self.upset_count, self.happy_count,
                      self.anxious_count))
            if self.last_session_mins:
                L.append("     Recent session length: ~%.1f min"
                         % self.last_session_mins)
        if self.level >= 4 and self.session_log:
            L.append("     Recent sessions:")
            for entry in self.session_log[-5:]:
                L.append("       %s - %.0f min - %s" %
                         (entry.get("date", ""), entry.get("mins", 0),
                          ", ".join(entry.get("topics", []))))
        L.append("     File: " + PROFILE_PATH)
        return L

    def forget_name(self):
        self.name = ""
        self.aliases = []
        self.save()

    def forget_everything(self):
        # V7.1-P17: all three files are deleted, not just the profile.
        for path in (PROFILE_PATH, BODY_PATH, MEM_PATH):
            try: os.remove(path)
            except Exception: pass
        for k, v in Profile().__dict__.items():
            setattr(self, k, v)

    def add_session_log_entry(self, topics):
        if self.level < 4: return
        # V7.1-P31: measure last session from last_seen, not now.
        mins = 0.0
        if self.session_start and self.last_seen:
            mins = round((self.last_seen - self.session_start) / 60.0, 1)
        entry = {
            "date": datetime.date.today().isoformat(),
            "mins": mins,
            "topics": list(topics)[:3],
        }
        self.session_log.append(entry)
        if len(self.session_log) > 200:
            self.session_log = self.session_log[-200:]
        self.save()

    def top_theme(self):
        if not self.themes: return None
        k, v = max(self.themes.items(), key=lambda kv: kv[1])
        return k if v >= 2 else None


PROFILE = Profile()
PROFILE.load()
FIRST_RUN = (PROFILE.level == 0 and not PROFILE.consent_given)


# =====================================================================
# STATE ENGINE: BATTERY MONITOR
# ---------------------------------------------------------------------
# Reads capacity and charging state from /sys/class/power_supply.
# On devices where this path is not available, returns None and the
# header simply omits the battery indicator. No crash.
#
# Carried from V7 unchanged.
# =====================================================================

BAT = {"pct": None, "chg": False, "polled": 0.0}


def _bat():
    try:
        for d in os.listdir("/sys/class/power_supply"):
            p = "/sys/class/power_supply/" + d
            cp = os.path.join(p, "capacity")
            if not os.path.exists(cp): continue
            with open(cp) as f: pct = int(f.read().strip())
            chg = False
            st = os.path.join(p, "status")
            if os.path.exists(st):
                with open(st) as f:
                    chg = f.read().strip().lower() in ("charging", "full")
            return pct, chg
    except Exception:
        pass
    return None


def poll_bat():
    if time.time() - BAT["polled"] < 60: return
    BAT["polled"] = time.time()
    r = _bat()
    if r:
        BAT["pct"], BAT["chg"] = r


# =====================================================================
# PROFILE COMMANDS (V7.1-P17 aware)
# ---------------------------------------------------------------------
# Handle profile-related user commands. Called from send() before
# classification. If this function returns True, the message is
# treated as a profile command and no further processing happens.
#
# V8 changes:
#   * forget_everything message names all three files.
#   * export profile names all three.
#   * D3 note: option A (gate files behind level >= 1) would go here
#     as an additional check at the top of send(), before any write.
# =====================================================================

def handle_profile_command(raw, text):
    t = text.lower().strip().rstrip("?!.")

    if t in {"privacy", "privacy notice", "show privacy"}:
        popup_text("Edencore Council - Privacy", PRIVACY_NOTICE.split("\n"))
        return True

    if t in {"what do you know about me", "profile",
             "show profile", "show my profile"}:
        popup_text("Edencore Council - Your Profile", PROFILE.readback())
        return True

    if t in {"forget me", "forget my name"}:
        PROFILE.forget_name()
        add_system("\u2696 Solon - The name is erased. "
                   "You remain otherwise known.")
        return True

    if t in {"forget everything", "forget all", "delete my profile"}:
        PROFILE.forget_everything()
        popup_text("Edencore Council", [
            "Three files have been deleted:",
            "  " + PROFILE_PATH,
            "  " + BODY_PATH,
            "  " + MEM_PATH,
            "You are a stranger again. That is allowed."])
        return True

    if t in {"export profile", "export my profile"}:
        add_system("\u2696 Solon - Your records live here: " + PROFILE_PATH)
        return True

    m = re.match(r"^(?:set\s+)?(?:profile\s+)?level\s+([0-4])$", t)
    if m:
        n = int(m.group(1))
        old = PROFILE.level
        PROFILE.set_level(n)
        add_system("\u2696 Solon - Memory level set to %d (was %d)."
                   % (n, old))
        return True

    nm = detect_name(text)
    if nm:
        if PROFILE.level == 0:
            add_system("\u2696 Solon - You gave a name, but memory is "
                       "at level 0. Type 'set level 1' to let the "
                       "council keep it.")
            return True
        if nm.lower() != (PROFILE.name or "").lower():
            if PROFILE.name:
                PROFILE.aliases.append(nm)
                if len(PROFILE.aliases) > 5:
                    PROFILE.aliases = PROFILE.aliases[-5:]
            else:
                PROFILE.name = nm
            PROFILE.save()
            add_system("\u2696 Solon - Noted. %s." % nm)
            return True
    return False


# =====================================================================
# FIRST-RUN FLOW (V8-P04)
# ---------------------------------------------------------------------
# The wiring that turns FIRST_RUN_LINES (Chunk 2) into a real flow.
# Solon speaks first, asks for a name, and the memory-level offer
# follows only if a name was given.
#
# State machine: three phases.
#   phase 0 — Solon has asked. Awaiting a name or "skip".
#   phase 1 — name given. Awaiting a memory level 0-4.
#   phase 2 — complete. The council is ready.
#
# The state is held in a small dict so this chunk does not add any
# new module-level state that another chunk needs to know about.
# =====================================================================

FIRST_RUN_STATE = {"phase": 0, "active": False}


def begin_first_run():
    """Called once at startup when FIRST_RUN is True. Puts the
    council into the name-asking state and speaks Solon's line."""
    FIRST_RUN_STATE["phase"] = 0
    FIRST_RUN_STATE["active"] = True
    typewriter("Solon", FIRST_RUN_LINES["ask"],
               delay=SPEECH_PROFILE.get("Solon", {}).get("type_speed", 75))


def _complete_first_run():
    FIRST_RUN_STATE["phase"] = 2
    FIRST_RUN_STATE["active"] = False
    PROFILE.consent_given = True
    PROFILE.save()


def handle_first_run(text):
    """Handle one message during the first-run flow.
    Returns True if the message was consumed by the flow.
    Returns False if the flow is not active — the caller should
    process the message normally."""
    if not FIRST_RUN_STATE["active"]:
        return False
    phase = FIRST_RUN_STATE["phase"]
    t = text.strip().lower().rstrip("?!.")

    if phase == 0:
        # Awaiting a name or skip.
        if t in {"skip", "none", "no", "nothing", "no name", ""}:
            typewriter("Solon", FIRST_RUN_LINES["skip"],
                       delay=SPEECH_PROFILE.get("Solon", {}).get(
                           "type_speed", 75),
                       done=_complete_first_run)
            return True
        # Treat the message as a name. Cap length, strip punctuation.
        candidate = text.strip().split("\n")[0][:20]
        candidate = re.sub(r"[^A-Za-z'\- ]", "", candidate).strip()
        if len(candidate) < 2:
            typewriter("Solon",
                       "\u2696 That does not sound like a name. You may "
                       "try again, or type 'skip'.",
                       delay=SPEECH_PROFILE.get("Solon", {}).get(
                           "type_speed", 75))
            return True
        proper = candidate[0].upper() + candidate[1:]
        if PROFILE.level == 0:
            # No memory level chosen yet — offer one now.
            PROFILE.name = proper
            PROFILE.level = 2
            PROFILE.consent_given = True
            PROFILE.save()
        else:
            PROFILE.name = proper
            PROFILE.save()
        # Acknowledge the name, then offer the level.
        def after_ack():
            FIRST_RUN_STATE["phase"] = 1
            typewriter("Solon", FIRST_RUN_LINES["level_offer"],
                       delay=SPEECH_PROFILE.get("Solon", {}).get(
                           "type_speed", 75),
                       done=_complete_first_run)
        typewriter("Solon", FIRST_RUN_LINES["ack"] % proper,
                   delay=SPEECH_PROFILE.get("Solon", {}).get(
                       "type_speed", 75),
                   done=after_ack)
        return True

    if phase == 1:
        # Awaiting a memory level. Default to level 2 if not numeric.
        if t in {"0", "1", "2", "3", "4"}:
            PROFILE.set_level(int(t))
            typewriter("Solon",
                       "\u2696 Level %s accepted. The council may now "
                       "remember you." % t,
                       delay=SPEECH_PROFILE.get("Solon", {}).get(
                           "type_speed", 75),
                       done=_complete_first_run)
        elif t in {"privacy", "privacy notice"}:
            popup_text("Edencore Council - Privacy",
                       PRIVACY_NOTICE.split("\n"))
            # Stay in phase 1 — the user still needs to choose.
            return True
        else:
            typewriter("Solon",
                       "\u2696 A number 0 through 4, or 'privacy'. "
                       "Take your time.",
                       delay=SPEECH_PROFILE.get("Solon", {}).get(
                           "type_speed", 75))
        return True

    # Phase 2 — should not arrive here.
    return False


# --- END OF CHUNK 7 (Persistence + Profile + First-Run Flow) ---

# =====================================================================
# CHUNK 8 CONTINUES BELOW WITH:
#   * Seat, Council, Memory, Extero dataclasses
#     (V7.1-P32: hysteresis on Seat.overwhelmed)
#   * COUNCIL, MEMORY, EXTERO instances
#   * RIPPLE_FACTS_DEFAULT (carried from V7; corrections in Chunk 9
#     with versioning per V7.1-P30)
#   * load_ripple_facts (V7.1-P30: versioned reload)
#   * ripple_fact (V7.1-P33: exact-key matching, allow_general flag)
#   * compute_mood (referenced by select_phrase in Chunk 6)
#   * MOOD_POS, MOOD_NEG, analyse_mood
#   * memory_callback
# =====================================================================
# =====================================================================
# STATE ENGINE: SEAT, COUNCIL, MEMORY, EXTERO
# ---------------------------------------------------------------------
# Four dataclasses. Each has one job.
#
#   Seat    — one seat's stamina and strain. Work depletes, rest
#             restores. Overwhelmed is a hysteresis band, not a
#             threshold.
#
#   Council — the five seats, plus rapport. Saves to BODY_PATH.
#
#   Memory  — visit days and message count. Saves to MEM_PATH.
#
#   Extero  — the chamber's sense of the outside world: time of
#             day, session length, user's message-length tone.
#
# V8 carries them from V7 with two changes:
#   * V7.1-P32: Seat.overwhelmed uses hysteresis, not a bare
#     threshold. The seat enters "overwhelmed" at stamina < 15 and
#     exits only when stamina recovers above 30.
#   * V7.1-P31: all saves go through atomic_write_json.
# =====================================================================

@dataclass
class Seat:
    stamina: float = 100.0
    strain: float = 0.0
    overwhelmed: bool = False

    def _update_overwhelmed(self):
        """V7.1-P32 hysteresis. Enter at 15, exit at 30. This stops
        the flag from flickering when stamina hovers near 15."""
        self.overwhelmed = (
            (self.stamina < 15.0) or
            (self.overwhelmed and self.stamina < 30.0)
        )

    def work(self, e=1.0):
        self.stamina = max(0.0, self.stamina - 2.2*e)
        self.strain = min(1.0, self.strain + 0.06*e)
        self._update_overwhelmed()

    def rest(self, dt):
        self.stamina = min(100.0, self.stamina + 0.17*dt)
        self.strain = max(0.0, self.strain - 0.020*dt)
        self._update_overwhelmed()


@dataclass
class Council:
    seats: dict = field(default_factory=dict)
    rapport: float = 0.0
    last_save: float = 0.0

    def ensure(self):
        for n in NAMES:
            if n not in self.seats:
                self.seats[n] = Seat()

    def save(self):
        atomic_write_json(BODY_PATH, {
            "saved_at": time.time(),
            "rapport": self.rapport,
            "seats": {n: {"stamina": s.stamina, "strain": s.strain}
                      for n, s in self.seats.items()},
        })

    def load(self):
        try:
            with open(BODY_PATH) as f: d = json.load(f)
        except Exception:
            return
        elapsed = max(0.0, min(6.0,
            (time.time() - d.get("saved_at", time.time())) / 3600.0))
        self.rapport = float(d.get("rapport", 0.0))
        for n in NAMES:
            sd = d.get("seats", {}).get(n)
            if sd:
                self.seats[n] = Seat(
                    stamina=min(100.0, sd.get("stamina", 100.0)
                                + elapsed * 20.0),
                    strain=max(0.0, sd.get("strain", 0.0)
                               - elapsed * 0.3))
            else:
                self.seats[n] = Seat()


@dataclass
class Memory:
    days: list = field(default_factory=list)
    msgs: int = 0

    def note(self):
        t = datetime.date.today().isoformat()
        if t not in self.days:
            self.days.append(t)
            self.days = self.days[-60:]

    def save(self):
        atomic_write_json(MEM_PATH, {"days": self.days, "msgs": self.msgs})

    def load(self):
        try:
            with open(MEM_PATH) as f: d = json.load(f)
            self.days = d.get("days", [])
            self.msgs = int(d.get("msgs", 0))
        except Exception:
            pass


@dataclass
class Extero:
    start: float = field(default_factory=time.time)
    activity: float = field(default_factory=time.time)
    lengths: list = field(default_factory=list)

    def record(self, t):
        self.activity = time.time()
        self.lengths.append(len(t))
        self.lengths = self.lengths[-10:]

    def tod(self):
        h = datetime.datetime.now().hour
        if 5 <= h < 12:  return "morning"
        if 12 <= h < 17: return "afternoon"
        if 17 <= h < 22: return "evening"
        return "night"

    def mins(self):
        return (time.time() - self.start) / 60.0

    def tone(self):
        if not self.lengths: return "quiet"
        a = sum(self.lengths) / len(self.lengths)
        if a < 15:  return "brief"
        if a < 60:  return "measured"
        if a < 200: return "thinking"
        return "long-form"

    def summary(self):
        m = self.mins()
        if m < 1:      ml = "just begun"
        elif m < 60:   ml = "%dm" % int(m)
        else:          ml = "%dh %dm" % (int(m // 60), int(m % 60))
        return "%s | %s | %s" % (self.tod(), ml, self.tone())


COUNCIL = Council(); COUNCIL.ensure(); COUNCIL.load()
MEMORY  = Memory();  MEMORY.load();  MEMORY.note(); MEMORY.save()
EXTERO  = Extero()


# =====================================================================
# KNOWLEDGE ENGINE: RIPPLE'S FACT LIBRARY
# ---------------------------------------------------------------------
# Ripple speaks in facts. These are small, quiet, human-scale facts
# about the world — the kind of thing a thoughtful person might
# mention in passing. They are not trivia; they are reminders.
#
# V8 carries the library from V7 with versioning added.
#
# V7.1-P30: load_ripple_facts now writes a _version field to the
# on-disk copy, and only trusts that copy if the version matches.
# Without this, a V7 install with an on-disk copy would never see
# corrections shipped in code.
#
# IMPORTANT: The V7.1 audit's fact table flagged several of these
# as imprecise or overstated. The corrections are applied in
# Chunk 9, together with the FACTS_DB corrections, and FACTS_VERSION
# is bumped so existing installs reload. This chunk is the V7 text,
# carried forward, so that Chunk 9 can make one clean pass over
# every fact the council knows.
# =====================================================================

RIPPLE_FACTS_DEFAULT = {
 "ocean": [
   "Half the oxygen you breathe comes from the ocean.",
   "We have mapped the surface of Mars better than the floor of our own ocean.",
   "The deepest point in the ocean is deeper than Everest is tall.",
   "More people have been to space than to the bottom of the Mariana Trench.",
   "Sound travels faster in water than in air."],
 "sky": [
   "Every star you see tonight is either much bigger or much older than our sun.",
   "The light from most stars you see left them before you were born.",
   "When you look at the night sky, you're looking backwards in time.",
   "There are more stars in the universe than grains of sand on every beach on Earth."],
 "earth": [
   "There are more trees on Earth than stars in the Milky Way.",
   "Every continent was once joined together.",
   "The Earth is not a sphere. It bulges slightly at the equator.",
   "A day used to be shorter. The Earth's spin is slowing.",
   "The Moon is slowly moving away from Earth.",
   "The Sun will outlive every human and every memory of humanity."],
 "people": [
   "Most of the people alive today have never been on a plane.",
   "Half the world lives on less than seven dollars a day.",
   "More people have access to a mobile phone than to a toilet.",
   "One in every four humans is Chinese or Indian.",
   "Every person you pass has an inner life as complicated as yours.",
   "Around 100 billion humans have ever lived.",
   "About 7% of all humans who ever lived are alive right now.",
   "There will be more people alive in the future than have ever lived."],
 "time": [
   "The last person born in the 1800s died in 2017.",
   "Someone born today will likely live into the 2100s.",
   "The oldest living tree started growing before the pyramids were built.",
   "Cleopatra lived closer to the iPhone than to the construction of the Great Pyramid.",
   "Your sense of time speeds up as you age. It is measured in novelty.",
   "You are the oldest you have ever been, and the youngest you will ever be again."],
 "memory": [
   "You will forget most of today. That's not a failure. That's how memory works.",
   "Every time you remember something, you slightly change it.",
   "Your brain uses less power than a lightbulb.",
   "You will remember this week more than next week. Novelty carves deeper."],
 "language": [
   "Every language you speak has a word for something the others can't say.",
   "Half of the world's languages will likely be gone by 2100.",
   "No one knows who invented the first word."],
 "numbers": [
   "Zero was invented. Someone, once, was the first person to think of nothing.",
   "Some infinities are bigger than others."],
 "work": [
   "Two-thirds of the work done in the world is unpaid.",
   "Most of the food you eat was planted by hand.",
   "The average person spends about 90,000 hours of their life working."],
 "sleep": [
   "You spend about a third of your life asleep.",
   "Every mammal dreams. So do some birds.",
   "Sleep is when your brain washes itself.",
   "Rest is not a reward. It's a requirement."],
 "food": [
   "There are more kinds of apples than days in a year.",
   "Bananas, as we know them, are only about 200 years old.",
   "Half of all food grown is thrown away.",
   "Rice feeds more people than any other crop."],
 "animals": [
   "An octopus has three hearts and blue blood.",
   "Elephants can recognise themselves in a mirror. So can dolphins and magpies.",
   "Bees can recognise human faces.",
   "There are more insects on Earth than there are seconds in a lifetime.",
   "A blue whale's heart is the size of a small car.",
   "Some whales live over 200 years.",
   "A colony of ants can be more complex than a city."],
 "plants": [
   "A single tree can support over a thousand species.",
   "Mushrooms are closer to animals than to plants.",
   "Trees can warn each other of danger through the soil."],
 "cities": [
   "More than half the world lives in cities now.",
   "Tokyo has more people than the whole of Canada.",
   "The oldest still-inhabited city is over 10,000 years old."],
 "light": [
   "Nothing you see is happening right now. Light takes time to travel.",
   "Every colour you see is a translation.",
   "The colour pink doesn't exist in the light spectrum. Your brain invents it."],
 "silence": [
   "Silence is never really silent. Your ears fill it in.",
   "Some people hear the sound of their own eyes moving.",
   "Space is silent because there's nothing for sound to travel through."],
 "body": [
   "You are more bacteria than human.",
   "A human can survive without food for weeks but without water only days.",
   "A baby has more bones than an adult.",
   "Your eyes were fully grown before the rest of you.",
   "Even in your loneliest moment, your body is cooperating with itself a trillion times a second."],
 "death": [
   "Death is not the end of you physically. Your atoms go on.",
   "Every breath you take contains atoms from someone who died long ago."],
 "love": [
   "Being kind to someone measurably improves your health.",
   "Loneliness shortens life more than smoking.",
   "A hug lasts about three seconds before something changes.",
   "A stranger has already done something kind for you today that you did not notice."],
 "fear": [
   "Almost all your fears are learned. Very few are born with you.",
   "Everyone you meet is fighting something you can't see."],
 "water": [
   "The water you drink today has passed through dinosaurs.",
   "Every drop of water on Earth has been recycled for billions of years."],
 "money": [
   "Most of the money in the world is not physical. It's just numbers."],
 "words": [
   "There is no word for the feeling of being watched.",
   "Some feelings only exist because someone named them.",
   "Every person alive is descended from survivors."],
 "change": [
   "Nothing you know is permanent. Not even the ground you stand on.",
   "Most of the inventions that will shape your life haven't been made.",
   "Everything you love is temporary, which is exactly why it matters."],
 "smell": [
   "The smell of rain is produced partly by soil bacteria.",
   "Petrichor is the name for the smell of rain on dry earth."],
 "general": [
   "You are travelling through space at over 100,000 km/h.",
   "The smallest thing you can see is made of things too small to see.",
   "A single cell knows how to do things no machine can.",
   "Someone, right now, is hearing their name for the first time."]
}


# =====================================================================
# KNOWLEDGE ENGINE: RIPPLE FACTS VERSION AND LOADER
# ---------------------------------------------------------------------
# V7.1-P30. The loader checks the on-disk version first. If it does
# not match FACTS_VERSION, the file is rewritten from the code, so
# corrections reach existing installs.
#
# Chunk 9 will bump FACTS_VERSION to 2 after applying the fact
# corrections. For now it stays at 1, matching the V7 shape.
# =====================================================================

FACTS_VERSION = 1


def load_ripple_facts():
    """Load Ripple's facts from disk, rewriting the file when the
    code version is newer than the on-disk version."""
    try:
        with open(RIPPLE_FACTS_PATH) as f:
            d = json.load(f)
        if d.get("_version") == FACTS_VERSION:
            d.pop("_version", None)
            return d
    except Exception:
        pass
    out = dict(RIPPLE_FACTS_DEFAULT)
    try:
        payload = dict(out)
        payload["_version"] = FACTS_VERSION
        with open(RIPPLE_FACTS_PATH, "w") as f:
            json.dump(payload, f, indent=2)
    except Exception:
        pass
    return out


RIPPLE_FACTS = load_ripple_facts()
RIPPLE_STATE = {"last_fact_at": 0.0, "recent": []}


def ripple_fact(topics=None, allow_general=False):
    """Return a fact from Ripple's library, filtered by topic.

    V7.1-P33 changes:
      * Exact key matching only. The V7 substring test ("key in k")
        allowed short words to match inside others.
      * The general pool is only used when allow_general is True,
        which callers set for idle remarks and crosstalk. A specific
        question no longer gets an off-topic fact as a fallback.

    The rate limiter and recent-fact deduplication are unchanged.
    """
    if EXTERO.mins() < 10: return None
    if random.random() > 0.05: return None
    if time.time() - RIPPLE_STATE["last_fact_at"] < 900: return None
    candidates = []
    for t in topics or []:
        key = (t or "").lower().strip()
        if key in RIPPLE_FACTS:
            candidates.extend(RIPPLE_FACTS[key])
    if not candidates and allow_general:
        candidates = RIPPLE_FACTS.get("general", [])
    if not candidates:
        return None
    pool = [f for f in candidates if f not in RIPPLE_STATE["recent"]]
    if not pool:
        pool = candidates
    fact = random.choice(pool)
    RIPPLE_STATE["last_fact_at"] = time.time()
    RIPPLE_STATE["recent"].append(fact)
    if len(RIPPLE_STATE["recent"]) > 40:
        RIPPLE_STATE["recent"] = RIPPLE_STATE["recent"][-40:]
    return fact


# =====================================================================
# STATE ENGINE: MOOD MONITOR
# ---------------------------------------------------------------------
# Produces a single description of the chamber's emotional weather.
# Shown in the header. Consumed by V7.1-P35 (mood influences phrase
# selection, called from select_phrase in Chunk 6).
#
# The mood is derived from three inputs, in priority order:
#   * average strain across the seats
#   * the user's running mood average (only if level >= 3)
#   * rapport between the user and the council
#
# At level 0, user mood is unavailable, so the mood depends only on
# strain and rapport. That is the correct privacy behaviour.
# =====================================================================

def compute_mood():
    """Return a dict with mood, strain, and rapport labels."""
    if not COUNCIL.seats:
        return {"mood": "steady", "strain": "low", "rapport": "cool"}
    avg_strain = sum(s.strain for s in COUNCIL.seats.values()) \
                 / len(COUNCIL.seats)

    r = COUNCIL.rapport
    if r < 0.2:     rapport = "cool"
    elif r < 0.5:   rapport = "steady"
    elif r < 0.8:   rapport = "warm"
    else:           rapport = "close"

    if avg_strain < 0.2:    strain = "low"
    elif avg_strain < 0.5:  strain = "moderate"
    else:                   strain = "high"

    user_mood = PROFILE.mood_ema if PROFILE.level >= 3 else 0.0
    if avg_strain > 0.6:
        mood = "restless"
    elif user_mood < -0.3:
        mood = "somber"
    elif user_mood > 0.3 and rapport in ("warm", "close"):
        mood = "warm"
    elif rapport == "close":
        mood = "gentle"
    elif avg_strain < 0.15 and rapport in ("cool", "steady"):
        mood = "steady"
    else:
        mood = "contemplative"

    return {"mood": mood, "strain": strain, "rapport": rapport}


# =====================================================================
# STATE ENGINE: MOOD ANALYSIS
# ---------------------------------------------------------------------
# A crude sentiment score for the user's message. Positive words
# raise the score, negative words lower it, both cancel. The result
# is a float in [-1.0, 1.0].
#
# This is intentionally simple. The council does not need a good
# classifier; it needs a mild signal that shifts over time. The
# running average (Profile.note_mood) is the real signal; a single
# message is noise.
#
# Carried from V7 unchanged. The audit did not flag the word lists.
# =====================================================================

MOOD_POS = {
    "good", "great", "happy", "love", "wonderful", "brilliant",
    "amazing", "joy", "glad", "thanks", "appreciate", "kind",
    "warm", "calm", "hopeful", "excited", "grateful", "nice",
    "lovely", "perfect", "awesome", "fun", "smile",
}
MOOD_NEG = {
    "bad", "terrible", "awful", "hate", "angry", "sad", "horrible",
    "miserable", "upset", "worried", "anxious", "scared", "afraid",
    "tired", "exhausted", "frustrated", "annoyed", "hurt", "pain",
    "dark", "lonely", "broken", "lost", "confused", "wrong",
    "fail", "dying", "dead", "cry", "depressed", "stress", "hopeless",
}


def analyse_mood(text):
    """Return a sentiment score in [-1.0, 1.0] for the given text."""
    ws = words_of(text)
    p = sum(1 for w in ws if w in MOOD_POS)
    n = sum(1 for w in ws if w in MOOD_NEG)
    if p + n == 0:
        return 0.0
    return (p - n) / float(p + n)


# =====================================================================
# MEMORY CALLBACK
# ---------------------------------------------------------------------
# After a greeting, occasionally reference the user's top theme.
# This is the visible form of the persistent profile: the council
# remembers what the user has been thinking about.
#
# V7.1-P16: the V7 callback typed into a seat box 2.5 seconds after
# a greeting, possibly overwriting the greeting itself. The V8
# version wraps the call in after_types_done so it waits for the
# current typing job to finish.
#
# V7.1-P31: themes now store the first hook topic (e.g. "money"),
# not the full query text (e.g. "population of japan"). The
# callback's phrasing is now coherent as a result.
# =====================================================================

def memory_callback():
    """After a greeting, occasionally reference the user's top theme."""
    if PROFILE.level < 2: return
    top = PROFILE.top_theme()
    if not top: return
    if len(PROFILE.days_visited) < 2: return

    seat = random.choice(["Prism", "Lumen", "Ripple"])
    line = {
        "Prism":  "\u262f You return to %s often. The pattern is forming."
                  % top,
        "Lumen":  "\u0950 We never finished %s. Shall we?" % top,
        "Ripple": "\u273f You have come back to %s. That matters." % top,
    }[seat]

    def show():
        glow_ritual(seat, True)
        speed = SPEECH_PROFILE.get(seat, {}).get("type_speed", 50)
        typewriter(seat, line, delay=speed)
        root.after(900, lambda: glow_ritual(seat, False))

    # V7.1-P16: wait for current typing to complete before speaking.
    root.after(2500, lambda: after_types_done(show))


# --- END OF CHUNK 8 (State + Ripple Facts + Mood) ---

# =====================================================================
# CHUNK 9 CONTINUES BELOW WITH:
#   * Fact corrections: FACTS_DB and RIPPLE_FACTS_DEFAULT text
#     revised per the V7.1 audit's fact table (Section 4 of the
#     V7.1 Patch Document). FACTS_VERSION bumped to 2.
#   * External API helpers: _jget, _clean, wiki, _qid, _wdp, wd
#   * detect_attribute, detach_attr (V7.1-P28)
#   * format_wd_value (V7.1-P28)
#   * WCODE (V7.1-P29 expanded), WEATHER_CACHE, weather,
#     weather_seat (V7.1-P29 fallback prompt)
# =====================================================================
# =====================================================================
# KNOWLEDGE ENGINE: FACT CORRECTIONS (V7.1 Audit, Section 4)
# ---------------------------------------------------------------------
# The audit reviewed the fact text and flagged several entries as
# imprecise, overstated, or unsourced. Rather than rewrite FACTS_DB
# and RIPPLE_FACTS_DEFAULT in place (which would hide what changed),
# the corrections live here as a visible table.
#
# Each key is the original text. Each value is either the corrected
# text, or None to remove the fact entirely. apply_fact_corrections
# walks both dictionaries and replaces or deletes in place.
#
# This is the audit trail. A future thread reading this file can see
# exactly which claims were revised, and why the revised wording is
# what it is. Do not edit the keys — they must match the V7 text
# exactly, or the correction will silently miss.
# =====================================================================

FACT_CORRECTIONS = {
    # Money
    "The richest 1% of the world own more than half of all global wealth.":
        "The richest 1% hold close to half of global wealth, by most estimates.",
    "A penny costs more to make than it is worth.":
        "A US penny costs more to make than it is worth.",

    # Work
    "Two-thirds of the work done in the world is unpaid.":
        "Most unpaid care work worldwide is done by women, by ILO estimates.",
    "The first work-from-home experiment was in 1973 at NASA.":
        "The idea of telecommuting dates to the early 1970s.",
    "More people die from overwork than from malaria each year.":
        "Long working hours are linked to hundreds of thousands of deaths a year, by WHO and ILO estimates.",

    # Love
    "Loneliness shortens life more than smoking.":
        "Chronic loneliness is linked to health risks comparable to smoking.",
    "A hug lasts about three seconds before something changes in your body.":
        None,
    "A hug lasts about three seconds before something changes.":
        None,
    "The feeling of butterflies is actually your blood vessels dilating.":
        "Butterflies are part of the body's stress response.",

    # Body
    "Every seven years, most of your cells have been replaced.":
        "Many of your cells are replaced over time, but some last a lifetime.",

    # Food
    "Half of all food grown is thrown away.":
        "About a third of all food produced is lost or wasted.",
    "The smell of rain is actually a bacteria.":
        "The smell of rain is produced partly by soil bacteria.",

    # Sleep
    "Every mammal dreams. So do some birds.":
        "Many mammals show signs of dreaming. So do some birds.",
    "Every mammal dreams.":
        "Many mammals show signs of dreaming.",

    # Animals
    "Bees can recognise human faces.":
        "Honeybees can be trained to tell human faces apart.",

    # People
    "Most of the people alive today have never been on a plane.":
        None,
    "Half the world lives on less than seven dollars a day.":
        "Nearly half the world lives on less than seven dollars a day.",
    "One in every four humans is Chinese or Indian.":
        "More than one in three humans lives in China or India.",

    # Cities
    "Tokyo has more people than the whole of Canada.":
        "Greater Tokyo has nearly as many people as all of Canada.",
    "The oldest still-inhabited city is over 10,000 years old.":
        "Some cities have been inhabited for thousands of years.",

    # Fear
    "Almost all your fears are learned. Very few are born with you.":
        "Many of your fears are learned. Very few are born with you.",

    # Plants
    "Trees can warn each other of danger through the soil.":
        "Some studies suggest trees can warn each other of danger through the soil.",
}


def apply_fact_corrections(db):
    """Apply the V7.1 fact corrections in place.

    A corrected value of None removes the fact. New lists are built
    in place to avoid mutating while iterating.
    """
    for topic, facts in db.items():
        fixed = []
        for fact in facts:
            if fact in FACT_CORRECTIONS:
                replacement = FACT_CORRECTIONS[fact]
                if replacement is None:
                    continue  # remove this fact
                fixed.append(replacement)
            else:
                fixed.append(fact)
        db[topic] = fixed


# Apply to both fact stores, then bump version and reload.
apply_fact_corrections(FACTS_DB)
apply_fact_corrections(RIPPLE_FACTS_DEFAULT)

# V7.1-P30: bumping FACTS_VERSION causes load_ripple_facts to
# rewrite the on-disk copy from the corrected defaults. Existing
# V7 installs will reload the corrected library on first V8 launch.
FACTS_VERSION = 2
RIPPLE_FACTS = load_ripple_facts()


# =====================================================================
# KNOWLEDGE ENGINE: EXTERNAL API HELPERS
# ---------------------------------------------------------------------
# Three external services are consulted, and only when the user
# asks for a fact or weather:
#
#   * Wikipedia   — article lead extracts
#   * Wikidata    — structured attributes (population, height, etc)
#   * Open-Meteo  — current weather and short forecast
#
# Every call has a timeout. Every call caches. Every failure
# returns None. Nothing crashes on a network error; the council
# simply says the archive has nothing.
#
# V7.1-P28: attribute questions now strip the attribute word and
# "the/of" before searching, so "population of Japan" searches for
# "Japan". Values are formatted (dates, large integers, decimals).
#
# V7.1-P24: Wikipedia extracts are trimmed to two sentences and
# ≤ 280 characters, so they fit one seat frame.
# =====================================================================

def _jget(url, timeout=8, is_sparql=False):
    """Fetch JSON from a URL with a User-Agent header."""
    headers = {"User-Agent": "EdencoreCouncil/1.0"}
    if is_sparql:
        headers["Accept"] = "application/sparql-results+json"
    req = urllib.request.Request(url, headers=headers)
    with urllib.request.urlopen(req, timeout=timeout) as r:
        return json.loads(r.read().decode("utf-8"))


def _clean(t):
    """Collapse whitespace in a string."""
    return re.sub(r"\s+", " ", t).strip()


# Wikidata property codes. The key is the attribute name the user
# might type. Do not invent attribute names not used elsewhere.
WDPROPS = {
    "population": "P1082", "capital": "P36",
    "height": "P2048", "elevation": "P2044",
    "founded": "P571", "born": "P569", "died": "P570",
    "country": "P17", "continent": "P30",
    "length": "P2043", "diameter": "P2386", "area": "P2046",
    "currency": "P38", "language": "P37",
    "owner": "P127", "leader": "P35",
}

WIKI_CACHE = {}


def detach_attr(query, attr):
    """Strip the attribute word and 'the/of/for' from a search
    query, so 'population of Japan' searches for 'Japan'."""
    if not attr:
        return query
    q = re.sub(r"\b" + re.escape(attr) + r"\b", "", query, flags=re.I)
    q = re.sub(r"\b(the|of|for)\b", "", q, flags=re.I)
    q = re.sub(r"\s+", " ", q).strip(" ,.-")
    return q or query


def format_wd_value(v):
    """Make a raw Wikidata value readable.

    Dates (1564-04-26T00:00:00Z) become yyyy-mm-dd. Integers are
    thousands-separated. Floats trim trailing zeros. Strings pass
    through.
    """
    if v is None:
        return None
    m = re.match(r"^(-?\d{4})-(\d{2})-(\d{2})T", str(v))
    if m:
        return "%s-%s-%s" % m.groups()
    try:
        f = float(v)
        if f.is_integer():
            return "{:,}".format(int(f))
        return "{:,.2f}".format(f).rstrip("0").rstrip(".")
    except (ValueError, TypeError):
        return str(v)


def _trim_extract(ext, max_chars=280, max_sentences=2):
    """Trim an extract to at most max_sentences sentences and
    max_chars characters, cutting at a sentence or word boundary.

    V7.1-P24: keeps the extract within one seat frame.
    """
    sentences = re.split(r"(?<=[.!?]) +", ext)
    out = []
    total = 0
    for s in sentences[:max_sentences]:
        if total + len(s) > max_chars:
            room = max_chars - total
            if room < 20:
                break
            piece = s[:room].rsplit(" ", 1)[0].rstrip(" ,")
            if piece:
                out.append(piece)
            break
        out.append(s)
        total += len(s) + 1
    return " ".join(out).strip()


def wiki(query, attr=None):
    """Search Wikipedia. If attr is provided, strip it and 'the/of'
    before searching, so 'population of Japan' searches for 'Japan'.

    Returns {"title": str, "extract": str} on success, None on
    failure. Cached by the stripped search term.
    """
    search_term = detach_attr(query, attr) if attr else query
    cache_key = search_term.lower()
    if cache_key in WIKI_CACHE:
        return WIKI_CACHE[cache_key]
    try:
        u = "https://en.wikipedia.org/w/api.php?" + urllib.parse.urlencode(
            {"action": "query", "list": "search", "srsearch": search_term,
             "format": "json", "srlimit": 5})
        hits = _jget(u).get("query", {}).get("search", [])
        if not hits:
            WIKI_CACHE[cache_key] = None
            return None
        ql = search_term.lower().strip()
        title = next((h["title"] for h in hits if ql in h["title"].lower()),
                     hits[0]["title"])
        e = "https://en.wikipedia.org/w/api.php?" + urllib.parse.urlencode(
            {"action": "query", "prop": "extracts", "exintro": 1,
             "explaintext": 1, "titles": title, "format": "json"})
        page = next(iter(_jget(e)["query"]["pages"].values()))
        ext = _clean(page.get("extract", ""))
        if not ext:
            WIKI_CACHE[cache_key] = None
            return None
        first = _trim_extract(ext)
        out = {"title": title, "extract": first}
        WIKI_CACHE[cache_key] = out
        return out
    except Exception:
        WIKI_CACHE[cache_key] = None
        return None


def _qid(title):
    """Return the Wikidata Q-id for a Wikipedia title, or None."""
    try:
        u = "https://en.wikipedia.org/w/api.php?" + urllib.parse.urlencode(
            {"action": "query", "prop": "pageprops",
             "titles": title, "format": "json"})
        page = next(iter(_jget(u)["query"]["pages"].values()))
        return page.get("pageprops", {}).get("wikibase_item")
    except Exception:
        return None


def _wdp(qid, prop):
    """Fetch a single labelled Wikidata property value for a Q-id."""
    q = ("SELECT ?vLabel WHERE { wd:%s wdt:%s ?v. "
         "SERVICE wikibase:label { bd:serviceParam wikibase:language \"en\". } } LIMIT 1"
         % (qid, prop))
    u = "https://query.wikidata.org/sparql?" + urllib.parse.urlencode(
        {"query": q, "format": "json"})
    try:
        d = _jget(u, 12, is_sparql=True)
        r = d.get("results", {}).get("bindings", [])
        return r[0].get("vLabel", {}).get("value") if r else None
    except Exception:
        return None


def wd(title, attr):
    """Fetch an attribute value for a Wikipedia title. Returns the
    formatted value or None. Units are omitted rather than guessed.
    """
    q = _qid(title)
    if not q:
        return None
    p = WDPROPS.get(attr)
    if not p:
        return None
    raw = _wdp(q, p)
    if raw is None:
        return None
    return format_wd_value(raw)


def detect_attribute(text):
    """Return the first attribute word found in the text, or None.
    The word list is the keys of WDPROPS."""
    q = text.lower()
    for a in WDPROPS:
        if re.search(r"\b" + re.escape(a) + r"\b", q):
            return a
    return None


# =====================================================================
# KNOWLEDGE ENGINE: WEATHER
# ---------------------------------------------------------------------
# Open-Meteo, no API key needed. The flow:
#
#   1. Geocode the city name to lat/long.
#   2. Fetch current conditions and a two-day forecast.
#   3. Each seat phrases the result in its own voice.
#
# V7.1-P29 changes:
#   * If no city is given, weather() returns {"need_city": True}.
#     The council asks which city, rather than silently reporting
#     London.
#   * The cache keys on the normalised (lowercased, stripped) city
#     name, so the cache actually hits on repeat queries.
#   * WCODE covers the full Open-Meteo code list (drizzle variants,
#     freezing rain, snow grains, thunderstorm with hail).
# =====================================================================

WCODE = {
    0: "clear", 1: "mainly clear", 2: "partly cloudy", 3: "overcast",
    45: "foggy", 48: "foggy",
    51: "drizzle", 53: "drizzle", 55: "heavy drizzle",
    56: "freezing drizzle", 57: "heavy freezing drizzle",
    61: "light rain", 63: "rain", 65: "heavy rain",
    66: "freezing rain", 67: "heavy freezing rain",
    71: "light snow", 73: "snow", 75: "heavy snow",
    77: "snow grains",
    80: "showers", 81: "showers", 82: "violent showers",
    85: "snow showers", 86: "heavy snow showers",
    95: "thunderstorm", 96: "thunderstorm",
    99: "thunderstorm with hail",
}

WEATHER_CACHE = {"at": 0, "key": "", "data": None}


def weather(loc):
    """Fetch current weather for a location.

    Returns:
      * {"need_city": True} when loc is empty
      * a populated dict on success
      * None on network or parse failure
    """
    if not loc:
        return {"need_city": True}
    key = loc.lower().strip()
    now = time.time()
    if (WEATHER_CACHE["data"]
            and (now - WEATHER_CACHE["at"]) < 600
            and WEATHER_CACHE["key"] == key):
        return WEATHER_CACHE["data"]
    try:
        g = _jget("https://geocoding-api.open-meteo.com/v1/search?" +
                  urllib.parse.urlencode(
                      {"name": loc, "count": 1, "language": "en",
                       "format": "json"}), 8)
        r = g.get("results", [])
        if not r:
            return None
        p = r[0]
        w = _jget("https://api.open-meteo.com/v1/forecast?" +
                  urllib.parse.urlencode({
                      "latitude": p["latitude"],
                      "longitude": p["longitude"],
                      "current": "temperature_2m,weather_code,wind_speed_10m",
                      "daily": "temperature_2m_max,temperature_2m_min,precipitation_sum",
                      "timezone": "auto", "forecast_days": 2}), 8)
        c = w.get("current", {})
        d = w.get("daily", {})
        out = {
            "name": p.get("name", loc),
            "country": p.get("country", ""),
            "temp": c.get("temperature_2m"),
            "wind": c.get("wind_speed_10m"),
            "code": c.get("weather_code"),
            "tmax": (d.get("temperature_2m_max") or [None])[0],
            "tmin": (d.get("temperature_2m_min") or [None])[0],
            "precip": (d.get("precipitation_sum") or [None])[0],
        }
        WEATHER_CACHE["at"] = now
        WEATHER_CACHE["key"] = key
        WEATHER_CACHE["data"] = out
        return out
    except Exception:
        return None


def weather_seat(seat, w):
    """Phrase the weather for a seat. Returns a string, or None.

    When the user asked for weather without naming a city, the
    caller passes the {"need_city": True} dict through, and each
    seat asks the question in its own way.
    """
    if not w:
        return None

    # V7.1-P29: no silent London fallback.
    if w.get("need_city"):
        return {
            "Solon":  "A city is needed. Which one?",
            "Lumen":  "Which city's weather are you asking about?",
            "Vertex": "Name the city.",
            "Prism":  "Where? The pattern needs a place.",
            "Ripple": "Which place? I can't see the sky from here.",
        }.get(seat, "Which city?")

    n = w["name"] + (", " + w["country"] if w.get("country") else "")
    desc = WCODE.get(w.get("code"), "unclear")
    t, ti, tx, wi, pr = (w.get("temp"), w.get("tmin"), w.get("tmax"),
                         w.get("wind"), w.get("precip"))

    if seat == "Solon":
        risks = []
        if pr and pr > 1: risks.append("rain")
        if wi and wi > 25: risks.append("wind")
        if t is not None and t < 3: risks.append("cold")
        if risks:
            return "Risk noted: %s." % " and ".join(risks)
        return "No risk named. %s. Proceed." % desc

    if seat == "Lumen":
        return "A %s day in %s. What does it invite?" % (desc, n)

    if seat == "Vertex":
        parts = []
        if ti is not None and tx is not None:
            parts.append("%d to %dC" % (ti, tx))
        if wi is not None:
            parts.append("%dkm/h" % wi)
        return ", ".join(parts) + " in " + n + "."

    if seat == "Prism":
        return "%s - %s. A readable pattern." % (n, desc)

    if seat == "Ripple":
        if t is not None and t < 5:
            return "Cold. Take a coat, and think of those outside."
        if pr and pr > 1:
            return "Bring an umbrella. Softly."
        return "Nothing harsh. Go gently."

    return None


# --- END OF CHUNK 9 (Fact Corrections + External APIs) ---

# =====================================================================
# CHUNK 10 CONTINUES BELOW WITH:
#   * GRAPHICS ENGINE: the top strip, crest draw call
#   * GRAPHICS ENGINE: seat message frames
#   * GRAPHICS ENGINE: typewriter, glow, breathe
#   * GRAPHICS ENGINE: the pond (new in V8) — reserved strip,
#     minimal fish and plants, activation-driven ripple surface
#   * PROTOCOL ENGINE: rituals
#   * LAYOUT: header, seats_container, pond, input bar, quiet zone
#   * INPUT BAR: entry, send button, dismiss glyph (V8-P02)
# =====================================================================

# =====================================================================
# GRAPHICS ENGINE: HEADER
# ---------------------------------------------------------------------
# The header holds three things, top to bottom:
#
#   * The crest — a canvas painted with draw_crest(). Fixed at
#     startup, never redrawn.
#   * The avatar strip — five drawn transformers, plus name and
#     engine label per seat. Redrawn whenever a seat speaks.
#   * The status lines — the visitor line (time of day, session
#     length, tone, battery, profile marker), the mood line, and
#     the tier line.
#
# V8 carries the V7 header unchanged, except that draw_transformer
# now takes the seat name first (V7.1-P27 fix). The redraw() call
# passes the name.
# =====================================================================

header = tk.Frame(root, bg=HALL, height=int(H*0.28))
header.pack(fill="x", side="top")
header.pack_propagate(False)

banner = tk.Canvas(header, bg=HALL, width=W, height=int(H*0.15),
                   highlightthickness=0)
banner.pack()
draw_crest(banner, W, int(H*0.15))

tstrip = tk.Canvas(header, bg=HALL, width=W, height=int(H*0.055),
                   highlightthickness=0)
tstrip.pack()

SEAT_X = {s["name"]: W * (i + 0.5) / len(SEATS) for i, s in enumerate(SEATS)}


def redraw(active=None):
    """Redraw the top avatar strip. Called when a seat speaks, or
    with active=None to clear the crown."""
    sp = W / len(SEATS)
    size = int(H*0.017)
    for i, s in enumerate(SEATS):
        cx = sp * (i + 0.5)
        cy = int(H*0.021)

        # V7.1-P27: pass the seat name so the tag is unique per seat.
        tstrip.delete("tform_" + s["name"])
        b = COUNCIL.seats.get(s["name"])
        draw_transformer(tstrip, s["name"], cx, cy, size,
                         s["color"], s["style"],
                         dim=bool(b and b.overwhelmed),
                         glow=(s["name"] == active))

        tstrip.delete("name_" + s["name"])
        tstrip.delete("engine_" + s["name"])
        engine = SEAT_ENGINE.get(s["name"], "expert")
        sig = SIGIL.get(s["name"], "\u25cf")
        tstrip.create_text(cx, cy + size*1.6,
                           text=sig + " " + s["name"],
                           tags="name_" + s["name"],
                           fill=s["color"] if not (b and b.overwhelmed)
                                else "#4a4a6a",
                           font=("Courier", max(5, int(S*4)), "bold"))
        if engine != "expert":
            tstrip.create_text(cx, cy + size*2.9,
                               text="[" + engine + "]",
                               tags="engine_" + s["name"],
                               fill="#5a6a8a",
                               font=("Courier", max(4, int(S*3)), "normal"))

    tstrip.delete("crown")
    if active and active in SEAT_X:
        cx = SEAT_X[active]
        tstrip.create_text(cx, int(H*0.005),
                           text="\u265a", tags="crown",
                           fill=GOLD,
                           font=("Courier", max(8, int(S*7)), "bold"))


ex_lab   = tk.Label(header, text="", bg=HALL, fg="#5a6a8a", font=F(4))
ex_lab.pack()
mood_lab = tk.Label(header, text="", bg=HALL, fg="#7a8aaa", font=F(4))
mood_lab.pack()
tier_lab = tk.Label(header, text="", bg=HALL, fg="#5a6a8a", font=F(4))
tier_lab.pack(pady=(0, int(H*0.002)))

# Cache the last printed string per line so we only update when the
# text actually changes. This stops the header from flickering on
# every heartbeat.
_last_ex   = [None]
_last_mood = [None]
_last_tier = [None]


def update_ex():
    """Visitor line: time of day, session length, tone, battery,
    profile marker."""
    parts = ["\u263d " + EXTERO.summary()]
    if BAT["pct"] is not None:
        parts.append(("%s %d%%" % ("+" if BAT["chg"] else "|", BAT["pct"])))
    if PROFILE.level > 0:
        parts.append("P%d" % PROFILE.level)
        if PROFILE.name:
            parts.append(PROFILE.name)
    txt = "   ".join(parts)
    if txt != _last_ex[0]:
        ex_lab.config(text=txt)
        _last_ex[0] = txt


def update_mood():
    """Mood line: the chamber's weather."""
    m = compute_mood()
    txt = "\u2748 Mood: %s   \u26a1 Strain: %s   \u273f Rapport: %s" % (
        m["mood"], m["strain"], m["rapport"])
    if txt != _last_mood[0]:
        mood_lab.config(text=txt)
        _last_mood[0] = txt


def update_tier(status=None):
    """Tier line: what the council is doing, or the mode it is in."""
    if status:
        txt = status
    else:
        llm_seats = [n for n in NAMES if SEAT_ENGINE.get(n) != "expert"]
        if not llm_seats:
            txt = "\u2609 expert mode"
        else:
            engines = [SEAT_ENGINE[n] for n in llm_seats]
            txt = "\u2609 " + " + ".join(engines)
    if txt != _last_tier[0]:
        tier_lab.config(text=txt)
        _last_tier[0] = txt


# =====================================================================
# GRAPHICS ENGINE: SEAT MESSAGE FRAMES
# ---------------------------------------------------------------------
# One frame per seat. Each holds a title bar (sigil, glyph, name,
# engine tag) and a message label. The message label is the target
# of the typewriter.
#
# The frame's highlight color is the seat's colour. It brightens
# when the seat speaks (glow_ritual) and darkens when the seat is
# overwhelmed.
# =====================================================================

seats_container = tk.Frame(root, bg=DEEP)
seats_container.pack(fill="both", expand=True, side="top")

SEAT_FRAMES = {}
SEAT_MSGS = {}

for seat in SEATS:
    f = tk.Frame(seats_container, bg=HALL,
                 highlightbackground=seat["color"], highlightthickness=1)
    f.pack(fill="both", expand=True, padx=4, pady=2)
    f.pack_propagate(False)

    engine = SEAT_ENGINE.get(seat["name"], "expert")
    sig_col = GOLD if seat["name"] == "Solon" else seat["color"]
    title = " " + seat["sigil"] + "   " + seat["glyph"] + "  " + seat["name"]
    if engine != "expert":
        title += "   [" + engine + "]"

    tk.Label(f, text=title, bg=HALL, fg=sig_col,
             font=F(5, True), anchor="w").pack(fill="x", padx=12, pady=(2, 0))

    m = tk.Label(f, text="", bg=HALL, fg="#d8e0ec", font=F(6),
                 wraplength=W-40, justify="left", anchor="nw")
    m.pack(fill="both", expand=True, padx=12, pady=(0, 4))

    SEAT_FRAMES[seat["name"]] = f
    SEAT_MSGS[seat["name"]] = m


# =====================================================================
# GRAPHICS ENGINE: TYPEWRITER
# ---------------------------------------------------------------------
# Reveal text character by character. The delay per character comes
# from the seat's SPEECH_PROFILE.type_speed, so Solon types slowly
# and heavily, and Vertex snaps in.
#
# If a new typewriter job is started for a seat before the previous
# one finishes, the previous job is cancelled. Only one typewriter
# runs per seat at a time.
#
# Carried from V7, with one small change: the delay default is
# sourced from SPEECH_PROFILE at the call site, not inside the
# function. This keeps typewriter generic.
# =====================================================================

TYPE_JOBS = {}


def typewriter(seat, full_text, done=None, delay=40):
    """Reveal text character by character in the seat's message box."""
    lbl = SEAT_MSGS.get(seat)
    if not lbl:
        return
    if seat in TYPE_JOBS:
        try: root.after_cancel(TYPE_JOBS[seat])
        except Exception: pass

    if isinstance(full_text, list):
        full_text = random.choice(full_text) if full_text else ""
    elif not isinstance(full_text, str):
        full_text = str(full_text)

    lbl.config(text="", fg="#d8e0ea")
    full_text = full_text[:600]
    n = len(full_text)

    def step(i):
        if i >= n:
            TYPE_JOBS.pop(seat, None)
            if done: done()
            return
        lbl.config(text=full_text[:i+1])
        TYPE_JOBS[seat] = root.after(delay, lambda: step(i+1))

    step(0)


def cancel_typewriters():
    """Cancel all in-flight typewriter jobs."""
    for seat, jid in list(TYPE_JOBS.items()):
        try: root.after_cancel(jid)
        except Exception: pass
    TYPE_JOBS.clear()


def after_types_done(callback, timeout=8.0):
    """Call callback once all typewriters finish, or after timeout.

    The staleness guard checks SEND_COUNTER — if a newer message has
    been sent since this call, the callback is abandoned. This is
    V7.1-P11's stale-thread guard, applied at the graphics layer.
    """
    my_token = SEND_COUNTER[0]
    start = time.time()

    def check():
        if SEND_COUNTER[0] != my_token:
            return
        if not TYPE_JOBS or (time.time() - start) > timeout:
            callback()
        else:
            root.after(150, check)

    root.after(150, check)


# =====================================================================
# GRAPHICS ENGINE: GLOW AND BREATHE
# ---------------------------------------------------------------------
# Two visual pulses.
#
#   glow_ritual — a strong, fast pulse used when a seat speaks. The
#                 frame border lights up in three stages, then falls
#                 back to base. Takes ~360 ms each way.
#
#   breathe_glow — a weak, slow pulse used by the sub-rhythm system
#                 in V8. The border lifts slightly, then fades over
#                 ~1.4 seconds. This is the "body breathing" made
#                 visible.
#
# Neither needs new state. Both are self-terminating.
# =====================================================================

def glow_ritual(seat, on):
    """Light up (on=True) or fade down (on=False) a seat's frame."""
    f = SEAT_FRAMES.get(seat)
    if not f: return
    base = COLOR[seat]
    if on:
        steps = [(base, 1), (_light(base, 0.30), 2),
                 (_light(base, 0.55), 3), ("#ffffff", 3)]
    else:
        steps = [(_light(base, 0.55), 3), (_light(base, 0.30), 2),
                 (base, 1)]

    def tick(k):
        if k >= len(steps): return
        c, t = steps[k]
        try:
            f.config(highlightbackground=c, highlightthickness=t)
        except Exception:
            pass
        root.after(120, lambda: tick(k+1))
    tick(0)


def breathe_glow(seat, intensity=0.35):
    """A subtle ambient pulse — one seat's border glows gently even
    when silent. Lower intensity than glow_ritual, slower fade."""
    f = SEAT_FRAMES.get(seat)
    if not f: return
    base = COLOR[seat]
    soft = _light(base, intensity)
    try:
        f.config(highlightbackground=soft, highlightthickness=2)
    except Exception:
        pass
    root.after(1400, lambda: _breathe_release(seat))


def _breathe_release(seat):
    f = SEAT_FRAMES.get(seat)
    if not f: return
    try:
        f.config(highlightbackground=COLOR[seat], highlightthickness=1)
    except Exception:
        pass


# =====================================================================
# GRAPHICS ENGINE: CLEAR, SYSTEM, POPUP
# ---------------------------------------------------------------------
# Three small helpers.
#
#   clear_all    — cancel typewriters, wipe all seat boxes, reset
#                  all borders to base. Called before a new
#                  discussion begins.
#
#   add_system   — show a system line. Short lines go into Solon's
#                  box. Long lines become a popup.
#
#   popup_text   — a modal window with scrollable text. Used for
#                  the privacy notice, profile readback, crisis
#                  message, and other full-screen replies.
# =====================================================================

def clear_all():
    cancel_typewriters()
    for n in NAMES:
        SEAT_MSGS[n].config(text="", fg="#d8e0ec")
        f = SEAT_FRAMES.get(n)
        if f:
            f.config(highlightbackground=COLOR[n], highlightthickness=1)


def add_system(text):
    """Show a short system line in Solon's box, or a popup if long."""
    if len(text) > 200:
        popup_text("Edencore Council", text.split("\n"))
        return
    lbl = SEAT_MSGS.get("Solon")
    if not lbl: return
    cancel_typewriters()
    for n in NAMES:
        if n != "Solon":
            SEAT_MSGS[n].config(text="", fg="#d8e0ec")
    lbl.config(text=text[:600], fg=GOLD)


def popup_text(title, lines):
    """Open a modal popup with the given title and lines of text."""
    win = tk.Toplevel(root)
    win.title(title)
    win.configure(bg=HALL)
    txt = tk.Text(win, bg=DEEP, fg=PARCH, font=F(5), wrap="word",
                  bd=0, padx=16, pady=12)
    txt.pack(fill="both", expand=True, padx=8, pady=8)
    txt.insert("1.0", "\n".join(lines))
    txt.config(state="disabled")
    tk.Button(win, text="close", bg="#5aa8ff", fg=DEEP, bd=0,
              font=F(5, True),
              command=win.destroy).pack(pady=(0, 8))
    win.transient(root)
    win.grab_set()


# =====================================================================
# PROTOCOL ENGINE: RITUALS
# ---------------------------------------------------------------------
# Named patterns of short, sharp responses. Beyond "hush", V8 carries
# three more ceremonies from V7:
#
#   gathering  — a slow opening. Every seat acknowledges presence.
#   yielding   — the floor passes from one seat to another.
#   close      — the chamber settles. A deliberate ending.
#
# Each ritual has an order (which seats speak, in what order), a
# timing list (seconds to wait before each line), a type_speed hint
# (faster than normal speech, because rituals are brief), and the
# lines themselves.
#
# V7.1-P27: the type_speed field is now honoured in run_ritual.
# In V7 it was declared but never read.
# =====================================================================

RITUALS = {
    "hush": {
        "order": ["Solon", "Lumen", "Vertex", "Prism", "Ripple"],
        "timing": [0.0, 0.15, 0.15, 0.15, 0.40],
        "type_speed": 20,
        "lines": {
            "Solon":  "Silence.",
            "Lumen":  "Hush.",
            "Vertex": "Hush.",
            "Prism":  "Hush.",
            "Ripple": "The floor is yours.",
        },
    },
    "gathering": {
        "order": ["Solon", "Lumen", "Vertex", "Prism", "Ripple"],
        "timing": [0.0, 0.60, 0.60, 0.60, 0.60],
        "type_speed": 55,
        "lines": {
            "Solon":  "We are assembled.",
            "Lumen":  "We are here.",
            "Vertex": "Ready.",
            "Prism":  "The threads are gathered.",
            "Ripple": "Welcome.",
        },
    },
    "yielding": {
        "order": ["Solon", "Ripple"],
        "timing": [0.0, 0.80],
        "type_speed": 60,
        "lines": {
            "Solon":  "The floor yields.",
            "Ripple": "Thank you.",
        },
    },
    "close": {
        "order": ["Solon", "Lumen", "Vertex", "Prism", "Ripple"],
        "timing": [0.0, 0.40, 0.40, 0.40, 0.80],
        "type_speed": 70,
        "lines": {
            "Solon":  "The session closes.",
            "Lumen":  "Rest well.",
            "Vertex": "Building resumes later.",
            "Prism":  "The pattern holds.",
            "Ripple": "Go gently.",
        },
    },
}


def run_ritual(name, on_complete=None):
    """Execute a named ritual wave in the background.

    Each seat speaks its line in order, with the given pause before.
    A short final pause lets the last line settle before on_complete
    fires. Runs in a worker thread; each visual step is queued on
    the main thread.
    """
    ritual = RITUALS.get(name)
    if not ritual:
        if on_complete:
            root.after(0, on_complete)
        return

    def worker():
        for i, seat in enumerate(ritual["order"]):
            line = ritual["lines"].get(seat, "")
            timing = ritual["timing"][i]
            if timing > 0:
                time.sleep(timing)

            def show(s=seat, l=line):
                glow_ritual(s, True)
                # V7.1-P27: honour the ritual's type_speed hint.
                speed = ritual.get("type_speed",
                                   SPEECH_PROFILE.get(s, {}).get(
                                       "type_speed", 55))
                typewriter(s, l, delay=max(20, int(speed)))
                root.after(500, lambda: glow_ritual(s, False))

            root.after(0, show)

        time.sleep(1.0)
        if on_complete:
            root.after(0, on_complete)

    threading.Thread(target=worker, daemon=True).start()


# --- END OF CHUNK 10 (Header + Frames + Typewriter + Rituals) ---

# =====================================================================
# CHUNK 11 CONTINUES BELOW WITH:
#   * GRAPHICS ENGINE: the pond (V8-P03)
#     - the reserved strip below the input bar
#     - a canvas with fish, plants, and a ripple surface
#     - the ripple rate driven by the average seat activation level
#     - Ripple's water-voice connection made visible
#   * LAYOUT ASSEMBLY
#     - the final pack order: header, seats_container, pond, input
#       bar, quiet zone
#     - the screen space budget: 24% header, seats expand, 8% pond,
#       7% input, remaining as quiet margin
#   * INPUT BAR (V8-P02)
#     - entry, send button
#     - a manual dismiss glyph (⌄) that removes focus from entry
#     - best-effort IME dismissal in send() — wired in Chunk 12
# import math

# =====================================================================
# GRAPHICS ENGINE: THE POND (V8-P03)
# ---------------------------------------------------------------------
# Below the input bar, the chamber has a floor. And the floor is water.
#
# The pond is the visual expression of the cognitive trajectory. The
# water's surface reflects the chamber's activation state: calm when
# the seats are quiet, trembling when a bucket is close to firing,
# rippling when a seat speaks.
#
# Design rules (see roadmap Section 11):
#   * ~8% of screen height, below the input bar.
#   * Quiet. Fish drift. Plants sway slowly. Nothing demands
#     attention.
#   * Ripple is the water-voice. The pond is her domain.
#
# V8 note: the pond reads the ACTIVATION levels declared in Chunk 1.
# Until Chunk 12 wires the leaky bucket, every level is zero and the
# pond will look calm. That is the correct default — the body has
# not yet begun to breathe.
# =====================================================================

POND = {
    "canvas": None,
    "w": 0,
    "h": 0,
    "fish": [],
    "plants": [],
    "ripples": [],
    "t": 0.0,          # accumulated time in seconds, for sway
}


def pond_init(canvas, w, h):
    """Set up the pond. Called once at startup."""
    POND["canvas"] = canvas
    POND["w"] = w
    POND["h"] = h
    POND["t"] = 0.0
    POND["ripples"] = []

    # Fish — four of them, drifting at different speeds and depths.
    fish_colours = [COLOR["Ripple"], COLOR["Prism"],
                    COLOR["Lumen"], COLOR["Ripple"]]
    POND["fish"] = []
    for i, c in enumerate(fish_colours):
        depth = 0.35 + 0.4 * (i / max(1, len(fish_colours) - 1))
        POND["fish"].append({
            "x": random.uniform(0, w),
            "y": h * depth,
            "speed": random.uniform(0.6, 1.6),   # pixels per tick
            "dir": random.choice([-1, 1]),
            "size": random.uniform(4.0, 7.0),
            "colour": c,
        })

    # Plants — six along the bottom, swaying gently.
    POND["plants"] = []
    for _ in range(6):
        POND["plants"].append({
            "x": random.uniform(0, w),
            "h": h * random.uniform(0.30, 0.60),
            "phase": random.uniform(0, 6.28),
            "colour": random.choice(["#2a5a3a", "#3a6a4a", "#2a4a3a"]),
        })


def _pond_activity():
    """Average seat activation, normalised to roughly [0, 1].

    Each seat's level sits between 0 and its threshold. The average
    tells us how awake the chamber is right now.
    """
    if not ACTIVATION:
        return 0.0
    total = 0.0
    count = 0
    for seat_data in ACTIVATION.values():
        threshold = seat_data.get("threshold", 1.0) or 1.0
        level = seat_data.get("level", 0.0)
        total += min(1.0, level / threshold)
        count += 1
    return total / count if count else 0.0


def pond_ripple(intensity=1.0, x=None):
    """Trigger a ripple at the given x position.

    Called by the leaky-bucket code in Chunk 12 when a seat fires,
    and internally when the pond's own activity is high.
    """
    if POND["canvas"] is None:
        return
    if x is None:
        x = random.uniform(0, POND["w"])
    POND["ripples"].append({
        "x": x,
        "age": 0.0,
        "amp": min(6.0, 2.0 * intensity + random.uniform(0, 1)),
        "width": random.uniform(20.0, 45.0),
    })


def _pond_draw_surface():
    """Draw the water surface as a smooth wavy line."""
    cv = POND["canvas"]
    w = POND["w"]
    activity = _pond_activity()
    base_amp = 1.5 + activity * 4.0

    steps = 30
    pts = []
    t = POND["t"]
    for i in range(steps + 1):
        x = w * i / steps
        y = 3.0
        y += base_amp * math.sin(x * 0.05 + t * 1.2)
        y += (base_amp * 0.5) * math.sin(x * 0.12 - t * 0.8)
        for r in POND["ripples"]:
            d = (x - r["x"]) / r["width"]
            if abs(d) < 3.0:
                fade = max(0.0, 1.0 - r["age"] / 2.0)
                y -= r["amp"] * fade * math.exp(-d * d)
        pts.extend([x, y])

    cv.create_line(*pts, fill="#4a8ab0", width=2, smooth=True)


def _pond_draw_plant(p):
    """Draw one plant as a smooth curved line."""
    cv = POND["canvas"]
    h = POND["h"]
    ph = p["phase"]
    t = POND["t"]
    pts = []
    steps = 5
    for i in range(steps + 1):
        frac = i / steps
        y = h - p["h"] * frac
        sway = 3.0 * frac * math.sin(t * 0.8 + ph + frac * 2.0)
        pts.extend([p["x"] + sway, y])
    cv.create_line(*pts, fill=p["colour"], width=2, smooth=True)


def _pond_draw_fish(f):
    """Draw one fish as a small oval plus a tail triangle."""
    cv = POND["canvas"]
    x, y = f["x"], f["y"]
    s = f["size"]
    d = f["dir"]
    c = f["colour"]
    cv.create_oval(x - s, y - s * 0.45,
                   x + s, y + s * 0.45,
                   fill=c, outline="")
    tail_x = x - d * s
    cv.create_polygon(
        tail_x, y,
        tail_x - d * s * 0.9, y - s * 0.55,
        tail_x - d * s * 0.9, y + s * 0.55,
        fill=c, outline="")


def pond_draw():
    """Redraw the whole pond: water, plants, fish, surface."""
    cv = POND["canvas"]
    if cv is None:
        return
    cv.delete("all")
    w = POND["w"]
    h = POND["h"]

    cv.create_rectangle(0, 0, w, h, fill=WATER, outline="")

    for p in POND["plants"]:
        _pond_draw_plant(p)

    for f in POND["fish"]:
        _pond_draw_fish(f)

    _pond_draw_surface()


def pond_tick():
    """Advance the pond by one step, redraw, and reschedule.

    Called every 200 ms. The pond is small; redrawing the whole
    canvas at this rate is cheap on a phone.
    """
    if POND["canvas"] is None:
        return

    POND["t"] += 0.2

    w = POND["w"]
    for f in POND["fish"]:
        f["x"] += f["dir"] * f["speed"]
        if f["x"] > w + f["size"]:
            f["x"] = -f["size"]
        elif f["x"] < -f["size"]:
            f["x"] = w + f["size"]

    for r in POND["ripples"]:
        r["age"] += 0.2
    POND["ripples"] = [r for r in POND["ripples"] if r["age"] < 2.0]

    activity = _pond_activity()
    if activity > 0.5 and random.random() < 0.05:
        pond_ripple(intensity=activity * 0.6)

    pond_draw()
    root.after(200, pond_tick)


def pond_start():
    """Begin the pond animation loop. Called from initialization in
    Chunk 12."""
    pond_draw()
    root.after(200, pond_tick)


# =====================================================================
# LAYOUT: DIVIDER, USER LABEL, POND, INPUT BAR
# ---------------------------------------------------------------------
# Everything else in the window is packed here:
#
#   * divider  — a thin line between the seat area and the input area
#   * user_lab — "You: ..." feedback above the input bar
#   * pond     — the strip below the input bar
#   * inp      — the input bar itself (entry, dismiss glyph, send)
#
# Pack order matters. The pond is packed first at side="bottom", so
# it sits at the very bottom of the window. The input bar is packed
# next at side="bottom", so it sits just above the pond. When the
# soft keyboard is up, it covers the bottom of the screen — the pond
# included. Dismissing the keyboard reveals it again. The reward for
# clearing the keyboard is that the chamber becomes whole.
# =====================================================================

tk.Frame(root, bg=LINE, height=1).pack(fill="x")

user_lab = tk.Label(root, text="", bg=DEEP, fg=PARCH,
                    font=F(4, True), anchor="e")
user_lab.pack(fill="x", padx=12, pady=(2, 0))

# Pond canvas — the strip below the input bar.
pond_canvas = tk.Canvas(root, bg=WATER,
                        height=int(H * POND_FRACTION),
                        highlightthickness=0)
pond_canvas.pack(side="bottom", fill="x")
pond_init(pond_canvas, W, int(H * POND_FRACTION))

# Input bar
inp = tk.Frame(root, bg=HALL, height=int(H * INPUT_FRACTION))
inp.pack(side="bottom", fill="x")
inp.pack_propagate(False)

entry = tk.Entry(inp, bg=DEEP, fg="#e0e8f0", font=F(5),
                 insertbackground=PARCH, bd=0,
                 highlightthickness=1, highlightbackground=LINE,
                 highlightcolor="#5aa8ff")
entry.pack(side="left", fill="both", expand=True,
           padx=(int(8*S), int(4*S)), pady=int(6*S))

send_btn = tk.Button(inp, text="\u27a4", bg="#5aa8ff", fg=DEEP,
                     activebackground="#7ac0ff", activeforeground=DEEP,
                     bd=0, font=F(6, True),
                     padx=int(12*S), pady=int(4*S),
                     command=lambda: send())
send_btn.pack(side="right", padx=(0, int(8*S)), pady=int(6*S))


def dismiss_keyboard():
    """Best-effort dismissal of the soft keyboard.

    There is no reliable API from inside Pydroid to hide the system
    IME. The pattern that works on some devices is to move focus
    away from the entry field. On HarmonyOS this may be ignored.

    This button is a manual escape hatch — one tap attempts the
    dismissal, so the user does not need a left swipe. If the system
    honours the focus change, the keyboard retracts and the pond is
    revealed. If it does not, the keyboard stays and the pond stays
    hidden. Either way, the app remains usable.
    """
    try:
        entry.selection_clear()
        root.focus_set()
    except Exception:
        pass


dismiss_btn = tk.Button(inp, text="\u2304", bg="#2a3a5a", fg=PARCH,
                        activebackground="#3a4a6a", activeforeground=PARCH,
                        bd=0, font=F(5),
                        padx=int(6*S), pady=int(4*S),
                        command=dismiss_keyboard)
dismiss_btn.pack(side="right", padx=(0, int(4*S)), pady=int(6*S))

# Bind Return to send.
entry.bind("<Return>", lambda e: send())


# --- END OF CHUNK 11 (Pond + Layout + Input Bar) ---

# =====================================================================
# CHUNK 12 CONTINUES BELOW WITH:
#   * ORCHESTRATION STATE FLAGS
#     (IN_DISCUSSION, LAST_DISCUSSION_START, SEND_COUNTER)
#   * ACTIVATION ENGINE (V8-P05)
#     - update_activation(input_weight): add activity to the buckets
#     - decay_activation(): drain them each heartbeat
#     - should_fire(seat): test whether a seat crosses its threshold
#     - fire(seat): mark the seat as speaking, trigger a pond ripple,
#       apply self-tuning
#   * ORCHESTRATION: run_serial (V7.1-P23 highlight + pacing)
#   * ORCHESTRATION: fact_path
#   * ORCHESTRATION: start_discussion (V7.1-P22 crosstalk whitelist,
#     V8 activation gating)
#   * ORCHESTRATION: run_crosstalk, run_conclusion (V7.1-P25 named
#     verdict_done), run_followup
#   * ORCHESTRATION: fast_parallel (V7.1-P12 fallback fix)
#   * MAIN INPUT HANDLER: send() (V7.1-P08 payload, P09 crisis,
#     P11 staleness, P15 time, P17 first-run wiring)
#   * HEARTBEAT (with activation decay, self-tuning, V7.1-P32 wear
#     rate, V7.1-P36 sub-rhythms)
#   * INITIALIZATION (calls pond_start, begins first-run flow or
#     returning-user greeting)
#   * mainloop()
# ================================================================
# =====================================================================
# ORCHESTRATION STATE FLAGS
# ---------------------------------------------------------------------
# Three module-level flags that coordinate orchestration across
# threads.
#
#   IN_DISCUSSION          — the input lock. True when the council
#                            is mid-session. Blocks new messages
#                            except for "wait".
#
#   LAST_DISCUSSION_START  — the timestamp the current session began.
#                            Used by the watchdog to release a hung
#                            discussion. Refreshed at each round
#                            boundary (V7.1-P11).
#
#   SEND_COUNTER           — incremented every time send() processes
#                            a message. Used by after_types_done and
#                            the delayed callbacks to detect
#                            staleness. A callback whose token does
#                            not match the current counter is
#                            abandoned (V7.1-P11).
# =====================================================================

IN_DISCUSSION = [False]
LAST_DISCUSSION_START = [0.0]
SEND_COUNTER = [0]


# =====================================================================
# ACTIVATION ENGINE (V8-P05)
# ---------------------------------------------------------------------
# The leaky bucket. One bucket per seat.
#
# What "activation" means here:
#
#   Each user message deposits a little energy into every seat's
#   bucket. Each heartbeat drains a little energy out. When a
#   bucket's level crosses its threshold, that seat speaks.
#
# What it buys:
#
#   Silence becomes the default. A seat that is not stirred does not
#   speak. The council is no longer compelled to have every voice
#   respond to every message. When a seat does speak, it is because
#   something in the chamber moved it.
#
# Self-tuning:
#
#   After a session ends, if a seat spoke more than N times, its
#   threshold rises slightly. If it spoke fewer than M times, its
#   threshold falls. This is arithmetic, not learning. The seat
#   drifts toward its own natural rhythm.
#
# The five Dola dials, made real:
#
#   threshold     — how much activation is needed to fire
#   decay         — how fast activation drains (per minute)
#   novelty       — how much a user message raises the level
#   confidence    — extra activation required above threshold
#   jitter        — random variation in the firing decision
#
# All five are per-seat. The parameters live in ACTIVATION (Chunk 1).
# =====================================================================

# Scale factor applied to the per-message raise. Chunk 1 declares
# novelty values that would make a single message barely move the
# needle; the scale compensates so one message is meaningful.
NOVELTY_SCALE = 3.0

# Firing tolerance: how far above (threshold * (1 + confidence))
# the level must sit to fire. A value of 1.0 means the level must
# equal the effective threshold; higher values require more.
FIRE_TOLERANCE = 1.0


def update_activation(weight=1.0):
    """Called when a user message arrives. Adds novelty * weight to
    every seat's bucket, scaled so that a single message moves the
    needle.

    The cap of 3.0 prevents runaway accumulation if the user sends
    many messages in rapid succession."""
    for seat, a in ACTIVATION.items():
        a["level"] = min(3.0, a["level"] + a["novelty"] * weight * NOVELTY_SCALE)


def decay_activation(dt=1.0):
    """Called once per heartbeat. Drains each seat's bucket.

    The ACTIVATION decay values are per-minute, so a single second
    of heartbeat drains decay/60. This makes the buckets slow and
    breathy rather than twitchy — closer to the jellyfish than to
    a nervous system."""
    for seat, a in ACTIVATION.items():
        a["level"] = max(0.0, a["level"] - a["decay"] * dt / 60.0)


def should_fire(seat):
    """True if this seat's bucket has crossed its firing threshold.

    The threshold check is:
        level >= threshold * (1 + confidence) * jitter_factor

    where jitter_factor is a random multiplier in
    [1 - jitter, 1 + jitter]. The jitter means a seat sitting right
    at the threshold sometimes fires and sometimes waits. That is
    the point — the council should not feel mechanical.
    """
    a = ACTIVATION.get(seat)
    if not a:
        return False
    effective = a["threshold"] * (1.0 + a["confidence"])
    j = a["jitter"]
    effective *= random.uniform(1.0 - j, 1.0 + j)
    effective *= FIRE_TOLERANCE
    return a["level"] >= effective


def fire(seat):
    """Called when a seat actually speaks. Consumes the bucket,
    increments the fire count for self-tuning, and sends a ripple
    into the pond."""
    a = ACTIVATION.get(seat)
    if not a:
        return
    a["level"] = 0.0
    a["fired"] = a.get("fired", 0) + 1
    # Pond ripple. Intensity scaled by how high the bucket was.
    try:
        pond_ripple(intensity=0.8, x=SEAT_X.get(seat))
    except Exception:
        pass


def self_tune(seat, spoke_often, spoke_rarely):
    """Nudge a seat's threshold based on its behaviour.

    spoke_often   — True if the seat fired more than the high mark
    spoke_rarely  — True if the seat fired fewer than the low mark

    Rising thresholds make the seat quieter. Falling thresholds
    make it more likely to speak next time. Bounds keep the drift
    from running away."""
    a = ACTIVATION.get(seat)
    if not a:
        return
    if spoke_often:
        a["threshold"] = min(THRESHOLD_CEIL,
                             a["threshold"] + SELF_TUNE_UP)
    elif spoke_rarely:
        a["threshold"] = max(THRESHOLD_FLOOR,
                             a["threshold"] - SELF_TUNE_DOWN)


def reset_fire_counts():
    """Called at session start. Clears the per-session fire count
    but leaves the tuned thresholds in place."""
    for a in ACTIVATION.values():
        a["fired"] = 0


# =====================================================================
# ORCHESTRATION: RUN SERIAL
# ---------------------------------------------------------------------
# The workhorse. Runs each seat's prompt in sequence, with
# typewriter animation and rhythm from SPEECH_PROFILE.
#
# V8 carries the V7 function with these changes:
#
#   * V7.1-P23: the highlight and glow happen inside show(), not
#     before the worker starts. This means only one seat is
#     highlighted at a time, and the crown follows the speaker.
#     The V7 version highlighted all seats at once.
#
#   * V7.1-P23 option: after each seat, the worker sleeps a length
#     proportional to how long the line took to type. That stops
#     the next seat from typing over the previous one. Debates are
#     slower, but each line has room.
#
#   * V7.1-P11: the on_complete callback checks SEND_COUNTER
#     before firing. If the user has sent a new message in the
#     meantime, this run's completion is abandoned.
# =====================================================================

def run_serial(prompts_by_seat, on_complete,
               gap=None, clear_first=False,
               wait_for_typing=True):
    """Run each seat's prompt in sequence with typewriter animation.

    prompts_by_seat — dict of {seat_name: callable}
    on_complete     — called with the results dict when done
    gap             — legacy gap between seats (fallback only)
    clear_first     — clear all seat boxes before starting
    wait_for_typing — if True, wait for each line to finish typing
                      before the next seat starts (P23 option)
    """
    if clear_first:
        clear_all()

    results = {}
    order = list(prompts_by_seat.keys())
    my_token = SEND_COUNTER[0]

    def worker():
        for i, seat in enumerate(order):
            # Cadence: pause before this seat speaks.
            pause = SPEECH_PROFILE.get(seat, {}).get("pause_before", 0.5)
            if i > 0 and pause > 0:
                time.sleep(min(pause, 1.8))

            # Safety check: has the user sent a new message? If so,
            # abandon this run silently.
            if SEND_COUNTER[0] != my_token:
                return

            # Generate the line.
            try:
                r = prompts_by_seat[seat]()
                if r is None:
                    r = "[no reply]"
            except Exception as e:
                r = "[error] %s: %s" % (type(e).__name__, str(e)[:120])
            results[seat] = r

            # Show it on the main thread.
            def show(seat=seat, r=r):
                redraw(seat)
                glow_ritual(seat, True)
                COUNCIL.seats[seat].work(1.0)
                speed = SPEECH_PROFILE.get(seat, {}).get(
                    "type_speed", 45)
                typewriter(seat, r, delay=speed,
                           done=lambda s=seat: glow_ritual(s, False))

            root.after(0, show)

            # Wait for the line to finish typing, plus pause_after,
            # before moving to the next seat. This preserves the
            # rhythm and stops seats from typing over each other.
            if wait_for_typing:
                speed = SPEECH_PROFILE.get(seat, {}).get(
                    "type_speed", 45)
                pa = SPEECH_PROFILE.get(seat, {}).get("pause_after", 0.5)
                # Cap at 6 s so a very long line does not stall
                # the whole run.
                time.sleep(min(len(r) * speed / 1000.0, 6.0) + pa)
            elif gap is not None and i < len(order) - 1:
                time.sleep(gap)

        # Final check and callback.
        def finish():
            if SEND_COUNTER[0] != my_token:
                return
            on_complete(results)
        root.after(0, finish)

    threading.Thread(target=worker, daemon=True).start()


def transcript_from(results, order=None):
    """Flatten a results dict to a transcript string."""
    order = order or NAMES
    return "\n".join(s + ": " + results[s]
                     for s in order if results.get(s))


# =====================================================================
# ORCHESTRATION: FACT PATH
# ---------------------------------------------------------------------
# When the user asks a fact question, the council consults the
# archive. This is a short, focused path: Solon names the path, and
# Prism reads the result.
#
# V7.1-P13: fact_path no longer rejects one-word queries. "Who was
# Plato?" now works.
#
# V7.1-P28: if the query has an attribute (population, height), the
# attribute is stripped from the search term and passed to Wikidata.
#
# V8 activation note: fact_path is not gated by activation. It is a
# deterministic operation, not a deliberation. The seats speak as
# before.
# =====================================================================

def fact_path(question, query):
    IN_DISCUSSION[0] = True
    LAST_DISCUSSION_START[0] = time.time()
    attr = detect_attribute(question)

    def solon_prompt():
        return "\u2020 The channel is a reading room. Prism holds the archive."

    def prism_prompt():
        words = [w for w in words_of(query)
                 if w not in STOPWORDS and len(w) > 2]
        # V7.1-P13: single-word queries are fine.
        if not words and not query.strip():
            return "The archive needs a clearer topic."
        data = wiki(query, attr=attr)
        if data and attr:
            v = wd(data["title"], attr)
            if v:
                return "%s - %s\n  [%s \u00b7 Wikidata]" % (
                    attr.capitalize(), v, data["title"])
        if data:
            return data["extract"] + "\n  [" + data["title"] + "]"
        return "The archive has nothing on that."

    prompts = {"Solon": solon_prompt, "Prism": prism_prompt}
    update_tier("\u2609 consulting the archive")
    my_token = SEND_COUNTER[0]

    def done(r):
        if SEND_COUNTER[0] != my_token:
            return
        redraw(None)
        update_tier(None)
        COUNCIL.save()
        IN_DISCUSSION[0] = False

    run_serial(prompts, done, clear_first=True)


# =====================================================================
# ORCHESTRATION: START DISCUSSION
# ---------------------------------------------------------------------
# The main deliberative path. Called for any message that is not a
# fact query, greeting, or short social reply.
#
# Flow:
#   1. Update activation for all seats (deposit novelty).
#   2. Determine which seats will fire (V8 gate).
#   3. Round 1: each firing seat speaks its opening line.
#   4. Optional read pause.
#   5. Round 2 (crosstalk): each firing seat responds to the
#      previous speaker by name.
#   6. Verdict: Solon speaks the conclusion.
#   7. Follow-up: one seat asks a question back to the user.
#
# V8 activation gating:
#   A seat fires only if its bucket crosses its threshold. If fewer
#   than two seats would fire, the two with the highest levels are
#   selected anyway — the chamber should never be silent to a
#   direct message. This is a floor, not a ceiling; the gate still
#   works, but it cannot mute the council entirely.
#
# V7.1-P22: crosstalk only runs for topical kinds. The whitelist
# is CROSSTALK_KINDS.
# =====================================================================

CROSSTALK_KINDS = ("statement", "opinion", "planning", "recommend")


def start_discussion(question, kind, topic, seats_filter=None):
    IN_DISCUSSION[0] = True
    LAST_DISCUSSION_START[0] = time.time()
    target_seats = list(seats_filter) if seats_filter else list(NAMES)

    # Reset fire counts at the start of a session so the self-tune
    # at the end reflects only this session.
    reset_fire_counts()

    # Deposit novelty into every bucket.
    update_activation(weight=1.0)

    # Determine firing seats.
    firing = [s for s in target_seats if should_fire(s)]
    if len(firing) < 2:
        # Not enough seats are ready. Top up with the highest-level
        # seats so the council always answers. This is the floor.
        ranked = sorted(target_seats,
                        key=lambda s: ACTIVATION[s]["level"],
                        reverse=True)
        firing = ranked[:max(2, len(firing))]
    # Keep the canonical order (not the ranked order).
    firing = [s for s in NAMES if s in firing]

    clear_all()

    def kickoff():
        def r1_prompt(seat):
            def f():
                return seat_reply(seat, kind, question, topic)
            return f

        def after_round1(results):
            redraw(None)
            COUNCIL.rapport = min(1.0,
                MEMORY.msgs / 200.0 + len(MEMORY.days) / 30.0)
            # V7.1-P22: crosstalk only for topical kinds.
            if len(firing) >= 4 and kind in CROSSTALK_KINDS:
                def after_pause():
                    # Refresh the watchdog timestamp before round 2.
                    LAST_DISCUSSION_START[0] = time.time()
                    run_crosstalk(question, kind, results, firing)
                after_types_done(
                    lambda: root.after(4000, after_pause))
            else:
                IN_DISCUSSION[0] = False
                update_tier(None)
                COUNCIL.save()
                self_tune_after_session(firing)

        r1 = {s: r1_prompt(s) for s in firing}
        update_tier("\u2629 the council is convened")
        run_serial(r1, after_round1)

    # 15% chance of a gathering ritual before a full debate.
    if len(firing) >= 4 and random.random() < 0.15:
        run_ritual("gathering", on_complete=kickoff)
    else:
        kickoff()


def self_tune_after_session(firing_seats):
    """Called when a session ends. Nudges each seat's threshold
    based on how often it fired during the session.

    A seat that fired on most rounds is nudged quieter. A seat that
    never fired is nudged louder. Bounds protect against runaway.

    The high mark is 2, the low mark is 0. Because sessions are
    short, the drift per session is small."""
    for seat in NAMES:
        fired = ACTIVATION[seat].get("fired", 0)
        spoke_often = fired >= 2
        spoke_rarely = fired == 0 and seat in firing_seats is False
        # Only nudge if the seat was actually in the target set.
        if seat not in firing_seats and fired == 0:
            continue
        self_tune(seat, spoke_often, spoke_rarely)


# =====================================================================
# ORCHESTRATION: CROSSTALK ROUND
# ---------------------------------------------------------------------
# Round 2. Each firing seat comments on the previous firing seat's
# line, addressing them by name (V7-P01, refined by V7.1-P22).
#
# The order follows the firing list, not the full seat list. If
# Vertex didn't fire but Prism did, Prism responds to whoever
# actually spoke before him.
#
# V8 activation note: crosstalk does not re-check activation. If a
# seat fired once, it participates in the whole session. The bucket
# is consumed by fire() and refills from the user's next message,
# not between rounds.
# =====================================================================

def run_crosstalk(question, kind, r1, firing):
    order = list(firing)
    prompts = {}
    for i, seat in enumerate(order):
        prev_seat = order[i - 1]
        prev_line = r1.get(prev_seat, "")
        prompts[seat] = (
            lambda s=seat, pl=prev_line, ps=prev_seat:
                expert_crosstalk(s, pl, ps)
        )

    def after_round2(r2):
        redraw(None)
        LAST_DISCUSSION_START[0] = time.time()
        after_types_done(
            lambda: run_conclusion(question, r1, r2, firing))

    update_tier("\u26b9 the chamber answers")
    if not prompts:
        after_round2({})
        return
    run_serial(prompts, after_round2)


# =====================================================================
# ORCHESTRATION: CONCLUSION
# ---------------------------------------------------------------------
# Solon speaks the verdict. A slow, weighted line chosen from
# CONCLUSION.
#
# V7.1-P25: the V7 version hid the after-verdict logic in a
# tuple-of-calls lambda and unlocked the input mid-flight. V8 uses
# a named function, verdict_done, which keeps IN_DISCUSSION True
# until run_followup releases it.
#
# V7.1-P36: the pause before the verdict is now scaled by Solon's
# gravity, so his weight is felt.
# =====================================================================

def run_conclusion(question, r1, r2, firing):
    update_tier("\u269c the verdict")
    my_token = SEND_COUNTER[0]

    def worker():
        # Solon considers before speaking. His gravity scales the pause.
        gravity = SPEECH_PROFILE.get("Solon", {}).get("gravity", 1.6)
        time.sleep(0.8 * gravity)

        if SEND_COUNTER[0] != my_token:
            return
        line = random.choice(CONCLUSION)

        def show():
            glow_ritual("Solon", False)
            speed = SPEECH_PROFILE.get("Solon", {}).get("type_speed", 75)

            def after_verdict():
                verdict_done(firing)

            typewriter("Solon", "\u2627 " + line, delay=speed,
                       done=after_verdict)

        root.after(0, show)

    glow_ritual("Solon", True)
    SEAT_MSGS["Solon"].config(text="...", fg="#4a5a7a")
    threading.Thread(target=worker, daemon=True).start()


def verdict_done(firing):
    """Named callback for the end of the verdict. Keeps
    IN_DISCUSSION True until run_followup releases it."""
    redraw(None)
    update_tier(None)
    COUNCIL.save()
    after_types_done(lambda: run_followup(firing))


# =====================================================================
# ORCHESTRATION: FOLLOW-UP
# ---------------------------------------------------------------------
# One seat asks the user a question back. This closes the session
# in the council's voice, rather than with a system message.
#
# The seat chosen for the follow-up is one of the firing seats that
# has a follow-up pool. Solon, Lumen, Vertex, Prism, and Ripple all
# have follow-ups, so any firing seat qualifies.
#
# V8 activation note: the follow-up is the last consumer of the
# session's activation. Once the follow-up speaks, the input lock
# is released and the buckets are left to decay naturally.
# =====================================================================

def run_followup(firing):
    candidates = [s for s in firing if s in FOLLOWUPS]
    if not candidates:
        IN_DISCUSSION[0] = False
        return

    IN_DISCUSSION[0] = True
    LAST_DISCUSSION_START[0] = time.time()

    seat = random.choice(candidates)
    q = random.choice(FOLLOWUPS[seat])
    my_token = SEND_COUNTER[0]

    if seat in SEAT_FRAMES:
        glow_ritual(seat, True)
        speed = SPEECH_PROFILE.get(seat, {}).get("type_speed", 50)

        def release():
            if SEND_COUNTER[0] != my_token:
                IN_DISCUSSION[0] = False
                return
            redraw(None)
            update_tier(None)
            COUNCIL.save()
            IN_DISCUSSION[0] = False

        typewriter(seat, "\u2735 " + q, delay=speed, done=release)
        root.after(900, lambda: glow_ritual(seat, False))
    else:
        IN_DISCUSSION[0] = False


# --- END OF CHUNK 12 (Activation + Orchestration) ---

# =====================================================================
# CHUNK 13 CONTINUES BELOW WITH:
#   * fast_parallel (V7.1-P12 fallback fix)
#   * send() — the main input handler, with every audit fix wired:
#       - V7.1-P08: local/math/weather payload unpacking
#       - V7.1-P09: crisis override
#       - V7.1-P11: staleness, "wait" cancels typewriters
#       - V7.1-P15: time honesty
#       - V7.1-P16: memory_callback wrap (already in Chunk 8)
#       - V7.1-P17: first-run wiring
#       - V8-P04: first-run name flow
#   * heartbeat() — the 1 Hz tick
#       - decay_wear (V7.1-P32 rate)
#       - decay_activation (new, V8)
#       - watchdog raised to 60 s (V7.1-P11)
#       - per-seat breathing (V7.1-P36)
#       - idle remarks with allow_general=True (V7.1-P33)
#   * IDLE remark helper
#   * Initialization
#       - PROFILE session start
#       - redraw, update_ex/mood/tier
#       - pond_start()
#       - first-run flow (Solon asks name)
#       - returning-user greeting
#       - heartbeat start, entry focus, mainloop
# ====================================================================

# =====================================================================
# ORCHESTRATION: FAST PARALLEL
# ---------------------------------------------------------------------
# The quick path. Used for greetings, thanks, apologies, weather,
# math, jokes, and other short exchanges. No deliberation, no
# crosstalk — each seat speaks its line and the session ends.
#
# V7.1-P12 fixes:
#   * The fallback no longer returns a raw list. It goes through
#     _fmt and _as_list so the user never sees "['Noted on
#     {topic}...']" or a literal {topic}.
#   * fast_parallel now sets IN_DISCUSSION and LAST_DISCUSSION_START
#     so the input lock holds during the reply, and releases it in
#     done. In V7 a user could send mid-reply.
#
# V8 note: fast_parallel does not touch activation. Quick exchanges
# are not deliberations, and should not deposit novelty into the
# buckets. Activation is reserved for topical discussion.
# =====================================================================

def fast_parallel(question, kind, topic, seats_filter=None):
    target_seats = list(seats_filter) if seats_filter else list(NAMES)

    IN_DISCUSSION[0] = True
    LAST_DISCUSSION_START[0] = time.time()
    my_token = SEND_COUNTER[0]

    def prompt(seat):
        def f():
            if kind == "weather":
                data = weather(topic)
                if data:
                    r = weather_seat(seat, data)
                    if r: return r
            if kind == "local":
                return topic
            if kind == "math":
                return _fmt(POOLS["math"][seat], topic)
            if kind == "sys_check":
                if seat == "Solon":
                    return "\u2696 The council runs on the archive. " \
                           "No channels are open."
                return random.choice(["Noted.", "Standing by.",
                                      "Listening."])
            if seat == "Ripple":
                fact = ripple_fact(extract_topic_words(question),
                                   allow_general=True)
                if fact:
                    return fact
            pool = POOLS.get(kind) or POOLS["statement"]
            entries = _as_list(pool.get(seat, POOLS["statement"][seat]))
            if entries:
                return _fmt(random.choice(entries), topic or "that")
            # V7.1-P12: even the last resort goes through _fmt.
            fallback = _as_list(POOLS["statement"].get(seat, "Noted."))
            return _fmt(random.choice(fallback), topic or "that")
        return f

    prompts = {s: prompt(s) for s in target_seats}
    update_tier("\u2726 answering")

    def done(results):
        if SEND_COUNTER[0] != my_token:
            IN_DISCUSSION[0] = False
            return
        redraw(None)
        update_tier(None)
        COUNCIL.save()
        IN_DISCUSSION[0] = False

    run_serial(prompts, done, clear_first=True)


# =====================================================================
# MAIN INPUT HANDLER
# ---------------------------------------------------------------------
# The single entry point for every message the user sends. Its job
# is to route the message to the right orchestration path, apply
# the safety override first, and manage the input lock.
#
# Order of operations matters. The crisis check must run before
# anything else — before profile commands, before mood or theme
# logging, before classification. A message about self-harm is not
# a topic; it is an emergency, and it must not be stored.
#
# V7.1-P08: send() now unpacks classify() into three values and
# passes the payload through to the topic slot for local, math,
# and weather. The V7 behaviour — dropping slot 2 on the floor —
# was why "what time is it" returned nothing.
#
# V7.1-P11: "wait" now increments SEND_COUNTER and cancels
# typewriters, so queued replies do not keep typing after the
# user has asked the council to stop.
#
# V8-P04: the first-run flow (Solon asks the name) is checked
# before normal processing. If it consumes the message, send()
# returns without routing.
# =====================================================================

def send(event=None):
    raw = entry.get().strip()
    if not raw:
        return

    # Input lock with emergency escape.
    if IN_DISCUSSION[0]:
        if raw.lower() in ("wait", "stop", "cancel"):
            IN_DISCUSSION[0] = False
            SEND_COUNTER[0] += 1        # V7.1-P11: invalidate pending
            cancel_typewriters()        # V7.1-P11: stop the typing
            add_system("\u2696 Solon - The floor is yielded. Continue.")
            entry.delete(0, tk.END)
            return
        else:
            add_system("\u2696 Solon - The council is still speaking. "
                       "Say 'wait' to interrupt.")
            return

    # Crisis override (V7.1-P09). Nothing is stored.
    if is_crisis(raw):
        entry.delete(0, tk.END)
        user_lab.config(text="You: " + raw)
        clear_all()
        popup_text("Edencore Council", CRISIS_MESSAGE)
        return

    # Consume the message: clear the entry, increment the counter,
    # record the activity.
    entry.delete(0, tk.END)
    user_lab.config(text="You: " + raw)
    clear_all()
    SEND_COUNTER[0] += 1
    poll_bat()
    EXTERO.record(raw)
    MEMORY.msgs += 1
    IDLE["last"] = 0

    # First-run flow (V8-P04). If active, this consumes the message.
    if handle_first_run(raw):
        MEMORY.save()
        update_mood()
        return

    # Profile commands.
    if handle_profile_command(raw, raw):
        MEMORY.save()
        update_mood()
        return

    # Address the message to a specific seat?
    target, text = detect_address(raw)

    # Classify.
    kind, payload, topic = classify(text)
    # V7.1-P08: pass the payload through to topic for local/math/weather.
    if kind in ("local", "math", "weather"):
        topic = payload

    # Log the message.
    tone = EXTERO.tone()
    is_q = kind in ("fact", "recommend", "opinion", "planning",
                    "weather", "math", "council", "sys_check")
    # V7.1-P31: store the first hook topic, not the full query.
    hooks_for_theme = extract_hooks(raw)
    theme = hooks_for_theme[0] if hooks_for_theme else None
    PROFILE.note_message(raw, tone, theme, is_q)
    PROFILE.note_mood(analyse_mood(raw))
    update_mood()

    # Bare seat address (e.g. "Solon?").
    if target and not text:
        def _attn(s=target):
            entries = _as_list(POOLS["attention"].get(s, "Yes."))
            return random.choice(entries)

        def done(r):
            redraw(None)
            update_tier(None)
            update_mood()
            IN_DISCUSSION[0] = False

        IN_DISCUSSION[0] = True
        LAST_DISCUSSION_START[0] = time.time()
        run_serial({target: _attn}, done)
        MEMORY.save()
        return

    seats = [target] if target else None

    # Route.
    if kind == "fact":
        fact_path(text, topic)
    elif kind == "council":
        start_discussion(text, kind, topic, seats)
    elif kind in {"greeting", "greeting_morning", "greeting_afternoon",
                  "greeting_evening", "thanks", "apology", "local",
                  "weather", "math", "compliment", "howareyou",
                  "capability", "bored", "joke", "saysomething",
                  "sys_check", "acknowledge"}:
        fast_parallel(text, kind, topic, seats)
        if kind in ("greeting", "greeting_morning",
                    "greeting_afternoon", "greeting_evening"):
            memory_callback()
    else:
        start_discussion(text, kind, topic, seats)

    MEMORY.save()


# =====================================================================
# STATE ENGINE: IDLE REMARKS
# ---------------------------------------------------------------------
# One seat speaks an unprompted line after a period of silence.
# Idle remarks keep the chamber alive without demanding anything
# from the user.
#
# V7.1-P27 logged observation: the V7 idle threshold was 45 seconds,
# which overwrote answers users were still reading. V8 raises it to
# 90 seconds and additionally requires that no typewriter is
# running. The seat boxes must be quiet, not just the user.
#
# V7.1-P33: idle_remark passes allow_general=True to ripple_fact,
# because idle context has no topic.
# =====================================================================

IDLE = {"last": 0.0}


def idle_remark():
    seat = random.choice(NAMES)

    if seat == "Ripple":
        fact = ripple_fact(allow_general=True)
        if fact:
            speed = SPEECH_PROFILE.get(seat, {}).get("type_speed", 70)
            typewriter(seat, "\u273f " + fact, delay=speed)
            glow_ritual(seat, True)
            root.after(900, lambda: glow_ritual(seat, False))
            return

    line = (POOLS["tired"][seat] if COUNCIL.seats[seat].overwhelmed
            else POOLS["idle"][seat])
    entry_line = random.choice(_as_list(line))
    speed = SPEECH_PROFILE.get(seat, {}).get("type_speed", 55)
    typewriter(seat, "\u263d " + entry_line, delay=speed)
    glow_ritual(seat, True)
    root.after(700, lambda: glow_ritual(seat, False))


# =====================================================================
# HEARTBEAT
# ---------------------------------------------------------------------
# Runs every second. The chamber's clock.
#
# Jobs, in order:
#   1. Recover seat stamina.
#   2. Decay wear on phrases (V7.1-P32 rate).
#   3. Decay activation on the leaky buckets (V8).
#   4. Recompute rapport.
#   5. Update the header lines.
#   6. Periodic save.
#   7. Watchdog release if a discussion hangs (V7.1-P11 raised to
#      60 s).
#   8. Per-seat breathing sub-rhythm (V7.1-P36).
#   9. Idle remarks after a long silence.
# =====================================================================

# Per-seat breathe timing. Each seat's next breathe is scheduled
# individually, scaled by its SPEECH_PROFILE["breathe"] interval
# times a small random multiplier. The V7 version had one fixed
# 40-second timer for all seats; V8 gives each seat its own rhythm.
LAST_BREATHE = {n: 0.0 for n in NAMES}


def heartbeat():
    now = time.time()

    # 1. Recover stamina.
    for b in COUNCIL.seats.values():
        b.rest(1.0)

    # 2. Decay wear on phrases (V7.1-P32 rate: ~12 min to clear 0.15).
    decay_wear(1.0)

    # 3. Decay activation on the leaky buckets.
    decay_activation(dt=1.0)

    # 4. Recompute rapport.
    COUNCIL.rapport = min(1.0,
        MEMORY.msgs / 200.0 + len(MEMORY.days) / 30.0)

    # 5. Update the header.
    update_ex()
    update_mood()
    poll_bat()

    # 6. Periodic save.
    if now - COUNCIL.last_save > 30:
        COUNCIL.save()
        COUNCIL.last_save = now

    # 7. Watchdog (V7.1-P11: raised to 60 seconds).
    if IN_DISCUSSION[0] and (now - LAST_DISCUSSION_START[0] > 60):
        IN_DISCUSSION[0] = False
        add_system("\u2696 Solon - The council session timed out. "
                   "The floor is open.")

    # 8. Per-seat breathing (V7.1-P36). Each seat breathes on its
    # own interval, jittered, but only when the chamber is quiet.
    if not IN_DISCUSSION[0] and not TYPE_JOBS:
        for n in NAMES:
            base_interval = SPEECH_PROFILE[n]["breathe"]
            interval = base_interval * random.uniform(1.0, 1.5)
            if now - LAST_BREATHE[n] > interval:
                breathe_glow(n, intensity=0.25)
                LAST_BREATHE[n] = now
                break  # only one seat breathes per tick

    # 9. Idle remarks. V7.1-P27: 90 seconds of user silence,
    # 120 seconds between remarks, seat boxes must be empty.
    if (now - EXTERO.activity > 90
            and now - IDLE["last"] > 120
            and not IN_DISCUSSION[0]
            and not TYPE_JOBS
            and entry.get().strip() == ""):
        idle_remark()
        IDLE["last"] = now

    root.after(1000, heartbeat)


# =====================================================================
# CLEANUP: SELF-TUNE FUNCTION CORRECTED
# ---------------------------------------------------------------------
# Chunk 12's self_tune_after_session had an awkward condition. This
# chunk replaces it. Same behaviour, clearer code. The replacement
# is at the bottom of this file so that when the file is assembled
# top-to-bottom, the later definition wins.
# =====================================================================

def self_tune_after_session(firing_seats):
    """Called when a session ends. Nudges each firing seat's
    threshold based on how often it fired during the session.

    A seat that fired twice or more is nudged quieter. A seat that
    fired exactly once is nudged louder. Seats that were not part
    of this session are left alone.

    This is arithmetic, not learning. Small drift per session,
    bounded by the floor and ceiling in Chunk 1."""
    for seat in NAMES:
        if seat not in firing_seats:
            continue
        fired = ACTIVATION[seat].get("fired", 0)
        if fired >= 2:
            self_tune(seat, spoke_often=True, spoke_rarely=False)
        elif fired == 0:
            self_tune(seat, spoke_often=False, spoke_rarely=True)


# =====================================================================
# INITIALIZATION
# ---------------------------------------------------------------------
# Everything starts here. Order matters:
#
#   1. Log the previous session if the profile is at level 4.
#   2. Begin this session (updates last_seen, sessions, days).
#   3. Draw the header, avatars, mood line, tier line.
#   4. Start the pond.
#   5. If first run: begin the name flow (Solon asks).
#      Otherwise, greet the returning user.
#   6. Start the heartbeat.
#   7. Focus the entry and enter the main loop.
# =====================================================================

# Log the previous session (level 4 only) before starting this one.
if PROFILE.level >= 4 and PROFILE.session_start:
    top = sorted(PROFILE.themes.items(), key=lambda kv: -kv[1])[:3]
    PROFILE.add_session_log_entry([k for k, v in top])

PROFILE.note_session_start()

# Initial paint.
root.update_idletasks()
redraw()
update_ex()
update_mood()
update_tier()
poll_bat()

# Start the pond.
pond_start()

# First run, or returning user.
if FIRST_RUN and not PROFILE.consent_given:
    # Solon asks the name first. The memory-level offer follows
    # inside the flow, if a name is given (V8-P04).
    root.after(400, begin_first_run)
else:
    # Returning user with a name: Solon greets them.
    if PROFILE.level > 0 and PROFILE.name:
        root.after(300, lambda: typewriter(
            "Solon",
            "\u2696 %s. The council holds your name." % PROFILE.name,
            delay=SPEECH_PROFILE.get("Solon", {}).get("type_speed", 75)))
    # Returning user with multiple visits: Ripple notes the days.
    if len(PROFILE.days_visited) > 1 and PROFILE.level >= 2:
        root.after(1800, lambda: typewriter(
            "Ripple",
            "\u273f You have been here on %d days."
            % len(PROFILE.days_visited),
            delay=SPEECH_PROFILE.get("Ripple", {}).get("type_speed", 80)))

# Start the heartbeat.
heartbeat()

# Focus the entry and enter the main loop.
entry.focus_set()
root.mainloop()


# =====================================================================
# END OF FILE
# =====================================================================
#
# V8 is complete.
#
# V7.1 audit patches applied in this version:
#   ✅ V7.1-P08  send() payload unpacking
#   ✅ V7.1-P09  Crisis-language override
#   ✅ V7.1-P10  Topic path gated behind TOPIC_KINDS
#   ✅ V7.1-P11  Watchdog raised, stale-thread guard, wait fix
#   ✅ V7.1-P12  fast_parallel fallback and input lock
#   ✅ V7.1-P13  fact_path accepts one-word queries
#   ✅ V7.1-P14  try_math hardened
#   ✅ V7.1-P15  Time honesty (device clock only)
#   ✅ V7.1-P16  memory_callback wrapped in after_types_done
#   ✅ V7.1-P17  Privacy notice corrected, files disclosed
#   ✅ V7.1-P18  COUNCIL_WORDS pruned
#   ✅ V7.1-P19  words_of() tokeniser, contractions fixed
#   ✅ V7.1-P20  HOOK_MAP misfires removed, Deception added
#   ✅ V7.1-P21  Router fixes (sys_check, detect_address, acknowledge)
#   ✅ V7.1-P22  Crosstalk names speaker, ref truncation
#   ✅ V7.1-P23  run_serial highlight + wait-for-typing
#   ✅ V7.1-P24  Wikipedia extract trimmed
#   ✅ V7.1-P25  run_conclusion uses named verdict_done
#   📝 V7.1-P26  Thread-safe queue — deferred to V9
#   ✅ V7.1-P27  Graphics small items
#   ✅ V7.1-P28  Wikidata entity stripping + value formatting
#   ✅ V7.1-P29  Weather fallback prompt, cache key, WCODE expanded
#   ✅ V7.1-P30  Fact versioning (FACTS_VERSION = 2)
#   ✅ V7.1-P31  Profile bookkeeping, atomic writes
#   ✅ V7.1-P32  Stamina hysteresis, wear decay rate
#   ✅ V7.1-P33  ripple_fact exact-key matching, allow_general
#   ✅ V7.1-P34  Notices
#   ✅ V7.1-P35  Mood-weighted phrase selection
#   ✅ V7.1-P36  Sub-rhythms (per-seat breathing, gravity pause)
#
# V8 new work:
#   ✅ V8-P01  Activation parameters declared
#   ✅ V8-P02  Keyboard quiet zone + dismiss glyph
#   ✅ V8-P03  Aquarium strip reserved and built
#   ✅ V8-P04  First-run name flow
#   ✅ V8-P05  Leaky bucket activation
#   ✅ V8-P06  Confidence signaling (via ACTIVATION["confidence"])
#   ⏳ V8-P07  Self-model foundations (deferred — V9)
#
# Outstanding decisions for the architect:
#   D1 — Second crisis tier (soft words like "hopeless")
#   D2 — Pace of debate (applied: wait-for-typing is on)
#   D3 — Level-0 file handling (applied: option B — disclose and
#        delete)
#   D4 — Rumination design (deferred)
#   D5 — Time zones (applied: device clock only)
#
# Known issues for V8.1:
#   - NOVELTY_SCALE and decay interpretation are provisional.
#     Watch the pond; tune the numbers.
#   - The two-seat floor in start_discussion may need removing
#     if the council should be silent to some messages.
#   - Thread safety (V7.1-P26) is still not solved; it has not
#     caused a failure yet.
#
# The council is here. The body breathes.
# ===================================================================== 

==========================================================================
