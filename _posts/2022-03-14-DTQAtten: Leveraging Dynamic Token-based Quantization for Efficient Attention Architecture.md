---
thumbnail-img: assets/img/posts/dtqatten.jpg
---

Tao Yang, Dongyue Li, **Zhuoran Song**, Yilong Zhao, Fangxin Liu, Zongwu Wang, Zhezhi He and Li Jiang.

Models based on the attention mechanism, i.e. trans- formers, have shown extraordinary performance in Natural Lan- guage Processing (NLP) tasks. However, their memory footprint, inference latency, and power consumption are still prohibitive for efficient inference at edge devices, even at data centers. To tackle this issue, we present an algorithm-architecture co-design with dynamic and mixed-precision quantization, DTQAtten. We present empirically that the tolerance to the noise varies from token to token in attention-based NLP models. This finding leads us to quantize different tokens with mixed levels of bits. Thus, we design a compression framework that (i) dynamically quantizes tokens while they are forwarded in the models and (ii) jointly determines the ratio of each precision. Moreover, due to the dynamic mixed-precision tokens caused by our frame- work, previous matrix-multiplication accelerators (e.g. systolic array) cannot effectively exploit the benefit of the compressed attention computation. We thus design our accelerator with the variable-speed systolic array (VSSA) and propose an effective optimization strategy to alleviate the pipeline-stall problem in VSSA without hardware overhead. We conduct experiments with existing attention-based NLP models, including BERT and GPT- 2 on various language tasks. Our results show that DTQAtten outperforms the previous neural network accelerator Eyeriss by 13.12× in terms of speedup and 3.8× in terms of energy-saving. Compared with the state-of-the-art attention accelerator SpAtten, our DTQAtten achieves at least 2.65× speedup and 3.38× energy efficiency improvement.

![dtqatten](/assets/img/posts/dtqatten.jpg)

* Accepted by ACM/IEEE Design Automation & Test in Europe Conference and Exhibition (DATE 2022, CCF-B)
* [paper]()
* [cite]()