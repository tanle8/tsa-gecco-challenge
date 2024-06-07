# TSA on GECCO Industrial Challenge Dataset

## Dataset Description

The GECCO 2018 Industrial Challenge, presented by the Genetic and Evolutionary Computation Conference, centered around a critical and increasingly relevant issue—monitoring drinking-water quality. This dataset was provided as part of a competition aimed at fostering innovative approaches in evolutionary computation and machine learning to detect anomalies in water quality, which are indicative of potential health hazards or system failures.

### Dataset Overview
The challenge dataset comprises multivariate time series data collected from a real-world water management system. The data includes several physicochemical parameters measured over time, reflecting the complexity and dynamics of water quality management. Key features include:

- `Time`: Timestamps for each measurement, providing the temporal context for the data.
- `Tp` (Temperature): The water temperature, measured in degrees Celsius, which can influence chemical reactions and microbial growth in water.
- `Cl` (Chlorine Dioxide - MS1) and Cl_2 (Chlorine Dioxide - MS2): Concentrations of chlorine dioxide from two different measurement stations, indicating the level of disinfectant present, which is crucial for maintaining water safety.
- `pH`: A measure of how acidic/basic water is, pivotal for both water quality and equipment maintenance.
- `Redox` (Reduction-Oxidation Potential): An indicator of the water’s ability to break down contaminants.
- `Leit` (Electrical Conductivity): Reflects the water's ionic activity and total dissolved solids.
- `Trueb` (Turbidity): Measures the clarity of water, where higher values may indicate pollution.
- `Fm` and `Fm_2` (Flow rates): Recorded at two different water lines, these indicate the volume of water flow, essential for detecting leaks or changes in water demand.
- `EVENT`: A boolean label identifying whether a measurement is considered an anomaly, crucial for training models to recognize signs of potential issues.

## Applications and Importance

The dataset not only serves as a valuable resource for developing and benchmarking anomaly detection algorithms but also plays a vital role in enhancing the safety and efficiency of water treatment facilities. By accurately identifying anomalies, predictive models can help prevent serious issues such as contamination events or system malfunctions before they affect water quality and public health.

## Link to the dataset

- [GECCO Challenge 2018](https://www.spotseven.de/gecco/gecco-challenge/gecco-challenge-2018/)
- [Resource Package (contains the dataset)](https://www.spotseven.de/wp-content/uploads/2018/03/ResourcePackage2018.zip)

## Authors

Group: Duy Tan LE and Julien Guyet

