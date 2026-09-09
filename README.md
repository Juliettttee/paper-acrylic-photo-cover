# Paper Acrylic Photo Cover

A reusable photo-to-illustration skill for ChatGPT and Codex.

It transforms uploaded photographs into quiet, minimalist paper-textured acrylic cover illustrations with clear matte color blocks, handmade edges, restrained details, and generous negative space.

This is the original, fuller paper-acrylic edition. For a paler treatment with more exposed paper and broken pigment, use the separate `airy-paper-acrylic-cover` skill.

## Features

* Minimalist paper-acrylic illustration
* Fuller and more clearly defined matte color blocks
* Visible handmade paper texture
* Thin, slightly unstable hand-drawn lines
* Generous negative space
* Small illustrated subject occupying approximately 10–20% of the illustration area
* No more than four principal colors extracted from the source photograph
* Simplified but recognizable people, animals, objects, and architecture
* Support for standalone illustrations and photo-and-illustration posters
* No invented text, logos, objects, or decorative elements

## Visual Style

The final artwork should resemble:

* A quiet picture-book cover
* An independent art publication
* A poetic paper poster
* A travel-journal illustration
* A natural-observation notebook
* A handmade acrylic or gouache study

The illustration should remain simple, gentle, restrained, and poetic while maintaining fuller color coverage and stronger visual definition than the airy edition.

The subject should look physically painted on paper rather than digitally rendered.

## Available Modes

### 1. Photo and Illustration Poster

This is the default mode when the user does not specify a layout.

* Portrait format: `3:4`
* Divide the canvas into two strictly equal sections
* The upper photograph occupies exactly 50% of the canvas
* The lower illustration occupies exactly 50% of the canvas
* Use a perfectly straight horizontal midpoint boundary
* Preserve the uploaded original photograph in the upper half
* Create the paper-acrylic interpretation in the lower half
* Do not blend the photograph and illustration together

### 2. Standalone Illustration

Use this mode when the user explicitly requests:

* An illustration without the original photograph
* A horizontal banner
* A standalone cover
* “不用上下对比”
* “只要插画”

The default standalone format is landscape `4:3`.

Do not include the original photograph or create an upper-and-lower comparison layout.

## Composition Rules

Inspect the uploaded photograph before generating.

Preserve the smallest set of visual information required to recognize the original moment:

* Main subject
* Recognizable silhouette
* Exact pose, action or gesture
* Direction of movement
* Relationship between important subjects and objects
* Essential architecture or environmental structure
* Emotional atmosphere
* No more than four principal colors

Do not reproduce every detail from the photograph.

Simplify the scene into one coherent illustrated cluster while preserving the elements that make the original image distinctive.

The illustrated subject should normally occupy approximately 10–20% of the available illustration area, surrounded by generous negative space.

## Original Acrylic Treatment

Build the illustration with:

* Clear matte acrylic or gouache color blocks
* Substantially filled principal shapes
* Restrained but visible colors
* Slightly stronger pigment density than the airy edition
* Thin and imperfect structural lines
* Subtle dry-brush marks
* Irregular painted edges
* Minor pigment variation
* Light handmade imperfections

The paper texture should remain visible in the background, around painted edges and through subtle brush marks.

Do not allow excessive blank paper to pass through the main subject. The subject should remain visually complete and clearly defined.

Avoid making the result pale, washed out, translucent or nearly invisible.

## Environment and Architecture

Include only the environmental information needed to recognize the original scene.

Important architecture or objects may include:

* Buildings
* Balconies
* Windows
* Staircases
* Chairs
* Vehicles
* Umbrellas
* Trees
* Walls
* Interior structures

Do not reconstruct every background detail. However, preserve enough of an important structure to communicate its main shape, viewing angle and relationship with the subject.

Do not remove an essential building or object merely to increase negative space.

Simplify it into controlled flat shapes and loose structural lines.

## People and Faces

Preserve:

* Pose
* Gesture
* Clothing silhouette
* Hairstyle
* Direction of attention
* Relationship with the environment

When facial features are visible, simplify them to:

* Two dots or short marks for the eyes
* One tiny line or mark for the nose
* One short line for the mouth

Do not create realistic portrait details, detailed eyes, skin texture or carefully rendered facial anatomy.

## Animals

Preserve the animal’s:

* Species
* Characteristic silhouette
* Body posture
* Essential markings
* Ear shape
* Tail shape
* Expression
* Direction of attention
* Interaction with people or objects

Use complete matte color shapes rather than realistic fur rendering.

## Color Rules

Use no more than four principal colors extracted from the source photograph.

Colors should be:

* Harmonious
* Restrained
* Soft but clearly visible
* Matte
* Moderately filled
* Strong enough to define the subject
* Appropriate to the original atmosphere

Paper white may function as part of the composition, but it should not dissolve or fragment the main subject.

Avoid complex gradients, excessive transparency and weak near-white coloring.

## Paper and Paint Texture

Preserve a handmade appearance through:

