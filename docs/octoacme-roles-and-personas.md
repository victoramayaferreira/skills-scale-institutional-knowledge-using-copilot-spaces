# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

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
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master / Delivery Manager

### Role Summary
The Scrum Master / Delivery Manager facilitates team delivery rituals, coaches on agile practices, and removes impediments so the team can focus on delivering value. They act as a servant-leader who optimises team flow without prescribing solutions.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Identify, track, and actively remove blockers and dependencies
- Coach the team on agile/scrum principles and continuous improvement
- Protect the team from unplanned interruptions and scope creep mid-sprint
- Track sprint velocity and flag delivery risks to the Project Manager
- Help refine processes between sprints based on retrospective outcomes

### Goals
- Maximise team throughput and sustainability
- Maintain a healthy team rhythm and psychological safety
- Reduce waste and process friction over time

### Typical Communication
- Daily standup facilitation and impediment log updates
- Retro action items and improvement tracking
- Coordination with PM on blockers requiring escalation

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Surfaces blockers that need schedule or resource intervention |
| Product Manager | Clarifies priorities to keep sprint goals focused |
| Developers | Coaches on process, facilitates ceremonies, removes impediments |
| QA/Testing | Ensures testing tasks are visible in sprint planning and tracked |
| Stakeholders | Shields team from ad-hoc requests; funnels them through PM/PdM |

---

## UX/UI Designer

### Role Summary
The UX/UI Designer translates user and business needs into clear interaction flows, wireframes, and prototypes. They ensure that what is built is usable, accessible, and aligned with OctoAcme's product experience goals.

### Responsibilities
- Define user flows, wireframes, and high-fidelity prototypes
- Contribute to acceptance criteria by capturing usability requirements
- Collaborate with Product Managers during discovery and definition
- Conduct usability reviews and feed findings back into the backlog
- Maintain a shared design system or component library where relevant
- Provide design handoff assets and annotations for Developers

### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework caused by unclear design requirements
- Ensure design decisions are traceable to user research and product goals

### Typical Communication
- Design review sessions with Product Managers and Developers
- Figma / design-tool links and annotations in tickets
- Usability findings shared in planning and retrospectives

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Product Manager | Co-defines user flows; validates designs against product goals |
| Project Manager | Communicates design milestone readiness for planning |
| Developers | Provides annotated handoff assets; reviews implementation fidelity |
| QA/Testing | Reviews test cases for usability and accessibility coverage |
| Stakeholders | Presents prototypes for early feedback before development begins |

---

## DevOps / Site Reliability / Support Engineer

### Role Summary
The DevOps / SRE / Support Engineer ensures that software can be delivered, operated, and supported reliably in production. They own the CI/CD pipeline, observability tooling, runbooks, and incident response processes.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Define and maintain service-level objectives (SLOs) and alerting rules
- Author and keep runbooks and incident-response playbooks current
- Support release planning by assessing infrastructure readiness
- Lead or participate in post-incident reviews and blameless retrospectives
- Collaborate with Developers on non-functional requirements (performance, security, scalability)

### Goals
- Achieve high deployment frequency with low change-failure rates
- Reduce mean time to recovery (MTTR) for production incidents
- Increase system observability and proactive alerting coverage

### Typical Communication
- Release readiness checklists and deployment plans
- Incident reports and post-mortem summaries
- On-call rotation schedules and escalation paths

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Confirms infrastructure readiness for release milestones |
| Product Manager | Provides observability data (usage, errors) to inform priorities |
| Developers | Reviews non-functional requirements; supports pipeline troubleshooting |
| QA/Testing | Aligns on smoke-test suites run in CI and post-deployment validation |
| Stakeholders | Communicates production health metrics and incident status |

---

## Documentation Lead / Technical Writer

### Role Summary
The Documentation Lead / Technical Writer maintains the living documentation ecosystem for OctoAcme—including process docs, release notes, API references, and onboarding guides—so that knowledge remains accurate and discoverable.

### Responsibilities
- Author and maintain process documentation, release notes, and runbooks
- Keep onboarding guides current with team, tooling, and process changes
- Review PRs and tickets for documentation impact and flag gaps
- Establish and enforce documentation standards and templates
- Partner with Developers and PMs to capture architectural decisions and rationale
- Conduct periodic documentation audits to retire stale content

### Goals
- Ensure every team member can find authoritative, current documentation
- Reduce onboarding time through clear, structured guides
- Minimise knowledge silos by making tacit knowledge explicit

