# Codesupply - Technical Project Plan

# Overview

CodeSupply is managed in the following GitHub project: https://github.com/orgs/codesupply-project/projects/5.

Work Packages, tasks, and subtasks are all described below. See [Example tasks](#example-tasks) for reference.

## Work packages

The work in the project is divided into four Work Packages:
* Work Package 1 - Consortium Management 
* Work Package 2 - Open Data Catalogs ([`codesupply-t2`](https://github.com/codesupply-project/management/issues/69))
* Work Package 3 - Open Source Analysis Tools ([codesupply-t3](https://github.com/codesupply-project/management/issues/76))
* Work Package 4 - Open Calls 
* Work Package 5 - Ecosystem Dissemination 

Work Packages 1 and 2 are represented as a Github issue with `issueId` named according to `codesupply-t<work package number>`, e.g Work Package 2 is represented as [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69).

*Note: The `t`, rather than `w` in `Work Package`, is used to make the tasks and subtasks easier to track.*

## Tasks

Each task relates to a Work Package, directly or indirectly, e.g.:
* top level task [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69) corresponds to Work Package 2
* task [`codesupply-t2-4`](https://github.com/codesupply-project/management/issues/73) is a sub task to [`codesupply-t2`](https://github.com/codesupply-project/management/issues/69)
* sub task `codesupply-t2-4-3` is a sub tack to [`codesupply-t2-4`](https://github.com/codesupply-project/management/issues/73)

Each task has meta information, such as

* Assignees - used to keep track of who is/are assigned to the ticket

For project management, we also use the *Planning* data:

* Estimate - a time estimate
* ProjectID - project identifier (CodeSupply)
* IssueID - the task identifier. Each task is name `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`
* Iteration - the iteration when the task is planned for
* TargetDate - the deadline for the task
* Priority - the task's priority
* Actual - the actual time the task took to finish

### Top-level tasks (Work Package) 

The top-level tasks (Work Packages) are divided into smaller tasks, in which case the issueid is named according to `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`.

You can find a list of the tasks in CodeSupply here: [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10).

### Tasks

These tasks are quite big, almost an entire project by themselves, and are best viewed as a group of tasks. They are named according to `codesupply-<task number>-<sub task>`, e.g. `codesupply-t2-4`.

Tasks are divided into smaller subtasks, in which case the issueid is named according to `codesupply-<task number>-<sub task>-<sub sub task>`, e.g. `codesupply-t2-4-2`

### Subtasks

Subtasks are assigned to one or more persons to work on. They are named according to `codesupply-<task number>-<sub task>-<sub sub task>`, e.g. `codesupply-t2-4-2`. Each subtask has a parent task (parent issue) to makes it easier to find the relationship to the bigger picture.

### Example tasks

Work Package 2 can be found here: [Software Supply Chain Open Data Catalog](https://github.com/codesupply-project/management/issues/69). You can find the tasks under Work Package 2 listed as "Subissues" under the description 

One of the listed tasks is [Create and deploy an open data catalog of code threats consisting of known vulnerabilities and known malicious open source software packages](https://github.com/codesupply-project/management/issues/73). In this task, you can find:
* "Parent" (just below the title on the left side) - which task it belongs to
* "Planning" (below Assigness, Labels, Type and Fields to the right - the details described above

## Milestones

In CodeSupply, there are multiple milestones, which you can find here: [Milestones View](https://github.com/orgs/codesupply-project/projects/5/views/9)

## Deliverables

CodeSupply includes deliverables, which can be found here: [Deliverables View](https://github.com/orgs/codesupply-project/projects/5/views/8)

# Roles

## Developer/engineer

As an engineer, you will likely focus on an subtask, e.g. `codesupply-t2-2-4`. The parent task, e.g. `codesupply-t2-2`, and work package, e.g. `codesupply-t2`, provide the context you need.

## Project manager

As a project manager, you will likely use the views:
* [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10)
* [Milestones View](https://github.com/orgs/codesupply-project/projects/5/views/9)
* [Deliverables View](https://github.com/orgs/codesupply-project/projects/5/views/8)

In the [Tasks View](https://github.com/orgs/codesupply-project/projects/5/views/10), you can follow the progress of the actionable subtasks.
