# EXP-08: Prompt Engineering for AI Workflow Automation

### Date : 03.09.2026
### Register No : 212224063003

---

# AIM

To design structured prompts for automating common workflow tasks such as email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation using Generative AI.

---

# OBJECTIVE

The objective of this experiment is to demonstrate how structured prompts can automate repetitive workflow activities and improve the efficiency, consistency, and clarity of project management.

---

# ENGINEERING USE CASE

## College Symposium Management

A college is organizing a technical symposium with multiple events, student participants, faculty coordinators, judges, sponsors, and volunteers.

The workflow requires:

- Planning events
- Assigning responsibilities
- Scheduling activities
- Communicating with participants
- Recording meetings
- Documenting requirements
- Answering common questions

AI is used to automate these tasks using structured prompts.

---

# WORKFLOW

```text
Symposium Requirements
          ↓
     Task Planning
          ↓
   Project Scheduling
          ↓
   Requirement Document
          ↓
    Meeting Minutes
          ↓
      Email Writing
          ↓
      FAQ Generation
          ↓
  Automated Workflow
```

---

# 1. EMAIL WRITING

## Purpose

Generate professional emails quickly using structured information.

## Prompt

> Act as a college event coordinator. Write a professional email inviting students to participate in a technical symposium.
>
> Event Name: TechFusion 2026  
> Date: 20 September 2026  
> Venue: Main Auditorium  
> Registration Deadline: 15 September 2026  
> Events: Paper Presentation, Coding Contest, Project Expo  
>
> Include a clear subject, greeting, event details, registration deadline, and a polite closing.

## Sample Output

### Subject: Invitation to TechFusion 2026

Dear Students,

We are pleased to invite you to **TechFusion 2026**, a technical symposium organized at the college on **20 September 2026** at the **Main Auditorium**.

Participants can register for events including:

- Paper Presentation
- Coding Contest
- Project Expo

The registration deadline is **15 September 2026**.

We encourage all interested students to participate and showcase their technical skills.

Regards,  
**Symposium Organizing Committee**

## Benefit

- Saves writing time
- Maintains professional tone
- Produces consistent communication

---

# 2. MEETING MINUTES

## Purpose

Convert meeting discussions into structured minutes.

## Prompt

> Convert the following symposium meeting discussion into formal meeting minutes. Include date, attendees, decisions, assigned responsibilities, deadlines, and action items.
>
> Discussion:
> - Symposium scheduled for 20 September.
> - Registration portal must be completed by 5 September.
> - Faculty coordinator will approve event rules.
> - Student volunteers will manage registration desks.
> - Technical team will arrange projectors and internet connectivity.

## Sample Output

### Meeting Minutes

**Meeting:** TechFusion 2026 Planning  
**Date:** 01 September 2026

| Discussion | Responsibility | Deadline |
|---|---|---|
| Registration portal | Registration Team | 05 Sep |
| Event rules | Faculty Coordinator | 07 Sep |
| Registration desk | Student Volunteers | 18 Sep |
| Projector and internet | Technical Team | 18 Sep |

### Key Decision

The symposium will be conducted on **20 September 2026**.

### Action Items

- Complete registration portal.
- Finalize event rules.
- Allocate volunteer teams.
- Test technical equipment.

---

# 3. TASK PLANNING

## Purpose

Convert project objectives into actionable tasks.

## Prompt

> Create a task plan for organizing a college technical symposium. Divide the work into major activities, assign a responsible team, define priority, and provide a deadline.

## Sample Output

| Task | Responsible Team | Priority | Deadline |
|---|---|---|---|
| Select events | Faculty Team | High | 03 Sep |
| Open registration | Registration Team | High | 05 Sep |
| Contact judges | Faculty Team | Medium | 08 Sep |
| Promote symposium | Media Team | High | 10 Sep |
| Arrange venue | Logistics Team | High | 18 Sep |
| Test equipment | Technical Team | High | 18 Sep |
| Final rehearsal | All Teams | High | 19 Sep |

## Benefit

Task planning becomes faster and responsibilities are easier to track.

---

# 4. PROJECT SCHEDULING

## Purpose

Create a timeline for completing the symposium activities.

## Prompt

> Create a project schedule for TechFusion 2026 from 1 September to 20 September 2026. Organize tasks chronologically and identify dependencies between tasks. Present the schedule in a table.

## Sample Output

| Activity | Start Date | End Date | Dependency |
|---|---|---|---|
| Event Finalization | 01 Sep | 03 Sep | None |
| Registration Setup | 03 Sep | 05 Sep | Event Finalization |
| Promotion | 05 Sep | 15 Sep | Registration Setup |
| Judge Confirmation | 04 Sep | 08 Sep | Event Finalization |
| Venue Preparation | 15 Sep | 18 Sep | Event Finalization |
| Technical Testing | 18 Sep | 19 Sep | Venue Preparation |
| Final Rehearsal | 19 Sep | 19 Sep | Technical Testing |
| Symposium | 20 Sep | 20 Sep | All Tasks |

