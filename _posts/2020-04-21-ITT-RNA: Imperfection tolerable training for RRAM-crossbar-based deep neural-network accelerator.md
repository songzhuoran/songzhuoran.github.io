---
thumbnail-img: assets/img/posts/itt-rna.jpg
---
**Zhuoran Song**, Lerong Chen, Tianjian Li, Naifeng Jing, Xiaoyao Liang, Yanan Sun and Li Jiang.

Deep neural networks (DNNs) have gained a strong momentum among various applications. The enormous matrix-multiplication exhibited in the above DNNs is computation and memory intensive. Resistive Random-Access Memory crossbar(RRAM-crossbar) consisting of memristor cells can naturally carry out the matrix-vector multiplication. RRAM-crossbar based accelerator therefore has two orders of magnitude of higher energy-efficiency than conventional accelerators. The imperfect fabrication process of RRAM-crossbars, however, causes various defects and process variations. These fabrication imperfections not only result in significant yield loss but also degrade the accuracy of DNNs executed on the RRAM-crossbars. 

In this paper, we first propose an accelerator-friendly neural-network training method, by leveraging the inherent self-healing capability of the neural network, to prevent the large-weight synapses from being mapped to the imperfect memristors. 
Next, we propose a dynamic adjustment mechanism to extend the above method for deep neural networks, such as multi-layer perceptrons (MLPs), wherein the imperfect-memristor induced errors can accumulate and magnify through multiple layers. Such off-device training method is a pure software solution, and it is unable to provide enough accuracy for convolutional neural networks (CNNs). Several works propose error-tolerable hardware design by allowing the retraining of CNNs on the RRAM-crossbar. Although this hardware-based on-device training method is effective, the frequent write operation on RRAM-crossbar hurt the endurance of RRAM-crossbars. Consequently, we propose a software and hardware co-design methodology to effectively preserve the classification accuracy of CNN with few on-device training iterations. Experimental results show that the proposed method can guarantee < 1.1% loss of accuracy for resistance variations in MLP and CNN. Moreover, the proposed method can guarantee < 1% loss of accuracy even when stuck-at-faults (SAF) rate =20%.

![itt-rna](/assets/img/posts/itt-rna.jpg)

* Accepted by IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD 2020, CCF-A)
* [[paper]](https://ieeexplore.ieee.org/abstract/document/9075156/)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:ztgIT6nm2lgJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KL2jIU:AAGBfm0AAAAAYjPwlIWneOjtBn8yY_JQvekDhpH8T90K&scisig=AAGBfm0AAAAAYjPwlNBIlYvN5_xOCkEuG9V1ZFE4-Gbz&scisf=4&ct=citation&cd=-1&hl=zh-CN)