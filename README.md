# Random Walk Metrics

This repository contains solutions for four activities related to the analysis of random walk trajectories and the comparison of observed and theoretical distributions. Each activity focuses on a different type of random walk, including Brownian Motion (BM), Correlated Random Walk (CRW), and Lévy Walk (LW). The results of each activity are visualized using Plotly.

## Activity 1: Path Length - (BM1 vs BM2 vs CRW)
### Objective:
- Generate trajectories: Generate trajectories for three types of random walks: two Brownian Motion (BM) and one Correlated Random Walk (CRW).
- Path length calculation: For each trajectory, calculate the total path length.
- Comparison: Compare the path lengths of the three different trajectories.
- Visualization: Display the results using Plotly graphs.

### Key Functions:
- brownian_motion(): Generates a Brownian Motion trajectory.
- correlated_random_walk(): Generates a Correlated Random Walk trajectory.
- path_length(): Calculates the total path length for a given trajectory.

## Activity 2: Mean Squared Displacement - (BM vs CRW)
### Objective:
- Generate trajectories: Generate Brownian Motion (BM) and Correlated Random Walk (CRW) trajectories.
- Mean squared displacement calculation: For each trajectory, calculate the mean squared displacement.
- Comparison: Compare the mean squared displacement curves of BM and CRW trajectories.
- Visualization: Display the results using Plotly graphs.

### Key Functions:
- mean_squared_displacement(): Calculates the mean squared displacement for a given trajectory.
- plot_msd_comparison(): Compares and visualizes the mean squared displacement curves.

## Activity 3: Turning-angle Distribution - (source dist. vs observed dist.)
### Objective:
- Generate CRW trajectories: Generate two Correlated Random Walk (CRW) trajectories with different Cauchy coefficients.
- Turning angle calculation: Calculate the turning angles for each trajectory.
- Comparison: Compare the observed distribution (histogram of turning angles) with the source distribution (theoretical curve).
- Visualization: Display the results using Plotly graphs.

### Key Functions:
- turning_angles(): Calculates the turning angles from a given trajectory.
- plot_turning_angle_distribution(): Compares and visualizes the observed and source distributions of turning angles.

## Activity 4: Step-length Distribution - (source dist. vs observed dist.)
### Objective:
- Generate LW trajectories: Generate Lévy Walk (LW) trajectories with different alpha coefficients.
- Step length calculation: Calculate the step lengths along each trajectory.
- Comparison: Compare the observed distribution (histogram of step lengths) with the source distribution (theoretical curve).
- Visualization: Display the results using Plotly graphs.

### Key Functions:
- levy_walk(): Generates a Lévy Walk trajectory.
- step_lengths(): Calculates the step lengths for a given trajectory.
- plot_step_lengths_distribution(): Compares and visualizes the observed and source distributions of step lengths.