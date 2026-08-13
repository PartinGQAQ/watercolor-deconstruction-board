---
name: watercolor-deconstruction-board
description: Convert a supplied photo or illustration into an easy-to-paint, highly simplified watercolor study board with broad color shapes, lightly cartoonized people, a small set of complete standalone scene elements, and visual mixing recipes that show how base pigments produce the colors used in the painting. Standalone elements may be primary subjects or secondary but complete objects such as a whole tree, building, vehicle, lamp, flower cluster, or piece of furniture. Use when the user asks to turn an image into simple or cartoon watercolor, make a reference easier to draw or copy, reduce it to broad color blocks, isolate complete scene elements, extract its palette, explain watercolor color mixing, or create a watercolor decomposition, study, reference, or teaching sheet.
---

# Watercolor Deconstruction Board

Create one coherent watercolor study board from the user's reference image. Make every element easy for a beginner or casual painter to reproduce. Favor simple silhouettes, broad luminous washes, lightly cartoonized forms, and useful color-mixing relationships over realism, detail, or decoration. Default to fresh, water-rich color rather than dense, highly saturated paint.

Use this priority order whenever requirements compete:

1. Easy to draw and paint
2. Simple, attractive shape language
3. Recognizable pose, object category, and key visual cues
4. Exact anatomy, facial likeness, texture, and minor detail

## Workflow

1. Inspect the reference image before generating.
2. Identify the complete scene, 1–3 semantically and visually complete standalone elements, 4–6 target colors, and the smallest plausible set of base pigments needed to mix them.
3. Write a simplification plan before prompting: choose no more than four recognition anchors for the complete painting, define the large color masses, and list everything else for deletion or merging.
4. Treat the supplied image as the edit target or sole content reference. Use the image generation tool in edit mode and preserve recognizable content and relationships.
5. Compose one board containing:
   - a simplified complete watercolor painting in the upper-left or center;
   - a small number of complete standalone scene-element studies along the bottom;
   - a color-mixing recipe panel on the right.
6. Inspect the result. Regenerate if secondary details compete with the silhouette, repeated structures are individually rendered, a bottom study is only a color region or arbitrary fragment, an element lacks a coherent whole silhouette, the studies overlap, or the right panel reads as an ordinary palette instead of mixing recipes.

## Simplify Aggressively

Translate the reference into 4–7 dominant shapes or visual layers. Use large, continuous color masses with calm edges.

- Preserve the subject category, count, placement, pose, and essential spatial relationships. Preserve only the few identity cues needed for recognition; do not pursue portrait-level likeness by default.
- Merge minor textures, repeated details, tiny shadows, and background noise into larger shapes.
- Use only 1–2 transparent washes per major shape.
- Let one large color family dominate the painting. Reserve accent colors for focal features.
- Keep approximately 70% broad flat or gently graded washes, 20% soft overlaps, and no more than 10% fine accents.
- Retain watercolor transparency, paper grain, slight pigment pooling, and a few natural blooms without fragmenting a shape.
- Use hard or soft edges intentionally. Do not fill large areas with many small brush marks.
- Omit decorative additions not present in the reference.

## Keep the Watercolor Luminous

Control pigment strength independently from structural detail. A scene may contain useful form and depth without becoming dark, saturated, or opaque.

- Default to water-rich, low-to-medium chroma washes. Let the warm paper color remain visible through every large colored region.
- Leave approximately 25–35% of the main painting as untouched or nearly untouched paper, including breathing gaps, light-facing planes, and soft transitions.
- Keep approximately 70% of painted area in pale-to-middle values, 20–25% in middle-dark values, and no more than 5–10% in concentrated dark accents.
- Limit the darkest value to small focal anchors and contact shadows. Never fill an entire tree crown, garment, mountain wall, building face, or background zone with near-black paint.
- Build depth primarily through value temperature, dilution, soft overlap, and edge control—not through uniformly stronger saturation.
- Neutralize intense source colors with water and a small amount of their complement or earth color when needed. Preserve hue identity while reducing digital-looking saturation.
- Use one pale first wash per major shape and at most one selective reinforcing pass. Keep the second pass smaller than the first; do not glaze the entire shape again.
- Reserve fully saturated accent color for one or two small focal elements. Even these accents must show paper grain and slight value variation.
- Keep shadows colored and transparent. Prefer diluted blue-gray, violet-gray, green-gray, or warm neutral mixtures over opaque black or muddy charcoal.
- Paint foliage and dark hair as connected translucent mid-dark families with a few concentrated accents, not as solid black silhouettes.
- Make palette and recipe swatches look like real watercolor tests: translucent edges, visible paper, a pale diluted stage, and a final swatch no denser than the corresponding painted area.

