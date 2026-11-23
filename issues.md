# Twelve mandatory GitHub Issues

Create each Issue with the title, owner, milestone, label and estimated hours below. Add the Issue to the Project Board. Use the assignment IDs (T01–T12) in titles.

## T01 – Develop project charter
**Owner:** A | **Effort:** 4h | **Milestone:** M1 | **Labels:** documentation, planning  
**Objective:** Establish the purpose, scope, stakeholders, constraints and success criteria.  
**Description:** Draft the charter and obtain team review.  
**Deliverable:** `docs/project-charter.md`.  
**Acceptance criteria:** Scope and out-of-scope items are clear; at least three measurable success criteria; team and sponsor roles stated; reviewed by another member.  
**Dependency:** None.  
**Evidence:** File link and PR.

## T02 – Gather stakeholder requirements
**Owner:** B | **Effort:** 4h | **Milestone:** M1 | **Labels:** requirements, documentation  
**Objective:** Define what students and administrators need.  
**Description:** Document stakeholders, six functional requirements, quality requirements and user stories.  
**Deliverable:** `docs/requirements.md`.  
**Acceptance criteria:** Six feature requirements documented; stakeholders identified; requirement review recorded.  
**Dependency:** None.  
**Evidence:** File link and PR.

## T03 – Prepare scope and WBS
**Owner:** C | **Effort:** 4h | **Milestone:** M1 | **Labels:** planning, documentation  
**Objective:** Break project work into manageable packages.  
**Description:** Produce WBS hierarchy and work-package explanations.  
**Deliverable:** `docs/wbs.md`.  
**Acceptance criteria:** Initiation, planning, execution and closure branches; work packages and deliverables explained.  
**Dependency:** T01.  
**Evidence:** WBS file and PR.

## T04 – Prepare schedule, dependencies and budget
**Owner:** A | **Effort:** 4h | **Milestone:** M2 | **Labels:** planning, documentation  
**Objective:** Establish the schedule baseline and simulated budget.  
**Description:** Map task owners, durations, dependencies, milestones and budget at 50,000 UZS per hour.  
**Deliverable:** `docs/schedule-budget.md`.  
**Acceptance criteria:** 45-hour total; 2,250,000 UZS total; dependencies documented; delay-sensitive tasks identified.  
**Dependency:** T03.  
**Evidence:** Schedule document and PR.

## T05 – Design initial wireframes
**Owner:** B | **Effort:** 4h | **Milestone:** M2 | **Labels:** design, documentation  
**Objective:** Show the main student and administrator interactions.  
**Description:** Create submission/tracking and admin dashboard wireframes.  
**Deliverable:** Wireframe images or mockups saved in repository.  
**Acceptance criteria:** Required fields, category/priority, tracking ID/status, assignment and dashboard summary are represented; peer review completed.  
**Dependency:** T02.  
**Evidence:** Mockups and PR.

## T06 – Develop risk register and quality plan
**Owner:** C | **Effort:** 4h | **Milestone:** M2 | **Labels:** risk, testing, documentation  
**Objective:** Proactively manage project risks and quality.  
**Description:** List at least five risks with probability, impact, owner and mitigation; describe quality approach.  
**Deliverable:** `docs/risk-quality.md`.  
**Acceptance criteria:** At least five risks; risk priority/seriousness rationale; quality review approach documented.  
**Dependency:** T03.  
**Evidence:** File and PR.

## T07 – Create student request interface prototype
**Owner:** B | **Effort:** 4h | **Milestone:** M3 | **Labels:** design  
**Objective:** Demonstrate request submission and tracking.  
**Description:** Create mockup/prototype with Student ID, category, description, priority, submit action, confirmation and request ID/status display.  
**Deliverable:** Student prototype.  
**Acceptance criteria:** All fields and validation/confirmation states represented; request tracking state demonstrated; reviewed.  
**Dependency:** T05.  
**Evidence:** Prototype and PR.

## T08 – Create administrator dashboard prototype
**Owner:** A | **Effort:** 4h | **Milestone:** M3 | **Labels:** design  
**Objective:** Demonstrate administrator workflow.  
**Description:** Create dashboard with open/ongoing/completed summaries, request list, assignment and status update flow.  
**Deliverable:** Admin dashboard prototype.  
**Acceptance criteria:** Status counts, request details, assignment and status update are represented; reviewed.  
**Dependency:** T05.  
**Evidence:** Prototype and PR.

## T09 – Prepare and execute prototype test cases
**Owner:** C | **Effort:** 4h | **Milestone:** M3 | **Labels:** testing, documentation  
**Objective:** Validate key requirements against the prototype.  
**Description:** Execute six test cases and record expected/actual results and pass/fail.  
**Deliverable:** `docs/test-cases.md`.  
**Acceptance criteria:** Six cases cover required fields, category, priority, confirmation, tracking/status and admin dashboard; simulated functions clearly identified.  
**Dependency:** T07 and T08.  
**Evidence:** Test document and PR.

## T10 – Evaluate and document change request
**Owner:** A | **Effort:** 3h | **Milestone:** M4 | **Labels:** change-request, risk, documentation  
**Objective:** Assess the simulated automatic email acknowledgment request.  
**Description:** Analyze scope, effort, cost, schedule, risk and recommendation.  
**Deliverable:** `docs/change-request.md`.  
**Acceptance criteria:** Three-hour provisional estimate analyzed; impacts and recommendation documented; decision recorded.  
**Dependency:** T08 (and change request linked to T10).  
**Evidence:** Change record and PR.

## T11 – Perform final verification and issue review
**Owner:** C | **Effort:** 3h | **Milestone:** M4 | **Labels:** testing, documentation  
**Objective:** Verify deliverables and evidence before closure.  
**Description:** Review completed Issues, files, PR merges, milestones, board and unresolved work.  
**Deliverable:** `docs/verification-closure.md`.  
**Acceptance criteria:** Evidence checked; incomplete work explicitly documented; verification result recorded.  
**Dependency:** T09 and T10.  
**Evidence:** Verification report and PR.

## T12 – Consolidate final report and closure documents
**Owner:** B | **Effort:** 3h | **Milestone:** M4 | **Labels:** documentation  
**Objective:** Consolidate project evidence and lessons learned.  
**Description:** Assemble final PDF/report outline and closure content with links and screenshots.  
**Deliverable:** Final PDF and `docs/verification-closure.md` updated as needed.  
**Acceptance criteria:** Required report sections included; GitHub links work; screenshots and evidence included; lessons learned recorded.  
**Dependency:** T11.  
**Evidence:** Final report and PR.
