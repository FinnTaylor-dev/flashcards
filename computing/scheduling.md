Q: What is scheduling in the context of a CPU?
A: Deciding which tasks to process, for how long, and in what order.

---

C: [Scheduling] is the process of deciding which tasks to process, for how long, and in what order to ensure the CPU processes tasks as fast as possible.

---

Q: What is pre-emptive scheduling?
A: A scheduling category that allocates the CPU to processes for specific, time-limited slots and allows currently running processes to be interrupted.

---

Q: What is non-pre-emptive scheduling?
A: A scheduling category that allocates the CPU to a process for an unlimited time slot until it completes its burst time or switches to a waiting state, without interruption.

---

C: In [pre-emptive] scheduling, the CPU is allocated for time-limited slots, whereas in [non-pre-emptive] scheduling, it is allocated for unlimited time slots until completion or a waiting state.

---

Q: Is Round Robin a pre-emptive or non-pre-emptive scheduling algorithm?
A: Pre-emptive.

---

Q: How does the Round Robin scheduling algorithm distribute processor time?
A: It equally distributes processor time amongst all processes by giving each a specific time quantum.

---

Q: What happens to a process in Round Robin if it is not completed by the end of its time quantum?
A: It is moved to the back of the ready queue.

---

Q: Is First-Come-First-Served (FCFS) a pre-emptive or non-pre-emptive scheduling algorithm?
A: Non-pre-emptive.

---

Q: How does the FCFS scheduling algorithm prioritize processes?
A: It prioritizes processes based on their arrival order, serving the one that arrived first.

---

Q: Is Multi-Level Feedback Queue (MLFQ) a pre-emptive or non-pre-emptive scheduling algorithm?
A: Pre-emptive.

---

Q: How does the MLFQ scheduling algorithm handle tasks that exceed their time quantum?
A: They trickle down to lower priority queues.

---

Q: What is the primary purpose of using multiple queues in the MLFQ algorithm?
A: To group tasks of equal size together and prioritize shorter, more critical tasks.

---

Q: Is Shortest Job First (SJF) typically a pre-emptive or non-pre-emptive scheduling algorithm?
A: Non-pre-emptive.

---

Q: How does the SJF scheduling algorithm select the next process to run?
A: It selects the process with the shortest burst time when the CPU becomes available.

---

Q: Is Shortest Remaining Time First (SRTF) a pre-emptive or non-pre-emptive scheduling algorithm?
A: Pre-emptive.

---

Q: How does the SRTF scheduling algorithm determine which process to run next?
A: Whenever a new process arrives, it compares the remaining times of all processes and gives priority to the one with the shortest remaining time.

---

Q: Which scheduling algorithm is known for giving all processes a fair share of the CPU and being ideal for time-sharing systems?
A: Round Robin.

---

Q: What is a major drawback of the Round Robin scheduling algorithm?
A: Choosing the right time quantum is difficult, and it can lead to high turnaround and waiting times for long processes.

---

Q: Which scheduling algorithm is simple and fair based on arrival order, but can suffer from poor performance if a long process arrives before shorter ones?
A: First-Come-First-Served (FCFS).

---

Q: Which scheduling algorithm minimizes waiting time and is highly efficient for short processes?
A: Shortest Job First (SJF).

---

Q: What is a shared major drawback of both Shortest Job First (SJF) and Shortest Remaining Time First (SRTF)?
A: Both require knowing the burst time of processes in advance.

---

Q: What is a significant drawback of SRTF compared to non-pre-emptive algorithms?
A: It has a high context switching overhead due to frequent preemption.

---

Q: Which scheduling algorithm uses multiple queues to group similar-sized tasks and trickle down processes that exceed their time quantum?
A: Multi-Level Feedback Queue (MLFQ).

---

Q: What is a major drawback of the Multi-Level Feedback Queue (MLFQ) algorithm?
A: It is more complex than other algorithms, and setting the correct parameters, such as the number of queues and ageing rules, can be difficult.

---

Q: What is the term for the phenomenon where long processes are neglected or delayed indefinitely because shorter processes keep arriving?
A: Starvation.

---

Q: On what does the suitability of a specific scheduling algorithm primarily depend?
A: The specific scenario and the system requirements.

---

C: The suitability of a scheduling algorithm largely depends on the specific [scenario] and the [system requirements].
