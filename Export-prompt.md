# Your codebase already has a design language — colors scattered across stylesheets, spacing patterns buried in component files, typography choices locked in Tailwind configs. A DESIGN.md captures all of it in one place so Stitch can generate screens that look like they belong to your product instead of a blank-slate default.

# There are two ways to get there: a quick prompt you can paste into any coding agent, or a dedicated skill that automates the entire pipeline.

# Copy this prompt into any coding agent (Gemini, Claude Code, Cursor, Antigravity) from a project directory. No skills or plugins required — the agent reads your source files and writes a DESIGN.md from what it finds.

# Add specifics about your codebase’s purpose, critical files, and goals.

Read the codebase and/or website before designing. The repo and/or website are the source of truth. Start with real content. Pull product names, taglines, and copy from the README. Pull labels, values, and terminology from config files, CLI help text, schemas, and error messages. Nothing invented, nothing placeholder — if the repo doesn’t contain it, the design doesn’t show it.

Look at existing code for visual identity: color values, type scales, spacing tokens, component patterns. If a design system exists, inherit it. If values are scattered across files, collect them — they reveal visual intent even when undocumented. Read the core logic and data structures, not just the docs. They tell you the product’s native shape — a timeline, a graph, a catalog, a pipeline. Let that shape organize the page instead of a section template.

Find what the README leads with. That feature dominates the page. Establish its weight before placing anything else — what matters before what measures.
