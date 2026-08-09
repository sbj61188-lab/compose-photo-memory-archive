---
name: compose-photo-memory-archive
description: >
  Create editorial archival artworks from user photographs. Preserve the
  original photograph as the factual anchor while generating a companion
  abstract memory field derived from the source image. Use for photo memory
  archive, abstract photo poster, archival stamp artwork, photo diptych,
  and related visual-memory compositions.
---

# Compose Photo Memory Archive

## Purpose

Transform each supplied photograph into one finished editorial archive
artwork. Preserve the original photograph faithfully and build a coordinated
companion field from the photograph's own spatial, tonal, and color
relationships.

## Core principle

The photograph is the factual anchor. The companion field is interpretive,
not a replacement for the photograph.

Preserve people, faces, bodies, hands, clothing, architecture, signs, numbers,
objects, relationships, lighting, and color memory. Permit only proportional
scaling and a restrained crop that does not damage the subject.

## Workflow

1. Inspect each source photograph independently.
2. Identify the subject, viewpoint, scene geometry, important text, object and
   person counts, dominant axes, visual weight, movement direction, negative
   space, tonal hierarchy, and source palette.
3. Choose 2–4 subject anchors that must remain legible in the companion field.
4. Build the fixed two-panel composition:
   - landscape: original photo on top, companion field below;
   - portrait: original photo on the left, companion field on the right;
   - square: default to original photo on top, companion field below.
5. Build an abstract memory motif from 3–6 source-specific spatial or tonal
   facts. Prefer relationships, rhythm, intervals, mass, axes, and negative
   space over literal tracing.
6. Derive one compact archival seal or micro-mark from the same source facts.
7. Add exactly three small source-derived color swatches:
   - representative dominant chromatic color;
   - dark structural color;
   - pale neutral or restrained accent.
8. Reserve a small, natural journaling area inside the quiet space.
9. Add one concise English title of 2–5 words. Add either a short poetic
   subtitle or a small archive caption only when it improves balance.
10. Review the finished raster at full size and as a thumbnail.
11. Regenerate only when a defect materially affects source fidelity, layout,
    balance, typography, or invented content.
    
## Output requirements

After the image generation step succeeds:

1. Return the actual generated image as the final user-visible image artifact.
2. Do not only describe the generated image in text.
3. Do not claim that the image is displayed unless the image artifact is actually attached or rendered in the final response.
4. If the image-generation tool returns a file or artifact path, preserve and return that artifact rather than discarding it.
5. If generation succeeds but the image artifact cannot be surfaced to the user, report the failure explicitly instead of pretending the image was displayed.
6. The final response should contain the generated image first, followed by a brief description only if useful.

## Integration rules

- Photo and companion panel must have matching dimensions and aspect ratio.
- Keep the main join straight, clean, and edge-to-edge.
- Use optical balance rather than mechanically centering every element.
- Keep approximately 55–80% quiet space in the companion field, adjusted to
  the source and format.
- Keep the seal secondary to the main motif.
- Keep the three swatches small and grouped.
- Added colors must be traceable to the source photograph.
- Do not use the saturated dominant source color unchanged as a full
  companion-field background.
- Keep one coherent surface treatment.
- Do not use gradients, dissolves, torn seams, page turns, shadows, tape,
  mockups, or decorative separators.
- Do not turn the companion field into a second fully illustrated copy of the
  photograph.

## Guardrails

Never:
- redraw, retouch, extend, stylize, recolor, or otherwise alter photographic
  content;
- invent scenery, subjects, symbols, decorative patterns, logos, labels,
  dates, or watermarks;
- move, merge, duplicate, invert, straighten, or exaggerate core subject
  counts, silhouettes, axes, tiering, spacing, or directional relationships;
- let typography, seal, and motif compete equally for attention.

## References

Read these only when the corresponding detail is needed:

- `references/composition-system.md`
- `references/visual-language.md`
- `references/quality-check.md`

## Output

Produce one flat finished composite per source photograph. The result should
read as a preserved visual-memory artifact rather than a decorated photo.
