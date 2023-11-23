<div style="text-align: center;">

# **_ProCaller_**

**Software Project Management Plan**

### Version 0.2

### 11/21/2023

# Wind Falcons

</div>

## Revision History

| **Date** | **Description** | **Author** | **Comments** |
| --- | --- | --- | --- |
| _11/21/2023_ | _Version 0.1_ | _Ryan Dotzlaw_ | _Initial Document Commit_ |
| _11/22/2023_ | _Version 0.2_ | _Ryan Dotzlaw_ | _Completed Section 1_ |

**Table of Contents**

- [1. Project Overview](#1-project-overview)
   * [1.1 Purpose, Scope, and Objectives](#11-purpose-scope-and-objectives)
   * [1.2 Assumptions, Constraints, and Risks](#12-assumptions-constraints-and-risks)
   * [1.3 Project Deliverables](#13-project-deliverables)
   * [1.4 Schedule and Budget Summary](#14-schedule-and-budget-summary)
   * [1.5 References](#15-references)
   * [1.6 Definitions and Acronyms](#16-definitions-and-acronyms)
- [2. Project Organization](#2-project-organization)
   * [2.1 Organizational Structure](#21-organizational-structure)
   * [2.2 Roles and Responsibilities](#22-roles-and-responsibilities)
- [3. Managerial Process Plans](#3-managerial-process-plans)
   * [3.1 Start-up Plan](#31-start-up-plan)
      + [3.1.1 Estimates](#311-estimates)
      + [3.1.2 Staffing](#312-staffing)
      + [3.1.3 Resource Acquisition](#313-resource-acquisition)
   * [3.2 Work Plan](#32-work-plan)
      + [3.2.1 Work Breakdown Structure](#321-work-breakdown-structure)
      + [3.2.2 Schedule Allocation](#322-schedule-allocation)
      + [3.2.3 Resource Allocation](#323-resource-allocation)
      + [3.2.4 Budget Allocation](#324-budget-allocation)
   * [3.3 Project Tracking Plan](#33-project-tracking-plan)
      + [3.3.1 Requirements Control](#331-requirements-control)
      + [3.3.2 Schedule Control](#332-schedule-control)
      + [3.3.3 Communication Plan](#333-communication-plan)
      + [3.3.4 Project Closeout Plan](#334-project-closeout-plan)
- [4. Technical Process Plans](#4-technical-process-plans)
   * [4.1 Process Model](#41-process-model)
   * [4.2 Methods, Tools, and Techniques](#42-methods-tools-and-techniques)
   * [4.3 Infrastructure](#43-infrastructure)
   * [4.4 Product Acceptance](#44-product-acceptance)
- [5. Supporting Process Plans](#5-supporting-process-plans)
   * [5.1 Documentations](#51-documentations)
   * [5.2 Quality Assurance](#52-quality-assurance)
- [6. Additional Plans](#6-additional-plans)




# 1. Project Overview

## 1.1 Purpose, Scope, and Objectives

The purpose of the _ProCaller_ project is to create an online phone system to place virtual calls between users anytime. 
This online phone system will be accessed by the users through an application designed to work on desktop, laptop and mobile devices.

_ProCaller_ will remove the need for users to have additional devices, such as cellphones or landline phones, to communicate with other users.
For example, this would allow companies to not have to spend money supplying their employees with these devices. 
Instead it would allow employees to use any internet connected device, such as an already provided work computer or a personal device.

Elements that are within the projects scope are as follows:
-	Audio-Only Calls between users
-	Ability to create outgoing calls and receive incoming calls on the app
-	Allowing users to log into their accounts on the app
-	Seamless routing of incoming calls to all of a user’s logged in apps, regardless of the platform
-	Tracking Call Logs
-	Functional application for mobile devices and computers
-	Monitoring and Moderation software for the system
-	Calculating user’s bills
-	Informing users of their bills

Elements that are out of the project scope include the following:
-	Video Calls between users
-	Text chat between users
-	Web-based application
-	Recording calls
-	Integration with other systems (pre-recorded messages, call menus)
-	Voicemail

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

| **Name** | **Task ID** | **From** | **To** |
| -------- | ----------- | -------- | ------ |
| Frontend Application | 4 | Day 0 | Day 25 |
| Routing Server | 3 | Day 0 | Day 19 |
| System Console | 1 | Day 9 | Day 25 |
| Billing System | 2 | Day 9 | Day 25 |


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

Specify the internal and external structure of the organization for your project. 

## 2.2 Roles and Responsibilities

Identify and state the nature of each major work activity and supporting process.

Identify the organizational units that are responsible for those processes and activities.

Consider using a matrix of work activities and supporting processes vs. organizational units to depict project roles and responsibilities.

# 3. Managerial Process Plans

This section of the ICT Project Management Plan specifies the project management processes for the project. This section defines the plans for project start-up, risk management, project work, project tracking and project close-out. 

## 3.1 Start-up Plan

### 3.1.1 Estimates

Specify the estimated cost, schedule and resource requirements for conducting the project, and specify the associated confidence levels for each estimate.

Specify the methods, tools and techniques used to estimate project cost, schedule and resource requirements;

Specify the sources of estimate data and the basis of the estimation such as: analogy, rule of thumb, standard unit of size, cost model, historical database, etc.

Specify the methods, tools, techniques to be used to re-estimate the project cost, schedule and required resources.

Specify the schedule for re-estimation, which might be regular, a periodic or event-driven (e.g.: on project milestones).

### 3.1.2 Staffing

Specify the number of required staff, providing the following details:

- number of personnel by skill level,

- numbers and skill levels in each project phase, and

- duration of personnel requirement.

Specify the sources of staff personnel (e.g.: internal transfer, new hire, contracted, etc.)

Consider using resource Gantt charts, resource histograms, spreadsheets and tables to depict the staffing plan by skill level, by project phase, and by aggregations of skill levels and project phases. 

### 3.1.3 Resource Acquisition

Specify the plan for acquiring the resources and assets, in addition to personnel, needed to successfully complete the project.

Describe the resource acquisition process.

Specify the assignment of responsibility for all aspects of resource acquisition.

Specify acquisition plans for equipment, computer hardware and software, training, service contracts, transportation, facilities, and administrative and janitorial services.

Specify when in the project schedule the various acquisition activities will be required.

Specify any constraints on acquiring the necessary resources.

If necessary, expand this subsection to lower levels, to accommodate acquisition plans for various types of resources.

## 3.2 Work Plan

### 3.2.1 Work Breakdown Structure

Define a Work Breakdown Structure (WBS) to specify the various work activities to be performed in the ICT project, and to depict the relationships among these work activities.

Decompose the work activities to a level that exposes all project risk factors, and that allows accurate estimation of resource requirements and schedule duration for each work activity.

Specify the following factors for each work activity:

- necessary resources,

- estimated duration,

- products or deliverables of the activity,

- acceptance criteria for the work activity products, and

- predecessor and successor work activities.

The level of decomposition internally within the WBS may vary depending on the quality of the requirements, familiarity of the work, applicable level of technology, etc. 

### 3.2.2 Schedule Allocation

Specify the scheduling relationships among the project work activities in a manner that depicts the time-sequencing constraints and illustrates opportunities for concurrent work activities.

Identify the critical path in the schedule.

Indicate any constraints on the scheduling of particular work activities, that are caused by external factors.

Identify appropriate schedule milestones to assess the scope and quality of project work products and of project achievement status.

Techniques for depicting schedule relationships may include milestone charts, activity lists, activity Gantt charts, activity networks, critical path networks and PERT charts. 

### 3.2.3 Resource Allocation

Provide a detailed itemization of the resources allocated to each major work activity in the project WBS.

Specify the numbers and required skill levels of personnel for each work activity.

Specify, as appropriate, the allocation of the following resources if applicable:

- personnel (by skill level),

- computing resources

- software tools

- special testing and simulation facilities, and

- administrative support.

Use a separate line item for each type of resource for each work activity.

### 3.2.4 Budget Allocation

Provide a detailed breakdown of the necessary resource budgets for each of the major work activities in the WBS.

Specify the estimated cost for activity personnel, and include as appropriate, the costs for the following items if appliable:

- travel,

- meetings,

- computing resources,

- software tools,

- special testing and simulation facilities, and

- administrative support.

Use a separate line item for each type of resource in each activity budget.

## 3.3 Project Tracking Plan

### 3.3.1 Requirements Control

Specify the process for measuring, reporting and controlling changes to the project requirements.

Specify the processes to be used in assessing the impact of requirements changes on product scope and quality, and the impacts of requirements changes on project schedule, budget, resources and risk factors.

In the processes for requirements management, include traceability, prototyping and modeling, impact analysis and reviews. 

### 3.3.2 Schedule Control

Specify the schedule control activities by identifying the processes to be used for the following purposes:

- to measure the progress of work completed at the major and minor project milestones,

- to compare actual progress to planned progress, and

- to implement corrective action when actual progress does not conform to planned progress.

Specify the methods and tools that will be used to measure and control schedule progress.

Identify the objective criteria that will be used to measure the scope and quality of work completed at each milestone, and hence to assess the achievement of each schedule milestone. 

### 3.3.3 Communication Plan

Specify the methods, tools and techniques of communication.

Specify a frequency and detail of communications related to project management. 

### 3.3.4 Project Closeout Plan

dentify the plans necessary to ensure orderly closeout of the ICT project.

Specify the following if appliable:

- a staff reassignment plan

- a process for archiving project materials,

- a process for capturing project metrics in the business projects database,

- a process for post-mortem debriefings of project personnel, and

- a plan for preparation of a final report to include lessons learned and an analysis of project objectives achieved. 

# 4. Technical Process Plans

## 4.1 Process Model

Specify the software development process to be used.

Specify the timing and goal of each phase of the process. 

## 4.2 Methods, Tools, and Techniques

Specify the development methodologies, programming languages and other notations, and the processes, tools and techniques to be used to specify, design, build, test, integrate, document, deliver, modify and maintain the project deliverable and non-deliverable work products.

Specify the technical standards, policies, and procedures governing development and/or modification of the work products. 

## 4.3 Infrastructure

Specify the plan for establishing and maintaining the development environment (hardware, operating system, network and software), and the policies, procedures, standards, and facilities required to conduct the ICT project. These resources may include workstations, local area networks, software tools for analysis, design implementations, testing, and project management, desks, office space, and provisions for physical security, administrative personnel, and janitorial services.

## 4.4 Product Acceptance

Specify the plan for customer acceptance of the deliverables generated by the ICT project.

Specify objective criteria for determining acceptability of the deliverables.

Reference a formal agreement of the acceptance criteria signed by representatives of the ICT organization and the customer.

Specify any technical processes, methods, or tools required for deliverable acceptance, such as testing, demonstration, analysis and inspection. 

# 5. Supporting Process Plans

## 5.1 Documentations

Specify the plans for generating non-deliverable and deliverable project documentation.

Specify the following information or object identification:

- list of documents to be prepared,

- controlling template or standard for each document,

- who will prepare each document,

- who will review each document,

- due dates for review copies,

- due dates for initial baseline versions, and

- a distribution list for review copies and baseline versions and quantities required 

## 5.2 Quality Assurance

Specify or reference the quality assurance plan for the ICT project, containing the information identified in the following lines.

Specify the plans for assuring that the ICT project fulfills its commitments to the ICT process and the ICT product as specified in the requirements specification, the ICT Project Management Plan, supporting plans and any standards, procedures, or guidelines to which the process or the product must adhere.

As applicable, specify the quality assurance procedures to be used, such as analysis, inspection, review, audit, and assessment.

Indicate the relationship among the quality assurance, verification and validation, review, audit, configuration management, system engineering, and assessment processes. 

# 6. Additional Plans

Specify or reference any additional plans required to satisfy product requirements and contractual terms, which may include:

- plans for assuring that safety, privacy, and security requirements are met,

- special facilities or equipment specification,

- product installation plans,

- user training plans,

- integration plans,

- data conversion plans,

- system transition plans,

- product maintenance plans, or

- product support plans. 

