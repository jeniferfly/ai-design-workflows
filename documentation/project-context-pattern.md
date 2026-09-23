# Project Context Pattern

A practical approach to maintaining reusable AI project context without
creating a knowledge dump.

> **Curate, don't accumulate.**

Project context is most useful when it contains the information that
repeatedly improves future work.

The goal is not to give AI everything that has ever happened in a
project. The goal is to maintain a small, trustworthy set of sources
that reduces repeated setup and keeps important decisions available.

------------------------------------------------------------------------

## What Belongs in Durable Project Context?

Good candidates include information that is:

-   reused across multiple tasks;
-   stable enough to remain useful;
-   expensive to rediscover;
-   important for consistency;
-   authoritative or clearly labeled;
-   likely to improve future decisions.

Examples:

-   design principles;
-   current standards;
-   approved templates;
-   terminology;
-   reusable components;
-   source hierarchy;
-   accessibility requirements;
-   approved reference designs;
-   recurring workflow guidance;
-   durable lessons learned.

------------------------------------------------------------------------

## What Should Usually Stay Task-Specific?

Not every detail deserves permanent project status.

Keep temporary information close to the task when it is:

-   relevant only to one revision;
-   likely to expire quickly;
-   exploratory;
-   unresolved;
-   duplicated elsewhere;
-   useful only as short-term working context.

Examples:

-   one-time review comments;
-   temporary deadlines;
-   rejected explorations;
-   draft wording;
-   superseded versions;
-   incidental conversation.

Promote something into durable context only when reuse creates real
value.

------------------------------------------------------------------------

## A Simple Context Model

Think in three layers:

### PROJECT

Durable, reusable context.

Examples:

-   standards;
-   templates;
-   approved patterns;
-   terminology;
-   reusable workflows.

### TASK

Current requirements and working material.

Examples:

-   current brief;
-   current source;
-   screenshots;
-   requested revision;
-   component-specific requirements.

### OUTPUT

The deliverable being created or revised.

Examples:

-   design;
-   document;
-   prototype;
-   presentation;
-   code;
-   asset.

This separation helps prevent permanent project context from becoming
overloaded with temporary task details.

------------------------------------------------------------------------

## Build a Trusted Source Set

A useful project source set might contain:

``` text
project-context/
│
├── design-principles.md
├── terminology.md
├── source-hierarchy.md
├── accessibility-standard.md
├── approved-patterns/
├── templates/
└── workflows/
```

The structure should reflect the project. Do not create folders simply
to make the system look complete.

------------------------------------------------------------------------

## Avoid Duplication

When the same guidance appears in several files, it becomes harder to
know which version is current.

Prefer:

**one maintained source → referenced by other documents**

over:

**the same rule copied into five files**

Duplication creates drift.

If a concept needs to appear in several places, keep the authoritative
version in one source and summarize or link to it elsewhere.

------------------------------------------------------------------------

## Maintain Authority

Reusable context should make source authority clearer---not more
confusing.

Useful practices include:

-   mark current standards clearly;
-   archive or remove superseded versions;
-   distinguish examples from requirements;
-   identify approved baselines;
-   date material when freshness matters;
-   keep historical information labeled as historical.

See [`source-of-truth-pattern.md`](source-of-truth-pattern.md) for a
fuller source hierarchy.

------------------------------------------------------------------------

## Capture Learning Selectively

After a project, ask:

> Will this lesson materially improve future work?

If yes, consider preserving it as:

-   a template;
-   a checklist;
-   a component;
-   a workflow;
-   a design pattern;
-   a standard;
-   an approved reference.

If no, let it remain part of the completed project history.

Documentation has a maintenance cost. Preserve what earns that cost.

------------------------------------------------------------------------

## Signs the Context Set Is Working

A healthy project context set should:

-   reduce repeated uploads;
-   reduce repeated explanations;
-   improve consistency;
-   make source authority clearer;
-   shorten future briefs;
-   make approved patterns easier to reuse;
-   reduce accidental drift;
-   help new work start from a stronger baseline.

If maintaining the context takes more effort than it saves, simplify it.

------------------------------------------------------------------------

## Periodic Context Review

Occasionally review the source set and ask:

-   Is this still current?
-   Is anything duplicated?
-   Has a temporary decision become a durable standard?
-   Has an old standard been superseded?
-   Are historical examples clearly labeled?
-   Is anything here no longer helping?

Project context should evolve as the system evolves.

------------------------------------------------------------------------

## Related Guides

-   [`source-of-truth-pattern.md`](source-of-truth-pattern.md)
-   [`../workflows/creative-project-workflow.md`](../workflows/creative-project-workflow.md)
-   [`../responsible-ai/human-review-checklist.md`](../responsible-ai/human-review-checklist.md)

------------------------------------------------------------------------

## Guiding Principle

**Keep the context that makes the next decision easier.**
