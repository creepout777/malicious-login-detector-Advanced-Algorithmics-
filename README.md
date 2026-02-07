[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/2sSoQrm2)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20939741&assignment_repo_type=AssignmentRepo)
# Malicious Login Detector: A Data Structure Approach to Brute-Force Attack Detection  
*A Semester Project for Advanced Algorithms*  

---

## Project Overview  
This project simulates a **login monitoring system** that detects suspicious or malicious login attempts such as brute-force or credential stuffing.  

You will use the **core Data Structures & Algorithms** from this course (arrays, linked lists, stacks, queues, searching, sorting, trees, and graphs) to build different modules of the system. By the end of the semester, you will integrate these modules into a single working tool: the **Malicious Login Detector**.  

---

## Objectives  
- Learn to **implement classical data structures** from scratch.  
- Apply them to a simple **cybersecurity scenario**.  
- Analyze **time and space complexity** for each module.  
- Integrate all modules into a complete working system.  

---

## Input Dataset  
Your program should read login attempts from a CSV file with the format such as timestamp, username, status, ip_address and so on.

You may generate your own dataset or use existing dataset.

---

## Modules & Tasks  

### 1. Arrays and Linked Lists → Login Record Storage  
- Store login attempts using arrays and linked lists.  
- Compare performance for insertion, deletion, and traversal.  

### 2. Stack → Suspicious User Tracker  
- Maintain a stack of recent login results per user.  
- If a user fails **k times in a row**, mark as *suspicious*.  

### 3. Queue → Login Request Simulation  
- Use a FIFO queue to simulate incoming login requests.  
- Extend with a priority queue: high-risk IPs are processed first.  

### 4. Searching → Blacklist Checking  
- Keep a blacklist of usernames/IPs.  
- Implement **linear search** and **binary search**.  
- Compare their performance.  

### 5. Sorting → Ranking of Accounts  
- Sort users by number of failed logins.  
- Implement bubble sort, insertion sort, quick sort, and merge sort.  
- Run experiments to find crossover points.  

### 6. Trees → Classification of Attempts  
- Build a classification tree with categories:  
  - Normal  
  - Suspicious  
  - Attack  
- Traverse the tree to assign each user to a category.  

### 7. Graphs → Attack Spread Simulation  
- Model accounts as graph nodes.  
- Add an edge if the same IP tries multiple accounts.  
- Use BFS/DFS to trace attacker spread.  

---

## Integration (Final System)  
At the end, combine all modules into a single CLI program (GUI is a Plus):  

## Deliverables

1. **Source Code**  
   - Organized by module (arrays, stacks, queues, etc.).  
   - Final integration into one working program.  

2. **Report (5–8 pages)**  
   - Explanation of each data structure used.  
   - Time and space complexity analysis.  
   - Experimental results (timing comparisons, performance charts).  

3. **Demo Presentation**  
   - Live or recorded.  
   - Show the program running on sample input and producing output.  

## Originality & Plagiarism Policy  

- *Unique datasets*: Each team must create or source a different dataset (e.g., varied attack patterns, time windows, IP pools).  
- *Algorithmic choices*: The reason behind your chocie of algorithm
- *Similarity checks (Plagiarsm detection)* will be enforced. Similarity shouldn't exceed 25%. 
- *Security defense check*: During demo, each team will face *challenge scenarios* to verify robustness.  
- *Oral defense*: Each member must explain one module’s logic. 

---
