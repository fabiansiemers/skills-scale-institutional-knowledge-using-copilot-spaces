# OctoAcme — Cross-Functional Communication Guide

## Purpose
Establish clear patterns for communication across different roles to improve collaboration, reduce misunderstandings, and ensure all stakeholders have the information they need.

## Principles
- **Clarity**: Be specific about what you need and by when
- **Context**: Provide enough background for others to understand why
- **Actionability**: Make it clear what action or decision is required
- **Timeliness**: Communicate early when blockers or changes arise
- **Transparency**: Keep relevant stakeholders informed of progress and risks

## Communication Matrix

### Who Communicates with Whom

| From -> To | Primary Topics | Frequency | Format |
|-----------|---------------|-----------|--------|
| **Developer -> Product Manager** | Feature questions, technical constraints, scope clarifications | As needed | Slack, PR comments, planning meetings |
| **Developer -> Project Manager** | Blockers, timeline impacts, resource needs | Daily standup, as needed | Standup, Slack, email |
| **Developer -> UX Designer** | Implementation questions, feasibility feedback, design clarifications | As needed | Slack, PR reviews, design reviews |
| **Developer -> Technical Architect** | Architecture decisions, technical approach validation | Before major changes | Slack, design docs, PR reviews |
| **Developer -> Data Analyst** | Instrumentation needs, metric questions | As needed | Slack, planning meetings |
| **Product Manager -> Project Manager** | Priority changes, scope decisions, stakeholder updates | Weekly sync | Meeting, email |
| **Product Manager -> UX Designer** | Feature requirements, user research insights, design validation | Weekly, as needed | Meeting, design reviews |
| **Product Manager -> Customer Advocate** | User feedback prioritization, feature validation | Weekly, as needed | Meeting, Slack |
| **Product Manager -> Data Analyst** | Success metric definition, experiment design | As needed | Meeting, Slack |
| **Project Manager -> All Team Members** | Status updates, risk alerts, schedule changes | Weekly | Email, Slack, standup |
| **Project Manager -> Scrum Master** | Team capacity, impediments, cross-team coordination | As needed | Meeting, Slack |
| **UX Designer -> Developer** | Design specs, accessibility requirements, implementation feedback | During sprint | Slack, PR reviews, design handoff |
| **UX Designer -> Product Manager** | Design research findings, usability concerns, design proposals | Weekly | Meeting, design reviews |
| **Technical Architect -> Developer** | Architecture guidance, technical standards, code review feedback | Ongoing | PR reviews, design docs, meetings |
| **Scrum Master -> Project Manager** | Team health, velocity trends, impediment escalation | Weekly | Meeting, Slack |
| **Scrum Master -> All Team Members** | Process improvements, ceremony facilitation, coaching | Daily/weekly | Standup, retros, 1-on-1s |
| **Customer Advocate -> Product Manager** | User feedback, pain points, feature requests | Weekly | Meeting, feedback reports |
| **Customer Advocate -> UX Designer** | Usability feedback, user testing results | As needed | Meeting, Slack |
| **Data Analyst -> Product Manager** | Metric reports, experiment results, insights | Weekly/monthly | Dashboard, reports, meetings |
| **Data Analyst -> All Roles** | KPI updates, data insights | Monthly | Reports, presentations |

## Communication Templates

### Blocker Notification
**When**: You encounter a blocker that impacts timeline or deliverables  
**Recipients**: Project Manager, relevant team members  
**Format**:
```
🚧 Blocker: [Brief description]

What's blocked: [Specific work item or feature]
Impact: [Timeline impact, affected deliverables]
Root cause: [What's causing the blocker]
Help needed: [Specific action or decision required]
Urgency: [Immediate / This sprint / This week]
```

