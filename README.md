# SDLC Practice

## 1. What is SDLC?

SDLC stands for Software Development Life Cycle. It is a step-by-step process for building software in a clear and organized way. Teams use SDLC to plan work, reduce mistakes, and deliver a product that meets user needs. Each phase has a goal, and teams move from one phase to the next in order. Following SDLC helps teams work together and improve quality over time.

## 2. Core Phases

### Requirements

In this phase, the team finds out what the software should do. They talk to users, write user stories, and define clear goals and rules.

### Design

The team plans how the software will look and work. They create wireframes, system diagrams, and technical plans before writing code.

### Implementation

Developers write the actual code based on the design. They build features, connect systems, and follow coding standards.

### Testing

The team checks if the software works correctly. They find bugs, test edge cases, and make sure the product meets the requirements.

### Deployment

The finished software is released to users. The team publishes it to servers or app stores and makes it available to the public.

### Maintenance

After launch, the team fixes bugs, adds improvements, and keeps the software secure. They also respond to user feedback and changing needs.

## 3. Real-World Example

**Feature:** Instagram Reels — short vertical videos users can create, edit, and share.

- **Requirements:** Instagram identified that users wanted a TikTok-style video experience inside the app. The team defined goals: 15–90 second videos, music, effects, and a dedicated Reels feed.
- **Design:** Designers created mockups for the camera, editing tools, and Reels tab. Engineers planned video storage, compression, and the recommendation algorithm.
- **Implementation:** Developers built the recording UI, video processing pipeline, and Reels feed. They integrated music libraries and sharing features.
- **Testing:** QA tested recording on different phones, checked video quality, and verified the feed loaded quickly. Beta users tested the feature before a full launch.
- **Deployment:** Instagram rolled out Reels region by region and promoted it in the app. The feature went live to millions of users worldwide.
- **Maintenance:** The team fixed playback bugs, improved the algorithm, and added new effects over time. They also monitored performance and user reports after launch.

## 4. Risks of Skipping Phases

1. **Skipping Requirements:** The team may build the wrong features. Users get a product that does not solve their real problems, and time and money are wasted.
2. **Skipping Design:** Developers may write code without a clear plan. This leads to messy architecture, rework, and harder maintenance later.
3. **Skipping Testing:** Bugs reach users in production. This can cause crashes, data loss, security issues, and loss of user trust.

# SDLC Phase Walkthrough

## 1. Phase Inputs and Outputs

### Requirements

- **Input:** User needs, business goals, and stakeholder feedback.
- **Output:** A requirements document with clear features, rules, and acceptance criteria.

### Design

- **Input:** Approved requirements and project goals.
- **Output:** Wireframes, system diagrams, and a technical design plan.

### Implementation

- **Input:** Approved design documents and technical specifications.
- **Output:** Working code that matches the design and requirements.

### Testing

- **Input:** Completed code and test plans based on requirements.
- **Output:** A test report showing passed tests, found bugs, and release readiness.

### Deployment

- **Input:** Tested and approved software ready for release.
- **Output:** Live software available to users in production.

### Maintenance

- **Input:** Live software, user feedback, and bug reports.
- **Output:** Bug fixes, updates, and improved software over time.

## 2. Handoffs

### Design → Implementation

Before development starts, the design phase should be done when:

- Requirements are clear and agreed upon by the team.
- UI mockups and user flows are approved.
- Technical architecture and data models are documented.
- The team knows what "done" looks like for the feature.

### Testing → Release

Before a production release, testing should be done when:

- All planned test cases have been executed.
- Critical and high-priority bugs are fixed or accepted.
- The feature works on target devices and environments.
- QA signs off that the software meets the requirements.

## 3. Roles Snapshot

| Role | Main Phase(s) | Responsibility |
|------|---------------|----------------|
| **PM / Product Owner** | Requirements, Maintenance | Defines what to build, sets priorities, and tracks user needs after launch. |
| **Designer** | Design | Creates UI/UX mockups and defines how the feature should look and feel. |
| **Developer** | Implementation, Maintenance | Writes code, fixes bugs, and improves the software over time. |
| **QA** | Testing | Tests the software, finds bugs, and confirms it meets requirements. |
| **DevOps** | Deployment, Maintenance | Manages servers, releases, monitoring, and production stability. |

## 4. Mini Timeline

**Feature:** Add dark mode

```
┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
│ Request │ → │ Design  │ → │  Build  │ → │  Test   │ → │ Release │ → │ Monitor │
└─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘
```

