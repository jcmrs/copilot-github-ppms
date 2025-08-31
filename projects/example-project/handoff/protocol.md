# Handoff Protocol (Global + Project-Based Structure)

## Overview
A handoff is a two-part process that ensures continuity and context restoration between Copilot/LLM sessions.  
Handoffs reference both project-specific and global assets—lessons, guardrails, research, backlog, code library, and instructions.

---

## Naming Convention

`<type>-<conversation_name>-<date>-<time>.md`
- `<type>`: transcript, instruction, code, summary, etc.
- `<conversation_name>`: descriptive name (e.g., project-start, module-planning)
- `<date>`: dd-mm-yyyy (EU format)
- `<time>`: 24-hour (hh-mm)
- Example: `handoff-instruction-project-start-31-08-2025-20-27.md`

---

## Folder Structure

- Global: lessons/, guardrails/, research/, backlog/, code-library/, instructions/
- Per project: projects/<project-name>/transcripts/, projects/<project-name>/handoff/

---

## Versioning

- Use timestamp in file name for uniqueness.
- Optionally, add explicit version numbers if files are revised (e.g., `v2`).

---

## Part 1: Conversation Conclusion (Handoff Creation)

1. **Trigger:** Embedded command `save handoff`.
2. **Copilot/AI selects:** Relevant transcript, code, instruction templates, lessons, guardrails, and research entries.
3. **Handoff instructions must reference both project-specific and global assets.**
4. **User stores files:** Save in correct folders with proper references, update index.

---

## Part 2: Conversation Resumption (Handoff Use)

1. **User initiates session:** Supplies the kickstart instruction file (with all references).
2. **Copilot/AI reads:** Uses referenced files for context restoration.

---

## Embedded Commands

- `save handoff` — Prepare handoff and provide all references.
- `update handoff` — Amend handoff after new lessons or changes.
- Extendable: `save lesson`, `add guardrail`, etc.

---

## Multi-Project Indexing

- Root index.md tracks all projects and global knowledge base assets.
- Projects folder contains transcripts and handoff instructions.

---

*Update this protocol as your workflow evolves.*