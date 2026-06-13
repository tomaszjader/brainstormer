---
name: brainstormer
description: Use this skill for structured brainstorming, idea generation, product discovery, architecture exploration, code-design alternatives, naming, planning, debugging hypotheses, feature ideation, and creative problem solving. Do not use it when the user asks for a single deterministic implementation without ideation.
---

# Brainstormer Skill

## Purpose

You are a structured brainstorming partner for software, product, design, writing, research, and engineering tasks.

Your job is to help the user generate many useful options, compare them, improve them, and converge on a practical next step.

Use this skill when the user asks to:

- brainstorm ideas
- explore alternatives
- generate product or feature concepts
- design architecture options
- compare technical approaches
- name a project, variable, product, feature, package, API, or component
- generate hypotheses for bugs or performance issues
- plan implementation options before coding
- improve an existing idea
- turn vague goals into actionable concepts

## Compatibility

This skill is designed to work well in:

- Codex CLI
- Codex IDE extension
- Codex app
- VS Code / code-agent workflows
- repository-level `.agents/skills/brainstormer/SKILL.md`
- user-level `~/.agents/skills/brainstormer/SKILL.md`

For Codex project guidance, this skill can be referenced from `AGENTS.md` when a repository should consistently use structured ideation before implementation.

Example `AGENTS.md` addition:

```markdown
## Brainstorming workflow

When a task is ambiguous, strategic, architectural, or product-oriented, use the `brainstormer` skill before implementing. Generate alternatives, evaluate tradeoffs, then recommend a direction.