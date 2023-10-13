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
| \<date\> | \<Version 1\> | \<Your Name\> | \<First Revision\> |
| ||||

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

[you may need to refine your scope/purpose defined in the project charter after eliciting requirements with stakeholder]

The introduction to the Software Requirement Specification (SRS) document should provide an overview of the complete SRS document. While writing this document please remember that this document should contain all of the information needed by a software engineer to adequately design and implement the software product described by the requirements listed in this document. (Note: the following subsection annotates are largely taken from the IEEE Guide to SRS).

## 1.1 Purpose

_What is the purpose of this SRS and the (intended) audience for which it is written._

## 1.2 Definitions, Acronyms, and Abbreviations

_This subsection should provide the definitions of all terms, acronyms, and abbreviations required to properly interpret the SRS. This information may be provided by reference to one or more appendixes in the SRS or by reference to other documents._

## 1.3 References

_This subsection should:_

_(1) Provide a complete list of all documents referenced elsewhere in the SRS, or in a separate, specified document._

_(2) Identify each document by title, report number - if applicable - date, and publishing organization._

_(3) Specify the sources from which the references can be obtained._

_This information may be provided by reference to an appendix or to another document._

# 2. General Description

## 2.1 User Characteristics

The characteristics of the eventual users of ProCaller are the callers and callees. These two stakeholders are those who wish to connect and speak through an online system rather than using classical telephone communication. The callees are users who have a need to receive phone calls via a single business phone number. These businesses (callees) can set up a business phone number and receive calls from their customers (callers). The callers can use the ProCaller from a desktop application or mobile phone to reach their desired business. These stakeholders are any business with the need to receive phone calls from their customers. The callers are any person who wishes to call a business.

## 2.2 Assumptions and Dependencies

The ProCaller desktop application will be developed to be used on any common personal computer operating system, namely, Mac and Windows. The ProCaller application will be developed to be used on any common mobile phone operating system, namely, Android and iOS. If any of these previously listed operating systems are not available the SRS will have to be changed accordingly. It is assumed any hardware the ProCaller application will be used on will have a microphone and speakers. ProCaller is dependent on the use of a functional audio input and output.

# 3. Specific Requirements

This will be the largest and most important section of the SRS. The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project's software design, implementation, and testing.

## 3.1 Functional Requirements

This section describes specific features of the software project. Specify the requirements as user story.

…

\<

Sell Configured to Ordered Products.

The system shall display all the products that can be configured.

The system shall allow user to select the product to configure.

The system shall display all the available components of the product to configure

\>

…

## 3.2 Non-Functional Requirements

Non-functional requirements may exist for the following attributes. Often these requirements must be achieved at a system-wide level rather than at a unit level. State the requirements in the following sections in measurable terms (e.g., 95% of transaction shall be processed in less than a second, system downtime may not exceed 1 minute per day, \> 30 day MTBF value, etc).

This section describes non-functional features of the software project. Specify the requirements as user story.

### 3.2.1 Performance

\< The product shall take initial load time depending on internet connection strength which also depends on the media from which the product is run.\>

### 3.2.2 Reliability

\< The system shall provide RAID V Disk Stripping on all database storage disks.\>

### 3.2.3 Availability

\< The system shall provide a contractual agreement with an internet service provider for T3 access with 99.9999% availability. \>

### 3.2.4 Security

\< The system shall use secure sockets in all transactions that include any confidential customer information.

The system shall automatically log out all customers after a period of inactivity.\>

## 3.2.5 Interfaces

## 3.3 Design Constraints

- The software should be designed and implemented in accordance with Wind Falcons coding and design standards.
- The software requires a stable internet connection to function correctly.

## 3.4 Legal, Copyright, and Other Notices

Copyright © 2023 Wind Falcons co. All Rights Reserved

## 3.5 Other Requirements

- The software should meet a professional standard of quality. 

## 4 Other Supporting Documents

- [Project Readme](../README.md)
- [Project Charter](../a1/Project_Charter.md)

## A. Appendices

- [SRS Template](https://umanitoba-my.sharepoint.com/:w:/g/personal/shaowei_wang_umanitoba_ca/ER9IR-uOnnRPquKir7Fy1BIBQOT7YvxIEknOVjHbqnj7cQ?e=qQSWEK)