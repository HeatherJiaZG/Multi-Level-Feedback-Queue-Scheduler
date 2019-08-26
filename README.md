# Multi-Level-Feedback-Queue-Scheduler
Build an MLFQ scheduler with four priority queues in C. When a process uses up its time-slice (counted as a number of ticks), it will be downgraded to the lower priority level. The time-slices for higher priorities are shorter than lower priorities. The scheduling method in each of these queues is round-robin, except the bottom queue which is implemented as FIFO.