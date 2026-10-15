# Training Center — Prompt Engineering Library

**Final Project | Day 5 | Scenario B1: Learner Support Desk**  
**Date:** 2026-10-15  
**Library owner:** Training Center Prompt Library

## Project Overview

This project presents a reusable prompt library designed for the Learner Support Desk at a training center. It applies structured prompt engineering to five common support activities: answering inquiries, summarizing complaints, classifying requests, improving staff-written responses, and protecting learner information.

The library is organized for consistent outputs, clear staff workflows, and responsible AI use. Each template defines its purpose, task instructions, input variables, output expectations, and review safeguards.

## Project Objectives

- Standardize recurring learner-support tasks through reusable prompts.
- Produce clear, consistent responses and internal summaries.
- Base policy-related answers on the approved Training Center Facts.
- Preserve meaning while improving clarity and professionalism.
- Support learner privacy through anonymization and human review.
- Document prompt evaluation and example outputs in a dedicated test report.

## Selected Tasks and Templates

| Task | Template | Purpose |
| --- | --- | --- |
| T1 — Answer Inquiry | `TC-Answer-Inquiry-v1` | Draft a polite answer using approved training-center information. |
| T2 — Summarize Complaint | `TC-Summarize-Complaint-v1` | Condense a complaint while preserving its main issue, details, and request. |
| T3 — Classify Request | `TC-Classify-Request-v1` | Assign one suitable category and explain the classification. |
| T4 — Soften Draft | `TC-Soften-Draft-v1` | Rewrite a harsh or unclear staff draft in a professional tone. |
| T5 — Mask Learner Details | `TC-Mask-Learner-Details-v1` | Replace identifying details with consistent anonymous codes. |

## Prompt Design Approach

The templates follow the **RACE** structure:

- **Role:** Establishes the assistant's specific support function.
- **Action:** Describes the steps to perform.
- **Context:** Supplies approved facts or the task's source material.
- **Expectation:** Specifies language, tone, format, and quality rules.

Templates also include reusable variables and explicit constraints to promote predictable and reviewable outputs.

## Project Structure

```text
TC_Final_Project/
├── README.md
└── PE_Library_Mshary/
    ├── library_index.md
    ├── library_guide.md
    ├── Test_Results_Report.pdf
    ├── templates/             # Five reusable task templates
    ├── blocks/                # Approved Training Center Facts
    ├── rules/                 # Responsible-use rules
    └── evidence/              # Output examples and test screenshots
```

## How to Use the Library

1. Open `PE_Library_Mshary/library_index.md` and select the template matching the learner-support task.
2. Read the instructions in `library_guide.md` and copy the chosen template.
3. Supply the required input and set any relevant variables such as language, tone, or maximum length.
4. For policy-related tasks, refer to the approved facts in `blocks/`; preserve the template's safety rules.
5. Review the output for factual accuracy, completeness, privacy, and appropriate wording before using it.
6. Consult `Test_Results_Report.pdf` for the documented evaluation approach and supporting screenshots.

## Testing and Documentation

The test report organizes evaluation around three complementary areas: **prompt quality (RACE)**, **template quality (reusability and safeguards)**, and **output quality (accuracy, completeness, and responsible use)**. Supporting screenshots are retained in the `evidence/` folder. The report is the reference for individual observations and recorded results.

## Responsible AI Practices

The library emphasizes approved information, privacy-conscious handling of learner details, consistent use of anonymized examples, and human review of generated drafts. AI-generated content supports staff workflows; it does not independently approve registrations, refunds, certificates, or other administrative decisions.

## Deliverables

The submission contains five task templates, a shared facts block, responsible-use rules, a library index, an operating guide, a test results report, and supporting evidence files.

---
**Training Center Prompt Library · Day 5 Final Project · 2026-10-15**
