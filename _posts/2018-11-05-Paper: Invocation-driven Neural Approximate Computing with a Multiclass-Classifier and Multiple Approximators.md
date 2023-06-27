---
thumbnail-img: assets/img/posts/approximate.jpg
---
Neural approximate computing gains enormous energy-efficiency at the cost of tolerable quality-loss. A neural approximator can map the input data to output while a classifier determines whether the input data are safe to approximate with quality guarantee. However, existing works cannot maximize the invocation of the approximator, resulting in limited speedup and energy saving. By exploring the mapping space of those target functions, in this paper, we observe a nonuniform distribution of the approximation error incurred by the same approximator. We thus propose a novel approximate computing architecture with a Multiclass-Classifier and Multiple Approximators (MCMA). These approximators have identica network topologies, and thus can share the same hardware resource in an neural processing unit(NPU) clip. In the runtime, MCMA can swap in the invoked approximator by merely shipping the synapse weights from the on-chip memory to the buffers near MAC within a cycle. We also propose efficient co-training methods for such MCMA architec- ture. Experimental results show a more substantial invocation of MCMA as well as the gain of energy-efficiency.


Authors: Haiyue Song, Li Jiang, Chengwen Xu, **Zhuoran Song**, Naifeng Jing, Xiaoyao Liang and Qiang Xu.


![approximate](/assets/img/posts/approximate.jpg)

* Accepted by ACM/IEEE International Conference on Computer-Aided Design (ICCAD 2018, CCF-B).
* [[paper]](https://dl.acm.org/doi/abs/10.1145/3240765.3240819)
* [[cite]](https://scholar.googleusercontent.com/scholar.bib?q=info:epvgja-q7sIJ:scholar.google.com/&output=citation&scisdr=CgVK0WDnEPjT2KL3Z_U:AAGBfm0AAAAAYjPxf_XHLLmwO6JQvPcH2M2oNBADfT1A&scisig=AAGBfm0AAAAAYjPxf2nE3KySXiunXlS7J88u6lxKj3Ck&scisf=4&ct=citation&cd=-1&hl=zh-CN)