| Step | Description |
|------|-------------|
| **Request** | Users ask for a dark theme to reduce eye strain at night. |
| **Design** | Designer creates mockups for dark colors and a theme toggle. |
| **Build** | Developers add dark mode styles and a switch in settings. |
| **Test** | QA checks colors, readability, and the toggle on all screens. |
| **Release** | DevOps deploys the update to production for all users. |
| **Monitor** | Team watches for bugs and user feedback after launch. |

# Waterfall, Agile, and Hybrid

## 1. Waterfall Sketch

Waterfall is a sequential SDLC model. Each phase must be completed before the next one starts. The team moves forward in a fixed order and does not go back to earlier phases easily.

**Linear flow:**

```
Requirements → Design → Implementation → Testing → Deployment → Maintenance
```

Waterfall is a more sequential model. One phase is finished before the team moves to the next phase.

### Strengths

- Clear structure and documentation at each stage.
- Easy to plan timelines, budgets, and milestones upfront.

### Weaknesses

- Hard to change requirements after a phase is done.
- Users see working software late in the project.

## 2. Agile Sketch

Agile is a flexible SDLC approach. Teams work in small cycles and deliver value early and often. Instead of planning everything upfront, they learn and adapt as they go.

Key ideas:

- **Short iterations:** Work happens in small time boxes (sprints), usually 1–4 weeks.
- **Working software:** Each iteration aims to deliver usable features, not just documents.
- **Frequent feedback:** Teams review progress often with users and stakeholders.
- **Changing priorities:** Requirements can shift based on new needs or market changes.
- **Continuous improvement:** Teams reflect after each cycle and improve how they work.

**Simple cycle:**

```
Plan → Build → Test → Review → Feedback → Repeat
```

## 3. Project Comparison

### Bank Core System

A bank core system handles accounts, transactions, and sensitive financial data. This type of project needs strong regulation, security, and data integrity. Mistakes can cause legal problems, financial loss, and loss of customer trust.

Because the risk is high, teams often need detailed upfront planning, strict design reviews, and thorough testing before release. A Waterfall or more plan-driven hybrid approach fits well here. Security and compliance rules must be defined early and followed carefully.

**Bank Core System → Hybrid / Waterfall-oriented**

### Marketing Landing Page

A marketing landing page is usually smaller and changes more often. Teams may test headlines, layouts, colors, and call-to-action buttons to improve conversion rates. Analytics and user feedback help them learn quickly what works.

Agile fits better here because teams can ship small updates fast, run experiments, and respond to results without long planning cycles.

**Marketing Landing Page → Agile**

## 4. Hybrid Reality

Most real software teams do not use only Waterfall or only Agile. They mix practices based on project needs.

In a hybrid approach, teams can combine:

- **Upfront planning** for major goals and constraints
- **Architecture** decisions for stable system structure
- **Security requirements** defined early for sensitive areas
- **Short development iterations** for building and delivering features
- **Continuous testing** throughout the cycle
- **User feedback** to guide improvements

This mix helps teams stay safe and structured where risk is high, while staying flexible where change is frequent.

**Takeaway:** The best development model depends on risk, regulation, project size, and how often requirements change.

# ProofChain — Digital Content Integrity Verification System

## Product Overview

**ProofChain** helps users verify when a digital file was registered and whether it has changed since then.

When a user uploads a document or image, the system links the file to a verifiable record. ProofChain does **not** claim the content is true. It only checks whether the current file matches the originally registered file.

**Example — verified file:**

```text
PROOFCHAIN

Document
inspection-report.pdf

Created record
15 Aug 2026 — 14:32

Fingerprint
SHA-256 ✓

Integrity
✓ VERIFIED

Current file matches
original registered fingerprint.
```

**Example — modified file:**

```text
⚠ INTEGRITY CHECK FAILED

Current fingerprint does not match
the registered fingerprint.
```

**MVP scope:**

- Upload a file and register its fingerprint + timestamp
- Verify a file against the registry
- Show audit logs for registration and verification events

---

## 1. Case Study — Why Hybrid?

**Product:** ProofChain — Digital Content Integrity Verification System
**Model:** Hybrid

1. **Integrity requirements must be defined before coding.** The team must agree on what "verified" means before building features.
2. **The data model and verification process require careful design.** Fingerprint, timestamp, and registry relationships need upfront architecture work.
3. **Security-critical functions require strong testing.** A false "VERIFIED" result would break user trust in the entire product.
4. **Dashboard and UX can evolve through Agile iterations.** Upload flow, reports, and admin screens can improve after the core engine works.
5. **Additional verification features can be released gradually.** Team accounts, API access, and batch verification can ship in later sprints.

