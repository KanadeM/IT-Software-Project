## 稿子

#### ZHIDONGZHOU [2分钟]

1. 主页

   - Hi, this is the team **GA-BoxJelly**. 
2. Outline

   1. This presentation is about the **Garmin API project** for the **Coaching Mate Web Application**. 
   2. We will first <u>Briefly talk about</u> the **Background** of our project.
   3. Next, we will explain what **Technology** we used for our project and how we made **Deployment**.
   4. Then our Development leader will make a quick **DEMO** of our development outcome.
   5. After that, we will <u>summarise what has been completed</u> regarding our project requirements and our scope.
   6. And lastly, we will provide detail of how we planned for our final **Handover**.
3. Backgroud

   - Okay, First, let's look at what our project's all about? 
4. Coaching Mate
   - The **CoachingMate** is a system for the coach to deliver training sessions to their athletes. And it's now we are specifically required to enable Athletes to review all their Activities and Activity Details through Coaching Mate Web Application.
5. GARMIN
   - And **Garmin Connect** is the tool for Tracking, Analyzing and Sharing health and fitness activities from **Wearable Devices**. So Athletes with Devices like **Garmin Watch** will have their activity data sync to the **Garmin Connect**. And they provide an API that enables us to access those activity data.
6. Project Goal
   - So, the **GOAL** of our project is about **data integration** with **Garmin API** and syncing the Activity data to the **Coaching-Mate Dashboard**.
   - And our **Coaching-Mate** project is NOT built from scratch, and we are working on the code from the Previous **Garmin API Project**. So our main focus is to maintain and improve the existing platform. And we need to guarantee the data integration from GARMIN and ensure the dashboard display and retrieve the list of activity and activity details from **Garmin Connect**.
7. Next, Yuanwei will introduce the **Technology stack** used in our project and how our product is **Deployed**.

#### YUANWEIMAO

8. Now I will introduce the **Technology** we used in our development.
   - We use `Spring Boot` as the backend framework for backend development because it is suitable for rapid development.
   - We use `MongoDB` as the database because in the early stage of the project, as the database structure is <u>uncertain</u>, `MongoDB` gives us the <u>flexibility</u> to make a change along the way.
   - And for the `Frontend`, according to the client's requirements, we used `React` framework specifically.


9. And we have made some major improvement on `API`:
   - In the previous code, we had to repeat the same request every time. This method is troublesome when coding and needs to be modified in each file if there are changes, which is not a good practice. 
   - Our development encapsulates all requests in the same format and adds necessary specifications.
   - For example, each `Request` must have a token, and if it can not <u>log in</u>, it will return an empty string. 
   - And we need to verify every `Response`. If the status code is not 200, an error message will be displayed directly to the user.
   - Also, in the previous code, we need a new `Response` with specific `parameters` every time to return to the Frontend, which is inconvenient. 
   - And it is not a good choice to throw an exception to the client without exception handling. 
   - Our team update the code to process and return all `Requests` <u>uniformly</u>. And the format is fixed, consisting of `statusCode`, `message`, and `data`. 
   - And our new Frontend can perform <u>global processing</u> as long as the status code is not `200`. 
   - And all the exceptions will be handled before being displayed to the user.
   - And for the testing, our team use `JUnit` for unit testing. And `swagger` to test the API.
10. And for the **Deployment**:
    - We use `Heroku` to deploy both our Frontend and Backend and Lingjun will now make a DEMO based on that.

#### YUANWEIMAO (1)

8. Now I will introduce the **Technology** we used in our development.
   - We use `Spring Boot` as the backend framework for backend development because it is suitable for rapid development.
   - We use `MongoDB` as the database because in the early stage of the project, as the database structure is <u>uncertain</u>, `MongoDB` gives us the <u>flexibility</u> to make a change along the way.
   - And for the `Frontend`, according to the client's requirements, we used `React` framework specifically.
   - And for the testing, our team use `JUnit` for unit testing. And `swagger` to test the API.
9. And for the **Deployment**:
   - We use `Heroku` to deploy both our Frontend and Backend and Lingjun will now make a DEMO based on that.

#### LINGJUNMENG

10. This is the initial page for <u>log-in</u> and <u>registration</u>. 
    - *Imagine a new User Alice* first visits our website. 
    - Since activity data contains private information, and every User has individual statistical data, log-in and registration functions are necessary to distinguish Users. 
    - The first thing Alice has to do is register for an account. 
    - By clicking the **Register button**, Alice can enter the registration page. 
    - On the page, Alice has to enter her <u>Full Name</u>, <u>Username</u>, <u>Password twice</u> and <u>Email address</u>. 
    - And we will check the <u>password entered twice</u> is the same. 
    - If the <u>password</u> is not the same, Alice will not be able to register. 
    - In addition, registration will also be blocked if the <u>email address</u> is not in the correct format. 
    - If all the information is entered correctly, Alice can register the account. 
    
