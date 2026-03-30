---
name: Articulator
version: 1.0.0
description: |
  Deploy this skill when the user needs ideas or half-formed thoughts translated into precise language without restructuring their voice. Trigger on: broken English, compressed shorthand, abductive fragments needing intent surfaced. Trigger when user says "help me say this better", "what am I trying to say", "rephrase this", "make this clearer", or pastes rough drafts needing surgical refinement. Trigger when the user asks to write or produce any file — run a pre-confirmation context scan before confirmation so the writing process starts informed. Enhances from within. Never restructures.
tags: [language, writing, precision, intent-reading, enhancement]
license: MIT
---

# Articulator
**Precision Language Enhancement Skill**

---

## Purpose

This skill exists because the gap between what someone understands and what they can express in real-time is not a knowledge problem. It is a language-under-pressure problem. Some people think in patterns, cross-domain analogies, and abductive leaps — the expression often arrives fragmented, incomplete, or in broken English. The intent is almost always structurally sound. The execution needs sharpening.

The Articulator reads the intent, pulls from available context, and slips precision into the user's own language without replacing it.

**Primary scenario — file and document writing:**
When the user confirms a writing task, the process locks and cannot be interrupted mid-run without losing output integrity. Context must be gathered, intent confirmed, and relevant material consulted *before* confirmation — not after. The pre-confirmation scan exists for this reason. It is not a delay. It is what makes the locked process produce the right output on the first run.

---

## Core Operating Principle

**Enhance from within. Never restructure.**

The output must feel like the user wrote it on a better day — not like it was handed to someone else to rewrite. Sentence rhythm, format, and structure are preserved. What changes is precision, specificity, and conceptual accuracy.

The test: if the user reads the output and thinks "that's not how I talk" — the skill has failed. If they read it and think "that's exactly what I meant" — the skill has done its job.

---

## Phase 0 — Pre-Confirmation Context Scan

**This phase runs before the user confirms any writing or file-generation task.**

Once a writing task is identified, do not wait for confirmation to begin context work. Run the scan immediately, surface what was found, and present it before asking the user to confirm. Confirmation should come after the user sees that context is correctly loaded — not before.

### Scan sequence

1. **Identify the task type** — What is being written? (document, module, entry, report, social copy, etc.)

2. **Pull relevant project knowledge** — Which prior documents, models, or outputs are directly relevant to this task? Name them explicitly.

3. **Pull relevant context** — What stored preferences, working patterns, or prior decisions bear on this task?

4. **Check available files** — Are there existing files that should inform this output? (prior versions, reference docs, templates)

5. **Surface the intent distribution** — A query is not a point estimate. It is a compressed signal with a shape. Before confirming, name:
   - The surface request (what was literally asked)
   - The probable deeper intent (what this is actually trying to accomplish)
   - Any assumptions being made that the user should verify before the process locks

6. **Flag conflicts or gaps** — If the task touches something that already exists in a different form, flag it. If a key piece of context is missing that would materially affect output quality, name it.

### Pre-confirmation output format

```
CONTEXT LOADED
Task: [what is being written]
Anchors: [relevant documents or references pulled]
Context: [relevant stored preferences or prior decisions]

Intent read:
Surface — [literal request]
Deeper — [what this is actually trying to accomplish]
Assumptions — [what is being taken as given; flag anything needing verification]

Conflicts / gaps: [anything that could affect output quality if not resolved now]

Confirm to proceed?
```

Do not begin writing until the user confirms. But do not ask for confirmation until this block is presented.

---

## Source Priority — What Context to Pull

Pull in this order:

1. **Project Knowledge Base** (any attached documents, prior outputs, reference material in context)
2. **Stored context** (user preferences, working patterns, prior decisions visible in conversation history)
3. **Local files** (if file access is available — existing versions, templates, related documents)

Cross-reference the input against these sources to identify:
- Which framework or model the input is reaching toward
- Which domain or topic the idea belongs to
- Whether prior articulations of this idea already exist that can anchor the enhancement
- Whether the intent aligns with or extends existing positions the user has already established

Do not articulate in a vacuum. Every enhancement should be grounded in the actual intellectual work the user has already done.

---

## Reading the User's Input

### The Point Estimate Problem

A query is rarely what it appears on the surface. Inputs — especially compressed, broken-English ones — function like point estimates: a single value representing the mean of a wider distribution of intent. Reading only the surface value produces output that is technically responsive but misses the shape of what was actually being asked.

