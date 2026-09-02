---
title: "Agile Masterclass_M16F(1-36)"
---

# Agile Masterclass_M16F(1-36)

**Hospital Management System (HMS)**

**Lesson 1 -- Project Introduction, Business Problem & Industry
Context**

**Enterprise Healthcare Operations Case Study**

**Learning Objective**

After this lesson, you will understand:

✅ What a Hospital Management System is\
✅ Why hospitals need digital transformation\
✅ How a BA approaches a hospital software project\
✅ Business problems behind HMS implementation\
✅ Key stakeholders and business objectives

**1. Project Introduction**

**Project Name:**

**Hospital Management System (HMS)**

**Industry:**

Healthcare / Hospital Operations

**Project Type:**

Enterprise Healthcare Management Platform

**Business Scenario**

A multi-specialty hospital group operates:

-   3 hospitals

-   500+ beds

-   200+ doctors

-   1000+ healthcare staff

-   Thousands of daily patients

Current operations are managed through:

-   Paper records

-   Excel sheets

-   Multiple disconnected systems

-   Manual approvals

The hospital wants to implement a centralized HMS platform.

**2. What is a Hospital Management System?**

A Hospital Management System is a software platform that manages:

Patient Journey

↓

Registration

↓

Appointment

↓

Consultation

↓

Diagnosis

↓

Treatment

↓

Billing

↓

Discharge

↓

Follow-up

It connects:

**Clinical Operations**

Doctors, nurses, labs

-   

**Administrative Operations**

Reception, billing, insurance

-   

**Management Operations**

Hospital leadership, analytics

**3. Why Hospitals Need HMS?**

**Problem 1: Patient Data Fragmentation**

Current Situation:

Patient visits hospital.

Reception has data.

Doctor has separate notes.

Lab has separate reports.

Billing has separate records.

Problem:

No single patient view.

Business Impact:

❌ Slow treatment decisions

❌ Duplicate data entry

❌ Poor patient experience

**Solution:**

Centralized Electronic Patient Record (EPR)

**4. Problem 2: Appointment Management Issues**

Current Process:

Patient calls reception.

Reception checks doctor availability manually.

Appointment recorded in diary.

Problems:

❌ Long waiting time

❌ Double booking

❌ Poor doctor utilization

HMS Solution:

Online appointment scheduling:

Patient

↓

Select Doctor

↓

Check Availability

↓

Book Slot

↓

Confirmation

**5. Problem 3: Manual Billing Process**

Current:

Doctor consultation completed.

↓

Billing staff manually creates invoice.

↓

Insurance team verifies documents.

Problems:

❌ Billing errors

❌ Claim delays

❌ Revenue leakage

HMS Solution:

Automated billing workflow:

Treatment Data

↓

Billing Engine

↓

Insurance Verification

↓

Invoice Generation

↓

Payment

**6. Problem 4: Lack of Hospital Visibility**

Management cannot easily answer:

-   How many patients today?

-   Which department is overloaded?

-   Revenue status?

-   Bed availability?

-   Doctor performance?

HMS Solution:

Management Dashboard:

Example:

Today\'s Patients:

850

Available Beds:

42

Revenue:

₹25 Lakhs

Emergency Cases:

35

**7. Business Problem Statement (BA Artifact)**

A BA documents the problem clearly.

**Business Problem:**

The hospital currently operates through fragmented manual processes
resulting in inefficient patient management, delayed information access,
billing errors, and poor operational visibility. A centralized Hospital
Management System is required to improve healthcare delivery efficiency,
data accuracy, and patient experience.

**8. Project Objectives**

**Primary Objectives:**

**Objective 1**

Create a centralized patient information system.

**Objective 2**

Digitize hospital workflows.

**Objective 3**

Improve operational efficiency.

**Objective 4**

Reduce manual errors.

**Objective 5**

Provide real-time analytics for decision-making.

**9. Scope Definition**

A BA must define scope early.

**In Scope**

**Patient Management**

✅ Registration

✅ Patient profile

✅ Medical history

**Appointment Management**

✅ Doctor scheduling

✅ Booking

✅ Notifications

**Clinical Management**

✅ Consultation notes

✅ Diagnosis

✅ Prescription

**Hospital Operations**

✅ Admission

✅ Bed management

✅ Discharge

**Financial Management**

✅ Billing

✅ Insurance claims

**Reporting**

✅ Dashboards

✅ Analytics

**Out of Scope (Initial Release)**

❌ Robotic surgery integration

❌ Advanced AI diagnosis

❌ Medical device control

❌ National healthcare exchange integration

**10. BA Perspective: Key Questions**

Before designing the system, a BA asks:

**Process Questions**

-   How does patient registration happen today?

-   Who approves admissions?

-   How are bills generated?

**User Questions**

-   Who uses the system?

-   What information does each user need?

**Business Questions**

-   What problems are most costly?

-   What outcomes define success?

**11. Initial Stakeholder List**

  -----------------------------------------------------------------------
  **Stakeholder**                      **Role**
  ------------------------------------ ----------------------------------
  Hospital CEO                         Business Sponsor

  Hospital Administrator               Operations Owner

  Doctors                              Clinical Users

  Nurses                               Care Providers

  Reception Staff                      Patient Management

  Billing Team                         Financial Operations

  Insurance Team                       Claims Processing

  IT Team                              System Management

  Patients                             End Users
  -----------------------------------------------------------------------

**12. High-Level User Journey**

Patient

↓

Registration

↓

Appointment

↓

Doctor Consultation

↓

Lab/Pharmacy

↓

Billing

↓

Discharge

↓

Follow-up

**13. BA Deliverables Started**

Project #5 now contains:

Hospital Management System

Discovery Phase

✓ Project Vision

✓ Business Problem

✓ Objectives

✓ Scope

✓ Stakeholders

✓ High-Level User Journey

**Interview Question**

**\"Tell me about a healthcare software project you worked on.\"**

Strong Answer:

\"I worked on a Hospital Management System designed to digitize patient
registration, appointments, clinical workflows, billing, and analytics.
I analyzed existing hospital processes, identified operational gaps,
documented requirements, created workflows and user stories, and
supported Agile delivery.\"

**Practical Assignment**

Create a list of:

**10 Hospital Management System Stakeholders**

For each mention:

-   Stakeholder Name

-   Role

-   Interest in HMS

**Lesson 2 -- Stakeholder Analysis, User Personas & AS-IS Process
Mapping (BPMN)**

**Understanding the Current Hospital Workflow Before Building the
Solution**

**Learning Objective**

After this lesson, you will understand:

✅ How to identify HMS stakeholders\
✅ How different hospital users interact with the system\
✅ How to create healthcare user personas\
✅ How to analyze current hospital processes\
✅ How to create AS-IS BPMN thinking as a BA

**1. Why Stakeholder Analysis Is Critical in HMS**

A hospital is a complex ecosystem.

A mistake in understanding one stakeholder can impact:

-   Patient safety

-   Revenue

-   Compliance

-   Clinical operations

A BA must understand:

\"Who uses the system, what do they need, and what problems do they
face?\"

**2. HMS Stakeholder Analysis**

**Stakeholder Group 1: Executive Management**

**1. Hospital CEO**

**Responsibility:**

Overall hospital performance

**Goals:**

-   Increase operational efficiency

-   Improve patient satisfaction

-   Increase revenue

**Needs:**

-   Executive dashboards

-   Financial reports

-   Hospital performance metrics

**2. Hospital Administrator**

**Responsibility:**

Daily hospital operations

**Goals:**

-   Smooth patient flow

-   Better resource utilization

**Needs:**

-   Bed availability

-   Department workload

-   Staff management

**Stakeholder Group 2: Clinical Users**

**3. Doctor**

**Persona**

Name:

Dr. Sharma

Role:

Consultant Physician

Experience:

12 years

**Goals:**

-   Access complete patient history

-   Record diagnosis quickly

-   Manage treatment plans

**Pain Points:**

❌ Paper files are difficult to track

❌ Previous medical history unavailable

❌ Documentation takes time

**HMS Needs:**

-   Electronic patient records

-   Digital prescriptions

-   Clinical notes

**4. Nurse**

**Persona**

Name:

Priya

Role:

Staff Nurse

**Goals:**

-   Monitor patients

-   Update care activities

**Pain Points:**

❌ Manual charts

❌ Communication gaps

**HMS Needs:**

-   Nursing dashboard

-   Medication schedule

-   Patient alerts

**Stakeholder Group 3: Administrative Users**

**5. Receptionist**

**Goals:**

Register patients quickly.

**Pain Points:**

❌ Long queues

❌ Duplicate patient records

**HMS Needs:**

-   Patient registration

-   Appointment scheduling

