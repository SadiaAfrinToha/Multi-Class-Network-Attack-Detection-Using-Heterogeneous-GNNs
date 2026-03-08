# Multi-Class Network Attack Detection using Heterogeneous Graph Neural Networks

This project focuses on detecting multiple types of network attacks using **Heterogeneous Graph Neural Networks (HeteroGNN)**. The goal is to model network traffic as a graph and analyze relationships between different entities such as hosts and flows to improve intrusion detection.

## Overview
Traditional intrusion detection systems often struggle to capture complex relationships within network traffic. In this work, network data is represented as a **heterogeneous graph**, allowing the model to learn interactions between different node types.

Two graph neural network architectures are implemented and compared:

- **GraphSAGE-based HeteroGNN**
- **Graph Transformer-based HeteroGNN**

## Dataset
The dataset contains approximately **539,998 network traffic records** categorized into four classes:
- Benign  
- PingScan  
- PortScan  
- DoS  

## Objective
The main objective of this project is to evaluate how different **Heterogeneous GNN architectures** perform in detecting and classifying network attacks in large-scale traffic data.

## Results
The GraphSAGE-based HeteroGNN achieved:
- **96.13% Macro F1 Score (Validation)**
- **94.94% Test Accuracy**

## Technologies Used
- Python  
- PyTorch  
- PyTorch Geometric  
- Graph Neural Networks (GNN)  
- Network Security / Intrusion Detection
