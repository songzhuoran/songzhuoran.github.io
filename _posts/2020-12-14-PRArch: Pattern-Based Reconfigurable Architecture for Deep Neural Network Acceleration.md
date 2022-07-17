---
thumbnail-img: assets/img/posts/prarch.jpg
---
Zhaoming Jiang, **Zhuoran Song**, Naifeng Jing and Xiaoyao Liang.

Quantization is now widely used for Deep Neural Network (DNN) inference acceleration. While mixed-precision quantization achieve better compression rate as well as better accuracy compared to fixed-precision quantization, it is non- trivial and costly to make hardware accelerator like systolic array to support mixed-precision. In this paper, we propose a Pattern-based Mixed-precision Quantization algorithm, namely PMQ, to transform mixed-precision kernels into fix-precision which is hardware friendly, and we further observe the pattern- based sparsity existing in the high parts of transformed kernels, leading to a novel aggregated sparse kernel convolution. Based on the PMQ, we propose an accelerator PRArch supporting mixed- precision convolution neural networks using fix-precision systolic array with minimal overhead. Experiments on several typical convolution networks show a speedup of 1.86x in average com- pared to coarse-grained quantization accelerator Eyeriss using the same computation chip area, and the accuracy drop less than 1% without fine-tuning.


![prarch](/assets/img/posts/prarch.jpg)

* Accepted by IEEE International Conference on High Performance Computing and Communications (HPCC 2020, CCF-C)
* [[paper]](https://ieeexplore.ieee.org/abstract/document/9408033)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:kBFV-0BrhfwJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KL2pnY:AAGBfm0AAAAAYjPwvnaaPzBoh8kZwaMHA1DQE2ouejR5&scisig=AAGBfm0AAAAAYjPwvqSjiQCq7l1TtszFI-ajTtFq8Bnp&scisf=4&ct=citation&cd=-1&hl=zh-CN)