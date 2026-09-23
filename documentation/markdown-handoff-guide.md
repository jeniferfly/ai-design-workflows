# Markdown Handoff Guide

A practical introduction to using Markdown as a clean working format for
AI-assisted creative projects.

------------------------------------------------------------------------

## What Is Markdown?

Markdown is plain text with lightweight structure.

A few simple symbols identify things such as:

-   headings;
-   lists;
-   emphasis;
-   links;
-   code;
-   quotations.

For example:

``` markdown
# Project Brief

## Goal

Create a clear onboarding experience.

## Requirements

- Use the approved design system.
- Preserve accessibility.
- Keep source material appropriately sanitized.

**Output:** Review-ready concept
```

The symbols carry the structure without requiring the extra formatting
and packaging of a traditional document.

------------------------------------------------------------------------

## Why Use Markdown?

For AI-assisted workflows, Markdown can function as a **clean handoff
format**.

It provides enough structure to preserve meaning while reducing
unnecessary formatting noise.

### Cleaner context

A traditional document may contain layout information, headers, footers,
decorative elements, tables, repeated navigation, or other formatting
that is not relevant to the task.

A Markdown working copy can focus attention on the content and
requirements that matter.

### Easier to review

Because Markdown is readable as plain text, people can quickly inspect
what information is being provided before it is used in an AI workflow.

### Portable

Markdown is not tied to a specific design or office application.

It works well for:

-   briefs;
-   requirements;
-   standards;
-   templates;
-   project notes;
-   documentation;
-   reusable project context.

### Reusable

A well-maintained Markdown source can become part of a trusted project
source set rather than being recreated for every request.

------------------------------------------------------------------------

## Markdown and Responsible Source Preparation

Markdown can also make source preparation easier.

A practical workflow might be:

**Approved Source → Working Copy → Sanitize → Structure → Review → Use**

### 1. Start with the approved source

Identify the current source of truth.

### 2. Create a working copy

Extract only the content needed for the task.

### 3. Sanitize

Remove confidential, proprietary, personal, or otherwise unnecessary
information when appropriate.

### 4. Structure

Use headings, lists, and emphasis to preserve the relationships that
matter.

### 5. Review

Check the Markdown file before using it.

Confirm that:

-   necessary requirements remain;
-   unnecessary information has been removed;
-   meaning has not changed;
-   required handling or classification information is retained when
    applicable.

### 6. Use an appropriate AI environment

A clean source still needs to be used within an environment appropriate
for the information and task.

------------------------------------------------------------------------

## Important: Markdown Is Not a Security Feature

Converting information to Markdown does **not** make that information
safe to share.

Markdown is a file format---not a security control.

A Markdown file can still contain:

-   confidential information;
-   proprietary information;
-   personal information;
-   credentials;
-   internal URLs;
-   sensitive project details.

Always review and sanitize the content itself.

> **Clean formatting is not the same as safe information.**

------------------------------------------------------------------------

## What Markdown Should Preserve

A useful working copy should preserve the information necessary to
complete the task accurately.

Depending on the project, that may include:

-   goals;
-   requirements;
-   constraints;
-   terminology;
-   hierarchy;
-   interaction rules;
-   accessibility requirements;
-   acceptance criteria;
-   approved content.

Sanitization should remove unnecessary information without stripping
away the context required to do the work correctly.

------------------------------------------------------------------------

## What Markdown Can Remove

When it is not required for the task, a working copy may be able to
remove:

-   decorative document formatting;
-   repeated headers and footers;
-   unrelated sections;
-   unnecessary metadata;
-   internal comments;
-   names or identifiers not required for the work;
-   proprietary details unrelated to the requested output.

What should be removed depends on the source, the task, and the
applicable information-handling requirements.

------------------------------------------------------------------------

## Example: Before and After

### Traditional source

Imagine a 20-page project document containing:

-   cover pages;
-   revision history;
-   stakeholder names;
-   internal references;
-   project background;
-   requirements;
-   unrelated appendices;
-   decorative formatting.

### Markdown working copy

The AI task may only need:

``` markdown
# Component Requirements

## Goal
Help users compare three available options.

## Requirements
- Present all three options with equal visual weight.
- Support keyboard navigation.
- Maintain visible focus states.
- Provide clear selected and unselected states.

## Deliverable
Review-ready interactive prototype.
```

The working copy is not better because it is Markdown.

It is better because someone intentionally selected and structured the
context the task needs.

------------------------------------------------------------------------

## When Markdown Is a Good Fit

Consider Markdown when:

-   the task is primarily text or requirements driven;
-   source formatting is not important;
-   you want a portable working source;
-   project context will be reused;
-   the material benefits from clear hierarchy;
-   you want a file that is easy for both people and AI tools to
    interpret.

Markdown may not be sufficient when visual layout, complex tables,
imagery, annotations, or document-specific formatting are themselves
part of the requirement. In those cases, keep the appropriate visual
references alongside the Markdown source.

------------------------------------------------------------------------

## Related Guides

-   [`../workflows/creative-project-workflow.md`](../workflows/creative-project-workflow.md)
-   [`../prompting/prompt-structure.md`](../prompting/prompt-structure.md)
-   [`../responsible-ai/responsible-ai-checklist.md`](../responsible-ai/responsible-ai-checklist.md)

------------------------------------------------------------------------

## Guiding Principle

**Use Markdown as a clean handoff format---enough structure to preserve
meaning, without the extra packaging.**
