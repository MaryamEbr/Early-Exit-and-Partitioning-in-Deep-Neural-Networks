# Early-Exit-and-Partitioning-in-Deep-Neural-Networks
This repository contains some of the codes for the paper "Combining DNN partitioning and early exit" published in EdgeSys '22: Proceedings of the 5th International Workshop on Edge Systems, Analytics and Networking, April 2022

Abstract:
DNN inference is time-consuming and resource hungry. Partitioning and early exit are ways to run DNNs efficiently on the edge. Partitioning balances the computation load on multiple servers, and early exit offers to quit the inference process sooner and save time. Usually, these two are considered separate steps with limited flexibility. This work combines partitioning and early exit and proposes a performance model to estimate both inference latency and accuracy. We use this performance model to offer the best partitioned/early exit DNN based on deployment information and user preferences. Our experiments show that the flexibility in the number and position of partitioning points and placement on available devices plays an important role in deciding the best output.

Evaluated models and datasets are:
- ResNet + CIFAR10
- InceptionV3 + CIFAR10
- MobileNetV3 + CIFAR10
- ResNet + cat and dog

The code for these models is written in TensorFlow and can be found in the repository.
