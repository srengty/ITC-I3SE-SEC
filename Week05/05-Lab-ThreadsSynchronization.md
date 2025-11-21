<div style="margin-bottom: 20px;">
<div class="header" style="background-color: #26679cff;">
    <h3>Software Engineering Concepts</h3>
    <h4>SE - Lab 05</h4>
</div>
</div>
<div style="text-align: right; font-style: italic; margin-bottom: 20px;">
    <p>Topic: <span style="color: #26679cff;">Threads communication and synchronization</span><br>
    Estimation: <span style="color: #26679cff;">15 hours.</span> </p>
</div>

# Lab Overview
The purpose of this lab is to deepen your understanding of multithreading and concurrency in Java through practical implementation of various concepts.

# Task 1: Implement a Thread-Safe Bank Account
Create a `BankAccount` class that supports concurrent deposits and withdrawals without race conditions.

# Task 2: Producer-Consumer with Bounded Buffer
Implement a producer-consumer system where producers add items to a bounded buffer and consumers remove them.

# Task 3: Reader-Writer Problem
Implement a solution where multiple readers can access a resource simultaneously, but writers need exclusive access.

# Task 4: Dining Philosophers Problem
Implement the classic Dining Philosophers problem:
- 5 philosophers sitting around a circular table
- 5 forks (one between each pair of philosophers)
- Each philosopher alternates between thinking and eating
- To eat, a philosopher needs both left and right forks
- Prevent deadlock and starvation

**Requirements:**
- Each philosopher should eat at least 3 times
- Use proper synchronization to avoid deadlock
- Display philosopher states (thinking/hungry/eating)
- Implement timeout mechanism to break potential deadlocks
- Run simulation for 2 minutes and show statistics
![Dining Philosophers](http://localhost:5500/res/images/an_illustration_of_the_dining_philosophers_problem.png)

**Submission Guidelines:**
- Create separate Java files for each task
- Include comments explaining your approach
- Add README.md with execution instructions
- Submit all source code and output screenshots
- Deadline: One week from assignment date