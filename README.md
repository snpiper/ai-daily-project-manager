# AI Daily Project Manager

An AI workflow experiment that converts messy end-of-day project updates into structured action items and a concise progress/risk report.

## The problem

Project updates are often written as informal notes:

> "The data pipeline is mostly done. Sarah still needs to validate the dashboard numbers. The client wants an update tomorrow."

Important information can easily get lost:

* What actually needs to be done?
* Who owns it?
* What is blocked?
* What changed today?
* Is there a project risk that needs attention?

## The experiment

This workflow takes an informal project update and produces two independent outputs:

### 1. Action items

Clear, specific tasks with an owner.

Example:

* Validate dashboard numbers - Sarah
* Prepare client update for tomorrow - Project Lead

### 2. Progress / risk report

A short view of what changed and what needs attention.

Example:

* Data pipeline work is substantially complete.
* Dashboard validation is still pending.
* Client communication depends on validation.
* No overall timeline change yet, but the dependency should be monitored.

## Design principles

The workflow is designed around several principles:

* **Do not invent information.** If ownership is unclear, ask rather than guess.
* **Use specific actions.** Avoid vague tasks such as "work on dashboard."
* **Preserve continuity.** Unfinished work should carry forward rather than disappear.
* **Separate tasks from reporting.** A task list and a project-health report serve different purposes.
* **Keep outputs concise.** The goal is to make project updates easier to act on, not produce another long report.

## Why I built it

This is an experiment in applying AI to everyday project-management workflows.

The interesting part isn't simply generating text. It is designing the rules that determine:

1. What information the AI should extract
2. What it should ignore
3. When it should make an inference
4. When it should ask for clarification
5. How the output should be structured
6. How information should persist from one day to the next

## What I'm exploring

This is part of a broader exploration of using AI to improve business and project workflows.

Future versions could explore:

* Automatic identification of blockers
* Detecting changes in project trajectory
* Connecting tasks across multiple days
* Generating stakeholder-specific updates
* Integrating with project-management tools
* Measuring whether the workflow actually saves time

## Status

**Interesting experiment — Version 1**

This project is intentionally small. The goal is to learn by building, testing, and iterating rather than trying to create a production-ready application immediately.
