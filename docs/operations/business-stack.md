# Boilerhaus Business Stack Research and Readiness Guide v1

## Purpose

This document gives Boilerhaus a practical guide for researching, comparing, and deciding on the business stack needed to operate ScopeHouse well.

It also includes a full to do list of what needs to be ready before moving forward with more serious business activity.

This is not a final stack decision document.

It is a founder research and readiness guide.

## How to use this document

Use this in order.

1. Work category by category.
2. Shortlist only 2 to 3 options per category.
3. Score each option with the same criteria.
4. Delay final decisions on anything that does not block current testing.
5. Turn decisions into a tight implementation checklist only after the research is good enough.

## Core rule

Do not decide the whole business stack at once.

You only need enough decisions to keep testing, collecting revenue, and staying organized.

## Decision stages

### Stage 1, needed now

These decisions support testing, early operations, and basic business readiness.

- legal entity and business name path
- bookkeeping path
- invoicing and payments
- email
- operating docs and file storage
- product analytics

### Stage 2, needed soon

These decisions support repeatability after the first testing wave.

- CRM or pipeline workflow
- support workflow
- proposal and agreement workflow
- contract signing flow
- content workflow

### Stage 3, needed later

These decisions should wait until real pressure exists.

- full self-hosted business stack
- heavier finance automation
- deeper integrations
- ERP style tools
- large support platforms
- advanced BI or reporting stack

## Research scorecard

For each tool or option, score from 1 to 5.

- setup effort
- monthly cost
- maintenance burden
- Canadian fit
- founder trust in running it
- migration pain later
- how well it fits a one-person or very small team workflow
- how well it protects focus during testing

Use this template:

### Option name

- category:
- hosted or self-hosted:
- shortlist status:
- setup effort:
- monthly cost:
- maintenance burden:
- Canadian fit:
- trust in running it:
- migration pain later:
- small team fit:
- focus protection:
- notes:
- final decision:

## Category-by-category research checklist

## 1. Legal entity and business name

Goal:
Decide how Boilerhaus should exist legally and how ScopeHouse sits under it.

Research questions:

- should Boilerhaus be an Ontario named corporation or numbered corporation first
- should ScopeHouse be registered immediately as a business name
- what founder records are needed after incorporation
- who will handle legal review when needed

Deliverable:

- legal entity decision
- filing path
- business name decision for ScopeHouse
- founder action list for incorporation

Done when:

- you know what to file
- you know the order of filing
- you know what docs to save

## 2. Bookkeeping and accounting

Goal:
Choose the bookkeeping system that keeps records clean without creating too much admin burden.

Research options:

- Wave
- Manager
- Akaunting
- spreadsheet only, only as baseline comparison

Research questions:

- does it support the level of accounting discipline you want
- how hard is setup and ongoing reconciliation
- can it handle Canadian tax and year-end handoff cleanly
- does it fit service revenue and software revenue together
- if self-hosted, how much upkeep will it create

Deliverable:

- bookkeeping system decision
- bookkeeping owner decision, founder only or founder plus accountant
- monthly bookkeeping routine outline

Done when:

- one system is chosen
- a first chart of accounts is planned
- monthly reconciliation rhythm is defined

## 3. Invoicing and proposals

Goal:
Choose how Boilerhaus sends invoices, proposals, and service offers.

Decision:
Use Wave for invoicing.

Research options:

- Stripe invoicing only
- Invoice Ninja
- Wave invoicing
- accounting tool native invoicing if chosen

Research questions:

- do you want invoicing tied closely to accounting or separated from it
- do you need proposals and quotes, not only invoices
- do you need self-hosting enough to justify the setup
- can the system support both founder-led service work and future product billing

Deliverable:

- invoicing system decision
- proposal workflow decision
- first service invoice and proposal template plan

Current choice:

- invoicing system: Wave
- proposal path: keep it lightweight alongside Wave until a stronger proposal workflow is needed

Done when:

- you know how money will be requested
- you know how proposals will be sent
- you know how invoices will be tracked

