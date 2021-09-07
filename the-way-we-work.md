
# The Way We Work - NHSUK Software Development

---

TODO: Use corporate controlled document template

TODO: Do the Quick Guides reconcile with (match up to) the main document

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
4. Quarterly objective setting cycle
    4.1    
    4.2    
    4.3    
    4.4    
    4.5    
99. Appendices  
    - N1. Quick Guide for Principal Engineers  
    - N2. Quick Guide for Senior Developers  
    - N3. Quick Guide for Developers  
    - N4. Quick Guide for Contractors  
    - N5. Quick Guide for Delivery Managers & Product Owners  


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
- Autonomy: People work best when they control how they work
- Mastery: People work best when they are always learning
- Purpose: People work best when they choose what to work on
- Support: People work best when they are supported by their colleagues
- Structure: Progress is best made within an iterative and incremental system

Therefore:

- We will focus on future growth, not on past performance
- We will ensure individuals choose what to work on and how to do that work
- We will ensure individuals have the time to learn new things
- We will ensure individuals understand their role and responsibilities
- We will ensure individuals at all levels receive the support they need
- We will expand the current quarterly objective setting cycle to accommodate the above

### 1.4. How we will measure our success

The Way We Work will be judged a success if it helps NHSUK software developers rapidly deliver value to users whilst improving the technical quality of our products.

The leadership team will be held accountable for those business outcomes. The Way We Work is not intended to be a way to assess the performance of individuals.

The leadership team has decided to measure their success in 3 broad categories:

- Software Engineering Quality Dashboard
- Individual Contribution
- Team Participation

**Software Engineering Quality Dashboard**

The dashboard contains a number of technical measures for each of our products and we have been instructed to improve those scores.

The leadership team will monitor progress towards improving our scores, which will be achieved by developers completing objectives as part of their 20% time.

**Individual Contribution**

Users are happy when value is delivered continuously and developers are happy when a piece of work is complete. 

The leadership team will monitor how often developers are able to contribute code which is deployed to production.

**Team Participation**

We do our best work when we work together and when we help each other to improve.

The leadership team will monitor activity on Jira tickets.

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
|**LEADERSHIP and AUTONOMY**| 20% Time | SDMT Operational Planning | Strategy Implementation and Lean Improvement Projects | Vision and Strategy |
|**GROWING THE TEAM**| Pairing | Mentoring | Coaching | Delegating |
|**DUTY OF CARE**| Buddying | Line Management | Line Management | Line Management |
|**FINANCE**|  |  | Payments to Contractors | Overall Budget |

Developers should focus on activities in their own column rather than activities in preceeding columns.

---

## 3. Responsibilities Explained

This section lists the key best practices required within each of the responsibility areas.

We believe that if developers do these things, and if they try to always improve how they do them, then surely excellent outcomes will follow. 

### 3.1 Code

#### 3.1.1 Feature Development

This work will be carried out within a delivery team.

**Sprint Planning**

- attend sprint planning at the beginning of each sprint
- help to select which stories will be in the next sprint
- agree to select only those tickets which are sufficiently elaborated
- take into account your other responsibilities when deciding how many tickets to select
- agree only to an amount of work that you can comfortably complete (and deploy) in the next sprint
- ensure the solution is delivered incrementally, with a deployment each sprint

**Writing Code**

- write code which is deployed to production at least once per sprint
- collaborate with fellow developers to select appropriate tickets from the sprint backlog
- comply with coding standards while creating new code
- ensure you write unit tests, and collaborate with testers to ensure they can write tests too

**Jira Tickets**

- ensure Jira tickets assigned to you are kept up to date
- write notes on Jira tickets to record progress or document blockers
- write notes on Jira tickets to record mentoring/pairing and what was learned
- change the status of Jira tickets promptly to help keep your team informed

**Code Review**

- review the code of other developers in your team
- ensure your team is following a code review checklist
- review other people's code before writing your own
- invest enough time to provide a thorough review
- ensure code complies with our coding standards
- ensure you understand the new code
- use the code review as an opportunity to provide constructive advice and teaching

**Retrospectives**

- attend a retrospective at the end of each sprint
- before attending a retrospective, reflect on what went well in the last sprint and what went less well
- express your opinions honestly in the retrospective whilst respecting other people's feelings
- ensure that Jira tickets are created to address issues
- ensure improvement tickets are brought into the following sprint so that improvements can be realised

#### 3.1.2 System Design and Documentation

This work will be carried out within a delivery team.

- lead the design of the solution
- ensure the system remains well-documented at all times
- check the system against the criteria in the Engineering Quality Framework
- ensure the system conforms to approved NHSUK architecture patterns
- ensure all architecture decisions are documented in a standard location
- ensure code and tests are sufficiently documented
- ensure documentation allows new team members to contribute to the project
- ensure each project has a README.md file containing (at least) links to complete documentation
- maintain coding standards documentation

#### 3.1.3 Engineering Quality Framework

This work will be carried out in collaboration with SDMT.

