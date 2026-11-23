# Requirements & Stakeholder Analysis

## Functional requirements
- **FR-01 Submit request:** Student can submit a request with Student ID, category, description, and priority.
- **FR-02 Categorize:** Student can choose a service category (IT, classroom maintenance, library, administrative services).
- **FR-03 Track:** System assigns a unique request ID and presents it to the student.
- **FR-04 Assign:** Administrator can assign a request to a responsible staff member or service team.
- **FR-05 Update status:** Authorized administrator can update request status; student can view status.
- **FR-06 Dashboard:** Dashboard displays counts/lists of open, ongoing and completed requests.

## Non-functional / quality requirements
- Clear and simple interface.
- Required fields and validation messages are shown.
- Status and request ID are easy to locate.
- Prototype is usable for demonstration; production security and availability are outside scope.
- Mock data should not contain real sensitive student information.

## Stakeholders
| Stakeholder | Interest / need | Engagement |
|---|---|---|
| Students | Submit and track requests | User feedback / mockup review |
| IT support | Receive and resolve technical requests | Validate IT category and workflow |
| Maintenance staff | Receive facilities requests | Validate assignment and status flow |
| Library staff | Handle library requests | Validate category and workflow |
| Administrators | Assign, prioritize and monitor requests | Review dashboard |
| University administration (sponsor) | Visibility, accountability and service improvement | Approve scope (simulated) |
| Project team | Deliver planning and prototype evidence | Daily coordination |

## User story examples
- As a student, I want to submit a categorized request so that it reaches the appropriate service.
- As a student, I want a unique request ID so that I can track my request.
- As an administrator, I want to assign requests so that ownership is clear.
- As an administrator, I want to update status so that students see progress.
- As an administrator, I want a dashboard so that I can monitor workload.
