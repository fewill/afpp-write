---
name: evaluate-question
description: Evaluates an already-written AFPP test question against format, style, and content standards. Use when the user asks to evaluate, review, or check a question.
---

# AFPP Item Evaluation Skill

When evaluating a question, work through each check below in order and report findings. Flag every issue — do not skip checks because a previous check failed.

---

## 1. Format Completeness

Confirm all required elements are present:

- [ ] Skill Rating (JSQ or SQ)
- [ ] Cognitive Level (Recall, Application, or Analysis)
- [ ] Rationale (one sentence justifying the skill rating)
- [ ] Complete interrogative stem ending in `?`
- [ ] Exactly three responses labeled A, B, C
- [ ] Answer line identifying the correct response
- [ ] Source citation with document, section, and PDF page number

---

## 2. Stem Quality

- [ ] The stem is a complete interrogative sentence (not a fill-in-the-blank or true/false)
- [ ] The stem does NOT teach the test taker — it does not include information that hints at or narrows the correct answer. *Red flag: clauses like "even though X" or "despite Y" that restate the sub-competency.*
- [ ] The stem uses active voice and third person
- [ ] The stem uses "financial institution" — not "bank" or "credit union"
- [ ] No trademark symbols (no ®, ™)

---

## 3. Response Quality

- [ ] Exactly one defensible correct answer — verify against the cited source text
- [ ] All three responses are grammatically parallel
- [ ] All three responses are roughly equal in length (no response is notably longer, which telegraphs the answer)
- [ ] Distractors are plausible but clearly wrong on close reading
- [ ] No trivial, absurd, or overlapping distractors
- [ ] `NOT` is in all caps where used for emphasis
- [ ] No bold or underline formatting in responses

---

## 4. Skill Rating and Cognitive Level

- [ ] The skill rating (JSQ vs. SQ) is appropriate for the knowledge tested:
  - JSQ: working knowledge a practitioner develops in ~2 years
  - SQ: deeper expertise requiring ~5 years
- [ ] The cognitive level matches the question type:
  - Factual / Recall: tests a specific fact, definition, or rule
  - Procedural / Application: tests applying a rule to a scenario
  - Conditional / Analysis: tests identifying when/under what condition a rule applies
- [ ] The rationale explains *why* this is JSQ vs. SQ knowledge specifically

---

## 5. Source Validation

- [ ] The source is an approved document (see `sources/` directory)
- [ ] The citation includes a PDF page number (not a line number from a `.txt` file)
- [ ] The cited passage actually supports the correct answer — confirm by reading the source
- [ ] The correct answer cannot be derived from a different, contradictory passage in the same source

---

## 6. Answer Position

- [ ] Note the answer position (A, B, or C) and flag if this question is part of a set where that position is already overrepresented

---

## Reporting Format

Report findings as:

**PASS** — if all checks pass with no issues.

**ISSUES FOUND** — list each failing check with a brief explanation and a suggested fix. Use this structure:

```
❌ [Check name]: [What is wrong]
   Fix: [Specific suggested correction]
```

For minor advisory notes (not blocking issues), use:

```
⚠️  [Check name]: [Advisory note]
```

If the source citation uses line numbers instead of a page number, offer to convert it.
