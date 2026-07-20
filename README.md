# Hi, I'm Sherry 👋

I build evidence-grounded AI agents and workflows: systems that make their sources, decisions, tests, and human-review boundaries inspectable.

My background is in product and entrepreneurship. I now work at the intersection of AI product design, agent reliability, research automation, and reproducible evaluation.

## Selected work

### [nanoGPT Learning Lab](https://github.com/sherrywong0512/nanoGPT)

**Reproducible learning and evaluation tooling built on Andrej Karpathy's nanoGPT.**

- Added a CLI that records configuration, environment, Git state, data hashes, logs, metrics, summaries, and checkpoints for each experiment.
- Added controlled CPU experiments, artifact-consistency checks, a generated evidence dashboard, and integration tests.
- Preserved the upstream training code unchanged and documented the boundary between upstream work, AI assistance, and my own learning evidence.
- Evidence: [experiment report](https://github.com/sherrywong0512/nanoGPT/blob/master/docs/experiment-report.md) · [tests](https://github.com/sherrywong0512/nanoGPT/tree/master/tests) · [passing CI](https://github.com/sherrywong0512/nanoGPT/actions/workflows/ci.yml) · [v1.0 tag](https://github.com/sherrywong0512/nanoGPT/tree/v1.0)

### [Evidence-grounded research adapter](https://github.com/sherrywong0512/open_deep_research/pull/1)

**A contribution to LangChain's open-deep-research fork that turns research output into reviewable due-diligence evidence.**

- Separates research candidates from verified quotations and requires explicit human review before promotion.
- Preserves observed source URLs, rejects unsafe URLs and incomplete evidence, and checks that excerpts are grounded in fetched content.
- Includes adapters, pinned public fixtures, examples, and focused tests.
- Status: active pull request; the contribution is not presented as upstream or merged work.

### [Evidence-first investment research workflow](https://github.com/sherrywong0512/ai-berkshire-sherry/tree/codex/framework-eval-3cases)

**A fork experiment that tests whether explicit evidence contracts improve AI-assisted investment research.**

- Added freshness gates, report audits, review registries, adversarial evidence review, and publication checks.
- Compared the original and modified workflows across three blind-evaluation cases.
- Ran an end-to-end Tencent research case with claim-level evidence and review artifacts.
- Evidence: [fork methodology](https://github.com/sherrywong0512/ai-berkshire-sherry/blob/codex/framework-eval-3cases/docs/SHERRY_FORK_V1.md) · [evaluation](https://github.com/sherrywong0512/ai-berkshire-sherry/tree/codex/framework-eval-3cases/evals/2026-07-13-framework-comparison) · [passing CI](https://github.com/sherrywong0512/ai-berkshire-sherry/actions/workflows/verify.yml)

## How I work

```text
real problem → explicit evidence contract → smallest useful workflow
→ tests and adversarial review → documented limits → next iteration
```

I care about the boundary between a convincing AI demo and a system people can responsibly use: provenance, failure handling, evaluation, human judgment, and clear ownership of AI-assisted work.

## Current focus

- AI agent product design and reliability
- Research agents with traceable evidence
- Evaluation workflows that replace vague quality claims with reviewable artifacts

Based in Singapore · Open to AI Agent, AI product, and applied-AI opportunities.

---

## 中文简介

我是 Sherry，拥有产品与创业背景，目前专注于构建**证据可追溯、决策可检查、边界可解释**的 AI Agent 与智能工作流。

这里的项目不以“用了多少 Agent”为成果，而以可复现运行、测试、证据链、人工复核边界和对失败条件的说明作为验证。代表项目包括 nanoGPT 可复现实验室、深度研究证据适配器，以及经过三案例盲测的 AI 投研证据工作流。
