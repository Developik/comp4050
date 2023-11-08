<div style="text-align: center;">

# **Pro Caller**

## Software Requirements Specification

## Version 1.0

## October 13, 2023

## Wind Falcons

</div>

<div style="page-break-after: always;"></div>

## Revision History

| **Date** | **Description** | **Author** | **Comments** |
| --- | --- | --- | --- |
| _10/10/2023_ | _Version 1.0_ | _Josh Sigurdson_ | _Initial Set-up_ |
| _10/10/2023_ | _Version 1.1_ | _Josh Sigurdson_ | _Completed Section 2_ |
| _10/12/2023_ | _Version 1.2_ | _Ikram Khan Shipon_ | _Completed Sections 3.2.1 - 3.2.5_ |
| _10/12/2023_ | _Version 1.3_ | _Andrii Provozin_ | _Completed Section 1_ |
| _10/12/2023_ | _Version 1.4_ | _Khush Patel_ | _Completed Section 3.1_ |
| _10/13/2023_ | _Version 1.5_ | _Ryan Dotzlaw_ | _Completed Sections 3.3 - Appendix A_ |


<div style="page-break-after: always;"></div>

**Table of Contents**

- [1. Introduction](#1-introduction)
  - [1.1 Purpose](#11-purpose)
  - [1.2 Definitions, Acronyms, and Abbreviations](#12-definitions-acronyms-and-abbreviations)
  - [1.3 References](#13-references)
- [2. General Description](#2-general-description)
  - [2.1 User Characteristics](#21-user-characteristics)
  - [2.2 Assumptions and Dependencies](#22-assumptions-and-dependencies)
- [3. Specific Requirements](#3-specific-requirements)
  - [3.1 Functional Requirements](#31-functional-requirements)
    - [3.1.1 Call Notification](#311-call-notifications)
      - [3.1.1.1 Incoming Call Notifications](#3111-incoming-call-notifications)
      - [3.1.1.2 Missed Call Notifications](#3112-missed-call-notifications)
      - [3.1.1.3 Busy Call Notifications](#3113-busy-call-notifications)
      - [3.1.1.4 Decline Call Notifications](#3114-decline-call-notifications)
    - [3.1.2 Call Handling](#312-call-handling)
      - [3.1.2.1 Accepting Incoming Calls](#3121-accepting-incoming-calls)
      - [3.1.2.2 Declining Incoming Calls](#3122-declining-incoming-calls)
      - [3.1.2.3 Call Conferencing](#3123-call-conferencing)
    - [3.1.3 Call Dialing](#313-call-dailing)
      - [3.1.3.1 Dailing Unsaved Numbers](#3131-dialing-unsaved-numbers)
      - [3.1.3.2 Dailing Saved Numbers](#3132-dialing-saved-numbers)
  - [3.2 Non-Functional Requirements](#32-non-functional-requirements)
    - [3.2.1 Performance](#321-performance)
    - [3.2.2 Reliability](#322-reliability)
    - [3.2.3 Availability](#323-availability)
    - [3.2.4 Security](#324-security)
  - [3.2.5 Interfaces](#325-interfaces)
  - [3.3 Design Constraints](#33-design-constraints)
  - [3.4 Legal, Copyright, and Other Notices](#34-legal-copyright-and-other-notices)
  - [3.5 Other Requirements](#35-other-requirements)
  - [4 Other Supporting Documents](#4-other-supporting-documents)
  - [A. Appendices](#a-appendices)

<div style="page-break-after: always;"></div>

# 1. Introduction

This paper serves as a thorough Software Requirements Specification (SRS) for the creation of ProCaller, a virtual phone system for the internet. <br>

ProCaller enables customers to make and receive calls through the internet, it aims to change communication removing the need to use the conventional landline connections. ProCaller offers an effective solution for both individuals and enterprises, with the capacity to use it on desktop and mobile platforms. <br>

In the next parts, we will go into detail about the information related to the users and stakeholders, important assumptions and dependencies, as well as functional and non-functional components of the ProCaller system. This SRS will direct the project's software design, implementation, and testing to make sure the finished product satisfies the performance, reliability, security, and ui criteria. And that it aligns with the client's vision. <br>

This document is a crucial tool that will serve as a set of specifications and a roadmap for the project managers, testing team, and developers who are working to complete the ProCaller project. 

## 1.1 Purpose

The purpose of this SRS is the fulfill the following:

- Specify the project's parameters and key components for the online virtual phone system.
- Give precise definitions and descriptions of the important parts, procedures, and features of the system.
- Provide a thorough reference for project development, directing software engineers, developers, and stakeholders over the course of the project.
- Ensure that the client's expectations and the development team's understanding of the system's needs are aligned.

The intended audience are: 

- Software Development Team 
- Project Manager
- Project Owner
- Testing Team
- Business Department

## 1.2 Definitions, Acronyms, and Abbreviations

Acronyms and abbreviations definitions:

Software Requirements Specification, or SRS

- A document that provides a thorough description of the features and functionalities of a software project's requirements and specifications.

User Interface, or UI

- Users engage with the visual and interactive components of a software application to carry out activities. <br> 
Example: Facebook web page.

Application Programming Interface (API)

- A set of guidelines and procedures that permit communication between various software programs. <br> Example: Twitter API, allows fetching data in JSON format.

Design requirements, or D-requirements

- Clear specifications that direct a software project's conception, execution, and testing.

Operating System (OS):

- Software that controls computer hardware and offers assistance to computer programs. <br> Example: Windows 11.


## 1.3 References

| **Reference number** | **Document Title**|**Date** | **Author** | **Source** |
| --- | --- | --- | --- | --- |
| 1 | _Project Software Description_ | _09/01/2023_ | _Shaowei Wang_ | [Link](https://umanitoba-my.sharepoint.com/:w:/g/personal/shaowei_wang_umanitoba_ca/EX6PKNTuX1hGomL4NyNYSIcBHg5ImCFl2BPrVJnFbBWIsQ?e=prDfNs) |


# 2. General Description

## 2.1 User Characteristics

The characteristics of the eventual users of ProCaller are the callers and callees. These two stakeholders are those who wish to connect and speak through an online system rather than using classical telephone communication. The callees are users who have a need to receive phone calls via a single business phone number. These businesses (callees) can set up a business phone number and receive calls from their customers (callers). The callers can use the ProCaller from a desktop application or mobile phone to reach their desired business. These stakeholders are any business with the need to receive phone calls from their customers. The callers are any person who wishes to call a business.

## 2.2 Assumptions and Dependencies

The ProCaller desktop application will be developed to be used on any common personal computer operating system, namely, Mac and Windows. The ProCaller application will be developed to be used on any common mobile phone operating system, namely, Android and iOS. If any of these previously listed operating systems are not available the SRS will have to be changed accordingly. It is assumed any hardware the ProCaller application will be used on will have a microphone and speakers. ProCaller is dependent on the use of a functional audio input and output.

# 3. Specific Requirements

This will be the largest and most important section of the SRS. The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project's software design, implementation, and testing.

## 3.1 Functional Requirements

This section describes specific features of the software project.  

### 3.1.1 Call Notifications

#### 3.1.1.1 Incoming Call Notifications
- The system should notify the callee for all incoming calls.
#### 3.1.1.2 Missed Call Notifications
- The system should notify the callee for all the missed calls that occurred when the callee was engaged in another call or offline.
#### 3.1.1.3 Busy Call Notifications
- The system should notife caller if the callee is currently engaged in another call and cannot accept the incoming call.
#### 3.1.1.4 Decline Call Notifications
- The system should notify the caller if the callee declines the incoming call.

### 3.1.2 Call Handling

#### 3.1.2.1 Accepting Incoming Calls
- The callee should have the ability to accept incoming calls.
#### 3.1.2.2 Declining Incoming Calls
- The callee should have the option to decline incoming calls, whether they are currently engaged in another call or in an idle state.
#### 3.1.2.3 Call Conferencing
- The callee should have the capability to merge an incoming call with their ongoing call, enabling conference call functionality.

### 3.1.3 Call Dailing

#### 3.1.3.1 Dialing Unsaved Numbers
- The callee should have the capability to manually dial any phone number.
#### 3.1.3.2 Dialing Saved Numbers
- The callee should have the capability to directly dial a phone number from their saved contacts or address book.
 




## 3.2 Non-Functional Requirements

This section describes non-functional features of the software project.

### 3.2.1 Performance

- The system shall take initial load time depending on internet connection strength which also depends on the media from which the system is run.

- The system shall respond to any UI interaction within 200 milliseconds.

- The system should handle a minimum of 1000 concurrent calls without any degradation in performance.

### 3.2.2 Reliability

- The system shall have a fault tolerant mechanism to allow continuous operation.

- The system must maintain data integrity to ensure user data is accurate and consistent within the application.

### 3.2.3 Availability

- The system shall have 99.99% availability discounting any scheduled maintenance periods.

### 3.2.4 Security

- The system shall use secure sockets in all calls that include any confidential customer information.

- The system shall automatically log out all customers after a period of inactivity.

- All calls must be end-to-end ecnrypted between devices.

### 3.2.5 Interfaces

- The system must have an intuitive UI and must not exceed more than 15mins of training to setup and use.
- The system should be compatible with laptops, desktops and any mobile devices.
- The system must have a well-documented, fast and secure API to integrate with third-party applications.



## 3.3 Design Constraints

- The software should be designed and implemented in accordance with Wind Falcons coding and design standards.
- The software requires a stable internet connection to function correctly.

## 3.4 Legal, Copyright, and Other Notices

Copyright © 2023 Wind Falcons co. All Rights Reserved

## 3.5 Other Requirements

- The software should meet a professional standard of quality.
- The software should be considered visually appealing to the majority of it's userbase. 

## 4 Other Supporting Documents

- [Project Readme](../README.md)
- [Project Charter](../a1/Project_Charter.md)

## A. Appendices

- [SRS Template](https://umanitoba-my.sharepoint.com/:w:/g/personal/shaowei_wang_umanitoba_ca/ER9IR-uOnnRPquKir7Fy1BIBQOT7YvxIEknOVjHbqnj7cQ?e=qQSWEK)

