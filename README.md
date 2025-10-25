# Requirement-Analysis-in-Software-Development.
##📌 Introduction

This repository provides a structured documentation of the Requirement Analysis phase for a Booking Management System project. It serves as a foundational step in the Software Development Lifecycle (SDLC), showcasing how system requirements are gathered, analyzed, modeled, and validated before development begins.

The goal of this repository is to create a clear, organized, and traceable reference that demonstrates best practices in requirement documentation. Each task within this phase will contribute to understanding how requirements evolve from initial ideas into detailed system specifications.

---

What is Requirement Analysis?

Requirement Analysis is the process of identifying, understanding, documenting, and validating what a software system must do to meet user and business needs. It helps teams clearly define what the software should achieve before the development stage begins.

This process involves working closely with stakeholders to gather information about goals, functions, and constraints. The outcomes are written requirements, diagrams, and models that guide the design and implementation phases.

🔍 Importance in the Software Development Lifecycle (SDLC)

Requirement Analysis is a critical step in building successful software because it:

Ensures a shared understanding between clients, users, and developers.

Supports better project planning and accurate effort estimation.

Reduces conflicts and misunderstandings during later stages.

Provides a blueprint for system design, development, and testing.

Increases the likelihood of delivering a product that meets real needs.

---

🔍 Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities:

• Requirement Gathering

Collecting information from stakeholders using interviews, questionnaires, research, and observations.

• Requirement Elicitation

Exploring and uncovering actual needs, expectations, and hidden requirements through active engagement techniques.

• Requirement Documentation

Organizing requirements into clear, structured artifacts such as SRS documents, user stories, and system diagrams.

• Requirement Analysis and Modeling
Reviewing and refining requirements while visualizing the system using tools like use case diagrams or flowcharts.

• Requirement Validation
Confirming that requirements are correct, complete, and truly aligned with business goals.

---

🧩 Types of Requirements

Software requirements are categorized into two major types that work together to shape how a system behaves and performs.

✅ Functional Requirements

These describe what the system should do. They define specific features, operations, and behaviors of the software to support user goals.

Examples for the Booking Management System:

• Users can search for available rooms or services
• Customers can create a booking and receive confirmation
• Admin can approve, modify, or cancel bookings
• System should store and retrieve booking history
• Payment processing must record successful transactions

✅ Non-Functional Requirements

These define how the system should perform. They focus on quality attributes such as speed, security, and usability.

Examples for the Booking Management System:

• System should load pages within 3 seconds for optimal user experience
• Booking data must be securely stored and protected from unauthorized access
• The interface should be easy to navigate for all customer types
• System must support high availability during peak booking periods
• Users should be able to access the system on both mobile and desktop

---

🎭 Use Case Diagrams

Use Case Diagrams visually show how actors interact with the system. They help teams understand user goals and clarify system boundaries early in development.

Benefits of Use Case Diagrams

• Provide clear communication between stakeholders and developers
• Reveal required system interactions and missing features
• Help identify actors, user goals, and dependencies
• Support better planning and validation of requirements

📌 Booking Management System Use Case Diagram

Actors and primary use cases include:

Actors
• Customer
• Admin
• Payment Service

Use Cases
• Search bookings
• Create booking
• Manage booking (edit/cancel)
• Make payment
• View booking history
• Confirm booking

---

Acceptance Criteria

Acceptance Criteria define the specific conditions that must be met for a feature or requirement to be considered complete, functional, and acceptable to stakeholders. They act as a clear checklist that guides development, testing, and validation — making sure the delivered feature meets user expectations and business goals.

🔍 Importance in Requirement Analysis

During Requirement Analysis, Acceptance Criteria help teams:

Clearly understand what “done” means for each feature.

Ensure alignment between stakeholders, developers, and testers.

Support test case creation and quality validation.

Reduce misunderstandings and rework during development.

Improve overall user satisfaction by ensuring features behave as expected.

By defining Acceptance Criteria early, the team ensures that every feature is measurable, testable, and traceable back to user needs.

💡 Example: Checkout Feature (Booking Management System)

The Checkout feature is considered complete when all the following conditions are met:

User can review booking details before making payment.

System provides secure payment options (e.g., card, wallet, transfer).

Successful payment automatically creates a confirmed booking record.

Failed payment does not create a booking, and an error message is displayed.

A success confirmation message appears instantly after payment.

User receives a booking confirmation notification or email.
