# LLM Evaluation Templates

Reusable templates for evaluating large language model (LLM) outputs in a structured, consistent and reviewable way.

> These are original, generic templates. They contain no client, platform or confidential material, and all examples were written by me for this repository.

## Why this exists

Good evaluation is consistent and easy for a reviewer to check. These templates turn that into a repeatable process: clear criteria, specific evidence, and a written rationale for every decision.

## What's inside

| File | Purpose |
|------|---------|
| `error-taxonomy.md` | A defined set of error categories for classifying where a model response goes wrong |
| `rubric-template.md` | A scoring rubric covering accuracy, completeness, instruction following and clarity |
| `rationale-template.md` | A fixed format for writing evidence-backed pass/fail decisions |
| `side-by-side-comparison-template.md` | A table for comparing two model responses to the same prompt |

## Evaluation principles

1. **Verify, don't assume.** Check each claim against a reliable source.
2. **Be specific.** Name the exact error or omission, not just "incorrect".
3. **Show evidence.** A reviewer should be able to confirm the decision quickly.
4. **Flag ambiguity.** If a prompt or guideline is unclear, note it instead of guessing.
5. **Stay consistent.** Apply the same standard to every response.

## How to use

1. Read the response against the prompt.
2. Classify any errors using `error-taxonomy.md`.
3. Score using `rubric-template.md`.
4. Write your decision using `rationale-template.md`.
5. If comparing models, use `side-by-side-comparison-template.md`.

## Related

See my [fact-verification-casebook](https://github.com/SylvesterAdahJohn/fact-verification-casebook) for worked examples of evidence-based verification.

## Author

John Adah Sylvester, AI Research Evaluator
[LinkedIn](https://www.linkedin.com/in/john-sylvester-54b758444)
