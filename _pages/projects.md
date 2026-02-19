---
layout: page
title: Projects
permalink: /projects/
description: These are selected projects I have worked on or am currently developing, focused on optimization, stochastic modeling, and data-driven decision-making in high-risk, high-intensity operational settings such as healthcare and aviation.
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---
---

## Healthcare Optimization

### Equitable Surgical Case Allocation via Stochastic Integer Programming

This project develops a stochastic integer optimization framework for allocating surgical cases across surgeons while explicitly incorporating workload equity. Surgical assignment decisions influence not only system efficiency but also how workload accumulates across individual surgeons under uncertainty in case durations and emergency arrivals. The model optimizes equity in surgical case allocation while preserving operational feasibility.

The formulation was implemented in Python using Gurobi and evaluated using multi-year, surgery-level EHR data from a U.S. medical center. We incorporated uncertainty in surgery duration and emergency workload variability. Compared to historical allocation practices, the model achieved up to a 70% reduction in maximum pairwise workload envy while maintaining realistic utilization levels. This work contributes a quantitative foundation for fairness-aware surgical workload allocation in high-stakes healthcare environments.

**Methods:** Mixed-Integer Linear Programming (MILP), stochastic modeling, simulation  
**Tools:** Python, Gurobi, R, Jupyter, LaTeX  
**Status:** Ongoing  

---

### Surgical Workload Quantification & Queueing-Based Tradeoff Analysis

This project introduces a data-driven framework for quantifying surgical workload and analyzing its operational consequences. Using unsupervised clustering on large-scale healthcare data, surgeries were classified into distinct workload types based on complexity indicators such as patient severity, case characteristics, and duration. These workload classes were embedded into a stochastic queueing model to study tradeoffs between pre-surgery waiting time and surgeon utilization under uncertainty.

Sensitivity analyses examined staffing levels and prioritization policies to evaluate their effect on system performance. Results demonstrated that additional staffing reduced waiting time for lowest-priority cases by up to 82.5%, while priority reordering alone achieved reductions of approximately 42.5%. The work provides a structured methodology for linking workload measurement to policy-level decisions in operating room systems.

**Methods:** Unsupervised learning (clustering), stochastic queueing models, sensitivity analysis  
**Tools:** R, Python, statistical modeling  
**Status:** Completed  

---

## Aviation Analytics

### Pilot Fatigue Analytics & Risk Indicator Identification

This project investigates pilot fatigue using operational flight metrics combined with subjective and objective fatigue measures. Statistical learning methods, including regression modeling and decision tree analysis, were applied to identify key predictors of fatigue outcomes and to characterize relationships between workload intensity, duty schedules, and fatigue risk.

The analysis translated model findings into interpretable risk indicators that can support operational monitoring and fatigue mitigation strategies. By integrating behavioral data with operational variables, this work demonstrates how data-driven analytics can inform safety-critical decision-making in aviation systems.

**Methods:** Regression modeling, decision trees, statistical analysis  
**Tools:** R, data visualization  
**Status:** Completed  

---

