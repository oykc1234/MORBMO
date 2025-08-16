# Multi-objective Red-billed Blue Magpie Optimizer (MORBMO)

This repository contains the official implementation of the algorithm presented in the paper:  
**"Multi-objective Red-billed Blue Magpie Optimizer: A Novel Algorithm for Multi-objective UAV Path Planning"**  
published in *Results in Engineering*.

<img width="725" height="308" alt="image" src="https://github.com/user-attachments/assets/48f98e79-a1e3-4120-9628-364a34fa5af6" />

## About the Paper
The paper proposes MORBMO, a novel multi-objective optimization algorithm inspired by the hunting behaviors and food storage strategies of Red-billed Blue Magpies. Key contributions include:

1. **Algorithm Design**:
   - Extension of single-objective RBMO to multi-objective optimization
   - Incorporates non-dominated sorting and crowding distance mechanisms
   - Features elite food storage strategy for preserving high-quality solutions
   - Implements team-based search tactics for balanced exploration/exploitation

2. **Benchmark Evaluation**:
   - Comprehensive testing on 46 static multi-objective benchmark functions
   - Covers five major test suites:
     - ZDT (6 functions)
     - DTLZ (7 functions)
     - WFG (9 functions)
     - UF (10 functions)
     - CF (10 functions)
   - Additional 4 custom UAV path planning scenarios

3. **Performance Metrics**:
   - Evaluated using four standard indicators:
     - Generational Distance (GD)
     - Spacing
     - Inverted Generational Distance (IGD)
     - Hypervolume (HV)
   - Demonstrates superior convergence and diversity maintenance

## About the Code
This implementation provides:
- Complete MORBMO algorithm implementation
- All 46 benchmark test functions covering ZDT, DTLZ, WFG, UF and CF suites
- Pareto front visualization tools

The code demonstrates MORBMO's performance on standard multi-objective benchmarks and includes visualization of the obtained Pareto fronts, reproducing the key experimental results from the paper.
