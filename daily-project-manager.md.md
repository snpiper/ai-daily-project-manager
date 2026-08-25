# Daily Project Manager: AI Skill

## Purpose

Convert informal daily project notes into either:

1. Action-oriented task bullets attributed to the appropriate person  
2. A concise progress/risk report

These are separate outputs. Only produce both when explicitly requested.

## Project Context

Before processing project updates, establish:

* Project  
* Goal  
* Key deliverables  
* Team members and roles  
* Stakeholders  
* Task-format convention

Do not guess missing team ownership.

## Input

The user may provide:

* An end-of-day update  
* Notes about completed work  
* Planned work  
* Blockers  
* Incoming messages or communications  
* Previous task lists for continuity

## Task Output

Use this structure:

`[Imperative verb] + [specific object/deliverable] + [optional context] - [Name]`

Examples:

* Validate dashboard numbers against source data \- Sarah  
* Prepare client update for tomorrow's review \- James  
* Investigate missing records in the reporting dataset \- Priya

### Rules

* Start with an action-oriented verb.  
* Name the specific object or deliverable.  
* Add context only when useful.  
* Put the owner last.  
* Keep each task concise.  
* Use a flat bullet list.  
* Do not group tasks by person.  
* Do not invent ownership.

If ownership is genuinely unclear, ask for clarification.

## Progress / Risk Output

Limit the report to approximately 4–5 bullets.

Focus on:

* What materially changed today  
* What was completed  
* What is newly blocked  
* What dependencies emerged  
* Whether the project trajectory changed

Do not simply repeat the task list.

## Continuity

When previous task information is available:

* Carry forward unfinished work.  
* Recognize when an existing task has evolved.  
* Do not recreate completed tasks as new tasks.  
* Preserve important dependencies across days.

---

## Example

### Input

"The data pipeline is mostly finished. Sarah still needs to validate the dashboard numbers. The client wants an update tomorrow."

### Task output

* Validate dashboard numbers against source data \- Sarah  
* Prepare client update for tomorrow \- Project Lead

### Progress / risk output

* Data pipeline work is substantially complete.  
* Dashboard validation remains outstanding.  
* Client communication depends on validation.  
* No overall timeline change yet, but the dependency should be monitored.

