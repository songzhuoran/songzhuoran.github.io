---
thumbnail-img: assets/img/posts/e2sr.jpg
---
Nowadays high-resolution (HR) videos have been a popular choice for a better viewing experience. Recent works have shown that super-resolution (SR) algorithms can provide superior quality HR video by applying the deep neural network (DNN) to each low-resolution (LR) frame. Obviously, such per-frame DNN processing is compute-intensive and hampers the deployment of SR algorithms on mobile devices. Although many accelerators have proposed solutions, they only focus on mobile devices. Differently, we notice that the HR video is originally stored in the cloud server and should be well exploited to gain high accuracy and performance improvement. Based on this observation, this paper proposes an end-to-end video CODEC assisted system (E<sup>2</sup>SR), which tightly couples the cloud server with the device to deliver a smooth and real-time video viewing experience. We propose the motion vector search algorithm executed in the cloud server, which can search the motion vectors and residuals for part of HR video frames and then pack them as addons. We further propose the reconstruction algorithm executed in the device to fast reconstruct the corresponding HR frames using the addons to skip part of DNN computations. We design the corresponding E<sup>2</sup>SR architecture to enable the reconstruction algorithm in the device, which achieves significant speedup with minimal hardware overhead. Our experimental results show that the E<sup>2</sup>SR system achieves 3.4x performance improvement with less than 0.56 PSNR loss compared with the state-of-the-art EDVR scheme.

Authors: **Zhuoran Song**, Zhongkai Yu, Naifeng Jing and Xiaoyao Liang.

![e2sr](/assets/img/posts/e2sr.jpg)

* Accepted by Design Automation Conference (DAC 2022, CCF-A)
* [paper](https://dl.acm.org/doi/abs/10.1145/3489517.3530423)
* [cite](https://scholar.googleusercontent.com/scholar.bib?q=info:nUNm4YqWNI4J:scholar.google.com/&output=citation&scisdr=Cm1sAW37EPrgrjn0KqQ:AGlGAw8AAAAAZJryMqRTJQ-Oo_b_sTQEUjqKxjI&scisig=AGlGAw8AAAAAZJryMu16E-si0piOIq4-Op7Zc3c&scisf=4&ct=citation&cd=-1&hl=zh-CN)