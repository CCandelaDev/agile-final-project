# agile-final-project
Final project using Agile

# Agile Workflow

This project follows an **Agile Kanban workflow** using GitHub Projects.  
The goal is to organize issues (user stories, tasks, bugs, and improvements) and track their progress through well-defined stages.  

## Kanban Columns

- **New issues** → All new issues start here before prioritization.  
- **Icebox** → Issues with low priority or ideas to be validated (may never be developed).  
- **Backlog project** → Issues selected for future development but not yet assigned to a sprint.  
- **Sprint backlogs** → Issues chosen for the current sprint.  
- **In progress** → Issues currently being worked on.  
- **Review / QA** → Issues under testing or pending review.  
- **Done** → Completed issues. When moved here, the related GitHub issue is automatically closed.  

## Workflow Rules

1. **Issue lifecycle**  
   - Issues are created in **New issues**.  
   - They are then classified into **Icebox** or **Backlog project**.  
   - From the **Backlog project**, some are moved into **Sprint backlogs** during sprint planning.  
   - Developers move them to **In progress** when they start working on them.  
   - Once finished, they go to **Review/QA** for testing and validation.  
   - If validated, they move to **Done** → the GitHub issue is automatically closed.  

2. **Closed Issues**  
   - When an issue is moved to **Done**, GitHub automatically marks it as **closed**.  
   - Moving an already closed issue to another column (e.g., QA or Closed) does **not reopen** it.  
   - This ensures that once an issue is marked **Done**, it stays closed in GitHub.  

## Labels & Priorities
- **enhancement** → New features or improvements.  
- **technical debt** → Refactoring or technical maintenance tasks.  
- **bug** → Issues that represent defects to be fixed.  

## Story Points
- Each issue is estimated with **story points** to measure complexity and effort.  
- Issues in **Icebox** and **Done** are excluded from sprint capacity planning.  

---
✅ This workflow ensures transparency, prioritization, and a clear development cycle.  
