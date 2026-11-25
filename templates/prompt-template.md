---
id: BPH-CATEGORY-NNN
title: Replace with a specific task
category: replace-with-directory-name
language: zh-CN
version: 0.1.0
validation_status: draft
tags: [replace]
---

# Task title / 任务名称

## Purpose / 适用场景

Describe one concrete research task, intended user, and out-of-scope uses.

## Inputs / 输入参数

| Variable | Required | Meaning / example |
| --- | --- | --- |
| `{{research_question}}` | Yes | A specific research question |
| `{{data_summary}}` | Yes | Format, dimensions, species, study design |
| `{{environment}}` | If code is requested | OS, language and package versions |

## Prompt

```text
你是一名生物信息学研究助手。请协助完成以下任务：
研究问题：{{research_question}}
数据说明：{{data_summary}}
运行环境：{{environment}}

先核查关键输入是否齐全；缺失会改变结论的信息时，先列出问题。
说明分析假设、适用条件和方法选择依据，再给出可执行步骤。
如输出代码，请包含输入检查、可复现设置、输出路径及软件版本记录。
不得编造数据、运行结果、参考文献或已经执行过的操作。
将已知事实、假设和待验证结论分开表述。

按以下格式输出：
1. 输入核查与待澄清问题
2. 分析方案与理由
3. 代码或操作步骤（如适用）
4. 验收检查与预期输出结构
5. 局限、失败情形和下一步
```

## Example / 使用示例

Supply concrete replacements for every variable and describe expected output properties. Label synthetic data explicitly.

## Acceptance checks / 验收标准

- All critical input checks are addressed.
- Code, if present, runs in the recorded environment on the supplied fixture.
- Conclusions are limited to available evidence; references are verifiable.

## Limitations / 局限

Describe task-specific failure modes, assumptions, and manual review needs.

## Validation / 验证记录

Untested. Add relative links to evaluation records after actual runs.

## References / 参考资料

Add verified primary sources when scientific or software-specific claims are made. Do not invent citations.
