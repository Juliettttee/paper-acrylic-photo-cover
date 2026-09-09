---
name: paper-acrylic-photo-cover
description: Transform uploaded photographs into quiet, minimalist paper-textured acrylic cover illustrations with fuller matte color blocks, either as a standalone 4:3 landscape artwork or a strict 50/50 upper-photo and lower-illustration 3:4 vertical poster.
---

# Paper Acrylic Photo Cover

Use the built-in image-generation workflow to transform uploaded photographs into the established paper-acrylic cover style.

This is the original, fuller and more solid version. Do not apply the pale, broken, highly exposed-paper treatment of the separate `airy-paper-acrylic-cover` skill.

## Choose the output mode

- **Photo + illustration poster:** Default mode when the user does not specify a layout. Use portrait 3:4 with a perfectly straight midpoint boundary: exactly 50% original photograph above and 50% illustration below.
- **Standalone illustration:** Use only when the user explicitly asks for an illustration without the original photograph, a horizontal banner, or “不用上下对比”. Default to landscape 4:3.
- Follow any explicitly requested aspect ratio or layout.
- For multiple photographs, create one independent output for each photograph. Do not combine unrelated photographs into a collage unless explicitly requested.

## Read the photograph

Inspect every source photograph before generating.

Identify and preserve:

1. The principal subject and recognizable silhouette.
2. The exact pose, gesture, action or direction of movement.
3. The relationship between the subject and essential nearby objects.
4. Important architectural or environmental forms required to recognize the scene.
5. The emotional atmosphere.
6. No more than four principal colors derived from the photograph.

Preserve distinctive actions instead of converting the subject into a generic pose.

## Original acrylic art direction

- Keep the illustrated subject cluster relatively small, normally around 10–20% of the applicable illustration area.
- Surround it with generous negative space.
- Use warm-white, ivory or lightly textured handmade paper.
- Build the subject with clear, matte and substantially filled acrylic or gouache color blocks.
- Colors should be restrained and harmonious but must remain visible, complete and sufficiently solid.
- Use slightly stronger color density and contrast than the airy version.
- Keep the paper texture visible mainly in the background, along painted edges and through subtle dry-brush marks.
- Do not allow excessive blank paper to break through the principal subject.
- Use thin, slightly unstable hand-drawn lines only to clarify important structure.
- Preserve subtle paint drag, uneven pigment density, irregular edges and handmade imperfections.
- Avoid glossy digital rendering and perfectly smooth vector shapes.
- Use no more than four principal colors extracted conceptually from the source photograph.
- Simplify details while keeping the original theme immediately recognizable.

The result should resemble a quiet picture-book cover, an independent art publication, a poetic paper poster or a travel notebook illustration.

It should remain gentle and restrained, but fuller, more graphic and more materially painted than the airy edition.

## Environment and architecture

Use only the environmental information required to recognize the original scene.

Do not reconstruct every background detail. However, do not impose a fixed limit on environmental elements when an important building, staircase, chair, vehicle, umbrella, tree or room structure is essential to the scene.

Preserve enough of an important building or spatial structure to communicate:

- Its main massing and silhouette.
- Its relationship with the subject.
- The direction of stairs, walls, windows or balconies.
- The original viewing angle.
- The emotional atmosphere of the location.

Simplify these elements into controlled flat shapes and loose structural lines rather than removing them completely.

## People and faces

Preserve the person’s pose, gesture, clothing silhouette, hairstyle and relationship with the environment.

Faces must remain highly simplified. When facial features are visible, use only:

- Two dots or short marks for the eyes.
- One tiny line or mark for the nose.
- One short line for the mouth.

Do not generate realistic portrait details, detailed eyes, skin texture or carefully rendered facial anatomy.

## Animals

Preserve the animal’s:

- Species and characteristic silhouette.
- Body posture.
- Essential markings.
- Ear and tail shape.
- Expression or direction of attention.
- Interaction with nearby people or objects.

Use complete matte color shapes rather than realistic fur rendering.

## Photo-region invariants

In photo + illustration mode:

- Keep the upper half as the uploaded original photograph.
- Preserve its photographic realism, natural light, identity, pose, color atmosphere and complete composition.
- Fit the complete photograph into the upper half whenever possible.
- If the aspect ratio does not match, use restrained neutral padding or unobtrusive background extension instead of cropping the main subject.
- Never repaint, stylize, beautify, stretch, distort or change the anatomy of the photographic subject.
- Do not invent objects or people in the photograph.
- The boundary between the two halves must be perfectly straight and positioned at the exact vertical midpoint.

## Text and logos

Do not add any text, title, date, location, caption, logo, watermark or symbol that is not already present in the source photograph.

Preserve existing text or a recognizable logo only when it is essential to the original subject or the user explicitly requests it.

## Avoid

Avoid:

- Pale, washed-out or nearly invisible subjects.
- Excessively broken pigment inside the main subject.
- Excessive exposed paper passing through the subject.
- The highly airy treatment belonging to `airy-paper-acrylic-cover`.
- Photorealistic rendering in the illustration.
- Direct photo tracing.
- Pure line art or outline-only drawings.
- Oversized subjects.
- Crowded compositions.
- Full realistic backgrounds.
- More than four principal colors.
- Complex perspective details.
- Dense shadows or fine cross-hatching.
- Detailed fur or realistic skin.
- Watercolor bleeding.
- Colored-pencil or crayon texture.
- Heavy oil-paint impasto.
- Commercial cartoon or ecommerce styling.
- Anime or chibi styling.
- 3D rendering.
- Glossy digital finishes.
- Smooth vector illustration.
- Excessive cuteness.
- Invented objects, text or logos.
- AI-style decorative overworking.

## Execution and review

Use the image-generation workflow and state the selected output mode clearly in the generation prompt.

After generation, verify:

- Correct requested aspect ratio.
- Exact 50/50 division when using poster mode.
- Original photograph preserved in the upper half.
- Recognizable subject, action and spatial relationship.
- Important architecture or objects retained when required.
- Simplified facial features.
- Illustrated subject scale near 10–20%.
- Generous negative space.
- Four principal colors or fewer.
- Fuller matte acrylic color blocks.
- Visible paper and handmade texture.
- No unrequested text, logos or invented objects.

If a major requirement fails, perform one targeted regeneration.
