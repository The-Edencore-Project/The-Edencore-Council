# ---------------------------------------------------------------------
# V9 DESIGN NOTE — THE THREE LAYERS OF THE WORLD
# ---------------------------------------------------------------------
# The world has three layers, and they obey different rules.
#
#   LAYER 1  NATURAL   — mountains, oceans, forests, biomes, fauna
#   LAYER 2  HUMAN     — cities, towns, villages, density, activity
#   LAYER 3  DIGITAL   — compute, connectivity, cables, smart things
#
# They are separated because they change at different rates:
#
#   NATURAL   — permanent. A mountain does not move.
#   HUMAN     — slow. Cities evolve over decades.
#   DIGITAL   — fast. The digital world changed completely in 30 years.
#
# Different rates of change = different layers.
#
# ---------------------------------------------------------------------
# THE PRINCIPLE: NAMED EXEMPLARS + CATEGORY BANDS
# ---------------------------------------------------------------------
# Do not store every object. Store:
#   - a small number of BANDS (usually 1-5)
#   - one or two NAMED EXEMPLARS per band
#   - the CHARACTERISTIC that defines the band
#
# This gives the council a fuzzy understanding of the whole category
# without needing 50,000 rows. To answer "how big is X?", it finds
# the band and compares to the exemplar. That is how a human does it.
#
# =====================================================================
# LAYER 1 — THE NATURAL WORLD
# =====================================================================
#
# MOUNTAINS (bands 1-5)
#   1  hills            — Cotswolds, Chilterns
#   2  small ranges     — Pennines, Appalachians
#   3  medium ranges    — Alps, Rockies, Pyrenees
#   4  large ranges     — Andes, Urals, Great Dividing
#   5  colossal         — Himalaya, Karakoram
#
# OCEANS (bands 1-4)
#   1  small seas       — Adriatic, Baltic
#   2  medium seas      — North Sea, Caribbean
#   3  large oceans     — Atlantic, Indian
#   4  colossal         — Pacific
#
# RIVERS (bands 1-4)
#   1  small            — Thames, Seine
#   2  medium           — Rhine, Danube
#   3  large            — Mississippi, Yangtze
#   4  colossal         — Amazon, Nile
#
# FORESTS (bands 1-4) — with TYPE
#   1  small            — Epping Forest
#   2  medium           — Black Forest
#   3  large            — Congo Basin
#   4  colossal         — Amazon, Siberian taiga
#   TYPE  pine, deciduous, tropical rainforest, mangrove, boreal
#
# BIOMES — one classification per place
#   tropical, subtropical, temperate, boreal, arctic
#   desert, grassland, tundra, wetland, alpine
#
# DESERTS, PLAINS, PLATEAUS, TUNDRA — same 1-5 band schema
#
# FAUNA (bands 1-5)
#   1  microfauna       — insects, soil life
#   2  small animals    — rabbits, mice, birds
#   3  medium animals   — wolves, deer, seals
#   4  large animals    — bears, horses, big cats
#   5  megafauna        — elephants, whales, bison
#
# =====================================================================
# LAYER 2 — THE HUMAN WORLD
# =====================================================================
#
# SETTLEMENTS (bands 1-5)
#   1  hamlet          — a few houses
#   2  village         — small community
#   3  town            — local centre
#   4  city            — regional centre
#   5  megacity        — global hub
#
# DENSITY (bands 1-5)
#   1  wilderness      — almost no one
#   2  rural           — farms, scattered
#   3  suburban        — low-density housing
#   4  urban           — dense
#   5  hyperdense      — Hong Kong, Manhattan
#
# ACTIVITY — one per place
#   agricultural, industrial, service, tech, tourist, mixed
#
# MOVEMENT — one per place
#   hub, spoke, quiet, transit
#
# The council can reason:
#   "Is this a city or a town?"          -> band check
#   "Is it rural or urban?"              -> density check
#   "What does it do?"                   -> activity check
#
# =====================================================================
# LAYER 3 — THE DIGITAL WORLD (NEW)
# =====================================================================
#
# This layer is what makes Edencore different from a traditional
# world model. Most world models stop at humans. But the world now
# has a computational substrate, and it has geography.
#
# CONNECTIVITY (bands 1-4)
#   1  dark            — no reliable connection
#   2  shallow         — basic connectivity
#   3  deep            — high bandwidth, low latency
#   4  dense           — full fibre, edge compute, always-on
#
# COMPUTE (bands 1-4)
#   1  absent          — no local compute
#   2  distributed     — small nodes, cloud-only
#   3  regional        — data centres nearby
#   4  dense           — major clusters (Silicon Valley, Shenzhen)
#
# PHYSICAL INFRASTRUCTURE — named exemplars
#   undersea cables, satellite constellations, server farms,
#   smart grids, smart homes, cell towers
#
# SMART ENVIRONMENT — one per place
#   smart home, smart city, IoT active, IoT emerging, IoT absent
#
# The council can reason:
#   "Is this area well-connected?"       -> connectivity band
#   "Is there compute here?"             -> compute band
#   "Is this place smart or not?"        -> smart environment
#
# The user's original terms are preserved here:
#   deep, shallow, condensed, diluted
# They are exactly right. They describe the digital world the way
# a human feels it, not the way a network engineer measures it.
#
# =====================================================================
# THE NAME CONVENTION
# =====================================================================
#
# Every entry in the tree follows the same shape:
#
#   (name, category, band, parent, tags)
#
# Example entries:
#
#   ("Siberia",   "region",   4, "Russia",  ["taiga", "cold", "vast"])
#   ("Amazon",    "region",   5, "Brazil",  ["rainforest", "tropical"])
#   ("Everest",   "peak",     5, "Himalaya",["highest", "8848m"])
#   ("Sahara",    "desert",   5, "Africa",  ["hot", "vast", "sand"])
#   ("Hampshire", "county",   3, "England", ["temperate", "rural-mix"])
#   ("Tokyo",     "megacity", 5, "Japan",   ["hyperdense", "tech"])
#   ("Silicon V", "region",   5, "USA",     ["dense compute", "deep"])
#
# A band is never a precise value. It is a category. The named
# exemplar gives the council a comparison point. That is enough.
#
# =====================================================================
# DATA BUDGET
# =====================================================================
#
# Layer 1 (Natural)    ~3,000 entries    ~200 KB
# Layer 2 (Human)      ~8,000 entries    ~500 KB
# Layer 3 (Digital)    ~500 entries      ~40 KB
#
# Total                ~11,500 entries   ~750 KB
#
# Under 1 MB. Fits comfortably in Pydroid. Loads instantly.
#
# =====================================================================
# WHY THREE LAYERS, NOT ONE
# =====================================================================
#
# Because they obey different rules:
#
#   - Natural places are described by TERRAIN and BIOME.
#   - Human places are described by SIZE, DENSITY, and ACTIVITY.
#   - Digital places are described by CONNECTIVITY and COMPUTE.
#
# A mountain and a megacity and a server farm are all "places," but
# they have nothing in common. Forcing them into one schema would
# force the council to reason badly about all three.
#
# Three layers, three vocabularies, one tree.
#
# =====================================================================
# WHAT THIS REPLACES
# =====================================================================
#
# Do not store coordinates for every point on Earth (Design Note 18).
# Do not store every village by name (Design Note 18).
# Do not store precise measurements for every object.
#
# Instead: BANDS, EXEMPLARS, and CHARACTERISTICS.
#
# The world as a human understands it, not as a machine measures it.
# ---------------------------------------------------------------------
