---
title: "Agile Masterclass_M16C (1-36)"
---

# Agile Masterclass_M16C (1-36)

**Lesson 8 -- Complete BA Portfolio Project #2**

**AI Healthcare Appointment Assistant**

**End-to-End Business Analysis Case Study**

**Learning Objective**

After this lesson, you will understand:

✅ How to create a complete BA case study from scratch\
✅ How to analyze a healthcare product idea\
✅ How to identify business problems\
✅ How to define stakeholders and objectives\
✅ How to create BA artifacts for a product project\
✅ How to present a healthcare AI product in interviews

**PROJECT OVERVIEW**

**Project Name**

**AI Healthcare Appointment Assistant Platform**

**Industry**

Healthcare / Digital Health

**Methodology**

Agile Scrum

**BA Role**

Business Analyst

**1. Business Context**

Healthcare organizations face increasing challenges:

-   Patients struggle to find the right doctor

-   Appointment booking requires phone calls

-   Reception teams handle repetitive queries

-   Doctors face scheduling inefficiencies

-   Patients forget appointments

Hospitals want a digital solution to improve patient experience and
operational efficiency.

**2. Business Problem Statement**

**Current Situation (AS-IS)**

Today many hospitals follow:

Patient

↓

Calls Hospital

↓

Receptionist Collects Details

↓

Checks Doctor Availability

↓

Suggests Appointment Slot

↓

Patient Confirms

↓

Manual Reminder

**Problems Identified**

  -----------------------------------------------------------------------
  **Problem**                              **Business Impact**
  ---------------------------------------- ------------------------------
  Phone-based booking                      Long waiting time

  Manual availability checking             Reception workload

  No intelligent recommendations           Poor patient experience

  Missed appointments                      Revenue loss

  Limited analytics                        Poor decision making
  -----------------------------------------------------------------------

**3. Business Objective**

The goal is:

Build an AI-powered appointment assistant that helps patients find
doctors, schedule appointments, and receive personalized support.

**Business Goals**

**Goal 1**

Improve patient experience

Metric:

Reduce appointment booking effort

**Goal 2**

Reduce administrative workload

Metric:

Reduce manual scheduling activities

**Goal 3**

Improve appointment utilization

Metric:

Reduce missed appointments

**4. Stakeholder Analysis**

A BA starts by identifying stakeholders.

  ------------------------------------------------------------------------
  **Stakeholder**           **Role**             **Interest**
  ------------------------- -------------------- -------------------------
  Hospital Management       Sponsor              Business growth

  Patients                  Primary Users        Easy booking

  Doctors                   Service Providers    Efficient schedules

  Reception Team            Operational Users    Reduced workload

  IT Team                   Implementation       System delivery

  Compliance Team           Risk Management      Healthcare regulations
  ------------------------------------------------------------------------

**5. User Personas**

**Persona 1: Patient**

Name:

Rahul

Role:

Patient

Goals:

Find doctor quickly

Pain Points:

• Long waiting times

• Difficulty finding specialists

• Forgetting appointments

Needs:

Simple booking experience

**Persona 2: Doctor**

Name:

Dr. Sharma

Role:

Physician

Goals:

Manage appointments efficiently

Pain Points:

• Schedule conflicts

• Unplanned visits

Needs:

Better calendar management

**6. Current Process Analysis (AS-IS)**

**Existing Appointment Process**

Patient Requests Appointment

↓

Receptionist Collects Information

↓

Check Doctor Schedule

↓

Doctor Available?

◇

Yes No

↓ ↓

Confirm Suggest Alternative

↓

Send Confirmation

↓

Appointment Completed

**7. Gap Analysis**

Now BA compares current vs desired state.

  ------------------------------------------------------------------------
  **Area**      **Current State** **Future State**   **Gap**
  ------------- ----------------- ------------------ ---------------------
  Doctor Search Manual enquiry    AI recommendation  No intelligent search

  Booking       Phone based       Digital booking    No self-service

  Reminder      Manual calls      Automated alerts   No notification
                                                     system

  Support       Human dependent   AI assistant       Limited availability
  ------------------------------------------------------------------------

**8. Proposed Solution (TO-BE)**

AI Appointment Assistant:

Patient Opens App

↓

AI Assistant Understands Requirement

↓

Suggests Doctors

↓

Shows Available Slots

↓

Patient Books Appointment

↓

Confirmation Sent

↓

Reminder Generated

**9. Major Features**

