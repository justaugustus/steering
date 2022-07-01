﻿# Kubernetes Steering Committee Charter

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

## Changes

In instances where a process is not already specified within this document,
changes to the Steering Committee charter will be considered according to the
processes set forth in the committee's [operations documentation][changes].

[changes]: /operations/changes.md

## Membership

### Elections

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

### Resignation

If a committee member chooses not to continue in their role, for whatever
self-elected reason, they must notify the committee in writing. As a courtesy,
such notifications should be given at least 30 calendar days in advance of
their departure.

The committee can choose to accept a member's resignation and carry out
offboarding procedures at any time following the written notice.

### Removal

#### No confidence

A Steering Committee member may be removed by a two-thirds vote of no
confidence from other Steering Committee members.

The call for a vote will happen in a public Steering Committee meeting and a
GitHub issue in kubernetes/steering by a current member and must be seconded by
another.

There is a one week community feedback period for contributors to use to reach
out to Steering Committee members with their thoughts or log them on the open
issue including non-binding votes. After that period, Steering Committee
members have 48 hours to vote on the issue.

## Voting

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
