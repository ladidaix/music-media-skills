---
name: carousel-builder
description: Build social media carousels for Instagram, LinkedIn, and TikTok with face-safe crops, a consistent identity system, platform-safe footers, and a rigorous high-resolution quality check. Use when creating a multi-slide social post, a slide deck for social, or a quote or tips carousel.
---

# Carousel Builder

## Purpose

Produce social carousels that look like they came from one editorial desk: a consistent visual system, copy in a clear voice, and a quality check thorough enough that defects get caught before the audience sees them.

## Workflow

1. Get the brief: platform, slide count, copy or outline, and the photos and assets.
2. Write the copy first. Scene first, contractions, the Oxford comma, and no em dashes. Never invent quotes, facts, or biographical details. Every claim must be verifiable against source material.
3. Build at high resolution, in the visual system below.
4. Run the full quality check before delivery. Look at the slides yourself, zoomed in, the way a reader will.
5. Deliver individual slide files, never a zip. Include a caption draft that matches the slides and ends on the call to action, if there is one.

## Visual system

### Every carousel

1. Face-aware crops: faces are never cut off, clipped by a frame edge, or hidden behind text. Verify every slide visually at high resolution.
2. Identity badge: a small circular crop of the final slide's photo, placed top-right on every slide, with a soft frosted halo and no hard ring. Render it sharp at high resolution. Its distance from the top edge should mirror the footer's distance from the bottom edge.
3. Platform-safe footer: put your handle in the footer, shifted inward far enough to clear the platform's action buttons and caption overlay on Instagram and TikTok.
4. Pick one text case system, for example all caps for headlines, and hold it across the whole deck unless the brief says otherwise.

### A glossy editorial template (starting point, adapt freely)

An editorial base with a beauty-magazine gloss works well for music and culture topics:

1. Palette: a cream base (`#F5F8EA`), warm dark ink panels (`#211712`), a coral accent (`#D75638`), and a pink accent (`#F4A7C3`). Dark contrast is mandatory. Never go full pastel.
2. Type pairing: a heavy display face for headlines (for example Unbounded Black), a serif italic for accent words inside the headline (for example Playfair Display Italic, in the coral accent), and a clean sans for body copy in sentence case (for example Epilogue).
3. A highlighted word in body copy gets the serif italic accent treatment, not just a color swap.
4. Devices that carry the system: an ink masthead panel on the cover, ink header and footer strips on interior slides, rounded photo frames with an offset outline (coral on the cover, pink inside), circular slide-number badges, a small sparkle badge on the cover photo corner, a squiggle underline under the serif accent word, a dotted divider row, and a tracked-caps series label as a kicker (for example `YOUR SERIES NAME`).
5. Never put meta text on the creative itself. A sticker announcing the format is not part of the design.

## Layout rules (the A+ audit)

1. Use one margin grid across all slides, and align everything to it.
2. Align type by its measured ink bounding box, never by the draw origin. Two lines that start at the same coordinate can still look misaligned.
3. Compute panel padding evenly from the content, on all sides.
4. Offset outline frames land exactly on the grid. Inset the photo by the offset amount so the math stays honest.
5. Center the cover badge exactly on the photo's corner point, not near it.
6. Draw body text word by word on a shared baseline. Aligning each word by its ink top makes baselines jump, which is the single most common amateur tell in generated carousels.
7. The bottom margin equals the top margin. No dead space at the foot of a slide.
8. If you build with a script, make the script self-audit these checks and print pass or fail for each one. All checks pass before delivery.

## Quality check

1. Render the tightest slides, especially bottom strips and dense text pages, at 70 dpi or higher and zoom in before delivery.
2. Check faces, crops, contrast, and text legibility on a phone-sized view, not only on a desktop.
3. For PDF carousels (LinkedIn), embed the original images losslessly. Never let an encoder recompress them.
4. If a PDF previews sharp but posts fuzzy, check the PDF's page dimensions before re-rendering. Small page dimensions lose pixels at any DPI. Re-export at a larger page size instead of only raising the render resolution.

## Output contract

Deliver:

1. The final slide images (or the PDF), high resolution and quality checked.
2. A caption draft consistent with the slides.
3. A short done and waiting-on note: what is ready to post, and what still needs approval.

## Example

A five-slide album review carousel:

1. Cover: artist photo with a face-safe crop, ink masthead panel, headline with one serif italic accent word, series kicker, sparkle badge.
2. The context: two or three sentences on where this album sits in the artist's career, one highlighted phrase.
3. The standout track: a pull quote from the lyrics you can verify, the track's story, and a dotted divider.
4. The verdict: who this album is for, in one honest paragraph.
5. Closer: your handle footer, the identity badge photo, and a question that invites comments.