**Feature 1**

AI Doctor Recommendation

Description:

Suggest doctors based on:

-   Medical need

-   Specialty

-   Availability

-   Location

**Feature 2**

Smart Appointment Booking

Description:

Patients can select available time slots.

**Feature 3**

AI Chat Assistant

Description:

Answer common healthcare appointment queries.

**Feature 4**

Appointment Reminder

Description:

Send reminders through notifications.

**10. Epic Definition**

**Epic:**

AI-Powered Appointment Management

Business Goal:

Improve patient scheduling experience.

**Features:**

Epic

↓

Doctor Discovery

↓

Appointment Booking

↓

AI Assistant

↓

Reminder Management

**11. Sample User Stories**

**US-001: Search Doctor**

As a patient,

I want to search doctors based on my requirement,

So that I can find the right healthcare provider.

Acceptance Criteria:

Given patient enters a specialty

When search is performed

Then matching doctors should be displayed.

**US-002: Book Appointment**

As a patient,

I want to select an available appointment slot,

So that I can schedule a consultation.

Acceptance Criteria:

Given available slots exist

When patient selects a slot

Then appointment confirmation should be generated.

**12. BA Deliverables Created**

Your portfolio should include:

AI Healthcare Appointment Assistant

\|

├── Business Problem

├── Stakeholder Analysis

├── Personas

├── AS-IS BPMN

├── Gap Analysis

├── TO-BE BPMN

├── BRD

├── FRD

├── User Stories

├── Acceptance Criteria

├── User Journey

├── Wireframes

├── UAT

└── Closure Report

**13. Interview Explanation**

Question:

\"Explain your healthcare appointment project.\"

Answer structure:

\"I worked on an AI Healthcare Appointment Assistant case study where I
analyzed the existing appointment workflow, identified pain points,
mapped stakeholders, designed future-state processes, created functional
requirements, converted them into Agile user stories, and defined UAT
scenarios to validate the solution.\"

**14. Portfolio Value**

This project demonstrates:

  -----------------------------------------------------------------------
  **Skill**                          **Evidence**
  ---------------------------------- ------------------------------------
  Business Analysis                  BRD, FRD

  Process Modeling                   BPMN

  Product Thinking                   Features, Personas

  UX Understanding                   Journey Maps

  Agile                              User Stories

  Testing                            UAT
  -----------------------------------------------------------------------

**Practical Assignment**

Create the following for this project:

**Part 1:**

Write 5 Functional Requirements:

Format:

FR ID:

Requirement:

User:

Priority:

Acceptance Criteria:

**Part 2:**

Create 5 User Stories:

Format:

As a\...

I want\...

So that\...

**Lesson 9 -- BA Portfolio Project #2**

**Creating BRD & FRD for AI Healthcare Appointment Assistant**

**Building Enterprise-Level Requirement Documents**

**Learning Objective**

After this lesson, you will understand:

✅ How to create a professional BRD from a healthcare product idea\
✅ How to separate business requirements from functional requirements\
✅ How to write requirements that developers and stakeholders
understand\
✅ How to create portfolio-quality BA documents\
✅ How BRD connects to FRD, User Stories, and UAT

**1. Requirement Document Flow in Real Projects**

A professional BA follows:

Business Problem

↓

BRD

(Business Need)

↓

FRD

(System Capability)

↓

User Stories

(Development Work)

↓

Acceptance Criteria

(Testing)

↓

UAT

(Business Validation)

**PART 1 -- BUSINESS REQUIREMENTS DOCUMENT (BRD)**

**2. BRD Overview**

**Project Name**

AI Healthcare Appointment Assistant Platform

**Document Purpose**

The purpose of this document is to define the business objectives,
scope, stakeholders, and high-level requirements for implementing an
AI-powered healthcare appointment management solution.

**3. Executive Summary**

**Current Situation**

Healthcare organizations experience challenges in appointment management
due to:

-   Manual scheduling processes

-   High dependency on reception teams

-   Difficulty finding appropriate specialists

-   Missed appointments

-   Limited patient engagement

**Proposed Solution**

An AI-powered appointment assistant that enables patients to:

-   Search doctors

-   Receive intelligent recommendations

-   Book appointments

-   Get reminders

-   Manage consultations

**4. Business Problem**

**Problem Statement**

Patients often face difficulty accessing healthcare services efficiently
because appointment scheduling depends heavily on manual processes,
resulting in delays, poor experience, and increased administrative
workload.