---

## 2. Phase Checklist — Expected Artifacts

| Phase | Expected Artifacts |
|-------|-------------------|
| **Requirements** | Integrity requirements doc, verification rules, user stories, acceptance criteria, scope for MVP vs future features |
| **Design** | Threat model, verification flow diagram, data model, API design, audit trail design, security notes |
| **Implementation** | Hashing service, verification API, document registry, upload UI, audit logging |
| **Testing** | Modified-file test cases, duplicate registration tests, security tests, integration tests, test report |
| **Deployment** | Environment configuration, secrets management, database migrations, rollout plan, rollback plan |
| **Maintenance** | Monitoring dashboard, failed verification alerts, audit log review, incident response, vulnerability updates |

### Requirements

- [ ] Problem statement and product boundaries documented
- [ ] User stories for upload, verify, and audit views
- [ ] Acceptance criteria for VERIFIED vs FAILED states
- [ ] Non-goals documented (ProofChain does not validate truth of content)

### Design

- [ ] Threat model completed
- [ ] Data model: file record, fingerprint, timestamp, owner, audit event
- [ ] Verification flow diagram
- [ ] API contract for register and verify endpoints

### Implementation

- [ ] SHA-256 fingerprint generation
- [ ] Registry storage for original records
- [ ] Verification endpoint comparing current vs registered fingerprint
- [ ] Audit log for register and verify actions

### Testing

- [ ] Test: unchanged file returns VERIFIED
- [ ] Test: one-byte change returns INTEGRITY CHECK FAILED
- [ ] Test: duplicate registration handled correctly
- [ ] Test: unauthorized access blocked

### Deployment

- [ ] Staging environment validated
- [ ] Migration tested
- [ ] Rollback steps documented
- [ ] Production smoke test completed

### Maintenance

- [ ] Monitoring for verification failures and API errors
- [ ] Audit log retention policy defined
- [ ] Incident playbook for false VERIFIED reports
- [ ] Dependency and security patch process defined

---

## 3. Risk Flag — Design Phase

**Riskiest phase:** Design

If the relationship between **original file → fingerprint → timestamp → verification result** is designed incorrectly, the product loses its core value.

**Example failure:**

```text
Original file  → fingerprint A
Modified file  → fingerprint B
System wrongly shows → ✓ VERIFIED
```

In this case, users trust a product that cannot detect change. The business and technical credibility of ProofChain collapses.

### Mitigation

1. **Threat modeling in Design.** Identify risks such as registry tampering, replay attacks, and incorrect match logic.
2. **Design review with explicit pass/fail rules.** Document exactly when the system must return VERIFIED or FAILED.
3. **Test vectors defined before Implementation.** Include cases where a single character change must fail verification.
4. **Immutable audit trail.** Record who registered a file, when it was verified, and what result was returned.
5. **Staging validation before release.** Run known good and known bad files through the full flow before production rollout.

---

## 4. Teach-back — SDLC in Under 2 Minutes

**Audience:** A non-developer friend
**Goal:** Explain SDLC using ProofChain

---

**Script:**

"Imagine I give you a PDF today. Six months later, someone asks: is this **exactly** the same file?

That is the problem ProofChain solves. But before we build it, we need a clear process. That process is called the **Software Development Life Cycle**, or SDLC.

First, in **Requirements**, we define what the product must do. For ProofChain, we do not say the document is true. We only say whether the current file matches the original registered file.

Next, in **Design**, we plan how verification works. What fingerprint do we store? How do we compare files later? This step is critical because a bad design could show VERIFIED even after a file changes.

Then comes **Implementation**. Developers build the hashing service, registry, and verification checks.

After that, **Testing** checks real scenarios. If one word in the file changes, the result must be FAILED, not VERIFIED.

In **Deployment**, we release the product carefully with migrations, configuration, and rollback plans.

Finally, in **Maintenance**, we monitor errors, review audit logs, and fix issues after launch.

So SDLC is not just coding. It is a step-by-step way to build software safely — especially when trust and accuracy matter."

**Estimated time:** ~90–120 seconds

# Requirements Discovery — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Feature:** File Integrity Verification

**Feature goal:** A user should be able to check whether a file still matches the version previously registered in ProofChain.

---

## 1. Stakeholder Questions

Before building File Integrity Verification, the team should ask these discovery questions:

