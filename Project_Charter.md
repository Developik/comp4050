**# _\<PROJECT NAME\>_**

**# PROJECT CHARTER**

# Version 1.1

# 26/09/2023

# Wind Falcons

**VERSION HISTORY**

_[Provide information on how the development and distribution of the Project Charter up to the final point of approval was controlled and tracked. Use the table below to provide the version number, the author implementing the version, the date of the version, the name of the person approving the version, the date that particular version was approved, and a brief description of the reason for creating the revised version.]_

| **Version #** | **Implemented**** By **|** Revision ****Date** | **Approved**** By **|** Approval ****Date** | **Reason** |
| --- | --- | --- | --- | --- | --- |
| 1.0 | _Andrii Provozin_ | _09/26/2023_ | _Ryan Dotzlaw_ | _09/26/2023_ | _Completed Part 5_ |
| 1.1 | Ryan Dotzlaw | 09/26/2023 | Andrii Provozin | 09/26/2023| Completed Part 3|
 |
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
 |

| **Name** | **Email** | **Period of being project manager** |
| --- | --- | --- |
| Andrii Provozin | provozia@myumanitoba.ca | 09/21/2023 – N/A |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**TABLE OF CONTENTS**

[**1**](#_3whwml4) **INTRODUCTION**  **4**

[1.1](#_2bn6wsx)Purpose of Project Charter 4

[**2**](#_qsh70q) **PROJECT AND PRODUCT OVERVIEW**  **4**

[**3**](#_tyjcwt) **JUSTIFICATION**  **4**

[3.1](#_3as4poj)Business Need 4

[3.2](#_1pxezwc)Objectives 4

[3.3](#_49x2ik5)High-Level Requirements 4

[3.4](#_2p2csry)Major Deliverables 5

[3.5](#_147n2zr)Boundaries 5

[**4**](#_17dp8vu) **DURATION**  **5**

[4.1](#_3rdcrjn)Timeline 5

[4.2](#_26in1rg)Executive Milestones 5

[**5**](#_3o7alnk) **ASSUMPTIONS, CONSTRAINTS AND RISKS**  **5**

[5.1](#_23ckvvd)Assumptions 5

[5.2](#_ihv636)Constraints 6

[5.3](#_1ksv4uv)Risks 6

[**6**](#_32hioqz) **PROJECT ORGANIZATION**  **6**

[6.1](#_1hmsyys)Stakeholders (Internal and External) 6

[6.2](#_z337ya)Roles and Responsibilities 6

[**7**](#_3j2qqm3) **PROJECT CHARTER APPROVAL**  **8**

[**APPENDIX A: REFERENCES**](#_41mghml)[**9**](#_41mghml)

1.
# INTRODUCTION

  1.
## PURPOSE OF PROJECT CHARTER

_[Provide the purpose of the project charter.]_

The _\<Project Name\>_ project charter documents and tracks the necessary information required by decision maker(s) to approve the project for funding. The project charter should include the needs, scope, justification, and resource commitment as well as the project's sponsor(s) decision to proceed or not to proceed with the project. It is created during the Initiating Phase of the project.

The intended audience of the _\<Project Name\>_ project charter is the project sponsor and senior leadership.

1.
# PROJECT AND PRODUCT OVERVIEW

_[Typically, the description should answer who, what, when and where, in a concise manner. It should also state the estimated project duration (e.g., 18 months) and the estimated project budget (e.g., $1.5M)._

1.
# JUSTIFICATION

  1.
## OBJECTIVES

[_identify the objectives using_ _**SMART (Specific, Measurable, Attainable, Relevant, Time-bound)**_]

The objectives of the _Online Virtual Phone System_ are as follows:

- _In 6 months, create an app that can be used on mobile devices and computers that allows users of the app to call other users, regardless of application platform, over the internet._
- _In 8 months, create a backend server that routes the numbers dialed by a user to an (IP, Port) pair, connecting one user to another using the server as an intermediary. Additionally, the backend server needs to store users, and log call metadata (length, time, etc.) for determining the billing cost._
- _In 1 year, 2 months, design a GUI called the System Console, that allows specific members of a client company to control and monitor their own Online Virtual Phone System network. Performing actions like finding available phone numbers, setting phone number – (IP, Port) mapping, controlling calls per user, etc._
- _In 1 year, 6 months, create a billing system that calculates the cost a client company owes based on the calls made by their users and their plan, among other factors. Additionally, the billing system needs to send a bill to the user at the end of the current billing period, and any Administrators should be able to view a client’s current bill using the System Console._

  1.
## HIGH-LEVEL REQUIREMENTS

The following table presents the requirements that the project's product, service or result must meet in order for the project objectives to be satisfied.

| **Req. #** | **Requirement Description** |
| --- | --- |
| 1 | 	Allow users to call each other over the internet with the App.|
| 2 |	Allow Administrators to monitor and moderate the network of users with the System Console.|
| 3 |	The billing software charges users based on their use and prevents them from using the system if they don’t pay for it. |


  1.
## MAJOR DELIVERABLES

The following table presents the major deliverables that the project's product, service or result must meet in order for the project objectives to be satisfied.

| **Major Deliverable** | **Deliverable Description** |
| --- | --- |
|Application| The application used by clients to perform calls. Both the mobile, and computer applications.|
|Backend Server|The backend server that routes calls, tracks logs and stores user data. By this point the Online Virtual Phone System should be capable of being used by two users to call each other.|
|System Console|The GUI that allows Administrators to moderate and monitor the Online Virtual Phone System.|
|Billing System|Integrates with the Backend Server and the System Console to calculate a user’s bill and make it available to see for Administrators. Additionally, it should contact users with their bill at the end of the current billing period and deny them system access if they fail to pay it.|


  1.
## SCOPE

Things that are in scope include the following:
*	Audio-Only Calls between users
*	Ability to create outgoing calls and receive incoming calls on the app
*	Allowing users to log into their accounts on the app
*	Seamless routing of incoming calls to all of a user’s logged in apps, regardless of the platform
*	Tracking Call Logs
*	Functional application for mobile devices and computers
*	Monitoring and Moderation software for the system
*	Calculating user’s bills
*	Informing users of their bills

Things that are out of scope include the following:
*	Video Calls between users
*	Text chat between users
*	Web-based application
*	Recording calls
*	Integration with other systems (pre-recorded messages, call menus)
*	Voicemail


# DURATION

## TIMELINE

 ![Shape1](4050-gp1-TIMELINE.png)

## EXECUTIVE MILESTONES

_[Example: For CPIC major/tactical projects, these milestones could be used to complete the Funding Plan/Cost and Schedule section of the OMB Exhibit 300.]_

The table below lists the high-level Executive Milestones of the project and their estimated completion timeframe.

| **Executive Milestones** | **Estimated Completion Timeframe** |
| --- | --- |
| Project Planned and authorized to proceed. | Two weeks after project concept is approved.  |
| Requirements Analysis Complete | Eight weeks after Project Initiation.|
|Completion of Application Development|Six weeks after Requirements Analysis Completion.|
|Completion of Back-end Server Development|Six weeks after Application Development Completion.|
|Prototype Release|Two weeks after Completion of Application and Server Back-End Development|
|Completion of System Console |Twelve weeks after Prototype Release.|
|Completion of Payment System|Twenty weeks after System Console Completion|
|System Testing Completed| Four weeks after Payment System Completion |
|System Development Completed|Twelve weeks after System Testing Completion|

# ASSUMPTIONS, CONSTRAINTS AND RISKS

## ASSUMPTIONS

_[Example: The system is being developed to capture data from public health partners. One assumption is that data is entered electronically into the system.]_

This section identifies the statements believed to be true and from which a conclusion was drawn to define this project charter.

1. _Users of the online virtual phone system are expected to have access to dependable internet and cloud services in order to place and receive calls._
2. _The billing software must correctly determine prices depending on call length, time of day, and calling plan. A crucial restriction is ensuring accuracy in billing calculations._
3.

  1.
## CONSTRAINTS

_[Example: There might be time constraints on developing a system that is used to track data of highly infectious diseases like SARS.]_

This section identifies any limitation that must be taken into consideration prior to the initiation of the project.

1. The system needs to make sure that no phone numbers can start with a particular prefix that is used for advanced features. The available phone numbers are constrained by this restriction, which should be taken into account while designing the dialing plan.
2. The billing software must correctly determine prices depending on call length, time of day, and calling plan. A crucial restriction is ensuring accuracy in billing calculations.

  1.
## RISKS

_[Example: The risk of accessibility or unavailability of public health partners for obtaining requirements to develop a data collection system may delay project deliverables. A possible mitigation strategy might be to schedule requirement sessions with the partners as early as possible. List the risks that the project sponsor should be aware of before making a decision on funding the project, including risks of not funding the project.]_

| **Risk** | **Mitigation** |
| --- | --- |
| The possibility of poor internet connectivity or cloud service disruptions could impair users' capacity to communicate by interfering with their ability to make and receive calls through the system. | Implement redundancies or backup communication systems to reduce the likelihood of service outages. |
| --- | --- |
| Errors in billing or conflicts with users run the danger of causing financial losses or client dispair. | Implement thorough testing and validation of the billing system to reduce errors and develop a transparent procedure for handling disputes. |
|
 |
 |
|
 |
 |
|
 |
 |

1.
# PROJECT ORGANIZATION

  1.
## STAKEHOLDERS (INTERNAL AND EXTERNAL)

_[Examples of stakeholders include an epidemiologist performing a behavioral research project and people in the field collecting data using a software application (the proposed project) to collect the data required for a behavioral research project.]_

  1.
## ROLES AND RESPONSIBILITIES

_[Depending on your project organization, you may modify the roles and responsibilities listed in the table below.] [You can put the project sponsor as TA] [Project manager could be the member take the role for this round.]_

This section describes the key roles supporting the project.

| **Name & Organization** | **Project Role** | **Project Responsibilities** |
| --- | --- | --- |
| \<Name\>\<Org\> | Project Sponsor | Person responsible for acting as the project's champion and providing direction and support to the team. In the context of this document, this person approves the request for funding, approves the project scope represented in this document, and sets the priority of the project relative to other projects in his/her area of responsibility. |
| --- | --- | --- |
| \<Name\>\<Org\> | Project Manager (This could include a Contractor Project Manager or an FTE Project Manager) | Person who performs the day-to-day management of the project and has specific accountability for managing the project within the approved constraints of scope, quality, time and cost, to deliver the specified requirements, deliverables and customer satisfaction. |
| \<Name Orog\> | Developer | Person who perform the day-to-day development and maintenance of the project |

1.
# PROJECT CHARTER APPROVAL

The undersigned acknowledge they have reviewed the project charter and authorize and fund the _\<Project Name\>_ project. Changes to this project charter will be coordinated with and approved by the undersigned or their designated representatives.

_[List the individuals whose signatures are desired. Examples of such individuals are Business Steward, Project Manager or Project Sponsor. Add additional lines for signature as necessary. Although signatures are desired, they are not always required to move forward with the practices outlined within this document.]_

| Signature: |
 | Date: |
 |
| --- | --- | --- | --- |
| Print Name: |
 |
 |
 |
| Title: |
 |
 |
 |
| Role: |
 |
 |
 |

| Signature: |
 | Date: |
 |
| --- | --- | --- | --- |
| Print Name: |
 |
 |
 |
| Title: |
 |
 |
 |
| Role: |
 |
 |
 |

| Signature: |
 | Date: |
 |
| --- | --- | --- | --- |
| Print Name: |
 |
 |
 |
| Title: |
 |
 |
 |
| Role: |
 |
 |
 |

**APPENDIX A: REFERENCES**

_[Insert the name, version number, description, and physical location of any documents referenced in this document. Add rows to the table as necessary.]_

The following table summarizes the documents referenced in this document.

| **Document Name and Version** | **Description** | **Location** |
| --- | --- | --- |
| _\<Document Name and Version Number\>_ | _[Provide description of the document]_ | _\<URL or Network path where document is located\>_ |

s

_[Insert appropriate Disclaimer(s)]_