**5. Business Objectives**

  -----------------------------------------------------------------------
  **Objective**                      **Expected Outcome**
  ---------------------------------- ------------------------------------
  Enable self-service booking        Improve patient convenience

  Automate doctor discovery          Faster doctor selection

  Reduce manual scheduling           Lower administrative effort

  Improve reminders                  Reduce missed appointments
  -----------------------------------------------------------------------

**6. Project Scope**

**In Scope**

✅ Patient registration

✅ Doctor search

✅ AI recommendations

✅ Appointment booking

✅ Appointment reminders

✅ Appointment dashboard

**Out of Scope**

❌ Medical diagnosis

❌ Treatment recommendations

❌ Prescription generation

❌ Insurance claim processing

**7. Stakeholders**

  -----------------------------------------------------------------------
  **Stakeholder**                    **Responsibility**
  ---------------------------------- ------------------------------------
  Hospital Management                Business approval

  Patients                           Primary users

  Doctors                            Appointment providers

  Reception Team                     Operational users

  IT Team                            System implementation

  Compliance Team                    Healthcare governance
  -----------------------------------------------------------------------

**8. Business Requirements**

**BR-001: Digital Appointment Booking**

Requirement:

The organization needs a digital platform that allows patients to
schedule appointments without manual intervention.

**BR-002: Intelligent Doctor Discovery**

Requirement:

The system should help patients identify suitable doctors based on their
needs.

**BR-003: Automated Communication**

Requirement:

The system should provide automated appointment confirmations and
reminders.

**BR-004: Operational Visibility**

Requirement:

Hospital management should have visibility into appointment activities.

**9. Success Criteria**

  -----------------------------------------------------------------------
  **Metric**                      **Expected Improvement**
  ------------------------------- ---------------------------------------
  Booking process                 Faster patient scheduling

  Reception workload              Reduced manual activities

  Patient engagement              Improved experience

  Appointment attendance          Reduced missed appointments
  -----------------------------------------------------------------------

**PART 2 -- FUNCTIONAL REQUIREMENTS DOCUMENT (FRD)**

**10. FRD Purpose**

The FRD describes:

What the system must do to satisfy business requirements.

**11. Functional Requirement Structure**

Requirement ID

Requirement Name

Description

User

Priority

Precondition

Main Flow

Acceptance Criteria

Dependencies

**12. Functional Requirements**

**FR-001: Patient Registration**

**Description**

The system shall allow patients to create an account.

**User**

Patient

**Priority**

Must Have

**Main Flow**

Patient enters details

↓

System validates information

↓

Account created

↓

Confirmation sent

**Acceptance Criteria**

Given:

Patient provides valid details

When:

Registration is submitted

Then:

Patient account should be created.

**FR-002: Doctor Search**

**Description**

The system shall allow patients to search doctors based on
specialization.

**User**

Patient

**Priority**

Must Have

**Acceptance Criteria**

Given:

Patient enters specialty

When:

Search is executed

Then:

Relevant doctors should be displayed.

**FR-003: AI Doctor Recommendation**

**Description**

The system shall recommend doctors using patient requirements and
available data.

**User**

Patient

**Priority**

Should Have

Acceptance Criteria:

Given:

Patient provides healthcare requirement

When:

AI recommendation runs

Then:

Recommended doctors should be displayed.

**FR-004: Appointment Booking**

**Description**

The system shall allow patients to select available appointment slots.

**User**

Patient

**Priority**

Must Have

Acceptance Criteria:

Given:

Doctor has available slots

When:

Patient selects slot

Then:

Appointment should be confirmed.

**FR-005: Appointment Reminder**

**Description**

The system shall send automated reminders before appointments.

**User**

Patient

**Priority**

Should Have

Acceptance Criteria:

Given:

Appointment exists

When:

Reminder time is reached

Then:

Notification should be sent.

**13. Requirement Traceability Example**

Connecting business → system → testing:

  ------------------------------------------------------------------------
  **Business Requirement**    **Functional Requirement**        **UAT**
  --------------------------- --------------------------------- ----------
  BR-001 Booking              FR-004 Appointment Booking        UAT-001

  BR-002 Doctor Search        FR-002 Search Doctor              UAT-002

  BR-003 Communication        FR-005 Reminder                   UAT-003
  ------------------------------------------------------------------------

**14. Portfolio Artifact Created**

Your project now contains:

AI Healthcare Appointment Assistant

