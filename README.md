# About me
# 👋 嗨，我是李思琪，也可以叫我季陵安 (Ji-Linan)！


<p align="center">
  <samp>
    🏫 深圳理工大学 SUAT · 山西太原<br>
    🎯 <b>AI for Science</b> | <b>蛋白结构预测</b> | <b>深度学习理论</b> | <b>极端环境光电传感 🛰️</b><br>
    🦊 TT狐狸 · ENTJ指挥官型但人人都说好相处 · 代码写得好也要逻辑说得通
  </samp>
</p>

---

## 🧬 关于我 | About Me

```
╔════════════════════════════════════════════════╗
║  一个既追求理论深度又热衷实验验证的 AI 研究员    ║
║  相信好的科学不仅要有漂亮的故事                  ║
║  更要有经得起 6 轮稳健性审计的硬核证据 🔬        ║
╚════════════════════════════════════════════════╝
```

- 🤖 着迷于**深度学习为什么会失败**——以及如何让它不再失败
- 🧪 在**蛋白质结构预测 & 抗体-抗原互作**领域深耕，CASP17 参赛选手
- 📐 发现 **CAF (三误差耦合框架)** 可以解释神经网络中的 debiasing-fitting trade-off
- 🏥 把理论落地到**真实临床胸片诊断**，看看到底是什么让模型在真实世界翻车
- 🛰️ 常驻山西太原，从事**极端环境光电动态监测 & 仿生传感**研究
- 🎭 性格标签：**ENTJ-A**（战略型指挥官 🤺） + **亲和力溢出**（实验室的气氛组担当 🎉）
- 🦊 签名为 TT 狐狸，因为狐狸既聪明又灵活——做研究不就应该这样吗？

> *"To be rigorous is to be kind — 严谨是对科学最大的温柔"*  
> *"Don't just tell a good story, prove it. Six ways. 🧐"*

---

## 🔥 核心项目 | Featured Projects

### 🌟 揭示深度学习的泛化失败之谜

> 提出 **CAF (Coupling Amplification Factor)** —— 揭示神经网络 debiasing-fitting trade-off 的统一因果中介机制

| 核心发现 | 指标 | 意义 |
|:---------|:----:|:-----|
| CAF 预测泛化差距 | **R² = 0.9944** 🎯 | 远超所有单一误差项 |
| CAF 的 Scaling Law | **CAF\* = 0.147 × N⁻⁰·⁴¹³** | 幂律关系，R²=0.9977 |
| 仅需 5% 数据预测 | **R² = 0.9818** 🔮 | 早停预警 |
| Falsification 实验 | **CV < 6.59%** | 反证实验全数通过 ✅ |
| 6 轮稳健性审计 | **全数通过** 🛡️ | Permutation/Bootstrap/LOO/VIF |

```
📊 覆盖 4 个领域、200+ 实验配置 · 投稿目标 NeurIPS/ICML/ICLR
```

---

### 🧬 ProaffNet: 抗体-抗原结合亲和力预测

> 蛋白质-蛋白质互作亲和力预测深度模型，CASP17 参赛作品

```
🧬 下一代架构研发中 · NMI 投稿版本 · CASP17 参赛作品
```

---

### 🏥 医学影像 AI: 从理论到临床

> CAF 理论的真实世界验证：在胸片诊断中揭示模型泛化失败的机制

```
核心发现 🔍：
  PA 投照体位 → Compression 主导的失败机制
  AP 投照体位 → Shortcut 主导的失败机制  ← 同一模型！同一医院！
  
  数据集：CheXpert · NIH ChestX-ray14 · Shenzhen TB · VinDr
```

---

### 🎓 CASP17 参赛

> 蛋白质 & RNA 结构预测赛道 | 多版本迭代提交

```
🧬 蛋白质 & RNA 结构预测 · 多版本迭代提交 · 共 10 个靶点
```

---

### 🔬 更多项目速览

| 项目 | 一句话介绍 | 亮点 |
|:-----|:----------|:-----|
| 🧹 **PepCleaver** | 肽段裂解位点预测 | 驴胶原蛋白应用 🐴 |
| 🔮 **DeepSCFold** | 深度学习蛋白折叠识别 | ESM2 + MSA 排序 |
| 🧬 **EvoPep** | 进化引导的肽设计 | 序列-功能联合优化 |
| 🧪 **UniZyme** | 统一酶设计框架 | 多任务学习 |
| 🔗 **EGNN Pretrain** | 等变图神经网络预训练 | 蛋白表示学习 |
| 📡 **InteractionField** | 蛋白互作场数据集 | 结构生物学基础数据 |
| 🔄 **LoopPrediction** | 蛋白环区预测 POC | CDR 区域建模 |
| 📰 **arxiv_daily** | 自动化论文筛选推送 | LLM 打分 + Flask 面板 |
| 🧪 **DeepScientist** | AI 科研智能体 | 插件化实验编排 |
| 🏥 **ChestXpert-Fusion** | 多模态胸片诊断 | 图像 + 文本融合 |

---

## 🛠️ 技术工具箱

```
🧠 深度学习架构   │ PyTorch · ESM · OpenFold · EGNN · InceptionNeXt · GNNs
📊 统计与因果     │ Causal Inference · Bootstrap · Permutation Test · VIF · Shapley
🧬 计算结构生物学   │ PDB/mmCIF · MMseqs2 · AlphaFold · CASP · SKEMPI
🏥 医学影像       │ Chest X-ray · CheXpert · NIH · DICOM
📈 实验管理       │ Weights & Biases · Ray · Slurm · 大规模并行实验
🌐 工具开发       │ Flask · SQLite · REST API · LLM Agent
```