-   Patient search

**6. Billing Executive**

**Goals:**

Generate accurate bills.

**Pain Points:**

❌ Manual calculations

❌ Insurance delays

**HMS Needs:**

-   Automated billing

-   Insurance integration

**7. Insurance Coordinator**

**Goals:**

Process insurance claims.

**Pain Points:**

❌ Missing documents

❌ Claim rejection

**HMS Needs:**

-   Claim tracking

-   Document management

**Stakeholder Group 4: Support Users**

**8. Lab Technician**

Needs:

-   Test orders

-   Result entry

-   Report publishing

**9. Pharmacist**

Needs:

-   Prescription management

-   Inventory tracking

**10. IT Administrator**

Needs:

-   User management

-   Security

-   System monitoring

**3. Stakeholder Power-Interest Matrix**

BA uses this to prioritize communication.

HIGH POWER

Manage Closely Keep Satisfied

CEO Insurance Head

Hospital Admin Department Heads

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Monitor Keep Informed

IT Team Patients

Nurses

Reception Staff

LOW POWER

**4. Patient Persona**

Patients are also stakeholders.

**Persona**

**Name:**

Raj

**Age:**

45

**Situation:**

Requires treatment at hospital.

**Goals:**

-   Quick appointment

-   Short waiting time

-   Easy access to reports

**Pain Points:**

❌ Long queues

❌ Repeating medical history

❌ Difficult billing process

**HMS Expectations:**

-   Online appointment

-   Digital records

-   Notifications

**5. Current AS-IS Hospital Registration Process**

Now we analyze the existing workflow.

**AS-IS Scenario:**

Patient visits hospital for consultation.

**Current Process**

Patient Arrives

↓

Reception Collects Details

↓

Manual Form Filling

↓

Search Existing Record

↓

Create Patient File

↓

Assign Doctor

↓

Patient Waits

↓

Consultation

**6. AS-IS Problems Identified**

  ------------------------------------------------------------------------
  **Process Step**    **Problem**                  **Impact**
  ------------------- ---------------------------- -----------------------
  Registration        Manual entry                 Slow process

  Patient Search      Paper files                  Duplicate records

  Doctor Access       No history availability      Delayed decisions

  Appointment         Manual booking               Scheduling issues
  ------------------------------------------------------------------------

**7. AS-IS BPMN Thinking**

Participants:

**Pool 1:**

Patient

**Pool 2:**

Reception Department

**Pool 3:**

Doctor

**AS-IS BPMN Flow**

Patient

(Start)

\|

Visit Hospital

\|

Provide Details

↓

Reception

Collect Information

\|

Search Existing Record

\|

Create Patient File

\|

Assign Doctor

↓

Doctor

Review Patient

\|

Consultation

\|

Write Prescription

(End)

**8. Another AS-IS Process: Admission Workflow**

Current:

Doctor recommends admission

↓

Admission Desk Checks Bed

↓

Manual Registration

↓

Assign Room

↓

Create Paper File

↓

Patient Admitted

**Problems:**

❌ Bed availability unclear

❌ Manual approvals

❌ Delayed admission

**9. BA Findings Summary**

At discovery stage:

Hospital Current State

Problems:

✓ Manual processes

✓ Data duplication

✓ Poor visibility

✓ Long patient waiting time

✓ Billing inefficiencies

Need:

Centralized HMS Platform

**10. BA Artifacts Added**

Project #5 now contains:

Hospital Management System

Discovery & Analysis

✓ Stakeholder Analysis

✓ User Personas

✓ Power Interest Matrix

✓ AS-IS Process

✓ BPMN Understanding

✓ Pain Point Analysis

**Interview Question**

**\"How do you gather requirements from multiple hospital
stakeholders?\"**

Strong Answer:

\"I identify stakeholders across clinical, administrative, and
management teams. I conduct interviews and workshops, understand their
workflows and pain points, map current processes, and convert findings
into business and functional requirements.\"

**Practical Assignment**

Create a persona for:

**Hospital Billing Executive**

Include:

1.  Goals

2.  Daily Activities

3.  Pain Points

4.  HMS Requirements

**Lesson 3 -- TO-BE Process Design, Future Workflow & BPMN Automation**

**Designing the Digital Hospital of the Future**

**Learning Objective**

After this lesson, you will understand:

✅ How a BA transforms manual hospital processes into digital workflows\
✅ How HMS improves patient, doctor, and administrative journeys\
✅ How to design TO-BE BPMN workflows\
✅ How automation reduces operational problems\
✅ How to identify HMS functional requirements from processes

**1. AS-IS → TO-BE Thinking**

A BA compares:

**Current State**

vs

**Future State**

**Current Hospital Process (AS-IS)**

Patient Arrives

↓

Manual Registration

↓

Paper File Creation

↓

Appointment Assignment

↓

Doctor Consultation

↓

Manual Prescription

↓

Billing

Problems:

❌ Long waiting time\
❌ Duplicate patient records\
❌ Lost medical history\
❌ Manual billing errors\
❌ Poor coordination between departments

**Future HMS Process (TO-BE)**

Patient Registration

↓

Digital Patient Profile

↓

Online Appointment

↓

Doctor Consultation

↓

Electronic Medical Record

↓

Digital Prescription

↓

Automated Billing

↓

Patient Follow-up

**2. TO-BE Patient Registration Workflow**

**Future Scenario:**

A patient visits hospital.

**Step 1: Patient Registration**

User:

Receptionist / Patient

System:

-   Checks existing patient

-   Creates unique patient ID

-   Stores demographics

**Step 2: Appointment Scheduling**

System:

-   Shows doctor availability

-   Suggests available slots

-   Confirms appointment

**Step 3: Patient Check-in**

System:

-   Marks arrival

-   Adds patient to doctor queue

**TO-BE BPMN Concept**

Participants:

**Pool 1:**

Patient

**Pool 2:**

Reception System

**Pool 3:**

Doctor

Patient

(Start)

\|

Book Appointment

\|

Arrive Hospital

↓

HMS System

Search Patient Record

\|

Confirm Appointment

\|

Generate Queue Token

↓

Doctor

Open Patient Record

\|

Consultation

\|

Update Medical Record

(End)

**3. TO-BE Doctor Consultation Workflow**

**Current Problem:**

Doctor writes notes manually.

**Future Solution:**

Doctor Dashboard:

Shows:

-   Patient history

-   Previous visits

-   Lab reports

-   Allergies

-   Medications

Workflow:

Patient Queue

↓

Doctor Opens Record

↓

Reviews History

↓

Records Diagnosis

↓

Creates Prescription

↓

Orders Lab Tests

↓

Updates Patient Record

**4. Electronic Medical Record (EMR)**

One of the most important HMS modules.

**EMR Contains:**

**Patient Information**

-   Name

-   Age

-   Contact

**Medical History**

-   Previous illnesses

-   Surgeries

-   Allergies

**Clinical Information**

-   Diagnosis

-   Notes

-   Prescription

**Investigation Data**

-   Lab reports

-   Imaging reports

**5. TO-BE Admission Workflow**

**Current:**

Manual bed allocation.

**Future HMS:**

Doctor Recommends Admission

↓

Admission Request Created

↓

System Checks Bed Availability

↓

Admin Approves Admission

↓

Room Assigned

↓

Patient Admitted

**Business Benefit:**

Before:

Staff manually searched beds.

After:

Real-time bed dashboard.

**6. TO-BE Billing Workflow**

**Current:**

Manual invoice preparation.

**Future:**

Treatment Completed

↓

Charges Automatically Generated

↓

Insurance Eligibility Check

↓

Bill Created

↓

Payment Received

↓

Receipt Generated

**7. HMS Automation Opportunities**

A BA identifies automation areas.

  -----------------------------------------------------------------------
  **Process**                **Automation**
  -------------------------- --------------------------------------------
  Registration               Auto patient ID

  Appointment                Online scheduling

  Doctor Notes               Digital documentation

  Billing                    Automatic calculation

  Insurance                  Claim validation

  Reports                    Dashboard analytics
  -----------------------------------------------------------------------

**8. Business Rules Example**

BA documents rules.

**Rule 1: Duplicate Patient Detection**

Condition:

If mobile number already exists:

System should show existing patient profile.

**Rule 2: Appointment Booking**

Condition:

Doctor cannot have two appointments at the same time.

**Rule 3: Bed Allocation**

Condition:

Patient admission cannot proceed without available bed confirmation.

**9. HMS Functional Requirements Generated**

From TO-BE process:

**FR-HMS-001**

Patient Registration

Requirement:

The system shall allow authorized users to create and manage patient
profiles.

**FR-HMS-002**

Appointment Management

Requirement:

