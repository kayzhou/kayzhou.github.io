---
title: WWW 2024 | 时间序列（Time Series）论文总结
date: 2024-04-10 07:38:22
tags:
- 科研
- 时间序列预测
---

---
created: 2024-04-10T07:30:50 (UTC +08:00)
tags: [数据挖掘,LLM（大型语言模型）,人工智能]
source: https://zhuanlan.zhihu.com/p/681773037
author: 

---

# WWW 2024 | 时间序列（Time Series）论文总结

> ## Excerpt
>
> WWW 2024 | 时间序列（Time Series）和时空数据（Spatial-Temporal）论文总结 WWW 2024已经放榜，本次会议共提交了2008篇文章，research tracks共录用约400多篇论文，录用率为20.2%。本次会议将于2024年5月13日-17…

---

## 时间序列（Time Series）

### 1\. UniTime: A Language-Empowered Unified Model for Cross-Domain Time Series Forecasting

**作者**：Xu Liu, Junfeng Hu, Yuan Li, Shizhe Diao, **Yuxuan Liang, Bryan Hooi, Roger Zimmermann**

**链接**：[https://arxiv.org/abs/2310.09751](https://arxiv.org/abs/2310.09751)

**关键词**：多变量时序预测，大模型，跨域

**摘要**：多元时间序列预测在当代网络技术中发挥着关键作用。 与特定时间序列应用领域创建专用模型的传统方法相比，本研究提倡超越领域边界的统一模型范式。 然而，学习有效的跨域模型面临以下挑战。 首先，各个领域在数据特征（例如变量数量）方面表现出差异，这给现有模型带来了障碍，这些模型对这些因素施加了不灵活的约束。 其次，该模型在区分不同领域的数据时可能会遇到困难，导致评估表现不佳。 第三，时间序列域的不同收敛速度也会导致经验性能受损。 为了解决这些问题，本文提出 UniTime 来进行有效的跨域时间序列学习。 具体来说，UniTime可以灵活地适应具有不同特征的数据。 它还使用域指令和语言 TS 转换器来提供识别信息并调整两种模式。 此外，UniTime 采用掩蔽来缓解域收敛速度不平衡问题。 广泛的实验证明了 UniTime 在提升最先进的预测性能和零样本可迁移性方面的有效性。

![](https://pic4.zhimg.com/v2-fe4e39e72cae81f11637126af07dd537_b.jpg)

![](https://pic4.zhimg.com/v2-7057ce863d5b6cda77769a3e7c713a93_b.jpg)

### 2\. Dynamic Multi-Network Mining of Tensor Time Series

**作者**：Kohei Obata, Koki Kawabata, Yasuko Matsubara, Yasushi Sakurai

**关键词**：时序挖掘，动态多重网络

### 3\. E2USD: Efficient-yet-effective Unsupervised State Detection for Multivariate Time Series

**作者**：Zhichen Lai, Huan Li, Dalin Zhang, Yan Zhao, Weizhu Qian, **Christian S. Jensen**

**代码**：[https://github.com/AI4CTS/EtoUsd/](https://github.com/AI4CTS/EtoUsd/)

**关键词**：无监督，状态检测，多元时序

### 4\. Revisiting VAE for Unsupervised Time Series Anomaly Detection: A Frequency Perspective

**作者**：Zexin Wang, Changhua Pei, Minghua Ma, Xin Wang, Zhihan Li, Dan Pei, Saravan Rajmohan, Dongmei Zhang, Qingwei Lin, Haiming Zhang, Jianhui Li, Gaogang Xie

**链接**：[https://arxiv.org/abs/2402.02820](https://arxiv.org/abs/2402.02820)

**关键词**：异常检测，VAE，频域

**摘要**：时间序列异常检测（AD）对于网络系统起着至关重要的作用。 各种网络系统依靠时间序列数据来实时监控和识别异常情况，以及启动诊断和补救程序。 变分自编码器（VAE）由于其卓越的去噪能力，在近几十年来越来越受欢迎，这对于异常检测非常有用。 然而，本文研究表明，基于 VAE 的方法在同时捕获长周期异质模式和详细的短周期趋势方面存在挑战。 为了应对这些挑战，本文提出了频率增强条件变分自编码器（FCVAE），这是一种用于单变量时间序列的新型无监督 AD 方法。 为了确保准确的 AD，FCVAE采用创新方法将全局和局部频率特征同时集成到条件变分自编码器（CVAE）的条件中，以显著提高重建正常数据的准确性。 结合精心设计的“目标注意力”机制，该方法允许模型从频域中挑选最有用的信息，以更好地构建短期趋势。 FCVAE 已在公共数据集和大型云系统上进行了评估，结果表明它优于最先进的方法。 这证实了该方法在解决当前基于 VAE 的异常检测模型的局限性方面的实际适用性。

![](https://pic3.zhimg.com/v2-c04cbb5e63f197597007175d57a919b6_b.jpg)

FACVAE

### 5\. Breaking the Time-Frequency Granularity Discrepancy in Time-Series Anomaly Detection

**作者**：Youngeun Nam, Susik Yoon, Yooju Shin, Minyoung Bae, Hwanjun Song, Jae-Gil Lee, Byung Suk Lee

**关键词**：异常检测，时频转换

![](https://pic3.zhimg.com/v2-d5be88a624dbd36604454c42fbc50616_b.jpg)

DualTF

## 时空数据（Spatial-Temporal）

### 1\. Exploiting Spatial-Temporal Data in Knowledge Graphs for Enhanced Prediction

**作者**：Ruiyi Yang, Flora Salim, Hao Xue

**关键词**：时空预测，知识图谱（增强）

### 2\. Unveiling Delay Effects in Traffic Forecasting: A Perspective from Spatial-Temporal Delay Differential Equations

**作者**：Qingqinglong, Zheng Fang, Chen Fang, Chong You Chen, Pengfei Wang, Yuanchun Zhou

**链接**：[https://arxiv.org/abs/2402.01231](https://arxiv.org/abs/2402.01231)

**关键词**：交通预测，延迟微分方程

**摘要**：交通流预测是交通规划和管理的基础研究问题，是时空预测的典范和典型。 近年来，图神经网络（GNN）和循环神经网络（RNN）在捕获时空相关性以进行交通流预测方面取得了巨大成功。 然而，两个不可忽视的问题尚未得到很好的解决：1）GNN 中的消息传递是即时的，而实际上相邻节点之间的空间消息交互可能会延迟。 一个节点的流量变化需要几分钟（即时间延迟）才能影响其连接的邻居。 2）交通状况不断变化。 交通流预测的预测频率可能根据具体场景要求而变化。 大多数现有的离散模型需要对每个预测范围进行重新训练，限制了它们的适用性。 为了解决上述问题，本文提出了一种神经时空延迟微分方程模型，即 STDDE。 它将延迟效应和连续性纳入统一的延迟微分方程框架中，该框架明确地模拟了空间信息传播中的时间延迟。 此外，还提供了理论证明来证明其稳定性。 然后设计了一个可学习的流量图时延估计器，它利用隐藏状态的连续性来实现梯度后向过程。 最后，提出了一个连续输出模块，能够准确预测各种频率的交通流量，这为不同场景提供了更大的灵活性和适应性。 大量的实验表明了所提出的 STDDE 的优越性以及具有竞争力的计算效率。

![](https://pic4.zhimg.com/v2-748da0ea33302e8dd99e1058d2641833_b.jpg)

STDDE

### 3\. UrbanCLIP: Learning Text-enhanced Urban Region Profiling with Contrastive Language-Image Pretraining from the Web

**作者**：Yibo Yan, Haomin Wen, Siru Zhong, Wei Chen, Haodong Chen, Qingsong Wen, **Roger Zimmermann, Yuxuan Liang**

**链接**：[https://arxiv.org/abs/2310.18340](https://arxiv.org/abs/2310.18340)

**关键词**：对比学习，多模态，CLIP，LLM

**摘要**：根据网络数据进行城市区域分析对于城市规划和可持续发展至关重要。 可以看到LLM在各个领域的上升趋势，特别是处理多模态数据研究，例如视觉语言学习，其中文本模态作为图像的补充信息。 由于文本模态从未被引入城市区域剖析的模态组合中，因此本文旨在回答两个基本问题：i）文本模态能否增强城市区域剖析？ ii) 如果是的话，以什么方式以及涉及哪些方面？ 为了回答这些问题，利用大型语言模型（LLM）的力量，引入了第一个 LLM 增强框架，将文本模态知识整合到城市意象分析中，名为 LLM 增强型城市区域分析与对比语言图像 预训练（UrbanCLIP）。 具体来说，它首先通过开源图像到文本的LLM为每个卫星图像生成详细的文本描述。 然后，该模型在图像-文本对上进行训练，将自然语言监督与对比损失和语言建模损失无缝地统一到城市视觉表示学习中。 对中国四个主要城市的三个城市指标的预测结果证明了其优越的性能，与最先进的方法相比，R^2 平均提高了 6.1%。

![](https://pic4.zhimg.com/v2-4af43afe23773bc0785125b3787407e3_b.jpg)

UrbanCLIP

### 4\. COLA: Cross-city Mobility Transformer for Human Trajectory Simulation

**作者**：Yu Wang, Tongya Zheng, Yuxuan Liang, Shunyu Liu, Mingli Song

**关键词**：迁移学习，人类轨迹模拟

![](https://pic3.zhimg.com/v2-07d32ad594969539dcabee96093036ca_b.jpg)

COLA

### 5\. More Than Routing: Joint GPS and Route Modeling for Refine Trajectory Representation Learning

**作者**：Zhipeng Ma, Zheyan Tu, Xinhai Chen, Yan Zhang, Deguo Xia, Guyue Zhou, Yilun Chen, **Yu Zheng**, Jiangtao Gong

**关键词**：轨迹表示学习

### 6\. Decentralized Collaborative Learning with Adaptive Reference Data for On-Device POI Recommendation

**作者**：Ruiqi Zheng, Liang Qu, Tong Chen, Lizhen Cui, Yuhui Shi, Hongzhi Yin

**关键词**：POI推荐，协作学习，去中心化

### 7\. Physical Trajectory Inference Attack and Defense in Decentralized POI Recommendation

**作者**：Jing Long, Tong Chen, Guanhua Ye, **Kai Zheng**, Nguyen Quoc Viet Hung, Hongzhi Yin

**链接**：[https://arxiv.org/abs/2401.14583](https://arxiv.org/abs/2401.14583)

**关键词**：POI推荐，协作学习，去中心化，隐私保护，差分隐私

**摘要**：作为基于位置的社交网络（LBSN）中不可或缺的个性化服务，兴趣点（POI）推荐旨在帮助个人发现有吸引力的地方。 然而，精准推荐能力依赖于强大的服务器收集海量的用户历史签到数据，存在极大的隐私泄露风险。 尽管一些用于 POI 推荐的协作学习 (CL) 框架增强了推荐弹性并允许用户将个人数据保留在设备上，但他们仍然共享个人知识以提高推荐性能，从而为潜在攻击者留下了漏洞。 鉴于此，设计了一种新的物理轨迹推断攻击（PTIA）来暴露用户的历史轨迹。 具体来说，对于每个用户，通过分析目标 POI 及其相关 POI 的聚合信息来识别交互的 POI 集。 评估了 PTIA 在两个现实世界数据集上跨两种类型的去中心化 CL 框架进行 POI 推荐的有效性。 实证结果表明，PTIA 对用户的历史轨迹构成了重大威胁。 此外，本地差分隐私（LDP）作为 CL 框架的传统隐私保护方法，也被证明对 PTIA 无效。 鉴于此，提出了一种基于对抗性博弈的针对 PTIA 的新型防御机制（AGD），以消除敏感 POI 及其相关 POI 中的信息。 经过大量的实验，AGD被证明是精确和实用的，对推荐性能的影响最小。

![](https://pic4.zhimg.com/v2-c313cbc2061c898518cbae288a90a59b_b.jpg)

PTIA

### 8\. MMPOI: A Multi-Modal Content-Aware Framework for POI Recommendations

**作者**：Yang Xu, **Gao Cong**, Lei Zhu, Lizhen Cui

**关键词**：POI推荐，多模态

**论文**：Negative Sampling in Next-POI Recommendations: Observation, Approach, and Evaluation

**作者**：Hong-Kyun Bae, Yebeen Kim, Hyunjoon Kim, Sang-Wook Kim

**关键词**：下一个POI推荐，负采样

## 相关链接

WWW2024 accepted：[https://www2024.thewebconf.org/accepted/research-tracks/](https://www2024.thewebconf.org/accepted/research-tracks/)

[ICLR 2024 | 时空数据(Spatial-Temporal)论文汇总](https://zhuanlan.zhihu.com/p/680045138)

[ICLR 2024 时间序列（Time Series）论文总结](https://zhuanlan.zhihu.com/p/678332686)

[SIGIR 2023 时空数据论文总结](https://zhuanlan.zhihu.com/p/664577452)

[KDD 2023时空数据相关论文](https://zhuanlan.zhihu.com/p/650189765)