# Data Repository Hybrid Flow Shop Scheduling

This repository contains the input and output data for the paper applied in the paper ""Dispatching Rules for a Two-Stage Hybrid Flow Shop Scheduling with No Inter-Stage Waiting Time". The repository consists of "Input Instances", "CPlex", "Heuristic Code", "Simulation Output" and "Benchmark".

"Input Instances": contains the instances applied which is based on the paper of Vallada et al. (2015). This data can be used to create your own optimization for hybrid flow shop with no inter-stage waiting time for minimising makespan or flow time. When you look online, you can find an overall optimization for this topic.
"CPlex": shows the Multi-Integer-Linear-Programming Model (MILP) which was benchmarked with heuristic solutions in the paper.
"Heuristic Code": contains the code of the implemented heuristic solution approaches, SPT, LPT, HILL, VALLEY, etc.
"Simulation Output": contains the detailed results. In "Evaluations" you can find all tables analyzing the results of the MILP and heuristics. 
"Benchmark": contain all generated data used for the benchmark. We compare "Results_CPLEX" and "Heuristic_results" using an ARPD-table.

# Abstract
This computational study investigates a production scheduling problem for a two-stage hybrid flow shop (HFS) with parallel machines at least at one stage and with zero inter-stage waiting policies between process steps. This scenario is important in industries such as steel production and chemical processing, where cooling time between process steps must be avoided. In this paper, we propose eight dispatching rules that are applied to instances of up to 200 jobs, and benchmark them based on various performance metrics that demonstrate the effectiveness of the proposed heuristic approaches. The dispatching rules, such as Shortest Task Time (STT) and Shortest Processing Time (SPT) are combined with machine assignment rules, such as First Available Machine (FAM) and Minimum Idle Time (MIT), and optimized for makespan and total completion time in the no-wait HFS. Furthermore, for our computational study, we investigate two sequencing approaches - stage-oriented decomposition (A1) and reduction to a flow shop problem (A2) - in the benchmark of this computational study.

If you have any questions, we are happy to get in touch with you. Please contact me via quoikav@outlook.com
