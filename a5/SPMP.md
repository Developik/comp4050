<div style="text-align: center;">

# **_ProCaller_**

**Software Project Management Plan**

### Version 7.0

### 11/21/2023

# Wind Falcons

</div>

## Revision History

| **Date**     | **Description** | **Author**       | **Comments**              |
| ------------ | --------------- | ---------------- | ------------------------- |
| _11/21/2023_ | _Version 1.0_   | _Ryan Dotzlaw_   | _Initial Document Commit_ |
| _11/22/2023_ | _Version 2.0_   | _Ryan Dotzlaw_   | _Completed Section 1_     |
| _11/23/2023_ | _Version 3.0_   | _Josh Sigurdson_ | _Completed Section 4_     |
| _11/23/2023_ | _Version 4.0_   | _Ikram Khan_     | _Added Section 3_         |
| _11/24/2023_ | _Version 5.0_   | _Andrii Provozin_| _Added Section 5_         |
| _11/24/2023_ | _Version 6.0_   | _Khush Patel_     | _Added Section 2_        |
| _11/24/2023_ | _Version 6.1_   | _Khush Patel_     | _Added Section 3.2_        |
| _11/24/2023_ | _Version 7.0_   | _Khush Patel_     | _Fixed Errors and Added Section 6_        |


**Table of Contents**

