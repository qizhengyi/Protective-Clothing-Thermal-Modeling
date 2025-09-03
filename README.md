Protective Clothing Thermal Modeling — Mathematical Contest in Modeling (MCM/ICM)
📘 Project Overview
This repository contains my work for the 2018 National Undergraduate Mathematical Contest in Modeling (CUMCM, Problem A).
The project focuses on thermal modeling of protective clothing in high-temperature environments, combining partial differential equations (PDEs), numerical analysis, and optimization techniques.
The objective was to design a multi-layer protective clothing system that minimizes heat transfer to the human body, ensuring safety while optimizing material thickness and cost.
🧩 Problem Statement
The protective clothing consists of three fabric layers plus an air gap, modeled as a 1-D heat conduction system.
We were asked to:
Simulate skin temperature distribution under fixed environmental and material conditions.
Determine the optimal thickness of the middle insulation layer to keep skin temperature safe (<47 °C) within 60 minutes, while minimizing material usage.
Jointly optimize both insulation and air-gap thickness when exposed to more extreme heat conditions.
🔬 Methodology
Mathematical Modeling: Derived governing equations using the 1-D heat conduction PDE with appropriate boundary conditions.
Numerical Solution: Implemented an implicit finite-difference scheme in MATLAB (pdepe) for stability and accuracy.
Parameter Calibration: Fitted model outputs to experimental skin-temperature data for validation.
Optimization: Conducted grid search and constrained optimization to determine the thinnest material layers satisfying safety requirements.
Statistical Verification: Exported simulation results to Excel and analyzed heat distribution curves for compliance with safety constraints.
📊 Key Results
Case 1 (Baseline, 75 °C environment): Skin temperature rose from 37 °C to ~48.1 °C over 90 minutes.
Case 2 (65 °C environment): Optimal middle-layer thickness was 8.4 mm, ensuring skin temperature <47 °C with safe exposure time.
Case 3 (80 °C environment): Optimal configuration found at 10 mm (middle layer) + 4.4 mm (air gap), balancing protection and minimal material use

.
🚀 Repository Structure
CUMCM-2018-Problem-A-Chinese.docx — Official problem statement (Chinese).
A201819010003_叶派良_戚正奕_吴梓康.pdf — Full competition paper, including derivations and results.
problem1.xlsx — Simulated skin temperature data for Case 1.
Matlab_Code/ — MATLAB scripts used for PDE modeling and optimization.
🛠️ Tools & Skills Demonstrated
Programming: MATLAB (numerical PDE solvers, automation of simulations), Excel (data analysis).
Quantitative Methods: Heat transfer modeling, constrained optimization, Monte Carlo verification.
Data Analysis: Experimental data calibration, time-series simulation, curve fitting.
Teamwork & Communication: Produced a complete technical report under competition conditions.
📖 Relevance
This project highlights my ability to:
Translate complex physical problems into mathematical and computational models.
Apply statistical modeling, PDE solvers, and optimization to real-world safety engineering problems.
Work effectively under tight deadlines — skills directly transferable to quantitative research, financial modeling, and risk analysis roles in the financial sector
.

National Undergraduate Mathematical Contest in Modeling (CUMCM)