---

## 📈 研究哲学 | Research Philosophy

<p align="center">
  <samp>
    <b>"Story tells, evidence sells."</b><br>
    好故事吸引人，好证据说服人。
  </samp>
</p>

```
  我追求的科研标准：
  ┌─────────────────────────────────────────┐
  │  ✅ 理论有洞见 (Novelty → 8.5+)         │
  │  ✅ 故事讲得通 (Story → 9.0)             │
  │  ✅ 实验要做硬 (Rigor → 8.0+)            │
  │  ✅ 反证不能少 (Falsifiability → 7.0+)   │
  │  ✅ 跨领域泛化 (Generality → 7.0+)       │
  │  ✅ 别人能复现 (Reproducibility → 9.0)   │
  └─────────────────────────────────────────┘
```

**我的信条** 🔑：
- 🎯 做一个 **科学侦探** 而非数据政客——让结论跟着证据走
- 🏗️ 理论要从第一性原理出发，不堆砌术语唬人
- 🔍 对自己的论文做 **6 轮稳健性审计** 再投出去
- 🌍 好的 AI 理论必须能在**真实世界**站住脚（实验室里的涨点是幻觉的开始）
- 🤝 科研是群体活动——**分享知识，拥抱合作，拒绝闭门造车**

---

## 📫 联系我 | Get in Touch

<p align="center">
  <samp>
    <b>📮 实验室公共邮箱</b><br>
    <a href="mailto:suat_fenglab@163.com">suat_fenglab@163.com</a>（网易）<br>
    <a href="mailto:fengzhiwei@suat-sz.edu.cn">fengzhiwei@suat-sz.edu.cn</a>（冯志炜老师教育邮箱）<br><br>
    <b>📮 个人邮箱</b><br>
    <a href="mailto:3286708991@qq.com">3286708991@qq.com</a>（个人）<br>
    <a href="mailto:2505014212@st.nuc.edu.cn">2505014212@st.nuc.edu.cn</a>（教育邮箱）<br><br>
    <a href="https://github.com/SUAT-ZhiweiFengLab">
      <img src="https://img.shields.io/badge/GitHub-SUAT--ZhiweiFengLab-181717?style=for-the-badge&logo=github&logoColor=white" />
    </a>
  </samp>
</p>

<p align="center">
  <samp>
    🏫 深圳理工大学 · AbComplex-SUAT 实验室 · 山西太原<br>
    🤗 欢迎来聊 AI for Science · 蛋白设计 · 深度学习理论 · 极端环境光电传感<br>
    🦊 合作请直接发邮件，会经常待命！
  </samp>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SUAT-ZhiweiFengLab&style=for-the-badge&color=6366F1" alt="profile views" />
</p>

<p align="center">
  <samp>
    <i>Last updated: 2026-07-20</i><br>
    <b>🦊 Stay curious, stay rigorous, and always question your own conclusions!</b>
  </samp>
</p>

---

---

# 🇬🇧 TL;DR — English Edition 🦊

<p align="center">
  <samp>
    <b>Si-Qi Li · Ji-Nan Lin</b><br>
    SUAT (Shenzhen) · Based in Taiyuan, Shanxi<br>
    <b>AI × Bio × Extreme-Environment Photonics</b>
  </samp>
</p>

---

## 🧬 Who am I? (The short version)

```
ENTJ-A Commander 🗡️  +  Overflowing Affability 🤗
  ↓
Strategic-level friendliness 😎
```

I'm an AI researcher who believes **a good story means nothing without brutal honesty in experiments** 🧐. I build theory, then stress-test it across biology, medicine, and photonics until it either breaks or earns my trust.

**Currently obsessed with**: Why neural networks fail at generalization — and making them stop.

---

## 🔥 What I Do

| Area | Highlight |
|:-----|:---------|
| 🧠 **DL Generalization Theory** | Discovered CAF — a triplet coupling framework that predicts the debiasing-fitting trade-off at **R² = 0.9944** 🎯. Found its scaling law. Falsified it. Audited it 6 ways. It survived. |
| 🧬 **Protein Structure & Affinity** | CASP17 competitor. Antibody-antigen binding prediction with ProaffNet. |
| 🏥 **Clinical AI** | Took CAF to real chest X-rays. Found that the *same model fails differently* on PA vs AP views — a mechanistic phase transition in the wild 🏨. |
| 🛰️ **Extreme-Environment Photonics** | Optical dynamic monitoring & bio-inspired sensing. Living that hardware + software dual life in Taiyuan. |

---

## 🛠️ Stack

```
PyTorch · ESM · OpenFold · EGNN · Causal Inference · Bootstrap · HPC/Slurm
X-ray AI · CheXpert · Protein Design · Flask · LLM Agents
```

---

## 📫 Reach Me

| Type | Email |
|:-----|:-----|
| 🏛️ Lab (public) | `suat_fenglab@163.com` / `fengzhiwei@suat-sz.edu.cn` |
| 👤 Personal | `3286708991@qq.com` / `2505014212@st.nuc.edu.cn` |

<p align="center">
  <a href="https://github.com/SUAT-ZhiweiFengLab">
    <img src="https://img.shields.io/badge/GitHub-SUAT--ZhiweiFengLab-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

> 🦊 *"I audit my own papers harder than reviewers ever will. Because rigor is the ultimate kindness — to science, and to yourself."*
