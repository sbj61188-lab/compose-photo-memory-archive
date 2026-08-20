---
name: compose-photo-memory-archive
description: >
  Create editorial photo-memory archive diptychs from supplied photographs.
  Preserve the photograph unchanged and generate one complete watercolor
  companion panel containing its own title, three painted color swatches, and
  empty journaling lines. Use for photo memory archives, abstract photo
  posters, editorial memory artworks, and photo diptychs.
---

# Compose Photo Memory Archive

## Fixed visual contract

Create one quiet two-panel archive artifact.

- Landscape or square source: original photograph on top; companion panel below.
- Portrait source: original photograph on the left; companion panel on the right.
- Preserve the source photograph as the factual anchor. Copy its pixels
  unchanged, except for proportional resizing needed to match panel dimensions.
- Generate ONE complete companion panel with GPT Image 2.
- The companion panel must already contain its watercolor motif, handwritten
  title, exactly three painted swatches, and 2–4 empty journaling lines.
- Do not generate archive elements separately. Do not add them later with code,
  fixed layout coordinates, or a post-generation overlay.

The desired look is an airy, tactile watercolor page: perceptible source memory,
gentle paper ground, restrained archival cues, and no extra framing system.

## Workflow

1. Inspect the source and identify 3–6 source-specific memory anchors:
   defining subject, spatial rhythm, atmosphere, light, material, and palette.
2. Choose a concise English title of 2–5 words.
3. Generate only the companion panel, using the source image as visual memory
   and preserving its aspect ratio.
4. Regenerate if the source is copied too literally, required archive elements
   are missing, or the result looks like a generic poster template.
5. Resize the accepted companion proportionally to the exact source dimensions.
6. Stitch the untouched source and companion edge-to-edge.
7. Export the final composite and a reduced preview.

## Companion panel prompt

Use this structure with source-specific anchors and colors:

```text
Create ONE companion memory panel only, same aspect ratio as the referenced
[landscape/portrait/square] photo. Do not include the original photo. This is
for an editorial photo-memory archive diptych.

Core rule: 神似不完全形似. Preserve the memory anchors, but do not make a
direct watercolor copy of the photo. Important forms should be incomplete,
semi-transparent, reduced, slightly displaced, and poetic: recognizable in
spirit, not copied in full shape.

Keep one or two source-specific structural relationships perceptible, such as a
dominant silhouette, major directional axis, mass relationship, gesture, or
light pattern. Do not reproduce all detailed geometry.

Source memory anchors: [write 3–6 source-specific anchors]. In the companion
panel, [describe how the defining subject becomes a reduced watercolor trace
rather than a literal redraw].

Visual language: refined archival watercolor on lightly textured paper,
[source-derived wash/material/ink marks]. Primary motif about 42–48% of the
panel, total visible load about 60–68%, with 32–40% calm paper ground.

Archive elements must be integrated and clearly visible: exactly three small
irregular hand-applied watercolor swatches with soft uneven edges, grouped
together in quiet paper space, derived from [three source colors]. Add a
journaling area with 2–4 widely spaced low-contrast horizontal ruled lines and
no prose. Add one concise, legible handwritten English title exactly:
“[TITLE]”. Keep the title under 35% of panel width.

No dates, location note, subtitle, caption, tape, mockup, border frame, labels,
logos, watermark, or extra text.
```

## Never

- Alter, redraw, retouch, recolor, or regenerate the source photograph.
- Ask the model to create the original-photo panel or the complete diptych.
- Add titles, swatches, journaling lines, captions, margins, seams, shadows, or
  borders after the companion panel has been generated.
- Create a detail-for-detail watercolor duplicate of the photograph.
- Invent scenery, people, symbols, dates, place names, captions, logos, or
  watermarks.
- Use gradients, torn seams, page turns, tape, mockups, frames, drop shadows,
  or decorative separators.
- Let title, swatches, or journaling lines compete with the main motif.

## Acceptance check

Confirm at full size and thumbnail size:

- source photo pixels remain unchanged;
- panels have matching dimensions and a clean edge-to-edge join;
- the companion reads as one coherent watercolor page;
- one or two source structural relationships remain perceptible without a
  literal redraw;
- exactly three painted swatches, a small handwritten title, and empty writing
  lines are visibly integrated into the page;
- the final feels like a quiet editorial memory artifact, not a decorated photo
  or a rigid template.

Read `references/composition-system.md`,
`references/visual-language.md`, and `references/quality-check.md` when their
detail is needed.
