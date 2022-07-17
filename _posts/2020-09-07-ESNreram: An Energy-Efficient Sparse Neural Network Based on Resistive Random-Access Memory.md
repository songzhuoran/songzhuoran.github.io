---
thumbnail-img: assets/img/posts/esnreram.jpg
---

**Zhuoran Song**, Yilong Zhao, Yanan Sun, Xiaoyao Liang and Li Jiang.

The sparsity in the deep neural networks (DNNs) can be leveraged by methods such as pruning and quantization to assist the energy-efficient deployment of large-scale deep neural networks onto hardware platforms, such as GPU and ASIC, for better performance and power efficiency. However, for the metal-oxide resistive random access memory (ReRAM) architecture, the study of energy-efficient methods still shrink the model size or constrain the precision of DNN by leveraging the DNN sparsity. Due to the circuit features of ReRAM, reading bit-0 naturally consumes less energy than reading bit-1. In this paper, we exploit the fine-grained tuning method on the bit-level to reduce energy consumption of ReRAM. Specifically, we present the gradient-search and the weight-group update algorithm, which can significantly unbalance the proportion of bit-1 and bit-0 inside the weights of DNN with negligible NN accuracy loss. Experiments demonstrate that the percentage of bit-0, in some typical convolutional neural networks (CNNs), increases to 33.8%, with less than 0.5% degradation in NN accuracy. The energy reduction can be up to 65%.

![esnreram](/assets/img/posts/esnreram.jpg)

* Accepted by ACM/IEEE Accepted by ACM/IEEE (GLSVLSI 2020, CCF-C)
* [paper](https://dl.acm.org/doi/abs/10.1145/3386263.3406897)
* [cite](https://scholar.googleusercontent.com/scholar.bib?q=info:XpHr1d7jUUwJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KL3SfM:AAGBfm0AAAAAYjPxUfO8BxtCttBR9HZ9V4EuRwq0Cq83&scisig=AAGBfm0AAAAAYjPxUXAoLzgHZZLeMf8_8O-U5Ddh4N0X&scisf=4&ct=citation&cd=-1&hl=zh-CN)