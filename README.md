# CPU Scheduling Algorithms

CPU Scheduling is a process of determining which
process will own CPU for execution while another
process is on hold. The main task of CPU scheduling
is to make sure that whenever the CPU remains idle,
the OS at least select one of the processes available
in the ready queue for execution. The selection
process will be carried out by the CPU scheduler. It
selects one of the processes in memory that are
ready for execution.

### Algorithms Implemented

- The first process arrived in the ready queue is processed first.
  - **First Come First Serve (FCFS)**
    > Non-Preemptive
- The shortest job in the ready queue is processed first.
  - **Shortest Job First (SJF)**
    > Non-Preemptive
  - **Shortest Remaining Job First (SRJF)**
    > Preemptive
- The longest job in the ready queue is processed first.
  - **Longest Job First (LJF)**
    > Non-Preemptive
  - **Longest Remaining Job First (LRJF)**
    > Preemptive
- The highest priority job in the ready queue is processed first.
  - **Priority Non-Preemptive (PNP)**
    > Non-Preemptive
  - **Priority Preemptive(PP)**
    > Preemptive
- The jobs in the ready queue are given a fixed time quantum.
  - **Round Robin (RR)**
    > Preemptive
- The job with the highest response ratio in the ready queue is processed first.
  - **Highest Response Ratio Next (HRRN)**
    > Non-Preemptive

**Non-Preemptive:**
Once a job enters the Running Queue, it will only leave when its required CPU Burst Time is completed or it requires an I/O Job.

**Preemptive:**
A job in the Running Queue can be removed (preeempted) by other process of higher priority or with better criteria satisfaction or the given time quantum is completed.

### Tech Used

- HTML
- CSS
- Vanilla JS
- Google Charts
- Chart.js
