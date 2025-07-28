# Physics_Informed_Neural_Nets_PINNs
Some common Physics-based Differential Equations solved with the help of Neural Networks

- **PINNs–Schrodinger_Equation_LLM_Int.ipynb**
  Integrates GPT 3.5-Turbo to dynamically assign Learning Rates and control the Number of Epochs to train the PINN. The Training is done in short bursts of Epochs. The LLM analyzes the Loss trend to decides whether to go for the next burst of epoch or not. It also decides the learning rate for the burst.
  
- **PINNs–Schrodinger_Equation.ipynb**  
  Applies PINNs to approximate solutions of the time‑dependent Schrödinger equation.

- **PINNs–Newton’s_Law_of_cooling.ipynb**  
  Demonstrates a PINN approach to modeling exponential temperature decay in Newton’s law of cooling.

- **PINNs–Neumann_Dirichlet.ipynb**  
  Enforces mixed Neumann and Dirichlet boundary conditions in a PINN framework for PDEs.

- **PINNs–System_of_ODEs.ipynb**  
  Solves coupled systems of ordinary differential equations using physics‑informed neural networks.

- **PINNs–Solving_ODE.ipynb**  
  Uses PINNs to learn the solution of a single ordinary differential equation from data.
