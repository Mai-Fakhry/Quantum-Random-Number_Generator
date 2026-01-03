# Quantum Random Number Generator 🚀

A **Quantum Random Number Generator (QRNG)** that leverages the inherent randomness of quantum mechanics to produce truly unpredictable numbers using quantum circuits. Unlike classical pseudo-random number generators (PRNGs), this generator produces *real* randomness from quantum measurement outcomes. :contentReference[oaicite:0]{index=0}

---

## 🔍 Overview

This project implements a basic quantum random number generator using quantum computing principles. A qubit is prepared in a superposition state and then measured. The measurement collapses the qubit into either `0` or `1` with equal probability—resulting in a random bit sequence. :contentReference[oaicite:1]{index=1}

---

## 📦 Features

- Generate quantum random bits (0 or 1)
- Combine multiple bits to form longer random numbers
- Built using quantum circuits and simulator/backend support (e.g., Qiskit)

---

## ⚙️ Prerequisites

Before you begin, make sure you have:

- Python 3.6+
- Qiskit (if using IBM quantum backends)
- (Optional) IBM Quantum API token for running on real hardware

Install dependencies:

```bash
pip install -r requirements.txt