1. **Who uses the feature?** Who will verify files — internal staff, external clients, auditors, or all of them?
2. **Why do they need verification?** What problem happens today when someone cannot confirm a file is unchanged?
3. **What files need verification?** Which file types, sizes, and sources must be supported in the first release?
4. **What does "verified" mean to the user?** Does the user expect proof of sameness, proof of origin, or proof of legal validity?
5. **What should happen when verification fails?** Should the user see guidance, contact support, download a report, or block a workflow?
6. **How should users identify the original registered file?** Will they search by file name, upload again, enter a record ID, or scan a QR code?
7. **How important is verification speed?** Is verification used occasionally or many times per hour during critical work?
8. **What information should users see in the result?** Do they need only pass/fail, or also timestamp, owner, and change details?
9. **What audit/history information is needed?** Who must see when a file was registered, verified, and by whom?
10. **What security/privacy expectations exist?** Who can access verification results, and what file data can be stored or displayed?

---

## 2. Problem vs Solution

### User Problems

1. A user cannot easily tell whether a stored document has changed since registration.
2. A team member may receive a modified file but has no simple way to compare it with the trusted original.
3. An auditor needs evidence that a file shown today is the same file that was registered earlier.
4. A user may not know which registered record belongs to the file they are holding now.
5. When verification fails, users may not understand what changed, what to do next, or who to notify.
6. Organizations lack a clear history of when files were registered and later checked.

### Premature Solutions

1. Use blockchain to store every fingerprint.
2. Build a mobile app before understanding who verifies files and when.
3. Add AI to detect whether document content is true or false.
4. Require all users to create accounts before any verification can happen.
5. Store full file copies forever in the cloud for every verification request.
6. Launch with support for every file type and size on day one.

Requirements discovery should first validate the problem before selecting technologies or architecture.

---

## 3. Constraints

### Business Constraints

1. The MVP must focus on File Integrity Verification before advanced features such as batch processing or team dashboards.
2. The product must clearly explain that ProofChain checks file sameness, not factual truth.
3. The business needs a simple verification flow that non-technical users can understand.
4. Support and onboarding effort must stay manageable for a small initial user base.

### Time Constraints

1. The first release must deliver core register-and-verify functionality within a limited project timeline.
2. Discovery, design, and testing must fit into planned sprint cycles.
3. Not all requested file types or integrations can be delivered in the first version.
4. Documentation and user guidance must be ready before launch.

### Legal / Compliance Constraints

1. Privacy, retention, and data handling requirements must be reviewed with relevant legal and compliance experts.
2. The system should collect only the data needed to register and verify files.
3. Users may need clear consent and notice about what file metadata is stored.
4. Audit records may need to be kept for an agreed retention period, subject to expert review.
5. Access to verification history may need role-based controls.

### Technical Constraints

1. Verification depends on a reliable fingerprint method such as SHA-256 for registered files.
2. Large files may affect upload time, processing time, and storage costs.
3. The system must return a clear result: match or no match.
4. Verification must work through a defined API and user interface.
5. Failed verification must not be shown as successful under any condition.

---

## 4. Ambiguity Hunt

**Vague request:**

> "Make file verification faster."

This request should **not** be accepted as a final requirement.

### Clarifying Questions

1. What is the current verification time today?
2. What target verification time is expected by users or the business?
3. Which part feels slow — upload, fingerprint calculation, database lookup, or total response time?
4. Which file sizes are considered slow?
5. What is the maximum file size the first release must support?
6. How many verification requests are expected at the same time?
7. Is the problem worse on web, mobile, or API clients?
8. Does "faster" mean average speed, worst-case speed, or both?
9. What test conditions should be used to measure speed — network type, file type, user location?
10. Is speed more important than accuracy, audit detail, or security controls?

These questions help turn a vague request into a measurable requirement.

### Clarified Requirement Example

> For files up to **[defined size]**, 95% of verification requests should return a result within **[agreed target]** under **[defined test conditions]**.

---

## 5. Key Takeaway

Requirements discovery helps the team understand real user needs before building the product.

It separates actual problems from early technical ideas that may not solve the right problem.

**Understand the problem before choosing the solution.**

# User Stories — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Feature focus:** File Integrity Verification

**Product boundary:** ProofChain verifies file integrity against a previously registered version. It does **not** verify whether the information inside the file is factually true.

---

## 1. Main User Stories

### Story 1 — Register a File

**As a** project manager, **I want** to register a file in ProofChain, **so that** my team has a trusted original record for future integrity checks.

### Story 2 — Verify a File

**As a** compliance officer, **I want** to verify an uploaded file against a registered record, **so that** I can confirm whether the file still matches the original version.

### Story 3 — Understand Verification Result

**As a** team member, **I want** to see a clear verification result, **so that** I immediately know whether the file matches or does not match the registered version.

