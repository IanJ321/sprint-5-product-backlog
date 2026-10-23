---
layout: default
title: Sprint 5 Beginning Product Backlog
permalink: /backlogs/sprint-05-beginning-product-backlog
---

Sprint 4 (previous):

Product Owner: Ian

Scrum Master: Andres

Sprint 5 (current):

Product Owner: Abdul

Scrum Master: David

Sprint 6 (next):

Product Owner: Andres

Scrum Master: Ian

Sprint 4 Planning: 08 October 2026, 09:30

Sprint 4 Planning Participants: Ian, Andres, David, Abdul

Sprint 4 Committed: 33 pts (Insurance Risk Calculator)

Sprint 4 Review:

**TODO (confirm): 20 Oct 2026, Ian, Andres, David, Abdul | All in-person**

Demo: the Insurance Risk Calculator client (Azure Static Web App) calling the Node.js APIs on Azure App Service, from entering health information to seeing the risk category

Committed: 33 pts | Delivered: 28 pts (85%)

Delivered:
- RC-001: Sprint 4 Scrum Master and Product Owner identified (0 pts)
- RC-002: Backlogs managed and prioritized around the MVP (2 pts)
- RC-003: Sprint Planning facilitated on 08 Oct (2 pts)
- RC-005: Client and server repositories connected to Azure Static Web App and Node.js server (5 pts)
- RC-007: Inputs for age, height, weight, blood pressure, and family history (4 pts)
- RC-008: Inputs validated, including height of at least 2 feet (4 pts)
- RC-010: Wake API called when the page loads (2 pts)
- RC-011: Risk calculation API in Node.js (6 pts)
- RC-014: No calculations on the client (1 pt)
- RC-015: Client deployed as an Azure static website (2 pts)

Not delivered:
- RC-004: GitHub organization (2 pts), moved to Later; the team used personal repositories
- RC-012: One Node.js API per member (3 pts), partially done; David's riskCategory change was merged on 20 Oct

**TODO: feedback received during the review**

Sprint 4 Retrospective:

**TODO (confirm): 20 Oct 2026, Ian, Andres, David, Abdul | All in-person**

What went well:
- Roles were clear from the start (Scrum Master: Andres, Product Owner: Ian)
- Server APIs were built and deployed to Azure App Service (Wake, BP, BMI, and Risk Calculation)
- The client was connected to the Node.js backend and deployed with an Azure Static Web Apps CI/CD workflow (RC-005, RC-015)
- All risk calculations were kept on the server (RC-014)

What to improve:
- Most work was committed in the last few days of the sprint (16-18 Oct) instead of spread across it
- Not every member had commits in the shared repositories before the sprint ended
- An API connectivity bug between client and server was found after the sprint ended (fixed 21 Oct)
- Story IDs were not used in every commit message

Action items for Sprint 5:
- Each member makes their first commit within the first three days of the sprint
- Every commit message includes its story ID (for example, "Story RC-010 done")
- Test client and server together on the development branch before merging to production
- Keep the Product Backlog, Sprint Backlog, and metrics files consistent with each other

Capacity Review: 24 total points / 6 points per member

Sprint 5 Beginning Product Backlog:

| **ID** | **User Story / Task** | **Priority (1-10)** | **Estimate (SP)** | **Spike (Y/N)** | **Status** | **Assigned** |
|--------|------------------------|--------------|--------------|------------|--------------|--------------|
| RC-001 | As the Product Owner, I want to continuously groom the product backlog for high priority stories and appropriately assign them to team members. | -- | - | Y | ----- | ----- |
| RC-002 | As a Scrum Team, we want to attend Capstone sprint planning and coordinate across production teams. | -- | - | Y | ----- | ----- |
| RC-003 | As a Scrum Team, we want to update and test the products "credits" page to include ourselves. | -- | - | Y | ----- | ----- |
| RC-004 | As a Scrum Team, we want to implement development, test, and production CI/CD for the product. | -- | - | Y | ----- | ----- |
| RC-005 | As a Scrum Team, we want to utilize the product and individually add at least two valuable stories to the product backlog. | -- | - | Y | ----- | ----- |
| RC-006 | As a Scrum Team, we want to participate in the Fall 2026 midterm Product Review on Tuesday, 27 Oct at 2 pm. | -- | - | Y | ----- | ----- |
| RC-007 | As a user, I want to view the list of teams responsible for development so that I know who is working on the product. | -- | - | N | ----- | ----- |
| RC-008 | As a user, I want to confirm before deleting a quiz or flashcard deck so that I do not accidentally lose my study materials. | -- | - | N | ----- | ----- |
| RC-009 | As a new user, I want clear guidance when I have no quizzes or flashcards so that I can easily create my first study material. | -- | - | N | ----- | ----- |
| RC-010 | As a user, I want to receive a warning when leaving quiz creation or editing with unsaved changes so that I do not lose my work.  | -- | - | N | ----- | ----- |
| RC-011 | As a user, I want to see my current question number and total number of questions when taking a quiz so that I can view my progression. | -- | - | N | ----- | ----- |
| RC-012 | As a user, I want to see poll calculations so that I can easily view the correct voting percentages. | -- | - | N | ----- | ----- |
| RC-013 | As a user, I want to group my flashcards and quizzes by subject so that I can easily organize and manage my study materials. | -- | - | N | ----- | ----- |
| RC-014 | As a user, I want to be able to share my study material with other users so that we can study together. | -- | - | N | ----- | ----- |
| RC-015 | As a user, I want to add an optional timer to my quizzes so that I can practice my timeliness in real exams. | -- | - | N | ----- | ----- |
| RC-016 | As a user, I want to access QuizMaster on mobile devices so that I can study on-the-go without a laptop or bulky device. | -- | - | N | ----- | ----- |
