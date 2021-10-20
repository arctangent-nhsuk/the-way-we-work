
# The Way We Work - NHSUK Software Development

---

TODO: Use corporate controlled document template

---

> Not only must the physician show himself prepared to do what is necessary, he must also secure the co-operation of the patient, the attendants, and of external circumstances.

-- Hippocrates

---

- Version
- Author: Jacob
- Date: 1 September 2021
- Distribution: All (i.e. not a secret once approved)
- Reviewed by
- Approved by (Sean)
- Next review date

---

## Table of Contents

1. Introduction  
    1.1 What is The Way We Work?    
    1.2 Why have we created The Way We Work?    
    1.3 How we designed The Way We Work   
    1.4 How we will measure our success      
2. Roles Explained     
    2.1 Summary    
    2.2 Responsibility Matrix    
    2.3 Time Allocations    
3. Responsibilities Explained    
    3.1 Code    
    3.2 Leadership and Autonomy    
    3.3 Growing the Team    
    3.4 Duty of Care    
    3.5 Finance      
4. Quarterly Objective Setting Cycle    
    4.1 Summary    
    4.2 The Quarterly Cycle    
    4.3 Quarterly Objective Setting    
    4.4 Alignment with Corporate Performance Management System     

**Appendices**

- [Quick Guide for Developers](https://github.com/arctangent-nhsuk/the-way-we-work/blob/main/quick-guide-for-developers.md)
- [Quick Guide for Senior Developers](https://github.com/arctangent-nhsuk/the-way-we-work/blob/main/quick-guide-for-senior-developers.md)
- [Quick Guide for Principal Engineers](https://github.com/arctangent-nhsuk/the-way-we-work/blob/main/quick-guide-for-principal-engineers.md)
- [Quick Guide for Head of Development](https://github.com/arctangent-nhsuk/the-way-we-work/blob/main/quick-guide-for-head-of-development.md)
- [Quick Guide for Delivery Managers & Product Owners](https://github.com/arctangent-nhsuk/the-way-we-work/blob/main/quick-guide-for-delivery-managers-and-product-owners.md)


---

## 1. Introduction

### 1.1 What is The Way We Work?

This document and its appendices set out our vision for how software developers should go about their work within NHSUK. 

It provides a view of our policy arranged in such a way that the Development & Test Leadership Team ("the leadership team") can act independently in a fair and consistent way while bringing about the policy objectives.

While we'd encourage all developers and related professionals to read this document, the best way to get started is to read the appropriate Quick Guide in the appendices to see what this policy means for you specifically.

### 1.2 Why have we created The Way We Work?

Developers have told us that in order to do their best work they need a clearer explanation of their roles and more support from the leadership team. This document is our attempt to meet those needs.

The leadership team are also mindful of improvement targets set by senior managers including the Director of Product Delivery, the Head of Software Engineering, and NHSUK's Head of Delivery. This document explains how we will empower our developers to bring about the required improvements.

### 1.3 How we designed The Way We Work

We believe in:

- Growth: Everyone has the potential to improve
- Autonomy: People do their best work when they are able to choose how they work
- Mastery: People do their best work when they are able to learn the skills they need
- Purpose: People do their best work when they understand the purpose and value of what they are doing
- Support: People do their best work when they are supported by their colleagues
- Structure: Progress is best made within an iterative and incremental system

Therefore:

- We will focus on future growth, not on past performance
- We will ensure individuals choose what to work on next and how to do that work
- We will ensure individuals have the time to learn new things
- We will ensure individuals understand their role and responsibilities
- We will ensure individuals at all levels receive the support they need
- We will expand the current quarterly objective setting cycle to accommodate the above

### 1.4. How we will measure our success

The Way We Work will be judged a success if it helps NHSUK software developers rapidly deliver value to users whilst improving the technical quality of our products.

The leadership team will be held accountable for those business outcomes, which will be measured at a team level (i.e. for each delivery team). The Way We Work is not intended to be a way to assess the performance of individuals.

The leadership team has decided to measure their success in 3 broad categories:

- Software Engineering Quality Dashboard
- Individual Contribution
- Team Participation

**Software Engineering Quality Dashboard**

The dashboard contains a number of technical measures for each of our products and we have been instructed to improve those scores.

The leadership team will monitor progress towards improving our scores, which will be achieved by developers completing objectives as part of their Quality Time.

We will measure this for each delivery team as a whole rather than at an individual level.

**Individual Contribution**

Users are happy when value is delivered continuously because they can enjoy that value immediately.

Developers are happy when value is delivered continuously because it makes work more effective, efficient and sustainable.

The leadership team will monitor how often teams are able to contribute code which is deployed to production.

We will measure this for each delivery team as a whole rather than at an individual level.

**Team Participation**

We do our best work when we work together and when we help each other to improve.

The leadership team will monitor activity on Jira tickets.

We will measure this for each delivery team as a whole rather than at an individual level.

---

## 2. Roles Explained

### 2.1 Summary

All software developers have a shared purpose: to use software engineering best practices to support rapid and safe delivery of high-quality software.

However, we must match the right people to the right tasks to make sure all the work gets done and to make sure work remains challenging and enjoyable for all our developers.

Certain work areas require more knowledge, skills, and experience than others. Therefore, the seniority of a software developer determines which types of work they should focus on. 

As a general rule, as a developer progresses through their career we expect their general focus to shift from individual work to a whole-team approach.

### 2.2 Responsibility Matrix

The responsibility matrix below shows pay bands across the top and areas of responsibility down the side. The new responsibilities acquired at each pay band are therefore set out in a columnar fashion.

|ROLE TITLE|Developer (bands 6 & 7)|Senior Developer (band 8a)|Principal Engineer (band 8b)|Development & Test Manager (band 8c)|
|---| :--------------- | :--------- | :--------------- | -------------- |
| **FOCUS** | **SELF** | **SINGLE TEAM** | **MULTIPLE TEAMS** | **ALL TEAMS** |
|**CODE**| Feature Development | System Design, Feature Development, and Documentation | Engineering Quality Framework |                |
|**LEADERSHIP and AUTONOMY**| Quality Time | SDMT Operational Planning | Strategy Implementation and Lean Improvement Projects | Vision and Strategy |
|**GROWING THE TEAM**| Pairing | Mentoring | Coaching | Delegating |
|**DUTY OF CARE**| Buddying | Line Management | Line Management | Line Management |
|**FINANCE**|  |  | Payments to Contractors | Overall Budget |

Developers should focus on activities in their own column rather than activities in preceeding columns.

---

## 3. Responsibilities Explained

This section lists the key activities and associated best practices required within each of the responsibility areas.

We believe that if developers do these things, and if they try to always improve how they do them, then surely excellent outcomes will follow. 

### 3.1 Code

#### 3.1.1 Feature Development

Feature Development refers to all the activities involved in creating new features, enhancing existing features, or fixing bugs. These activities include sprint planning, writing code, managing Jira tickets, reviewing code, and carrying out retrospectives.

The reason we do Feature Development is to deliver value to our users. These users most frequently are members of the public but can also include our colleagues (e.g. through improvements to admin functionality).

As well as delivering value directly by working on user-facing features, we also deliver value indirectly by making improvements to the code and infrastructure in order to comply with non-functional requirements (NFRs) set out in the Engineering Quality Framework.

Feature Development work is carried out within a delivery team.

**Sprint Planning**

Sprint Planning is a planning activity undertaken by a delivery team before each new sprint begins. 

The reason we do Sprint Planning is to help the developers in the team select an achievable amount of work for the upcoming sprint, taking into account the relative value which will be delivered to users and the information available to developers (so that we only work on tickets which are "ready").

Best practices:

- attend sprint planning at the beginning of each sprint
- help to select which stories will be in the next sprint
- agree to select only those tickets which are sufficiently elaborated
- take into account your other responsibilities when deciding how many tickets to select
- agree only to an amount of work that you can comfortably complete (and deploy) in the next sprint
- ensure the solution is delivered incrementally, with a deployment each sprint

**Writing Code**

Writing Code is the act of transforming requirements into instructions a computer can follow in order to deliver value to users. This activity will typically involve a great deal of problem solving, both in determining what those instructions should be and also in how those instructions can be issued in a way that guarantees a high degree of success (e.g. through making code testable and the system observable).

Best practices:

- write code which is deployed to production at least once per sprint
- collaborate with fellow developers to select appropriate tickets from the sprint backlog
- comply with coding standards while creating new code
- ensure you write unit tests, and collaborate with testers to ensure they can write tests too

**Managing Jira Tickets**

We use Jira to manage the flow of work within delivery teams. It is important for all members of a team to manage their own Jira tickets in order for the delivery manager and other team members to have an accurate view of the team's progress.

Best practices:

- ensure Jira tickets assigned to you are kept up to date
- write notes on Jira tickets to record progress or document blockers
- write notes on Jira tickets to record mentoring/pairing and what was learned
- change the status of Jira tickets promptly to help keep your team informed

**Code Review**

Code Review is a quality assurance activity undertaken prior to new code being merged into the code repository's main branch.

The reasons we review code are to ensure that new code correctly interprets and solves requirements, to ensure new code complies with agreed standards, to ensure that at least one other person apart from the author understands the new code (i.e. the code reviewer), and to provide an opportunity for dialogue leading to teaching, learning, and continuing professional development of both the author and the reviewer.

Best practices:

- review the code of other developers in your team
- ensure your team is following a code review checklist
- review other people's code before writing your own
- invest enough time to provide a thorough review
- ensure code complies with our coding standards
- ensure you understand the new code
- use the code review as an opportunity to provide constructive advice and teaching

**Retrospectives**

Retrospectives are an opportunity to consolidate learning and to agree improvement activities before each new sprint begins. They help to ensure that a delivery team can adapt in order to maximise the flow of value to users.

Best practices:

- attend a retrospective at the end of each sprint
- before attending a retrospective, reflect on what went well in the last sprint and what went less well
- express your opinions honestly in the retrospective whilst respecting other people's feelings
- ensure that Jira tickets are created to address issues
- ensure improvement tickets are brought into the following sprint so that improvements can be realised

#### 3.1.2 System Design and Documentation

System Design and Documentation are important activities taking a whole-system approach to ensuring value can be delivered to users continuously.

We focus on ensuring systems are well designed - and remain so through refactoring - so that it is always as easy as possible to do additional feature development work without accruing technical debt.

We focus on ensuring the system is well documented so that new team members can be brought quickly up to speed where required, thus ensuring the team can be scaled up if completion of the product backlog is required sooner than is currently projected.

System Design and Documentation is carried out within a delivery team.

Best practices:

- lead the design of the solution
- ensure the system remains well-documented at all times
- ensure the system conforms to approved NHSUK architecture patterns
- ensure all architecture decisions are documented in a standard location
- check the system against the criteria in the Engineering Quality Framework
- ensure new systems comply fully with the EQF requirements
- agree reduced service readiness criteria and a remediation plan with TAB in exceptional circumstances where new systems cannot fully comply with the EQF
- ensure code and tests are sufficiently documented
- ensure documentation allows new team members to contribute to the project
- ensure each project has a README.md file containing (at least) links to complete documentation
- maintain coding standards documentation

#### 3.1.3 Engineering Quality Framework

The Engineering Quality Framework (EQF) is a set of agreed standards and best practices put in place across the Product Development directorate by our Head of Engineering. Compliance with these standards and best practices is measured and reported in the Engineering Quality Dashboard (EQD).

It is a priority for NHSUK software delivery leadership to deliver improvements to our EQD scores. This requires identifying and leading effective and efficient cross-product programmes of development activity that can be undertaken alongside feature development work.

This work will be carried out by the leadership team in collaboration with SDMT.

- maintain and develop technical expertise in the EQF areas
- design and deliver technical prototypes or experiments to inform decisions and future development
- collaborate with the leadership team to decide the future technical direction of NHSUK
- ensure scores in the EQF areas are tracked for each of our products
- maintain up-to-date technical expertise through regular and routine learning
- collaborate with other Principal Engineers to share knowledge and discuss improvement ideas
- provide expert technical advice to SDMT and individual Senior Developers are required

### 3.2 Leadership and Autonomy

#### 3.2.1 Quality Time

Quality Time is a reserved proportion of time to be used by developers to complete their own personal objectives. (Previously, we had the concept of "20% Time" which was then supplemented with 2 hours of separate training time. We have brought these two things together under the new Quality Time name.)

We agreed this arrangement with delivery managers because we feel it is important to set aside time for professional development and because we recognise that developers can make valuable contributions to a product which might otherwise be neglected due to the difficulty in measuring relative value against user-facing functionality.

Quality Time work will be carried out within a delivery team.

Best practices:

- agree and document your personal objectives as part of the quarterly objective setting cycle
- spend one day each week working on your personal objectives
- update the corporate PDR system with progress against your objectives and key results
- ensure Jira tickets are created for your personal objectives
- ensure your ticket(s) are brought into the sprint backlog when appropriate

#### 3.2.2 SDMT Operational Planning

Operational Planning is the act of solving and driving through the resolution of day-to-day problems arising within delivery teams. Senior Developers within delivery teams rely on the supoport and guidance of colleagues in other teams to coordinate actions which may involve more than one delivery team. These actions may relate to staff (e.g. agreeing to lend an expert to assist another team), or they may relate to the ongoing programmes of activity to drive improvements to the EQD (e.g. coordinating cross-team infrastructure improvements).

Operational Planning work will be carried out in collaboration with SDMT.

Best practices:

- attend the Senior Developers Management Team (SDMT) meeting each week
- help to maintain and execute the SDMT Plan
- chair SDMT on a rotating basis, preparing the agenda and writing meeting minutes
- share important developments in your team or area of work
- raise and discuss problems that require cross-team collaboration to solve
- offer your assistance to help solve cross-team problems

#### 3.2.3 Strategy Implementation and Lean Improvement Projects

Strategy Implementation and Lean Improvement Projects are means to achieve technical and non-technical improvements to the administration, management, or continual improvement of the whole NHSUK team of software developers, and also how the team interacts with its stakeholders (including colleagues in other professions).

Strategy Implementation and Lean Improvement Projects are carried out by the leadership team.

Best practices:

- design lean improvement projects to deliver improvements across multiple products
- lead, motivate and hold to account other developers to deliver the desired improvements
- identify and agree priority improvement areas with DTLT
- select one area per quarter to target as a personal objective

#### 3.2.4 Vision and Strategy

Vision and Strategy are high-level leadership tools used to communicate where the team is headed and to set out the ways in which the team should seek to get there.

Vision and Strategy development is carried out by the Head of Development in collaboration with the leadership team.

Best practices:

- define and communicate a clear vision for NHSUK software development
- collaborate with the leadership team to agree a strategy to deliver the vision

### 3.3 Growing the Team

#### 3.3.1 Pairing

Pairing is where two people work together to solve a problem and/or complete a piece of work.

We pair with others to bring additional mental capactity to bear, to provide an opportunity for mutual teaching and learning, and - especially when people from different professions collaborate - to eliminate delays that would otherwise occur due to handoffs.

Paising is carried out within a delivery team.

Best practices:

- work together with other members of a delivery team when you think this would be productive
- pairing can take place both with technical and non-technical delivery team members
- remember that pairing should lead to higher quality work and improved knowledge sharing

#### 3.3.2 Mentoring

Mentoring (in the context of NHSUK software development) is the deliberate transmission of technical knowledge from an expert developer to another developer.

This technical knowledge could relate to particular technologies, frameworks and tools, or it could relate to wider professional knoweldge such as the concepts and methods of agile software development.

Mentoring is carried out within a delivery team.

Best practices:

- mentor other developers within your delivery team
- actively seek out opportunities to develop the knowledge and skills of other developers
- pair with other developers whenever possible to complete feature tickets instead of working alone
- record who you paired with and what was discussed on the relevant Jira ticket

#### 3.3.3 Coaching

Coaching (in the context of NHSUK software development) is a way of leading others in order to develop autonomy and self-belief so that they are able to achieve their potential.

Coaching will be carried out on a one-to-one basis by arrangement with other developers.

Best practices:

- design programmes of coaching to improve developers' knowledge of agile software development
- provide one-to-one coaching to support developers through their immediate and specific work issues
- promote a coaching culture in NHSUK software development
- obtain a recognised coaching qualification
- develop and maintain knowledge of coaching methods, tools, techniques etc.

#### 3.3.4 Delegating

Delegating is where a senior leader gives another member of staff the responsibility and authority to achieve an objective or to complete an assigned task. It is an effective way of "scaling-up" leadership team capacity, capability, and resilience.

The Head of Development will Delegate to the leadership team.

Best practices:

- identify opportunities to stretch and empower other members of the leadership team
- delegate responsibility for the completion of significant work packages (e.g. lean improvement projects)
- ensure resources are made available as agreed (e.g. developer time)
- provide support and guidance where requested or required
- champion the activities of other members of the leadership team (e.g. via all-hands presentations)

### 3.4 Duty of Care

#### 3.4.1 Buddying

What this is:

Why we do this:

How we do this:

This work will be carried out on an ongoing basis.

- act as the first point of contact to an apprentice or new joiner
- assist them with their issues in preference to doing other work

#### 3.4.2 Line Management of Permanent Staff

What this is:

Why we do this:

How we do this:

This work will be carried out on an ongoing basis.

When line managing Band 6/7 staff:

- comply with corporate policies and procedures
- meet with each of your reports on the first or last day of each sprint (i.e. "between sprints")
- discuss progress towards objectives and key results and update the corporate performance management system 
- ask your reports who they paired with in the previous sprint
- ask your reports what they learned in the previous sprint
- ensure your reports have sufficient work in the upcoming sprint
- ensure your reports have included some Quality Time work in the upcoming sprint
- discuss the planned work to help identify any support you can provide
- ensure each of your reports is carrying out their role as described in this document
- participate in recruitment activities and interview panels

Additionally, when line managing Band 8a/8b staff:

- ensure your reports are appropriately managing their own reports
- ask your reports what they were able to teach others through mentoring
- ask what their reports achieved in the last 2 weeks
- ask what their reports are working on in the next 2 weeks
- record praiseworthy achievements

#### 3.4.3 Line Management of Contractors

Although contractors are not permanent members of staff, they are notionally line managed by Principal Engineers in order to provide them with the support they need in order to do their best work.

It is also important for Principal Engineers to ensure that contractors are delivering an appropriate amount of value, and be ready to take action if this is not the case.

Best practices:

- comply with corporate policies and procedures
- meet with each of your contractors on the first or last day of each sprint (i.e. "between sprints")
- ensure your contractors have sufficient work in the upcoming sprint
- discuss the planned work to help identify any support you can provide
- participate in recruitment activities and interview panels

### 3.5 Finance

#### 3.5.1 Payments to Contractors

Payments to contractors are made on a weekly basis in exchange for the services they provide to NHSUK delivery teams. It is important that there is an appropriate level of control around these payments because collectively they add up to well over £1 million per year. Principal Engineers are responsible for these payments Because contractors are notionally line managed by them.

Best practices:

- check with Delivery Managers to ensure contractor invoices are accurate
- make prompt payments to contractors (e.g. batched payments Tuesday morning)

#### 3.5.2 Overall budget

What this is:

Why we do this:

How we do this:

This work will be carried out on an ongoing basis.

- manage the budget for NHSUK software development
- make payments to suppliers
- approve other expenditure

---

## 4. Quarterly Objective Setting Cycle

### 4.1 Summary

NHSUK software development operates a quarterly objective setting cycle, with a recommendation that developers choose 3 objectives to complete each quarter. A developer's objectives must be agreed with their line manager prior to the commencement of each quarter and recorded on the corporate performance management system. Progress against objectives must also be recorded on this system after each fortnightly 1-2-1 meeting.

### 4.2 The Quarterly Cycle

Objective setting within NHSUK operates on a quarterly cycle, with quarters beginning on the first day of April, July, October, and January. We refer to each cycle as follows:

- Quarter One ("Q1") - April, May, and June
- Quarter Two ("Q2") - July, August, and September
- Quarter Three ("Q3") - October, November, and December
- Quarter Four ("Q4") - January, February, and March

Note that for consistency with the wider organisation we have chosen to align our quarter names with both the annual leave year and the financial year.

### 4.3 Quarterly Objective Setting

Developers must always have a list of objectives they are actively working towards in their Quality Time. These objectives should include training as well as feature development or tech debt remediation - a single objective may include combinations of each of these.

To make sure this happens, during the last two weeks of each quarter developers should meet with their line manager to agree new objectives for the next quarter.

Based on the amount of Quality Time available (about 12 days per quarter) we recommend that developers choose 3 objectives, with each objective being broken down into 4 "SMART" key results. This means that a developer can be expected to complete a key result each week on average.

We recommend objectives which are either relevant to a developer's current delivery team mission or to the wider Engineering Quality Framework priorities. This is because we believe that choosing objectives which pull in the same direction as the wider team will enhance the learning experience as well as benefitting the whole team.

To help developers choose appropriate objectives, Principal Engineers and Senior Developers will frequently design improvement projects that need contributions from developers in several teams. However, it is completely acceptable for a developer to pursue their own improvement ideas so long as these are agreed with their line manager.

### 4.4 Alignment with Corporate Performance Management System

NHSD has recently implemented a new web-based performance management application. Line managers must use this application to record everything relevant to personal objectives.

The corporate requirement is for annual objective setting with one "check-in conversation" per month. We have chosen to go above and beyond this requirement in order to more accurately match both the cadence of our work (i.e. fortnightly sprints) and the mercurial nature of software development (i.e. constant technological progress and rapidly changing digital systems).

Therefore we require that objectives are recorded - and, where appropriate, closed down - within the corporate web application on a quarterly basis. Additionally, a "conversation check-in" must be created for each fortnightly 1-2-1 between a developer and their line manager. At a minimum this should contain a review of progress against each objective (e.g. which key results have been completed and/or are currently being worked on, any support requested and received, any blockers to be overcome etc.).
