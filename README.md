# Business Analysis Case Study — User Registration

## 📌 Project Overview

This project is a **Business Analysis case study** focused on analyzing and documenting a requirement for a new-user registration feature for **ownwebsite.com**.

The objective was to take a simple one-line business requirement and transform it into structured Business Analysis documentation by identifying assumptions, asking the right stakeholder questions, defining user requirements, creating acceptance criteria, documenting the use case, and representing the process visually.

The case study demonstrates a practical approach to moving from a **high-level requirement → requirement clarification → user story → acceptance criteria → use case → process visualization**.

---

## 🎯 Business Requirement

> The system should allow a new user to register for access to ownwebsite.com so that they can log in and use the website.

Since the initial requirement contained limited detail, the first step was to identify assumptions and areas requiring clarification from the SME/Product Owner.

---

## 🧩 Business Analysis Approach

The requirement was analyzed through the following stages:

1. Requirement Understanding
2. Assumption Identification
3. Stakeholder/SME Questions
4. User Story Creation
5. Acceptance Criteria Definition
6. Use Case Documentation
7. Alternate & Exception Flow Identification
8. Wireframe Creation
9. Activity Diagram Creation
10. Next-Step Identification

---

## 1. Requirement Analysis

### Initial Requirement

The website should allow new users to register and subsequently access the website through their account.

### Initial Assumptions

The case study assumes that:

* Any visitor can register.
* The registration form requires **Name, Email Address, and Password**.
* Email address will be used as the login ID.
* Email verification is required before account activation.
* Users must agree to Terms & Conditions.
* Passwords must follow basic security requirements.
* Login, forgot password, and profile editing are separate requirements.

These assumptions are explicitly marked for confirmation with the SME/Product Owner rather than being treated as confirmed business requirements.

---

## 2. SME / Stakeholder Questions

A **5W1H-based questioning approach** was used to identify missing information and avoid making unsupported assumptions.

### Why — Business Purpose

* Why is user registration required?
* What business value will registration provide?
* What user problem does registration solve?
* Is this a new feature or an improvement to an existing process?

### Who — Users

* Who can register?
* Are there specific user groups?
* How technically comfortable are the users?
* Will registration be available on mobile, desktop, or both?

### What — Information

* What information should users provide?
* Which fields are mandatory?
* Which fields are optional?
* Is email or phone verification required?

### How — Process

* What happens after the user submits the registration form?
* What happens if an email already exists?
* Is approval required before account activation?

### Rules & Validation

* What password rules should be applied?
* Are Terms & Conditions and Privacy Policy mandatory?
* Are there age or eligibility restrictions?

### Success & Errors

* What should users see after successful registration?
* What error messages should be displayed?
* How will registration success be measured?

### Look & Feel

* Is there an existing design or branding guideline?
* Are there existing registration pages that can be used as references?

The questions are intended to be discussed with the SME/Product Owner before finalizing the requirements.

---

## 3. User Story

### Story ID

**US-001**

### Title

**New User Registration**

### User Story

**As a** new visitor to ownwebsite.com,
**I want** to register using my name, email, and password,
**So that** I can create an account and log in to use the website.

---

## 4. Acceptance Criteria

### AC1 — Registration Form

**Given** I am on the website,
**When** I click Register,
**Then** I should see a form requesting:

* Name
* Email
* Password
* Confirm Password

### AC2 — Successful Registration

**Given** I have entered valid information and agreed to the Terms & Conditions,
**When** I submit the registration form,
**Then** my account should be created and I should receive a verification email.

### AC3 — Existing Email

**Given** I enter an email address that is already registered,
**When** I submit the form,
**Then** the system should display an appropriate error message and suggest logging in instead.

### AC4 — Weak Password

**Given** I enter a password that does not meet the required rules,
**When** I submit the form,
**Then** the system should display the applicable password requirements.

### AC5 — Email Verification

**Given** I receive a valid verification email,
**When** I click the verification link,
**Then** my account should become active and I should be able to log in.

These acceptance criteria are based directly on the case study's defined user story.

---

## 5. Use Case

### Use Case ID

**UC-001**

### Use Case Name

**Register for Access to ownwebsite.com**

### Actor

**New User / Visitor**

### Description

