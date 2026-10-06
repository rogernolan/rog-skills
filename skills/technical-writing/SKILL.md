---
name: technical-writing
description: Use when writing or revising technical documentation that needs plain, concrete prose, explicit system ownership, restrained structure, and architecture-level precision
---

# Technical Writing

## Core pattern

Precision is the aim; clarity lets the reader verify it. Name actors, decisions,
scope, assumptions, evidence, and uncertainty.

Write connected paragraphs explaining what the system does, why it has this
shape, and how its parts relate. Prefer short familiar words that preserve
precision. Use everyday English when equally exact; keep a technical
term when it is more precise. Define terms controlling scope or acceptance; do
not let qualifiers such as “reasonable” carry policy. Preserve thresholds and
examples.

Name the actor that owns the claim: project for scope, organisation for
decisions, component for behaviour.

Prefer operational statements: say what a component manages, moves, decides,
or checks. Give capabilities their own sentence.

Make the component that performs an action the grammatical subject:

> The scheduler assigns the task; the harness starts the assigned model.

If the actor is unknown, say ownership is undecided. Use active voice to expose
authority, sequence, retries, and uncertainty. “The request is retried” is
incomplete until the actor and duplicate prevention are named.

State scope directly. Name overlaps and exceptions with a boundary example. Do
not imply a false partition or invent a primary/secondary hierarchy
between deliverables.

Use “is” or “will” for decisions, “should” for recommendations, and explicit
uncertainty for open questions. Do not turn an example into a commitment. State
settled exclusions as “not in scope” or “will not”. Put material assumptions
beside an estimate.

Label evidence as known, observed, reported, assumed, proposed, or unknown. Name
dependencies and when they matter. Access and investigation do not expand
scope. Bound discovery to its required outcome. Keep materially different costs
or resources separate.

Prefer explicit design statements to sales language. Keep rationale that
explains why the design differs from familiar approaches. State the mechanism
behind comparisons; remove unsupported praise.

## Shape the document

Start with the smallest complete explanation. Preserve ownership, delegation,
sequence, and hierarchy before inventory. Connect paragraphs so each advances
the previous one. Add structure only when it makes a relationship or choice
easier to scan. In a proposal, state the enduring capability and first
proof.

When revising, preserve technical meaning, decisions, examples, and uncertainty.
Avoid stock metaphors and canned phrases. Cut any word that does not change
meaning, scope, evidence, or tone. Remove generic AI aphorisms, restatement,
and rhetorical justification. Keep qualifications that change the design or
decision. Introduce examples directly; prefer “For example” to scene-setting.

## Final check

- Can every action name its responsible component?
- Does any passive construction conceal ownership or authority?
- Does the wording distinguish decisions, evidence status, and open questions?
- Does each heading or bullet improve navigation?
- Did compression preserve relationships, assumptions, and examples?

If an answer is no, revise the sentence or state the unresolved design choice.
These rules serve precision. Break one before making the prose less accurate or
natural.
