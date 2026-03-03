# OctoAcme Project Management Documentation

This directory contains the comprehensive project management processes and guides used by OctoAcme to deliver customer value through structured, iterative, and data-informed execution.

## Project Management Overview

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The organization follows a five-phase lifecycle: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (day-to-day delivery with regular standups and tracking), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings for continuous improvement). Central to this approach is the **Project One-pager**—a lightweight charter that documents the problem statement, objectives, success metrics, stakeholders, and initial risk list.

The organization defines clear roles and accountability across three primary personas: **Developers** (design, build, test, and deliver features while identifying technical risks), **Product Managers** (define what to build, prioritize the backlog, and measure outcomes through data), and **Project Managers** (coordinate schedules, manage risks, facilitate meetings, and ensure transparency). Each project has a named PM and Product Lead, establishing single-threaded ownership. Communication cadence is consistent and purposeful: daily standups focus on blockers and progress, weekly syncs between PM and Product Manager ensure alignment, and monthly stakeholder updates provide broader visibility.

Quality and execution are maintained through disciplined workflows and governance. The team uses GitHub Projects with defined columns (Backlog, Ready, In Progress, In Review, QA, Done), enforces small pull requests (≤400 lines), requires at least one approval before merging, and runs automated tests, linting, and security scanning in CI. A **Risk Register** captures risks with ID, description, impact/probability, owner, and mitigation plan—reviewed weekly during syncs. Before any release, teams verify all acceptance criteria are met, CI passes, release notes are drafted, and rollback plans are documented.

Finally, OctoAcme embeds continuous improvement into its culture through structured retrospectives held after each sprint, release, or milestone. This closed-loop system—from initiation through retrospective—reinforces psychological safety, data-informed decisions, and iterative refinement that drives sustainable project delivery.

## Documentation Structure

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's principles, core roles, key artifacts, and communication cadence
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Guide for validating and authorizing work, aligning stakeholders, and creating the Project One-pager
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — Process for turning approved initiatives into actionable plans and prioritized backlogs
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Day-to-day delivery guidance including team rhythm, workflows, quality practices, and blocker escalation
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Risk management framework, communication templates, and escalation paths
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Standardized release types, pre-release requirements, deployment checklist, and rollback procedures
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — Framework for capturing learnings and converting them into actionable improvements
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Detailed definitions of Developers, Product Managers, and Project Managers with responsibilities and goals

## Quick Start

1. **Starting a New Project?** Begin with the [Initiation Guide](octoacme-project-initiation.md) to create your Project One-pager and validate stakeholder alignment.
2. **Ready to Plan?** Use the [Planning Guide](octoacme-project-planning.md) to break work into shippable increments and create your backlog.
3. **In Delivery Mode?** Reference the [Execution & Tracking Guide](octoacme-execution-and-tracking.md) for team rhythm, workflow standards, and quality practices.
4. **Preparing to Release?** Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release requirements and deployment checklist.
5. **Retrospective Time?** Use the [Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Contributing to These Docs

To suggest updates or new content, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.