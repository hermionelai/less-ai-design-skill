# Color choices and ambient light

The benchmark is mostly near-white, stable dark text and actions, low-saturation light that blends into the background, and quiet frosted surfaces. This describes a material relationship, not a mandatory palette or permission to change a live product.

## Comparable directions

- **Warm blue-gray:** a slightly warm white and pale sand transition into blue-gray; professional with some warmth.
- **Muted lilac:** near-white with small amounts of gray-lilac and silver-blue; delicate and exploratory.
- **Pale blue:** white with a light blue glow; clear and calm.

These are descriptions from visual exploration. Project-specific images are not distributed in this public repository. They are not pixel specifications or evidence of implemented motion. Other palettes can be proposed when the context supports them.

## Choice without a rigid skin system

Compare a few meaningful color temperatures on the same real page with identical content and controls. A preset may be a starting point for adjusting warmth, hue, strength, or motion. Not every proposal needs three options and not every product needs a theme selector. Distinguish design-review choices from end-user personalization.

Variation mainly belongs in ambient light, temperature, and a little surface reflection. An accent is not a command to tint every button, label, icon, and paragraph. Keep error, warning, success, focus, and action hierarchy stable. Do not assume an unrestricted full-spectrum slider is a useful default.

## Making the light believable

- Keep most of the canvas near-white; color should feel like environmental light rather than a painted theme panel.
- If an opaque white rectangle looks disconnected, soften fill, edge, and shadow first. Do not remove a needed container automatically.
- Place gradients according to the composition, not a mechanical blob in each corner.
- Charcoal actions are a stable anchor in the reference direction. Other contexts can justify other action colors.
- Evaluate color in a real page, not only swatches or interchangeable component cards.

## Optional motion

Low-saturation light may drift slowly or shift subtly in warmth or brightness. Its presence should stay below the content and task. Do not move the layout, change text size, reshape controls, or shift click targets.

Make the static composition work first. Start with a long cycle and low amplitude where appropriate, without prescribing a universal duration. Reading, tables, and frequent-action workspaces may be entirely static. Brand pages and posters do not automatically need animation either.

Provide an appropriate pause or static option for automatic changes. Do not immediately override a manually selected appearance. Respect `prefers-reduced-motion` by reducing or disabling decorative motion. Motion preference and automatic palette rotation are separate concerns.

Keep text, focus, state, and action contrast readable in every frame. Background movement is not a progress or success signal. Fall back to static light or a clear solid surface when needed; avoid expensive continuous full-screen blur.

## Avoid falling back into a template

Rainbow blobs, neon purple-blue, liquid spheres, obvious waves, rapid hue cycling, glowing breathing buttons, cursor spotlights, and glass on every surface are not default expressions of the future. They may suit other art directions, but not this benchmark without a specific reason.

Preserve the chosen proportions, hierarchy, spacing, alignment, and actions while exploring light and temperature. If the result still feels generic, inspect composition and real content before adding decoration.

## Verify

Check the default, presets, strength extremes, motion, pause, reduced-motion behavior, and solid fallback as relevant. Appearance changes should preserve inputs, filters, and task state. Reuse the logic and quality across products, not necessarily the hue or background image.