The system shall allow patients and staff to schedule, modify, and
cancel appointments.

**FR-HMS-003**

Electronic Medical Record

Requirement:

The system shall maintain digital patient medical records accessible to
authorized healthcare providers.

**FR-HMS-004**

Billing Automation

Requirement:

The system shall automatically calculate charges based on services
provided.

**10. Before vs After Impact**

  ------------------------------------------------------------------------
  **Area**             **Before HMS**           **After HMS**
  -------------------- ------------------------ --------------------------
  Registration         Manual forms             Digital records

  Appointments         Phone-based              Online scheduling

  Medical History      Paper files              EMR

  Billing              Manual calculation       Automated

  Reporting            Delayed                  Real-time dashboard
  ------------------------------------------------------------------------

**11. BA Artifacts Added**

Project #5 now contains:

Hospital Management System

Process Design

✓ AS-IS Analysis

✓ TO-BE Process

✓ BPMN Workflow

✓ Automation Opportunities

✓ Business Rules

✓ Functional Requirements

**Interview Question**

**\"How do you identify automation opportunities in healthcare
processes?\"**

Strong Answer:

\"I first map the current AS-IS process, identify bottlenecks and manual
activities, analyze business impact, design a future-state TO-BE
workflow, and define requirements for automation while considering
compliance and user needs.\"

**Practical Assignment**

Design TO-BE workflow for:

**Laboratory Management Module**

Include:

1.  Test Request

2.  Sample Collection

3.  Lab Processing

4.  Result Generation

5.  Doctor Review

**Lesson 4 -- BRD, Scope, Business Requirements & Success Metrics**

**Converting Hospital Problems Into Business Requirements**

**Learning Objective**

After this lesson, you will understand:

✅ How to create a BRD for a healthcare enterprise system\
✅ How to define HMS business objectives\
✅ How to document scope boundaries\
✅ How to identify business requirements\
✅ How to define success metrics/KPIs

**1. Requirement Engineering Journey in HMS**

A BA converts:

Hospital Problem

↓

Business Objective

↓

Business Requirement

↓

Functional Requirement

↓

User Story

↓

Development

↓

Testing

**2. Business Requirements Document (BRD)**

**Project Name:**

Hospital Management System (HMS)

**Industry:**

Healthcare / Hospital Operations

**Project Vision:**

Build a centralized digital hospital platform that improves patient
care, operational efficiency, data accuracy, and decision-making through
integrated healthcare workflows.

**3. Business Problem Statement**

Current hospital operations are fragmented across multiple departments.

Patient information, appointments, clinical records, billing, and
reporting are managed through disconnected manual processes.

This results in:

-   Long patient waiting times

-   Duplicate patient records

-   Billing errors

-   Poor coordination between departments

-   Limited operational visibility

**4. Business Objectives**

**Objective 1:**

**Improve Patient Experience**

Expected Outcome:

-   Faster registration

-   Reduced waiting time

-   Easy appointment booking

**Objective 2:**

**Digitize Clinical Operations**

Expected Outcome:

-   Electronic Medical Records

-   Digital prescriptions

-   Better doctor access to history

**Objective 3:**

**Improve Revenue Management**

Expected Outcome:

-   Accurate billing

-   Faster insurance processing

-   Reduced revenue leakage

**Objective 4:**

**Improve Hospital Visibility**

Expected Outcome:

-   Real-time dashboards

-   Operational insights

-   Better decision-making

**5. Project Scope**

Scope defines:

\"What is included and what is not?\"

**IN SCOPE**

**Module 1: Patient Management**

Features:

✅ Patient registration

✅ Patient profile

✅ Medical history

✅ Patient search

**Module 2: Appointment Management**

Features:

✅ Doctor schedule

✅ Appointment booking

✅ Queue management

✅ Notifications

**Module 3: Clinical Management**

Features:

✅ Consultation notes

✅ Diagnosis recording

✅ Prescription management

✅ Medical records

**Module 4: Admission Management**

Features:

✅ Admission request

✅ Bed allocation

✅ Room management

✅ Discharge process

**Module 5: Laboratory Management**

Features:

✅ Test ordering

✅ Sample tracking

✅ Result publishing

**Module 6: Pharmacy Management**

Features:

✅ Prescription processing

✅ Medicine inventory

✅ Dispensing

**Module 7: Billing & Insurance**

Features:

✅ Invoice generation

✅ Payment tracking

✅ Insurance claims

**Module 8: Analytics**

Features:

✅ Hospital dashboard

✅ Department reports

✅ Revenue analytics

**OUT OF SCOPE (MVP)**

Not included initially:

❌ AI disease diagnosis

❌ Robotic healthcare systems

❌ Medical device integration

❌ National health exchange integration

**6. Business Requirements**

A BA documents requirements using IDs.

**BR-HMS-001**

**Centralized Patient Information**

Requirement:

The hospital shall maintain a single digital patient profile containing
demographic, clinical, and administrative information.

Business Value:

Reduce duplicate records and improve patient care.

**BR-HMS-002**

**Appointment Optimization**

Requirement:

The system shall provide digital appointment scheduling capabilities to
improve patient flow and doctor utilization.

Business Value:

Reduce waiting time.

**BR-HMS-003**

**Electronic Medical Records**

Requirement:

The system shall enable healthcare providers to create, access, and
update electronic patient medical records.

Business Value:

Improve clinical decision-making.

**BR-HMS-004**

**Automated Billing**

Requirement:

The system shall automate billing processes based on healthcare services
provided.

Business Value:

Reduce billing errors.

**BR-HMS-005**

**Hospital Analytics**

Requirement:

The system shall provide dashboards for monitoring operational and
financial performance.

Business Value:

Enable data-driven decisions.

**7. Stakeholder Goals Mapping**

  ------------------------------------------------------------------------
  **Stakeholder**   **Goal**                   **Business Requirement**
  ----------------- -------------------------- ---------------------------
  Doctor            Access patient history     EMR

  Receptionist      Faster registration        Patient Management

  Billing Team      Accurate invoices          Billing Automation

  Administrator     Monitor operations         Analytics

  Patient           Easy appointments          Appointment System
  ------------------------------------------------------------------------

**8. Business Success Metrics (KPIs)**

A project is successful only when outcomes improve.

**KPI 1: Patient Waiting Time**

Before HMS:

60 minutes

Target:

20 minutes

Measurement:

Average waiting time per patient

**KPI 2: Appointment Efficiency**

Measure:

Doctor schedule utilization

Example:

Before:

65%

After:

90%

**KPI 3: Billing Accuracy**

Measure:

Billing errors per month

Before:

200 errors

Target:

\<20 errors

**KPI 4: Patient Satisfaction**

Measure:

Patient feedback score

Before:

3.2/5

Target:

4.5/5

**KPI 5: Operational Visibility**

Measure:

Time required to generate reports.

Before:

2 days

After:

Real-time dashboard

**9. Business Benefits**

**Operational Benefits**

✅ Faster workflows

✅ Reduced paperwork

✅ Better coordination

**Clinical Benefits**

✅ Complete patient history

✅ Improved care decisions

✅ Reduced medical errors

**Financial Benefits**

✅ Better billing

✅ Faster payments

✅ Reduced leakage

**10. BRD Artifact Created**

Project #5 now contains:

Hospital Management System

Business Analysis Documentation

✓ BRD

✓ Business Problem

✓ Vision

✓ Objectives

✓ Scope

✓ Business Requirements

✓ Stakeholder Mapping

✓ KPIs

**Interview Question**

**\"What sections do you include in a BRD?\"**

Strong Answer:

\"A BRD includes business objectives, problem statement, scope,
stakeholders, current challenges, business requirements, assumptions,
constraints, risks, and success metrics.\"

**Practical Assignment**

Create 5 business requirements for:

**Telemedicine Module inside HMS**

For each include:

-   Requirement ID

-   Business Need

-   Expected Benefit

**Lesson 5 -- FRD, Functional Requirements, Modules & User Stories**

**Translating Business Needs Into System Requirements**

**Learning Objective**

After this lesson, you will understand:

✅ Difference between BRD and FRD\
✅ How to create functional requirements for HMS\
✅ How to break modules into features\
✅ How to write healthcare user stories\
✅ How to create acceptance criteria

**1. BRD vs FRD**

A common BA interview question:

\"What is the difference between BRD and FRD?\"

**BRD (Business Requirement Document)**

Focus:

**Why are we building this system?**

Created from:

Business problems and objectives.

Example:

Hospital needs to reduce patient waiting time.

**FRD (Functional Requirement Document)**

Focus:

**What should the system do?**

Created from:

Business requirements.

Example:

System shall allow patients to book appointments online.

