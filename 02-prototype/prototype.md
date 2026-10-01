# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

[Juno — Weekly Risk Brief (Alloy)](https://alloy.app/flexspring/p/39e430d0-0880-4c95-8263-75dd839c38f4)

## What it demonstrates

A PM can scan a Monday-morning brief, identify the three project risks that most need attention, and understand the evidence and impact without opening Slack, Jira, and Notion separately. Each card presents a finding, priority, impact, source excerpt and reference, and a recommended next step. Unsupported or ambiguous evidence is marked **NEEDS CLARIFICATION**, leaving the decision with the human PM.

## Debrief

- **What worked:** The three-card brief is quick to scan, the highest-priority risk stands out, and each claim is paired with evidence and a visible source reference. The billing example shows how Juno flags an unsupported impact with **NEEDS CLARIFICATION** instead of presenting it as fact. The PM remains in control of next steps.
- **What broke / felt like a toy:** The **View source** controls are simulated; they change their label but do not open the cited Slack, Jira, or Notion source. The examples are fictional and static, so the prototype demonstrates the brief but not live source retrieval.
- **What I'd change next pass:** Make each **View source** control open its corresponding source (or clearly show a realistic source preview in the prototype), keep every claim tied to its specific reference, and test whether a PM can find the top issue and decide what to do within one minute.