Reject results that resemble marker fill, flat digital cel color, opaque gouache, poster paint, oil paint, or heavily inked illustration. If a generated result is too vivid, regenerate by reducing pigment load and dark-area coverage while preserving the same structure and detail count.

Treat the reference as source material, not as a checklist. Recognition must come from the outer silhouette, dominant color planes, spatial arrangement, and at most four high-value anchors. Do not preserve a feature merely because it is visible.

Use three information levels:

1. **Level 1 — always keep:** outer silhouette, dominant color masses, overall pose or perspective, and large spatial relationships.
2. **Level 2 — ration carefully:** choose at most four recognition anchors for the complete painting, such as glasses, a hand gesture, and one clothing cue for a person, or roof angle, arch rhythm, and one opening for a building.
3. **Level 3 — delete or merge:** repeated units, surface texture, minor fixtures, thin lines, small gaps, trim, hardware, tiny highlights, and local shadows.

Limit the complete painting to roughly 10–16 deliberate internal marks beyond the large color masses. A repeated system counts as one visual idea and may use at most 3–5 representative marks; never draw every window, baluster, brick, leaf cluster, cloud puff, cable, fold, or hair strand. Omit any nonessential feature smaller than roughly 2% of the main painting's width. Do not compensate for omitted detail with dense outlines.

When writing the generation prompt, positively name only the Level 1 forms and selected Level 2 anchors. Put Level 3 features into one concise deletion sentence. Never enumerate numerous small reference details in the positive preservation instructions because naming them encourages the model to render them.

Avoid photorealism, dense texture, individually rendered small objects, excessive mountain facets, tiny repeated strokes, complex linework, opaque gouache, heavy impasto, anime rendering, 3D rendering, and ornamental collage styling.

### Subject-specific abstraction

- **Architecture:** Keep the building silhouette, 2–5 main color planes, perspective direction, and at most four architectural anchors. Represent repeated windows, arches, columns, or railings with 3–5 simplified marks total, not full rows. Delete bricks, balusters, panel seams, trim repetitions, small fixtures, cables, vents, and hardware unless one is the chosen isolated element.
- **Trees and plants:** Keep one connected crown or plant silhouette, a trunk or stem when needed, and at most three tonal variations. Allow 3–5 broad cluster or branch gestures when they materially clarify the species or shape. Delete individual leaves, small internal holes, twigs, veins, and repeated petals.
- **Clouds and terrain:** Keep the outer contour and 2–4 broad shadow regions. Delete tiny scallops, wisps, facets, and repeated texture.
- **Objects, food, and vehicles:** Keep the outer silhouette, 2–5 main color planes, and at most four category-defining features. Allow a few broad divisions that explain grouped contents or construction. Delete seams, controls, fasteners, granular toppings, reflections, and minor attachments.

## Simplify People for Easy Painting

Render people as charming, lightly cartoonized watercolor characters unless the user explicitly asks for realistic portrait likeness. Make the figure easy to redraw from a few shapes.

- Use a clean rounded or gently angular head shape, a simple neck, one torso mass, simple tapered limb shapes, and one or two large clothing masses.
- Allow mild cartoon proportion, such as a slightly larger head and cleaner, shorter limb geometry. Keep the original overall pose and body direction.
- Reduce the face to 3–5 marks: simple brows or eyes, a minimal nose indication, and a short mouth mark. Omit pores, eyelids, detailed nostrils, teeth, and modeled facial planes.
- Preserve only high-value recognition cues such as hairstyle silhouette, glasses, hat, dominant clothing shape and color, one important accessory, and the action being performed.
- Merge fingers into mitten-like or single contour hand shapes. Show individual fingers only when essential to understanding the action.
- Merge garment folds, seams, fabric texture, jewelry detail, shoe construction, and small logos into broad shapes. Keep at most 1–3 decisive fold or edge lines.
- Use flat or gently graded skin and clothing washes with minimal shading. Avoid anatomical modeling and realistic skin rendering.
- Keep facial features and outlines sparse enough that a beginner could copy the character without portrait-drawing skills.
- Apply the same simplified character design consistently in the main painting and any isolated subject study.

Do not make the person photorealistic, semi-realistic, anatomically intricate, fashion-illustration detailed, chibi, exaggerated comic, or anime unless the user explicitly requests that variant. Default to gentle editorial cartoon watercolor: recognizable, tasteful, and simple.

## Isolate Complete Scene Elements

Place 1–3 complete standalone element studies along the bottom. These elements do not need to be the main subject. A secondary scene object is valid when it forms a coherent, independently recognizable whole. Prefer fewer convincing elements over a full row of forced fragments; one element is acceptable.

Apply both tests before including an element:

1. **Semantic test:** If removed from the scene, can it still be named as one thing?
2. **Completeness test:** Does it retain a coherent outer silhouette and the essential parts expected of that thing?

