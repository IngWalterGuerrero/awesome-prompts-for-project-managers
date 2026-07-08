---
title: Schedule Analysis Prompts
category: llm-prompts
tools: [ChatGPT, Claude, Gemini]
level: advanced
language: en
tags: [schedule, delay-analysis, critical-path]
---

# Schedule Analysis Prompts

## Category

llm-prompts

## Recommended Use

Analyze schedule delays, critical path issues, recovery options, and project timeline risks.

## Ideal For

- Weekly schedule reviews
- Recovery plans
- Delay explanations
- Executive updates

## Compatible Tools

- ChatGPT
- Claude
- Gemini

## Level

advanced

## Variables

- `[PROJECT_CONTEXT]`
- `[SCHEDULE_STATUS]`
- `[CRITICAL_PATH]`
- `[DELAYS]`
- `[CONSTRAINTS]`

## Prompt

```text
Analyze the schedule status for this project. Project context: [PROJECT_CONTEXT]. Schedule status: [SCHEDULE_STATUS]. Critical path: [CRITICAL_PATH]. Delays: [DELAYS]. Constraints: [CONSTRAINTS]. Identify the main schedule risks, explain impacts on milestones, propose recovery actions, and prepare an executive summary with decisions needed.
```

## Example Use

```text
Analyze the schedule status for a substation project delayed by procurement and access constraints.
```

## Expected Output

A schedule analysis with delay drivers, milestone impact, recovery options, and decision points.

## Notes

Include baseline dates and current forecast dates whenever possible.
