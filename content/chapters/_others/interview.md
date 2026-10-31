<!--metadata
  title: "Intv"
  authors: ["Subhajit Gorai"]
  dateCreated: "14/04/2026"
  dateEdited: "22/04/2026"
  description: ""
  tags: [""]
-->

# OA Analytics

> Find previously asked questions in cs oa, interviews, of everything, be it coding, os, cn, maths, aptitude everything. I want to have idea. search in various sources, google reddit all platforms@Web search 

I searched across **Reddit, GeeksforGeeks, LeetCode Discuss, placement resources, and recent interview experience posts**. One clear pattern emerges:

> **There is no fixed question bank.** Companies keep changing exact questions, but the **same concepts and problem families repeat again and again.** ([Reddit][1])

Below is a consolidated list of what people repeatedly reported.

---

# 1. Coding (Most Important)

Nearly every OA contains **2 coding questions** (sometimes 1 easy + 1 medium, sometimes 2 medium).

Most repeated topics:

### Arrays

* Two Sum variations
* Prefix Sum
* Sliding Window
* Kadane
* Rotation
* Merge intervals
* Frequency counting
* Sorting-based problems

Questions commonly seen:

* Product Except Self
* Trapping Rain Water
* Max Subarray
* Rotate Array
* Merge Intervals

---

### Strings

Frequently asked

* Longest substring without repeating
* Anagrams
* Pattern matching
* Encoding/Decoding
* Palindrome
* String compression

---

### HashMaps

Very common

Questions

* Group Anagrams
* Top K Frequent
* Frequency maps
* Pair sums
* Duplicate detection

---

### Trees

Extremely common

Questions

* Diameter of Binary Tree
* Lowest Common Ancestor
* BST validation
* Level Order Traversal
* Good Nodes
* Serialize/Deserialize

Amazon interview reports repeatedly mention Diameter variations. ([Reddit][2])

---

### Graphs

Often medium difficulty.

Topics

* BFS
* DFS
* Connected Components
* Number of Islands
* Rotten Oranges
* Shortest Path
* Topological Sort

Questions reported

* Number of Islands
* Rotten Oranges
* Grid BFS

([Reddit][3])

---

### Heap / Priority Queue

Common

Questions

* Merge K Sorted Lists
* K Closest Points
* Top K Frequent
* Running Median

Amazon interviews mention Merge K Sorted Lists repeatedly. ([LeetCode][4])

---

### Dynamic Programming

Usually one medium.

Topics

* Coin Change
* LIS
* House Robber
* Knapsack
* Partition

Microsoft experiences particularly mention DP. ([GeeksforGeeks][5])

---

### Binary Search

Very common.

Questions

* Koko Eating Bananas
* Search in Rotated Array
* Capacity to Ship Packages
* First/Last Occurrence

---

### Greedy

Very common in OAs.

Amazon OA reports frequently mention greedy-based problems. ([Reddit][2])

---

# 2. OS Questions

These appear in MCQ rounds and interviews.

Most repeated:

## Process vs Thread

Expected:

* Memory
* Context switching
* Scheduling
* Communication

---

## Deadlock

Know

* Coffman conditions
* Prevention
* Avoidance
* Detection
* Recovery

---

## Scheduling

FCFS
SJF
Priority
Round Robin
Questions like

> Calculate average waiting time.

---

## Virtual Memory

Asked repeatedly.

Know

* Paging
* Segmentation
* TLB
* Page Fault
* Demand Paging

---

## Synchronization

Questions
Semaphore
Mutex
Monitor
Producer Consumer
Readers Writers
Dining Philosophers

---

## Memory Allocation

* Internal fragmentation
* External fragmentation
* Buddy system

---

## System Calls

Difference
User mode
Kernel mode
Interrupt
Trap

---

# 3. DBMS

Repeated almost everywhere.
Normalization
1NF
2NF
3NF
BCNF

---

SQL

Questions

* GROUP BY
* HAVING
* Window Functions
* JOIN
* Self Join
* Left Join
* Indexes

---

Transactions

ACID
Isolation Levels
Deadlock
Locking

---

Indexes

B Tree
Hash
Clustered
Non-clustered

---

# 4. Computer Networks

Very frequently asked.

TCP vs UDP

---

HTTP vs HTTPS

---

OSI Layers

---

DNS

---

ARP

---

Subnetting

---

Congestion Control

---

Three Way Handshake

Four Way Termination

---

Socket Programming basics

---

REST APIs

Status Codes
GET
POST
PUT
DELETE

---

# 5. OOP

Very common.

Questions
Inheritance
Polymorphism
Abstraction
Encapsulation
Virtual Function
Constructor
Destructor
Overloading vs Overriding
Composition vs Inheritance
Interface vs Abstract Class
Diamond Problem
SOLID Principles

---

# 6. Mathematics

Many OAs include these.
Probability
Permutations
Combinations
Modular Arithmetic
GCD
LCM
Prime
Logarithms
Recurrence
Basic Calculus (rare)
Matrix operations
Bit Manipulation

---

# 7. Aptitude

Repeated topics
Time and Work
Speed Distance
Pipes
Probability
Profit Loss
Simple Interest
Compound Interest
Ratios
Number Systems
Logical Reasoning
Blood Relations
Seating Arrangement
Coding Decoding
Series
Syllogisms

---

# 8. Behavioral Questions

Amazon especially.

Examples
Tell me about a challenge.
Tell me about a conflict.
Failure.
Leadership.
Innovation.
Deadline.
Ownership.
Difficult teammate.
Disagreement.
These are based on Amazon Leadership Principles. ([Reddit][2])

---

# 9. Resume-Based Questions

Every interviewer asks things like
Explain your project.
Why did you choose this architecture?
Biggest challenge?
How would you scale it?
How is authentication handled?
Database choice?
Trade-offs?

Since you've built projects like Flask applications and worked with embeddings, expect deep follow-up questions on implementation details rather than just features.

---

# 10. System Design (Sometimes for Interns, Often for SDE-2)

Examples

Design TinyURL
Design Parking Lot
Design Chat App
Design Rate Limiter
Design Cache
Design URL Shortener
LLD examples
Chess
LRU Cache
Elevator
Snake & Ladder
Library Management

Amazon SDE-II experiences commonly report LLD/HLD after the OA. ([LeetCode][6])

---

# 11. OA Pattern (Most Common)

Most companies follow roughly:

```txt
Resume
      ↓
Online Assessment

2 Coding Problems

+ Aptitude (sometimes)

+ CS MCQs

+ Work Simulation (Amazon)

+ Behavioral
      ↓

Technical Interview

DSA

OS

CN

DBMS

Projects

Resume
      ↓

HR
```

([Placement Papers][7])

---

# 12. What Reddit Analysis Shows

A community analysis of around **300 publicly shared interview questions** found:

* **71%** came from Online Assessments.
* The most common coding tasks were **practical data manipulation** rather than obscure dynamic programming.
* Amazon appeared most frequently among shared experiences, followed by Uber, TikTok, Microsoft, Snowflake, Google, Salesforce, Stripe, and Meta. ([Reddit][1])

---

## High-Yield Preparation Order

If you want the best return on your preparation time, prioritize:

1. Arrays & Hash Maps
2. Strings & Sliding Window
3. Binary Search
4. Trees & BST
5. Graphs (BFS/DFS)
6. Heaps
7. Greedy
8. Dynamic Programming
9. OS fundamentals
10. DBMS (SQL + normalization + ACID)
11. Computer Networks (TCP/IP, HTTP, DNS)
12. OOP & SOLID
13. Aptitude & probability
14. Behavioral stories (STAR format)

If you're targeting **product companies** (Google, Microsoft, Amazon, Atlassian, Adobe, Salesforce, Walmart, Flipkart, etc.), this list covers the overwhelming majority of topics reported across recent OAs and technical interviews.

