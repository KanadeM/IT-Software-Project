| Epic | User Story ID | Acceptance Criteria ID | Given | When | Then |
| :--- | :------------ | :--------------------- | :---- | :--- | :--- |
|      |               |                        |       |      |      |



# US01
#### Description
> Acceptance Test for Account Register

#### [User Story (Confluence): EP01-US01](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                                         | Story ID | Issue ID                                                         | Issue Type       | As      | I Want To                              | So That                            | Size Estimation | MoSCoW Priority | Justification                                                                                                                                                                             |
| :------------------------------------------- | :------- | :--------------------------------------------------------------- | :--------------- | :------ | :------------------------------------- | :--------------------------------- | :-------------- | :-------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | 01       | [#31](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/31) | Account Register | Athlete | I want to be able to create my account | I can have a Coaching-mate account | Medium          | Must have       | *Size estimation*: require align only useful information to be required for register. And Input validation for security reason.*MoSCoW priority*: Athlete must have an account for login. |



#### [Acceptance Criteria (Confluence): EP01-US01](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)
@j79cheng 

| Epic                                         | User Story ID | Acceptance Criteria ID | Given                                                      | When                                                       | Then                                                                                             |
| :------------------------------------------- | :------------ | :--------------------- | :--------------------------------------------------------- | :--------------------------------------------------------- | :----------------------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | US01          | AC01                   | there is a registration form                               | I try to create a new Coaching-Mate account                | I can fill the required Information and submit the registration form for obtain the new account. |
| **Epic-01 Coaching-Mate Account Management** | US01          | AC02                   | I want notification message about where I make the mistake | I fill some invalid information into the registration form | I can correct invalid information to a valid one.                                                |

#### [Acceptance Test (Confluence): AC01](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)

@ZhidongZhou 

- AC01 
    - [x] 1.1 Jeremy visit Coaching-Mate website and Click "Sign-in" button;
    - [x] 1.2 Jeremy is redirected to the registration form;
    - [x] 1.3 Jeremy get all required registration information correct and submit the form;
    - [x] 1.4 Jeremy is redirected to the "login" page on success of registration.
- AC02 
    - [x] 2.1 Jeremy enter an incorrect format of "Name" and receive error message;
    - [x] 2.2 Jeremy enter an incorrect format of "Password" and receive error message;
    - [x] 2.3 Jeremy enter an incorrect format of "Email" and receive error message.

#### [Acceptance Test (Issue 18): AC01 & AC02](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/18)

#### Review
@KanadeM 



# US02 & 03


#### Description
> Acceptance Test for Account Login & Logout

#### [User Story (Confluence): EP01-US02 & US03](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                                         | Story ID | Issue ID                                                         | Issue Type           | As      | I Want To                                  | So That                           | Size Estimation | MoSCoW Priority | Justification                                                                                                                                                   |
| :------------------------------------------- | :------- | :--------------------------------------------------------------- | :------------------- | :------ | :----------------------------------------- | :-------------------------------- | :-------------- | :-------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | 02       | [#10](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10) | Account login/logout | Athlete | I want to be able to login into my account | I can use the watch personally    | Medium          | Must have       | *Size estimation*: user token is required, and user database require be well connected.*MoSCoW priority*: Athlete must be able to login & logout their account. |
| **Epic-01 Coaching-Mate Account Management** | 03       | [#10](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10) | Accout logout        | Athlete | I want to be able to logout of my account  | I can change to another's account | Medium          | Must have       | *Size estimation*: user token is required, and user database require be well connected.*MoSCoW priority*: Athlete must be able to login & logout their account. |

#### [Acceptance Criteria (Confluence): EP01-US02 & US03](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)
@j79cheng 

| Epic                                         | User Story ID | Acceptance Criteria ID | Given                                                                     | When                                         | Then                                                                                 |
| :------------------------------------------- | :------------ | :--------------------- | :------------------------------------------------------------------------ | :------------------------------------------- | :----------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | US02          | AC03                   | there is a login window                                                   | I try to login with my Coaching-Mate account | I can successfully login with my account, and redirect to the Dashboard (Main Page). |
| **Epic-01 Coaching-Mate Account Management** | US02          | AC04                   | there is a notification message to warn the login credential is incorrect | I enter the wrong account name or password   | I can try to re-enter a valid login credential.                                      |
| **Epic-01 Coaching-Mate Account Management** | US03 | AC05 | there is a logout button | I try to logout from Coaching-Mate account | I can successfully logout, and redirect to the Login Page. |

#### [Acceptance Test (Confluence): AC03, AC04 & AC05](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)

@ZhidongZhou 

- AC03
    - [x] 3.1 Jeremy can enter account name for login in login form;
    - [x] 3.2 Jeremy can enter password for login in login form;
    - [x] 3.3 Jeremy can successfully login its account with correct login credential;
    - [x] 3.4 Jeremy is redirected to the "Home" Page on success of login.
- AC04
    - [x] 4.1 Jeremy get error message with invalid login credential.
- AC05
    - [x] 5.1 Jeremy can click "logout" button to log out it's Coaching-Mate account;
    - [x] 5.2 Jeremy is redirected to the "login" page after logout.

#### [Acceptance Test (Issue 10): AC03, AC04 & AC05](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/10)

#### Review

@KanadeM 


# US04
#### Description
> Retrieve password

#### [User Story (Confluence): EP01-US04](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)


| Epic                                         | Story ID | Issue ID                                                         | Issue Type                | As      | I Want To                                 | So That                                             | Size Estimation | MoSCoW Priority | Justification                                                                                                                                                    |
| :------------------------------------------- | :------- | :--------------------------------------------------------------- | :------------------------ | :------ | :---------------------------------------- | :-------------------------------------------------- | :-------------- | :-------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | 04       | [#42](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/42) | Retrieve Account Password | Athlete | I want to be able to retrieve my password | I can get my password back if I forgot              | Small           | Should have     | *Size estimation*: easy to set up retrieve password function with registration email.*MoSCoW priority*: not affect the core process.                             |

#### [Acceptance Criteria (Confluence): EP01-US04](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)

@j79cheng 

#### [Acceptance Test (Confluence): AC06 & AC07](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)

@ZhidongZhou 

#### [Acceptance Test (Issue ?): AC06 & AC07](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/)

#### Review 
@KanadeM 




# US05
#### Description
> Forgot password

#### [User Story (Confluence): EP01-US05](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                                         | Story ID | Issue ID                                                         | Issue Type                | As      | I Want To                                 | So That                                             | Size Estimation | MoSCoW Priority | Justification                                                                                                                                                    |
| :------------------------------------------- | :------- | :--------------------------------------------------------------- | :------------------------ | :------ | :---------------------------------------- | :-------------------------------------------------- | :-------------- | :-------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-01 Coaching-Mate Account Management** | 05       | [#43](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/43) | Reset Account Password    | Athlete | I want to be able to reset my password    | I can change update my password for security reason | Small           | Should have     | *Size estimation*: change password requires an email sent to user and user can then simply change their password.*MoSCoW priority*: not affect the core process. |

#### [Acceptance Criteria (Confluence): EP01-US05](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)

@j79cheng 

#### [Acceptance Test (Confluence): AC08 & AC09](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)

@ZhidongZhou 

#### [Acceptance Test (Issue ?): AC08 & AC09](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/)

#### Review 
@KanadeM 




# US07 & 08
#### Description
 > Connect and Disconnect to Garmin API


#### [User Story (Confluence): EP01-US07 & 08](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                              | Story ID | Issue ID                                                       | Issue Type                 | As      | I Want To                                                            | So That                                                               | Size Estimation | MoSCoW Priority | Justification                                                                                                                                                |
| :-------------------------------- | :------- | :------------------------------------------------------------- | :------------------------- | :------ | :------------------------------------------------------------------- | :-------------------------------------------------------------------- | :-------------- | :-------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Epic-02 Garmin API Connection** | 07       | [#9](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/9) | Make Garmin API Connection | Athlete | I want to connect my coaching mate account to Garmin                 | my Coaching-Mate account can get my Activity data from Garmin connect | Large           | Must have       | *Size estimation*: Many API connection related subtasks is required to be done.*MoSCoW priority*: Athlete must be able to connect Coaching-mate with Garmin. |
| **Epic-02 Garmin API Connection** | 08       | [#9](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/9) | Make Garmin API Connection | Athlete | I want to be able to disconnect my coaching mate account from Garmin | I am able to stop receiving data from Garmin connect                  | Large           | Should have     | *Size estimation*: only add one button for disconnection.*MoSCoW priority*: not affect the core process.                                                     |



#### [Acceptance Criteria (Confluence): EP02-US07 & 08](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)

@j79cheng 

| Epic                              | User Story ID | Acceptance Criteria ID | Given                        | When                                                   | Then                                                        |
| :-------------------------------- | :------------ | :--------------------- | :--------------------------- | :----------------------------------------------------- | :---------------------------------------------------------- |
| **Epic-02 Garmin API Connection** | US07          | AC10                   | there is a connect button    | I try to connect my Coaching mate account to Garmin    | I can receive activity data from the Garmin connect.        |
| **Epic-02 Garmin API Connection** | US08          | AC11                   | there is a disconnect button | I try to disconnect my Coaching mate account to Garmin | I can stop receiving activity data from the Garmin connect. |

#### [Acceptance Test (Confluence): AC10 & AC11](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)
@ZhidongZhou

- AC10
    - [x] 10.1 Maria has finished her login;
    - [x] 10.2 Maria visits the connection web page;
    - [x] 10.3 Maria clicks the connect button;
    - [x] 10.4 Maria connects the coaching mate account to Garmin successfully;
    - [x] 10.5 Maria views the activity data.
- AC11
    - [x] 11.1 Maria has finished her login;
    - [x] 11.2 Maria visits the connection web page;
    - [x] 11.3 Maria clicks the disconnect button;
    - [x] 11.4 Maria disconnects the coaching mate account to Garmin.

#### [Acceptance Test (Issue 13): AC10 & AC11](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/13)

#### Review 
@KanadeM 


# US09

#### Description
 > Agree or Disagree to Connect with Garmin API 

#### [User Story (Confluence): EP01-US09](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                              | Story ID | Issue ID                                                         | Issue Type                   | As      | I Want To                                                                                | So That                                                 | Size Estimation | MoSCoW Priority | Justification                                                                                                                                       |
| :-------------------------------- | :------- | :--------------------------------------------------------------- | :--------------------------- | :------ | :--------------------------------------------------------------------------------------- | :------------------------------------------------------ | :-------------- | :-------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-02 Garmin API Connection** | 09       | [#30](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/30) | Manage Garmin API Connection | Athlete | I want to be able to choose whether to connect my coaching mate account to Garmin or not | I am able to manage my account’s connection selectively | Small           | Should have     | *Size estimation*: Before connection give user a button to exit, if they want make connection later.*MoSCoW priority*: not affect the core process. |

#### [Acceptance Criteria (Confluence): EP02-US09](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)

| Epic                              | User Story ID | Acceptance Criteria ID | Given                     | When                                                                   | Then                                            |
| :-------------------------------- | :------------ | :--------------------- | :------------------------ | :--------------------------------------------------------------------- | :---------------------------------------------- |
| **Epic-02 Garmin API Connection** | US07          | AC12                   | there is a connect window | I click the agree button to connect my Coaching mate account to Garmin | I can get my account's connection on this page. |

#### [Acceptance Test (Confluence): AC12 & AC13](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)
@j79cheng 

- AC12
    - [ ] 12.1 Maria has clicked the connection button and has viewed the activity data;
    - [ ] 12.2 Maria receives the webpage with agree or disagree buttons;
    - [ ] 12.3 Maria clicks the agree button;
    - [ ] 12.4 Maria enters the Garmin page by her coaching mate account.
- AC13
    - [ ] 13.1 Maria has entered the Garmin page;
    - [ ] 13.2 Maria clicks the disagree button;
    - [ ] 13.3 Maria leaves the Garmin page.


#### [Acceptance Test (Issue 48): AC12](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/48)

#### Review 
@KanadeM 

# US10

#### Description
> Acceptance Test for Activity Dashboard

#### [User Story (Confluence): EP01-10](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)
| Epic                              | Story ID | Issue ID                                                         | Issue Type                   | As      | I Want To                                                                                | So That                                                 | Size Estimation | MoSCoW Priority | Justification                                                                                                                                       |
| :-------------------------------- | :------- | :--------------------------------------------------------------- | :--------------------------- | :------ | :--------------------------------------------------------------------------------------- | :------------------------------------------------------ | :-------------- | :-------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-03 View Synchronised Activity Data**       | [US10](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/1) | [#14](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/14) | View Activity Data can from Coaching-Mate Activity Dashboard Page | Athlete                                                      | I want all my activity data from Garmin been shown on the Coaching-mate Dashboard | I can view all my activities from the Coaching-mate Dashboard | Medium    | Must have                                                    | *Size estimation*: We need collect Activity data (JSON format) from Garmin, and make this sync with our database & then show on the frontend, which is a complicated task.*MoSCoW priority*: Athlete Must be able to see their Activities after connection. |

#### [Acceptance Criteria (Confluence): EP03-US10](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)
@ZhidongZhou 

| Epic                                        | User Story ID | Acceptance Criteria ID | Given                               | When                                 | Then                                                                                    |
| :------------------------------------------ | :------------ | :--------------------- | :---------------------------------- | :----------------------------------- | :-------------------------------------------------------------------------------------- |
| **Epic-03 View Synchronised Activity Data** | US10          | AC14                   | there is an activity dashboard page | I try to view all my activities data | I can view all my activities data clearly and correctly on the coaching-mate dashboard. |

#### [Acceptance Test (Confluence): AC14](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)
@j79cheng 
- [ ] AC-14.1 Tom finishes his activity
- [ ] AC-14.2 Tom opens his dashboard
- [ ] AC-14.3 Tom views all activity records on dashboard.


#### [Acceptance Test (Issue 11): AC14](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/11)

#### Review 
@KanadeM 


# US11
#### Description
> Acceptance Test for Activity Detail Page

#### [User Story (Confluence): EP01-11](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/User+Stories)

| Epic                              | Story ID | Issue ID                                                         | Issue Type                   | As      | I Want To                                                                                | So That                                                 | Size Estimation | MoSCoW Priority | Justification                                                                                                                                       |
| :-------------------------------- | :------- | :--------------------------------------------------------------- | :--------------------------- | :------ | :--------------------------------------------------------------------------------------- | :------------------------------------------------------ | :-------------- | :-------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Epic-03 View Synchronised Activity Data** | [US11](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/44) | [#44](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/44) | View Activity Detail from Coaching-Mate Activity Detail Page | Athlete                                                      | I want detailed activity data for each single activity is shown on an Activity Detail Page. | I can view detailed activity data for specific activity from the Activity Detail Page. | Large                                                        | Must have | *Size estimation*: More complicated as different type of Activity have different contents of data.*MoSCoW priority*: Athlete Must be able to see each Activity in detail. |                                                              |

#### [Acceptance Criteria (Confluence): EP03-US11](https://confluence.cis.unimelb.edu.au:8443/pages/resumedraft.action?draftId=101454231&draftShareId=24924477-367f-43bb-abbf-df560a51464d&)
@ZhidongZhou 
| Epic                                        | User Story ID | Acceptance Criteria ID | Given                                                        | When                                             | Then                                                         |
| :------------------------------------------ | :------------ | :--------------------- | :----------------------------------------------------------- | :----------------------------------------------- | :----------------------------------------------------------- |
| **Epic-03 View Synchronised Activity Data** | US11          | AC15                   | that I have finished my connect to the account and click a single activity | I try to view the detail for a specific activity | I can view the detail clearly and correctly for a specific activity on the activity detail page. |
| **Epic-03 View Synchronised Activity Data** | US11          | AC16                   | that I have finished my connect to the account and click a single activity | I try to get my activity detailed data           | the data is easy to understand                               |

#### [Acceptance Test (Confluence): AC15 & AC16](https://confluence.cis.unimelb.edu.au:8443/display/COMP900822022SM1GA/Acceptance+Test)
@j79cheng 

- AC15
    - [ ] 15.1 Tom finishes his activity; 
    - [ ] 15.2 Tom opens his dashboard;                                   
    - [ ] 15.3 Tom click the newest activity;                             
    - [ ] 15.4 Tom views the newest activity's details;                   
    - [ ] 15.5 Tom get all his activity information from the detail page. 
- AC16
    - [ ] 16.1 Tom finishes his activity; 
    - [ ] 16.2 Tom opens his dashboard;                                   
    - [ ] 16.3 Tom click the newest activity;                             
    - [ ] 16.4 Tom views the newest activity's details;                   
    - [ ] 16.5 Tom find the activity information is easy to understand.   

#### [Acceptance Test (Issue 12): AC15 & AC16](https://github.com/COMP90082SM12022/GA-Boxjelly/issues/12)

#### Review 
@KanadeM 