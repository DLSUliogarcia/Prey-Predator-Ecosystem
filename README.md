The NetLogo application models a prey-predator ecosystem of foxes, rabbits, and grass patches on a small field.

The Model has the following buttons and sliders:
- rabbit-count: the initial population of rabbits
- fox-count: the initial population of foxes
- rabbit-fertility: the average size of a rabbit’s litter
- fox-fertility: the average size of a fox’s litter
- rabbit-speed: the distance covered by a rabbit’s “forward” motion
- fox-speed: the distance covered by a fox’s “forward” motion
- grass-energy: the energy present in grass patches
- grass-regrowth rate: the number of ticks before grass regrows on the map
- SETUP: sets up the environment based on the inputs
- GO: runs the environment, using the setup

Foxes are the model’s predators, behaving in the following ways:
- All movement costs 1 Energy
- At 0 energy, foxes die, disappearing from the model
- Foxes hunt rabbits, gaining the energy of the eaten rabbit
- Foxes have a 25% chance of reproducing while the model runs. Foxes lose ⅓ of their energy for birthing, split among their litter, each of whom gets 10 plus the portion of the parent’s lost energy.

Rabbits are the model’s prey, behaving in the following ways:
- All movement costs 1 energy
- At 0 energy, rabbits die, disappearing from the model
- Rabbits eat grass patches, gaining the energy of the patch
- Rabbits have a 25% chance of reproducing while the model runs. Rabbits lose ⅓ of their energy for birthing, split among their litter, each of whom gets the divided portion of the parent’s lost energy.

Grass Patches are the model’s food source for the prey
- Grass Patches spawn and grow on random points in the environment.
- Grass Patches have variable amounts of energy.
- Grass Patches regrow on random points after certain amounts of ticks.
