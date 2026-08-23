# DSA Group Simulation Project: Linear Search Algorithm

A physical human-roleplay simulation demonstrating the internal logic, state steps, and operation counts of the Linear Search algorithm on an unsorted array.

# Repository Structure

DSA-Roleplay-Ch2-6/
* report/
  * DSA_Roleplay_Report.pdf # Official PDF Report submission
* video/
  * README.md # Direct link to the public video recording
* README.md # Project overview (This file)

# Video Simulation

* Simulation Video Link: Watch Simulation Video
* Duration: 5 – 10 Minutes
* Content: Full enactment of 4 search scenarios with live narrator explanations and real-time operation tally logging.

# Team Roles & Responsibilities

The physical simulation features 6 participants, each assigned an active, distinct role:

* Camera / Narrator / Scribe
  * Responsibility: Films simulation, narrates code execution, logs comparisons live
  * Card / Prop Value: Whiteboard / Camera
* Pointer / Search Index
  * Responsibility: Loops through array by physically stepping between nodes
  * Card / Prop Value: Index Arrow Prop
* Data Node 0
  * Responsibility: Represents Array Index 0
  * Card / Prop Value: 4
* Data Node 1
  * Responsibility: Represents Array Index 1
  * Card / Prop Value: 7
* Data Node 2
  * Responsibility: Represents Array Index 2
  * Card / Prop Value: 11
* Data Node 3
  * Responsibility: Represents Array Index 3
  * Card / Prop Value: 15

# Initial Array State

* [4, 7, 11, 15]

# Simulated Scenarios & Operation Log

We executed four distinct operational runs to demonstrate time complexity variations across best, average, and worst cases:

* Scenario 1: Best Case
  * Target: 4
  * Index Found: 0
  * Comparisons: 1
  * Time Complexity: O(1)
* Scenario 2: Average Case
  * Target: 11
  * Index Found: 2
  * Comparisons: 3
  * Time Complexity: O(N)
* Scenario 3: Worst Case (Present)
  * Target: 15
  * Index Found: 3
  * Comparisons: 4
  * Time Complexity: O(N)
* Scenario 4: Worst Case (Absent)
  * Target: 20
  * Index Found: Not Found
  * Comparisons: 4
  * Time Complexity: O(N)
* Total Operations: 12 Comparisons

# Critical Reflections on Human Role-Play

In our report, we analyze four major physical limitations encountered when simulating computer memory using human actors:

* Pacing and Live Audio Synchronization: Human movement and vocalization introduce variable latency compared to a CPU clock cycle.
* Visual Framing & Legibility: Balancing wide shots (all nodes + tally board) with close-up legibility of numerical values.
* Simulating Out-of-Bounds Checks: Replicating index < array.length bounds checks required explicit physical boundary markers.
* Index vs. Value Confusion: Mitigating potential human error in distinguishing between a node's physical sequence index (0–3) and stored data value (4, 7, 11, 15).

# Report Documentation

* The full group documentation is located in the /report directory.

# Course & Project Metadata

* Course: Data Structures & Algorithms
* Project Type: Group Simulation Project (Chapters 2–6)
* Submission Deadline: Saturday, 22 August 2026, 11:59 PM
