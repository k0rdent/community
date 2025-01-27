# Community Membership

This document outlines the various responsibilities of contributor roles in
k0rdent. The k0rdent project is currently subdivided into two main subprojects:

* [k0rdent cluster management](https://github.com/k0rdent/kcm)
* [k0rdent Observability and FinOps](https://github.com/k0rdent/kof)

## New contributors

New contributors should be welcomed to the community by existing members,
helped with PR workflow, and directed to relevant documentation and
communication channels.


## Established community members

Established community members are expected to demonstrate their adherence to the
principles in this document, familiarity with project organization, roles,
policies, procedures, conventions, etc., and technical and/or writing ability.
Role-specific expectations, responsibilities, and requirements are enumerated
below.


## Membership Levels

| **Role**   | **Responsibilities**                                                  | **Requirements**                                                                                                                    | **Defined By**                                                 |
| ---------- | --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| Member     | Active contributor in the community                                   | Sponsored by 1 reviewer or maintainers. Multiple contributions to the project.                                                      | k0rdent GitHub Org Member                                  |
| Reviewers  | Review contribution from other members in the community               | Sponsored by a maintainer. Demonstrated history of reviews and contributions in a specific subprojects                              | [MAINTAINERS]() file entry |
| Maintainer | Define the technical direction of the project and oversee subprojects | Sponsored by another maintainer. Demonstrated history of reviews and contributions in specific subprojects and in the main project. | [MAINTAINERS]() file entry                     |

## Membership Responsibilities and Requirements

### Member

Members are active contributors who can be assigned issues and are expected to remain engaged in the project. Members are given the [Triage GitHub role](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization#repository-access-for-each-permission-level) to requested LitmusChaos repositories, in order to facilitate issue management and moderate discussions.

#### Requirements:

- Two-factor authentication enabled on GitHub.
- Multiple contributions, including code, documentation, or participation in discussions.
- Sponsored by an existing reviewers or maintainers.

#### Responsibilities:

- Moderate GitHub discussions and triage issues.
- Respond to issues and PRs assigned to them.
- Review and contribute to discussions actively.

#### Nomination Process:

To become a member:

1. Open an issue in the `k0rdent/k0rdent` repository.
2. Ensure your sponsors are `@mentioned` in the issue.
3. Include a list of your contributions that represent your work in the project.
4. Your sponsors must confirm their support by commenting with +1 on the issue.
5. Once the sponsors have responded, the request will be reviewed by project leads. Any missing information will be requested.

---

### Reviewer

Reviewers evaluate code quality and correctness for specific areas of the project.

#### Requirements:

- Member for at least 3 months.
- Active participation in discussions and issue reviews for 1 month.
- Reviewed or authored at least 5 significant PRs.
- Sponsored by a maintainer.

#### Responsibilities:

- Provide feedback on new PRs and issues.
- Focus on code quality and correctness during reviews.

#### Nomination Process:

To become a reviewer:
1. Open an issue in the `k0rdent/k0rdent` repository.
2. Ensure your sponsors are `@mentioned` in the issue.
3. Include examples of PRs you have authored or reviewed.
4. Your sponsor must confirm their support by commenting with +1 on the issue.
5. Once the sponsor has responded, the request will be reviewed by project leads. Any missing information will be requested.

---

### Maintainer

Maintainers are experienced contributors who drive the technical direction of the project and ensure its health and sustainability.

#### Requirements:

- Sustained contributions to the project over time (code, design, or community leadership).
- Demonstrated technical expertise and sound judgment in project discussions.
- Nominated and approved by existing maintainers.

#### Responsibilities:

- Review and merge PRs to maintain project quality.
- Set the technical direction and roadmap for the project.
- Mentor and guide members.
- Participate in governance decisions and resolve conflicts.
- Ensure transparency by documenting decisions publicly.

#### Nomination Process:

To become a maintainer:

1. Open an issue in the `k0rdent/k0rdent` repository.
2. Ensure your sponsors are `@mentioned` in the issue.
3. Include a summary of your contributions and their impact on the project.
4. Your sponsors must confirm their support by commenting with +1 on the issue.
5. Once the sponsors have responded, the request will be reviewed by project leads. Any missing information will be requested.

## Adding maintainers

Maintainers are first and foremost contributors that have shown they are
committed to the long term success of a project. Contributors wanting to become
maintainers are expected to be deeply involved in contributing code, pull
request review, and triage of issues in the project for more than three months.

Just contributing does not make you a maintainer, it is about building trust
with the current maintainers of the project and being a person that they can
depend on and trust to make decisions in the best interest of the project.

Periodically, the existing maintainers curate a list of contributors that have
shown regular activity on the project over the prior months. From this list,
candidates are selected and proposed as maintainers.

After a candidate has been proposed as maintainer via a Pull Request by any of the existing maintainers, the other maintainers are given five business days to discuss the candidate, raise objections and cast their vote. The Votes take place via the pull request comment. Candidates must be approved by at least 66% of the current maintainers by adding their vote on the PR. The reviewer role has the same process but only requires 33% of current maintainers. Only maintainers of the repository that the candidate is proposed for are allowed to vote. The candidate becomes a maintainer once the pull request is merged.

## Membership Management

- ### Inactive Members

  Members with no significant contributions for 12 months may be removed from the GitHub organization. Reinstatement requires going through the membership process again.

  - ## Removal of inactive maintainers

  Similar to the procedure for adding new maintainers, existing maintainers can
  be removed from the list if they do not show significant activity on the
  project. Periodically, the maintainers review the list of maintainers and their
  activity over the last three months.

  If a maintainer has shown insufficient activity over this period, a neutral
  person will contact the maintainer to ask if they want to continue being
  a maintainer. If the maintainer decides to step down as a maintainer, they
  open a pull request to be removed from the MAINTAINERS file.

  - ## Emeritus maintainers

  For committers who are stepping down or being removed due to inactivity,
  the project would like to memorialize their contributions to the project by
  recognizing them as Emeritus maintainers in the MAINTAINERS.md file. 
  It will include a brief paragraph summarizing their contribution to the
k0rdent project and recognize them as permanent Emeritus members of the
  community. While Emeritus maintainers are not active in the project, their
  expertise is always valued and their LGTM may count towards the required LGTM
  count to merge a code change into the project.

  If in the future an Emeritus maintainer has the desire or ability to return to
  contributing to the project, Emeritus maintainers can submit a pull request
  reversing their removal from the emeritus list and approval only requires
  2 LGTMs from current maintainers to return to full maintainer status in the
  project.

  - ## Stepping down policy

  Life priorities, interests, and passions can change. If you're a maintainer but
  feel you must remove yourself from the list, inform other maintainers that you
  intend to step down, and if possible, help find someone to pick up your work.
  At the very least, ensure your work can be continued where you left off.

  After you've informed other maintainers, create a pull request to remove
  yourself from the MAINTAINERS file.

- ### Changes in Membership Roles

  Role changes are discussed by project leads and approvers and finalized through consensus.




[k0rdent org]: https://github.com/k0rdent
[two-factor authentication]: https://help.github.com/articles/about-two-factor-authentication
