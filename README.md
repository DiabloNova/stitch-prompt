****What the prompt does****

The prompt tells the agent to work backwards from your code, not forwards from a template. It extracts three layers:

**Content** — Product names, labels, and copy pulled directly from the source. No filler text, no lorem ipsum.

**Visual identity** — Colors, fonts, spacing, and component patterns gathered from stylesheets, theme files, and Tailwind configs.

**Information architecture** — The natural shape of your product’s data, which determines how the page is organized.
The output is a DESIGN.md you can drop into .stitch/DESIGN.md and immediately use for screen generation.

# ****Tips for better results****

**Point the agent at specific directories**. Add lines like *“Focus on src/styles/, tailwind.config.ts, and src/components/”* to the context block.

**Name your stack**. Telling the agent *“This is a React + Tailwind + shadcn/ui project”* helps it look in the right places.

**Iterate**. The first extraction captures the big picture. Refine it: *“The accent color should be the teal from the navbar, not the blue from the footer.”*

****Automated extraction with Stitch Design Skills****

The prompt above works anywhere, but it relies on the agent’s general reasoning. Stitch Design Skills are purpose-built agent instructions that know exactly where to look for design tokens in every major framework — React, Vue, Svelte, Angular, plain CSS, and Tailwind.

**What are Stitch Design Skills?**

Stitch Design Skills is an open-source collection of 13 agent skills organized into three plugins:

**Plugin: What it does**

*stitch-design*:	Create and capture designs — extract tokens from code, snapshot running apps, upload to Stitch
*stitch-build*:	Turn designs into code — React components, walkthrough videos, shadcn/ui integration
*stitch-utilities*:	Enhance quality — prompt optimization, premium design systems, autonomous multi-page generation
