## Code Library Mindmap

``` mermaid

mindmap
  root((PhysCompute))
    Quantum Mechanics
      3D Particle in a Box
      3D Quantum Harmonic Oscillator
      Eigenvalue Solvers
    Numerical Calculus
      Riemann & Trapezoid Integration
      Numerical Derivatives
      Newton's Method
      Bisection Root Finding
    Linear Algebra
      LU Decomposition
      Matrix Inversion & Determinants
      Euclidean Norms
      Transpose Operations
    Data & Error Analysis
      Discrete Fourier Transform
      Floating Point Error Analysis
      Binary-Decimal Conversion
      Sieve of Eratosthenes

```

## ⚡ Quick Start

You can run any script directly using Python. For example, to find the root of a function using the Newton-Raphson method:

```
# Clone the repository
git clone https://github.com/hamzaakmal98/PhysCompute-A-Numerical-Simulation-Library-for-Classical-Quantum-Physics.git

# Navigate to the directory
cd /PhysCompute-A-Numerical-Simulation-Library-for-Classical-Quantum-Physics

# Run the Newton's Method solver
python "Newton's method.py"

```

**Example Output:**

The script will numerically converge on the root of your defined function:

```
Iteration 1: x = 1.500000, error = 0.250000
Iteration 2: x = 1.416667, error = 0.006944
Iteration 3: x = 1.414216, error = 0.000006
Root found at: 1.414214

```

## 🛠️ Usage for Quantum Simulations

To visualize a 3D Quantum Harmonic Oscillator, ensure you have matplotlib installed, then run:

```
python "3d QHO.py"

```
This script computes the wave function ψ(x,y,z) and renders the probability density across the spatial grid.

## 🧪 Technical Highlights

**Numerical Precision:** Implements adaptive step-sizes in calculus modules to minimize floating-point truncation errors.

**Matrix Operations:** Utilizes LU Decomposition over standard inversion to reduce computational complexity from O(n^3) to O(n^2) for repeated forward/backward substitutions.

**Quantum Modeling:** Visualizes probability densities ∣ψ∣^2 for 3D potentials, providing intuitive insights into quantum tunneling and confinement.
