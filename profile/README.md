# PhenoGenoLab

**表型 × 基因组 · 医学遗传与生物信息** · Medical Genetics & Bioinformatics

用生物信息、大语言模型与深度学习，把「**变异 → 致病性**」与「**基因 → 疾病**」的判断做得更准、更可复现。
本组织托管课题组与项目的代码。

官网：[genemed.tech/jclab](https://www.genemed.tech/jclab) · 地址：Changsha, China

## 代码方向

- **变异解读** — 多语种文献 → ACMG/AMP 2015 证据项，ClinVar 交叉验证，输出可追溯的证据表
- **表型与疾病推理** — 临床自由文本 → HPO 术语；HPO → 候选疾病排序（LIRICAL / CNB / BOQA 集成），MONDO 归一
- **数据资源** — ClinVar 提交记录证据抽取、DNA 基础模型统一评测基准
- **临床落地** — 产前筛查 / 诊断辅助平台（文献流水线 + RAG 后端 + Web 工作台）

## 开源项目

| 仓库 | 说明 |
| --- | --- |
| [LinguaSeeker](./LinguaSeeker) | LLM 解析多语种 PDF 文献抽取 ACMG/AMP 证据，集成 ClinVar 验证，优先输出 HTML 报告 |
| [demo_PhenoBrain](./demo_PhenoBrain) | PhenoBrain 离线诊断流程的可复现运行环境：HPO 表型列表 → 候选疾病排序 |

## 技术栈

`Python` · `TypeScript / React` · `Java / Spring AI` · `Rust` · `FastAPI` · `LangGraph` · `PostgreSQL` · `Docker`

## 联系

- 官网：[genemed.tech/jclab](https://www.genemed.tech/jclab)
- 邮箱：[yhvguk@stu.hunau.edu.cn](mailto:yhvguk@stu.hunau.edu.cn)
