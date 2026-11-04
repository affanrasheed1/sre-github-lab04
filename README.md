# sre-github-lab04
# Departmental FYP and Palagirsm prevention system
# Overview: 
## Every year, each batch of Software Engineering students completes a Final Year Project (FYP). The department also calls this the Final Year Design Project (FYDP). These projects contain months of work: proposals, reports, source code, slides and demo videos. Today this work is kept in Google Drive folders, and in earlier years also on hard copies, DVDs and USB drives. The committee has no tool to search past projects or to check a new project against them.
## The Departmental FYP and Plagiarism Prevention System is a web platform that solves this. Students submit their FYP files digitally. After the supervisor and the FYP Committee approve them, the files go into one central, searchable archive. The system then compares new proposals and submissions with archived projects and reports possible duplication to the committee, so that people can make the final decision.
## This Vision Document explains why the system is needed, who it is for, what it will and will not do, and how we will judge its success. It gives the group, the supervisor and the department one shared view before the Software Requirements Specification (SRS) begins. Our requirements come from a Google Form completed by the FYP Committee Chair, Ms. Natalia Chaudhry, on 6 October 2026 and student requirements are form also google form completed by students . The main requirements are listed in Appendix A, and the points we still need to confirm are in Appendix B.

# Scope: 
## These are high-level features. Detailed requirements will be written in the SRS. The Chair ranked the searchable archive as the most important feature for the first version, so it is built first.
## F1 Central FYP Archive and Search (highest priority)
## Digital storage of approved FYPs, identified by unique Group ID and batch year. Users with permission can search and open past projects.
## F2
## Submission and Approval Workflow
## Students submit the final report (PDF), source code (ZIP), presentation slides, supervisor approval form and demo video. Only digital ## files are accepted. A project enters the archive after approval by both the supervisor and the committee.
## F3
## Multi-dimensional Similarity Analysis
## Compares a new proposal or submission with archived FYPs on objectives, scope, methodology and deliverables, not only text. The same title or similar wording alone does not count as duplication.