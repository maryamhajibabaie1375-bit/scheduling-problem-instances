# Scheduling Problem: Mathematical Model & Metaheuristic in C#

This repository contains problem instances . The filename of each text file consists of four integers, which denote the number of jobs, machines, operators, and TOU periods, respectively.

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
- `fp`:Start of period
- `ep`:End of period
- `si`:Setup time of jobs 
- `tc`:Tardiness cost of jobs 

## ?? Prerequisites & Usage
- **Language:** C# (.NET Core or Framework)
- **Solver:** (e.g., IBM ILOG CPLEX / Gurobi / Or-Tools) - *CPLEX*
- **IDE:** Visual Studio 2022 or VS Code


