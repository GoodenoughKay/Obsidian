---
title: "复试备考材料——上海中医药大学中医药人工智能学院（改写版）"
date: 2026-04-09
tags:
  - 考研复试
  - 上中医药
  - 中医药AI
  - 面试叙事
  - 自我介绍
category: "考研备战"
---

# 复试备考材料——上海中医药大学中医药人工智能学院

> ⚠️ 本版本专门针对**上海中医药大学中医药人工智能学院**改写。  
> 原材料（上科大材料与化工版）中所有"相场模型""材料界面""ML势函数"的连接叙事**在本场合全部作废**，不要使用。  
> 该学院核心研究方向：多模态大模型、中医知识图谱、四诊客观化、智能临床决策支持。

---

## 一、中文自我介绍

> 您好，我叫位凯瑞，本科就读于上海应用技术大学大数据管理与应用专业，GPA 3.62，专业排名第六。
>
> 我有两段主要项目经历。
>
> 第一段是科研项目，研究基于深度学习求解双曲守恒律方程。经典的 PINN 在有激波的方程中会结构性失效，我复现了 IFNN 方法，用隐式解构造无偏导损失函数，在 Burgers 方程上成功捕捉了激波，L₂ 误差比 PINN 低约两个数量级。这段经历让我深入理解了一个核心问题：当真实系统存在不连续性或强非线性时，如何设计在数学上自洽的 AI 方法——这和医学数据里的突变、异常、个体差异处理有共同的方法论挑战。
>
> 第二段是毕业设计，用 C++17 为 Apple M3 芯片实现高性能 HNSW 向量搜索引擎。利用 NEON SIMD、FP16 压缩、细粒度自旋锁等硬件优化，在 SIFT1M 百万级数据集上实现查询 QPS 7104，单次延迟 0.14 毫秒，Recall@10 达 92.4%。高效向量检索是大规模医疗知识库和多模态模型的基础能力，这段经历让我具备了构建此类基础设施的工程能力。
>
> 了解到贵院正在推进中医药 AI 的系统性研究，包括多模态大模型、知识图谱、智能诊断等方向，我认为我的算法和工程背景能在这里找到真实的落地场景。希望能在导师指导下，做有实际意义的研究。

**时长参考**：约 60–70 秒

---

## 二、英文自我介绍

### 版本A：标准 1 分钟（必背）

```text
Good morning, dear professors. I'm Wei Kairui, a final-year student 
majoring in Big Data Management and Applications at Shanghai Institute 
of Technology.

My training gave me solid foundations in machine learning, algorithm 
design, and systems programming. I hold CET-6 and have practical 
experience in both Python and C++.

I completed two research projects. The first compared Physics-Informed 
Neural Networks with Implicit Function Neural Networks for solving 
hyperbolic PDEs with shock solutions — this gave me experience in 
designing AI methods that remain mathematically sound under 
discontinuous, highly nonlinear conditions. The second was my 
graduation project: a high-performance vector search engine in C++17, 
optimized for the Apple M3 chip, achieving 7,104 QPS and 92.4% recall 
on the SIFT1M benchmark.

I'm applying to the School of AI in TCM because I believe AI methods 
for medical knowledge representation and clinical decision support 
are among the most impactful directions in applied AI today. 
My background in numerical methods, machine learning, and 
high-performance systems gives me tools that are directly useful 
in building the infrastructure for intelligent TCM applications.

Thank you.
```

### 版本B：详细 2 分钟（备用）