## 4. Payments

Goal:
Choose how Boilerhaus gets paid.

Decision:
Use Wave for current payment collection tied to invoices.

Research questions:

- will Stripe be the main processor for both service and product payments
- what payment methods matter most early
- what will happen for invoiced service work versus future product subscriptions

Deliverable:

- payment processor decision
- first payment collection workflow
- refund and invoice handling notes

Current choice:

- payment processor for current invoiced work: Wave
- revisit product subscription billing separately if ScopeHouse later needs a stronger recurring billing system

Done when:

- you can take money cleanly
- the money lands in the right account
- the bookkeeping path is clear

## 5. Email and communications

Goal:
Choose the business email and calendar setup.

Current choice:

- domain email provider: IONOS
- public ScopeHouse address: `scopehouse@boilerhaus.org`
- current working inbox: `chris@boilerhaus.org`
- `scopehouse@boilerhaus.org` forwards to `chris@boilerhaus.org`
- both `scopehouse@boilerhaus.org` and `chris@boilerhaus.org` forward to `128boilerrat@gmail.com`
- `chris@boilerhaus.org` is the main operating inbox for the project right now

Research options:

- Google Workspace
- Microsoft 365
- anything else only if it clearly beats them

Research questions:

- which system will be the company standard for email and calendar
- what domain email addresses need to exist first
- how will support or contact email be routed later

Deliverable:

- email provider decision
- initial email addresses list
- domain and admin ownership checklist

Current working address:

- `scopehouse@boilerhaus.org`
- `chris@boilerhaus.org`

Done when:

- business email is live
- founder admin access is secure
- key aliases are planned

## 6. Docs, files, and internal workspace

Goal:
Decide how Boilerhaus should use Nextcloud and whether it is enough for internal operations.

Research options:

- Nextcloud only
- Nextcloud plus Collectives, Deck, and Tables
- external alternative only as comparison

Research questions:

- can Nextcloud become the internal source of truth for docs and workflow
- should sales pipeline live in Deck or somewhere else
- should trackers live in Tables or a spreadsheet
- how should folders be structured for legal, finance, ops, and product docs

Deliverable:

- Nextcloud operating model
- folder structure plan
- app usage plan, Collectives, Deck, Tables, Files

Done when:

- you know what Nextcloud is for
- you know what should not live in Nextcloud
- internal docs are not scattered

## 7. Product analytics

Goal:
Choose how to measure product usage and activation.

Research options:

- PostHog
- lighter analytics alternatives only if they clearly fit better

Research questions:

- what events matter most for ScopeHouse
- do you need self-hosted analytics now or later
- how much setup effort is acceptable during testing
- what is the first success moment to track

Deliverable:

- analytics tool decision
- first event list
- first dashboard list

Done when:

- you know what to instrument
- you know what activation means
- you know what product signals you care about most

## 8. CRM and pipeline workflow

Goal:
Choose how to manage leads, design partners, and service opportunities.

Research options:

- current tracker plus Nextcloud workflow
- lightweight CRM
- HubSpot or similar, only if clearly needed

Research questions:

- is the current tracker enough for now
- when does a full CRM become worth it
- can Nextcloud Deck and Tables handle the first real pipeline

Deliverable:

- interim pipeline decision
- conditions that would trigger adopting a larger CRM

Done when:

- no leads are going stale
- next action is visible for every active lead

## 9. Contracts and signatures

Goal:
Choose how proposals, agreements, and signatures will work.

Research options:

- simple PDF plus email acceptance
- Dropbox Sign or similar
- other signature tool

Research questions:

- when do you need formal signature flow versus simple agreement by email
- what needs legal review before sending to customers
- how will signed docs be stored and linked to invoices

Deliverable:

- signature flow decision
- first contract template review path

Done when:

- you know how a paid service engagement gets documented
- signed files are stored in one place

## 10. Security and access

Goal:
Set the baseline for founder security and account control.

Research questions:

- which password manager will be used
- where are recovery codes stored
- who owns domains, VPS, GitHub, Stripe, and email admin access
- what should be backed up automatically

