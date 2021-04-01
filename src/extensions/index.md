# Extensions

NeuroGen is designed to be modular and extensible, with [convention over configuration](https://en.wikipedia.org/wiki/Convention_over_configuration).

Extensions are supposed to be embedded into the Unity project of NeuroGen and are typically written in C#.

Each extension is expected to host its own algorithm (not necessarily genetic/evolutionary algorithm) for training, testing, etc. However, they all share the same purpose - training cars to drive themselves through [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning).