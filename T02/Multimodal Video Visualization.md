# Multimodal Video Visualization（多模态视频可视分析）文献总结

> **选题**：Multimodal Video Visualization
> **参考论文**：*Anchorage: Visual Analysis of Satisfaction in Customer Service Videos Via Anchor Events*
> **文献数量**：5 篇，原文见同级 `reference/` 文件夹
> **状态**：写作中——提纲已列好，正文待补充

## 1. 领域概述

<!-- TODO：用 3-5 段说明这一领域研究什么、典型分析任务有哪些、面临哪些共同挑战 -->

要点提示：

- 研究对象：同时携带画面、语音/音频、文本（字幕、转写、日志）等多条信息通道的视频数据。
- 典型任务：时序总览与摘要、事件与异常定位、多模态一致性验证、模型解释与可信度、跨视频比较与排序。
- 常见挑战：特征稀疏（有价值的行为只占几秒）、情感语义模糊（同一表情在不同情境含义相反）、情境缺失（非结构化视频难以分段）、模态冲突（各通道结论可能矛盾）、证据需可回溯到原始视频。

## 2. 文献梳理

> 每篇按"论文信息 / 解决的问题 / 方法与可视化设计 / 主要贡献与创新点 / 评估与局限"五段来写。
> 考核明确要求：总结中必须涵盖每篇文献的**主要贡献和创新点**。

### 2.1 Anchorage: Visual Analysis of Satisfaction in Customer Service Videos Via Anchor Events

<!-- TODO：本方向的参考论文，建议写得最详细 -->

- **论文信息**：K. K. Wong, X. Wang, Y. Wang, J. He, R. Zhang, and H. Qu. IEEE TVCG, 30(7): 4008-4021, 2024.
- **解决的问题**：
- **方法与可视化设计**：
- **主要贡献与创新点**：
- **评估与局限**：

### 2.2 VisTellAR: Embedding Data Visualization to Short-Form Videos Using Mobile Augmented Reality

<!-- TODO -->

- **论文信息**：W. Tong, K. Shigyo, L.-P. Yuan, M. Fan, T.-C. Pong, H. Qu, and M. Xia. IEEE TVCG, 31(3): 1862-1874, 2025.
- **解决的问题**：
- **方法与可视化设计**：
- **主要贡献与创新点**：
- **评估与局限**：

### 2.3 AI-Based Multimodal Framework for Shot-Level Analysis of Documentary-Style Micro-Lecture Videos

<!-- TODO -->

- **论文信息**：J. Liang and G. Liu. In Proc. 4th Int. Conf. on Cloud Computing, Big Data Application and Software Engineering (CBASE), pp. 335-340, 2025.
- **解决的问题**：
- **方法与可视化设计**：
- **主要贡献与创新点**：
- **评估与局限**：

### 2.4 Video Visualization and Visual Analytics: A Task-Based and Application-Driven Investigation

<!-- TODO：这是一篇综述，可用来支撑第 1 节的领域概述与第 4 节的研究趋势 -->

- **论文信息**：W. Xia, G. Sun, T. Li, B. Chang, J. Tang, G. Zhang, and R. Liang. IEEE TCSVT, 34(11): 11316-11339, 2024.
- **解决的问题**：
- **方法与可视化设计**：
- **主要贡献与创新点**：
- **评估与局限**：

### 2.5 Predicting Content Similarity via Multimodal Modeling for Video-In-Video Advertising

<!-- TODO -->

- **论文信息**：X. Song, B. Xu, and Y.-G. Jiang. IEEE TCSVT, 31(2): 569-581, 2021.
- **解决的问题**：
- **方法与可视化设计**：
- **主要贡献与创新点**：
- **评估与局限**：

## 3. 横向对比

<!-- TODO：填完各篇后，用这张表把五篇串起来 -->

| 文献 | 分析对象 | 多模态通道 | 可视化形式 | 交互方式 | 评估方式 | 主要贡献定位 |
| --- | --- | --- | --- | --- | --- | --- |
| Anchorage (2024) | | | | | | |
| VisTellAR (2025) | | | | | | |
| 微课多模态框架 (2025) | | | | | | |
| 视频可视分析综述 (2024) | | | | | | |
| 视频内嵌广告匹配 (2021) | | | | | | |

## 4. 小结与研究趋势

<!-- TODO：总结共性规律（如从单模态帧级特征走向多模态事件级语义、可视化成为模型可信度的基础设施、评估与数据仍是短板等） -->

## 5. 参考文献

1. K. K. Wong, X. Wang, Y. Wang, J. He, R. Zhang, and H. Qu. Anchorage: Visual Analysis of Satisfaction in Customer Service Videos Via Anchor Events. *IEEE TVCG*, 30(7): 4008-4021, 2024.
2. W. Tong, K. Shigyo, L.-P. Yuan, M. Fan, T.-C. Pong, H. Qu, and M. Xia. VisTellAR: Embedding Data Visualization to Short-Form Videos Using Mobile Augmented Reality. *IEEE TVCG*, 31(3): 1862-1874, 2025.
3. J. Liang and G. Liu. AI-Based Multimodal Framework for Shot-Level Analysis of Documentary-Style Micro-Lecture Videos. In *Proc. 4th Int. Conf. on Cloud Computing, Big Data Application and Software Engineering (CBASE)*, pp. 335-340, 2025.
4. W. Xia, G. Sun, T. Li, B. Chang, J. Tang, G. Zhang, and R. Liang. Video Visualization and Visual Analytics: A Task-Based and Application-Driven Investigation. *IEEE TCSVT*, 34(11): 11316-11339, 2024.
5. X. Song, B. Xu, and Y.-G. Jiang. Predicting Content Similarity via Multimodal Modeling for Video-In-Video Advertising. *IEEE TCSVT*, 31(2): 569-581, 2021.

## 写作提示（正文写完后请删除本节）

- 文件名即所选研究领域，请勿改名；参考文献原文统一放在同级 `reference/` 中。
- 每篇至少写清"解决了什么问题、用了什么方法与可视化设计、贡献与创新点是什么、验证到什么程度、有什么局限"。
- 若某篇只是相邻领域参考、不计入本方向的五篇，请在该条后标注"（相邻领域）"。
