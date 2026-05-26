# Change / Impact Document

You are producing a deliverable document for a development task. The task requires you to document what was changed, where it was changed, and what the impact is. This document is handed to QA for test planning, to stakeholders for sign-off, or kept as a record of what was done.

Take the context provided below and produce a clean, structured change document.

---

## CONTEXT

Paste the task details, what you changed, or your raw notes here:

```
{{PASTE_CONTEXT_HERE}}
```

---

## OUTPUT FORMAT

Generate the document using this structure:

---

# {{CHANGE_TITLE}}

**Date:** {{DATE}}
**Author:** {{YOUR_NAME}}
**App / Module:** {{APP_OR_MODULE_NAME}}
**Story / Ticket:** {{TICKET_REFERENCE}}

---

## 1. Change Summary

2-3 sentences explaining what was changed and why. Plain English, no jargon unless necessary.

## 2. What Was Changed

A table of every individual change made:

| # | Location | What Changed | Before | After | Reason |
|---|----------|-------------|--------|-------|--------|
| 1 | ...      | ...         | ...    | ...   | ...    |

**Column guide:**
- **Location** — Where the change was made (espace, screen, action, file, component)
- **What Changed** — The specific thing modified (condition, property, configuration, code block)
- **Before** — What it looked like before (the old value, expression, or behaviour)
- **After** — What it looks like now (the new value, expression, or behaviour)
- **Reason** — Why this specific change was needed

## 3. Impact Analysis

### Directly Affected
Bullet list of screens, actions, modules, users, or workflows directly touched by the changes.

### Indirectly Affected
Bullet list of anything that depends on the changed items and could behave differently as a result. If none, write "No indirect impacts identified."

### Not Affected (Confirmed)
Bullet list of areas explicitly verified to be unaffected. This helps QA skip unnecessary testing.

## 4. Rollback Plan

If these changes need to be reversed, what are the steps? Be specific:

1. ...
2. ...

If not applicable (e.g., purely additive changes), write "Rollback: revert the publish and redeploy the previous version."

## 5. Testing Requirements

### What QA Should Verify
Numbered list of specific things to test:

1. ...
2. ...

### Regression Checks
Numbered list of things that should still work exactly as before:

1. ...
2. ...

## 6. Sign-Off

| Role | Name | Status |
|------|------|--------|
| Developer | ... | Done |
| QA | ... | Pending |
| Stakeholder | ... | Pending |

---

## RULES

1. Every change gets its own row — do not batch changes together
2. Before/After must be specific — show the actual values, expressions, or states, not vague descriptions
3. If a Before value is "N/A" (new addition), say "N/A — new" in the Before column
4. Impact analysis must cover direct, indirect, and confirmed-unaffected areas
5. Testing requirements should be specific enough for QA to execute without asking questions
6. Keep it factual and concise
