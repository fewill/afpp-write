---
name: write-question
description: Writes a draft test question for the AFPP test suite. Use when the user asks to write a test question, or when you want to write a test question for the user.
---

# AFPP Item Writing Skill

## Before Writing

1. **Confirm the KSA.** If the user has not specified one, prompt with the valid list from `sources/afpp-ksa-outline.md`.
2. **Check for existing questions.** Review the relevant `drafts/ksa_{number}_v*_draft.txt` and `entered-questions.txt` to avoid repeating topics already covered.
3. **Identify a source passage.** Locate a specific passage in an approved source document (see below) that supports the question. Do not write the question without a source.

---

## Required Question Format

Every question must include all of the following elements, in this order:

```
Q# — [Factual | Procedural | Conditional] / [JSQ | SQ]

Skill Rating: [JSQ | SQ]
Cognitive Level: [Recall | Application | Analysis]
Rationale: [One sentence justifying the skill rating — what makes this JSQ vs. SQ knowledge]

[Complete interrogative stem ending in ?]

  A. [Response]
  B. [Response]
  C. [Response]

Answer: [A | B | C]

Source: [Document]. [Publisher]. [Chapter/Section], [section heading], p. [PDF page number].
```

---

## Skill Ratings

| Rating | Experience | Description |
|--------|-----------|-------------|
| JSQ | ~2 years | Just Sufficiently Qualified — working knowledge a practitioner develops in ~2 years on the job |
| SQ | ~5 years | Senior Qualified — deeper expertise requiring ~5 years of experience |

---

## Cognitive Levels

| Type | Level | Description |
|------|-------|-------------|
| Factual | Recall | Tests knowledge of a specific fact, definition, or rule |
| Procedural | Application | Tests ability to apply a procedure or rule to a scenario |
| Conditional | Analysis | Tests ability to identify the condition under which a rule applies |

---

## Style Rules

- **Stem:** Use a complete interrogative sentence ending with `?`. Do not include information that hints at or teaches the correct answer — ask only what is being tested. *Wrong: "Which action can a receive-only participant perform even though it cannot initiate credit transfers?" Right: "Which action is a receive-only participant allowed to perform?"*
- **Voice:** Active voice, third person throughout.
- **Terminology:** Use "financial institution" — never "bank" or "credit union."
- **Capitalization:** Write `NOT` in all caps when used for emphasis in a response. Do not use bold or underline in responses.
- **Trademarks:** No trademark symbols (no ®, ™).
- **Parallel structure:** All three responses must be grammatically parallel and roughly equal in length. Avoid one response that is notably longer than the others (telegraphs the correct answer).
- **Distractors:** Each distractor must be plausible but clearly wrong on close reading. Avoid trivial, absurd, or overlapping distractors.
- **One correct answer:** There must be exactly one defensible correct answer supported by the source text.

---

## Answer Position Distribution

When writing multiple questions for a set, target **A(3), B(3), C(3)** across nine questions. For a single question, vary the position from any recently written questions to avoid a pattern.

---

## Source Citation Format

Citations must include the document name, publisher, chapter or section, section heading, and **PDF page number** (not line number from the text file).

**Examples:**
- `AFPP Handbook (2026). Nacha. Chapter 1 – Fundamentals of Faster Payments, "Customer credit transfers and requests for payment" section, p. 47.`
- `FedNow Service Operating Procedures (June 2025). Federal Reserve Banks. Section 12.a – RFP Warranties, p. 50.`
- `Operating Circular 8 (April 1, 2026). Federal Reserve Banks. FedNow Service. Section 8.2, p. 11.`
- `12 CFR Part 1005 (Regulation E). Consumer Financial Protection Bureau. Section 1005.11(c), p. 15.`

To convert a line number from a `.txt` source file to a PDF page number, use pdftotext to locate the phrase on the correct physical page, then confirm the printed page number from the page footer.

---

## Approved Source Documents

All source documents are in the `sources/` directory:

| File | Coverage |
|------|----------|
| `2026-AFPP-HANDBOOK-FINAL.pdf` | Primary reference — all KSAs |
| `062425-fednow-service-operating-procedures.pdf` | FedNow rules, warranties, message types |
| `040126-operating-circular-8.pdf` | FedNow security procedures, indemnification |
| `010224-operating-circular-4.pdf` | Federal Reserve payment services |
| `RTP_Participation_Rules_Effective_07-21-2025.pdf` | RTP agreements, participant obligations |
| `Introduction_to_the_RTP_System_October_2020.pdf` | RTP message types, overlay services |
| `12 CFR Part 1005-Reg-E.pdf` | Regulation E — consumer error resolution |
| `12-CFR Part-210_RegJ.pdf` | Regulation J |
| `PCIDSS_QRGv3.pdf` | PCI DSS — card network security |
| `ffiec_itbooklet_retailpaymentsystems.pdf` | FFIEC examination guidance |
| `visa-rules-public.pdf` | Visa Direct requirements |
| `Glossary of Terms _ Faster Payments Council.txt` | FPC terminology |
| `instant_payment_systems_compliance_guidance_brochure.pdf` | BSA/AML compliance |
