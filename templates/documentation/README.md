# Documentation Templates

These are deliverable document templates. When a story asks you to document something, pick the right template, paste it into any LLM with your raw info, and get a clean, structured document back.

## Which Template Do I Use?

| Template | Use When... | Example |
|----------|-------------|---------|
| **audit-inventory.md** | The story asks you to find, list, or catalog items in a system | "Audit all 15 role check usages and document every hit" |
| **change-impact.md** | The story asks you to document what you changed and its impact | "Document all OR conditions added for the new master role" |
| **how-to-runbook.md** | The story asks you to write steps someone else can follow | "Document how to import a role into consumer espaces" |

## How To Use Any Template

1. Open the template file
2. Copy the entire contents
3. Paste into any LLM (Claude, ChatGPT, Gemini, Copilot, etc.)
4. Replace `{{PASTE_CONTEXT_HERE}}` with your raw story details, notes, or findings
5. The LLM outputs a ready-to-use document
6. Copy the output into your wiki (Confluence, Notion, SharePoint, etc.)

## One Story, Multiple Docs

A single story might need more than one template. For the RequestMasterAdmin story for example:
- **audit-inventory.md** — for Step 2 (audit all 15 role check usages)
- **change-impact.md** — for Step 3 (document every OR condition added)
- **how-to-runbook.md** — for Step 1 (document the import process for future reference)
