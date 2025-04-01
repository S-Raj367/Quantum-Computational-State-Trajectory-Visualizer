# Quantum State Visualizer

![Project Banner](https://via.placeholder.com/1200x400.png?text=Quantum+State+Visualizer)

A web-based tool for building, visualizing, and simulating quantum circuits with interactive state representations.

## Features

- **Circuit Builder**: Intuitive interface for constructing quantum circuits
- **Real-time Visualization**: Graphical representation of quantum circuits
- **Simulation Engine**: Run quantum circuit simulations
- **Results Visualization**: 
  - Probability distribution charts
  - Bloch sphere representations
  - Measurement statistics

## Components

### CircuitVisualizer

**Props:**
- `circuit` (required): Quantum circuit object
- `width`: Canvas width (default: 800)
- `height`: Canvas height (default: 400)

### ResultsVisualizer

**Displays:**
1. Probability distribution
2. Bloch spheres (for single qubits)
3. Measurement statistics

## Tech Stack

- **Frontend:** React + TypeScript
- **Styling:** Tailwind CSS
- **Visualization:** Canvas API
- **Quantum Library:** Custom simulation engine

### Circuit Methods

| Method | Description |
|--------|-------------|
| `h(qubit)` | Hadamard gate |
| `x(qubit)` | Pauli-X gate |
| `cx(control, target)` | CNOT gate |
| `measure()` | Perform measurement |
| `simulate(options)` | Run simulation |

## Installation

```bash
git clone https://github.com/yourusername/quantum-state-visualizer.git
cd quantum-state-visualizer
npm install
npm run dev
