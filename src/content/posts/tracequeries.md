---
title: 🔺 Datadog APM 
pubDate: '2025-09-20'
---

Since joining the APM team in February 2023, I have 



## Latency Investigation (2025, Private Beta) 

![_](./_assets/tracequeries/investigator2.png)

![_](./_assets/tracequeries/investigator3.png)

**🎥 Live Demo**

::link{url="https://www.youtube.com/live/FW8_RoDxnpc?feature=shared&t=1948"}

---

## Change Tracking (2024, GA)

Text about the project

**🎥 Live Demo**
::link{url="https://www.youtube.com/live/ZMNXNH-kJAM?feature=shared&t=4840"}

![_](./_assets/tracequeries/changetracking1.gif)

![_](./_assets/tracequeries/changetracking2.png)

---

## Trace Queries (2023-2024, GA)

![_](./_assets/tracequeries/3.png)

I led the design of [Trace Queries](https://www.datadoghq.com/blog/trace-queries/), a product that expanded the analytical power of distributed tracing in Datadog. It unlocked entirely new capabilities, enabling users to query traces based on service relationships, end-to-end latency thresholds, and other complex conditions that were previously impossible to express.

##### Impact
- Launched a major addition to APM, a $500M ARR business for Datadog.
- Growing the product from <mark>0 to over 45,000 monthly active users</mark> within one year after GA.

##### Scope & Team 
- Led the entire design process, including strategy, user research, design execution, and post-launch evaluation. 
- Collaborated closely with a cross-functional team of 30+ including PMs, TPMs, Senior/Staff+ Engineers, and Engineering Managers.
- The work underwent multiple rounds of review with VPs of Engineering, Product, and Design prior to launch

##### Timeline
- 6 months from concept to private beta 

<!-- ::link{url="https://www.datadoghq.com/blog/trace-queries/"} -->

## Why add Trace Queries?
Distributed traces hold a wealth of information, but finding the right ones as part of the troubleshooting process can feel like searching for a needle in a haystack.

In January 2023, Datadog customers reported that the UI failed to load traces, pointing to issues somewhere along the request path:

![_](./_assets/tracequeries/4.png)

To debug the issue, you'd need to express a query like "Find traces that passed through both `web-ui` and `trace-query`, where `trace-query` returned an error."

At the time, Datadog’s query language couldn’t express this structure. The UI only allows you to users to write `service:trace-query status:error`, which returned many irrelevant results. While the data existed, there was no way to query based on span relationships:

![Datadog has the data but users cannot query for it](./_assets/tracequeries/5.png)

Users faced similar challenges when trying to answer questions like:
- Which errors in trace-query service result in an upstream errors?
- Upstream service calls grouped by service
- Downstream service calls with high latency
- Traces where one service calls another more than 10 times

The usual workarounds (inject spans to get more information, resort to logs, keep browsing...) are manual, time-consuming, and often hitting cardinality limits.


## Process
With the need for a new language that can express more complex questions, I kicked off the project with an intensive exploration phase focused on understanding pain points. Examples of use cases that were collected from customers during this phase:

> Monitor an end-to-end request availability (with multiple points of failure) and not individual services’ availability (Indeed).

> Identify relevant traces when the information is spread across
multiple spans from the same request (Mercedes-Benz).

Armed with insights and a list of clients that were willing to give us feedback along the way, I began translating their needs into concrete concepts, sketching initial user flows and interactions using Excalidraw. This low-fidelity prototyping allowed for rapidly iterating without getting bogged down in details too early.

![_](./_assets/tracequeries/10.png)
![_](./_assets/tracequeries/14.png)

One key activity during this phase was a user story mapping exercise, which we ran over multiple rounds to align on the scope, priorities, and a shared vision of what we committed to build.

![_](./_assets/tracequeries/9.png)

## Outcome

##### Onboarding 
![Example queries included in the UI based on common use cases reported by customers](./_assets/tracequeries/8.png)
![Tooltip interaction](./_assets/tracequeries/9.gif)

## Outcome
![_](./_assets/tracequeries/12.png)

**Live Demo**
::link{url="https://www.youtube.com/live/GjcLWupY0jk?t=3574s"}

