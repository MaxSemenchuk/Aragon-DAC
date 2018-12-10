# Aragon DAC Delivery Process

The following processes are designed to optimize the value produced by the Aragon DAC team.

### Methodology

The team will follow a Kanban style of delivery with a continuous pipeline of work that minimizes WIP without any hard constraints.  We favor Kanban over Scrum since the team capacity fluctuates from week to week and a consistent team capacity is a requirement of Scrum.  


### Meetings

* Daily scrum \(&lt;.5 hrs every weekday\)
  * Each dev reports in on progress, plans, blockers, etc.
  * PM should screenshare Zenhub board during meeting to ensure any updates are captured
* Backlog grooming \(1 hr every 2 weeks\)
  * PM should facilitate the meeting and screenshare the [Zenhub board](https://app.zenhub.com/workspaces/all-aragon-repos-5996d0a88c7c6963f4a4dfdc/boards?repos=98191281,104566586,133385725)
  * We’ll review and update issues for completeness, assignee, size, etc.
  * Review the Nest projects for any updates
* Retrospective \(1 hr once/month\)
  * Prior to the meeting, everyone records in a doc what’s working in our development process and what could be improved
  * At the meeting, all points are reviewed and discussed if necessary
  * PM documents all discussion and action items
* All devs meeting with Aragon One \(1 hr every 2 weeks\)
  * Meeting to sync up with the Aragon One team

### Zenhub Board Practices

[Main board](https://app.zenhub.com/workspaces/all-aragon-repos-5996d0a88c7c6963f4a4dfdc/boards?repos=98191281,104566586,133385725)

#### Columns

1. Backlog - default column for any new issues
2. Todo A1 - issues that have been marked for the Aragon One team to do
3. Todo A-DAC - issues that have been marked for the Aragon DAC team to do
4. Doing - issues in progress
5. Review - issues that have been completed and are being reviewed
6. Closed - complete issues

#### Labels

Labels are standardized across all repos \(hack, js, and cli at least\).  Their use is not required but is often helpful in tagging issues. Here is the core set:

1. priority: high - used to mark an issue as high priority in a way that is less likely to get lost in the shuffle of things; such issues should be listed at the top of a backlog or Todo column
2. bug
3. enhancement
4. good first issue - an easy issue for a new dev or a bounty
5. discussion - for features that are not approved yet and need more discussion
6. breaking change

#### Practices

* All devs should keep their issue status up-to-date and in the correct column in Zenhub
* Prioritize issues in the backlog and Todo columns by reordering and adding the "priority: high" label to the highest ones
* Break large issues into smaller ones and assign t-shirt sizing to them \(i.e. points 3, 8 or 21\); since we’re not running Scrum, we don’t need to go more granular than that
* When Zenhub releases the ability to add repos to more than one workspace \(end of Q1 2019\), a new cleaner board will be created to manage only the issues that are relevant to the Aragon DAC team.  It will include relevant aragon repos in addition to any Aragon DAC specific repos like the Giveth integration.
* The Aragon One team also uses Zenhub for their development; they are onboarding Patty, a new PM; Brett is also a key person who manages these issues

### Reports

* TBD

### Nest

* When a Nest project is approved, Maria assigns either an Aragon One or Aragon DAC dev to oversee the project execution and approve milestone deliverables
* Assigned dev joins a keybase channel with Nest project participants to allow for project communication
* Maria is managing in-flight Nest projects in the Aragon One Flow instance that we don’t have access to.  This will be managed by Stefano’s team in the future. She will be talking to Stefano about how he’d like to manage it but ideally it would be in a place where Aragon DAC and Aragon One devs have access.  This will be more important as we get assigned more projects in the near future and need to keep track of dates, scope, etc.
* These are the current assignments:
  * Wetonomy: Daniel
  * Tennagraph: Gabriel & Quazia



