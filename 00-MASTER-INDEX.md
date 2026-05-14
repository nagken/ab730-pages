# AB-730 - Microsoft Certified: AI Business Professional - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/ai-business-professional/

## The 4 Exam Domains - Mind Map

```mermaid
mindmap
  root((AB-730))
    Generative AI Fundamentals
      What is Generative AI
        LLMs vs traditional AI
        Tokens Embeddings
        Prompts and Completions
        Hallucinations Limitations
      AI Patterns
        Q and A
        Summarization
        Drafting and Rewriting
        Translation
        Code generation
      Responsible AI Principles
        Fairness Reliability
        Privacy Security
        Inclusiveness
        Transparency Accountability
    Microsoft AI Portfolio
      Microsoft 365 Copilot
        Word Excel PowerPoint
        Outlook Teams OneNote
        Business Chat Loop
        Copilot Pages
      GitHub Copilot
        Code completion
        Copilot Chat
        Copilot for PRs
      Industry-Specific Copilots
        Sales Copilot
        Service Copilot
        Finance Copilot
      Copilot Studio
        Custom copilots
        Agents Topics Plugins
      Azure AI Foundry
        Model catalog
        Prompt flow
        Custom solutions
    Apply AI to Work
      Productivity Use Cases
        Email drafting
        Meeting summaries
        Document analysis
        Data insights Excel
      Collaboration
        Teams meeting recap
        Channel summary
        Loop pages co-creation
      Content Creation
        PowerPoint design
        Marketing copy
        Social media posts
      Decision Support
        Trend analysis
        Forecasting hints
        Risk identification
    Adoption and Governance
      Prompt Crafting Basics
        Goal Context Source Expectations
        Iterative refinement
        Examples and constraints
      Data Protection
        Tenant boundary
        Commercial Data Protection
        DLP policies
        Sensitivity labels
      Adoption Strategy
        Personas Champions
        Use case discovery
        Training and enablement
        Measuring impact
      Compliance and Trust
        EU AI Act basics
        GDPR considerations
        Audit and monitoring
```

## Domain map

```mermaid
flowchart LR
    Master["AB-730 Master Index"]
    D01["Generative AI Fundamentals"]
    Master --> D01
    D02["Manage Prompts and Conversations with AI"]
    Master --> D02
    D03["Draft and Analyze Business Content with AI"]
    Master --> D03
    D01 --> S1[Capabilities + limits]
    D01 --> S2[Responsible AI]
    D02 --> S3[Prompt engineering]
    D02 --> S4[Iteration + context]
    D03 --> S5[Documents, email, summaries]
    D03 --> S6[Data analysis with Copilot]
```

## Domain weights

```mermaid
pie showData
    title AB-730 domain weights
    "Generative AI Fundamentals" : 33
    "Manage Prompts and Conversations with AI" : 33
    "Draft and Analyze Business Content with AI" : 34
```

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Generative AI Fundamentals :t1, 0, 1d
    Manage Prompts and Conversations with AI :t2, after t1, 2d
    Draft and Analyze Business Content with AI :t3, after t2, 2d
```

## What this exam tests

AB-730 is for **business users**, not developers or admins. It validates that you can:
- Use Microsoft 365 Copilot, Copilot Chat, and other GenAI tools effectively to do real business work.
- Understand the **basics** of how generative AI works (LLMs, hallucinations, grounding) without coding knowledge.
- Apply **responsible AI principles** when using AI tools at work.
- Craft **effective prompts** to get useful business outputs.
- Use AI to **draft, analyze, and summarize** business content (emails, docs, meetings, data).

## Top 12 things to know

1. **Generative AI** creates new content from a prompt; trained on massive datasets.
2. **LLMs hallucinate** - they invent plausible-but-wrong facts. Always verify.
3. **Copilot in Microsoft 365** is grounded in your tenant data via the Microsoft Graph - more accurate than web Copilot for work tasks.
4. **Microsoft Copilot (free, web)** uses public web data + GPT models. No tenant grounding.
5. **Responsible AI** = fairness, reliability, privacy, inclusiveness, transparency, accountability.
6. **Effective prompts** include: goal, context, source/data, format, tone, length.
7. **Iterate** prompts: rarely is the first answer perfect. Refine.
8. **Citations** in Copilot's grounded answers link to the underlying file - click to verify.
9. **Sensitivity labels** (from Microsoft Purview) flow through Copilot output.
10. **You are responsible** for what you publish from AI output.
11. **Don't paste regulated data** (PHI, PCI) into web Copilot.
12. **Copilot Chat (web grounding)** can use Bing search; M365 Copilot uses your work data.

## Common gotchas

- Web Copilot does NOT see your work files; M365 Copilot does.
- Copilot summaries can omit important nuance.
- AI-generated images may be biased without prompt guardrails.
- Copilot in Excel needs a structured table.
- Copilot in Outlook drafts emails in your voice based on past sent items - review tone.

## Supporting pages

- [05-exam-cheatsheet.md](05-exam-cheatsheet.md)
- [06-references.md](06-references.md)
- [07-extra-ab730-concepts.md](07-extra-ab730-concepts.md)
- [08-learn-summaries.md](08-learn-summaries.md)
- [09-arch-ab730.md](09-arch-ab730.md)
- [11-microsoft-resources.md](11-microsoft-resources.md)
- [12-glossary.md](12-glossary.md)
- [13-flashcards.md](13-flashcards.md)
- [14-pitfalls.md](14-pitfalls.md)
- [15-hands-on-labs.md](15-hands-on-labs.md)
- [16-architecture-center.md](16-architecture-center.md)
- [17-copilot-quiz.md](17-copilot-quiz.md)
- [99-practice-assessment.md](99-practice-assessment.md)
- [99-video-tutorials.md](99-video-tutorials.md)

---

**Next:** open [01-genai-fundamentals.md](01-genai-fundamentals.md)
