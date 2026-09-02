---
title: "Agile Masterclass_M7 (89-)"
---

# Agile Masterclass_M7 (89-)

**Before Starting Lesson 1**

Let\'s understand the documentation hierarchy.

A product is built through a chain of documents:

PRODUCT VISION

\|

↓

PRODUCT ROADMAP

\|

↓

BUSINESS CASE

\|

↓

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

\| \|

BRD PRD

\| \|

↓ ↓

FRD + NFR User Stories

\| \|

↓ ↓

Process Models Acceptance Criteria

\|

↓

Development

\|

↓

Testing

\|

↓

Release Notes

**Example: AI Pharmacovigilance Platform**

**Product Vision**

Question:

**Why are we building this?**

Answer:

\"To reduce pharmacovigilance case processing time using AI-powered
automation while maintaining regulatory compliance.\"

**Roadmap**

Question:

**Where are we going?**

Example:

Phase 1:

-   Case intake

-   PDF extraction

Phase 2:

-   MedDRA coding AI

-   Duplicate detection

Phase 3:

-   Signal detection

-   Predictive analytics

**Business Case**

Question:

**Should we invest money in this?**

Example:

Current problem:

-   Manual ICSR processing takes 2 hours/case.

Solution:

AI automation reduces processing time by 60%.

Expected benefit:

-   Lower operational cost.

-   Faster regulatory submission.

**PRD**

Question:

**What product should we build?**

Example:

Feature:

AI Case Extraction

Requirement:

System should extract:

-   Patient information

-   Drug information

-   Adverse events

-   Reporter details

**User Story**

Question:

**What does the user need?**

Example:

As a Pharmacovigilance Specialist,

I want AI to extract case information automatically,

so that I can reduce manual data entry time.

**Acceptance Criteria**

Question:

**How do we know it works?**

Example:

Given:

A valid adverse event PDF is uploaded.

When:

AI extraction completes.

Then:

The system should display extracted patient, drug, and event information
with confidence scores.

**Process Flow**

Question:

**How does the workflow happen?**

Example:

Receive Case

↓

Upload Document

↓

AI Extraction

↓

Medical Review

↓

Approve

↓

Submit to Regulatory Authority

**RTM**

Question:

**Can we trace requirements from business need to testing?**

Example:

Business Need

\|

↓

Requirement

\|

↓

User Story

\|

↓

Test Case

\|

↓

Release

**Why Module 7 is Critical for Your Career Goal**

For a pure developer:

Coding ability is important.

For a Product/BA role:

The ability to convert:

Business Problem

↓

Product Requirement

↓

Feature

↓

User Story

↓

Development

↓

Testing

↓

Business Outcome

is the core skill.

**Portfolio Goal After Module 7**

By the end of this module, you should be able to create documentation
for:

**Project:**

**AI Pharmacovigilance Platform**

You will create:

✅ Product Vision Document\
✅ Product Roadmap\
✅ Business Case\
✅ PRD\
✅ BRD\
✅ FRD\
✅ NFR Document\
✅ User Story Backlog\
✅ Acceptance Criteria\
✅ Wireframes\
✅ Use Cases\
✅ BPMN Process Flow\
✅ UML Diagrams\
✅ Decision Tables\
✅ RTM\
✅ Release Notes

This becomes a strong portfolio project for:

-   Healthcare BA

-   Product Analyst

-   AI Product Manager interviews

**Lesson 1: Product Vision (Masterclass)**

**Role Perspective:** Product Manager • Product Owner • Business Analyst
• AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What Product Vision is.

-   Why every successful product needs a vision.

-   Difference between Vision, Mission, Strategy, and Roadmap.

-   How Product Managers create a Product Vision.

-   How to write a Product Vision Document.

-   Real examples from Amazon, Google, healthcare, and AI products.

-   How to create a Product Vision for your AI Pharmacovigilance
    Platform.

**1. Concept: What is Product Vision?**

**Simple Definition**

A **Product Vision** is a clear statement describing:

**\"What future we want to create for our customers through our
product.\"**

It explains:

-   Why the product exists.

-   Who it helps.

-   What problem it solves.

-   What impact it creates.

A Product Vision is the **North Star** of the product.

Every decision should connect back to it.

**2. Why Does Product Vision Exist?**

Imagine a company says:

\"Let\'s build a healthcare AI platform.\"

The team asks:

Developer:

\"What features should we build?\"

Designer:

\"What should the user experience look like?\"

Business team:

\"What problem are we solving?\"

Regulatory team:

\"What compliance requirements matter?\"

Without a vision, everyone moves in different directions.

**Without Vision**

Product Team

↓

Feature A

↓

Feature B

↓

Feature C

No clear destination

**With Vision**

PRODUCT VISION

↓

Product Strategy

↓

Roadmap

↓

Features

↓

User Stories

↓

Development

**3. Real-Life Analogy**

Imagine planning a journey.

Your destination:

\"I want to reach Mumbai.\"

That is your **Vision**.

Your route:

Highway → Ahmedabad → Vadodara → Mumbai

That is your **Strategy**.

Your stops:

Fuel stop, hotel, sightseeing

That is your **Roadmap**.

Your daily driving tasks:

Take highway exit, fill fuel, check GPS

Those are your **Tasks**.

**4. Technical Explanation**

A Product Vision usually answers five questions:

  -----------------------------------------------------------------------
  **Question**           **Answer**
  ---------------------- ------------------------------------------------
  Who?                   Target users

  What?                  Product solution

  Why?                   Problem being solved

  How?                   Differentiation

  Impact?                Expected outcome
  -----------------------------------------------------------------------

**5. Product Vision Formula**

A common Product Vision template:

**For \[target customer\] who \[customer need/problem\], our product
\[solution\] that \[key benefit\]. Unlike \[current alternatives\], we
provide \[unique value\].**

Example:

For pharmacovigilance professionals who spend significant time manually
processing adverse event cases, our AI platform automates case
extraction, coding, and validation to reduce processing time while
improving regulatory compliance.

**6. Vision vs Mission vs Strategy vs Roadmap**

This is a very common interview topic.

**Product Vision**

**Question:**

**Where are we going?**

Example:

Make drug safety monitoring faster and safer through AI.

**Product Mission**

**Question:**

**Why do we exist every day?**

Example:

Help healthcare organizations identify and manage safety risks
effectively.

**Product Strategy**

**Question:**

**How will we achieve the vision?**

Example:

-   Build AI extraction capability.

-   Integrate regulatory databases.

-   Automate case processing.

**Product Roadmap**

**Question:**

**When will we deliver things?**

Example:

Q1:

Case Management

Q2:

AI Coding

Q3:

Signal Detection

Visual:

VISION

\|

↓

MISSION

\|

↓

STRATEGY

\|

↓

ROADMAP

\|

↓

FEATURES

\|

↓

USER STORIES

**7. Who Creates Product Vision?**

Usually:

**Product Manager**

Owns the vision.

**Product Owner**

Translates vision into backlog decisions.

**Business Analyst**

Provides:

-   User insights.

-   Business requirements.

-   Process understanding.

**Stakeholders**

Provide:

-   Business goals.

-   Regulatory needs.

-   Customer expectations.

**8. When is Product Vision Created?**

Usually:

**New Product**

Before development starts.

Example:

Building an AI Pharmacovigilance Platform.

**Existing Product**

When:

-   Market changes.

-   Customer needs change.

-   Technology changes.

Example:

Traditional PV software → AI-powered PV platform.

**9. Product Vision Example: Amazon**

Amazon is known for a customer-centric approach.

A simplified interpretation of Amazon\'s product thinking:

Build products and services that make customer experiences simpler,
faster, and more convenient.

The vision guides decisions like:

-   One-click buying.

-   Prime delivery.

-   Recommendation systems.

**10. Product Vision Example: Healthcare**

**Problem**

Pharmacovigilance teams process thousands of adverse event reports
manually.

Problems:

-   Slow processing.

-   Human errors.

-   High operational cost.

**Product Vision**

\"To create an intelligent pharmacovigilance platform that uses AI to
accelerate adverse event processing, improve data quality, and help
healthcare organizations ensure patient safety.\"

**11. AI Product Vision Example**

For your AI Pharmacovigilance Platform:

**Current State**

Case Received

↓

Manual Data Entry

↓

Manual Coding

↓

Medical Review

↓

Submission

Problems:

-   Takes hours.

-   Requires manual effort.

-   Error risk.

**Future State**

Case Received

↓

AI Extraction

↓

AI Coding

↓

AI Validation

↓

Human Approval

↓

Submission

**Product Vision Statement**

\"To build an AI-powered pharmacovigilance platform that transforms drug
safety operations by automating case processing, improving regulatory
compliance, and enabling faster detection of patient safety risks.\"

**12. Product Vision Canvas**

A Product Vision Canvas helps organize thinking.

Template:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

\| PRODUCT VISION \|

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Target Users:

Problem:

Current Solution:

Pain Points:

Product Solution:

Key Benefits:

Differentiation:

Business Goals:

Success Metrics:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**13. Example: AI Pharmacovigilance Vision Canvas**

**Target Users**

-   Pharmacovigilance specialists

-   Medical reviewers

-   Drug safety managers

-   Regulatory teams

**Problem**

Manual processing of adverse event cases.

**Pain Points**

-   Time-consuming data entry.

-   Coding complexity.

-   Duplicate cases.

-   Compliance pressure.

**Solution**

AI-powered case processing platform.

**Benefits**

-   Faster processing.

-   Improved accuracy.

-   Reduced workload.

**Success Metrics**

-   50% reduction in case processing time.

-   95% extraction accuracy.

-   Reduced compliance errors.

**14. Common Mistakes**

**Mistake 1:**

Writing a feature list instead of vision.

Wrong:

\"We will build dashboards, reports, AI extraction.\"

That is roadmap/features.

Correct:

\"We will improve drug safety monitoring using AI.\"

**Mistake 2:**

Making vision too technical.

Wrong:

\"Build React + Python + LLM platform.\"

Technology is not the vision.

**Mistake 3:**

Ignoring users.

Wrong:

\"We want to build the best AI system.\"

Best for whom?

**Mistake 4:**

Making vision impossible.

Wrong:

\"Eliminate all human decisions in healthcare.\"

Healthcare requires human judgment.

**15. Best Practices**

✔ Keep vision simple.

✔ Focus on customer impact.

✔ Connect to business goals.

✔ Make it inspiring.

✔ Review it regularly.

✔ Use it for prioritization decisions.

**16. Interview Questions**

**Q1. What is a Product Vision?**

**Answer:**

Product Vision describes the future state a product aims to achieve,
including the customer problem, solution direction, and expected impact.

**Q2. Difference between Product Vision and Roadmap?**

**Answer:**

Vision describes where we want to go; Roadmap describes how and when we
will get there.

**Q3. Who owns Product Vision?**

**Answer:**

Typically the Product Manager owns the vision, while collaborating with
stakeholders, Product Owners, and business teams.

**Q4. Can a Product Vision change?**

**Answer:**

Yes. Vision can evolve based on market changes, customer feedback,
technology changes, and business strategy.

**17. Mini Quiz**

**Q1.**

Product Vision answers:

A. What database will we use?

B. Where do we want the product to go?

C. Who writes code?

**Q2.**

Which comes first?

A. User Stories

B. Product Vision

C. Tasks

**Q3.**

\"Build AI-powered drug safety automation\" is:

A. Vision

B. Task

C. Bug

**Q4.**

True or False:

A Product Vision should mainly describe technical features.

**18. Practical Assignment**

Create a Product Vision for your portfolio project:

**Project:**

**AI Pharmacovigilance Platform**

Fill this:

Product Name:

Target Users:

Problem We Solve:

Current Challenges:

Our Solution:

Key Benefits:

Why Different:

Business Impact:

Success Metrics:

**19. Jira Example**

In Jira, Product Vision is usually connected through:

Vision

↓

Roadmap

↓

Epic

↓

Feature

↓

User Story

↓

Task

Example:

Vision:

\"Improve drug safety monitoring.\"

Epic:

\"AI Case Processing\"

Feature:

\"Automatic Data Extraction\"

User Story:

\"As a PV specialist, I want AI to extract adverse event data\...\"

**20. Lesson Summary**

Today we learned:

-   Product Vision is the North Star of a product.

-   It explains why a product exists.

-   Vision is different from roadmap and strategy.

-   Product Managers use vision to guide decisions.

-   Healthcare and AI products need clear user-focused vision.

**Key Takeaways**

1.  **Vision = Where are we going?**

2.  **Strategy = How will we get there?**

3.  **Roadmap = When will we deliver?**

4.  **Features and stories come after vision.**

5.  **A strong vision connects customer problems with business impact.**

**Lesson 2: Product Roadmap (Masterclass)**

**Role Perspective:** Product Manager • Product Owner • Business Analyst
• AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a Product Roadmap is.

-   Why Product Roadmaps exist.

-   Difference between Vision, Strategy, Roadmap, Backlog.

-   Types of Product Roadmaps.

-   How Product Managers create roadmaps.

-   How to create a Healthcare AI Product Roadmap.

-   Common roadmap mistakes.

-   Interview questions.

-   Practical assignment.

**1. Concept: What is a Product Roadmap?**

**Simple Definition**

A **Product Roadmap** is a high-level plan that shows:

**What product improvements we will build, why we are building them, and
the expected timeline.**

It connects:

Product Vision

\|

↓

Product Strategy

\|

↓

Product Roadmap

\|

↓

Features

\|

↓

User Stories

\|

↓

Development

**2. Why Does Product Roadmap Exist?**

Imagine a company building an AI Healthcare Platform.

Without a roadmap:

Marketing says:

\"Build patient dashboard.\"

Compliance says:

\"Build audit trail.\"

Customers say:

\"Improve reporting.\"

Engineering says:

\"Fix technical issues.\"

Everyone has different priorities.

A roadmap creates alignment.

**Without Roadmap**

Customer Request

↓

Feature

↓

Feature

↓

Feature

No clear direction

**With Roadmap**

Vision

↓

Strategy

↓

Quarterly Goals

↓

Features

↓

User Stories

↓

Release

**3. Real-Life Analogy**

Imagine building a house.

**Vision:**

\"I want a comfortable family home.\"

**Strategy:**

\"Build a modern, energy-efficient house.\"

**Roadmap:**

Year 1:

-   Foundation

-   Structure

Year 2:

-   Interior

-   Garden

Year 3:

-   Smart home automation

**Backlog:**

Specific tasks:

-   Buy cement.

-   Install wiring.

-   Paint walls.

**4. Roadmap vs Vision vs Backlog**

Very common interview question.

  ------------------------------------------------------------------------
                 **Vision**       **Roadmap**       **Backlog**
  -------------- ---------------- ----------------- ----------------------
  Question       Where are we     How will we       What work needs to be
  answered       going?           progress?         done?

  Level          Highest          Medium            Detailed

  Owner          Product Manager  Product Manager   Product Owner

  Changes        Rare             Periodic          Frequent

  Example        AI drug safety   Add AI extraction Build PDF parser
                 platform         in Q2             
  ------------------------------------------------------------------------

**5. Types of Product Roadmaps**

**Type 1: Timeline Roadmap**

Shows features by time.

Example:

Q1 Q2 Q3

Case Intake AI Coding Signal Detection

Dashboard Duplicate AI Predictive Analytics

**Advantages**

✔ Easy for executives.

**Disadvantages**

❌ Creates expectation of fixed dates.

**Type 2: Theme-Based Roadmap**

Focuses on outcomes instead of features.

Example:

Q1

Improve Case Processing Speed

Q2

Improve Data Accuracy

Q3

Improve Safety Intelligence

Advantages:

✔ More flexible.

✔ More Agile.

**Type 3: Now / Next / Later Roadmap**

Very common in Agile.

NOW

(Current Sprint/Quarter)

\- Login

\- Case Management

NEXT

(Upcoming)

\- AI Extraction

\- MedDRA Coding

LATER

\- Predictive Signals

\- Advanced Analytics

**Type 4: Outcome-Based Roadmap**

Focuses on business outcomes.

Example:

Instead of:

❌ \"Build dashboard\"

Say:

✅ \"Improve drug safety decision-making\"

**6. Agile Product Roadmap Principles**

Traditional thinking:

Plan everything for 2 years

↓

Execute exactly

Agile thinking:

Vision

↓

Short-term certainty

↓

Long-term flexibility

Agile Roadmaps should:

✔ Communicate direction.

✔ Allow changes.

✔ Focus on customer value.

✔ Avoid over-promising.

**7. Who Creates Product Roadmap?**

**Product Manager**

Owns:

-   Vision alignment.

-   Prioritization.

-   Business value.

**Product Owner**

Uses roadmap to:

-   Manage backlog.

-   Create stories.

**Business Analyst**

Supports with:

-   Requirements.

-   User needs.

-   Process analysis.

**Engineering Team**

Provides:

-   Technical feasibility.

-   Estimates.

-   Dependencies.

**8. Healthcare Example**

**Product:**

Hospital Management System

Vision:

\"Improve healthcare operations through digital automation.\"

**Roadmap:**

**Phase 1: Core Operations**

Features:

-   Patient registration.

-   Appointment booking.

-   Doctor scheduling.

**Phase 2: Clinical Intelligence**

Features:

-   Electronic medical records.

-   Analytics dashboard.

-   Decision support.

**Phase 3: AI Healthcare**

Features:

-   AI diagnosis support.

-   Predictive analytics.

-   Patient chatbot.

**9. AI Pharmacovigilance Product Roadmap**

Now let\'s create your portfolio roadmap.

**Product Vision:**

\"Transform drug safety operations using AI automation.\"

**Phase 1: Foundation (0--3 Months)**

Goal:

Digitize basic workflows.

Features:

**User Management**

-   Login

-   Roles

-   Permissions

**Case Management**

-   Create case

-   Edit case

-   Track status

**Document Upload**

-   PDF upload

-   Image upload

**Phase 2: AI Automation (3--6 Months)**

Goal:

Reduce manual processing.

Features:

**AI Data Extraction**

Extract:

-   Patient details

-   Drug information

-   Adverse events

**MedDRA Coding Assistant**

AI suggests:

-   Preferred Terms

-   System Organ Classes

**Duplicate Detection**

Identify duplicate ICSRs.

**Phase 3: Intelligence Layer (6--12 Months)**

Goal:

Enable proactive safety monitoring.

Features:

**Signal Detection**

Identify safety signals.

**Literature Screening**

AI scans publications.

**Risk Dashboard**

Predict safety trends.

**Phase 4: Enterprise Scale (12+ Months)**

Features:

-   Regulatory integrations.

-   Multi-country support.

-   Advanced AI models.

-   Audit automation.

**Roadmap Visualization**

AI Pharmacovigilance Platform

VISION:

Improve Drug Safety Using AI

