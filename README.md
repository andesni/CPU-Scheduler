# Prerequisite
* OpenJDK8+

To start with this program, you'll need an IDE compatible with at least Java 8 like VSCode.
A collection of extensions suggested by Microsoft: Language Support for Java by Red Hat, Debugger for Java, Test Runner for Java.

# Usage

The CPU Scheduling Simulator was implemented with Java Language and Java Swing as a GUI.
The simulator allows users to input process details, choose a scheduling algorithm, and visualize the execution timeline of the processes.

Use the "Add" button to add a new row to the process details table.
Use the "Remove" button to remove the selected process from the table.
Available Algorithms in this Scheduling Simulator include:
*  First Come First Serve (FCFS)
*  Shortest Job First (SJF)
*  Shortest Remaining Time (SRT)
*  Round Robin (RR)
*  Priority Scheduling Non-Preemptive (PSN)
*  Priority Scheduling Preemptive (PSP)\
If the selected algorithm is Round Robin, a dialogue will prompt the user to input a time quantum.
Once the selected scheduling algorithm is executed based on the provided process details, the simulator will update the table with calculated waiting times (WT) and turnaround times (TAT) for each process.\
The execution timeline will also be visualized in the chart area.

Users can add, remove, or modify processes and repeat the computation with different scheduling algorithms or parameters.

The visual representation of the execution timeline (chart area) provides users with an intuitive understanding of how processes are scheduled and executed over time. Users can explore the impact of different scheduling algorithms on waiting times and turnaround times for a given set of processes

# Visual representation


https://github.com/andesni/CPU-Scheduler/assets/93085549/b0ec1835-12f2-48b9-96af-8952f15948bc

.