### Story 4 — View Verification History

**As an** external auditor, **I want** to view verification history for a registered file, **so that** I can review when checks were performed and what results were returned.

### Story 5 — Identify Registered Record

**As a** records administrator, **I want** to identify the correct registered record for a file, **so that** verification is performed against the intended original version.

---

## 2. Acceptance Criteria

### Story 1 — Register a File

**Scenario 1 — Valid registration**

**Given** a user uploads a supported file for registration
**When** the file is processed successfully
**Then** ProofChain stores the file fingerprint and registration timestamp
**And** the file is saved as a registered record

**Scenario 2 — Registration result visible**

**Given** a file registration completes successfully
**When** the user views the confirmation screen
**Then** the user sees a success message
**And** the registered file name, record ID, and registration timestamp are displayed

**Scenario 3 — Registered record can later be referenced**

**Given** a file has been registered in ProofChain
**When** the user opens the record details later
**Then** the system shows the same record ID and fingerprint reference
**And** the record can be selected for future verification

**Scenario 4 — Failed registration must not appear successful**

**Given** a file registration fails due to an unsupported file type or processing error
**When** the registration attempt completes
**Then** the system shows a failure message
**And** no registered record is created
**And** the result is not shown as successful

### Story 2 — Verify a File

**Scenario 1 — Identical file returns VERIFIED**

**Given** a file was previously registered in ProofChain
**When** the user uploads the same unchanged file for verification
**Then** the system returns a VERIFIED result
**And** confirms the current fingerprint matches the registered fingerprint

**Scenario 2 — Modified file returns FAILED**

**Given** a file was previously registered in ProofChain
**When** the user uploads a modified version of that file
**Then** the system returns a FAILED or NO MATCH result
**And** does not show the result as VERIFIED

**Scenario 3 — Correct registered version is used**

**Given** multiple registered records exist for similar files
**When** the user verifies a file against a selected record ID
**Then** the system compares the uploaded file only to that registered record
**And** the result reflects the comparison against the correct original version

**Scenario 4 — Processing failure must never return VERIFIED**

**Given** a verification request is submitted
**When** the system cannot complete hashing, lookup, or comparison due to a processing or system failure
**Then** the system returns an error state
**And** does not return VERIFIED

**Scenario 5 — Clear result shown to user**

**Given** a verification request completes
**When** the user views the result screen
**Then** the user sees a clear status of VERIFIED or FAILED / NO MATCH
**And** the registered file name or record ID used for the check is visible

---

## 3. Epic Split

### Epic

**As an** organization, **I want** a complete document integrity management platform, **so that** I can manage and verify all important digital records.

This epic is too large for one sprint. It should be split into smaller shippable stories:

1. **Register one file** — **As a** project manager, **I want** to register one file with a stored fingerprint and timestamp, **so that** the organization has a trusted original record.

2. **Verify one registered file** — **As a** compliance officer, **I want** to verify one uploaded file against a registered record, **so that** I can confirm whether it still matches the original version.

3. **Display verification result** — **As a** team member, **I want** to see a clear pass/fail verification result, **so that** I know immediately whether the file matches the registered version.

4. **View registration details** — **As a** records administrator, **I want** to view registration details for a file, **so that** I can confirm which original record is stored in ProofChain.

5. **View verification history** — **As an** external auditor, **I want** to view verification history for a registered file, **so that** I can review past checks and outcomes.

6. **Manage access to records** — **As a** security administrator, **I want** to manage which users can view or verify registered records, **so that** sensitive file information stays protected.

Each story can be built, tested, and released independently while moving toward the full epic.

---

## 4. Priority Pass

Stories ordered by **user value** and **risk** (highest priority first):

| Priority | Story | User Value | Risk | Reason |
|----------|-------|------------|------|--------|
| 1 | Register a File | High | High | Verification cannot exist without a registered original record |
| 2 | Verify a File | High | High | Core product outcome; an incorrect result breaks trust |
| 3 | Understand Verification Result | High | Medium | Users need an immediate, understandable answer after verification |
| 4 | Identify Registered Record | Medium | High | Verifying against the wrong record creates a false sense of integrity |
| 5 | View Verification History | Medium | Low | Important for audit review, but not required for the first verification flow |

**Priority rule used:** Deliver registration and verification first, then result clarity, record identification, and history.

---

## 5. Key Takeaway

User stories capture intent from the user's perspective.

Acceptance criteria make "done" testable and reduce misunderstanding.

Small, prioritized stories reduce delivery risk and help teams get feedback faster.

