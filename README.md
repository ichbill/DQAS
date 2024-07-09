# Dataset Quantization with Active Learning based Adaptive Sampling

Zhenghao Zhao, Yuzhang Shang, Junyi Wu, and Yan Yan

This repository is an official PyTorch implementation of the ECCV 2024 paper: Dataset Quantization with Active Learning based Adaptive Sampling

## **Abstract**
<div align="justify">
Deep learning has made remarkable progress recently, largely due to the availability of large, well-labeled datasets. However, the training on such datasets elevates costs and computational demands. To address this, various techniques like coreset selection, dataset distillation, and dataset quantization have been explored in the literature. Unlike traditional techniques that depend on uniform sample distributions across different classes, our research demonstrates that maintaining performance is feasible even with uneven distributions. We find that for certain classes, the variation in sample quantity has a minimal impact on performance. Inspired by this observation, an intuitive idea is to reduce the number of samples for stable classes and increase the number of samples for sensitive classes to achieve a better performance with the same sampling ratio. Then the question arises: how can we adaptively select samples from a dataset to achieve optimal performance? In this paper, we propose a novel active learning based adaptive sampling strategy, Dataset Quantization with Active Learning based Adaptive Sampling (DQAS), to optimize the sample selection. In addition, we introduce a novel pipeline for dataset quantization, utilizing feature space from the final stage of dataset quantization to generate more precise dataset bins. Our comprehensive evaluations on the multiple datasets show that our approach outperforms the state-of-the-art dataset compression methods.
</div>

<br>

Code will be released soon!
