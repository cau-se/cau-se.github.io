---
layout: post
title: Paper on Research Software Structure Optimization
date: 2025-10-28 10:11:00+0100
inline: false
related_posts: false
---

### New paper in Software

**H. Schnoor, W. Hasselbring, R. Jung: "<span>Using Genetic Algorithms for Research Software Structure Optimization</span>" _Software_, vol. 4, no. 4, 2025, doi:&nbsp;[https://doi.org/10.3390/software4040026](https://doi.org/10.3390/software4040026)**

#### Abstract

Our goal is to generate restructuring recommendations for research software systems based on software architecture descriptions that were obtained via reverse engineering. We reconstructed these software architectures via static and dynamic analysis methods in the reverse engineering process. To do this, we combined static and dynamic analysis for call relationships and dataflow into a hierarchy of six analysis methods. For generating optimal restructuring recommendations, we use genetic algorithms, which optimize the module structure. For optimizing the modularization, we use coupling and cohesion metrics as fitness functions. We applied these methods to Earth System Models to test their efficacy. In general, our results confirm the applicability of genetic algorithms for optimizing the module structure of research software. Our experiments show that the analysis methods have a significant impact on the optimization results. A specific observation from our experiments is that the pure dynamic analysis produces significantly better modularizations than the optimizations based on the other analysis methods that we used for reverse engineering. Furthermore, a guided, interactive optimization with a domain expert’s feedback improves the modularization recommendations considerably. For instance, cohesion is improved by 57% with guided optimization.