# Design Sketch — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Feature focus:** File Integrity Verification

**Product boundary:** ProofChain verifies whether a file matches a previously registered version. ProofChain does **not** determine whether the information inside the document is factually true.

---

## 1. Context Diagram

Who uses ProofChain and what external systems it may interact with:

```text
                         ┌─────────────────────┐
                         │  Identity Provider  │
                         │  (login / roles)    │
                         └──────────┬──────────┘
                                    │
    ┌───────────────────────────────┼───────────────────────────────┐
    │                               │                               │
    ▼                               ▼                               ▼
┌─────────────┐          ┌──────────────────────────────┐   ┌─────────────────┐
│ Project     │ register │                              │   │ Object Storage  │
│ Manager     │ manage   │         ProofChain           │   │ (optional file  │
│ records     │─────────▶│  File Integrity Verification │◀─▶│ upload buffer)  │
└─────────────┘          │                              │   └─────────────────┘
                         │  Internal:                   │
┌─────────────┐ verify   │  - Web UI                    │
│ Compliance  │─────────▶│  - Verification API          │
│ Officer     │          │  - Registry DB               │
└─────────────┘          │  - Audit Log                 │
                         │  - Hashing / Authorization   │
┌─────────────┐ view     │  - Background Jobs           │
│ Team Member │ result   │                              │
└─────────────┘─────────▶│                              │
                         └──────────────────────────────┘
┌─────────────┐ review              ▲
│ External    │ history             │
│ Auditor     │─────────────────────┘
└─────────────┘

┌─────────────┐ manage access
│ Records /   │ and records
│ Security    │─────────────────────▶ ProofChain
│ Admin       │
└─────────────┘
```

**Actors:**

| Actor | Primary responsibility |
|-------|------------------------|
| Project manager | Register and manage records |
| Compliance officer | Verify files |
| Team member | View verification results |
| External auditor | Review verification history |
| Records / security administrator | Manage access and records |

**External systems:**

| System | Purpose |
|--------|---------|
| Identity provider | Authentication and role-based access |
| Object storage (optional) | Temporary upload handling for large files |

Audit logging is handled **inside** ProofChain as an internal responsibility, not as a separate external system.

---

## 2. Component Sketch

Major parts of the system and their responsibilities:

```text
┌─────────────────────────────────────────────────────────────┐
│                        Web UI                               │
│  Upload file, select record, show VERIFIED / FAILED result  │
└───────────────────────────┬─────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                     Verification API                        │
│  Register file, verify file, fetch record, fetch history    │
└───────┬───────────────────────────────┬─────────────────────┘
        │                               │
        ▼                               ▼
┌──────────────────┐           ┌────────────────────┐
│ Hashing Service  │           │ Authorization Layer│
│ Generate/compare │           │ Check user access  │
│ SHA-256 values   │           │ to records/history │
└────────┬─────────┘           └────────────────────┘
         │
         ▼
┌──────────────────┐           ┌────────────────────┐
│ Registry DB      │           │ Audit Log          │
│ File records,    │           │ Record register /  │
│ file versions,   │           │ verify events      │
│ fingerprints     │           └────────────────────┘
└──────────────────┘
         ▲
         │
┌──────────────────┐
│ Background Jobs  │
│ Process large    │
│ file hashing     │
│ asynchronously   │
└──────────────────┘
```

These are **logical components** within the ProofChain application. They do **not** represent separately deployed microservices.

For the MVP, components such as **Hashing Service** and **Authorization Layer** can live as modules or layers inside the same application.

| Component | Responsibility |
|-----------|----------------|
| **Web UI** | Lets users register files, run verification, and view results/history |
| **Verification API** | Handles register, verify, record lookup, and history requests |
| **Hashing Service** | Creates and compares SHA-256 fingerprints |
| **Registry DB** | Stores file records, file versions, fingerprints, and timestamps |
| **Audit Log** | Records who registered or verified a file and the outcome |
| **Authorization Layer** | Controls which users can access records and history |
| **Background Jobs** | Processes large files without blocking the user interface |

---

## 3. Data Sketch

Main entities and relationships for **File Integrity Verification**.

This is a **conceptual data model**, not a SQL schema.

```text
User
 │
 │ creates
 ▼
FileRecord ──────── has many ──────── FileVersion ──────── has one ──────── Fingerprint
                                              │
                                              │ has many
                                              ▼
                                       VerificationEvent
                                              │
User ─────────────────────────────────────────┘
 │ performs

FileRecord / FileVersion / VerificationEvent
 │
 │ related to
 ▼
AuditEntry
```