### Feature Clarification Request
**When**: You need clarification on requirements or acceptance criteria  
**Recipients**: Product Manager, UX Designer (if design-related)  
**Format**:
```
📋 Feature Question: [Feature name]

Context: [Where you are in implementation]
Question: [Specific question about requirements or design]
Current assumption: [What you're assuming if unclear]
Impact if incorrect: [What might need to change]
Need response by: [Date/time]
```

### Technical Decision Proposal
**When**: Proposing a significant technical change or architecture decision  
**Recipients**: Technical Architect, relevant Developers, Project Manager  
**Format**:
```
🏗️ Technical Decision: [Brief title]

Problem: [What technical challenge we're addressing]
Proposed solution: [Brief description or link to design doc]
Alternatives considered: [Other options and why not chosen]
Trade-offs: [Pros and cons of proposed approach]
Impact: [Performance, timeline, maintenance, etc.]
Feedback requested by: [Date]
Decision needed by: [Date]
```

### Design Feedback Request
**When**: Seeking feedback on design work  
**Recipients**: Product Manager, Developers, Stakeholders  
**Format**:
```
🎨 Design Review: [Feature name]

Design link: [Figma/prototype URL]
Stage: [Early concept / Detailed design / Final review]
Context: [User problem being solved, goals]
Specific feedback wanted: [What you're most uncertain about]
Constraints: [Technical, timeline, or scope constraints to consider]
Feedback deadline: [Date]
```

### Status Update
**When**: Regular project updates or significant milestone completion  
**Recipients**: Stakeholders, Project Manager, Team  
**Format**:
```
📊 Status Update: [Project name] - [Date]

Completed this week:
- [Item 1]
- [Item 2]

In progress:
- [Item 1 - Owner - Expected completion]
- [Item 2 - Owner - Expected completion]

Coming next week:
- [Item 1]
- [Item 2]

Risks/blockers:
- [Risk 1 - Mitigation plan]
- [Blocker 1 - Help needed]

Metrics update:
- [Key metric 1: value (trend)]
- [Key metric 2: value (trend)]
```

### User Research Findings
**When**: Sharing insights from user research or feedback  
**Recipients**: Product Manager, UX Designer, relevant stakeholders  
**Format**:
```
👥 User Research: [Study name/topic]

Method: [Interviews / Survey / Usability test / Analytics]
Sample: [Number of participants, key demographics]

Key findings:
1. [Finding 1 - with supporting quote or data]
2. [Finding 2 - with supporting quote or data]
3. [Finding 3 - with supporting quote or data]

Recommended actions:
- [Action 1 - Priority]
- [Action 2 - Priority]

Full report: [Link to detailed findings]
```

### Risk Alert
**When**: Identifying a new risk or escalating an existing one  
**Recipients**: Project Manager, affected stakeholders  
**Format**:
```
⚠️ Risk Alert: [Risk title]

Risk description: [What could go wrong]
Impact if realized: [Timeline, quality, cost, scope impact]
Probability: [Low / Medium / High]
First identified: [Date]
Owner: [Who's monitoring/mitigating]
Mitigation plan: [Current or proposed actions]
Escalation needed: [Yes/No - specific decision or resource needed]
```

### Dependency Notification
**When**: Your work depends on another team or you're blocking another team  
**Recipients**: Project Manager, dependent team contacts  
**Format**:
```
🔗 Dependency: [Brief description]

Your team: [Team name]
Dependent team: [Team name]
Type: [We need from them / They need from us]

What's needed: [Specific deliverable, decision, or resource]
Why needed: [Context and impact]
Needed by: [Date]
Current status: [On track / At risk / Blocked]
Point of contact: [Name for questions]
```

### Experiment Results
**When**: Sharing results from A/B tests or experiments  
**Recipients**: Product Manager, relevant stakeholders, team  
**Format**:
```
🧪 Experiment Results: [Experiment name]

Hypothesis: [What we thought would happen]
Method: [A/B test details, sample size, duration]

Results:
- [Metric 1]: [Control value] vs [Variant value] ([% change, statistical significance])
- [Metric 2]: [Control value] vs [Variant value] ([% change, statistical significance])

Recommendation: [Ship / Don't ship / Iterate / Run longer]
Rationale: [Why we recommend this action]
Next steps: [What happens next]

Full analysis: [Link to detailed report]
```

