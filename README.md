# Plotting Radar Chart with Python

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Rye](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/rye/main/artwork/badge.json)](https://rye.astral.sh)

## Dependency

- [python](https://www.python.org/)
  - version 3.10 or higher is recommended.

- [rye](https://rye.astral.sh/)
  - seting up python environment easily and safely.
  - `numpy`, `matplotlib`, `notebook`, `pandas`, `pycirclize` are needed to run all scripts in this repository.

## Setup
```sh
git clone https://github.com/MizuhoAOKI/radar_chart.git
cd radar_chart
rye sync
```

## Usage

### Plot Radar Chart

```sh
cd radar_chart
rye run jupyter notebook notebooks/plot_iros2024_result.ipynb
```

Evaluation Data

<img src="./media/iros2024_result_table.png" width="500" />

Radar Chart of Cylinder Garden

<img src="./media/radar_cylinder_garden.png" width="300" />

Radar Chart of Maze

<img src="./media/radar_maze.png" width="300" />

## Acknowledgement
I used [pyCirclize](https://moshi4.github.io/pyCirclize/) to plot the rader charts.

Thank you for developing such a useful visualization tool!
