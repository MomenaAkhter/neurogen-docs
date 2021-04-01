# Main Module

NeuroGen begins all its operations from one module, *Main*.

It abides by the [Singleton Pattern](https://en.wikipedia.org/wiki/Singleton_pattern), making it convenient to access its instance from any part of the simulator.

The Main module initiates the training of cars by activating the selected extension, with the selection set at compile time.

The module also handles loading [native plugins](https://docs.unity3d.com/Manual/NativePlugins.html) of Unity, handling connections with native libraries such as SQLite 3.

## Attributes

- Genome Count (quantity of cars)
- Input count (from the sensors of each car)
- Output count (for controlling each car)
- Genome Prefab ([prefab](https://docs.unity3d.com/Manual/Prefabs.html) representing a car)
- Extensions List
- Default Camera
- Default Track Information
- Selected Extension Index