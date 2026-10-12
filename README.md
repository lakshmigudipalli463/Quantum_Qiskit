# 🚀 Qiskit Fall Fest 2026 – Quantum Computing Challenges

Welcome to my **Qiskit Fall Fest 2026** project!

I created this repository while learning the basics of quantum computing using **Python and Qiskit**. These four challenges helped me understand how quantum circuits work and how changing quantum gates can affect measurement results.

You don't need any previous knowledge of quantum computing to explore this project!

## 🌟 What is Quantum Computing?

Normal computers use bits, which represent either `0` or `1`.

Quantum computers use **qubits**. A qubit can be prepared in a quantum state that gives different possible outcomes when measured.

A quantum circuit is a sequence of operations, called **quantum gates**, applied to qubits. When we measure the qubits, we obtain classical results such as `0` and `1`.

In this project, I used Qiskit to create quantum circuits, simulate them, and observe their measurement results.

## 🧪 Challenges Completed

### Challenge 1: Predict the Output

**Goal:** Understand how quantum gates affect measurement results.

- Used an X gate to change a qubit's state.
- Applied the X gate twice to observe how the state changes.
- Used a Hadamard (H) gate to explore superposition.
- Compared predictions with simulation results using histograms.

### Challenge 2: Make the Quantum Coin Biased

**Goal:** Explore how a quantum gate can change the probability of measurement outcomes.

- Used the rotation gate `RY`.
- Modified the rotation angle to change the probability of measuring `0` or `1`.
- Compared the measurement results using histograms.

### Challenge 3: Can You Change the Correlation?

**Goal:** Understand how two qubits can produce related measurement outcomes.

- Created a Bell-state circuit using H and CNOT gates.
- Observed the outcomes `00` and `11`.
- Added an X gate to one qubit.
- Observed how the outcomes changed to `01` and `10`.

### Challenge 4: Quantum Correlation Switch

**Goal:** Switch between correlated and opposite measurement outcomes.

- Built a circuit that produced the outcomes `00` and `11`.
- Modified the circuit by adding an X gate.
- Observed the outcomes `01` and `10`.
- Compared both experiments using histograms and measurement counts.

## 🛠️ Tools Used

- **Python** – Programming language
- **Qiskit** – Framework for building quantum circuits
- **Qiskit Aer** – Quantum circuit simulator
- **JupyterLab** – Environment used to write and execute the notebooks
- **Matplotlib** – Used to visualize measurement results with histograms
- **GitHub** – Used to store and share the project

## 📂 Project Structure

The repository contains four Jupyter notebooks:

1. `Challenge_1_Predict_the_Output.ipynb`
2. `Challenge_2_Make_the_Quantum_Coin_Biased.ipynb`
3. `Challenge_3_Change_the_Correlation.ipynb`
4. `Challenge_4_Quantum_Correlation_Switch.ipynb`

Each notebook includes the circuit, code, measurement results, histograms, and explanations of the experiment.

## 🎯 What I Learned

Through these challenges, I learned how to:

- Create quantum circuits using Qiskit.
- Apply quantum gates such as X, H, CNOT, and RY.
- Simulate quantum circuits using 100 shots.
- Understand measurement counts and probability distributions.
- Visualize results using histograms.
- Explore correlations between two qubits.
- Compare predictions with actual simulation results.

## 💡 Final Note

This project represents my first steps into quantum computing. I completed these experiments to build a basic understanding of quantum circuits through practical examples.

I'm excited to continue learning more about quantum computing and Qiskit!

**Thank you for visiting my repository!** 😊
