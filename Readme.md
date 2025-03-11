# Sparse Signal Recovery using Orthogonal Matching Pursuit (OMP)
## Overview

This project implements the Orthogonal Matching Pursuit (OMP) algorithm for sparse signal recovery, based on the paper titled "Greed is Good: Algorithmic Results for Sparse Approximation" by Joel A. Tropp. The OMP algorithm is applied to various scenarios, including noiseless and noisy cases, as well as the decoding of compressed images and audio signals.

## Project Structure

    code.ipynb: Notebook containing the implementation of the OMP algorithm and experimental setups for signal recovery.
    load_data.py: Python script for loading data used in the project.
    Data/: Directory containing data files necessary for the experiments.
    README.md: This file, providing an overview of the project and its components.

## Requirements

    Python 3.x
    NumPy
    Matplotlib
    SciPy (for loading data)

## Usage
    this repository is just for refrence as utilizing OMP algorithms included in sklearn library is more efficient and easier to use.

## Experimental Setup

The project is divided into several parts, each corresponding to a different aspect of sparse signal recovery using OMP:

    Noiseless Signal Recovery: Evaluates the performance of OMP in recovering sparse signals in the absence of noise. It includes generating synthetic data, computing performance metrics, and plotting phase transition diagrams.

    Noisy Signal Recovery: Extends the evaluation to scenarios with added noise. It analyzes the impact of noise level on recovery performance and compares it with noiseless cases.

    Decoding Compressed Images: Implements OMP for recovering hidden messages from compressed image sketches. It explores the performance of OMP in comparison to least squares solutions.

    Decoding Compressed Audio Signals: Applies OMP to recover messages from compressed audio signals. It investigates the minimum number of measurements required for accurate recovery and compares the results with least squares solutions.

## Results and Analysis

The project provides insights into the effectiveness of the OMP algorithm for sparse signal recovery under various conditions. It includes visualizations such as phase transition plots and reconstructed images/audio signals to illustrate the performance and limitations of OMP.

## References

    Joel A. Tropp, "Greed is Good: Algorithmic Results for Sparse Approximation"
    Additional references cited within the project code.