**Requirement Flow**

Business Problem

↓

BRD

↓

Business Requirement

↓

FRD

↓

Functional Requirement

↓

User Story

↓

Development

**2. HMS Functional Requirement Document (FRD)**

**Project:**

Hospital Management System

**Module 1: Patient Registration**

**Business Need:**

Create a centralized patient database.

**Functional Requirements**

**FR-HMS-001**

**Create Patient Profile**

Requirement:

The system shall allow authorized staff to create new patient profiles.

Input:

-   Name

-   Date of birth

-   Gender

-   Contact details

-   Address

Output:

Unique Patient ID

**Acceptance Criteria**

Given receptionist is logged in

When patient details are entered

Then system creates a unique patient record

And displays patient ID

**User Story**

As a receptionist,

I want to create patient profiles,

so that patient information is stored digitally.

**Module 2: Appointment Management**

**FR-HMS-002**

**Doctor Availability**

Requirement:

System shall display doctor availability and available appointment
slots.

**User Story**

As a patient,

I want to view doctor availability,

so that I can book a suitable appointment.

**Acceptance Criteria**

Given doctor schedule exists

When patient searches doctor

Then available slots should display

And unavailable slots should not be bookable

**Module 3: Electronic Medical Record (EMR)**

**FR-HMS-003**

**Maintain Patient Medical History**

Requirement:

System shall allow doctors to view and update patient medical records.

Data:

-   Diagnosis

-   Symptoms

-   Allergies

-   Previous visits

-   Treatment history

**User Story**

As a doctor,

I want access to patient history,

so that I can make better treatment decisions.

**Module 4: Prescription Management**

**FR-HMS-004**

**Digital Prescription**

Requirement:

System shall allow doctors to create electronic prescriptions.

Features:

-   Medicine selection

-   Dosage

-   Frequency

-   Duration

-   Instructions

**User Story**

As a doctor,

I want to create digital prescriptions,

so that medication instructions are accurate.

**Module 5: Laboratory Management**

**FR-HMS-005**

**Lab Test Ordering**

Requirement:

System shall allow doctors to order laboratory investigations.

Workflow:

Doctor

↓

Order Test

↓

Lab Receives Request

↓

Sample Collection

↓

Result Entry

↓

Doctor Reviews Result

**User Story**

As a doctor,

I want to order lab tests electronically,

so that results are linked to patient records.

**Module 6: Admission & Bed Management**

**FR-HMS-006**

**Bed Allocation**

Requirement:

System shall display available beds and allow authorized users to assign
beds.

Rules:

-   Cannot assign occupied bed

-   Must record admission date

-   Must record department

**User Story**

As an admission executive,

I want to allocate beds,

so that patient admission is managed efficiently.

**Module 7: Billing Management**

**FR-HMS-007**

**Generate Patient Invoice**

Requirement:

System shall automatically generate invoices based on hospital services.

Includes:

-   Consultation charges

-   Lab charges

-   Pharmacy charges

-   Room charges

**User Story**

As a billing executive,

I want automated invoices,

so that billing errors are reduced.

**Module 8: Insurance Management**

**FR-HMS-008**

**Insurance Claim Tracking**

Requirement:

System shall track insurance claim status.

Statuses:

-   Submitted

-   Under Review

-   Approved

-   Rejected

-   Paid

**Module 9: Reporting Dashboard**

**FR-HMS-009**

**Hospital Performance Dashboard**

Requirement:

System shall provide dashboards showing operational and financial
metrics.

Metrics:

-   Patient count

-   Revenue

-   Bed occupancy

-   Doctor utilization

**3. HMS Feature Breakdown**

  -----------------------------------------------------------------------
  **Module**                              **Feature**
  --------------------------------------- -------------------------------
  Patient Management                      Registration

  Patient Management                      Medical History

  Appointments                            Booking

  Appointments                            Doctor Schedule

  EMR                                     Clinical Notes

  EMR                                     Prescription

  Lab                                     Test Orders

  Admission                               Bed Allocation

  Billing                                 Invoice

  Insurance                               Claims

  Analytics                               Dashboard
  -----------------------------------------------------------------------

**4. Non-Functional Requirements**

Important in healthcare systems.

**Security**

Requirement:

System shall restrict patient data access based on user roles.

**Performance**

Requirement:

Patient records should load within 3 seconds.

**Availability**

Requirement:

System should maintain 99.9% uptime.

**Compliance**

Requirement:

System should maintain audit logs for healthcare data access.

**5. BA Artifact Created**

Project #5 now contains:

Hospital Management System

Requirement Documentation

✓ FRD

✓ Functional Requirements

✓ User Stories

✓ Acceptance Criteria

✓ Business Rules

✓ Non-Functional Requirements

**Interview Question**

**\"How do you convert business requirements into user stories?\"**

Strong Answer:

\"I analyze the business requirement, identify the user role and
business goal, write the user story using the \'As a user, I want, so
that\' format, define acceptance criteria, and validate it with
stakeholders before development.\"

**Practical Assignment**

Create user stories for:

**HMS Pharmacy Module**

Create 5 stories:

Format:

**As a \[user\], I want \[feature\], so that \[benefit\].**

**Lesson 6 -- Epic Creation, Product Backlog, Prioritization & Jira
Setup**

**Managing HMS Delivery Using Agile**

**Learning Objective**

After this lesson, you will understand:

✅ How to convert HMS requirements into Epics and Features\
✅ How to create an Agile Product Backlog\
✅ How to prioritize healthcare features\
✅ How to structure Jira for HMS\
✅ How a BA supports Agile delivery

**1. From Requirements to Agile Backlog**

A BA converts:

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

Sprint Task

**Example**

Business Goal:

Reduce patient waiting time

↓

Epic:

Appointment Management

↓

Feature:

Online Appointment Booking

↓

User Story:

As a patient, I want to book appointments online so that I can avoid
waiting in queues.

↓

Acceptance Criteria:

-   Doctor availability displayed

-   Slot can be selected

-   Confirmation generated

**2. HMS Epic Structure**

Our HMS Product Backlog will contain these Epics:

**EPIC 1: Patient Management**

Goal:

Create a complete digital patient profile system.

Features:

-   Patient Registration

-   Patient Search

-   Medical History

-   Patient Profile Management

**EPIC 2: Appointment Management**

Goal:

Improve patient scheduling and doctor utilization.

Features:

-   Doctor Schedule

-   Appointment Booking

-   Appointment Cancellation

-   Queue Management

-   Notifications

**EPIC 3: Clinical Management (EMR)**

Goal:

Enable digital healthcare delivery.

Features:

-   Clinical Notes

-   Diagnosis Recording

-   Prescription Management

-   Allergy Tracking

-   Medical History

**EPIC 4: Admission & Bed Management**

Goal:

Optimize inpatient operations.

Features:

-   Admission Request

-   Bed Availability

-   Room Allocation

-   Discharge Management

**EPIC 5: Laboratory Management**

Goal:

Digitize investigation workflows.

Features:

-   Test Ordering

-   Sample Tracking

-   Result Entry

-   Report Sharing

**EPIC 6: Pharmacy Management**

Goal:

Manage medication workflows.

Features:

-   Prescription Processing

-   Inventory Tracking

-   Medicine Dispensing

**EPIC 7: Billing & Insurance**

Goal:

Improve hospital revenue cycle.

Features:

-   Invoice Generation

-   Payment Tracking

-   Insurance Claims

-   Claim Status

**EPIC 8: Analytics Dashboard**

Goal:

Provide operational visibility.

Features:

-   Patient Dashboard

-   Revenue Dashboard

-   Department Analytics

-   Performance Reports

**3. HMS Product Backlog Example**

  -------------------------------------------------------------------------------
  **Priority**   **Story    **User Story**                 **Epic**
                 ID**                                      
  -------------- ---------- ------------------------------ ----------------------
  P1             HMS-101    Create patient profile         Patient Management

  P1             HMS-102    Book appointment               Appointment

  P1             HMS-103    Doctor views medical history   EMR

  P1             HMS-104    Generate invoice               Billing

  P2             HMS-105    Manage beds                    Admission

  P2             HMS-106    Order lab tests                Laboratory

  P2             HMS-107    Track insurance claim          Insurance

  P3             HMS-108    Advanced analytics             Dashboard
  -------------------------------------------------------------------------------

**4. Feature Prioritization Using MoSCoW**

Healthcare systems have many requirements.

BA must decide:

\"What should we build first?\"

**Must Have (MVP)**

Critical for hospital operations.

✅ Patient Registration

✅ Appointment Booking

✅ EMR

✅ Billing

✅ User Authentication

**Should Have**

Important but can come later.

✅ Lab Integration

✅ Pharmacy Management

