SHORTEST JOB FIRST CPU SCHEDULING
description:
This program implements the Shortest Job First (SJF) non-preemptive CPU scheduling algorithm.
It takes input for multiple processes, including their process ID, arrival time, and burst time, and then simulates how a CPU schedules them. At each step, the program selects the process with the smallest burst time among those that have already arrived. Once a process is chosen, it runs to completion without interruption.
The program calculates:
Completion Time (CT) – when a process finishes execution
Turnaround Time (TAT) = CT − Arrival Time
Waiting Time (WT) = TAT − Burst Time
If no process has arrived at the current time, the CPU remains idle and time is incremented.
Finally, it displays the waiting time and turnaround time for each process, along with their average values.
