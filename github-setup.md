# GitHub setup guide

## Repository
1. Sign in at GitHub.
2. Use **+ → New repository**.
3. Name it `CampusHelp-TeamXX`.
4. Description: `University Student Service Request Portal - Project Management Assignment`.
5. Set Private unless lecturer requests Public.
6. Initialize with README and create repository.
7. Repository Settings → collaborators/access → invite the other two team members.

## Labels
Create labels: `requirements`, `planning`, `design`, `testing`, `documentation`, `risk`, `change-request`, `blocked`.

## Milestones
Issues → Milestones → New milestone. Create M1 Project Initiation (Day 2), M2 Project Planning (Day 4), M3 Project Execution (Day 7), M4 Monitoring and Closure (Day 10). Set actual calendar due dates.

## Issues
Create the 12 titles and copy their content from `docs/issues.md`. Assign the listed owner, label and milestone. Add each to the project.

## Project Board
1. Profile → Projects → New project → Board.
2. Name `CampusHelp Project Management - TeamXX`.
3. Use status columns Todo, In Progress, Done.
4. Add all 12 repository Issues.
5. Create Table and Roadmap views.
6. In Table view add fields: Priority (single select High/Medium/Low), Estimated Hours (number), Actual Hours (number), Start Date (date), Due Date (date).
7. Set High priority: T01, T02, T04, T07, T08, T09, T11. Medium: T03, T05, T06, T10, T12.
8. Configure Roadmap with Start Date and Due Date.

## Branch and Pull Request (each member)
1. Open repo; branch dropdown → create branch (e.g. `student-a-charter`).
2. Add or edit a file in that branch.
3. Commit with a descriptive message.
4. Pull requests → New Pull Request; base `main`, compare your branch.
5. Describe changes and link the relevant Issue.
6. Request review from another member.
7. Respond to comments, then merge.
8. Add the PR link to the Issue. Each student should author at least one PR and review another.

## Progress checkpoints
At Day 2, Day 5 and Day 8: review board, count closed Issues, list blocked/unfinished work, update actual hours, review next milestone, post update and capture screenshot. Completion percentage = closed Issues ÷ 12 × 100. Distinguish actual progress from planned progress.

## Screenshots to capture
- Repo homepage and URL
- Collaborator access
- Charter/WBS
- Milestones and due dates
- Labels
- Issues list
- Project Board (start, middle, close)
- Table view and Roadmap
- Pull Requests and peer reviews
- Monitoring checkpoints
- Test results and closure
