---
layout: default
title: Project Management
parent: Week 8
grand_parent: Unit 3
nav_order: 2
---

# Project Management Documentation & Tools

In the previous page, we explored the fundamentals of production management, including production workflows, the project manager's role, and various project management methodologies. Now we'll examine the concrete resources and tools that project managers use to organize their work and facilitate the communication necessary when teams collaborate.

All of the documentation and technology presented on this page serves a single critical purpose: **to organize and facilitate communication within project teams**. Effective project management is fundamentally about ensuring that everyone involved has the information they need, when they need it, to make good decisions and deliver quality work.

The tools and documentation types covered here represent common industry practices, but this list is not comprehensive. Different industries, organizations, and project types may require additional or alternative documentation approaches.

---

## Documentation

Project managers rely on various types of documentation to track progress, manage risks, and maintain clear communication channels. The following table introduces three essential documentation types used across many industries:

| Documentation Type | Description | Primary Use |
|-------------------|-------------|-------------|
| **Gantt Charts** | Horizontal bar charts that visualize project timelines, task dependencies, and milestones | Planning and tracking project schedules; visualizing workflow sequencing |
| **Risk Registers** | Systematic records of identified risks, their likelihood, impact, and mitigation strategies | Proactively managing potential project obstacles; documenting risk response plans |
| **Query Trackers** | Centralized logs of questions, clarifications, and decisions made throughout a project | Maintaining consistency; documenting decisions; preventing repeated questions |

Each of these documentation types serves specific communication needs within project management. Let's explore them in greater detail.

---

### Gantt Charts

A Gantt chart is an invaluable tool for visualizing workflow timelines and dependencies. This horizontal bar chart tracks timing and progress, identifying important milestones in project workflows. For busy project managers context-switching among multiple projects, Gantt charts provide at-a-glance visibility into whether projects remain on track to meet agreed-upon delivery dates.

Understanding **sequencing** is crucial when creating Gantt charts. In the chapter "Project time management in translation and localization," Keiran J. Dunne defines different types of activity sequencing. The traditional **"finish-to-start"** process requires a predecessor stage to be completed before the next stage can begin. However, finish-to-start processes aren't the only option. Turnaround times can be reduced by using **"start-to-start"** processes, in which a following stage begins around the same time as the predecessor stage, allowing parallel work streams.

#### Example Gantt Chart

Below is a simplified Gantt chart illustrating both finish-to-start and start-to-start processes for a translation project:

| Task | Week 1 | Week 2 | Week 3 | Week 4 |
|------|--------|--------|--------|--------|
| **Project Setup** | ████████ | | | |
| **Source Analysis** | | ████████ | | |
| **Translation** | | ████ | ████████ | |
| **Editing** (start-to-start) | | | ████ | ████ |
| **Proofreading** (finish-to-start) | | | | ████████ |
| **Final QA & Delivery** | | | | ████ |

**Legend:** ████ = Active work period

Notice how Translation and Editing overlap (start-to-start), while Proofreading can only begin after Editing is complete (finish-to-start). This sequencing allows the team to reduce overall project time while maintaining quality control.

