# Multi-threaded-sorting

In this project, an array-sorting application is written, using two different methods: QuickSort and MergeSort.

This application is implemented as both [single-threaded](https://github.com/Ezgii/Multi-threaded-sorting/blob/main/SinglethreadedSorting.java) and [multi-threaded](https://github.com/Ezgii/Multi-threaded-sorting/blob/main/MultithreadSort.java), to see how multi-threading improves the speed.

### Results

#### Below figure compares the execution times of the single-threaded and multi-threaded implementations, for different array sizes:

![execution times](https://github.com/Ezgii/Multi-threaded-sorting/blob/main/execution_times.png)

The execution time tests are performed in the below environment : 

Processor : Apple M1 8-core CPU

Memory : 16GB LPDDR4

Operating System : macOS Monterey version 12.1

Java : JRE 17.0.2
  



#### Below figure shows the CPU utilization during single-threaded sorting:

![CPU_single](https://github.com/Ezgii/Multi-threaded-sorting/blob/main/CPU_utilization_single_threaded.jpeg)

#### Below figure shows the CPU utilization during multi-threaded sorting:

![CPU_multi](https://github.com/Ezgii/Multi-threaded-sorting/blob/main/CPU_utilization_multi_threaded.jpeg)

### Conclusion:
In this work it is shown that utilizing multithreading as a source for more raw computer power, indeed increases the performance of an algorithm. However, the increase starts off when the data being processed is sufficiently big enough that the overhead for thread creation is a smaller factor than the overall execution time.



