
<div style="text-align: center;">

# **Chinese Railroad Ministry**

## Risk Management Plan

## Version 1.0

## November 10th, 2023

## Wind Falcons

</div>

## Revision History

| **Date**     | **Description** | **Author**        | **Comments**                        |
| ------------ | --------------- | ----------------- | ----------------------------------- |
| _11/08/2023_ | _Version 1.0_   | _Josh Sigurdson_    | _Initial commit and task breakdown_ |
| _11/08/2023_ | _Version 2.0_   | _Khush Patel_    | _10 Risk Identification_ |
| _11/08/2023_ | _Version 2.1_   | _Josh Sigurdson_    | _10 Risk Identification_ |
| _11/08/2023_ | _Version 3.0_ | _Ikram Khan_ | _5 Key Risk Identification and Justification_ |
| _11/09/2023_ | _Version 3.1_ | _Andrii Provozin_ | _5 Key Risk Identification and Justification_ |
| _11/09/2023_ | _Version 4.1_   | _Khush Patel_    | _Updated an Risk_ |
| _11/10/2023_ | _Version 5.0_   | _Ryan Dotzlaw_    | _Added Intro, Additional Insights, and Summary_ |


## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Risk Identification](#2-risk-identification)
- [3. Key Risk Identification](#3-key-risk-identification)
  - [3.1 Justification](#31-justification)
  - [3.2 Response Plan](#32-response-plan)
- [4. Additional Insights](#4-additional-insights)
- [5. Summary](#5-summary)

## 1. Introduction

The purpose of this document is to define a robust risk management plan for the Automated Railway Reservation System (ARRS) project, as requested by the Chinese Railroad Ministry (CRM).
The ARRS project involves several conditions:

* None of the team involved speak the language. Interpreters must be relied on.
* There will only be a small management team brought from the company, all other personnel and equipment is supplied by the CRM.
* The local programmers have a good background in computer science, but lack skills in software engineering, object-oriented developement, and telecommunication skills.
* There is sufficient hardware for a client-server approach.
* The CRM has failed to implement a similar project before they had access to good telecommunications technology.
* Customers, employees and managers will be available to communicate with for clarifications.

These conditions, along with the list of resources supplied by the CRM, and other contextual factors will be used to perform risk identification, analysis, prioritization and planning in order to build the risk management plan.

## 2. Risk Identification

| **Risk** | **Description** | **Probability** |  **Potential Loss** | **Risk Exposure** | **Risk Category** |
| -------- | --------------- | --------------- | ------------------- | ----------------- | ----------------- |
| Misalignment with Stakeholders | Risk of miscommunication between CRM and stakeholders on project goals and objectives, could result into conflicting priorities and expectations. | 0.25 | 150000 | 37500 | Mission and Goals |
| The Unplanned competitors Risk | The marketing team didn't find any other companies to compete with, so they didn't make a plan for dealing with future competitors and a disorganized organization can struggle to successfully complete a software project. | 0.4 | 200000 | 80000 | Organization Management |  
| Regular Changes in Requirements | Regular changes in the requirements and specifications from CRM could potentially impact scope and timeline. | 0.2 | 150000 | 30000 | Customer |  
| Overspending in the Budget | Unexpected expenses like providing more resources to train developer, changes in hardware requirement can possibly exceed budget. | 0.2 | 70000 | 14000 | Budget/Cost |  
|Unsuccessful Marketing | If the marketing plan is ineffective, due to it being led by an inexperienced recent graduate, failing to penetrate the market will result in the need for more funds to be allocated to marketing to raise the public's awareness | 0.5 | 200000| 100000 | Budget/Cost|
| Delays in Resource Availability | Delay in training for CASE tool as AsiaPac being trained last. This could affect the project's schedule and overall progress.  | 0.1 | 90000 | 9000 | Schedule |  
| Management assumptions | Management assuming prototype is doable with in 90 days using the CASE tool could affect the schedule if prototype are not done in the given time-frame.   | 0.6 | 100000 | 60000 | Schedule | 
| Scope Creep | The project's scope expanding without adjustments to the project schedule could delay and increase the cost. | 0.5 | 250000 | 125000 | Schedule |  
| Software Integration | Issues in integrating Software with Hardware could lead to instable system resulting in operational challenges. | 0.6 | 200000 | 120000 | Project Content |  
| High Dependency on Vendors | Heavy reliance on external vendors for critical components could cause delays or issues outside the project scope. | 0.3 | 100000 | 30000 | Project Content |
| Scalability and Performance | The high variance in test number and real world data which also varies significantly by hour, day and season could lead to system not performing optimally. | 0.3 | 150000 | 45000 | Performance |  
|Reservation Overload| The growing amount of users will imply greater number of reservations. This could overall effect system performance if there are too many reservations (>25,000 per day) being made at one time.| 0.4| 400000 | 160000 | Performance |
| Inexperience in Foreign Project Management | The PM has never worked on an international project before. This could then lead to miscommunication/misunderstanding between the PM and the team when managing foreign teammates. | 0.2 | 100000 | 20000 | Project Management |
| Loss of Product Quality due to Poor Communication | Analyses of alternatives and quality assurance can be lost in translation when developing the software, leading to poor product quality. | 0.4 | 200000 | 80000 | Development Risk |
|Distance between Team Members | Some of the team will be in China. Teams need face-to-face contact on a regular basis. This will degrade time efficiency and quality of the project if there are no regular meetings of the entire team. | 0.5 | 300000 | 150000 | Development Environment |
|Deficiency in CRM's Hardware and Software | The development tools and platforms provided by CRM may not be sufficiently built for the needs of the project. This can lead to a reduction in possible features and development efficiency. | 0.3 | 600000 | 180000 | Development Environment |
| Management Team in Foreign Environment | The four-person management team will be relocated to China for the project. This will force the management team to use interpreters for communication overall reducing the efficacy of communication and loss of team coalition. This can then reduce project efficiency and quality| 0.5 | 350000 | 175000 | Development Environment |
|Many Inexperienced Programmers | Around 38% of the team have a lack of experience. This can reduce productivity by 10-25 times relative to a fully experienced team of programmers| 0.6|500000|300000|Staff|
|Staff has a Lack of Knowledge in Object Orientation | None of the personnel at CRM have experience developing OO systems. This inexperience can reduce productivity with the needed time to learn OO systems. |0.25 | 200000 | 50000 | Staff |
|Quality of Support | The team has an unverified quality of communication. This may cause an inability to communicate problems, thus reducing quality of customer support and the project's efficiency | 0.4 | 200000 |80000 | Maintenance |

## 3. Key Risk Identification

This section identifies the key risks for this project. The risks are prioritised based on the highest risk exposure from the table above.

1. Many Inexperienced Programmers.

2. Deficiency in CRM's Hardware and Software.

3. Management Team in Foreign Environment.

4. Reservation Overload.

5. Distance between Team Members.

### 3.1 Justification

- **Many Inexperienced Programmers**:  
  Inexperienced development team may take much longer to complete tasks, resulting in delays and potentially compromised project quality. Due to the significant impact inexperienced programmers can have on project productivity, this risk is ranked at the top.

- **Deficiency in CRM's Hardware and Software**:  
  Inadequate tools and platforms can result in slower development processes, scalability challenges, and potential budget overruns, impacting both project timeline and quality. To ensure the project succeeds, addressing this risk requires a proactive assessment of existing resources and necessary upgrades. Hence this risk is prioritised.

- **Management Team in Foreign Environment**:  
  The management team's presence in a foreign setting creates possible misalignment and communication issues. This risk is significant since it could affect team cohesiveness, decision-making, and the effectiveness of the project as a whole.

- **Reservation Overload**:  
  If the system cannot handle a high volume of reservations, it could result in poor user experience, potential system crashes, and increased customer dissatisfaction. This makes it a critical risk as it directly affects the system's performance.

- **Distance between Team Members**:  
  The geographical separation of team members, especially when some are located in China, can lead to communication and collaboration difficulties. This can impact the project's efficiency and the quality of work delivered.

### 3.2 Response Plan

| **Risk** | **Person Responsible** | **Response Strategy** | **Action Plan** | **Resource** |
| -------- | ---------------------- | --------------------- | --------------- | ------------ |
| **Many Inexperienced Programmers** | Project Manager | Mitigate | Training and Mentorship: Provide novice team members with extensive training through an implemented program. Assign seasoned mentors to assist and advise them. | Mentoring guidelines and training materials. |
| **Deficiency in CRM's Hardware and Software** | System Architect | Avoid | Evaluation and Upgrade: Evaluate the hardware and software that are currently in use. Arrange and carry out the necessary improvements to fix the flaws.  | Tools for evaluation and resource upgrades. |
| **Management Team in Foreign Environment** | IT Manager | Mitigate | Communication Protocols: Clearly define the channels of communication. Utilize online collaboration platforms to overcome the distance. Arrange frequent online conferences to coordinate plans and choices. | Platforms for online meetings and collaboration tools. |
| **Reservation Overload** | System Architect | Avoid | Capacity Planning: Evaluate the reservation system's capacity. To manage the additional demand, implement upgrades and optimizations. Track system performance over time. | Instruments for system monitoring and performance analysis. |
| **Distance between Team Members** | Scrum Master | Mitigate | Establish reliable virtual collaboration solutions for virtual cooperation. Create a transparent communication system and schedule frequent online meetings. Encourage frank and proactive communication in the culture. | Platforms for online meetings and collaboration tools. |

## 4. Additional Insights

All the key risks, except for **Reservation Overload**, will be managed directly at the initial stages of the project. 
While this will make the initial stages of the project more challenging, should the risk management plan be followed, for the rest of the project the only other key risk will be **Reservation Overload**.

In addition to that, the risk factor of **Reservation Overload** will be lessened if the **Deficiency in CRM's Hardware and Software** is managed correctly. 
The newer hardware would allow more reservations to occur at once without overloading the system.


## 5. Summary

In summary, the risk identification table provides a list of possible risks the ARRS project may face, along with the estimated consequences of said risks.

Additionally, **Many Inexperienced Programmers**, **Deficiency in CRM's Hardware and Software**, **Management Team in Foreign Environment**, **Reservation Overload**, and **Distance between Team Members** are the key risks due to their high risk exposure, and for the reasons defined in the justification section.

Finally, the response plan provides a plan of action to help mitigate or avoid the key risks of the ARRS project.
