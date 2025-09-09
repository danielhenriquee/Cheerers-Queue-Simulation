# Cheerers-Queue-Simulation
Cheerers-Queue-Simulation - Project for Data Structures - 2024/1

Authors: Daniel Henrique, Gabriel Laurentino, Pedro Henrique e Victor Menezes

This project simulates a deterministic queue system for managing two types of “cheerers”: regular and club members. 
The program maintains predefined proportions of both types and their respective service wait times, ensuring deterministic behavior rather than random distribution. 
It is designed as an educational project for practicing data structures, queue management, and simulation techniques.  

**Project Structure**  
- `linkedQueue.h` — Generic linked queue implementation supporting enqueue, dequeue, and traversal.  
- `main.cpp` — Simulation driver with menu input, queue initialization, and step-by-step time unit simulation.  

**Features**  
  
- Deterministic creation of cheerers maintaining predefined proportions:  
  - Regular cheerers: ~95%  
  - Club members: remaining proportion  
- Deterministic assignment of wait times for both types:  
  - Regulars: wait times 1, 2, or 3 based on proportion rules  
  - Club members: wait times 1 or 2 based on proportion rules  
- Simulation of multiple queues per type, distributing new cheerers to the shortest queue  
- Tracking of wait times and removal from queues when service is complete  
- Step-by-step time unit simulation with live queue printing  
- Calculation of average queue lengths for regular and club members  
- Support for waiting lists if no queues exist for a given type  

**Notes**
- The simulation maintains deterministic behavior; there is no randomization.
- Queues are implemented as generic linked queues (LinkedQ_TList) and can be reused in other projects.
- The program prints all queues at each time unit, including waiting lists, and shows average queue lengths after the simulation ends.
- Designed for educational purposes to demonstrate queue management, proportional assignment, and simulation in C++.
