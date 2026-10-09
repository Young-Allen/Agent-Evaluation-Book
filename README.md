# Agent-Evaluation-Book

- [Agent 评测精选技术文章索引](Agent-Evaluation-Article-Index.md)：从 Word 文档提取的文章清单、推荐指数、简介与原文链接。
- [Anthropic《Demystifying evals for AI agents》中文整理与工程解读](Anthropic-Demystifying-Evals-for-AI-Agents-zh.md)：核心术语、评分器、Agent 类型、随机性指标和 Step 0—8 建设流程，附原文图。
- [Agent 评测漫谈：详细学习笔记与工程分析](Agent-Evaluation-Talk-analysis.md)：指标设计、人机对齐、Trace、长程任务与 Skill 生命周期评测。
- [Agent 评测全览学习笔记](Agent-Evaluation-White-Paper-01-summary.md)
- [Agent 工程评测 Skill](skills/agent-evaluation/SKILL.md)：评测设计、离线回归、线上观察与问题归因，附任务和报告模板。

Skill 仅保存在本项目的 `skills/agent-evaluation/`，不安装到个人 Codex 目录。使用时可以明确指定项目内文件，例如：

```text
读取 skills/agent-evaluation/SKILL.md，按其中流程分析这个 Agent 项目的评测缺口，并设计核心任务和 Rubric。
读取 skills/agent-evaluation/SKILL.md，结合这些 Trace 分析任务失败原因，给出证据和回归任务。
读取 skills/agent-evaluation/SKILL.md，为新版本设计影子验证、A/B 和巡检方案。
```
