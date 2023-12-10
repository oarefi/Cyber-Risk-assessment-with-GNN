Cyber Risk Assessment with Graph Neural Networks
This repository contains a project focused on using Graph Neural Networks (GNNs) for Cyber Risk Assessment. The project involves creating a synthetic dataset representing a network of assets and applying a GNN model to identify critical nodes in the context of cybersecurity.

Project Overview
Objective: To utilize Graph Convolutional Networks (GCNs) to assess and identify critical assets in a cyber risk environment, based on the likelihood of attack, cost of defense, and cost of remediation.
Dataset: A synthetic dataset representing assets as nodes in a graph, with features including the likelihood of attack, cost of defense, and cost of remediation. Edges represent dependencies between assets.
Model: A Graph Convolutional Network with a custom loss function designed to highlight nodes with high risk and influence within the network.
Application: The model aims to identify critical nodes, providing insights for prioritizing security measures in a cyber risk management framework.
Repository Structure
src/: Source code for the project, including data generation, model definition, and training scripts.
notebooks/: Jupyter notebooks demonstrating the workflow, from data generation to model training and analysis.
data/: Directory containing the synthetic dataset used for the project.
requirements.txt: List of Python packages required to run the code.
Key Features
Synthetic Data Generation: Code to create a synthetic graph dataset simulating a network of assets with associated risk factors.
Graph Neural Network Implementation: Implementation of a GCN model with PyTorch and PyTorch Geometric.
Custom Loss Function: A novel loss function that combines asset risk and network influence, guiding the model to identify critical nodes.
Visualization: Code to visualize the graph and highlight critical nodes identified by the model.
Analysis Tools: Scripts for node-level analysis to validate the model's effectiveness in identifying critical assets.
