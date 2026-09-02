---
title: "Advance_Jra"
---

# Advance_Jra

**JIRA ADVANCED PRACTICE**

**PHASE 4 -- Enterprise Jira Simulation**

**Project: AI Healthcare Platform**

**Lesson 8 -- Jira Automation & Advanced Rules**

**Automating Enterprise Agile Delivery Processes**

**Learning Objective**

After this lesson, you will understand:

✅ What Jira Automation is\
✅ How enterprise teams reduce manual work\
✅ How BA uses automation for requirement governance\
✅ How workflow rules are automated\
✅ How notifications and approvals work\
✅ How automation improves delivery quality

**1. What is Jira Automation?**

Jira Automation allows teams to create rules:

\"When something happens, automatically perform an action.\"

Basic structure:

TRIGGER

↓

CONDITION

↓

ACTION

Example:

When Story moves to UAT

↓

Check Acceptance Criteria

↓

Notify Business Tester

**2. Why Enterprise Teams Use Automation**

Without automation:

❌ Manual status updates\
❌ Missed notifications\
❌ Delayed approvals\
❌ Poor visibility

With automation:

✅ Faster workflow\
✅ Better governance\
✅ Less human error\
✅ Consistent process

**3. Jira Automation Components**

**1. Trigger**

Something happens.

Examples:

-   Issue created

-   Status changed

-   Sprint started

-   Due date reached

**2. Condition**

A rule check.

Examples:

-   Priority = High

-   Issue Type = Bug

-   Component = AI Engine

**3. Action**

What Jira does.

Examples:

-   Assign issue

-   Send notification

-   Update field

-   Create issue

**4. Automation Rule Example 1**

**Auto Assign BA Review**

**Business Need**

Every new requirement must be reviewed by BA.

Rule:

TRIGGER:

New Story Created

CONDITION:

Issue Type = Story

ACTION:

Assign to BA

Result:

Every new story automatically enters BA queue.

**5. Automation Rule Example 2**

**Block Development Without Acceptance Criteria**

**Problem**

Developers receive incomplete stories.

Rule:

TRIGGER:

Story moved to Development

CONDITION:

Acceptance Criteria is empty

ACTION:

Prevent transition

AND

Notify BA

Business Benefit:

Improves requirement quality.

**6. Automation Rule Example 3**

**Notify QA When Development Completes**

Before:

Developer finishes → waits → QA discovers later

Automation:

TRIGGER:

Status changes:

Development → QA

ACTION:

Notify QA Team

Result:

Faster testing cycle.

**7. Automation Rule Example 4**

**High Severity Bug Escalation**

Healthcare systems require fast response.

Scenario:

Critical patient safety defect reported.

Rule:

TRIGGER:

Bug Created

CONDITION:

Priority = Critical

ACTION:

Assign QA Lead

AND

Notify Product Owner

AND

Create Incident Ticket

**8. Automation Rule Example 5**

**Sprint Completion Reminder**

Problem:

Incomplete stories remain unnoticed.

Rule:

TRIGGER:

24 hours before sprint end

CONDITION:

Open issues exist

ACTION:

Notify Scrum Team

Message:

\"Please review incomplete sprint items.\"

**9. BA Requirement Governance Automation**

Now we design BA-specific automation.

**Rule A**

**Missing Business Value**

Trigger:

Story created

Condition:

Business Value field empty

Action:

Notify Product Owner

**Rule B**

**Requirement Aging Alert**

Trigger:

Issue stays in Business Analysis \> 5 days

Action:

Alert BA Lead

**Rule C**

**UAT Approval Tracking**

Trigger:

Story moved to UAT

Condition:

UAT approver missing

Action:

Assign Business Tester

**10. Automation for Healthcare Compliance**

Healthcare software requires audit visibility.

**Example:**

Requirement changes after approval.

Rule:

TRIGGER:

Approved requirement modified

ACTION:

Create Change Request

AND

Notify Compliance Team

Why?

Because healthcare systems require controlled changes.

**11. Jira Automation with AI Healthcare Platform**

Let\'s design practical rules.

**Automation Rule Table**

  -----------------------------------------------------------------------
  **Rule**                   **Trigger**                  **Action**
  -------------------------- ---------------------------- ---------------
  BA Assignment              Story created                Assign BA

  Incomplete Story           Move to Development          Block

  QA Notification            Move to QA                   Notify QA

  Critical Bug               Bug created                  Escalate

  UAT Reminder               UAT pending                  Notify users

  Sprint Alert               Sprint ending                Reminder

  Requirement Change         Approved story edited        Create CR
  -----------------------------------------------------------------------

**12. Automation and Workflow Together**

Enterprise flow:

Story Created

↓

Automation:

Assign BA

↓

BA Review

↓

Automation:

Check Acceptance Criteria

↓

