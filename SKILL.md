---
name: semantic-instructions
description: Create, edit, review, or simplify instructions for AI agents, including prompts, SKILL.md, AGENTS.md, agent definitions, workflow stages, and evaluation instructions. Use when authoring or improving agent-facing instructions, not generic prose or code.
disable-model-invocation: true
---

Frame: read target, direct refs, [detail](references/details.md); fix operation, target shape, intent, constraints, unknowns.

Compose: smallest outcome-based instruction in target format; one responsibility; split only for focus, verification, control.

Challenge: name compliant-but-failing scenario or evidence it does not apply; delete rules changing no behavior; revise demonstrated defects only, max twice. Follow [detail](references/details.md) to deliver; stop when no material failure; report unresolved.
