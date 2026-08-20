# Compose Photo Memory Archive

An open-source Codex skill for turning a photograph into a restrained editorial
photo-memory archive diptych.

## What it creates

Each result contains:

- one untouched original photograph;
- one source-derived watercolor companion panel;
- one concise handwritten English title;
- exactly three painted source-derived color swatches;
- 2–4 empty journaling lines.

The companion panel is generated as one complete image. The final step only
joins it edge-to-edge with the untouched photograph.

## Visual principle

The work follows “神似不完全形似”:

- preserve the source’s atmosphere, light, rhythm, color, and subject memory;
- keep one or two recognizable structural relationships;
- avoid a detail-for-detail watercolor copy;
- avoid reducing the source into unrelated generic atmosphere.

The result should feel like a preserved visual-memory artifact rather than a
decorated photograph.

## Non-negotiable rules

- Never redraw, retouch, recolor, or regenerate the source photograph.
- Generate only the companion panel; never ask the image model for the full
  diptych.
- Generate the motif, title, swatches, and journaling lines together in that
  companion panel.
- Do not add archive elements later with a compositor or layout overlay.
- Do not add captions, subtitles, dates, location labels, seals, logos, frames,
  tape, shadows, or watermarks.

## Panel layout

| Source orientation | Final layout |
| --- | --- |
| Landscape | Original on top, companion below |
| Portrait | Original on left, companion on right |
| Square | Original on top, companion below |

## Repository structure

```text
compose-photo-memory-archive/
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── composition-system.md
    ├── visual-language.md
    └── quality-check.md
```

## License

Released under the [MIT License](LICENSE).
