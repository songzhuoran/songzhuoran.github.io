---
thumbnail-img: assets/img/posts/piparch.jpg
---
Image processing arises as a promising domain for manifold applications requiring for heavy computing power and memory bandwidth with higher image resolution. Graphics processing unit (GPU) is widely used in image processing algorithms but suffers from its powerful programmability that costs high hardware overhead. Moreover, GPU consumes much energy to access data from high-capacity register files, making it hard to implement on wearable devices. Enabling low power and efficient architecture with low hardware overhead remains challenging.

In this paper, we propose a programmable image processing architecture (PIPArch) that explores the spatial locality in images to save energy while achieving high performance. We also design the instruction set architecture (ISA) to control the PIPArch. By supporting multiple parallel pipelines, we can keep the hardware utilization of PIPArch high. We evaluate the proposed PIPArch by developing the cycle-accurate simulator with some typical image processing algorithms. Compared to NVIDIA Tesla V100 GPU, PIPArch gains 23.63x speedup.

Authors: Feiyang Wu, **Zhuoran Song**, Jing Ke, Li Jiang, Naifeng Jing and Xiaoyao Liang.

![piparch](/assets/img/posts/piparch.jpg)

* Accepted by 2021 IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA 2022, CCF-C)
* [[paper]](https://ieeexplore.ieee.org/abstract/document/9644888/)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:gYcee5FhPCUJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KLplys:AAGBfm0AAAAAYjPvjystlhPn7uSHaGjSe30xRxIn3WYV&scisig=AAGBfm0AAAAAYjPvj36vXmywTB5v5eiQQNRBfhivNfsC&scisf=4&ct=citation&cd=-1&hl=zh-CN)