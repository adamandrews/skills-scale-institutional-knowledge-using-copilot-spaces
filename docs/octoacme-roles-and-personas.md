# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The roles below are adaptable: a person may hold more than one role on a small project, while larger projects may assign a role to a team or committee. Confirm role assignments and decision authority at project initiation.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes. On some projects, this role may also serve as the product owner; if so, make that combined accountability explicit.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with project managers and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently and make ownership, dependencies, and decisions visible; they do not replace the sponsor's or product manager's decision authority.

### Responsibilities
- Create and maintain project plans and timelines
- Coordinate risks, dependencies, and resource constraints with their owners
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track decisions and escalate issues to the appropriate decision-maker

### Goals
- Deliver projects on time and within agreed scope
- Minimize unplanned work and unresolved escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Project Roles and Personas

These are candidate roles to clarify accountability across business, delivery, technical, change, risk, and operational work. They need not all be separate people or be required on every project. At initiation, agree who fills each applicable role, what decisions they can make, and how they work with the existing Product Manager, Project Manager, and Developers.

### Executive Sponsor / Project Sponsor

**Purpose and responsibilities**
- Owns the business outcome and champions the project with organizational leadership.
- Secures or advocates for funding, people, and organizational support.
- Makes or obtains decisions on escalated scope, priority, or resources within their authority.
- Resolves escalations that the project team cannot settle and confirms continued strategic alignment.

**Interactions and handoffs**
- Sets outcomes and constraints with the Product Manager and confirms that proposed trade-offs support the business case.
- Works with the Project Manager on escalation thresholds, resource constraints, and decisions requiring sponsor authority.
- Receives status, risks, and decision recommendations from the Project Manager; communicates organizational decisions back to the team.
- Engages the Steering Committee when a decision exceeds the sponsor's delegated authority.

### Product Owner / Business Owner

**Purpose and responsibilities**
- Represents business needs and owns the definition and prioritization of desired outcomes and requirements.
- Clarifies acceptance criteria and makes timely decisions about requirement trade-offs and acceptance within delegated authority.
- Ensures that delivered work meets business needs and coordinates business-side validation.

**Interactions and handoffs**
- Partners with the Product Manager to align business requirements, product direction, roadmap priorities, and success measures. If one person fills both roles, document the combined remit.
- Works with stakeholders and Subject-Matter Experts to clarify needs and validate assumptions.
- Gives the Project Manager prioritized requirements, acceptance criteria, and decisions needed for planning; receives progress and impact information in return.
- Collaborates with Developers and the Technical Lead to resolve implementation questions and reviews completed work against agreed criteria.

### Technical Lead / Solution Architect

**Purpose and responsibilities**
- Guides technical design and ensures that implementation meets agreed architecture, security, reliability, and quality expectations.
- Identifies technical dependencies, estimates, constraints, and risks; recommends options and mitigations.
- Ensures that technical decisions are documented and that the solution can be operated and supported.

**Interactions and handoffs**
- Works with Developers on design, implementation, testing, and technical review, and with the Project Manager on estimates, dependencies, and delivery risks.
- Consults the Product Manager and Product Owner / Business Owner on technical trade-offs that affect outcomes, scope, or acceptance criteria.
- Partners with the Operations / Service Owner on supportability and readiness, handing over architecture and operational knowledge before release.

### Change / Adoption Lead

**Purpose and responsibilities**
- Plans how affected people and teams will understand, adopt, and sustain the change.
- Identifies stakeholder impacts, readiness needs, communications, training, and adoption measures.
- Tracks adoption concerns and recommends actions to address barriers.

**Interactions and handoffs**
- Works with the Sponsor to maintain visible leadership support and with the Product Manager and Product Owner to align change activities to the intended outcomes.
- Coordinates with the Project Manager so stakeholder, training, and communication activities are included in the plan and risks are visible.
- Partners with the Operations / Service Owner on transition communications and support materials; shares readiness findings and outstanding adoption needs before handover.

### Risk / Control Owner

**Purpose and responsibilities**
- Owns monitoring and response for an assigned risk, issue, assumption, dependency, or control rather than only recording it.
- Assesses likelihood and impact, maintains evidence and status, and carries out agreed mitigation or control activities.
- Raises emerging concerns promptly and recommends escalation when exposure exceeds agreed thresholds.

