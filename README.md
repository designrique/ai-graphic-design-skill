# AI Graphic Design — Claude Code Skill

> A Claude Code skill for creating logos, brand identities, and visual assets using AI — built from real-world production experience, not theory.

## Why This Exists

I'm a **graphic designer with a Master's degree in Computer Science**. For years I lived in both worlds — crafting brand identities by hand in Illustrator and studying how machines learn to see. When generative AI hit the design industry, I saw the same problem everywhere: designers either rejected AI entirely or surrendered creative control to it, producing what the industry now calls "AI slop" — generic, soulless visuals with no brand coherence.

**Neither extreme works.**

This skill was born from my need to **scale visual identity production without losing the essence and creative control** that makes a brand memorable. I needed a system that would let me produce 10x the output while maintaining the mathematical precision of Bezier curves, the intentionality of color theory, and the strategic depth of brand archetypes.

After curating and distilling **46 specialized sources** on AI-assisted graphic design — covering tools, prompt engineering, vectorization pipelines, IP law, and Python automation — I compiled everything into a single, actionable skill that any Claude Code user can install and use immediately.

## What It Covers

| Section | Content |
|---|---|
| **Tool Selection Matrix** | 15 AI tools mapped to specific scenarios (Recraft for SVG, Midjourney for ideation, Firefly for IP-safe work, etc.) |
| **Briefing Frameworks** | RCAO and StoryBrand templates for defining brand identity before any visual generation |
| **Prompt Engineering** | Structured formulas per tool — Recraft (shape logic + constraints), Midjourney (artistic vocabulary + --sref/--cref/--seed), DALL-E (natural language), Stable Diffusion (LoRAs + ControlNet) |
| **End-to-End Workflow** | 5 phases: Briefing → Ideation → Vector Creation → Mockups → Delivery |
| **Visual Consistency** | Style IDs, seed fixing, moodboards, LoRAs, manual curation techniques |
| **Vectorization Pipeline** | Raster → Smart Upscaling (4 models) → Vectorizer.ai/Chat2SVG → Bezier cleanup (Box Method) |
| **Python Automation** | py5, vpype, Aspose.SVG, Blender API for batch generation and post-processing |
| **Delivery Formats** | SVG/EPS/PDF (vector) vs PNG/JPG (raster) with DPI specs for print and digital |
| **IP Safety & Ethics** | Risk matrix by tool (Firefly vs Midjourney vs Stable Diffusion) + legal rules (BR/US/UK) |
| **Professional Mockups** | Displacement Maps + Blend Options in Photoshop; AI alternatives (Phygital+, Nano Banana) |
| **Anti-patterns** | 7 common mistakes designers make with AI and how to avoid them |
| **2025-2026 Competency Roadmap** | The skills a designer needs to evolve from executor to "AI Creative Director" |

## The Philosophy

> "AI tool interfaces become obsolete in months. Fundamentals last decades."

This skill treats AI as an **accelerator**, not a replacement. The designer remains the creative director — curating, refining, and making the judgment calls that no model can. The skill encodes this philosophy at every level:

- **Briefing before generation** — no visual work starts without a defined brand archetype
- **Constraints are as important as instructions** — negative prompts and restrictions prevent generic output
- **Human post-processing is non-negotiable** — Bezier cleanup, manual curation, and displacement maps ensure professional-grade deliverables
- **Document everything** — seeds, prompts, and parameters are archived for reproducibility

## Installation

### Claude Code CLI

```bash
claude skill install designrique/ai-graphic-design-skill
```

### Manual

Copy `SKILL.md` to your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/ai-graphic-design
cp SKILL.md ~/.claude/skills/ai-graphic-design/
```

## Usage

Once installed, the skill activates automatically when you mention:
- Logo, logotype, brand, branding, visual identity
- Mockup, visual presentation, graphic material
- Visual prompt, image generation for brand
- SVG, EPS, vector, Illustrator, Recraft, Midjourney

## Knowledge Sources

This skill was distilled from **46 curated sources** covering:
- Advanced AI tool documentation and benchmarks
- Prompt engineering research for visual generation
- Bezier curve mathematics and the Box Method for vector optimization
- IP law and copyright frameworks for AI-generated content (BR, US, UK)
- Python automation pipelines for scalable design systems
- Professional mockup techniques (displacement maps, blend options)
- Brand strategy methodologies (RCAO, StoryBrand, brand archetypes)

## About the Author

**Henrique** — Graphic Designer & MSc in Computer Science. Building at the intersection of design craft and computational thinking. This skill reflects a production-tested workflow for scaling brand identity work with AI while preserving creative intent and mathematical precision.

## License

MIT
