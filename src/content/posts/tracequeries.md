---
title: 🔺 Datadog Trace Queries 
pubDate: '2023-09-20'
---

In 2023, I led the design of [Trace Queries](https://www.datadoghq.com/blog/trace-queries/), a product that significantly improves the analytical capability of distributed traces.

##### Impact
- Successfully launch a major initiative for APM, a $500M ARR business for Datadog
- Achieving from <mark>0 to over 40,000</mark> monthly active users a few months after GA.

##### Role
-  I owned the entire design life cycle including research, strategy, design execution and user evaluation.
- The team consists of over 30 people including PM, TPM, Staff+ Engineers, and Engineering Managers. Before launch, the work went through multiple rounds of review by VPs of Engineering, Product, and Design.

##### Timeline
- 6 months from conception to private beta 
- 4 months from private beta to public release 

### Watch the live demo
::link{url="https://www.youtube.com/live/GjcLWupY0jk?t=3574s"}

<!-- ::link{url="https://www.datadoghq.com/blog/trace-queries/"} -->

## Problem: It’s hard to find the right trace
A real-life example: In Jan 2023, Datadog customers reported that the UI failed to load traces, which means that there are issues with this path.

With the query language at the time, you can’t express structure. The UI only allows you to users to write this query, which means traces you do not need would also show up in the results. 
```
text
```

> Datadog have the data but users cannot query for it. They cannot query for a specific sequence of events based on the relationship between spans.

- Which errors in trace-query service result in an upstream errors?
- Upstream service calls grouped by service
- Downstream service calls with high latency
- Traces where one service calls another more than 10 times

Workarounds (inject spans to get more info, resort to logs, keep browsing...) are manual and time-consuming.

## Solution:
A new query language that can express more complex questions

- Structural operators (child & descendant) `->` `=>` 
- Logical operators `and` `or` `not`	
- Aggregations `span_count()` 
- E2E traces `trace_duration`
