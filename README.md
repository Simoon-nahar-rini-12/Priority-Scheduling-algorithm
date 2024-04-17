# Priority-Scheduling-algorithm
<ins>_**Experiment name:**_</ins> Implementation of the  Priority Scheduling algorithm.

<ins>_**Description:**_</ins> The program is intended to implement the Priority Scheduling algorithm in C++. Priority Scheduling is a non-preemptive scheduling technique that chooses the process with the highest priority for execution. In this code, each process has a burst time and a priority value. 
The application begins by asking the user to enter the total number of processes (n), then the burst time and priority for each process. The burst time specifies how long a process takes to complete, but the priority value dictates how activities are scheduled. The user enters these parameters for each procedure in consecutive order. The program then determines the waiting time for each process. The waiting time for a process is the sum of the burst times of all previous processes. The program iteratively calculates the waiting time for each process based on the sorted order of processes. The program then calculates the turnaround time for each process by adding the burst time and the waiting time. 
The turnaround time is the overall time it takes for the process to complete from when it arrives.
Finally, the program shows a table with the process ID, burst time, waiting time, and turnaround time for each process.

<ins>_**Input:**_</ins>The input required for this Priority Scheduling algorithm code consists of the following steps:
Number of Processes: The user needs to input the total number of processes (n) that they want to schedule. This value should be an integer.
Burst Time: The amount of time required for a process to complete its execution. This should be an integer value.
Priority: The priority value assigned to the process. Processes with higher priority values are scheduled before those with lower priority values. This should also be an integer value.

<ins>_**Output:**_</ins>
The output of the provided Priority Scheduling Algorithm code will display the turnaround time and waiting time for each process  and the final result:

![Picture5](https://github.com/simoon06/Priority-Scheduling-algorithm/assets/139492391/243d91d3-123c-4f58-80b0-19c605155a3f)
