# ⚙ CPU Scheduling Simulator

An interactive web-based simulator to visualize and understand different CPU scheduling algorithms used in Operating Systems.

---

## 🚀 Features

* Supports multiple scheduling algorithms:

  * FCFS (First Come First Served)
  * SJF (Shortest Job First - Non Preemptive)
  * Round Robin (Time Quantum = 2)
  * Priority Scheduling *(based on burst time)*

* Dynamic process input

* Step-by-step execution of algorithms

* Visual Gantt-style representation

* Calculates:

  * Waiting Time (WT)
  * Turnaround Time (TAT)
  * Average WT & TAT

---

## 🛠 Tech Stack

* HTML
* CSS
* JavaScript

---

## ▶ How to Run

1. Download or clone this repository
2. Open the file:

   ```
   cpu-scheduling.html
   ```
3. Enter number of processes
4. Add Arrival Time and Burst Time
5. Click **Run** and explore different algorithms

---

## ⚠ Notes

* SJF is implemented as **non-preemptive**
* Round Robin uses a **fixed time quantum = 2**
* Priority scheduling uses **burst time as priority (for demonstration purposes)**

---

## 🎯 Purpose

This project is created to help students:

* Understand CPU scheduling concepts visually
* Prepare for Operating Systems practicals and viva
* Compare different scheduling algorithms easily

---

## 📌 Future Improvements

* Add Preemptive SJF (SRTF)
* Custom time quantum input for Round Robin
* Proper priority input field
* Improved UI/UX and validation

---

## 👩‍💻 Author
#Ninii<3

Created as part of Operating Systems practical work.
