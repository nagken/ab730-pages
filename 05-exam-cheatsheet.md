# AB-730 Exam Cheatsheet

> Print-friendly. The 60-second reset before exam time.

## The 3 domains

| Domain | Weight | Key skills |
|---|---|---|
| Generative AI Fundamentals | 33% | LLMs, hallucination, responsible AI, M365 vs web Copilot |
| Manage Prompts and Conversations | 33% | GCSE prompt pattern, iteration, anti-patterns |
| Draft and Analyze Content | 34% | Copilot in Word/Excel/PPT/Outlook/Teams, citations, sensitivity |

## Microsoft AI tool selector

| Need | Tool |
|---|---|
| Free, web-grounded chat | Microsoft Copilot (free) |
| Tenant-grounded for work | Microsoft 365 Copilot |
| Build a custom chatbot | Copilot Studio |
| Develop AI app | Azure AI Foundry |
| Code completions | GitHub Copilot |

## App selector for business tasks

| Task | App |
|---|---|
| Long doc to slides | PowerPoint |
| Email triage | Outlook |
| Meeting recap | Teams |
| Spreadsheet trends | Excel (table) |
| Document drafting | Word |
| Web research | Microsoft Copilot (web) |

## Prompt pattern (GCSE)

| Letter | Means | Example |
|---|---|---|
| G | Goal | "Draft a 100-word announcement" |
| C | Context | "to the product team about Q2 delay" |
| S | Source | "based on attached project plan" |
| E | Expectations | "tone: confident; format: 1 paragraph + bullets" |

## Responsible AI - 6 principles

1. Fairness
2. Reliability and safety
3. Privacy and security
4. Inclusiveness
5. Transparency
6. Accountability

## Hallucination mitigation

1. Use grounded tools (M365 Copilot).
2. Ask for citations.
3. Cross-check with primary source.
4. Don't blindly publish.

## Sensitivity labels

- Microsoft Purview labels (Confidential / Highly Confidential / etc.) flow through Copilot output.
- Output inherits highest sensitivity label of cited sources.

## Question-pattern translator

| Wording | Answer |
|---|---|
| "AI invented a fact" | Hallucination |
| "use my company's email as context" | M365 Copilot (not web) |
| "AI must work for users with disabilities" | Inclusiveness |
| "user must know they are talking to AI" | Transparency |
| "find trends in a spreadsheet" | Copilot in Excel + table |
| "summarize a missed meeting" | Copilot in Teams |
| "weak prompt got generic output" | Add Goal/Context/Source/Expectations |
| "label stays after Copilot summarizes" | Sensitivity labels via Purview |

## 60-second reset

1. Three domains, ~33% each.
2. M365 Copilot = your work data; Web Copilot = public web.
3. Six responsible-AI principles.
4. GCSE prompt pattern: Goal, Context, Source, Expectations.
5. Always cite + verify; you are accountable.
6. Sensitivity labels flow through.

---

[Master Index](00-MASTER-INDEX.md)
