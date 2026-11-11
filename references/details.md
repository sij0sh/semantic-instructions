# Details

**Frame.** Read the target and direct references; identify existing rules, evidence, and unresolved questions. Separate requirements from preferences; distinguish facts, assumptions, unknowns, and decisions. Surface consequential ambiguity as a question, not a requirement.

**New.** SKILL.md needs `name`/`description` frontmatter; AGENTS.md is plain markdown; agent definitions follow project shape or surface unknown; prompts are plain text; workflow/evaluation instructions follow surrounding format.

**Instruction kinds.** Semantic directives guide judgment; evaluative questions expose failure; mechanical rules govern execution. State when conditional rules apply. Use deterministic mechanics for state, ordering, persistence, and checkable constraints. A mechanical rule needs a trigger, a decision it changes, and an observable outcome.

**Challenge.** Sufficiency: test whether literal compliance could miss the intended outcome. Describe a concrete failure case, or a plausible case and evidence ruling it out; "none found" alone is insufficient. Necessity: state how each rule changes behavior; remove rules with no effect. Semantic directives need no mechanical trigger. Revise only affected text, in at most two passes total; recheck after each. Stop when no material defect remains or the limit is reached; report unresolved risks.

**Output.** Review never writes files. Return findings inline, with a proposed diff for warranted changes. For create/edit/simplify, write to the specified target path and briefly confirm; without a path, return the instruction inline. New files use the required format; edits preserve format and scope. Explain removed or contested rules and report unresolved questions or risks; otherwise add no commentary.

**Artifacts.** Workflow stages—what is lost at a boundary? Agent definitions—ownership or contract gap? Evaluations—could a compliant agent pass superficially?
