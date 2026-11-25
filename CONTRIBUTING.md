# Contributing / 贡献指南

Contributions in Chinese or English are welcome. 欢迎中文或英文贡献。

1. Search existing prompts and issues to avoid duplicates.
2. Fork the repository and create a descriptive branch.
3. Copy [the prompt template](templates/prompt-template.md) into the most relevant category. Use lowercase kebab-case filenames and a unique stable ID, such as `BPH-SC-001`.
4. Describe inputs, assumptions, output format, limitations, and acceptance checks. Include a small public or synthetic example; never submit identifiable participant data, secrets, or unpublished material without permission.
5. Set `validation_status: draft` until a real model run is recorded. To request promotion, attach an [evaluation record](templates/evaluation-template.md) and update the [catalog](prompts/README.md).
6. Open a pull request explaining the research task and validation performed. Disclose AI-assisted drafting and verify all claims yourself.

中文要点：单条 Prompt 对应清晰任务；参数可替换；不编造数据、软件运行结果或文献；说明失败情况；提供验收标准；同步更新目录。翻译可以单独贡献，使用 `.zh-CN.md` 或 `.en.md` 后缀并共享同一 ID。

## Review

A maintainer checks structure, clarity, originality, and scope before merging. A domain reviewer checks scientific assumptions and test evidence before `reviewed` status is assigned. Until reviewers are recruited, prompts may remain drafts; no professional review is implied by merging alone.

Use [the quality rubric](docs/QUALITY.md). Record reviewer identity, date, prompt revision, and unresolved limitations. Fixes to the prompt require re-evaluating affected cases.

## Attribution and conduct

Submit only content you may distribute under the [MIT License](LICENSE). Preserve third-party attribution and licensing requirements. Be respectful, discuss evidence rather than people, and use issues for reproducible problems. Contributors are listed in [CONTRIBUTORS.md](CONTRIBUTORS.md) with their consent.
