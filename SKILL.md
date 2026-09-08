---
name: paper-acrylic-photo-cover
description: Transform uploaded photographs into quiet, minimalist paper-textured acrylic cover illustrations, either as a standalone 4:3 landscape artwork or a strict 1:1 photo-and-illustration vertical poster. Use when the user asks for the established paper-acrylic, picture-book, independent-publication, poetic-poster, or “刚才那个画风” treatment.
---

# Paper Acrylic Photo Cover

Use the built-in image-generation workflow to derive an illustration from each uploaded photograph. Inspect every source image before prompting. Treat the photograph as the subject reference, not merely a loose mood reference.

## Choose the output mode

- **Standalone illustration:** use when the user asks for an illustration only or a horizontal banner. Default to landscape 4:3.
- **Photo + illustration poster:** use when the user asks to retain the original photograph or divide the image into two parts. Default to portrait 3:4, with a perfectly straight midpoint boundary and exactly 50% photograph above / 50% illustration below.
- Follow an explicitly requested aspect ratio or layout instead of these defaults.
- For multiple photos, create one independent output per photo. Never combine unrelated photos into a collage unless explicitly requested.

## Read the photograph before simplifying

Identify the smallest set of features that makes the moment recognizable:

1. Main subject and distinctive silhouette.
2. Specific pose, gesture, direction of movement or interaction.
3. Essential spatial relationship between the subject and one or two nearby objects.
4. Emotional tone of the moment.
5. Up to four source-derived colors.

Preserve unusual actions over generic appearance. For example, a cat balancing with paws on a chair arm should remain that action rather than becoming a generic sitting cat.

## Illustration art direction

- Place the complete illustrated subject cluster at roughly 10–20% of the total applicable illustration area. Keep generous uninterrupted negative space on every side.
- Use rough white, ivory or pale handmade paper with visible fibers and restrained grain.
- Build the subject with a few clear, complete acrylic or gouache flat-color blocks. Use thin, slightly unstable hand-drawn marks only to clarify structure.
- Simplify details aggressively while keeping the original subject immediately identifiable.
- Retain slight paint drag, dry-brush grain, tiny smudges and irregular pigment edges. The result must not look like smooth vector or glossy digital art.
- Use no more than four principal colors, sampled conceptually from the source. Paper color may act as one color or as negative space.
- Include at most one to three minimal environmental cues. Do not reconstruct the full room, street, landscape or background.
- Aim for a quiet picture-book cover, independent art publication, travel notebook or natural-observation page: gentle, airy, playful but not childish.

## Photo-region invariants

In photo + illustration mode:

- Keep the upper half recognizably photographic with natural light, realistic texture, original identity, pose, structure and color atmosphere.
- Allow subtle editorial color grading and natural crop/reframing only.
- Never repaint, stylize, stretch, distort, beautify, change anatomy or invent content in the photograph.
- If necessary, extend only unobtrusive background areas to fit the frame; never extend or deform the subject.

## Text and marks

Default to no added text, logos, captions, watermarks or symbols. Add small text only when the user explicitly asks for it, using exact supplied wording or clearly photo-grounded wording. Never reproduce incidental brand marks as decorative elements.

## Avoid

Avoid photographic rendering in the illustration, photo tracing, pure line art, outline-only drawings, crowded composition, oversized subjects, full backgrounds, more than four colors, complex perspective, dense shadows, fine cross-hatching, detailed fur, watercolor bleeding, colored-pencil or crayon texture, heavy oil paint, commercial cartoon styling, ecommerce styling, templates, 3D rendering, glossy digital finish, anime, chibi, exaggerated cuteness, AI-style decorative overworking, invented objects and anatomical errors.

## Execution and review

Use the image-generation skill and built-in image tool. State the source image's role and the chosen mode in the prompt. After generation, inspect the result for:

- requested aspect ratio and exact split geometry;
- preserved photographic invariants when applicable;
- recognizable gesture and spatial relationship;
- subject scale near 10–20%;
- large negative space;
- four colors or fewer;
- visible paper/acrylic hand-made texture;
- absence of unrequested text, logos and extra objects.

If one of these fails materially, make one targeted regeneration. Save the accepted image non-destructively and report its path.
