# Design Note #003 — Turning Expert Pricing Intuition into a Human-AI Decision Workflow

## Overview

This Design Note explores how expert pricing intuition can be translated into a structured Human-AI decision workflow.

Using the Harvard Business School case *Flashion: Art vs. Science in Fashion Retailing* as the analytical context, the experiment combines descriptive analysis, interpretable modeling, pricing scenario simulation, and human judgment.

The objective is not automated pricing. It is to turn tacit expert knowledge into a decision process that can be tested, documented, challenged, and gradually accumulated as organizational knowledge.

## Problem

Flash-sale retail creates a difficult pricing environment:

- Selling windows are short.
- Initial pricing decisions matter.
- Historical data can inform demand.
- Important contextual signals may remain outside the dataset.
- Experienced buyers possess tacit knowledge that models may not capture.

The key question is: how should expert judgment and analytical models work together?

## Case Study

English case study: [ashdaily.blog](https://ashdaily.blog/design-note-003-turning-expert-pricing-intuition-into-a-human-ai-decision-workflow/)

## Workflow

Validate the business assumption → Define the business objective → Translate intuition into an interpretable model → Simulate alternative pricing scenarios → Keep human judgment in the final decision → Record overrides and reasoning as new organizational knowledge

## Human-AI Division of Labor

### Human

- Define the business problem and form hypotheses.
- Select meaningful variables and challenge model assumptions.
- Interpret results and make the final decision.

### AI

- Organize data and assist with analytical code.
- Run statistical calculations and test hypotheses.
- Simulate pricing scenarios and support comparison and visualization.

## Core Principle

The model is decision support, not decision truth:

Expert intuition → Testable hypothesis → Data analysis → AI-supported simulation → Human judgment → Recorded rationale

## Limitations

This Design Note is an analytical extension of the Harvard Business School case *Flashion: Art vs. Science in Fashion Retailing*. The regression analysis, pricing simulations, and Human-AI workflow are part of an independent analytical experiment; they do not indicate that Flashion implemented the proposed AI pricing workflow. The analysis does not establish causal effects between price and sell-through.

## Files

- [`prompt-template.md`](./prompt-template.md) — reusable prompt for a human-led pricing decision workflow
