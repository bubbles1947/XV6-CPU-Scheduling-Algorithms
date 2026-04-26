# XV6-Scheduling-Algorithms
I built two different scheduling algorithms for the XV6 Operating System. Work Stealing and Predictive SJF. 
The default xv6 scheduler is "fair" but inefficient for mixed workloads. It treats a short,
interactive task (like a shell command) the same as a long, CPU-bound calculation. This
behaviour leads to high average turnaround times. To optimize this, we need to implement
Shortest Job First (SJF) scheduling, but since we cannot know the future length of a CPU
burst, we must predict it, utilizing modern and intelligent concepts in the scheduling. 


