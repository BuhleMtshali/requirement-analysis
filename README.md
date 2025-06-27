# Requirement Analysis in Software Development

## 📌 Introduction

This repository documents the requirement analysis phase for a Booking Management System, as part of the ALX FeatureForge project. It simulates a real-world scenario in software development, focusing on the critical early stage of planning — identifying, organizing, and validating system requirements.

---

## 📖 What is Requirement Analysis?

Requirement Analysis is the structured process of identifying the needs and expectations of users and stakeholders for a software system. It serves as the foundation of the Software Development Lifecycle (SDLC), ensuring that the system is built with a clear purpose and aligned with business objectives.

It includes:
- Understanding stakeholder needs
- Documenting requirements in a formal format
- Creating models and diagrams
- Validating requirements before development begins

Without proper requirement analysis, software projects risk misalignment, scope creep, poor user adoption, and budget overruns.

---

## 🔍 Why is Requirement Analysis Important?

Here are three key reasons why this process is essential:

- **Prevents Miscommunication**  
  Clearly defined requirements reduce ambiguity and ensure that everyone — developers, designers, and stakeholders — are on the same page.

- **Reduces Risk and Rework**  
  Early identification of system needs helps spot issues before code is written, saving time and money.

- **Provides a Blueprint for Development**  
  A well-structured requirement analysis serves as a map that guides developers and testers throughout the SDLC.

---

## 🔧 Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting raw data and needs from stakeholders via interviews, surveys, and observations.

- **Requirement Elicitation**  
  Refining and clarifying gathered data through collaboration, brainstorming, or prototypes.

- **Requirement Documentation**  
  Structuring the requirements into readable, usable documentation (e.g., SRS docs, user stories, use cases).

- **Requirement Analysis and Modeling**  
  Analyzing the impact and feasibility, and creating visual representations like use case diagrams.

- **Requirement Validation**  
  Verifying that all requirements are correct, complete, and agreed upon by stakeholders.

---

## 🗂️ Types of Requirements

### ✅ Functional Requirements
These describe **what the system should do**.

**Examples for a Booking Management System:**
- Users can register, log in, and manage their profiles.
- Admins can view and manage all bookings.
- The system must allow users to search for available properties.

### ⚙️ Non-Functional Requirements
These describe **how the system should behave**.

**Examples:**
- The site should load within 2 seconds.
- The platform must support up to 10,000 concurrent users.
- All data should be encrypted during transmission.

---

## 🎭 Use Case Diagrams

Use Case Diagrams visualize the interactions between system actors (users, admins) and the system itself. They help define system boundaries and expectations.

### 🔹 Benefits:
- Clarifies system functionality
- Identifies primary actors and interactions
- Helps detect missing features early

![Use Case Diagram](./alx-booking-uc.png)

---

## ✅ Acceptance Criteria

Acceptance Criteria are the conditions a software feature must meet to be accepted by the client or stakeholders.

They provide clear boundaries for what’s in scope, helping prevent misinterpretation during development.

### Example: Checkout Feature

**User Story:**  
_As a customer, I want to complete a booking so I can secure my stay._

**Acceptance Criteria:**
- A logged-in user can click “Book Now” on a listing.
- The system displays a booking confirmation page with selected dates and total cost.
- The user receives a confirmation email.
- If payment fails, the user is shown an error and prompted to retry.

---

## 📎 Repo Info

- GitHub Repository: [requirement-analysis](https://github.com/yourusername/requirement-analysis)

---