Include an element only when both answers are yes. Rank candidates by completeness, visual independence, distinctiveness, and ease of painting—not by narrative importance.

- Allow people, animals, plants, props, and architecture equally. Valid examples include a complete person, whole tree, recognizable building, car, bicycle, streetlamp, bench, chair, boat, flower cluster, potted plant, mountain, moon, or coherent group such as a flower-and-leaf sprig.
- Preserve natural grouping and attachment. Keep a person with essential clothing and action-defining held objects; keep a tree with its trunk and crown; keep a building with its overall mass, roof or top termination, and base where visible; keep a cup with its handle.
- Allow a conventional self-contained study such as one whole leaf, blossom, shell, or fruit when it has a complete silhouette.
- Select a background or secondary element even when it is not compositionally dominant, provided it passes both tests.
- Use only elements substantially visible in the reference. Do not invent large hidden portions to turn a heavily cropped or occluded fragment into a supposedly complete object.
- Keep studies non-overlapping, consistently styled, and surrounded by generous white space. Scale them for legibility without implying false relative size.
- Simplify each isolated element independently instead of copying the detailed rendering from the main painting. Preserve its outer contour and no more than five internal recognition marks.

Reject fragments such as one tree branch without the tree, half a crown, an isolated sleeve, part of a wall, a cropped roof edge, an arbitrary patch of foliage, a road segment, a shadow, sky wash, edge atmosphere, or color field. Never split one object merely by color, lighting, depth, or texture. Do not invent, duplicate, or complete missing objects merely to fill space.

## Build Mixing Recipes

Replace a conventional palette with a visual derivation panel. Show how base pigments become the important colors used in the painting.

1. Select 3–5 base pigments that can plausibly generate the reference palette. Prefer familiar watercolor families such as warm yellow, cool yellow, crimson or magenta, ultramarine or cobalt, cyan, burnt sienna, and neutral dark. Use only the subset needed by the image.
2. Select 4–6 target colors actually visible in the final painting.
3. Create one horizontal recipe row per target color using this visual grammar:

   `base pigment swatch + base pigment swatch [+ water/neutral swatch] → intermediate mixed swatch → target color swatch`

4. Make the base swatches visibly unequal in size when a ratio matters. A larger swatch means more pigment; a smaller swatch means less. Use a pale, diluted swatch or droplet-like wash to represent added water.
5. Ensure the rightmost target swatch closely matches a clearly visible color in the main painting.
6. Repeat base pigments across rows so the panel demonstrates that a compact base set can create the whole image.
7. Keep the progression left-to-right and align all rows cleanly. Use simple plus signs and arrows only if they render clearly.
8. Do not present six unrelated final-color rectangles. Every target color must have a visible source-to-result relationship.

Do not claim chemically exact pigment ratios from pixels. Treat the recipes as visually plausible mixing guidance. Avoid pigment codes, HEX values, long labels, and generated prose inside the image. If accurate text rendering is explicitly requested, add short pigment names only; otherwise rely on swatches, spacing, plus signs, arrows, and size ratios.

## Layout and Prompt Requirements

Use a warm-white cold-press watercolor-paper background and a landscape board with generous margins. Make the paper itself the principal light source throughout the board.

- Allocate roughly 60–65% of the board to the complete painting.
- Allocate up to 20–25% to the bottom element row; reduce or omit this area when only one or no complete standalone element qualifies.
- Allocate roughly 15–20% to the right mixing panel.
- Keep the entire sheet spacious, editorial, balanced, and easy to scan.
- Preserve the reference's dominant palette and mood while reducing its complexity.

Include the following ideas explicitly in the generation prompt:

