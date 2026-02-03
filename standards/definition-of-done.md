# Definition of Done (DoD)

The Definition of Done defines the **minimum, non-negotiable completion criteria**
required for work to be considered complete, usable, and potentially releasable
in an enterprise environment.

Work that does not meet **all** DoD criteria is **not Done**, regardless of effort,
time spent, or external pressure.

---

## Purpose

The Definition of Done exists to:

- Ensure consistent quality across teams
- Prevent incomplete or fragile work from being promoted
- Enable reliable Sprint Reviews and release decisions
- Reduce rework, defects, and operational risk
- Establish trust in delivery reporting

“Almost done” is not a delivery state.

---

## Completion Criteria

A backlog item is considered **Done** only when **all** of the following are true:

### Functional Completion
- Acceptance criteria are fully met and validated
- Business intent is satisfied without known gaps
- Edge cases and error scenarios are handled

### Code & Build Quality
- Code is peer-reviewed and merged per engineering standards
- No critical or high-severity issues remain open
- Builds pass without warnings that indicate instability

### Testing
- Automated tests are executed successfully
- Required manual testing is completed
- Regression impact is assessed and addressed
- No unresolved defects that violate quality thresholds

### Documentation & Traceability
- User-facing and technical documentation is updated as required
- Operational or support notes are captured where applicable
- Decisions and assumptions are documented

### Security & Compliance
- Security checks are completed as required
- Compliance requirements are satisfied or explicitly approved
- No known policy violations remain unresolved

### Deployment & Operability
- Work is deployable via standard pipelines
- Feature toggles or configuration are in place if needed
- Monitoring, logging, and rollback considerations are addressed

---

## Release Readiness

Completion does not automatically imply release approval.

However, Done work must be:
- Technically releasable
- Operationally supportable
- Safe to deploy without extraordinary intervention

Release decisions remain a product and business choice.

---

## Guiding Principle

**Done means usable, releasable, and supportable.**

Anything less is incomplete and must not be presented as finished.

---

## Enforcement Expectations

The Definition of Done is enforced through:

- Sprint Planning (commitment discipline)
- Sprint Review (increment validation)
- Scrum Master facilitation
- Product Owner acceptance decisions
- Leadership support under delivery pressure

Standards that collapse under pressure are not standards.

---

## Common Anti-Patterns (Not Done)

The following do **not** meet the Definition of Done:

- “Code complete” without testing
- Deferred documentation
- Known defects postponed to “later”
- Partial implementations labeled complete
- Manual steps required to deploy without approval

---

## Expected Outcomes

Consistent application of this DoD results in:

- Higher delivery predictability
- Reduced defect leakage
- Stronger Sprint integrity
- Increased stakeholder trust
- Fewer last-minute surprises

---

## Relationship to Other Standards

This Definition of Done works in conjunction with:

- `definition-of-ready.md`
- `scrum-events/`
- `roles/`

Ready protects the Sprint start.  
Done protects the Sprint outcome.

