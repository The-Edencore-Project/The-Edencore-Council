
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