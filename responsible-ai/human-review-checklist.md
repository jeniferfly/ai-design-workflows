# Human Review Checklist

A practical final review for AI-assisted creative work.

AI can accelerate drafting, exploration, transformation, prototyping,
and production.

Human review turns that output into finished work.

Use this checklist as a flexible review aid---not as a requirement to
mechanically check every item for every project.

------------------------------------------------------------------------

## 1. REQUIREMENTS

Confirm that the output solves the assignment that was actually given.

-   [ ] Does the result address the stated goal?
-   [ ] Are all required elements present?
-   [ ] Were the correct sources used?
-   [ ] Were important constraints followed?
-   [ ] Were preservation requirements respected?
-   [ ] Did the AI introduce requirements that were never established?

------------------------------------------------------------------------

## 2. ACCURACY

Check content rather than assuming polished output is correct.

-   [ ] Are factual statements supported by the source?
-   [ ] Are names, labels, terminology, and numbers correct?
-   [ ] Has anything been invented or inferred without support?
-   [ ] Are summaries faithful to the source?
-   [ ] Are links, references, and citations correct where applicable?

If the source does not establish something important, surface the gap.

------------------------------------------------------------------------

## 3. VISUAL QUALITY

Review the work as a designer---not just as a proofreader.

-   [ ] Is the hierarchy clear?
-   [ ] Is alignment intentional?
-   [ ] Is spacing consistent?
-   [ ] Are related elements visually grouped?
-   [ ] Is the composition balanced?
-   [ ] Is typography consistent and readable?
-   [ ] Is visual decoration serving a purpose?
-   [ ] Does the work feel coherent with the intended design system or
    brand?

Small refinements are worthwhile when they materially improve clarity,
balance, hierarchy, or polish.

------------------------------------------------------------------------

## 4. ACCESSIBILITY

Check the requirements relevant to the format.

Depending on the project:

-   [ ] Is text readable?
-   [ ] Is contrast sufficient?
-   [ ] Is information communicated by more than color alone?
-   [ ] Are focus states visible?
-   [ ] Is keyboard interaction supported where required?
-   [ ] Are labels and instructions understandable?
-   [ ] Is alternative text appropriate for meaningful imagery?
-   [ ] Is the reading/order structure logical?
-   [ ] Is motion handled appropriately?

Accessibility review should match the actual medium and project
requirements.

------------------------------------------------------------------------

## 5. FUNCTIONALITY

For interactive or technical work:

-   [ ] Does the primary flow work?
-   [ ] Do hover, focus, selected, disabled, error, and completion
    states behave correctly where applicable?
-   [ ] Are related visual states aligned?
-   [ ] Does keyboard behavior still work?
-   [ ] Does the experience behave correctly at relevant screen sizes?
-   [ ] Did the revision break anything outside the target area?
-   [ ] Are completion or success conditions correct?

Test behavior rather than inferring it from appearance.

------------------------------------------------------------------------

## 6. UNINTENDED CHANGES

This is especially important during targeted revisions.

Compare against the approved baseline.

-   [ ] Did only the requested elements change?
-   [ ] Is approved content still intact?
-   [ ] Did any dimensions shift unexpectedly?
-   [ ] Did typography change?
-   [ ] Did assets change?
-   [ ] Did interaction behavior change?
-   [ ] Did accessibility behavior change?
-   [ ] Did responsive behavior change?

A revision can solve the requested problem while accidentally creating
another one.

------------------------------------------------------------------------

## 7. ASSUMPTIONS

Look for decisions the AI may have made on its own.

Ask:

-   Did the source actually establish this?
-   Was this a reasonable implementation choice or an unsupported
    requirement?
-   Does a person need to approve this decision?
-   Should the decision be documented for future work?

When an assumption materially affects the outcome, make it visible.

------------------------------------------------------------------------

## 8. RESPONSIBLE USE

Before final approval:

-   [ ] Was an appropriate AI environment used?
-   [ ] Was only appropriate source material provided?
-   [ ] Was unnecessary sensitive information removed where appropriate?
-   [ ] Has the final output been reviewed for information that should
    not appear?
-   [ ] Is the team comfortable owning and approving the result?

See [`responsible-ai-checklist.md`](responsible-ai-checklist.md) for the
broader Protect → Verify → Own framework.

------------------------------------------------------------------------

## 9. BASELINE DECISION

If the work is approved, decide whether it should become the new
baseline.

-   [ ] Is this the version future revisions should start from?
-   [ ] Is the version/name clear?
-   [ ] Should an older version be marked superseded?
-   [ ] Did this revision establish a reusable pattern?
-   [ ] Is there a lesson worth documenting?

Do not promote every experiment into a standard.

Protect the versions that have actually earned approval.

------------------------------------------------------------------------

## Quick Final Check

Before shipping, ask:

**Correct?**\
Does it meet the requirements?

**Clear?**\
Can the intended audience understand and use it?

**Consistent?**\
Does it align with the approved system?

**Accessible?**\
Have relevant accessibility needs been addressed?

**Protected?**\
Were approved elements preserved?

**Owned?**\
Has a person reviewed and approved the result?

------------------------------------------------------------------------

## Related Guides

-   [`responsible-ai-checklist.md`](responsible-ai-checklist.md)
-   [`../workflows/design-revision-workflow.md`](../workflows/design-revision-workflow.md)
-   [`../workflows/visual-feedback-workflow.md`](../workflows/visual-feedback-workflow.md)
-   [`../documentation/source-of-truth-pattern.md`](../documentation/source-of-truth-pattern.md)

------------------------------------------------------------------------

## Guiding Principle

**AI can accelerate the process. Human judgment creates the finished
work.**
