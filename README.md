# SciPlex Perturbation Prediction

This repository contains the code and analysis for CS 582 Coding Assignment 1. This project will explore 
perturbation prediction using Graph Neural Networks (GNN) on single-cell RNA sequencing data, and will 
explore GNN explainability frameworks for explaining model predictions and identifying genes which are
predictive of the perturbation.

# Quickstart

To run the main code and analysis notebook, the only requirement is a Python environment with common
numerical and plotting libraries (Numpy, Pandas, Matplotlib) as well as common single-cell analysis
libraries (Anndata, Scanpy). For Deep Learning and GNNs, Pytorch and Pytorch geometric are required.

An environment file is provided, which can be used to recreate the same environment used during project
development:

```conda create -n pyg --file environment.yml```
