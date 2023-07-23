# SDaaS Failure Detection for Drone Swarms in Delivery

Welcome to the SDaaS (Swarm Delivery as a Service) Failure Detection code repository! This repository contains the implementation of a battery behavior analysis algorithm that enables the detection of soft failures in drone swarms during delivery operations. The code utilizes a margin-aware pruning technique and a signal-based heuristic to classify battery behavior time series as either soft failing or not. Additionally, it computes a severity score to assess the overall impact of the detected failure on the drone swarm's delivery capabilities.


## Introduction

Drone swarms play a critical role in modern delivery systems, and ensuring their reliable operation is of utmost importance. This repository presents an algorithm designed to detect soft failures in drone swarms, which could lead to delivery disruptions. The code combines a margin-aware pruning approach with a signal-based heuristic to analyze the battery behavior time series and make accurate failure predictions.

## Dataset

To train and evaluate the SDaaS Failure Detection algorithm, we used the Oxford Battery Degradation Dataset, available at the following link: [Oxford Battery Degradation Dataset](https://ora.ox.ac.uk/objects/uuid:03ba4b01-cfed-46d3-9b1a-7d4a7bdf6fac). Please download the dataset "Oxford_Battery_Degradation_Dataset_1.mat" from the link and place it in the directory before running the code.

