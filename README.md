# Numerical Pursuit Simulation

A numerical investigation of a fox-rabbit pursuit problem using ODE modeling, obstacle constraints, and speed-decay assumptions.

## Project Background

This project models a predator-prey pursuit scenario as a differential game. A fox pursues a rabbit in an environment with physical constraints, including a circular fence, a single opening, and an impenetrable straight-line fence.

## Problem I Solved

The goal was to determine whether the rabbit escapes or the fox captures it under two speed models: constant velocity and diminishing speed caused by fatigue.

## Tools & Tech Stack

- MATLAB.
- ODE modeling.
- `ode45` numerical solver.
- Trajectory visualization.
- Technical reporting in LaTeX.

## Core Features

- Predator-prey trajectory simulation.
- Constant speed model.
- Exponential fatigue speed-decay model.
- Obstacle-aware pursuit path interpretation.
- Comparative analysis of model outcomes.

## Project Highlights

- Shows how a small change in physical assumptions changes path behavior.
- Connects mathematical modeling with robotics and multi-agent systems.
- Uses simulation results to compare model realism.

## Data / AI / Product Thinking

- Data thinking: interprets simulation outputs and compares model scenarios.
- AI relevance: pursuit and multi-agent decision problems are related to robotics and autonomous systems.
- Product thinking: frames model assumptions, constraints, and outcomes clearly for non-specialist readers.

## Outcome

The simulation found fox capture in both constant and diminishing speed models, while the fatigue model produced more complex path behavior due to environmental constraints.

## Repository Structure

```text
numerical-pursuit-simulation/
├── README.md
├── src/
├── reports/
│   └── simulation-summary.md
├── assets/
│   ├── constSpeed.jpg
│   └── DimSpeed.jpg
└── docs/
```

## Resume Bullet

- Built a MATLAB ODE simulation of a constrained predator-prey pursuit problem, comparing constant-speed and fatigue-based models to interpret trajectory outcomes under environmental constraints.

## Contact

For questions or collaboration: [steventang30999@gmail.com](mailto:steventang30999@gmail.com)
