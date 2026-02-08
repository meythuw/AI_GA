# Knapsack Optimization using Genetic Algorithm

This repository presents a **team-based academic project** that applies **Genetic Algorithms (GA)** to solve the **Knapsack Optimization Problem**, a classical combinatorial optimization problem in Artificial Intelligence.

The project focuses on designing, implementing, and analyzing different genetic operators and parameter settings to evaluate their impact on solution quality and convergence behavior.

---

## Project Overview

The Knapsack Problem aims to select a subset of items with given weights and values such that the total value is maximized without exceeding a fixed capacity constraint.  
Due to its NP-hard nature, heuristic and evolutionary approaches such as Genetic Algorithms are commonly used to obtain near-optimal solutions.

In this project, we implemented a Genetic Algorithm framework and conducted extensive experiments to analyze how different GA components influence optimization performance.

---

## Objectives

The main objectives of this project are:

- To formulate the Knapsack Problem as an optimization task suitable for Genetic Algorithms
- To design and implement key genetic operators, including selection, crossover, and mutation
- To evaluate the impact of genetic parameters such as:
  - Population size
  - Number of generations
  - Crossover rate
  - Mutation rate
- To analyze algorithm performance under different experimental settings
- To visualize and interpret optimization results

---

## Methodology

### 1. Problem Formulation
- Defined the Knapsack optimization problem with capacity constraints
- Encoded candidate solutions as chromosomes
- Designed a fitness function to evaluate solution quality

### 2. Genetic Algorithm Design
The Genetic Algorithm consists of the following components:

- **Population Initialization**  
  Random initialization of candidate solutions

- **Fitness Evaluation**  
  Calculation of fitness scores based on total value and feasibility

- **Selection Strategy**  
  Selection of parent chromosomes based on fitness

- **Crossover Operator**  
  Generation of offspring through recombination of parent chromosomes

- **Mutation Operator**  
  Introduction of random variations to maintain population diversity

- **Stopping Criteria**  
  Termination based on the number of generations

### 3. Experimental Setup
Multiple experiments were conducted to evaluate the influence of different parameters, including:
- Number of generations
- Population size
- Mutation rate
- Crossover rate
- Selection strategy

---

## Experimental Results and Analysis

- Conducted comparative experiments across various parameter configurations
- Analyzed convergence behavior and solution stability
- Evaluated trade-offs between exploration and exploitation
- Identified parameter settings that yield better optimization performance

Results demonstrate that genetic parameter tuning plays a critical role in achieving high-quality solutions for the Knapsack Problem.

---

## My Contribution (Nguyễn Thị Minh Thư)

My primary contributions to this project include:

- Formulating the Knapsack optimization problem and defining the fitness function
- Designing and implementing **crossover mechanisms** in the Genetic Algorithm
- Designing and implementing **mutation operators**
- Conducting experimental analysis on the impact of:
  - Mutation rate
  - Reproduction (crossover) rate
- Interpreting and reporting experimental results
- Co-authoring the technical report

All work was conducted collaboratively within a team-based academic setting.

---

## Tools and Technologies

- Programming Language: Python  
- Algorithm: Genetic Algorithm  
- Optimization Problem: Knapsack Problem  
- Development Environment: Jupyter Notebook  

---

## Academic Context

- Course: Artificial Intelligence  
- Institution: University of Economics Ho Chi Minh City (UEH)  
- Project Type: Team-based academic project

---

## Notes

This repository reflects collaborative academic work.  
The contributions listed above represent the specific components I was directly responsible for in the project.
