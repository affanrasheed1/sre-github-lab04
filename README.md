# Departmental FYP Archive and Plagiarism Prevention System

## Overview
Every year, Software Engineering students submit Final Year Projects (FYPs) containing proposals, final reports, source code, slides, and demo videos[cite: 11]. Historically, these files were stored across scattered Google Drive folders, DVDs, and USB drives without a centralized, searchable repository or automated duplicate checking[cite: 11]. 

The **Departmental FYP Archive and Plagiarism Prevention System** is a centralized web platform for the Department of Software Engineering, FCIT, University of the Punjab[cite: 11]. It digitally archives approved FYPs, identified by Group ID and batch year, and performs multi-dimensional similarity analysis across project objectives, scope, methodology, and deliverables to assist the FYP Committee in identifying potential project duplication[cite: 11].

## Scope
 **In scope:** Centralized digital archiving of approved FYPs with search functionality by Group ID and batch year[cite: 11].
* **In scope:** Digital multi-file submission workflow accepting final reports (PDF), source code (ZIP), presentation slides, supervisor approval forms, and demo videos[cite: 11].
* **In scope:** Multi-dimensional similarity analysis comparing objectives, scope, methodology, and deliverables against past archived projects with side-by-side reporting[cite: 11].
* **In scope:** Student draft pre-check mechanism allowing students to check projects for potential duplication before final submission[cite: 11].
* **Out of scope:** Automated grading, scoring, or automated academic penalty decisions[cite: 11].
* **Out of scope:** Hard-copy, DVD, or USB physical submission handling (digital files only)[cite: 11].
* **Out of scope:** Course assignment archiving (reserved for potential future releases)[cite: 11].

## Stakeholders
* **FYP Students:** Submit project proposals, draft pre-checks, and final digital deliverables[cite: 11]. They benefit from streamlined digital submissions and early warning of potential project duplication[cite: 11].
* **Supervisors (FAC Members):** Review group submissions, approve projects for archiving, and monitor groups flagged for similarity revisions[cite: 11].
* **FYP Committee (Chair & Members):** Review similarity reports, evaluate side-by-side scope comparisons, approve final archiving, and assign flagged duplicate projects for revision[cite: 11].
* **FYDP Coordinator / Administrators:** Manage platform configurations, system roles, user access, backup routines, and similarity threshold percentages[cite: 11].
* **Department Chairman:** Defines access policies, privacy rules, and authorization levels for viewing prior project records[cite: 11].

## Functional Requirements
* **FR-01:** The system shall store approved FYPs in a centralized digital archive indexed by unique Group ID and batch year[cite: 11].
* **FR-02:** The system shall accept digital submissions containing final PDF reports, ZIP source code, presentation slides, supervisor approval forms, and demo videos[cite: 11].
* **FR-03:** The system shall compare incoming project proposals and submissions against archived FYPs across objectives, scope, methodology, and deliverables, generating a similarity report[cite: 11].
* **FR-04:** The system shall flag submissions exceeding a configurable single-digit similarity threshold and route them to the FYP Committee for review[cite: 11].
* **FR-05:** The system shall allow registered students to run a draft similarity pre-check on their project prior to final submission[cite: 11].

## Nonfunctional Requirements
* **NFR-01 (Performance):** For a database containing up to 500 archived FYPs, the system shall generate and display a multi-dimensional similarity report in 30 seconds or less in at least 95 out of 100 trials under standard network conditions[cite: 11].
* **NFR-02 (Security & Access Control):** The system shall restrict archive search and document retrieval access strictly to authorized FYP Committee members, FYDP Coordinators, and Administrators, resulting in 0 successful unauthorized access attempts during boundary testing[cite: 11].

## Acceptance Criteria
* **FR-01:** Given an approved FYP with Group ID "BSEF25M-G01" and batch year "2026", saving the approved project causes it to appear in the searchable archive under those exact parameters[cite: 11].
* **FR-02:** Given a student submission containing all 5 required files (PDF report, ZIP source code, slides, approval form, and demo video), uploading the set changes the submission state to "Pending Approval"[cite: 11].
* **FR-03:** Given a new project proposal with objectives identical to an archived 2024 project, generating a similarity analysis produces a report detailing objective similarity percentage alongside a side-by-side comparison view[cite: 11].
* **FR-04:** Given a project submission that evaluates to a 12% overall similarity score against a system threshold set at 5%, the system automatically marks the project as "Flagged" and assigns it to the FYP Committee review queue[cite: 11].
* **FR-05:** Given a student running a draft pre-check on an unsubmitted proposal draft, the system displays the preliminary similarity score without saving the draft to the permanent archive[cite: 11].

## Assumptions and Open Questions
* **Assumption A-01:** All historical and future FYP submissions will be provided strictly in digital format without physical copies[cite: 11].
* **Assumption A-02:** Objective and scope comparisons rely on structured input sections provided by students during submission[cite: 11].
* **Question Q-01:** What exact single-digit percentage (e.g., 5% vs 9%) will be configured as the official department similarity threshold[cite: 11]?
* **Question Q-02:** What specific privacy and viewing permissions will the Department Chairman establish for general student access to prior project records[cite: 11]?
* **Question Q-03:** How many draft pre-checks will an individual student group be allowed to execute per submission cycle[cite: 11]?

## Project Status and Viewing
Documentation only. Application implementation has not started[cite: 5, 6]. 
To view this project, clone the repository and open `README.md` in a Markdown viewer or read the rendered version on GitHub[cite: 6].

## Author
* **Muhammad Affan** (Roll No: BSEF25M550)[cite: 11]
* Course: Software Requirement Engineering (BS Software Engineering, FCIT, University of the Punjab, Lahore)[cite: 1, 11]

## Contributing
Create a documentation branch (`doc/feature`), edit and review the `README.md`, commit your changes, push the branch to `origin`, and open a pull request for review[cite: 4, 6, 8].
