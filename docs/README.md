# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This README is the entry point for how we initiate, plan, execute, release, and continuously improve projects at OctoAcme. Use this page to find the key process documents, understand the core workflows and roles, and get pointers for where to add project-specific artifacts.

## Project Management Process Summary

OctoAcme runs projects with a clear, principle-driven lifecycle that moves from lightweight initiation through planning, execution, release, and retrospective. Initiation emphasizes a one-pager to capture the problem, success metrics, stakeholders, and an initial timeline; projects only move to planning when metrics, priority, and team availability are clear. Planning breaks approved initiatives into shippable increments, defines a Definition of Done, creates a prioritized backlog with acceptance criteria, and captures dependencies and risks in a risk register. Releases are treated as distinct events (patch/minor/major) with pre-release checks, rollback plans, and release notes, and every project closes with a retrospective to capture learnings and convert them into actionable backlog items.

Workflows rely on lightweight, repeatable artifacts and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) to make status visible and reduce handoffs. Pull requests are kept small, linked to issues, and include acceptance criteria; CI runs tests and linters before reviews are requested, and at least one approval is required to merge. Planning activities include kickoff meetings, backlog refinement, estimation (T-shirt sizing or story points), and creation of a release plan and milestone map. Regular checklists (initiation, planning, execution, deployment) are used to ensure consistency and surface gaps.

Roles and responsibilities are explicitly defined so ownership and expectations are clear: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers define outcomes, prioritize the backlog, and measure success; developers implement features, tests, and docs; QA validates acceptance criteria and quality; stakeholders provide input and approvals. Communication is structured around a team rhythm of daily standups, weekly delivery syncs, regular PM+PdM alignment, demos at the end of sprints or milestones, and monthly stakeholder updates. Templates such as weekly status summaries and a single source-of-truth project README support consistent, asynchronous updates.

Quality assurance and risk management are built into every phase. Testing practices include unit tests, integration tests, and end-to-end smoke tests for critical flows, all executed in CI alongside security scanning. Manual QA is used where necessary for feature acceptance, and smoke tests are run before and after deployments. Risk registers capture impact, likelihood, owner, and mitigation plans and are reviewed in weekly syncs; escalation follows a tiered path from team-level triage to PM, product lead, and sponsor engagement for business-impacting issues. Together these practices create a disciplined, observable approach to delivering value while managing uncertainty.

## Process Documentation Index

- <a>Project Management Overview</a>
- <a>Project Initiation Guide</a>
- <a>Project Planning</a>
- <a>Execution &amp; Tracking</a>
- <a>Risk Management &amp; Communication</a>
- <a>Release &amp; Deployment Guide</a>
- <a>Retrospective &amp; Continuous Improvement</a>
- <a>Roles &amp; Personas</a>

## How to use these docs

- Keep project-specific charters, release notes, and status updates inside the project repository under docs/ or in the project board so they remain discoverable.
- When updating process docs, follow the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template to propose changes.
- Use this README as the single source-of-truth for where process docs live and link to any project-level README for status and decisions.
