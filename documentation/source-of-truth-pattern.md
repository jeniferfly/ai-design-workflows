# Source of Truth Pattern

A simple method for establishing which information should guide
AI-assisted creative work when multiple sources are available.

AI works more reliably when source authority is explicit.

A project may contain current requirements, approved designs, templates,
reusable standards, historical examples, screenshots, notes, and
previous conversations. These sources are useful---but they are not
automatically equal.

------------------------------------------------------------------------

## The Core Pattern

A practical source hierarchy is:

1.  **Current explicit instruction**
2.  **Current authoritative project material**
3.  **Approved project-specific references**
4.  **Reusable standards and templates**
5.  **Historical examples and prior context**
6.  **Inference**

The exact hierarchy can vary by project. What matters is making the
priority clear.

------------------------------------------------------------------------

## 1. Current Explicit Instruction

The current request should normally take priority when it intentionally
changes an earlier decision.

### Example

An approved component uses a blue button, but the current revision
explicitly requires the button to use a newly approved neutral style.

The current instruction supersedes the older component example for that
property.

------------------------------------------------------------------------

## 2. Current Authoritative Project Material

Use current requirements, specifications, briefs, or approved source
documents to establish what the project actually requires.

These materials should override assumptions drawn from older examples.

------------------------------------------------------------------------

## 3. Approved Project-Specific References

Approved designs and working implementations are valuable references
for:

-   visual language;
-   interaction patterns;
-   component behavior;
-   layout;
-   established decisions.

They are especially useful during targeted revisions.

An approved example demonstrates what worked in that project. It does
not automatically establish a universal rule.

------------------------------------------------------------------------

## 4. Reusable Standards and Templates

Standards, design systems, templates, and reusable components provide
consistency across related work.

Use them when they apply---but allow current project requirements to
override them when necessary.

A reusable pattern should support the project, not force the project to
conform to an outdated assumption.

------------------------------------------------------------------------

## 5. Historical Examples and Prior Context

Historical material can help recover:

-   previous decisions;
-   useful reasoning;
-   earlier iterations;
-   lessons learned;
-   patterns worth considering.

Treat it as context unless it has been explicitly preserved as a current
standard.

> **History can inform the work without controlling it.**

------------------------------------------------------------------------

## 6. Inference

Inference should come last.

When an important decision is not established by the available sources,
surface the gap.

Do not allow an AI-generated assumption to silently become a
requirement.

### Better

> The supplied sources do not establish the hover treatment. Should it
> follow the current component standard or the approved reference
> screen?

### Riskier

Silently choosing a hover treatment and presenting it as though the
source required it.

------------------------------------------------------------------------

## Handling Conflicts

When two sources disagree:

1.  identify the conflict;
2.  determine which source has higher authority;
3.  use the higher-authority source;
4.  document the decision if it may matter later.

If authority is unclear and the difference materially affects the work,
ask for a decision rather than guessing.

------------------------------------------------------------------------

## Source Labels

For complex projects, it can help to label sources by role.

### AUTHORITATIVE

Defines current requirements.

### APPROVED REFERENCE

Shows a reviewed solution or established pattern.

### REUSABLE STANDARD

Provides shared guidance across projects.

### HISTORICAL

Provides background or prior decisions.

### INSPIRATIONAL

Supports exploration but does not define requirements.

These labels make it easier for both people and AI tools to understand
how a source should be used.

------------------------------------------------------------------------

## Example

Imagine a project includes:

-   a current creative brief;
-   an approved component from a previous project;
-   a design-system specification;
-   an older screenshot;
-   a note from an earlier exploration.

A reasonable hierarchy might be:

``` text
1. Current creative brief
2. Current design-system specification
3. Approved component reference
4. Older screenshot
5. Exploration note
```

If the creative brief explicitly requires something different from the
older component, the brief wins.

------------------------------------------------------------------------

## Avoiding Source Drift

Source drift happens when outdated or lower-authority information
gradually influences the work as though it were current.

Reduce it by:

-   naming the authoritative source;
-   removing superseded files when appropriate;
-   labeling historical references;
-   maintaining approved baselines;
-   avoiding duplicate versions of the same standard;
-   documenting important changes.

------------------------------------------------------------------------

## Related Guides

-   [`project-context-pattern.md`](project-context-pattern.md)
-   [`../workflows/creative-project-workflow.md`](../workflows/creative-project-workflow.md)
-   [`../prompting/prompt-structure.md`](../prompting/prompt-structure.md)

------------------------------------------------------------------------

## Guiding Principle

**One clear source of truth is more useful than a pile of competing
context.**
