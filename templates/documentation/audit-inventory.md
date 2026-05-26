# Audit / Inventory Log

You are producing a deliverable document for a development task. The task requires you to audit, inventory, or catalog items in a system. This could be role usages, API endpoints, configurations, dependencies, screen references, or any other set of items that need to be found and recorded.

Take the context provided below and produce a clean, structured audit document that can be handed to another developer, QA, or a stakeholder.

---

## CONTEXT

Paste the task details, system info, or raw findings here:

```
{{PASTE_CONTEXT_HERE}}
```

---

## OUTPUT FORMAT

Generate the document using this structure:

---

# {{AUDIT_TITLE}}

**Date:** {{DATE}}
**Conducted By:** {{YOUR_NAME}}
**App / Module:** {{APP_OR_MODULE_NAME}}
**Purpose:** One sentence explaining why this audit was done.

---

## Scope

What was audited, where, and what was included/excluded.

- **Target:** What you were looking for (e.g., "All usages of the 15 request-type role check functions")
- **Searched In:** Where you looked (e.g., espaces, modules, repos, screens)
- **Excluded:** Anything deliberately skipped and why

## Findings

A table of every item found:

| # | Item | Location | Type | Details | Status / Notes |
|---|------|----------|------|---------|----------------|
| 1 | ...  | ...      | ...  | ...     | ...            |

**Column guide:**
- **Item** — The thing found (function name, role, endpoint, config, etc.)
- **Location** — Where it was found (espace, screen, action, file, line number)
- **Type** — Category of usage (screen-level, logic condition, widget visibility, API call, etc.)
- **Details** — Specifics (the expression, the condition, the configuration value)
- **Status / Notes** — Current state, flags, or action needed

## Summary Counts

| Category | Count |
|----------|-------|
| ...      | ...   |
| **Total** | **...** |

## Gaps / Missing Items

Anything expected but NOT found, or items that need follow-up:

- [ ] ...
- [ ] ...

If none: "All expected items accounted for."

## Recommendations

Bullet list of actions to take based on the findings. If this is purely an inventory with no action needed, write "No action required — inventory complete."

---

## RULES

1. Every item gets its own row — do not group or summarize away individual findings
2. Use the exact table columns defined above, add more columns only if the context demands it
3. Counts must match the table rows — no discrepancies
4. Flag anything ambiguous or unexpected in the Status/Notes column
5. If the context doesn't provide enough detail for a cell, write "TBD" and flag it in Gaps
6. Keep it factual — no opinions, no filler