✅ Insurance Tracking

**Could Have**

Future improvements.

✅ Patient Mobile App

✅ AI Health Assistant

✅ Predictive Analytics

**Won\'t Have Initially**

Not part of first release.

❌ Robotic Surgery Integration

❌ Advanced AI Diagnosis

**5. Jira Project Setup**

**Project Name:**

HMS

**Project Type:**

Scrum

**Jira Issue Hierarchy**

Epic

↓

Story

↓

Task

↓

Sub-task

↓

Bug

**6. Jira Epics**

Example:

**Epic:**

HMS-EPIC-001

Patient Management

Stories:

**HMS-101**

Create Patient Profile

**HMS-102**

Search Patient Record

**HMS-103**

Update Patient Information

**7. Jira Workflow**

BACKLOG

↓

TO DO

↓

IN PROGRESS

↓

CODE REVIEW

↓

TESTING

↓

UAT

↓

DONE

**8. Sprint Planning Example**

**Sprint 1 Goal:**

\"Enable basic patient registration and appointment booking.\"

Duration:

2 Weeks

Sprint Stories:

  -----------------------------------------------------------------------
  **Story**                                              **Points**
  ------------------------------------------------------ ----------------
  Create Patient Profile                                 5

  Search Patient Record                                  3

  Doctor Schedule Setup                                  5

  Appointment Booking                                    8
  -----------------------------------------------------------------------

Total:

21 Story Points

**9. Story Point Estimation Example**

**Patient Registration**

Complexity:

-   Form creation

-   Validation

-   Database storage

Estimate:

5 points

**Appointment Booking**

Complexity:

-   Calendar

-   Doctor availability

-   Notifications

-   Conflicts

Estimate:

8 points

**10. BA Role in Backlog Management**

Before Sprint:

BA ensures:

✅ Clear user stories

✅ Acceptance criteria ready

✅ Business rules documented

✅ Dependencies identified

During Sprint:

BA:

-   Answers questions

-   Clarifies requirements

-   Supports testing

After Sprint:

BA:

-   Reviews demo

-   Collects feedback

-   Updates backlog

**11. HMS Agile Artifact Created**

Project #5 now contains:

Agile Delivery

✓ Epics

✓ Features

✓ Product Backlog

✓ Prioritization

✓ Jira Structure

✓ Sprint Example

✓ Estimation Approach

**Interview Question**

**\"How do you prioritize requirements in a healthcare project?\"**

Strong Answer:

\"I prioritize based on patient safety, business value, regulatory
needs, operational impact, and technical feasibility. Critical workflows
like patient registration, clinical records, and billing are prioritized
before enhancement features.\"

**Practical Assignment**

Create MoSCoW prioritization for these HMS features:

1.  AI Diagnosis Assistant

2.  Patient Registration

3.  Bed Management

4.  Mobile Appointment App

5.  Billing System

6.  Pharmacy Inventory

7.  Voice-based Doctor Notes

Classify each as:

-   Must Have

-   Should Have

-   Could Have

-   Later

**Lesson 7 -- User Journey Mapping, Wireframes & UX Requirements**

**Designing HMS From the User\'s Perspective**

**Learning Objective**

After this lesson, you will understand:

✅ Difference between process flow and user journey\
✅ How a BA creates healthcare user journeys\
✅ How to identify user pain points\
✅ How to define UX requirements\
✅ How to create low-fidelity wireframe concepts

**1. Why User Journey Matters in HMS**

A process map tells:

\"What steps happen?\"

A user journey tells:

\"What does the user experience during those steps?\"

Example:

**Process View**

Patient Registration

↓

Appointment

↓

Consultation

↓

Billing

**User Journey View**

Patient feels:

Confused → Waiting → Consultation → Payment Stress → Follow-up

A BA must understand both.

**2. Primary HMS Users**

We will create journeys for:

1.  Patient

2.  Doctor

3.  Receptionist

4.  Billing Executive

5.  Hospital Administrator

**3. Patient Journey Map**

**Persona:**

Raj

Age:

45

Goal:

Complete consultation quickly

**Current Journey (Before HMS)**

  -----------------------------------------------------------------------
  **Stage**        **Action**       **Pain Point**          **Emotion**
  ---------------- ---------------- ----------------------- -------------
  Find hospital    Calls hospital   No information          Confused

  Registration     Fills forms      Long queue              Frustrated

  Appointment      Waits            No visibility           Anxious

  Consultation     Meets doctor     History unavailable     Concerned

  Billing          Pays bill        Manual process          Stressed
  -----------------------------------------------------------------------

**Future Journey (After HMS)**

  --------------------------------------------------------------------------
  **Stage**      **Action**                   **HMS Support**  **Emotion**
  -------------- ---------------------------- ---------------- -------------
  Booking        Books appointment online     Slot             Happy
                                              availability     

  Arrival        Digital check-in             Queue token      Relaxed

  Consultation   Doctor views history         EMR access       Confident

  Billing        Digital invoice              Fast payment     Satisfied

  Follow-up      Gets reminders               Notifications    Engaged
  --------------------------------------------------------------------------

**4. Doctor User Journey**

**Persona:**

Dr. Sharma

Goal:

Provide efficient patient care

**Before HMS**

Problems:

-   Paper records

-   Missing history

-   Manual notes

-   Time-consuming documentation

**After HMS**

Journey:

Login

↓

View Patient Queue

↓

Open Medical Record

↓

Review History

↓

Record Diagnosis

↓

Create Prescription

↓

Order Tests

**Doctor Benefits:**

✅ Faster consultation

✅ Better decisions

✅ Complete patient information

**5. Receptionist Journey**

**Goal:**

Manage patient flow efficiently

Before:

Patient arrives

↓

Search files

↓

Manual registration

↓

Schedule appointment

Problems:

-   Duplicate records

-   Slow registration

After:

Search Patient

↓

Create/Update Profile

↓

Book Appointment

↓

Generate Token

**6. Billing Executive Journey**

**Goal:**

Generate accurate bills quickly

Before:

Problems:

-   Manual calculations

-   Missing charges

-   Claim delays

After:

Treatment Completed

↓

System Receives Charges

↓

Invoice Generated

↓

Insurance Verified

↓

Payment Processed

**7. UX Requirements**

A BA converts user needs into UX requirements.

**UX Requirement 1**

**Patient Dashboard**

Requirement:

The system should provide patients with an easy-to-use dashboard to
manage appointments, reports, and payments.

**UX Requirement 2**

**Doctor Dashboard**

Requirement:

The system should provide doctors quick access to patient history,
consultation notes, and prescriptions.

**UX Requirement 3**

**Reception Dashboard**

Requirement:

The system should enable reception staff to register patients within
minimal steps.

**8. HMS Wireframe Concepts**

Wireframes are low-level screen designs.

**Screen 1: Patient Dashboard**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Welcome Raj \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Upcoming Appointment \|

\| Dr. Sharma \|

\| 10:30 AM \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Medical Reports \|

\| Prescriptions \|

\| Bills \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

**Screen 2: Doctor Dashboard**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Doctor Dashboard \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Today\'s Queue:

1\. Raj Kumar

2\. Amit Patel

3\. Neha Shah

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Patient History

Diagnosis

Prescription

Lab Reports

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

**Screen 3: Reception Dashboard**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Patient Registration \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Search Patient:

\[\_\_\_\_\_\_\_\_\_\_\_\_\]

New Patient

\[Create\]

Appointment:

\[Book Slot\]

Queue:

15 Waiting

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

**Screen 4: Billing Dashboard**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Billing Management \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Patient:

Raj Kumar

Services:

Consultation ₹500

Lab ₹2000

Medicine ₹1500

Total:

₹4000

\[Generate Invoice\]

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

**9. User Flow Example**

**Appointment Booking**

Patient Opens App

↓

Select Doctor

↓

Select Date

↓

Choose Slot

↓

Confirm Booking

↓

Receive Notification

**10. UX Problems BA Should Identify**

  -----------------------------------------------------------------------
  **Problem**                                   **Solution**
  --------------------------------------------- -------------------------
  Too many registration fields                  Simplified form

  Doctors need many clicks                      Quick actions

  Patients don\'t know status                   Live updates

  Billing confusion                             Clear invoice
  -----------------------------------------------------------------------

**11. BA Artifacts Added**

Project #5 now contains:

Hospital Management System

UX Analysis

✓ User Personas

✓ Patient Journey Map

✓ Doctor Journey

✓ Reception Journey

✓ UX Requirements

✓ Wireframe Concepts

✓ User Flows

**Interview Question**

**\"What is the difference between user journey mapping and workflow
mapping?\"**

Strong Answer:

