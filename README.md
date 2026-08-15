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

# Implementation Discipline — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Story in focus:** Story 2 — Verify a File

**Story reminder:** **As a** compliance officer, **I want** to verify an uploaded file against a registered record, **so that** I can confirm it still matches the registered version.

**Expected results:** **VERIFIED**, **NO MATCH**, or **ERROR** — never show **ERROR** or **NO MATCH** as **VERIFIED**.

**OPEN_DEPENDENCY:** Supported file types and maximum file size remain **TBD**. This does not fully block core verification orchestration, but it must be resolved before production performance and acceptance decisions are finalized.

---

## 1. Slice Work

Break **Story 2 — Verify a File** into implementation tasks.

**Verification flow:**

```text
submitted file
→ calculate fingerprint
→ load selected FileVersion
→ retrieve stored Fingerprint
→ compare
→ VERIFIED / NO MATCH / ERROR
→ VerificationEvent
→ AuditEntry
```

### API

- [ ] Add `POST /verify` endpoint with verification request/response contract
- [ ] Accept uploaded file and selected target `FileVersion` / record ID
- [ ] Enforce authorization before verification
- [ ] Calculate fingerprint for the submitted file
- [ ] Load selected **FileVersion** and retrieve stored **Fingerprint**
- [ ] Compare the calculated fingerprint of the submitted file against the stored **Fingerprint** for the selected **FileVersion**
- [ ] Return **VERIFIED**, **NO MATCH**, or **ERROR** with record metadata
- [ ] Record **VerificationEvent** and **AuditEntry**

### UI

- [ ] Add verify screen with file upload and record/version selector
- [ ] Submit the selected file and target **FileVersion** for verification
- [ ] Show loading state while verification runs
- [ ] Display result using **VERIFIED**, **NO MATCH**, or **ERROR**
- [ ] Show record ID, file name, and timestamp used for the check
- [ ] Provide clear next-step message for **NO MATCH** and **ERROR**

### Tests

- [ ] Identical file → **VERIFIED**
- [ ] Modified or different file → **NO MATCH**
- [ ] Processing failure → **ERROR**
- [ ] **ERROR** must never become **VERIFIED**
- [ ] Correct **FileVersion** is used
- [ ] Unauthorized request is rejected
- [ ] **VerificationEvent** is recorded
- [ ] **AuditEntry** is recorded

### Docs

- [ ] Document verification API request/response contract
- [ ] Document verification flow
- [ ] Document result terminology (**VERIFIED** / **NO MATCH** / **ERROR**)
- [ ] Note remaining open requirement: supported file types and maximum file size remain **TBD**

---

## 2. Branch Mentality

**Never implement this story directly on `main`.**

Use one feature branch with small logical commits inside it.

**Safe workflow:**

1. Switch to `main`
2. Pull / update `main`
3. Confirm clean working tree
4. Create `feature/verify-file-story`
5. Implement the smallest coherent change
6. Run relevant tests
7. Create one small logical commit
8. Continue with the next slice
9. Run full validation
10. Push the feature branch
11. Open a pull request
12. Pass CI and review
13. Merge only after checks pass

**Example branch:** `feature/verify-file-story`

**Example commits on the same feature branch:**

```text
feat(verification): define verification contract
feat(verification): compare file fingerprints
test(verification): cover verification outcomes
feat(web): add verification flow
docs: document verification behavior
```

These are **not separate branches**. They are small logical commits inside one feature branch.

---

## 3. Definition of Done — Coding

A story is done only when all items below are satisfied:

- [ ] Story acceptance criteria are satisfied
- [ ] Code follows the agreed ProofChain design
- [ ] Unit tests pass
- [ ] Integration / API tests pass where applicable
- [ ] **VERIFIED** / **NO MATCH** / **ERROR** outcomes are tested
- [ ] Error paths are tested
- [ ] Authorization behavior is tested
- [ ] **VerificationEvent** recording is verified
- [ ] **AuditEntry** recording is verified
- [ ] Lint and formatting checks pass
- [ ] Documentation is updated
- [ ] Code review is completed
- [ ] CI checks pass
- [ ] No unresolved critical or high-severity defects remain

**"Code written" alone does not mean Done.**

**Story-level done:** all slice tasks complete, PR merged, and verification flow demo works end to end.

---

## 4. Spike vs Build

### Full Story Decision

**FULL_STORY_SPIKE_REQUIRED:** **NO**

The known parts of the verification story can be built directly:

- API orchestration
- **FileVersion** lookup
- Stored fingerprint retrieval
- Fingerprint comparison
- **VERIFIED** / **NO MATCH** / **ERROR** mapping
- **VerificationEvent**
- **AuditEntry**
- Basic UI flow
- Authorization

### Targeted Technical Spike

**TARGETED_FINGERPRINT_SPIKE:** **YES**

Supported file types and maximum file size remain **OPEN / TBD**, so fingerprint processing strategy is still technically uncertain.

Questions to research in a time-boxed spike:

- Should hashing process the entire file in memory?
- Can hashing be streamed?
- How does file size affect processing time?
- How does file size affect memory usage?
- Should verification always be synchronous?
- Under what future conditions might background processing be appropriate?

**Important:** Do not invent a maximum file size or production threshold. A spike is not a production feature. It is time-boxed technical research.

### Spike Exit Criteria

- [ ] Hashing behavior is tested with representative file sizes.
- [ ] Processing time is observed and recorded.
- [ ] Memory behavior is observed and recorded.
- [ ] Streaming feasibility is confirmed and documented.
- [ ] A sync vs background-processing recommendation is documented.

When the spike is complete, the developer should be able to choose an implementation strategy without guessing.

| Situation | Choice | ProofChain example |
|-----------|--------|-------------------|
| Verification workflow is already defined | **Build** | Implement verify API, UI, events, and audit |
| Fingerprint processing strategy is uncertain | **Spike** | Research memory vs streaming hashing with representative files |
| Acceptance criteria and design already exist | **Build** | Map comparison result to **VERIFIED** / **NO MATCH** / **ERROR** |

---

## 5. Implementation Boundary

This story does **not** include:

- Factual truth verification
- AI truth detection
- Blockchain
- Permanent full-file archival by default
- Organization-wide global verification history
- Advanced enterprise permission-management UI

ProofChain verifies integrity against a selected previously registered **FileVersion** only.

---

## 6. Key Takeaway

Implementation stays predictable when work is sliced into small tasks across API, UI, tests, and docs.

Use one feature branch, small logical commits, and a clear Definition of Done.

Build the known verification workflow now, run a targeted fingerprint spike for open file-size uncertainty, and keep product scope limited to integrity verification.

# Code Review & PR Hygiene — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Context:** Reviewing changes for **Story 2 — Verify a File**

**Review focus:** correctness, tests, naming, security, clarity, and product boundary.

---

## 1. Review Checklist

Use this checklist when reviewing ProofChain code:

| # | Check | Question |
|---|-------|----------|
| 1 | **Correctness** | Does verification compare the uploaded file against the selected **FileVersion** fingerprint correctly? |
| 2 | **Result mapping** | Are outcomes mapped only to **VERIFIED**, **NO MATCH**, or **ERROR**? |
| 3 | **Failure safety** | Can **ERROR** or **NO MATCH** ever be shown as **VERIFIED**? |
| 4 | **Tests** | Do tests cover identical file, modified file, processing failure, and authorization? |
| 5 | **Events / audit** | Are **VerificationEvent** and **AuditEntry** recorded for verification attempts? |
| 6 | **Naming / readability** | Are names clear (`FileVersion`, `Fingerprint`, `VerificationEvent`) and consistent with the spec? |
| 7 | **Authorization / security** | Is authorization checked before reading protected records or returning history? |
| 8 | **Error handling** | Are processing failures handled explicitly instead of silently defaulting to success? |
| 9 | **Scope** | Does the change avoid truth-checking, blockchain, or unrelated feature creep? |
| 10 | **Documentation / CI** | Is relevant documentation updated, do formatting/lint checks pass, and are required CI checks green? |

---

## 2. Give Feedback

> This is a fictional pseudocode diff created only for code-review practice. It is not production ProofChain code.

### Sample diff

```diff
diff --git a/verify_service.py b/verify_service.py
index 1111111..2222222 100644
--- a/verify_service.py
+++ b/verify_service.py
@@ -10,8 +10,12 @@ def verify_file(uploaded_file, record_id):
-    stored_hash = db.get_latest_hash(record_id)
+    stored_hash = db.get_latest_hash(record_id)
     uploaded_hash = hash_file(uploaded_file)
-    if uploaded_hash == stored_hash:
-        return "VERIFIED"
-    return "FAILED"
+    if uploaded_hash == stored_hash:
+        return {"status": "VERIFIED"}
+    return {"status": "VERIFIED", "note": "close enough"}
```

**Expected behavior:**

- match → **VERIFIED**
- mismatch → **NO MATCH**
- processing failure → **ERROR**

### Kind comment

> Non-blocking: could we rename `record_id` to `file_version_id` here? Verification is performed against a specific registered **FileVersion**, so the more precise name would make the intent easier to follow.

### Necessary critical comment

> **Blocking:** This change can return **VERIFIED** when fingerprints do not match (`"close enough"`). That would allow a modified file to appear valid, which breaks the core ProofChain integrity rule. Non-matching fingerprints must return **NO MATCH**. Please fix the mismatch path and add a test that proves a changed file never returns **VERIFIED**.

---

## 3. Receive Feedback

### Sample review comment you disagree with

> "Fingerprint comparison should be moved into a separate microservice before this PR is merged."

### Professional response

> Thanks for the feedback. I understand the independent scaling concern. For the current ProofChain MVP, hashing and fingerprint comparison are logical modules inside one application, not separately deployed microservices. I suggest keeping the existing boundary for this vertical slice and revisiting extraction only if profiling or scaling evidence shows it is needed.

**Response habits:**

- Acknowledge the reviewer's concern
- Explain the current design boundary calmly
- Tie the answer to the agreed MVP architecture
- Stay open to revisiting the decision with evidence

---

## 4. PR Hygiene

A good ProofChain pull request description should include:

| # | Section | What to include |
|---|---------|-----------------|
| 1 | **What changed** | The main code or behavior added or updated |
| 2 | **Why it changed** | The user or business reason for the change |
| 3 | **Related story / requirement** | Which user story, spec item, or slice this PR completes |
| 4 | **Scope** | What is included in this PR |
| 5 | **Out of scope** | What is intentionally not included |
| 6 | **How it was tested** | Tests run and manual checks performed |
| 7 | **Important design decisions** | Key trade-offs or architecture choices made in the PR |
| 8 | **Risks / known limitations** | Remaining risks, open dependencies, or unresolved constraints |
| 9 | **Screenshots or API examples** | UI screenshots or request/response examples when relevant |
| 10 | **Reviewer focus areas** | Where reviewers should spend the most attention |

**Good PR habits:**

- Keep PRs small and focused on one story or slice
- Use a clear title such as `feat(verification): compare uploaded file fingerprint`
- List acceptance criteria satisfied
- Mention risk areas such as authorization and false **VERIFIED**
- Do not merge your own PR without review

---

### Example PR — Verify a File

#### Summary

Implements **Story 2 — Verify a File** so an authorized user can upload a file and check whether it matches a previously registered **FileVersion**.

#### Why

Users need to confirm that a shared file still matches the registered original version without guessing from file name or size alone.

#### Changes

- Adds verification request/response flow
- Calculates uploaded file fingerprint
- Compares it with stored **Fingerprint**
- Returns **VERIFIED**, **NO MATCH**, or **ERROR**
- Records **VerificationEvent** and **AuditEntry**
- Adds basic verification UI

#### Testing

- Identical file → **VERIFIED**
- Different file → **NO MATCH**
- Processing failure → **ERROR**
- Unauthorized request rejected
- **VerificationEvent** and **AuditEntry** verified

#### Out of Scope

- Factual truth verification
- AI truth detection
- Blockchain
- Permanent full-file archival
- Advanced enterprise permission UI

#### Known Limitations

Supported file types and maximum file size remain **TBD**. A targeted fingerprint-processing spike will explore how this uncertainty affects implementation strategy. No production size threshold is defined yet.

#### Reviewer Focus

Reviewers should focus on:

- **VERIFIED** / **NO MATCH** / **ERROR** mapping
- False **VERIFIED** risk
- Authorization behavior
- Correct **FileVersion** selection
- **VerificationEvent** / **AuditEntry** recording

---

## 5. Review Priorities

Review comments should follow this priority order:

1. **Correctness**
2. **Security / data protection**
3. **Failure behavior**
4. **Tests**
5. **Maintainability / clarity**
6. **Style**

A naming preference and an integrity bug do not have the same severity.

For example, renaming `record_id` to `file_version_id` can be a **non-blocking** readability suggestion.

Returning **VERIFIED** for a modified file is a **blocking** issue and must be fixed before merge.

---

## 6. Key Takeaway

Code review is a quality and knowledge-sharing gate in the SDLC, not a contest about who is right.

Feedback should be specific, respectful, and proportional to risk.

Blocking comments should protect correctness and security; minor preferences should not unnecessarily block delivery.

# Testing — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Context:** Quality for **Story 2 — Verify a File**

Testing is a continuous life-cycle activity, not a final surprise phase. Different levels catch different failures. Everyone owns quality — QA deepens it, but developers do not outsource it entirely.

ProofChain verifies whether a file matches a **selected previously registered FileVersion** (integrity only). It does **not** perform factual truth verification, AI truth detection, or blockchain validation.

User-facing results are **VERIFIED**, **NO MATCH**, or **ERROR** only.

---

## 1. Testing Levels

| Level | What it checks | ProofChain example |
|-------|----------------|-------------------|
| **Unit** | One function or module in isolation | `compare_fingerprints(stored, uploaded)` returns **NO MATCH** when hashes differ |
| **Integration** | Two or more components working together | Verification API reads stored **Fingerprint**, checks authorization, and persists **VerificationEvent** / **AuditEntry** |
| **End-to-end (E2E)** | Full user flow through the real system | Authorized user uploads an identical file in the UI and sees **VERIFIED** with the correct record reference |

**How they differ:**

- **Unit tests** are fast and precise. They catch logic bugs such as returning **VERIFIED** on mismatch.
- **Integration tests** catch wiring problems such as wrong **FileVersion** lookup, missing audit recording, or unauthorized access slipping through service boundaries.
- **E2E tests** catch user-facing gaps such as broken upload flow, wrong screen text, or authorization bypass in the full path.

---

## 2. Map Tests to a User Story

**Story:** Story 2 — Verify a File

**As a** compliance officer, **I want** to verify an uploaded file, **so that** I can confirm it still matches the registered version.

### Unit Tests

1. Matching fingerprints → **VERIFIED**
2. Different fingerprints → **NO MATCH**
3. Mismatch must never produce **VERIFIED**
4. Invalid fingerprint input is handled safely
5. Result mapping only produces **VERIFIED**, **NO MATCH**, or **ERROR**

### Integration Tests

1. Authorized request + matching file → **VERIFIED**
2. Authorized request + modified file → **NO MATCH**
3. Processing failure → **ERROR**
4. Unauthorized request is rejected
5. Correct **FileVersion** and stored **Fingerprint** are used
6. **VerificationEvent** and **AuditEntry** are persisted correctly

### End-to-End Tests

1. Unchanged file → **VERIFIED** shown
2. Modified file → **NO MATCH** shown
3. Processing failure → **ERROR** shown
4. Unauthorized user cannot complete protected verification

---

## 3. Testing Strategy

```text
            E2E
        Integration
           Unit
```

Use the pyramid intentionally:

- **Many fast unit tests** for fingerprint comparison and result mapping
- **Fewer integration tests** for API + **FileVersion** / **Fingerprint** + authorization + audit
- **A smaller number of high-value E2E tests** for critical Verify a File user journeys

Each level has a different cost and failure-detection strength. Balance coverage with maintainability rather than assuming more E2E tests are always better.

---

## 4. Bug Life Cycle

| Step | What happens |
|------|--------------|
| 1. **Report** | Bug is logged with observed behavior, expected behavior, environment, and supporting evidence |
| 2. **Reproduce** | Team confirms the issue can be reproduced reliably using documented steps |
| 3. **Triage** | Team assesses severity, impact, reproducibility, and priority; assigns an owner |
| 4. **Fix** | Developer implements the correction and adds or updates tests |
| 5. **Developer Verification** | Developer confirms the fix locally with relevant unit/integration tests and failure-path checks |
| 6. **QA / Review Verification** | Fix is independently re-tested and related regression cases are checked |
| 7. **Close** | Bug is closed only after verification passes |

**ProofChain example:**

Modified file is incorrectly shown as **VERIFIED**.

- **Report:** "Upload changed PDF for record R-102 → expected **NO MATCH**, got **VERIFIED**"
- **Reproduce:** Repeat with the same registered **FileVersion**, changed file bytes, and authorized user; mismatch result appears consistently
- **Triage:**
  - **Severity:** HIGH — breaks ProofChain's core integrity guarantee that modified files must not appear valid
  - **Impact:** Users may trust a changed document as unchanged; audit trail becomes misleading
  - **Reproducibility:** Confirmed on staging with two changed PDF uploads
  - **Priority:** Fix before merge / release
- **Fix:** Correct mismatch mapping in verification logic; add regression test proving changed files never return **VERIFIED**
- **Developer Verification:** Run unit tests for mismatch mapping and integration tests for modified file → **NO MATCH** plus **ERROR** failure path
- **QA / Review Verification:** QA independently repeats identical/modified/failure scenarios and checks no regression in **VerificationEvent** / **AuditEntry** recording
- **Close:** Close only after fix verification and regression pass

---

## 5. Quality != Only QA

Developers are responsible for quality **before** handoff. QA adds depth, but the team should not treat testing as someone else's final gate.

**Quality is shared ownership.**

**Developer responsibilities before handoff:**

- [ ] Understand acceptance criteria before coding
- [ ] Keep implementation aligned with agreed design
- [ ] Write unit tests
- [ ] Add integration tests where appropriate
- [ ] Test failure and error paths
- [ ] Test authorization and security behavior
- [ ] Verify **VerificationEvent** and **AuditEntry** behavior
- [ ] Run lint, formatting, and static checks
- [ ] Update relevant documentation
- [ ] Self-review the diff before requesting review

**What QA still adds:**

- **Exploratory testing** beyond scripted cases
- **Broader system behavior** across modules and workflows
- **Regression coverage** across stories and releases
- **User-facing risks** such as confusing result screens or broken upload flows
- **Independent verification** before release or merge approval

---

## 6. Key Takeaway

Use unit, integration, and E2E tests together — each level catches failures the others may miss.

Map tests directly to user story acceptance criteria so quality is measurable, not assumed.

Quality is shared ownership: developers build it in continuously, QA deepens it, and bug handling should move quickly from report to verified close.

# Release & CI — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System

Releasing software is a controlled SDLC activity, not only a deployment command.

A healthy release process combines automated quality gates, readiness checks, monitoring, and a safe rollback strategy.

**Sample release:** ProofChain v0.1.0 — File Registration & Verification MVP

**Product boundary:** ProofChain verifies whether a file matches a previously registered **FileVersion**. It does **not** determine whether information inside the file is factually true.

User-facing results are **VERIFIED**, **NO MATCH**, or **ERROR** only.

---

## 1. Release Checklist

### Before Release

- [ ] Acceptance criteria completed
- [ ] Code review approved
- [ ] CI checks passing
- [ ] Unit tests passing
- [ ] Integration tests passing
- [ ] Critical E2E verification journeys passing
- [ ] No unresolved critical/high defects
- [ ] Security/auth behavior reviewed
- [ ] Documentation/changelog prepared

### Database / Configuration

- [ ] Database migrations reviewed
- [ ] Migration compatibility checked
- [ ] Backup/recovery considerations reviewed
- [ ] Required environment configuration documented
- [ ] Feature flags have safe defaults
- [ ] Secrets are not committed to source control

**Feature flag example:**

```text
PROOFCHAIN_FILE_VERIFICATION_ENABLED=false
```

The flag can be enabled in a controlled way during release.

A feature flag supports controlled exposure and rollback mitigation. It does **not** replace database migrations or testing.

### Deployment

- [ ] Deploy approved build artifact
- [ ] Confirm migration status
- [ ] Confirm application health
- [ ] Enable feature flag only when dependencies are ready
- [ ] Record deployed version

### Smoke Test

Run a small post-deploy confidence check — not a full regression suite.

1. Application health endpoint responds successfully
2. User can register a file
3. Same file verification returns **VERIFIED**
4. Modified file verification returns **NO MATCH**
5. **VerificationEvent** and **AuditEntry** are created

### After Release

- [ ] Monitor errors
- [ ] Monitor latency
- [ ] Monitor verification failures
- [ ] Watch for unexpected **VERIFIED** results
- [ ] Confirm audit events continue to be recorded
- [ ] Keep rollback decision window active

---

## 2. Continuous Integration as a Quality Gate

CI is more than "tests run automatically." It provides repeatable evidence before merge and release.

```text
Developer
  → Feature Branch
  → Pull Request
  → CI
  → Review
  → Merge
  → Release
```

**Example CI quality gates:**

1. Formatting / lint
2. Static analysis
3. Unit tests
4. Integration tests
5. Security / dependency checks
6. Build verification

**What CI provides:**

- CI provides repeatable evidence.
- CI does **not** replace human review.

Human judgment is still required for:

- Architecture
- Product intent
- Security context
- Maintainability
- Risk

Failed required CI checks should block merge.

For ProofChain, CI helps prevent integrity regressions such as modified files returning **VERIFIED** before code reaches production.

---

## 3. Rollback / Mitigation Plan

**Sample bad release:** Modified files are incorrectly returning **VERIFIED**.

**Severity:** HIGH — this breaks ProofChain's core integrity guarantee. Users may trust changed content as unchanged, and audit history becomes misleading.

**Response plan:**

| Step | Action |
|------|--------|
| 1. **Detect** | Monitoring, support report, or smoke test identifies the problem |
| 2. **Stop / Contain** | Prevent new verification traffic from producing risky results |
| 3. **Disable Feature** | Set `PROOFCHAIN_FILE_VERIFICATION_ENABLED=false` to shut down the verification flow; if no flag exists, move to application rollback |
| 4. **Assess Data Impact** | Identify affected **VerificationEvent** records and the time window; do not silently delete incorrect **VERIFIED** results — preserve the audit trail |
| 5. **Roll Back Application** | Return to the last known-good application version |
| 6. **Verify Recovery** | Re-run smoke tests: health, register, **VERIFIED**, **NO MATCH**, audit recording |
| 7. **Communicate and Follow Up** | Create an incident record, notify affected users/stakeholders if needed, and add root cause + regression test + prevention action |

**Database rollback caution:**

Do not assume database rollback is automatic or safe.

Forward-compatible migrations are preferred. Destructive database rollback must be evaluated separately with backup, compatibility, and data-impact analysis.

**Rollback vs mitigation:**

- **Rollback** = return to a previous known-good application version
- **Mitigation** = temporary risk reduction such as feature disable or traffic containment while investigation continues

---

## 4. Version Note

## ProofChain v0.1.0

### Added

- File registration with **FileVersion** records
- Fingerprint-based integrity verification
- **VERIFIED**, **NO MATCH**, and **ERROR** result states
- **VerificationEvent** and **AuditEntry** recording
- Basic authorization for protected verification flows

### Quality

- Unit, integration, and critical E2E coverage
- CI quality gates
- Release smoke-test checklist

### Known Limitations

- Supported file types remain **TBD**
- Maximum supported file size remains **TBD**
- Advanced role-management UI is out of scope for v0.1.0
- ProofChain verifies file integrity, not factual truth

---

## 5. Release Principles

1. Build once, promote the same artifact.
2. Prefer backward-compatible database changes.
3. Use feature flags for controlled exposure, not as a substitute for testing.
4. Every release needs observable health signals.
5. Rollback must be planned before deployment.

# Environments & Deployment — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System

Operations begin at deploy. Environments exist to reduce risk. Promoting through staging with proper config discipline is core SDLC hygiene.

ProofChain verifies file integrity against a registered **FileVersion**. It does **not** determine whether the information inside a file is factually true.

User-facing results are **VERIFIED**, **NO MATCH**, or **ERROR** only.

---

## 1. Environment Map

| Environment | Primary purpose | ProofChain responsibilities |
|-------------|-----------------|------------------------------|
| **Local** | Developer experimentation and fast feedback | Run unit/integration tests, debug **Fingerprint** comparison, test **VERIFIED** / **NO MATCH** / **ERROR** mapping with synthetic data |
| **Staging** | Pre-production validation with production-like setup | Validate migrations, auth, **VerificationEvent** / **AuditEntry** flows, and release smoke tests with sanitized test data |
| **Production** | Serve real users and real **FileRecord** data | Protect integrity guarantees, monitor verification outcomes, preserve audit history |

**Environment safety rules:**

**Production secrets**

- Production credentials/secrets must never be reused in local or staging.
- Each environment uses its own credentials.

**Production data**

- Production customer files/data must not be copied casually into local or staging.
- Prefer synthetic or sanitized test data.
- Test data must be clearly distinguishable from production data.
- Lower environments must not accidentally trigger production notifications/events.

Local is for learning. Staging is for confidence. Production is for trust.

---

## 2. Promotion Path

**Build once, promote the same artifact.**

Example artifact: `proofchain-v0.1.0`

```text
Feature Branch
  → Pull Request
  → CI
  → Merge
  → Build Immutable Artifact
  → Staging
  → Staging Validation
  → Production Approval
  → Production
  → Post-Deploy Smoke Test
  → Monitoring
```

**Promotion rules:**

- The artifact validated in staging is the artifact promoted to production.
- Code is not manually changed between staging and production.
- Production deployment requires required validation to **PASS**.
- After production deploy, run a post-deploy smoke test, then continue monitoring.

**Production smoke test examples:**

1. Application health
2. Register file
3. Unchanged file → **VERIFIED**
4. Modified file → **NO MATCH**
5. **VerificationEvent** / **AuditEntry** recording

---

## 3. Config Awareness

| Category | Local | Staging | Production |
|----------|-------|---------|------------|
| **Secrets** | Developer/test credentials | Staging-only credentials | Production-only credentials |
| **Database URLs** | Local database | Staging database | Production database |
| **Service / API URLs** | `localhost` app/API endpoints | Staging app/API endpoints | Production app/API endpoints |
| **Feature flags** | Often enabled for testing | Controlled rollout testing | Safe default; enable deliberately |
| **Logging / Observability** | Verbose local logs | Staging alerts and traces | Production monitoring and incident alerts |
| **External Integrations** | Dev/mock IdP, optional storage, monitoring | Staging IdP, storage, monitoring endpoints | Production IdP, storage, monitoring endpoints |

**ProofChain config examples (no real values):**

```text
PROOFCHAIN_FILE_VERIFICATION_ENABLED=true|false
DATABASE_URL=...
SERVICE_API_URL=...
IDENTITY_PROVIDER_URL=...
```

**Config rules:**

- Production secrets are never reused in local/staging.
- Secrets must stay outside source control.
- Local, staging, and production use separate databases.
- Local/staging must never connect to the production database.
- Production URLs and credentials must not be hardcoded.
- Feature flag values may differ by environment.
- External integrations use environment-specific endpoints and credentials.

### Configuration Principles

1. Keep secrets outside source control.
2. Separate environment-specific configuration from application code.
3. Use different credentials and data stores per environment.
4. Validate required configuration at startup/deployment.
5. Document configuration without documenting secret values.

---

## 4. Unsafe Shortcut

**Scenario:** Modified files occasionally return **VERIFIED**.

**Unsafe shortcut:** Deploy an untested hotfix directly to production.

**Why it is risky:**

1. The fix may introduce another integrity regression.
2. No regression-test evidence exists.
3. Environment/configuration differences may be missed.
4. Authorization/security behavior may break.
5. **VerificationEvent** / **AuditEntry** behavior may break silently.
6. Rollback readiness may be unknown.

**Safer hotfix path:**

1. **Contain / mitigate** — disable risky traffic or set `PROOFCHAIN_FILE_VERIFICATION_ENABLED=false`
2. **Create hotfix branch**
3. **Implement minimal fix**
4. **Add regression test**
5. **Run focused CI**
6. **Obtain expedited review**
7. **Validate in staging**
8. **Promote the same validated artifact to production**
9. **Run production smoke test**
10. **Monitor and document the incident**

**Emergency does not mean no process.**

The emergency process may be faster and narrower, but it must remain controlled. Minimum safety controls still apply:

- Automated tests
- Review
- Rollback readiness
- Post-deploy verification

If staging cannot be used, treat that as an exceptional, explicitly risk-accepted case — not the normal path.

---

## 5. Key Takeaway

Environments reduce risk by separating experimentation, validation, and live operation.

Build once, promote the same artifact through staging with environment-specific config discipline.

Avoid uncontrolled production hotfixes — mitigate first, then follow the safer controlled path.

# Maintenance & Operations — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System

Most of a product's life is after launch. Maintenance and operations keep value alive. Monitoring and a calm incident process are part of SDLC — not an afterthought.

ProofChain verifies whether a file matches a previously registered **FileVersion**. It does **not** determine whether the information inside a file is factually true.

User-facing results are **VERIFIED**, **NO MATCH**, or **ERROR** only.

---

## 1. Maintenance Types

| Type | Purpose | ProofChain example |
|------|---------|-------------------|
| **Corrective** | Fix an active defect after release | Patch bug where modified files incorrectly return **VERIFIED** |
| **Adaptive** | Adjust to changed environment | Update identity provider integration when auth endpoints change |
| **Perfective** | Improve performance or usability | Make verification result screen clearer without changing integrity rules |
| **Preventive** | Reduce future risk before a production defect appears | Upgrade an aging hashing dependency and strengthen **Fingerprint** regression tests before a known compatibility or security risk becomes a production incident |

**How they differ:**

- **Corrective** fixes something already broken in production or release.
- **Preventive** reduces risk **before** an active production defect exists — it is not the same as reacting to an alert after users are affected.
- **Adaptive** responds to external change.
- **Perfective** improves the product without fixing a defect.

Monitoring or alert improvements can support preventive work, but they should not be the main preventive example on their own.

---

## 2. Signals to Watch

For a simple ProofChain verification API, monitor these core signals:

| Signal | What it tells us | Why it matters |
|--------|------------------|----------------|
| **Request rate** | Traffic volume and usage spikes | Helps detect abuse, rollout effects, or capacity pressure |
| **Error rate** | Overall failed requests | Shows rising instability in verification flows |
| **Request latency** | Response time (p95/p99) | Slow **Fingerprint** processing reduces trust and may hide failures |
| **HTTP 5xx rate** | Server/processing failures | May cause **ERROR** outcomes or failed verification attempts |
| **VERIFIED / NO MATCH / ERROR distribution** | Result mix over time | Shifts may indicate logic, config, or data issues |
| **Unexpected VERIFIED anomalies** | Modified inputs returning **VERIFIED** | **HIGH PRIORITY** — false **VERIFIED** breaks ProofChain's core integrity guarantee |
| **Authentication / authorization failures** | Access control problems | May expose protected **FileRecord** / **FileVersion** data incorrectly |
| **Database errors / latency** | Persistence health | Can break lookup of **FileVersion** / **Fingerprint** or audit writes |
| **VerificationEvent / AuditEntry persistence failures** | Audit write problems | Verification may succeed visually while audit evidence is lost |
| **Application health / availability** | Service up/down status | Basic availability for register and verify flows |

**Additional useful signal:** deployed version tag — correlates incidents with releases, but does not replace the core signals above.

**Distribution nuance:** A change in **VERIFIED** / **NO MATCH** / **ERROR** distribution is an investigation signal. A distribution change alone does not prove that a bug exists.

### Structured Logging

Use structured logs for investigation and on-call response:

- Structured log fields, not unstructured text only
- Correlation / request ID across API, database, and audit writes
- Safe identifiers such as **FileRecord** ID and **FileVersion** ID
- Result state (**VERIFIED**, **NO MATCH**, **ERROR**)
- Deployed version where useful for incident correlation
- No passwords, tokens, or secrets
- Do not casually log full customer file contents

Preserve audit evidence for incident investigation. Logs support analysis; they do not replace retained **VerificationEvent** / **AuditEntry** records.

---

## 3. Incident Outline

**Sample incident:** Modified files may incorrectly return **VERIFIED**.

**Severity:** HIGH

**Impact:** A changed file may be trusted as unchanged, violating ProofChain's core integrity guarantee.

| Step | Actions |
|------|---------|
| 1. **Detect** | Alert, dashboard anomaly, or support report shows modified files returning **VERIFIED** |
| 2. **Triage** | Assess affected version, affected time window, reproducibility, user impact, and priority |
| 3. **Mitigate** | Stop risky outcomes first — e.g. set `PROOFCHAIN_FILE_VERIFICATION_ENABLED=false` |
| 4. **Investigate** | Review **Fingerprint** calculation, **FileVersion** lookup, comparison logic, recent deployment/config changes, and **VerificationEvent** / **AuditEntry** evidence |
| 5. **Fix** | Apply minimal corrective change and add regression test |
| 6. **Verify** | Run CI, review, staging checks, and validate **VERIFIED**, **NO MATCH**, **ERROR**, authorization, and audit persistence |
| 7. **Restore / Monitor** | Controlled production restore, production smoke test, then monitor errors, latency, result distribution, and unexpected **VERIFIED** |
| 8. **Review** | Document root cause, affected records/time window, prevention actions, and runbook updates |

**Mini timeline example:**

```text
09:10  Detect: unexpected VERIFIED anomaly alert
09:15  Triage: reproducible on version proofchain-v0.1.0; user impact confirmed
09:25  Mitigate: PROOFCHAIN_FILE_VERIFICATION_ENABLED=false
09:40  Investigate: comparison logic regression after deploy
10:10  Fix + regression test pass in CI and staging
10:45  Verify + restore in production; smoke test passes
11:00  Monitor: result distribution and audit writes watched
11:30  Review: root cause and prevention actions recorded
```

### Incident Safety Rules

- Preserve audit evidence.
- Do not silently delete incorrect **VerificationEvent** or **AuditEntry** records.
- Identify affected deployment version and time window.
- Prefer mitigation before a rushed production fix.
- Communicate current status and user impact.
- Record follow-up and prevention actions.

If incorrect **VERIFIED** records exist, preserve them as incident evidence rather than secretly rewriting history.

---

## 4. On-Call Empathy

The on-call engineer should not need to guess basic incident context.

Provide these 10 fields:

1. **Clear alert title**
2. **Severity**
3. **Affected service / feature**
4. **User impact**
5. **First detected time**
6. **Current deployed version**
7. **Recent deployment / change**
8. **Relevant logs / dashboard / evidence**
9. **Known mitigation / rollback steps**
10. **Escalation / contact owner**

### Alert Quality

**Bad alert:**

> Verification is broken.

**Useful alert:**

> HIGH — ProofChain File Verification: modified files may return **VERIFIED**. First detected at `[time]`, affecting version `[version]`. Verification has been disabled with the feature flag. See `[dashboard/runbook]`.

A useful alert includes severity, affected feature, impact, detected time, deployed version, mitigation status, and an investigation resource.

**What to avoid:**

- Vague one-line reports
- Missing deployment/version context
- Sharing production secrets or full customer files in chat

---

## 5. Minimal On-Call Runbook

1. **Service purpose** — verify uploaded files against registered **FileVersion** fingerprints
2. **Health check** — confirm application health endpoint responds
3. **Key dashboards / signals** — error rate, latency, result distribution, unexpected **VERIFIED**
4. **Structured logs** — search by request ID, **FileVersion** ID, result state
5. **Feature flag mitigation** — disable `PROOFCHAIN_FILE_VERIFICATION_ENABLED`
6. **Rollback procedure** — return to last known-good application version if needed
7. **Production smoke test** — health, register, **VERIFIED**, **NO MATCH**, audit recording
8. **Escalation owner** — contact designated incident owner / engineering lead

---

## 6. Key Takeaway

Maintenance keeps ProofChain useful after launch — through corrective, adaptive, perfective, and preventive work.

Watch API signals that protect integrity, security, and audit behavior.

A calm incident process — detect, triage, mitigate, investigate, fix, verify, restore/monitor, review — is part of professional SDLC operations.

# Retrospective & Continuous Improvement — ProofChain

**Product:** ProofChain — Digital Content Integrity Verification System
**Project:** ProofChain SDLC practice (requirements through maintenance)

Retrospectives close the SDLC loop: learn → adjust → build better. Continuous improvement needs actions and feedback into requirements — not only venting.

ProofChain verifies whether a file matches a previously registered **FileVersion**. ProofChain does **not** determine whether information inside the file is factually true. **NO MATCH** means integrity mismatch only.

---

## 1. Retro Format

**Recent project:** ProofChain MVP documentation and Story 2 — Verify a File slice

### Went Well

1. Product boundary became clear early: integrity verification is not factual truth verification.
2. **VERIFIED**, **NO MATCH**, and **ERROR** terminology stayed consistent across requirements, testing, and operations.
3. **FileRecord** → **FileVersion** → **Fingerprint** made the verification target easier to understand.
4. Feature branch + review + PR workflow reduced risk to `main`.
5. Testing, rollback, monitoring, and incident handling became part of SDLC instead of afterthoughts post-implementation.

### Improve

1. **Observation:** Some assignment requirements were found only during the first review.
   **Impact:** Rework increased before commit-ready quality was reached.

2. **Observation:** Supported file types and maximum file size remained **TBD** for multiple exercises.
   **Impact:** Implementation and acceptance criteria stayed partially open.

3. **Observation:** Some terminology and design decisions needed several iterations to stabilize.
   **Impact:** Review cycles repeated similar consistency checks.

4. **Observation:** Operational requirements were detailed later in the lifecycle than ideal.
   **Impact:** Release and maintenance thinking arrived after core product sections were already written.

5. **Observation:** A reusable pre-commit checklist was not used from the first exercise onward.
   **Impact:** First-pass quality varied and review findings repeated.

### Actions

| Action | Owner | Due | Success Signal |
|--------|-------|-----|----------------|
| Use a requirements readiness check before design work begins | Me | 2026-09-30 | No unresolved core boundary or result-state questions at design start |
| Create and use a reusable pre-commit review checklist | Me | 2026-09-20 | Checklist used on every new README exercise before commit |
| Resolve file type + maximum size **TBD** before implementation acceptance | Me | 2026-10-15 | Mini spec lists a documented decision or explicit spike outcome |
| Move operations requirements checklist into the design phase | Me | 2026-10-01 | Next exercise includes ops/release notes in design or mini spec |
| Apply terminology and product-boundary checks in the first draft of each exercise | Me | 2026-09-25 | First draft passes terminology/product-boundary review without rework |

---

## 2. From Complaint to Action

**Complaint 1:** "Requirements keep changing after design starts."

- **Observation:** Some core requirements remain unresolved when design begins.
- **Action:** Introduce a short requirements readiness check before design.
- **Owner:** Me
- **Due:** 2026-09-30
- **Success Measure:** No unresolved core product-boundary or result-state questions when design begins.

**Complaint 2:** "We keep finding important issues during final review."

- **Observation:** Important consistency and assignment checks are sometimes performed only during the final pre-commit review.
- **Action:** Use a reusable pre-commit checklist covering assignment requirements, terminology, architecture consistency, product boundary, and `git diff --check`.
- **Owner:** Me
- **Due:** 2026-09-20
- **Success Measure:** Reduce the number of exercises requiring substantive changes after their first pre-commit review.

---

## 3. Process Metric for Next Month

**Primary metric:** Review Rework Rate

**Definition:** Percentage of reviewed exercises that require substantive changes after the first pre-commit review.

**Formula:**

```text
Review Rework Rate =
  Exercises requiring substantive changes after first review
  /
  Total reviewed exercises
  × 100
```

**Why this metric:** Many ProofChain exercises received **PASS_WITH_CHANGES** on first review. This metric provides a learning signal for requirements clarity, first-pass quality, and pre-commit checklist effectiveness.

**Measurement period:** Next month

**Baseline:** Baseline will be established during the first measurement period.

This metric is a learning signal, not a performance target.

**Goodhart / gaming note:** The goal is not to hide review findings or avoid useful changes to make the percentage look better. A lower number is useful only when it reflects genuinely clearer requirements and stronger first-pass quality.

---

## 4. Feedback Loop

Validated feedback returns to requirements and backlog work — it should not stop at support tickets or venting.

```text
User
  ↓
Feedback
  ↓
Capture
  ↓
Triage
  ↓
Clarify
  ↓
Requirements / Backlog
  ↓
Prioritize
  ↓
Design
  ↓
Implementation
  ↓
Testing
  ↓
Release
  ↓
Observe
  ↓
User
  ↺
```

**Seven logical steps:**

1. **Capture** — record the feedback with source and context
2. **Triage** — classify as defect, usability issue, new need, or out of scope
3. **Clarify** — confirm what the user or system signal actually means
4. **Convert to requirement/story** — update requirements, story, or acceptance criteria
5. **Prioritize** — decide whether and when the work enters the backlog
6. **Build / test / release** — design, implement, test, and release the change
7. **Observe outcome** — monitor whether the original problem decreased

Feedback must be understood and validated before becoming work. Not every signal becomes a requirement automatically.

### ProofChain Feedback Example

**User feedback:** "I uploaded a modified document but I don't understand what **NO MATCH** means."

Do not jump directly to a UI tweak without understanding the problem.

1. Capture feedback.
2. Investigate what the user misunderstood.
3. Clarify expected understanding.
4. Create or update requirement.
5. Create user story.
6. Define acceptance criteria.
7. Prioritize.
8. Implement, test, and release.
9. Observe whether confusion decreases.

**Requirement example:** When verification returns **NO MATCH**, the interface must clearly explain that the uploaded file does not match the selected registered **FileVersion**.

**User story example:** As a user verifying a file, I want a clear explanation when verification returns **NO MATCH**, so that I understand what the integrity result means.

**Acceptance criteria:**

- Given a mismatching file, when verification completes, then the UI displays **NO MATCH**.
- The UI explains that the uploaded file does not match the selected registered **FileVersion**.
- The UI must not describe **NO MATCH** as proof of fraud, false information, or factual inaccuracy.

**Boundary:** **NO MATCH** means integrity mismatch only. It does **not** mean the document is false, fraudulent, or factually incorrect.

### Feedback Sources

1. User feedback
2. Support requests
3. Monitoring signals
4. Incident reviews
5. QA findings
6. Analytics
7. Retrospectives
8. Security findings

All of these sources can create input for triage and, when validated, can become requirements/backlog work.

---

## 5. Retrospective Principles

1. Focus on process, not blame.
2. Prefer evidence over assumptions.
3. Convert observations into actions.
4. Give actions an owner and target date.
5. Feed learning back into requirements and future work.

A retrospective without follow-up actions is only a conversation.