[1]: https://www.reddit.com/r/leetcode/comments/1u3fpb4/i_collected_analyzed_300_interview_questions_in/?utm_source=chatgpt.com "i collected / analyzed 300 interview questions in the past 3 months and here is what i found"
[2]: https://www.reddit.com/r/developersIndia/comments/1o8c9p6/selected_amazon_india_sde1_interview_experience/?utm_source=chatgpt.com "[Selected] Amazon India SDE-1 Interview Experience"
[3]: https://www.reddit.com/r/leetcode/comments/1kkyqg5?utm_source=chatgpt.com "Amazon | India | SDE-I Offer 🚀"
[4]: https://leetcode.com/discuss/post/6975862/?utm_source=chatgpt.com "Amazon [India] SDE II | Interview Experience - Discuss - LeetCode"
[5]: https://www.geeksforgeeks.org/interview-experiences/microsoft-online-assessment-experience/?utm_source=chatgpt.com "Microsoft Online Assessment Experience - GeeksforGeeks"
[6]: https://leetcode.com/discuss/post/6961860/amazon-l5-sde-ii-bangalore-june-2025-sel-ocr8/?utm_source=chatgpt.com "Amazon L5 (SDE II) | Bangalore | June 2025 | Selected - Discuss - LeetCode"
[7]: https://placementpapers.app/online-assessments/?utm_source=chatgpt.com "Online Assessment Questions - OA Format & Preparation Guide for Top Companies | Placement Papers"

---

> @Web search exact questions can you find in cs theory / apti?

Yes. I found actual questions reported by candidates. While companies rarely reuse the *exact same* MCQs, the following questions (or extremely close variants) appear repeatedly across interview experiences.

---

# Operating Systems

## 1. Process vs Thread ⭐⭐⭐⭐⭐

> Explain the difference between a process and a thread.

Follow-up:

* Which has its own address space?
* Which is cheaper to create?
* Which shares memory?
* Context switching cost?

Asked in:

* Infosys
* Oracle
* Perfios
* OFSS
* Numerous interview reports ([GeeksforGeeks][1])

---

## 2. What is a deadlock?

Then

* Four Coffman conditions
* Prevention
* Avoidance
* Detection
* Recovery

---

## 3. Difference between Mutex and Semaphore

Classic interview question.

---

## 4. What is a context switch?

What gets saved?

PCB?

Registers?

Program Counter?

---

## 5. CPU Scheduling

Given

```
P1  BT=8
P2  BT=4
P3  BT=9
P4  BT=5
```

Find

* Waiting Time
* Turnaround Time

using

* FCFS
* SJF
* RR

Very common MCQ.

---

## 6. Virtual Memory

Questions like

> Why do we need virtual memory?

> What is paging?

> Difference between paging and segmentation?

---

## 7. Page Replacement

MCQ

```
FIFO

Reference String

7 0 1 2 0 3 0 4

How many page faults?
```

This exact pattern is common. ([FACE Prep][2])

---

# DBMS

## 1. ACID Properties ⭐⭐⭐⭐⭐

Explain

Atomicity

Consistency

Isolation

Durability

---

## 2. Normalization

Very frequently

```
Is this table in 2NF?

3NF?

BCNF?
```

or

```
Convert this table into 3NF.
```

Appears almost everywhere. ([GeeksforGeeks][1])

---

## 3. SQL Queries

Very common.

Examples

```
Find second highest salary.
```

---

```
Nth highest salary.
```

---

```
Employee

Department

INNER JOIN

LEFT JOIN
```

---

```
GROUP BY

HAVING
```

---

```
Window Functions

ROW_NUMBER()

RANK()
```

---

## 4. Indexes

Difference

B Tree

Hash

Clustered

Non-clustered

---

## 5. Keys

Difference between

Primary

Candidate

Alternate

Composite

Foreign

---

## 6. Transactions

```
Dirty Read

Non Repeatable Read

Phantom Read
```

---

# Computer Networks

## 1. TCP vs UDP ⭐⭐⭐⭐⭐

Almost every report mentions this. ([GeeksforGeeks][3])

---

## 2. Three Way Handshake

Explain

```
SYN

SYN ACK

ACK
```

---

## 3. Four Way Connection Termination

FIN

ACK

---

## 4. HTTP vs HTTPS

---

## 5. DNS

How google.com is resolved.

---

## 6. Socket vs Port

Oracle interview specifically asked

> Difference between port and socket. ([GeeksforGeeks][4])

---

## 7. OSI Model

Typical MCQ

```
Which layer performs routing?

A)

Transport

B)

Network

C)

Application

D)

Data Link
```

---

# OOP

Asked everywhere.

Examples

Difference

```
Overloading

vs

Overriding
```

---

```
Interface

vs

Abstract Class
```

---

```
Composition

vs

Inheritance
```

---

```
Virtual Function?
```

---

```
What is polymorphism?
```

---

```
Diamond Problem?
```

---

# Aptitude

## Quant

Repeated topics

### Time & Work

```
A can finish in 12 days

B in 18 days

Together?
```

---

### Probability

```
Two dice

Probability sum = 8
```

---

### Permutation

```
How many ways

MISSISSIPPI
```

---

### Profit Loss

```
20% gain

10% loss

Net?
```

---

### Speed Distance

```
Train crosses pole

Bridge

Platform
```

---

### Pipes

Classic.

---

### Ratios

---

### SI CI

---

### Ages

---

# Logical Reasoning

Very common.

```
Blood Relation
```

---

```
Coding Decoding

APPLE

→

CRRNG?
```

---

```
Seating Arrangement
```

---

```
Syllogisms

All dogs are animals

Some animals...

```

---

```
Number Series

2 6 12 20 30 ?
```

---

# Technical Aptitude

These surprise many students.

Example

```
What is complexity?

for(i=1;i<n;i++)
   for(j=1;j<n;j++)
```

---

```
Output of C code
```

---

```
Stack trace
```

---

```
Binary tree traversal
```

---

```
Queue operation
```

---

```
Binary Search iterations
```

These are almost identical to technical aptitude rounds used by TCS, Infosys, Capgemini, etc. ([FACE Prep][2])

---

# Real Questions Reported by Candidates

Some interview reports include exact questions:

### Perfios

* Process vs Thread
* TCP vs UDP
* Reverse Linked List
* Sort 0s and 1s
* Level Order Traversal
* Design a database and write SQL queries. ([GeeksforGeeks][3])

---

### Oracle

* Difference between Port and Socket
* Interface vs Abstract Class
* Design Chess using OOP
* AVL Trees
* Red-Black Trees
* Maximum Sum Path in Binary Tree
* Equilibrium Index ([GeeksforGeeks][4])

---

### Infosys

* Four pillars of OOP
* Types of Keys
* Virtual keyword
* File handling
* Difference between C and C++
* SQL joins
* Identify Normal Form ([GeeksforGeeks][1])

---

### Citrix OA

* XOR-based bit manipulation problem
* Technical MCQs from DSA, DBMS, CN, OS
* Aptitude questions ([GeeksforGeeks][5])

---

### Anchanto

* Coin Change
* Weighted Job Scheduling
* SQL queries
* Technical MCQs on C/C++, Java, DBMS, OS, CN ([GeeksforGeeks][6])

---

# Best Sources for Hundreds of Real Questions

These consistently contain actual interview questions shared by candidates:

