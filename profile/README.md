# PhenoGeno Lab

**临床基因组学与罕见病 AI** · Clinical genomics & rare-disease AI

我们把 **ACMG/AMP 变异解读**、**HPO 表型标准化** 与 **大模型证据抽取** 做成可复现的工具链，
落地在两个临床场景：**产前筛查 / 诊断** 与 **遗传变异分类**。

## 研究方向

- **变异解读** — 多语种文献 → ACMG/AMP 2015 证据项，ClinVar 交叉验证，可追溯的证据表
- **表型标准化** — 临床自由文本（中/英）→ HPO 术语 + 发病年龄，输出稳定 JSON 契约
- **疾病推理** — HPO → 候选疾病排序（LIRICAL / CNB / BOQA 离线集成 + 在线增强），MONDO 归一
- **证据工程** — 可复现流水线、离线部署、基准与验收测试

## 开源项目

| 仓库 | 说明 |
| --- | --- |
| [LinguaSeeker](./LinguaSeeker) | LLM 解析多语种文献抽取 ACMG/AMP 证据，集成 ClinVar 验证，优先输出 HTML 报告 |
| [demo_PhenoBrain](./demo_PhenoBrain) | PhenoBrain 离线诊断流程的可复现运行环境：HPO 表型列表 → 候选疾病排序 |

## 在研平台

> 内部仓库，按需开放合作。

- **PrenatalSeeker** — 产前筛查智能辅助平台：文献获取 / 解析 / LLM 抽取流水线（FastAPI + LangGraph），RAG 后端（Spring Boot + Spring AI），React 工作台
- **HPO 表型与疾病推理服务** — 表型标准化智能体 + 疾病推理/注释智能体，可组合为病例级推断流水线
- **DNA 基础模型基准** — Enformer / GET / GPN / Nucleotide Transformer / SegmentNT 的统一验证与评测

## 技术栈

`Python` · `TypeScript / React` · `Java / Spring AI` · `Rust` · `FastAPI` · `LangGraph` · `PostgreSQL` · `Docker`

## 联系

- 地址：Changsha, China
- 邮箱：[yhvguk@stu.hunau.edu.cn](mailto:yhvguk@stu.hunau.edu.cn)
