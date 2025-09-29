---
layout: default
title: PM Plan Example
parent: Week 8
grand_parent: Unit 3
nav_order: 4
---

# Project Title: Action Items Professional
**Project Manager:** Alaina Brandt

## Project Description
*Action Items Professional* aka *Action Items Pro* is a web application for tracking one's todo list. Todos can be organized according to filters like project and status. The app features both list and schedule views. Estimated and actual completion times can be added to the todos recorded in the app - useful for understanding estimation accuracy and task completion rates.

## People Involved
Here is the contact list for the project, along with information about who to contact in specific circumstances.

| Name | Role | Contact About... | Contact Info |
|------|------|------------------|--------------|
| Alaina Brandt | Project Manager & Lead Developer | Status updates, project instructions, feature requests, design preferences | alainambrandt@gmail.com |
| Wei Chen | Backend Developer | Database architecture, API development, server-side logic | wchen@actionitemspro.dev |
| María González | Frontend Developer | User interface implementation, responsive design, client-side functionality | mgonzalez@actionitemspro.dev |
| Fatima Al-Rashid | UI/UX Designer | Visual design, user experience, accessibility standards | falrashid@actionitemspro.dev |
| Thabo Khumalo | QA Lead | Testing strategies, quality standards, bug prioritization | tkhumalo@actionitemspro.dev |
| Lin Zhang | QA Tester | Bug reports, test case execution, regression testing | lzhang@actionitemspro.dev |
| Diego Ramírez | Marketing Manager | Social media strategy, content calendar, brand messaging | dramirez@actionitemspro.dev |
| Naledi Mbeki | Content Writer | Marketing copy, help documentation, user guides | nmbeki@actionitemspro.dev |
| Omar Hassan | Sales Manager | Client onboarding, pricing strategy, partnership opportunities | ohassan@actionitemspro.dev |

## Gantt Chart

Below is our project timeline organized by major phases. The current date is Week 1 of our development cycle.

| Phase / Task | Week 1-2 | Week 3-4 | Week 5-6 | Week 7-8 | Week 9-10 |
|--------------|----------|----------|----------|----------|-----------|
| **MVP Features Development** | | | | | |
| User preferences page | ████████ | ████ | | | |
| Drag and drop functionality | | ████████ | ████ | | |
| Reset password functionality | ████████ | | | | |
| Sales page and user access groups | | | ████████ | ████ | |
| **Quality Assurance** (start-to-start) | | | ████ | ████████ | ████ |
| Fix known bugs | | | ████████ | ████ | |
| QA testing on entire site | | | | ████████ | ████ |
| Pilot with early adopters | | | | | ████████ |
| Collect and implement feedback | | | | | ████████ |
| **Marketing & Sales** (start-to-start) | | | | ████ | ████████ |
| Develop marketing materials | | | | ████████ | ████ |
| Social media campaign launch | | | | | ████████ |
| **Project Launch** | | | | | ████ |

**Legend:** ████ = Active work period

## Risk Register

We've identified five main risks for the web application, along with the risk mitigation strategies outlined in the chart. When you identify a new risk, please add it to the risk register and notify the project manager.

| Risk ID | Risk Description | Probability | Impact | Owner | Mitigation Strategy | Status |
|---------|-----------------|-------------|--------|-------|-------------------|--------|
| R-001 | Drag and drop functionality may not work consistently across all browsers | Medium | High | Wei Chen | Conduct cross-browser testing early; use well-tested libraries; allocate buffer time for troubleshooting | Active |
| R-002 | Early adopters may request significant feature changes during pilot phase, affecting launch timeline | High | Medium | Alaina Brandt | Set clear expectations about pilot scope; prioritize feedback into immediate vs. future releases; maintain version 2.0 roadmap | Active |
| R-003 | Team members working across multiple time zones may cause communication delays | Medium | Medium | Alaina Brandt | Establish core overlap hours for meetings; use asynchronous communication tools effectively; document decisions thoroughly | Mitigated |
| R-004 | Database performance issues may emerge as user base grows | Low | High | Wei Chen | Design with scalability in mind; conduct load testing before launch; plan infrastructure upgrade path | Monitored |
| R-005 | Security vulnerabilities in password reset functionality could compromise user accounts | Low | High | Wei Chen & Thabo Khumalo | Follow security best practices; conduct security audit before launch; implement rate limiting and email verification | Active |

## Queries Tracker

We welcome your questions as you go about your work. Here are some frequently asked questions we've encountered as we carry out development work. When you have a question, please add it to the queries tracker and notify the project manager.

| Query ID | Date Raised | Raised By | Category | Query | Response | Responded By | Date Resolved | Status |
|----------|-------------|-----------|----------|-------|----------|--------------|---------------|--------|
| Q-001 | 2025-09-15 | María González | Design | Should the drag-and-drop feature work on mobile devices, or is it desktop-only for MVP? | Desktop-only for MVP. Mobile users will use tap-to-edit functionality. Full mobile drag-and-drop scheduled for v2.0 based on user demand | Alaina Brandt | 2025-09-15 | Closed |
| Q-002 | 2025-09-22 | Lin Zhang | Testing | During QA testing, should we prioritize testing on the most popular browsers or test all browsers equally? | Prioritize Chrome, Safari, and Firefox (covers 85% of our target users). Edge and Opera are secondary. Document any browser-specific issues for future reference | Thabo Khumalo | 2025-09-22 | Closed |
| Q-003 | 2025-09-25 | Wei Chen | Technical | The estimated completion time feature requires timezone handling. Should we store times in UTC or user's local timezone? | Store all timestamps in UTC in database. Convert to user's local timezone for display. This prevents confusion for users who travel or work across timezones | Alaina Brandt | 2025-09-25 | Closed |
| Q-004 | 2025-09-27 | Diego Ramírez | Marketing | What key features should we highlight in our social media launch campaign? Are there any features we should avoid emphasizing? | Highlight: (1) organizing todos by project, (2) drag-and-drop simplicity, (3) schedule view for time blocking. Avoid: mentioning features planned for v2.0 that aren't in MVP yet | Alaina Brandt | 2025-09-28 | Closed |
| Q-005 | 2025-09-29 | Omar Hassan | Sales | Should we offer a free tier or start with paid-only subscriptions at launch? | Launch with freemium model: free tier with core features (up to 50 todos), paid tier unlocks unlimited todos, advanced filtering, and priority support. This reduces barrier to adoption | Alaina Brandt | Pending | Open |

## Project Management Platform

We are using GitHub Projects to manage this project. We have a number of boards that we use there to track our progress. These include:

- **Roadmap Board** - Here we track our progress on the features that need to be developed ahead of product launch, along with the more advanced features we have planned for version 2.0 and beyond
- **Bug Tracker** - We use this board to log and monitor bugs, record information about fixes, and track testing status
- **Sprint Planning Board** - We organize our two-week sprints here, moving tasks from backlog to in-progress to completed
- **Team Retrospective Board** - Here we reflect on what went well about a sprint and what can be improved next time, fostering continuous improvement

All team members have access to these boards and are expected to update their task statuses daily. The project manager reviews all boards each morning and addresses any blockers or concerns raised by team members.

---

## 📥 Download This Content

Find this file [on our repo](https://github.com/alainamb/uic_tr35-business-english-II/blob/main/unit3/week8/pm-plan-example.md) and download it!

---

**Week 8 Complete!** Next week we'll explore [Quality Management Systems](../week9/week9-overview.md)