\|

├── BRD

│ ├── Problem

│ ├── Objectives

│ ├── Scope

│ └── Business Requirements

└── FRD

├── Functional Requirements

├── Acceptance Criteria

└── Traceability

**Interview Question**

**Q:**

\"What is the difference between BRD and FRD?\"

Strong Answer:

\"BRD explains why the project is needed and what business outcomes are
expected. FRD explains what the system should do to achieve those
business objectives.\"

**Practical Assignment**

Create:

**5 Additional Functional Requirements**

For:

**AI Healthcare Appointment Assistant**

Possible areas:

-   Patient profile

-   Doctor calendar

-   Cancellation

-   Feedback

-   Admin dashboard

Use:

FR ID → Requirement → User → Priority → Acceptance Criteria

**Lesson 10 -- Designing BPMN, User Journey & Wireframes for AI
Healthcare Appointment Assistant**

**Turning Requirements Into Product Design**

**Learning Objective**

After this lesson, you will understand:

✅ How BAs convert requirements into process models\
✅ How to create AS-IS and TO-BE BPMN for a healthcare product\
✅ Difference between User Journey and User Flow\
✅ How wireframes help BA--UX--Development collaboration\
✅ How to create portfolio-quality product artifacts

**1. Requirement → Process → Design Flow**

A BA connects business needs to product design:

Business Requirement

↓

Process Analysis

↓

BPMN Model

↓

User Journey

↓

User Flow

↓

Wireframe

↓

Development

**PART 1 -- BPMN PROCESS MODELING**

**2. Why BPMN is Important for BA**

BPMN answers:

\"How does work happen today and how should it happen in the future?\"

It helps identify:

-   Manual steps

-   Bottlenecks

-   Automation opportunities

-   Roles involved

**3. AS-IS BPMN**

**Process:**

Traditional Appointment Booking

Participants:

-   Patient

-   Receptionist

-   Doctor

**AS-IS Process**

PATIENT

Start

↓

Call Hospital

↓

Provide Requirement

↓

RECEPTIONIST

Collect Patient Details

↓

Check Doctor Availability

↓

Doctor Available?

◇

Yes No

↓ ↓

Book Slot Suggest Other Doctor

↓

Confirm Appointment

↓

PATIENT

Receive Confirmation

End

**4. AS-IS Pain Point Analysis**

  ------------------------------------------------------------------------
  **Step**                **Problem**                 **Impact**
  ----------------------- --------------------------- --------------------
  Phone call              Limited availability        Patient waiting

  Manual search           Time consuming              Staff workload

  Manual reminders        Missed appointments         Revenue impact
  ------------------------------------------------------------------------

**5. TO-BE BPMN**

**AI Appointment Assistant Process**

Participants:

-   Patient

-   AI Assistant

-   Hospital System

-   Doctor

PATIENT

Start

↓

Open Healthcare App

↓

Enter Healthcare Need

↓

AI ASSISTANT

Analyze Requirement

↓

Recommend Doctors

↓

PATIENT

Select Doctor

↓

SYSTEM

Check Availability

↓

Available Slot?

◇

Yes No

↓ ↓

Book Slot Suggest Alternative

↓

SYSTEM

Send Confirmation

↓

Generate Reminder

↓

End

**6. BPMN Improvement Analysis**

Before:

Manual:

Patient → Receptionist → Doctor

After:

Digital:

Patient → AI Assistant → System

**Business Benefits:**

  -----------------------------------------------------------------------
  **Improvement**               **Benefit**
  ----------------------------- -----------------------------------------
  Self-service booking          Better patient experience

  AI recommendation             Faster doctor selection

  Automation                    Reduced staff workload

  Digital reminders             Fewer missed appointments
  -----------------------------------------------------------------------

**PART 2 -- USER JOURNEY MAP**

**7. What is a User Journey?**

User Journey describes:

The complete experience of a user while achieving a goal.

It focuses on:

-   User emotions

-   Pain points

-   Opportunities

**User Journey:**

Patient Booking Appointment

  --------------------------------------------------------------------------------
  **Stage**      **User        **Emotion**   **Pain Point**      **Opportunity**
                 Action**                                        
  -------------- ------------- ------------- ------------------- -----------------
  Need           Search        Concerned     Don\'t know right   AI guidance
  Healthcare     solution                    doctor              

  Doctor Search  Explore       Confused      Too many options    Recommendation
                 doctors                                         

  Booking        Select slot   Hopeful       Availability        Real-time slots
                                             uncertainty         

  Confirmation   Receive       Satisfied     Fear of forgetting  Reminder
                 details                                         

  Visit          Consult       Satisfied     Waiting time        Digital check-in
                 doctor                                          
  --------------------------------------------------------------------------------

