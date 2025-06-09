# LSTM_Implementation_From_Scratch

This repository contains a complete from-scratch implementation of a Long Short-Term Memory (LSTM) neural network, **without using any machine learning libraries**. The core components — including the **forward pass** and **backpropagation through time (BPTT)** — have been manually built using only NumPy for matrix operations.

---

## 🚀 Project Highlights

- 🔧 **Manual LSTM Cell Implementation**  
  Constructs an LSTM unit from scratch, modeling gates, memory cells, and outputs step by step.

- 🔁 **Forward Pass Logic**  
  Computes hidden and cell states over a sequence using sigmoid and tanh activations, following standard LSTM equations.

- 🔙 **Backpropagation Through Time (BPTT)**  
  Calculates gradients for all parameters across time steps, propagating errors backward through the entire sequence.

- 🧮 **No ML Frameworks Used**  
  Built entirely using NumPy — no PyTorch, TensorFlow, or high-level libraries.

---

## LSTM Architecture Recap

The implementation follows the standard LSTM formulation:

- **Input gate (iₜ):** controls how much of the new information flows into the cell.
- **Forget gate (fₜ):** controls how much of the previous cell state is retained.
- **Output gate (oₜ):** determines how much of the cell state is exposed.
- **Cell candidate (ĉₜ):** new candidate information added to the cell state.

## 🙌 Acknowledgments
Inspired by classical LSTM papers and online tutorials.

