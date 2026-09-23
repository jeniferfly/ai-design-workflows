# Targeted Revision Template

A reusable prompt template for refining approved work without
unintentionally redesigning it.

> **Targeted revision---not a redesign.**

Use this template when an existing design, component, document,
prototype, or implementation already works and only a specific change is
needed.

------------------------------------------------------------------------

## Template

``` text
TARGETED REVISION

Baseline:
[Name or version of the current approved work.]

Context:
[Briefly explain what this is and why the revision is needed.]

Source / Reference:
[Identify the current source of truth, screenshot, specification, or approved reference.]

Requested Change:
[Describe exactly what should change.]

Preservation Requirements:
With only the revision described above, preserve all other approved:
- content;
- layout;
- visual styling;
- functionality;
- interaction behavior;
- accessibility;
- responsive behavior;
- assets;
- states;
- relationships between unaffected elements.

Additional protected properties:
[List anything especially important that must not change.]

Verification:
Before considering the revision complete:
- confirm the requested change is present;
- confirm protected elements remain unchanged;
- verify affected states or responsive layouts;
- confirm existing functionality still works;
- check the result against the supplied reference.

Deliverable:
[Specify the expected output and version/name if needed.]
```

------------------------------------------------------------------------

## Example

``` text
TARGETED REVISION

Baseline:
Profile Card v1.2

Context:
The component is approved and functioning correctly. The supporting text feels slightly crowded beneath the title.

Source / Reference:
Use Profile Card v1.2 as the visual and functional baseline.

Requested Change:
Increase the vertical spacing between the title and supporting text from 8 px to 16 px.

Preservation Requirements:
With only the spacing revision above, preserve all other approved content, dimensions, typography, icon placement, alignment, border radius, hover behavior, accessibility, and responsive behavior.

Additional protected properties:
- Do not change the card height.
- Do not move the icon.
- Do not change spacing between the supporting text and button.

Verification:
- Confirm the title-to-copy spacing is 16 px.
- Confirm the card dimensions remain unchanged.
- Confirm all cards remain aligned.
- Confirm hover, keyboard focus, and mobile behavior still work.

Deliverable:
Return the revised component as Profile Card v1.3.
```

------------------------------------------------------------------------

## Why Preservation Requirements Matter

AI systems often interpret a revision as permission to improve nearby
elements.

Sometimes that is useful.

During a targeted revision, it can create unnecessary rework.

Explicit preservation requirements establish a boundary:

> **This is the part we are changing. Everything else remains the
> approved baseline.**

This makes iteration more predictable and helps protect decisions that
have already been reviewed.

------------------------------------------------------------------------

## Visual Feedback Tips

Prefer feedback that identifies observable relationships.

### Instead of

> Make it look better.

### Try

> Reduce the visual weight of the divider so the section heading remains
> the strongest element.

### Instead of

> The button feels off.

### Try

> Align the button's left edge with the text column while preserving its
> current size and vertical position.

### Instead of

> Fix this area.

### Try

> Extend the selected area downward while keeping its x-position, width,
> and top edge unchanged.

Precise feedback does not require technical language. It requires a
clear description of **what relationship should change and what should
stay fixed**.

------------------------------------------------------------------------

## Revision Checklist

Before submitting a targeted revision request, confirm:

-   [ ] The approved baseline is identified.
-   [ ] The requested change is specific.
-   [ ] Unaffected elements are protected.
-   [ ] Important fixed properties are named.
-   [ ] A reference is included when it improves clarity.
-   [ ] Verification criteria are defined.
-   [ ] The expected deliverable is clear.

------------------------------------------------------------------------

## Related Guides

-   [`prompt-structure.md`](prompt-structure.md)
-   [`../workflows/creative-project-workflow.md`](../workflows/creative-project-workflow.md)

------------------------------------------------------------------------

## Guiding Principle

**Change what needs to change. Protect what already works.**
