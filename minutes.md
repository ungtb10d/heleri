# Alpine Linux council weekly meeting minutes

## Meeting minutes 2021-08-24 (17:15 - 18:00)

### Present

* Chair: Natanael Copa
* Scribe: Kevin Daudt
* Carlo Landmeter
* Kaarle Kunkku (Consultant)

### Follow-up

#### Write an article about the council

Assigned to Kevin and Carlo. Has not been done yet. Need to pick a moment to do
it. Provide a draft for ncopa. Need to make sure the article is clear for others
and ensures this is not a major change in direction.

#### Legal entity

This is not urgent, so lets not rush it. We keep researching options and see
what suits us. The [issue][issue6] provides some options.

Main goal is to protect individual members from financial liability, though, at
the moment no one is using personal their credit-card for hosting.

Another goal is to protect individual members against legal action.

Third goal is the be able to accept donations as an organization.

The question is whether the overhead is worth the benefits, we will need to
research that. We could contact projects like NLnet to ask for advise. Carlo can
contact them.

Conclusion: We will post-pone this issue for later.
Follow-Up: Carlo

#### Document the governance structure

Assigned: Kevin

Goal: Adjust the governance handbook to document the current structure.
Follow-up: Kevin, ask Nathan Angelacos to help

One thing to document: Who assigns the council members, how are members removed
from the council and how to deal with members resigning.

Our current view is that the council decides who will be on the council. We want
to keep the direction of the project stable.

Umbrella projects might expect a certain governance style. Has influence on what
we do regarding legal entities.

Is the TSC involved in any decision making regarding members? We could have
special provisions in case for example someone disappears. It's a good idea to
consult the TSC in general.

Task: Document and communicate how the community can bring up issues.

### New points

#### How to handle monetary contributions

Something documented on [the wiki][alpine-developers], but it's severely
outdated.

We probably want to move this to the official documentation.

Question: who do we list as potential receivers of donations?

Hypothetical situation: what if some company wants to buy Alpine Linux?

A legal entity would help a lot with these situations. These issues have been
handled until now, we could wait until the entity has been setup.

Right now, we could point a potential donor to individual members.

Task: remove the developers wiki page

### Postponed

* Document the scope of the Council

[issue6]: https://gitlab.alpinelinux.org/alpine/council/-/issues/6
[alpine-developers]:https://wiki.alpinelinux.org/wiki/Alpine_Linux:Developers

## Meeting minutes 2021-06-22 (17:15 - 18:00)

### Present

* Scribe: Natanael Copa
* Kevin Daudt
* Chair: Carlo Landmeter

### Follow up previous

* Natanael has talked with every on the core team
* Carlo has created TSC project in gitlab

### meeting with TSC

Things to discuss with the TSC:

* how does it operate?
* what is the responsibility scope?
* how do you join/leave the TSC?

## Meeting minutes 2021-06-15 (17:15 - 18:00)

### Present

* Natanael Copa
* Chair: Kevin Daudt
* Scribe: Carlo Landmeter

### Follow up previous meeting

* Writing an article about the council (Status: pending)

### Agenda Item: MIPS Support

* Drop support for 3.14
* Try to bring support back in 3.14.1 when builder has catched up

### Agenda Item: Legal entity

* Create an issue to track it
* Do we actually need it
* The reason for now looks mostly financial
* See how we could implement it and with support of some organization/structure
* Would it matter in which country we set it up
* Postpone further discussion for next month

### Agenda Item: Commissioning the TSC

* Create a TSC project (Follow up Kevin)
* Setup an initial meeting with the members (Follow up Natanael)
* Create an agenda to discus in our first TSC meeting (Follow up Carlo)
* Do we need to have a TSC irc channel to discus sensitive matters

## Meeting minutes 2021-06-08 (17:15 - 18:00)

### Present

* Chair: Natanael Copa
* Scribe: Kevin Daudt
* Carlo Landmeter

### Follow-up previous meeting

* libera.chat
  * Handled, Ariadne will handle the technical part
* discord
  * Handled
* TSC members from core team
  * All existing members who were contacted indicated they want to be part of
    the TSC, they understood it means a commitment.
  * Need to work out the details of the TSC, and document it

### Agenda item: Drop mips64 for Alpine 3.14

