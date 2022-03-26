---
title: Agile Scrum
last updated: Mar 26, 2022
---

# Agile Scrum

Main reference is still the official [Scrum Guide](https://www.scrumguides.org/scrum-guide.html)


## Scrum Values

> When the values of commitment, courage, focus, openness and respect are embodied and lived by the Scrum Team, the Scrum pillars of transparency, inspection, and adaptation come to life and build trust for everyone. The Scrum Team members learn and explore those values as they work with the Scrum events, roles and artifacts.


## Roles

Here we assume a setup where there's a Product Owner who's part of the delivery organization. The actual Product Owner is denoted here as _Customer Product Owner_.

* Scrum Team
  * [Product Owner](agile-product-owner.md)
  * [Scrum Master](agile-scrum-master.md)
  * Development Team - includes doers of the work i.e., Devs, Testers, Designers, BAs
* Customer Stakeholders
  * Program Sponsor
  * Customer Product Owner
  * Customer Technology Representative

## Scrum Events and Activities

Scrum only considers **5 Events**:

1.  Sprint Planning,
2.  the Sprint,
3.  Daily Scrum,
4.  Sprint Review, and
5.  Sprint Retrospective.

Other activities include: Release Planning, and Backlog Refinement.

Stakeholders primarily considered for this table include the Customer PO and the Scrum Team.

| Event | Required | Optional | Time box | Output |
|-|-|-|-|-|
| Release Planning | Customer PO, Scrum Team | | 6 hrs | Prioritized epics and user stories |
| Backlog Refinement | Customer PO, Scrum Team | Scrum Master | 1-2 hrs / wk | User Stories in the Product Backlog |
| Sprint Planning | Scrum Team | Customer PO | Sprint duration in weeks x 2 hrs | Sprint Goal, Sprint Backlog, Schedule, Team; <br/> Sprint Info Page, Sprint Data Page update |
| Daily Scrum | Scrum Team | Customer PO, PO | 15 mins | Updates on progress, raised impediments (if any) |
| Sprint Review | Customer PO, Scrum Team | Program Sponsor, Customer Technology Representative | Sprint duration in weeks x 1 hr(s) | Information on completed user stories, Closure of the Sprint; <br/> Updates to Sprint Info and Sprint Data pages |
| Sprint Retrospective | Scrum Team | Customer PO | Sprint duration in weeks x 1 hr(s) | Action items, learnings, <br/> Retro notes in Sprint Info Page |

## Processes

### Project Initiation

* Project Kick-off
* Hand-over from the Solutioning Team (if available)
  * Introduction of Scrum Team and Customer Stakeholders
  * High-level alignment on what's going to be built
  * High-level alignment on methodology
  * High-level timeline and what are the immediate next steps
* PO, SM, Tech Lead to work with Customer PO
  * Product Vision, high-level roadmap
  * Capture known risks, assumptions and dependencies
* SM to facilitate finalizing these working agreements, cadences, definition of done, etc. with the Scrum Team. PO to align these with Customer PO.
* Tech Lead to initiate discussions and setup of development prerequisites (framework, tooling, coding standards, etc.). Consult with Customer Technology Representative as needed.
* [More in Project Initiation](pm-project-initiation.md)
* [More in Working Agreements](agile-working-agreements.md)

### Release Planning

* SM facilitates the Release Planning.
* Customer PO and Scrum Team work together on user story mapping.
* **Output:** Prioritized epics and user stories, to be used by PO/Dev Team in creating user stories
* For reporting: PO works with Customer PO in documenting the high-level plans to be shared with Program Sponsor.
* [More on User Story Mapping](agile-user-story-mapping.md)

### Backlog Refinement

* PO and Dev Team sets aside time for backlog refinement to prepare for Sprint Planning.
* Optional: Customer PO is included in backlog refinement. Otherwise, PO serves as Proxy.
* As needed, Scrum Team to do ad hoc consultations to Customer PO and/or Business Technology Representative.
* **Output:** User Stories in the Product Backlog to be discussed in the Sprint Planning
* [More on Backlog Refinement](agile-backlog-refinement.md)

### Sprint Planning

* SM facilitates the Sprint Planning.
* Optional: Customer PO is included in Sprint Planning. Otherwise, PO serves as Proxy.
* PO shares the goal in mind, highlighting if there are any expectations of or demos to Stakeholders.
* PO/BA discusses the user stories. Dev Team sizes the user stories using poker planning.
* Dev Team raises if there are other user stories for tech backlog items or retrospective items that need to be handled in the sprint.
* PO and Dev Team agrees on the sprint goal and the user stories to be included in the Sprint.
* SM notes the Scrum Team's availability during the sprint, also highlighting any holidays.
* Dev Team creates tasks for the user stories and identifies who will do what.
* **Output:**
  * Sprint Goal, Sprint Backlog, Schedule (sprint duration, milestones, holidays), Team (members, availability)
  * Note: Sprint Backlog includes committed user stories, plus the plan for delivering (tasks, owners)
  * Sprint Info page, and initial numbers in the Sprint Data page
* For reporting: SM recaps to Scrum Team and Customer PO via email. *TBD: if other recipients are needed*
* [More on Sprint Data](agile-sprint-data.md)

### Daily Scrum

* SM facilitates the Daily Scrum.
* SM/Dev Team finalizes on which approach to use -- [Person-by-person or story-by-story](https://www.mountaingoatsoftware.com/blog/should-the-daily-standup-be-person-by-person-or-story-by-story).
* **Output:** Updates on progress, raised impediments (if any)

### Sprint Review

* SM facilitates the Sprint Review.
* Check against the Sprint Goal -- what was and wasn't accomplished.
* Dev Team recaps user stories that were demoed to the Customer PO, and uses this time to conduct any other needed demos.
* Dev Team can also conduct demo of the completed user stories to other stakeholders for feedback.
* **Output:**
  * Information on completed user stories, Closure of the Sprint
  * Updates to the Sprint Info page and Sprint Data page
* For reporting: SM recaps to Scrum Team and Customer PO via email. *TBD: if other recipients are needed*

### Sprint Retrospective

* SM facilitates the Sprint Retrospective.
* Optional: Customer PO is included in the Sprint Retrospective.
* **Output:** Action items for improvement, learnings, Retro notes in the Sprint Info page

### Project Reporting

* For customer: SM facilitates a regular touch base with the stakeholders. *TBD: F2F or email, cadence e.g., monthly status update meeting*
* For internal: SM facilitates a regular touch base with the stakeholders. *TBD: Email or F2F, cadence e.g., email status report every 2 weeks*
* **Output:** Meeting Minutes, Project Status Report pages and emails

## Workflows

### User Story Workflow

Actual status values will vary depending on the configuration of the tool and the project team conventions.

Happy path: ```NEW``` > ```READY``` > ```IN PROGRESS``` > ```FOR TESTING``` > ```FOR REVIEW``` > ```FOR DEMO``` > ```DONE```


* PO creates user stories into the Product Backlog. Dev Team can also create user stories and align it with PO. Initial state is ```NEW```.
* PO and Dev Team refines user stories during Backlog Refinement, and through other needed ad hoc discussions. Once the story is ready to be picked up in the coming sprints, it can be set to ```READY```.
* Dev Team sizes and creates plans (through tasks and identification of owners) for the implementation of the user stories during Sprint Planning.
* Once the Dev Team starts working on the user story, it's updated to ```IN PROGRESS``` usually by the Developer.
* Once the Developer confirms that it's ready for testing in the TEST environment, Developer updates state to ```FOR TESTING```.
* Once the Tester confirms that it's ready for review in the TEST environment, Tester updates state to ```FOR REVIEW```.
  * Testers assess bugs they find while testing the user story.
  * If acceptance criteria can't be met, depending on how big the user story is, they can either just track via the user story OR create a Bug Report.
  * Bug Reports are assigned to the Developer working on the user story. No need to size them. They follow a similar workflow, except that it doesn't need to go to the PO for review.
  * If the Scrum Team is on the fence about the bug found, they can discuss. Outcomes could be: align not to fix, OR create a bug report for it to be fixed within the Sprint, OR create a new user story for it in the product backlog.
  * If user story has bugs to be fixed, Tester sets state to ```FOR FIXING```. Bugs will need to be fixed by Developer and verified by Tester to mark the bug as ```DONE```.
* Once the PO accepts the user story, the state is updated to ```FOR DEMO```. Note that the PO can either review the user story directly in the provided environment, or request the Dev Team to demo it to her.
  * If it's not OK, Dev Team can: create a bug report for it to be fixed within the Sprint, OR create a new user story in the product backlog.
  * If user story has bugs to be fixed, PO sets state to ```FOR FIXING```. Bugs will need to be fixed by Developer and verified by Tester, and regression testing has to be done by the Tester before passing back to PO ```FOR REVIEW```.
* PO arranges for a demo to the Customer PO to cover the user stories that are already ready for demo. *This is not limited to the Sprint Review at the end of the sprint.*
* Once the Customer PO accepts the user story, the state is updated to ```DONE```. Similar to the when the PO reviews the user story, state can be reverted back to ```FOR FIXING``` if there's an item that needs to be handled within the sprint.

## Tools

* Agile tools for user story, bug management
  * Jira
  * Azure DevOps
* Poker Planning
  * [PlanITPoker](https://www.planitpoker.com/)
  * [Planning Poker](https://planningpoker.com/)
  * [Pointing Poker](https://www.pointingpoker.com/)
  * [Planning Poker Online](https://planningpokeronline.com/)
* Retro tools
  * [EasyRetro](https://easyretro.io/)
  * [Retromat - Inspiration and plans for (agile) retrospectives](https://retromat.org/)
  * [FunRetrospectives](https://app.funretrospectives.com/new)
