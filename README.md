# Ex.No.7 — AI-Assisted Workflow Automation Using Structured Prompts


REGISTER NUMBER: 212224063003


---

## Aim

To automate common engineering-project documentation and communication tasks — Email Writing, Meeting Minutes, Task Planning, Project Scheduling, Requirement Documentation, and FAQ Generation — using structured prompts, and to compile the outputs into a single automated workflow document for a real engineering project scenario.

**AI Tools Required:** ChatGPT, Claude, Gemini (any AI text-generation tool capable of following structured, template-based prompts).

---

## Engineering Example Selected

**Project: Drone Survey Project**

**Context:** A student team is developing an autonomous drone-based land survey system for mapping agricultural fields and generating elevation/vegetation reports. The team needs to manage communication, meetings, tasks, scheduling, requirements, and stakeholder queries throughout the project lifecycle — this experiment automates that documentation workflow using structured AI prompts.

---

## Procedure

1. Identify the recurring documentation/communication tasks in a typical engineering project lifecycle.
2. For each task, design a **structured prompt** (clear role, context, required fields, and output format) rather than an open-ended request.
3. Run each structured prompt through an AI tool and record the output.
4. Review each output for accuracy, completeness, and professional tone.
5. Compile all six automated outputs into a single **Automated Workflow Documentation** package for the Drone Survey Project.

---

## 1. Email Writing (Automated)

**Structured Prompt:**
> "Write a professional email from a final-year engineering student to the faculty project guide, requesting approval to procure a LiDAR sensor module for a drone survey project. Include: subject line, greeting, purpose, brief justification (2–3 lines), estimated cost, and a polite closing requesting a reply by Friday."

**Generated Output (sample):**
> **Subject:** Request for Approval — LiDAR Sensor Procurement for Drone Survey Project
>
> Dear Professor,
>
> I hope you are doing well. As part of our final-year Drone Survey Project, our team requires a LiDAR sensor module to accurately capture elevation data for the agricultural field mapping module. The sensor will improve terrain-mapping accuracy significantly compared to our current camera-only approach. The estimated cost of the module is ₹8,500, within our allocated project budget.
>
> Could you kindly review and approve this procurement? We would appreciate a response by Friday so we can proceed with ordering in time for our next testing phase.
>
> Thank you for your continued guidance.
>
> Regards,
> [Team Name], Drone Survey Project Team

---

## 2. Meeting Minutes (Automated)

**Structured Prompt:**
> "Generate meeting minutes for a project team meeting with the following details: Date: [date], Attendees: 4 team members + guide, Agenda: review flight-controller integration progress, discuss LiDAR procurement, assign next sprint tasks. Format as: Meeting Title, Date, Attendees, Agenda, Discussion Summary, Action Items with owners and due dates."

**Generated Output (sample):**

| Field | Details |
|---|---|
| Meeting Title | Drone Survey Project — Weekly Review |
| Date | [Insert Date] |
| Attendees | Team Members A, B, C, D; Project Guide |
| Agenda | Flight-controller integration status, LiDAR procurement update, sprint task assignment |
| Discussion Summary | Flight-controller PID tuning is 70% complete; minor drift observed during hover tests. LiDAR procurement approved, expected delivery in 5 days. Team agreed to begin sensor-fusion module design in parallel. |
| Action Items | 1. Member A — Fix hover drift by refining PID gains (Due: 3 days). 2. Member B — Track LiDAR delivery and prepare mounting bracket (Due: 5 days). 3. Member C — Draft sensor-fusion architecture (Due: 1 week). 4. Member D — Update project documentation with current progress (Due: 3 days). |

---

## 3. Task Planning (Automated)

**Structured Prompt:**
> "Create a task breakdown for the next two weeks of the Drone Survey Project's flight-controller and sensor integration phase. Format as a table with Task, Owner, Priority (High/Medium/Low), and Estimated Duration."

**Generated Output (sample):**

| Task | Owner | Priority | Estimated Duration |
|---|---|---|---|
| Tune PID controller to fix hover drift | Member A | High | 3 days |
| Mount and wire LiDAR sensor | Member B | High | 2 days |
| Design sensor-fusion (IMU + LiDAR) architecture | Member C | Medium | 5 days |
| Update GPS waypoint navigation logic | Member A | Medium | 4 days |
| Conduct outdoor test flight #3 | All | High | 1 day |
| Update project documentation | Member D | Low | 2 days |

---

## 4. Project Scheduling (Automated)

**Structured Prompt:**
> "Generate a 6-week project schedule for the Drone Survey Project covering: hardware assembly, flight-controller tuning, sensor integration, field survey algorithm development, testing, and final report preparation. Present as a week-by-week table with milestones."

**Generated Output (sample):**

