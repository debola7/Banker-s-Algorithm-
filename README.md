
# Banker's Algorithm Simulation (Python)

This project is an implementation of the **Banker's Algorithm**, a classic Operating Systems algorithm used for **deadlock avoidance**.  
It simulates how resources are allocated to processes in a safe state, ensuring that no process enters a deadlock situation.

---

## Features
- Written in **Python** for clarity and simplicity.  
- Implements the **safety algorithm** to check if the system is in a safe state.  
- Handles multiple processes and multiple resource types.  
- Demonstrates how Operating Systems manage **resource allocation**.  

---

## How It Works
1. Takes input for:
   - Number of processes  
   - Number of resource types  
   - Allocation matrix  
   - Maximum demand matrix  
   - Available resources  

2. Runs the **Banker's Algorithm** to determine:
   - If the system is in a safe state  
   - The safe sequence of process execution (if one exists)  

---

## Example Output
System is in a SAFE state.
Safe sequence is: P1 -> P3 -> P0 -> P2


---

## Requirements
- Python 3.x  

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/bankers-algorithm.git
   cd bankers-algorithm
2. Run the script:

python bankers_algorithm.py

Learning Outcome

This project strengthened my understanding of:

Deadlock avoidance in Operating Systems

Translating algorithms into real code

Writing modular and testable Python programs
