**# ProCaller

**# PROJECT CHARTER**

### Version 1.7

# 26/09/2023

# Wind Falcons

**VERSION HISTORY**

_[Provide information on how the development and distribution of the Project Charter up to the final point of approval was controlled and tracked. Use the table below to provide the version number, the author implementing the version, the date of the version, the name of the person approving the version, the date that particular version was approved, and a brief description of the reason for creating the revised version.]_

| **Version #** | **Implemented**** By **|** Revision ****Date** | **Approved**** By **|** Approval ****Date** | **Reason** |
| --- | --- | --- | --- | --- | --- |
| 1.0 | _Andrii Provozin_ | _09/26/2023_ | _Ryan Dotzlaw_ | _09/26/2023_ | _Completed Part 5_ |
| 1.1 | Josh Sigurdson | 09/26/2023 | Andrii Provozin | 09/26/2023 | Completed Part 4 |
| 1.2 | Ryan Dotzlaw | 09/26/2023 | Andrii Provozin | 09/26/2023| Completed Part 3|
| 1.3 | _Ikram Khan Shipon_ | _09/27/2023_ | _Andrii Provozin_ |  _09/28/2023_ | _Added part 2 and name of the project_ |
| 1.4 | _Khush Patel_ | _09/27/2023_ | _Andrii Provozin_ | _09/28/2023_ | _Completed Part 6_ |
| 1.5 | _Andrii Provozin_ | _09/27/2023_ | _Khush Patel_ | _09/28/2023_ | _Fixes of Project look and extra character removal_ |
| 1.6 | _Khush Patel_ | _09/28/2023_ | _Andrii Provozin_ | _09/28/2023_ | _Final Changes and project charter approval_ |
| 1.7 | _Andrii Provozin_ | _09/28/2023_ | _Khush Patel_ | _09/28/2023_ | _Final Changes and project charter approval_ |

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

# INTRODUCTION

## PURPOSE OF PROJECT CHARTER

_[Provide the purpose of the project charter.]_

The _ProCaller_ project charter documents and tracks the necessary information required by decision maker(s) to approve the project for funding. The project charter should include the needs, scope, justification, and resource commitment as well as the project's sponsor(s) decision to proceed or not to proceed with the project. It is created during the Initiating Phase of the project.

The intended audience of the _\<Project Name\>_ project charter is the project sponsor and senior leadership.

# PROJECT AND PRODUCT OVERVIEW

_ProCaller_ is an online phone system that uses the internet to place virtual calls between users anytime. It's primary users will be business employees who can make and receive calls using an installed app on desktop, laptop or a  mobile phone. Each device connected to the system will have a unique phone number assigned to it that can be used to make and receive calls.

The estimated time for this project is 18 months with an estimated budget of $1.5M.

# JUSTIFICATION

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

## MAJOR DELIVERABLES

The following table presents the major deliverables that the project's product, service or result must meet in order for the project objectives to be satisfied.

| **Major Deliverable** | **Deliverable Description** |
| --- | --- |
|Application| The application used by clients to perform calls. Both the mobile, and computer applications.|
|Backend Server|The backend server that routes calls, tracks logs and stores user data. By this point the Online Virtual Phone System should be capable of being used by two users to call each other.|
|System Console|The GUI that allows Administrators to moderate and monitor the Online Virtual Phone System.|
|Billing System|Integrates with the Backend Server and the System Console to calculate a user’s bill and make it available to see for Administrators. Additionally, it should contact users with their bill at the end of the current billing period and deny them system access if they fail to pay it.|

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
2. _Only one administrator can access the system at a time._
3. _Both clients have initiating the call have our app installed on their devices_. 
4. _Administrators acquired other required permissions to make changes to user's plan (legal right to change the plan, approval from the manager, etc.)_.

## CONSTRAINTS

_[Example: There might be time constraints on developing a system that is used to track data of highly infectious diseases like SARS.]_

This section identifies any limitation that must be taken into consideration prior to the initiation of the project.

