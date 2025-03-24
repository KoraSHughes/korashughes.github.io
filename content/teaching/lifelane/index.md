---
title: LifeLane
summary: Improving NYC EMS Response Time Through Data Visualization
date: 2024-04-20
type: docs
math: false
tags:
  - Machine Learning Visualization
  - Data Science
  - Python
image:
  caption: 'Visualization of EMS Dispatch'
---

You can find the source code at this [Project Repository](https://github.com/KoraSHughes/LifeLane). Additionally, if you'd like to read about the results you can do so at this [Paper Link](https://docs.google.com/document/d/1ndv_jZA0513jfY0hkFEzEAKQVghc-FsKNOGY6w6WLoM/edit?usp=sharing).

## Brief Description

Emergency medical system (EMS) response times in NYC are growing. According to the New York Post, the average EMS response time increased by 20 seconds last year, totaling 9 minutes and 50 seconds. This has led to an increase in deaths via fires and medical emergencies. Thus, we want to take a data scientists' approach to optimizing this problem While we can’t easily restructure the current EMS dispatch sites, we can analyze EMS dispatch data and cross-reference it with traffic patterns to optimize the placement of new dispatch sites and the staffing of current dispatch sites. To accomplish this, we can create a regression problem by setting our target variable to INCIDENT_TRAVEL_TM_SECONDS_QY in the EMS Dispatch Dataset which is the time elapsed in seconds between the first_assignment_datetime – time at which the emergency incident was assigned by the operator - and the first_on_scene_datetime - the time at which the team arrived at the incident location. Once optimized, we can reverse engineer this problem to find the times and locations where dispatch travel time is the worst. With this information, we can suggest new policies and procedures that specifically target these zones in order to minimize future dispatch time.