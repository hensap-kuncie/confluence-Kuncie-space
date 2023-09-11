


## Product Design and Research

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| MAU View rate |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 


## Product Management

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal | <ul><li>Addressing technical debts, improving app vitals, and service monitoring 

</li><li>- Part 2 (>50%) 

</li><li>- Mentor booking development (~25%) 

</li><li>- Jira Active sprint Kanban 

</li></ul>[https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12](https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12) | 
| Highlights | <ul><li>A/B Testing: 1) New home page design and 2) Onboarding journey 

</li><li>- Several new events registration: 1) close confirmation 2) module completion

</li></ul> | 
| Lowlights (if any) | Some developments are paused or slowing down as we focusing on addressing technical debts and improving app vitals. Impacted initiatives: - Learning resources (paused) - FE development on automated mentor booking (slow down) - Event registration: 1) chat 2) video watch duration | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| ⭐️ MAU view rate |  **Before sprint** : - Latest version: 44% (-3p) - Overall: 37.7% (+0p)  **Mid sprint** : - Latest version: 43% (-1p) - Overall: 35% (-2p) | The current home page design is not ideal yet for both first time and existing. | Improve first time view | ≧50% | <ul><li>Develop remote config for 1) 

</li></ul>[new design](https://munaelevate.atlassian.net/browse/KEY-486?atlOrigin=eyJpIjoiNzE3ZGRjNzllZTA0NDQ3Y2FhNTgxOWI5MTljMWI4ZGYiLCJwIjoiaiJ9) and 2) [onboarding journey A/B testing](https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12/backlog?atlOrigin=eyJpIjoiZjNhNDIzMzQyZmFjNDZiMTgyM2M1ZTk2NzE2YmY4ZDMiLCJwIjoiaiJ9) | contentPurple | not startedBlue |  |  | 
| Weekly avg. viewed per user |  **Before sprint** : - Latest version: 9.5 (+5%) - Overall: 10 (+0%)  **Mid sprint** : N/A - Latest version: 9.6 (+1.72%) - Overall: 10.2 (+2.72%) | Our BE hasn't handle case where the content in a module is updated causing wrong signal of module completion/progress after content team update their published content | Address technical debt that affect user progress table | ≧15 | <ul><li>

</li></ul>[Refactor end point for user progress table and DB architecture](https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12/backlog?atlOrigin=eyJpIjoiZjNhNDIzMzQyZmFjNDZiMTgyM2M1ZTk2NzE2YmY4ZDMiLCJwIjoiaiJ9) | contentPurpletech debtYellow | in progress |  |  | 
| ANR |  **Before sprint** : - Latest version 0.33% - Previous version: 0.20%  **Mid sprint** : - Latest version 0.41% - Previous version: 0.08% | <ul><li>CDN from from telkomsel akamai had shown slow response time for the past few days (2.65s) - Codec processing issue causing app to freeze in low end device

</li></ul> | Reduce ANR to be in peer indsutry | <ul><li>Maintain below threshold 0.47% - 

</li><li>Beat peer median below 0.12%

</li></ul> | <ul><li>

</li></ul>[Addressing top 5 issue in firebase performance ](https://munaelevate.atlassian.net/browse/KEY-459?atlOrigin=eyJpIjoiNjg1MGY2NDViZDVmNDZjNTg5MWIyYmNmN2M3Nzc3OGIiLCJwIjoiaiJ9)- Liase with harmonic to getbetter understanding on Akamai and CDN | tech debtYellowplatformRed | in progress |  |  | 
| Crash rate |  **Before sprint** : - Latest version: 0.61% - Previous version: 0.43%  **Mid sprint** : - Latest version: 0.62% - Previous version: 0.33% | The new versions seems to be not stable on low end or non snapdragon device causing crash on users who have those devices | Reduce the crashrate to be on peer industry number | <ul><li>Maintain below threshold 1.09% - 

</li><li>Beat peer median below 0.38%

</li></ul> | [Addressing top 5 issue from Sentry](https://munaelevate.atlassian.net/browse/KEY-455) | platformRedtech debtYellow | in progress |  |  | 
| Supporting GTM metric on acquisition | Refer to correspondent stream | refer to corespondent stream | Leverage Telkomsel channel and assets to help meets the acquisition target by the end of the year | 39K users/month - 97K users/month | UAT is planned this sprint with Telkomsel ([Telkomsel data bundling](https://munaelevate.atlassian.net/browse/KEY-4?atlOrigin=eyJpIjoiODEwMzE4OGU0ZWUzNDU2ZDliYjBlZGNkZWVjNGFhYWUiLCJwIjoiaiJ9)) | acquisitionPurplepartnership | in progress |  |  | 
| Lead time to book mentor | 2 days | The mentoring booking process right now is barebone and manual | Improve the mentor booking process and operational efficiency | less than 1 hour | [Mentor SaaS integration development](https://munaelevate.atlassian.net/browse/KEY-15?atlOrigin=eyJpIjoiMWY5MGM0YWM5MzJkNDIxYWE3NjU0YjFkYTRkNzYyMjgiLCJwIjoiaiJ9) @Muhammad Hilman to update: 1. From the BE side the development is expected to be completed in this sprint. 2. Some of the BE Stories i.e. Get Availability and Book Mentor Session has been completed, the former has passed the QA and the later failed which currently is being fixed. 3. The progress from FE is currently still ongoing, where currently FE focus on completing the rest of the stories and integration. The progress was delayed due to tasks on tech debt last sprint. 4. The progress above reflects only the happy flow where the Rescheduling and Cancellation feature is due to be developed in the next sprint. | platformYellowmentoringBlue | in progress |  |  | 
|  |  |  |  |  |  |  |  |  |  | 


## Engineering

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
|  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 




## Content

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
|  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 


## GTM

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
|  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 


## Talent Acquisition

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
|  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 


## Venture Ops and General Management

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal |  | 
| Highlights |  | 
| Lowlights (if any) |  | 
| Stream Dependency (if any) |  | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
|  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  | 





*****

[[category.storage-team]] 
[[category.confluence]] 
