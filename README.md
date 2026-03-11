# AFPP Exam Item Writing

Question development workflows, plans, and drafts for the
[Accredited Faster Payments Professional (AFPP)](https://www.nacha.org/afpp) certification exam.

## Overview

This repository contains item writing work product for assigned KSAs (Knowledge, Skills, and Abilities)
from the AFPP exam blueprint. Each KSA follows a structured three-stage workflow:

1. **Prompt** — defines the sub-competencies, source materials, and constraints for the question set
2. **Plan** — maps each question to a specific source passage, documents the answer key, and pre-checks style compliance
3. **Draft** — final question text with Skill Rating blocks, three-option responses, answer, and source citations

## Question Format

Each question includes:

- **Skill Rating** — JSQ (Just Sufficiently Qualified, ~2 years experience) or SQ (Senior Qualified, ~5 years experience)
- **Cognitive Level** — Recall (Factual), Application (Procedural), or Analysis (Conditional)
- **Rationale** — justification for the skill rating assignment
- **Stem** — complete interrogative sentence
- **Responses A, B, C** — one correct answer and two defensible distractors
- **Source citation** — authoritative document, section, and PDF page number

Each nine-question set targets the distribution: Factual (2 JSQ + 1 SQ), Procedural (2 JSQ + 1 SQ),
Conditional (1 JSQ + 2 SQ), with answer positions balanced A(3), B(3), C(3).

## KSAs Covered

| KSA | Topic | Versions |
|-----|-------|---------|
| 1004 | Types and functions of participation | v1, v2 |
| 3001 | Faster payments risk management fundamentals | v1, v2 |
| 3003 | Customer onboarding programs, policies, and procedures | v2 |
| 4004 | Faster payments overlay and value-added services | v1, v2 |
| 5002 | Laws and regulations applicable to faster payments | v1, v2 |
| 5003 | Error resolution protections, rights, and liabilities | v1, v2 |
| 5004 | Role of client/customer agreements and disclosures | v1, v2 |

## File Naming Convention

```
ksa_{number}_v{n}_prompt.txt   — writing prompt and sub-competency list
ksa_{number}_v{n}_plan.txt     — source passages, question map, answer key
ksa_{number}_v{n}_draft.txt    — final question drafts
```

## Source Materials

All questions are grounded in authoritative sources including:

- AFPP Handbook (2026)
- FedNow Service Operating Procedures (June 2025)
- Operating Circular 4 and Operating Circular 8
- RTP Participation Rules (effective July 21, 2025)
- Introduction to the RTP System (October 2020)
- Nacha Operating Rules (via AFPP Handbook)
- 12 CFR Part 1005 (Regulation E)
- 12 CFR Part 210 (Regulation J)
- PCI DSS Quick Reference Guide v3
- FFIEC IT Booklet — Retail Payment Systems
- Visa Rules (public)
- FPC Glossary of Terms
- Instant Payments Compliance Guidance Brochure

## Submission

`selected-question-drafts.txt` contains the seven questions selected for submission to the AFPP item bank,
one per assigned KSA, with validated PDF page number citations.
