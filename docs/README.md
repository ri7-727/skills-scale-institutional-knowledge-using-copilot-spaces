# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a high-level summary of OctoAcme's project management processes and links to each detailed process document.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. 

### Core Roles and Responsibilities

The organization defines three primary roles, each with distinct responsibilities:

- **Project Manager**: Coordinates delivery, timelines, risks, and communications to ensure projects stay on track
- **Product Manager**: Defines outcomes, prioritizes the backlog, and measures success against business and customer value
- **Developers**: Implement features while collaborating on design, testing, and quality standards

This clear ownership model ensures accountability while fostering cross-functional alignment through a consistent communication cadence: weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates.

### The Project Lifecycle

OctoAcme projects flow through five interconnected phases:

1. **Initiation**: Validate business need and stakeholder alignment via a lightweight One-pager that captures the problem, goal, success metrics, and resource needs
2. **Planning**: Break work into shippable increments with a prioritized backlog, acceptance criteria, and Definition of Done; map milestones and identify dependencies
3. **Execution**: Manage day-to-day delivery using GitHub Projects, small pull requests (≤400 lines), daily standups, weekly syncs, and automated CI checks before review
4. **Release**: Standardize deployment with pre-release checks, release notes, rollback planning, and post-deploy verifications
5. **Close & Retrospective**: Capture learnings, track action items, and drive continuous improvement

### Quality Assurance and Risk Management

Quality is embedded throughout the delivery cycle, not siloed to the end:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed

Risk management is formalized through a **Risk Register** (tracking impact, likelihood, owner, and mitigation) reviewed weekly. Blocker escalation follows a three-level model: team-level triage in standups → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues.

---

## Links to Process Documents

Each document below covers a specific phase or aspect of OctoAcme project management:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles, roles, artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create the One-pager
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into increments, backlog prioritization, estimation, and dependency management
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day team rhythm, PR workflow, quality practices, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk lifecycle, stakeholder communication templates, and escalation paths
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, and rollback playbook
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retros, tracking improvements, and building a culture of learning
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Developer, Product Manager, and Project Manager personas and responsibilities

---

## How to Use These Docs

- **For new teammates**: Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation, then explore specific documents as needed
- **During project initiation**: Reference the [Project Initiation Guide](octoacme-project-initiation.md) and use the Project One-pager template
- **During execution**: Keep the [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) docs handy for daily workflow and escalation guidance
- **Before releases**: Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) to ensure all pre-release requirements are met
- **After milestones**: Reference the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide to run effective retros

## Maintaining These Docs

These documents are living artifacts. When you identify gaps, improvements, or new best practices:

1. Update the relevant process document directly if it's a minor clarification
2. For larger changes or new sections, create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
3. Keep this README in sync when adding or removing process documents

---

_Last updated: 2026-06-14_