```text
Good morning, dear professors. I'm Wei Kairui, 22 years old, from 
Xuzhou, Jiangsu. I'm a final-year student at Shanghai Institute of 
Technology, majoring in Big Data Management and Applications. 
My GPA is 3.62 out of 5, ranking sixth in my program, and I've 
received the university scholarship four times.

Technically, I'm proficient in C++ and Python, with hands-on 
experience in deep learning, algorithm design, and system-level 
performance optimization. I hold CET-6 and read English academic 
literature independently.

My first research project focused on deep learning for solving 
hyperbolic conservation law PDEs. The core challenge was that 
standard PINN methods fail structurally at shock discontinuities — 
they smooth over the jump instead of capturing it. I reproduced 
the Implicit Function Neural Network approach, which constructs 
a loss function using implicit solutions with no partial derivatives, 
successfully capturing the shock in the Burgers equation. The L₂ 
error was roughly two orders of magnitude lower than PINN. 
This taught me how to design AI methods that remain valid when 
data contains sharp discontinuities — a challenge directly 
relevant to handling anomalies and individual variation in 
clinical data.

My graduation project is a lightweight HNSW vector search engine 
in C++17, optimized for the Apple M3's ARM architecture. Using 
NEON SIMD, FP16 compression, and fine-grained spinlocks, I achieved 
7,104 queries per second with 92.4% recall on the SIFT1M benchmark. 
Fast, accurate vector retrieval is foundational to large-scale 
medical knowledge bases and multimodal models — exactly the 
infrastructure that intelligent TCM systems need.

I'm applying here because this school represents the most serious 
institutional commitment to AI in traditional Chinese medicine in 
China. The work on multimodal large models for pattern-syndrome 
analysis, knowledge graphs, and intelligent clinical decision 
support is exactly where I want to contribute. I'm confident 
my computational background can provide real value in building 
and improving these systems.

Thank you for your time.
```

---

## 三、跨专业动机（重要：你不是跨考，这是优势）

> ⚠️ 面试官问"你是大数据专业，为什么来这里"时，**不要**解释成"我想转行学中医"。  
> 正确角色定位：**你是带着算法和工程能力来做 AI 的，中医药是应用场景，不是你要学的主科**。

**标准回答：**

> 我不认为这是跨专业，而是方向的聚焦。大数据管理与应用本来就是一个工具性专业，核心是让计算技术在真实问题里发挥作用。在做 PINN 项目的过程中，我逐渐意识到医疗是 AI 最需要、也最难做好的场景——数据异质性强、标注稀少、错误代价高。中医药 AI 还叠加了知识体系的结构化问题，比通用医疗 AI 更难、也更有意思。贵院正在做的多模态大模型和知识图谱研究，技术核心是多模态对齐、知识表示、检索增强生成，这些都是我有能力参与的方向。我的算法和工程背景在这里有真实的用武之地。

---

## 四、中文高频追问

### Q1：你对中医药了解多少？

> 我没有中医背景，这点我不回避。但我了解过贵院在做的事：用多模态大模型做四诊客观化、用知识图谱结构化中医方证体系、用智能体辅助临床决策。这些问题的技术核心——多模态对齐、知识图谱构建、检索增强生成——都是我有能力参与的方向。中医的领域知识我需要补，但补知识比补算法能力快得多。入学后我会系统学习，同时希望尽快在工程侧做出贡献。

### Q2：你觉得 AI 在中医药哪个方向最有前景？

> 我认为是"四诊客观化结合多模态融合"这个方向。中医诊断依赖望闻问切，传统上高度依赖医生的主观经验，难以标准化和传承。如果能用计算机视觉分析舌象面色，用语音处理分析声音，再结合结构化问诊数据，训练一个真正理解中医方证逻辑的多模态模型，这件事既有学术价值，又有极强的临床落地潜力。我的 HNSW 项目做的高效向量检索，在这类大规模多模态知识库的构建里是基础组件之一——这是我觉得自己能直接贡献的地方。

### Q3：你的研究计划是什么？

> 第一年先补中医药领域基础知识，系统学习导师的研究方向，尽快进入实验室工作节奏。同时我会主动承担工程侧任务——模型推理加速、知识库检索优化这类工作，我现在就能做。中期希望找到一个具体的研究问题，比如如何让多模态医学模型在小样本中医数据上泛化更好，或者如何设计更高效的中医知识图谱表示，做出可发表的工作。

### Q4：你的 HNSW 项目和医疗有什么关系？

> 直接关系在于向量检索是医疗 AI 的基础设施。具体来说：大规模中医知识库里存着方证关联、药材配伍、历代医案，检索相似病案或方证是临床辅助决策的核心操作；多模态模型做推理时也需要高效的相似度检索。HNSW 就是解决这类问题的标准算法，我的工作是把它在边缘设备上做到极致性能——这对未来中医 AI 走进基层诊所、走进移动端是有意义的。

### Q5：你的优势和不足分别是什么？

**优势：**
> 我的优势是算法理解和工程实现的结合。PINN 项目让我能在理论层面分析 AI 方法为什么会失败；HNSW 项目让我能在工程层面把一个算法做到工业级性能。这两种能力在研究里是互补的——能分析问题的边界，也能把解决方案真正做出来跑起来。

