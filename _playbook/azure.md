---
layout: post
title: Azure DevOps
author: Ajay Mistry
---
### Overview

Azure DevOps is a Software as a service (SaaS) platform from Microsoft that provides an end-to-end DevOps toolchain for developing and deploying software. It was formerly known as Visual Studio Team Services (VSTS) but has been rebranded as Azure DevOps.

At a high level, Azure DevOps provides a number of services/features to support teams to:

*   Capture and organise requirements and issues; plan and assign work and track team activity. The software is designed to support Scrum, Kanban and hybrid models. It also assists with prioritisation, portfolio management and release management.
*   Build and deploy applications; collaborate on code development; version code using git and manage test plans from web. It provides the ability to configure CI/CD pipelines for applications of any language, deploying to any platform or any cloud with full traceability and visibility across development activities
*   Azure DevOps Configuration To use Azure DevOps features, users must be added to a security group with the appropriate permissions and granted access to the tool. The ability to use specific artefacts and features of the tool are based on the access level and security group to which a user is assigned.

### Access levels

Access levels grant or restrict access to Azure DevOps features. This is in addition to permissions granted through security groups (see below), which provide or restrict specific tasks. Access levels enable administrators to provide their user base access to the features they need and only pay for those features.

When you add a user or group to a team or project, they're automatically granted access to those features supported by the default access level and those supported by the security group to which they are added.

Users can be assigned to one of the following access levels:

*   Stakeholder: Provides partial access to a limited set if features, can be assigned to unlimited users for free. Basic: Provides access to most features.
*   Basic + Test Plans: Provides access to all features included in Basic, as well as Azure Test Plans.
*   Visual Studio subscription: For users who already have a Visual Studio subscription.

### Security Groups

Security Groups define what users can do with each Azure DevOps feature their access level supports. The most common built-in security groups are Readers, Contributors and Project Administrators. The Team Administrator role grants permission to specific tasks of the features.

#### DevOps Security Groups

Project readers Permission to view project information, the code base, work items, and other artefacts but not modify them.

Project Contributors Permission to contribute fully to the project code base and work item tracking. They cannot manage or administrator resources.

Project Administrators Permission to administer all aspects of teams and project. Although they cannot create team projects.

If you require access to a board or require additional permissions please contact Wayne Eastaugh or Ajay Mistry.

### Azure Boards

The Azure Boards web service enables teams to manage their software projects. It provides a rich set of capabilities including native support for Scrum and Kanban, customisable dashboards, and integrated reporting.

Teams can track user stories, backlog items, task, features, and bugs associated with their project. The work item types and workflow available to the project is determined by the process that is being used.

#### Using the Azure Board

Here is an overview of the configured User Story card:

*   Title – This is a mandatory field used to capture the name of the User Story
*   Assignee – This field is used to capture the name of the person that the User Story is assigned to
*   State - This field captures the status of the User Story (see workflows above)
*   Area - This field captures the name of the project
*   Reason – This field captures the previous State
*   Iteration – This field captures the Sprint that the User Story is assigned to
*   Description – This field is used to capture the details of the requirement
*   Acceptance Criteria - This field is used to capture any acceptance criteria that must be satisfied when delivering the requirement
*   Technical Impact Assessment - This field is used to capture any information which describes the impact that delivering the requirement will have on any systems (existing or new)
*   Discussion - This section is used to facilitate collaboration within and conversation between the MDT members relating to the delivery of the User Story. Using the “@” feature to tag team members when asking or responding to an action or question results in notification emails being sent to those people.
*   Planning - This section captures details regarding the delivery effort and complexity of the User Story. The fields in this section are not mandatory and it is up to the project to decide which to use.
*   Story Points - This field captures the value of the Story Point value of the User Story.

### Requirements Management

#### ​​​​​​​Epic

Large long-running objective or strategic container for solution initiative. Epics can be defined as a big chunk of work that has one common objective. Think of it as a placeholder that can hold multiple features or stories which are focussed on the specific scope. For example, it could be a service or customer request or business requirement. An epic usually takes more than one sprint to complete.

#### Feature

Solution behaviour that fulfils a stakeholder need. Features are the functional components that make up a capability or product. For example, this might be a website brochureware page, a product search, basket, credit card payment or paypal integration. Again, dependent on scale and scope it may be necessary to include or omit this level to structure the solution requirements appropriately.

#### User Story

A small piece of functionality. A story is a granular expression of a piece of functionality (part of a feature) to be implemented. Its purpose is to inform implementation. As such it should be sufficiently small so it can be easily (usually within a couple of days) implemented so that it provides user value and is testable.

#### Task

Activity performed to deliver or implement the User Story. This could, for example, be the building of a code module or a creation of a test plan or a piece of analysis, a workshop etc or even more tangible activities such as a desk move, server installation or laptop build.

### Best Practice

The decomposition above supports Programme/Portfolio-level tracking and reporting - the Epics and Features provide a sufficient level of detail to form a Roadmap of delivery. User Stories enable the project to track the delivery of business requirements on a sprint by sprint basis. Tasks allow Developers/Testers/Analysts to manage their own deliverables within a Sprint.

The most important principle here is that every Task - every piece of work - is related to the delivery or implementation of a User Story which in turn supports the delivery of a Feature and/or in turn an Epic. Ultimately, if no business value can be traced back to the work you are performing then there is a question over whether it really needs be done.

The Azure DevOps boards are currently set-up with a three-tier requirement hierarchy (Epic-Feature-User Story) which should be sufficient to cater for the majority of project shapes and sizes. The boards however are flexible enough to scale up or down to support more complex or simpler project deliveries e.g. Epic-User Story for simpler projects or potentially, in extreme cases, Theme-Epic-Feature-User Story\* for even more complex projects.

Note: To enable Themes a [configuration change](ttps://docs.microsoft.com/en-us/azure/devops/organizations/settings/work/customize-process-backlogs-boards?view=azure-devops#add-portfolio-backlog) is required to add another backlog portfolio

Important: The use of consistent terminology with respect to Requirements hierarchy is very important in achieving a homogeneous user experience across Digital projects.

We are moving away from using Product Backlog Item as our requirements descriptor and the User Story will be our de-facto atomic business requirement going forwards and should be present in any requirements set that we deliver against.

The current accepted hierarchical entities are Epics,Features, User Story, Tasks and their relationships need to exist as set out in this Playbook. Every project should start with the default hierarchical structure Epic-Feature-User Story and scale up or down as necessary.

#### Knowledge Management

It is recommended that every project will create and maintain a Wiki page on their project Azure board to capture information relating to the objectives of the project and their solution delivery (including high level design, process flows and business rulesets etc).

This will act as the main knowledge repository for the project, product or service. Where possible all details of the technical implementation should be as close to the code base as possible e.g. in the form of comments surrounding the code.
