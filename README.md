# 毕业设计题目：设备算力差异对联邦学习的影响研究
中文摘要：在联邦学习的应用场景中，各设备的算力通常存在差异。本文深入研究了联邦学习中设备算力差异对模型训练的影响，并探究了FedProx算法在解决这一问题上的独特优势。通过模拟不同算力差异的实验环境，我们详细分析了FedProx算法与传统FedAvg算法，以及FedProx在是否存在近端项情况下，在测试准确率、模型稳定性等方面的表现。实验结果表明，FedProx算法在设备算力差异较大的情况下，能够显著提升模型的测试准确率，同时增强模型的稳定性。并且在近端项的存在下有效地限制了客户端模型与全局模型之间的差异。这一机制不仅有助于减少由数据异质性引发的模型偏差，还能显著促进全局模型的稳定性。这一研究不仅验证了FedProx算法在处理算力差异问题上的有效性，也为联邦学习在异构设备环境中的应用提供了可行的解决方案。本研究对于优化联邦学习算法、提升模型性能具有重要的理论和实践意义。
英文摘要：In the application scenarios of federated learning, there are often variations in the computational power of various devices. This paper delves into the impact of device computational power differences on model training in federated learning and explores the unique advantages of the FedProx algorithm in addressing this issue. By simulating experimental environments with varying computational power differences, we analyze in detail the performance of the FedProx algorithm and the traditional FedAvg algorithm, as well as the performance of FedProx with and without the proximal term, in terms of test accuracy, model stability, and other metrics. The experimental results show that the FedProx algorithm can significantly improve the test accuracy of the model and enhance its stability when there are large differences in device computational power. Furthermore, the presence of the proximal term effectively limits the difference between the client models and the global model. This mechanism not only helps reduce model biases caused by data heterogeneity but also significantly enhances the stability of the global model. This research not only verifies the effectiveness of the FedProx algorithm in handling computational power differences but also provides a feasible solution for the application of federated learning in heterogeneous device environments. This study has important theoretical and practical significance for optimizing federated learning algorithms and improving model performance.
kaggle计算机程序网址：https://www.kaggle.com/code/dushulang/fedprox2?scriptVersionId=180567884
