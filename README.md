# Scheduling Problem: Mathematical Model & Metaheuristic in C#

This repository contains problem instances . The problem is characterized by varying numbers of jobs, machines, operators, and Time-of-Use (TOU) periods, with specific instance parameters encoded directly in the filenames.

## ?? Repository Structure
- `Data-Small-Instance/`: Small-scale Instances.
- `Data-Medium-Instance/`: Medium-scale instances.
- `Data-Large-Instance/`: Large-scale instances.

## ?? Data Specification
Each `.txt` file follows a specific structure used by the C# parser:
- `cp`: Energy consumption cost in periods
- `co`: Outsourcing cost of jobs 
- `dd`: Due Date of jobs
- `p`: Processing Time of jobs
- `e (job, machine)`: Energy consumption rate of job  on machine   
- `b (job, machine)`: Machines eligible
- `u (job, op)`: Operators eligible

## ?? Prerequisites & Usage
- **Language:** C# (.NET Core or Framework)
- **Solver:** (e.g., IBM ILOG CPLEX / Gurobi / Or-Tools) - *CPLEX*
- **IDE:** Visual Studio 2022 or VS Code

To run the solver:
1. Clone the repository.
2. Point the file path to one of the instances in the `Data-*` folders.
3. Run the solution.