## Meeting Best Practices

### Sprint Planning
- **Attendees**: Developers, Product Manager, UX Designer, Scrum Master
- **Duration**: 1-2 hours
- **Prep**: Backlog groomed, acceptance criteria defined, designs ready
- **Outcome**: Sprint backlog committed, tasks estimated, capacity confirmed

### Daily Standup
- **Attendees**: Core delivery team (Developers, Scrum Master, optionally PM/PdM)
- **Duration**: 15 minutes
- **Format**: What did you do? What will you do? Any blockers?
- **Outcome**: Team alignment, blockers surfaced, quick help coordinated

### Sprint Review/Demo
- **Attendees**: Team + stakeholders
- **Duration**: 1 hour
- **Format**: Show working software, gather feedback
- **Outcome**: Stakeholder feedback, acceptance of completed work

### Retrospective
- **Attendees**: Core team (Developers, PM, PdM, UX, Scrum Master)
- **Duration**: 1 hour
- **Format**: What went well? What needs improvement? Action items?
- **Outcome**: 2-3 actionable improvements for next sprint

### Design Review
- **Attendees**: UX Designer, Product Manager, Developers, stakeholders
- **Duration**: 30-60 minutes
- **Format**: Present designs, gather feedback, discuss feasibility
- **Outcome**: Design approved or iteration plan, implementation guidance

### Architecture Review
- **Attendees**: Technical Architect, Developers, Project Manager
- **Duration**: 1 hour
- **Format**: Present technical design, discuss trade-offs, make decision
- **Outcome**: Approved architecture, documented decision, implementation plan

## Escalation Paths

### Level 1: Team-level
- **When**: Day-to-day blockers, clarifications, minor risks
- **Response time**: Same day
- **Who handles**: Scrum Master, Project Manager, Product Manager

### Level 2: Cross-team
- **When**: Dependencies blocked, resource conflicts, significant risks
- **Response time**: 1-2 days
- **Who handles**: Project Manager escalates to product leads, engineering managers

### Level 3: Leadership
- **When**: Business-impacting issues, major scope changes, critical risks
- **Response time**: Same day to 1 week depending on severity
- **Who handles**: Senior leadership, executives, sponsors

## Communication Tools

### Synchronous (Real-time)
- **Slack/Teams**: Quick questions, informal updates, links sharing
- **Video calls**: Complex discussions, design reviews, standups
- **In-person**: Sensitive topics, brainstorming, relationship building

### Asynchronous (Non-real-time)
- **Email**: Formal updates, stakeholder communications, decisions
- **GitHub PRs/Issues**: Code reviews, bug reports, feature discussions
- **Documentation**: Persistent knowledge, process guides, design docs
- **Dashboards**: Metrics, status, analytics

## Tips for Effective Cross-Functional Communication

1. **Know your audience**: Adjust technical depth based on who you're talking to
2. **Lead with context**: Don't assume others know what you're working on
3. **Be specific**: "I need X by Y" is better than "This is important"
4. **Use the right channel**: Don't use Slack for decisions that need a paper trail
5. **Follow up in writing**: Summarize verbal decisions in email or docs
6. **Tag appropriately**: Use @mentions sparingly and only when action is needed
7. **Respect time zones**: Schedule meetings fairly, use async when possible
8. **Document decisions**: Update shared docs so others can find context later
9. **Close the loop**: Confirm when issues are resolved or decisions are made
10. **Assume positive intent**: Written communication lacks tone—give benefit of the doubt

## Continuous Improvement
- Review communication patterns in retrospectives
- Update templates based on what works
- Share examples of effective communication
- Address communication breakdowns promptly and learn from them