Development

↓

Automation:

Notify QA

↓

UAT

↓

Automation:

Request Approval

↓

Done

**13. Automation Limitations**

Automation is powerful, but:

It cannot replace:

-   Business judgment

-   Requirement analysis

-   Stakeholder decisions

-   Prioritization

Example:

Jira can notify:

\"Risk detected\"

But BA decides:

\"What is the business impact?\"

**14. Senior BA Automation Checklist**

A BA should identify:

☑ Repetitive manual activities

☑ Approval delays

☑ Missing information

☑ Communication gaps

☑ Compliance requirements

☑ Reporting needs

**Completed Jira Artifact**

AI Healthcare Platform

JIRA AUTOMATION DESIGN

✅ Automation Concepts

✅ Workflow Automation

✅ BA Governance Rules

✅ Notification Rules

✅ Approval Automation

✅ Compliance Automation

STATUS: COMPLETED

**Real BA Learning**

A junior Jira user updates tickets manually.

A senior BA designs a system where:

Jira itself helps enforce quality, visibility, and governance.

**Next Lesson**

**Lesson 9 -- Jira JQL, Advanced Search & Enterprise Filters**

We will learn:

-   JQL fundamentals

-   Advanced queries

-   Finding blocked work

-   Tracking requirements

-   Creating saved filters

-   Building dashboards from filters

-   BA/Product Owner real-world queries

This is essential for senior BA roles.

continue

**JIRA ADVANCED PRACTICE**

**PHASE 4 -- Enterprise Jira Simulation**

**Project: AI Healthcare Platform**

**Lesson 9 -- Jira JQL, Advanced Search & Enterprise Filters**

**Finding, Tracking & Managing Enterprise Work Items**

**Learning Objective**

After this lesson, you will understand:

✅ What JQL is\
✅ How BAs use Jira search professionally\
✅ How to create advanced filters\
✅ How to track requirements, defects, risks, and releases\
✅ How saved filters power dashboards\
✅ How to answer stakeholder questions quickly

**1. What is JQL?**

JQL = **Jira Query Language**

It is a search language used to find Jira issues.

Simple search:

\"Show me all high-priority bugs.\"

Advanced search:

\"Show me all critical defects in Release 1.0 assigned to QA that are
blocking UAT.\"

**2. JQL Structure**

Basic format:

FIELD OPERATOR VALUE

Example:

priority = Highest

Meaning:

Find issues where priority is Highest.

**3. Common JQL Fields**

**Issue Fields**

  -----------------------------------------------------------------------
  **Field**                   **Purpose**
  --------------------------- -------------------------------------------
  project                     Project name

  issueType                   Story, Bug, Task

  status                      Current stage

  priority                    Importance

  assignee                    Owner

  reporter                    Creator

  created                     Creation date

  updated                     Last change
  -----------------------------------------------------------------------

**4. Basic JQL Examples**

**Find all Stories**

project = AHP

AND issuetype = Story

**Find Bugs**

project = AHP

AND issuetype = Bug

**Find High Priority Issues**

priority = High

**Find Open Issues**

status != Done

**5. BA Real-World JQL Queries**

Now we simulate BA daily work.

**Query 1**

**\"Show me all stories waiting for BA review\"**

project = AHP

AND status = \"Business Analysis\"

Use:

-   Requirement tracking

-   BA workload management

**Query 2**

**\"Which stories are blocked?\"**

project = AHP

AND status = Blocked

BA Action:

Investigate:

-   Missing requirement?

-   Dependency?

-   Technical issue?

**Query 3**

**\"Which stories are ready for development?\"**

project = AHP

AND status = \"Ready for Development\"

Purpose:

Sprint preparation.

**Query 4**

**\"Show UAT pending items\"**

project = AHP

AND status = UAT

BA Uses:

Follow up with business testers.

**6. Advanced JQL Operators**

**AND**

Both conditions must match.

Example:

project = AHP

AND priority = Highest

**OR**

Either condition.

Example:

priority = High

OR priority = Highest

**NOT**

Exclude.

Example:

status != Done

**IN**

Multiple values.

Example:

