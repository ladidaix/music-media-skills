# Sample output: Carousel Builder

Input: "Turn this album review into a five-slide Instagram carousel."

## Build plan

1. Slide 1, cover: headline set in two lines, for example with one serif italic accent word; artist photo cropped face-safe (face sits in the upper third, clear of the headline block); identity badge, for example bottom left.
2. Slide 2: the review's opening argument, word for word, one margin grid, 64px safe frame on all sides.
3. Slide 3: the track-by-track passage, word for word; flagged back to the author because it runs 12 words over the slide's capacity, with the two candidate cut points marked. Nothing trimmed silently.
4. Slide 4: the verdict paragraph, word for word, pull line set larger.
5. Slide 5, closer: rating line, footer handle placed to clear the platform's action buttons, follow prompt.

## Self-audit (runs before delivery)

1. Baselines: all interior headlines share one baseline grid. Pass.
2. Bottom margins: measured ink to footer gap equal on slides 2 to 5. Pass.
3. Face safety: no text overlaps the cover face region. Pass.
4. Copy integrity: slide text diffed against the source review. One flagged overflow (slide 3), zero silent edits. Pass with flag.
5. Export: lossless PNG, 1080 x 1350. Pass.

Delivered with a caption checklist (hook line, three context tags, one question for the comments) instead of a drafted caption. The author writes the caption.
