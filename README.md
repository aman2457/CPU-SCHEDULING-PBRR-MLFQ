# CPU-SCHEDULING-PBRR-MLFQ
*code is in C Language
This repository contains two  program for cpu scheduling 
1. Priority Based Round Robin 

CPU schedules N processes which arrive at time 0 and each process is allocated the CPU for a specific user input time unit, processes are scheduled using a preemptive round robin scheduling algorithm. Each process must be assigned a numerical priority, with a higher number indicating a higher relative priority. In addition to the processes one task has priority 0. The length of a time quantum is T units, where T is the custom time considered as time quantum for processing. If a process is preempted by a higher priority process, the preempted process is placed at the end of the queue. Design a scheduler so that the task with priority 0 does not starve for resources and gets the CPU at some time unit to execute. Also compute waiting time, turn around.


2.Multilevel Feedback Queue Scheduling with 3 Queue

Implement the multi-level feedback queue scheduling algorithm by considering the following diagram: You can use the code of others to implement Roud-Robin, and FCFS but implement aging by your own self.
