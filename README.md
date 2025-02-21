# mri-multi-spatial: Deep Learning-Driven Spatial Reconstruction of Multi-Component T1 Relaxation Spectra Using Multi-Voxel MRI Signals

This repository contains the code and resources for my Master's thesis project, which focuses on using deep learning to reconstruct spatial multi-component T1 relaxation spectra from multi-voxel MRI signals.  The goal is to improve the speed and accuracy of advanced T1 relaxometry for enhanced tissue characterization.

## Project Structure

The project is organized into the following directories:

*   **`data_analysis`**:  Contains Jupyter notebooks used for data exploration, preprocessing, and analysis.
*   **`models`**:  Contains the implementations of the different deep learning models used in the thesis.
    *   `one_signal`:  Models trained on single-voxel signals.
    *   `spatial_signal_center_spectrum`: Models utilizing spatial information, focusing on the center voxel's spectrum.
    *   `spatial_signal_full_patch`: Models utilizing spatial information, predicting the spectra for all voxels within that patch.
*   **`visualization_evaluation`**: Contains Jupyter notebooks used for visualizing results and evaluating model performance.

## Overview

This project investigates deep learning models for spatial reconstruction of multi-component T1 relaxation spectra, aiming to overcome the limitations of standard T1 mapping techniques in terms of spatial resolution and acquisition speed.  The project uses a synthetic MRI dataset to train and evaluate various architectures, including:

*   Deep Neural Network
*   2D Convolutional Neural Networks
*   3D Convolutional Neural Networks
*   U-Net