2026 Q1

\|

├── Login

├── Case Management

└── Document Upload

2026 Q2

\|

├── AI Extraction

├── MedDRA Coding

└── Duplicate Detection

2026 Q3

\|

├── Signal Detection

├── Literature Screening

└── Analytics

2026 Q4

\|

├── Regulatory Integration

├── Enterprise Features

└── Advanced AI

**10. Roadmap Prioritization**

Product Managers decide:

\"What should we build first?\"

Common frameworks:

**MoSCoW**

**Must Have**

Critical features.

Example:

Case Management.

**Should Have**

Important but not urgent.

Example:

Advanced Reporting.

**Could Have**

Nice to have.

Example:

Voice assistant.

**Won\'t Have**

Not now.

Example:

Mobile app initially.

**11. Roadmap and Agile Releases**

Example:

Roadmap

↓

Release 1

↓

Sprint 1

Sprint 2

Sprint 3

↓

Release 2

Roadmap is not a detailed Sprint plan.

**12. Common Mistakes**

**Mistake 1:**

Creating a feature shopping list.

Wrong:

-   Dashboard

-   Reports

-   Chatbot

-   AI

Better:

Outcome:

\"Reduce PV processing time by 50%.\"

**Mistake 2:**

Making roadmap too detailed.

A roadmap is not a Jira backlog.

**Mistake 3:**

Treating dates as commitments.

Agile roadmaps are forecasts.

**Mistake 4:**

Ignoring customer feedback.

Roadmaps must evolve.

**13. Best Practices**

✔ Connect roadmap to business goals.

✔ Focus on outcomes.

✔ Review regularly.

✔ Keep stakeholders aligned.

✔ Communicate trade-offs.

✔ Link roadmap items to measurable KPIs.

**14. Interview Questions**

**Q1. What is a Product Roadmap?**

**Answer:**

A Product Roadmap is a strategic plan showing product direction, major
initiatives, features, and expected outcomes over time.

**Q2. Difference between Roadmap and Backlog?**

**Answer:**

Roadmap shows high-level direction and priorities; backlog contains
detailed work items needed to execute the roadmap.

**Q3. Should Agile roadmaps have fixed dates?**

**Answer:**

Dates may exist as forecasts, but Agile roadmaps should remain flexible
based on learning and changing priorities.

**Q4. Who owns the Product Roadmap?**

**Answer:**

Usually the Product Manager owns it, collaborating with stakeholders,
Product Owners, and engineering teams.

**15. Mini Quiz**

**Q1.**

Product Roadmap answers:

A. Where are we going?

B. What code should developers write today?

C. Individual tasks

**Q2.**

Which roadmap is most Agile-friendly?

A. Fixed 3-year feature list

B. Now/Next/Later roadmap

C. Developer task list

**Q3.**

Backlog is:

A. High-level product direction

B. Detailed work items

C. Business vision

**Q4.**

True or False:

A roadmap should never change.

**16. Practical Assignment**

Create a roadmap for:

**AI Pharmacovigilance Platform**

Use:

Product Goal:

Phase 1 (0-3 months):

Phase 2 (3-6 months):

Phase 3 (6-12 months):

Key Metrics:

Business Outcomes:

Also answer:

1.  Why did you choose these features first?

2.  Which features are MVP?

3.  Which features can wait?

**17. Jira Example**

Roadmap hierarchy:

Product Vision

↓

Initiatives

↓

Epics

↓

Features

↓

User Stories

↓

Tasks

Example:

Initiative:

\"AI-powered Case Processing\"

Epic:

\"AI Data Extraction\"

Story:

\"As a PV specialist, I want AI extraction\...\"

Task:

\"Develop PDF parser API\"

**18. Lesson Summary**

Today we learned:

-   Product Roadmap connects vision to execution.

-   Roadmaps focus on direction, not detailed tasks.

-   Agile roadmaps allow change.

-   Product Managers use roadmaps for alignment and prioritization.

-   AI Healthcare products require phased roadmaps.

**Key Takeaways**

1.  **Vision tells where you are going.**

2.  **Roadmap tells the journey.**

3.  **Backlog tells the detailed work.**

4.  **Agile roadmaps focus on outcomes, not only features.**

5.  **A good roadmap balances customer value, business goals, and
    technical feasibility.**

**Lesson 3: Business Case (Masterclass)**

**Role Perspective:** Product Manager • Business Analyst • Product Owner
• AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a Business Case is.

-   Why companies create Business Cases before building products.

-   Difference between Business Case, BRD, PRD, and Roadmap.

-   How to calculate business value and ROI.

-   How Product Managers justify investments.

-   How to create a Business Case for an AI Healthcare Product.

-   How to answer Business Case interview questions.

**1. Concept: What is a Business Case?**

**Simple Definition**

A **Business Case** is a document that explains:

**\"Why should the organization invest money, time, and resources into
this initiative?\"**

It answers:

-   What problem are we solving?

-   Why solve it now?

-   What benefits will we get?

-   How much will it cost?

-   Is the investment worthwhile?

**2. Why Does a Business Case Exist?**

Imagine you are a Product Manager.

You go to leadership and say:

\"I want to build an AI Pharmacovigilance Platform.\"

Leadership asks:

-   How much will it cost?

-   What problem does it solve?

-   How much money will it save?

-   What risks exist?

-   What is the expected return?

A Business Case provides these answers.

Without Business Case:

Idea

↓

Build Product

↓

Hope it succeeds

With Business Case:

Problem

↓

Analysis

↓

Investment Decision

↓

Build Product

↓

Measure Benefits

**3. Real-Life Analogy**

Imagine buying a car.

You don\'t simply say:

\"I want a new car.\"

You analyze:

Cost:

₹10 lakh

Benefits:

-   Saves travel time.

-   Better comfort.

-   Lower maintenance.

Decision:

Is the benefit worth the cost?

A Business Case works the same way for products.

**4. Technical Explanation**

A Business Case typically contains:

Business Case Document

1\. Executive Summary

2\. Business Problem

3\. Current Situation

4\. Proposed Solution

5\. Benefits

6\. Cost Analysis

7\. ROI Calculation

8\. Risks

9\. Alternatives

10\. Recommendation

11\. Success Metrics

**5. Business Case vs Other Documents**

Very important interview topic.

  -----------------------------------------------------------------------
  **Document**           **Main Question**
  ---------------------- ------------------------------------------------
  Product Vision         Where are we going?

  Business Case          Should we invest?

  BRD                    What does the business need?

  PRD                    What product should we build?

  FRD                    How should the system behave?

  User Story             What user action is needed?
  -----------------------------------------------------------------------

Visual:

Business Idea

↓

Business Case

(Should we build?)

↓

BRD

(What business needs?)

↓

PRD

(What product?)

↓

User Stories

(What work?)

**6. Who Creates a Business Case?**

Usually:

**Product Manager**

Owns:

-   Business opportunity.

-   Market analysis.

-   Expected value.

**Business Analyst**

Supports:

-   Requirements analysis.

-   Process problems.

-   Data analysis.

**Finance Team**

Provides:

-   Cost estimates.

-   ROI analysis.

**Stakeholders**

Provide:

-   Business objectives.

-   Strategic alignment.

**7. When is a Business Case Created?**

Common situations:

**New Product**

Example:

Building AI Pharmacovigilance Software.

**Major Feature Investment**

Example:

Adding AI Signal Detection.

**Digital Transformation**

Example:

Replacing manual PV workflows.

**Regulatory Requirement**

Example:

New compliance reporting system.

**8. Business Case Structure Explained**

**Section 1: Executive Summary**

A short overview.

Example:

\"The organization currently spends significant resources on manual
pharmacovigilance case processing. This proposal recommends implementing
an AI-powered platform to reduce processing time, improve accuracy, and
support regulatory compliance.\"

**Section 2: Business Problem**

Describe current pain.

Example:

Current PV process:

Case Received

↓

Manual Data Entry

↓

Manual Coding

↓

Medical Review

↓

Submission

Problems:

-   High processing time.

-   Manual errors.

-   Increased operational cost.

**Section 3: Current State Analysis**

Example:

Current:

-   10,000 cases/month.

-   Average processing time: 2 hours/case.

-   50 PV specialists required.

**Section 4: Proposed Solution**

Example:

AI Pharmacovigilance Platform:

Capabilities:

-   AI data extraction.

-   Automated coding suggestions.

-   Duplicate detection.

-   Signal analysis.

**Section 5: Benefits Analysis**

Benefits can be:

**Financial Benefits**

Example:

Reduced operational cost.

**Operational Benefits**

Example:

Faster case processing.

**Strategic Benefits**

Example:

Better patient safety monitoring.

**Compliance Benefits**

Example:

Reduced regulatory risk.

**9. ROI Calculation**

**Formula**

ROI =

(Net Benefit - Investment Cost)

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Investment Cost

× 100

Example:

Investment:

₹1 crore

Annual savings:

₹2 crore

ROI:

(2 - 1)

\-\-\-\-\-\-\-\--

1

×100

=100%

**10. AI Pharmacovigilance Business Case Example**

**Problem**

A pharmaceutical company processes:

100,000 adverse event cases/year.

Current process:

Average cost per case:

₹500

Annual cost:

100000 × 500

= ₹5 crore

**Proposed AI Solution**

Investment:

₹2 crore

Expected efficiency improvement:

40%

Savings:

5 crore × 40%

= ₹2 crore/year

**Business Outcome**

Benefits:

-   Lower operational cost.

-   Faster regulatory reporting.

-   Improved quality.

**11. Cost-Benefit Analysis**

Example:

  -----------------------------------------------------------------------
  **Cost**                   **Benefit**
  -------------------------- --------------------------------------------
  AI Software                Faster processing

  Training                   Reduced manual effort

  Integration                Better compliance

  Maintenance                Improved scalability
  -----------------------------------------------------------------------

**12. Risk Analysis**

Every Business Case must discuss risks.

Example:

**Risk:**

AI extraction errors.

**Mitigation:**

Human review before submission.

**Risk:**

Regulatory acceptance.

**Mitigation:**

Maintain audit trail and validation.

**13. Healthcare Example**

Hospital wants AI diagnosis support.

Business Case:

Problem:

Doctors spend too much time reviewing patient data.

Solution:

AI clinical decision support.

Benefits:

-   Faster diagnosis.

-   Better patient outcomes.

Risks:

-   Wrong recommendations.

Mitigation:

Human doctor approval required.

**14. AI Product Example**

AI Medical Chatbot Business Case:

Problem:

Patients need quick medical information.

Solution:

AI assistant.

Benefits:

-   24/7 availability.

-   Reduced support workload.

Risks:

-   Hallucination.

Mitigation:

-   Medical knowledge base.

-   Human escalation.

**15. Common Mistakes**

**Mistake 1:**

Only describing features.

Wrong:

\"We need AI extraction.\"

Correct:

\"AI extraction will reduce processing time by 40%.\"

**Mistake 2:**

Ignoring costs.

Every investment requires cost analysis.

**Mistake 3:**

No measurable outcomes.

Bad:

\"Improve efficiency.\"

Good:

\"Reduce processing time from 2 hours to 45 minutes.\"

**Mistake 4:**

Ignoring risks.

Especially dangerous in healthcare.

**16. Best Practices**

✔ Start with business problem.

✔ Quantify benefits.

✔ Include measurable KPIs.

✔ Consider alternatives.

✔ Include risks.

✔ Connect investment to strategy.

**17. Interview Questions**

**Q1. What is a Business Case?**

**Answer:**

A Business Case justifies an investment by explaining the problem,
proposed solution, expected benefits, costs, ROI, and risks.

**Q2. Difference between Business Case and PRD?**

**Answer:**

Business Case explains why we should build something. PRD explains what
product needs to be built.

**Q3. Who approves a Business Case?**

**Answer:**

Usually business leaders, executives, finance, and relevant
stakeholders.

**Q4. How do you measure Business Case success?**

**Answer:**

Through KPIs such as:

-   ROI.

-   Cost savings.

-   Revenue impact.

-   Customer satisfaction.

-   Operational improvement.

**18. Mini Quiz**

**Q1.**

Business Case answers:

A. Should we invest?

B. How to code?

C. How to design UI?

**Q2.**

ROI measures:

A. Business return compared to investment

B. Number of developers

C. Story Points

**Q3.**

Which comes first?

A. User Story

B. Business Case

C. Task

**Q4.**

True or False:

A Business Case should only discuss technical benefits.

**19. Practical Assignment**

Create a Business Case for:

**AI Pharmacovigilance Platform**

Fill:

Project Name:

Business Problem:

Current Process:

Current Pain Points:

Proposed Solution:

Expected Benefits:

Estimated Cost:

Expected Savings:

ROI:

Key Risks:

Success Metrics:

**20. Jira Example**

Business Case connects to Jira through:

Business Objective

↓

Initiative

↓

Epic

↓

Feature

↓

User Story

↓

Task

Example:

Business Objective:

\"Reduce PV processing cost by 40%.\"

Initiative:

\"AI Case Automation.\"

Epic:

\"AI Data Extraction.\"

Story:

\"As a PV specialist, I want automatic extraction\...\"

**21. Lesson Summary**

Today we learned:

-   Business Case explains why a product investment should happen.

-   It connects business problems to financial and strategic outcomes.

-   It is created before major investments.

-   Product Managers use Business Cases to gain approval.

-   Healthcare AI products require strong ROI and risk analysis.

**Key Takeaways**

1.  **Business Case = Why should we build it?**

2.  **It focuses on value, cost, ROI, and risk.**

3.  **Features alone do not justify investment.**

4.  **Healthcare products require benefit + safety + compliance
    analysis.**

5.  **A Product Manager must think like a business owner.**

