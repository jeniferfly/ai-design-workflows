# Design Request Template

A lightweight copy-and-paste structure for starting design work with AI.

This is the shorter companion to the full prompt framework.

------------------------------------------------------------------------

## Copy-and-Paste Template

``` text
DESIGN REQUEST

Context:
[What are we designing, for whom, and why?]

Source:
[What requirements, content, design system, or reference should guide the work?]

Goal:
[What should the design accomplish?]

Requirements:
- [Requirement]
- [Requirement]
- [Requirement]

Visual Direction:
[Desired qualities, hierarchy, composition, style, or references.]

Constraints:
[Accessibility, platform, dimensions, technology, content, or other boundaries.]

Open Decisions:
[List anything that should be resolved rather than guessed.]

Verification:
[How should the result be evaluated?]

Deliverable:
[What should be returned?]
```

------------------------------------------------------------------------

## Example

``` text
DESIGN REQUEST

Context:
Create a concept for a fictional productivity dashboard used by small creative teams.

Source:
Use the supplied product brief as the content source. Follow the existing neutral design tokens for spacing and component radius.

Goal:
Help users understand today's priorities and project status at a glance.

Requirements:
- Show today's three priority tasks.
- Show active projects and current status.
- Include one clear primary action.
- Support desktop and mobile layouts.
- Maintain accessible contrast and visible focus states.

Visual Direction:
Clean, calm, spacious, and intentional. Strong information hierarchy with minimal decoration.

Constraints:
Do not add features that are not established by the brief.

Open Decisions:
The source does not establish whether project status should use bars or text labels. Present the decision for review before treating either option as final.

Verification:
Confirm all required content is represented, hierarchy is clear, and no unsupported functionality has been introduced.

Deliverable:
Review-ready design concept with a short rationale.
```

------------------------------------------------------------------------

## When Revising Existing Work

For revisions, add:

``` text
Baseline:
[Approved version]

Requested Change:
[Specific change]

Preserve:
[What must remain unchanged]
```

For more controlled revisions, use the full targeted revision template.

------------------------------------------------------------------------

## Good Design Requests Usually Establish

-   the problem;
-   the audience;
-   the source;
-   the requirements;
-   the visual intent;
-   the constraints;
-   unresolved decisions;
-   the expected output.

They do not need to prescribe every visual decision.

------------------------------------------------------------------------

## Related Guides

-   [`prompt-structure.md`](prompt-structure.md)
-   [`targeted-revision-template.md`](targeted-revision-template.md)
-   [`../templates/creative-brief-template.md`](../templates/creative-brief-template.md)
-   [`../templates/revision-request-template.md`](../templates/revision-request-template.md)

------------------------------------------------------------------------

## Guiding Principle

**Treat the prompt like a creative brief---not a magic phrase.**
