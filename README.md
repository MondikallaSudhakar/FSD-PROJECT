# FSD-PROJECT
Student Placement Management Portal for managing companies, placement drives, eligibility, applications, and selection status.
# Student Placement Management Portal

## Project Overview

The Student Placement Management Portal is a centralized digital platform developed to manage the complete campus recruitment workflow between students, companies, and the placement department.

The system replaces fragmented placement activities with a structured workflow where placement officers can publish recruitment drives and manage applicants, while students can discover relevant opportunities, verify eligibility, submit applications, and monitor their progress from a single portal.

## What the Portal Solves

Managing campus placements manually can involve spreadsheets, notices, forms, and repeated communication between students and the placement department. This makes it difficult to maintain accurate application records and track the progress of individual students.

This portal brings these activities into one system and provides a clear flow:

**Company → Placement Drive → Eligibility → Student Application → Applicant Management → Selection Status**

## Core Functionality

### Student Portal

Students can:

* Register and access the placement portal
* Explore currently available placement drives
* View company and recruitment details
* Check eligibility requirements before applying
* Submit applications for suitable opportunities
* Track the status of submitted applications
* View their selection status

### Placement Officer Portal

Placement officers can:

* Register and manage company information
* Modify existing company details
* Remove outdated company records
* Create and publish placement drives
* Configure eligibility requirements for each drive
* View students who have applied
* Manage applications received for recruitment drives
* Update the recruitment outcome of applicants

## Placement Workflow

The application follows a structured recruitment lifecycle:

Company Information
       |
       v
Placement Drive Creation
       |
       v
Eligibility Criteria
       |
       v
Eligible Students
       |
       v
Student Application
       |
       v
Applicant Review
       |
       v
Selection Status

This workflow keeps placement information organized and makes the application process easier to follow for both students and placement officers.

## Main Modules

### 1. Student Management

Handles student registration and provides students with access to available placement opportunities.

### 2. Company Management

Maintains company information and allows placement officers to add, modify, and remove company records.

### 3. Placement Drive Management

Allows officers to create individual recruitment drives with relevant company and recruitment information.

### 4. Eligibility Management

Stores the requirements associated with a placement drive so students can determine whether they are eligible before applying.

### 5. Application Management

Maintains student applications against individual placement drives and allows officers to view the applicant pool.

### 6. Selection Management

Allows placement officers to update the outcome of student applications and enables students to track their current status.

## Key Highlights

* Centralized placement information
* Separate student and placement officer workflows
* Eligibility-driven application process
* Structured placement drive management
* Application tracking
* Selection status management
* Reduced dependency on manual placement records
* Clear recruitment workflow from drive creation to final selection

## Technology

The project is implemented as a web-based application using modern web development technologies.

> Add your exact technologies here, for example:
>
> * Frontend: React.js
> * Backend: Spring Boot
> * Database: MySQL
> * API: REST API
> * Version Control: Git and GitHub

## Project Architecture

```text
                    Student Placement Portal
                              |
                +-------------+-------------+
                |                           |
          Student Module              Officer Module
                |                           |
       +--------+--------+          +-------+--------+
       |        |        |          |       |        |
   Companies Eligibility Apply   Companies Drives Applicants
       |        |        |          |       |        |
       +--------+--------+          +-------+--------+
                |                           |
                +------------+--------------+
                             |
                       Application Data
                             |
                       Selection Status

## Completed Features

The following core functionality has been implemented:

* Student registration
* Company management
* Placement drive creation
* Eligibility criteria management
* Student application process
* Applicant viewing
* Application status management
* Selection status updates

## Use Case

The portal can be deployed by a college placement department to organize campus recruitment activities in a single digital environment. It can support multiple companies and placement drives while maintaining the relationship between students, eligibility requirements, applications, and selection outcomes.

## Project Outcome

The completed system provides a structured and transparent approach to campus placement management. Students get a single place to discover and apply for opportunities, while placement officers gain a centralized interface for managing recruitment activities and applicant information.

## Future Scope

Although the core placement workflow is complete, the platform can be extended with:

* Resume upload and profile management
* Automated eligibility validation
* Email and application notifications
* Interview scheduling
* Placement analytics and dashboards
* Company-wise placement reports
* Student placement history
* Automated recruitment reports
* Role-based authentication and authorization

## Contributors

This project was developed as a team project with the goal of creating a practical solution for digitizing the campus placement workflow.

