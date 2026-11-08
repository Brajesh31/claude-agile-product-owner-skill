# claude-agile-product-owner-skill

A Claude Code skill for product ownership, backlog management, user story writing, sprint planning, and delivery tracking.

## Overview

This skill helps product owners turn product goals into actionable work for delivery teams. It focuses on clear user stories, measurable acceptance criteria, backlog prioritization, sprint capacity, and review of delivery outcomes.

## Main Capabilities

- Break epics into manageable user stories.
- Write INVEST-oriented stories.
- Generate acceptance criteria.
- Prioritize backlog items.
- Plan sprint capacity.
- Track velocity and delivery metrics.
- Prepare stakeholder communication.
- Support agile ceremonies.
- Identify dependencies and delivery risks.

## User Story Structure

A useful story describes:

- Who needs the capability.
- What they need to do.
- Why the outcome matters.
- Acceptance criteria that can be verified.
- Dependencies and constraints where relevant.

Example:

```text
As a project member,
I want to filter tasks by status,
so that I can focus on work that needs attention.

Acceptance criteria:
- A user can select one or more statuses.
- The task list updates to match the selected filters.
- Clearing filters restores the full task list.
- Empty results are communicated clearly.
```

## Installation

```bash
git clone https://github.com/Brajesh31/claude-agile-product-owner-skill.git ~/.claude/skills/agile-product-owner
```

## Usage

Invoke the skill for backlog and sprint work:

```text
/agile-product-owner
```

Provide the product goal, user roles, existing backlog, team capacity, sprint duration, and delivery constraints.

## Included Utility

The repository includes `scripts/user_story_generator.py` for generating stories and supporting sprint-planning workflows.

Run the script with the documented options:

```bash
python scripts/user_story_generator.py
```

Review its help and expected input before using it on a project backlog.

## Recommended Workflow

1. Confirm the product objective.
2. Break the objective into epics or outcomes.
3. Create focused user stories.
4. Add testable acceptance criteria.
5. Identify dependencies and risks.
6. Estimate effort with the delivery team.
7. Prioritize by value, urgency, and effort.
8. Plan work within realistic sprint capacity.
9. Track delivery and impediments.
10. Review outcomes and update the backlog.

## Story Quality Checklist

- Story describes a real user need.
- Scope is small enough to estimate.
- Acceptance criteria are observable.
- Dependencies are visible.
- Edge cases are considered.
- Technical tasks are connected to product outcomes.
- The team understands the expected result.

## Repository Contents

- `SKILL.md`: Main product ownership workflow.
- `scripts/user_story_generator.py`: Story generation and sprint utility.
- `README.md`: Backlog and delivery guidance.

## Practical Principle

A backlog full of vague stories is not a plan. Make work understandable and testable before asking a team to estimate or commit to it.
