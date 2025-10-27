# Sequential Decision Making with Stochastic Bandits

## Project Description
This project implements classical stochastic multi-armed bandit algorithms, including **epsilon-greedy** and **Upper Confidence Bound (UCB)**, to simulate sequential decision making in uncertain environments. We analyze cumulative rewards, explore-exploit trade-offs, and visualize algorithmic performance. Applications include finance, adaptive clinical trials, and sustainable resource allocation.

**Research Alignment:**  
- Sequential decision making and stochastic modeling (Guanting Chen)  
- Stochastic processes and interacting particle systems (Vidyadhar G. Kulkarni)  
- Machine learning applications in decision-making and optimization  

## Project Outcomes
- Implementation of **epsilon-greedy** and **UCB** algorithms
- Simulation of a multi-armed Bernoulli bandit environment
- Cumulative reward analysis and visualization
- Discussion and inference of algorithm performance

## Methodology
1. **Environment Setup:** Multi-armed Bernoulli bandit with specified reward probabilities.
2. **Algorithms Implemented:**
   - Epsilon-Greedy: Balances exploration and exploitation using a fixed probability ε.
   - UCB (Upper Confidence Bound): Selects arms based on confidence intervals to prioritize exploration efficiently.
3. **Simulation:** Run each algorithm for a large number of steps and record rewards.
4. **Visualization:** Plot cumulative rewards to compare performance.
5. **Evaluation:** Discuss convergence, performance, and real-world applicability.

## Results
- UCB achieves higher cumulative rewards than epsilon-greedy in most simulations.
- Both algorithms learn to select optimal arms over time.
- Provides a foundational understanding for more advanced reinforcement learning techniques.

## Discussion
- **Epsilon-Greedy:** Simple and effective, but exploration is uniform and independent of past knowledge.
- **UCB:** Adapts exploration according to uncertainty, often outperforming epsilon-greedy in longer horizons.
- Demonstrates sequential decision making, stochastic modeling, and algorithmic learning.

## Inference
- Both algorithms successfully illustrate the exploration-exploitation trade-off.
- The framework can be extended to applications in finance, healthcare, neuroimaging, and sustainability.
- Highlights the practical impact of sequential learning in stochastic environments.

## Tools
- Python >=3.8  
- NumPy  
- Matplotlib  
- Seaborn  
