# agentGenerativeTracking

## Generative Models for Goal-Directed Movement

This repository contains Julia code implementing generative models for simulating goal-directed movements in diverse scenarios. The models include the Random Walk Model, Goal-Directed Model, Tourist Model, and New Yorker Model. Each model is defined using the Gen probabilistic programming language, capturing distinct characteristics such as uncertainty, noise, and goal-directed behavior.

## Key Features:

Random Walk Model: Simulates movements with random steps and measurement noise.
Goal-Directed Model: Represents purposeful movements towards a goal with adjustable uncertainty.
Tourist Model: Introduces increased noise and step variance to model tourist-like movement patterns.
New Yorker Model: Features reduced uncertainty, simulating more directed movements akin to locals.
Inference Scripts:
The repository includes scripts for performing Bayesian inference using Metropolis-Hastings on the generative models. Explore how these models can be fitted to observed data to make inferences about the underlying parameters governing movement patterns.

## Usage:

Clone the repository: git clone https://github.com/your-username/generative-movement-models.git
Install dependencies: julia install.jl
Explore and run generative models and inference scripts: julia run_inference.jl
Contributions and Feedback:
Contributions, bug reports, and feedback are welcome! Feel free to open issues or pull requests to enhance the functionality and usability of the models.