**8. User Journey Insights**

BA identifies:

**Problem:**

Patients need confidence before booking.

**Opportunity:**

AI should guide patients during doctor discovery.

**PART 3 -- USER FLOW**

**9. User Flow vs User Journey**

Important interview concept.

  -----------------------------------------------------------------------
  **User Journey**                     **User Flow**
  ------------------------------------ ----------------------------------
  Experience focused                   Action focused

  Shows emotions                       Shows screens/actions

  Why user does something              How user completes task
  -----------------------------------------------------------------------

**Example:**

**User Journey**

\"Patient wants quick healthcare access.\"

**User Flow**

Login

↓

Home Screen

↓

Search Doctor

↓

View Recommendations

↓

Select Doctor

↓

Choose Slot

↓

Confirm Booking

**PART 4 -- WIREFRAMES**

**10. Why BA Creates Wireframes?**

A BA does not replace UX designers.

But wireframes help:

-   Explain requirements

-   Validate ideas

-   Remove ambiguity

-   Align stakeholders

**Screen 1:**

**Patient Home Dashboard**

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Hello Rahul

What do you need help with?

\[ Search Doctor \]

\[ Book Appointment \]

Upcoming Appointment

Dr. Sharma

Tomorrow 10:00 AM

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**Screen 2:**

**AI Doctor Recommendation**

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Tell me your requirement

\"I have chest discomfort\"

AI Suggestions:

1\. Cardiologist

Dr. Sharma

Available Today

2\. Dr. Patel

Available Tomorrow

\[Book Appointment\]

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**Screen 3:**

**Appointment Booking**

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Doctor:

Dr. Sharma

Available Slots:

10:00 AM

11:30 AM

2:00 PM

\[Confirm Booking\]

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**11. Wireframe Requirement Mapping**

  -----------------------------------------------------------------------
  **Screen**                              **Requirement**
  --------------------------------------- -------------------------------
  Home Dashboard                          Patient Access

  Doctor Search                           FR-002

  Recommendation                          FR-003

  Booking                                 FR-004

  Reminder                                FR-005
  -----------------------------------------------------------------------

**12. Portfolio Artifact Created**

Your project now includes:

AI Healthcare Appointment Assistant

\|

├── BRD

├── FRD

├── AS-IS BPMN

├── TO-BE BPMN

├── User Journey Map

├── User Flow

└── Wireframes

**Interview Question**

**Q:**

\"How do BPMN and wireframes help a BA?\"

Strong Answer:

\"BPMN helps me understand and improve business processes, while
wireframes help translate requirements into a visual solution and align
stakeholders, UX designers, and development teams.\"

**Practical Assignment**

Create:

**1. AS-IS BPMN**

For:

**Online Pharmacy Order Process**

Include:

-   Customer

-   Pharmacist

-   Delivery Team

**2. Three Wireframes**

For:

AI Healthcare Appointment Assistant:

-   Login Screen

-   Doctor Search Screen

-   Booking Confirmation Screen

**Lesson 11 -- Agile Delivery for AI Healthcare Appointment Assistant**

**Creating Epics, Product Backlog, Sprint Plan & Jira Structure**

**Learning Objective**

After this lesson, you will understand:

✅ How a BA supports Agile delivery after requirements are created\
✅ How to convert BRD/FRD into Agile backlog items\
✅ How to create Epics, Features, User Stories, and Tasks\
✅ How to plan sprints for a healthcare AI product\
✅ How a BA works with Product Owner, Scrum Master, and Development Team

**1. From Requirement to Agile Backlog**

In traditional projects:

BRD

↓

FRD

↓

Development

↓

Testing

In Agile:

Business Goal

↓

Epic

↓

Feature

↓

User Story

↓

Acceptance Criteria

↓

Sprint

↓

Increment

**2. BA Role in Agile Delivery**

A BA helps:

**Before Sprint**

-   Refine requirements

-   Clarify user stories

-   Define acceptance criteria

-   Identify dependencies

**During Sprint**

-   Answer developer questions

-   Clarify business rules

-   Support testing

**After Sprint**

-   Support demo

-   Gather feedback

