# Contributing to AI Graphic Design Skill

Thanks for your interest in improving this skill! Contributions are welcome from designers, developers, and anyone working at the intersection of AI and graphic design.

## How It Works

1. **Fork** this repository
2. **Create a branch** for your change (`git checkout -b add-comfyui-workflow`)
3. **Make your changes** following the guidelines below
4. **Open a Pull Request** with a clear description of what you changed and why
5. **I review and merge** — all PRs require my approval before merging

## What We're Looking For

### High-value contributions

- **New tools** — AI tools not yet covered in the Tool Selection Matrix (with real usage experience, not just marketing copy)
- **Prompt examples** — Tested prompts that produce reliable results, especially for underrepresented tools
- **Workflow improvements** — Better pipelines, shortcuts, or automation scripts you've validated in production
- **Anti-patterns** — Mistakes you've made so others don't have to
- **IP/legal updates** — Copyright law evolves fast; corrections with sources are very welcome
- **Translations** — Translating the SKILL.md to other languages (keep the original Portuguese intact)

### What to avoid

- **Untested advice** — Every technique in this skill has been validated. Don't add something you read about but haven't tried
- **Tool marketing** — "Tool X is amazing" without concrete capabilities, limitations, and use cases
- **Removing constraints/negative prompts** — The anti-pattern philosophy is core to this skill; suggestions to "simplify" by removing restrictions will be rejected
- **AI-generated filler** — Ironically, don't use AI to bulk-generate content for this repo. Write from experience

## Formatting Rules

- Keep the existing Markdown structure (numbered sections, tables, code blocks)
- New tools go in the **Tool Selection Matrix** table with: Scenario | Tool | Why
- New anti-patterns go in the **Anti-patterns** table with: Error | Consequence | How to avoid
- Use plain ASCII — no accented characters in the SKILL.md (it's designed for maximum compatibility)

## Commit Messages

Follow conventional commits:

```
feat: add ComfyUI workflow for batch logo generation
fix: correct Midjourney --sref parameter syntax
docs: add Figma AI vectorization to tool matrix
```

## Questions?

Open an issue. I'm happy to discuss whether a contribution fits before you invest time writing it.
