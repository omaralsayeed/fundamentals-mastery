Fundamentals Mastery Checklist — Study Mode

> Use this repo-style checklist to track your progress. Clone it into your GitHub, check items as you complete them, and use it as your personal learning playbook.




---

1. Databases (RDBMS + NoSQL)

Core Concepts

[ ] ACID vs BASE — definitions and tradeoffs

[ ] Normal forms (1NF, 2NF, 3NF, BCNF) and denormalization reasons

[ ] Keys: primary, foreign, composite, surrogate

[ ] Indexes: B-tree vs hash vs composite indexes

[ ] Joins: inner, left/right outer, full outer, cross join

[ ] Transactions & isolation levels + anomalies

[ ] Locks: optimistic vs pessimistic

[ ] Query execution plans (EXPLAIN/EXPLAIN ANALYZE)

[ ] Window functions and common table expressions (CTEs)

[ ] Stored procedures, triggers, views

[ ] Data modelling (ER modelling, document modelling)

[ ] CAP theorem, replication, sharding, partitioning

[ ] Backup & restore strategies

[ ] Consistency models for NoSQL


Practical / Implementation

[ ] Design and implement an ER diagram for an e-commerce or booking domain

[ ] Implement the same in MongoDB with document schema

[ ] Create sample queries with joins, window functions, and aggregations

[ ] Run and analyze EXPLAIN for slow queries and optimize with indexes

[ ] Simulate transactions and isolation anomalies in MySQL

[ ] Setup MySQL replication (master–replica demo)

[ ] Implement text search (MySQL vs MongoDB)


Interview Practice

[ ] Explain indexing and when it fails

[ ] Optimize a slow query example

[ ] Design a schema for comments/blog

[ ] Explain sharding a users table



---

2. Operating Systems

Core Concepts

[ ] Processes vs threads vs coroutines

[ ] Process lifecycle and system calls

[ ] CPU scheduling algorithms

[ ] Concurrency primitives: mutex, semaphore, spinlock

[ ] Race conditions, memory visibility

[ ] Deadlocks: detection, prevention, Banker’s algorithm

[ ] Virtual memory: paging, segmentation, TLBs

[ ] Page replacement algorithms (FIFO, LRU, Clock)

[ ] I/O subsystems, interrupts vs polling

[ ] File systems basics (inodes, journaling, mounting)

[ ] Python threads (GIL caveats), multiprocessing, async/await


Practical Tasks

[ ] Producer-consumer with threading in Python

[ ] Compare multiprocessing vs threading in Python

[ ] Simulate Round Robin and SJF schedulers

[ ] Create a deadlock, then fix with ordering

[ ] Explore memory swapping via a heavy program


Interview Practice

[ ] Explain python app.py lifecycle

[ ] Page table + TLB lookup explanation

[ ] Debug a multithreading bug

[ ] Explain Python GIL tradeoffs



---

3. Data Structures & Algorithms

Core Implementations

[ ] Dynamic array implementation

[ ] String algorithms (two-pointer, sliding window)

[ ] Linked lists (reverse, detect cycle, merge)

[ ] Stacks, queues, deque

[ ] Trees: BST (insert, delete, traversals)

[ ] Heaps & priority queues

[ ] Tries (prefix search, autocomplete)

[ ] Graphs (BFS, DFS, Dijkstra, Topo Sort, DSU)

[ ] Hash tables (collision handling)

[ ] Sorting algorithms (quick, merge, heap)

[ ] Dynamic Programming (knapsack, LIS, coin change)

[ ] Greedy algorithms

[ ] Bit manipulation basics

[ ] Complexity analysis (Big-O/Θ/Ω, amortized)


Patterns to Master

[ ] Sliding window

[ ] Two pointers

[ ] Fast/slow pointers

[ ] BFS/DFS on trees/graphs

[ ] Backtracking

[ ] Divide & conquer

[ ] Dynamic programming

[ ] Greedy selection

[ ] Priority-queue problems


Practical Tasks

[ ] Implement all structures in Python

[ ] Solve 100 Easy + 150 Medium LeetCode problems

[ ] Track problem solutions with complexity notes

[ ] Mock timed interviews (45–60min)


Interview Practice

[ ] Explain tradeoffs: array vs linked list vs hash vs tree

[ ] Identify problem pattern quickly

[ ] Walk through code on whiteboard/editor



---

4. Object-Oriented Programming & Design

Core Concepts

[ ] OOP pillars: encapsulation, abstraction, inheritance, polymorphism

[ ] SOLID principles

[ ] Design patterns: Factory, Singleton, Builder, Adapter, Decorator, Facade, Strategy, Observer, Command, Iterator

[ ] Interfaces vs abstract classes

[ ] Composition over inheritance

[ ] Object lifecycle, immutability

[ ] Unit testing and TDD basics

[ ] System design basics: REST API design, caching, auth, rate-limiting


Practical Tasks

[ ] Re-implement Shopping Cart with classes in Python & JS/TS

[ ] Implement 5 design patterns in code with tests

[ ] Write unit tests with pytest/Jest

[ ] Mini design exercise: URL shortener


Interview Practice

[ ] Whiteboard class diagram for a design problem

[ ] Explain composition vs inheritance decision

[ ] Refactor procedural → OO design



---

5. Full-stack / Systems Integration

[ ] RESTful API with proper routes, status codes, error handling

[ ] Authentication: JWT vs session-based

[ ] Caching with Redis (or simulate TTL)

[ ] Rate limiting, input validation, safe queries

[ ] Logging & monitoring basics

[ ] Dockerize a project

[ ] Setup CI (GitHub Actions) to run tests



---

6. Study Schedule Template

Daily: 30–45 min DSA, 20–30 min theory (rotate DB/OS/OOP), 10–15 min review notes

Weekly: Project feature (4–8h), 1 mock interview, 1 in-depth read + summary



---

7. Self-Assessment Rubric

[ ] ✔ Explain & implement transactions + isolation levels

[ ] ✔ Optimize queries with EXPLAIN

[ ] ✔ Implement producer/consumer + fix deadlocks

[ ] ✔ Implement 10 data structures from scratch

[ ] ✔ Solve medium DSA in under 50 min

[ ] ✔ Design REST API with schema, endpoints, scaling notes



---

8. Final Checklist

[ ] CRUD app with MySQL + MongoDB hybrid

[ ] 10 optimized SQL queries with EXPLAIN analysis

[ ] 8 multithreading/process demos documented

[ ] 15 data structures with tests

[ ] 150 LeetCode problems (variety by pattern)

[ ] 5 design patterns implemented with README

[ ] Dockerized project + CI pipeline

[ ] 6 mock interviews (3 DSA, 2 system/design, 1 behavioral)

