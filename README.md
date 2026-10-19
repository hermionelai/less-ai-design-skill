# less-ai-design-skill

## Vibe code with AI. Lose the AI look.

Built something useful with AI, but it still looks like every other AI-generated website? Start here.

**A tool-agnostic design skill for product design, web design, and UI/UX. Turn generic AI-generated interfaces into clean, polished, user-friendly experiences with clear typography, restrained color, thoughtful materials, and natural interactions.**

Keep the speed of building with AI. Give the result a more considered finish: readable type, well-aligned layouts, clear actions, and details that belong to the product.

## One prompt to get started

Attach this repository to your AI tool, or give it `SKILL.md` and the relevant reference files, then ask:

```text
Use less-ai-design-skill to remove the generic AI look from this design.
Keep the existing features, content, and business logic.
Improve typography, hierarchy, alignment, controls, and interaction states.
Choose color and materials that suit the product; do not force a preset style.
First refine one representative page, then apply the agreed direction.
```

This is a reusable set of design instructions, not an automatic one-click filter. The tool needs access to your design or source files to make changes; review and publishing follow your usual workflow.

## Use it with your preferred tool

**No Codex installation required.** Everything important is written in portable Markdown; the component example is standalone HTML/CSS/JavaScript.

- **Any AI assistant:** upload or paste `SKILL.md`, then include the references relevant to your task. If the assistant cannot open relative links, supply those files explicitly.
- **AI coding tools:** keep the repository in your project and ask the agent to read `SKILL.md`. Tools with instruction or rule files can point to it; loading behavior and context limits vary by tool.
- **Tools that support skills:** load the folder using that tool's supported skill mechanism. Automatic discovery is tool-specific.
- **Designers and teams:** use the references as a review guide and a shared language for design decisions.

Optional Codex setup:

```sh
git clone https://github.com/hermionelai/less-ai-design-skill.git ~/.codex/skills/less-ai-design-skill
```

Check that the destination does not already contain work. Reopen your session, then invoke `$less-ai-design-skill`. The `agents/openai.yaml` file contains optional Codex display metadata; the core guidance does not depend on it.

## What it covers

| Area | Focus |
| --- | --- |
| Product design | User tasks, information hierarchy, workflows, responsive layouts |
| Web design | Websites, landing pages, navigation, page composition, visual finish |
| UI and interaction design | Buttons, forms, filters, lists, tables, dialogs, feedback, keyboard behavior |
| Visual direction | Typography, color options, subtle materials, optional ambient motion |
| Brand expression | Professional warmth and a restrained sense of the future |

It can refine an existing interface or guide a new one. It does not prescribe a technology stack, a single palette, or one layout for every product.

## The design direction

- **Clean, with substance.** Remove visual noise without stripping away useful information.
- **Polished, without decoration for its own sake.** Work on proportion, type, spacing, alignment, and states before adding effects.
- **User-friendly by design.** Make content readable, actions discoverable, and feedback understandable.
- **Flexible color, consistent logic.** Offer meaningful color-temperature options; keep semantics and contrast stable.
- **Material with a purpose.** Subtle glass and ambient light can add depth when they help the composition. They are optional.
- **Less template, more context.** Avoid interchangeable card grids, unnecessary pills, glowing buttons, and vague AI marketing copy.

System fonts, useful icons, necessary cards, and gradients are not banned. The question is whether they fit the task and have been handled well.

## Inside

- [SKILL.md](SKILL.md): core instructions and reference routing
- [Product UI](references/product-ui.md): typography, buttons, icons, labels, alignment, surfaces
- [Component patterns](references/component-patterns.md): forms, navigation, dialogs, feedback, AI interactions
- [Color and light](references/color-and-light.md): palette choices and optional motion
- [Cross-surface guidance](references/cross-surface.md): adapting the direction across products and formats
- [Brand expression](references/brand-expression.md): human warmth and future-facing visual work
- [Reference library](references/reference-library.md): visual references and what to borrow
- [External skills and systems](references/external-skills.md): further methods and first-party resources
- [Component study](assets/component-study.html): an original interactive example; download and open locally

The example does not submit or store real data. Project-specific screenshots, private attachments, and local absolute paths are excluded. Example measurements are starting points, not universal standards.

## License

Original writing and the component example are available under the [MIT License](LICENSE). Third-party brands, sites, design systems, and linked skills retain their own rights. This license does not cover their assets; no third-party images, fonts, or upstream skill code are bundled.