| Entity | Description | Key fields |
|--------|-------------|------------|
| **User** | Person using the system | `user_id`, `role` |
| **FileRecord** | Logical file identity in ProofChain | `record_id`, `file_name`, `owner_id` |
| **FileVersion** | One registered version of a file | `version_id`, `record_id`, `registered_at`, `version_number` |
| **Fingerprint** | Hash value for one file version | `algorithm`, `hash_value` |
| **VerificationEvent** | One verification attempt against a file version | `verification_id`, `version_id`, `result`, `verified_at`, `user_id` |
| **AuditEntry** | Immutable activity log | `event_type`, `actor_id`, `timestamp`, `outcome`, `related_entity` |

**Relationships:**

- One **User** can create many **FileRecord** entries
- One **FileRecord** can have many **FileVersion** entries
- One **FileVersion** has one **Fingerprint**
- One **FileVersion** can have many **VerificationEvent** entries
- One **User** can perform many **VerificationEvent** entries
- **FileRecord**, **FileVersion**, and **VerificationEvent** can each relate to **AuditEntry** records

Even if the MVP initially creates only one **FileVersion** per **FileRecord**, keeping **FileVersion** in the conceptual model makes future version history explicit.

**Registration flow:**

1. User registers a file
2. **FileRecord** is created
3. Initial **FileVersion** is created
4. **Fingerprint** is generated
5. **AuditEntry** is recorded

**Verification flow:**

1. User selects a registered version
2. Uploaded file fingerprint is calculated
3. Result is compared with the registered **Fingerprint**
4. **VerificationEvent** is recorded
5. **AuditEntry** is recorded

---

## 4. Trade-off Note

### Decision

**Store only the file fingerprint and metadata, not the full file content by default.**

### Why this was chosen

- Lower storage requirements
- Smaller privacy exposure
- Simpler MVP
- Clear integrity comparison through fingerprint matching
- Matches the product goal: check integrity, not host file content

### Disadvantage

If ProofChain stores only a fingerprint and metadata, it **cannot reconstruct, restore, or serve the original file from the fingerprint alone**.

### Alternative rejected

**Permanent full-file storage by default.**

### Why it was rejected

- Higher storage and security burden
- More privacy and retention concerns
- Slower uploads and higher infrastructure cost
- Not required for MVP integrity checking if users can re-upload a file for verification

### Future option

If future requirements include archival or original-file retrieval, object storage can be introduced intentionally.

### Takeaway

Design should support the smallest trustworthy solution first, then add heavier storage or processing only if requirements prove it is necessary.

---

## 5. Key Takeaway

Design connects requirements to implementation.

A simple context diagram, component sketch, and data sketch help the team agree on boundaries before writing large amounts of code.

Trade-off notes make important decisions visible early and reduce rework later.

# Mini Spec — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Feature:** File Integrity Verification
**Status:** MVP specification

**Product boundary:** ProofChain verifies whether a file matches a previously registered version. It does **not** determine whether the information inside the document is factually true.

---

## Problem

Teams share digital files over time but cannot easily prove a file is still the exact same version that was registered earlier. ProofChain solves this by registering a file fingerprint and later comparing an uploaded file against that registered version.

---

## Users

| User | Need |
|------|------|
| Project manager | Register and manage trusted file records |
| Compliance officer | Verify files against registered versions |
| Team member | Understand verification results quickly |
| External auditor | Review verification history |
| Records / security administrator | Identify records and manage access |

---

## MVP Scope

**In scope:** Register a file, verify a file, show **VERIFIED** / **NO MATCH** / **ERROR** results, identify the correct record, view history for a selected record.

**MVP file type / size:** TBD — supported file types and maximum file size must be agreed before implementation.

**Out of scope for MVP:** blockchain, AI truth-checking, full-file archival by default, batch verification, mobile app, organization-wide history reporting, advanced enterprise permission management UI.

**MVP build order:** Register → Verify → Show result → Identify record → View history

---

## User Stories (MVP)

1. **Register a File** — **As a** project manager, **I want** to register a file, **so that** my team has a trusted original record.
2. **Verify a File** — **As a** compliance officer, **I want** to verify an uploaded file, **so that** I can confirm it still matches the registered version.
3. **Understand Verification Result** — **As a** team member, **I want** a clear **VERIFIED**, **NO MATCH**, or **ERROR** result, **so that** I know whether the file matches or whether the check could not be completed.
4. **View Verification History** — **As an** authorized user, **I want** to view verification history for a selected **FileRecord**, **so that** I can review past checks for that record. Organization-wide history is not an MVP requirement.
5. **Identify Registered Record** — **As a** records administrator, **I want** to find the correct record, **so that** verification uses the intended version.

