# Peng2555

<div align="center">

![hero](https://capsule-render.vercel.app/api?type=waving&color=0:081c15,22:1b4332,48:2d6a4f,72:40916c,100:95d5b2&height=260&section=header&text=Designing%20Antibodies%20with%20Code&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AIDD%20%7C%20Antibodies%20%7C%20CADD%20%7C%20Reproducible%20Pipelines&descAlignY=58&descSize=16)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&pause=1200&center=true&vCenter=true&width=980&lines=From+antibody+sequence+and+structure+to+experiment-ready+variants;Building+platforms+that+turn+AIDD+models+into+usable+workflows;Connecting+folding%2C+redesign%2C+docking%2C+and+decision+support)](https://git.io/typing-svg)

<p>
  <img src="https://img.shields.io/badge/Focus-AIDD-183a1d?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Antibodies-2d6a4f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-CADD-40916c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Style-Reproducible%20Research-74c69d?style=for-the-badge" />
</p>

</div>

## A Short Introduction | 一句话介绍

I build computational systems for **AI-driven drug discovery**, with a current focus on **therapeutic antibodies / nanobodies**, **protein–drug platforms**, and **structure-based CADD workflows**.  
我在构建面向 **AI 驱动药物发现** 的计算系统，当前重点是 **治疗性抗体 / 纳米抗体**、**蛋白质–药物计算平台**，以及 **基于结构的 CADD 工作流**。

I like research that does not stop at analysis, but becomes a usable workflow for the next experiment, the next model, and the next decision.  
我希望研究不只停在分析，而能变成支撑下一轮实验、下一轮建模和下一次决策的工作流。

## Research Map | 研究地图

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>What I Work On</h3>
      <p><strong>Therapeutic Antibodies</strong><br/>Affinity modulation, thermostability (Tm), developability, and sequence–structure redesign.</p>
      <p><strong>Protein–Drug Platform</strong><br/>Folding, redesign, docking, and MD modules wrapped into reproducible, queueable systems.</p>
      <p><strong>Structure-Based CADD</strong><br/>Literature-faithful docking protocols, validation matrices, and decision-ready reporting.</p>
    </td>
    <td width="50%" valign="top">
      <h3>我在做什么</h3>
      <p><strong>治疗性抗体</strong><br/>关注亲和力调控、热稳定性（Tm）、可开发性，以及序列–结构改造。</p>
      <p><strong>蛋白质–药物平台</strong><br/>把折叠、改造、对接与 MD 模块封装成可复现、可排队的系统。</p>
      <p><strong>基于结构的 CADD</strong><br/>关注文献级对接协议、验证矩阵，以及面向决策的结果汇报。</p>
    </td>
  </tr>
</table>

## Signature Themes | 核心主题

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>01<br/>Model-Guided Design</h3>
      <p>Using folding, inverse folding, and PLMs to connect sequence, structure, and function for antibody discovery.</p>
      <p>用折叠、逆折叠与蛋白语言模型连接序列、结构与功能，服务抗体发现。</p>
    </td>
    <td width="33%" valign="top">
      <h3>02<br/>Reproducible Pipelines</h3>
      <p>Turning raw biological data into auditable workflows, structured outputs, and reusable research assets.</p>
      <p>把原始生物数据转成可审计流程、结构化输出和可复用研究资产。</p>
    </td>
    <td width="33%" valign="top">
      <h3>03<br/>Decision Systems</h3>
      <p>Building systems that help prioritize experiments instead of merely producing figures.</p>
      <p>构建能支撑实验优先级判断的系统，而不只是产出图表。</p>
    </td>
  </tr>
</table>

## Current Buildboard | 当前构建板

```text
Antibody Discovery Engine
|- sequence / structure QC (ANARCI, pLDDT, interface checks)
|- thermostability & affinity redesign
|- developability filters (hydrophobic patch, charge, liabilities)
|- docking / MD / reporting for experiment handoff
`- platform infrastructure (queue, auth, 3D viewer)
```

```text
当前研究系统
|- 序列 / 结构质检（ANARCI、pLDDT、界面检查）
|- 热稳定性与亲和力改造
|- 可开发性过滤（疏水斑块、电荷、化学负债）
|- 对接 / MD / 面向实验交接的报告
`- 平台基础设施（任务队列、账号、3D 可视化）
```

## Featured Projects | 代表项目

| Project | What it is | Why it matters |
|---|---|---|
| **[protein-drug-platform](https://github.com/Peng2555/protein-drug-platform)** | Local AIDD platform for structure prediction, sequence redesign, docking, affinity maturation, and MD. | Turns model calls into a usable research system with queues, auth, and 3D viewing. |
| **[ras-tricomplex-docking](https://github.com/Peng2555/ras-tricomplex-docking)** | RAS tri-complex CADD workflows for RMC-6236 (noncovalent) and RMC-6291 (covalent). | Shows literature-faithful docking can be scripted, validated, and reused. |
| **[Nanobody-sequence-optimization](https://github.com/Peng2555/Nanobody-sequence-optimization)** | PyMOL antibody toolkit for CDR annotation, interface analysis, and surface hydrophobicity / charge. | Makes structural inspection fast, consistent, and documentable. |
| **[gLM2_JAC](https://github.com/Peng2555/gLM2_JAC)** | gLM2 Jacobian contact-map visualization for protein–nucleic acid systems. | Bridges PLM internals and interpretable structural signal. |

| 项目 | 是什么 | 为什么重要 |
|---|---|---|
| **[protein-drug-platform](https://github.com/Peng2555/protein-drug-platform)** | 面向结构预测、序列改造、对接、亲和力成熟与 MD 的本地 AIDD 平台。 | 把模型调用变成带队列、账号与 3D 可视化的可用研究系统。 |
| **[ras-tricomplex-docking](https://github.com/Peng2555/ras-tricomplex-docking)** | RAS 三元复合物 CADD：RMC-6236（非共价）与 RMC-6291（共价）。 | 证明文献级对接协议可以被脚本化、验证并复用。 |
| **[Nanobody-sequence-optimization](https://github.com/Peng2555/Nanobody-sequence-optimization)** | PyMOL 抗体工具集：CDR 标注、界面分析、表面疏水 / 电荷。 | 让结构检查更快、更一致、也更可文档化。 |
| **[gLM2_JAC](https://github.com/Peng2555/gLM2_JAC)** | 基于 gLM2 雅可比矩阵的蛋白–核酸接触图可视化。 | 把 PLM 内部信号转成可解释的结构信息。 |

### Earlier Directions | 早期方向

- Cyclic peptide candidate ranking with geometric constraints and multi-metric evaluation
- Multi-omics analysis prototype ([omacs](https://github.com/Peng2555/omacs))
- Hands-on exploration of protein design / PLM stacks (`IgGM`, `ESM`, `PPIFlow`, `RFdiffusion`, `pepGLAD`, ...)

- 基于几何约束与多指标评价的环肽候选筛选
- 多组学分析平台原型（[omacs](https://github.com/Peng2555/omacs)）
- 蛋白设计 / PLM 工具栈的实践探索（`IgGM`、`ESM`、`PPIFlow`、`RFdiffusion`、`pepGLAD` 等）

## Method Stack | 方法栈

<p>
  <img src="https://img.shields.io/badge/Python-14213d?style=for-the-badge&logo=python&logoColor=ffd60a" />
  <img src="https://img.shields.io/badge/FastAPI-0a9396?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-9d0208?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/ESM--2-005f73?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Boltz2-1d3557?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IgGM-2d6a4f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AntiFold-40916c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ProteinMPNN-52b788?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Rosetta-7f5539?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AutoDock%20Vina-ca6702?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GROMACS-023e8a?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PyMOL-3c096c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RDKit-0a9396?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ANARCI-1b4332?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Git-7f5539?style=for-the-badge&logo=git&logoColor=white" />
</p>

## GitHub Signal | GitHub 信号

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Peng2555&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Peng2555&layout=compact&hide_border=true&theme=transparent" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Peng2555&theme=transparent&hide_border=true" />
</div>

## Philosophy | 研究观

> Good research code should not only run once.  
> It should be understandable, reproducible, and useful for the next decision.

> 好的研究代码不应只跑一次。  
> 它应该可理解、可复现，并且能服务下一次决策。

## Contact | 联系方式

- GitHub: [@Peng2555](https://github.com/Peng2555)
- Email: `1733317481@qq.com`

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:95d5b2,38:52b788,72:2d6a4f,100:081c15&height=130&section=footer)

</div>