### Typical Communication
- Changelog and release-notes updates aligned to each release cycle
- Documentation review comments in PRs
- Periodic "docs health" summaries shared with the team

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Coordinates docs deliverables in the release plan |
| Product Manager | Captures feature rationale and user-facing change descriptions |
| Developers | Reviews PRs for documentation accuracy; requests technical reviews |
| QA/Testing | Documents test coverage, acceptance criteria, and known limitations |
| Stakeholders | Produces stakeholder-facing summaries, changelogs, and FAQs |

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and the delivery team. They elicit, analyse, and document requirements, translating business needs into clear user stories and acceptance criteria.

### Responsibilities
- Facilitate requirements workshops and stakeholder interviews
- Document user stories, use cases, and acceptance criteria
- Maintain the requirements traceability between business goals and backlog items
- Validate that delivered solutions meet original business requirements
- Identify and document gaps, edge cases, and out-of-scope items
- Support the Product Manager in backlog grooming and prioritisation

### Goals
- Ensure delivery team has clear, unambiguous requirements before build
- Reduce rework caused by late-discovered requirements gaps
- Maintain traceability from business goal to delivered feature

### Typical Communication
- Requirements documents and user story maps shared in planning
- Acceptance criteria co-authored in tickets with Product Manager
- Stakeholder meeting notes and decision logs

### Interactions with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Flags scope changes and dependency impacts on the plan |
| Product Manager | Co-owns requirements prioritisation and feature definition |
| Developers | Answers requirements questions and clarifies edge cases during build |
| QA/Testing | Reviews test cases against acceptance criteria; validates coverage |
| Stakeholders | Primary point of contact for requirements elicitation and sign-off |

---

## Role Interaction Matrix (RACI-Style)

The table below maps each role to key project lifecycle activities using **R** (Responsible), **A** (Accountable), **C** (Consulted), and **I** (Informed).

| Activity | PM | PdM | Developers | QA | Scrum Master | UX/UI | DevOps/SRE | Docs Lead | BA | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| Project initiation & charter | A | C | I | I | I | I | I | I | C | C |
| Requirements elicitation | C | A | I | I | I | C | I | I | R | C |
| Backlog prioritisation | C | A | C | C | C | C | C | I | C | I |
| Sprint planning | R | C | R | C | R | C | I | I | C | I |
| Design & prototyping | I | A | C | I | I | R | I | I | C | C |
| Feature development | I | C | R | C | C | C | C | I | C | I |
| QA & acceptance testing | C | A | C | R | I | C | C | I | C | I |
| CI/CD & deployment | C | I | C | C | I | I | R | I | I | I |
| Release notes & docs | C | C | C | I | I | I | C | R | C | I |
| Stakeholder communication | R | C | I | I | I | I | I | I | C | I |
| Retrospective & process improvement | A | C | R | C | R | C | C | C | C | I |

---

## Role Handoff Checklist

Use this checklist at key cross-functional handoff points to ensure nothing falls through the cracks.

### Discovery → Planning Handoff
- [ ] Business Analyst has provided reviewed user stories and acceptance criteria
- [ ] UX/UI Designer has shared wireframes or prototypes for key flows
- [ ] Product Manager has confirmed backlog priorities for the upcoming sprint/milestone
- [ ] Business Analyst has documented any out-of-scope items or deferred requirements

### Planning → Development Handoff
- [ ] Acceptance criteria are written in tickets and reviewed by QA
- [ ] UX/UI Designer has completed design handoff assets for the sprint's scope
- [ ] DevOps / SRE has confirmed infrastructure or environment readiness
- [ ] Scrum Master has confirmed the sprint goal is clear and backlog is groomed

### Development → QA Handoff
- [ ] Developers have documented any known edge cases or incomplete areas
- [ ] Feature branch is deployed to a test environment
- [ ] Acceptance criteria are linked to test cases in the QA plan
- [ ] UX/UI Designer is available for usability questions during testing

### QA → Release Handoff
- [ ] All acceptance criteria are verified and sign-off is captured
- [ ] DevOps / SRE has reviewed the deployment and rollback plan
- [ ] Documentation Lead has updated or reviewed release notes
- [ ] Project Manager has confirmed stakeholder communication is planned

### Post-Release
- [ ] DevOps / SRE has confirmed production monitoring is active
- [ ] Documentation Lead has published final release notes
- [ ] Business Analyst has validated that delivered features meet business requirements
- [ ] Scrum Master has scheduled the retrospective

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

