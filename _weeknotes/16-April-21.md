---
layout: post
title: 16 April 2021
date: 2021-04-16
author: Roni Saanumi
---

#### **Monitor – Jon Widdows**

- Just waiting on signatures on the Project Closure Report to formally announce closure, but in essence we have.
- While we have been waiting for the Service Team to start, the team have been fixing several urgent bugs and picked up two PBIs. All are expected to be released at the end of this week, if testing is successful.
- On Friday a demo of what has been built so far for payments will be given to the key stakeholders and the Common Components Team, ahead of formal handover.
- This will be the final week note on Monitor from a ‘project’ perspective, as it moves to the first Service Team with BSF, PSCRF and IRS.
- All the very best to Chris and the Team!


#### **Data Platform Service** - **Andrew Godleman**

- In our fourteenth sprint, slightly shorter than usual because of the Easter break, we prepared to create the cloud hosted environments that will enable the components to be production ready, and we also supported the ‘go live’ of the Affordable Homes service, using our authentication and authorisation components. We presented our work on 12/04/21.
- **Understanding Cloud Hosting** **and Deployment Pipelines** This sprint our cloud hosted environments for developing and testing were set up, meaning we are a lot closer to being able to move our code to a live production environment. It also meant the team had a chance to become familiar with the tools that move code from development environments to ‘live’ environments via a ‘deployment pipeline’.
- **Helm and Terraform** Software code is deployed (put on machines) via a tool called Kubernetes, and the Helm tool packages up all the configuration information necessary to make the software work, in a way that’s easy to re-use. Terraform is where the setup of the server environment is defined by lines of special code/instructions so it’s easy to deploy and manage server environments.
- **What we’re doing in Sprint 15...**Production-ready Location component In sprint 15 we’ll be putting our location component into our cloud-hosted environments, including configuring the deployment pipeline. How do I get my money? We’ll also be looking into the architecture of our payments component and how to use the Microsoft Azure Service Bus to deliver it.


#### **Cloud Hosting Service - Ben Patterson**

- Sprint 15 start end of sprint 14 - See the Showcase recording here - https://web.microsoftstream.com/video/a8e32867-96f4-48c3-8a22-35bb36b099ed
- Team continues work to further PROD hardening and iteration to prepare for CC PROD sub environments
- Spend review - this week we are catching up with Nikki to ensure we are on track as aim to prove some value get out of Alpha
- Some days out for the team with planned leave see a slightly reduced capacity this sprint.
- Content strategy and alignment ongoing, further refining the service wrapping content
- Successful backlog refinement results in a streamlined set of stories remaining before we plan Beta activities


#### **HR Performance Management/Building Brilliant Performance (Alpha) – Alycia & Al**

- Jez has completed work on process mapping, and leaves us to join the Investments Service Team (thanks and good luck Jez!)
- Angie has been holding more usability sessions with colleagues (including Directors) and writing up her findings
- Alycia and Georgia held Risk Scoring discussions with Nick from Operational Risk
- DPIA review and guidance will complete next week, but DPO confirmed that the contract with the supplier could proceed
- Contract ping pong has been happening at the latter end of the week with the supplier and Legal. We still hope to finalise and sign-off this week, so we can commence the 4 week implementation phase, with a targeted launch of the new digital service on Monday May 17th
- Digital Accessibility Centre audit for the new service is scheduled for Apr 19th

#### **E-learning tool (Live) – Al**

- Retrospective held with Gino and Nikki

#### **Service Teams – Rob, Chris, Jon, Steve & Al**

- Session held with PMO on Service Teams to further understanding on the first team and general approach
- Investments Service Team kicks off next week with an initial focus on knowledge sharing


#### **Data Platform Service - Martin Ciran**

- A major milestone has been achieved: we now have an **end-to-end** (non-production) **data platform service**! This means that all parts of the solution have been connected to each other and can be built in an automated way. We have a deployment pipeline that builds the core infrastructure and another one that builds the Data Platform itself. The data model for Finance use case (using PaDD and PCS data) have been deployed to the Curated layer and the corresponding datasets are available in Azure SQL. Power BI has been connected to that database and uses it as a source for Finance scorecards and other visualisations.
- The work continues on the Investment use case with a focus on Delivery Review report that is built based on the data from PCS and some Excel data sources. We've built a first version of the model which contains Spend and Receipts and are extending it with Starts and Completions data.
- We had an internal **GDS Alpha Assessment** last Friday. The focus was on non-technical aspects of the project. The assessors were interested in how we work with user and their needs, what we've learned in Alpha and what's our plan for the next phase. We have not received the report yet, but the feedback on the spot was positive, so we're hoping for the best.
- We are updating our backlog with stories required for the **next phase of the project** which will focus on making the service production ready.

#### **Service Teams – Chris**

- **Service Team (Infrastructure Grants and Loans)**

- A busy week preparing for the new Service Team of 11 to start on Monday 19th April for Investments (Phase 1: IRS, Monitor, BSF, PSCR)

- This includes moving across existing backlogs for the products and setting up / testing the configuration in Azure DevOps

- Much of the first week will be focused on both Onboarding, Training and Knowledge Transfer as the backlog of work is built up behind the scenes between the DM and PM

- Met with the business stakeholders as an introduction to the new Service Team model

- Met with the Product Manager to discuss the plan for the first sprints and iterations

- Attended various catch-ups with fellow Delivery Managers

- Phase 2 to follow in early course which will bring the Target, Bids (HBF, HIF and ERP), Partner Portal and DRAM products into the portfolio.

- Starting to review Ways of Working

#### **Data Protection and Privacy Management - Alpha**



- The project is to continue again from April 19th following the Digital Project pause

- Supplier follow-up discussions to take place next week with One Trust, Core Stream and InfoSec. This will enable the project team to make a final decision on the preferred product to procure

- Met with Helen Makin from Legal team before going on leave to discuss the paperwork that she requires to be able to reviewing the Legal terms for the supplier to be procured

- Preparation work completed ahead of attending the Heads of Profession meeting on 19th April to obtain the approval to move to the Beta phase

- Green light and written report received following the Alpha GDS Assessment in March.

#### **Management Information (MI Suite)**



- Planning completed for Sprint 8

- Good progress made with developing the Power BI report for KPI 8 (Low Medium Volume Builders) which is nearing completion to be pushed into System Testing. This is the last of the reports to be completed for Release 1

- The new Performance and Business Planning hub is coming together well which Munaf Turfail has been working on. A first pass was reviewed on Monday

- System Testing is now finished for KPI 4 (Share of funding to the top 50% of LAs by the price earnings ratio) and will now move into UAT

- Handover work of KPI 9 (MMC reporting) completed by Jez Hart to David Tait ahead of Jez moving to the new Service Team.



#### **Product Support Week notes - Rob Briggs**

This week, focus was working towards Release 64, with a quick IMS hotfix on Monday night for 5 must do fixes!

Only feels like yesterday it was EOY/SOY, but here we are back to the 2 week release cycle.

In total the team has completed 16 System Changes/Fixes applied on Thursday Night and the completion of an additional 34 PBI’s during the last 2 weeks (resulting in hotfixes or ad-hoc support calls for user requests or defects fixed and other changes awaiting release). As always there are PBI’s that have been migrated into the next sprint that have already had significant work done against them.

Quite a bit of work has been done on Azure Dev Ops getting the first service team area configured in the single Project Area, including implementing a significantly improved process, along side multiple dash boards.

This week has also seen the team release the 2021 FVA NROSH Survey for UAT to our colleges in Regulation, this is well ahead of schedule and should allow for them to bring forward their release of this major survey to RP's.
