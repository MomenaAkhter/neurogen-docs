# NEATPack

NeatPack is an extension of NeuroGen based on the NEAT algorithm. It includes features such as:

- Training cars, based on neural networks, to drive, using the NEAT algorithm
- Rendering the topologies of neural networks on screen

## Notes

- When a session starts:
    - All the cars are instantiated by the `PopulationProxy.InstantiateAllGenomes` method
    - Genome instances are created by the `Population.Populate` method
- `Genome` instances are converted to `PackedGenome` instances for serialization/deserialization
- Genomes are stored in the `PopulationCar.Evolve` method