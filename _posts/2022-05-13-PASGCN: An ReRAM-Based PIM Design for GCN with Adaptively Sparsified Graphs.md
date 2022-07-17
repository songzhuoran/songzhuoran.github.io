---
thumbnail-img: assets/img/posts/pasgcn.jpg
---
Graph Convolutional Network (GCN) is a promising but computing-and memory-intensive learning model. Processing-in-memory (PIM) architecture based on the ReRAM crossbar is a natural fit for GCN inference. It can reduce the data movements and compute the vector-matrix multiplication (VMM) in analog. However, it requires an unbearable crossbar cost to leverage the massive parallelism exhibited in GCNs. First, this paper explores the design space for GCN inference on ReRAM crossbars and presents the first PIM-based GCN accelerator named PIMGCN, PIMGCN employs dense data mapping and a search-execute architecture to take full advantage of the intra-vertex parallelisms with acceptable crossbars cost. Two scheduling strategies for PIMGCN to maximize the inter-vertex parallelisms and optimize the pipeline are proposed. The optimal scheduling is reduced to a maximum independent set problem, which is solved by a novel node-grouping algorithm. Second, this paper explores the task-irrelevant information in the graphs and proposes an adaptively sparsified GCN network targeted for PIMGCN, which is named as ASparGCN. ASparGCN exploits an MLP-based edge predictor to get edge selection strategies for each GCN layer separately and adaptively in the training stage, and only inferences with the selected edges in the test stage. We design two regularization terms to guide the selection strategies to achieve architecture-friendly sparse graphs for PIMGCN. The overall algorithm-architecture co-design is named as PASGCN. Compared to the state-of-the-art software framework running on Intel Xeon CPU and NVIDIA RTX8000 GPU, PASGCN achieves an average of 16455× and 110.7× speedup, 8.0E+06× and 6.67E+03× energy reduction, respectively. Compared with ASIC accelerator HyGCN HyGCN, PASGCN achieves 326.31× speedup and 124.8× energy reduction.

Authors: Tao Yang, Dongyue Li, Fei Ma, **Zhuoran Song**, Yilong Zhao, Jiaxi Zhang, Fangxin Liu and Li Jiang.

![pasgcn](/assets/img/posts/pasgcn.jpg)

* Accepted by IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD 2022, CCF-A)
* [paper]()
* [cite]()