* No objection from the council. Follow up: ncopa
* For new architectures, make sure we want to commit to stable releases

### Agenda item: expectations from TSC members

* Should be trusted and respected
* Should have social skills, being able to coordinate
* Example in following the code-of-conduct
* Willing to mentor new TSC members
* Not expected to be a permanent role

### Agenda item: how do we improve communication with the community

* *Problem*: how will people of the community know about the council, where meeting
  minutes are published, etc.
* Make better use of the website, write an article about the council Follow-up:
  clandmeter, kdaudt
* In addition, send it to the mailing list

### Other points

* Skip the meeting in the week of the 29th of June due to absence of members.

## Meeting minutes 2021-06-01 (17:15 - 18:00)

### Present

* **Chair**: Carlo Landmeter
* **Scribe**: Natanael Copa
* Kevin Daudt

### Agenda item: libera.chat IRC namespace & channels

* Carlo follows up

### Agenda item: Alpine discord

* The council has nothing against endorsing discord as long as we have volunteers that can manage it and make sure that the
  Alpine Code of Conduct is followed. Carlo follows up.

### Agenda item: TSC

* Natanael follows up with current core team members
* being a member should mean something, so members are expected to participate
* we believe there will monthly meetings



## Meeting minutes 2021-05-27 (17:15 - 18:00)

### Present

* **Chair**: Kevin Daudt
* **Scribe**: Carlo Landmeter
* Natanael Copa

### Agenda item: The structure and role of the Technical Steering Committee (TSC)

* TSC will be built around the current core team as defined in [Gitlab](https://gitlab.alpinelinux.org/groups/Core/-/group_members)
* TSC will coordinate all current teams
* Current teams are:
  * Development
  * Infrastructure
  * Documentation
  * Security
  * Cloud 
* TSC will (for now) operate in a similar way as Fedora [FRESCo](https://docs.fedoraproject.org/en-US/fesco/#_common_tasks_and_responsibilities)
* Each team will have assigned a team lead as currently defined or else defined by the TSC

### Agenda item: Documenting process of the governance structure

* Kevin will take responsibility in setting up the structure
* Carlo will support in writing documentation

### Agenda item: reschedule council meetings

* Reschedule council meetings to Tuesday 17:15 weekly (instead of Thursday) 

### libera.chat IRC namespace & channels (Gitlab issue [#1](https://gitlab.alpinelinux.org/alpine/council/-/issues/1))

* Register the channels under the new group/namespace
* Find users who are capable and interested to manage the IRC channels (Operators)
* Delegate control to a group to manage channels and cloaks

### Alpine discord (Gitlab issue [#2](https://gitlab.alpinelinux.org/alpine/council/-/issues/2))

* Postponed to next Council meeting due to time constraints

### Action items

#### Documenting process of the governance structure

* Followup: @ikke
* Deadline: TBD

#### Register Libera.chat channels

* Followup: @clandmeter
* Deadline: 2021-06-1

#### Delegate control over Libera channels and users

* Followup: @clandmeter
* Deadline: TBD


## Meeting minutes 2021-05-21 (17:15 - 18:00)

### Present

* Chair: Natanael Copa
* Scribe: Kevin Daudt
* Carlo Landmeter

### Agenda item: how to organize meetings

* Roles will rotate each meeting
    * Chairman will collect agenda items and lead the meeting
    * Chairman sets up the meeting
    * Scribe will collect the agenda items before each meeting
    * Scribe will be responsible for the minutes
* Each meeting will need to have a published agenda
* Each decision will require a person that is responsible and a deadline
* Meeting is time boxed (30-60 minutes)

* Community can request agenda points via issues

* Documentation should go in the governance handbook, based on decisions in the
  meeting

* In the beginning: weekly meetings, on thursday 17:15 CEST

### Agenda item: Technical steering committee

* Question: what to do with the current core team?
* Question: what is the role of the TSC

* Followup: next week

### Action items

* Create a repository for the meetings. 
    * Followup: @kdaudt
    * Deadline: 2021-05-27

* Investigate the structure of fedora (TSC)
    * https://docs.fedoraproject.org/en-US/fesco/
    * Followup: @kdaudt, @ncopa, @clandmeter
    * Deadline: 2021-05-27

