# 多模态音频理解研究综述：从基础模型到音频大语言模型

> 🤖 由 Claude Opus 4.6 自动生成 · 最后更新：2026-03-14

本仓库收录 VLA（Vision-Language-Action）与具身智能领域的论文分析与自动综述，
覆盖 **107 篇** arXiv 论文，使用 Claude Batches API 批量分析生成。

## 📄 综述文档

- [vla_survey_20260314_2316.md](surveys/vla_survey_20260314_2316.md)
- [vla_survey_20260314_2020.md](surveys/vla_survey_20260314_2020.md)

## 📊 论文分析

[paper_analyses/](paper_analyses/) 目录包含每篇论文的结构化 JSON 分析，字段包括：
- `one_sentence_summary`：一句话概括
- `key_contributions`：核心贡献
- `technical_approach`：技术方法
- `survey_theme`：主题分类
- `importance_score`：重要程度评分（1-5）

## 🔍 覆盖方向

| 方向 | 说明 |
|------|------|
| VLA核心架构 | Vision-Language-Action Models |
| 基础模型迁移 | Foundation Models for Robotics |
| 操作策略学习 | Robot Manipulation Policies |
| 视觉表示学习 | Visual Representation Learning |
| 任务规划推理 | LLM-based Task Planning |
| 数据与基准 | Datasets and Benchmarks |

## ⚙️ 生成方式

本仓库由 [`research-agent`](https://github.com) 自动生成：
1. 从 arXiv 收集论文
2. 使用 Claude Batches API（5折）批量分析
3. 使用 Claude Opus 4.6 + Streaming 生成综述
4. 自动推送到本仓库

---

*本仓库内容由 AI 自动生成，供学习参考，请结合原始论文进行研究。*
