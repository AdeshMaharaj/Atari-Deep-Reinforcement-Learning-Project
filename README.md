# Atari-Deep-Reinforcement-Learning-Project
**Name:** Adesh Maharaj    

## Project Overview
This project implements and evaluates **Deep Q-Networks (DQN)** and **Double DQN** on the Atari game **Space Invaders**.  
The work is part of **CS6482: Deep Reinforcement Learning** and explores both baseline and improved reinforcement learning techniques.  

Key components:
- Implementation of **Vanilla DQN** using PyTorch and Gymnasium
- Extension to **Double DQN** to reduce overestimation bias
- Training and evaluation on **SpaceInvadersNoFrameskip-v4**
- Discussion of enhancements such as **Dueling DQN**, **Prioritized Experience Replay (PER)**, and **hyperparameter tuning** with Optuna
- References to published research and open-source implementations  

---

Results:

- Vanilla DQN: Achieves stable training but tends to overestimate Q-values.
- Double DQN: Shows improved stability and higher average scores due to reduced bias.
- Performance comparisons, learning curves, and discussions are included in the notebook.

Added Value
The notebook also explores:

- Hyperparameter tuning (e.g., with Optuna, Stable Baselines Zoo configs)
- Dueling DQN architecture
- Prioritized Experience Replay (PER)
- Insights from state-of-the-art RL papers such as Rainbow DQN

References
See the full reference list at the end of the notebook, covering:

- Foundational papers (Mnih et al., van Hasselt et al.)
- Improvements (Rainbow, PER, Dueling DQN)
- Open-source repos and tutorials used for guidance


Notes:
This notebook was developed as part of CS6482: Deep Reinforcement Learning coursework.

It executes fully without errors and is structured with clear sections for reproducibility.

yaml
Copy code

