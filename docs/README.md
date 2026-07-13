# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation hub. This directory contains standardized processes, templates, and guidance for running projects successfully across the organization.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, and project lifecycle.

## Overview: How OctoAcme Runs Projects

OctoAcme operates a structured, lifecycle-driven approach to project management grounded in five core principles: customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety. The organization's project lifecycle encompasses five distinct phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments), **Execution** (day-to-day delivery and progress tracking), **Release** (standardized deployment to production), and **Close/Retrospective** (capturing learnings for continuous improvement). This phased approach ensures projects move through clear decision gates—particularly after initiation, where success metrics must be defined, stakeholder alignment confirmed, and team availability validated before advancing to planning.

The organizational structure relies on three core roles with clear ownership: **Project Managers** coordinate delivery, manage schedules and risks, and maintain stakeholder communication; **Product Managers** define what should be built, prioritize backlogs, and measure outcomes against success metrics; and **Developers** implement features while collaborating on design, testing, and risk identification. This model is reinforced through a defined communication cadence: daily standups (15 minutes focusing on progress, blockers, and dependencies), weekly syncs between PM and Product Manager, twice-weekly team standups during execution, monthly stakeholder updates, and ad-hoc escalations as needed.

Quality and execution are embedded throughout OctoAcme's processes via multiple mechanisms: the Definition of Done ensures consistency across sprints, acceptance criteria are mandatory for all backlog items, automated CI includes tests and linting before code review, and at least one approval is required before merging. The organization employs a tiered escalation system for blockers—team-level triage in standups (Level 1), PM escalation to Product Lead and dependent teams (Level 2), and sponsor-level escalation for business-impacting issues (Level 3). Additionally, OctoAcme maintains formal risk management through a Risk Register, monitors key metrics like velocity and burndown, and conducts structured retrospectives after sprints or milestones to identify and track improvements with clear owners and timelines.

## Process Documentation

OctoAcme projects follow a structured lifecycle with guidance for each phase:

1. **[Project Initiation](octoacme-project-initiation.md)** - Validate business need, align stakeholders, and make go/no-go decisions
2. **[Project Planning](octoacme-project-planning.md)** - Break work into shippable increments and create actionable plans
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day delivery, quality, and progress
4. **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Identify, track, and communicate risks and dependencies
5. **[Release & Deployment](octoacme-release-and-deployment.md)** - Standardize releases and reduce production risk
6. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and drive improvements

## Reference

- **[Roles & Personas](octoacme-roles-and-personas.md)** - Understand key roles and responsibilities
- **[Project Management Overview](octoacme-project-management-overview.md)** - Core principles, artifacts, and communication cadence

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Artifacts

Every OctoAcme project produces or maintains these key artifacts:

- **Project Charter / One-pager** - Problem statement, goals, and success metrics
- **Roadmap and Release Plan** - High-level timeline and milestones
- **Sprint/Iteration Backlog** - Prioritized, estimated work items with acceptance criteria
- **Acceptance Criteria & Definition of Done** - Clear exit criteria for quality
- **Risk Register** - Tracked risks with impact, likelihood, and mitigation plans
- **Retrospective notes and action items** - Learnings and improvements from each phase

## Getting Started as a New Team Member

1. **Read the Overview** - Start with the [Project Management Overview](octoacme-project-management-overview.md) (5 min read)
2. **Understand Your Role** - Review [Roles & Personas](octoacme-roles-and-personas.md) to see your responsibilities and typical communication patterns
3. **Pick Your Phase** - Based on your current project stage, dive into the relevant process doc:
   - Just starting a project? → [Project Initiation](octoacme-project-initiation.md)
   - In the planning phase? → [Project Planning](octoacme-project-planning.md)
   - Building and tracking? → [Execution & Tracking](octoacme-execution-and-tracking.md)
   - Managing risks? → [Risk Management & Communication](octoacme-risks-and-communication.md)
   - Preparing to ship? → [Release & Deployment](octoacme-release-and-deployment.md)
   - Project complete? → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
4. **Ask Questions** - All team members are encouraged to provide feedback and ask clarifying questions. Our processes are meant to evolve based on team learnings.

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM + Product Manager sync
- **Monthly**: Stakeholder updates
- **As needed**: Escalations and ad-hoc coordination

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please:
- Check the relevant process document for additional details
- Reach out to your Project Manager or Product Lead
- Submit feedback via an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
