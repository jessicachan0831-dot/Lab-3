# Between the Abyss and the Stars

## Project Overview

This project is an L-System based generative art project created for IAT 460. It explores visual similarities between natural and cosmic structures through two different L-System rule sets:

- **Bioluminescent Coral** — an asymmetric branching structure inspired by coral and underwater plants
- **Stellar Bloom** — a radial structure inspired by snowflakes, crystals, flowers, and stars

The final **Cosmic Garden** combines both systems in one dark environment with scattered points of light.

## Requirements

This project uses Python and the following library:

- ColabTurtle

The project was developed and tested in Google Colab.

## How to Run

1. Open `l-systems.ipynb` in Google Colab.
2. Run the installation cell:

   `!pip install ColabTurtle`

3. Run the notebook cells from top to bottom.
4. The notebook will generate the different L-System patterns and sample outputs.

## Adjustable Parameters

The appearance of the generated patterns can be changed by adjusting:

- `iterations` — controls the complexity and amount of branching
- `angle` — controls the direction and spread of branches
- `distance` — controls the length of each drawn segment
- color values — control the appearance of different branch depths
- line thickness — represents different stages of growth

## Sample Outputs

The project includes five sample outputs:

1. Young Coral
2. Mature Coral
3. Young Stellar Bloom
4. Mature Stellar Bloom
5. Cosmic Garden

The samples demonstrate how different parameters and iteration depths can change the final generated structure.
