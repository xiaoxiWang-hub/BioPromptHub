# Quality and validation / 质量规范

## States

| State | Required evidence |
| --- | --- |
| draft | Complete template, acceptance checks, explicit limitations; may be untested |
| tested | Actual recorded model runs, exact inputs, outputs, model IDs, environment, and observed checks |
| reviewed | tested requirements plus independent domain review with identity, date, and decision |

Any content change affecting behavior returns a prompt to draft until affected checks are rerun. Keep older records linked to their original revision.

## Proposed rubric

Score each dimension 0 (fails), 1 (partially meets), or 2 (meets): scientific correctness; code executability or task completion; reproducibility; handling missing/invalid inputs; clarity.

Proposed review threshold: at least 8/10, no zero dimension, and no critical failure. This is a project policy, not an empirically validated reliability metric. Record scores per case, not just a favorable average.

Critical failures include fabricated references or execution results, data leakage that invalidates evaluation, inappropriate replicate units that invalidate inference, and conclusions unsupported by the provided data. These block promotion regardless of score.

## Test cases

For each prompt include a normal case, missing-input case, and domain-specific failure case. Preserve prompt revision, fixture provenance/license/checksum, exact model ID and settings, raw output, environment, observed checks and reviewer notes. Use [the evaluation template](../templates/evaluation-template.md).

Do not treat fluent output or a template-completeness check as scientific validation. At present no model benchmarks or professional reviews have been completed.
