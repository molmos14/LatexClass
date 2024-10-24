Based on the contents of your repository, here is a draft README for your **LatexClass** repository:

---

# LatexClass

This repository contains the LaTeX class and document templates used for projects and reports related to the exploration of Mars by the NASA Rover Perseverance.

## Introduction

This repository includes a detailed LaTeX document (`main.tex`) that models the NASA Rover Perseverance using Python, focusing on its exploration in search of water on Mars. The document encompasses various aspects of artificial intelligence concepts, search algorithms, and the performance of the rover in a simulated environment.

## Authors

- **Manuel Olmos Antillón** - Ingeniería en Sistemas Computacionales, Escuela de Ingeniería y Ciencias, Tecnológico de Monterrey
- **Ximena Serna Mendoza** - Ingeniería en Ciencia de Datos y Matemáticas, Escuela de Ingeniería y Ciencias, Tecnológico de Monterrey
- **Guillermo Ian Barbosa Martínez** - Ingeniería en Nanotecnología, Escuela de Ingeniería y Ciencias, Tecnológico de Monterrey
- **Ismael Posadas Pichardo** - Ingeniería en Biotecnología, Escuela de Ingeniería y Ciencias, Tecnológico de Monterrey
- **Paolo Medrano Magaña** - Ingeniería en Biotecnología, Escuela de Ingeniería y Ciencias, Tecnológico de Monterrey

## Table of Contents

- [Introduction](#introduction)
- [PEAS](#peas)
- [Actuators](#actuators)
- [Sensors](#sensors)
- [Representations](#representations)
- [Generated Models](#generated-models)
- [Program Documentation](#program-documentation)
- [Search Algorithms](#search-algorithms)
- [Analysis of Searches](#analysis-of-searches)
- [Conclusions](#conclusions)
- [Appendix](#appendix)
- [References](#references)

## PEAS

### Performance
The Rover Perseverance is designed to collect samples of rock and regolith based on their chemical, physical, mineral, and organic characteristics in search of signs of ancient microbial life.

### Environment
The environment for the rover is the Jezero Crater on Mars, which may have once supported microbial life.

### Actuators
- Wheels for movement
- Integrated camera tripod for panoramic views
- UV laser for chemical detection
- MOXIE for oxygen production from CO2
- Lasers for rock analysis
- Titanium test tubes for sample storage
- Drilling apparatus for surface penetration
- Robotic arm for sample handling

### Sensors
- SuperCam for long-distance chemical analysis
- Microphone for audio recording
- SHERLOC and UV laser for detailed chemical analysis
- RIMFAX for subsurface geological analysis
- PIXL for fine-scale chemical analysis
- MOXIE for CO2 detection and oxygen production

## Representations

![Representations](images/representations.png)
- Water: `--`
- Obstacles: `*`
- Topographical levels: `1, 2, 3, 4, 5, 6`
- Terrain boundary: `#`
- Rover: `+`

## Generated Models

![Generated Model 1](images/env1.jpeg)
![Generated Model 2](images/env2.jpeg)
![Generated Model 3](images/env3.jpeg)
These models represent different simulated environments for the Rover Perseverance.

## Program Documentation

The `environment` code contains functions to create a map with water bodies, obstacles, and varying terrain heights. The functions allow users to specify the number and size of water bodies, obstacles, and the maximum terrain height.

### Libraries
- `random` for random coordinate and dimension generation
- `SimpleAI` for executing informed, uninformed, and local search algorithms

### Functions
- `init_env(width, height)`: Initializes an empty environment.
- `square_coordinates(top_corner, bottom_corner, circular)`: Generates coordinates within a specified rectangle.
- `generate_water_chunks(env, water_chunks_sizes, percentages)`: Generates water bodies in the environment.
- `generate_obstacles(env, obstacles, percentages)`: Generates obstacles in the environment.
- `surrounding(env, coordinate)`: Retrieves elements surrounding a given coordinate.
- `generate_terrain(env, max_terrain_height)`: Generates varying terrain heights.
- `generate_border(env)`: Generates a border around the environment.
- `remove_border(env)`: Removes the border around the environment.
- `environment(...)`: Generates an environment with specified parameters.
- `paint_env(env, show_symbols, rover_pos)`: Prints a visual representation of the environment.

## Search Algorithms

### Informed Searches
- Greedy Search
- Uniform Cost Search
- A* Search

### Uninformed Searches
- Breadth-First Search
- Depth-First Search

### Local Searches
- Hill Climbing
- Hill Climbing with Random Restarts
- Simulated Annealing

## Analysis of Searches

### Informative and Non-Informative
- Map 1
- Map 2
- Map 3

### Local
- Hill Climbing
- Hill Climbing with Random Restarts
- Simulated Annealing

## Conclusions

Summary and findings from the various stages of the project and the capabilities of the Rover Perseverance in its search for water on Mars.

## Appendix

Additional information and technical details.

## References

List of references used in the document.

---

Feel free to modify this draft as needed.
