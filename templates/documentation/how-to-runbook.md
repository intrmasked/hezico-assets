# How-To / Runbook

You are producing a deliverable document for a development task. The task requires you to write instructions that someone else can follow to perform a process, configure a system, or complete a procedure. This could be a setup guide, a deployment runbook, a configuration walkthrough, or any repeatable set of steps.

Take the context provided below and produce a clean, structured how-to document.

---

## CONTEXT

Paste the task details, process info, or raw notes here:

```
{{PASTE_CONTEXT_HERE}}
```

---

## OUTPUT FORMAT

Generate the document using this structure:

---

# {{HOWTO_TITLE}}

**Last Updated:** {{DATE}}
**Author:** {{YOUR_NAME}}
**App / Module:** {{APP_OR_MODULE_NAME}}
**Audience:** {{WHO_THIS_IS_FOR — e.g., developers, QA, ops, new team members}}

---

## 1. Purpose

1-2 sentences explaining what this document helps someone do and when they would need it.

## 2. Prerequisites

Everything that must be true or in place before starting:

- [ ] Access / permissions required
- [ ] Tools or software needed
- [ ] Configuration or environment state
- [ ] Knowledge assumptions (what the reader should already know)

If none, write "No prerequisites."

## 3. Steps

Numbered steps. Each step must have:
- A clear action heading
- What to do (specific instructions)
- Where to do it (screen, file, tool, menu path)
- Expected result (what you should see after completing the step)

### Step 1 — {{ACTION_HEADING}}

**Do:** Specific instruction.

**Where:** Location (e.g., Service Studio > Manage Dependencies > EmpApp_Roles)

**Expected Result:** What the user should see or what should happen after this step.

### Step 2 — {{ACTION_HEADING}}

**Do:** ...

**Where:** ...

**Expected Result:** ...

*(Continue for all steps)*

## 4. Verification

How to confirm the process was completed successfully:

| Check | Expected Result | Pass? |
|-------|----------------|-------|
| ...   | ...            | [ ]   |

## 5. Troubleshooting

Common issues and how to fix them:

| Problem | Cause | Fix |
|---------|-------|-----|
| ...     | ...   | ... |

If none known, write "No known issues. If you encounter problems, contact {{CONTACT_OR_TEAM}}."

## 6. Notes

Anything extra — tips, warnings, edge cases, related documents:

- ...

If none, write "None."

---

## RULES

1. Steps must be sequential and numbered — never assume the reader knows the order
2. Every step must include Where (location) and Expected Result — never leave the reader guessing
3. Use exact names for menus, buttons, screens, fields — not vague references
4. If a step has a decision point (if X then do Y, else do Z), call it out explicitly
5. Write for someone doing this for the first time — do not skip "obvious" steps
6. Keep language direct: "Click", "Open", "Navigate to", "Enter", "Select" — imperative verbs
7. Screenshots are encouraged if the output format supports them — note where one should go with `[Screenshot: description]`