-   Update backlog

**3. Product Backlog Structure**

For AI Healthcare Appointment Assistant:

Product Vision

↓

Epics

↓

Features

↓

User Stories

↓

Tasks

**4. Product Vision**

**Vision Statement**

\"Enable patients to access healthcare services faster through an
AI-powered appointment assistant that simplifies doctor discovery,
booking, and communication.\"

**5. Epic Creation**

An Epic represents a large business capability.

**Epic 1:**

**Patient Appointment Management**

Business Goal:

Enable patients to manage healthcare appointments digitally.

Features:

Epic:

Patient Appointment Management

\|

├── Patient Registration

├── Doctor Search

├── Appointment Booking

├── Appointment Cancellation

└── Appointment History

**Epic 2:**

**AI Healthcare Assistant**

Features:

AI Healthcare Assistant

\|

├── Natural Language Search

├── Doctor Recommendation

├── FAQ Support

└── Appointment Guidance

**Epic 3:**

**Hospital Administration**

Features:

Hospital Administration

\|

├── Doctor Schedule Management

├── Appointment Dashboard

├── Reports

└── User Management

**6. Feature Breakdown**

Example:

**Feature:**

Doctor Search

Requirement:

Patients should find doctors easily.

User Stories:

US-001 Search doctor by specialty

US-002 Filter doctor by location

US-003 View doctor profile

**7. User Story Creation**

**User Story Format**

As a \<user\>

I want \<capability\>

So that \<business value\>

**User Story 1**

**Doctor Search**

As a patient,

I want to search doctors by specialty,

So that I can find the right healthcare provider quickly.

Acceptance Criteria:

Given:

Patient is on doctor search page

When:

Patient enters \"Cardiologist\"

Then:

System displays matching doctors.

**User Story 2**

**AI Recommendation**

As a patient,

I want AI to recommend suitable doctors,

So that I do not need to manually search.

Acceptance Criteria:

Given:

Patient describes healthcare need

When:

AI analyzes requirement

Then:

Relevant doctors should be suggested.

**User Story 3**

**Appointment Booking**

As a patient,

I want to book an available time slot,

So that I can schedule my consultation.

Acceptance Criteria:

Given:

Doctor has available slots

When:

Patient confirms appointment

Then:

Booking confirmation should be generated.

**8. Story Prioritization**

BA supports Product Owner using prioritization techniques.

**MoSCoW Method**

  -----------------------------------------------------------------------
  **Priority**            **Feature**
  ----------------------- -----------------------------------------------
  Must Have               Doctor Search

  Must Have               Appointment Booking

  Should Have             AI Recommendation

  Could Have              Voice Assistant

  Won\'t Have             Online Payment (Phase 2)
  -----------------------------------------------------------------------

**9. Sprint Planning**

Assumption:

2-week sprints

**Sprint 1:**

**Goal:**

Create basic appointment capability

Stories:

  -----------------------------------------------------------------------
  **Story**                                          **Priority**
  -------------------------------------------------- --------------------
  Patient Registration                               Must

  Doctor Search                                      Must

  Doctor Profile                                     Must
  -----------------------------------------------------------------------

**Sprint 2:**

**Goal:**

Enable booking workflow

Stories:

  -----------------------------------------------------------------------
  **Story**                                         **Priority**
  ------------------------------------------------- ---------------------
  View Availability                                 Must

  Book Appointment                                  Must

  Confirmation                                      Must
  -----------------------------------------------------------------------

**Sprint 3:**

**Goal:**

Add AI capabilities

Stories:

  -----------------------------------------------------------------------
  **Story**                                             **Priority**
  ----------------------------------------------------- -----------------
  AI Chat Assistant                                     Should

  Doctor Recommendation                                 Should

  Smart Suggestions                                     Could
  -----------------------------------------------------------------------

**10. Jira Structure Example**

A BA working with Jira might create:

PROJECT:

AI Healthcare Assistant

EPICS:

EPIC-01 Appointment Management

EPIC-02 AI Assistant

EPIC-03 Administration

STORIES:

US-001 Search Doctor

US-002 Book Appointment

US-003 AI Recommendation

TASKS:

API Development

UI Development

Database Design

Testing

**11. Acceptance Criteria Quality Check**

Good acceptance criteria should be:

**Specific**

❌ System should work properly

✅ System should display available doctor slots

**Testable**

❌ User friendly

✅ User can complete booking within three steps

**Business-focused**

