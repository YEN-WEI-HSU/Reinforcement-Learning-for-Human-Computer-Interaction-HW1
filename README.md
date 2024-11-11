# Reinforcement-Learning-for-Human-Computer-Interaction-HW1

# DQN introduction
Combines Q-learning with deep neural networks to handle large state spaces.

Uses an ε-greedy strategy to balance exploration (choosing random actions) and exploitation (choosing the best-known actions).

Bellman Equation: Q(st​,at​)= R_t ​+ gamma * max​Q(s_t+1​, a′)

# PPO introduction
PPO belongs to the family of policy gradient methods.

PPO uses a clipped objective function to prevent large updates to the policy.

PPO's clipped objective: L(θ) = E[min(r(θ) * A, clip(r(θ),1−ϵ,1+ϵ) * A) ]
