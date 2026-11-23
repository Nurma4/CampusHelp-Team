# Schedule, Dependencies and Budget

## 10-working-day schedule (adapt calendar dates to lecturer's assigned start)
| Task | Days | Owner | Effort | Milestone |
|---|---|---|---:|---|
| T01 Project charter | 1–2 | A | 4h | M1 |
| T02 Requirements | 1–2 | B | 4h | M1 |
| T03 Scope and WBS | 2 | C | 4h | M1 |
| T04 Schedule/dependencies/budget | 3–4 | A | 4h | M2 |
| T05 Wireframes | 3–4 | B | 4h | M2 |
| T06 Risk/quality plan | 3–4 | C | 4h | M2 |
| T07 Student interface prototype | 5–7 | B | 4h | M3 |
| T08 Admin dashboard prototype | 5–7 | A | 4h | M3 |
| T09 Test cases and execution | 6–7 | C | 4h | M3 |
| T10 Change request evaluation | 8–9 | A | 3h | M4 |
| T11 Final verification | 9–10 | C | 3h | M4 |
| T12 Final report/closure | 9–10 | B | 3h | M4 |
| **Total** | | | **45h** | |

## Dependencies (Finish-to-Start)
- T03 depends on T01.
- T04 depends on T03.
- T05 depends on T02.
- T07 depends on T05.
- T08 depends on T05.
- T09 depends on T07 and T08.
- T11 depends on T09 and T10.
- T12 depends on T11.

T02 is not listed as dependent on T01; it may begin independently.

## Critical / delay-sensitive tasks
- **T05 Wireframes:** T07 and T08 cannot start until wireframes are sufficiently reviewed.
- **T07/T08 prototypes:** Both are predecessors of T09 testing; delay in either may delay testing.
- **T09 testing:** Testing and defect review feed final verification.
- **T11 verification:** T12 closure report depends on verification.

## Budget
| Member | Planned hours | Rate | Cost |
|---|---:|---:|---:|
| A | 15h | 50,000 UZS/h | 750,000 UZS |
| B | 15h | 50,000 UZS/h | 750,000 UZS |
| C | 15h | 50,000 UZS/h | 750,000 UZS |
| **Total** | **45h** | | **2,250,000 UZS** |

This is a simulated academic planning cost, not a payment.