❌ Button should be blue

✅ Patient should receive confirmation after booking

**12. Sprint Backlog Example**

  ------------------------------------------------------------------------
  **ID**       **Story**               **Estimate**    **Status**
  ------------ ----------------------- --------------- -------------------
  US-001       Doctor Search           5 SP            To Do

  US-002       Doctor Profile          3 SP            To Do

  US-003       Booking                 8 SP            In Progress
  ------------------------------------------------------------------------

**13. BA Portfolio Artifact Created**

Your project now includes Agile delivery evidence:

AI Healthcare Appointment Assistant

\|

├── Product Vision

├── Epics

├── Features

├── User Stories

├── Acceptance Criteria

├── Sprint Backlog

└── Jira Structure

**Interview Question**

**Q:**

\"How does a BA contribute in Agile Scrum?\"

Strong Answer:

\"A BA helps translate business needs into user stories, defines
acceptance criteria, supports backlog refinement, clarifies requirements
during development, and ensures the delivered increment meets business
expectations.\"

**Practical Assignment**

Create backlog for:

**AI Healthcare Appointment Assistant**

Create:

**3 Epics**

**5 Features**

**10 User Stories**

Format:

Epic:

Feature:

User Story:

Acceptance Criteria:

Priority:

**Lesson 12 -- UAT, Metrics & Business Outcome for AI Healthcare
Appointment Assistant**

**Completing the Full BA Case Study**

**Learning Objective**

After this lesson, you will understand:

✅ How a BA validates whether a product solves business problems\
✅ How to create UAT scenarios from requirements\
✅ How to define KPIs and success metrics\
✅ How to measure business value after implementation\
✅ How to complete a portfolio case study professionally

**1. Where We Are in the BA Lifecycle**

We have completed:

Business Problem

↓

Stakeholder Analysis

↓

AS-IS Process

↓

Gap Analysis

↓

TO-BE Process

↓

BRD

↓

FRD

↓

User Stories

↓

Sprint Delivery

↓

UAT

↓

Business Outcome

**2. Why UAT is Important**

Development team asks:

\"Does the system work technically?\"

Business users ask:

\"Can I use this solution to perform my work?\"

UAT answers:

\"Is this solution acceptable for business use?\"

**3. BA Role During UAT**

The BA:

-   Converts requirements into test scenarios

-   Coordinates business users

-   Clarifies expected behavior

-   Tracks defects

-   Confirms fixes

-   Supports sign-off

**4. UAT Preparation**

**UAT Participants**

  -----------------------------------------------------------------------
  **Role**                      **Responsibility**
  ----------------------------- -----------------------------------------
  Patient Representative        Validate booking experience

  Hospital Admin                Validate operations

  Doctor                        Validate schedule management

  BA                            Coordinate testing

  Product Owner                 Approve acceptance
  -----------------------------------------------------------------------

**5. UAT Test Scenario 1**

**Patient Searches Doctor**

**Requirement:**

FR-002 Doctor Search

**Test Case:**

  -----------------------------------------------------------------------
  **Field**                 **Details**
  ------------------------- ---------------------------------------------
  Test ID                   UAT-001

  Scenario                  Search Doctor

  User                      Patient

  Precondition              Patient logged in

  Input                     Specialty = Cardiologist
  -----------------------------------------------------------------------

**Steps:**

  ---------------------------------------------------------------------------
  **Step**   **Action**                  **Expected Result**
  ---------- --------------------------- ------------------------------------
  1          Open app                    Dashboard displayed

  2          Select Search Doctor        Search screen opens

  3          Enter specialty             Matching doctors displayed
  ---------------------------------------------------------------------------

**Result:**

Pass / Fail

**6. UAT Test Scenario 2**

**Book Appointment**

Requirement:

FR-004 Appointment Booking

Test:

  -----------------------------------------------------------------------
  **Field**             **Details**
  --------------------- -------------------------------------------------
  Test ID               UAT-002

  Scenario              Book Appointment

  User                  Patient

  Input                 Available doctor slot
  -----------------------------------------------------------------------

Steps:

  --------------------------------------------------------------------------
  **Step**   **Action**                 **Expected Result**
  ---------- -------------------------- ------------------------------------
  1          Select doctor              Doctor profile opens

  2          Select time slot           Slot selected

  3          Confirm                    Appointment created
  --------------------------------------------------------------------------

**7. UAT Test Scenario 3**

**Appointment Reminder**

