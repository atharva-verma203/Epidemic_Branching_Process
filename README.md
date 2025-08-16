## 🦠 Epidemic Spread Modeling using Branching Process
This project applies statistical modeling and simulation to analyze epidemic dynamics, focusing on the critical role of the basic reproduction number ($R_0$) in the outcome of an outbreak.

## 📊 Overview
* **Objective**: To simulate infection spread and estimate extinction probabilities to analyze epidemic dynamics.
* **Methodology**: A single-type Galton-Watson branching process was used, with offspring distribution modeled by a Poisson distribution.
* **Tools**: Python (NumPy, Matplotlib, Seaborn), R (ggplot2).

## 💡 Project Highlights
1.  **Simulation & Methodology**:
* Designed and implemented an interactive simulation to track infection counts over generations.
* Used Python to model infection spread and visualize outcomes.
* Used R to estimate extinction probabilities across different values of $R_0$

​2.  **Key Findings**:
* Subcritical Regime ($R_0$ < 1): High extinction rates (~80%), confirming epidemics are unlikely to sustain themselves.
* Critical Threshold ($R_0$ = 1) : An unstable point where the epidemic is expected to die out over time, with a 100% theoretical extinction probability.
* Supercritical Regime ($R_0$ > 1) : A sharp drop in extinction probability (~30-40%), indicating a high potential for sustained outbreaks.
* $R_0$ and Outcome : Small increases in $R_0$ past the critical threshold lead to drastically different outcomes, highlighting its importance in public health.
* Clustering Analysis: Visual analysis demonstrates a clear non-linear relationship between infections, extinction probability, and $R_0$.

## 📈 Conclusion
This project demonstrates how computational modeling and statistical analysis can provide crucial insights for public health decision-making. The findings reinforce that maintaining the reproductive number ($R_0$) below one is essential to prevent widespread outbreaks.
