## In Scope
The Garmin API project will focus on how Users' data from its workout sessions is being synchronized between devices and dashboards through the Garmin API.

| StoryID | User    | Story/Scenario                                                                                                                                                                               | MoSCoW Priority | Requirement Type |
| :------ | :------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------- | :--------------: |
| 01      | Athlete | As an athlete, I want to log in to my Garmin account, so that I can access and manage my workouts from all my devices.                                                                       | Must            |      Login       |
| 02      | Athlete | As an athlete, I want to connect the workout Dashboard Application with the Garmin API, so that Garmin can help me integrate my workout data.                                                | Must            |  API Connection  |
| 03      | Athlete | As an athlete, I want to manage the configurations of my Garmin account, so that I can manage where my data is being collected and other preferences.                                        | Should          |     Settings     |
| 04      | Athlete | As an athlete, I want to view my workout data on all my devices (Wareable Devices & Dashboard Applications), so that I can easily track my workout progress.                                 | Must            | Synchronization  |
| 05      | Athlete | As an athlete, I want to report any mistakes (Duplicate/Wrong data) about my workout session, so that I can get them corrected or deleted.                                                   | Should          |  Report Mistake  |
| 06      | Athlete | As an athlete, I want to change the status (In Progress, Pause & Done) of my workout session, so that my workout session status can be checked by my coach (No Need to Upload Pause Status). | Could           |  Workout Status  |
| 07      | Athlete | As an athlete, I want to receive notifications on my watch whenever my coach releases a workout task to me, so that I will not miss any workout task assigned to me.                         | Could           |   Notification   |
| 08      | Athlete | As an athlete, I want to share or comment (maybe like a workout session) on my friend's workout session, so that I can chat and socialize with my friends.                                   | Could           |      Social      |
| 09      | Athlete | As an athlete, I want to view the Heat Map of my workout session.                                                                                                                            | Could           |     Heat Map     |
| 10      | Coach   | As a coach, I want to log in to my Garmin account, so that I can access and manage my athlete workout sessions from all my devices.                                                          | Must            |      Login       |
| 11      | Coach   | As a coach, I want to connect the workout Dashboard Application with the Garmin API, so that Garmin can help me integrate my athlete workout data.                                           | Must            |  API Connection  |
| 12      | Coach   | As a coach, I want to release workout tasks from the dashboard to my Athletes, so that athletes can manage to start their workout.                                                           | Must            |      Create      |
| 13      | Coach   | As a coach, I want to manage the configurations of my Garmin account, so that I can manage which data is being collected and other preferences.                                              | Should          |     Settings     |
| 14      | Coach   | As a coach, I want to view the real-time data of all my Athletes, so that I can easily track their progress.                                                                                 | Must            | Synchronization  |
| 15      | Coach   | As a coach, I want to report any mistake (Duplicate/Wrong data) about the Athlete's workout data, so that I can get them corrected or deleted.                                               | Should          |  Report Mistake  |
| 16      | Coach   | As a coach, I want to receive notifications on the Dashboard whenever my Athlete starts or finish their workout task so that I can update their training plan on time.                       | Could           |   Notification   |
| 17      | Coach   | As a coach, I want to share or comment (maybe like a workout session) on my Athlete's workout sessions, so that I can better motivate them.                                                  | Could           |      Social      |
| 18      | Coach   | As a coach, I want to view the Heat Map of Athlete's workout sessions, so then I can gain a visualized understanding of their exercise performance.                                          | Could           |     Heat Map     |


## Out Scope
Our Garmin API project will not be working on adding new features such as instant messaging or adding workout templates.

| StoryID | User    | Story/Scenario                                               | MoSCoW Priority |
| :------ | :------ | :----------------------------------------------------------- | :-------------- |
| 01      | Athlete | As an athlete, I want to chat (Voice all/message) with my coach and friends on Garmin, so that I can exchange workout experiences with them. | Could           |
| 02      | Coach   | As a coach, I want to design and save a new workout template, so when I have a new athlete, so that I can send her the workout template I have set up. | Could           |

