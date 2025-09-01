# SV-COMP Results (SPF)

This directory contains evaluation results of **Symbolic PathFinder (SPF)** on the SV-COMP Reach-Safety benchmarks, generated across different configurations and versions of SPF. 

Each result folder also contains the **`jpf-sv-comp` script** that was used to run SPF for that configuration. 

## Results Overview  

- **SPF 2.0 (Jun 30, 2025) – Z3** 
  Results compiled **before** the start of my contribution. This baseline run reflects the default configuration of SPF 2.0. 

- **SPF 3.0 (Jul 27, 2025) – Z3, Choco, CVC3** 
  Results compiled **after** several fixes and improvements, including: 
  - Corrected range settings for **Choco**. 
  - Fixed parsing bugs for **Z3** and **CVC3**. 
  - Adjusted default minimum range for symbolic double variables. 

- **SPF 3.0 (Aug 20, 2025) – Sequential Solver (Z3 + Choco)** 
  Results obtained with the **sequential solver**, where Z3 and Choco are combined to complement each other. 

## Summary  

- SPF 2.0 results serve as the **baseline**. 
- SPF 3.0 individual solvers (Z3, Choco, CVC3) show improvements after bug fixes and range corrections. 
- The combined sequential solver (Z3 + Choco) demonstrates the advantage of using **multiple solvers together**. 

