# Component and feedback patterns

These are independent interpretations of established patterns, not verbatim rules from an upstream system. Open the original [component study](../assets/component-study.html) for an adjustable example. It is not a production component library and does not submit real data.

## Actions

Give a local task a clear primary action; make back and cancel quieter. Distinguish destructive actions from ordinary confirmation and explain consequences. Offer reversal where appropriate. Use the same terminology in labels and feedback. Use links for navigation and static markup for informational labels.

Consider default, hover/focus, pressed, processing, and completion/failure states. Prevent duplicate submission without erasing the action's meaning. Preserve input on failure. If the reason for a disabled control is unclear, explain it nearby, not only in a tooltip on the disabled element.

## Forms and settings

Keep labels visible. Put examples and constraints near the field. Point errors to a specific field and explain how to fix them. Preserve entered information when recovering from errors. Make it clear whether changes apply immediately or require saving. Break long tasks into meaningful sections, not a new step for every two fields.

## Navigation and filters

Separate global navigation, page filters, and item actions. Retain selected conditions and make count changes understandable. Reset only the relevant scope. In real products, useful search and pagination state may belong in the URL for back navigation and sharing; do not add routing machinery to a simple local demo without a reason. Selection appearance must match single- or multi-select behavior.

## Lists and tables

Help users identify the entity and main field, then scan conditions, labels, and status. Share column and text anchors; align icons to the related visual group. Separate row actions from global and bulk actions. Choose pagination or progressive disclosure to suit the data. Choose tables or cards based on comparison tasks, not which is assumed to look more premium.

## Dialogs and side panels

Use a dialog for temporary confirmation, input, or local detail. A side panel or separate page may suit ongoing comparison. Manage entry focus, keyboard navigation, Escape, and restoration. Keep long content scrollable and actions reachable. Avoid nested dialogs. Retain the behavior of native dialogs or established accessible primitives when restyling them.

## Feedback

| State | Helpful content and action | Avoid |
| --- | --- | --- |
| First use | Explain what will appear and offer a starting action | A long tutorial occupying every region |
| No results | Preserve filter context and suggest adjustment | Implying data loss or a system failure |
| System error | Explain the immediate impact and a recovery path | An endless spinner or an unexplained code |
| Loading | Local busy state and stable layout | Arbitrary skeletons or replacing the entire page |
| Complete | Confirm the actual action and necessary next step | A full-screen celebration for every success |

## AI interactions

Distinguish input, generated output, sources, and execution state. Show only available progress; do not invent reasoning traces or percentages. Offer stop/resume where the real capability supports it. Let people edit, copy, and revisit results. Keep consequential decisions under user control. A chat box is not automatically the right homepage; structured tasks may work better as forms and lists.

## Semantics and materials

Category labels, actionable filters, and feedback states are distinct objects. Establish meaning before choosing color; do not use one lilac treatment for both a discipline and an error. Frosting should express a clear layering relationship and preserve table readability. Brand texture does not automatically belong inside inputs.
