# Database Module

The database module provides a friendly API for storing relational data related to extensions, especially models representing [Artificial Neural Networks](https://en.wikipedia.org/wiki/Artificial_neural_network), such as genomes. It's a [Native Unity plug-in](https://docs.unity3d.com/Manual/NativePlugins.html) primarily used by extensions of NeuroGen for saving/loading models.

> The module's API is at a much higher level, abstractifying the database engine, SQLite 3. SQLite 3 is used as an embedded and relational database, chosen for its stable and lightweight nature.