**Explore this topic further:**
- [Gantt Chart 101: How to Build and Use Them Effectively](https://slack.com/blog/productivity/gantt-chart-101-how-to-build-and-use-them-effectively) by Slack
- [The Hard Side of Project Management](https://universidaduic.sharepoint.com/:v:/s/TR35-BusinessEnglishII-2026-1/EU6_s_n9dmhCsFQTiKZmvuEBNrH3B-W0RIUWPftqcf6ibA?e=7w2OmJ) by Carina Balbo - a selection of this video has been provided to students privately on Teams; please do not share this outside of our course

#### Reflection Questions

1. What are the advantages and disadvantages of start-to-start sequencing compared to finish-to-start sequencing?
2. In what situations might a project manager choose to use finish-to-start sequencing even if start-to-start is possible?

---

### Risk Registers

Risk management is a critical component of successful project management. Rather than reacting to problems as they arise, effective project managers proactively identify potential risks, assess their likelihood and impact, and develop mitigation strategies before issues materialize.

A **risk register** is a systematic tool for documenting identified risks throughout a project's lifecycle. This living document helps teams:
- Anticipate potential obstacles before they become crises
- Allocate resources appropriately to high-impact risks
- Communicate risks transparently with stakeholders
- Track mitigation efforts and their effectiveness

Risk registers typically include several key elements for each identified risk: a clear description of what could go wrong, the probability of occurrence, the potential impact on the project, assigned ownership for monitoring and response, and planned mitigation strategies.

#### Example Risk Register

| Risk ID | Risk Description | Probability | Impact | Owner | Mitigation Strategy | Status |
|---------|-----------------|-------------|--------|-------|-------------------|--------|
| R-001 | Source files contain embedded text in graphics requiring additional processing | Medium | High | PM | Request editable source files during kickoff; budget extra time for graphic handling | Active |
| R-002 | Subject matter expert unavailable for terminology review during peak translation phase | Low | Medium | Client Lead | Identify backup SME; conduct terminology review during project setup phase | Mitigated |
| R-003 | Translation memory from previous project contains inconsistent terminology | Medium | Medium | Quality Lead | Conduct TM cleanup before project start; establish clear terminology for this project | Active |
| R-004 | Key translator unavailable due to scheduling conflict | Low | High | Resource Manager | Identify backup translator with similar specialization; maintain relationships with multiple qualified resources | Monitored |
| R-005 | Client requests scope changes late in production affecting delivery timeline | Medium | High | PM/Account Manager | Include change management process in project agreement; communicate impact of changes clearly | Active |

**Explore this topic further:**
- [ISO 31000 Risk Management Guidelines](https://www.iso.org/obp/ui/en/#iso:std:iso:31000:ed-2:v1:en)
- [What is a risk register: a project manager's guide (and example)](https://asana.com/resources/risk-register) by Asana

#### Reflection Questions

1. Why is it important to assign an owner to each risk rather than making risk management a general team responsibility?
2. How might risk management practices differ between short-term projects (under one week) and long-term projects (several months)?

---

### Query Trackers

In any complex project, questions and clarifications are inevitable. Whether team members need guidance on terminology choices, clients require explanations about technical processes, or stakeholders need clarity on project decisions, a systematic approach to managing these queries prevents confusion and ensures consistency.

A **query tracker** (also called a query log or query sheet) is a centralized document that records all questions raised during a project, along with their responses and resolution status. This tool serves multiple essential functions:
- Prevents the same questions from being asked repeatedly
- Documents important decisions and their rationale
- Maintains a searchable knowledge base for future reference
- Ensures all team members have access to the same information
- Tracks response times and identifies communication bottlenecks

Query trackers are particularly valuable in translation and localization projects, where linguistic decisions must remain consistent across large volumes of content and multiple team members. However, the principle of systematic query management applies across all industries where teams must coordinate their work and maintain consistency.

#### Example Query Tracker

| Query ID | Date Raised | Raised By | Category | Query | Response | Responded By | Date Resolved | Status |
|----------|-------------|-----------|----------|-------|----------|--------------|---------------|--------|
| Q-001 | 2025-09-15 | Translator A | Terminology | Should "cloud computing" be translated literally or left in English for technical audience? | Leave in English - confirmed with client that target audience is technical IT professionals familiar with English terminology | PM | 2025-09-15 | Closed |
| Q-002 | 2025-09-18 | Editor B | Style | Client's style guide specifies formal register, but source content uses casual tone. Which takes priority? | Follow style guide register. Client confirmed formal tone is required for brand consistency | Quality Lead | 2025-09-19 | Closed |
| Q-003 | 2025-09-20 | Proofreader C | Content | Source text contains apparent error in statistical data (25% vs 2.5%). Should we query client or correct? | Query sent to client for verification before correction | PM | Pending | Open |
| Q-004 | 2025-09-22 | Translator D | Technical | Source file contains locked sections. Do these require translation? | Client confirmed locked sections are placeholders and should not be translated | Technical Lead | 2025-09-22 | Closed |
| Q-005 | 2025-09-23 | QA Reviewer | Terminology | Terms "usuario" and "usuaria" both appear in target text. Should we standardize? | Use inclusive form "usuaria/usuario" or neutral alternatives where possible, per client's diversity guidelines | Client Lead | 2025-09-24 | Closed |

**Explore this topic further:**
- [Query Sheet Management for Project Managers and Translators](https://terralocalizations.com/wp-content/uploads/2024/01/ENG-Query-Sheet-Management-for-Project-Managers-and-Translators-Marina-Ilari.pdf) by Marina Ilari
- [Are you Trapped in The Translation Query Management Maze?](https://slator.com/trapped-in-translation-query-management-maze-heres-how-to-escape) by Kaleidoscope

#### Reflection Questions

1. How does maintaining a query tracker contribute to quality management and knowledge retention beyond just a single project?
2. What challenges might arise in maintaining query trackers for very large projects with multiple team members, and how might these be addressed?

---

### Discussion Question

**What additional documents should be added to a project manager's documentation suite?**

Think about projects you've been involved in or industries you're interested in. What other types of documentation would help project managers communicate effectively and keep projects on track? Share your thoughts on the Teams channel, explaining:
- What type of documentation you're suggesting
- What communication need it addresses
- In what situations it would be most valuable

---

## Technology

While documentation types like Gantt charts and risk registers define *what* information project managers need to track, technology platforms provide the *how* — the systems and tools that make documentation accessible, collaborative, and actionable.

A variety of technological platforms are available for project management, each with different strengths and designed for different workflows. The platform choice often depends on factors such as team size, project complexity, budget, integration needs with other tools, and organizational preferences.

Some popular project management platforms include:

- **[GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)** - Integrated with code repositories, ideal for software development projects
- **[Notion](https://www.notion.com/)** - Flexible workspace combining wikis, databases, and project boards
- **[Trello](https://trello.com/)** - Visual Kanban-style boards for task management
- **[Airtable](https://www.airtable.com)** - Spreadsheet-database hybrid with powerful linking and views
- **[Asana](https://asana.com)** - Comprehensive project management with multiple view options
- **[Monday.com](https://monday.com)** - Customizable work operating system with automation

Many organizations also use combinations of standard office tools like Google Workspace (Docs, Sheets, Drive) or Microsoft 365 (Word, Excel, SharePoint, Teams) to build custom project management solutions that integrate with their existing infrastructure.

### Class Discussion

**Share your project management technology experience:**

Have you used any of the above tools before, or other project management platforms not listed here? Please share your experiences and recommendations on Teams, addressing:
- Which platform(s) you've used
- What type of project or work you used it for
- What you found most helpful about the platform
- Any limitations or challenges you encountered
- Whether you would recommend it to others, and for what types of projects

If you haven't used project management platforms before, research one of the tools listed above and share what appeals to you about it or what concerns you might have about using it.

---

## 📥 Download this Content
Find this file [on our repo](https://github.com/alainamb/uic_tr35-business-english-II/blob/main/unit3/week8/project-management.md) and download it.

### 🤖 GAI Study Prompts
Copy the downloaded content and try it with these prompts:
- "Help me create a Gantt chart for [describe your project type]"
- "What are the most critical risks I should consider for [specific project type] and how should I document them?"
- "Generate a query tracker template customized for [your industry or project type]"
- "Compare the advantages and disadvantages of different project management platforms for [specific needs]"
- "What documentation would be most important for managing [describe your project scenario]?"
- "How do I decide between finish-to-start and start-to-start sequencing for different types of tasks?"
- "What are best practices for maintaining project documentation in fast-paced environments?"

---

**Next Activity**: [Project Management Plan Assignment](project-management-plan-assignment.md)
