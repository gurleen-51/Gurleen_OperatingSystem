# Gurleen_OperatingSystem_2301420051_B.Tech – Computer Science (Data Science)

Operating System Assignment



---

## **Introduction**

This experiment focuses on the fundamental concepts of **process management in the Linux operating system**. The objective is to understand how processes are created, executed, monitored, and prioritized using system-level programming and kernel-supported interfaces. The experiment is divided into five tasks that collectively illustrate how Linux handles process lifecycle and scheduling.

---

## **Description of Tasks**

### **🔹 Task 1 – Process Creation**

The first activity demonstrates the creation of multiple processes.

* A main (parent) process spawns **three separate child processes**.
* The **`fork()` system call** is used to duplicate the process.
* The program prints the **PID of the parent and each child**, proving successful creation.

---

### **🔹 Task 2 – Executing Another Program**

This task explores how a process can load and execute an entirely different program.

* A child process is created solely to run an **external command**.
* The **`exec()` system call** replaces the current process with the command **`ls -l`**.

---

### **🔹 Task 3 – Understanding Special Process States**

This part highlights important process states that result from improper synchronization:

* **Zombie Process:** A finished child process whose termination status is not collected.
* **Orphan Process:** A child process left running after its parent exits and is adopted by **init/systemd**.

---

### **🔹 Task 4 – Accessing Process Information via /proc**

This task interacts with the Linux kernel directly using the **/proc virtual filesystem**.

* Information such as process status, executable path, and open file descriptors is extracted from **/proc/PID/** directories.
* Demonstrates how Linux exposes internal process details to the user.

---

### **🔹 Task 5 – Controlling Process Priority**

This task focuses on controlling CPU scheduling:

* Uses **`nice` and priority values** to modify process scheduling fairness.
* **Lower values = higher priority**, **higher values = lower priority**.


---

## Assignments

| Assignment   | File Name                           |
| ------------ | ----------------------------------- |
| Assignment 1 | **2301420051_ASSIGNMENT-1(OS).pdf** |
| Assignment 2 | **2301420051_ASSIGNMENT-2(OS).pdf** |
| Assignment 3 | **2301420051_ASSIGNMENT-3(OS).pdf** |
| Assignment 4 | **2301420051_ASSIGNMENT-4(OS).pdf** |



