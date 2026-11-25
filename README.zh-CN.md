# BioPromptHub · 生物信息学提示词库

**面向生物信息学研究的可复用、结构化 AI 提示词。**

[English](README.md) · [提示词目录](prompts/README.md) · [贡献指南](CONTRIBUTING.md) · [开发路线](docs/ROADMAP.md)

本项目收集分析规划、代码编写与审核、文献研究和结果解释等场景的 Prompt。每条提示词应明确输入、输出、适用范围和验证状态，便于研究者复用与改进。

## 快速使用

1. 从[分类目录](prompts/README.md)选择任务。
2. 复制文件的 `Prompt` 部分，替换全部 `{{变量}}`。
3. 提供物种、数据类型、实验设计、软件版本和预期输出；缺失的关键信息应先澄清。
4. 人工核查代码、统计假设、参考文献及生物学结论，再应用于真实研究。

请仅提供有权共享的数据，优先使用公开或合成示例。

## 首批建设目标

| 方向 | 入口 | 已收录草稿 |
| --- | --- | --- |
| Single-cell RNA-seq | [单细胞分析](prompts/single-cell-rna-seq/README.md) | 6 |
| Bulk RNA-seq | [转录组分析](prompts/bulk-rna-seq/README.md) | 6 |
| R / Python | [编程与复现](prompts/r-python/README.md) | 5 |
| Literature Research | [文献研究](prompts/literature-research/README.md) | 4 |
| AI / Machine Learning | [机器学习](prompts/ai-machine-learning/README.md) | 4 |

首批 25 条结构化提示词草稿已收录，覆盖以上五个领域。全部标记为 draft / untested；模型测试与独立专业审核属于 Phase 3，尚未完成。

## 目录说明

```text
prompts/          提示词分类与索引
templates/        标准 Prompt 和测试记录模板
docs/             路线图、质量标准、使用指南
evaluations/      模型测试和审核证据
datasets/         公开或合成测试数据
workflows/        后续完整分析流程
examples/         输入示例与验收要点
.github/          Issue 与 Pull Request 模板
```

## 质量与贡献

按[标准模板](templates/prompt-template.md)提交，参见[贡献指南](CONTRIBUTING.md)。状态分为 `draft`（草稿）、`tested`（已记录测试）、`reviewed`（已记录专业审核）。未完成测试不得声称已验证；详见[质量规范](docs/QUALITY.md)。

## 许可证

原创内容使用 [MIT License](LICENSE)。外部数据和文献遵循各自许可。项目用于辅助研究，模型输出需要独立科学验证。
