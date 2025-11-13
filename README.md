# Sybil Detection Showcase

This repository showcases examples of our Sybil detection work and analysis results. Here you can see the outcomes of our detection methods applied to blockchain data.

## Overview

Our analysis identifies suspicious patterns and clusters of addresses that exhibit Sybil behavior across multiple blockchain networks. The detection process involves several stages, each revealing different types of coordinated activity.

## Detection Results

Our comprehensive analysis has identified **11,882 addresses** with suspicious patterns, representing **23.764%** of analyzed addresses and **1.957%** of total points. These addresses were detected through multiple complementary approaches:

- **Graph Analysis**: Identifies interconnected networks of addresses with suspicious transaction patterns
- **Cluster Analysis**: Groups addresses with similar behavioral characteristics
- **Pattern Recognition**: Detects coordinated activities and timing anomalies

## Examples of Our Work

Below are visual examples demonstrating the types of patterns we identify:

### 1. Network Graph Analysis

The following graph illustrates a typical Sybil cluster structure - a central hub address connected to multiple peripheral addresses, indicating coordinated activity:

![Network Graph](graph.png)

This star-shaped network pattern shows a central address (`3ce9...b4c8`) directly connected to 14 peripheral addresses, with bidirectional transactions between them. Such patterns are strong indicators of coordinated Sybil behavior.

### 2. Cluster Analysis Table

The cluster analysis table below shows detailed metrics for a detected cluster, including:

- Transaction timestamps across different chains
- Active days and transaction volumes
- Cross-chain activity patterns
- Volume distributions

![Cluster Analysis Table](cluster_table.png)

The color-coded heatmap visualizes the similarity of behavioral patterns within the cluster. Addresses with similar colors exhibit nearly identical transaction patterns, timestamps, and volume distributions - a clear sign of coordinated activity.

### 3. Detection Summary

The following table summarizes our complete detection results across all analysis stages:

## Sybil Detection Summary

| Analysis Stage            |  Total Addresses |  Total Points        | % of All Addresses | % of All Points |
|--------------------------|--------------------|------------------------|--------------------|-----------------|
| PREVIOUS_SYBILS      | 113                | 9,879,058,667          | 0.226%             | 0.165%          |
| GRAPH_ANALYSIS_PART_1| 922                | 84,743,926,622         | 1.84%              | 1.41%           |
| GRAPH_ANALYSIS_PART_2| 586                | 16,928,731,487         | 1.17%              | 0.28%           |
| CLUSTER_ANALYSIS     | 6,350              | 5,769,054,327          | 12.70%             | 0.10%           |
| ARMA_CLUSTER_ANALYSIS| 3,911              | 128,388,782            | 7.82%              | 0.002%          |
|  **TOTAL**              | **11,882**         | **117,449,159,885**    | **23.764%**        | **1.957%**      |

## Key Insights

- **Graph Analysis** identified 1,508 addresses (3.01% of total) with interconnected suspicious patterns
- **Cluster Analysis** revealed 6,350 addresses (12.70% of total) with similar behavioral characteristics
- **ARMA Cluster Analysis** detected 3,911 addresses (7.82% of total) with advanced pattern anomalies
- Combined detection methods provide comprehensive coverage of different Sybil attack vectors

## Notes

- All visualizations and data presented here are examples from our actual detection work
- Results are based on comprehensive analysis of on-chain transaction data
- Detection methods are continuously refined to identify new patterns and attack vectors
- For inquiries or collaboration opportunities, please contact us through the repository
