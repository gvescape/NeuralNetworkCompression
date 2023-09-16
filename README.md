# NeuralNetworkCompression - CNN Pruning Criterion: Enhancing Efficiency and Interpretability
The success of Convolutional Neural Networks (CNNs) in various applications has led to a significant increase in computing and parameter storage costs. Recent efforts have focused on pruning and compressing the weights of multiple layers to reduce these overheads while preserving performance [1]. This report introduces a novel CNN pruning criterion driven by the interpretability of neural networks. We leverage explainable AI principles to automatically determine the relevance scores of critical components, such as weights or filters. Our investigation establishes a connection between model compression and interpretability research.

In our experiments, we demonstrate the effectiveness of our proposed strategy in transfer-learning scenarios. Specifically, we adapt pre-trained VGG16 models to specific tasks using the CIFAR100 Dataset to evaluate our approach. Notably, our method proves to be particularly advantageous in resource-constrained application scenarios where the target task's data is limited, and fine-tuning is not feasible. With our approach, we achieve a remarkable reduction in model size by a factor of 10 while maintaining a minimal accuracy drop.

Please refer to the report for more details and the implementation [report.pdf](https://github.com/gvescape/NeuralNetworkCompression/blob/main/Deep_Neural_Network_Compression-Final%20Report-1.pdf)
