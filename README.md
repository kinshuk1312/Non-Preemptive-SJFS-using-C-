# Non-Preemptive-SJFS-using-Cpp
Shortest job first (SJF) or shortest job next, is a scheduling policy that selects the waiting process with the smallest execution time to execute next. SJN is a non-preemptive algorithm.  
Shortest Job first has the advantage of having a minimum average waiting time among all scheduling algorithms. 
It is a Greedy Algorithm. 
It may cause starvation if shorter processes keep coming. 

Algorithm:  
1. Sort all the process according to the arrival time. 
2. Then select that process which has minimum arrival time and minimum Burst time. 
3. After completion of process make a pool of process which after till the completion of previous process and select that process among the pool which is having minimum Burst time.
