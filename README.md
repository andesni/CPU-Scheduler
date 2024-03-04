# CPU-Scheduler
Java CPU Scheduler

The CPU Scheduling Simulator was implemented with Java Language and Java Swing as a GUI.
Using Java Swing came with a few difficulties, but it seemed to be the most straightforward approach to implementing the Simulator.
The simulator allows users to input process details, choose a scheduling algorithm, and visualize the execution timeline of the processes.

Use the "Add" button to add a new row to the process details table.
Use the "Remove" button to remove the selected process from the table.
Available Algorithms in this Scheduling Simulator include:
 First Come First Serve (FCFS)
 Shortest Job First (SJF)
 Shortest Remaining Time (SRT)
 Round Robin (RR)
 Priority Scheduling Non-Preemptive (PSN)
 Priority Scheduling Preemptive (PSP)
If the selected algorithm is Round Robin, a dialogue will prompt the user to input a time quantum.
Once the selected scheduling algorithm is executed based on the provided process details, the simulator will update the table with calculated waiting times (WT) and turnaround times (TAT) for each process.
The execution timeline will also be visualized in the chart area.

Users can add, remove, or modify processes and repeat the computation with different scheduling algorithms or parameters.

The visual representation of the execution timeline (chart area) provides users with an intuitive understanding of how processes are scheduled and executed over time. Users can explore the impact of different scheduling algorithms on waiting times and turnaround times for a given set of processes.
