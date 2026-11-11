---
name: semantic-instructions
description: Create, edit, review, or simplify instructions for AI agents, including prompts, SKILL.md, AGENTS.md, agent definitions, workflow stages, and evaluation instructions. Use when authoring or improving agent-facing instructions, not generic prose or code.
disable-model-invocation: true
---

Frame: read the target, its direct references, and [details](references/details.md). Identify the requested operation, target format, intended outcome, constraints, and unknowns.

Compose: write the smallest instruction set that preserves the intended outcome and constraints. Use the target format; give each instruction one responsibility. Split only for focus, verification, or control.

Challenge: name a compliant-but-failing case, or give evidence ruling out a plausible case. Remove rules with no behavioral effect. Revise only demonstrated defects; stop when no material defect remains or after two revision passes. Report unresolved risks.
