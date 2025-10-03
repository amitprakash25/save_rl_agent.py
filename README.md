
## 📌 Problem Context
Habitat fragmentation threatens biodiversity by blocking natural wildlife movement. 
Ecologists need AI-based tools to predict movement corridors, detect barriers, and recommend connectivity paths between habitats.

This project applies **AI + ML techniques** (computer vision, clustering, graph algorithms, predictive modeling, reinforcement learning) to solve this problem.

## 🎯 Assigned Task
My task is **“Save Trained Reinforcement Learning Agent”**.  
This means training a reinforcement learning (RL) model, saving it to disk, and showing how it can be reloaded for future use without retraining.

## 🐍 Code Explanation
- Environment: `CartPole-v1` (used as a simple test environment).  
- Algorithm: PPO (Proximal Policy Optimization) from Stable-Baselines3.  
- Steps:
  1. Train RL agent for 5000 timesteps.
  2. Save the trained model (`ppo_cartpole_agent.zip`).
  3. Load the model back to demonstrate reuse.

## 📦 Installation
Run the following to install required libraries:
```bash
pip install stable-baselines3 gymnasium
