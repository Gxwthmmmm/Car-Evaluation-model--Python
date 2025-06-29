# Car-Evaluation-model--Python

Car Evaluation Model in the UCI ML Repository
The Car Evaluation dataset from the UCI Machine Learning Repository is derived from a hierarchical decision model designed to assess the acceptability of cars based on multiple attributes. It is widely used for classification tasks and testing machine learning algorithms, especially for structure discovery and constructive induction methods.

Key Details:

Origin: The dataset is based on a decision model developed for the DEX expert system, as described by Bohanec and Rajkovic (1988).

Instances: 1,728

Features: 6 input attributes (all categorical)

Target Variable: Car acceptability (acceptance)

Attributes
Attribute	Description	Possible Values
buying	Buying price of the car	vhigh, high, med, low
maint	Maintenance cost	vhigh, high, med, low
doors	Number of doors	2, 3, 4, 5more
persons	Capacity in terms of persons to carry	2, 4, more
lug_boot	Size of luggage boot	small, med, big
safety	Estimated safety of the car	low, med, high
Target (acceptance): unacc, acc, good, vgood

Model Structure
The original decision model is hierarchical, structured as follows:

CAR (acceptability)

PRICE
buying (buying price)
maint (maintenance cost)

TECH (technical characteristics)
COMFORT
doors (number of doors)
persons (capacity)
lug_boot (luggage boot size)
safety (estimated safety)

Use Cases
Classification: The dataset is primarily used for classification tasks to predict car acceptability based on input features.

Testing Algorithms: It is especially useful for evaluating algorithms that perform constructive induction and structure discovery, given its known underlying concept structure.

