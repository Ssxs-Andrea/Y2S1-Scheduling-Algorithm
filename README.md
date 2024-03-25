# Y2S1-Scheduling-Algorithm

## Overview
This C program implements a scheduling algorithm that combines First Come First Served (FCFS), Round Robin (RR), and a Multi-Level Feedback Queue (MLFQ). The program prompts the user to select the scheduling algorithm and provides options for FCFS, RR, and Multi-Level Scheduling. The scheduling is demonstrated with Gantt charts, and the program will calculate and display a table that shows waiting time, turnaround time, and completion time for each process. Finally, the average waiting time and average waiting time of the program will be displayed.
The program consists of three main functions: firstcomefirstserve(), roundrobin(), and multilevel(). Each function implements a specific scheduling algorithm and includes relevant data structures and logic.

1. First Come First Served: Implements the First Come First Served scheduling algorithm.

2. Round Robin: Implements the Round Robin scheduling algorithm.

3. Multilevel feedback queue: Implements the Multi-Level scheduling algorithm, it runs on the higher priority queue first, which is  Round Robin queue, then onto the lower priority queue, First Come First Served queue.
