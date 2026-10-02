# JobHunt — AI-Powered Job Search Agent

JobHunt is an AI-powered job-search automation system that continuously searches selected company career boards, filters irrelevant opportunities, evaluates job-candidate fit using an LLM, and generates personalized application material for the most relevant roles.

The goal is simple:

> Turn hundreds of job postings into a small, actionable shortlist.

The system does **not** automatically apply to jobs. It keeps the final decision and application submission with the user.

---

## Overview

Traditional job searching requires repeatedly:

- Opening multiple company career pages
- Searching for relevant roles
- Checking location and seniority
- Reading long job descriptions
- Comparing roles against a resume
- Writing customized application material

JobHunt automates the repetitive parts of this process.

```text
Company Career Boards
        │
        ▼
   Job Collection
        │
        ▼
Deterministic Filtering
        │
        ├── Title matching
        ├── Location matching
        ├── Freshness check
        └── Seniority filtering
        │
        ▼
    LLM Screening
        │
        ▼
   Fit Score + Reason
        │
        ▼
    Top Shortlist
        │
        ▼
   LLM Application Kit
        │
        ├── Fit Summary
        ├── Tailored Resume Bullets
        ├── Skill Gaps
        ├── Cover Note
        └── Questions to Ask
        │
        ▼
     Email Digest
