# Quantum State Visualizer
![Image](https://github.com/user-attachments/assets/fc722f84-fb45-4500-8219-36cbde495669)
![Image](https://github.com/user-attachments/assets/054f62b6-4e4d-43d5-aed2-5e64e96f4075)
![Image](https://github.com/user-attachments/assets/e0871507-54bd-476a-8338-6dc301a8f72e)
![Image](https://github.com/user-attachments/assets/c4bd913a-8568-4967-bb35-0bb6b984fb8f)
![Image](https://github.com/user-attachments/assets/eb0baf1e-8f89-42e4-870e-3dceae09f2db)
![Image](https://github.com/user-attachments/assets/2005284d-cb3d-46dd-a4be-2232060def5e)





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
