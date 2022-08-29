# Example Double DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_double_dqn_example/blob/master/double_dqn_tutorial.ipynb) of double deep q-network (DDQN) with ReLAx.

DDQN actor was trained on Kangaroo-v0 Atari Gym environment for 3m env-steps. 

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![ddqn_training](https://github.com/nslyubaykin/relax_double_dqn_example/blob/master/ddqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![dqn_q_func](https://github.com/nslyubaykin/relax_double_dqn_example/blob/master/ddqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187167897-00973308-d12c-4aad-9f22-44677599cafa.mp4
