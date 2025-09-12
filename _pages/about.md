---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!-- 2020年在<a href="http://www.ues.pku.edu.cn/old/szdw/qbjs/w/311950.htm" target="_blank">`王仰麟教授`</a>与<a href="http://www.ues.pku.edu.cn/jszy/pj/pjgrjl/47d5081a72b1402693d0ef0eac835be3.htm" target="_blank">`彭建教授`</a>指导下于北京大学获得博士学位，期间曾前往美国两院院士<a href="https://search.asu.edu/profile/1227885" target="_blank">`Billie Turner教授`</a>课题组进行联合培养。现主要从事景观格局与社会-生态过程领域的研究，发表国内外>期刊论文50余篇，含1篇Nature旗下期刊论文。 -->


I am an assistant professor at <a href="https://www.cs.sjtu.edu.cn/" target="_blank">Computer Science and Engineering Department</a> in <a href="https://www.sjtu.edu.cn/" target="_blank">Shanghai Jiao Tong University (SJTU)</a>. I received the Master and Ph.D. degrees from Shanghai Jiao Tong University under the supervision of <a href="https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html" target="_blank">`Prof. Quan Chen`</a> and <a href="https://cs.sjtu.edu.cn/~guo-my/" target="_blank">`Prof. Minyi Guo`</a>. For now, I still work closely with <a href="https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html" target="_blank">`Prof. Quan Chen`</a> and <a href="https://raphael-hao.top/" target="_blank">`Assist Prof. Weihao Cui`</a>.

My previous research focused on:
- Task scheduling across various architectures
- Resource management in datacenters
- DNN inference system design

Currently, my research focus on: 
- Cloud computing and deep learning systems
- LLM inference and training systems
- Serverless architectures for diverse applications
- Advanced resource management in datacenters

**I am now looking for perspective Undergraduate Students and Master Students (Enrollment Date: 2026.09). If you are interested in above areas, we should talk.**

<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2019.09 – 2022.06*, Shanghai Jiao Tong University        `Doctor`
- *2016.09 – 2019.03*, Shanghai Jiao Tong University        `Master`
- *2012.09 – 2016.06*, Huazhong University of Science and Technology         `Bachelor`

<!-- <span class='anchor' id='-xsjz'></span>

# 💻 学术兼职

- 2025-至今，《生态学报》 `青年编委`
- 2024-至今，《Human and Ecological Risk Assessment》 `副主编`
- 2024-至今，中国生态学会青年工作委员会 `副秘书长` -->

<span class='anchor' id='-fblw'></span>

# 📝 Publications

### Preprint

- \* Denotes the `Corresponding author.`
- ^ Denotes the `Equal contribution.`
<!-- - Shulai Zhang, Ao Xu, Quan Chen, `Han Zhao`, Weihao Cui, Ningxin Zheng, Minyi Guo. Boosting Embodied AI Agents through Perception-Generation Disaggregation and Asynchronous Pipeline Execution. **(On Arxiv)**  -->
- Chuhao Xu, Zijun Li, Quan Chen, `Han Zhao`, Minyi Guo. LLM-Mesh: Enabling Elastic Sharing for Serverless LLM Inference. **(On Arxiv)** 
- Weihao Cui, Ji Zhang, `Han Zhao*`, Chao Liu, Wenhao Zhang, Jian Sha, Quan Chen, Bingsheng He, Minyi Guo. Xputimer: Anomaly diagnostics for divergent llm training in gpu clusters of thousand-plus scale. **(On Arxiv)** 
- Weihao Cui, Ziyi Xu, `Han Zhao`, Quan Chen, Zijun Li, Bingsheng He, Minyi Guo. Efficient Function-as-a-Service for Large Language Models with TIDAL. **(On Arxiv)** 
- Weihao Cui^, Yukang Chen^, `Han Zhao^`, Ziyi Xu, Quan Chen, Xusheng Chen, Yangjie Zhou, Shixuan Sun, Minyi Guo, M. Optimizing SLO-oriented LLM Serving with PD-Multiplexing. **(On Arxiv)**
- Chunyu Xue, Weihao Cui, `Han Zhao`, Quan Chen, Shulai Zhang, Pengyu Yang, Jing Yang, Shaobo Li, Minyi Guo. A codesign of scheduling and parallelization for large model training in heterogeneous clusters. **(On Arxiv)**

### Published

