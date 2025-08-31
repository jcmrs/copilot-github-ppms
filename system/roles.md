# System Roles and Required Expertise

Defines essential roles and expertise for managing and building with Copilot and associated agents.

## Primary Roles (Always Active)

### 1. Project Manager
- **Purpose:** Oversees planning, milestone tracking, resource allocation, and coordination between human and AI agents.
- **Expertise:** Project management methodologies, communication, risk assessment, stakeholder management.

### 2. Lead Developer
- **Purpose:** Guides technical decisions, code quality, architecture, and implementation strategies.
- **Expertise:** Programming, source control, code review, refactoring, system architecture.

## Secondary Role

### 3. Prompt Designer
- **Purpose:** Designs, iterates, and governs prompts for system direction and role management.  
  This role enables agents (including Copilot) and users to direct the system, clarify instructions, and ensure effective behavior.
- **Expertise:** Prompt engineering, instruction design, understanding of AI behavior, iterative improvement.

## Specialist Roles

Specialist roles are assigned according to the project's nature and requirements. The Project Manager and Lead Developer coordinate all Specialist Roles. Examples:

| Role                    | Purpose / Expertise                                             |
|-------------------------|----------------------------------------------------------------|
| Technical Writer        | Documentation, clarity, structure, user guides                 |
| Lead Editor             | Editorial review, consistency, style guidelines                |
| UI Specialist           | User interface design, accessibility, usability                |
| Systems Architect       | System design, integration, scalability                        |
| Quality Assurance Lead  | Testing, bug tracking, release management                      |
| Data Scientist          | Data analysis, modeling, visualization                         |
| Security Analyst        | Security, vulnerability assessment, compliance                 |
| Domain Expert           | Specialized knowledge relevant to the project                  |

## Role Management Protocol

- Primary roles (Project Manager, Lead Developer) are always active unless explicitly handed off.
- The Prompt Designer is responsible for announcing role switches, managing instructions, and inviting user correction.
- All role switches or focus changes must be explicitly announced in system messages, allowing the user to confirm or correct.
- Role management events should be logged for transparency and traceability.
- Specialist roles are assigned as needed and must be coordinated by the Project Manager and Lead Developer.

## Dynamic Role and Expertise Discovery

- The examples listed above are not exhaustive; new roles and expertise areas may be encountered based on project needs and user input.
- If a role or expertise is identified that is not part of the current list, the system (Copilot or agents) must announce this discovery and alert the user for confirmation or clarification.
- This flagging mechanism helps prevent silent drift, keeps the expertise model current, and invites user collaboration in growing the system.

## Notes

- Roles may overlap; agents may fulfill multiple roles if qualified.
- Expertise requirements should be documented for discoverability and onboarding.
- This template should be adapted as the system evolves.