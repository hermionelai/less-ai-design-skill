# Product UI and interaction

## Information and density

Start with what people need to read, compare, and do. Use type size, weight, spacing, light dividers, and grouping to distinguish information. Do not default to a rounded container around every group. Simplifying does not mean deleting necessary details or making supporting text tiny and faint.

Give each region a clear visual emphasis. A simple entry page may need one functional statement, short steps, and a primary action; the task determines whether more is necessary. Do not impose a three-step homepage on every product. Workspaces and directories should retain filters, statuses, sources, and context.

## Buttons

- Use a stable treatment for primary actions. Within a local group, make relative importance clear rather than emphasizing every action equally. Do not impose an arbitrary page-wide button limit.
- A proven light-interface example uses charcoal primary buttons, quiet secondary surfaces, and text links for lower-priority actions. Other accent colors remain valid when the brand and task support them.
- Use pill shapes selectively. Labels, dropdowns, and dialogs need not share the same oversized radius.
- Name the action and object: "Upload resume" or "Save changes," rather than "Explore the future."
- Design default, hover, pressed, keyboard focus, disabled, loading, success, and failure states consistently. A small background change or press response may work; approximately 150–200 ms is an optional starting point, not a rule. Avoid drifting controls and looping glows.
- Prevent duplicate submission while keeping the action understandable. Preserve input after failure and provide a useful recovery path. Do not simulate real success with a timer in production.
- Use icons to support labels. Common single-purpose icon-only controls still need accessible names.
- Keep focus visible and controls usable without hover. Around 44 CSS pixels can be a starting point for prominent touch targets, subject to device and accessibility requirements; do not equate native platform points with web pixels.

## Typography

Readability is part of the finish. Use a suitable system sans serif or brand face for product text; reserve expressive faces for appropriate contexts. Avoid making the whole page bold.

A large-type job directory used 24px titles, 21px company names, 18px conditions, 16px labels/actions, and 14px dates. This is a project example, not a universal scale. For Chinese body copy, 16–18px can be an initial range; adjust to device, reading distance, density, and the actual language. Check other scripts separately.

Distinguish px, pt, and platform points. Verify computed sizes in the browser rather than shrinking the page or screenshot. Supporting text also needs enough contrast.

## Labels and icons

Group by meaning: entity, location, eligibility, status, category, and skills. A map pin can distinguish location, a graduation cap education, and a calendar a cohort or date. Use a coherent stroke weight; icons should help recognition.

Information labels should not mimic buttons: no gratuitous press state, hover shadow, or pointer cursor. An example uses pale blue for employment type, muted lilac for discipline, and neutral gray for skills. Use a small, stable semantic system rather than a different color for every word. Never rely on color alone.

Distinguish filters from static labels. Single and multiple selection must match the behavior. Dense category filters can use text and a light selected surface instead of heavy borders on every option.

## Alignment and geometry

Define shared grids, baselines, and visual groups before deciding between top and center alignment. In an entity list, center the initials tile against the full title-and-label group when those belong together. Align conditions and actions consistently. Check long titles after wrapping; avoid guessed fixed margins.

Keep an icon inside and centered within its backplate unless deliberate offset is part of an explicitly chosen art direction. If a real logo is unavailable, use a recognizable short name, not mechanically extracted initials. Keep the full entity name available.

## Materials and depth

Near-white with a little pale blue or lilac ambient light is one proven direction, not a required background. Avoid obvious rainbow clouds, hard wave edges, and neon as default decoration.

Borrow Apple's attention to material and hierarchy, without claiming a web blur is equivalent to native Liquid Glass. Use frosted surfaces selectively for navigation, controls, or overlays. Keep primary reading areas clear. A large opaque white rectangle can feel disconnected from a softly colored background.

For a lightly frosted entry surface, 10–20% white fill and approximately 12–20px blur may be useful starting points. Overlays may need a more opaque surface. Adjust to contrast, background, and performance. Provide a readable solid fallback when blur is unavailable or transparency is reduced.

## Layout and behavior

Design desktop websites for a landscape browser workspace, not an enlarged phone card. Allow natural vertical scrolling where content requires it. Reflow narrow layouts rather than forcing desktop columns into horizontal overflow.

Dialogs need a clear title, close action, Escape behavior, managed focus, and focus restoration. Long content must scroll and actions remain reachable. Background blur must not blur the dialog's text. Respect reduced motion.

Core links should reach the corresponding page. Visual refinement preserves filter semantics, fields, pagination, export, sources, and business logic unless the task explicitly changes them.
