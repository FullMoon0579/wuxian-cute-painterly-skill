# 无线搞可爱风：Style Bible

This reference describes the stable visual rules observed across the supplied sample set. It is a guide for decisions, not a rigid checklist.

## Shape language

- Use large, readable silhouettes assembled from rounded blobs, blunt wedges, triangles, stepped tufts, leaf-like ears, oversized paws, and simple costume panels.
- Mix rounded masses with a few sharp graphic points. The tension between soft and angular shapes creates the playful character.
- Let proportions be intentionally compressed or slightly off: large head/eyes, compact torso, short limbs, oversized accessories, or a pose that feels a little stiff.
- Simplify anatomy and objects until they read as icons or toy-like cut-paper forms.
- Use overlap and block boundaries to imply depth instead of detailed modeling.

## Face and expression

- Eyes are usually the strongest anchor: oversized ovals, simple dark pupils, colored irises, sleepy half-lids, star/cross highlights, or tiny graphic marks.
- Keep noses and mouths minimal. A tiny wedge, dot, curved stroke, or small open shape is enough.
- Favor clear emotional shorthand: blankly cute, sleepy, smug, startled, earnest, or mildly awkward.
- Avoid intricate facial rendering and avoid realistic eye anatomy.

## Color system

Use a limited family of approximately 4–8 dominant colors, with one dark anchor and one light/highlight color. Useful families include:

- Violet family: muted lavender, saturated purple, deep plum, turquoise/cyan accents, creamy white.
- Cobalt family: vivid blue, ice blue, navy, pale blue-gray, cream, occasional yellow or coral.
- Lime family: acid lime or spring green, navy/blue-gray, cream, muted brown, small pink or yellow accents.
- Teal family: turquoise/green background, warm tan or ochre body, chocolate-brown shadow, cream highlights.
- Candy family: pink, coral, peach, lilac, cream, and a dark berry or navy anchor.

Colors can be vivid, but they should feel slightly softened by grain. Prefer colored shadows over black. Keep the background high-contrast enough that the silhouette reads immediately.

## Rendering and texture

- Simulate a simple handmade digital painting with dry brush, wax crayon, chalk, gouache-like opacity, and subtle paper or canvas grain.
- Use imperfect fills and slightly fuzzy or broken edges. Small overlaps, uneven corners, and visible brush drag are part of the charm.
- Shade with one or two broad neighboring shapes rather than smooth airbrush gradients. Highlights are usually opaque pale shapes, not glossy specular reflections.
- Keep texture subordinate to the silhouette: grain should enrich flat areas, not become splattered paint, heavy noise, or a dramatic poster effect.
- The supplied set is flatter and quieter than a polished comic illustration: avoid thick ink contours, neon edge light, 3D volume, and high-frequency detail.

## Composition

- Default to a square, centered character illustration with a generous but not empty field around the subject.
- Use close crops for expressive portraits and full-body or three-quarter views for costume/prop storytelling.
- A simple grounding shadow, platform, branch, cloud, or color shape can stabilize the subject.
- Backgrounds may include sparse clouds, stars, repeated diamonds, dots, or faint motifs, but should remain secondary and low-detail. Prefer a single-color field or a lightly textured field over large paint swashes or cinematic gradients.
- Keep the main silhouette legible at thumbnail size. One strong focal subject is preferable to a crowded scene unless the user explicitly requests a group.

## Anatomy integrity gate

The cute, simplified construction must not be used as an excuse for broken anatomy. Before accepting an output, verify that every visible appendage belongs to a clear body part and that the count matches the pose:

- no duplicate arms, hands, legs, feet, eyes, ears, tails, or repeated accessories;
- no example of two pairs of hands where only one pair is intended;
- no extra fingers, fused fingers, detached hands, floating limbs, or ghosted limb fragments;
- no mirrored appendage accidentally emerging from the torso or behind an existing limb;
- hidden limbs must remain hidden or be placed consistently with the pose, not reappear as unexplained fragments;
- if a pose is complex, simplify the gesture and overlap fewer limbs rather than risking ambiguity.

For batch outputs, inspect each panel separately at a larger scale. Regenerate any panel that fails this gate, even if its color and texture match the style.

## Controlled variation for batches

Keep these stable across a batch:

- edge roughness and brush texture;
- approximate palette family and contrast ratio;
- eye and face shorthand;
- flat-block shading logic;
- background simplicity and graphic treatment.

Vary these between images:

- pose, expression, crop, prop, silhouette accent, secondary color, and background motif.

Do not vary all of them at once. A batch should feel like one illustrated series.

## Negative prompt cues

Use only the exclusions relevant to the request, but usually include: photorealistic, 3D render, glossy plastic, smooth airbrush, heavy black outline, clean vector polish, neon rim light, dramatic gradient, splattered paint, giant motion lines, cinematic realism, duplicated limbs, extra arms, extra hands, extra fingers, fused hands, detached limbs, ghost appendages, mirrored limbs, malformed anatomy, detailed background, excessive tiny details, random text, watermark, logo, username, platform badge, stock mark.
