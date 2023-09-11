


## Product Design and Research

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal | <ul><li>Transaction (research & design) - Guided Pace Module - New figma structure - Profiling high retention users

</li></ul> | 
| Highlights | <ul><li>Support B2B experiment with landing page in [http://kuncie.com](http://kuncie.com)

</li></ul> | 
| Lowlights (if any) | <ul><li>Experiment guided pace learning

</li></ul> | 
| Stream Dependency (if any) | <ul><li>Growth for recruiting the survey participant via Kuncie IG feed & story

</li></ul> | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| MAU View rate | - | Content team already have list of titles but low confidence on prioritization. We are trying to capture users interest towards that. Also exploring new titles based on users interest | - | - | <ul><li>Understanding users interest towards proposed content titles - Explore future content titles

</li></ul> | contentPurple | in progress |  |  | 
| Retention rate | - | Analyzing users dependency towards Kuncie value and breaking it down per segment | - | - | Product Market Fit Survey Q4 2021 | contentPurple | doneYellow |  |  | 
| Retention | - | Understand what are the key drivers in Kuncie that made the 2% users stay until the D30. Understand what is the characteristic of this 2% of users who are still staying on the app until the D30? | - | - | Profiling high retention users (D30) | contentPurple | in progress |  |  | 
| Revenue | - | Understanding gamifications. Concept test buy > value or buy>points>value | - | - | Research Transaction | contentPurple | in progress |  |  | 
| Revenue | - | Versatile UI pages | - | - | Transaction Pages | MARKETINGPurple | in progress |  |  | 
| Retention | - | IF we guide the learning pace THEN the retention will increase. | - | - | Guided Pace Module (align with eka, untuk timeline module) | contentPurple | in progress |  |  | 
| DesignDeliverySpeed | - | HMW establish a scalable design files in figma | - | - | New Figma Structures & Visual Library | designopsYellow | in progress |  |  | 


## Product Management

### Summary


|  **Subjects**  |  **Key Points**  | 
|  --- |  --- | 
| Sprint Goal | Optimize product funnel and BE code to improve view rate | 
| Highlights | <ul><li>MoEngage rich landing 

</li><li>PiP research

</li></ul> | 
| Lowlights (if any) | Data bundling delayed due to accounting edge case handling with Telkomsel (3 days SLA from Telkomsel) | 
| Stream Dependency (if any) | N/A | 


### OKR Update


|  **Metrics**  |  **Latest snapshot**  **(AS IS)**  |  **Problem/Hypothesis**  |  **Objectives**  |  **Expected KRs**  **(TO BE)**  |  **Initiatives**  |  **Category**  |  **Status**  |  **Expected delivery**  |  **Expected date of outcome**  | 
|  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- |  --- | 
| MAU View Rate |  **Before sprint** : - Latest version: 44% (+1p) - Overall: 34% (0)  **Mid sprint** : - Latest version: 43.3% (-0.7p) - Overall: 34.9% (+0.9p) | Our search to view conversion is still quite low | Improve first time view | ≧50% | Transcription searchch improvement | contentPurple | in review |  |  | 
| Weekly avg. viewed per user |  **Before sprint** : - Latest version: 7.8 (+0.6p) - Overall: 8.26 (-0.2p)  **Mid sprint** : - Latest version: 8.3 (+0.5p) - Overall: 8.6 (+0.4p) | Our BE hasn't handle case where the content in a module is updated causing wrong signal of module completion/progress after content team update their published content | Address technical debt that affect user progress table | ≧15 | [Refactor end point for user progress table and DB architecture](https://munaelevate.atlassian.net/jira/software/c/projects/KEY/boards/12/backlog?atlOrigin=eyJpIjoiZjNhNDIzMzQyZmFjNDZiMTgyM2M1ZTk2NzE2YmY4ZDMiLCJwIjoiaiJ9) | contentPurpletech debtYellow | in progress |  |  | 
| Learning session length (view) |  **Before sprint** - Latest version (v.1.3.9): 5.2 min - Overall: 5.2m  **Mid-Sprint** - Latest version (v.1.3.9): 5.6m - Overall: 5.4m | Based on users research, user wants to be able to watched video while doing other things | Improve app usage frequency | ≧ 10 min | Research on Picture in Picture implementation | contentPurple | in progress |  |  | 
| ANR |  **Before sprint** : - Latest version 0.33% - Previous version: 0.20%  **Mid sprint** : - Latest version 0.51% - Previous version: 0.08% | <ul><li>CDN from from telkomsel akamai had shown slow response time for the past few days (2.65s) 

</li><li>Codec processing issue causing app to freeze in low end device

</li></ul> | Reduce ANR to be in peer indsutry | <ul><li>Maintain below threshold 0.47% 

</li><li>Beat peer median below 0.12%

</li></ul> | [Addressing top 2 issue in firebase performance](https://munaelevate.atlassian.net/browse/KEY-459?atlOrigin=eyJpIjoiNjg1MGY2NDViZDVmNDZjNTg5MWIyYmNmN2M3Nzc3OGIiLCJwIjoiaiJ9) | TECH DEBTRedPLATFORMYellow | IN PROGRESS |  |  | 
| Crash Rate |  **Before sprint** : - Latest version: 0.61% - Previous version: 0.43%  **Mid sprint** : - Latest version: 0.39% - Previous version: 0.6% | The new versions seems to be not stable on low end or non snapdragon device causing crash on users who have those devices | Reduce the crashrate to be on peer industry number | <ul><li>Maintain below threshold 1.09%

</li><li>Beat peer median below 0.38%

</li></ul> | [Addressing top 2 issue from Sentry](https://munaelevate.atlassian.net/browse/KEY-455) | PLATFORMYellowTECH DEBTRed | IN PROGRESS |  |  | 
| Supporting GTM metric on acquisition | Refer to correspondent stream | refer to corespondent stream | Leverage Telkomsel channel and assets to help meets the acquisition target by the end of the year | 39K users/month - 97K users/month | UAT is planned this sprint with Telkomsel ([Telkomsel data bundling](https://munaelevate.atlassian.net/browse/KEY-4?atlOrigin=eyJpIjoiODEwMzE4OGU0ZWUzNDU2ZDliYjBlZGNkZWVjNGFhYWUiLCJwIjoiaiJ9)) | acquisitionPurplepartnership | in progress |  |  | 
| Lead time to book mentor | 2 days | The mentoring booking process right now is barebone and manual | Improve the mentor booking process and operational efficiency | less than 1 hour | [Mentor SaaS integration development](https://munaelevate.atlassian.net/browse/KEY-15?atlOrigin=eyJpIjoiMWY5MGM0YWM5MzJkNDIxYWE3NjU0YjFkYTRkNzYyMjgiLCJwIjoiaiJ9) @Muhammad Hilman to update: 1. All the BE Happy Flow items had been developed and tested. The BE items are ready for release2. In Sprint 33 there are 5 new tickets for BE team including Rescheduling 3. FE team is still in the integration phase with the BE items following few new dependencies to BE work 4. Design team is finalizing the flow for Cancellation and Rescheduling | platformYellowmentoringBlue | in progress |  |  | 


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
