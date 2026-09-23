# Design Revision Workflow

A practical workflow for refining approved work without losing the
decisions that already work.

**BASELINE → TARGET → BOUNDARIES → REVISE → VERIFY → PROTECT**

AI-assisted revision is most dependable when the request clearly
separates the part being changed from the parts that have already been
approved.

The goal is simple:

> **Targeted revision---not a redesign.**

------------------------------------------------------------------------

## 1. BASELINE

Identify the current approved version before making changes.

The baseline might be:

-   an approved design;
-   a working component;
-   a presentation;
-   a prototype;
-   a document;
-   an implementation;
-   a previous version that has already passed review.

Name the baseline whenever possible.

### Why this matters

Without a clear baseline, an AI system may treat the task as a fresh
design opportunity rather than a controlled revision.

**Output:** One clearly identified starting point.

------------------------------------------------------------------------

## 2. TARGET

Identify exactly what needs to change.

Describe the target using observable language.

### Weak

> Improve the card.

### Stronger

> Increase the vertical spacing between the card title and supporting
> copy.

The stronger direction gives the revision a specific target without
inviting unrelated changes.

### Useful questions

-   Which element is changing?
-   Which property or relationship needs adjustment?
-   Is the request visual, functional, content-related, or behavioral?
-   Is there a screenshot or reference that makes the target clearer?

**Output:** A specific revision target.

------------------------------------------------------------------------

## 3. BOUNDARIES

Define what must remain unchanged.

This is the preservation layer.

Depending on the project, protect:

-   approved content;
-   layout;
-   typography;
-   dimensions;
-   assets;
-   visual hierarchy;
-   interaction behavior;
-   states;
-   accessibility;
-   responsive behavior;
-   existing functionality;
-   relationships between unaffected elements.

### Example

> Increase the height of the selected area while keeping its x-position,
> width, and top edge unchanged.

The request identifies both the changing property and the fixed
properties.

**Output:** Clear revision boundaries.

------------------------------------------------------------------------

## 4. REVISE

Make the smallest change that satisfies the requirement.

Avoid using a targeted revision as an opportunity to clean up unrelated
details unless those changes have also been requested.

### Useful principle

**Change only what is necessary to solve the identified problem.**

This keeps reviews focused and reduces the risk of introducing new
issues into approved work.

**Output:** A revised version with a controlled change set.

------------------------------------------------------------------------

## 5. VERIFY

Compare the result against both the request and the baseline.

Verification should answer two questions:

1.  Did the requested change happen?
2.  Did anything else change that should not have?

### Review areas

-   requested geometry or spacing;
-   content;
-   alignment;
-   hierarchy;
-   interaction states;
-   keyboard behavior;
-   accessibility;
-   responsive behavior;
-   functionality;
-   visual consistency.

Screenshots or side-by-side comparisons are especially useful when the
revision is visual.

**Output:** A reviewed revision with no unintended changes.

------------------------------------------------------------------------

## 6. PROTECT

When the revision is approved, establish the new baseline.

Record the version or approved reference so future work starts from the
correct state.

A protected baseline makes subsequent refinements easier because the
team does not need to reconstruct which version was considered correct.

### Capture

-   approved version;
-   what changed;
-   any reusable lesson;
-   any new standard created by the revision.

**Output:** A new trusted baseline.

------------------------------------------------------------------------

## Revision Request Pattern

A useful revision request contains:

``` text
Baseline:
[Current approved version]

Requested Change:
[Specific change]

Preserve:
[Everything that must remain unchanged]

Reference:
[Screenshot, specification, or approved example]

Verify:
[How to confirm the revision is correct]

Deliverable:
[Expected output/version]
```

------------------------------------------------------------------------

## When a Redesign Is Actually Needed

Targeted revision is not always the right approach.

A broader redesign may be appropriate when:

-   the underlying requirements have changed;
-   the current system cannot support the new need;
-   accessibility or usability problems require structural changes;
-   the existing pattern is no longer appropriate;
-   multiple small fixes are symptoms of a larger design problem.

When that happens, make the shift explicit.

Do not disguise a redesign as a small revision.

------------------------------------------------------------------------

## Related Guides

-   [`../prompting/targeted-revision-template.md`](../prompting/targeted-revision-template.md)
-   [`../prompting/prompt-structure.md`](../prompting/prompt-structure.md)
-   [`visual-feedback-workflow.md`](visual-feedback-workflow.md)
-   [`../responsible-ai/human-review-checklist.md`](../responsible-ai/human-review-checklist.md)

------------------------------------------------------------------------

## Guiding Principle

**Change what needs to change. Protect what already works.**