---

# 5. REQUIREMENT DOCUMENTATION

## Purpose

Generate a structured requirement document for the symposium management system.

## Prompt

> Prepare a Software Requirement Specification for a College Symposium Management System. Include functional requirements, non-functional requirements, users, system inputs, system outputs, and major modules.

## Sample Output

### Functional Requirements

- Student registration
- Event selection
- Participant management
- Attendance tracking
- Schedule management
- Certificate generation
- Feedback collection

### Non-Functional Requirements

- Easy to use
- Secure
- Reliable
- Fast response
- Scalable

### Users

- Students
- Faculty coordinators
- Judges
- Volunteers
- Administrators

### Main Modules

```text
User Management
       ↓
Event Management
       ↓
Registration
       ↓
Schedule Management
       ↓
Attendance
       ↓
Certificate Generation
       ↓
Feedback
```

---

# 6. FAQ GENERATION

## Purpose

Automatically generate answers to frequently asked participant questions.

## Prompt

> Generate frequently asked questions for a college technical symposium. Include registration, eligibility, events, venue, deadlines, certificates, and contact information. Present the result in a question-and-answer format.

## Sample Output

### FAQ

**Q1. Who can participate?**  
Students who meet the eligibility requirements of the respective event can participate.

**Q2. What events are available?**  
Paper Presentation, Coding Contest, and Project Expo.

**Q3. What is the registration deadline?**  
The registration deadline is 15 September 2026.

**Q4. Where will the symposium be held?**  
The event will be conducted at the Main Auditorium.

**Q5. Will participants receive certificates?**  
Participants can receive certificates according to the event rules.

**Q6. How can I get support?**  
Participants can contact the symposium organizing committee.

---

# 7. STRUCTURED PROMPT TEMPLATE

A structured prompt can be written using the following components:

```text
ROLE
 ↓
TASK
 ↓
CONTEXT
 ↓
INPUT DATA
 ↓
CONSTRAINTS
 ↓
OUTPUT FORMAT
```

## Example

> **Role:** Act as a college event coordinator.  
> **Task:** Prepare a symposium schedule.  
> **Context:** Technical symposium with multiple events.  
> **Input:** Event list, dates, venue, staff availability.  
> **Constraints:** Avoid schedule conflicts and maintain realistic timing.  
> **Output Format:** Present the result as a table with activity, date, time, and responsible team.

---

# 8. AUTOMATED WORKFLOW

## Combined Prompt Workflow

```text
Event Requirements
       ↓
AI Task Planner
       ↓
Project Schedule
       ↓
Requirement Document
       ↓
Meeting Minutes
       ↓
Email Generation
       ↓
FAQ Generation
       ↓
Final Workflow Report
```

### Example Automation

```text
Input:
"TechFusion 2026, 20 September, 3 events"

        ↓

Task Planning
        ↓

Registration + Promotion + Venue + Technical Setup

        ↓

Scheduling
        ↓

Dates + Dependencies + Responsibilities

        ↓

Documentation
        ↓

Requirements + Meeting Minutes

        ↓

Communication
        ↓

Emails + FAQs
```

---

# COMPARISON OF MANUAL AND AI WORKFLOW

| Activity | Manual Process | AI-Assisted Process |
|---|---|---|
| Email Writing | Time-consuming | Fast |
| Meeting Minutes | Manual preparation | Automatically structured |
| Task Planning | Requires manual organization | Generated instantly |
| Scheduling | Manual coordination | Faster planning |
| Requirement Documentation | Requires more effort | Structured automatically |
| FAQ Generation | Manually written | Generated from context |
| Consistency | Depends on writer | More consistent |
| Productivity | Moderate | High |

---

# OBSERVATION

- Structured prompts make workflow automation more consistent and organized.
- AI can generate emails, meeting minutes, task lists, schedules, requirements, and FAQs from the same project information.
- Using clear roles, context, constraints, and output formats improves the usefulness of generated results.
- Human review is still required before using AI-generated content in real project communication.

---

# RESULT

A structured AI-assisted workflow was successfully designed for **College Symposium Management**. AI was used to automate email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation.

---

# CONCLUSION

Prompt engineering can automate repetitive workflow activities and reduce manual effort in project management. Structured prompts provide consistent and well-organized outputs, while human verification ensures that the generated information is correct and suitable for real-world use. The experiment demonstrates that Generative AI can act as an effective assistant for managing engineering and academic project workflows.

---

# DELIVERABLE

**Automated Workflow Documentation for College Symposium Management**