11. After signing up, Alice can **log in** to the website with the account and password. 
    - The Coaching-Mate uses the <u>Garmin API</u> to synchronize data and show the User his historical activities. 
    - So if Alice wants to see her activities, she needs to connect to Garmin first. 
    - By clicking **connect to Garmin button**. The page will redirect to Garmin connect. 
    - On this page, if Alice agrees to the policy, the coaching mate can <u>complete the connection</u> with Garmin.

12. Once the connection is completed, Alice can enter the **dashboard page** to see statistics about her activities. 
    1. If Alice wants to see all her <u>activities</u>, she can go to the activities page. 
    2. Since Alice does not have any activities now, the Dashboard displays the <u>default data</u>, and the activity list is also empty.

13. Now Alice wants to **start an activity**, she can use the Garmin watch to start a running, and when the running is complete, she can click end. 
    - At this time, the activity data will be <u>synchronized</u> to Garmin. Then Garmin will sync the data to our website. 
    - When we **refresh the page**, we can see the activity data now.
    - This is the <u>summary</u> of the activity. 
    - By clicking the activity, Alice can see the <u>detailed information</u> like max heart rate, Calories and temperature. At the same time, the Dashboard will also be updated.

14. Since Alice doesn't have enough activities, I'll use **another account** to show the Dashboard and other features. 
    - *Imagine another User, Bob.* He already has some activities and wants to see his activities and stats. 
    - Bob can **log in** to the website using his account and password.

15. The <u>top four blocks</u> show the number of activities for each type in history. 
    1. The <u>Line Chart</u> shows the expected and the actual activity time for the last week. 
    2. By Clicking the <u>top icon</u>, Bob can switch the line chart of different types. 
    3. The <u>bottom left chart</u> shows some brief statistics about different types. 
    4. The <u>Middle bottom graph</u> shows activity by percentage. 
    5. The <u>bottom right graph</u> shows daily Heart Rate Zones.

16. On the activities page, Bob can **filter** different activities by clicking the activity type icon in the upper right.
17. This is all of our demos; I will hand it back to Yuanwei to introduce the technical details.

#### YUANWEIMAO (2)

19. Next I will show our improvemnet on the `API`:

- In the previous code, we had to repeat the same request every time. This method is troublesome when coding and needs to be modified in each file if there are changes, which is not a good practice. 
- Our development encapsulates all requests in the same format and adds necessary specifications.
- For example, each `Request` must have a token, and if it can not <u>log in</u>, it will return an empty string. 
- And we need to verify every `Response`. If the status code is not 200, an error message will be displayed directly to the user.
- Also, in the previous code, we need a new `Response` with specific `parameters` every time to return to the Frontend, which is inconvenient. 
- And it is not a good choice to throw an exception to the client without exception handling. 
- Our team update the code to process and return all `Requests` <u>uniformly</u>. And the format is fixed, consisting of `statusCode`, `message`, and `data`. 
- And our new Frontend can perform <u>global processing</u> as long as the status code is not `200`. 
- And all the exceptions will be handled before being displayed to the user.

#### RUIYING FENG

20. In terms of **task fulfillment**. 

- All critical requirements now have been completed.
- As shown in today's **DEMO**, Our team now has **completed** the coaching-mate account management, including the Account <u>register</u>, Account <u>log-in</u>, and <u>log-out</u>.
- And the <u>reset</u> and <u>retrieve</u> account password function is not implemented because of the <u>limitation in development time</u>, and this function will *not affect the core process of our system*.
- Our project <u>API</u> is now well connected with Garmin.
- And the list of activity data is now synced to the coaching-mate website <u>dashboard</u> page. And also the <u>detailed activity data</u>.
- Our team did *not make any data analysis* of the activity data as this is outside of our project scope. *However, we provide some charts for activities data instead of showing them in raw format.*

#### JIALIANGCHENG

21. Hello, this is Jialiang. I am the scrum master of Boxjelly, and now I will talk about the final deliverable of the project. 

- We will **Handover** our project on June thirteen (6月13号), and mainly including 2 parts: **project code** and **project documentation**. 

22. The **code** will contain both the front-end and the back-end code. 

- We will provide completely refactored front-end code, based on the react framework as our client asked for. 
- As for the back-end code, it would be a new version that upgrades from the previous team. 

23. For **documentation**, we would have mainly 4 topics:
    1. The **Requirements Analysis** shows our thinking and understanding of the product.
    2. We have the **Development specification**, which talks about the technology and deployment we used.
    3. We provide the **Quality control** document, which contains the results of our thinking and practice on product testing.
    4. The user manual provides **Deployment Guidelines** and database structure to help later developers better understand what we have done.
24. That’s all for our presentation.

- All my team members and I really appreciate your listening.
- And now we are ready for **Questions**.[]()