1. The system needs to make sure that no phone numbers can start with a particular prefix that is used for advanced features. The available phone numbers are constrained by this restriction, which should be taken into account while designing the dialing plan.
2. The billing software must correctly determine prices depending on call length, time of day, and calling plan. A crucial restriction is ensuring accuracy in billing calculations.
3. The system should be capable of keeping user records should be retained indefinitely, so storage auto-scaling should be taken into consideration.
4. Client should be connecting to the server via sockets.
5. System should have database schema set up in a way that would allow fetching any user's bill for any billing period. 


## RISKS

_[Example: The risk of accessibility or unavailability of public health partners for obtaining requirements to develop a data collection system may delay project deliverables. A possible mitigation strategy might be to schedule requirement sessions with the partners as early as possible. List the risks that the project sponsor should be aware of before making a decision on funding the project, including risks of not funding the project.]_

| **Risk** | **Mitigation** |
| --- | --- |
| The possibility of poor internet connectivity or cloud service disruptions could impair users' capacity to communicate by interfering with their ability to make and receive calls through the system. | Implement redundancies or backup communication systems to reduce the likelihood of service outages. |
| Errors in counting calls, billing or other conflicts with users run the danger of causing financial losses or client dispair. | Implement thorough testing and validation of the billing system to reduce errors and develop a transparent procedure for handling disputes. |
| Multiple administrators can log into the system at the same time, so if operations are not atomic it could corrupt the data. | Implement the database design where save operations are atomic. | 
| Conflict in priorities of requests between call processing and software administration. | Make a table with priorities defined for each known operation before starting to implement it. |
| Attacker acquiring access to one of the administrator accounts and corrupting data to cause damage. | Implement additional security measures, like MFA (Multi factor authentification).




# PROJECT ORGANIZATION

## STAKEHOLDERS (INTERNAL AND EXTERNAL)

#### Internal Stakeholders:
  1. Project Sponsor: Pengfei He (TA).
  2. Project Manager: Andrii Provozin.
  3. Development Team: Josh Sigurdson, Ikram Khan Shipon, Ryan Dotzlaw and Khush Patel.

#### External Stakeholders:
  1. Customer: Pengfei He's company's primary customers are the end-users of the virtual phone system.
  2. Customer Support: An outsourced customer support technician who provides technical support and assistance to customers using the virtual phone system.


## ROLES AND RESPONSIBILITIES

_[Depending on your project organization, you may modify the roles and responsibilities listed in the table below.] [You can put the project sponsor as TA] [Project manager could be the member take the role for this round.]_

This section describes the key roles supporting the project.

| **Name & Organization** | **Project Role** | **Project Responsibilities** |
| --- | --- | --- |
| Pengfei He, Universit of Manitoba | Project Sponsor | Phengfei takes on a central role in our project by defining its goals, objectives, scope, and timeline. They are also responsible for securing the necessary funding. Phengfei also provides guidance to ensure that our project aligns effectively with its intended objectives.|
| Andrii Provozin, Wind Falcons | Project Manager | Andrii takes on the role of scheduling meetings and maintaining project documentation. He holds specific accountability for managing the project within the approved constraints and is responsible for reviewing all work completed by the team. |
| Ryan Dotzlaw, Wind Falcons  | Developer | Ryan is in charge of enhancing the user interface and user experience (UI/UX) for both the mobile and desktop applications.|
| Ikram Khan Shipon, Wind Falcons | Developer | Ikram's tasks include developing tools for administrators for tracking and moderating the activities of users, as well as developing call logs system for users.  |
| Josh Sigurdson, Wind Falcons | Developer | Josh is responsible for developing the database system and integrating it with the application.  |
| Khush Patel, Wind Falcons | Developer | Khush is responsible for implementing the seamless routing system of calls. |

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
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Introduction](#introduction) |
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Project](#project-and-product-overview) |
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Justification](#justification) |
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Duration](#duration) |
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Assumptions-constraints-and-risks](#assumptions-constraints-and-risks) |
| Project_Charter 1.7| Documentation for tracks the necessary information required by decision makers to approve the project for funding.| [Project-organization](#project-organization) |


s

_[Insert appropriate Disclaimer(s)]_
