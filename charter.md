# Kubernetes Steering Committee Charter

This document outlines the mission, scope, and objectives of the Kubernetes
Steering Committee.

## Mission

The Kubernetes Steering Committee is the governing body of the Kubernetes
project, providing decision-making and oversight pertaining to the Kubernetes
project bylaws, sub-organizations, and financial planning.  The Steering 
Committee also defines the project values and structure.

## How

* Adapt the role and structure of the Steering Committee as needed to meet the
  needs of the project.
* Responsibilities not explicitly delegated to other
  parties<sup>[2](#footnote2)</sup> through their charters reside with
  the Steering Committee.
* All management<sup>[1](#footnote1)</sup> responsibilities should be delegated to other
  parties<sup>[2](#footnote2)</sup>.
* All technical responsibilities should be delegated to SIGs (i.e. the SC shouldn't
  retain technical responsibilities itself).

## Direct responsibilities of the Steering Committee

The following responsibilities belong directly to the Steering Committee.

* Through the chartering review process, delegate ownership of, responsibility for
  and authority over areas of the project to specific entities<sup>[2](#footnote2)</sup>.
* Define, evolve, and defend the non-technical vision / mission and the values
  of the project.
* Charter and refine policy for defining new community groups<sup>[3](#footnote3)</sup>,
  and establish transparency and accountability policies for such groups
* Define and evolve project and group<sup>[3](#footnote3)</sup> governance
  structures and policies<sup>[4](#footnote4)</sup>.
* Act as a final non-technical escalation point for any Kubernetes repository<sup>[5](#footnote5)</sup>.
* Request funds and other support from the CNCF (e.g. marketing, press, etc.)
* Define and enforce requirements for community groups<sup>[3](#footnote3)</sup>
  to be in good standing such as having an approved charter.

### Not yet delegated responsibilities

The following responsibilities belong to the Steering Committe, but may be delegated in the future.

* Coordinate with the CNCF regarding usage of the Kubernetes brand and deciding
  which things can be called “Kubernetes”, as well as how that mark can be used
  in relation to other efforts or vendors.
* Decide, for the purpose of elections, who is a member of standing of the
  Kubernetes project, and what privileges that entails.
* Control and delegate access to and establish processes regarding
  any Kubernetes repository<sup>[5](#footnote5)</sup> 
* Control and delegate access to and establish processes regarding
  project resources/assets<sup>[6](#footnote6)</sup>  

## Transparency

The processes and operational model of the committee are intended to sustain a
healthy open source community.
Wherever and whenever possible, the committee strives to operate in a
transparent manner.

In keeping with the community's accepted definition of
[_"committee"_][committee], committees do not always operate in the open and
topics may arise that require discretion.

In the absence of a documented process, seated committee members will determine
an appropriate process and document it for transparency purposes.

[committee]: https://git.k8s.io/community/governance.md#committees

## Changes

In instances where a process is not already specified within this document,
changes to the Steering Committee charter will be considered according to the
processes set forth in the committee's [operations documentation][changes].

[changes]: /operations/changes.md

## Membership

### Composition

The Steering Committee is composed of seven (7) members.

### Resignation

If a committee member chooses not to continue in their role, for whatever
self-elected reason, they must notify the committee in writing. As a courtesy,
such notifications should be given at least 30 calendar days in advance of
their departure.

The committee can choose to accept a member's resignation and carry out
offboarding procedures at any time following the written notice.

## Voting

<!--

COMMUNITY CONSIDERATIONS

Voting

- [ ] Better define voting requirements in specific scenarios
  - Consider 5/7, as 4/6 is a simple majority of the entire committee
  - Clarify requirements respective to size of committee and round up e.g., 7 * 2/3 = 4.6666..., which would be 5 votes out of 7
  - Are there scenarios where unanimity should be considered?
  - [Stephen] What about a combination of both?

-->

In the course of the committee's operations, members will be expected to vote
on decisions within the body's purview.

These votes may proceed on agreed-upon platforms by the committee, such as:

* a pull request
* an issue
* a Steering Committee [meeting](#meetings)
* a mailing list

Unless otherwise specified by a process, the requirement for passing a vote is
a **_two-thirds supermajority of the
[fixed membership of the committee](#composition)_**.

Example:

* 7 (members) / 3 = 2.333...
* 2.333... * 2 = 4.666...
* Round up to the nearest whole number (5)
* 5 members in attendance would be required to vote during a meeting

### Abstention

For any self-elected reason, members of the committee may decide to abstain
from a vote.

Abstaining members will only be considered as contributing to quorum, in the
event that a vote is called in a meeting.

## Meetings

Steering Committee members are generally expected to attend every meeting. We
use the following guidelines to determine whether we have reached quorum and
are able to proceed with a meeting.

### Quorum

Quorum **to meet** is a **_majority of the
[fixed membership of the committee](#composition)_**.

Example:

* 7 (members) / 2 = 3.5
* Round up to the nearest whole number (4)
* 4 members in attendance would be required to meet

Quorum **to vote in a meeting** is a **_two-thirds supermajority of the
[fixed membership of the committee](#composition)_**.

Example:

* 7 (members) / 3 = 2.333...
* 2.333... * 2 = 4.666...
* Round up to the nearest whole number (5)
* 5 members in attendance would be required to vote during a meeting

<!--

STEERING CONSIDERATIONS

Removal

- [ ] Special election for specific removal scenarios
  - What is the perception of having a committee remove a representative that was elected by the community?
- [ ] Codify the voting process and channels for removal scenarios
- [ ] Consider CoCC guidance on removals as prior art: https://github.com/kubernetes/community/blob/master/committee-code-of-conduct/charter.md#removal
- [ ] Consider prior art in changes to maintainership e.g., SPIFFE/SPIRE (https://github.com/spiffe/spire/blob/main/MAINTAINERS.md#changes-in-maintainership)

COMMUNITY CONSIDERATIONS

No Confidence

- [ ] Provide guidelines on "no confidence"
  - Process transparency could be considered inversely proportional to the importance of these guidelines

Removal

- [ ] Scope of removal of members (one, many)
- [ ] Precedence for removal scenarios
- [ ] What details of removal scenarios should be public/private?
  - Call for removal?
  - Reason for removal?
  - Vote on removal?
  - What are the public artifacts of the removal process?
- [ ] What details of election results should be public/private?
- [ ] Consequences of removal scenarios
  - Are individuals ineligible for re-election?
    - Should community members have an opinion in this decision?
- [ ] When is removal appropriate?
- [ ] How should CoC concerns be considered in the removal process? Should they be?
- [ ] Guard against "popularity contests" or "burning at the person" in committee voting scenarios
- [ ] Are there antitrust implications in the removal process?
- [ ] Special elections may not have representative turnout
  - Define guidance on acts and thresholds to consider in a vote for removal
- [ ] Is removal an extraordinary power to grant?
  - "Policies like this have to work for the good of the community both when used well and when used poorly."
- [ ] Define removal process guidelines
  - "brief rationale for removal" + short time + "brief rebuttal"
  - Offer resignation as an option

-->

## Elections

Every year, the Steering Committee holds a general election for open seats with
[SIG Contributor Experience][sig-contribex] owning the process.

SIG Contributor Experience may delegate this responsibility to a subproject.

Our [election policy document][general-elections] covers the details for how
this works.

Policy and operations of special elections initiated by the Steering Committee
for other reasons (as yet to be determined) may be handled by some agreed-upon
[process][changes] by the committee.

[general-elections]: /elections.md
[sig-contribex]: https://git.k8s.io/community/sig-contributor-experience

### Vacancies

In the event of a resignation, removal, or other loss of an elected Steering 
Committee member, the candidate with the next most votes from the previous 
election will be offered the seat. This process will continue until the seat is 
filled. 

In case this fails to fill the seat, a special election for that position will 
be held as soon as possible. [Eligible voters](https://git.k8s.io/steering/elections.md#eligibility-for-voting) from the most recent election 
will vote in the special election (ie: eligibility will not be redetermined at 
the time of the special election). A committee member elected in a special 
election will serve out the remainder of the term for the person they are 
replacing, regardless of the length of that remainder.

## Inclusive Leadership Training

Members of the committee must take an
[Inclusive Open Source Community Orientation course](https://training.linuxfoundation.org/training/inclusive-open-source-community-orientation-lfc102/)
in support of our community values.  Members are required to report
completion of the course as part of on-boarding within 30 days from
the date of their appointment.


---

<a name="footnote1">1</a>: Decisions and work pertaining to the daily 
operations of the project.

<a name="footnote2">2</a>: Such as individuals, Special Interest Groups and
Committees

<a name="footnote3">3</a>: Such as Special Interest Groups, Working Groups,
and Committees

<a name="footnote4">4</a>: including how contributors become 
committers/maintainers, approvers, reviewers, members, etc.  As well as 
responsibilities associated with these role

<a name="footnote5">5</a>: Currently includes all repositories under the 
github organizations kubernetes, kubernetes-sigs, kubernetes-incubator, 
kubernetes-security, kubernetes-client, etc. and is expected to expand in the
future.

<a name="footnote6">6</a>: Including artifact repositories, build and test
infrastructure, web sites and their domains, blogs, social-media accounts,
etc.
