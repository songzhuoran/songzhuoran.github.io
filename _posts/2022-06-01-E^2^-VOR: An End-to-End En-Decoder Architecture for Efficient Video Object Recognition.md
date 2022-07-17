---
thumbnail-img: assets/img/posts/e2vor.jpg
---

**Zhuoran Song**, Naifeng Jing and Xiaoyao Liang.

High-resolution video object recognition (VOR) evolves so fast but is very compute-intensive. This is because VOR leverages compute-intensive deep neural network (DNN) for better accuracy. Although many works have been proposed for speedup, they mostly focus on DNN algorithm and hardware acceleration on the edge side. We observe that most video streams need to be losslessly compressed before going online and an encoder should have all the video information. Moreover, as the cloud should have abundant computing power to handle sophisticated VOR algorithm, we propose to take one-shot effort for a modified VOR algorithm at the encoding stage in cloud and integrate the full VOR regeneration into a slightly extended decoder on the device. The scheme can enable light-weight VOR with server-class accuracy by simply leveraging the classic and economic video decoder universal to any mobile device. Meanwhile, the scheme can save massive computing power for not repetitively processing the same video on different user devices that makes it extremely sustainable for green computing across the whole network. 

We propose E^2^-VOR, an end-to-end encoder and decoder architecture for efficient VOR. We carefully design the scheme to have minimum impact on the video bitstream transmitted. In the cloud, the VOR extended video encoder tracks on a macro-block basis and packs intelligent information into the video stream for increased VOR accuracy and fast regenerating process. On the edge device, we extend the traditional video decoder with a small piece of dedicated hardware to enable the efficient VOR regeneration. Our experiment show that E^2^-VOR can achieve 5.0X performance improvement with less than 0.4% VOR accuracy loss compared to the state-of-the-art FAVOS scheme. On average, E^2^-VOR can run over 54 frames-per-second (FPS) for 480P videos on an edge device.

![e2vor](/assets/img/posts/e2vor.jpg)

* Accepted by Transactions on Design Automation of Electronic Systems (TODAES 2022, CCF-B)
* [paper](https://dl.acm.org/doi/abs/10.1145/3543852)
* [cite](https://scholar.googleusercontent.com/scholar.bib?q=info:hfL9h0aBYbQJ:scholar.google.com/&output=citation&scisdr=CgVSaNk7EPjT2ELiVB8:AAGBfm0AAAAAYtPkTB-566EDTisQnXmFruUXZ7Mlsidp&scisig=AAGBfm0AAAAAYtPkTLYtAbVb8B13bMvtA4woyrmaRTNy&scisf=4&ct=citation&cd=-1&hl=zh-CN)