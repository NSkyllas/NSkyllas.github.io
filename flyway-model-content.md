# Flyway model
Simulating migratory routes under environmental constraints

## Context
Migratory birds travel thousands of kilometres between breeding and wintering areas. These journeys are not random. Birds must balance time, energy use, and environmental conditions such as wind and food availability.

The question is: how do these large-scale migration routes emerge from these constraints?

## Approach
I developed a mechanistic model that simulates migration as an optimisation problem. Instead of prescribing routes, the model allows routes to emerge based on environmental conditions and movement costs.

At each step, the model evaluates possible directions and selects the path that minimises a defined cost.

## Key components
- **Wind support**  
  Tailwinds reduce energy costs, while headwinds increase them.

- **Crosswind**  
  Strong crosswinds can push birds off course and increase travel distance.

- **Distance**  
  Shorter routes are generally preferred, but may not always be optimal under atmospheric conditions.

- **Food availability**  
  Stopover locations with higher food availability can offset longer travel distances.

## Results
The model successfully reproduces observed migration patterns when compared with tracking data.

It shows that different populations follow different strategies:
- Some optimise for **energy efficiency**  
- Others optimise for **travel time**

This suggests that migration strategies are shaped by a combination of environmental conditions and ecological context.

## Why it matters
Understanding migration as an optimisation problem helps explain why birds follow specific routes rather than simple shortest paths.

It also provides a framework to explore how migration may change under future climate conditions, where wind patterns and resource availability are shifting.

## Tools
Python, xarray, geospatial data processing, climate reanalysis data, tracking data
