


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
| Sprint Goal | Optimize product funnel and BE code to improve view rate | 
| Highlights | Beginning of the Sprint - We try reduce our technical debt payout effort to 30% per sprint starting from this sprint - The team is exploring on how to track chat and watch duration - We start to continue learning resource development again Mid sprint - A/B Testing for onboarding journey is starting, need to wait for 2 weeks to see impact on retention - Mentoring pods updating the mentoring service blueprint - App roll-out updated to 75% | 
| Lowlights (if any) | Beginning of the Sprint - UAT for Telkomsel bundling is still ongoing - Team throughput will be lower for the next few until we have new members because the team are now being more mindful on non-functional requirement when building new feature Mid Sprint - Design A/B Test cannot be done in parallel to minimize conflict and skewed of insight - | 
| Stream Dependency (if any) | N/A | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| ⭐️ MAU view rate |  **Before sprint** : - Latest version: 43.1% (-0.5p) - Overall: 34.2% (-2p)  **Mid sprint** : - Latest version: N/A - Overall: N/A | <ul><li>The current home page design is not ideal yet for both first time and existing. - Our current onboarding flow has ~17% drop off resulting longer lead time from register to view

</li></ul> | Improve first time view | ≧50% | Running A/B test on onboarding and new home page design once the app roll out to 25% | CONTENTPurple | IN PROGRESS |  |  | 
| Weekly avg. viewed per user |  **Before sprint** : - Latest version: 7.2 (-2p) - Overall: 8.4 (-1.6)  **Mid sprint** : - Latest version: 6.8 (-1.4p) - Overall: 7.4 (-1p) | Our BE hasn't handle case where the content in a module is updated causing wrong signal of module completion/progress after content team update their published content | Address technical debt that affect user progress table | ≧15 | [Refactor end point for user progress table and DB architecture](https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12/backlog?atlOrigin=eyJpIjoiZjNhNDIzMzQyZmFjNDZiMTgyM2M1ZTk2NzE2YmY4ZDMiLCJwIjoiaiJ9) | CONTENTPurpleTECH DEBTYellow | IN PROGRESS |  |  | 
| Learning session length (view) |  **Before sprint** - New version (v.1.3.9): 4.8 min - Previous version (≦1.3.8): 4.6 min  **Mid-Sprint** - New version (v.1.3.9): 4.8 min - Previous version (≦1.3.8): 4.6 min | Based on users research, video content alone won't keeps users coming back. Supplementary supplement will help users to help users take a next actions on their learning | Improve app usage frequency | ≧ 10 min | [Support on multiple file format like PDF, GDrive, and Website](https://kuncie.atlassian.net/browse/KEY-3) (This sprint we start on small task first) | CONTENTPurple | IN PROGRESS |  |  | 
| ANR |  **Before sprint** : - Latest version 0.33% - Previous version: 0.20%  **Mid sprint** : - Latest version 0.41% - Previous version: 0.08% | <ul><li>CDN from from telkomsel akamai had shown slow response time for the past few days (2.65s) 

</li><li>Codec processing issue causing app to freeze in low end device

</li></ul> | Reduce ANR to be in peer indsutry | <ul><li>Maintain below threshold 0.47%

</li><li>Beat peer median below 0.12%

</li></ul> | [Addressing top 2 issue in firebase performance](https://munaelevate.atlassian.net/browse/KEY-459?atlOrigin=eyJpIjoiNjg1MGY2NDViZDVmNDZjNTg5MWIyYmNmN2M3Nzc3OGIiLCJwIjoiaiJ9) | TECH DEBTYellowPLATFORMPurple | IN PROGRESS |  |  | 
| Crash Rate |  **Before sprint** : - Latest version: 0.61% - Previous version: 0.43%  **Mid sprint** : - Latest version: 0.4% - Previous version: 0.6% | The new versions seems to be not stable on low end or non snapdragon device causing crash on users who have those devices | Reduce the crashrate to be on peer industry number | <ul><li>Maintain below threshold 1.09%

</li><li>Beat peer median below 0.38%

</li></ul> | [Addressing top 2 issue from Sentry](https://munaelevate.atlassian.net/browse/KEY-455) | PLATFORMPurpleTECH DEBTYellow | IN PROGRESS |  |  | 
| Supporting GTM metric on acquisition | Refer to correspondent stream | refer to corespondent stream | Leverage Telkomsel channel and assets to help meets the acquisition target by the end of the year | 39K users/month - 97K users/month | UAT is planned this sprint with Telkomsel ([Telkomsel data bundling](https://munaelevate.atlassian.net/browse/KEY-4?atlOrigin=eyJpIjoiODEwMzE4OGU0ZWUzNDU2ZDliYjBlZGNkZWVjNGFhYWUiLCJwIjoiaiJ9)) | acquisitionRedpartnershipPurple | IN PROGRESS |  |  | 
| Lead time to book mentor | 2 days | The mentoring booking process right now is barebone and manual | Improve the mentor booking process and operational efficiency | less than 1 hour | [Mentor SaaS integration development](https://munaelevate.atlassian.net/browse/KEY-15?atlOrigin=eyJpIjoiMWY5MGM0YWM5MzJkNDIxYWE3NjU0YjFkYTRkNzYyMjgiLCJwIjoiaiJ9) @Muhammad Hilman to update: 1. All the BE items had been developed and tested. The BE items are ready for release 2. FE team is still in the integration phase with the BE items. We are optimistic that all the items in Happy Flow is going to be completed by this sprint 3. Need e-mait template from Design team 4. Design team is finalizing the flow for Cancellation and Rescheduling | platformYellowmentoringBlue | IN PROGRESS |  |  | 


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