**不足：**
> 我对中医药领域知识是空白的，这是客观事实。另外我在多人协作的大型工程项目上经验不足，之前的工作基本是独立完成的。这两点我都清楚，入学后会有意识地补。

---

## 五、英文追问

### Q: Why TCM AI specifically?

```text
Traditional Chinese medicine has thousands of years of accumulated 
clinical knowledge, but that knowledge is largely unstructured, 
subjective, and hard to transmit systematically. AI can change that.

The technical challenges here are genuinely hard — small labeled 
datasets, multimodal inputs, and the need to preserve the relational 
structure of pattern-syndrome reasoning rather than just doing 
flat classification. These are interesting problems that require 
careful algorithmic thinking, not just scaling existing methods.

My background in building systems that work correctly under 
mathematically difficult conditions gives me a concrete way 
to contribute to this kind of work.
```

### Q: What can you contribute that a biology or medicine student can't?

```text
I can build things that actually run efficiently at scale.

A lot of AI in medicine stops at proof-of-concept — the model 
works in the lab but can't be deployed in a real clinical system. 
My graduation project is specifically about closing that gap: 
taking an algorithm that works in theory and making it fast 
and reliable enough to matter in practice.

I also have experience thinking carefully about why AI methods 
fail structurally — the PINN project was entirely about 
understanding the mathematical reason a method breaks down 
and finding an alternative with better theoretical guarantees. 
That kind of analysis is useful in high-stakes medical contexts 
where failure modes matter.
```

### Q: What do you know about TCM?

```text
I'll be honest — I don't have a formal TCM background. 
But I've looked into what your school is actually building: 
multimodal large models for pattern-syndrome diagnosis, 
knowledge graphs for TCM formulas and herbs, 
intelligent agents for clinical decision support.

The core technical problems — multimodal alignment, 
knowledge representation, retrieval-augmented generation — 
are areas where I can contribute from day one. 
The domain knowledge I need to acquire, and I will, 
but learning a domain is faster than learning to build systems.
```

---

## 六、面试现场应急句

```text
没听清楚：
"I'm sorry, could you please repeat the question?"

没理解意思：
"I want to make sure I understand correctly — are you asking about [X]?"

答不上来时（不要沉默超过3秒）：
"That's an interesting question. I haven't studied that specific 
area in depth yet, but from what I understand..."

需要思考时：
"Let me think about that for just a moment."

结束回答：
"That's my current understanding — happy to discuss further."
```

---

## 七、必须背下来的数字（两个项目）

| 项目 | 指标 | 数字 |
|------|------|------|
| HNSW | 单核构建吞吐量提升 | 3.2 倍 |
| HNSW | 8线程构建加速比 | 3.31 倍 |
| HNSW | 查询 QPS | 7104 |
| HNSW | 单次延迟 | 0.14 毫秒 |
| HNSW | Recall@10 | 92.4% |
| HNSW | 数据集规模 | 100万，128维 |
| PINN/IFNN | PINN L₂误差 | $4.2 \times 10^{-1}$ |
| PINN/IFNN | IFNN L₂误差 | $3.72 \times 10^{-3}$ |
| PINN/IFNN | Adam 结束 loss | $1.24 \times 10^{-3}$ |
| PINN/IFNN | L-BFGS 结束 loss | $2.78 \times 10^{-5}$ |
| PINN/IFNN | 激波位置 | $x \approx 0.45$ |
| PINN/IFNN | 时空网格 | $101 \times 101$，步长 0.01 |

---

## 八、复试前必做一件事

**去确认一位具体导师的姓名和研究方向，在面试中自然提到。**

联系方式：
- 电话：021-51323143
- 邮箱：aitcm@shutcm.edu.cn

打电话问"请问有哪些导师在招调剂生"，5分钟能解决，对面试加分远超任何材料准备。

---

## 九、两段经历在面试中的分工

| 老师的问题指向 | 主用哪段 | 核心信息 |
|---|---|---|
| 为什么来这里/动机 | 两段结合 | 工程能力在中医药AI有真实用武之地 |
| 科研能力 | PINN/IFNN | 有完整科学流程，能理解方法论边界 |
| 工程能力 | HNSW | 有具体性能数字，不说空话 |
| 和医疗的连接 | HNSW | 向量检索是医疗知识库基础设施 |
| 能给实验室带来什么 | 两段结合 | 算法理解 + 工程执行力 |
