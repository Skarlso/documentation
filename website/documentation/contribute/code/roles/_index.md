---
title: Community Roles
weight: 20
---


## Community Roles

This document describes contribution roles within the Gardener community, outlining their requirements and responsibilities. It aims to help new contributors understand the review process and provides guidance for those interested in gaining membership. Various aspects and definitions were adopted from the Kubernetes Community membership document ([ref](https://github.com/kubernetes/community/blob/master/community-membership.md)), with slight adjustments  to fit the organizational setup and size of Gardener.

> [!Note]
> Not every Gardener sub-project may have applied the listed community roles yet. 
> If adopted, this document is linked in the repository's top-level `README.md` file.

### Member

Members are active contributors in the Gardener community. They can have issues and PRs assigned to them, and are granted the privilege to run pre-submit tests on their own and all other PRs.
Technically, members are defined by their membership in the [Gardener Github org](https://github.com/gardener).

**Requirements**
- Demonstrate stake and long-term commitment in the Gardener project, e.g., through previous code contributions or company affiliation
- Maintained Github profile to make yourself known to other project maintainers
- Enabled Github notifications for their ongoing PR reviews and issues

**Responsibilities**
- Responsive to their assigned PRs, issues and mentions

**How to become a member**
- Fulfill listed requirements
- Obtain sponsorship from at least two approvers
- **Process**: Open an issue in the affected project repository (use [issue template](https://github.com/gardener/documentation/blob/master/website/documentation/contribute/code/roles/assets/_issue_template.md); if accepted, an org owner assigns the member to the corresponding group.

### Reviewer

Reviewers are responsible for assessing code quality and correctness within specific areas of the project.
They are granted the privilege to `/lgtm` pull requests.
Members of this role are technically defined in the `OWNERS_ALIASES` file, placed at the root level of the repository.

**Requirements**
- Solid understanding of the codebase and software engineering principles
- Professional expertise in at least one Gardener topic area: `core`, `networking`, `observability`, `scalability`, `security`, etc.
- Enabled Github notifications for PR invites, area issues and updates

**Responsibilities**
- Regular contributions in the form of pull requests, reviews, and issues
- Tracking of open pull requests and issues within their subject domain
- Responsiveness, especially during code reviews and discussions

**How to become a reviewer**
- Demonstrate the requirements through previous contributions (code changes, PR review participation, issue discussions) in the relevant topic area
- Obtain sponsorship from at least two approvers
- **Process**: Open an issue in the affected project repository (use [issue template](https://github.com/gardener/documentation/blob/master/website/community/roles/assets/_issue_template.md); if accepted, an approver creates a PR to update `OWNERS_ALIASES`.

### Approver

Approvers ensure holistic acceptance of contributions, including compatibility, adherence to conventions, performance, operations, and interactions across the system. Furthermore, they verify that pull requests align with established practices in the existing codebase and comply with the best practices and standards defined in the development docs and the contributor guide.
They are granted the privilege to `/approve` pull requests.
Members of this role are technically defined in the `OWNERS_ALIASES` file, placed at the root level of the repository.

Approvers share the requirements and responsibilities of [reviewers](#reviewer), with additional expectations:

**Requirements**
- Sound technical judgement
- Deep understanding of the Gardener codebase, features, and extensions
- Strong operational experience with Gardener
- Active community engagement in the form of contributions to the Gardener Community Review meeting, Slack discussions or similar

**Responsibilities**
- Responsiveness and ability to triage reviews
- Mentoring contributors and reviewers
- Authority to approve code contributions
- Regular contributions across multiple topic areas, including larger changes and refactorings

**How to become an approver**
- Serve as a reviewer for at least 3 months
- **Process**: Obtain sponsorship from a quorum of approvers; nomination happens by one or more existing approvers

### Adjustment of Membership Status

Approvers periodically review the contents of the `OWNERS` and `OWNERS_ALIASES` files to ensure accuracy. If a reviewer or approver becomes inactive or does not fulfill the defined requirements and responsibilities, their status may be adjusted or removed. These decisions are made on a case-by-case basis and require agreement from a quorum of approvers.
