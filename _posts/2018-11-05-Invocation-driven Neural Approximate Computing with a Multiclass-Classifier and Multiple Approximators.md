---
thumbnail-img: assets/img/posts/dropout.jpg
---
Haiyue Song, Li Jiang, Chengwen Xu, **Zhuoran Song**, Naifeng Jing, Xiaoyao Liang and Qiang Xu.

The training phases of Deep neural network (DNN) consumes enormous processing time and energy. Compression techniques utilizing the sparsity of DNNs can effectively accelerate the inference phase of DNNs. However, it can be hardly used in the training phase because the training phase involves dense matrix-multiplication using General Purpose Computation on Graphics Processors (GPGPU), which endorse regular and structural data layout. In this paper, we propose the Approximate Random Dropout that replaces the conventional random dropout of neurons and synapses with a regular and online generated patterns to eliminate the unnecessary computation and data access. We develop a SGD-based Search Algorithm that producing the distribution of dropout patterns to compensate the potential accuracy loss. We prove our approach is statistically equivalent to the previous dropout method. Experiments results on multilayer perceptron (MLP) and long short-term memory (LSTM) using well-known benchmarks show that the speedup rate brought by the proposed Approximate Random Dropout ranges from 1.18-2.16 (1.24-1.85) when dropout rate is 0.3-0.7 on MLP (LSTM) with negligible accuracy drop.

![dropout](/assets/img/posts/dropout.jpg)

* Accepted by ACM/IEEE International Conference on Computer-Aided Design (ICCAD 2018, CCF-B)
* [[paper]](https://dl.acm.org/doi/abs/10.1145/3240765.3240819)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:epvgja-q7sIJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KL3Z_U:AAGBfm0AAAAAYjPxf_XHLLmwO6JQvPcH2M2oNBADfT1A&scisig=AAGBfm0AAAAAYjPxf2nE3KySXiunXlS7J88u6lxKj3Ck&scisf=4&ct=citation&cd=-1&hl=zh-CN)