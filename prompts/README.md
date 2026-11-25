# Prompt catalog / 提示词目录

首批共 **25 条中文草稿**。全部为 `draft / untested`，尚未完成模型测试或专业审核。示例与验收要点是预期行为，不是观察结果。

## Single-cell RNA-seq（6）

| ID | Task | Language | Validation |
| --- | --- | --- | --- |
| BPH-SC-001 | [单细胞输入与元数据核查](single-cell-rna-seq/input-metadata-audit.md) | zh-CN | draft — untested |
| BPH-SC-002 | [按样本设计单细胞质量控制](single-cell-rna-seq/sample-aware-qc.md) | zh-CN | draft — untested |
| BPH-SC-003 | [归一化与批次整合决策](single-cell-rna-seq/normalization-integration-plan.md) | zh-CN | draft — untested |
| BPH-SC-004 | [单细胞聚类与稳定性评估](single-cell-rna-seq/clustering-stability.md) | zh-CN | draft — untested |
| BPH-SC-005 | [基于证据的细胞类型注释](single-cell-rna-seq/evidence-based-annotation.md) | zh-CN | draft — untested |
| BPH-SC-006 | [按生物学重复设计 pseudobulk 差异分析](single-cell-rna-seq/donor-aware-pseudobulk.md) | zh-CN | draft — untested |

## Bulk RNA-seq（6）

| ID | Task | Language | Validation |
| --- | --- | --- | --- |
| BPH-BR-001 | [Bulk RNA-seq 实验设计与比较定义](bulk-rna-seq/experimental-design.md) | zh-CN | draft — untested |
| BPH-BR-002 | [计数矩阵导入与样本对齐](bulk-rna-seq/count-matrix-validation.md) | zh-CN | draft — untested |
| BPH-BR-003 | [Bulk RNA-seq 探索性质量评估](bulk-rna-seq/exploratory-qc.md) | zh-CN | draft — untested |
| BPH-BR-004 | [DESeq2 差异分析与显式 contrast](bulk-rna-seq/deseq2-explicit-contrast.md) | zh-CN | draft — untested |
| BPH-BR-005 | [富集分析与背景基因集核查](bulk-rna-seq/enrichment-with-background.md) | zh-CN | draft — untested |
| BPH-BR-006 | [可复现转录组结果报告](bulk-rna-seq/reproducible-results-report.md) | zh-CN | draft — untested |

## R / Python（5）

| ID | Task | Language | Validation |
| --- | --- | --- | --- |
| BPH-RP-001 | [生物信息学分析代码审查](r-python/analysis-code-review.md) | zh-CN | draft — untested |
| BPH-RP-002 | [构造最小复现并定位 R/Python 错误](r-python/minimal-reproducible-debugging.md) | zh-CN | draft — untested |
| BPH-RP-003 | [安全合并表达数据与样本信息](r-python/safe-metadata-joins.md) | zh-CN | draft — untested |
| BPH-RP-004 | [绘制可核查的科研图表](r-python/honest-research-visualization.md) | zh-CN | draft — untested |
| BPH-RP-005 | [记录并重建 R/Python 分析环境](r-python/environment-reproducibility.md) | zh-CN | draft — untested |

## Literature research（4）

| ID | Task | Language | Validation |
| --- | --- | --- | --- |
| BPH-LR-001 | [设计可复现文献检索策略](literature-research/reproducible-search-strategy.md) | zh-CN | draft — untested |
| BPH-LR-002 | [从论文提取可追溯证据](literature-research/traceable-evidence-extraction.md) | zh-CN | draft — untested |
| BPH-LR-003 | [公平比较生物信息学方法](literature-research/fair-method-comparison.md) | zh-CN | draft — untested |
| BPH-LR-004 | [带引用核验的文献综合](literature-research/citation-grounded-synthesis.md) | zh-CN | draft — untested |

## AI / Machine learning（4）

| ID | Task | Language | Validation |
| --- | --- | --- | --- |
| BPH-ML-001 | [组学机器学习数据泄漏审查](ai-machine-learning/data-leakage-audit.md) | zh-CN | draft — untested |
| BPH-ML-002 | [设计按个体分组的嵌套验证](ai-machine-learning/grouped-nested-validation.md) | zh-CN | draft — untested |
| BPH-ML-003 | [组学分类基线与性能报告](ai-machine-learning/baseline-classifier-evaluation.md) | zh-CN | draft — untested |
| BPH-ML-004 | [模型解释与外部验证计划](ai-machine-learning/interpretation-external-validation.md) | zh-CN | draft — untested |

新增内容请使用[标准模板](../templates/prompt-template.md)，质量要求见[质量规范](../docs/QUALITY.md)。
