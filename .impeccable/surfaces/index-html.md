---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: ["404.html"]
---

# Surface brief: portfolio home (index.html)

Scope: the single-page portfolio. Mode: Experience (portfolio) with a Persuade close: hire / email Harsh, download resume.
Audience/job: recruiters, hiring managers, tech leads deciding in under a minute whether Harsh ships LLM products.
Constraints: static single file on GitHub Pages (relative paths, no build, no API keys, no backend: contact form composes a mailto). No invented metrics, clients, stats or testimonials. CGPA hidden. Resume at `resume.pdf` (user supplies). No profile photo exists. Old clip-art logos not used.
History: v1 dark sidebar (rejected: template, plain). v2 light "AI product launch" (replaced by the user's pinned reference). v3 dark glass (current, tag `v1` on `dev`). The in-page "Ask about my work" assistant and the iridescent gradient were removed at the user's request.

## Pinned reference (user, 2026-10-08)
Dribbble shot "AI-Portfolio Interactive Portfolio & Smart WebFlow Design" by Mominor Rahman: https://dribbble.com/shots/27276445. Used as a style reference only; none of its images or copy are reused.

## Direction contract

THESIS: The user-pinned dark, glassy AI portfolio: a glowing particle robot in a glass app window leads the first screen, and a live, animated workflow of the finance agent shows how Harsh's systems actually work. Refuses the reference's fake stats, lorem copy and stock photo slot.

OWN-WORLD: Deep blue-black ground (#0A0A12) with soft violet/blue/pink light fields; frosted glass panels (white 4–7% fill, 10% hairline, backdrop blur) with large radii; one solid violet (#6D5CF0) for every control and selected state, no gradient fills; soft violet (#9D8CFF) for the highlighted headline phrase. Sora display, Manrope body, JetBrains Mono only for code, dates and window titles. Lucide-style 1.75px line icons; brand marks (Simple Icons) only in the built-with row and skill chips.

STORY: Robot and headline, then services, featured finance agent (animated workflow), filterable project cards (Document Q&A RAG chatbot first), about and tech, journey, contact form, footer.

FIRST VIEWPORT: Glass nav bar (HP mark, links, Resume, solid violet "Hire me"; menu button under 900px, solid top bar under 640px). Left: headline "I build AI agents that read, reason & act." with the key phrase in soft violet, sub, "View my work" (violet) + "Download resume" (glass), built-with row. Right: glass app window (harsh-patel / ai-agent, RAG · Agents tag) with the canvas particle robot on a perspective grid floor and three floating chips (Retrieval, Tool calling, Python APIs).

FORM: Signature interactions: the particle robot drifts, blinks and scatters from the pointer; the finance-agent workflow runs step by step (nodes spin then check, connectors fill violet with a travelling packet, caption narrates) only while visible, and shows the finished state under reduced motion.

FINISH: unreviewed and undocumented is unfinished; changes end with a check at desktop and phone width, an updated DESIGN.md, and provenance on every shipping raster.
