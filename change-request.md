# Change Request CR-01 – Automatic Email Acknowledgment

**Requestor:** Simulated university administration  
**Date:** Day 6 (as stipulated in assignment)  
**Requested change:** Automatically send an email acknowledgment when a student submits a service request.

## Scope assessment
Live email acknowledgment was explicitly excluded from the original scope (live SMS/email services). This request is therefore outside the original scope. A simulated acknowledgment state/message could be demonstrated without implementing a real email integration.

## Estimate and cost
Provisional effort: **3 hours**.  
Planning rate: 50,000 UZS/hour.  
Additional simulated cost: **150,000 UZS**.

## Impact
- **Schedule:** Adds effort during the execution/closure period; may compete with prototype testing and verification.
- **Tasks:** T07 student submission flow, T09 testing, T11 final verification and documentation may be affected.
- **Risk:** Integration/verification time is limited; real email service setup is outside scope and could introduce dependencies.
- **Scope:** Requires a baseline change if actual email integration is approved.

## Recommendation: DEFER real integration; APPROVE a simulated acknowledgment
The team recommends deferring real email delivery because it was explicitly out of scope and the ten-day schedule and no-external-service-charges constraint are tight. Approve only a simulated confirmation screen or documented acknowledgment flow if the prototype can accommodate it within the provisional three hours, without reducing required testing.

## Decision record
Decision: **Defer real integration; allow simulation for demonstration.**  
Decision owner: Project Manager (Student A), subject to simulated sponsor/team review.  
Record the decision and any updated Issue scope in GitHub.
