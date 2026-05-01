# Emerging Technology Assignment

## Overview
This repository contains solutions to five problems exploring the **Deutsch and Deutsch–Jozsa algorithms** using Python and Qiskit.

The work demonstrates how quantum computing can determine whether a Boolean function is **constant** or **balanced**, highlighting the theoretical advantage of quantum algorithms over classical approaches.

---

## Learning Focus
This assignment explores:

- Quantum computing as an **emerging technology**
- Classical vs quantum computation
- Oracle-based problem solving
- Implementation using modern tools such as Qiskit

---

## Contents

- **Problem 1:** Generating random constant and balanced Boolean functions  
- **Problem 2:** Classical testing and efficiency analysis  
- **Problem 3:** Construction of quantum oracles  
- **Problem 4:** Implementation of Deutsch’s algorithm  
- **Problem 5:** Scaling to the Deutsch–Jozsa algorithm  

All solutions are contained in:

`problems.ipynb`

---

## Technologies Used

- Python 3
- Qiskit
- Qiskit Aer (simulator)

---

## Requirements

All required Python packages are listed in `requirements.txt`, including:

- qiskit
- qiskit-aer
- numpy (if used)

---

## Setup Instructions

Clone the repository and install dependencies:

```bash
git clone https://github.com/matthewlukyanov2/emerging_technology
cd emerging_technology
pip install -r requirements.txt
jupyter notebook problems.ipynb
```

### Notes
- The notebook is designed to run **sequentially from top to bottom**
- All results are reproducible using the provided setup
- Quantum circuits are executed using the **Aer simulator**
- Real quantum hardware may produce slightly different results due to noise and decoherence

---

## References

- IBM Quantum Learning — Deutsch–Jozsa Algorithm  
  https://quantum.cloud.ibm.com/learning/en/modules/computer-science/deutsch-jozsa

- IBM Quantum Learning — Quantum Query Algorithms Course  
  https://quantum.cloud.ibm.com/learning/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-jozsa-algorithm

- Qiskit Documentation  
  https://qiskit.org/documentation/

- Qiskit Tutorials — Error Mitigation  
  https://quantum.cloud.ibm.com/docs/en/tutorials/error-mitigation-with-qiskit-functions

- Python Documentation — itertools.product  
  https://docs.python.org/3/library/itertools.html#itertools.product

- Deutsch–Jozsa Algorithm — Wikipedia  
  https://en.wikipedia.org/wiki/Deutsch%E2%80%93Jozsa_algorithm