Deliverable:

- password manager decision
- critical account inventory
- backup checklist

Done when:

- critical systems are not dependent on memory or loose notes
- admin access is organized and recoverable

## Full business readiness to do list

Primary tracker:

- private GitHub Project `BoilerHAUS / Full business readiness to do list`

## Phase 1, current testing phase

Goal:
Keep testing ScopeHouse while reducing chaos.

- [ ] test ScopeHouse with real scenarios for several days
- [ ] log bugs, friction, and trust breaks
- [ ] note where onboarding feels unclear
- [ ] note what first success moment feels strongest
- [ ] note what would stop a real user from trusting the product
- [ ] keep business stack decisions in shortlist mode only

## Phase 2, legal and structural readiness

- [ ] decide Ontario corporation path for Boilerhaus
- [ ] decide whether Boilerhaus will be named or numbered first
- [ ] decide whether ScopeHouse will be registered as a business name immediately
- [ ] prepare incorporation documents and filing order
- [ ] create founder legal document folder
- [ ] decide who will review legal and tax issues when needed

## Phase 3, finance readiness

- [ ] choose bookkeeping shortlist, 2 to 3 options max
- [ ] research each against the scorecard
- [ ] choose accounting system
- [ ] open business bank account once legal entity exists
- [x] choose invoicing and proposal path, Wave
- [x] choose payment collection path, Wave
- [ ] create first invoice template
- [ ] create first proposal or service offer template
- [ ] define monthly bookkeeping routine
- [ ] decide when accountant review happens

## Phase 4, operating stack readiness

- [x] create `scopehouse@boilerhaus.org`
- [x] choose business email provider, IONOS
- [ ] set up domain email and admin controls
- [ ] define Nextcloud role in the stack
- [ ] create Nextcloud folder structure for legal, finance, ops, and customer work
- [ ] decide whether to use Collectives, Deck, and Tables
- [ ] move core operating docs into the chosen structure
- [ ] set up password manager and secure critical account access
- [ ] list all admin accounts and owners

## Phase 5, sales and customer readiness

- [ ] confirm discovery call workflow
- [ ] confirm demo workflow
- [ ] confirm founder-led service offer workflow
- [ ] choose proposal and signature flow
- [ ] define where leads are tracked
- [ ] define when a lead becomes design partner, service, pilot, or no fit
- [ ] define where signed docs and invoices are stored

## Phase 6, analytics and learning readiness

- [ ] choose product analytics shortlist
- [ ] decide what event tracking is needed now
- [ ] define activation and first success moment clearly
- [ ] define first dashboard or weekly metrics view
- [ ] instrument the app only after the core event list is agreed

## Phase 7, launch and operational readiness

- [ ] review the beta onboarding checklist
- [ ] review the launch readiness checklist
- [ ] confirm who handles support and follow-up
- [ ] confirm weekly business review cadence
- [ ] confirm what must be true before inviting more users

## Priority order

If everything feels overwhelming, do this in order.

### First

- keep testing ScopeHouse
- decide legal path
- shortlist bookkeeping options
- shortlist invoicing options
- define how Nextcloud will be used

### Second

- choose bookkeeping system
- choose invoicing and payment flow
- set up business email
- set up security basics

### Third

- choose analytics path
- refine pipeline workflow
- choose signature flow

### Fourth

- expand only if real usage creates pressure

## What to avoid

- deciding the entire stack in one weekend
- installing tools just because they are self-hosted
- building a system you do not trust yourself to maintain
- choosing a tool without knowing how painful migration will be later
- using testing stress as a reason to delay basic legal and finance readiness forever

## Decision checkpoint template

Use this after each category.

### Category

- final choice:
- why this won:
- what you are giving up:
- what must be set up first:
- who owns setup:
- when this needs to be live:

## Final reminder

You do not need the perfect business stack.

You need:

- a legal path
- a money path
- an operations path
- a learning path

Everything else can follow after the first real pressure appears.
