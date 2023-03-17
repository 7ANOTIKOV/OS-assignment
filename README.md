# CPU Scheduling Algorithms RR and SJF Implementation using Java

This Assignment contains Java implementations of two CPU scheduling algorithms: Round Robin (RR) and Shortest Job First (SJF).

## Round Robin (RR) Algorithm
Round Robin (RR) algorithm is a CPU scheduling algorithm. It is also used in network schedulers. It is especially designed for time sharing system. It is also known as time slicing scheduling algorithm. It is closely similar to FCFS scheduling. In this section, we will discuss the round robin scheduling algorithm and its implementation in a Java program.

![My Image](RR%20output.png)

Advantage of Round Robin Scheduling:
+ It is cyclic in nature.
+ It never leads to starvation.
+ Each task is served by CPU for a fixed time.
+ Not priorities any task.
+ It is the same as FCFS scheduling.



## Shortest Job First Algorithm
The shortest job first (SJF) or shortest job next, is a scheduling policy that selects the waiting process with the smallest execution time to execute next. SJN, also known as Shortest Job Next (SJN), can be preemptive or non-preemptive.  

Advantages of SJF:
+ SJF is better than the First come first serve(FCFS) algorithm as it reduces the average waiting time.
+ SJF is generally used for long term scheduling
+ It is suitable for the jobs running in batches, where run times are already known.
+ SJF is probably optimal in terms of average turnaround time.