status IN (\"QA Testing\",\"UAT\")

**7. Tracking Sprint Progress**

Query:

project = AHP

AND sprint = \"Sprint 1\"

Shows:

All sprint items.

**8. Tracking Requirement Changes**

Important for BA governance.

Query:

project = AHP

AND issuetype = Story

AND updated \>= -7d

Meaning:

Stories changed in last 7 days.

BA checks:

-   What changed?

-   Why changed?

-   Was approval received?

**9. Release Management Queries**

Example:

Find Release 1.0 items.

project = AHP

AND fixVersion = \"1.0\"

Shows:

Everything planned for release.

**10. Finding Delayed Work**

Query:

project = AHP

AND status != Done

AND created \<= -30d

Meaning:

Issues older than 30 days still incomplete.

**BA Action:**

Review:

-   Is requirement still valid?

-   Is priority correct?

-   Is dependency blocking?

**11. Creating Saved Filters**

A filter saves a useful query.

Example:

**Filter Name**

\"BA Requirement Review Queue\"

JQL:

project = AHP

AND status = \"Business Analysis\"

ORDER BY priority DESC

Benefits:

Every morning BA opens this filter.

**12. Enterprise BA Filter Library**

A senior BA maintains filters:

**Filter 1**

**My BA Queue**

assignee = currentUser()

AND status != Done

**Filter 2**

**Critical Healthcare Issues**

priority = Highest

AND status != Done

**Filter 3**

**UAT Monitoring**

status = UAT

**Filter 4**

**Sprint Risk**

sprint in openSprints()

AND status != Done

**Filter 5**

**Requirement Changes**

issuetype = Story

AND updated \>= -14d

**13. JQL + Dashboard Integration**

Dashboards use filters.

Example:

BA Dashboard:

Widget:

\"Pending Requirements\"

Uses:

status = \"Business Analysis\"

Widget:

\"Blocked Stories\"

Uses:

status = Blocked

**14. Stakeholder Questions Using JQL**

**Question:**

\"How many features are left for Release 1.0?\"

Query:

fixVersion = \"1.0\"

AND issuetype = Story

AND status != Done

**Question:**

\"Why is sprint delayed?\"

Queries:

status = Blocked

and

status = \"Business Analysis\"

**Question:**

\"Which requirements changed recently?\"

issuetype = Story

AND updated \>= -7d

**15. BA JQL Best Practices**

A senior BA should:

✅ Create reusable filters\
✅ Name filters clearly\
✅ Avoid overly complex queries\
✅ Use dashboards for visibility\
✅ Review outdated filters regularly

**Completed Jira Artifact**

AI Healthcare Platform

JQL & FILTER MANAGEMENT

✅ JQL Fundamentals

✅ Advanced Queries

✅ BA Filters

✅ Release Queries

✅ Sprint Queries

✅ Requirement Tracking

✅ Dashboard Integration

STATUS: COMPLETED

**Real BA Learning**

A junior BA searches Jira manually.

A senior BA builds a visibility system where answers are available
instantly.

**Next Lesson**

**Lesson 10 -- Enterprise Jira Dashboard Design & Reporting Framework**

We will create:

-   BA Command Center Dashboard

-   Product Owner Dashboard

-   Scrum Master Dashboard

-   Executive Dashboard

-   Healthcare Compliance Dashboard

This will complete the Jira Advanced Practice simulation.

continue

**JIRA ADVANCED PRACTICE**

**PHASE 4 -- Enterprise Jira Simulation**

**Project: AI Healthcare Platform**

**Lesson 10 -- Enterprise Jira Dashboard Design & Reporting Framework**

**Building Real Enterprise Dashboards**

**Learning Objective**

After this lesson, you will understand:

✅ How enterprise Jira dashboards are designed\
✅ Difference between BA, Product Owner, Scrum Master, and Executive
dashboards\
✅ Which gadgets are used for different purposes\
✅ How dashboards support decision-making\
✅ How healthcare projects track delivery, risk, and compliance

**1. What is a Jira Dashboard?**

A Jira Dashboard is:

A visual command center that converts Jira data into actionable
information.

A dashboard answers:

-   What is happening?

-   What is delayed?

-   What needs attention?

-   Are we delivering business value?

**2. Dashboard Design Principle**

A good enterprise dashboard follows:

DATA

↓

VISIBILITY

↓

INSIGHT

↓

ACTION

Example:

Data:

10 blocked stories

↓

Insight:

Development dependency problem

↓

Action:

Escalate dependency resolution

**3. Dashboard Types in Enterprise Projects**

For AI Healthcare Platform, we create:

1.  BA Command Center Dashboard

2.  Product Owner Dashboard

3.  Scrum Master Dashboard

4.  Executive Dashboard

5.  Healthcare Compliance Dashboard

**DASHBOARD 1**

**BA Command Center Dashboard**

**Audience**

Business Analyst

**Purpose**

Manage requirements and delivery quality.

**Gadget 1: Requirement Status Overview**

Shows:

Business Analysis

██████ 12

Ready for Development

████ 8

Development

███████ 15

UAT

███ 5

**BA Questions Answered:**

-   How many requirements need attention?

-   Are stories ready?

-   Where are bottlenecks?

**Gadget 2: BA Requirement Queue**

Filter:

project = AHP

AND status = \"Business Analysis\"

ORDER BY priority DESC

Shows:

High-priority requirements waiting for analysis.

**Gadget 3: Blocked Issues**

Filter:

status = Blocked

BA Action:

Identify blockers.

Examples:

-   Missing stakeholder approval

-   Missing data

-   Technical dependency

**Gadget 4: Requirement Change Tracker**

Filter:

issuetype = Story

AND updated \>= -7d

Purpose:

Track requirement changes.

**Gadget 5: Defect Trend**

Shows:

Are requirement defects increasing?

**BA Dashboard Layout**

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Requirement Status \| Blocked Issues

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Requirement Changes \| Defect Trend

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Sprint Progress

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**DASHBOARD 2**

**Product Owner Dashboard**

**Audience**

Product Owner

**Purpose**

Track product value delivery.

**Gadget 1: Epic Progress**

Example:

AI Patient Intelligence:

Completed:

70%

Remaining:

30%

**Gadget 2: Release Progress**

Release:

AI Healthcare MVP 1.0

Shows:

-   Completed features

-   Remaining scope

-   Risks

**Gadget 3: Backlog Priority View**

Shows:

Highest priority items:

1.  Patient Risk Prediction

2.  AI Assistant

3.  Analytics Dashboard

**Gadget 4: Velocity Trend**

Example:

  -----------------------------------------------------------------------
  **Sprint**                         **Velocity**
  ---------------------------------- ------------------------------------
  Sprint 1                           23

  Sprint 2                           28

  Sprint 3                           31
  -----------------------------------------------------------------------

**Product Owner Question:**

\"Will we deliver MVP on time?\"

**DASHBOARD 3**

**Scrum Master Dashboard**

**Purpose**

Monitor Agile health.

**Gadget 1: Sprint Burndown**

Tracks:

Remaining work.

**Gadget 2: Cumulative Flow Diagram**

Identifies:

Bottlenecks.

Example:

Problem:

QA column increasing.

Meaning:

Testing bottleneck.

**Gadget 3: Blocker Report**

Tracks:

Impediments.

**Gadget 4: Cycle Time Report**

Measures:

Delivery speed.

**DASHBOARD 4**

**Executive Dashboard**

**Audience**

-   CIO

-   Hospital Leadership

-   Sponsors

**Purpose**

Business-level visibility.

**Gadget 1: Release Health**

Example:

AI Healthcare Platform:

Status:

🟢 On Track

**Gadget 2: Business Value Progress**

Tracks:

Major capabilities delivered.

Example:

  -----------------------------------------------------------------------
  **Capability**                                **Status**
  --------------------------------------------- -------------------------
  AI Risk Prediction                            Completed

  Analytics Dashboard                           In Progress

  Automation                                    Planned
  -----------------------------------------------------------------------

**Gadget 3: Risk Overview**

Shows:

High Risks:

-   AI model performance

-   Data privacy compliance

-   Integration delays

**Gadget 4: KPI Dashboard**

Business metrics:

-   Patient engagement

-   Operational efficiency

-   Processing time reduction

**DASHBOARD 5**

**Healthcare Compliance Dashboard**

**Purpose**

Healthcare governance tracking.

**Metrics:**

**1. Security Issues**

Example:

Open vulnerabilities.

**2. Audit Requirements**

Track:

-   Audit logs

-   Compliance tasks

**3. Data Privacy Requirements**

Example:

Patient data protection stories.

**4. Approval Tracking**

Tracks:

Clinical approvals.

**4. Enterprise Dashboard Permissions**

Not everyone sees everything.

Example:

  -----------------------------------------------------------------------
  **Dashboard**                        **Users**
  ------------------------------------ ----------------------------------
  BA Dashboard                         BA Team

  Product Dashboard                    PO + BA

  Sprint Dashboard                     Scrum Team

  Executive Dashboard                  Leadership

  Compliance Dashboard                 Security + Compliance
  -----------------------------------------------------------------------

**5. Dashboard Maintenance**

A BA should review:

Monthly:

✅ Remove useless gadgets

✅ Update filters

✅ Add new KPIs

✅ Remove outdated reports

**6. AI Healthcare Platform Final Dashboard Architecture**

EXECUTIVE DASHBOARD

\|

PRODUCT OWNER DASHBOARD

\|

BA COMMAND CENTER

\|

SCRUM TEAM DASHBOARD

\|

COMPLIANCE DASHBOARD

**7. Complete Jira Simulation Status**

We have now built:

AI Healthcare Platform Jira System

✅ Project Setup

✅ Issue Hierarchy

✅ Epics

✅ Features

✅ User Stories

✅ Workflow

✅ Sprint Management

✅ Reports

✅ Automation

✅ JQL

✅ Enterprise Dashboards

**Final Skill Achieved**

You can now explain in an interview:

\"I have experience designing Jira project structures, managing
enterprise backlogs, creating workflows, supporting sprint execution,
building dashboards, using JQL filters, and implementing automation
rules for Agile delivery.\"
