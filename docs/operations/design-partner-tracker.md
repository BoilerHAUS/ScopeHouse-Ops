# ScopeHouse Design Partner Tracker v1

## Purpose

Create a simple operating tracker for design partner outreach, qualification, follow-up, and onboarding.

This tracker should work for a founder-led workflow first.

It should be simple enough to run in:

- Google Sheets
- Airtable
- Notion table
- a lightweight CRM

## Core rule

Do not treat this like a bloated CRM.

The tracker exists to answer five questions fast:

1. Who is this person or account?
2. How good is the fit?
3. What stage are they in?
4. What is the next action?
5. Are they a design partner, a paid-service lead, or only research?

## Recommended tracker structure

Use one row per lead or account.

If one account has multiple people involved, keep one account row and note the main contact plus other stakeholders in notes.

## Required fields

### Identity and source

- account_name
- primary_contact_name
- primary_contact_role
- email_or_contact_method
- segment
- source
- date_added

### Project context

- project_type
- project_stage
- project_size_notes
- location_optional

### Qualification

- hard_gate_passed
- complexity_score
- problem_intensity_score
- timing_urgency_score
- decision_authority_score
- workflow_fit_score
- collaboration_value_score
- payment_signal_score
- total_score
- qualification_label
- reason_tag

### Pipeline control

- stage
- last_contact_date
- next_action
- next_action_due_date
- owner

### Opportunity path

- design_partner_candidate
- paid_service_candidate
- paid_pilot_candidate
- follow_up_priority

### Insight capture

- top_pain_point
- current_tools
- strongest_broken_workflow
- willingness_to_pay_notes
- best_quote
- notes

## Segment options

Use one of these:

- homeowner
- solo-gc
- consultant
- design-build

## Project stage options

Use one of these:

- idea
- planning
- quote-collection
- pre-construction
- active-job
- closeout

## Qualification label options

Use one primary label:

- design-partner-priority
- design-partner-possible
- research-only
- paid-service-candidate
- paid-pilot-candidate
- not-now

## Reason tag options

Use one main reason tag where useful:

- too-small
- too-early
- weak-pain
- weak-authority
- weak-fit
- no-budget-signal
- strong-homeowner-fit
- strong-pro-fit

## Stage definitions

Keep stages narrow and operational.

### 1. identified

Lead is added, but no contact yet.

### 2. outreach-sent

Initial outreach is sent. Waiting for reply.

### 3. replied

Lead has replied, but no discovery call yet.

### 4. discovery-scheduled

Discovery call is booked.

### 5. interviewed

Discovery call happened. Qualification is logged.

### 6. qualified

Lead passed the rubric strongly enough for active follow-up.

### 7. design-partner-invite

Lead has been invited into the design partner path.

### 8. onboarding

Lead is actively being onboarded into beta, founder-led setup, or workflow testing.

### 9. active-design-partner

Lead is participating and giving live feedback.

### 10. paid-service

Lead is in a paid founder-led setup or planning support engagement.

### 11. paid-pilot

Lead is using ScopeHouse in a paid pilot path.

### 12. parked

Lead is not dead, but timing or fit is not right now.

### 13. closed-lost

Lead is not a fit or is no longer worth active follow-up.

## Follow-up priority options

Use:

- high
- medium
- low

### High

Use for:

- strong design partner candidate
- active project
- clear pain
- follow-up due within 7 days

### Medium

Use for:

- possible design partner
- useful research lead
- timing not urgent but worth keeping warm

### Low

Use for:

- weak fit
- weak urgency
- no live next step

## Recommended field notes

### Source examples

- referral
- outbound
- waitlist
- network
- content
- warm-intro

### Owner

Use the person responsible for next action.
For now this is likely just the founder.

## Minimum viable tracker view

If you want the smallest useful version, start with these columns only:

- account_name
- primary_contact_name
- segment
- project_stage
- hard_gate_passed
- total_score
- qualification_label
- stage
- last_contact_date
- next_action
- next_action_due_date
- follow_up_priority
- top_pain_point
- notes

Then add the rest once interviews are flowing.

## Recommended views

### View 1, all active leads

Show:

- account_name
- segment
- stage
- qualification_label
- next_action_due_date
- follow_up_priority

### View 2, design partner priority

Filter:

- qualification_label = design-partner-priority

### View 3, paid-service candidates

Filter:

- paid_service_candidate = yes

### View 4, parked leads

Filter:

- stage = parked

### View 5, follow-up due this week

Filter:

- next_action_due_date within current week

## Data entry rules

1. Update the row immediately after each interview.
2. Never leave next_action blank if the lead is still active.
3. If the lead is parked or closed-lost, record why.
4. Keep best_quote short and verbatim where possible.
5. Re-score only when major project timing or fit changes.

## Example row shape

- account_name: Smith Kitchen Renovation
- primary_contact_name: Jane Smith
- segment: homeowner
- project_stage: quote-collection
- hard_gate_passed: yes
- total_score: 18
- qualification_label: design-partner-priority
- reason_tag: strong-homeowner-fit
- stage: qualified
- last_contact_date: 2026-04-01
- next_action: schedule design partner follow-up
- next_action_due_date: 2026-04-05
- follow_up_priority: high
- top_pain_point: quote comparison confusion

## Recommended next action templates

Use short, concrete actions:

- send first outreach
- book discovery call
- send follow-up note
- score lead from interview
- invite to design partner path
- schedule onboarding session
- send paid service offer
- park until project starts
- close lost and log reason

## Relationship to other docs

Use this tracker with:

- `docs/product/customer-interview-script.md`
- `docs/operations/design-partner-rubric.md`

The interview script collects the signals.
The rubric scores the signals.
The tracker runs the pipeline.
