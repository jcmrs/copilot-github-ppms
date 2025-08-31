# System Handoff Protocol

## Purpose
Defines the process for handing off system milestones and context between agents and operators.

## Steps
1. Save a verbatim transcript of all relevant messages (full context preferred).
2. If context capture is incomplete, document a lesson.
3. Create a handoff instruction referencing all related context/materials.
4. Use agreed folder and naming conventions for discoverability:
   - `transcripts/` (project-level)
   - `handoff/` (project-level)
   - etc.
5. **Global Elements:**  
   The following are stored and indexed globally (not per project):
   - Lessons (`lessons/`)
   - Code and reusable modules (`code/`)
   - Instructions and protocols (`protocols/`)
   - Roles and required expertise (`system/roles.md`)
   - Global indexes (e.g., `lessons/index.md`, `code/index.md`)
   - Any other system-wide resources
   All handoffs must reference the relevant global indexes and elements.
6. Ensure explicit links between transcript, global lessons (via the lesson index), code, roles, protocols, and handoff instructions.

## Notes
- If transcript is partial, clearly note and document the limitation.
- All global resources must be captured, indexed, and referenced for discoverability and reuse across the system.