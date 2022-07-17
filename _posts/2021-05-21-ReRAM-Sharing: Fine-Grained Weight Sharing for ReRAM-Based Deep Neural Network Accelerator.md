---
thumbnail-img: assets/img/posts/sharing.jpg
---
Deep Neural Networks (DNNs) have gained a strong momentum across various applications in recent years. Mean- while, they are compute- and memory-intensive as the deep layers induce massive matrix-multiplication operations. The Resistive Random Access Memory (ReRAM) can naturally carry out the matrix-multiplication in memory. Therefore, ReRAM-based accelerators are widely used for deploying DNN applications. Researchers strive to compress DNNs to accelerate DNNs on the ReRAM-based accelerators. However, the existing works focus on ReRAM-crossbar level compression. Such coarse-grained pruning lacks the flexibility for a higher compression rate.

In this paper, we present our ReRAM-Sharing, a software- hardware co-design scheme, to explore fined-grained weight sharing compression for ReRAM-based accelerators. Due to the limits of ADC bandwidth and ADC numbers, DNN computation on ReRAM crossbars is conducted in a smaller granularity, denoted as Operation Unit (OU). Motivated by this, we propose ReRAM-Sharing algorithm that applies weight-sharing on OU- level to exploit fine-grained sparsity. Our proposed ReRAM- Sharing reduces the redundancy of DNNs while maintaining the representation capability. Moreover, as the ReRAM-Sharing algorithm is orthogonal with the traditional pruning techniques, we can integrate them to shrink NN model size further. We then propose the ReRAM-Sharing architecture, which introduces the index table and adders to the traditional ReRAM-based accel- erator, to support the ReRAM-Sharing algorithm. Experiment results show that our proposed ReRAM-Sharing achieves up to 59.39x and 14.47x compression ratio with negligible accuracy loss on CIFAR-10 and ImageNet datasets, respectively.

Authors: **Zhuoran Song\***, Dongyue Li\*, Zhezhi He, Xiaoyao Liang and Li Jiang.

![sharing](/assets/img/posts/sharing.jpg)

* Accepted by IEEE International Symposium on Circuits and Systems (ISCAS 2021, CCF-C)
* [[paper]](https://ieeexplore.ieee.org/abstract/document/9401155)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:DnjWBzavqeUJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KLpzkM:AAGBfm0AAAAAYjPv1kOkFzdY9w5lYwiG8AiZsp0J2oyf&scisig=AAGBfm0AAAAAYjPv1nguDzdZXOj5ULfbnA4zhxYqaQZg&scisf=4&ct=citation&cd=-1&hl=zh-CN)