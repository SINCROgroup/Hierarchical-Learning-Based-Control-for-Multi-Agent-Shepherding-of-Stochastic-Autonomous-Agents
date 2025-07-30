# Hierarchical Reinforcement Learning for Multi-Agent Shepherding of Non-Cohesive Targets  

This repository contains the source code and demonstration videos associated with the paper:  

**[1]** Italo Napolitano, Stefano Covone, Andrea Lama, Francesco De Lellis, Mario di Bernardo, *"Hierarchical Reinforcement Learning for Multi-Agent Shepherding of Non-Cohesive Targets,"* 2025.  

## Repository structure  

### `videos/`  

This folder contains the demonstration videos referenced in the paper:  

- **`dqn_1H1T.mp4`**: Simulation from Section IV.C (Fig. 3a in [1]). A single herder (blue diamond) corrals and contains a single target (magenta dot) within the goal region (green circle) using a Deep Q-Network (DQN) policy.  

- **`ppo_1H1T.mp4`**: Simulation from Section IV.C (Fig. 3b in [1]). A single herder uses a Proximal Policy Optimization (PPO) policy to corral a single target into the goal region.  

- **`ppo_2H5T.mp4`**: Simulation from Section V.C (Fig. 7 in [1]). Two herders corral and contain five targets using a Multi-Agent PPO (MAPPO) hierarchical policy.  

- **`scalability.mp4`**: Simulation from Section VI.C (Fig. 9 in [1]). Demonstrates the scalability of the trained MAPPO network by extending it from 2 herders/5 targets to 5 herders/50 targets. Each herder senses only the five closest targets and the nearest herder.  

- **`tracking.mp4`**: Simulation from Section VI.D (Fig. 10 in [1]). Two herders guide five targets towards a time-varying goal region in a tracking scenario.  

- **`robotarium.mp4`**: Experiment from Section VII (Fig. 11 in [1]). Two herder robots corral and contain five target robots on the Robotarium platform using a MAPPO hierarchical policy.  
