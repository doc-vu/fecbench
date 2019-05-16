# FECBench: A Holistic Interference-aware Approach for Application Performance Modeling

Installation Scripts Available here: https://github.com/doc-vu/fecbench-ansible

Abstract from the IC2E Paper About FECBench

*Services hosted in multi-tenant cloud platforms
often encounter performance interference due to contention for
non-partitionable resources, which in turn causes unpredictable
behavior and degradation in application performance. To grapple
with these problems and to define effective resource management
solutions for their services, providers often must expend significant
efforts and incur prohibitive costs in developing performance
models of their services under a variety of interference scenarios
on different hardware. This is a hard problem due to the wide
range of possible co-located services and their workloads, and
the growing heterogeneity in the runtime platforms including
the use of fog and edge-based resources, not to mention the
accidental complexities in performing application profiling under
a variety of scenarios. To address these challenges, we present
FECBench (Fog/Edge/Cloud Benchmarking), an open source
framework comprising a set of 106 applications covering a
wide range of application classes to guide providers in building
performance interference prediction models for their services
without incurring undue costs and efforts. Through the design
of FECBench, we make the following contributions. First, we
develop a technique to build resource stressors that can stress
multiple system resources all at once in a controlled manner,
which helps to gain insights into the impact of interference
on an application’s performance. Second, to overcome the need
for exhaustive application profiling, FECBench intelligently uses
the design of experiments (DoE) approach to enable users to
build surrogate performance models of their services. Third,
FECBench maintains an extensible knowledge base of application
combinations that create resource stresses across the multidimensional
resource design space. Empirical results using realworld
scenarios to validate the efficacy of FECBench show that
the predicted application performance has a median error of only
7.6% across all test cases, with 5.4% in the best case and 13.5%
in the worst case.*

