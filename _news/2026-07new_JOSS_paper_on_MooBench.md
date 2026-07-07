---
layout: post
title: JOSS Paper on MooBench
date: 2026-07-07 10:11:00+0100
inline: false
related_posts: false
---

### New JOSS Paper on MooBench

**David Georg Reichelt, Shinhyung Yang, Marcel Hanson, and Wilhelm Hasselbring (2026). "<span>MooBench: A micro-benchmark for performance overhead measurement of observability tools.</span>" _Journal of Open Source Software_, 11(123), 10400, doi:&nbsp;[https://doi.org/10.21105/joss.10400](https://doi.org/10.21105/joss.10400)**

#### Abstract

Understanding the runtime behavior of software is inherently difficult due to the unpredictability of the software's behavior itself and the non-determinism of underlying layers, such as Just-In-Time (JIT) compilation in virtual machines, operating system scheduling, and CPU frequency scaling. Observability tools aim to answer questions regarding runtime behavior of software, such as "How much time did this request take?" or "ow often did method A call method B?" (Majors et al., 2022). These questions are answered using telemetry data, i.e., measurement data that is obtained from the code execution. To collect telemetry data, additional code needs to be executed, which introduces overhead. This overhead affects both system performance and the accuracy of the measurements themselves. The MooBench microbenchmark measures this overhead and contains factorial experiments that facilitate breaking down this overhead into its root causes.
The MooBench benchmark was originally developed to examine the performance overhead of the Kieker observability framwork (Hasselbring & van Hoorn, 2020; Hoorn et al., 2012; Yang, Reichelt, Jung, et al., 2025) in Java (Waller & Hasselbring, 2013) and was extended as a general overhead measurement microbenchmark for various observability tools, currently within the Java and Python ecosystem. In this paper, we describe why it is needed, how it is structured, and how it is used in research.