**Lesson 4: BRD (Business Requirement Document) (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a BRD is.

-   Why businesses create BRDs.

-   Difference between BRD, PRD, and FRD.

-   Who creates and uses a BRD.

-   How Business Analysts gather business requirements.

-   Structure of a professional BRD.

-   How to write BRD requirements.

-   Healthcare and Pharmacovigilance BRD examples.

-   How BRD connects to Agile delivery.

**1. Concept: What is BRD?**

**Simple Definition**

**BRD = Business Requirement Document**

A BRD describes:

**\"What the business wants to achieve and why.\"**

It focuses on:

-   Business goals.

-   Business problems.

-   Stakeholder needs.

-   Expected outcomes.

It does **not** explain detailed technical solutions.

**Example**

A pharmaceutical company says:

\"We need to reduce manual pharmacovigilance case processing.\"

This is a **business requirement**.

The BRD explains:

-   Why this is needed.

-   Who needs it.

-   What business outcome is expected.

**2. Why Does BRD Exist?**

Imagine a company says:

\"Build a new drug safety system.\"

The development team asks:

-   Why are we building it?

-   Who will use it?

-   What problem does it solve?

-   What business value is expected?

Without a BRD:

Different teams interpret the requirement differently.

**Without BRD**

Business Idea

↓

Developer Interpretation

↓

Product Built

↓

Business Says:

\"This is not what we wanted.\"

**With BRD**

Business Need

↓

BRD

↓

Clear Understanding

↓

PRD

↓

Development

↓

Business Outcome

**3. Real-Life Analogy**

Imagine you visit a doctor.

You say:

\"I have frequent headaches.\"

This is the **business problem**.

The doctor asks:

-   When does it happen?

-   How severe?

-   Any other symptoms?

This investigation creates understanding before treatment.

A BRD does the same for a business problem.

**4. BRD vs Business Case vs PRD vs FRD**

Very important interview topic.

  -----------------------------------------------------------------------
  **Document**   **Main Question**                **Focus**
  -------------- -------------------------------- -----------------------
  Business Case  Should we invest?                Justification

  BRD            What does the business need?     Business requirements

  PRD            What product should we build?    Product features

  FRD            How should the system behave?    Functional details
  -----------------------------------------------------------------------

Visual:

Business Problem

↓

Business Case

(Should we do it?)

↓

BRD

(What does business need?)

↓

PRD

(What product solution?)

↓

FRD

(System behavior)

↓

Development

**5. Who Creates BRD?**

**Business Analyst**

Usually owns BRD creation.

Responsibilities:

-   Understand business needs.

-   Conduct stakeholder interviews.

-   Document requirements.

-   Validate requirements.

**Product Manager**

Provides:

-   Product strategy.

-   Customer problems.

-   Business goals.

**Stakeholders**

Provide:

-   Business expectations.

-   Operational needs.

-   Regulatory requirements.

**Engineering Team**

Reviews:

-   Feasibility.

-   Constraints.

**6. When is BRD Created?**

Common situations:

**New Product**

Example:

AI Pharmacovigilance Platform.

**Digital Transformation**

Example:

Moving manual PV process into AI automation.

**Process Improvement**

Example:

Reducing drug safety reporting delays.

**Regulatory Changes**

Example:

New compliance reporting requirements.

**7. BRD Structure**

A professional BRD usually contains:

Business Requirement Document

1\. Document Purpose

2\. Business Background

3\. Business Objectives

4\. Problem Statement

5\. Stakeholders

6\. Current Process

7\. Future Process

8\. Business Requirements

9\. Scope

10\. Out of Scope

11\. Assumptions

12\. Constraints

13\. Success Criteria

14\. Risks

15\. Approval

**8. BRD Section Explanation**

**1. Document Purpose**

Why does this document exist?

Example:

\"This document defines business requirements for implementing an
AI-powered pharmacovigilance case processing platform.\"

**2. Business Background**

Explain current situation.

Example:

Current:

-   Cases processed manually.

-   High workload.

-   Increasing regulatory requirements.

**3. Business Objectives**

What does business want?

Example:

-   Reduce processing time.

-   Improve data quality.

-   Increase compliance.

**4. Problem Statement**

Clearly define pain.

Example:

\"Manual adverse event case processing causes delays and increases
operational costs.\"

**5. Stakeholders**

Who is affected?

Example:

  -----------------------------------------------------------------------
  **Stakeholder**                     **Role**
  ----------------------------------- -----------------------------------
  PV Specialist                       Processes cases

  Medical Reviewer                    Validates cases

  Regulatory Team                     Submits reports

  IT Team                             Maintains system

  Management                          Tracks KPIs
  -----------------------------------------------------------------------

**6. Current Process (AS-IS)**

Example:

Case Received

↓

Manual Data Entry

↓

Manual Coding

↓

Medical Review

↓

Submission

Problems:

-   Slow.

-   Error-prone.

-   Difficult to scale.

**7. Future Process (TO-BE)**

Example:

Case Received

↓

AI Extraction

↓

AI Coding Suggestion

↓

Human Review

↓

Submission

**8. Business Requirements**

These describe what business needs.

Examples:

**BR-001**

The system should reduce manual case entry effort.

**BR-002**

The system should support regulatory audit requirements.

**BR-003**

The system should provide case status tracking.

Notice:

These are business needs, not technical details.

**9. Scope**

Defines boundaries.

**In Scope:**

✔ Case management

✔ AI extraction

✔ Audit trail

✔ Reporting

**Out of Scope:**

❌ Clinical diagnosis

❌ Autonomous regulatory submission without review

**10. Success Criteria**

How will we know success?

Example:

Before:

Case processing time:

2 hours

After:

Target:

45 minutes

**9. Healthcare Example BRD**

**Project:**

Hospital AI Assistant

**Business Problem:**

Doctors spend significant time reviewing patient records.

**Business Requirement:**

The system should provide AI-assisted patient information summarization.

**Success Metric:**

Reduce record review time by 30%.

**10. Pharmacovigilance BRD Example**

**Project:**

AI ICSR Processing Platform

**Business Objective:**

Improve adverse event case processing efficiency.

**Business Requirements:**

BR-001:

The system should allow users to upload safety documents.

BR-002:

The system should extract relevant case information automatically.

BR-003:

The system should maintain complete audit history.

**11. Agile BRD Usage**

Traditional approach:

BRD

↓

Complete Requirements

↓

Development

Agile approach:

BRD becomes a starting point:

Business Need

↓

BRD

↓

Epics

↓

Features

↓

User Stories

↓

Sprint Development

**12. BRD to User Story Example**

BRD:

\"Business needs automated case extraction.\"

↓

Epic:

AI Case Processing

↓

Feature:

Document Extraction

↓

User Story:

As a PV specialist,

I want AI to extract case information from documents,

so that I can reduce manual entry.

**13. Common Mistakes**

**Mistake 1:**

Writing technical solutions.

Wrong:

\"Use Python and GPT model.\"

BRD should say:

\"System should automate information extraction.\"

**Mistake 2:**

Missing stakeholders.

Healthcare products involve:

-   Medical teams.

-   Regulatory teams.

-   Compliance teams.

**Mistake 3:**

Unclear requirements.

Bad:

\"Improve system.\"

Good:

\"Reduce case processing time by 40%.\"

**Mistake 4:**

No scope definition.

Without scope:

Projects keep expanding.

**14. Best Practices**

✔ Focus on business outcomes.

✔ Use clear language.

✔ Define measurable goals.

✔ Identify stakeholders early.

✔ Separate requirements from solutions.

✔ Validate with business users.

**15. Interview Questions**

**Q1. What is a BRD?**

**Answer:**

A BRD captures business needs, objectives, problems, and high-level
requirements that a solution must address.

**Q2. Who prepares BRD?**

**Answer:**

Usually a Business Analyst prepares it with input from stakeholders,
Product Managers, and subject matter experts.

**Q3. Difference between BRD and PRD?**

**Answer:**

BRD focuses on business needs and objectives. PRD defines the product
solution and features required.

**Q4. Should Agile teams use BRD?**

**Answer:**

Yes. Agile teams may use lightweight BRDs to align on business goals
while allowing requirements to evolve.

**16. Mini Quiz**

**Q1.**

BRD mainly focuses on:

A. Business needs

B. Programming code

C. Database design

**Q2.**

Who usually creates BRD?

A. Business Analyst

B. Customer only

C. Developer only

**Q3.**

\"Reduce PV case processing time by 50%\" is:

A. Business Requirement

B. Technical Task

C. Bug

**Q4.**

True or False:

BRD should describe detailed coding implementation.

**17. Practical Assignment**

Create a BRD outline for your portfolio project:

**AI Pharmacovigilance Platform**

Fill:

Project Name:

Business Problem:

Business Objective:

Stakeholders:

Current Process:

Problems:

Future Process:

Business Requirements:

In Scope:

Out of Scope:

Success Metrics:

Risks:

**18. Jira Example**

BRD connects to Jira like this:

Business Objective

↓

Initiative

↓

Epic

↓

Feature

↓

User Story

↓

Acceptance Criteria

↓

Task

Example:

Business Requirement:

\"Reduce manual case processing.\"

Epic:

AI Case Automation.

Story:

\"As a PV specialist, I want AI extraction\...\"

**19. Lesson Summary**

Today we learned:

-   BRD explains business needs.

-   It answers \"What does the business need and why?\"

-   It is different from PRD and FRD.

-   Business Analysts commonly create BRDs.

-   BRDs connect business problems to Agile backlog items.

**Key Takeaways**

1.  **BRD = Business Need Document.**

2.  **It focuses on WHY and WHAT, not HOW.**

3.  **Business requirements should be measurable.**

4.  **Healthcare BRDs must include compliance and stakeholder needs.**

5.  **A good BA converts business problems into actionable
    requirements.**

**Lesson 5: PRD (Product Requirement Document) (Masterclass)**

**Role Perspective:** Product Manager • Product Owner • Business Analyst
• AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a PRD is.

-   Why Product Managers create PRDs.

-   Difference between BRD and PRD.

-   Structure of a professional PRD.

-   How to convert business problems into product requirements.

-   How PRDs work in Agile teams.

-   How to write PRD requirements for AI Healthcare products.

-   How to create a PRD for your AI Pharmacovigilance Platform.

**1. Concept: What is PRD?**

**Simple Definition**

**PRD = Product Requirement Document**

A PRD explains:

**\"What product should be built and how it should solve user
problems.\"**

It describes:

-   Product goals.

-   User needs.

-   Features.

-   User experience.

-   Functional requirements.

-   Success metrics.

Think of PRD as the bridge between:

Business Problem

↓

Product Solution

↓

Engineering Team

**2. Why Does PRD Exist?**

Imagine a Product Manager says:

\"We need AI automation for pharmacovigilance.\"

Engineering asks:

-   What exactly should AI do?

-   Which users need it?

-   What data should it process?

-   What happens after AI gives output?

-   How do we know it works?

A PRD answers these questions.

**Without PRD**

Idea

↓

Development

↓

Different Interpretations

↓

Wrong Product

**With PRD**

User Problem

↓

PRD

↓

Clear Product Requirements

↓

Design

↓

Development

↓

Testing

↓

Release

**3. Real-Life Analogy**

Imagine ordering food at a restaurant.

You tell the chef:

\"Make something good.\"

The chef doesn\'t know:

-   Vegetarian or non-vegetarian?

-   Spicy or mild?

-   Quantity?

-   Preferences?

Now imagine a detailed order:

\"Prepare vegetarian pasta, medium spicy, serves two people, no
cheese.\"

That is similar to a PRD.

It removes ambiguity.

**4. BRD vs PRD (Very Important)**

This is one of the most asked interview questions.

  -----------------------------------------------------------------------
  **BRD**                            **PRD**
  ---------------------------------- ------------------------------------
  Business Requirement Document      Product Requirement Document

  Created by BA                      Usually owned by Product Manager

  Focuses on business need           Focuses on product solution

  Explains WHY                       Explains WHAT

  High-level                         More detailed

  Business audience                  Product + Design + Engineering
  -----------------------------------------------------------------------

Example:

**BRD:**

\"Reduce pharmacovigilance case processing time.\"

**PRD:**

\"The system should automatically extract patient, drug, and adverse
event information from uploaded safety documents.\"

**5. PRD Position in Product Development**

Business Case

↓

BRD

↓

PRD

↓

Design

↓

User Stories

↓

Development

↓

Testing

↓

Release

**6. Who Creates PRD?**

**Product Manager**

Main owner.

Responsible for:

-   Product goals.

-   User problems.

-   Feature priorities.

-   Success metrics.

**Product Owner**

Uses PRD to:

-   Create backlog.

-   Write user stories.

-   Prioritize work.

**Business Analyst**

Supports:

-   Requirement analysis.

-   Process understanding.

-   Stakeholder input.

**Engineering Team**

Provides:

-   Technical feasibility.

-   Architecture feedback.

**7. When is PRD Created?**

**New Product**

Example:

Building AI Drug Safety Platform.

**New Feature**

Example:

Adding AI Signal Detection.

**Major Enhancement**

Example:

Adding regulatory integration.

**8. PRD Structure**

A professional PRD usually contains:

Product Requirement Document

1\. Document Overview

2\. Product Vision

3\. Problem Statement

4\. Goals and Objectives

5\. Target Users

6\. User Personas

7\. User Journey

8\. Features

9\. Functional Requirements

10\. Non-Functional Requirements

11\. User Stories

12\. Acceptance Criteria

13\. UX Requirements

14\. Dependencies

15\. Risks

16\. Success Metrics

17\. Release Plan

**9. PRD Section Explanation**

**1. Product Overview**

Example:

Product:

AI Pharmacovigilance Platform

Purpose:

Automate adverse event case processing using AI.

**2. Problem Statement**

Example:

Current problem:

PV specialists manually extract information from safety reports.

Challenges:

-   Time-consuming.

-   Error-prone.

-   Difficult to scale.

**3. Product Goals**

Goals should be measurable.

Example:

Goal 1:

Reduce case processing time by 50%.

Goal 2:

Improve extraction accuracy to 95%.

Goal 3:

Maintain regulatory compliance.

**4. Target Users**

Example:

**Primary Users**

-   Pharmacovigilance Specialist.

-   Medical Reviewer.

**Secondary Users**

-   Regulatory Manager.

-   Quality Auditor.

**5. User Personas**

A persona represents a typical user.

Example:

**Persona:**

Name:

Priya

Role:

PV Specialist

Experience:

5 years

Pain Points:

-   Manual data entry.

-   Repetitive work.

-   Time pressure.

Goal:

Process cases faster.

**6. User Journey**

Example:

Current Journey:

Receive PDF

↓

Read document

↓

Enter data manually

↓

Code event

↓

Review

Future Journey:

Upload PDF

↓

AI Extraction

↓

AI Suggests Coding

↓

Human Approval

↓

Submit

**7. Feature Requirements**

Example:

**Feature:**

AI Data Extraction

Description:

The system extracts relevant case information from documents.

Inputs:

-   PDF.

-   Email attachments.

-   XML files.

Outputs:

-   Patient details.

-   Drug details.

-   Adverse events.

**8. Functional Requirements**

Functional requirement describes:

What the system should do.

Example:

FR-001:

The system shall allow users to upload safety documents.

FR-002:

The system shall extract adverse event information.

FR-003:

The system shall display AI confidence scores.

**9. Non-Functional Requirements**

These describe quality attributes.

Examples:

Performance:

System should process a document within 30 seconds.

Security:

User data must be encrypted.

Availability:

System uptime should be 99.9%.

(We will cover NFR deeply in a later lesson.)

**10. User Stories in PRD**

Example:

As a PV Specialist,

I want AI to extract adverse event details,

so that I can reduce manual data entry.

**11. Acceptance Criteria**

Example:

Given:

A valid safety report PDF.

When:

The user uploads the document.

Then:

The system extracts patient, drug, and event information.

**12. AI Product PRD Example**

**Feature:**

AI Signal Detection

**User Problem:**

PV teams manually analyze large volumes of safety data.

**Product Requirement:**

The system should analyze adverse event patterns and identify potential
safety signals.

**Success Metrics:**

-   Signal detection accuracy \>90%.

-   Reduce analysis time by 60%.

**13. Healthcare PRD Example**

**Feature:**

AI Medical Summary

Requirement:

The system should summarize patient history for doctors.

Acceptance Criteria:

Given:

Patient medical records.

When:

Doctor requests summary.

Then:

System provides concise medical summary with source references.

**14. Common PRD Mistakes**

**Mistake 1:**

Writing solutions instead of problems.

Wrong:

\"Build GPT chatbot.\"

Correct:

\"Help users quickly access medical information.\"

**Mistake 2:**

No user perspective.

Wrong:

\"System needs database.\"

Correct:

\"User needs faster case search.\"

**Mistake 3:**

No success metrics.

Wrong:

\"Improve experience.\"

Correct:

\"Reduce processing time by 40%.\"

**Mistake 4:**

PRD becomes too technical.

PRD is not architecture documentation.

**15. Best Practices**

✔ Start with user problem.

✔ Define measurable outcomes.

✔ Include user journeys.

✔ Collaborate with engineering.

✔ Keep requirements clear.

✔ Update PRD as learning happens.

✔ Link PRD with Jira backlog.

**16. PRD and Agile**

Traditional:

Write PRD

↓

Build Everything

↓

Release

Agile:

PRD

↓

Epic

↓

Feature

↓

User Stories

↓

Sprint

↓

Feedback

↓

Improve

**17. Jira Example**

PRD maps to Jira hierarchy:

Product Goal

↓

Epic

↓

Feature

↓

User Story

↓

Task

↓

Test Case

Example:

PRD Feature:

AI Extraction

↓

Epic:

Case Automation

↓

Story:

\"As a PV specialist, I want automatic extraction\...\"

**18. Interview Questions**

**Q1. What is PRD?**

**Answer:**

A PRD defines what product needs to be built, including user problems,
features, requirements, and success criteria.

**Q2. Difference between BRD and PRD?**

**Answer:**

BRD defines business needs. PRD defines the product solution that
satisfies those needs.

**Q3. Who owns PRD?**

**Answer:**

Usually Product Manager owns PRD creation with input from BA, users,
designers, and engineering teams.

**Q4. Should PRD contain technical design?**

**Answer:**

Generally no. PRD explains product requirements; technical design is
owned by engineering.

**19. Mini Quiz**

**Q1.**

PRD mainly answers:

A. What product should we build?

B. How to write code?

C. How much salary developers get?

**Q2.**

Who usually owns PRD?

A. Product Manager

B. Database Administrator

C. Customer only

**Q3.**

\"System should allow PDF upload\" is:

A. Product Requirement

B. Business Vision

C. Marketing slogan

**Q4.**

True or False:

PRD should focus only on technology.

**20. Practical Assignment**

Create a PRD outline for:

**AI Pharmacovigilance Platform**

Fill:

Product Name:

Product Vision:

Problem Statement:

Target Users:

User Personas:

Product Goals:

Key Features:

Functional Requirements:

Non Functional Requirements:

User Stories:

Acceptance Criteria:

Success Metrics:

Release Plan:

**21. Lesson Summary**

Today we learned:

-   PRD defines what product should be built.

-   PRD connects business needs to development.

-   Product Managers usually own PRDs.

-   PRDs contain goals, users, features, requirements, and success
    metrics.

-   Good PRDs focus on user problems, not just features.

**Key Takeaways**

1.  **BRD = What business needs.**

2.  **PRD = What product should provide.**

3.  **PRD is the bridge between users and engineering.**

4.  **Good PRDs define problems, solutions, and measurable outcomes.**

5.  **Healthcare AI PRDs must consider safety, compliance, and human
    oversight.**

**Lesson 6: FRD (Functional Requirement Document) (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• Solution Analyst

**Learning Objectives**

By the end of this lesson, you will understand:

-   What FRD means.

-   Why Functional Requirement Documents exist.

-   Difference between BRD, PRD, FRD, and User Stories.

-   Functional vs Non-Functional Requirements.

-   How Business Analysts write FRDs.

-   How to convert business needs into system behavior.

-   Healthcare and Pharmacovigilance FRD examples.

-   How FRD connects with Agile delivery and Jira.

**1. Concept: What is FRD?**

**Simple Definition**

**FRD = Functional Requirement Document**

An FRD describes:

**\"What functions the system must perform and how users interact with
it.\"**

It explains the expected behavior of the system.

Example:

Business says:

\"We need faster pharmacovigilance case processing.\"

BRD:

Reduce manual processing time.

PRD:

Build AI case processing capability.

FRD:

The system shall allow users to upload safety reports, extract case
data, validate fields, and submit cases for review.

**2. Why Does FRD Exist?**

Imagine developers receive this requirement:

\"Build a patient management system.\"

Developer questions:

-   How do users create patients?

-   What fields are required?

-   Who can edit information?

-   What happens after saving?

-   What validations are needed?

FRD removes ambiguity.

**Without FRD**

Business Requirement

↓

Developer Interpretation

↓

Different Understanding

↓

Rework

**With FRD**

Business Need

↓

BRD

↓

PRD

↓

FRD

↓

Development

↓

Testing

**3. Real-Life Analogy**

Think about ordering a custom kitchen.

**Business Requirement:**

\"I need a modern kitchen.\"

**Product Requirement:**

\"I need cabinets, storage, and appliances.\"

**Functional Requirement:**

\"Cabinet door should open with soft-close hinges.\"

\"Drawer should support 20 kg load.\"

\"Lights should turn on automatically.\"

FRD describes the detailed behavior.

**4. BRD vs PRD vs FRD**

Very important interview topic.

  --------------------------------------------------------------------------
  **Document**   **Main Question**          **Example**
  -------------- -------------------------- --------------------------------
  Business Case  Should we invest?          AI PV platform saves cost

  BRD            What business needs?       Reduce manual case processing

  PRD            What product should do?    AI extraction feature

  FRD            How should functions       Upload PDF → extract data →
                 behave?                    validate
  --------------------------------------------------------------------------

Hierarchy:

Business Goal

↓

Business Case

↓

BRD

↓

PRD

↓

FRD

↓

User Stories

↓

Development

**5. Who Creates FRD?**

**Business Analyst**

Usually responsible.

Activities:

-   Analyze requirements.

-   Define workflows.

-   Document system behavior.

-   Work with technical teams.

**Product Manager**

Provides:

-   Product objectives.

-   Priority.

**Developers**

Review:

-   Feasibility.

-   Technical constraints.

**QA Team**

Uses FRD for:

-   Test case creation.

-   Validation.

**6. When is FRD Created?**

Common situations:

**Enterprise Software**

Example:

Hospital Information System.

**Regulatory Systems**

Example:

Pharmacovigilance database.

**Complex Applications**

Example:

AI healthcare platform.

**7. Functional Requirement Meaning**

A functional requirement describes:

What the system must do.

Usually written as:

\"The system shall\...\"

Examples:

\"The system shall allow users to login.\"

\"The system shall generate monthly safety reports.\"

\"The system shall send notification emails.\"

**8. FRD Structure**

A professional FRD contains:

Functional Requirement Document

1\. Introduction

2\. Purpose

3\. Scope

4\. System Overview

5\. User Roles

6\. Functional Requirements

7\. Business Rules

8\. Use Cases

9\. Process Flows

10\. Data Requirements

11\. Validation Rules

12\. Error Handling

13\. Assumptions

14\. Dependencies

**9. FRD Sections Explained**

**1. Introduction**

Example:

This document describes functional requirements for the AI
Pharmacovigilance Case Processing System.

**2. Scope**

Defines:

What system will do.

Example:

Included:

-   Case creation.

-   Document upload.

-   AI extraction.

Excluded:

-   Drug discovery.

-   Clinical diagnosis.

**3. User Roles**

Example:

  -----------------------------------------------------------------------
  **Role**                    **Responsibility**
  --------------------------- -------------------------------------------
  PV Specialist               Process cases

  Medical Reviewer            Validate medical information

  Admin                       Manage users

  Auditor                     Review history
  -----------------------------------------------------------------------

**4. Functional Requirements**

The heart of FRD.

**Example FR-001**

**Requirement:**

User Login

**Description:**

The system shall allow authorized users to login.

**Input:**

-   Username

-   Password

**Output:**

-   User dashboard

**Validation:**

Invalid password should show error message.

**10. Healthcare FRD Example**

**System:**

Hospital Management System

**Requirement:**

Patient Registration

**Functional Requirement:**

FR-001:

The system shall allow reception staff to create a new patient record.

**Inputs:**

-   Name

-   Date of Birth

-   Contact Number

-   Address

**Processing:**

System validates mandatory fields.

**Output:**

Patient ID generated.

**11. Pharmacovigilance FRD Example**

**Feature:**

AI Case Extraction

**FR-001:**

Document Upload

Description:

The system shall allow PV users to upload safety documents.

Input:

-   PDF

-   XML

-   Email attachments

Process:

Upload Document

↓

Document Validation

↓

AI Extraction

↓

Display Extracted Data

Output:

Extracted:

-   Patient information

-   Drug details

-   Adverse events

**12. AI Product FRD Example**

**Feature:**

AI Confidence Score

Requirement:

The system shall display confidence scores for extracted fields.

Example:

Patient Age

Extracted Value:

45 years

Confidence:

96%

**13. Functional vs Non-Functional Requirements**

Another important interview topic.

  -----------------------------------------------------------------------
  **Functional**                   **Non-Functional**
  -------------------------------- --------------------------------------
  What system does                 How system performs

  Features                         Quality attributes

  User actions                     System characteristics

  Login                            Security

  Search                           Performance
  -----------------------------------------------------------------------

Example:

Functional:

\"User can upload PDF.\"

Non-functional:

\"PDF upload should complete within 5 seconds.\"

**14. FRD and User Stories**

Traditional:

FRD

↓

Development

Agile:

FRD

↓

Epic

↓

User Story

↓

Acceptance Criteria

Example:

FRD:

\"The system shall allow case creation.\"

↓

User Story:

As a PV specialist,

I want to create a safety case,

so that I can start processing adverse events.

**15. Common Mistakes**

**Mistake 1:**

Writing vague requirements.

Bad:

\"The system should be fast.\"

Good:

\"The system should load dashboard within 3 seconds.\"

**Mistake 2:**

Missing edge cases.

Example:

What happens if:

-   File upload fails?

-   Duplicate case exists?

-   Required field missing?

**Mistake 3:**

Mixing technical design.

Wrong:

\"The system shall use PostgreSQL.\"

That belongs to technical design.

**Mistake 4:**

Ignoring users.

Requirements should describe user behavior.

**16. Best Practices**

✔ Use clear language.

✔ Number requirements.

Example:

FR-001, FR-002.

✔ Define inputs and outputs.

✔ Include validations.

✔ Review with stakeholders.

✔ Link requirements to tests.

**17. Requirement Traceability**

FRD connects:

Business Requirement

↓

Functional Requirement

↓

User Story

↓

Test Case

↓

Release

Example:

BR-001:

Reduce PV processing time.

↓

FR-010:

AI extracts case data.

↓

Story:

\"As PV specialist\...\"

↓

Test:

Verify extraction accuracy.

**18. Jira Example**

FRD requirement:

\"System shall detect duplicate cases.\"

Converted into Jira:

Epic:

AI Case Processing

Feature:

Duplicate Detection

Story:

As a PV specialist,

I want duplicate cases identified,

so that I avoid duplicate submissions.

Acceptance Criteria:

System flags matching cases.

**19. Interview Questions**

**Q1. What is FRD?**

**Answer:**

FRD defines detailed functional behavior that a system must provide to
satisfy business and product requirements.

**Q2. Difference between PRD and FRD?**

**Answer:**

PRD defines product requirements from user and business perspective. FRD
defines detailed system functions required to implement those
requirements.

**Q3. Who uses FRD?**

**Answer:**

Business Analysts, developers, testers, architects, and stakeholders use
FRD.

**Q4. What makes a good functional requirement?**

**Answer:**

It should be clear, testable, specific, measurable, and traceable.

**20. Mini Quiz**

**Q1.**

FRD focuses on:

A. System functions

B. Company vision

C. Marketing strategy

**Q2.**

\"The system shall allow users to upload documents\" is:

A. Functional Requirement

B. Business Vision

C. KPI

**Q3.**

Who commonly creates FRD?

A. Business Analyst

B. Customer only

C. Sales team

**Q4.**

True or False:

FRD should contain every line of source code.

**21. Practical Assignment**

Create FRD requirements for:

**AI Pharmacovigilance Platform**

Write at least 5 requirements:

Example format:

FR ID:

Feature:

Requirement:

User Role:

Input:

Process:

Output:

Validation Rules:

Create requirements for:

1.  Login

2.  Case Creation

3.  Document Upload

4.  AI Extraction

5.  Duplicate Detection

**22. Lesson Summary**

Today we learned:

-   FRD explains system functionality.

-   FRD translates product needs into system behavior.

-   Business Analysts commonly create FRDs.

-   FRDs help developers and testers understand expected behavior.

-   Functional requirements must be clear and testable.

**Key Takeaways**

1.  **BRD = Business needs**

2.  **PRD = Product solution**

3.  **FRD = System functions**

4.  **Functional requirements describe what the system does**

5.  **Good requirements reduce development confusion and rework**

**Lesson 7: NFR (Non-Functional Requirements) (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• Solution Analyst • AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What Non-Functional Requirements (NFRs) are.

-   Why NFRs are as important as features.

-   Difference between Functional and Non-Functional Requirements.

-   Types of NFRs.

-   How to write good NFRs.

-   Healthcare and Pharmacovigilance NFR examples.

-   AI Product NFR considerations.

-   How NFRs are tested and tracked.

-   Interview questions.

**1. Concept: What are Non-Functional Requirements (NFR)?**

**Simple Definition**

A **Non-Functional Requirement** describes:

**\"How well a system should perform its functions.\"**

Functional requirements tell:

What the system does.

NFRs tell:

How the system should behave.

Example:

Functional Requirement:

\"The system shall allow users to upload safety reports.\"

Non-Functional Requirements:

\"The system shall process uploaded reports within 10 seconds.\"

\"The system shall encrypt patient data.\"

\"The system shall support 10,000 concurrent users.\"

**2. Why Do NFRs Exist?**

Imagine building a hospital application.

The system has:

✅ Patient registration\
✅ Appointment booking\
✅ Medical records

But:

-   It crashes during peak hours.

-   Patient data is exposed.

-   Pages load slowly.

-   No backup exists.

The features work, but the product fails.

NFRs prevent this.

**Without NFR**

Build Features

↓

System Works

↓

Users Suffer

↓

Performance/Security Problems

**With NFR**

Features

\+

Performance

\+

Security

\+

Reliability

\+

Compliance

↓

Successful Product

**3. Real-Life Analogy**

Buying a car.

Functional Requirements:

-   Car should move.

-   Car should have brakes.

-   Car should have air conditioning.

Non-Functional Requirements:

-   Mileage should be 20 km/litre.

-   Safety rating should be high.

-   Should start in cold weather.

-   Should last 10 years.

The car\'s functions work, but quality determines user satisfaction.

**4. Functional vs Non-Functional Requirements**

Very Important Interview Question.

  -----------------------------------------------------------------------
  **Functional Requirement**   **Non-Functional Requirement**
  ---------------------------- ------------------------------------------
  What system does             How system performs

  Features                     Quality attributes

  User actions                 System characteristics

  Business capability          Technical quality

  Example: Login               Example: Login response \< 2 seconds
  -----------------------------------------------------------------------

Example:

**Functional:**

\"The system shall generate safety reports.\"

**Non-Functional:**

\"The system shall generate reports within 5 seconds.\"

**5. Types of Non-Functional Requirements**

Major categories:

Non-Functional Requirements

\|

\|

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

\| \| \| \|

Performance Security Reliability Scalability

Usability Compliance Availability Maintainability

**6. Performance Requirements**

**Meaning:**

How fast the system responds.

Examples:

-   Page loading time.

-   API response time.

-   Report generation speed.

Healthcare Example:

Requirement:

\"Patient medical history should load within 3 seconds.\"

Pharmacovigilance Example:

\"The system should extract data from a safety report within 30
seconds.\"

**7. Security Requirements**

**Meaning:**

Protect information from unauthorized access.

Especially critical in healthcare.

Examples:

-   Authentication.

-   Authorization.

-   Encryption.

-   Audit logs.

Pharmacovigilance Example:

Requirement:

\"Only authorized PV users can access adverse event cases.\"

Another:

\"All patient information must be encrypted during storage and
transmission.\"

**8. Scalability Requirements**

**Meaning:**

Ability to handle growth.

Example:

Today:

10,000 cases/month.

Future:

1 million cases/month.

System should support growth.

AI Platform Example:

Year 1:

100 users

↓

Year 5:

10,000 users

System should continue working.

**9. Availability Requirements**

**Meaning:**

How often system should be operational.

Usually measured as uptime.

Example:

99.9% availability.

Meaning:

System downtime should be minimal.

Healthcare Example:

Emergency systems cannot be unavailable.

**10. Reliability Requirements**

**Meaning:**

System should work consistently without failures.

Examples:

-   Data should not be lost.

-   Transactions should complete correctly.

-   Recovery should be possible.

Pharmacovigilance Example:

A submitted safety case should never disappear.

**11. Usability Requirements**

**Meaning:**

How easy the system is to use.

Examples:

-   Simple navigation.

-   Clear messages.

-   Accessibility support.

Healthcare Example:

A doctor should complete patient registration without training.

**12. Maintainability Requirements**

**Meaning:**

How easily the system can be modified and maintained.

Examples:

-   Clean architecture.

-   Documentation.

-   Modular design.

AI Product Example:

AI model should be replaceable without rebuilding the entire system.

**13. Compliance Requirements**

Extremely important in healthcare.

Examples:

Pharmacovigilance systems require:

-   Data integrity.

-   Audit trail.

-   Regulatory compliance.

Example Requirement:

\"The system shall maintain complete audit history of all case
modifications.\"

**14. AI Product Specific NFRs**

AI systems have additional requirements.

**1. AI Accuracy**

Example:

\"AI extraction accuracy should exceed 95%.\"

**2. Explainability**

Users should understand AI decisions.

Example:

AI suggests:

\"Drug X associated with headache.\"

System should show:

Why?

Based on:

-   Previous cases.

-   Literature.

-   Data patterns.

**3. Bias Control**

AI should avoid unfair outcomes.

Example:

Medical AI should perform consistently across patient groups.

**4. Human Oversight**

Important in healthcare.

Example:

AI suggestion:

↓

Human medical reviewer approval

↓

Final submission

**5. Model Monitoring**

AI performance can change.

Need:

-   Accuracy monitoring.

-   Drift detection.

-   Retraining.

**15. Pharmacovigilance Platform NFR Example**

**Product:**

AI ICSR Processing Platform

**Performance**

NFR-001:

The system shall process uploaded safety documents within 30 seconds.

**Security**

NFR-002:

The system shall encrypt patient data.

**Availability**

NFR-003:

The system shall maintain 99.9% uptime.

**Audit**

NFR-004:

The system shall maintain complete user activity logs.

**Scalability**

NFR-005:

The system shall support 50,000 cases per month.

**AI Accuracy**

NFR-006:

AI extraction accuracy should be above 95%.

**16. How to Write Good NFRs**

A good NFR should be:

**Specific**

Bad:

\"The system should be fast.\"

Good:

\"The dashboard should load within 3 seconds.\"

**Measurable**

Bad:

\"System should be secure.\"

Good:

\"All data transmission should use encryption.\"

**Testable**

QA team should verify it.

**Realistic**

Don\'t demand impossible targets.

**17. NFR and Testing**

Each NFR requires testing.

Example:

NFR:

\"System supports 10,000 users.\"

Testing:

Load testing.

NFR:

\"Response time below 2 seconds.\"

Testing:

Performance testing.

NFR:

\"Data encrypted.\"

Testing:

Security testing.

**18. Common Mistakes**

**Mistake 1:**

Ignoring NFR until the end.

Wrong:

Build first, optimize later.

**Mistake 2:**

Using vague words.

Examples:

-   Fast.

-   Secure.

-   Reliable.

Need measurable values.

**Mistake 3:**

Ignoring compliance.

Healthcare cannot ignore:

-   Privacy.

-   Audit.

-   Security.

**Mistake 4:**

Only thinking about current users.

Always consider future growth.

**19. Best Practices**

✔ Define NFRs early.

✔ Make them measurable.

✔ Review with engineering.

✔ Include regulatory needs.

✔ Link NFRs with testing.

✔ Prioritize critical quality attributes.

**20. Interview Questions**

**Q1. What are Non-Functional Requirements?**

**Answer:**

NFRs define the quality attributes and constraints of a system, such as
performance, security, scalability, and reliability.

**Q2. Difference between functional and non-functional requirements?**

**Answer:**

Functional requirements describe system capabilities; non-functional
requirements describe how effectively the system performs those
capabilities.

**Q3. Give healthcare NFR examples.**

**Answer:**

-   Patient data encryption.

-   Audit trail.

-   High availability.

-   Fast response time.

-   Regulatory compliance.

**Q4. Why are NFRs important?**

**Answer:**

Because a system can have all required features but still fail if it is
slow, insecure, unreliable, or difficult to use.

**21. Mini Quiz**

**Q1.**

\"System should allow users to create cases.\"

This is:

A. Functional Requirement

B. NFR

C. KPI

**Q2.**

\"System should respond within 2 seconds.\"

This is:

A. Functional Requirement

B. Performance NFR

C. User Story

**Q3.**

\"Audit trail for all changes\" belongs to:

A. Security/Compliance NFR

B. Feature

C. Epic

**Q4.**

True or False:

AI products need additional NFRs like explainability and monitoring.

**22. Practical Assignment**

Create NFRs for:

**AI Pharmacovigilance Platform**

Write at least 10:

Template:

NFR ID:

Category:

Requirement:

Measurement:

Testing Method:

Cover:

1.  Performance

2.  Security

3.  Scalability

4.  Availability

5.  Reliability

6.  Compliance

7.  AI Accuracy

8.  Explainability

9.  Usability

10. Maintainability

**23. Jira Example**

NFRs can become:

Epic:

System Quality Improvements

Stories:

\"As an admin,

I want audit logs,

so that compliance requirements are satisfied.\"

Acceptance Criteria:

All user actions are recorded.

**24. Lesson Summary**

Today we learned:

-   NFRs define system quality.

-   Functional requirements explain what; NFRs explain how well.

-   Healthcare systems require strong security and compliance.

-   AI systems require accuracy, explainability, and monitoring.

-   Good NFRs are measurable and testable.

**Key Takeaways**

1.  **Features make a product useful.**

2.  **NFRs make a product reliable.**

3.  **Healthcare products cannot ignore security and compliance.**

4.  **AI products need additional quality controls.**

5.  **A good BA always thinks beyond features.**

**Lesson 8: User Stories & Acceptance Criteria (Masterclass)**

**Role Perspective:** Business Analyst • Product Owner • Product Manager
• Scrum Master • AI Product Manager

**Note:** We covered User Stories and Acceptance Criteria in depth in
**Module 4 (Product Backlog Mastery)**. This lesson revisits them from
the **Agile Documentation** perspective---how they are documented,
linked to BRD/PRD/FRD, and used in Jira and Sprint Planning.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a User Story is.

-   Why Agile uses User Stories instead of large requirement documents.

-   How User Stories fit into Agile documentation.

-   Story structure.

-   INVEST principle (revision).

-   Acceptance Criteria.

-   Given--When--Then format.

-   Epic → Feature → Story hierarchy.

-   Healthcare and AI examples.

-   Jira documentation.

-   Common interview questions.

**1. What is a User Story?**

**Simple Definition**

A **User Story** is a short description of a requirement from the
user\'s perspective.

Instead of writing:

\"Implement document upload functionality using API X.\"

Agile says:

\"As a PV Specialist, I want to upload a safety report so that I can
begin case processing.\"

The focus shifts from **technology** to **user value**.

**2. Why Do User Stories Exist?**

Before Agile, teams often wrote 300-page requirement documents.

Problems:

-   Difficult to read.

-   Difficult to update.

-   Stakeholders rarely read them.

-   Developers misunderstood requirements.

Agile introduced User Stories to make requirements:

-   Small

-   Clear

-   Easy to discuss

-   Easy to prioritize

**Traditional Documentation**

Requirement Document

Page 1

Page 2

Page 3

\...

Page 300

**Agile Documentation**

Epic

↓

Feature

↓

User Story

↓

Acceptance Criteria

↓

Sprint

**3. Real-Life Analogy**

Imagine opening a restaurant.

Instead of saying:

\"Build a restaurant.\"

Break it into user needs:

Customer:

\"I want to reserve a table.\"

Chef:

\"I want to receive orders digitally.\"

Manager:

\"I want daily sales reports.\"

Each becomes a User Story.

**4. Standard User Story Format**

Every User Story follows this template:

As a \<user role\>,

I want \<goal\>,

So that \<business value\>.

**Example**

As a Pharmacovigilance Specialist,

I want to upload adverse event reports,

So that I can process new safety cases efficiently.

**5. Anatomy of a Good User Story**

Example:

As a PV Specialist,

I want AI to extract patient information,

So that I reduce manual data entry.

Breakdown:

**Role**

-   PV Specialist

**Goal**

-   Extract patient information

**Benefit**

-   Reduce manual effort

**6. Epic → Feature → User Story**

Epic

↓

Feature

↓

User Story

↓

Task

Example:

Epic:

AI Case Processing

↓

Feature:

AI Data Extraction

↓

Story 1:

Extract Patient Information

↓

Story 2:

Extract Drug Information

↓

Story 3:

Extract Adverse Event

↓

Tasks:

-   Build API

-   Create UI

-   Write tests

**7. User Stories from PRD**

PRD says:

Build AI document extraction.

Convert into stories:

Story 1

As a PV Specialist,

I want to upload safety documents,

So that AI can process them.

Story 2

As a PV Specialist,

I want extracted information displayed,

So that I can review before submission.

Story 3

As a Medical Reviewer,

I want to approve AI suggestions,

So that only validated information is submitted.

**8. INVEST Principle (Revision)**

A good User Story follows **INVEST**.

  ---------------------------------------------------------------------------
  **Letter**   **Meaning**        **Question**
  ------------ ------------------ -------------------------------------------
  I            Independent        Can it be developed separately?

  N            Negotiable         Can details be discussed?

  V            Valuable           Does it provide user value?

  E            Estimable          Can the team estimate it?

  S            Small              Can it fit into one Sprint?

  T            Testable           Can QA verify it?
  ---------------------------------------------------------------------------

Example:

Bad Story:

Build entire AI system.

Not:

-   Small

-   Estimable

Good Story:

Upload safety document.

Fits INVEST.

**9. What is Acceptance Criteria?**

Acceptance Criteria define:

**How do we know this User Story is complete?**

Without them:

Developers and testers may have different expectations.

Example:

Story:

As a PV Specialist,

I want to upload PDF reports,

So that AI can process them.

Acceptance Criteria:

-   PDF files are accepted.

-   Maximum size is 25 MB.

-   Invalid files show an error.

-   Upload success message is displayed.

-   Uploaded file is stored securely.

**10. Given--When--Then Format**

This is a standard way to write Acceptance Criteria.

Template:

Given \<initial condition\>

When \<action\>

Then \<expected result\>

Example:

Given I am logged in,

When I upload a valid PDF,

Then the system stores the document successfully.

Another example:

Given an invalid file,

When I upload it,

Then an error message is displayed.

**11. Healthcare Example**

Story:

As a Doctor,

I want to view a patient\'s medical history,

So that I can make informed treatment decisions.

Acceptance Criteria:

-   Only authorized doctors can view records.

-   Records load within 3 seconds.

-   Patient history is displayed chronologically.

-   Access is logged for audit purposes.

**12. Pharmacovigilance Example**

Story:

As a PV Specialist,

I want AI to extract patient information,

So that I reduce manual entry.

Acceptance Criteria:

Given a valid ICSR PDF,

When the document is uploaded,

Then patient name, age, gender, suspect drug, and adverse event are
extracted.

And confidence score is displayed.

And user can edit extracted values.

And audit history is recorded.

**13. AI Product Example**

Story:

As a Medical Reviewer,

I want AI to suggest MedDRA terms,

So that coding becomes faster.

Acceptance Criteria:

-   Top 5 suggestions displayed.

-   Confidence score shown.

-   Reviewer can override suggestions.

-   Selected term is saved.

-   All actions are logged.

**14. User Story Lifecycle**

Business Need

↓

BRD

↓

PRD

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

Testing

↓

Done

**15. User Stories in Jira**

Example:

**Epic**

AI Case Processing

↓

**Story**

Upload Safety Report

↓

**Acceptance Criteria**

-   Supports PDF/XML

-   Maximum size 25 MB

-   Success message shown

↓

**Tasks**

-   Backend API

-   Frontend upload page

-   Unit tests

↓

**Bug**

Fix upload timeout

**16. Common Mistakes**

**Mistake 1: Writing Technical Tasks as Stories**

❌ Bad:

Build PostgreSQL database.

✅ Better:

As a PV Specialist, I want my case data stored securely so that it is
available whenever I need it.

**Mistake 2: Missing User Value**

❌ Bad:

Add button.

✅ Better:

As a user, I want a Submit button so that I can save my case.

**Mistake 3: Stories Too Large**

❌ Build complete AI platform.

✅ Split into:

-   Login

-   Upload

-   Extraction

-   Coding

-   Review

**Mistake 4: No Acceptance Criteria**

Without Acceptance Criteria:

-   Developers guess.

-   QA guesses.

-   Stakeholders disagree.

**17. Best Practices**

✔ Always think from the user\'s perspective.

✔ Keep stories small enough for one Sprint.

✔ Write measurable Acceptance Criteria.

✔ Collaborate with developers and QA.

✔ Link every story to business value.

✔ Use consistent wording in Jira.

**18. Interview Questions**

**Q1. What is a User Story?**

**Answer:**

A User Story is a short description of a requirement written from the
end user\'s perspective, focusing on the value the feature provides.

**Q2. Why does Agile use User Stories?**

**Answer:**

They are easier to understand, encourage collaboration, support
incremental development, and focus on customer value.

**Q3. What is the difference between a User Story and Acceptance
Criteria?**

**Answer:**

A User Story explains **what** the user needs and **why**. Acceptance
Criteria define **when the story is considered complete**.

**Q4. What is the INVEST principle?**

**Answer:**

A checklist to ensure User Stories are Independent, Negotiable,
Valuable, Estimable, Small, and Testable.

**19. Mini Quiz**

**Q1.**

Which is a correctly written User Story?

A.

\"Create database.\"

B.

\"As a Doctor, I want to view patient history so that I can make better
treatment decisions.\"

C.

\"Write API.\"

**Q2.**

Acceptance Criteria should be:

A. Measurable

B. Vague

C. Optional

**Q3.**

Which format is commonly used for Acceptance Criteria?

A. SWOT

B. Given--When--Then

C. Waterfall

**Q4.**

True or False:

A User Story should explain the technical implementation in detail.

**20. Practical Assignment**

Write **5 User Stories** with Acceptance Criteria for your **AI
Pharmacovigilance Platform**.

Cover these features:

1.  Login

2.  Case Creation

3.  AI Data Extraction

4.  MedDRA Coding Assistant

5.  Duplicate Detection

Use this template:

Story ID:

User Story:

Acceptance Criteria (Given--When--Then):

Priority:

Story Points:

Dependencies:

**21. Lesson Summary**

Today we learned:

-   User Stories capture requirements from the user\'s perspective.

-   Acceptance Criteria define when a story is complete.

-   INVEST helps write high-quality stories.

-   Stories are linked to BRDs, PRDs, and Jira backlog items.

-   Good stories focus on **user value**, not technical implementation.

**Key Takeaways**

1.  **User Stories answer \"Who needs what, and why?\"**

2.  **Acceptance Criteria answer \"How do we know it\'s done?\"**

3.  **INVEST is the quality checklist for User Stories.**

4.  **Stories should be small, valuable, and testable.**

5.  **In interviews, always explain the business value behind a User
    Story, not just its format.**

**Lesson 9: Wireframes (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• UX Designer • AI Product Manager

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a Wireframe is.

-   Why wireframes are created before development.

-   Low-Fidelity vs High-Fidelity Wireframes.

-   Wireframe vs Mockup vs Prototype.

-   How Business Analysts and Product Managers use wireframes.

-   Wireframing best practices.

-   Figma basics.

-   Healthcare and AI Pharmacovigilance wireframe examples.

-   Interview questions.

**1. Concept: What is a Wireframe?**

**Simple Definition**

A **Wireframe** is a **basic blueprint or skeleton of a screen**.

It shows:

-   What elements will appear on the page.

-   Where they will be placed.

-   How users will navigate.

A wireframe **does not focus on colors, fonts, or final design**. It
focuses on **structure and functionality**.

Think of it as an architectural blueprint before building a house.

**2. Why Do Wireframes Exist?**

Imagine you ask developers to build a dashboard.

Without a wireframe:

-   The developer imagines one layout.

-   The designer imagines another.

-   The Product Manager expects something different.

-   The client imagines something else.

Result:

❌ Rework\
❌ Delays\
❌ Confusion

A wireframe ensures everyone shares the same vision before development
starts.

**Without Wireframe**

Requirement

↓

Developer builds screen

↓

Stakeholder says:

\"This isn\'t what I expected.\"

↓

Rework

**With Wireframe**

Requirement

↓

Wireframe

↓

Review

↓

Approval

↓

Development

↓

Testing

**3. Real-Life Analogy**

Imagine building a hospital.

Would engineers immediately start pouring concrete?

No.

They first create:

-   Floor plans

-   Room layouts

-   Electrical layouts

-   Plumbing plans

A wireframe is the **floor plan** of a software screen.

**4. Types of Wireframes**

**Low-Fidelity Wireframe**

A rough sketch.

Usually:

-   Black and white.

-   Boxes.

-   Placeholder text.

-   No colors.

Purpose:

Focus on **layout**, not design.

Example:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Logo

Search Box

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Dashboard

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Menu

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Patient List

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Button

**Advantages**

-   Fast to create.

-   Easy to modify.

-   Encourages discussion.

**High-Fidelity Wireframe**

Much closer to the final product.

Includes:

-   Buttons

-   Icons

-   Real labels

-   Better spacing

-   Basic branding

Still **not fully interactive**.

**5. Wireframe vs Mockup vs Prototype**

One of the most common interview questions.

  -----------------------------------------------------------------------
  **Wireframe**      **Mockup**              **Prototype**
  ------------------ ----------------------- ----------------------------
  Structure          Visual Design           Interactive Experience

  Black & White      Colors & Branding       Clickable

  Layout             Appearance              User Flow

  Early Stage        Mid Stage               Late Stage
  -----------------------------------------------------------------------

**Example**

Imagine designing a mobile banking app.

**Wireframe**

\[Logo\]

\[Balance\]

\[Transfer\]

\[History\]

**Mockup**

Same screen with:

-   Bank colors.

-   Logos.

-   Fonts.

-   Icons.

**Prototype**

You click:

Transfer

↓

Money Transfer Screen opens.

It behaves like a real application.

**6. Who Creates Wireframes?**

Usually:

**UX Designer**

Creates detailed wireframes.

**Product Manager**

Provides:

-   Product goals.

-   Features.

-   User journey.

**Business Analyst**

Provides:

-   Business requirements.

-   Process flow.

-   Field requirements.

**Stakeholders**

Review and approve.

**7. When Are Wireframes Created?**

Usually after:

Business Case

↓

BRD

↓

PRD

↓

Wireframes

↓

Development

Sometimes:

Wireframes are created during:

-   Discovery workshops.

-   Sprint planning.

-   Requirement discussions.

**8. Wireframe Components**

A typical screen contains:

-   Header

-   Navigation Menu

-   Search Bar

-   Filters

-   Tables

-   Forms

-   Buttons

-   Notifications

-   Footer

Example:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Logo Search User

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Menu

Dashboard

Cases

Reports

Settings

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Case Table

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Case ID

Patient

Drug

Status

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Create Case Button

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**9. Healthcare Example**

Hospital Dashboard

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Hospital Logo

Search Patient

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Dashboard

Appointments

Doctors

Patients

Billing

Reports

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Today\'s Appointments

Critical Patients

Emergency Alerts

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Purpose:

Everyone understands where information appears before development.

**10. AI Pharmacovigilance Wireframe**

Let\'s design your portfolio project.

**AI Pharmacovigilance Dashboard**

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Logo \| Search Cases \| Notifications \| Profile \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| Dashboard \| Cases \| AI Extraction \| Reports \| Admin \|

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Today\'s Metrics

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Open Cases: 245

Pending Review: 36

Submitted: 184

Duplicate Alerts: 5

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Recent Cases

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Case ID

Patient

Drug

Reaction

AI Confidence

Status

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

\[Create Case\]

\[Upload Document\]

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**11. AI Document Upload Screen**

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Upload Safety Report

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Drag PDF Here

OR

Browse File

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Upload

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

AI Processing\...

Extracted Fields

Patient Name

Drug

Reaction

Country

Reporter

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Approve

Reject

Edit

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

**12. Figma Basics**

**Figma** is one of the most popular wireframing and UI design tools.

As a Business Analyst or Product Manager, you don\'t need to become a UI
designer, but you should know how to:

-   Open a Figma file.

-   Review screens.

-   Add comments.

-   Suggest changes.

-   Present flows to stakeholders.

Basic workflow:

Requirements

↓

Wireframe

↓

Stakeholder Review

↓

Design

↓

Development

**13. Best Practices for Wireframes**

✔ Keep it simple.

✔ Focus on layout, not colors.

✔ Label important fields.

✔ Think from the user\'s perspective.

✔ Validate with stakeholders early.

✔ Keep navigation consistent.

✔ Show important actions clearly.

**14. Common Mistakes**

**Mistake 1**

Adding too much design detail too early.

At the wireframe stage, structure is more important than visual polish.

**Mistake 2**

Ignoring user workflow.

Ask:

-   What does the user do first?

-   What happens next?

-   Is the flow intuitive?

**Mistake 3**

Missing important actions.

For example:

If users can create a case, they should also be able to:

-   Edit

-   Delete (if allowed)

-   Search

-   Filter

-   Export

**Mistake 4**

Not validating with stakeholders.

A 30-minute review can save weeks of rework.

**15. Jira Connection**

Wireframes are often attached to Jira issues.

Example:

Epic:

AI Case Processing

↓

Story:

Upload Safety Report

↓

Attachments:

-   Wireframe

-   PRD

-   Acceptance Criteria

↓

Development

This helps developers understand the expected UI.

**16. Real Industry Example**

Imagine **Amazon** wants to redesign its checkout page.

Before coding, teams create:

-   Wireframes

-   User flow diagrams

-   Mockups

-   Clickable prototypes

Only after reviews and usability testing does development begin.

The same approach is used in healthcare applications where design
mistakes can affect patient safety.

**17. Interview Questions**

**Q1. What is a Wireframe?**

**Answer:**

A wireframe is a low-detail visual representation of a screen that
focuses on layout, structure, and functionality rather than final
design.

**Q2. Difference between Wireframe and Prototype?**

**Answer:**

A wireframe is a static layout. A prototype is interactive and simulates
user interactions.

**Q3. Why are wireframes important?**

**Answer:**

They help align stakeholders, designers, developers, and testers before
development, reducing misunderstandings and rework.

**Q4. Which tool is commonly used for wireframing?**

**Answer:**

Figma is one of the most widely used tools. Others include Miro,
Balsamiq, Adobe XD (legacy), and Sketch (mainly on macOS).

**18. Mini Quiz**

**Q1.**

Wireframes mainly focus on:

A. Layout and structure

B. Final colors

C. Marketing content

**Q2.**

Which comes first?

A. Prototype

B. Wireframe

C. Development

**Q3.**

Which tool is commonly used for wireframing?

A. Figma

B. MySQL

C. Git

**Q4.**

True or False:

A wireframe should include every animation and visual effect.

**19. Practical Assignment**

Create a **low-fidelity wireframe** (paper, PowerPoint, Figma, or even
ASCII art) for your **AI Pharmacovigilance Platform**.

Design these screens:

1.  Login

2.  Dashboard

3.  Case List

4.  Create Case

5.  AI Extraction Screen

6.  Reports Dashboard

For each screen, identify:

-   Header

-   Navigation

-   Main content

-   Primary buttons

-   Filters

-   Tables

-   Notifications

**20. Jira Example**

Epic:

AI Case Processing

↓

Story:

Upload Safety Report

↓

Attachments:

✓ Wireframe

✓ PRD

✓ Acceptance Criteria

↓

Tasks

↓

Development

**21. Lesson Summary**

Today we learned:

-   Wireframes are the blueprint of a software screen.

-   They focus on layout and user flow.

-   Wireframes come before mockups and prototypes.

-   Product Managers and Business Analysts use them to communicate
    requirements clearly.

-   Figma is a key industry tool for creating and reviewing wireframes.

**Key Takeaways**

1.  **Wireframes answer: \"What will the screen look like?\"**

2.  **They reduce misunderstandings before development begins.**

3.  **Low-fidelity wireframes are for structure; high-fidelity
    wireframes add detail.**

4.  **Wireframes are a communication tool, not just a design artifact.**

5.  **As a BA or Product Manager, you should be comfortable reading,
    reviewing, and discussing wireframes---even if you don\'t design
    them yourself.**

**Lesson 10: Use Cases & Use Case Diagrams (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Solution
Analyst • System Analyst • Product Owner

**Industry Reality**

Although Agile emphasizes User Stories, **Use Cases are still widely
used** in:

-   Banking

-   Healthcare

-   Insurance

-   ERP (SAP, Oracle)

-   Government projects

-   Pharmacovigilance Systems

-   Hospital Information Systems

As a **Business Analyst**, you should know both.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a Use Case is.

-   Why Use Cases still exist.

-   Use Case vs User Story.

-   Components of a Use Case.

-   Fully Dressed Use Case.

-   UML Use Case Diagrams.

-   Healthcare examples.

-   AI Pharmacovigilance examples.

-   Interview questions.

**1. Concept: What is a Use Case?**

**Simple Definition**

A **Use Case** describes:

**How a user interacts with a system to achieve a goal.**

Unlike a User Story (which is short), a Use Case explains the **entire
interaction step-by-step**, including alternate paths and error
handling.

Example:

User Story:

As a PV Specialist, I want to upload a safety report so that AI can
process it.

Use Case:

1.  User logs in.

2.  User selects \"Upload\".

3.  User chooses a PDF.

4.  System validates the file.

5.  AI extracts information.

6.  User reviews the extracted data.

7.  User submits the case.

8.  System saves the case.

9.  Confirmation is displayed.

**2. Why Do Use Cases Exist?**

Imagine building a Hospital Management System.

Requirement:

\"Doctor should prescribe medicine.\"

Questions:

-   What if the patient isn\'t registered?

-   What if the medicine is unavailable?

-   What if the prescription is incomplete?

-   What if the system goes offline?

A User Story cannot capture all of this.

A Use Case can.

**3. Real-Life Analogy**

Think about using an ATM.

Goal:

Withdraw cash.

Steps:

1.  Insert card.

2.  Enter PIN.

3.  Select Withdraw.

4.  Enter amount.

5.  Receive cash.

6.  Receive receipt.

If:

-   PIN is wrong

-   Insufficient balance

-   ATM is offline

Different paths occur.

That entire interaction is a **Use Case**.

**4. User Story vs Use Case**

One of the most common BA interview questions.

  -----------------------------------------------------------------------
  **User Story**           **Use Case**
  ------------------------ ----------------------------------------------
  Short                    Detailed

  Focuses on value         Focuses on interaction

  Agile                    Agile + Traditional

  Few lines                Several pages (sometimes)

  Customer-focused         System-focused

  Easy to estimate         Helps understand complex behavior
  -----------------------------------------------------------------------

Example:

**User Story**

As a patient, I want to book an appointment so that I can meet my
doctor.

**Use Case**

Includes:

-   Login

-   Search doctor

-   View schedule

-   Select slot

-   Payment

-   Confirmation

-   Cancellation

-   Error handling

**5. Components of a Use Case**

A professional Use Case contains:

Use Case

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Use Case ID

Name

Goal

Actor

Trigger

Preconditions

Main Flow

Alternative Flow

Exception Flow

Postconditions

Business Rules

Frequency

Let\'s understand each.

**6. Actor**

An **Actor** is anyone (or anything) that interacts with the system.

Examples:

Healthcare:

-   Doctor

-   Nurse

-   Patient

-   Receptionist

Pharmacovigilance:

-   PV Specialist

-   Medical Reviewer

-   QA Reviewer

-   Regulatory Manager

AI Platform:

-   AI Model

-   External API

-   Admin

**7. Goal**

The objective the actor wants to achieve.

Examples:

Doctor:

View Patient Record.

PV Specialist:

Submit Safety Case.

Admin:

Create User.

**8. Trigger**

The event that starts the Use Case.

Example:

User clicks:

\"Upload Safety Report\"

↓

Use Case begins.

**9. Preconditions**

Conditions that must already be true.

Example:

-   User logged in.

-   User has upload permission.

-   Valid project selected.

**10. Main Flow (Happy Path)**

The normal successful process.

Example:

**Use Case**

Upload Safety Report

1\. User opens upload screen.

2\. User selects PDF.

3\. User clicks Upload.

4\. System validates file.

5\. AI extracts information.

6\. System displays extracted data.

7\. User reviews.

8\. User submits.

9\. System saves the case.

10\. Confirmation displayed.

**11. Alternative Flow**

What happens if users choose a different valid path?

Example:

Instead of PDF:

User uploads XML.

System processes XML successfully.

Still valid.

**12. Exception Flow**

What happens if something goes wrong?

Example:

File larger than 25 MB.

↓

Upload rejected.

↓

Message displayed.

↓

User retries.

Another:

AI extraction fails.

↓

System asks user to enter data manually.

**13. Postconditions**

State of the system after completion.

Example:

Safety case created successfully.

Audit history updated.

Case status = Draft.

**14. Fully Dressed Use Case Example**

**Use Case ID**

UC-001

**Name**

Upload Safety Report

**Actor**

PV Specialist

**Goal**

Create new safety case.

**Preconditions**

-   User logged in.

-   Valid role assigned.

**Main Flow**

1.  Open upload page.

2.  Select PDF.

3.  Upload.

4.  AI extracts data.

5.  User reviews.

6.  Submit.

**Alternate Flow**

User uploads XML.

System processes XML.

**Exception Flow**

Invalid format.

↓

Error displayed.

**Postcondition**

Safety case saved.

**15. UML Use Case Diagram**

A Use Case Diagram provides a high-level visual view of system
interactions.

Example:

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

\| AI PV Platform \|

\|\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\|

\| (Upload Report) \|

\| (Review Case) \|

\| (Approve AI Output) \|

\| (Generate Reports) \|

+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--+

PV Specialist \-\-\-\-\-\-\--\> (Upload Report)

Medical Reviewer \-\-\-\--\> (Approve AI Output)

Admin \-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\> (Manage Users)

QA \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\> (Audit Cases)

Actors remain **outside** the system boundary. Use Cases remain
**inside**.

**16. Hospital Example**

Hospital System

Patient

↓

Book Appointment

↓

Doctor

↓

View Records

↓

Receptionist

↓

Register Patient

↓

Billing Staff

↓

Generate Invoice

**17. AI Pharmacovigilance Example**

Actors:

-   PV Specialist

-   AI Engine

-   Medical Reviewer

-   Admin

Use Cases:

Login

Upload Document

AI Extraction

MedDRA Coding

Duplicate Detection

Review Case

Submit Case

Generate Reports

Diagram:

PV Specialist \-\-\-\-\--\> Upload Document

AI Engine \-\-\-\-\-\-\-\-\--\> Extract Data

Medical Reviewer \-\--\> Review AI Output

Admin \-\-\-\-\-\-\-\-\-\-\-\--\> User Management

**18. Use Case vs Process Flow**

Many beginners confuse these.

  -----------------------------------------------------------------------
  **Use Case**                     **Process Flow**
  -------------------------------- --------------------------------------
  User interaction                 Business process

  Actor-centered                   Workflow-centered

  Goal-oriented                    Sequence-oriented

  Focuses on system behavior       Focuses on overall business flow
  -----------------------------------------------------------------------

Example:

Use Case:

Doctor updates patient record.

Process Flow:

Patient Registration → Consultation → Prescription → Billing.

**19. Use Cases in Jira**

Usually:

Epic

↓

Feature

↓

User Story

↓

Linked Use Case Document

↓

Acceptance Criteria

↓

Tasks

Large enterprise organizations often attach Use Case documents to Jira
tickets.

**20. Common Mistakes**

**Mistake 1**

Writing Use Cases like User Stories.

Use Cases require detailed steps.

**Mistake 2**

Ignoring alternate flows.

Real systems rarely have only one successful path.

**Mistake 3**

Ignoring exception handling.

Ask:

-   What if login fails?

-   What if API is unavailable?

-   What if duplicate data exists?

**Mistake 4**

Mixing technical implementation with business behavior.

Use Cases describe behavior, not source code.

**21. Best Practices**

✔ Start with the actor\'s goal.

✔ Clearly define preconditions.

✔ Write numbered steps.

✔ Include alternate and exception flows.

✔ Keep language understandable by business and technical teams.

✔ Link Use Cases to User Stories and Acceptance Criteria.

**22. Interview Questions**

**Q1. What is a Use Case?**

**Answer:**

A Use Case describes how an actor interacts with a system to achieve a
specific goal, including normal, alternate, and exception flows.

**Q2. Difference between User Story and Use Case?**

**Answer:**

A User Story is a short Agile requirement focused on user value, while a
Use Case provides a detailed description of system interactions and
possible scenarios.

**Q3. What is an Actor in a Use Case?**

**Answer:**

An actor is a person, system, or external service that interacts with
the application to achieve a goal.

**Q4. Why are Use Cases still important?**

**Answer:**

They are valuable for documenting complex workflows, regulatory systems,
and enterprise applications where detailed interaction flows are
necessary.

**23. Mini Quiz**

**Q1.**

Who or what interacts with a system in a Use Case?

A. Actor

B. Sprint

C. Epic

**Q2.**

Which document typically contains detailed interaction steps?

A. Use Case

B. Vision Statement

C. Roadmap

**Q3.**

\"Invalid password\" belongs to:

A. Main Flow

B. Exception Flow

C. Product Vision

**Q4.**

True or False:

Use Cases are obsolete and never used in Agile projects.

**24. Practical Assignment**

Create a **Fully Dressed Use Case** for your **AI Pharmacovigilance
Platform**.

Use this template:

Use Case ID:

Use Case Name:

Primary Actor:

Goal:

Trigger:

Preconditions:

Main Flow:

Alternative Flow:

Exception Flow:

Postconditions:

Business Rules:

Then draw a simple UML Use Case Diagram for these functions:

-   Login

-   Upload Safety Report

-   AI Data Extraction

-   MedDRA Coding

-   Duplicate Detection

-   Review Case

-   Submit Case

-   Generate Reports

**25. Lesson Summary**

Today we learned:

-   A Use Case describes how users interact with a system to achieve a
    goal.

-   It captures the main flow, alternate flow, and exception flow.

-   Use Cases complement User Stories, especially for complex enterprise
    applications.

-   UML Use Case Diagrams provide a visual overview of actors and system
    functions.

-   Healthcare and Pharmacovigilance projects frequently use Use Cases
    because of their complexity and regulatory requirements.

**Key Takeaways**

1.  **User Stories describe user needs; Use Cases describe user
    interactions.**

2.  **Use Cases are especially valuable for complex workflows.**

3.  **Always document alternate and exception flows.**

4.  **Use Case Diagrams help communicate scope visually.**

5.  **As a Business Analyst, mastering Use Cases is a valuable skill for
    enterprise and healthcare projects.**

**Lesson 11: Process Flow Diagrams & BPMN (Business Process Model and
Notation) (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• Solution Analyst • Process Analyst

**Industry Reality**

If there is **one documentation skill that separates an average Business
Analyst from a strong Business Analyst**, it is the ability to create
clear **Process Flow Diagrams and BPMN diagrams**.

Almost every large organization (Amazon, Microsoft, Pfizer, Novartis,
IQVIA, Accenture, Deloitte, TCS, Infosys, Cognizant, etc.) uses process
flows during requirement gathering.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What a Process Flow is.

-   Why businesses create process diagrams.

-   Flowchart symbols.

-   BPMN basics.

-   Events, Activities, Gateways.

-   Swimlanes.

-   Healthcare workflow examples.

-   AI Pharmacovigilance workflow.

-   Difference between Flowchart and BPMN.

-   Interview questions.

**1. What is a Process Flow?**

**Simple Definition**

A **Process Flow** is a visual diagram showing:

**How work moves from start to finish.**

Instead of reading long paragraphs, stakeholders can understand the
process by looking at a diagram.

Example:

Patient visits hospital

↓

Registration

↓

Doctor consultation

↓

Prescription

↓

Billing

↓

Exit

This is a simple process flow.

**2. Why Do Process Flows Exist?**

Imagine a Product Manager says:

\"Users submit safety cases.\"

Developers ask:

-   Who submits them?

-   Who reviews them?

-   What happens after approval?

-   What if AI fails?

-   Can cases be rejected?

A process flow answers these questions visually.

Without Process Flow

Requirement

↓

Different Interpretations

↓

Confusion

↓

Rework

With Process Flow

Requirement

↓

Process Diagram

↓

Shared Understanding

↓

Development

**3. Real-Life Analogy**

Imagine making tea.

Instead of writing:

1.  Boil water.

2.  Add tea leaves.

3.  Add milk.

4.  Add sugar.

5.  Filter.

6.  Serve.

You draw:

Start

↓

Boil Water

↓

Add Tea

↓

Add Milk

↓

Filter

↓

Serve

↓

End

That\'s a Process Flow.

**4. Flowchart Symbols**

Every Business Analyst should know these symbols.

  -----------------------------------------------------------------------
  **Symbol**                  **Meaning**
  --------------------------- -------------------------------------------
  ○ Oval                      Start / End

  ▭ Rectangle                 Process / Activity

  ◇ Diamond                   Decision

  → Arrow                     Flow Direction

  ⏸ Document                  Document

  ⭕ Connector                Connect different parts
  -----------------------------------------------------------------------

Example:

(Start)

↓

Login

↓

Password Correct?

↓

Yes \-\-\-\-\-\-\-\-\-\-\--→ Dashboard

↓

No

↓

Show Error

↓

Login Again

↓

End

**5. Types of Process Flows**

Common types:

-   Basic Flowchart

-   Swimlane Diagram

-   BPMN Diagram

-   Value Stream Map

-   UML Activity Diagram

Today we\'ll focus on:

-   Flowcharts

-   BPMN

**6. What is BPMN?**

BPMN stands for:

**Business Process Model and Notation**

It is an **international standard** for drawing business processes.

Unlike simple flowcharts, BPMN shows:

-   Who performs each activity.

-   Business rules.

-   Events.

-   Parallel work.

-   Exceptions.

**7. Why BPMN?**

Large companies have:

-   Multiple departments.

-   External vendors.

-   APIs.

-   AI services.

-   Compliance requirements.

Simple flowcharts become difficult to manage.

BPMN handles complex workflows.

**8. BPMN Components**

**Start Event**

Indicates where the process begins.

(Start)

**Activity**

Work performed.

\[Upload Report\]

**Gateway**

Decision point.

Is PDF Valid?

/ \\

Yes No

**End Event**

Process finishes.

(End)

**9. Swimlanes**

One of the most important BPMN concepts.

Swimlanes show **who is responsible** for each activity.

Example:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

PV Specialist

Upload Document

↓

Review AI Output

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

AI Engine

Extract Data

↓

Suggest MedDRA

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Medical Reviewer

Approve Case

↓

Submit

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Each lane represents a participant.

**10. Healthcare Example**

Hospital Appointment Process

Patient

↓

Book Appointment

↓

Reception

↓

Register Patient

↓

Doctor

↓

Consultation

↓

Lab

↓

Tests

↓

Doctor

↓

Prescription

↓

Billing

↓

Exit

Notice:

Work moves between departments.

**11. AI Pharmacovigilance Example**

This resembles the workflow used in modern PV platforms.

Start

↓

Upload Safety Report

↓

AI Extracts Information

↓

Confidence \> 95%?

↓

Yes \-\-\-\-\-\-\-\-\-\-\-\-\-\-\--→ Review

↓

No

↓

Manual Data Entry

↓

Medical Review

↓

MedDRA Coding

↓

Duplicate Detection

↓

Quality Check

↓

Submit to Authority

↓

End

**12. BPMN Version**

Using Swimlanes:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

PV Specialist

Upload PDF

↓

Review AI Output

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

AI Engine

Extract Information

↓

Suggest Coding

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Medical Reviewer

Approve

↓

Submit

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Regulatory System

Receive Submission

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

This is much easier to understand than a long document.

**13. Process Flow vs Use Case**

Common interview question.

  -----------------------------------------------------------------------
  **Process Flow**                 **Use Case**
  -------------------------------- --------------------------------------
  Business workflow                User interaction

  Shows sequence                   Shows interactions

  Good for process analysis        Good for requirement analysis

  Visual                           Detailed document
  -----------------------------------------------------------------------

Example:

Use Case:

Upload Safety Report.

Process Flow:

Entire pharmacovigilance workflow from receipt to submission.

**14. Process Flow vs BPMN**

  -----------------------------------------------------------------------
  **Flowchart**                  **BPMN**
  ------------------------------ ----------------------------------------
  Simple                         Standardized

  Small processes                Enterprise processes

  Few symbols                    Rich notation

  Good for interviews            Used in large organizations
  -----------------------------------------------------------------------

**15. Business Analyst Responsibilities**

During requirement gathering:

BA:

↓

Interviews stakeholders.

↓

Understands current process (AS-IS).

↓

Creates Process Flow.

↓

Identifies problems.

↓

Designs improved process (TO-BE).

↓

Reviews with stakeholders.

↓

Development begins.

**16. AS-IS vs TO-BE Process**

Very common in BA projects.

**AS-IS**

Current process.

Example:

Email Received

↓

Read PDF

↓

Manual Data Entry

↓

Manual Coding

↓

Submit

Problems:

-   Slow.

-   Human errors.

-   Repetitive.

**TO-BE**

Future process.

Email Received

↓

AI Extraction

↓

AI Coding

↓

Human Review

↓

Submit

Benefits:

-   Faster.

-   More accurate.

-   Lower cost.

**17. AI Product Example**

Suppose we build:

AI Medical Chatbot.

Flow:

Patient Question

↓

AI Understands Query

↓

Medical Knowledge Retrieval

↓

AI Response

↓

Doctor Review? (if required)

↓

Patient Receives Answer

This is useful during discovery sessions.

**18. Common Mistakes**

**Mistake 1**

Too many arrows.

Keep diagrams readable.

**Mistake 2**

No Start/End.

Every process should have a beginning and an end.

**Mistake 3**

Mixing departments.

Use Swimlanes.

**Mistake 4**

Ignoring exceptions.

Ask:

-   What if AI fails?

-   What if login fails?

-   What if duplicate detected?

**19. Best Practices**

✔ Start with the current process (AS-IS).

✔ Identify pain points.

✔ Design the future process (TO-BE).

✔ Use consistent symbols.

✔ Keep diagrams on one page if possible.

✔ Validate with stakeholders before development.

**20. Industry Example**

Imagine **Amazon** introducing one-click ordering.

AS-IS:

-   Add to cart

-   Review cart

-   Confirm address

-   Select payment

-   Confirm order

TO-BE:

-   Click once

-   Order placed

The process flow highlights how many steps were eliminated.

Similarly, in healthcare, AI can reduce manual pharmacovigilance
workflows.

**21. Interview Questions**

**Q1. What is a Process Flow?**

**Answer:**

A Process Flow visually represents the sequence of activities required
to complete a business process.

**Q2. What is BPMN?**

**Answer:**

Business Process Model and Notation (BPMN) is a standardized graphical
notation for modeling business processes.

**Q3. What are Swimlanes?**

**Answer:**

Swimlanes divide a process diagram by participant or department, clearly
showing who is responsible for each activity.

**Q4. What is the difference between AS-IS and TO-BE?**

**Answer:**

AS-IS represents the current process. TO-BE represents the improved
future process after optimization.

**22. Mini Quiz**

**Q1.**

What does BPMN stand for?

A. Business Process Model and Notation

B. Business Product Management Network

C. Business Planning Management Notes

**Q2.**

Which BPMN element represents a decision?

A. Rectangle

B. Diamond (Gateway)

C. Oval

**Q3.**

What is the purpose of Swimlanes?

A. Show responsibility for each activity

B. Add colors

C. Improve UI design

**Q4.**

True or False:

A Process Flow should include alternate paths and major exceptions where
relevant.

**23. Practical Assignment**

For your **AI Pharmacovigilance Platform**, create:

**1. AS-IS Process Flow**

Current manual workflow.

**2. TO-BE Process Flow**

AI-assisted workflow.

**3. BPMN Diagram**

Include Swimlanes for:

-   PV Specialist

-   AI Engine

-   Medical Reviewer

-   Regulatory Authority

**24. Jira Example**

Epic:

AI Case Processing

↓

Story:

Create BPMN workflow

↓

Tasks:

-   Document AS-IS process

-   Document TO-BE process

-   Review with stakeholders

-   Attach BPMN diagram to Jira issue

**25. Lesson Summary**

Today we learned:

-   Process Flows visualize business workflows.

-   BPMN is the industry-standard notation for complex business
    processes.

-   Swimlanes identify responsibilities across teams.

-   AS-IS and TO-BE diagrams help analyze and improve business
    operations.

-   These techniques are essential for Business Analysts working in
    healthcare, AI, and enterprise projects.

**Key Takeaways**

1.  **A Process Flow explains \"How does the business process work?\"**

2.  **BPMN is the enterprise standard for modeling business processes.**

3.  **Swimlanes make responsibilities clear.**

4.  **Always compare the current process (AS-IS) with the future process
    (TO-BE).**

5.  **Strong process modeling skills are highly valued in Business
    Analyst interviews and real projects.**

**Lesson 12: UML (Unified Modeling Language) for Business Analysts
(Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Solution
Analyst • System Analyst • AI Product Manager

**Industry Reality**

Many beginners think UML is only for software developers.

In reality, **Business Analysts in enterprise projects (Banking,
Healthcare, Insurance, ERP, Telecom)** regularly use UML to communicate
requirements clearly with architects, developers, and testers.

As a BA, you do **not** need to master all 14 UML diagrams. You should
know the few that are used most often.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What UML is.

-   Why UML exists.

-   UML vs BPMN.

-   Structural vs Behavioral diagrams.

-   The UML diagrams most important for Business Analysts.

-   Healthcare and AI examples.

-   Interview questions.

-   Which UML diagrams you should prioritize.

**1. What is UML?**

**Simple Definition**

**UML = Unified Modeling Language**

It is a **standard visual language** used to describe, design, and
communicate software systems.

Instead of writing:

\"Doctor logs in, views patient record, updates diagnosis.\"

We can draw it visually.

This makes requirements easier to understand.

**2. Why Does UML Exist?**

Imagine a Hospital Management System.

Business says:

\"Doctors should manage patient records.\"

Developers ask:

-   Which screens?

-   Which objects?

-   Which systems communicate?

-   In what order?

Writing paragraphs becomes confusing.

UML provides standard diagrams to answer these questions.

**3. Real-Life Analogy**

Imagine assembling furniture.

Without diagrams:

You read 20 pages of text.

With diagrams:

You immediately understand:

-   Which part connects where.

-   Assembly order.

-   Final structure.

UML is the instruction diagram for software systems.

**4. UML vs BPMN**

A common interview question.

  -----------------------------------------------------------------------
  **UML**                             **BPMN**
  ----------------------------------- -----------------------------------
  Models software systems             Models business processes

  Focuses on system behavior and      Focuses on business workflows
  structure                           

  Used by developers, architects, BAs Used by BAs, process analysts,
                                      operations

  Technical perspective               Business perspective
  -----------------------------------------------------------------------

Example:

BPMN:

Patient Registration Process

↓

Doctor Consultation

↓

Billing

UML:

Patient Object

Doctor Object

Appointment Object

How they interact.

**5. Types of UML Diagrams**

UML has two main categories.

UML

├── Structural Diagrams

│

└── Behavioral Diagrams

**Structural Diagrams**

Show:

What the system is made of.

Examples:

-   Class Diagram

-   Component Diagram

-   Deployment Diagram

**Behavioral Diagrams**

Show:

How the system behaves.

Examples:

-   Use Case Diagram

-   Sequence Diagram

-   Activity Diagram

-   State Diagram

**6. UML Diagrams Every Business Analyst Should Know**

You do **not** need all 14.

Focus on these:

  -----------------------------------------------------------------------
  **Diagram**                            **Importance**
  -------------------------------------- --------------------------------
  Use Case Diagram                       ⭐⭐⭐⭐⭐

  Activity Diagram                       ⭐⭐⭐⭐⭐

  Sequence Diagram                       ⭐⭐⭐⭐☆

  Class Diagram                          ⭐⭐⭐⭐☆

  State Diagram                          ⭐⭐⭐☆☆

  Component Diagram                      ⭐⭐⭐☆☆
  -----------------------------------------------------------------------

These cover most BA interview and project needs.

**7. Use Case Diagram (Revision)**

Purpose:

Shows:

-   Actors

-   System

-   User interactions

Example:

Doctor \-\-\-\-\-\--\> (View Patient Record)

Patient \-\-\-\-\--\> (Book Appointment)

Admin \-\-\-\-\-\-\--\> (Manage Users)

Best for:

Understanding system scope.

**8. Activity Diagram**

Shows:

Business workflow.

Example:

Start

↓

Login

↓

Upload Document

↓

AI Extraction

↓

Review

↓

Submit

↓

End

Very similar to a Flowchart.

Healthcare Example:

Patient Arrives

↓

Registration

↓

Doctor Consultation

↓

Prescription

↓

Billing

↓

Exit

**9. Sequence Diagram**

One of the most useful diagrams for BAs.

Purpose:

Shows:

Who talks to whom and in what order.

Example:

AI Pharmacovigilance

PV Specialist

\|

Upload PDF

\|

System

\|

Send to AI

\|

AI Engine

\|

Extract Data

\|

System

\|

Display Results

\|

PV Specialist

Sequence matters.

Real example:

User

↓

Website

↓

Authentication Service

↓

Database

↓

Website

↓

Dashboard

Every interaction happens in order.

**10. Class Diagram**

Shows:

Objects and relationships.

Example:

Hospital System

Patient

\-\-\-\-\-\-\-\-\-\-\--

PatientID

Name

Age

Gender

\-\-\-\-\-\-\-\-\-\-\--

BookAppointment()

UpdateProfile()

Doctor

Doctor

\-\-\-\-\-\-\-\-\-\-\--

DoctorID

Specialization

\-\-\-\-\-\-\-\-\-\-\--

Prescribe()

Review()

Relationship:

Patient

↓

Appointment

↓

Doctor

Developers use this extensively.

BAs should understand the basics.

**11. State Diagram**

Shows:

Different states of an object.

Example:

Safety Case

Draft

↓

Submitted

↓

Under Review

↓

Approved

↓

Closed

Another example:

Hospital Appointment

Booked

↓

Confirmed

↓

Completed

↓

Closed

Very useful in:

-   Healthcare

-   Insurance

-   Workflow systems

**12. Component Diagram**

Shows:

Major software components.

Example:

AI PV Platform

Frontend

↓

API

↓

AI Engine

↓

Database

↓

Reporting Module

Helps understand system architecture at a high level.

**13. Deployment Diagram**

Shows:

Where software runs.

Example:

User

↓

Browser

↓

Application Server

↓

Database Server

↓

Cloud Storage

Mostly used by architects and infrastructure teams, but BAs should
recognize it.

**14. UML for AI Products**

AI Medical Chatbot

Sequence Diagram:

Doctor

↓

Ask Question

↓

Web App

↓

LLM

↓

Medical Knowledge Base

↓

LLM Response

↓

Doctor

This helps define system interactions.

**15. Pharmacovigilance Example**

Safety Case Lifecycle

State Diagram

Draft

↓

AI Extraction

↓

Medical Review

↓

QA Review

↓

Submission

↓

Archived

Sequence Diagram

PV Specialist

↓

Upload PDF

↓

AI Engine

↓

Extract Data

↓

System

↓

Display Output

↓

Reviewer

↓

Approve

**16. Which UML Diagrams Should YOU Master?**

Since your goal is:

-   Business Analyst

-   Product Analyst

-   Product Manager

-   AI Product Manager

Focus in this order:

  -----------------------------------------------------------------------
  **Priority**          **Diagram**
  --------------------- -------------------------------------------------
  ⭐⭐⭐⭐⭐            Use Case Diagram

  ⭐⭐⭐⭐⭐            Activity Diagram

  ⭐⭐⭐⭐☆             Sequence Diagram

  ⭐⭐⭐⭐☆             Class Diagram (basic understanding)

  ⭐⭐⭐☆☆              State Diagram

  ⭐⭐☆☆☆               Component Diagram

  ⭐☆☆☆☆                Deployment Diagram (awareness only)
  -----------------------------------------------------------------------

You do **not** need to become a software architect.

**17. Common Mistakes**

**Mistake 1**

Trying to learn all UML diagrams.

Start with the six most useful.

**Mistake 2**

Using UML when a simple flowchart would work.

Choose the simplest diagram that communicates clearly.

**Mistake 3**

Making diagrams too detailed.

Your audience matters.

Executives need simple diagrams.

Developers may need detailed ones.

**Mistake 4**

Ignoring business context.

Always connect UML diagrams back to business requirements.

**18. Best Practices**

✔ Use UML to simplify communication.

✔ Keep diagrams clean.

✔ Label everything clearly.

✔ Review diagrams with stakeholders.

✔ Store diagrams with project documentation or link them in
Jira/Confluence.

**19. Interview Questions**

**Q1. What is UML?**

**Answer:**

UML (Unified Modeling Language) is a standardized visual language used
to model software systems and communicate requirements, design, and
behavior.

**Q2. Difference between UML and BPMN?**

**Answer:**

UML focuses on software systems and interactions. BPMN focuses on
business processes and workflows.

**Q3. Which UML diagrams should a Business Analyst know?**

**Answer:**

Use Case, Activity, Sequence, Class (basic), State, and Component
diagrams.

**Q4. What is a Sequence Diagram?**

**Answer:**

A Sequence Diagram shows the order of interactions between actors,
systems, and components over time.

**20. Mini Quiz**

**Q1.**

UML stands for:

A. Unified Modeling Language

B. Universal Management Logic

C. Unified Marketing Language

**Q2.**

Which UML diagram shows interactions over time?

A. Sequence Diagram

B. Class Diagram

C. Component Diagram

**Q3.**

Which UML diagram is best for showing the lifecycle of a Safety Case?

A. State Diagram

B. Use Case Diagram

C. Deployment Diagram

**Q4.**

True or False:

A Business Analyst needs to master all UML diagrams in equal depth.

**21. Practical Assignment**

For your **AI Pharmacovigilance Platform**, create:

**1. Use Case Diagram**

Actors:

-   PV Specialist

-   Medical Reviewer

-   Admin

**2. Activity Diagram**

Workflow:

Login → Upload → AI Extraction → Review → Submit

**3. Sequence Diagram**

Interactions between:

-   User

-   Web Application

-   AI Engine

-   Database

**4. State Diagram**

Safety Case States:

Draft → In Review → Approved → Submitted → Closed

**22. Jira Example**

Epic:

AI Case Processing

↓

Story:

Document system interactions

↓

Attachments:

-   Use Case Diagram

-   Activity Diagram

-   Sequence Diagram

↓

Development

**23. Lesson Summary**

Today we learned:

-   UML is a standard language for modeling software systems.

-   BAs should focus on a handful of practical UML diagrams rather than
    all 14.

-   Use Case Diagrams show system scope, Activity Diagrams show
    workflows, Sequence Diagrams show interactions over time, and State
    Diagrams show lifecycle changes.

-   UML complements BPMN by focusing more on the software system than
    the business process.

**Key Takeaways**

1.  **UML helps teams communicate complex systems visually.**

2.  **BPMN models business processes; UML models software systems.**

3.  **Master Use Case, Activity, Sequence, and basic Class diagrams
    first.**

4.  **Choose the right diagram for the right audience.**

5.  **For healthcare and AI products, UML is especially useful for
    documenting complex interactions.**

**Lesson 13: Decision Tables & Decision Trees (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• Solution Analyst • AI Product Manager

**Industry Reality**

One of the biggest reasons software fails is **incorrect business
rules**.

Example:

-   Who is eligible for a loan?

-   Should an insurance claim be approved?

-   Should an adverse event be reported to regulators?

Writing these rules in paragraphs causes confusion.

**Decision Tables** and **Decision Trees** solve this problem.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What Decision Tables are.

-   What Decision Trees are.

-   Why they exist.

-   Decision Table vs Decision Tree.

-   When to use each.

-   Healthcare examples.

-   Pharmacovigilance examples.

-   AI Product examples.

-   Jira integration.

-   Interview questions.

**1. What is a Decision Table?**

**Simple Definition**

A **Decision Table** is a structured table that maps:

**Conditions → Actions**

It lists all important combinations of conditions and the resulting
action.

Instead of writing long paragraphs like:

\"If the report is valid and complete, approve it. If it is valid but
incomplete, request more information\...\"

You can present it in one table.

**2. Why Do Decision Tables Exist?**

Imagine you\'re building a login system.

Rules:

-   Correct username?

-   Correct password?

-   Account active?

Without a Decision Table, developers might interpret the logic
differently.

With a Decision Table, everyone follows the same rules.

**3. Real-Life Analogy**

Imagine traffic lights.

Conditions:

-   Light is Red

-   Light is Yellow

-   Light is Green

Actions:

-   Stop

-   Prepare

-   Go

You naturally use a Decision Table every day.

**4. Structure of a Decision Table**

A Decision Table has four parts:

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Conditions

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Possible Values

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Actions

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Expected Result

**5. Login System Example**

Conditions:

-   Username Correct?

-   Password Correct?

-   Account Active?

  -------------------------------------------------------------------------------
  **Rule**   **Username**    **Password**   **Active**   **Action**
  ---------- --------------- -------------- ------------ ------------------------
  R1         Yes             Yes            Yes          Login

  R2         Yes             No             Yes          Invalid Password

  R3         No              Yes            Yes          Invalid Username

  R4         Yes             Yes            No           Account Locked
  -------------------------------------------------------------------------------

Developers and testers now have a clear reference.

**6. Healthcare Example**

Hospital Appointment

Conditions:

-   Doctor Available?

-   Patient Registered?

  --------------------------------------------------------------------------
  **Rule**   **Doctor**   **Patient**   **Action**
  ---------- ------------ ------------- ------------------------------------
  R1         Yes          Yes           Book Appointment

  R2         Yes          No            Register Patient

  R3         No           Yes           Show Another Doctor

  R4         No           No            Register + Reschedule
  --------------------------------------------------------------------------

**7. Pharmacovigilance Example**

Suppose your AI platform receives a safety report.

Conditions:

-   Report Complete?

-   Serious Event?

-   Duplicate?

  ----------------------------------------------------------------------------------------
  **Rule**   **Complete**   **Serious**   **Duplicate**   **Action**
  ---------- -------------- ------------- --------------- --------------------------------
  R1         Yes            Yes           No              Submit Immediately

  R2         Yes            No            No              Standard Review

  R3         No             Yes           No              Request Missing Information

  R4         Yes            Yes           Yes             Flag Duplicate
  ----------------------------------------------------------------------------------------

This avoids confusion among developers, testers, and business users.

**8. AI Product Example**

AI Confidence Score

Conditions:

-   Confidence \>95%

-   Medical Review Required?

  ------------------------------------------------------------------------
  **Confidence**     **Review Needed**         **Action**
  ------------------ ------------------------- ---------------------------
  Yes                No                        Auto Accept

  Yes                Yes                       Send to Reviewer

  No                 Yes                       Manual Review

  No                 No                        Re-run AI Model
  ------------------------------------------------------------------------

This is common in AI-assisted healthcare systems.

**9. What is a Decision Tree?**

**Simple Definition**

A **Decision Tree** is a visual diagram that shows how decisions are
made step by step.

Instead of a table, it uses branches.

**10. Real-Life Analogy**

Buying a train ticket.

Need Ticket?

↓

Yes

↓

Online?

↓

Yes → Website

↓

No → Ticket Counter

Each answer leads to the next decision.

**11. Login Decision Tree**

Login

\|

Username Correct?

/ \\

Yes No

\| \|

Password Correct? Show Error

/ \\

Yes No

\| \|

Account Active? Wrong Password

/ \\

Yes No

Dashboard Account Locked

Very intuitive.

**12. Healthcare Decision Tree**

Hospital Emergency

Patient Arrives

↓

Emergency?

↓

Yes \-\-\-\-\-\-\-\-\-\-\-\-\-\-\--→ Emergency Room

↓

No

↓

Appointment?

↓

Yes \-\-\-\-\-\-\-\-\-\-\--→ OPD

↓

No

↓

Registration

**13. Pharmacovigilance Decision Tree**

Safety Report

↓

Serious?

↓

Yes

↓

Expected?

↓

Yes → Standard Processing

↓

No → Expedited Reporting

↓

Not Serious

↓

Routine Processing

This mirrors real regulatory workflows.

**14. Decision Table vs Decision Tree**

Very common interview question.

  -----------------------------------------------------------------------
  **Decision Table**                **Decision Tree**
  --------------------------------- -------------------------------------
  Tabular                           Graphical

  Better for many conditions        Better for simple branching

  Easy to test                      Easy to explain

  Good for QA                       Good for business discussions

  Compact                           Visual
  -----------------------------------------------------------------------

**15. When Should You Use Each?**

Use **Decision Table** when:

-   Many rules exist.

-   Multiple combinations must be tested.

-   QA needs complete coverage.

-   Regulatory systems have strict logic.

Examples:

-   Insurance

-   Banking

-   Pharmacovigilance

-   Tax calculation

Use **Decision Tree** when:

-   Explaining logic to business users.

-   Customer journey.

-   AI decisions.

-   Medical diagnosis flow.

-   Support workflows.

**16. Decision Tables in Jira**

Example:

Epic

↓

Duplicate Detection

↓

Story

\"As a PV Specialist, I want duplicate cases detected.\"

↓

Attachment

Decision Table

↓

Development

↓

Testing

QA uses the table to create test cases.

**17. Common Mistakes**

**Mistake 1**

Missing combinations.

Always consider all valid condition combinations.

**Mistake 2**

Conflicting rules.

Each combination should produce one clear action.

**Mistake 3**

Using paragraphs instead of structured logic.

Tables are easier to review and test.

**Mistake 4**

Ignoring edge cases.

Examples:

-   Missing mandatory fields.

-   AI unavailable.

-   Duplicate reports.

-   Invalid file formats.

**18. Best Practices**

✔ Keep conditions independent.

✔ Use meaningful rule names (R1, R2\...).

✔ Validate rules with stakeholders.

✔ Keep tables updated when business rules change.

✔ Use Decision Trees to explain, Decision Tables to implement and test.

**19. Interview Questions**

**Q1. What is a Decision Table?**

**Answer:**

A Decision Table is a structured representation of business rules that
maps combinations of conditions to specific actions.

**Q2. What is a Decision Tree?**

**Answer:**

A Decision Tree is a graphical representation of decision logic where
each branch represents a possible path based on conditions.

**Q3. When should you use a Decision Table instead of a Decision Tree?**

**Answer:**

Use a Decision Table when there are many condition combinations that
need to be documented and tested systematically.

**Q4. Why are Decision Tables useful for testers?**

**Answer:**

They clearly define all rule combinations, making it easier to design
complete and consistent test cases.

**20. Mini Quiz**

**Q1.**

A Decision Table mainly represents:

A. Conditions and Actions

B. UI Screens

C. Database Design

**Q2.**

Which format is more visual?

A. Decision Tree

B. Decision Table

C. BRD

**Q3.**

Which is better for testing many business rule combinations?

A. Decision Table

B. Decision Tree

C. Product Roadmap

**Q4.**

True or False:

Decision Tables are commonly used in banking, insurance, and healthcare
systems.

**21. Practical Assignment**

For your **AI Pharmacovigilance Platform**, create:

**1. Decision Table**

Conditions:

-   Report Complete?

-   Serious?

-   Duplicate?

-   AI Confidence \>95%?

Actions:

-   Auto Process

-   Manual Review

-   Request Information

-   Reject Duplicate

**2. Decision Tree**

Create a tree for:

Upload Report

↓

Valid?

↓

AI Success?

↓

Medical Review?

↓

Submit

**22. Jira Example**

Epic:

AI Case Processing

↓

Story:

Determine processing route for uploaded safety reports

↓

Attachments:

-   Decision Table

-   Decision Tree

-   Acceptance Criteria

↓

Development

↓

QA Testing

**23. Lesson Summary**

Today we learned:

-   Decision Tables organize complex business rules into structured rows
    and columns.

-   Decision Trees visualize decision paths step by step.

-   Decision Tables are ideal for testing and regulatory logic.

-   Decision Trees are excellent for explaining business decisions.

-   Both are essential documentation techniques for Business Analysts
    working on enterprise systems.

**Key Takeaways**

1.  **Decision Tables answer: \"Given these conditions, what should the
    system do?\"**

2.  **Decision Trees answer: \"How does the decision process flow?\"**

3.  **Use Decision Tables for complex rule combinations.**

4.  **Use Decision Trees for visual communication.**

5.  **Healthcare and Pharmacovigilance systems rely heavily on clear
    decision logic due to regulatory and patient safety requirements.**

**Lesson 14: RTM (Requirements Traceability Matrix) -- Masterclass**

**Role Perspective:** Business Analyst • Product Owner • Product Manager
• QA Lead • Scrum Master

**Industry Reality**

If I had to pick **one document that makes a Business Analyst look
highly professional**, it would be the **Requirements Traceability
Matrix (RTM)**.

RTM is heavily used in:

-   Banking

-   Healthcare

-   Pharmacovigilance

-   Medical Devices

-   Insurance

-   ERP

-   Government projects

Even in Agile teams, while a formal RTM may not always exist,
**traceability still exists**---often through tools like Jira.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What RTM is.

-   Why RTM exists.

-   Forward and Backward Traceability.

-   Requirement lifecycle.

-   RTM in Agile vs Waterfall.

-   Jira traceability.

-   Healthcare and AI Pharmacovigilance examples.

-   Interview questions.

**1. What is RTM?**

**Simple Definition**

RTM stands for **Requirements Traceability Matrix**.

It is a document (or tool view) that answers one simple question:

**Can we trace every requirement from the moment it is requested until
it is delivered and tested?**

Think of RTM as a **tracking sheet** for requirements.

**2. Why Does RTM Exist?**

Imagine a stakeholder says:

\"We requested a Duplicate Detection feature. Did it get built?\"

Without RTM:

-   Business doesn\'t know.

-   Developers don\'t know.

-   Testers don\'t know.

-   Product Manager doesn\'t know.

Result:

❌ Missing features.

❌ Untested features.

❌ Production defects.

RTM solves this.

**3. Real-Life Analogy**

Imagine ordering a package online.

You can track:

Order Placed

↓

Packed

↓

Shipped

↓

Out for Delivery

↓

Delivered

RTM does the same thing for requirements.

**4. Requirement Lifecycle**

A requirement goes through several stages.

Business Need

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

↓

Deployment

↓

Release

RTM links every stage together.

**5. Structure of an RTM**

A simple RTM looks like this:

  -------------------------------------------------------------------------
  **Requirement ID** **Requirement**   **User       **Test     **Status**
                                       Story**      Case**     
  ------------------ ----------------- ------------ ---------- ------------
  BR-001             Login             US-101       TC-001     Done

  BR-002             Upload Report     US-102       TC-002     In Progress

  BR-003             AI Extraction     US-103       TC-003     Testing
  -------------------------------------------------------------------------

This allows anyone to check the progress of a requirement.

**6. Forward Traceability**

Forward Traceability answers:

**Has every requirement been implemented and tested?**

Example:

Business Requirement

↓

User Story

↓

Development

↓

Test Case

↓

Release

Purpose:

Ensure nothing is missed.

**7. Backward Traceability**

Backward Traceability answers:

**Why was this feature built?**

Example:

A tester finds Feature X.

Question:

Which requirement requested it?

Feature

↑

User Story

↑

Business Requirement

Purpose:

Prevent unnecessary features (\"gold plating\").

**8. Bi-Directional Traceability**

The best practice.

You can trace:

Forward:

Requirement → Release

Backward:

Release → Requirement

Business Requirement

↓

User Story

↓

Development

↓

Testing

↓

Release

↑

Trace Back

**9. Healthcare Example**

Hospital Management System

Requirement:

Patients should book appointments online.

RTM:

  --------------------------------------------------------------------------
  **Requirement**                **User Story**  **Test Case**  **Status**
  ------------------------------ --------------- -------------- ------------
  Book Appointment               US-201          TC-501         Passed

  Cancel Appointment             US-202          TC-502         Passed

  Reschedule                     US-203          TC-503         Failed
  --------------------------------------------------------------------------

Immediately, the team knows rescheduling still has issues.

**10. Pharmacovigilance Example**

Requirement:

AI should detect duplicate safety cases.

RTM:

  -------------------------------------------------------------------------
  **Requirement**                 **Story**    **Test Case**   **Status**
  ------------------------------- ------------ --------------- ------------
  Duplicate Detection             US-301       TC-701          Passed

  MedDRA Coding                   US-302       TC-702          Passed

  AI Extraction                   US-303       TC-703          Failed
  -------------------------------------------------------------------------

The Product Owner instantly sees which capabilities are ready for
release.

**11. RTM in Agile**

Many people ask:

\"Does Agile use RTM?\"

Answer:

**Yes---but often in a lighter form.**

Instead of one large spreadsheet, Agile teams use tools.

Example in Jira:

Epic

↓

Feature

↓

User Story

↓

Task

↓

Test Case

↓

Bug

↓

Release

Each item is linked.

This is traceability.

**12. RTM in Waterfall vs Agile**

  -----------------------------------------------------------------------
  **Waterfall**                    **Agile**
  -------------------------------- --------------------------------------
  Formal RTM document              Often tool-based

  Heavy documentation              Lightweight documentation

  Excel frequently used            Jira/Azure DevOps links

  Updated by BA                    Shared responsibility

  Phase-based                      Continuous
  -----------------------------------------------------------------------

**13. Jira Traceability**

Suppose we have:

Epic:

AI Case Processing

↓

Feature:

AI Extraction

↓

Stories:

-   Upload PDF

-   Extract Patient

-   Extract Drug

-   Detect Duplicate

↓

Tasks:

-   Backend API

-   Frontend UI

-   AI Model

↓

Test Cases

↓

Bug Fixes

↓

Release

This entire chain provides traceability.

**14. AI Product Example**

AI Medical Chatbot

Requirement:

Provide safe medical answers.

RTM:

  ------------------------------------------------------------------------
  **Requirement**                  **Story**     **Test**     **Status**
  -------------------------------- ------------- ------------ ------------
  Ask Question                     US-401        TC-901       Passed

  AI Response                      US-402        TC-902       Passed

  Safety Warning                   US-403        TC-903       Passed

  Escalate to Doctor               US-404        TC-904       Failed
  ------------------------------------------------------------------------

This helps prioritize work before release.

**15. Requirement Coverage**

RTM also helps answer:

-   Which requirements are complete?

-   Which are not started?

-   Which failed testing?

-   Which were deferred?

-   Which are in production?

Without RTM, this becomes difficult to track.

**16. Common Mistakes**

**Mistake 1**

Requirements without IDs.

Always assign unique IDs (BR-001, FR-002, US-101).

**Mistake 2**

No link between requirements and tests.

Every requirement should have at least one test case.

**Mistake 3**

Outdated RTM.

An RTM is only useful if it is kept current.

**Mistake 4**

Missing non-functional requirements.

Performance, security, and usability requirements should also be
traceable.

**17. Best Practices**

✔ Give every requirement a unique ID.

✔ Link business requirements to user stories.

✔ Link user stories to test cases.

✔ Update RTM during each sprint.

✔ Review traceability before release.

✔ Use Jira or Azure DevOps links whenever possible.

**18. Interview Questions**

**Q1. What is RTM?**

**Answer:**

RTM is a document or tool-based matrix that traces requirements
throughout the software development lifecycle to ensure every
requirement is implemented and tested.

**Q2. What is Forward Traceability?**

**Answer:**

Forward Traceability tracks requirements from definition through
implementation, testing, and release to ensure nothing is missed.

**Q3. What is Backward Traceability?**

**Answer:**

Backward Traceability traces completed features back to their original
business requirements to ensure all work has a valid business purpose.

**Q4. Does Agile use RTM?**

**Answer:**

Yes. Agile often uses tool-based traceability through Jira or Azure
DevOps instead of maintaining a large standalone RTM document.

**19. Mini Quiz**

**Q1.**

RTM stands for:

A. Requirements Traceability Matrix

B. Requirement Test Mapping

C. Release Tracking Model

**Q2.**

Forward Traceability ensures:

A. Every requirement is implemented and tested.

B. Every developer has a laptop.

C. Every sprint has two weeks.

**Q3.**

Which Agile tool commonly provides traceability?

A. Jira

B. Photoshop

C. Excel Paint

**Q4.**

True or False:

A requirement should be traceable to one or more test cases.

**20. Practical Assignment**

For your **AI Pharmacovigilance Platform**, create an RTM with these
columns:

  ----------------------------------------------------------------------------------------------
  **Requirement    **Requirement**   **Epic**   **User      **Test     **Sprint**   **Status**
  ID**                                          Story**     Case**                  
  ---------------- ----------------- ---------- ----------- ---------- ------------ ------------

  ----------------------------------------------------------------------------------------------

Include at least these requirements:

-   Login

-   Upload Safety Report

-   AI Data Extraction

-   MedDRA Coding

-   Duplicate Detection

-   Reports Dashboard

Try assigning IDs like:

-   BR-001

-   FR-001

-   US-101

-   TC-001

**21. Jira Example**

Epic:

AI Case Processing

↓

Feature:

AI Extraction

↓

Story:

Extract Patient Information

↓

Task:

Develop Extraction API

↓

Test Case:

Validate Extracted Fields

↓

Bug:

Incorrect Date Parsing

↓

Release:

Version 1.2

This chain demonstrates end-to-end traceability.

**22. Lesson Summary**

Today we learned:

-   RTM tracks requirements from business request to release.

-   Forward Traceability ensures all requirements are built and tested.

-   Backward Traceability ensures every implemented feature has a
    business reason.

-   Agile teams achieve traceability primarily through tools like Jira.

-   RTM improves visibility, testing, compliance, and release
    confidence.

**Key Takeaways**

1.  **RTM answers: \"Where is this requirement in its lifecycle?\"**

2.  **Forward Traceability prevents missing requirements.**

3.  **Backward Traceability prevents unnecessary features.**

4.  **Unique IDs and linked artifacts are the foundation of
    traceability.**

5.  **For regulated industries like healthcare and pharmacovigilance,
    RTM is often essential for audits and compliance.**

**Lesson 15: Release Notes (Masterclass)**

**Role Perspective:** Business Analyst • Product Manager • Product Owner
• Scrum Master • QA Lead • Release Manager

**Industry Reality**

Imagine your team spends **6 months building an amazing product**, but
users don\'t know:

-   What\'s new?

-   What changed?

-   Which bugs were fixed?

-   Is there anything they need to do?

That\'s why **Release Notes** exist.

Every company---from startups to Amazon, Microsoft, Google, Salesforce,
and healthcare organizations---publishes release notes for every
production release.

**Learning Objectives**

By the end of this lesson, you will understand:

-   What Release Notes are.

-   Why they exist.

-   Types of releases.

-   Structure of professional Release Notes.

-   Release Notes in Agile.

-   Jira release management.

-   Healthcare and AI examples.

-   Interview questions.

-   Industry best practices.

**1. What are Release Notes?**

**Simple Definition**

**Release Notes** are documents that explain:

**What has changed in the new version of the software.**

They answer questions like:

-   What new features were added?

-   Which bugs were fixed?

-   Are there known issues?

-   Are there breaking changes?

-   Is any user action required?

**2. Why Do Release Notes Exist?**

Imagine your bank updates its mobile app overnight.

The next morning, you notice:

-   A new UPI screen.

-   A redesigned dashboard.

-   Faster login.

Without release notes, users wonder:

\"Is this a bug or a new feature?\"

Release notes explain the changes and reduce confusion.

**3. Real-Life Analogy**

Think of buying a new smartphone.

The manufacturer releases an update:

**Version 2.5**

-   Better camera.

-   Improved battery life.

-   Fixed Bluetooth issue.

-   Security improvements.

That\'s essentially a set of release notes.

**4. Types of Releases**

Understanding release types is important for interviews.

  ------------------------------------------------------------------------
  **Release Type**     **Purpose**                     **Example**
  -------------------- ------------------------------- -------------------
  Major                Big changes                     Version 3.0

  Minor                New features                    Version 2.4

  Patch                Bug fixes                       Version 2.4.1

  Hotfix               Urgent production fix           Version 2.4.2
  ------------------------------------------------------------------------

**Major Release**

Large changes.

Example:

Hospital Management System:

-   AI diagnosis module.

-   New patient portal.

-   Complete UI redesign.

Usually involves significant testing and communication.

**Minor Release**

Smaller feature additions.

Example:

-   Export patient data to Excel.

-   Add search filters.

-   Dashboard enhancements.

**Patch Release**

Only bug fixes.

Example:

-   Login bug fixed.

-   Report download issue resolved.

-   Performance improvements.

**Hotfix**

Emergency production issue.

Example:

AI Pharmacovigilance system fails to submit safety reports to
regulators.

The team creates an urgent hotfix rather than waiting for the next
planned release.

**5. Typical Release Lifecycle**

Sprint Development

↓

Testing

↓

User Acceptance Testing (UAT)

↓

Release Approval

↓

Production Deployment

↓

Release Notes Published

**6. Who Writes Release Notes?**

Usually a collaborative effort.

  -----------------------------------------------------------------------
  **Role**                            **Responsibility**
  ----------------------------------- -----------------------------------
  Product Manager                     Feature summary

  Business Analyst                    Business impact

  QA                                  Fixed defects & known issues

  Release Manager                     Version information

  Technical Writer (if available)     Final document
  -----------------------------------------------------------------------

**7. Structure of Professional Release Notes**

A typical release note includes:

Version Number

Release Date

Overview

New Features

Enhancements

Bug Fixes

Known Issues

Breaking Changes

Deployment Notes

Contact Information

**8. Example Release Notes**

**AI Pharmacovigilance Platform**

**Version:** 2.1.0

**Release Date:** 15 July 2026

**Overview**

This release improves case processing efficiency and introduces
AI-assisted MedDRA coding.

**New Features**

-   AI MedDRA coding suggestions.

-   Duplicate detection dashboard.

-   Bulk case upload.

**Enhancements**

-   Faster document upload.

-   Improved dashboard performance.

-   Better search filters.

**Bug Fixes**

-   Fixed duplicate case count.

-   Corrected PDF upload validation.

-   Fixed report export issue.

**Known Issues**

-   AI confidence score may take longer for very large files.

-   Dark mode is not yet available.

**Breaking Changes**

-   Old CSV upload format is no longer supported.

-   API version v1 is deprecated.

**9. Healthcare Example**

Hospital System

Version 4.0

**New Features**

-   Online appointment booking.

-   Telemedicine consultation.

-   Digital prescriptions.

**Bug Fixes**

-   Billing calculation corrected.

-   SMS reminder issue fixed.

**Known Issues**

-   Pharmacy inventory sync may be delayed during peak hours.

**10. AI Product Example**

AI Medical Chatbot

Release 3.2

**New**

-   Multi-language support.

-   Drug interaction detection.

-   Improved response accuracy.

**Fixed**

-   Slow response issue.

-   Login timeout.

-   Mobile display problems.

**11. Jira and Release Notes**

In Jira, release notes are often generated from completed issues linked
to a version.

Example:

Version 2.1

↓

Completed Stories

↓

Resolved Bugs

↓

Release Candidate

↓

Production

↓

Release Notes

Many organizations automate this process using Jira integrations.

**12. Release Notes vs Changelog**

A common interview question.

  -----------------------------------------------------------------------
  **Release Notes**                   **Changelog**
  ----------------------------------- -----------------------------------
  Written for users and business      Written for developers and
  stakeholders                        technical teams

  Focuses on business impact          Focuses on technical changes

  Easy to understand                  May include detailed technical
                                      commits
  -----------------------------------------------------------------------

Example:

**Release Note**

Added AI Duplicate Detection.

**Changelog**

Refactored duplicate_detection_service.py and updated API endpoint
/v2/cases/check-duplicate.

**13. Common Mistakes**

**Mistake 1**

Using technical jargon.

Instead of:

Refactored API authentication module.

Write:

Improved login security and authentication.

**Mistake 2**

Listing every tiny code change.

Focus on changes that matter to users and stakeholders.

**Mistake 3**

Forgetting known issues.

Being transparent builds trust and helps support teams prepare.

**Mistake 4**

Not mentioning breaking changes.

If users must update integrations or change behavior, call it out
clearly.

**14. Best Practices**

✔ Write for the intended audience.

✔ Group similar changes together.

✔ Highlight major new features first.

✔ Mention known limitations honestly.

✔ Include version number and release date.

✔ Keep language concise and easy to understand.

✔ Link to user guides or documentation when necessary.

**15. Release Notes in Agile**

In Scrum:

-   Features are completed during sprints.

-   Releases may happen every sprint or after multiple sprints.

-   Release Notes summarize everything delivered in that release.

Example:

Sprint 1:

-   Login

Sprint 2:

-   Dashboard

Sprint 3:

-   Reports

Release 1.0:

-   Login

-   Dashboard

-   Reports

One release note can cover work from multiple sprints.

**16. Interview Questions**

**Q1. What are Release Notes?**

**Answer:**

Release Notes are documents that communicate new features, improvements,
bug fixes, known issues, and other important information included in a
software release.

**Q2. Who prepares Release Notes?**

**Answer:**

Typically, Product Managers, Business Analysts, QA teams, Release
Managers, and Technical Writers collaborate to create them.

**Q3. Difference between Release Notes and a Changelog?**

**Answer:**

Release Notes are business- and user-focused, while a changelog is more
technical and often intended for developers.

**Q4. Why are Release Notes important?**

**Answer:**

They improve communication, reduce confusion, help users understand
changes, and support adoption of new features.

**17. Mini Quiz**

**Q1.**

Which release usually introduces major new capabilities?

A. Major Release

B. Patch

C. Hotfix

**Q2.**

A production-critical bug is normally addressed by:

A. Hotfix

B. Minor Release

C. Major Release

**Q3.**

Who is the primary audience for Release Notes?

A. Users and business stakeholders

B. Database servers

C. Compilers

**Q4.**

True or False:

Release Notes should clearly mention known issues and breaking changes
when applicable.

**18. Practical Assignment**

Write Release Notes for **Version 1.0** of your **AI Pharmacovigilance
Platform**.

Include:

-   Version Number

-   Release Date

-   Overview

-   New Features

-   Enhancements

-   Bug Fixes

-   Known Issues

-   Breaking Changes (if any)

Suggested features:

-   Login

-   Dashboard

-   AI Data Extraction

-   MedDRA Coding

-   Duplicate Detection

-   Reports

**19. Jira Example**

Version 1.0

↓

Completed Epics

↓

Completed Stories

↓

Resolved Bugs

↓

Release Approval

↓

Production Deployment

↓

Release Notes

**20. Lesson Summary**

Today we learned:

-   Release Notes communicate software changes to users and
    stakeholders.

-   They typically include new features, enhancements, bug fixes, known
    issues, and breaking changes.

-   Different release types (Major, Minor, Patch, Hotfix) serve
    different purposes.

-   Good Release Notes improve transparency, adoption, and support.

-   Jira and other Agile tools often help generate Release Notes from
    completed work.

**Key Takeaways**

1.  **Release Notes explain what changed and why it matters.**

2.  **Write for users and business stakeholders, not just developers.**

3.  **Always include version, date, major changes, and known issues.**

4.  **Be clear about breaking changes and required user actions.**

5.  **Well-written Release Notes are an important part of professional
    Agile delivery.**
