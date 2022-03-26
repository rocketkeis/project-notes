---
title: Solutioning
last updated:
---

# Solutioning

### Response Outline

Goes without saying that the response depends on the question or what is being asked for. Just don't lose track of that. We don't want to provide so much info and then realize we missed out answering the actual questions.

1. Project Background
2. Solution Overview
  * Paragraph(s) describing solution
  * Enumeration of included modules
  * High-level Architecture
3. Project Scope
  * In scope
  * Out of scope
4. Schedule
5. Cost
  * _IMPORTANT:_ Be careful of cost discussions (esp with customers). Note that cost will probably be padded with margin by the account.
  * Confirm with Delivery Manager on level of detail to include (e.g., just the total cost, monthly cost, if with breakdown)
  * Labor
  * Infrastructure
  * Licenses
  * FTE walk is prepared to get the cost, but not necessarily included in the response or SOW  
6. Assumptions
7. Dependencies


### Effort estimation

* SME / Tech Lead / Solution Architect to provide the breakdown of items to be estimated. This could then be used by the team to enter estimates for the tasks.
  * POC/Implementation - Dev SME
  * Test Automation - Test Automation SME
  * Testing Engagement - Testing SME
  * RPA, DT, UX, etc - corresponding SME depending on type of project
* Estimates could be in days (0.5, 1+)
* Can use PERT where estimate would be (P + 4*ML + O) / 6
  * P = pessimistic
  * ML = most likely
  * O = optimistic
* Possible considerations
  * Investigation, reading through documentation for each system that your app will need to interface with
  * Development
  * Testing
  * Design - PO/BA/Designer effort
  * Rework (review and revision, bug fixing and retesting)
* Put in allowances in case the client requires IE support


### Projecting the timeline

* Add 2 weeks (or more) for **[project initiation](pm-project-initiation.md)**
* Project initiation can include Sprint 0
* Plan for 2-week or 3-week sprints
  * For 2-week sprints, assume productive days is only 8 days instead of 10 -- to consider Sprint Ceremonies.
* _WATCHOUT:_ Based on the total development estimate, you can't just increase the number of developers by dividing it over the available time.
    * E.g., Total is 300 man-days.  And let's say you only have 100 calendar days.  It doesn't automatically mean you'll only need 3 persons.
* Allot time for security scan and remediation
* Allot time for preparing for app store deployment
    * Legal dependency
    * Certificates to use
* Allot time for hypercare (at least two weeks), handover, training
* For handover considerations, this depends on who will be in charge of the operations or support when the application is in production (e.g., if the team will be in DevOps mode or if they will fully handover to the Client for operations).
* As much as possible, allot folks full-time.  Avoid partial allocations.


### An example

Check that Available man-days \>\= Total estimates + Total sprint ceremony estimates (2 days per person per 10 day-sprint)

* Given:
  * Total dev estimate = 40 days
  * Total tester estimate = 30 days
* Proposal:
  * 1 month for development sprints (not including project initiation) = 20 days
  * 2 two-week sprints
  * 2 devs and 1 tester
* Check:
  * Available man-days = (2+1) members \* 20 days = 60 man-days
  * Total estimates = (40+30) = 70 man-days
  * Total sprint ceremony estimates = (2+1) members \* 2 days \* 2 sprints = 12 man-days
  * ? 60 \>= 70 + 12
  * Nope, meaning you need to revisit the proposal.


### Labor cost considerations

* Align on conversions/rates
  * Get latest rate cards from Manager
  * Rate cards contain hourly, daily, weekly, monthly rates - align if you'll just use hourly multiplied accordingly
  * If opting to multiply accordingly:
    * 8.5 hrs per day
    * 20 days per month
* Shift adjustment
* In line with shift adjustment, it's possible that taxi reimbursement will be allowed for the project team members. Confirm with Manager if it's still the site that will shoulder taxi reimbursements (hence, no impact on cost to client).
* Be careful of cost discussions (esp with customers). Note that cost will probably be padded with margin by the account.