- Shulai Zhang, Ao Xu, Quan Chen, `Han Zhao`, Weihao Cui, Zhen Wang, Yan Li, Limin Xiao, Minyi Guo. Efficient Performance-Aware GPU Sharing with Compatibility and Isolation through Kernel Space Interception . **ATC2025 (CCF-A)** 
- `Han Zhao`, Weihao Cui, Quan Chen, Zijun Li, Zhenhua Han, Nan Wang, Yu Feng, Jieru Zhao, Chen Chen, Jingwen Leng, Minyi Guo. EDAS: Enabling Fast Data Loading for GPU Serverless Computing. **TACO2025 (CCF-A)** 
- Pengyu Yang, Weihao Cui, Chunyu Xue, `Han Zhao`, Chen Chen, Quan Chen, Jing Yang, Minyi Guo. Taming Flexible Job Packing in Deep Learning Training Clusters. **TACO2025 (CCF-A)** 
- Yifu He, `Han Zhao`, Quan Chen, Weihao Cui, Minyi Guo. ARACHNE: Optimizing distributed parallel applications with reduced inter-process communication. **TACO2025 (CCF-A)** 
- Shulai Zhang, Quan Chen, Weihao Cui, `Han Zhao`, Chunyu Xue, Zhen Zheng, Wei Lin, Minyi Guo. Improving GPU Sharing Performance through Adaptive Bubbleless Spatial-Temporal Sharing. **Eurosys2025 (CCF-A)** 
- Yu Feng, Weikai Lin, Zihan Liu, Jingwen Leng, Minyi Guo, `Han Zhao`, Xiaofeng Hou, Jieru Zhao, Yuhao Zhu. Potamoi: Accelerating neural rendering via a unified streaming architecture. **TACO2024 (CCF-A)**
- `Han Zhao^`, Junxiao Deng^, Weihao Cui, Quan Chen, Youtao Zhang, Deze Zeng, Minyi Guo. Adaptive Kernel Fusion for Improving the GPU Utilization while Ensuring QoS. **TC2024 (CCF-A)**
- `Han Zhao`, Junxiao Deng, Weihao Cui, Deze Zeng, Jing Yang, Minyi Guo. Exploiting all intra-SM parallelism to maximize the throughput while ensuring QoS. **Chinese Science Information Science 2024 (CCF-A)**
- Chuhao Xu, Yiyu Liu, Zijun Li, Quan Chen, `Han Zhao`, Deze Zeng, Qian Peng, Xueqi Wu, Haifeng Zhao, Senbo Fu, Minyi Guo. FaaSMem: Improving Memory Efficiency of Serverless Computing with Memory Pool Architecture. **In ASPLOS2024 (CCF-A)**
- Binghao Chen, `Han Zhao*`, Weihao Cui, Yifu He, Shulai Zhang, Quan Chen, Zijun Li, Minyi Guo. Maximizing the Utilization of GPUs Used by Cloud Gaming through Adaptive Co-location with Combo. **SoCC2023 (CCF-B)**
- `Han Zhao`, Weihao Cui, Quan Chen, Jingwen Leng, Deze Zeng, Minyi Guo. Improving Cluster Utilization Through Adaptive Resource Management for Deep Neural Network and CPU Jobs Colocation. **TC2023 (CCF-A)**
- `Han Zhao`, Weihao Cui, Quan Chen, Minyi Guo. ISPA: Exploiting Intra-SM Parallelism in GPUs via Fine-grained Resource Management. **TC2022 (CCF-A)**
- Weihao Cui, `Han Zhao`, Quan Chen, Hao Wei, Zirui Li, Deze Zeng, Chao Li, Minyi Guo. DVABatch: Diversity-aware Multi-Entry Multi-Exit Batching for Efficient Processing of DNN Services on GPUs. **ATC2022 (CCF-A)**
- `Han Zhao`, Weihao Cui, Quan Chen, Youtao Zhang, Yanchao Lu, Chao Li, Jingwen Leng, Minyi Guo. Tacker:Tensor-CUDA Core Kernel Fusion for Improving the GPU Utilization while Ensuring QoS. **HPCA2022 (CCF-A)**
- Weihao Cui, `Han Zhao`, Quan Chen, Ningxin Zheng, Jingwen Leng, Jieru Zhao, Zhuo Song, Tao Ma, Yong Yang, Chao Li, Minyi Guo. Enable Simultaneous DNN Services Based on Deterministic Operator Overlap and Precise Latency Prediction. **SC2021 (CCF-A)**
- `Han Zhao`, Weihao Cui, Quan Chen, Jieru Zhao, Jingwen Leng, Minyi Guo. Exploiting Intra-SM Parallelism in GPUs via Persistent and Elastic Blocks. **ICCD2021 (CCF-B)**
- Weihao Cui, Quan Chen, `Han Zhao`, Mengze Wei, Xiaoxin Tang, Minyi Guo. E2bird: Enhanced Elastic Batch for Improving Responsiveness and Throughput of Deep Learning Services. **TPDS2020 (CCF-A)**
- `Han Zhao`, Weihao Cui, Quan Chen, Jingwen Leng, Kai Yu, Deze Zeng, Chao Li, Minyi Guo. CODA: Improving Resource Utilization by Slimming and Co-locating DNN and CPU Jobs. **ICDCS2020 (CCF-B)**
- `Han Zhao`, Quan Chen, Yuxian Qiu, Ming Wu, Yao Shen, Jingwen Leng, Chao Li, Minyi Guo. Bandwidth and Locality Aware Task-stealing for Manycore Architectures with Bandwidth-Asymmetric Memory. **TACO2019 (CCF-A)**