Requirement:

FR-005 Reminder System

Expected:

Patient receives notification before appointment.

**8. Defect Management**

During UAT, issues are recorded.

Example:

**Defect:**

Reminder notification not received

Defect Log:

  -----------------------------------------------------------------------
  **Field**                    **Value**
  ---------------------------- ------------------------------------------
  ID                           DEF-001

  Description                  Reminder missing

  Severity                     Medium

  Priority                     High

  Status                       Fixed
  -----------------------------------------------------------------------

**9. Requirement Traceability**

A BA ensures:

Business Need → Requirement → Test

Example:

  -----------------------------------------------------------------------
  **Business Requirement**          **Functional Requirement**  **UAT**
  --------------------------------- --------------------------- ---------
  Improve booking experience        FR-004 Booking              UAT-002

  Help patients find doctors        FR-002 Search               UAT-001

  Reduce missed appointments        FR-005 Reminder             UAT-003
  -----------------------------------------------------------------------

**10. Business Metrics**

A professional BA defines success measurement.

**Before Implementation**

  -----------------------------------------------------------------------
  **Metric**                                 **Current State**
  ------------------------------------------ ----------------------------
  Appointment booking                        Phone/manual

  Average booking time                       10 minutes

  Missed appointments                        High

  Reception workload                         High
  -----------------------------------------------------------------------

**After Implementation**

Expected:

  -----------------------------------------------------------------------
  **Metric**                                        **Target**
  ------------------------------------------------- ---------------------
  Digital bookings                                  Increase

  Booking time                                      Reduce

  Missed appointments                               Decrease

  Patient satisfaction                              Improve
  -----------------------------------------------------------------------

**11. Product KPIs**

**Patient Experience KPIs**

**Appointment Completion Rate**

Measures:

How many booked appointments are completed.

**Patient Satisfaction Score**

Measures:

User experience.

**Operational KPIs**

**Booking Processing Time**

Measures:

Speed improvement.

**Reception Workload Reduction**

Measures:

Administrative efficiency.

**AI-Specific KPIs**

Important for AI products:

**Recommendation Accuracy**

Are suggested doctors relevant?

**AI Response Quality**

Are responses useful?

**Human Escalation Rate**

How often users need human support.

**12. Business Outcome Statement**

Avoid unrealistic claims.

Do not write:

❌ \"Reduced hospital cost by 80%\"

without real production data.

Write:

✅

\"The solution is expected to improve patient access, reduce manual
scheduling effort, and increase appointment management efficiency.\"

**13. Project Closure Summary**

Your case study final summary:

**AI Healthcare Appointment Assistant**

**Problem**

Manual appointment processes create delays.

**Analysis**

Analyzed current workflows and identified automation opportunities.

**Solution**

Designed AI-powered appointment management platform.

**BA Contribution**

-   Requirements gathering

-   BPMN modeling

-   BRD/FRD creation

-   Agile backlog creation

-   UAT support

**Outcome**

Improved patient experience and operational efficiency.

**14. Final Portfolio Structure**

Your completed project:

AI Healthcare Appointment Assistant

\|

├── 01_Discovery

│ ├── Problem Statement

│ └── Stakeholder Analysis

├── 02_Process Analysis

│ ├── AS-IS BPMN

│ ├── Gap Analysis

│ └── TO-BE BPMN

├── 03_Requirements

│ ├── BRD

│ ├── FRD

│ └── RTM

├── 04_Product Design

│ ├── Personas

│ ├── User Journey

│ └── Wireframes

├── 05_Agile Delivery

│ ├── Epics

│ ├── User Stories

│ └── Sprint Plan

├── 06_Testing

│ ├── UAT Plan

│ ├── Test Cases

│ └── Defect Log

└── 07_Closure

└── Business Outcome

**Interview Question**

**Q:**

\"How do you know a solution is successful?\"

Strong Answer:

\"I define success based on business objectives and measurable KPIs. For
example, for a healthcare appointment platform, I would track booking
efficiency, patient satisfaction, appointment completion rate, and
operational workload reduction.\"

**Practical Assignment**

Create:

**UAT Package for AI Healthcare Appointment Assistant**

Include:

1.  5 UAT test cases

2.  3 possible defects

3.  5 business KPIs

**🎯 Project #2 Completed**

You now have two complete BA portfolio case studies:

✅ AI Pharmacovigilance Platform\
✅ AI Healthcare Appointment Assistant
