Overview
This guide Introduces how to manage Klaytn SW Projects.

Reference
Klaytn Group Dashboard : Klaytn 2.0 Dashboard 

Klaytn Dev Team Roadmap : 2022 Klaytn Dev Roadmap 

Klaytn Dev Team Schedule : 2022 Klaytn Dev Roadmap 

Dev Projects : Projects · klaytn/klaytn  

Klaytn Release Milestones : Milestones - klaytn/klaytn 

General Rules
GitHub is the main tool for project management.

A regular version is released every 2-3 month.

 

Unit

Objective

Creator

Detail

Roadmap

Team work and schedule

PM, Team leader, Cell leader

Status of overall team work and schedule

Milestone (Version)

Version management

PM, Team leader

Milestone contains major development items based on the Task

Create Milestone for each version

Only includes Tasks for the Milestone(version)

Project

Work management

Team leader, 

Cell leader

Create Project for each cell 

Includes Tasks, Story, SubTasks

Task (Issue)

High-level Dev item management

Team leader, Cell leader, Developer

To create an Issue

Mark Tasks using labels

Add to Milestone for each version and add to Project

May have multiple SubTasks

SubTask (Issue)

Dev item management

Cell leader, Developer

To create an Issue 

Mark SubTasks using labels

Add to Cell Project

Make it comprehensible for other developers

Story (Issue)

High-level item management

Team leader, Cell leader, Developer

To create an Issue

Mark Tasks using Story

Add to Cell Project

May have multiple SubTasks

Milestone(Version) Guide
Milestone is created for each version and task unit on the Roadmap.

Milestone for each version (e.g. v1.8.0)

Includes task Issues of projects

Release page includes other necessary action items such as documentation, binary update request and other work items.

e.g. https://krustuniverse.atlassian.net/wiki/spaces/KG/pages/9112519221 

Project Guide
Project for each cell’s task (e.g. Interface, Consensus)

A cell may divide up the project in multiple task units.

A task unit Project includes the Task Issues, Story Issues and the SubTask Issues

Issue Guide
To create an Issue, select an appropriate label (Task, Story, SubTask).

Select the appropriate Projects, Milestones in which the Issue is included.

Link Issue and PR.

Add the link to the SubTask Issue within the Task/Story Issue body.

e.g. https://github.com/klaytn/klaytn/issues/1104 

Kanban Board workflow
Issues have the following workflow.

To Do → In Progress → (PR) Review in Progress → Done