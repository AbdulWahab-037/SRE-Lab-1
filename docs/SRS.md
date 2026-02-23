# Software Requirements Specification (SRS)

Project: Online Course Registration System  
Course: Software Requirements Engineering Lab

## 1. Introduction
This document contains the improved and reviewed requirements for the Online Course Registration System.  
The requirements were analyzed using a review checklist to identify problems such as ambiguity, incompleteness, and lack of testability.

---

## 2. Requirement Review Activity

### Requirement 1
Original Requirement:
The system should be user-friendly.

Problems Identified:
- Not clear
- Not measurable
- Not testable
- Ambiguous

Improved Requirement:
The system shall provide a user interface where a new user can complete course registration within 3 minutes without external assistance.

---

### Requirement 2
Original Requirement:
The system shall store student records safely.

Problems Identified:
- Ambiguous
- Not measurable
- Incomplete

Improved Requirement:
The system shall store student records in a secure database with encryption and authenticated access.

---

### Requirement 3
Original Requirement:
The system should load quickly.

Problems Identified:
- Not measurable
- Ambiguous
- Not testable

Improved Requirement:
The system shall load the dashboard page within 2 seconds under normal network conditions.

---

### Requirement 4
Original Requirement:
The system shall allow users to register, login, and manage their profile.

Problems Identified:
- Not atomic
- Contains multiple functions
- Incomplete

Improved Requirements:

Requirement 4A:
The system shall allow users to create an account using an email and password.

Requirement 4B:
The system shall allow registered users to log in using valid credentials.

Requirement 4C:
The system shall allow users to update their profile information.

---

### Requirement 5
Original Requirement:
The system shall send notifications.

Problems Identified:
- Incomplete
- Ambiguous
- Not testable

Improved Requirement:
The system shall send email notifications to users after successful registration or profile updates.