* Visible paper fibers
* Natural paper grain
* Slight paint drag
* Subtle dry-brush texture
* Uneven pigment density
* Irregular painted edges
* Small imperfections in the linework
* Slightly misaligned color and outline

The result must not look like a polished vector illustration or glossy digital painting.

## Photo Preservation Rules

In photo-and-illustration mode:

* Keep the upper half as the uploaded original photograph
* Preserve photographic realism
* Preserve natural lighting
* Preserve the subject’s identity and anatomy
* Preserve the original pose and spatial structure
* Preserve the complete composition whenever possible
* Do not repaint, stylize, beautify or reconstruct the photograph
* Do not stretch or distort the photograph
* Do not invent people, objects or background content

If the photograph does not match the required upper-half aspect ratio, use restrained neutral padding or unobtrusive background extension rather than cropping or distorting the principal subject.

## Text and Logo Rules

Do not add any new:

* Text
* Title
* Date
* Location
* Caption
* Logo
* Watermark
* Symbol
* Decorative mark

Preserve existing text or a recognizable logo only when it is essential to the original subject or explicitly requested by the user.

## Avoid

* The pale, broken treatment of the airy edition
* Excessively exposed paper inside the main subject
* Nearly invisible or washed-out colors
* Photorealistic illustration
* Direct photo tracing
* Pure line art
* Outline-only drawings
* Oversized subjects
* Crowded compositions
* Complete realistic backgrounds
* More than four principal colors
* Complex perspective details
* Dense shadows
* Fine cross-hatching
* Detailed fur
* Realistic skin texture
* Watercolor bleeding
* Colored-pencil texture
* Crayon texture
* Heavy oil-paint impasto
* Smooth vector illustration
* Glossy digital painting
* 3D rendering
* Commercial cartoon styling
* E-commerce styling
* Anime or chibi styling
* Excessive cuteness
* Decorative AI-style detail accumulation
* Invented objects, text or logos

## Installation

GitHub repository:

```text
https://github.com/Juliettttee/paper-acrylic-photo-cover
```

To install it in ChatGPT or Codex, start a new conversation and paste:

```text
$skill-installer Install the skill from this GitHub repository:
https://github.com/Juliettttee/paper-acrylic-photo-cover
```

Do not enter only `$skill-installer`. Include the complete installation request and repository URL.

After installation, start a new conversation or restart Codex if the skill does not appear immediately.

## Usage

Upload a photograph and call the skill by name.

### Default photo-and-illustration poster

```text
$paper-acrylic-photo-cover

Create the default 3:4 poster with a strict 50/50 split. Preserve the original photograph in the upper half and create the fuller paper-acrylic illustration in the lower half.
```

### Standalone illustration

```text
$paper-acrylic-photo-cover

Create a standalone 4:3 paper-acrylic illustration. Do not include the original photograph or create an upper-and-lower comparison layout.
```

### Preserve important architecture

```text
$paper-acrylic-photo-cover

Create a standalone 4:3 illustration. Preserve more of the building structure and its relationship with the figures, but simplify unnecessary architectural details.
```

### Simplify facial features

```text
$paper-acrylic-photo-cover

Preserve the people’s poses and recognizable silhouettes. Simplify their faces to dot eyes and minimal nose and mouth lines.
```

### Preserve an important object

```text
$paper-acrylic-photo-cover

Keep the complete umbrella because it is essential to the relationship between the cat and the surrounding space.
```

## Suggested Prompt

```text
Based on the uploaded photograph, create a minimalist paper-textured acrylic cover illustration.

Do not directly copy or trace the photograph. Extract the most recognizable subject, action, silhouette, spatial relationship, essential environmental structure and emotional atmosphere.

Keep the illustrated subject cluster relatively small, occupying approximately 10–20% of the illustration area, with generous negative space around it.

Use no more than four principal colors extracted from the source photograph. Build the subject with clear, substantially filled, matte acrylic or gouache color blocks. Use thin, slightly unstable hand-drawn lines only to clarify important structure.

Preserve visible handmade paper texture, subtle dry-brush marks, slight paint drag, uneven pigment density and irregular painted edges. The principal subject should remain complete, visible and clearly defined.

Preserve important architecture or objects when they are essential to recognizing the scene. Simplify them without removing their main form or relationship with the subject.

Simplify visible facial features to dot eyes and minimal nose and mouth lines.

Do not add any text, logo, title, caption, watermark, object or decorative element that is not present in the source photograph.

The final artwork should resemble a quiet picture-book cover, an independent publication, a poetic paper poster or a travel-journal illustration.
```

## Repository Structure

```text
paper-acrylic-photo-cover/
├── SKILL.md
├── README.md
└── agents/
    └── openai.yaml
```

## Recommended GitHub Topics

```text
codex-skill
chatgpt-skill
image-generation
image-editing
photo-to-illustration
paper-texture
acrylic-illustration
gouache-illustration
minimalist-art
picture-book
negative-space
cover-art
ai-art
```

## Lighter Alternative

For a paler, softer and more breathable interpretation with broken pigment and more exposed paper, see:

```text
https://github.com/Juliettttee/airy-paper-acrylic-cover
```