Allows a new visitor to create an account on the website so they can log in later.

### Preconditions

* User is not currently logged in.
* User does not already have an existing account.

### Postconditions

* A new account is created.
* After successful email verification, the account becomes active.
* The user can proceed to log in.

---

## 6. Main Use Case Flow

| Step | User/System Action                                             |
| ---- | -------------------------------------------------------------- |
| 1    | User opens the Registration page                               |
| 2    | System displays the registration form                          |
| 3    | User enters name, email, password, and confirmation password   |
| 4    | User agrees to Terms & Conditions and submits                  |
| 5    | System validates the information and checks email availability |
| 6    | System creates the account and sends verification email        |
| 7    | User clicks the verification link                              |
| 8    | System activates the account                                   |
| 9    | User is redirected to the login page                           |

The main flow follows the documented use case in the case study.

---

## 7. Alternate & Exception Flows

### Alternate Flow — Existing Email

If the entered email address is already registered:

1. System identifies the existing account.
2. System displays an error message.
3. System suggests that the user log in instead.

### Exception Flow — Expired Verification Link

If the verification link has expired:

1. User attempts to verify the account.
2. System identifies the expired link.
3. System provides an option to request a new verification email.

---

## 8. Supporting Artifacts

The case study also includes supporting visual artifacts:

### Wireframe

A draft wireframe was created to demonstrate the proposed registration page structure.

### Activity Diagram

An activity diagram was created to visualize the registration process and system/user interactions.

These artifacts were created to communicate the requirement beyond textual documentation.

---

## 🔄 Requirement Traceability

The case study demonstrates how a single high-level requirement can be progressively transformed into detailed analysis artifacts:

```text
Business Requirement
        ↓
Assumptions
        ↓
SME Questions
        ↓
User Story
        ↓
Acceptance Criteria
        ↓
Use Case
        ↓
Alternate / Exception Flows
        ↓
Wireframe
        ↓
Activity Diagram
```

This approach helps ensure that business requirements are understood before development begins.

---

## 📁 Project Deliverables

The case study contains the following Business Analysis deliverables:

* Requirement Analysis
* Assumption Log
* SME / Stakeholder Questions
* User Story
* Acceptance Criteria
* Use Case
* Main Flow
* Alternate Flow
* Exception Flow
* Registration Page Wireframe
* Activity Diagram
* Next-Step Recommendations

---

## 🛠️ Business Analysis Techniques Demonstrated

This project demonstrates practical knowledge of:

* Requirement Analysis
* Requirement Clarification
* Assumption Identification
* Stakeholder Analysis
* 5W1H Questioning
* User Story Writing
* Acceptance Criteria
* Use Case Modeling
* Alternate & Exception Flow Analysis
* Process Modeling
* Wireframing
* Requirement Validation
* Stakeholder Collaboration

---

## 📌 Business Analyst Perspective

The key objective of this case study was **not simply to document the requirement**, but to identify what is missing from the requirement and determine what needs to be clarified before development.

The case study demonstrates the importance of:

* Asking the right questions instead of making assumptions.
* Converting business needs into user-focused requirements.
* Defining testable acceptance criteria.
* Documenting normal, alternate, and exception scenarios.
* Using visual artifacts to communicate requirements.
* Validating assumptions with the SME/Product Owner.

---

## 🚀 Next Steps

According to the case study, the next steps would be:

1. Discuss the identified questions with the SME/Product Owner.
2. Record and validate the stakeholder responses.
3. Update assumptions based on confirmed information.
4. Refine the user story and acceptance criteria.
5. Update the use case where required.
6. Get the wireframe reviewed by the UX team.
7. Finalize the requirements before development begins.

These next steps are explicitly identified in the original case study.

---

## 👤 Project Type

**Business Analysis Case Study**

### Role

**Business Analyst**

### Focus Area

**Web Application — User Registration**

### Key Deliverables

**Requirements + User Story + Acceptance Criteria + Use Case + Wireframe + Activity Diagram**

---

## ⭐ Key Takeaway

This case study demonstrates the transition from a **simple business requirement to structured, actionable requirements** that can be understood by business stakeholders, UX designers, developers, and QA teams.

> **Understand → Question → Analyze → Document → Validate → Communicate**
