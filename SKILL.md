---
name: wuxian-cute-painterly
description: "Generate batches of cute, rough-edged digital illustrations with geometric color blocks, expressive characters, tactile dry-brush texture, and saturated graphic backgrounds. Use when the user asks for the 无线搞可爱风 or this specific painterly mascot style."
---

# 无线搞可爱风绘图

Use this skill when creating a new illustration or a batch of illustrations in the visual language distilled from the user's reference set. The target is a reusable style system, not a copy of any one source image.

## Style target

- Build the subject from simplified, chunky, slightly geometric shapes rather than polished realism.
- Use broad, mostly flat color blocks with only a few overlapping shadow/highlight shapes. Keep the value range compact and the contrast softer than a comic poster.
- Match the supplied references' modest, slightly softened saturation. Use a single calm background field and let the character carry the color contrast; do not force neon purple, pure black, or dramatic complementary lighting unless requested.
- Keep edges visibly handmade: dry-brush, wax-crayon, chalky digital paint, soft grain, and small irregularities are desirable. The texture should feel like a lightly rough digital drawing, not a splattered paint effect.
- Prefer dark plum, brown, blue-gray, or a darker local color for structure; avoid thick, uniform black contour lines and glossy rim lights.
- Push character appeal through large eyes, simple facial marks, compact or deliberately awkward proportions, and an expressive pose.
- Pair a restrained single-color field with one centered focal subject. Add only a few quiet supporting props, clouds, stars, motifs, or a grounding shadow. Avoid large brush arcs, comic speed lines, paint splashes, or busy decorative framing unless the user asks for them.
- Keep the image playful, cute, and a little strange or clumsy; avoid generic glossy mascot rendering.

## Reference calibration

When the user provides a reference folder, inspect several representative images together and prioritize their shared visual grammar over generic words such as “cute,” “cartoon,” or “painterly.” The target should read as a simple hand-painted character illustration from the same small series:

- one main character or a compact pair, large and readable in the square frame;
- flat or gently layered fills, with visible but controlled paper/brush grain;
- wobbly, imperfect silhouettes and block boundaries rather than smooth vector geometry;
- low-to-medium saturation with palette families that can shift between purple, blue, teal, lime, tan, pink, and cream;
- a mostly plain background, sometimes with a faint repeated motif, not a cinematic scene;
- minimal facial marks and props, with no unnecessary typography.

Use 3–5 representative folder images as style references when the generation tool allows multiple references. Treat any watermarks, account labels, logos, or repeated stock marks as contamination to ignore.

Read [references/style-bible.md](references/style-bible.md) when choosing palettes, composition, texture, or negative constraints.

## Batch workflow

1. Parse the request into: subject, action or mood, number of images, aspect ratio, background preference, and any required text.
2. Choose one visual family for the batch (cool purple/teal, cobalt/ice, lime/navy, coral/cream, or another restrained family). Vary the subject and pose more than the rendering language.
3. Write a compact scene brief before generating: focal subject, silhouette, expression, dominant palette, secondary accent, background motif, and crop.
4. Apply the style target consistently across all images. Preserve the same edge texture, block-shape logic, eye language, and contrast pattern while changing the requested subject.
5. If the user asks for a set, keep a shared palette family and background treatment, but alternate pose, camera crop, prop, and accent color so the outputs do not look duplicated.
6. Review each result for silhouette readability at thumbnail size, coherent color grouping, visible handmade texture, and absence of accidental typography or platform marks. Revise prompts when a result becomes photorealistic, overly smooth, overly detailed, or anime-polished.
7. Perform a limb-consistency check on every character before accepting the result: count the visible arms, hands, legs, feet, eyes, and major appendages against the requested pose. Reject and regenerate any image with duplicated limbs (for example, two pairs of hands), extra fingers, fused hands, detached or ghost limbs, mirrored appendages, or anatomy that cannot be explained by the pose.

## Prompt construction

Use this order when composing an image prompt:

`[subject and action] + [chunky geometric silhouette] + [facial expression] + [restrained palette family] + [flat color-block shading] + [controlled dry-brush / waxy grain texture] + [simple square composition] + [quiet background treatment] + [style exclusions]`

Keep the subject-specific content in the first clause and the style constraints in the remaining clauses. If text is requested, treat it as a separate layout requirement and keep it short; otherwise instruct the generator to omit text.

## Fixed exclusions

Do not treat watermarks, platform logos, usernames, account IDs, stock marks, repeated diagonal marks, or source-image labels as design elements. Ignore them during style analysis and do not reproduce or add them. Also avoid photorealism, 3D plastic, glossy toy rendering, heavy black outlines, neon highlights, airbrushed gradients, dramatic rim lighting, splattered paint, huge comic motion marks, glossy vector-clean edges, excessive micro-detail, thin technical line art, realistic anatomy, duplicated arms or hands, extra fingers, fused or detached limbs, ghost appendages, accidental mirrored limbs, and busy backgrounds that compete with the subject.

## Output behavior

When the user gives only a subject, infer a simple cute pose and choose a palette family from the style bible. When the user gives a reference image, use it for subject/content guidance while translating it into this style; do not preserve source watermarks or unrelated typography. When the user requests multiple images, return a consistent batch plan and generate or describe each variation separately.
