# COMP90082 Software Project GA-Boxjelly

- [COMP90082 Software Project GA-Boxjelly](#comp90082-software-project-ga-boxjelly)
  - [Presentation (with Product DEMO)](#presentation-with-product-demo)
  - [Project Background](#project-background)
  - [Project Description](#project-description)
  - [Project Deployment](#project-deployment)
  - [Project Management Tools](#project-management-tools)
  - [Development Environment](#development-environment)
  - [Release Log](#release-log)
      - [Sprint 1 Release](#sprint-1-release)
      - [Sprint 2 Release](#sprint-2-release)
      - [Sprint 3 Release](#sprint-3-release)
      - [Sprint 4 Release](#sprint-4-release)
  - [Github Structure](#github-structure)
  - [Branches/Naming Conventions](#branchesnaming-conventions)
  - [Development Change Logs](#development-change-logs)
      - [Sprint 1 Change Logs](#sprint-1-change-logs)
      - [Sprint 2 Change Log](#sprint-2-change-log)
      - [Sprint 3 Change Log](#sprint-3-change-log)
      - [Sprint 4 Change Log](#sprint-4-change-log)
  - [About Us](#about-us)

<p align="center"><img src=https://fastly.jsdelivr.net/gh/ZhidongZhou/gallery@master/img/developer_api_devices_to_partner-ad040fd8f527261f2834e69a2dba24ff.png alt="blockw" style="zoom:30%;"/></p>

## Presentation (with Product DEMO)

<p align="center"><a href="https://youtu.be/ky0a-5rEVcI" rel="nofollow"><img src="https://fastly.jsdelivr.net/gh/ZhidongZhou/gallery@master/img/202205290059145.png" alt="Final Presentation"></a></p>

## Project Background

**CoachingMate**: 
The **CoachingMate** is a system for the coach to deliver training sessions to their athletes. And it's now we are specifically required to enable Athletes to review all their Activities and Activity Details through Coaching Mate Web Application

> **Client**: 
> [**Ollie Allan**](https://vic.tri-alliance.com/about/coaches/)
> Ollie is our client from Tri-Alliance. He has been involved in triathlon for 16+ years. He has extensive qualifications in coaching, including Level 2 Triathlon Coach, Level 1 Cycling, Swimming, Strength & Conditioning Coach, etc. Ollie’s passion for the sport and Tri Alliance cannot go unnoticed as his enthusiasm and commitment draws others to the sport and helps them achieve their goals sooner.
> **Tri-Alliance**:
> Tri Alliance VIC is the largest triathlon training squad in Melbourne, offering triathlon coaching, group training, and triathlon training programs for all levels and abilities. They are primarily a coaching service provider, developing comprehensive programs for athletes that wish to compete in various multisport events including, triathlon, duathlon, aquathon, swimming, cycling, and running.

**Garmin**: 
The **Garmin Connect** is the tool for Tracking, Analyzing and Sharing health and fitness activities from **Wearable Devices**. So Athletes with Devices like **Garmin Watch** will have their activity data sync to the **Garmin Connect**. And they provide an API that enables us to access those activity data.

- [Garmin API](https://developer.garmin.com/gc-developer-program/overview/)
- [Garmin Activity API](https://developer.garmin.com/gc-developer-program/activity-api/)
- [Flexible and Interoperable Data Transfer (FIT) SDK](https://developer.garmin.com/fit/overview/)

## Project Description

**Project Goal**:
the **GOAL** of our project is about **data integration** with **Garmin API** and syncing the Activity data to the **Coaching-Mate Dashboard**. Our **Coaching-Mate** project is NOT built from scratch, and we are working on the code from the Previous **Garmin API Project**. So our main focus is to maintain and improve the existing platform. And we need to guarantee the data integration from GARMIN and ensure the dashboard display and retrieve the list of activity and activity details from **Garmin Connect**.

**Our Scope**: 
The Garmin API is what our project will be focusing on. Garmin is a commercialized product that targets clubs and coaches. Garmin API gitprovides an easy way to integrate a platform directly into their content management website. This project needs to improve the APIs from the existing system, to increase the breadth of activities that are currently pulled by the CoachingMate backend.

Garmin should also be able to connect to external websites so that the workout data can be viewed by other people. Our team is also recommended to develop APIs for Garmin to connect to other external websites.
1. coaching-mate account management
   1. Account <u>register</u>
   2. Account <u>log-in</u>
   3. and <u>log-out</u>
2. Connect **CoachingMate Web Application** with the **Garmin Connect** API 
3. Show data from **Garmin Connect** to the <u>Dashboard</u> of the **CoachingMate Web Application**
   1. List of Activities
   2. Activity Details


**Out Scope**: 
Our team will not be responsible for data analytics. There are already a lot of functions on the Garmin dashboard. The GA teams will not be involved with the website design. This project will not be involved with how to visualize the data either.
1. Frontend UI Design 
2. Data Analysis

## Project Deployment 

**Deployment Walkthrough**: 

- [Deployment_Guideline](./docs/sprint_4_documentations/Handover/Deployment_Guideline_v1.0.pdf)
- [User Guide](./docs/sprint_4_documentations/Handover/User_Guide_v1.0.pdf)

**Deployment with Live Demo**: 
<!-- Update From Vue to React -->
<!-- - [Coaching-Mate Front-end](https://ga-boxjelly-frontend.herokuapp.com/#/) -->
- [Coaching-Mate Front-end](https://coaching-mate-frontend-react.herokuapp.com/)
- [Coaching-Mate Back-end](https://ga-boxjelly.herokuapp.com/)

## Project Management Tools

> - [Boxyjelly Confluence Space](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Boxjelly)
> - our team use the [Project Tasks Management Tool (Github Projects)](https://github.com/COMP90082SM12022/GA-Boxjelly/projects/1) (a Trello like tool) for manage our products and product backlogs. 

## Development Environment
- Frontend:
  - node: v14.17.6
  - vue-cli: 2.9.6
  - react: 16.9.34
- Backend:
  - Apache Maven: 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
  - Java version: 1.8.0_45, vendor: Oracle Corporation
  - MongoDB: mongodb-community@4.4

## Release Log

**Sprint Release Outline**

| Sprint   | Tag URL                                                                                                                        | Description                  |
| -------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------- |
| Sprint 1 | [Sprint 1 Release Tag](https://github.com/COMP90082SM12022/GA-Boxjelly/releases/tag/COMP90082_2022_SM1_GA_Boxjelly_BL_SPRINT1) | Detail see [Sprint 1 Release](####Sprint-1-Release) below |
| Sprint 2 | [Sprint 2 Release Tag](https://github.com/COMP90082SM12022/GA-Boxjelly/releases/tag/COMP90082_2022_SM1_GA_Boxjelly_BL_SPRINT2) | Detail see [Sprint 1 Release](####Sprint-2-Release) below |
| Sprint 3 | [Sprint 3 Release Tag](https://github.com/COMP90082SM12022/GA-Boxjelly/releases/tag/COMP90082_2022_SM1_GA_Boxjelly_BL_SPRINT3) |            Detail see [Sprint 3 Release](####Sprint-3-Release) below                  |
| Sprint 4 | [Sprint 4 Release Tag](https://github.com/COMP90082SM12022/GA-Boxjelly/releases/tag/COMP90082_2022_SM1_GA_Boxjelly_BL_SPRINT4)         |          Detail see [Sprint 4 Release](####Sprint-4-Release) below                    |

#### Sprint 1 Release

<table style="text-align: left; padding: 0px;" class="confluenceTable stickyTableHeaders" resolved=""><colgroup><col><col><col></colgroup><thead class="tableFloatingHeader" style="display: none;"><tr><th colspan="1" class="confluenceTh">Issue Type</th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue ID</span></span></th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue Title</span></span></th></tr></thead><tbody><tr><td rowspan="6" class="confluenceTd"><p>Project Inception &amp;</p><p>Requirement Documentation</p></td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/5" rel="nofollow"><span class="md-plain">#5</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Project Background</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/7" rel="nofollow"><span class="md-plain">#7</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Personas</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/6" rel="nofollow"><span class="md-plain">#6</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Motivational Model</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/4" rel="nofollow"><span class="md-plain">#4</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Confluence Setup and Structuring</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/8" rel="nofollow"><span class="md-plain">#8</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">User Stories</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/3" rel="nofollow"><span class="md-plain">#3</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Product Backlog</span></span></td></tr></tbody></table>


#### Sprint 2 Release

<div class="table-wrap"><table style="text-decoration: none; text-align: left; padding: 0px;" class="confluenceTable stickyTableHeaders" resolved=""><colgroup><col><col><col></colgroup><thead class="tableFloatingHeader" style="display: none;"><tr><th colspan="1" class="confluenceTh">Issue Type</th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue ID</span></span></th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue Title</span></span></th></tr></thead><tbody><tr><td rowspan="4" class="confluenceTd">Develop Functional Requirement&nbsp;</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/31" rel="nofollow"><span class="md-plain">#31</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">EP01-01 Account Register</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10" rel="nofollow"><span class="md-plain">#10</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">EP01-02&amp;03 Account login &amp; Logout</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/9" rel="nofollow"><span class="md-plain">#9</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">EP02-07&amp;08 Garmin API Connect &amp; Disconnect</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/30" rel="nofollow"><span class="md-plain">#30</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">EP02-09 Options (Yes/No) for Garmin API Connection</span></span></td></tr><tr><td rowspan="2" class="confluenceTd">Research for Decision Making</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/22" rel="nofollow"><span class="md-plain">#22</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Figure out what Data is involved during API Connection</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/21" rel="nofollow"><span class="md-plain">#21</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Research On API</span></span></td></tr><tr><td rowspan="2" class="confluenceTd">Basic Development Setup</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/28" rel="nofollow"><span class="md-plain">#28</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Frontend Code Environment Setup</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/17" rel="nofollow"><span class="md-plain">#17</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Backend Code Environment Setup</span></span></td></tr><tr><td rowspan="5" class="confluenceTd">Bug &amp; Fixing</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/36" rel="nofollow"><span class="md-plain">#36</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">BUG: Error on Garmin Push Module</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/33" rel="nofollow"><span class="md-plain">#33</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">BUG: Error RESTFUL API Post Request not work</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/27" rel="nofollow"><span class="md-plain">#27</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">BUG: Activity Data Fail to send from Garmin Watch to Garmin API</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/25" rel="nofollow"><span class="md-plain">#25</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">BUG: White Page Error in Swagger UI</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/15" rel="nofollow"><span class="md-plain">#15</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">BUG: Activity Files Upload Failed</span></span></td></tr><tr><td rowspan="3" class="confluenceTd">Acceptance Testing</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/20" rel="nofollow"><span class="md-plain">#20</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Acceptance Testing: EP01-01 Account Register</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/18" rel="nofollow"><span class="md-plain">#18</span></a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Acceptance Testing: EP01-02&amp;03 Account login &amp; Logout</span></span></td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c  md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/13" rel="nofollow"><span class="md-plain">#13</span></a></span></span></td><td class="confluenceTd"><span class="td-span md-focus"><span class="md-plain md-expand">Acceptance Testing: EP02-07&amp;08 Garmin API Connect &amp; Disconnect</span></span></td></tr></tbody></table></div>

#### Sprint 3 Release

<table style="text-decoration: none; text-align: left; padding: 0px;" class="confluenceTable stickyTableHeaders" resolved=""><colgroup><col><col><col></colgroup><thead class="tableFloatingHeaderOriginal"><tr><th colspan="1" class="confluenceTh">Issue Type</th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue ID</span></span></th><th class="confluenceTh"><span class="td-span"><span class="md-plain">Issue Title</span></span></th></tr></thead><tbody><tr><td rowspan="2" class="confluenceTd">Develop Functional Requirement&nbsp;<span class="td-span"><span class="md-meta-i-c md-link"></span></span></td><td class="confluenceTd"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/14" rel="nofollow">#14</a></td><td class="confluenceTd">EP03-10: Activity Dashboard Page</td></tr><tr><td class="confluenceTd"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/11" rel="nofollow">#44</a></td><td class="confluenceTd">EP03-11: EP03-11 Activity Detail Page</td></tr><tr><td rowspan="2" class="confluenceTd">Acceptance Testing</td><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/11" rel="nofollow"><span class="md-plain">#</span></a><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/31" rel="nofollow">11</a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Acceptance Testing: </span></span>EP03-10 Activity Dashboard Page</td></tr><tr><td class="confluenceTd"><span class="td-span"><span class="md-meta-i-c md-link"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/12" rel="nofollow"><span class="md-plain">#1</span></a><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10" rel="nofollow">2</a></span></span></td><td class="confluenceTd"><span class="td-span"><span class="md-plain">Acceptance Testing: </span></span>EP03-11 Activity Detail Page</td></tr><tr><td rowspan="2" class="confluenceTd">Bug &amp; Fixing</td><td colspan="1" class="confluenceTd"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/37" rel="nofollow">#37</a></td><td colspan="1" class="confluenceTd">BUG: Error on Synchronizing Data to Activity Detail bug-fix</td></tr><tr><td colspan="1" class="confluenceTd"><a class="external-link" href="https://github.com/COMP90082SM12022/GA-Boxjelly/issues/53" rel="nofollow">#53</a></td><td colspan="1" class="confluenceTd">Change frontend from VUE back to React</td></tr></tbody></table>

#### Sprint 4 Release

> No further functional development made in sprint 4
> Mainly working final handover (Only Add new Documentations) 
> Details see: [Sprint 4 Change Log](####Sprint-4-Change-Log)


## Github Structure

```shell
├── docs/
  ├── backups
​  ├── ideas
​  ├── sprint_1_requirement_documentations
​  ├── sprint_checklists
├── src/
​  ├── coaching-mate
​  ├── cm-frontend		
├── tests/ 
├── prototypes/low fidelity/
├── prototypes/high fidelity/ 
├── ui/ 
├── data samples
└── README.md
```

| Path                      | Description                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------------- |
| README.md                 | Project Background, Team Members, GitHub Structure & Change Logs for each sprint                          |
| [docs/](./docs/)                     | Requirements & Meeting Minutes                                                                            |
| [src/](./src/)                      | Project Source Code                                                                                       |
| [tests/](./tests/)                    | User/System Tests                                                                                         |
| [prototypes/low fidelity/](./prototypes/low%20fidelity/)  | Low fidelity files (screens, mockups, etc.)                                                               |
| [prototypes/high fidelity/](./prototypes/high%20fidelity/) | High fidelity files (screens, source files, etc.)                                                         |
| [ui/](./ui/)                       | User Interface Design & Development related files: (Prototype Materials, Icons, Fonts, Backgrounds, etc.) |
| [data samples/](./data%20samples/)             | Project Inputs Data for Prototyping (Simulation or DEMO)                                                  |


## Branches/Naming Conventions

**Branch Naming Convention**: `${TYPE}-${DESCRIPTION}`

- Branch Names are all uppercase.
- TYPE: 
  - **Bug** – The bug which needs to be fixed soon
  - **WIP** – The work is in progress, and I am aware it will not finish soon

- DESCRIPTION: Briefly explain what the branch does.

**Commit Naming Convention**: `${type}(${summary}): ${description}`

- In principle, commit messages should use all lowercase letters. Except for proper nouns or variables.
- type:
  - **feat** (feature)
  - **fix** (bug fix)
  - **doc** (documentation)
  - **style** (formatting, missing semi colons, …)
  - **refactor**
  - **test** (when adding missing tests)
  - **chore** (maintain)

- summary: Summarise the description in a few words.
- description: The description of the commit.

**Examples** 

| Branches                 | Commit                              |
| ------------------------ | ----------------------------------- |
| BUG-LOGO-ALIGNMENT-ISSUE | doc(swagger): make swagger useable  |
| WIP-IOC-CONTAINER-ADDED  | feat(login): finish login function. |


## Development Change Logs

**Documentation Change Log Format**: `{DataTime}` - `{Owner}` - `{Description}`
**Development Log Format**: `{User stories id}` - `{Filename}` - `{Description}`

#### Sprint 1 Change Logs

**Documentation Change Log**:
- Tue 22 Mar 2022 - Zhidong Zhou - Setup Repository Structuring follow the given guideline
- Sun 22 Mar 2022 - Jialiang Cheng - User Stories v1.0
- Sun 22 Mar 2022 - Yuanwei Mao - Requirement Background
- Sun 22 Mar 2022 - Lingjun Meng - Add Motivational Model v1.0
- Sun 27 Mar 2022 - Ruiying Feng - Requirement Persona v1.0
- Sun 27 Mar 2022 - Zhidong Zhou - Add Requirements Analysis Related Documentations in to `docs/`
- Sun 27 Mar 2022 - Jialiang Cheng - Add some documents in to `docs/`
- Sun 27 Mar 2022 - Zhidong Zhou - Setup & Manage Product Backlog: Task Management Tool (Github Project)
- Sun 27 Mar 2022 - Zhidong Zhou - Add User Stories v1.0
- Sun 27 Mar 2022 - Jialiang Cheng - Add Motivational Model `v1.0

#### Sprint 2 Change Log

**Documentation Change Log**:
- Sun 30 Apr 2022 - Jialiang Cheng - Update Motivational Model v2.0
- Sun 30 Apr 2022 - Zhidong Zhou - Update User Stories v2.0
- Sun 30 Apr 2022 - Yuanwei Mao - Add Test Case v1.0
- Sun 30 Apr 2022 - Ruiying Feng - Add Development Technology v1.0
- Sun 30 Apr 2022 - Lingjun Meng - Add Development Deployment v1.0

**Development Log**: 

- [EP01-01](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/31) - Account Register
  - `LoginController.java/UserService.java/UserDao.java` - Add register api
- [EP01-02&03](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10) - Account login/logout
  - `LoginController.java/UserService.java/UserPartner.java` - Update UserPartner.java to make user's password secret.
  - `LoginController.java/UserService.java/UserDao.java` - Add Logout api
- [EP02-07&08](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/9) - Make Garmin API Connection
  - `GarminPushController.java/ActivityService.java/AcvityServiceImpl.java/Activity.java` - Receive Activity and activity detail from garmin.
- [EP02-09](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/30) - Manage Garmin API Connection
  - `OAuthController.java` - Get activity token from garmin

**Acceptance Testing Log**:
- [Acceptance Testing: EP01-01 Account Register](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/20)
- [Acceptance Testing: EP01-02&03 Account login & Logout](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/18)
- [Acceptance Testing: EP02-07&08 Garmin API Connect & Disconnect](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/13)
- [Acceptance Testing: EP02-09 Options (Yes/No) for Garmin API Connection](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/48)

> Non-completed tasks:
> - [EP01-04](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/42) - Retrieve Account Password
> - [EP01-05](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/43) - Reset Account Password

#### Sprint 3 Change Log

**Documentation Change Log**:
- Sun 30 May 2022 - Zhidong Zhou - Add Acceptance Criteria v1.0
- Sun 30 May 2022 - Jialiang Cheng - Add Acceptance Test v1.0
- Sun 30 May 2022 - Yuanwei Mao - Add Test Case v1.0
- Sun 30 May 2022 - Ruiying Feng - Add Handover Documentation v1.0
- Sun 30 May 2022 - Lingjun Meng - Add Deployment Guidline v1.0
- Sun 30 May 2022 - Yuanwei Mao - Update Test Case v2.0

**Development Log**: 
- [EP03-10](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/14) - Activity Dashboard (All Activity Datas)
- [EP03-11](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/44) - Activity Details (Detail Data for each Activity)

**Acceptance Testing Log**:
- [Acceptance Testing: EP03-10 Activity Dashboard Page](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/11)
- [Acceptance Testing: EP03-11 Activity Detail Page](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/12)

> Remain Uncompleted tasks:
> - [EP01-04](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/42) - Retrieve Account Password
> - [EP01-05](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/43) - Reset Account Password


#### Sprint 4 Change Log

**Documentation Change Log**:
- Thu 09 Jun 2022 - Yuanwei Mao - Add Handover v1.0
- Thu 09 Jun 2022 - Lingjun Meng - Add Deployment Guideline v1.0
- Thu 09 Jun 2022 - Jialiang Cheng - Finalize Development Change Log v1.0
- Thu 09 Jun 2022 - Zhidong Zhou - Final Presentation v1.0
- Thu 09 Jun 2022 - Zhidong Zhou - Release History v1.0
- Thu 09 Jun 2022 - Ruiying Feng - User Guide v1.0


## About Us

**Year**: 2022

**Workshop**: COMP90082/U/1/SM1/W01/09

**Supervisor**: [Hanna Navissi](hanna.navissi@unimelb.edu.au)

**Team Members**: 

| Name           | ID      | Email                                 |
| -------------- | ------- | ------------------------------------- |
| Zhidong Zhou   | 1132353 | zhidongz@student.unimelb.edu.au       |
| Lingjun Meng   | 1157480 | lingjunm@student.unimelb.edu.au       |
| Yuanwei Mao    | 1185135 | yuamao@student.unimelb.edu.au         |
| Jialiang Cheng | 1251403 | jialiang.cheng@student.unimelb.edu.au |
| Ruiying Feng   | 948831  | ruiyingf@student.unimelb.edu.au       |