# Deep Learning Homework 2: Innovations in CNN Architectures

This Jupyter Notebook, `DL_HW2_b10705016.ipynb`, embodies a comprehensive exploration into the realm of Convolutional Neural Network (CNN) architecture design and optimization. Situated within the academic framework of a deep learning course, this assignment transcends traditional architectural paradigms by reimagining and refining CNN structures. The endeavor not only revisits seminal architectures like AlexNet, LeNet, and ResNet but also pioneers the integration of novel architectural elements aimed at amplifying model performance and efficiency.

## Overview

The notebook serves as a testament to the architectural depth and breadth of CNNs, meticulously detailing the development and refinement of custom CNN configurations. The narrative woven throughout this scholarly work emphasizes the pragmatic synthesis of theoretical concepts with the PyTorch framework, resulting in a critical evaluation of how architectural innovations can significantly elevate model performance.

## Architectural Highlights

At the heart of this notebook lies a model that draws inspiration from the profound insights of **ResNet** and **Network in Network (NiN)** frameworks. This synthesis is meticulously engineered, featuring bespoke residual blocks coupled with global average pooling techniques to forge a pathway toward enhanced learning dynamics and model interpretability.

### Custom Residual Blocks (ResBlocks)

A cornerstone of this architectural exploration is the `myResBlock`, a module meticulously engineered to harness the power of residual connections. This innovation facilitates a more robust information flow across the network, effectively combating the degradation problem and empowering the model to learn more complex representations with increased depth.

### Global Average Pooling: A Paradigm Shift

Embracing the elegance of simplicity, the notebook champions the use of global average pooling as a strategic alternative to fully connected layers. This approach not only mitigates the risk of overfitting by reducing the model's parameter count but also aligns with contemporary efforts to distill the essence of spatial feature maps into a compact and informative representation directly correlated with class predictions.

## Experimental Insights

In an evaluation of model performance, our experiments showcased a remarkable advancement in accuracy metrics. A traditional CNN combined with a Multi-Layer Perceptron (MLP) model, serving as our baseline, achieved an accuracy of 76%. In contrast, the refined architecture proposed in this notebook, despite adhering to a stringent model size constraint of under 6MB, significantly outperformed the baseline by securing an 81% accuracy. This leap in performance, achieved without compromising on model compactness, underscores the effectiveness of the introduced architectural modifications and sets a new benchmark for efficient CNN design.

## References

- [https://www.youtube.com/watch?v=DkNIBBBvcPs](https://www.youtube.com/watch?v=DkNIBBBvcPs)
- [https://medium.com/@chensheep1005/network-in-network-d847f9232846](https://medium.com/@chensheep1005/network-in-network-d847f9232846)
- [https://medium.com/ching-i/%E5%8D%B7%E7%A9%8D%E7%A5%9E%E7%B6%93%E7%B6%B2%E7%B5%A1-cnn-%E7%B6%93%E5%85%B8%E6%A8%A1%E5%9E%8B-lenet-alexnet-vgg-nin-with-pytorch-code-84462d6cf60c](https://medium.com/ching-i/%E5%8D%B7%E7%A9%8D%E7%A5%9E%E7%B6%93%E7%B6%B2%E7%B5%A1-cnn-%E7%B6%93%E5%85%B8%E6%A8%A1%E5%9E%8B-lenet-alexnet-vgg-nin-with-pytorch-code-84462d6cf60c)