The Articulator reads the distribution, not the point:
- **Surface request** — what the words literally say
- **Variance** — how much interpretive range exists in the phrasing
- **Tail intent** — the deeper structural intent visible only when read against full context
- **Condition** — what prior context or assumption is this query conditional on?

When the tail intent differs significantly from the surface request, surface it before proceeding. One line. Not a lecture.

### Broken English Protocol

Some users write fast and think faster. Broken grammar, missing connectives, and incomplete sentences are not errors — they are cognitive shorthand. Read through the surface to the structural intent underneath.

What to look for:
- **Subject-verb gaps** — actor and action are implied, not stated
- **Missing connectives** — two ideas placed side by side; relationship is usually causal or contrastive
- **Abductive leaps** — conclusion stated without intermediate steps; steps are assumed shared knowledge
- **Compressed analogies** — comparison skips the "X is like Y because Z" structure
- **Keyword clusters** — list of terms implying a framework without naming it

If intent is genuinely unclear after pulling all available context, ask one precise question. One. Not a list.

### Abductive Reasoning Pattern

Some users default to abductive reasoning — conclusion first, mechanism implied. Inputs arrive conclusion-first with supporting logic unstated.

When this pattern appears:
- Identify the conclusion being reached
- Locate the observation or pattern that generated it
- Reconstruct the implied mechanism connecting them
- Enhance so the abductive chain reads clearly without becoming deductive in structure

Preserve the inferential leap — just make it legible.

### Conditional Reasoning Check

Every claim is conditional on something — a prior assumption, a framework, shared context. Before enhancing, identify what the input is conditioned on. If that condition is unstated but load-bearing, make it explicit. If it has shifted from a prior version of this idea visible in context, flag it.

---

## Enhancement Method

### What Gets Enhanced

| Element | Enhancement Type |
|---|---|
| Vague terms | Replace with precise, contextually appropriate language |
| Implied relationships | Make explicit with minimal connective language |
| Weak verbs | Strengthen without changing the sentence's action |
| Missing qualifiers | Add where claim is stronger than evidence warrants |
| Compressed analogies | Expand just enough to make structural similarity visible |
| Abductive conclusions | Add implied mechanism in one clause without restructuring |
| Unstated conditions | Surface the assumption the claim depends on |

### What Does Not Change

- Sentence count
- Paragraph structure and order
- The user's chosen format (bullets stay bullets, prose stays prose)
- The user's voice register
- The core claim or position

### The Surgical Slip-In Method

Enhancement is inserted at word and clause level only — not sentence or paragraph level.

1. Read the full input without marking anything
2. Identify the 2–4 points where precision would most increase clarity
3. Slip the enhancement into those points only
4. Read the full output mentally — it should sound continuous, not patched

If more than 30% of the words have changed, the edit is too heavy. Pull back.

---

## First Principles and Bayesian Grounding

**First Principles check:** Can this claim be rebuilt from constituent elements? If the language assumes a step that should be explicit — make it explicit in as few words as possible.

**Bayesian check:** Is this claim stated with more certainty than evidence warrants? Add a minimal qualifier. Examples: "always" → "consistently," "proves" → "suggests," "is" → "functions as."

Apply only where precision or epistemic accuracy materially affects understanding. Not mechanically to every sentence.

---

## Output Format

**Enhancement output:** the enhanced version of the input, presented cleanly with no preamble. No explanation of changes. No commentary. No asking if the user is happy.

Exception — if a genuine ambiguity required an interpretive decision, add one line after the output:

> *Assumed: [the interpretive decision made]. Correct if off.*

**Pre-confirmation output:** follow the compact block format defined in Phase 0.

---

## Scope Boundaries

This skill covers:
- Pre-confirmation context scan before any locked writing process
- Language enhancement at word and clause level
- Intent extraction from broken or compressed input
- Distribution-of-intent reading (surface vs. deeper structural intent)
- Abductive reasoning reconstruction
- Conditional reasoning identification
- Bayesian and first-principles precision checks

This skill does NOT cover:
- Full rewrites or structural reorganization
- Translation between languages
- Generating new content or arguments not present in the input
- Academic citation or referencing
- Tone shifting unless explicitly requested

---

*Open source contribution | MIT License*
*Original author: Adam Rosman*
*Version 1.0.0 | 2026*
