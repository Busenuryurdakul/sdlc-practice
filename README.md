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
