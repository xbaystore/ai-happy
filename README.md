# The Sunrise Hug

Entry for make.fun's `ai-happy-01`.

A small laughing child hugs a golden retriever puppy in a field of
sunflowers at golden sunrise, petals drifting in the warm morning
air. Two faces, cheek to cheek, eyes closed, both grinning — one
hug, one moment, nothing else in the way. Warm storybook
illustration in gold, honey and soft green, with the sunrise behind
them and the two figures large enough to read at thumbnail size.

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled
`art.jpg` (1024×1024, 225 KB) to `entry.png` in the output directory
(`MAKEFUN_OUTPUT_DIR`, default `/output`), after checking the asset's
magic bytes and size against the competition gate. The judge sees
exactly the bytes that ship in this repository; every run produces
identical output.