- maintain and develop technical expertise in the EQF areas
- design and deliver technical prototypes or experiments to inform decisions and future development
- collaborate with the leadership team to decide the future technical direction of NHSUK
- ensure scores in the EQF areas are tracked for each of our products
- maintain up-to-date technical expertise through regular and routine learning
- collaborate with other Principal Engineers to share knowledge and discuss improvement ideas
- provide expert technical advice to SDMT and individual Senior Developers are required

### 3.2 Leadership and Autonomy

#### 3.2.1 20% Time

This work will be carried out within a delivery team.

- agree and document your personal objectives as part of the quarterly objective setting cycle
- spend one day each week working on your personal objectives
- update the corporate PDR system with progress against your objectives and key results
- ensure Jira tickets are created for your personal objectives...
- ... and ensure your ticket(s) are brought into the sprint backlog when appropriate

#### 3.2.2 SDMT Operational Planning

This work will be carried out in collaboration with SDMT.

- attend the Senior Developers Management Team (SDMT) meeting each week
- help to maintain and execute the SDMT Plan
- chair SDMT on a rotating basis, preparing the agenda and writing meeting minutes
- share important developments in your team or area of work
- raise and discuss problems that require cross-team collaboration to solve
- offer your assistance to help solve cross-team problems

#### 3.2.3 Strategy Implementation and Lean Improvement Projects

This work will be carried out in collaboration with the leadership team.

- design lean improvement projects to deliver improvements across multiple products
- lead, motivate and hold to account other developers to deliver the desired improvements
- identify and agree priority improvement areas with DTLT
- select one area per quarter to target as a personal objective

#### 3.2.4 Vision and Strategy

This work will be carried out in collaboration with the leadership team.

- define and communicate a clear vision for NHSUK software development
- collaborate with the leadership team to agree a strategy to deliver the vision

### 3.3 Growing the Team

#### 3.3.1 Pairing

This work will be carried out within a delivery team.

- work together with other members of a delivery team when you think this would be productive
- pairing can take place both with technical and non-technical delivery team members
- remember that pairing should lead to higher quality work and improved knowledge sharing

#### 3.3.2 Mentoring

This work will be carried out within a delivery team.

- mentor other developers within your delivery team
- actively seek out opportunities to develop the knowledge and skills of other developers
- pair with other developers whenever possible to complete feature tickets instead of working alone
- record who you paired with and what was discussed on the relevant Jira ticket

#### 3.3.2 Coaching

This work will be carried out on a one-to-one basis by arrangement with other developers.

- design programmes of coaching to improve developers' knowledge of agile software development
- provide one-to-one coaching to support developers through their immediate and specific work issues
- promote a coaching culture in NHSUK software development
- obtain a recognised coaching qualification
- develop and maintain knowledge of coaching methods, tools, techniques etc.

#### 3.3.3 Delegating

This work will be carried out in collaboration with the leadership team.

- identify opportunities to stretch and empower other members of the leadership team
- delegate responsibility for the completion of significant work packages (e.g. lean improvement projects)
- ensure resources are made available as agreed (e.g. developer time)
- provide support and guidance where requested or required
- champion the activities of other members of the leadership team (e.g. via all-hands presentations)

### 3.4 Duty of Care

#### 3.4.1 Buddying

This work will be carried out on an ongoing basis.

- act as the first point of contact to an apprentice or new joiner
- assist them with their issues in preference to doing other work

#### 3.4.2 Line Management of Permanent Staff

This work will be carried out on an ongoing basis.

When line managing Band 6/7 staff:

- comply with corporate policies and procedures
- meet with each of your reports on the first day of each sprint...
- ... to discuss and record progress towards objectives and key results
- ask your reports who they paired with in the previous sprint
- ask your reports what they learned in the previous sprint
- ensure your reports have sufficient work in the upcoming sprint
- ensure your reports have included some 20% Time work in the upcoming sprint
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

This work will be carried out on an ongoing basis.

- comply with corporate policies and procedures
- meet with each of your contractors on the first day of each sprint
- ensure your contractors have sufficient work in the upcoming sprint
- discuss the planned work to help identify any support you can provide
- participate in recruitment activities and interview panels

### 3.5 Finance

#### 3.5.1 Payments to Contractors

This work will be carried out on an ongoing basis.

- check with Delivery Managers to ensure contractor invoices are accurate
- make prompt payments to contractors (e.g. batched payments Tuesday morning)

#### 3.5.2 Overall budget

This work will be carried out on an ongoing basis.

- manage the budget for NHSUK software development
- make payments to suppliers
- approve other expenditure

---

## 4. Quarterly objective setting cycle

TODO

This is going to be very similar to the system Jacob already put in place. We can reuse some of the diagrams used to explain that system (in particular the goal-setting and 1-2-1 reviews) because they remain identical.

Need to produce a calendar showing key activities

Monthly-ish granularity i.e. to the level of when devs should be updating the corporate system with news about completed objectives.

- agree 3 suitable personal objectives and corresponding key results with your line manager
- ensure that one of these objectives is related to an agreed training activity
- enter your objectives and key results on the corporate PDR system


### 4.1 Summary

TODO

### 4.2 The Quarterly Cycle

TODO

### 4.3 Alignment with HR 

TODO

Create a "conversation check-in" once per fortnight (i.e. to capture what was discussed in the 1-2-1)

HR requires a "performance check-in" at the beginning and end of the year.
