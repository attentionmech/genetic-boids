# GeneticBoids

Simple 2d boid sim with some fun genetic algo inspired quirks. 

## Feats

- **Flocking Behaviors:** Boids exhibit alignment, separation, and cohesion.
- **Genetic System:** Each boid carries a binary genome that affects interaction.
- **Signal-Based Interaction:** Boids can signal genetically similar neighbors, influencing their movement.
- **Reproduction:** Boids reproduce when in close proximity, inheriting mixed genomes.
- **Aging:** Boids have a lifespan and die of old age.

## Explanation about signals and genes

Conceptually its inspired from how one sends a signal here on twitter with what knowledge they have using a tweet and overtime it forms a cluster through a algorithm.

each of those birdies is assigned a gene at start (a string), within a certain range + a larger random search => they can send signal based on that gene. the sudden spider web lines you are seeing are representing those signals. you can configure range, and strength of pull (i.e. how much it will nudge both of them towards each other)

this same gene string is used to create the offspring by cross and mutate. the color you see on these boids is derived from that string.

## Author

[@attentionmech](https://x.com/@attentionmech)  

