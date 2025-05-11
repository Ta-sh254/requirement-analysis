# requirement-analysis
- The aim of this repository is to provide me with basic knowledge of creating clear, structured markdown repositories and conceptualize and articulate project requirements, use cases and acceptance criteria.
- ## What is Requirement Analysis?
*Requirement Analysis* - This is the process of gathering, analyzing, and defining what software should do based on stakeholders needs. 

### Its importance in software development cycle (SDLC)
*Planning* - Defines the scope and features, enabling realistic time and 
resource estimates.
*Design* - UI/UX designers use the requirements to create mockups that 
reflect both functionality and branding.
*Testing* - Testers use requirements to write test cases (e.g., “Does Add to Cart work on mobile?”).
*Deployment* - Confidence in rollout because the features meet the agreed needs.
*Maintenance* - Clear documentation of requirements makes it easier to fix bugs or add new features later.
*Development* - Developers know exactly what to build — no guesswork, fewer revisions.

## Why is Requirement Analysis important?
### Clarity and Understanding
- Helps avoid confusion by making stakeholder expectations explicit.
- Reduces ambiguity, ensuring developers and clients are on the same page.
### Scope Definition
- Clearly outlines what will and won't be included in the project.
- Prevents scope creep, which can derail timelines and budgets.
### Basis for Design and Development
- Provides a well-defined foundation for building architecture, interfaces, and features.
- Ensures design choices align with user needs.
### Cost and Time Estimation
- With clear requirements, teams can accurately estimate needed time, manpower, and budget.
- Prevents underestimation and project overruns.
### Quality Assurance
- Enables testing against specific, agreed-upon requirements.
- Results in software that meets client expectations, improving satisfaction and reducing rework.

## Key Activities in Requirement Analysis
### Requirement Gathering
- Interviews: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
- Surveys/Questionnaires: Distributing surveys to collect requirements from a larger audience.
- Workshops: Organizing workshops with stakeholders to discuss and gather requirements.
- Observation: Observing end-users in their working environment to understand their needs.
- Document Analysis: Reviewing existing documentation and systems to understand current functionalities and requirements.
  
### Requirement Elicitation
- Brainstorming: Conducting brainstorming sessions to generate ideas and gather requirements.
- Focus Groups: Holding focus group discussions with selected stakeholders to gather detailed requirements.
- Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirements.
### Requirement Documentation
- Requirement Specification Document: Creating a detailed document that lists all functional and non-functional requirements.
- User Stories: Writing user stories to describe functionalities from the user’s perspective.
- Use Cases: Creating use case diagrams to show interactions between users and the system.
  
### Requirement Analysis and Modelling
- Requirement Prioritization: Prioritizing requirements based on their importance and impact on the project.
- Feasibility Analysis: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
- Modeling: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

### Requirement Validation
- Review and Approval: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
- cceptance Criteria: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
- Traceability: Establishing traceability matrices to ensure all requirements are addressed during development and testing.
  
# Types of Requirement
- *Definition*: Describe what the system should do.
- *Examples*: User authentication, property search, booking system, user registration.

## Key Functional Requirements:
*Search Properties*: Users should be able to search for properties based on various criteria such as location, price, and availability.
*User Registration*: New users should be able to create an account with personal details and login credentials.
*Property Listings*: Display properties with essential details and images.
*Booking System*: Users should be able to book properties, view booking details, and manage their bookings.
*User Authentication*: Secure login and registration process for users.

## Non-functional Requirements 🛡️
*Definition*: Describe how the system should perform.
*Examples*: Performance, security, scalability, usability, reliability.

## Key Non-functional Requirements:
*Performance*: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
*Security*: Ensure data encryption, secure login, and protect against common vulnerabilities.
*Scalability*: The system should be able to scale horizontally to handle increased traffic.
*Usability*: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
*Reliability*: The system should have an uptime of 99.9% and recover quickly from any failures.

# Use case diagrams
- Use case diagrams are a type of UML (Unified Modeling Language) diagram used to visually represent how users (actors) interact with a system to achieve specific goals (called use cases).

They show:

- *Actors* (users or external systems)

- *Use cases* (actions or functions the system performs)

- *Relationships* between actors and use cases

### Example:
For a login system, a simple use case diagram might show:

- Actor: User

- Use cases: Login, Reset Password

- Relationships: Arrows connecting the user to those actions

# #✅ Benefits of Use Case Diagrams:
1. ### Clarity of System Functionality
Gives a high-level overview of what the system does from the user's perspective.

2. ### Stakeholder Communication
Easy for non-technical stakeholders to understand system goals and interactions.

3. ### Requirement Validation
Helps ensure all expected user actions are captured during analysis.

4. ### Design Guidance
Guides developers and designers by highlighting key system interactions.

5. ### Scoping and Planning

Useful for breaking down and prioritizing features during early project phases.

#  Acceptance Criteria in Software Development

##  What is Acceptance Criteria?

**Acceptance Criteria** are **predefined conditions** that a software feature must meet to be considered **complete**, **functional**, and **accepted** by the product owner or client. They guide development and testing by defining **"done"** in measurable terms.

---

##  Why Acceptance Criteria Matter in Requirement Analysis

Acceptance Criteria are critical because they:

- *Clarify Expectations**: Turn vague requirements into concrete, testable outcomes.
- *Guide Development**: Developers know exactly what to build.
- *Enable Testing**: QA teams use criteria to create test cases and ensure quality.
- *Prevent Scope Creep**: Limit the feature scope to only what's explicitly agreed.
- *Ensure Stakeholder Satisfaction**: Everyone agrees on when a feature is "done."

---

##   Example: Acceptance Criteria for Checkout Feature  
*(Booking Management System)*

### **User Story**
> As a customer, I want to securely complete my booking and payment so that I can confirm my reservation without errors.


