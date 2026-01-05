# Evaluation of Von Neumann and Linear Congruential PRNGs

## Project Description
Random number generation plays a crucial role in simulations, numerical analysis, cryptography, and stochastic modeling. Since true randomness is difficult to obtain computationally, most applications rely on **Pseudo-Random Number Generators (PRNGs)**. This project focuses on the evaluation of two classical PRNG techniques: the **Von Neumann Middle Square Method** and the **Linear Congruential Generator (LCG)**.

Both methods are historically significant and conceptually simple, making them ideal for understanding the fundamentals of algorithmic randomness and its limitations.

---

## What This Project Does
In this project, we have:

- Implemented the **Von Neumann Middle Square PRNG**
- Implemented the **Linear Congruential Generator (LCG)**
- Generated sequences of pseudo-random numbers using both methods
- Analyzed their behavior with respect to:
  - Randomness quality
  - Periodicity and repetition
  - Distribution patterns
- Visualized the generated sequences using plots
- Compared the strengths and weaknesses of each PRNG based on observed results

All implementations, analysis, and visualizations are performed using **Python in a Jupyter Notebook**.

---

## Key Observations
- The **Von Neumann method** often degenerates quickly, producing repeating patterns or zeros, making it unreliable for long sequences.
- The **Linear Congruential Generator** produces better distributions but is highly sensitive to parameter selection.
- Neither method is suitable for cryptographic use, but both are valuable for educational and basic simulation purposes.

---

## Conclusion
This project demonstrates how early PRNG methods work and highlights their limitations through practical implementation and analysis. The comparison provides insight into why modern applications require more robust and statistically sound random number generation techniques.

---

## Tools Used
- Python
- Jupyter Notebook
- NumPy
- Matplotlib

---

## Author
**Avash Pradhan**
