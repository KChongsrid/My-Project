---
name: quick-code-explanation
description: Explain a code snippet or diff in three beginner-friendly bullets. Use when the user wants a quick explanation of code or changes.
---

# Quick Code Explanation

## Goal
Explain the provided code snippet or diff in plain,
beginner-friendly terms.

## Workflow
1. Read the supplied code. If none is provided or identified,
   ask the user for the snippet, diff, or file.
2. Identify the core logic. For a diff, focus on what changed
   and how it affects behavior.
3. Output exactly three bullets:
   - **What it does:** Summarize the purpose or change.
   - **Key element:** Explain the most important function,
     variable, or component.
   - **Edge case or bug:** Highlight a relevant concern.
     If none is apparent, say so. Do not invent an issue.

Define unfamiliar terms briefly and distinguish confirmed
behavior from assumptions. Do not modify code unless asked.
