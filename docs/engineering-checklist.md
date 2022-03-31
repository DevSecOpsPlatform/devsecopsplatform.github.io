---
layout: default
title: Engineering Checklist
nav_order: 2
permalink: /engineering-checklist/
---

# Engineering Checklist

This checklist helps to ensure that projects meet our Engineering Standards.

## Source Control

- [ ] No direct commit onto the main branch and is locked.
- [ ] Merge to the main branch are done through Pull Requests or Merge Requests.
- [ ] Create branches related to work items being worked on.
- [ ] Always commit with messages that are meaningful and informative.
- [ ] Always maintian README file that provides clear documentation of repository.

## Story/Task Tracking

- [ ] All items are tracked in Jira or similar software
- [ ] The tasks on Jira board should always reflect the current status.

## Testing

- [ ] Unit tests cover the majority of all components (>80% if possible).
- [ ] Integration tests run to test the solution e2e.

## CI/CD

- [ ] Project runs CI with automated build and test on each Merge Request.
- [ ] Project uses CD to manage deployments to an environment.
- [ ] Always maintain that the code in Main branch is always shippable.

## Security

- [ ] Secrets are stored in secured locations such as vault and not checked in to code.
- [ ] Data is encrypted in transit (and if necessary at rest) and passwords are hashed.
- [ ] Access is only granted on an as needed bases if possible temporarily.


## Agile/Scrum

- [ ] Scrum Master runs the daily standup
- [ ] The agile process is clearly defined within team.
- [ ] The Screum Team is responsible for backlog management and refinement.
- [ ] A working agreement is established between team members and customer.

## Code Reviews

- [ ] There is a clear agreement in the team as to function of code reviews.
- [ ] The team has a code review checklist or established process.
- [ ] A minimum number of reviewers (usually 2) for a Merge Request is enforced by policy.
- [ ] Linters/Code Analyzers, unit tests and successful builds for Merge Request are set up.
- [ ] There is a process to enforce a quick review turnaround.

## Retrospectives

- [ ] Retrospectives are conducted at the end of each sprint.
- [ ] The team identifies 1-3 proposed experiments to try each week/sprint to improve the process.
- [ ] The team conducts longer retrospective for Milestones and project completion.