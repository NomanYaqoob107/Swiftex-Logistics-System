# Swiftex-Logistics-System

## Group Details
**Team Leader:**
- Name: Muhammad Nouman
- Roll No: 2024-CS-669

**Team Members:**
1. Name: Waleed Ahmad - Roll No: 2024-CS-654
2. Name: Abdul Sami - Roll No: 2024-CS-681
3. Name: Ammar Jamil - Roll No: 2024-CS-683

## Project Description
Intelligent Courier Logistics Engine built in C++ simulating real-time parcel sorting, dynamic routing (Shortest Path), and tracking. Implements custom Data Structures (Graphs, Heaps, Hash Tables) for optimized logistics management.

## How to Run
Is code ko run karne ke liye:
1. Download the `main.cpp` file.
2. Open the file in any C++ compiler (DevC++, VS Code, Turbo).
3. Run the compiler.

## Key Features
1.Intelligent Parcel Sorting: Implements a Max-Heap to ensure high-priority and express parcels are dispatched first.
2.Dynamic Routing Engine: A Graph-based system using DFS to find multiple routes. It detects road blockages or traffic overloads and reroutes parcels in real-time.
3.Real-Time Transit Monitor: A live simulation of parcel movement with visual progress bars and ETA updates.
4.Rider Assignment Logic: A management system that matches parcels to riders based on weight categories (Light vs. Heavy) and current workload.
5.System Database: A custom Hash Table using quadratic probing for near-instant parcel lookups by ID.
6.Undo Mechanism: A Stack-based action history allowing users to revert dispatches or accidental entries.
