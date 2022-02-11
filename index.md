**Abstract:** Equivariant neural networks enforce symmetry within the structure of their convolutional layers, resulting in a substantial improvement in sample efficiency when learning an equivariant or invariant function. Such models are applicable to robotic manipulation learning which can often be formulated as a rotationally symmetric problem. This paper studies equivariant model architectures in the context of Q-learning and actor-critic reinforcement learning. We identify equivariant and invariant characteristics of the optimal Q-function and the optimal policy and propose equivariant DQN and SAC algorithms that leverage this structure. We present experiments that demonstrate that our equivariant versions of DQN and SAC can be significantly more sample efficient than competing algorithms on an important class of robotic manipulation problems.

## Paper

## Idea

## Video

## Code

[https://github.com/pointW/equi_rl](https://github.com/pointW/equi_rl)

## Citation
```
@inproceedings{
wang2022mathrmsoequivariant,
title={SO(2)-Equivariant Reinforcement Learning},
author={Dian Wang and Robin Walters and Robert Platt},
booktitle={International Conference on Learning Representations},
year={2022},
url={https://openreview.net/forum?id=7F9cOhdvfk_}
}
```

## Contact
If you have any questions, please feel free to contact [Dian Wang](https://pointw.github.io) at wang[dot]dian[at]northeastern[dot]edu.
