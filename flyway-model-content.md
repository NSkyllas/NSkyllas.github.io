# Flyway model
Simulating seabird migration routes with wind, distance, and food as guiding factors

## Context
Migratory birds do not simply follow the shortest route. They move through an atmosphere that can help or hinder them, and they also need access to productive stopover areas.

This project asked a simple question: can we explain real flyways by combining a few key environmental costs?

## Approach
I built a least-cost path model that simulates many possible flyways. Each route is scored using wind support, crosswind, travel distance, and food availability.

I then compared the simulated routes with tracking data from Arctic terns to see which combinations of costs best matched the observed migrations.

## Key components
- **Wind support**  
  Tailwinds make migration easier, while headwinds make it harder.

- **Crosswind**  
  Side winds can push birds away from their preferred route.

- **Distance**  
  Shorter routes often save time and energy.

- **Food availability**  
  Productive ocean regions can make longer routes worthwhile.

## Results
The model reproduced the main flyway patterns seen in the tracking data. It also showed that different Arctic tern populations seem to solve migration in different ways.

The Svalbard population was better explained by effort-saving routes shaped strongly by wind, while the Dutch population was better explained by routes that balance time, distance, and food.

## Why it matters
This helps explain why birds use certain ocean flyways instead of simply flying along the shortest line between two points.

It also provides a practical framework for asking how migration routes may shift when wind patterns and marine productivity change.

## Tools
Python, xarray, geospatial data processing, climate reanalysis data, tracking data
