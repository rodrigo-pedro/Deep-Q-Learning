# Deep-Q-Learning

Implementation of Deep Q-Learning and Double Deep Q-Learning algorithms for the [Highway-env](https://github.com/Farama-Foundation/HighwayEnv) Gym environment.

Uses a Conv Net to approximate the Q-function. Supports stacking of frames to capture temporal information with an LSTM layer. In both algorithms, the model is trained using a replay buffer and target network to stabilize learning.

## Files

- `dqn.ipynb`: Deep Q-Learning notebook
- `ddqn.ipynb`: Double Deep Q-Learning notebook
