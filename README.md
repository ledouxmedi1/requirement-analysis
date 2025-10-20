# Requirement Analysis in Software Development

## Introduction

This repository serves as a comprehensive resource for documenting the requirement analysis phase of a hotel booking management system, inspired by platforms like Airbnb and OYO. The purpose is to create a structured blueprint of functional and non-functional requirements, acceptance criteria, and system architecture diagrams to ensure clarity, alignment with stakeholder expectations, and a solid foundation for software development. By applying industry-standard practices, this project aims to simulate real-world requirement analysis tasks, emphasizing precision, scalability, and user-centric design.

## What is Requirement Analysis?

Requirement Analysis is a critical SDLC phase where stakeholder needs for a hotel booking system are gathered, analyzed, and documented to define what the system does and how it performs. It ensures a shared understanding among customers, hotel managers, and developers, forming the foundation for development.

### Importance
- **Clarity**: Eliminates ambiguity (e.g., defining “fast search” as <200ms response).
- **Scope Control**: Prevents scope creep by setting a clear project scope.
- **Development Guide**: Provides a blueprint for designing and building the system.
- **Cost/Time Accuracy**: Enables precise resource and timeline estimates.
- **Quality**: Aligns the product with user expectations (e.g., reliable bookings).

### Key Activities
1. **Gathering**: Collect needs via interviews, surveys, workshops, observation, and document analysis (e.g., reviewing OYO’s system gaps).
2. **Elicitation**: Refine requirements through brainstorming, focus groups, and prototyping (e.g., mockup of booking interface).
3. **Documentation**: Create SRS, user stories (e.g., “As a customer, I want to filter hotels by price”), and use cases.
4. **Analysis/Modeling**: Prioritize requirements (e.g., MoSCoW), assess feasibility, and model interactions (e.g., use case diagrams).
5. **Validation**: Review with stakeholders, define acceptance criteria, and ensure traceability via an RTM.

### Types of Requirements
- **Functional**: Features like hotel search, booking, and authentication (e.g., OAuth 2.0 login).
- **Non-Functional**: Quality attributes like performance (<2s page load), security (AES-256 encryption), scalability (10K concurrent users), usability (WCAG 2.1 AA), and reliability (99.99% uptime).

### Process
1. Gather stakeholder needs (e.g., customers want fast search).
2. Elicit detailed requirements via prototyping or discussions.
3. Document in SRS, user stories, and use cases.
4. Analyze, prioritize, and model requirements.
5. Validate with stakeholders, setting clear acceptance criteria (e.g., “Booking confirmation in <2 minutes”).

### Use Case Diagrams
- **Purpose**: Visualize user-system interactions (e.g., Guest → Search Hotels).
- **Components**: Actors (Guest, Manager) and use cases (Book Property, Manage Listings).
- **Benefits**: Clarify functionalities and improve stakeholder communication.

### Acceptance Criteria
- **Purpose**: Define measurable conditions for feature completion (e.g., “Search results load in <200ms”).
- **Benefits**: Ensure quality, guide testing, and align expectations.

This process ensures the hotel booking system is well-defined, scalable, and user-focused, as seen in platforms like Airbnb and OYO.
