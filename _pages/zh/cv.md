---
layout: archive
title: "个人简历"
permalink: /zh/cv/
lang: zh
locale: zh-CN
translation_key: cv
author_profile: true
excerpt: "盖乐的教育经历、研究工作、实习经历、论文与学术活动。"
---

## 盖乐（Le Gai）

清华大学网络科学与网络空间研究院 · 网络空间安全博士生

**邮箱：**[gl25@mails.tsinghua.edu.cn](mailto:gl25@mails.tsinghua.edu.cn)<br>
**英文完整简历：**[English CV]({{ '/cv/' | relative_url }})

## 研究兴趣

- 智能体与多智能体系统安全：协议风险、攻击归因与工作流恢复。
- 面向智能体系统的网络感知调度、准入控制与服务质量保障。
- 互联网测量、IPv6 安全、源地址验证与互联网范围服务发现。
- 大语言模型蒸馏与基于机器学习的恶意软件检测。

## 教育经历

**清华大学**，北京<br>
网络科学与网络空间研究院，网络空间安全博士，**2025–至今**，预计 **2030** 年毕业。GPA：**4.0/4.0**。

**西安电子科技大学**，西安<br>
网络与信息安全学院，网络工程学士，**2021–2025**。专业排名：**2/326**。

## 科研与实习经历

### 蚂蚁集团 · 北京

**安全部门智能体安全团队，科研实习生**<br>
**2026.06–至今**，计划至 2026.12。

- 围绕业务智能体系统开展多智能体协议与任务执行安全研究。
- 分析 A2A、BCS 等通信协议的安全机制和攻击面，设计协议层防护模块。
- 在业务场景验证任务执行安全机制，参与多智能体系统安全论文研究。

### 绿盟科技 · 北京

**网络资产评估方向实习生**<br>
**2024.06–2024.09**

- 研究 IPv4/IPv6 开放端口扫描、服务预测与扫描结果间的特征迁移。
- 分析 IEEE 地址分配、MAC 厂商信息、自治系统类别与协议栈分布。

### 绿盟科技 · 西安

**终端安全技术团队，安全测试实习生**<br>
**2023.06–2023.08**

- 参与等级保护 2.0 相关系统测试。
- 使用 Python、Django 与公司数据库开发自动化合规检查应用。
- 获得优秀实习生评价及校招录用机会。

### 西安电子科技大学

**恶意软件检测方向本科科研**<br>
**2022.09–2025.07**

在马建峰老师团队、冯鹏斌老师指导下，结合程序分析与机器学习研究恶意软件检测和网络攻击识别，参与 DawnGNN 论文及恶意软件检测、APK 混淆分析相关专利申请。

## 已发表或接收论文

