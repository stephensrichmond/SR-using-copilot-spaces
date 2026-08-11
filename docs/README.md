# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This folder contains comprehensive guides for running projects using the OctoAcme framework.

## Overview

OctoAcme's project management approach is built on five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

The framework spans the entire project lifecycle from initial concept through retrospective, with defined roles, communication cadences, quality gates, and risk management practices to ensure consistent, repeatable project execution.

## Quick Start

New to OctoAcme? Start with the **[Project Management Overview](./octoacme-project-management-overview.md)** for a high-level introduction to our approach, core roles, and key artifacts.

## Project Lifecycle

Follow these guides as you move through each phase of your project:

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and authorize work
2. **[Project Planning](./octoacme-project-planning.md)** — Create actionable plans, break work into shippable increments, and identify dependencies
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, escalate blockers, and maintain quality
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize releases, manage rollbacks, and reduce production risk
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

## Core Supporting Docs

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define responsibilities for Project Managers, Product Managers, Developers, and QA/Testing roles
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, assess, mitigate, and communicate risks, dependencies, and escalation paths

## Key Processes

### Communication Cadence
- Weekly sync between PM and Product Manager
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations as needed

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI/CD
- Manual QA for feature acceptance when needed

### Risk Management
Maintain a risk register tracking:
- Risk ID, Description, Impact, Likelihood, Owner, Mitigation plan, and Status
- Regular review at weekly syncs
- Escalation paths: Team-level → PM → Product Lead → Sponsor

## Getting Started

1. **For new projects**: Begin with [Project Initiation](./octoacme-project-initiation.md)
2. **For ongoing projects**: Reference the relevant phase guide
3. **For team members**: Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities
4. **For common questions**: Check the specific guide for your project phase

## Questions or Improvements?

Found a gap in the documentation? Have a suggestion for improvement? Create an issue using the "Add Content to Project Management Process Docs" template in `.github/ISSUE_TEMPLATE/` to propose updates.
