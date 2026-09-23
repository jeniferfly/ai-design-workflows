# Prompt Structure

A practical framework for turning an AI request into a clear creative
brief.

**Context → Source → Requested Change → Preservation Requirements →
Verification → Deliverable**

A strong prompt does not need to be long. It needs to make the important
parts of the assignment explicit.

For creative work, prompting works best when it functions like creative
direction: establish the situation, identify the source of truth, define
the change, protect approved work, explain how success will be checked,
and specify the expected output.

------------------------------------------------------------------------

## The Framework

### 1. Context

Explain what is being worked on and why.

Useful context might include:

-   project purpose;
-   audience;
-   stage of the project;
-   relevant design system;
-   whether this is a new build or a revision;
-   important constraints.

**Example**

> This is a targeted refinement to an approved onboarding screen. The
> existing layout and interaction are working correctly.

------------------------------------------------------------------------

### 2. Source

Identify what should guide the work.

Sources might include:

-   current requirements;
-   an approved design;
-   a screenshot;
-   a component specification;
-   a content brief;
-   a style guide;
-   a working file.

When several sources exist, establish which one is authoritative.

**Example**

> Use the attached approved screen as the visual baseline and the
> current requirements document as the source of truth for content.

------------------------------------------------------------------------

### 3. Requested Change

State exactly what should change.

Prefer observable, specific language.

**Vague**

> Fix the spacing.

**Better**

> Increase the vertical space between the section heading and the first
> card while keeping the card dimensions and horizontal alignment
> unchanged.

The stronger request identifies both the target and the relationship
being adjusted.

------------------------------------------------------------------------

### 4. Preservation Requirements

Explicitly identify what should remain unchanged.

This is especially important during revisions.

Preservation requirements might include:

-   approved content;
-   layout;
-   interaction behavior;
-   accessibility;
-   responsive behavior;
-   visual states;
-   dimensions;
-   component relationships;
-   existing functionality.

**Example**

> Preserve all other screen content, interaction behavior,
> accessibility, card dimensions, typography, and responsive behavior.

------------------------------------------------------------------------

### 5. Verification

Define how the result should be checked.

Verification turns a subjective request into something easier to review.

Examples:

-   compare against a reference;
-   confirm a behavior still works;
-   validate all interaction states;
-   check responsive layouts;
-   confirm accessibility requirements;
-   verify that unrelated elements did not change.

**Example**

> Verify that the spacing change is visible at desktop and mobile widths
> and that no other card positioning has changed.

------------------------------------------------------------------------

### 6. Deliverable

State what should be returned.

Examples:

-   revised design;
-   updated code;
-   Markdown document;
-   component specification;
-   image;
-   presentation;
-   review-ready prototype.

Include naming or versioning requirements when they matter.

------------------------------------------------------------------------

## Full Example

### Weak request

> Can you improve this card layout?

### Structured request

> **Context:** This is a targeted refinement to an approved card layout.
>
> **Source:** Use the current design as the visual and functional
> baseline.
>
> **Requested Change:** Increase the spacing between the card title and
> supporting copy by 8 px.
>
> **Preservation Requirements:** Keep the card size, typography, icon
> placement, border radius, interaction states, accessibility, and
> surrounding layout unchanged.
>
> **Verification:** Confirm that only the title-to-copy spacing changed
> and that all cards remain aligned.
>
> **Deliverable:** Return the revised component as the next version.

The second prompt gives the AI far less room to reinterpret the
assignment.

------------------------------------------------------------------------

## When You Do Not Need Every Section

The framework is a guide, not a form that must be completed
mechanically.

A simple request may only need:

**Context + Requested Change + Deliverable**

A complex revision may need all six parts.

Use enough structure to remove meaningful ambiguity.

------------------------------------------------------------------------

## Prompting as Creative Direction

Good creative direction does not prescribe every decision.

It establishes:

-   the problem;
-   the boundaries;
-   the source of truth;
-   the intended outcome;
-   the things that matter most.

AI prompting works similarly.

The goal is not to control every word the AI produces. The goal is to
create the conditions for a useful result that can be reviewed and
refined by a person.

------------------------------------------------------------------------

## Related Guides

-   [`targeted-revision-template.md`](targeted-revision-template.md)
-   [`../workflows/creative-project-workflow.md`](../workflows/creative-project-workflow.md)
-   [`../responsible-ai/responsible-ai-checklist.md`](../responsible-ai/responsible-ai-checklist.md)

------------------------------------------------------------------------

## Guiding Principle

**Make the brief explicit.**
