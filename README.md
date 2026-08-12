# Altos Lab

Open-source maintenance and product engineering by John Wu. I build small operations tools, test their failure boundaries, and leave reproducible setup and verification paths for the next contributor.

## Open-source maintenance

### OpenClaw Dashboard

[Repository](https://github.com/altoslab447/openclaw-dashboard) · [Quality gates](https://github.com/altoslab447/openclaw-dashboard/actions/workflows/proof.yml) · [Contributing](https://github.com/altoslab447/openclaw-dashboard/blob/main/CONTRIBUTING.md)

I am the primary maintainer of a local, read-only operator dashboard for OpenClaw workspaces. It combines task state, scheduled jobs, configuration, installed skills, and gateway logs without writing back to the workspace.

Current maintenance work focuses on parser compatibility, privacy and network boundaries, reproducible fixtures, issue triage, and keeping documentation aligned with executable behavior.

## Other public tools

- [Workflow Automation ROI Calculator](https://github.com/altoslab447/workflow-automation-roi-calculator) — a browser-only model for estimating automation savings, review cost, operating cost, and breakeven budget. [Live site](https://altoslab447.github.io/workflow-automation-roi-calculator/)
- [Workflow Reliability Checklist](https://github.com/altoslab447/workflow-reliability-checklist) — a review checklist for triggers, validation, retries, logging, human approval, rollback, and handoff readiness. [Live site](https://altoslab447.github.io/workflow-reliability-checklist/)
- [Freelance Opportunity Radar](https://github.com/altoslab447/outsourcing) — a small tool for scanning, filtering, and prioritizing remote contract opportunities.

## Working principles

- Start with the user workflow and an observable result.
- Keep sensitive or irreversible actions reviewable by a person.
- Treat build output as a checkpoint, not proof that behavior works.
- Document setup, limits, verification, and maintenance boundaries.

For an OpenClaw Dashboard bug or compatibility report, use the repository's [issue templates](https://github.com/altoslab447/openclaw-dashboard/issues/new/choose).