1. [GeeksforGeeks Interview Experiences](https://www.geeksforgeeks.org/interview-experiences/?utm_source=chatgpt.com)
2. [LeetCode Discuss – Interview Experiences](https://leetcode.com/discuss/interview-experience?utm_source=chatgpt.com)
3. [GeeksforGeeks Core CS Interview Course](https://www.geeksforgeeks.org/courses/core-computer-science-for-interview-preparation?utm_source=chatgpt.com)
4. [StudyBench CS Core Placement Guide](https://www.studybench.in/blog/cs-core-topics-for-placement-interviews?utm_source=chatgpt.com)
5. Reddit communities such as r/developersIndia, r/Btechtards, r/LeetcodeDesi, and r/PlacementsPrep, where candidates often post detailed OA and interview experiences. ([Reddit][7])

If you're preparing for **campus placements or SDE internships**, I can also compile a **"Top 300 Most Repeated CS Theory Questions"** (OS + DBMS + CN + OOP + Aptitude), distilled from hundreds of interview experiences into a single revision document. It would focus only on the questions that recur most often.

[1]: https://www.geeksforgeeks.org/interview-experiences/infosys-certification-interview-experience/?utm_source=chatgpt.com "Infosys Certification Interview Experience - GeeksforGeeks"
[2]: https://faceprep.in/article/ten-technical-interview-aptitude-questions-for-you-set-3/?utm_source=chatgpt.com "10 Technical Aptitude Questions: Set 3 (Solved)"
[3]: https://www.geeksforgeeks.org/interview-experiences/perfios-interview-experience-on-campus-2021/?utm_source=chatgpt.com "Perfios Interview Experience | On-Campus 2021 - GeeksforGeeks"
[4]: https://www.geeksforgeeks.org/interview-experiences/oracle-interview-experience-on-campus-2019/?utm_source=chatgpt.com "Oracle Interview Experience -On Campus (2019) - GeeksforGeeks"
[5]: https://www.geeksforgeeks.org/interview-experiences/citrix-interview-experience-on-campus-2/?utm_source=chatgpt.com "Citrix Interview Experience | (On-Campus) - GeeksforGeeks"
[6]: https://www.geeksforgeeks.org/interview-experiences/anchanto-interview-experience-on-campus-2021/?utm_source=chatgpt.com "Anchanto Interview Experience | On-Campus 2021 - GeeksforGeeks"
[7]: https://www.reddit.com/r/developersIndia/comments/1ujpxs8/people_who_recently_got_a_cs_internship_what_was/?utm_source=chatgpt.com "People who recently got a CS internship, what was your interview like?"

---

> @Web search Focus one by one then. first go for OS, find all actually asked questions you can get. shoud be asked in oa/interview. its important.

I went through interview experiences (Oracle, Cisco, Google, Nvidia, campus placements), Reddit discussions, and OS interview question compilations. A strong pattern emerged:

> **Around 80–90% of OS interview questions come from the same ~40 concepts.** Companies change the wording and depth, but the underlying questions repeat. ([GeeksforGeeks][1])

Below is a consolidated list of **actual questions that candidates reported being asked** in OAs and technical interviews.

---

# Tier 1 (Asked Everywhere) ⭐⭐⭐⭐⭐

These are the highest-frequency OS questions.

## Process & Thread

These appear in nearly every company.

Actual questions:

* What is a process?
* What is a thread?
* Difference between process and thread.
* Why are threads called lightweight processes?
* Does every process have at least one thread?
* What resources are shared between threads?
* What resources are NOT shared?
* When should you use processes instead of threads?
* Which context switch is cheaper, process or thread? Why?
* Can one thread crash another?
* If one thread crashes, what happens to the process?
* User-level threads vs kernel-level threads.
* How are threads scheduled?

Interview reports:

* Cisco
* Oracle
* Nvidia
* Google prep guides
* Infosys
* Numerous campus interviews ([Reddit][2])

---

## Process Lifecycle

Questions:

* Draw process state diagram.
* Difference between Ready and Waiting.
* Can a process go directly from Waiting to Running?
* Zombie process?
* Orphan process?
* Process Control Block (PCB)?
* What information is stored in PCB?
* What happens during `fork()`?
* Difference between `fork()` and `exec()`.

---

## Context Switching

Repeated everywhere.

Questions:

* What is context switching?
* Why is it expensive?
* What is saved during context switch?
* Does switching threads require kernel involvement?
* Hardware role in context switching?
* What triggers a context switch?
* Voluntary vs involuntary context switch.

---

# Tier 2 — CPU Scheduling ⭐⭐⭐⭐⭐

Extremely common.

Questions:

* FCFS
* SJF
* SRTF
* Round Robin
* Priority Scheduling
* Multilevel Queue
* Multilevel Feedback Queue

Calculation questions:

```
P1 BT=8 AT=0
P2 BT=4 AT=1
P3 BT=9 AT=2
P4 BT=5 AT=3

Find

Waiting Time

Turnaround Time

Completion Time
```

MCQs often ask:

* Which scheduling algorithm minimizes average waiting time?
* Which causes starvation?
* Which is preemptive?
* Which is used in time-sharing?
* Effect of quantum size in Round Robin.

---

# Tier 3 — Deadlock ⭐⭐⭐⭐⭐

One of the most repeated interview topics.

Questions:

* What is deadlock?
* Give a real-life example.
* Four Coffman conditions.
* Can deadlock occur with one process?
* Deadlock prevention.
* Deadlock avoidance.
* Detection.
* Recovery.
* Banker's Algorithm.
* Safe state.
* Unsafe state.
* Resource Allocation Graph.
* Wait-for Graph.
* Difference between deadlock and starvation.
* Difference between deadlock and livelock.

---

# Tier 4 — Synchronization ⭐⭐⭐⭐⭐

Actual questions:

* Race condition.
* Critical section.
* Why do race conditions occur?
* Mutex vs Semaphore.
* Binary semaphore vs mutex.
* Counting semaphore.
* Spinlock.
* Monitor.
* Condition Variable.
* Atomic operation.
* Busy waiting.
* Test-and-Set instruction.
* Compare-and-Swap.

Classic problems:

* Producer Consumer
* Readers Writers
* Dining Philosophers
* Sleeping Barber

Interviewers often ask how you would solve one of these using semaphores or mutexes.

---

# Tier 5 — Memory Management ⭐⭐⭐⭐⭐

Repeated in almost every interview.

Questions:

* What is virtual memory?
* Why is virtual memory needed?
* Paging.
* Segmentation.
* Difference between paging and segmentation.
* Logical vs physical address.
* Page table.
* TLB.
* TLB hit ratio.
* Demand paging.
* Page fault.
* Thrashing.
* Working set.
* Internal fragmentation.
* External fragmentation.
* Buddy allocator.

---

# Tier 6 — Page Replacement ⭐⭐⭐⭐

MCQs frequently use numerical problems.

Typical question:

```
Frames = 3

Reference String

7 0 1 2 0 3 0 4 2 3

FIFO

How many page faults?
```

Algorithms:

* FIFO
* LRU
* Optimal
* Clock

Also:

* Bélády's Anomaly.
* Which algorithm is stack-based?
* Why doesn't LRU exhibit Bélády's anomaly?

---

# Tier 7 — System Calls ⭐⭐⭐⭐

Questions:

* What is a system call?
* Examples of system calls.
* User mode vs kernel mode.
* Interrupt vs trap vs exception.
* How does `read()` work internally?
* What happens after a system call?
* Why can't user programs directly access hardware?

---

# Tier 8 — IPC (Inter-Process Communication) ⭐⭐⭐⭐

Questions:

* Why is IPC needed?
* Shared Memory.
* Message Queue.
* Pipe.
* Named Pipe.
* Socket.
* Signal.
* Memory-mapped files.

Comparison questions:

* Pipe vs Socket.
* Shared Memory vs Message Passing.

---

# Tier 9 — File Systems ⭐⭐⭐⭐

Questions:

* What is an inode?
* Hard link vs soft link.
* Directory structure.
* Journaling.
* FAT vs NTFS vs ext4.
* Mounting.
* File descriptor.
* Buffer cache.

---

# Tier 10 — Disk Scheduling ⭐⭐⭐

Questions:

* FCFS
* SSTF
* SCAN
* LOOK
* C-SCAN
* C-LOOK

Calculation questions are common.

---

# Tier 11 — Miscellaneous Concepts ⭐⭐⭐

Questions include:

* Multiprogramming vs multitasking.
* Time-sharing.
* Batch OS.
* Real-time OS (hard vs soft).
* Monolithic kernel vs microkernel.
* Multiprocessing vs multithreading.
* SMP vs AMP.
* NUMA basics.
* Cache affinity / CPU affinity (more common in systems roles). ([GeeksforGeeks][3])

---

# Coding / Practical OS Questions

Occasionally asked in interviews:

* Implement Producer–Consumer.
* Reader–Writer synchronization.
* Implement Semaphore.
* Implement LRU Cache.
* Design Thread Pool.
* Explain `fork()` + `exec()` execution.
* Write code demonstrating deadlock and fix it.

Cisco interview reports also mention implementing an **LRU cache** live, alongside OS questions on mutexes, semaphores, deadlocks, and process vs. thread. ([Reddit][2])

---

# Questions Specifically Reported in Company Interviews

**Oracle**

* Process vs Thread
* Context Switching
* Deadlock
* Scheduling
* Virtual Memory ([Reddit][4])

**Cisco**

* Mutex vs Semaphore
* Process vs Thread
* Deadlock
* OS MCQs in OA ([Reddit][2])

**Google (prep guidance)**

* Processes
* Threads
* Locks
* Mutexes
* Semaphores
* Monitors
* Deadlocks
* Context switching
* Scheduling ([Reddit][5])

**NVIDIA**

* Scheduling
* Virtual Memory
* Paging
* Deadlocks
* Synchronization
* Cache
* Interrupts
* Context Switching ([Reddit][6])

---

## If you only study 30 OS questions...

These cover the overwhelming majority of what appears in interviews:

1. Process vs Thread
2. PCB
3. Process States
4. Context Switch
5. User vs Kernel Threads
6. FCFS
7. SJF
8. Round Robin
9. Priority Scheduling
10. Waiting & Turnaround Time
11. Deadlock
12. Coffman Conditions
13. Banker's Algorithm
14. Mutex vs Semaphore
15. Race Condition
16. Critical Section
17. Producer–Consumer
18. Readers–Writers
19. Virtual Memory
20. Paging
21. Segmentation
22. Page Fault
23. TLB
24. FIFO vs LRU vs Optimal
25. Thrashing
26. System Calls
27. User Mode vs Kernel Mode
28. IPC (Pipes, Shared Memory, Message Queues)
29. Inodes & Hard vs Soft Links
30. Monolithic vs Microkernel

This is the "high-yield" OS set that repeatedly appears across campus OAs, SDE interviews, and systems-focused interviews according to recent interview experiences and preparation resources. ([GeeksforGeeks][1])

[1]: https://www.geeksforgeeks.org/operating-systems/operating-systems-interview-questions/?utm_source=chatgpt.com "Operating System Interview Questions - GeeksforGeeks"
[2]: https://www.reddit.com/r/InterviewCoderHQ/comments/1uhl0p9/cisco_swe_internship_interview_2026_passed_all_3/?utm_source=chatgpt.com "Cisco SWE Internship Interview 2026 [Passed All 3 Rounds]"
[3]: https://www.geeksforgeeks.org/operating-systems/process-management-interview-questions/?utm_source=chatgpt.com "Process Management Interview Questions - Operating System - GeeksforGeeks"
[4]: https://www.reddit.com/r/Btechtards/comments/1udn22n/oracle_oa_interview_experience_it_was_crazy/?utm_source=chatgpt.com "Oracle (OA + Interview Experience) — It Was Crazy"
[5]: https://www.reddit.com/r/leetcode/comments/1hnloo1?utm_source=chatgpt.com "Does Google actually ask OS questions for interns?"
[6]: https://www.reddit.com/r/leetcode/comments/1qpkhpt/nvidia_sw_interview/?utm_source=chatgpt.com "Nvidia SW Interview"

---

> @Web search Now gather for DBMS, again, focus that things should be actually asked before.

After looking through **candidate interview experiences**, **OA reports**, **GeeksforGeeks interview archives**, and **Reddit placement discussions**, one thing is very clear:

> **DBMS interviews are much more repetitive than DSA.** Roughly 80% of questions come from the same concepts, and many companies ask nearly identical questions. ([GeeksforGeeks][1])

Below is a list of **questions that have actually been reported by candidates**, organized by frequency.

---

# Tier 1 (Asked Almost Everywhere) ⭐⭐⭐⭐⭐

These should be considered mandatory.

---

## 1. Normalization

Probably the #1 DBMS interview topic.

Actual questions:

* What is normalization?
* Why do we normalize?
* Explain 1NF.
* Explain 2NF.
* Explain 3NF.
* Explain BCNF.
* Difference between 3NF and BCNF.
* Given a table, normalize it to 3NF.
* What anomalies does normalization remove?
* When should you denormalize?

Interview reports repeatedly mention interviewers asking candidates to identify the normal form of a table or normalize a schema. ([GeeksforGeeks][1])

---

## 2. ACID Properties

Very frequently asked.

Questions

* What is a transaction?
* Explain ACID.
* Why is Atomicity important?
* Difference between Consistency and Isolation.
* Give a real-life example of Atomicity.
* What happens if Durability fails?

Recent TCS interview experiences specifically mention ACID as one of the first DBMS questions. ([Reddit][2])

---

## 3. Keys

Questions

* Primary Key
* Candidate Key
* Super Key
* Alternate Key
* Composite Key
* Foreign Key

Common follow-ups

* Can Primary Key be NULL?
* Can Foreign Key be NULL?
* Difference between Candidate and Primary Key.
* Difference between Primary Key and Unique Key.

---

## 4. SQL Queries

Probably every interview.

Repeated questions

### Second Highest Salary

```sql
Find the second highest salary.
```

---

### Nth Highest Salary

---

### Duplicate Rows

```sql
Find duplicate rows.
```

---

### Employees earning more than manager

---

### Customers without orders

---

### Department-wise highest salary

---

### Average salary department-wise

---

### Delete duplicate rows

---

### Consecutive records

---

### Running total

---

### Window Functions

Questions

* ROW_NUMBER()
* RANK()
* DENSE_RANK()

The "second highest salary" problem is one of the most frequently reported SQL interview questions. ([GeeksforGeeks][3])

---

# Tier 2 (Very Frequently Asked) ⭐⭐⭐⭐

---

## JOINs

Questions

Difference between

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN
* CROSS JOIN
* SELF JOIN

Interviewers often draw two tables and ask you to sketch the output.

---

## GROUP BY

Questions

Difference between

```sql
WHERE

HAVING

GROUP BY
```

Typical question

```sql
Find departments having more than five employees.
```

---

## DELETE vs TRUNCATE vs DROP

One of the most repeated interview questions.

Expected comparison

* Rollback?
* Logging?
* Removes structure?
* Removes data?
* Speed?

Recent TCS interview reports specifically mention **DELETE vs TRUNCATE** being asked. ([Reddit][2])

---

## UNION vs UNION ALL

Questions

Difference?

Duplicates?

Performance?

---

## EXISTS vs IN

Frequently reported.

---

## CHAR vs VARCHAR

Very common for Oracle/MySQL roles. ([GeeksforGeeks][4])

---

# Tier 3 (Transactions & Concurrency) ⭐⭐⭐⭐

---

## Concurrency Control

Questions

* Why is concurrency needed?
* Lost Update
* Dirty Read
* Phantom Read
* Non-repeatable Read

---

## Isolation Levels

Questions

Explain

* Read Uncommitted
* Read Committed
* Repeatable Read
* Serializable

Follow-up

Which anomalies does each prevent?

---

## Locks

Questions

* Shared Lock
* Exclusive Lock
* Intention Lock
* Lock Granularity

---

## Deadlock

Questions

Can databases have deadlocks?

How are they detected?

How are they prevented?

---

# Tier 4 (Indexing) ⭐⭐⭐⭐

One of the favorite interview topics.

Questions

* What is an Index?
* Why use Index?
* Why not create indexes everywhere?
* Clustered Index
* Non-clustered Index
* Composite Index
* Covering Index

Follow-up

When does an index hurt performance?

---

## B+ Tree

Very common.

Questions

* Why B+ Tree?
* Why not Binary Search Tree?
* Why not Hash Table?
* Why do databases prefer B+ Trees?

---

# Tier 5 (ER Model) ⭐⭐⭐⭐

Questions

* Entity
* Attribute
* Relationship
* Weak Entity
* Cardinality
* Participation
* ER Diagram

Often

> Draw ER diagram for Library.

or

> Design Student-Course database.

---

# Tier 6 (Database Design) ⭐⭐⭐

Questions

Design

* Banking database
* Hospital database
* Library
* Food delivery
* College Management
* Airline Reservation

Interviewers then ask

* Primary keys?
* Foreign keys?
* Normalization?
* Relationships?

---

# Tier 7 (Functions & SQL Internals) ⭐⭐⭐

Questions

* Stored Procedure
* Trigger
* View
* Materialized View
* Cursor
* Function

Common follow-up

Difference between View and Materialized View.

---

# Tier 8 (Architecture) ⭐⭐⭐

Questions

* DBMS vs RDBMS
* Schema vs Instance
* Logical vs Physical Schema
* Data Independence
* Three Schema Architecture

---

# Tier 9 (Unexpected but Reported)

These appear less often but are worth knowing.

---

## Query Execution

Real question reported

> How does a SQL database engine execute a query?

One interviewee shared being asked to explain what happens internally after a SQL query is issued. ([Reddit][5])

---

## Query Optimization

Questions

* Why is one query faster?
* Explain execution plan.
* Full Table Scan.
* Index Scan.

---

## CAP Theorem

Occasionally asked for backend roles.

---

# SQL Coding Questions Reported Repeatedly

These problems appear again and again:

| Problem                        | Frequency |
| ------------------------------ | --------- |
| Second Highest Salary          | ⭐⭐⭐⭐⭐     |
| Nth Highest Salary             | ⭐⭐⭐⭐⭐     |
| Duplicate Rows                 | ⭐⭐⭐⭐      |
| Department-wise Highest Salary | ⭐⭐⭐⭐      |
| Employee > Manager Salary      | ⭐⭐⭐⭐      |
| Customers without Orders       | ⭐⭐⭐⭐      |
| Top N Salaries                 | ⭐⭐⭐⭐      |
| Consecutive Dates              | ⭐⭐⭐       |
| Running Total                  | ⭐⭐⭐       |
| Dense Rank                     | ⭐⭐⭐⭐      |
| Find Missing Records           | ⭐⭐⭐       |
| Remove Duplicates              | ⭐⭐⭐⭐      |

These are common enough that many interview preparation sites include them verbatim. ([GeeksforGeeks][3])

---

# Questions Specifically Reported by Companies

### TCS

Reported questions:

* DELETE vs TRUNCATE
* Normalization
* Where would you use normalization?
* ACID Properties
* SQL queries from projects ([Reddit][2])

---

### Infosys

Repeated reports mention:

* SQL queries
* Normal Forms
* Joins
* Keys
* DBMS basics ([Reddit][6])

---

### Oracle

Reported questions include:

* Indexes
* Joins
* Normalization
* Transactions
* SQL query writing ([GeeksforGeeks][1])

---

# If You Only Study 30 DBMS Questions

These provide excellent coverage for campus placements and SDE interviews:

1. DBMS vs RDBMS
2. Schema vs Instance
3. Three-schema architecture
4. Primary Key
5. Candidate Key
6. Foreign Key
7. Composite Key
8. Super Key
9. Functional Dependency
10. 1NF
11. 2NF
12. 3NF
13. BCNF
14. Denormalization
15. ACID Properties
16. Transactions
17. Isolation Levels
18. Deadlock in DBMS
19. Indexes
20. Clustered vs Non-clustered Index
21. B+ Tree
22. INNER/LEFT/RIGHT/FULL JOIN
23. GROUP BY vs HAVING
24. DELETE vs TRUNCATE vs DROP
25. UNION vs UNION ALL
26. EXISTS vs IN
27. Second Highest Salary (SQL)
28. Window Functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`)
29. Views vs Materialized Views
30. Stored Procedures vs Triggers

This set aligns closely with what candidates consistently report across OAs and technical interviews and will prepare you for the majority of DBMS discussions in placements.

[1]: https://www.geeksforgeeks.org/dbms/commonly-asked-dbms-interview-questions/?utm_source=chatgpt.com "DBMS Interview Questions with Answers - GeeksforGeeks"
[2]: https://www.reddit.com/r/PlacementsPrep/comments/1sihnyo/finally/?utm_source=chatgpt.com "Finally"
[3]: https://www.geeksforgeeks.org/dbms/commonly-asked-dbms-interview-questions-set-2/?utm_source=chatgpt.com "Commonly asked DBMS Interview Questions | Set 2 - GeeksforGeeks"
[4]: https://www.geeksforgeeks.org/sql/sql-interview-questions/?utm_source=chatgpt.com "SQL Interview Questions - DBMS - GeeksforGeeks"
[5]: https://www.reddit.com/r/developersIndia/comments/13jbh7o?utm_source=chatgpt.com "Interview experience"
[6]: https://www.reddit.com/r/infosys/comments/1toikg0/infosys_dse_interview/?utm_source=chatgpt.com "Infosys DSE interview"

---

> @Web search OOP now

After reviewing **recent interview experiences**, **campus placement reports**, **Reddit discussions**, and **OOP interview compilations**, OOP has the **smallest and most repetitive question pool** among the CS core subjects.

Unlike OS or DBMS, interviewers usually don't ask obscure OOP theory. They ask **basic concepts, followed by design trade-offs and small coding scenarios.** ([GeeksforGeeks][1])

---

# Tier 1 — Asked in Almost Every Interview ⭐⭐⭐⭐⭐

These are the questions that appear repeatedly across Infosys, Oracle, SAP, Goldman Sachs, OFSS, and many campus interviews.

---

## 1. What is OOP?

Usually followed by:

* Why OOP?
* Advantages over procedural programming?
* Real-world example?
* Why Java/C++ are object-oriented?

---

## 2. Four Pillars of OOP ⭐⭐⭐⭐⭐

Probably the most asked OOP question.

Interviewers ask:

* Explain Encapsulation.
* Explain Abstraction.
* Explain Inheritance.
* Explain Polymorphism.

Then immediately ask

> Give a real-life example.

or

> Give a coding example.

This is reported in multiple SAP Labs and AppViewX interview experiences. ([GeeksforGeeks][2])

---

# Encapsulation

Actual follow-ups

* Why use private members?
* Can encapsulation exist without classes?
* Difference between encapsulation and data hiding?
* Why getters/setters?

---

# Abstraction

Questions

* What is abstraction?
* Why abstract?
* Abstract class vs abstraction.
* Can abstraction exist without abstract class?

---

# Inheritance

Questions

* Why inheritance?
* Types of inheritance.
* Why Java doesn't support multiple inheritance through classes?
* Diamond Problem.
* Method inheritance.

---

# Polymorphism

Questions

* Compile-time polymorphism.
* Runtime polymorphism.
* Function overloading.
* Function overriding.
* Dynamic dispatch.
* Virtual function.

---

# Tier 2 — Class Relationships ⭐⭐⭐⭐⭐

---

## Abstract Class vs Interface

Probably the single most repeated comparison question.

Interviewers ask

* Difference?
* When to use interface?
* When to use abstract class?
* Can interface have methods?
* Can interface have variables?
* Multiple inheritance?

This appears in Infosys and SAP interview reports. ([Reddit][3])

---

## Composition vs Inheritance

Repeated especially in product companies.

Questions

* "Has-a" vs "Is-a"
* Which is better?
* When should you avoid inheritance?

---

## Association

Questions

Difference between

* Association
* Aggregation
* Composition

Almost always accompanied by a UML-style example.

---

# Tier 3 — Overloading & Overriding ⭐⭐⭐⭐⭐

Another favorite.

Questions

Difference between

* Method Overloading
* Method Overriding

Follow-ups

* Return type?
* Access modifier?
* Static methods?
* Private methods?
* Constructor overloading?
* Operator overloading?

---

# Tier 4 — Constructors ⭐⭐⭐⭐

Questions

* Default constructor
* Parameterized constructor
* Copy constructor (C++)
* Constructor overloading
* Constructor chaining
* Destructor (C++)
* Why constructor cannot be virtual?

---

# Tier 5 — Access Specifiers ⭐⭐⭐⭐

Frequently reported in SAP interviews.

Questions

Difference between

* Public
* Private
* Protected

Follow-ups

* Can private methods be inherited?
* Can protected members be accessed outside package?
* Which access modifier is default?

SAP Labs interviewers specifically asked multiple variations involving C++ access specifiers. ([GeeksforGeeks][2])

---

# Tier 6 — Static vs Dynamic ⭐⭐⭐⭐

Questions

* Static variable
* Static method
* Static binding
* Dynamic binding
* Early binding
* Late binding

---

# Tier 7 — Virtual Functions (C++) ⭐⭐⭐⭐

Questions

* Why virtual?
* Vtable?
* Runtime polymorphism?
* Pure virtual function?
* Abstract class?

---

# Tier 8 — Memory & Object Lifetime ⭐⭐⭐

Questions

* Stack vs Heap objects
* new vs malloc
* delete vs free
* Constructor call order
* Destructor call order

Mostly C++ interviews.

---

# Tier 9 — SOLID Principles ⭐⭐⭐

Increasingly common in backend interviews.

Questions

Explain

* Single Responsibility
* Open Closed
* Liskov Substitution
* Interface Segregation
* Dependency Inversion

Sometimes

> Give real example.

---

# Tier 10 — Scenario-Based Questions ⭐⭐⭐⭐

Instead of theory, interviewers often ask

---

## Design a Library

Classes?

Inheritance?

Composition?

---

## Design Parking Lot

---

## Design ATM

---

## Design Vending Machine

Oracle interview reports mention explaining a **vending machine interface**, focusing on OOP design rather than implementation. ([GeeksforGeeks][4])

---

## Design Chess

Frequently reported.

---

## Design Student Management

---

## Design Online Shopping Cart

---

## Design Bank Account

---

# Tier 11 — Small Coding Questions

Sometimes interviewers ask you to write code.

Examples

Implement

```cpp
Animal

Dog

Cat
```

Demonstrate

* Inheritance
* Overriding
* Runtime polymorphism

---

Implement

```cpp
Shape

Circle

Rectangle
```

---

Implement

```cpp
Employee

Manager
```

---

Implement

```cpp
Vehicle

Bike

Car
```

---

# MCQs Frequently Seen in OAs

Examples

---

### Which pillar hides implementation?

A) Inheritance

B) Encapsulation

C) Abstraction

D) Polymorphism

---

### Which supports runtime polymorphism?

A) Overloading

B) Overriding

C) Templates

D) Constructor

---

### Java supports multiple inheritance through?

A) Classes

B) Interface

C) Objects

D) Packages

---

### Which relationship is "Has-A"?

---

### Which keyword prevents inheritance?

---

### Which member cannot be overridden?

---

# Questions Specifically Reported by Companies

### Infosys

Reported questions

* Abstract class vs Interface
* Inheritance
* Project discussion using OOP concepts ([Reddit][3])

---

### SAP Labs

Reported

* Access specifiers
* Abstract class
* Interface
* OOP fundamentals ([GeeksforGeeks][2])

---

### AppViewX

Reported

* Four pillars of OOP
* Real-life examples
* Instagram feature design using OOP ([GeeksforGeeks][5])

---

### OFSS

Reported

* Basic OOP concepts in OA MCQs
* Output-based OOP questions
* Language-specific OOP fundamentals ([GeeksforGeeks][6])

---

### Goldman Sachs

Reported

* OA MCQs on OOP fundamentals alongside OS and DSA. ([GeeksforGeeks][7])

---

# If You Only Study 25 OOP Questions

These cover the overwhelming majority of interview questions:

1. What is OOP?
2. Advantages of OOP
3. Object vs Class
4. Encapsulation
5. Abstraction
6. Inheritance
7. Polymorphism
8. Data Hiding vs Encapsulation
9. Abstract Class vs Interface
10. Method Overloading vs Overriding
11. Compile-time vs Runtime Polymorphism
12. Association vs Aggregation vs Composition
13. Composition vs Inheritance
14. Access Specifiers
15. Static vs Dynamic Binding
16. Virtual Functions
17. Constructors
18. Destructors
19. Copy Constructor (C++)
20. Diamond Problem
21. Multiple Inheritance
22. SOLID Principles (basics)
23. Design a Parking Lot/Library/ATM using OOP
24. UML basics (class relationships)
25. Write a small inheritance hierarchy (e.g., `Shape`, `Vehicle`, `Employee`) demonstrating overriding and polymorphism.

### A notable trend

One recurring theme in recent interview experiences is that **many interviewers move beyond definitions**. After asking "What is encapsulation?" or "Interface vs abstract class?", they often follow with a prompt like:

> "Design a small system (ATM, Parking Lot, Vending Machine, Library) and explain why you chose inheritance, composition, or interfaces."

Being able to **apply** OOP concepts in a simple design discussion is often more valuable than memorizing definitions. ([Reddit][8])

[1]: https://www.geeksforgeeks.org/interview-prep/oops-interview-questions/?utm_source=chatgpt.com "OOP Interview Questions and Answers - GeeksforGeeks"
[2]: https://www.geeksforgeeks.org/interview-experiences/sap-labs-interview-experience-on-campus/?utm_source=chatgpt.com "SAP Labs Interview Experience (On-Campus) - GeeksforGeeks"
[3]: https://www.reddit.com/r/PlacementsPrep/comments/1t01fla/infosys_dse_interview_experience_oncampus_kolkata/?utm_source=chatgpt.com "Infosys DSE Interview Experience (On-Campus Kolkata) – Questions & Process"
[4]: https://www.geeksforgeeks.org/interview-experiences/company-name-interview-experience-for-job-title-65/?utm_source=chatgpt.com "Oracle On-Campus SDE Interview Experience - GeeksforGeeks"
[5]: https://origin.geeksforgeeks.org/interview-experiences/appviewx-interview-experience-for-rd-engineer-on-campus-2021/?utm_source=chatgpt.com "AppViewX Interview Experience for R&D Engineer | On-Campus 2021 - GeeksforGeeks"
[6]: https://www.geeksforgeeks.org/interview-experiences/ofss-interview-experience-on-campus-for-apps-profile/?utm_source=chatgpt.com "OFSS Interview Experience (On-Campus for APPS profile) - GeeksforGeeks"
[7]: https://www.geeksforgeeks.org/interview-experiences/goldman-sachs-internship-interview-experience-on-campus-4/?utm_source=chatgpt.com "Goldman Sachs Internship Interview Experience (On-Campus) - GeeksforGeeks"
[8]: https://www.reddit.com/r/cscareeradvice/comments/1t9w1ru/learned_oop_from_kunal_kushwaha_understood_the/?utm_source=chatgpt.com "Learned OOP from Kunal Kushwaha understood the theory but failed in interviews when asked to code. How should I actually master OOP?"

---

> @Web search Computer Networks now

After searching through **actual interview experiences (Cisco, TCS, network engineer roles, SDE interviews), Reddit discussions, and CN interview archives**, Computer Networks turns out to be one of the most standardized CS subjects.

> **Most interviews repeatedly ask the same 30–40 networking questions.** The wording changes, but the concepts are remarkably consistent. ([GeeksforGeeks][1])

---

# Tier 1 (Asked in Almost Every Interview) ⭐⭐⭐⭐⭐

---

# 1. OSI Model

This is **the most frequently asked CN question**.

Actual questions:

* Explain the OSI Model.
* Explain each layer.
* Why do we need layers?
* Which layer does routing happen in?
* Which layer handles encryption?
* Which layer performs error detection?
* Which layer is responsible for reliable communication?
* Give examples of protocols at each layer.
* What data unit (PDU) exists at each layer?

  * Bits
  * Frames
  * Packets
  * Segments

Very common follow-up:

> "What happens at every OSI layer when you open [www.google.com](http://www.google.com)?"

This exact question appears in Cisco interviews and is recommended by interviewers on Reddit. ([GeeksforGeeks][2])

---

# 2. TCP vs UDP ⭐⭐⭐⭐⭐

Probably the second most asked question.

Actual questions

* Difference between TCP and UDP.
* Which is faster?
* Why is TCP reliable?
* Why is UDP faster?
* Why does video streaming use UDP?
* Why does HTTP use TCP?
* Can UDP be made reliable?
* Which header is larger?
* Which consumes more bandwidth?

Interviewers almost always ask:

> "When would you choose UDP over TCP?"

Appears in Cisco, TCS, and many placement interviews. ([GeeksforGeeks][3])

---

# 3. Three-Way Handshake ⭐⭐⭐⭐⭐

Questions

* Explain SYN.
* Explain SYN-ACK.
* Explain ACK.
* Why are three steps needed?
* Why not two?
* Why not four?
* What sequence numbers are used for?

Follow-up

* What is connection establishment?
* What happens if ACK is lost?

---

# 4. Four-Way Connection Termination

Questions

* Why four packets?
* Why not three?
* TIME_WAIT?
* FIN_WAIT?
* CLOSE_WAIT?

---

# 5. What happens when you type a URL?

This is one of the most common end-to-end questions.

Interviewers ask:

> Explain everything after typing:

```text
https://www.google.com
```

Expected flow

1. Browser cache
2. DNS lookup
3. ARP (if needed)
4. TCP handshake
5. TLS handshake
6. HTTP request
7. Routing
8. Response
9. Rendering

Cisco interview experiences explicitly report this question. ([GeeksforGeeks][2])

---

# Tier 2 (Very Frequently Asked) ⭐⭐⭐⭐

---

# 6. DNS

Questions

* What is DNS?
* How does DNS work?
* Recursive vs iterative lookup.
* What is DNS cache?
* Root server?
* TLD server?
* Authoritative server?

---

# 7. HTTP vs HTTPS

Questions

Difference?

Encryption?

SSL?

TLS?

Certificates?

Port numbers?

---

# 8. IP Address

Questions

Difference between

IPv4

IPv6

Private IP

Public IP

Loopback

Broadcast

---

# 9. Subnetting

Extremely common in Cisco/network-oriented roles.

Questions

* Why subnet?
* CIDR
* Calculate network address
* Calculate broadcast address
* Number of hosts

Cisco interview reports specifically mention subnetting and supernetting. ([GeeksforGeeks][4])

---

# 10. Routers vs Switches vs Hubs

Questions

Difference

Hub

Switch

Router

Bridge

Gateway

Repeats across network engineering interviews. ([GeeksforGeeks][5])

---

# Tier 3 (Protocols) ⭐⭐⭐⭐

---

## ARP

Questions

* Why ARP?
* ARP Request
* ARP Reply
* ARP Cache

---

## ICMP

Questions

* What is ICMP?
* How does ping work?
* Does ping use TCP?
* Does ping use UDP?

---

## DHCP

Questions

* What is DHCP?
* Why DHCP?
* DHCP Discover
* Offer
* Request
* ACK

Cisco interview reports mention explaining DHCP in detail. ([GeeksforGeeks][4])

---

## NAT

Questions

* Why NAT?
* Advantages
* Private IP to Public IP
* PAT

---

## FTP

Questions

Difference

Active

Passive

---

## SMTP

POP3

IMAP

Frequently asked in service-based companies.

---

# Tier 4 (Routing) ⭐⭐⭐⭐

Questions

* Routing
* Static Routing
* Dynamic Routing
* Distance Vector
* Link State
* RIP
* OSPF

Follow-up

How does a router decide where to send packets?

---

# Tier 5 (Error & Flow Control) ⭐⭐⭐⭐

Questions

* Flow Control
* Congestion Control
* Sliding Window
* Stop-and-Wait
* Go-Back-N
* Selective Repeat

Cisco interview reports specifically mention **Go-Back-N**. ([GeeksforGeeks][4])

---

# Tier 6 (Data Link Layer) ⭐⭐⭐

Questions

* MAC Address
* Frame
* CRC
* Error Detection
* Error Correction

---

# Tier 7 (Application Layer) ⭐⭐⭐

Questions

HTTP

HTTPS

FTP

SMTP

POP3

IMAP

DNS

DHCP

SSH

Telnet

SNMP

---

# Tier 8 (Practical Questions) ⭐⭐⭐

Interviewers increasingly ask practical networking questions.

Examples

* What does ping do?
* traceroute vs ping
* Why ping works even if HTTP fails?
* How does Wi-Fi work?
* Why can't two devices have the same IP?
* Why can't two devices have the same MAC?

Cisco manager interviews specifically asked **"How does Wi-Fi work in your home?"** ([GeeksforGeeks][2])

---

# MCQs Frequently Seen in OAs

Examples

---

### Which protocol is connection-oriented?

A TCP

B UDP

C IP

D ICMP

---

### Which layer performs routing?

A Transport

B Network

C Data Link

D Session

---

### Which protocol resolves IP to MAC?

A DNS

B DHCP

C ARP

D ICMP

---

### Default HTTP port?

80

---

### HTTPS?

443

---

### Which protocol is used by ping?

ICMP

---

### Which protocol guarantees ordered delivery?

TCP

---

### Which protocol uses sequence numbers?

TCP

---

# Questions Specifically Reported by Companies

### Cisco

Reported questions

* OSI model
* TCP vs UDP
* HTTP vs HTTPS
* Routing
* Switching
* Frame vs Packet
* Data Link Layer
* Physical Layer
* DHCP
* Subnetting
* Go-Back-N
* Explain what happens after typing a URL. ([GeeksforGeeks][2])

---

### TCS

Reported questions

* OSI layers
* Ping command
* Basic networking concepts
* Transport layer responsibilities
* TCP vs UDP. ([Reddit][6])

---

### Freshers / SDE Interviews

Candidates repeatedly report being asked:

* OSI
* TCP/IP
* TCP vs UDP
* DNS
* Three-way handshake
* "Explain what happens when you enter a URL."
* Ping
* Traceroute
* Routers vs Switches. ([Reddit][7])

---

# If You Only Study 30 CN Questions

These cover the vast majority of networking interviews:

1. OSI Model
2. TCP/IP Model
3. OSI vs TCP/IP
4. TCP vs UDP
5. Three-Way Handshake
6. Four-Way Termination
7. What happens when you type a URL?
8. DNS
9. HTTP vs HTTPS
10. SSL vs TLS
11. IPv4 vs IPv6
12. Public vs Private IP
13. MAC Address vs IP Address
14. ARP
15. ICMP
16. Ping
17. Traceroute
18. DHCP
19. NAT
20. Router vs Switch vs Hub vs Bridge
21. Subnetting (CIDR basics)
22. Routing vs Forwarding
23. Static vs Dynamic Routing
24. RIP vs OSPF (basic idea)
25. Flow Control vs Congestion Control
26. Sliding Window
27. Go-Back-N vs Selective Repeat
28. FTP vs SFTP
29. SMTP vs POP3 vs IMAP
30. Ports (20/21, 22, 25, 53, 67/68, 80, 110, 143, 443)

## One question worth mastering

Across Reddit discussions, Cisco experiences, and interviewer advice, the single question that stands out is:

> **"Explain everything that happens from the moment you type `https://www.google.com` into your browser until the page appears."**

Answering this well naturally demonstrates your understanding of **DNS, ARP, TCP, TLS, HTTP, routing, switching, IP addressing, and the OSI model**—which is why many interviewers use it as a comprehensive networking question. ([Reddit][7])

[1]: https://www.geeksforgeeks.org/computer-networks/commonly-asked-computer-networks-interview-questions-set-1/?utm_source=chatgpt.com "Commonly asked Computer Networks Interview Questions - GeeksforGeeks"
[2]: https://www.geeksforgeeks.org/interview-experiences/cisco-interview-experience-for-summer-intern-off-campus/?utm_source=chatgpt.com "CISCO Interview experience For Summer Intern (Off-campus) - GeeksforGeeks"
[3]: https://www.geeksforgeeks.org/interview-experiences/cisco-interview-experience-for-internship-fte-on-campus-2021/?utm_source=chatgpt.com "Cisco Interview Experience for Internship + FTE | On-Campus 2021 - GeeksforGeeks"
[4]: https://www.geeksforgeeks.org/interview-experiences/cisco-interview-set-6/?utm_source=chatgpt.com "Cisco Interview | Set 6 - GeeksforGeeks"
[5]: https://www.geeksforgeeks.org/interview-experiences/cisco-interview-experience-for-network-engineer-on-campus-2021/?utm_source=chatgpt.com "Cisco Interview Experience for Network Engineer (On-Campus) 2021 - GeeksforGeeks"
[6]: https://www.reddit.com/r/PlacementsPrep/comments/1troypq/got_my_tcs_ninja_offer_letter_via_hackquest/?utm_source=chatgpt.com "Got my TCS Ninja Offer Letter via HackQuest Season 10! Interview Experience (Cybersec/Networks/AI focus)"
[7]: https://www.reddit.com/r/developersIndia/comments/10770p1?utm_source=chatgpt.com "About Computer Networks"

---

> additionals

For **SDE internships/fresher placements**, you've already covered the **four major Core CS subjects**:

1. ✅ Operating Systems
2. ✅ DBMS
3. ✅ Computer Networks
4. ✅ OOP

These four account for **the overwhelming majority of Core CS interview questions** at companies like Amazon, Microsoft, Oracle, Adobe, Cisco, Goldman Sachs, Infosys, TCS, etc. ([geeksforgeeks.org][1])

However, there are a few additional subjects that appear depending on the company and role.

---

# 1. Computer Organization & Architecture (COA) ⭐⭐⭐⭐

This is the next most common subject after the "big four."

It appears frequently in:

* Qualcomm
* NVIDIA
* Intel
* AMD
* Cisco
* Oracle
* Samsung
* Embedded/System Software roles

Typical questions actually reported:

* Cache vs Main Memory
* Cache Mapping
* Direct Mapping
* Associative Mapping
* Virtual Memory vs Cache
* Pipelining
* Hazards
* Branch Prediction
* RISC vs CISC
* Von Neumann vs Harvard
* Registers
* Interrupts
* DMA
* Endianness
* Assembly basics
* Addressing Modes

Qualcomm's OA explicitly included technical MCQs from OS, CN, DBMS, OOP, and C programming, with COA concepts commonly appearing in such hardware-oriented roles. ([geeksforgeeks.org][2])

---

# 2. Compiler Design ⭐⭐⭐

Less common, but definitely asked.

Reported questions:

* Lexical Analysis
* Parser
* Token
* DFA vs NFA
* Regular Expression
* Symbol Table
* Intermediate Code
* Phases of Compiler
* Syntax Tree

Reddit interview experiences mention candidates being asked Compiler Design and Theory of Computation questions, especially when interviewers wanted to probe CS fundamentals beyond the usual four subjects. ([Reddit][3])

---

# 3. Theory of Computation (TOC) ⭐⭐

Mostly for:

* Oracle
* Research
* Compiler
* Higher-end product companies

Questions include:

* DFA
* NFA
* Regular Expressions
* PDA
* CFG
* Turing Machine
* Chomsky Hierarchy

Usually only 1–2 questions.

---

# 4. Software Engineering ⭐⭐⭐

This has become more common recently.

Typical questions:

* SDLC
* Agile vs Waterfall
* Scrum
* Git workflow
* Testing
* Unit vs Integration Testing
* Functional vs Non-functional Requirements
* Design Patterns (basic)

Some recent placement preparation guides now explicitly include Software Engineering alongside OS, DBMS, CN, and OOP for freshers. ([geeksforgeeks.org][4])

---

# 5. C/C++ Language Internals ⭐⭐⭐⭐

Many OAs include language-specific MCQs.

Common questions:

* Pointer vs Reference
* `malloc()` vs `new`
* `free()` vs `delete`
* `const`
* `volatile`
* Memory layout
* Stack vs Heap
* Virtual Functions
* Vtable
* Copy Constructor
* Move Constructor (modern C++)
* Shallow vs Deep Copy

Qualcomm, Oracle, and OFSS interview reports frequently mention C/C++ output and concept questions. ([geeksforgeeks.org][2])

---

# 6. SQL (Beyond DBMS) ⭐⭐⭐⭐⭐

Although SQL is part of DBMS, companies often treat it as its own assessment.

Typical questions:

* Write SQL
* Optimize SQL
* Window Functions
* Recursive CTE
* Index usage
* Execution order

Many backend interviews spend more time on SQL than on DBMS theory.

---

# 7. Operating System + Linux Commands ⭐⭐

Sometimes asked:

* `grep`
* `chmod`
* `ps`
* `kill`
* `fork`
* `top`
* `lsof`
* `netstat`
* Environment variables

Mostly in backend, DevOps, and infrastructure interviews.

---

# 8. Basic System Design ⭐⭐⭐

This has become increasingly common even for freshers.

Questions like:

* Design Parking Lot
* Design Library
* Design URL Shortener
* Design Chat App
* Design Cache
* Design TinyURL

Usually not distributed systems—more often Low-Level Design (LLD).

---

# 9. Aptitude & Logical Reasoning ⭐⭐⭐⭐

Still common in OAs for:

* TCS
* Infosys
* Capgemini
* Cognizant
* Qualcomm
* Accenture

Topics:

* Probability
* Time & Work
* Number Series
* Seating Arrangement
* Coding-Decoding
* Data Interpretation
* Ratios
* Speed & Distance

Qualcomm's OA, for example, explicitly included aptitude along with technical MCQs. ([geeksforgeeks.org][2])

---

# If you're targeting SDE internships at product companies

I would prioritize subjects in this order:

| Priority | Subject                              | Importance |
| -------- | ------------------------------------ | ---------- |
| 1        | DSA                                  | ⭐⭐⭐⭐⭐      |
| 2        | DBMS                                 | ⭐⭐⭐⭐⭐      |
| 3        | Operating Systems                    | ⭐⭐⭐⭐⭐      |
| 4        | Computer Networks                    | ⭐⭐⭐⭐       |
| 5        | OOP                                  | ⭐⭐⭐⭐       |
| 6        | SQL                                  | ⭐⭐⭐⭐       |
| 7        | Computer Organization & Architecture | ⭐⭐⭐        |
| 8        | C/C++ language internals             | ⭐⭐⭐        |
| 9        | Basic System Design                  | ⭐⭐⭐        |
| 10       | Aptitude                             | ⭐⭐⭐        |
| 11       | Software Engineering                 | ⭐⭐         |
| 12       | Compiler Design / TOC                | ⭐⭐         |

### For your preparation

Given that you're targeting **software engineering roles**, I would recommend continuing in this order:

1. **COA** — the last major CS core subject that still appears regularly, especially in product companies.
2. **SQL** — focus on real interview query-writing questions.
3. **C/C++ internals** (or Java internals if interviewing in Java).
4. **Low-Level Design (LLD)** — increasingly common in fresher interviews.

Compiler Design and Theory of Computation are worth reviewing if you're applying to companies known for deeper CS interviews (e.g., Oracle, Qualcomm, NVIDIA) or compiler/systems roles, but they are much less common than the first six subjects. ([geeksforgeeks.org][4])

[1]: https://www.geeksforgeeks.org/computer-science-fundamentals/computer-science-subjects-interview-questions/?utm_source=chatgpt.com "Computer Science Subjects Interview Questions - GeeksforGeeks"
[2]: https://www.geeksforgeeks.org/interview-experiences/qualcomm-interview-experience-on-campus-3/?utm_source=chatgpt.com "Qualcomm Interview Experience (On-Campus) - GeeksforGeeks"
[3]: https://www.reddit.com/r/developersIndia/comments/t7a6mv?utm_source=chatgpt.com "Are Computer Core Subjects like DBMS/CN/OS asked in Internships?"
[4]: https://www.geeksforgeeks.org/blogs/prepare-cs-core-subjects-for-placements/?utm_source=chatgpt.com "21 Days to Prepare CS Core Subjects For Placements - OS, DBMS, CN & Software Engineering - GeeksforGeeks"
