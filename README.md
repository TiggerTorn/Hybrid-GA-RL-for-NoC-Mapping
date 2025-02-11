# Reinforcement Learning for Application Mapping Optimization in Network-on-Chip

This repository contains the code and data related to the dissertation titled **"Reinforcement Learning for Application Mapping Optimization in Network-on-Chip"** by Torntan Chainant. The project explores the integration of Reinforcement Learning (RL) with Genetic Algorithms (GA) to improve application mapping efficiency in Network-on-Chip (NoC) architectures, addressing the challenges of communication cost, latency, and power consumption.

Link for the video explanation -> https://www.youtube.com/watch?v=xxTYGuyey_E

## Introduction

Multiprocessor System-on-Chip (MPSoC) designs rely on efficient communication between processing elements. NoC architectures facilitate this but face challenges like high communication costs and latency. Traditional Genetic Algorithms are often used for application mapping, but they can get stuck in local optima. This project proposes a hybrid approach combining RL and GA (GA+RL) to dynamically optimize task placement, aiming to reduce communication costs and improve overall network performance.

## Key Features

- **Hybrid GA+RL Approach**: Combines the robust search capabilities of GA with the adaptive learning of RL.
- **Improved Optimization**: Demonstrates reduced communication costs, particularly in larger NoC topologies.
- **Scalability**: Tested on various mesh sizes, from small (3x3) to larger configurations (12x11).

## Aims & Objectives

- Develop a model for NoC application mapping using a hybrid GA+RL approach.
- Focus on reducing communication costs to enhance network performance.
- Compare the performance of the hybrid approach with traditional GA.
- Assess the scalability of the model across different NoC sizes and complexities.

## Experiment Design

The experiments were conducted using datasets of varying mesh sizes and evaluated three key metrics:

- **Communication Cost**: Measures the efficiency of data transfer between nodes.
- **Convergence Point**: Indicates when the algorithm stabilizes.
- **Runtime**: Total time taken for the algorithm to complete the task.

The GA+RL algorithm consistently achieved lower communication costs but had higher runtimes compared to the original GA. However, the difference in runtime reduced as the network size increased.

## Results

- **Better Optimization**: GA+RL consistently outperforms traditional GA, achieving lower communication costs, especially in larger networks.
- **Robust Convergence**: The hybrid approach effectively avoids local optima, ensuring more reliable optimization.
- **Scalability**: The approach scales well with increasing network size, making it suitable for more complex NoC systems.