<span class='anchor' id='-ryjx'></span>

# 🏅 Awards
- 2025 **CCF Distinguished Paper** `CCF杰出论文奖`
- 2025 **MSRA StarTrack Scholar** `微软铸星学者`
- 2023 **CCF Outstanding Doctoral Dissertation Award in Computer Architecture** `CCF体系结构优博`
- 2021 **SC2021 Best Reproducibility Advancement** `SC2021最佳实现提名奖`

<span class='anchor' id='-kyxm'></span>

# 🏛️ Projects

### National Project

- 2024-2026, **国家自然科学基金青年项目**，服务器无感知计算的加速器高效共享研究（`项目负责人`）
- 2025-2027, **国家重点研发计划**, 针对异构计算平台的资源实时隔离与高效调度系统（`实际项目实施`）
- 2024-2026, **国家重点研发计划**, 面向新一代国产超算系统的统一并行编程模型与并行编译（`子课题负责人`）
- 2023-2026, **国家重点研发计划**, 新型数据流异构处理器架构及计算系统（`子课题负责人`）

### Industrial Project

- 2025-2026, **CCF-蚂蚁绿色基金**, 最小化大模型推理成本：同构及异构模型极致合并部署降本研究（`项目负责人`）
- 2024-2025, **HW云联合实验室**, 大模型推理服务与微调任务的高效混部关键技术研究技术（`项目负责人`）
- 2023-2024, **HW委托研究项目**, 源码并行化检测与提示工具项目（`联合项目负责人`）
- 2023-2024, **HW委托研究项目**, 单节点到多节点并行应用源到源翻译工具项目（`联合项目负责人`）

<!-- - 2023-2025，**国家自然科学基金青年项目**，空间流动视角下水质净化服务惠益测度及其对景观格局演变的响应：以太湖流域为例（`主持`）
- 2023-2027，**科技部重点研发计划子课题**（2023YFF1304700），干旱区城市及其周边区域生态空间需水量精细化估算（`主持`）
- 2022-2023，**教育部地表过程与资源生态国家重点实验室开放课题**（2022-KF-03），太湖流域生态系统服务权衡分析及驱动识别：基于粮食-水-生态关联视角（`主持`）
- 2022-2023，**上海师范大学国家自然科学基金培育计划**（SK202219），太湖流域景观格局演变对水质净化服务的影响机制：基于空间流动视角（`主持`）
- 2022-2023，**上海高校青年教师培养资助计划项目**（ZZ202207005），课程思政改革要求下《地理科学导论》课堂教学设计（`主持`）
- 2023-2024，**上海高校市级重点课程**，地理科学导论（参与）
- 2019-2021，**国家自然科学基金国际（地区）合作与交流项目**（41911530080），陆-河交界面社会-经济-环境权衡管理（参与） -->

<span class='anchor' id='-cdkc'></span>

# 📚 Courses

- 2023.1 - Now, **Intelligent Computing Systems** `《智能计算系统》`
- 2023.1 - Now, **Parallel Computing and Parallel Algorithms** `《并行计算与并行算法》`

<!-- - 2023.1-至今，**景观与区域生态学**（3学分），本科生课程
- 2022.1-至今，**地理信息系统原理**（3学分），本科生课程
- 2021.9-至今，**地理科学导论**（3学分），本科生课程 -->

<span class='anchor' id='-xszd'></span>

# 🧑‍🎓 Students

### Non-Graduated
- `I am so glad to work with these outstanding students.💖💖`
- 2024级博士 邓俊骁
- 2024级硕士 徐奥，陈煜康
- 2025级博士 张翔
- 2025级硕士 王皓冬，张豪
- 2023级本科生 罗锦彬

### Graduated
- 2021级硕士 陈炳昊（英伟达）
- 2022级硕士 杨鹏宇（字节跳动）