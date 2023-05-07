Download Link: https://assignmentchef.com/product/solved-operating-system-homework-3
<br>
<h1>Part I</h1>

<ol>

 <li> Explain what memory-mapped I/O is and how it works.</li>

 <li> Explain what DMA is and how it works.</li>

 <li>Consider the following set of processes, with the length of the CPU-burst time given in milliseconds:</li>

</ol>

<em>Process    Burst Time     Priority</em>

<em>P</em><sub>1                           </sub>8                   4

<em>P</em><sub>2                           </sub>1                   1

<em>P</em><sub>3                           </sub>2                   3

<em>P</em><sub>4                           </sub>1                   5

<em>P</em><sub>5                           </sub>6                   2

The processes are assumed to have arrived in the order <em>P</em><sub>1</sub>, <em>P</em><sub>2</sub>, <em>P</em><sub>3</sub>, <em>P</em><sub>4</sub>, <em>P</em><sub>5</sub>, all at time 0.

<ul>

 <li> Draw four Gantt charts illustrating the execution of these processes using FCFS, SJF, a nonpreemptive priority (a smaller priority number implies a higher priority), and RR (quantum = 1) scheduling.</li>

 <li> What is the turnaround time of each process for each of the scheduling algorithms in part 3a?</li>

 <li>What is the waiting time of each process for each of the scheduling algorithms in part 3a?</li>

 <li> Which of the schedulers in part 3a results in the minimal waiting time (over all processes)?</li>

</ul>

<ol start="4">

 <li> A UNIX process has two parts—the user part and the kernel part. Is the kernel part like a subroutine and a coroutine? Why?</li>

</ol>

<h1>Part II</h1>

Write a monitor in C++ to simulate the dining philosopher problem mentioned in the textbook using the conditional variables provided by the Pthreads API. Make sure that your implementation is able to handle 5 philosophers and is free of the race condition.