```text
Treat the reference as source material, not as a checklist. Repaint it as a highly simplified transparent-watercolor study using only 4–7 large continuous shapes. Recognition must come from the outer silhouette, dominant color planes, overall spatial arrangement, and no more than four selected recognition anchors. Use broad calm washes, one or two washes per shape, and generous untouched paper. Beyond the large masses, allow about 10–16 deliberate internal marks in the complete painting. Represent any repeated system with at most 3–5 marks rather than drawing every unit. Omit nonessential features smaller than roughly 2% of the main painting width. Merge small textures, fixtures, thin lines, gaps, highlights, local shadows, and repeated details into larger color masses. Do not replace omitted details with dense outlines.

Use fresh, water-rich, low-to-medium chroma watercolor rather than dense saturated fill. Leave about 25–35% of the main painting as untouched or nearly untouched paper. Keep about 70% of painted area pale-to-middle value, 20–25% middle-dark, and at most 5–10% concentrated dark accents. Let warm paper show through every large colored shape. Start each shape with one pale wash and reinforce only a smaller selected area; never glaze the entire shape into uniform darkness. Create depth with dilution, temperature shifts, transparent overlap, and edge contrast rather than strong saturation. Neutralize overly vivid source colors with water and a restrained complementary or earth mixture. Keep shadows transparent and colored; avoid black-filled trees, hair, clothing, mountains, buildings, and backgrounds. Reserve the strongest color for one or two small focal accents only.

For architecture, preserve the building silhouette, 2–5 main color planes, perspective direction, and at most four architectural anchors. For trees and plants, preserve a connected crown or plant silhouette, at most three tonal variations, and 3–5 broad structural gestures when useful. For clouds or terrain, preserve the outer contour and 2–4 broad shadow regions. For objects, food, or vehicles, preserve the silhouette, 2–5 color planes, and at most four category-defining features or broad content divisions.

If people appear, reinterpret them as easy-to-draw, lightly cartoonized editorial watercolor characters. Build each person from a simple head, torso, limb, hair, and clothing shapes; use only 3–5 minimal facial marks; simplify hands, anatomy, folds, accessories, and shading. Preserve pose, hairstyle silhouette, glasses or other key cues, dominant outfit colors, and the action. Prioritize clarity and ease of painting over exact facial likeness. Avoid photorealistic portrait rendering, complex anatomy, detailed fingers, fabric texture, and dense facial features.

Along the bottom, show 1–3 complete standalone scene elements from the reference. They may be primary subjects or secondary elements such as a whole tree, recognizable building, vehicle, lamp, bench, flower cluster, food grouping, or complete figure. Choose by completeness, independence, distinctiveness, and ease of painting rather than narrative importance. Every element must be nameable by itself and retain a coherent whole silhouette with its essential parts, but use no more than five internal recognition marks. Preserve natural groupings. Fewer elements are preferable; one is acceptable, and omit the row if none qualifies. Reject lone branches, half trees, partial walls, roof fragments, cropped object pieces, color patches, sky washes, shadows, and atmosphere. Never split an object by color, lighting, depth, or texture, and never invent hidden portions or duplicate items to fill the row.

On the right, create 4–6 aligned visual mixing-recipe rows rather than a conventional palette. Each row must read left-to-right as base pigment swatch + base pigment swatch, optionally plus a diluted-water or neutral swatch, then an arrow to an intermediate mixture and a final target-color swatch used visibly in the main painting. Vary source-swatch sizes to suggest approximate mixing proportions. Reuse a compact set of 3–5 base pigments across the rows.

Render every recipe swatch as a translucent watercolor test on paper. Include a visibly diluted stage where useful, keep paper grain visible inside the target swatches, and match their concentration to the luminous painting rather than presenting dense digital color chips.

Delete unit-by-unit windows, rails, balusters, bricks, leaves, petals, cloud puffs, cables, seams, trim, hardware, tiny shadows, and surface texture unless represented by a few broad marks or selected as one of the four recognition anchors. No long text, HEX codes, watermark, invented subjects, decorative objects, dense brushwork, tiny facets, photorealism, opaque paint, or unrelated palette swatches.
```

## Quality Check

Before delivering, verify all of the following:

- The complete painting is recognizable but clearly simpler than the reference.
- Large color masses dominate; details do not dominate.
- The painting reads as water-rich transparent watercolor rather than dense digital color or opaque paint.
- Approximately 25–35% of the main painting remains untouched or nearly untouched paper.
- Concentrated darks occupy no more than about 5–10% of the painted area and remain focal accents rather than large filled regions.
- Large shapes retain visible paper luminosity; structure comes from dilution, temperature, overlap, and edges rather than excessive saturation.
- The complete painting uses no more than four explicitly preserved recognition anchors.
- The complete painting contains roughly 10–16 deliberate internal marks beyond its large color masses.
- Repeated structures are suggested with at most 3–5 representative marks rather than rendered unit by unit.
- Nonessential features smaller than roughly 2% of the main painting width are omitted.
- Every person is lightly cartoonized, built from simple paintable shapes, and easier to reproduce than the reference photo.
- People retain pose and a few key recognition cues without relying on realistic facial rendering or anatomical detail.
- Every bottom study is a semantically and visually complete, independently recognizable scene element from the reference.
- Every bottom study uses its outer silhouette and no more than five internal recognition marks.
- Secondary elements such as complete trees or buildings are eligible even when they are not the main subject.
- No element is a lone branch, cropped structural fragment, partial color region, shadow, or invented completion.
- No object is split by color, lighting, depth, or texture, and no fragment exists merely to fill the row.
- The number of bottom studies reflects the reference naturally; 0–2 studies are valid when little can be separated honestly.
- The right panel contains readable input-to-output mixing sequences.
- Each final target color appears in the main painting.
- A small base pigment set is reused across multiple recipes.
- Recipe swatches are translucent, show dilution logic, and do not become denser than the colors used in the painting.
- No hallucinated subjects, duplicated focal elements, malformed text, or watermark appears.