**Interactions and handoffs**
- Reports status, changes, and mitigation progress to the Project Manager, who coordinates the overall register and escalation process.
- Engages relevant Subject-Matter Experts and the Technical Lead to assess impacts and develop mitigations.
- Requests decisions or resources from the Sponsor or Steering Committee through the agreed escalation path when the response exceeds the owner's authority.

### Operations / Service Owner

**Purpose and responsibilities**
- Defines the operational, support, service-level, and maintenance needs for the delivered product or service.
- Confirms that monitoring, support procedures, ownership, documentation, and operational readiness are in place before transition.
- Accepts ongoing service ownership when the agreed handover criteria are met, or records gaps and conditions for acceptance.

**Interactions and handoffs**
- Works with the Technical Lead and Developers during design and delivery to ensure the solution is supportable and operational requirements are addressed early.
- Coordinates with the Project Manager on release readiness, handover criteria, and unresolved operational risks.
- Partners with the Change / Adoption Lead on support communications and readiness, then receives the service, runbooks, and known issues from the delivery team at handover.

### Subject-Matter Expert (SME)

**Purpose and responsibilities**
- Provides specialist business, domain, regulatory, or technical knowledge that the core team may not have.
- Reviews assumptions, requirements, impacts, and deliverables within their area of expertise and identifies relevant constraints or risks.
- Provides timely recommendations and evidence; decision authority remains with the designated accountable owner unless explicitly delegated.

**Interactions and handoffs**
- Works with the Product Manager and Product Owner / Business Owner to clarify needs and validate requirements, and with Developers and the Technical Lead to resolve domain questions.
- Shares findings and risks with the Project Manager for inclusion in plans, decisions, or escalations.
- Provides review feedback to the responsible owner, who records the decision and communicates any follow-up.

### Steering Committee / Governance Representative

**Purpose and responsibilities**
- Provides project oversight and makes or coordinates governance decisions on escalated scope, funding, risk, or priority within its charter.
- Reviews progress against outcomes, tolerances, and agreed controls; directs corrective action when needed.
- Ensures decisions and delegated authority are clear and timely.

**Interactions and handoffs**
- Receives concise status, risks, options, and recommendations from the Project Manager and Sponsor.
- Makes decisions beyond the Sponsor's or Project Manager's delegated authority and communicates direction back through the Sponsor and Project Manager.
- Avoids taking over day-to-day delivery coordination, which remains with the Project Manager and delivery team.

---

## Role Coordination and Accountability

| Work area | Primary accountability | Key collaboration / handoff |
| --- | --- | --- |
| Business outcomes and organizational support | Executive Sponsor | Aligns outcomes with Product Manager; receives escalations from Project Manager |
| Product direction, requirements, and prioritization | Product Manager and, where assigned, Product Owner / Business Owner | Consult stakeholders and SMEs; provide priorities and acceptance criteria to delivery |
| Plans, dependencies, status, and coordination | Project Manager | Coordinates role owners, tracks decisions and risks, escalates to Sponsor or governance |
| Technical design and implementation quality | Technical Lead / Solution Architect | Guides Developers; coordinates estimates and risks with Project Manager; aligns with Operations |
| Individual risk, issue, or control response | Assigned Risk / Control Owner | Updates Project Manager; seeks SME input; escalates beyond authority |
| Readiness, training, and adoption | Change / Adoption Lead | Aligns with Sponsor, Product roles, Project Manager, and Operations |
| Service readiness and ongoing support | Operations / Service Owner | Defines requirements with Technical Lead and Developers; accepts handover against agreed criteria |
| Specialist validation and advice | Subject-Matter Expert | Advises the accountable Product, Technical, Risk, or Operations owner |
| Decisions beyond delegated authority | Steering Committee / Governance Representative | Acts on recommendations from Sponsor and Project Manager and returns decisions through them |

At project initiation, tailor this model to project size and context, name accountable people for applicable roles, document decision rights and escalation thresholds, and agree expected inputs, outputs, and handoffs. One person may fill multiple roles, but conflicting responsibilities and approval authority should be made explicit. Use a RACI-style project-specific view where additional detail is needed; this table is guidance, not a substitute for project assignments.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to the exercise or project context and make decision authority explicit where it affects the scenario.
