# Sybil Detection Showcase

This repository showcases examples of our Sybil detection work and analysis results. Here you can explore the outcomes of our detection methods applied to blockchain data.

## Overview

Our analysis identifies suspicious patterns and clusters of addresses that exhibit Sybil behavior across multiple blockchain networks. The detection process involves several stages, each revealing different types of coordinated activity.

- **Graph Analysis**: Identifies interconnected networks of addresses with suspicious transaction patterns
- **Cluster Analysis**: Groups addresses with similar behavioral characteristics
- **Pattern Recognition**: Detects coordinated activities and timing anomalies

## Cluster Analysis Table

Example table used for checking clusters with random wallets

![Cluster Example](./cluster_example.png)

## Network Graph

Example of a graph used to analyze the connection logic:

![Graph Example](./graph_example.jpg)

## Sybil Detection Summary

Example of final result tables from a completed repository.

### Clusters example

|address                                   |comp_id|points    |hyperlink                                                                                   |
|------------------------------------------|-------|----------|--------------------------------------------------------------------------------------------|
|0x275b38c0ed84f5f902a5303b519d098f5e5f57c2|75     |117250    |[PNG](https://drive.google.com/file/d/18GJk5DTaL6fESqTYOr1Sso1N_NxgQ7HM/view?usp=drive_link)|
|0x44b818d64f2dfc9fc16c502aeff679ebee4769a0|75     |73        |[PNG](https://drive.google.com/file/d/18GJk5DTaL6fESqTYOr1Sso1N_NxgQ7HM/view?usp=drive_link)|
|0x187d1980fd99caf507d3e94b86f8a5aa781ef6a6|75     |154898    |[PNG](https://drive.google.com/file/d/18GJk5DTaL6fESqTYOr1Sso1N_NxgQ7HM/view?usp=drive_link)|
|0x8d241f4a0d718a4a82102a293919a476549a789c|75     |87471     |[PNG](https://drive.google.com/file/d/18GJk5DTaL6fESqTYOr1Sso1N_NxgQ7HM/view?usp=drive_link)|
|0x2715d17e27ba31c3546024163ff0e424886de9cf|75     |121601    |[PNG](https://drive.google.com/file/d/18GJk5DTaL6fESqTYOr1Sso1N_NxgQ7HM/view?usp=drive_link)|

### Summary table

| Analysis Stage            |  Total Addresses |  Total Points        | % of All Addresses | % of All Points |
|--------------------------|--------------------|------------------------|--------------------|-----------------|
| PREVIOUS_SYBILS      | 113                | 9,879,058,667          | 0.226%             | 0.165%          |
| GRAPH_ANALYSIS_PART_1| 922                | 84,743,926,622         | 1.84%              | 1.41%           |
| GRAPH_ANALYSIS_PART_2| 586                | 16,928,731,487         | 1.17%              | 0.28%           |
| CLUSTER_ANALYSIS     | 6,350              | 5,769,054,327          | 12.70%             | 0.10%           |
| ARMA_CLUSTER_ANALYSIS| 3,911              | 128,388,782            | 7.82%              | 0.002%          |
|  **TOTAL**              | **11,882**         | **117,449,159,885**    | **23.764%**        | **1.957%**      |