1. **Le Gai**, Zedong Jia, Lin He, et al. **TED: Abusing Tunnel Hosts and IPv6 Extension Headers for Pulsing DoS Attacks.** *USENIX Security 2026.*
2. Daguo Cheng, Zedong Jia, Ying Liu, Lin He, **Le Gai**, et al. **Divide, Predict, Conquer: Adaptive Internet-wide Service Discovery with Limited Seeds.** *IEEE INFOCOM 2026.*
3. **Le Gai**, Lin He, Chentian Wei, et al. **SpecNet-Agent: Network-Aware Speculation Control for QoS in Agentic Generative AI Services.** *IWQoS 2026, NetGenAI Workshop.* [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11661032/)
4. Pengbin Feng, **Le Gai**, et al. **DawnGNN: Documentation Augmented Windows Malware Detection using Graph Neural Network.** *Computers & Security*, 2024. [DOI](https://doi.org/10.1016/j.cose.2024.103788)

## 在审稿件

以下状态沿用英文简历。

1. **Le Gai**, Chenxi Zhao, Ying Liu, Zhongmou Liu, et al. **CANTER: Coordinated Admission and Network Transmission by Execution Role for Timely Web Agents.** 在审，*The Web Conference (WWW) 2027*。
2. Xiuming Liu, **Le Gai**, Zhiyuan Chang, et al. **Agent-Canary-Mas: End-to-End Evaluation of Protocol Risk in Long-Horizon Multi-Agent Systems.** 在审，*USENIX Security 2027*。[arXiv](https://arxiv.org/abs/2610.15529)
3. Xuanfeng Yang, **Le Gai**, Jiaming Wang, Xuan Zhang. **Beyond Policy Discrepancy: Capability-Aware Multi-Teacher On-Policy Distillation.** 在审，*ICLR 2027*。[arXiv](https://arxiv.org/abs/2610.26950)
4. Zhongmou Liu, **Le Gai**, et al. **Woodpecker: Provenance-Guided Local Repair for Compromised Multi-Agent LLM Workflows.** 在审，*DAC 2027*。
5. **Le Gai**, Lin He, Jiaxing Guo, et al. **Peering into the Blind Spot: Measuring Source Address Validation with Internet Tunnels.** 在审，*IEEE Transactions on Networking*。
6. Daguo Cheng, **Le Gai**, Lin He, Ying Liu, et al. **Target-Aware Adaptive Scanning and Security Applications for Internet-Scale Open Port Discovery.** 在审，*IEEE INFOCOM 2027*。

## 研究项目概览

### 面向智能体服务的网络感知调度与服务质量保障

**SpecNet-Agent 与 CANTER。** SpecNet-Agent 结合工作流依赖和拥塞反馈，调节检索宽度、智能体并行度与推测预算。CANTER 在原生工具调用循环中协调请求准入与执行角色感知的链路调度，研究受限网络资源下的及时完成与结果质量。

### 多智能体协议风险评估与攻击归因

**Agent-Canary-Mas。** 跟踪协议层攻击在长时序多智能体任务中的传播与下游影响，通过跨智能体证据连接局部利用行为与任务结果，评估问题智能体的定位能力。

### 受攻击智能体工作流的局部恢复

**Woodpecker。** 利用语义来源信息识别告警后的受污染计算，隔离受影响的工作流片段并选择性重放，研究恢复效果与额外计算开销之间的权衡。

### 能力感知的多教师模型蒸馏

**CA-MOPD。** 融合强化学习专家模型初始化共享学生模型，再结合教师与学生的能力差距、学生能力退化情况，调整各领域的蒸馏强度。

### IP 隧道与 IPv6 扩展头安全

**TED。** 分析 IP 隧道转发和 IPv6 扩展头处理共同引发的网络层脉冲式拒绝服务风险，通过互联网范围测量与实验研究其影响及缓解措施。

### 利用互联网隧道测量源地址验证部署

利用开放互联网隧道评估 IPv4/IPv6 网络的入向与出向源地址验证，无需在目标网络内部部署观测点，并分析部署情况与地址空间、自治系统类型、地理位置的关系。

### 目标感知的开放端口发现

**PortSeer。** 通过活跃主机自适应采样和多粒度双关联图预测常见端口，对剩余端口实施分层扫描，提高端口发现效率并减少探测开销。

### 有限种子条件下的互联网服务发现

**SPADE。** 结合多层自适应采样与分治预测，提取服务部署特征，在有限先验种子条件下开展互联网范围的服务预测与发现。

### IPv6 主动发现与地理定位

与阿里巴巴安全 AGI 实验室开展研究，结合主动探测、地址模式学习、被动观测与机器学习，探索 IPv6 发现、定位及大模型辅助安全归因。

## 本科研究项目

- **基于学习的恶意软件检测：**结合程序分析与机器学习开展恶意软件识别，形成 DawnGNN 及相关专利申请。
- **基于 API 知识图谱的勒索软件检测：**中央网信办网络安全学院学生创新资助计划，2024.05–2025.05；使用大模型构建 API 行为知识图谱，结合 RotatE 嵌入与分类模型研究检测及泛化能力。
- **RISC-V 密码运算加速：**2023.06–2024.11；开展国密算法实现、指令优化与专用运算单元设计，获得第八届全国密码技术竞赛全国一等奖，并在 CCF ChinaSoft 2024 报告。
- **联邦学习车机语音识别：**国家级大学生创新项目，2023.01–2023.12；在张俊伟老师指导下负责项目，优秀结题，并参与专利 CN116564339A。

## 专利申请

1. Pengbin Feng, **Le Gai**, Ning Xi. **面向工业互联网的语义增强型恶意软件检测方法**。申请号：CN202311455787.6。
2. Pengbin Feng, Xuan Lv, **Le Gai**, et al. **基于图注意力网络与 NLP 词嵌入模型的 APK 混淆机制检测方法**。申请号：CN202310897727.3。
3. **Le Gai**, Yanbo Sun, Junwei Zhang. **基于联邦学习的安全高效车机语音识别方法及系统**。公开号：CN116564339A。

## 学术报告

报告内容与会议照片见[学术报告与交流]({{ '/zh/talks/' | relative_url }})，包括 ChinaSoft 2024、IWQoS NetGenAI 2026、USENIX Security 2026、IETF 126 与 CNIRC 2026。

## 荣誉与奖励

**奖学金与综合荣誉：**国家奖学金、清华大学综合优秀一等奖学金、感恩中国近现代科学家奖学金、联想奖学金、奇安信奖学金、国家励志奖学金、优秀学生干部、优秀共青团员。

**竞赛：**全国大学生数学建模竞赛全国一等奖；第八届全国密码技术竞赛全国一等奖；美国大学生数学建模竞赛国际二等奖；第三届 IPv6 技术应用创新大赛全国二等奖；长安杯大学生电子数据取证竞赛全国三等奖；西安交通大学—绿盟联合 CTF 三等奖；星火杯特等奖；西安电子科技大学 ACM 程序设计竞赛二等奖。

## 学生工作与社区

- 清华大学礼射协会骨干，2025.09–2026.06。
- 清华大学网络科学与网络空间研究院团委骨干，2025.09–2026.06。
- 西安电子科技大学跑步协会会长，2022.09–2023.06。
- 西安电子科技大学青年志愿者协会环保部负责人，2022.09–2023.06。
- 原 XDSEC 成员，2022 年加入，主要参与 Pwn 与二进制安全方向。

## 技术能力与写作

熟悉 Python、Django、数据库集成与自动化测试；具备 IPv4/IPv6 测量、服务发现、协议安全及恶意软件分析经验；研究涉及图神经网络、知识图谱、RotatE、模型蒸馏、联邦学习、RISC-V 与密码算法加速。

在 GitHub、CSDN 与个人网站发表技术文章和安全题解 **100 余篇**，各平台累计阅读量 **150 万余次**、关注者 **2,000 余人**。