---

## Acceptance Criteria (Core)

### Story 1 — Register a File

- Successful registration stores fingerprint, record ID, file name, and timestamp.
- User sees confirmation with record details.
- Unsupported file type, oversize file, or processing failure does not create a record or show success.
- Registered record can be selected later for verification.

### Story 2 — Verify a File

- Identical file → **VERIFIED**
- Different or modified file → **NO MATCH** (never **VERIFIED**)
- Verification compares against the selected registered version only.
- Processing or system failure → **ERROR** (never **VERIFIED**)
- Result screen shows **VERIFIED**, **NO MATCH**, or **ERROR**, plus the record ID or file name used

**Result terminology:**

| Condition | User-facing result |
|-----------|-------------------|
| Identical file | **VERIFIED** |
| Modified file | **NO MATCH** |
| Processing failure | **ERROR** |

---

## Constraints

| Type | Constraint |
|------|------------|
| **Business** | MVP focuses on register + verify before advanced features |
| **Time** | First release must fit planned sprint cycles |
| **Legal / Compliance** | Privacy, retention, and data-handling requirements must be reviewed with appropriate experts |
| **Technical** | Use SHA-256 fingerprinting; **ERROR** and **NO MATCH** must never be shown as **VERIFIED** |
| **Security** | Authentication uses the defined Identity Provider; protected records and verification history require authorized access; audit information must not be silently modified through normal user workflows |
| **Product** | Store fingerprint + metadata by default, not full file content |

**Key trade-off:** ProofChain stores fingerprint + metadata rather than full files by default. This reduces storage and privacy exposure, but the system cannot reconstruct the original file from the fingerprint alone.

---

## Design Attachments

### Context (summary)

```text
Actors: Project Manager, Compliance Officer, Team Member,
        External Auditor, Records / Security Admin

External systems:
- Identity Provider
- Object Storage (optional upload buffer)

Inside ProofChain:
- Web UI, API, Registry DB, Audit Log, Hashing, Authorization, Jobs
```

Audit logging is an **internal** ProofChain responsibility.

### Component (summary)

```text
Web UI → Verification API → Hashing Service / Authorization
                         → Registry DB / Audit Log / Background Jobs
```

These are **logical components** within one application, not separately deployed microservices.

### Data (summary)

```text
User → FileRecord → FileVersion → Fingerprint
                      ↓
               VerificationEvent → AuditEntry
```

**FileVersion → VerificationEvent** is the core verification relationship.

---

## Self-Review Pass

This section records a **self-review** of the current mini spec. No external peer review was performed.

| Review Question | Result | Revision |
|-----------------|--------|----------|
| Is the product boundary clear? | Pass | Applied — integrity vs factual truth stated at top |
| Are users and stories complete? | Pass | Applied — 5 MVP stories retained |
| Are acceptance criteria testable? | Pass | Applied — Register (4) and Verify (5) use **VERIFIED** / **NO MATCH** / **ERROR** |
| Are constraints complete? | Pass | Applied — Business, Time, Legal / Compliance, Technical, Security, Product |
| Is design consistent with earlier sketches? | Pass | Applied — context, component, and data summaries aligned |
| Is verification terminology consistent? | Pass | Applied — removed user-facing **FAILED** wording |
| Is verification history scoped for MVP? | Pass | Applied — selected **FileRecord** only; no org-wide history |
| Are any requirements still open? | Open | Applied — MVP file type / size marked **TBD** |

---

## Ready-to-Build Check

- [x] Problem is clear
- [x] Users are identified
- [x] MVP scope is bounded
- [x] Five user stories are defined
- [x] Core acceptance criteria are testable
- [x] Constraints are documented
- [x] Context boundary is understood
- [x] Components have clear responsibilities
- [x] Core data relationships are defined
- [x] Key trade-off is documented
- [x] Product boundary is explicit

**READY_FOR_DEVELOPMENT:** YES

A developer can start the core **Register → Verify → Result** vertical slice without guessing the product intent, the result model, or the core architecture.

**OPEN_ITEM:** Supported file types and maximum size must be agreed before production acceptance.

Core implementation can begin with a provisional file policy, but production-ready acceptance testing depends on resolving the TBD file type / size requirement.

---

## Key Takeaway

A one-pager combines problem, users, stories, acceptance criteria, constraints, and design into one reviewable artifact.

Clarity beats length. A developer should be able to read this once and understand what to build first.