\"Workflow mapping focuses on the sequence of business activities and
system processes, while user journey mapping focuses on the user\'s
experience, emotions, pain points, and interactions throughout that
process.\"

**Practical Assignment**

Create a user journey map for:

**Hospital Admission Process**

Include:

1.  Patient actions

2.  Hospital actions

3.  Pain points

4.  HMS improvements

**Lesson 8 -- Database Concepts, Data Requirements, Integrations &
Healthcare Security**

**Understanding HMS Data Architecture as a Business Analyst**

**Learning Objective**

After this lesson, you will understand:

✅ What data HMS manages\
✅ How BA defines data requirements\
✅ Basic HMS database structure\
✅ Healthcare system integrations\
✅ Security and compliance requirements

**1. Why Data Understanding Is Important for BA**

A Hospital Management System is a **data-heavy system**.

Every hospital activity creates data:

Patient Visit

↓

Medical Record

↓

Lab Report

↓

Prescription

↓

Billing

↓

Insurance Claim

A BA does not design the database, but must understand:

-   What data is required?

-   Who creates it?

-   Who uses it?

-   How should it be protected?

**2. HMS Core Data Domains**

A BA usually divides HMS data into domains.

**Domain 1: Patient Data**

Contains:

-   Patient ID

-   Name

-   Date of Birth

-   Gender

-   Contact details

-   Address

-   Emergency contact

-   Insurance details

Example:

Patient

Patient_ID: P10045

Name: Raj Kumar

DOB: 15-04-1980

Blood Group: B+

**Domain 2: Medical Record Data (EMR)**

Contains:

Clinical information:

-   Symptoms

-   Diagnosis

-   Allergies

-   Previous diseases

-   Treatment history

-   Doctor notes

Example:

Patient:

Raj Kumar

Diagnosis:

Hypertension

Medication:

Medicine ABC

Doctor:

Dr. Sharma

**Domain 3: Appointment Data**

Contains:

-   Appointment ID

-   Patient ID

-   Doctor ID

-   Date

-   Time slot

-   Status

Example:

Appointment ID:

APT1001

Patient:

Raj Kumar

Doctor:

Dr. Sharma

Status:

Confirmed

**Domain 4: Billing Data**

Contains:

-   Invoice ID

-   Services

-   Charges

-   Payments

-   Insurance status

Example:

Invoice:

INV5001

Consultation:

₹500

Lab:

₹2000

Total:

₹2500

**Domain 5: Pharmacy Data**

Contains:

-   Medicine inventory

-   Stock quantity

-   Expiry date

-   Prescription details

**Domain 6: Laboratory Data**

Contains:

-   Test orders

-   Sample details

-   Results

-   Reports

**3. HMS High-Level Data Model**

A BA understands relationships.

Example:

PATIENT

\|

\| 1:M

\|

APPOINTMENT

\|

\|

CONSULTATION

\|

\|

PRESCRIPTION

\|

\|

BILLING

Meaning:

One patient can have:

-   Multiple appointments

-   Multiple consultations

-   Multiple prescriptions

-   Multiple bills

**4. Data Requirements Document (BA Artifact)**

BA documents:

**DR-HMS-001**

**Patient Information Requirement**

Requirement:

System shall store patient demographic and healthcare information
required for hospital operations.

**DR-HMS-002**

**Medical Record Requirement**

Requirement:

System shall maintain patient clinical history including diagnosis,
medication, and treatment information.

**DR-HMS-003**

**Audit Data Requirement**

Requirement:

System shall maintain user activity logs for healthcare data access.

**5. HMS System Integrations**

Modern hospitals rarely work alone.

HMS integrates with:

**1. Laboratory Information System (LIS)**

Purpose:

Send test orders and receive results.

Flow:

Doctor Orders Test

↓

HMS

↓

LIS

↓

Test Result

↓

HMS Patient Record

**2. Pharmacy System**

Purpose:

Manage medicines.

Flow:

Prescription

↓

Pharmacy

↓

Inventory Update

**3. Insurance Systems**

Purpose:

Claims processing.

Flow:

Patient Treatment

↓

HMS Billing

↓

Insurance Provider

↓

Claim Approval

**4. Payment Gateway**

Purpose:

Digital payments.

Supports:

-   Cards

-   UPI

-   Online payments

**5. National Healthcare Systems**

Examples:

-   Health information exchange

-   Digital health records

**6. API Integration Requirements**

BA may define:

**API Requirement Example**

**INT-HMS-001**

Lab Result Integration

Requirement:

The system shall exchange laboratory results between HMS and external
laboratory systems through secure APIs.

**7. Healthcare Security Requirements**

Healthcare data is sensitive.

A BA must define security needs.

**Security Requirement 1**

**Role-Based Access Control (RBAC)**

Example:

Doctor:

Can view medical records

Billing Staff:

Can view billing information only

**Security Requirement 2**

**Data Encryption**

Requirement:

Patient data shall be encrypted during storage and transmission.

**Security Requirement 3**

**Audit Trail**

System should record:

-   Who accessed data

-   When data was accessed

-   What changes were made

Example:

User:

Dr. Sharma

Action:

Viewed Patient Record

Time:

10:30 AM

**Security Requirement 4**

**Authentication**

Support:

-   Username/password

-   Multi-factor authentication

-   Session management

**8. Healthcare Compliance Considerations**

Depending on geography:

Examples:

-   HIPAA (US)

-   GDPR (Europe)

-   Local healthcare regulations

BA should ensure:

-   Privacy

-   Consent management

-   Data retention

-   Access control

**9. Non-Functional Requirements**

**Performance**

Requirement:

Patient records should load within 3 seconds.

**Availability**

Requirement:

HMS should be available 24/7 for critical hospital operations.

**Scalability**

Requirement:

System should support increasing patients and hospital branches.

**10. BA Artifact Added**

Project #5 now contains:

Hospital Management System

Technical Analysis Layer

✓ Data Requirements

✓ Data Domains

✓ High-Level Data Model

✓ Integration Requirements

✓ API Requirements

✓ Security Requirements

✓ Compliance Considerations

**Interview Question**

**\"What security requirements would you consider for a healthcare
application?\"**

Strong Answer:

\"I would consider role-based access control, authentication,
encryption, audit logging, data privacy, consent management, and
compliance requirements because healthcare systems handle sensitive
patient information.\"

**Practical Assignment**

Create integration requirements for:

**HMS + Pharmacy System**

Include:

1.  Integration purpose

2.  Data exchanged

3.  Business benefit

**Lesson 9 -- Testing Strategy, UAT, Traceability Matrix & Release
Planning**

**Validating a Healthcare Enterprise System Before Go-Live**

**Learning Objective**

After this lesson, you will understand:

✅ How BA supports testing activities\
✅ Difference between Functional Testing, UAT, and Production
Validation\
✅ How to create HMS UAT scenarios\
✅ How to build Requirement Traceability Matrix (RTM)\
✅ How to plan HMS releases

**1. Why Testing Is Critical in HMS**

A Hospital Management System handles:

-   Patient information

-   Medical history

-   Prescriptions

-   Billing

-   Insurance

-   Lab results

A defect can impact:

-   Patient safety

-   Hospital operations

-   Revenue

-   Compliance

Therefore:

Healthcare software requires strong validation before deployment.

**2. HMS Testing Approach**

Testing layers:

Requirement Validation

↓

Functional Testing

↓

Integration Testing

↓

Security Testing

↓

User Acceptance Testing

↓

Production Validation

**3. Functional Testing**

Performed mainly by QA team.

Purpose:

Verify individual features work correctly.

Example:

**Feature:**

Patient Registration

Test:

Input valid patient details.

Expected:

System creates patient ID.

**Functional Test Cases**

  -----------------------------------------------------------------------
  **Test    **Scenario**                 **Expected Result**
  ID**                                   
  --------- ---------------------------- --------------------------------
  FT-001    Create patient profile       Patient ID generated

  FT-002    Search patient               Correct record displayed

  FT-003    Book appointment             Appointment confirmed

  FT-004    Generate invoice             Correct bill created
  -----------------------------------------------------------------------

**4. Integration Testing**

HMS connects with many systems.

Examples:

-   Laboratory System

-   Pharmacy System

-   Insurance System

-   Payment Gateway

Example:

**HMS + Laboratory Integration**

Test:

Doctor orders blood test.

Expected:

1.  Order sent to LIS

2.  Lab receives request

3.  Result returned to HMS

4.  Doctor can view result

**5. Security Testing**

Important for healthcare.

Test:

**Unauthorized Access**

Scenario:

Billing employee tries accessing medical records.

Expected:

Access denied.

**Audit Logging**

Scenario:

Doctor views patient record.

Expected:

System records:

-   User

-   Time

-   Action

**6. User Acceptance Testing (UAT)**

UAT answers:

\"Can real hospital users successfully perform their work?\"

**UAT Participants**

  -----------------------------------------------------------------------
  **User**                      **Testing Area**
  ----------------------------- -----------------------------------------
  Doctor                        EMR, prescription

  Nurse                         Patient care workflow

  Receptionist                  Registration

  Billing Team                  Invoices

  Insurance Team                Claims

  Administrator                 Reports
  -----------------------------------------------------------------------

**7. HMS UAT Test Cases**

**UAT-HMS-001**

**Patient Registration**

User:

Receptionist

Scenario:

Create new patient.

Steps:

1.  Login

2.  Open registration

3.  Enter patient details

4.  Save

Expected Result:

Patient profile created with unique ID.

**UAT-HMS-002**

**Appointment Booking**

User:

Receptionist / Patient

Scenario:

Book doctor appointment.

Expected:

-   Available slots displayed

-   Appointment confirmed

-   Notification generated

**UAT-HMS-003**

**Doctor Consultation**

User:

Doctor

Scenario:

Record patient diagnosis.

Expected:

Doctor can:

-   View history

-   Add diagnosis

-   Create prescription

**UAT-HMS-004**

**Billing**

User:

Billing Executive

Scenario:

Generate final invoice.

Expected:

System calculates correct charges.

**UAT-HMS-005**

**Discharge Process**

User:

Hospital Administrator

Scenario:

Discharge admitted patient.

Expected:

-   Discharge summary generated

-   Final bill created

-   Bed status updated

**8. Requirement Traceability Matrix (RTM)**

RTM connects:

Business Requirement → Functional Requirement → User Story → Test Case

**HMS RTM Example**

  ------------------------------------------------------------------------
  **Business Requirement**   **Functional             **User     **Test
                             Requirement**            Story**    Case**
  -------------------------- ------------------------ ---------- ---------
  Reduce waiting time        Appointment Booking      HMS-102    UAT-002

  Digital medical records    EMR Management           HMS-103    UAT-003

  Improve billing            Invoice Generation       HMS-104    UAT-004

  Improve admission process  Bed Management           HMS-105    UAT-005
  ------------------------------------------------------------------------

**9. Defect Example**

During UAT:

**Bug:**

Incorrect Billing Calculation

Jira Bug:

Bug ID:

HMS-501

Title:

Incorrect calculation of room charges

Severity:

High

Steps:

1\. Admit patient

2\. Add room charges

3\. Generate invoice

Expected:

Correct total amount

Actual:

Duplicate room charge added

Status:

Open

**10. Release Planning**

A hospital system should not launch everything at once.

Use phased rollout.

**Release 1.0 -- HMS Foundation**

Timeline:

3 Months

Features:

✅ Patient Registration

✅ Appointment Management

✅ User Management

✅ Basic EMR

**Release 2.0 -- Clinical Operations**

Timeline:

6 Months

Features:

✅ Lab Management

✅ Pharmacy

✅ Admission

✅ Discharge

**Release 3.0 -- Enterprise Intelligence**

Timeline:

12 Months

Features:

✅ Analytics Dashboard

✅ Insurance Automation

✅ AI Features

**11. Go-Live Checklist**

Before production:

**Business Readiness**

✅ User training completed

✅ UAT sign-off received

**Technical Readiness**

✅ Data migration completed

✅ Security testing completed

✅ Backup configured

**Operational Readiness**

✅ Support team available

✅ Issue management process ready

**12. BA Role During Testing & Release**

Before Testing:

-   Prepare requirements

-   Define acceptance criteria

During Testing:

-   Clarify requirements

-   Support testers

-   Analyze defects

Before Release:

-   Validate business readiness

-   Coordinate sign-off

**13. BA Artifacts Added**

Project #5 now contains:

Hospital Management System

Testing & Release

✓ Test Strategy

✓ Functional Test Cases

✓ Integration Testing

✓ Security Testing

✓ UAT Scenarios

✓ RTM

✓ Release Plan

✓ Go-Live Checklist

**Interview Question**

**\"What is the role of a BA during UAT?\"**

Strong Answer:

\"A BA prepares UAT scenarios based on business requirements,
coordinates with business users, clarifies expected behavior, manages
defects, validates fixes, and supports final business sign-off.\"

**Practical Assignment**

Create UAT scenarios for:

**HMS Pharmacy Module**

Create 5 test cases:

-   Test ID

-   Scenario

-   Expected Result

**Lesson 10 -- Analytics Dashboard, KPIs, Reports & Executive Decision
Support**

**Turning Hospital Data Into Business Insights**

**Learning Objective**

After this lesson, you will understand:

✅ Why analytics is important in HMS\
✅ How a BA defines dashboard requirements\
✅ Difference between operational and strategic KPIs\
✅ How to design healthcare dashboards\
✅ How analytics supports hospital decisions

**1. Why Hospitals Need Analytics**

A hospital generates thousands of data points every day:

-   Patient visits

-   Admissions

-   Surgeries

-   Lab tests

-   Pharmacy sales

-   Revenue

-   Insurance claims

Without analytics:

Data exists but decisions are slow.

With HMS Analytics:

Data becomes actionable information.

**2. Analytics Flow in HMS**

Hospital Activities

↓

HMS Database

↓

Data Processing

↓

Analytics Engine

↓

Dashboards

↓

Business Decisions

**3. Dashboard Users**

Different users need different views.

**1. Hospital CEO Dashboard**

Purpose:

Strategic decision-making

Needs:

-   Revenue

-   Growth

-   Patient volume

-   Hospital performance

**2. Hospital Administrator Dashboard**

Purpose:

Daily operations

Needs:

-   Bed occupancy

-   Patient flow

-   Department workload

-   Staff utilization

**3. Doctor Dashboard**

Purpose:

Clinical productivity

Needs:

-   Patient queue

-   Consultation count

-   Follow-up cases

**4. Finance Dashboard**

Purpose:

Revenue management

Needs:

-   Billing

-   Payments

-   Insurance claims

-   Outstanding amounts

**4. HMS Executive Dashboard**

Example:

================================

HOSPITAL PERFORMANCE DASHBOARD

================================

Today\'s Patients:

850

Admissions:

75

Discharges:

62

Bed Occupancy:

88%

Revenue:

₹35 Lakhs

Pending Claims:

120

Patient Satisfaction:

4.5/5

================================

**5. Patient Analytics Dashboard**

**Purpose:**

Understand patient patterns.

Metrics:

**Daily Patient Visits**

Formula:

Total patients registered today

**Patient Growth Rate**

Formula:

(Current Month Patients - Previous Month Patients)

/ Previous Month Patients × 100

**Repeat Patient Rate**

Shows:

Patient loyalty.

**Business Question:**

\"Are patients returning to our hospital?\"

**6. Hospital Operations Dashboard**

**Bed Management**

Metrics:

**Bed Occupancy Rate**

Formula:

Occupied Beds / Total Available Beds × 100

Example:

400 occupied beds

500 total beds

= 80%

**Department Performance**

Metrics:

-   OPD visits

-   Emergency cases

-   Surgery count

-   Waiting time

**7. Clinical Dashboard**

For doctors and clinical managers.

Metrics:

**Average Consultation Time**

Example:

Doctor sees:

20 patients

Total consultation time:

300 minutes

Average:

15 minutes/patient

**Patient Follow-up Compliance**

Measures:

How many patients completed follow-up visits.

**8. Revenue Dashboard**

Important for hospital management.

Metrics:

**Total Revenue**

Includes:

-   Consultation

-   Pharmacy

-   Lab

-   Admission charges

**Revenue by Department**

Example:

  -----------------------------------------------------------------------
  **Department**                            **Revenue**
  ----------------------------------------- -----------------------------
  Cardiology                                ₹20L

  Neurology                                 ₹15L

  Orthopedics                               ₹12L
  -----------------------------------------------------------------------

**Claim Processing Metrics**

Insurance KPIs:

-   Claims submitted

-   Claims approved

-   Claims rejected

-   Pending claims

**9. Quality & Patient Safety Dashboard**

Healthcare organizations monitor quality.

Metrics:

**Patient Satisfaction Score**

Example:

Average rating:

4.6/5

**Readmission Rate**

Formula:

Patients readmitted / Total discharged patients

**Medication Error Rate**

Tracks:

Safety incidents.

**10. BA Dashboard Requirements**

A BA documents:

**Dashboard Requirement:**

**DASH-HMS-001**

**Hospital Executive Dashboard**

Requirement:

The system shall provide hospital leadership with real-time visibility
into operational, clinical, and financial performance indicators.

