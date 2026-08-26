# Codesupply - Technical Project Plan

# Overview

The Codesupply is managed in the following Github project: https://github.com/orgs/codesupply-project/projects/5.

We have work packages, tasks and sub tasks which are all described below.

## Work packages

The work in the project has been divided into four work packages:
* Work Package 1 - Consortium Management 
* Work Package 2 - Open Data Catalogs ([`codesupply-t2`](https://github.com/codesupply-project/management/issues/69))
* Work Package 3 - Open Source Analysis Tools ([codesupply-t3](https://github.com/codesupply-project/management/issues/76))
* Work Package 4 - Open Calls 
* Work Package 5 - Ecosystem Dissemination 

Work packages 1 and 2 are represented as a Github issue with `issueId` named according to `codesupply-t<work package number>`, e.g Work Package 2 is represented as [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69).

*Note: The `t`, rather than `w` as in Work Package, is used to make the tasks and sub tasks easier to track.*

## Tasks

Each task relates to a work package, directly or indirectly, e.g.:
* top level task [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69) corresponds to (actually is) Work package 2
* task [`codesupply-t2-4`](https://github.com/codesupply-project/management/issues/73) is a sub task to [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69)
* sub task `codesupply-t2-4-3` is a sub tack to [`codesupply-t2-4`](https://github.com/codesupply-project/management/issues/73)

Each task has a bit of meta information, such as

* Assignees - used to keep track of who is/are assigned to the ticket

For project management we will also use the *Planning* data:

* Estimate - a time estimate
* ProjectID - project identifier (Codesupply)
* IssueID - the task identifier. Each task is name `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`
* Iteration - the iteration when the task is planned for
* TargetDate - the deadline for the task
* Priority - the task's priority (currently not in use)
* Actual - the actual time the task took to finish

### Top level tasks (Work Package) 

The top level tasks (work packages) are divided into smaller tasks, in which case the issueid is named according to `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`.

You can find a list of the tasks in Codesupply here: [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10).

### Tasks

These tasks are quite big, almost a project by themselves, and are probably best seen as a group of tasks and not necessarily something actionable. They are named according to `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`.

The tasks are divided into smaller sub tasks, in which case the issueid is named according to `codesupply-<task number>-<sub task>-<sub sub task>`, e.g. `codesupply-t2-4-2`

### Sub tasks (actionable)

These tasks are something we can assign to one or more persons to work with. They are named according to `codesupply-<task number>-<sub task>-<sub sub task>`, e.g. `codesupply-t2-4-2`. Each of these tasks has a parent task (parent issue) which makes it easy for you to find the relationship to the bigger picture.

### Example task

The second work package can be found here: [Software Supply Chain Open Data Catalog](https://github.com/codesupply-project/management/issues/69). You can find the tasks under this work package linked in the description field. 

An example task is [Create and deploy an open data catalog of code threats consisting of known vulnerabilities and known malicious open source software packages](https://github.com/codesupply-project/management/issues/73). In this tasks you can find:
* "Parent" (just below the title on the left side) - which task it belongs to
* "Planning" (below Assigness, Labels, Type and Fields to the right). In here you'll find the details described above)

This task has actionable tasks which are listed in the description. 

## Milestones

In Codesupply there are multiple milestones, which you can find here: [Milestones View](https://github.com/orgs/codesupply-project/projects/5/views/9)

## Deliverables

Codesupply has a couple of deliverables, which can be found here: [Deliverables View](https://github.com/orgs/codesupply-project/projects/5/views/8)

# Roles

## Developer/engineer

As an engineer you will most likely focus on an actionable item, e.g. `codesupply-t2-2-4`. The parent task, e.g. `codesupply-t2-2`, and work package, e.g. `codesupply-t2`, provide you with the context you need.

## Project manager

As a project manager you will most likely use the views:
* [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10)
* [Milestones View](https://github.com/orgs/codesupply-project/projects/5/views/9)
* [Deliverables View](https://github.com/orgs/codesupply-project/projects/5/views/8)

In the [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10) you can follow the progress of the actionable sub tasks.
