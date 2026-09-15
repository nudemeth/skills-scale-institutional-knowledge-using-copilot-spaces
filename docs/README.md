# OctoAcme Project Management Docs

## Overview

This directory contains the comprehensive project management processes and playbooks used by OctoAcme for delivering product features, services, and integrations. Our approach emphasizes customer-first delivery, iterative execution, clear ownership, and data-informed decisions.

## OctoAcme Project Management Approach

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership and accountability. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, projects move into **Planning**, where work is broken into shippable increments with acceptance criteria, dependencies are mapped, and a release timeline is established.

The **Execution** phase emphasizes daily standups, sprint-based delivery with PR reviews, and continuous quality assurance. Quality is embedded throughout execution—small, focused PRs (≤400 lines when possible) require at least one approval before merge, automated CI testing and linting are mandatory, and a Definition of Done includes unit tests, integration tests where applicable, and security scanning. The project board (GitHub Projects) provides transparency across Backlog → Ready → In Progress → In Review → QA → Done, while velocity tracking and burndown metrics inform sprint planning.

**Release & Deployment** follows standardized checklists to reduce risk, with clear rollback procedures for production incidents. Finally, **Retrospectives** capture learnings and convert them into actionable improvements, creating a culture of continuous iteration and psychological safety.

Throughout all phases, OctoAcme maintains structured communication: daily 15-minute standups focused on progress and blockers, weekly PM-PdM syncs for alignment, twice-weekly team standups during delivery, and monthly stakeholder updates. A three-level escalation path (team → PM → Product Lead → Sponsor) ensures blockers are triaged and resolved quickly.

## Project Management Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** – Problem statement, stakeholder alignment, and go/no-go decision
2. **Planning** – Scope definition, backlog creation, resource allocation, and milestone mapping
3. **Execution** – Daily standups, PR reviews, testing, and progress tracking
4. **Release** – Deployment, verification, and stakeholder communication
5. **Retrospective** – Capture learnings and identify continuous improvements

## Process Documents

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's PM principles, roles, artifacts, and lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate, authorize, and align stakeholders on new initiatives |
| [Project Planning](octoacme-project-planning.md) | Breaking work into shippable increments and creating actionable plans |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery, standups, quality standards, and blocker escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk registers, stakeholder updates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklists, and rollback procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Post-project learnings and action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions of core roles (PM, PdM, Developer, QA) and responsibilities |

## Quick Reference

### Core Roles

- **Project Manager (PM)** – Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)** – Defines outcomes, prioritizes backlog, measures success
- **Developers** – Implement features, collaborate on design and testability
- **QA/Testing** – Validate quality and acceptance criteria
- **Stakeholders** – Provide inputs and approvals

### Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

### Communication Cadence

- **Daily standups** (15 min) – Focus on progress, blockers, dependencies
- **Weekly PM + PdM sync** – Alignment and decision-making
- **Twice-weekly delivery standups** (or as agreed) – Team-level coordination
- **Monthly stakeholder updates** – High-level progress and risks
- **Ad-hoc escalations** – As needed for blockers and critical decisions

### Key Principles

- **Customer-first** – Prioritize customer value and usability
- **Iterative delivery** – Deliver small, testable increments
- **Clear ownership** – Each project has named PM and Product Lead
- **Data-informed decisions** – Measure impact and iterate based on evidence
- **Psychological safety** – Encourage feedback and learning

## Getting Started

- **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to roles and lifecycle
- **Starting a new project**: Follow the [Project Initiation](octoacme-project-initiation.md) guide to validate and authorize work
- **Planning a project**: Use [Project Planning](octoacme-project-planning.md) to break work into shippable increments
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and quality standards
- **Managing risks**: Consult [Risks & Communication](octoacme-risks-and-communication.md) for risk registers and stakeholder updates
- **Preparing for release**: Follow [Release & Deployment](octoacme-release-and-deployment.md) checklists and procedures
- **After project completion**: Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings
