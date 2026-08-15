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