**Acceptance Criteria:**

Given user has administrator access

When dashboard is opened

Then system displays approved KPIs

And data is refreshed automatically

**11. Dashboard Wireframe**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Hospital Executive Dashboard \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Patients Today Revenue

850 ₹35L

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Bed Occupancy Claims

88% 120

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

Department Performance Chart

Cardiology ████████

Neurology ██████

Ortho █████

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

**12. KPI Mapping**

A BA connects:

Feature → KPI → Business Outcome

  -----------------------------------------------------------------------
  **HMS Feature**       **KPI**                 **Outcome**
  --------------------- ----------------------- -------------------------
  Appointment System    Waiting Time            Better patient experience

  EMR                   Medical error reduction Better care

  Billing Automation    Revenue accuracy        Financial improvement

  Bed Management        Occupancy rate          Resource optimization

  Analytics             Decision speed          Better management
  -----------------------------------------------------------------------

**13. Advanced Analytics Opportunities**

Future HMS enhancements:

**Predictive Analytics**

Examples:

-   Predict patient admission demand

-   Predict bed requirements

-   Predict medicine consumption

**AI Opportunities**

Examples:

-   AI appointment scheduling

-   AI clinical documentation

-   AI hospital operations assistant

**14. BA Artifacts Added**

Project #5 now contains:

Hospital Management System

Analytics & Reporting

✓ Dashboard Requirements

✓ KPI Definitions

✓ Executive Dashboard

✓ Operational Metrics

✓ Financial Metrics

✓ Healthcare Analytics Use Cases

**Interview Question**

**\"How do you define KPIs for a healthcare product?\"**

Strong Answer:

\"I start by understanding business objectives and stakeholder goals.
Then I define measurable indicators linked to outcomes such as patient
satisfaction, operational efficiency, revenue improvement, clinical
quality, and compliance.\"

**Practical Assignment**

Design KPIs for:

**Hospital Emergency Department Dashboard**

Create:

1.  KPI Name

2.  Formula

3.  Business Purpose

Create minimum 5 KPIs.

**Lesson 11 -- Final Case Study Documentation, Portfolio Presentation &
Interview Preparation**

**Converting HMS Work Into a Professional BA Portfolio Project**

**Learning Objective**

After this lesson, you will understand:

✅ How to package an end-to-end BA project\
✅ How to present HMS in interviews\
✅ What documents a BA portfolio should contain\
✅ How to explain your role and contribution\
✅ How to create a project case study

**1. Why Portfolio Documentation Matters**

Many candidates say:

\"I know requirements gathering.\"

But interviewers ask:

\"Show me how you applied it.\"

A portfolio proves:

-   Your BA thinking

-   Your documentation skills

-   Your process analysis ability

-   Your product understanding

**2. HMS Portfolio Case Study Structure**

Your final project document should look like an enterprise BA case
study.

**Section 1: Project Overview**

**Project Name:**

Hospital Management System (HMS)

**Industry:**

Healthcare

**Project Type:**

Enterprise Healthcare Digital Transformation Platform

**Duration:**

12 Months

**Delivery Model:**

Agile Scrum

**Project Vision:**

Build an integrated hospital management platform that digitizes patient
care, clinical workflows, administrative operations, and analytics to
improve healthcare efficiency and patient experience.

**Section 2: Business Problem**

Current hospital challenges:

-   Manual patient registration

-   Long waiting times

-   Paper-based medical records

-   Billing errors

-   Poor department coordination

-   Limited reporting capability

**Section 3: Stakeholder Analysis**

Include:

  -----------------------------------------------------------------------
  **Stakeholder**                         **Role**
  --------------------------------------- -------------------------------
  CEO                                     Project Sponsor

  Hospital Administrator                  Business Owner

  Doctors                                 Clinical Users

  Nurses                                  Care Providers

  Receptionists                           Operational Users

  Billing Team                            Finance Users

  Patients                                End Users

  IT Team                                 Technical Support
  -----------------------------------------------------------------------

**Section 4: AS-IS Process Analysis**

Example:

**Patient Registration**

Current:

Patient Arrival

↓

Manual Form

↓

File Creation

↓

Doctor Assignment

↓

Consultation

Problems:

-   Slow registration

-   Duplicate records

-   Missing history

**Section 5: TO-BE Process Design**

Future:

Online Registration

↓

Digital Patient Profile

↓

Appointment Booking

↓

EMR Access

↓

Consultation

↓

Digital Billing

Benefits:

-   Faster workflow

-   Better patient experience

-   Accurate data

**Section 6: Requirement Documentation**

Include:

**BRD**

Contains:

-   Business objectives

-   Scope

-   Business requirements

**FRD**

Contains:

-   Functional requirements

-   System behavior

**User Stories**

Example:

As a doctor, I want to view patient history so that I can provide better
treatment decisions.

**Acceptance Criteria**

Example:

Given doctor is logged in

When patient record is opened

Then medical history should be displayed.

**Section 7: Agile Delivery Artifacts**

Include:

**Epics**

Example:

Epic:

Patient Management

**Features**

Example:

Feature:

Patient Registration

**Product Backlog**

Example:

  -----------------------------------------------------------------------
  **ID**                 **Story**
  ---------------------- ------------------------------------------------
  HMS-101                Create patient profile

  HMS-102                Book appointment

  HMS-103                View medical history
  -----------------------------------------------------------------------

**Jira Board**

Show:

BACKLOG

↓

TO DO

↓

IN PROGRESS

↓

TESTING

↓

DONE

**Section 8: UX Artifacts**

Include:

**User Journey Map**

Patient journey:

Before:

Long queues

After:

Digital appointment

**Wireframes**

Screens:

-   Patient Dashboard

-   Doctor Dashboard

-   Billing Screen

-   Admin Dashboard

**Section 9: Testing Documents**

Include:

**Test Strategy**

**UAT Scenarios**

Example:

UAT:

Appointment Booking

Expected:

Patient can book available slot successfully.

**RTM**

Mapping:

Requirement → Story → Test Case

**Section 10: Analytics & KPIs**

Include:

**Hospital Dashboard Metrics**

Examples:

**Patient Waiting Time**

Target:

Reduce from 60 min → 20 min

**Bed Occupancy**

Target:

Optimize resource usage

**Revenue Accuracy**

Target:

Reduce billing errors

**3. How To Explain HMS In Interview**

Question:

**\"Tell me about your healthcare project.\"**

Sample Answer:

\"I worked on a Hospital Management System transformation project where
the objective was to digitize hospital operations. I analyzed current
workflows, gathered requirements from stakeholders like doctors,
administrators, billing teams, and patients. I created AS-IS and TO-BE
process models, documented BRD and FRD, converted requirements into user
stories, supported sprint planning, UAT, and defined KPIs for measuring
project success.\"

**4. BA Skills Demonstrated Through HMS**

  -----------------------------------------------------------------------
  **Skill**                         **Evidence**
  --------------------------------- -------------------------------------
  Requirement Gathering             Stakeholder workshops

  Process Analysis                  AS-IS / TO-BE BPMN

  Documentation                     BRD, FRD

  Agile                             Stories, Backlog, Jira

  UX Analysis                       Journey Maps, Wireframes

  Testing                           UAT, RTM

  Analytics                         KPIs, Dashboards
  -----------------------------------------------------------------------

**5. HMS Portfolio Folder Structure**

Your project repository:

Hospital Management System

01_Project_Overview

02_Business_Problem

03_Stakeholder_Analysis

04_AS_IS_Process

05_TO_BE_Process

06_BRD

07_FRD

08_User_Stories

09_Product_Backlog

10_Jira_Board

11_Wireframes

12_Testing_UAT

13_RTM

14_Dashboard_KPIs

15_Final_Case_Study

**6. Final HMS Project Completion Status**

**Completed BA Artifacts:**

✅ Business Problem\
✅ Stakeholder Analysis\
✅ Personas\
✅ AS-IS Process\
✅ TO-BE Process\
✅ BPMN Understanding\
✅ BRD\
✅ FRD\
✅ Epics\
✅ Features\
✅ User Stories\
✅ Acceptance Criteria\
✅ Product Backlog\
✅ Prioritization\
✅ Jira Structure\
✅ Sprint Planning\
✅ Wireframes\
✅ User Journey Mapping\
✅ Data Requirements\
✅ Integration Requirements\
✅ Security Requirements\
✅ Testing Strategy\
✅ UAT\
✅ RTM\
✅ Release Plan\
✅ KPIs & Dashboard

**Project #5 HMS = COMPLETE ✅**

You now have an enterprise-level BA case study suitable for:

-   Healthcare Business Analyst interviews

-   Product Analyst roles

-   HealthTech Product Manager roles