- [1. Project Overview](#1-project-overview)
  - [1.1 Purpose, Scope, and Objectives](#11-purpose-scope-and-objectives)
  - [1.2 Assumptions, Constraints, and Risks](#12-assumptions-constraints-and-risks)
  - [1.3 Project Deliverables](#13-project-deliverables)
  - [1.4 Schedule and Budget Summary](#14-schedule-and-budget-summary)
  - [1.5 References](#15-references)
  - [1.6 Definitions and Acronyms](#16-definitions-and-acronyms)
- [2. Project Organization](#2-project-organization)
  - [2.1 Organizational Structure](#21-organizational-structure)  
      - [2.1.1 Internal Structure](#211-internal-structure-of-the-organization-for-procaller-project)
      - [2.1.2 External Stricture](#212-external-structure-of-the-organization-for-procaller-project)
  - [2.2 Roles and Responsibilities](#22-roles-and-responsibilities)
- [3. Managerial Process Plans](#3-managerial-process-plans)
  - [3.1 Start-up Plan](#31-start-up-plan)
    - [3.1.1 Estimates](#311-estimates)
    - [3.1.2 Staffing](#312-staffing)
    - [3.1.3 Resource Acquisition](#313-resource-acquisition)
  - [3.2 Work Plan](#32-work-plan)
    - [3.2.1 Work Breakdown Structure](#321-work-breakdown-structure)
    - [3.2.2 Schedule Allocation](#322-schedule-allocation)
    - [3.2.3 Resource Allocation](#323-resource-allocation)
    - [3.2.4 Budget Allocation](#324-budget-allocation)
  - [3.3 Project Tracking Plan](#33-project-tracking-plan)
    - [3.3.1 Requirements Control](#331-requirements-control)
    - [3.3.2 Schedule Control](#332-schedule-control)
    - [3.3.3 Communication Plan](#333-communication-plan)
    - [3.3.4 Project Closeout Plan](#334-project-closeout-plan)
- [4. Technical Process Plans](#4-technical-process-plans)
  - [4.1 Process Model](#41-process-model)
  - [4.2 Methods, Tools, and Techniques](#42-methods-tools-and-techniques)
  - [4.3 Infrastructure](#43-infrastructure)
  - [4.4 Product Acceptance](#44-product-acceptance)
- [5. Supporting Process Plans](#5-supporting-process-plans)
  - [5.1 Documentations](#51-documentations)
  - [5.2 Quality Assurance](#52-quality-assurance)
- [6. Additional Plans](#6-additional-plans)

# 1. Project Overview

## 1.1 Purpose, Scope, and Objectives

The purpose of the _ProCaller_ project is to create an online phone system to place virtual calls between users anytime.
This online phone system will be accessed by the users through an application designed to work on desktop, laptop and mobile devices.

_ProCaller_ will remove the need for users to have additional devices, such as cellphones or landline phones, to communicate with other users.
For example, this would allow companies to not have to spend money supplying their employees with these devices.
Instead it would allow employees to use any internet connected device, such as an already provided work computer or a personal device.

Elements that are within the projects scope are as follows:

- Audio-Only Calls between users
- Ability to create outgoing calls and receive incoming calls on the app
- Allowing users to log into their accounts on the app
- Seamless routing of incoming calls to all of a user’s logged in apps, regardless of the platform
- Tracking Call Logs
- Functional application for mobile devices and computers
- Monitoring and Moderation software for the system
- Calculating user’s bills
- Informing users of their bills

Elements that are out of the project scope include the following:

- Video Calls between users
- Text chat between users
- Web-based application
- Recording calls
- Integration with other systems (pre-recorded messages, call menus)
- Voicemail

Video calls and text chat were not included in the scope since they aren't included in the project's purpose of creating a 'landline-esque' online phone system.
Additionally, including these two elements would greatly increase the complexity of the project at all levels, leading to a larger allocation of resources than availiable for this project.

A web-based application isn't included in the scope due to the stakeholders explicitly requesting the project to be implemented as a downloadable application.
The lack of a web-based application will remove the need for servers to run the application, leading to lower maintenance costs once the project is running.

Recording calls, integration with other systems, and voicemail were all deemed unnecessary by the stakeholders, so they were not included in the project's scope.

The project objectives are as follows:

- _In 6 months, create an app that can be used on mobile devices and computers that allows users of the app to call other users, regardless of application platform, over the internet._
- _In 8 months, create a backend server that routes the numbers dialed by a user to an (IP, Port) pair, connecting one user to another using the server as an intermediary. Additionally, the backend server needs to store users, and log call metadata (length, time, etc.) for determining the billing cost._
- _In 1 year, 2 months, design a GUI called the System Console, that allows specific members of a client company to control and monitor their own Online Virtual Phone System network. Performing actions like finding available phone numbers, setting phone number – (IP, Port) mapping, controlling calls per user, etc._
- _In 1 year, 6 months, create a billing system that calculates the cost a client company owes based on the calls made by their users and their plan, among other factors. Additionally, the billing system needs to send a bill to the user at the end of the current billing period, and any Administrators should be able to view a client’s current bill using the System Console._

There is one major deliverable for each objective, in order they are:

- The creation of the frontend application
- The creation of the routing server
- The creation of the system console
- The creation of the billing system

Each of the project's objectives will be considered complete if it meets the following conditions:

- The major deliverable meets the conditions defined in it's associated project objective.
- The major deliverable integrates and works with any previous project deliverables.
- The major deliverable has completed all the tasks associated with it, as defined in the project schedule's work breakdown structure.

The project of developing _ProCaller_ can potentially have several relationships with other projects:

- An advertisment project made to promote _ProCaller_.
- A project for the expansion of company server infrastructure depending on estimated _ProCaller_ demand and performance.
- As one of potentially many smaller projects started to achieve the goal of a larger project started by management to increase company profits.

As a result, this project will need to maintain communication with the company IT group to cover hardware requirements and server maintenance.
In addition, this project will need to integrate with the company's PR team for any advertising.

A reference to the official statement of project requirements can be found in the [project charter](../a1/Project_Charter.md).

## 1.2 Assumptions, Constraints, and Risks

There are four assumptions this project makes:

1. _Users of the online virtual phone system are expected to have access to dependable internet and cloud services in order to place and receive calls._
2. _Only one administrator can access the system at a time._
3. _Both clients have initiating the call have our app installed on their devices_.
4. _Administrators acquired other required permissions to make changes to user's plan (legal right to change the plan, approval from the manager, etc.)_.

The project's constraints are:

- The system needs to make sure that no phone numbers can start with a particular prefix that is used for advanced features. The available phone numbers are constrained by this restriction, which should be taken into account while designing the dialing plan.
- The billing software must correctly determine prices depending on call length, time of day, and calling plan. A crucial restriction is ensuring accuracy in billing calculations.
- The system should be capable of keeping user records should be retained indefinitely, so storage auto-scaling should be taken into consideration.
- Client application should be connecting to the routing server via sockets.
- System should have database schema set up in a way that would allow fetching any user's bill for any billing period.
- Version control software, specifically Github, will be used for the project's development and documentation storage.
- The schedule given to the project (a total of 1 year, 6 months) is generous when looking at the critical path analysis.
- Due to the time excess, the project is expected to be done at a high level of quality and in such a way to allow for potential further expansion after the final deliverable.
- The entire project will not be done from scratch, the development team will determine what stack they will use, and integrate various libraries into the code base as needed.
- The project has an initial budget of $120,000 in the first 6 months, after that it will be raised to a total of $500,000.
- There are five developers working on this project, one of them also has the role of project manager.

## 1.3 Project Deliverables

The project deliverables are:

1. Frontend Application
   - To be delivered in 6 months.
   - Deliver by submiting application installers (.exe, .apk, etc.) to project repository and project manager for a stakeholder demonstration.
   - Ensure the application can be installed on devices.
   - Ensure that frontend application can meet performance metrics defined in software requirements specification document.
   - Ensure the application functions as expected without the routing server (no call functionality, but app navigation works).
2. Routing Server
   - To be delivered in 8 months (2 months after previous deliverable).
   - Deliver by launching an instance of the routing server and informing the project manager for use in a stakeholder demonstration.
   - Ensure that routing server can meet performance metrics defined in software requirements specification document.
   - Ensure that the routing server integrates with the frontend application (call functionality available in frontend app).
3. System Console
   - To be delivered in 1 year, 2 months (6 months after previous deliverable).
   - Deliver by providing updated application with system console to project manager for a stakeholder demonstration.
   - Ensure the system console integrates with the previous two deliverables.
   - Ensure the system console accurately tracks data for use with the next deliverable.
4. Billing System
   - To be delivered in 1 year, 6 months (4 months after previous deliverable).
   - Deliver by submiting updated software to project manager for use with a stakeholder demonstration.
   - Additionally, submit software and documentation on running/configuring backend software to project manager to be passed to company IT team to start application distribution and starting additional backend servers in preparation for official release.
   - Ensure billing system integrates with the previous three deliverables.

## 1.4 Schedule and Budget Summary

The first 6 months will have a budget of $120,000, after that the budget will be raised to a total of $500,000.

The project is expected to be completed after 1 year and 6 months.

According to the critical path analysis in the project schedule, the completion dates for each deliverable are as follows:

| **Name**             | **Task ID** | **From** | **To** |
| -------------------- | ----------- | -------- | ------ |
| Frontend Application | 4           | Day 0    | Day 25 |
| Routing Server       | 3           | Day 0    | Day 19 |
| System Console       | 1           | Day 9    | Day 25 |
| Billing System       | 2           | Day 9    | Day 25 |

As mentioned previously, the total allocated time of 1 year, 6 months gives a lot of extra time by our estimates.

## 1.5 References

| **Name**                                 | **Path**                                       | **Date**   | **Version** |
| ---------------------------------------- | ---------------------------------------------- | ---------- | ----------- |
| Project Charter                          | ../a1/Project_Charter.md                       | 09/28/2023 | 1.7         |
| Software Requirements Specification Plan | ../a2/"Software Requirements Specification.md" | 10/13/2023 | 1.5         |
| Project Schedule                         | ../a3/"Project Scheduling.md"                  | 10/24/2023 | 1.6         |

## 1.6 Definitions and Acronyms

Software Requirements Specification (SRS):

- A document that provides a thorough description of the features and functionalities of a software project's requirements and specifications.

User Interface (UI):

- Users engage with the visual and interactive components of a software application to carry out activities. <br>
  Example: Facebook web page.

Application Programming Interface (API):

- A set of guidelines and procedures that permit communication between various software programs. <br> Example: Twitter API, allows fetching data in JSON format.

Design requirements (D-requirements):

- Clear specifications that direct a software project's conception, execution, and testing.

Operating System (OS):

- Software that controls computer hardware and offers assistance to computer programs. <br> Example: Windows 11.

Work Breakdown Structure (WBS):

- A hierarchical diagram consisting of higher-level requirements being broken down recursively into the smallest possible tasks.

# 2. Project Organization

## 2.1 Organizational Structure

## 2.1.1 Internal structure of the organization for ProCaller project:
-  Director / CEO
   -  Project Manager / Assitant Project Manager
      - Team Lead
         - Developer Manager
            - Developer
         - QA Manager
            - QA
      - IT Department
         - IT Manager
            - IT Representatives
      - Sales Department
         - Sales Manager
            - Sales Representatives
      

## 2.1.2 External structure of the organization for ProCaller project.

- Clients
   - Client support team
- Manufactureres
- Marketing and Public Relations (PR)
   - Marketing Manager
   - PR Specialist
- Users
   - User support Team


## 2.2 Roles and Responsibilities

| Work Activities/Processes  | Nature | Project Director/CEO | Project Manager | Team Lead | Developer Manager | IT Manager | Sales Manager |
|-----------------------------------|----------------------|----------------------| -----------------|-----------|---------------------|------------|---------------|
| Project Management    | Defining ProCaller's goals, scope, timeline, and resource allocation. Executing tasks to meet project milestones. | ✓                    | ✓               | ✓         |                     |            |               |
| Key Client Relationship Management  | Building and maintaining strong relationships with key clients. Understanding client needs and ensuring satisfaction. | ✓                    | ✓               | ✓         |                     |            | ✓             |
| Strategic Partnership Development |  Identifying and fostering collaborations with external partners to enhance project capabilities or reach new markets.  | ✓                    | ✓               |           | ✓                   | ✓          | ✓             |
| Marketing Strategy Development   | Creating plans to promote the ProCaller, including advertising, branding, and market positioning.    | ✓                    | ✓               |           |                     | ✓          |               |
| Public Relations Management   | Managing external communication, building a positive product image, and handling media relations.       | ✓                    | ✓               |           |                     | ✓          |               |
| User Community Engagement    | Actively involving and communicating with the user community. Gathering feedback and addressing user concerns.       |                     | ✓               | ✓         |                     |            |               |
| Client Support          | Providing assistance and resolving issues for clients who are using the ProCaller project.             |                      | ✓               |           |                     |            |               |
| IT Infrastructure Management | Overseeing the technical infrastructure, including servers, networks, and databases, to support the ProCaller project.        |                      |                   |           | ✓                   | ✓          |               |
| Sales Strategy Execution | Implementing sales plans to attract new clients and meet revenue targets for the ProCaller project.             |                      |                   |           |                     |            | ✓             |



# 3. Managerial Process Plans

This section of the _ProCaller_ Project Management Plan specifies the project management processes for the project. This section defines the plans for project start-up, risk management, project work, project tracking and project close-out.

## 3.1 Start-up Plan

### 3.1.1 Estimates

The estimated cost for the _ProCaller_ project is set at $500,000. Estimation methods involve a combination of historical databases, analogy-based estimations, and data from industry-standard cost models. Confidence levels associated with these estimates are all high due to the past project experiences and available data.

Plans for re-estimation are scheduled at specific project milestones, conducted through regular assessments, and aligned with major deliverable completions.

Table belows contains the total breakdown of associated costs.

| Category                       | Estimated Cost ($) | Confidence Level | Basis of Estimation                                             |
| ------------------------------ | ------------------ | ---------------- | --------------------------------------------------------------- |
| Interface Design               | 40,000             | High             | Historical data based on similar past design projects           |
| Backend Developement           | 220,000            | High             | Analogous estimation to comparable backend development projects |
| Techonology and Infrastructure | 100,000            | High             | Industry-standard cost models and data from similar projects    |
| Testing                        | 65,000             | High             | Data from previous testing phases, accounting for complexity    |
| Project Management             | 50,000             | High             | Based on allocated resources, previous project management costs |
| Documentation                  | 25,000             | High             | Estimation derived from similar documentation processes         |

### 3.1.2 Staffing

The project will consist of 5 developers with variation in skill levels for the entire duration.

| Skill Level  | Project Manager | FullStack Developers | QA  |
| ------------ | --------------- | -------------------- | --- |
| Entry-level  | 0               | 0                    |     |
| Mid-level    | 1               | 2                    | 1   |
| Senior-Level | 0               | 1                    |     |

Table belows contains the number of personnel by each phase:

| Project Phase | Project Manager | FullStack Developer | QA  |
| ------------- | --------------- | ------------------- | --- |
| Planning      | 1               |                     |     |
| Development   |                 | 3                   |     |
| Testing       |                 | 2                   | 1   |
| Deployment    |                 |                     |     |

Table belows shows the duration of personnel requirement and the sources they are drawn from.

|              | Project Manager   | FullStack Developer             | QA        |
| ------------ | ----------------- | ------------------------------- | --------- |
| **Duration** | 18 months         | 18 months                       | 8 months   |
| **Source**   | Internal Transfer | Internal transfer and new hires | Contracts |

### 3.1.3 Resource Acquisition

- **Personnel**: Recruitment through internal transfers, new hires, and contracted individuals.

- **Equipment, Hardware, and Software**: Vendor selection for required hardware components and software licenses and scheduled procurement aligned with project phases.

- **Service Contracts**: Identifying and finalizing service contracts for maintenance and support. Ongoing review of service provider performance.

Acquisition tasks are integrated within key project milestones, ensuring a consistent alignment with the various project phases. Regular reviews will be conducted to assess the effectiveness of acquisition strategies and make necessary adjustments in response to changes in project dynamics.

## 3.2 Work Plan

### 3.2.1 Work Breakdown Structure

A comprehensive Work Breakdown Structure (WBS) for the ProCaller project, including work activities, relationships, risk factors, resource requirements, schedule durations, necessary resources, estimated durations, deliverables, acceptance criteria, and dependencies, can be found in this [Project Scheduling Document](https://github.com/Developik/comp4050/blob/main/a3/Project%20Scheduling.md).


### 3.2.2 Schedule Allocation

A detailed scheduling relationships between project activities, critical path in the schedule, constraints on the scheduling, milestone charts, activity lists, activity Gantt charts, activity networks, critical path networks and PERT charts, can be found in this [Project Scheduling Document](https://github.com/Developik/comp4050/blob/main/a3/Project%20Scheduling.md).

### 3.2.3 Resource Allocation

A detailed itemization of the resources allocated to each major work activity in the project WBS, can be found in this [Project Scheduling Document](https://github.com/Developik/comp4050/blob/main/a3/Project%20Scheduling.md).


### 3.2.4 Budget Allocation

A breakdown of the necessary resource budgets for each of the major work activities in the WBS.

| Work Activities | Travel | Meetings | Computing Resources | Software Tools | Special Testing and Simulation Facilities | Administrative Support |
|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|
| System Console | $ 10,000 | $ 5,000 | $ 10,000 | $ 5,000 | $ 10,000 | $ 5,000|
| Billing System | $ 10,000 | $ 5,000 | $ 10,000 | $ 5,000 | $ 10,000 | $ 5,000 |
| Backend Functionality | $ 10,000 | $ 5,000 | $ 20,000 | $ 10,000 | $ 25,000 | $ 15,000 |
| App | $ 15,000 | $ 7,500 | $ 25,000 | $ 7,500 | $ 50,000 | $ 20,000 |


## 3.3 Project Tracking Plan

### 3.3.1 Requirements Control

- **Change Control**: Any proposed change to project requirements will be documented, identified, and logged through a formal change request process. It will be evaluated based on impact and alignment with project and then approved for changes to be implemented.

- **Impact Assessment**: Evaluate requirement changes for their effect on the project's functionality, usability, quality standards. Analyze for their impact on overall project timelines. Assess financial implications accounting for potential cost increases or decreases due to changes in requirements. Identify staffing needs, and skill sets due to changes in requirements and assess how requirement changes impact identified risks as well as any new risk factors.

### 3.3.2 Schedule Control

- **Measure progress**: Gannt chart produced during the project scheduling will be used to compare the planned vs actual progress at each milestone.

- **Milestone Checklists**: Detailed checklists for major milestones will be implemented to confirm all tasks are completed.

- **Critical Path Analysis**: The CPA from the project scheduling will be used to identify critical tasks and their effect on the project's overall timeline.

- **Tasks Reprioritization**: Tasks sequence will be rearranged to align with project objectives and timelines.

- **Quality Checkpoints**: Quality standards will be established for every milestone to ensure code quality meets expectations.

### 3.3.3 Communication Plan

Following the agile methodology, the below communcation plan will be implemented.

- Regular sprint meetings will be held in-person every 2 weeks that will feature progress updates, issue resolution, and collaborative brainstorming sessions. These will be held at the beginning of the week on Mondays.

- Weekly Status Report: At the end of the week, team members will submit their individual status report with a summary of completed work, issues ongoing and share struggles faced during tasks. These can be in-person or via microsoft teams.

- Each month, a stakeholder meeting will be held to discuss progress reports, project scope modifications, and take stakeholder feedback.

### 3.3.4 Project Closeout Plan

The plan below will be implemented to ensure the orderly closeout of the _ProCaller_ project.

- **Code Review**: Conduct a final code review of the entire codebase to ensure all features are completed and the code meets quality standards

- **Staff reassignment plan**: At the end of the project, a structured personal reorganization plan will be implemented. This includes redeploying team members to other ongoing projects within the organization or moving them into new roles as needed as well ensuring the contracts of contracted hires are completed.

- **Archiving project materials**: The following materials will be methodically archived: test results, meeting minutes, technical requirements, design documents, source code, and any other pertinent artefacts linked to the project. To guarantee accessibility for future reference, the organisation and storage of these materials will adhere to the company's archiving guidelines.

- **Capturing project metrics**: Key project metrics such as performance indicators, achieved milestones, resource utilization and adherence to schedules and budgets are consolidated into a comprehensive report and cataloged in a project database to provide a basis for future analysis and decision making.

- **Post-mortem debriefings of project personnel**: Post-poroject review sessions will review project successes, challenges, lessons learned, and best practices identified during implementation which will be documented for future reference.

- **Milestone Complete Confirmation**: Make sure to receive formal recognition and agreement from key stakeholders that the project is done.

- **Final report**: The project's goals, successes, difficulties encountered, solutions found, and suggestions for further work will all be included in a final thorough report. An extensive summary of the ProCaller project will be provided by this report, which will be distributed to all relevant parties, including upper management.

# 4. Technical Process Plans

This SPMP will specify the technical processes for the project. This section defines the plans for the software development process, methods, tools and techniques, infrastructure, and product acceptance.

## 4.1 Process Model

The software development process to be used will be Agile. The team will generate user stories and use them to create a product backlog. The team will then create a sprint backlog and use it to create a sprint/phase. The team will then develop the product increment and present it to the customer for feedback. The team will then repeat the process until the project is completed.

| **Phase**                | **Start and Finish date** | **Phase Goals**                                                                                                                                                                                                                          |
| ------------------------ | ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Project Startup/Learning | 09/28/2023 - 11/28/2023   | - Learn about the project and the technologies that will be used. <br> - Create the Project Charter and the Software Requirements Specification. <br> - Create the Project Schedule. <br> - Create the Software Project Management Plan. |
| Requirements             | 11/28/2023 - 12/23/2023   | - Become familiarized with the requirements <br> - Create a review documents (SRS, SPMP)                                                                                                                                                 |
| Phase 1                  | 12/23/2023 - 03/31/2024   | - Frontend Application Development                                                                                                                                                                                                       |
| Phase 2                  | 04/01/2024 - 05/31/2024   | - Routing Server Development                                                                                                                                                                                                             |
| Phase 3                  | 06/01/2024 - 11/31/2024   | - System Console Development                                                                                                                                                                                                             |
| Phase 4                  | 12/01/2024-03/31/2024     | - Billing System Development                                                                                                                                                                                                             |

## 4.2 Methods, Tools, and Techniques

The ProCaller team will consider using Object-Oriented Programming (OOP) as the development methodology for the project. The team will also consider software design patterns of: prototype, facade, and mediator patterns. There is no set development language for the project, but the team will consider using C++ or Java. The team will also consider using non-relational (no-SQL) and relational (SQL) databases, from: MySQL, PostgresQL. The team will use the following tools and techniques to develop the project: Visual Studio Code, Git, and Github. The team will use the following technical standards, policies, and procedures: the IEEE 830-1998 standard for Software Requirements Specification, the IEEE 1016-1998 standard for Software Design Descriptions, and the IEEE 1028-1998 standard for Software Reviews and Audits.

Additional tools to be used will be: Google Docs, Google Sheets, Google Slides, and Google Drive.

## 4.3 Infrastructure

The team will have access to the following resources: a computer lab with Linux-based machines, a server, and a network. The team will also have access to the following software: Visual Studio Code, Git, and Github. The team will also have access to the following hardware: Linux-based laptop computers, monitors, mice, and keyboards. The team will also have access to Google's G Suite, MatLab, and Discord.

The team will have a physical working space apart from the computer lab. They will be provided with individual desks with no partitions. The team will also have access to a whiteboard, a projector, a printer and a scanner.

There will be two administrative staff members assigned to the team. A technical support member working remotely with the ability to enter the offices when required. The building will be secured by a security team and the team will have access to the building 24/7. The building also has a janitorial service that will clean the office and computer lab every day after 6:00 PM.

## 4.4 Product Acceptance

The plan for customer acceptance of the deliverables involves defining acceptance criteria, conducting testing, demonstrating the deliverables, analyzing them for compliance with requirements, inspecting for defects, and allowing the customer to evaluate and accept based on the criteria. The specific processes, methods, and tools used will be documented in the acceptance criteria agreement between the ProCaller organization and the customer. Objective criteria for determining acceptability will also be specified.

The acceptance criteria will be defined in a formal agreement between the ProCaller organization and the customer. This agreement will outline the specific requirements and standards that the deliverables must meet in order to be accepted. Both parties will review and sign the agreement to ensure mutual understanding and an agreement to the acceptance criteria.

The deliverable acceptance process will involve the following technical processes, methods, and tools:

- Testing: The ProCaller team will conduct unit testing, integration testing, and system testing to ensure the functionality and quality of the deliverables. Testing tools such as JUnit, Mockito, and Selenium may be used.
- Demonstration: The ProCaller team will demonstrate the Front-end functionality, Routing Server, System Console, and Billing System to the customer for their evaluation and acceptance.
- Analysis: The deliverables will be analyzed to ensure they meet the specified requirements and standards outlined in the acceptance criteria. This may involve reviewing the code, documentation, and performance metrics.
- Inspection: The deliverables will undergo inspection to identify any defects, errors, or deviations from the requirements. This may involve code reviews, documentation reviews, and quality assurance checks.

# 5. Supporting Process Plans

## 5.1 Documentations

### List of Documents
1. Project Charter
2. Software Requirements Specification
3. Software Project Management Plan
4. Project Scheduling Plan (WBS, Pert, Gantt, etc.)
5. Risk Management Plan
6. Frontend Application Documentation
7. Routing Server Documentation
8. System Console Documentation
9. Billing System Documentation
10. Acceptance Criteria Agreement

### Controlling Template or Standard
- IEEE 830-1998 (Software Requirements Specification)
- IEEE 1016-1998 (Software Design Descriptions)
- IEEE 1028-1998 (Software Reviews and Audits)
- IEEE 1058-1998 (Software Project Management Plan)

### Document Preparation Responsibility
- Project Charter: Entire Team
- Software Requirements Specification: Requirements Team (Business Analysts)
- Software Project Management Plan: Project Manager
- Project Scheduling Plan: Project Manager
- Risk Management Plan: Project Manager
- Frontend Application Documentation: Development Team
- Routing Server Documentation: Development Team
- System Console Documentation: Development Team
- Billing System Documentation: Development Team
- Acceptance Criteria Agreement: Project Manager and Stakeholders

### Document Review Responsibility
- Project Charter: Project Manager and Stakeholders
- Software Requirements Specification: Development Team, QA Team, and Stakeholders
- Software Project Management Plan: Development Team and Project Manager
- Project Scheduling Plan: Development Team and Project Manager
- Risk Management Plan: Development Team and Project Manager
- Frontend Application Documentation: Development Team and QA Team
- Routing Server Documentation: Development Team and QA Team
- System Console Documentation: Development Team and QA Team
- Billing System Documentation: Development Team and QA Team
- Acceptance Criteria Agreement: Project Manager and Stakeholders

### Due Dates
- Project Charter: 09/28/2023
- Software Requirements Specification: 10/13/2023
- Software Project Management Plan: 10/24/2023
- Project Scheduling Plan: 11/21/2023
- Risk Management Plan: 11/21/2023
- Frontend Application Documentation: 03/31/2024
- Routing Server Documentation: 05/31/2024
- System Console Documentation: 11/31/2024
- Billing System Documentation: 03/31/2025
- Acceptance Criteria Agreement: Before Deliverable Demo

### Distribution List
- Project Charter: Entire Team, Stakeholders
- Software Requirements Specification: Entire Team, QA Team, Stakeholders
- Software Project Management Plan: Entire Team, Stakeholders
- Project Scheduling Plan: Entire Team, Stakeholders
- Risk Management Plan: Entire Team, Stakeholders
- Frontend Application Documentation: Entire Team, QA Team
- Routing Server Documentation: Entire Team, QA Team
- System Console Documentation: Entire Team, QA Team
- Billing System Documentation: Entire Team, QA Team
- Acceptance Criteria Agreement: Project Manager, Customer, QA Team

## 5.2 Quality Assurance

### Overview

The steps to guarantee that the ProCaller project fulfils its responsibilities as stated in the requirements specification, ProCaller Project Management Plan, and any applicable standards are described in this Quality Assurance (QA) plan. Procedures for quality assurance like analysis, inspection, review, audit, and assessment are included in the plan.

### Assurance Procedures

1. Analysis procedure: 
   - Spot problems at the outset of development.
      -  The QA team is in charge of conducting frequent analysis sessions.<br>
Activities: Process evaluation, requirements and risk analysis.

2. Inspection procedure: 
   - Verify that work products follow specifications.
      -  The QA team is in charge of overseeing inspection operations.<br>
Activities: Defect fixing, code and document inspections.

3. Review procedure: 
   - Assess accuracy and comprehensiveness.
      -  The QA team is in charge of planning frequent review sessions.<br>
Activities: Customer feedback, management reviews, and peer reviews.

4. Audit procedure: 
   - Conduct an impartial analysis of actions to ensure compliance.
      -  The QA team is in charge of doing recurring audits. <br>
Activities: Audits of the documentation, products, and processes.

5. Assessment procedure: 
   - Assess the efficiency of the QA procedure. 
      -  The QA team is in charge of the assessment processes. <br>
Activities: Process evaluations, ongoing feedback, and metric analysis.

### Connection to Other Procedures

- Validation and verification: 
   -  Close cooperation is required to guarantee accuracy and compliance.

- Configuration management: 
   -  Working together to ensure control and versioning.

- System engineering: 
   -  Integrating to guarantee regular compliance with specifications.


# 6. Additional Plans

Additional plans required to satisfy product requirements and contractual terms:

1) Safety, Privacy, and Security Assurance Plan.
2) Product Installation Plan.
3) User Training Plan.
4) Product Maintenance Plan.
5) Product Support Plan.

 It's important to note that these plans are not exhaustive, and additional plans may be developed as needed to address the unique aspects of the project.

*Note: Each plan's specific details will be customized to suit the project's unique needs and characteristics.*