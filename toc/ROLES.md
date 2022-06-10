This document describes the set of roles individuals might have within the
Cloud Foundry community, the requirements of each role, and the privileges that each
role grants.

- [Scope of Technical Contributions](#scope-of-technical-contributions)
- [Role Summary](#role-summary)
- [Member](#member)
- [Approver](#approver)
- [Working Group Technical Lead](#working-group-technical-lead)
- [Working Group Execution Lead](#working-group-execution-lead)
- [Scribe](#scribe)

See also [notes](#notes) on roles.

## Scope of Technical Contributions

The roles below frequently refer to code and to the community codebase.
That codebase encompasses not only the source code that constitutes the
system components in the community, but also other artifacts such as
documentation, specifications, and technical proposals.

By PR below, we mean any proposed change to one of these artifacts via
the natural proposal mechanism for that medium (for example, pull request
in GitHub, or suggested change in Google Docs). Code review refers to the
process of reviewing a proposed change, providing feedback on it, and
advocating to accept or to reject it.

## Role Summary

The following table lists the roles we use within the Cloud Foundry community. The
table describes:

- General responsibilities expected by individuals in each role
- Requirements necessary to join or stay in a given role
- How the role manifests in terms of permissions and privileges.

Keep in mind that responsibility follows a delegation model. The community delegates
to the TOC, who in turn delegates to working groups and their leads. Working groups can 
establish sub-working groups. Working groups delegate change approval to Approvers.

<table>
  <thead>
    <tr>
    <th>Role</th>
    <th>Responsibilities</th>
    <th>Requirements</th>
    <th>Privileges</th>
    <th>Scope</th>
    </tr>
  </thead>

  <tr>
    <td>(everyone)</td>
    <td>None</td>
    <td>None</td>
    <td>
        <p>Can submit PRs and issues</p>
        <p>Can join CF Slack workspace</p>
        <p>Can take part in community discussions</p>
    </td>
    <td>GitHub Organization</td>
  </tr>  

  <tr>
    <td>Member</td>
    <td>
        <p>Adheres to code of conduct</p>
    </td>
    <td>
        <p>Signed CLA (only for PRs)</p>
    </td>
    <td>
        <p>Can get PRs accepted</p>
    </td>
    <td>GitHub Organization</td>
  </tr>

  <tr>
    <td rowspan="2">Contributor</td>
    <td colspan="4"><i>Inherits from Member Role</i></td>
  </tr>
  <tr>
    <td>Regular active contributor in the community</td>
    <td>
        <p>Has made multiple contributions to the project</p>
    </td>
    <td>
        <p>Member of the GitHub cloudfoundry (and possibly the cloudfoundry-incubator) orgs</p>
        <p>Member of the Cloud Foundry Slack workspace</p>
    </td>
    <td>GitHub Organization</td>
  </tr>

  <tr>
  <tr>
    <td rowspan="2">Approver</td>
    <td colspan="4"><i>Inherits from Contributor Role</i></td>
  </tr>
  <tr>
    <td>
        <p><b>For 1+ repos in an area:</b></p>
        <p>Triage PRs and issues</p>
        <p>Approve and merge contributions from other members</p>
        <p>Perform small maintenance tasks, such as debugging test failures</p>
    </td>
    <td>Highly experienced and active reviewer and contributor to an area</td>
    <td>Entry in one or more OWNERS files in GitHub, and write permissions
        on one or more repos allowing PRs to be merged
    </td>
    <td>GitHub Directory</td>
  </tr>

  <tr>
    <td rowspan="2">Working Group Technical Lead</td>
    <td colspan="4"><i>Inherits from Approver Role</i></td>
  </tr>
  <tr>
    <td>
        <p>Set priorities for a functional area and approve proposals</p>
        <p>Triage incoming issues, set milestones, repo labels</p>
        <p>Roadmap alignment with top-level backlog</p>
        <p>Mentor new contributors, project members, and approvers</p>
        <p>Responsible for technical health of their functional area</p>
    </td>
    <td>Sponsored by the technical oversight committee as documented
        <a href="./mechanics/WORKING-GROUP-PROCESSES.md">here</a>
    </td>
    <td>Write permissions on one or more repos allowing issues to be manipulated</td>
    <td>Working Group</td>
  </tr>

  <tr>
    <td rowspan="2">Working Group Execution Lead</td>
    <td colspan="4"><i>Inherits from Contributor Role</i></td>
  </tr>
  <tr>
    <td>
        <p>Run their working group: Meetings, notes, roadmap, report</p>
        <p>Responsible for the holistic health of the <i>working group</i></p>
        <p>Work organization, planning, high-level execution</p>
        <p>Triage incoming issues, set milestones, repo labels</p>
        <p>Ensure all required skills are present within the working group</p>
        <p>Mentor new contributors, project members, and approvers</p>
    </td>
    <td>Sponsored by the technical oversight committee as documented
        <a href="./mechanics/WORKING-GROUP-PROCESSES.md">here</a>
    </td>
    <td>Write permissions on one or more repos allowing issues to be manipulated</td>
    <td>Working Group</td>
  </tr>

  <tr>
    <td rowspan="2">Scribe</td>
    <td colspan="4"><i>Inherits from Member Role</i></td>
  </tr>
  <tr>
    <td>
        <p>Ensure important information is represented in working group notes</p>
        <p>Post WG recordings to team drive</p>
    </td>
    <td>Sponsored by a working group execution or technical lead.</td>
    <td>Write permissions to team drive and team calendar</td>
    <td>Working Group</td>
  </tr>

</table>

## Member

A member is an occasional community contributor. They should adhere to the code of conduct, and
work towards becoming contributors as their involvement increases.

### Requirements

- Signs CLA
- Files PRs for changes and is responsive to feedback on their PRs.

## Contributor

<i>Includes everything from [Member](#member)</i>

Established community contributor are expected to demonstrate their adherence to the
principles in this document, familiarity with project organization, roles,
policies, procedures, conventions, etc., and technical and/or writing ability.

Contributors are continuously active making contributions the community. They can have
issues and PRs assigned to them, participate in working group meetings, and
pre-submit tests are automatically run for their PRs. Contributors are expected to
remain active in the community.

All contributors are encouraged to help with community code review, although each PR
must be reviewed by an official [Approver](#approver).

When reviewing, contributors should focus on code quality and correctness, including
testing and factoring. Contributors might also review for more holistic issues, but
this is not a requirement.

### Requirements

- Has made multiple contributions to the project or community. Contributions
  might include, but are not limited to:

  - Authoring and reviewing PRs on GitHub.

  - Filing and commenting on issues on GitHub.

  - Contributing to working group or community discussions.

- Subscribed to
  [cf-dev@lists.cloudfoundry.org](https://lists.cloudfoundry.org/g/cf-dev).

- Actively contributing to 1 or more areas.

### Responsibilities and privileges

- Responsive to issues and PRs assigned to them.

- Active maintainer of code they have contributed (unless responsibility is 
  explicitly transferred).

  - Code is well tested.

  - Tests consistently pass.

  - Addresses bugs or issues discovered after code is accepted.

Contributors who frequently contribute code are expected to proactively perform code
reviews and work towards becoming an approver for the area that they are active
in.

## Approver

<i>Includes everything from [Contributor](#contributor)</i>

Approvers are able to both review and approve code contributions. While
code review is focused on code quality and correctness, approval is focused on
holistic acceptance of a contribution including: backward / forward
compatibility, adhering to API and flag conventions, subtle performance and
correctness issues, interactions with other parts of the system, etc. Approver
status is scoped to a subset of the working group's codebases.

### Requirements
- Be a reviewer for at least 3 months
- Have completed at least 20 of the following
  - Submitted a substantial PR
  - Reviewed a substantial PR
  - Submitted a substantial Issue
  - Reviewed a substantial Issue
  - Involved in technical discussion. This includes, but is not limited to, being involved in technical decision making in proposals or    resolving interrupts in slack.
- Nominated by a WG lead (with no objections from other leads).

A substantial PR is anything that changes the logic of the code or introduces a complex amount of documentation. The following are examples of substantial PRs: bug fixes, features, large docs changes like creating a new debugging document or new architecture diagram. The following are examples of non-substantial PRs: dependabot PRs or small docs changes like fixing typos or reorganizing content.

A substantial Issue is anything that requires knowledge of the codebase. The following are examples of substantial Issues: feature requests, bug write ups, debugging help requests. The following are examples of non-substantial Issues: minor doc change requests.

A technical discussion is a thread on slack or in GitHub that requires knowledge of the codebase. The following are examples of technical discussions that will be considered: resolving interrupts in slack, or commenting on proposals. Technical discussions are counted per-thread, not per-message.

The WG lead has final say if an issue, PR, or discussion is considered substantial.

### Responsibilities and privileges

The following apply to the part of the codebase for which one would be an
approver in an OWNERS file:

- Approver status can be a precondition to accepting large code contributions.

- Demonstrate sound technical judgment.

- Responsible for project quality control via code reviews.

  - Focus on holistic acceptance of contribution such as dependencies with other
    features, backward / forward compatibility, API and flag definitions, etc.

- Expected to be responsive to review requests as per community expectations.

- Shares burden of executing smaller maintenance tasks in the working group

- Mentor new contributors and project members.

- Approve code contributions for acceptance.

- Triage new issues and PRs.

# Working Group Leadership Roles

We differentiate here between two key roles, WG Execution Lead and WG Technical
Lead. In small working groups, often these roles will be performed by one
person; in larger working groups it might be best to have different individuals
performing these roles. There is no 'formula': it is up to the working group
leadership to determine what is best for their working group.

## Working Group Technical Lead

<i>Includes everything from [Approver](#approver)</i>

Working group technical leads, or just 'tech leads', are approvers of an entire
area that have demonstrated good judgement and responsibility. Tech leads accept
design proposals and approve design decisions for their area of ownership, and
are responsible for the overall technical health of their functional area.

### Requirements

Getting to be a tech lead of an existing working group:

- Recognized as having expertise in the group's subject matter.

- Approver for a relevant part of the codebase for at least 3 months.

- Member for at least 6 months.

- Primary reviewer for 20 substantial PRs.

- Reviewed or merged at least 50 PRs.

- Sponsored by the technical oversight committee.

Additional requirements for leads of a new working group:

- Originally authored or contributed major functionality to the group's area.

### Responsibilities and privileges

The following apply to the area / component for which one would be an owner.

- Design/proposal approval authority over the area / component, though
  escalation to the technical oversight committee is possible.

- Technical review of feature tracks.

- Perform issue triage on GitHub.

- Apply/remove/create/delete GitHub labels and milestones.

- Write access to repo (assign issues/PRs, add/remove labels and milestones,
  edit issues and PRs, edit wiki, create/delete labels and milestones).

- Capable of directly applying lgtm + approve labels for any PR.

  - Expected to respect OWNERS files approvals and use
    standard procedure for merging code.

- Expected to work to holistically maintain the health of the project through:

  - Reviewing PRs.

  - Fixing bugs.

  - Identifying needed enhancements / areas for improvement / etc.

  - Execute pay-down of technical debt.

- Mentoring and guiding approvers, members, and new contributors.

## Working Group Execution Lead

<i>Includes everything from [Contributor](#contributor)</i>

Working group execution leads, or just 'execution leads', are responsible for
the overall health and execution of the working group itself. Execution leads
work with tech leads to ensure that the working group is making progress toward
its goals, is aligned with the project roadmap, etc. The execution lead may also
be the tech lead in a smaller working group, but they are distinct roles.

### Requirements

- Participant in the working group for at least 3 months, for example as scribe
  or approver.

- Recognized as having expertise in the group's subject matter.

- Sponsored by the technical oversight committee.

### Responsibilities and privileges

- Run their working group according to community-wide process.

  - Meetings. Prepare the agenda and run the regular working group meetings.

  - Notes. Ensure that meeting notes are kept up to date. Provide a link to the
    recorded meeting in the notes. The lead may delegate note-taking duties to
    the scribe.

  - Roadmap. Establish and maintain a roadmap for the working group outlining
    the areas of focus for the working group over the next 6 months.

  - Report. Report current status to the TOC meeting every 6 weeks.

- Holistic responsibility for their working group's feature
  tracks: tracking, health, and execution.

- Perform issue triage on GitHub.

- Apply/remove/create/delete GitHub labels and milestones.

- Write access to repo (assign issues/PRs, add/remove labels and milestones,
  edit project, issues, and PRs, edit wiki, create/delete labels and milestones).

- Expected to work to holistically maintain the health of the working through:

  - Being a good role model

  - Be an advocate for the working group inside and outside of the community

  - Foster a welcoming and collegial environment

  - Mentoring and guiding approvers, members, and new contributors.

## Scribe

<i>Includes everything from [Member](#member)</i>

One of the most underrated roles in open source projects is the role of note
taker. The importance and value of this role is frequently overlooked and
underestimated. Since one of the core project values is transparency, we have an
explicit scribe role to recognize these types of contributions. Working group
scribes assist the Working Group leads with the mechanical processes around
Working Group meetings.

### Requirements

- Participant in the working group for at least 1 month.

- Pattern of attendance and note-taking during working group meetings and one-offs.

- Sponsored by a working group execution or technical lead.

### Responsibilities and privileges

- Attend working group meetings and one-offs whenever possible.

- Ensure that important information from meetings makes it into the WG notes.

- Post WG recordings to the team drive.

# Notes

Within this section "manager" refers to a member who is an Execution Lead, Tech
Lead, Approver or Scribe. (this is different from a WG or Organization Member).

- Initial managers are defined at the founding of the WG as part of the
  acceptance of that WG.
- Managers SHOULD remain active and responsive in their Roles.
- Managers MUST be community members to be eligible to hold a leadership role within a SIG.
- Managers taking an extended leave of 1 or more months SHOULD coordinate with
  other managers to ensure the role is adequately staffed during the leave.
- Managers going on leave for 1-3 months MAY work with other managers to suggest
  a replacement using the normal process
- Managers of a role SHOULD remove any other managers that have not communicated
  a leave of absence and either cannot be reached for more than 1 month or are
  not fulfilling their documented responsibilities for more than 1 month.
  - This MAY be done through a super-majority vote of managers, or if there are
    not enough active managers to get a super-majority of votes cast, then
    removal MAY occur through exception process to the TOC.  The PR removing the
    manager should be open for at least 72 hours.
  - Prior to voting to remove a manager, leads SHOULD reach out to the affected
    manager and see if they need to take a leave.
- Membership disagreements MAY be escalated to the WG leads. WG lead membership
  disagreements MAY be escalated to the TOC.
- Managers MAY decide to step down at anytime and nominate a replacement who
  will be approved through the regular process for that role.

It is the hope of the steering committee that effective communication will make
the use of these rules something that happens under exceptional circumstances
only. In circumstances where it is unavoidable, these are presented so that the
process is clear.

---

The initial content of this page is from the work of the [Knative community](https://github.com/knative/community)
under the terms of the [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).
