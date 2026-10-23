---
name: xxd-panel-350
description: "Create XXD Panel 350 raster artwork: a faithful photograph paired with one Neon Spirit Overlay — the subject and only a small patch of its surroundings redrawn as a quiet, pale, carefully observed fine-ink line drawing, while the subject itself becomes a soft, chubby glowing spirit that keeps its silhouette, its body made of concentric rainbow halos airbrushed outward from a vivid core, with two tiny round eyes and a short line mouth, and a few smaller glowing spirits floating, peeking or sitting around it, linked by one coloured light arc or smoke ribbon, with one tiny hand-pencilled exhibition-label title in the lower-right corner. Accepts one image or a directory batch and supports top-bottom, left-right, design-only and four-device wallpaper outputs; multiple ratios or exact sizes; prompt-generated, user-exact or text-free typography. Use whenever the user invokes xxd-panel-350 or asks for this 霓虹精灵闯入线稿 style."
---

# XXD Panel 350

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design keeps only the subject and the small patch of surroundings right beside it, set centred slightly low with generous empty space and more headroom above than below, never touching the fold. The surroundings are a clean, accurate fine-liner drawing that follows the photograph's structure and perspective, washed with only the faintest near-warm-white tint of the photo's colours. The subject itself is no longer drawn with lines: it becomes the largest soft, rounded glowing spirit that still keeps its outline, its body built from concentric airbrushed halos — the innermost ring taken from the photograph's most vivid colour, then saturated pink, orange, yellow, green and blue rings with clear yet glowing boundaries — and a face of only two small round eyes and one short horizontal line mouth. A few smaller spirits of the same kind float, crouch or peek out from behind objects at different heights, joined by one coloured light arc or trail of smoke; they are the only saturated colour on the page. The single short title is tiny hand-written pencil in the lower-right corner, coloured like the pale line ink, with a gently absurd humour. Reject a full-scene copy, a filled background, spirits drawn with outlines like ordinary cartoon characters, a fully coloured drawing, a subject that loses its recognisable shape, sloppy line work, halos muddied into dirty colour, heavy black shadows, and spirits crowding the frame.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-350/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-350-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
