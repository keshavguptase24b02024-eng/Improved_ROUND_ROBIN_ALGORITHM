# Improved_ROUND_ROBIN_ALGORITHM
The traditional Round Robin CPU scheduling algorithm treats all processes equally, assigning each one a fixed time quantum in a cyclic order. While this ensures fairness, it can lead to increased waiting time for processes that are more critical or time-sensitive. To address this limitation, the improved Round Robin scheduling algorithm introduces priority-based classification of processes into high-priority and low-priority groups.

In this approach, high-priority processes are given preferential access to the CPU, reducing their average waiting time significantly across different workloads. Low-priority processes are still scheduled in a fair manner, although their waiting time improvement may vary depending on the process set. The algorithm aims to optimize CPU utilization while improving overall system responsiveness.

The implementation is based on the research paper “Improved Round Robin CPU Scheduling Algorithm based on Priority of Process” by Govind Prasad Arya, Kumar Nilay, and Devendra Prasad. Simulation results show that the proposed method reduces average waiting time compared to the traditional Round Robin scheduling in most scenarios, especially for high-priority tasks.

Link to the original Research Paper - (https://www.researchgate.net/publication/327964264_An_Improved_Round_Robin_CPU_Scheduling_Algorithm_based_on_Priority_of_Process)
