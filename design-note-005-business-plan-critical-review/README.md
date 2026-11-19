# Design Note #005 — Using AI to Challenge a Business Plan

## Overview

This Design Note documents an AI-assisted business-planning workflow based on a proposed Chinese-language ski school in Zao, Japan.

The objective was to explore how AI can help structure an early-stage business idea, identify weak assumptions, and improve a business plan through critical review.

Instead of accepting the first AI-generated output, the workflow introduces a second-stage challenge in which AI acts as a critical investor and business-model analyst.

## The Problem

Early-stage business ideas can contain:

- Unverified financial assumptions.
- Overly optimistic revenue projections.
- Unclear pricing structures.
- Business models dependent on the founder's working hours.
- Operational and regulatory risks that have not been fully examined.

Generating a business plan is relatively easy with AI. Evaluating whether its assumptions make sense is harder.

## Workflow Architecture

The workflow consists of three stages:

### 1. Draft

Ask AI to structure the initial business concept into:

- Business structure.
- Financial planning.
- Human resources.
- Digital marketing.
- Risk management.

### 2. Challenge

Ask AI to act as a critical investor and identify:

- Scalability problems.
- Unrealistic financial assumptions.
- Missing pricing strategies.
- Legal and operational risks.
- Gaps in the marketing and customer-acquisition model.

### 3. Revise

Use the critical review to reconstruct the business plan with:

- Scenario-based financial planning.
- A product ladder.
- A content-driven business model.
- A marketing funnel.
- An expanded risk register.
- A KPI framework.

## Human–AI Collaboration

| Component | Responsibility |
|---|---|
| Human | Define the business idea, set constraints, evaluate recommendations, and make decisions. |
| AI | Structure information, generate hypotheses, challenge assumptions, and propose revisions. |
| Human Review | Verify financial inputs, legal requirements, operational feasibility, and final decisions. |

AI-generated recommendations are not automatically accepted as facts.

## Key Design Principles

1. Separate initial assumptions from validated information.
2. Ask AI to challenge its own previous output.
3. Use multiple financial scenarios instead of relying on one optimistic forecast.
4. Identify the difference between a labor-based business and a scalable business model.
5. Preserve human responsibility for legal, financial, and operational decisions.
6. Treat AI-generated revisions as hypotheses requiring further validation.

## Case-Specific Planning Assumptions

The original planning exercise included these figures:

| Item | Value | Classification |
|---|---:|---|
| Initial startup capital | JPY 8 million | Initial planning estimate |
| Revised startup capital | JPY 9 million | AI-proposed revision |
| Original utilization rate | 65% | Initial assumption |
| Pessimistic utilization | 30% | Scenario assumption |
| Base utilization | 40% | Scenario assumption |
| Optimistic utilization | 60% | Scenario assumption |

These figures are not verified market data or actual business performance.

## Limitations

- No actual ski-school launch is demonstrated.
- No verified customer-acquisition or revenue data is available.
- Financial projections have not been independently validated.
- Japanese visa and employment requirements require professional legal verification.
- The workflow demonstrates planning and critical analysis, not proven business feasibility.

## Reusable Prompt

See [`prompt-template.md`](./prompt-template.md) for the reusable business-planning and critical-review prompt.

## Source

English case study: [ashdaily.blog](https://ashdaily.blog/design-note-005-using-ai-to-challenge-a-business-plan-a-critical-review-of-a-japanese-ski-school-startup/)

Original Chinese article: [Using AI to Build a Japanese Ski School Business Plan](https://ashdaily.blog/ai-poweredskibusinessplan/)

## Notes

- Design Note #005
- Ash AI Workflow
- Status: READY_FOR_HUMAN_REVIEW
- Publication Status: Not Published

---

**Core Takeaway**

AI should not merely help generate a business plan. It should also help identify why that plan might fail.

Human judgment remains responsible for deciding what is credible, what needs verification, and what should be changed.
