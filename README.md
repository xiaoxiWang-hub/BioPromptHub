# BioPromptHub

**Reusable prompts for bioinformatics research.**

[简体中文](README.zh-CN.md) · [Prompt catalog](prompts/README.md) · [Contribute](CONTRIBUTING.md) · [Roadmap](docs/ROADMAP.md)

BioPromptHub is an open collection of structured prompts for planning analyses, writing and reviewing code, and interpreting research. Each prompt describes its inputs, expected output, limitations, and validation status.

## Start here

1. Browse the [catalog](prompts/README.md).
2. Copy the `Prompt` section and replace every `{{variable}}` with your context.
3. Supply only data you are authorized to share. Use synthetic or public examples when possible.
4. Check generated code, references, statistical assumptions, and biological conclusions before use.

## Priority areas

| Area | Directory | Initial release target |
| --- | --- | --- |
| Single-cell RNA-seq | [single-cell-rna-seq](prompts/single-cell-rna-seq/README.md) | 6 prompts |
| Bulk RNA-seq | [bulk-rna-seq](prompts/bulk-rna-seq/README.md) | 6 prompts |
| R / Python | [r-python](prompts/r-python/README.md) | 5 prompts |
| Literature research | [literature-research](prompts/literature-research/README.md) | 4 prompts |
| AI / Machine learning | [ai-machine-learning](prompts/ai-machine-learning/README.md) | 4 prompts |

The Phase 2 target is 25 curated prompts. This initialization contains one untested starter example; it does not yet contain the full collection.

## Repository layout

```text
prompts/          Core categories and prompt catalog
templates/        Standard prompt and evaluation templates
docs/             Roadmap, quality rubric, and usage guidance
evaluations/      Recorded model runs and review evidence
datasets/         Small public or synthetic evaluation fixtures
workflows/        Future end-to-end research prompts
examples/         Example inputs and expected checks
.github/          Issue and pull request templates
```

## Quality and contributions

Use the [standard template](templates/prompt-template.md) and read the [contribution guide](CONTRIBUTING.md). Prompts progress through `draft`, `tested`, and `reviewed`; evidence requirements appear in the [quality guide](docs/QUALITY.md). These labels describe recorded checks, not universal reliability.

## License

Original repository content is released under the [MIT License](LICENSE). External datasets and publications retain their own licenses. This is a research aid; outputs require independent scientific validation.
