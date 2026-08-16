---
name: lsat-reasoning
description: "Audit dense passages and arguments by mapping task, evidence, warrants, alternatives, uncertainty, and conclusions. Use for LSAT-derived reasoning practice; never reproduce protected items or predict admissions."
---

# LSAT reasoning, evidence, and argument

## Purpose

Use this skill to operationalize competency F2-COMP-66-LSAT-001 as a bounded,
source-grounded reasoning, evidence, feedback, and improvement workflow.
The assessment, credential, degree, or program exemplar informing the skill
is evidence about the competency, not the competency itself.

## Use

Use it for reasoning coach and evidence auditor when the user supplies a domain task, case, passage,
study, policy record, model, or design record. Do not use it as a
admissions predictor, law-school selector, legal adviser, or answer-key reproducer.

## Workflow

1. State task, purpose, audience, constraints, supplied materials, intended use, accessibility, and decision rights.
2. Read supplied materials first; separate source claims, observations, inferences, project judgments, and missing evidence.
3. Build the domain-specific evidence record and connect claims, reasons, methods, facts, or requirements to locators.
4. Test alternatives, uncertainty, limitations, and the most consequential failure mode for this domain.
5. Produce a qualified learner or reviewer artifact and preserve unresolved questions.
6. Stop and route substantive judgment to the accountable human reviewer named in the safety reference.

## Competency spine

- orient and segment dense text
- map claims, reasons, assumptions, and implications
- test alternatives against evidence
- state a warranted conclusion
- write and audit a persuasive response

## Evidence requirements

- recoverable text map and locator ledger
- reasoning map with warrant
- alternative or uncertainty record
- conclusion tied to evidence

## Output contract

Return a structured record containing:

- task_contract and orientation
- source_ids, locators, provenance, and rights status
- competency evidence and evaluator dimensions
- alternatives, uncertainty, limitations, and unresolved_items
- learner_task or reviewer_feedback
- review_status and explicit boundary statement

Use status values such as READY_FOR_HUMAN_REVIEW, NEEDS_INPUT,
BLOCKED_PENDING_REVIEW, and FORMATIVE_ONLY. Never issue a credential,
licensure decision, professional sign-off, or high-impact decision.

## Guardrails

- Use original, public-domain, or permission-cleared passages only; never reproduce protected LSAT items or predict admissions.
- Do not invent sources, citations, facts, results, authorities, clinical findings, validation, or stakeholder positions.
- Keep SOURCE, CROSSWALK, INFERENCE, and PROJECT_EVALUATOR layers distinct.
- Use original, synthetic, public-domain, or permission-cleared challenge materials only.
- Preserve learner authorship; scaffold and audit rather than ghostwrite assessed work.

- Stop if the supplied record is missing or unverifiable.
- Stop if the task crosses the declared professional or consequential boundary.
- Stop if source, rights, privacy, or jurisdiction conditions cannot be established.
- Stop if the output would be presented as a credential, license, sign-off, or official decision.

## Handoffs

Human review owns high-stakes admissions, rights, and accessibility judgments.

Read references/source-crosswalk.md, references/competency-object.json,
references/evaluator-spec.json, references/textbook-architecture.md,
references/bounded-packet-001.md, and references/safety-and-boundaries.md
before making a domain-specific claim.