| Week | Phase | Milestone |
|---|---|---|
| 1 | Hardware Assembly | Frame, motors, ESCs, flight controller assembled and powered on |
| 2 | Flight-Controller Tuning | Stable hover achieved; PID tuning completed |
| 3 | Sensor Integration | LiDAR + camera + GPS integrated and streaming data |
| 4 | Survey Algorithm Development | Waypoint-based field-scan path planning implemented |
| 5 | Field Testing | Two outdoor test flights completed; data validated against ground truth |
| 6 | Reporting & Documentation | Final report, elevation/vegetation maps, and presentation completed |

---

## 5. Requirement Documentation (Automated)

**Structured Prompt:**
> "Generate a requirement document for the Drone Survey Project. Include: Functional Requirements, Non-Functional Requirements, Hardware Requirements, and Software Requirements, each as a bulleted list."

**Generated Output (sample):**

**Functional Requirements**
- The drone shall autonomously follow a pre-planned waypoint path over the target field.
- The system shall capture RGB and elevation (LiDAR) data during flight.
- The system shall generate a vegetation health map and elevation contour map post-flight.

**Non-Functional Requirements**
- The system shall maintain stable flight in wind speeds up to 20 km/h.
- Data processing shall complete within 30 minutes of flight completion.
- The system shall log flight telemetry for post-mission analysis.

**Hardware Requirements**
- Quadcopter frame with brushless motors and ESCs.
- Flight controller (e.g., Pixhawk) with GPS module.
- LiDAR sensor and RGB camera payload.

**Software Requirements**
- Ground control station software for mission planning (e.g., QGroundControl).
- Image-processing pipeline for orthomosaic and NDVI map generation.
- Data storage and visualization dashboard.

---

## 6. FAQ Generation (Automated)

**Structured Prompt:**
> "Generate a FAQ section (5 questions and answers) for stakeholders (farmers/faculty) evaluating the Drone Survey Project, covering cost, accuracy, flight time, data output, and safety."

**Generated Output (sample):**

1. **How accurate is the elevation and vegetation data?** The system targets sub-30cm elevation accuracy and NDVI-based vegetation health mapping, validated against ground-truth samples during testing.
2. **What is the flight time per survey?** The drone can survey approximately 5–8 acres per flight on a single battery charge (~18–20 minutes flight time).
3. **What does the survey report include?** An elevation contour map, a vegetation health (NDVI) map, and a summary report highlighting problem zones.
4. **Is the drone safe to operate near people and livestock?** The drone maintains a minimum safe altitude and includes an automatic return-to-home failsafe if signal is lost or battery is low.
5. **What is the estimated cost per survey?** Approximate operating cost is significantly lower than manual land surveying, primarily covering battery charging and minor equipment maintenance.

---

## Automated Workflow Documentation (Deliverable)

The six automated outputs above were compiled into a single workflow package for the Drone Survey Project:

```
Drone Survey Project — Automated Documentation Workflow
│
├── 1. Communication
│     └── Procurement approval email (LiDAR sensor)
│
├── 2. Meeting Management
│     └── Weekly review meeting minutes with action items
│
├── 3. Task Planning
│     └── 2-week sprint task breakdown (owner, priority, duration)
│
├── 4. Project Scheduling
│     └── 6-week phase-wise project schedule with milestones
│
├── 5. Requirement Documentation
│     └── Functional / Non-functional / Hardware / Software requirements
│
└── 6. Stakeholder Communication
      └── FAQ document for farmers/faculty evaluators
```

This package demonstrates that a single engineering project's entire documentation lifecycle — from an approval email to stakeholder FAQs — can be generated consistently and quickly using structured, field-filled prompts rather than free-form requests.

---

## Observations

- **Structured prompts** (specifying exact fields, format, and audience) produced consistently usable, near-final outputs, unlike open-ended prompts which required more editing.
- Reused project context (drone type, sensors, timeline) across all six prompts kept the outputs internally consistent — the same LiDAR procurement mentioned in the email also appeared correctly in the meeting minutes and task plan.
- Documents like **meeting minutes** and **task tables** benefited most from structured prompting, since their value depends entirely on correct formatting.
- **FAQ generation** required the most human review, since factual claims (accuracy figures, flight time) need to be verified against actual project test data before being shared with real stakeholders.

---

## Conclusion

Structured prompting proved highly effective for automating routine but essential project-documentation tasks — email writing, meeting minutes, task planning, scheduling, requirement documentation, and FAQ generation — for the Drone Survey Project. By specifying role, context, required fields, and output format in each prompt, the AI consistently produced professional, ready-to-use documentation, significantly reducing the manual effort typically spent on project administration and allowing the team to focus more time on core engineering work.

---

## Result

The structured prompts for automating Email Writing, Meeting Minutes, Task Planning, Project Scheduling, Requirement Documentation, and FAQ Generation were executed successfully for the Drone Survey Project, and the outputs were compiled into a complete Automated Workflow Documentation deliverable.
