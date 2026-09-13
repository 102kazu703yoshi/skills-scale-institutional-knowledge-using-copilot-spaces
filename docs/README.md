# OctoAcme Project Management Documentation

**Welcome to OctoAcme's Project Management Framework**

This directory contains comprehensive guidance on how OctoAcme runs projects. Whether you're kicking off a new initiative, planning work, tracking progress, or closing out a project, you'll find structured processes, checklists, and templates here.

## Our Approach

OctoAcme follows a customer-first, iterative project management approach focused on delivering value through clear ownership, data-informed decisions, and psychological safety. We deliver in phases with regular check-ins and learnings.

Our approach emphasizes:
- **Customer-first priorities:** Focus on customer value and usability in all decisions
- **Iterative delivery:** Ship small, testable increments rather than large monolithic releases
- **Clear ownership:** Every project has a named Project Manager (PM) and Product Manager (PdM) who drive accountability
- **Data-informed decisions:** Measure impact and continuously iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

Every OctoAcme project follows this five-phase approach:

1. **Initiation** — Validate the problem, align stakeholders, and confirm go/no-go
2. **Planning** — Break work into shippable increments, identify dependencies, and create a delivery roadmap
3. **Execution** — Build, test, review, and iterate with regular standups and demos
4. **Release** — Deploy to production with care, verify quality, and announce to stakeholders
5. **Close & Retrospective** — Capture learnings and convert them into improvements

## Execution Overview

Day-to-day execution is managed through a structured rhythm: daily 15-minute standups focused on progress and blockers, weekly delivery syncs to review progress and flag risks, and sprint-based planning tied to a project board. Work is broken into small, testable increments with pull requests capped at 400 lines and requiring at least one approval before merging. Quality is enforced through mandatory unit tests, integration tests, end-to-end smoke tests, and security scanning in CI pipelines.

Risk is treated as a continuous activity throughout execution. Teams maintain a Risk Register, identify threats during planning, and monitor them via weekly syncs. Escalation paths move from team-level triage through the PM to the Product Lead and ultimately to Sponsors for business-impacting issues.

Stakeholder communication is deliberate and tiered: weekly status updates provide progress, next steps, risks, and decisions needed; incident communication follows a structured template; and escalation paths are clearly defined to ensure the right level of visibility.

## Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications; ensures projects stay on track and blockers are addressed
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success; owns the vision and customer needs
- **Developers:** Implement features, collaborate on design and testability, and maintain code quality
- **QA/Testing:** Validate quality, verify acceptance criteria, and conduct manual testing when needed
- **Stakeholders:** Provide inputs, approvals, and business context for decisions

## Process Documentation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Validate business need, align stakeholders, and confirm go/no-go |
| [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, identify dependencies, and create a roadmap |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day delivery, track progress, and escalate blockers |
| [Risks & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardize how we release features to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed descriptions of typical roles and responsibilities |

## Getting Started

New to OctoAcme? Start here:

1. **Understand the big picture:** Read the [Project Management Overview](octoacme-project-management-overview.md) for context on our approach, roles, and key artifacts
2. **Know your role:** Review your role and responsibilities in [Roles & Personas](octoacme-roles-and-personas.md)
3. **Initiate a project:** When you're ready to start a project, follow the [Project Initiation](octoacme-project-initiation.md) guide to validate the business need and align stakeholders
4. **Plan delivery:** Use [Project Planning](octoacme-project-planning.md) to break work into increments and create a roadmap
5. **Execute and track:** Follow [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance
6. **Manage risks:** Reference [Risks & Communication](octoacme-risks-and-communication.md) for identifying and escalating issues
7. **Release confidently:** Use [Release & Deployment](octoacme-release-and-deployment.md) for standardized release processes
8. **Learn and improve:** Conduct retrospectives using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Communication Cadence

- **Daily standups (15 min):** Focus on progress, blockers, and dependencies
- **Weekly PM sync:** Project Manager and Product Manager alignment
- **Twice-weekly team standups:** Delivery team coordination (or as agreed)
- **Weekly stakeholder updates:** Progress, risks, and decisions needed
- **Monthly stakeholder briefings:** Roadmap and high-level status
- **Sprint/Milestone demos:** Show progress and gather feedback
- **Retrospectives:** After each sprint, release, or important milestone

## Key Artifacts

Every OctoAcme project maintains these artifacts:

- **Project Charter / One-pager:** Problem statement, goal, success metrics, stakeholders, timeline, risks, and team
- **Roadmap and Release Plan:** Prioritized features and release schedule
- **Sprint/Iteration Backlog:** Current work broken into shippable increments
- **Acceptance Criteria & Definition of Done:** Clear quality standards
- **Risk Register:** Ongoing risk identification, assessment, and mitigation tracking
- **Retrospective notes and action items:** Learnings and improvements from each phase

## Why This Matters

Currently, the project management documentation exists as separate files, but there was no central entry point or navigation guide. This README serves as:

- A **single source of truth** for discovering and understanding OctoAcme's project management framework
- A **onboarding accelerator** that reduces time for new team members to understand the overall structure and flow
- An **accessibility hub** that centralizes links to all related process documents
- A **quick reference** to help teams locate the guidance they need for each project phase
- A **scaling tool** to distribute institutional knowledge across the organization and reduce single-person dependency risk
