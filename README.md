<img width="504" height="628" alt="image" src="https://github.com/user-attachments/assets/d17457c5-8419-4383-9b79-cbf40a047d3e" /># Requirement-Analysis
This repository includes detailed problem definitions, goals, user personas, feature epics, user stories, acceptance criteria, and visuals, forming the foundation for product planning, development, and future enhancements as the BMS grows from concept to implementation.

What is Requirement Analysis?
Requirement Analysis is a foundational phase in the Software Development Lifecycle (SDLC) where business needs are examined, clarified, and translated into actionable technical requirements. It involves close collaboration between stakeholders such as product managers, end-users, designers, and engineers to ensure the product solves the right problem and delivers measurable value.

Why is Requirement Analysis Important?
1. Ensures all stakeholders clearly understand what needs to be built, reducing confusion and scope creep.
2. Saves time and cost by detecting gaps early, minimising rework and development delays.
3. Aligns the product with real user needs, leading to higher satisfaction and adoption while ensuring quality.

Key Activities in Requirement Analysis.
1. Requirement Gathering:
Collecting initial information about business needs and user expectations from stakeholders, existing systems, and market research.
2. Requirement Elicitation:
Engaging directly with users and stakeholders through interviews, workshops, surveys, and observation to uncover detailed needs, constraints, and hidden requirements.
3. Requirement Documentation:
Formally recording requirements in clear, structured artifacts such as PRDs, user stories, use cases, diagrams, and functional specifications for team reference.
4. Requirement Analysis and Modeling:
Examining and refining requirements to ensure they are feasible, unambiguous, prioritized, and well understood. This may include creating models like data flows, ERDs, and process diagrams.
5. Requirement Validation:
Confirming that documented requirements align with business objectives and user needs through stakeholder reviews, prototyping, and acceptance criteria verification.

Types of Requirements
1. Functional Requirements:
   Describe what the system should do, that is the specific behaviors, functions or features that the software must provide.
  Example: 
  1. The system shall allow users to search for hotels based on location, date, price, and amenities.
  2. The system shall send booking confirmation emails and SMS to customers after successful reservation. 
   
3. Non-Functional Requirements:
   Describe how the system performs, covering quality attributes such as performance, reliability, scalability, security and usability.
  Example: 
  1. The system shall respond to any booking request within 2 seconds under normal load/performance.
  2. The system shall handle 10,000 concurrent users without performance degradation


Use Case Diagrams
A Use Case Diagram is a type of Unified Modeling Language (UML) diagram that visually represents the functional interactions between actors and a system.
This shows what the system does, highlighting specific functionalities or services and the actors that interact with them.
<img width="504" height="628" alt="_- visual selection (1)" src="https://github.com/user-attachments/assets/059ed561-583e-4f93-8a48-5a43f40a20fd" />

Acceptance Criteria
Acceptance Criteria (AC) define the specific conditions that a system or feature must satisfy to be considered complete and acceptable by stakeholders.
They are crutial in Requirement Analysis because they:
1. Defines Clear Completion Standards:
   Acceptance criteria establish explicit conditions for a feature to be considered “done,” ensuring developers, testers, and stakeholders share a unified understanding of
   success.

2. Reduces Misunderstandings and Ambiguity:
   By translating high-level requirements into precise, testable statements, acceptance criteria prevent misinterpretation and misaligned expectations during development.
   
3.Guides Testing, Validation, and Planning:
  They serve as a blueprint for QA test cases, validate functionality against requirements, and help teams estimate effort and prioritize tasks effectively.

Example: Acceptance Criteria for a Checkout Feature (Booking Management System)
Feature: Checkout / Payment for a Booking
**Successful Payment**
Given a client has selected a service and time slot
When the client enters valid payment details and confirms payment
Then the system processes the payment successfully
And displays a confirmation message
And generates a booking record

**Invalid Payment Handling**
Given a client enters invalid payment information
When they attempt to confirm the payment
Then the system rejects the payment
And displays an error message
