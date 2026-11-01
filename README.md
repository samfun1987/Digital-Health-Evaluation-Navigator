# Digital Health Evaluation Navigator

A Claude skill that guides you through evaluating a digital health product. It is based on the UK OHID / GOV.UK framework [**Evaluating digital health products**](https://www.gov.uk/government/collections/evaluating-digital-health-products).

The skill starts from your real-world goal, not from a preferred method. It then works through seven stages, from goal and scope to conclusions and next action. It keeps a record of what you have agreed and challenges the plan from two angles: a methods expert, and the stakeholder whose decision the evidence needs to inform.

> Real-world goal → agreed context → evaluation questions → evidence approach → executable plan → defensible interpretation → decision or next action

## What's in this repository

| File | Purpose |
|---|---|
| [`SKILL.md`](SKILL.md) | The skill itself: instructions Claude follows when the skill is active (v0.3.1) |
| [`docs/instructions-for-use.md`](docs/instructions-for-use.md) | Two-page guide for users: what the skill is, why to use it and how to use it |

## The seven stages

1. **Goal and scope:** who the evidence is for and what decision they are making
2. **Product and change model:** how the product is expected to create change
3. **Evaluation questions and measures:** questions that can actually be answered, with outcomes and data sources
4. **Evaluation approach:** method family and study design matched to the question
5. **Plan and delivery:** a feasible plan covering sample, timelines, staffing and governance
6. **Analysis and interpretation:** the analysis plan and the strongest claim the design supports
7. **Conclusions and next action:** what the evidence does and does not support

## Installing the skill

**Claude apps (claude.ai / desktop):** zip the folder that contains `SKILL.md`. Then upload the zip under **Settings → Capabilities → Skills**.

**Claude Code:** copy the folder to `~/.claude/skills/digital-health-evaluation/` (personal) or `.claude/skills/digital-health-evaluation/` (project).

The skill is activated when you ask Claude for help evaluating a digital health product. See the [instructions for use](docs/instructions-for-use.md) for example prompts and tips.

## Status and limitations

- **Reference files not yet included.** `SKILL.md` mentions supporting files in `references/`, such as `method-selection.md` and `methods-comparative.md`. They aren't in this repository yet. The skill is written to work without them: it falls back to its core rules and the primary OHID sources rather than inventing their content.
- **Method guidance, not regulation.** The OHID collection was published in 2020–21. Current requirements, such as the NICE Evidence Standards Framework, DTAC, MHRA guidance, UK GDPR, HRA ethics and reporting standards, should be checked against the latest official sources.
- This project is not affiliated with or endorsed by OHID, DHSC, NHS England or NICE.

## Source

Office for Health Improvement and Disparities, [*Evaluating digital health products*](https://www.gov.uk/government/collections/evaluating-digital-health-products). GOV.UK content is published under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
