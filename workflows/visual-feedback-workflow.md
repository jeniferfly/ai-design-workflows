# Visual Feedback Workflow

A practical method for giving AI clear, reviewable visual direction.

Visual feedback works best when it describes **relationships**, not just
reactions.

Instead of asking AI to make something "better," identify what is
happening, what should change, what should remain fixed, and what
reference establishes the intended result.

**OBSERVE → LOCATE → RELATE → CHANGE → PRESERVE → COMPARE**

------------------------------------------------------------------------

## 1. OBSERVE

Start with what can actually be seen.

Separate the observation from the proposed solution.

### Reaction

> This feels crowded.

### Observation

> The heading, supporting copy, and first card have very little vertical
> separation, so the section reads as one dense block.

The observation gives the feedback something concrete to act on.

------------------------------------------------------------------------

## 2. LOCATE

Identify the exact element or region.

Useful ways to locate a target include:

-   element name;
-   position on the screen;
-   relationship to nearby elements;
-   order in a repeated set;
-   screenshot annotation;
-   visible text label.

### Example

> Update the fourth selectable area from the top, located between the
> two existing sections.

Location-based descriptions can be especially useful when internal
implementation names are unknown.

------------------------------------------------------------------------

## 3. RELATE

Describe the visual relationship that needs attention.

Common relationships include:

-   alignment;
-   spacing;
-   hierarchy;
-   proportion;
-   balance;
-   grouping;
-   contrast;
-   visual weight;
-   proximity;
-   containment;
-   state consistency.

### Example

Instead of:

> Move the button.

Try:

> Align the button's left edge with the text column while preserving its
> current vertical position.

The second version defines the intended relationship.

------------------------------------------------------------------------

## 4. CHANGE

State the requested adjustment.

When precision matters, specify:

-   x/y position;
-   width;
-   height;
-   spacing;
-   padding;
-   alignment;
-   color;
-   outline;
-   radius;
-   shadow;
-   state;
-   typography;
-   opacity.

Use exact measurements when they are known and useful. Otherwise,
describe the visual relationship clearly.

### Example

> Extend the hotspot downward. Keep the x-position, width, and top edge
> unchanged; increase only the height.

------------------------------------------------------------------------

## 5. PRESERVE

Identify what should not move with the change.

This is especially important when visual states are connected.

For example, if a selectable region has:

-   default state;
-   hover state;
-   selected state;
-   focus state;
-   checkmark;
-   outline;

a geometry change may need to apply consistently across all of them.

### Example

> Update the hotspot geometry and keep the hover and selected states
> aligned to the same revised bounds. Preserve the neighboring hotspot
> and all other interactions.

------------------------------------------------------------------------

## 6. COMPARE

Review the result against the reference and baseline.

Useful comparison methods include:

-   before/after screenshots;
-   side-by-side views;
-   overlays;
-   annotated screenshots;
-   reference designs;
-   measurements;
-   interaction testing.

Ask:

-   Did the intended relationship improve?
-   Did any unrelated element shift?
-   Are all visual states still aligned?
-   Does the change hold across relevant screen sizes?
-   Is the hierarchy still clear?

------------------------------------------------------------------------

## Useful Feedback Patterns

### Spacing

**Vague**

> Fix the spacing.

**Clearer**

> Increase the space between the section heading and the first card.
> Preserve the spacing between the cards.

### Alignment

**Vague**

> The icon looks off.

**Clearer**

> Center the icon vertically relative to the title and supporting copy
> group. Keep its horizontal position unchanged.

### Hierarchy

**Vague**

> Make the heading stand out more.

**Clearer**

> Increase the visual separation between the heading and supporting copy
> without increasing the heading size. Use spacing rather than
> additional decoration.

### Geometry

**Vague**

> Make the selection area bigger.

**Clearer**

> Extend the selection area downward while preserving its x-position,
> width, and top edge.

### State consistency

**Vague**

> The selected state doesn't line up.

**Clearer**

> Match the selected-state bounds to the default and hover-state
> geometry. Keep the checkmark centered within the revised area.

------------------------------------------------------------------------

## Screenshots as References

Screenshots are useful because they can establish:

-   which element is being discussed;
-   current visual relationships;
-   expected placement;
-   differences between versions;
-   the exact area that needs refinement.

Annotations should clarify the request, not become part of the final
design unless explicitly intended.

A useful screenshot does not replace written direction. It supports it.

------------------------------------------------------------------------

## Visual Feedback Checklist

Before sending visual feedback, ask:

-   [ ] Did I identify the exact target?
-   [ ] Did I describe the visual relationship?
-   [ ] Did I explain what should change?
-   [ ] Did I identify what should stay fixed?
-   [ ] Did I account for related visual states?
-   [ ] Did I include a reference when it would reduce ambiguity?
-   [ ] Did I define how I will compare the result?

------------------------------------------------------------------------

## Related Guides

-   [`design-revision-workflow.md`](design-revision-workflow.md)
-   [`../prompting/targeted-revision-template.md`](../prompting/targeted-revision-template.md)
-   [`../responsible-ai/human-review-checklist.md`](../responsible-ai/human-review-checklist.md)

------------------------------------------------------------------------

## Guiding Principle

**Describe the relationship---not just the reaction.**
