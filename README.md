# Hi, I'm Sherry 👋

[English](#english) · [中文](#中文)

## English

I’m an AI product builder and practitioner, focused on turning emerging technologies into workflows and products that are useful, testable, and designed to improve over time.

My startup experience has taught me to start with the real world: What problem are we solving? Will people use it? Can it work end to end? And can it grow beyond the effort of any one person?

I’m now bringing that perspective into the AI era—building evidence-grounded AI agents and workflows whose sources, decisions, tests, and human-review boundaries are inspectable.

## Selected work

### [Ingredient Opportunity Research](https://github.com/sherrywong0512/ingredient-opportunity-research)

**An original evidence-led Codex skill for ingredient feasibility and B2B customer discovery.**

- Turns material identity, science, regulation, formulation, cost-in-use, SKU adoption, and customer fit into an explicit two-stage decision workflow.
- Includes three audited case studies, hard evidence gates, transparent unresolved blockers, and a dependency-free project validator.
- Demonstrates product and domain judgment through a reusable Agent Skill rather than a one-off report.
- Evidence: [case studies](https://github.com/sherrywong0512/ingredient-opportunity-research#case-studies) · [quality model](https://github.com/sherrywong0512/ingredient-opportunity-research#quality-model) · [validator](https://github.com/sherrywong0512/ingredient-opportunity-research/blob/main/scripts/validate_project.py) · [passing CI](https://github.com/sherrywong0512/ingredient-opportunity-research/actions/workflows/validate.yml)

### [Evidence-Driven Project Evaluator](https://github.com/sherrywong0512/evidence-driven-project-evaluator)

**An original file-based AI Agent workflow for separating project viability from personal role fit.**

- Routes early opportunities through company screening, evidence collection, project intake, hard gates, feasibility assessment, and explicit participation decisions.
- Treats unknown facts as blockers rather than average scores and keeps project viability separate from “lead,” “bounded role,” or “do not participate” recommendations.
- Includes reusable rubrics and templates, an anonymized end-to-end example, a dependency-free validator, unit tests, and CI.
- Evidence: [workflow and design](https://github.com/sherrywong0512/evidence-driven-project-evaluator#工作流) · [fictional example](https://github.com/sherrywong0512/evidence-driven-project-evaluator/tree/main/examples/fictional-ai-pilot) · [validator and tests](https://github.com/sherrywong0512/evidence-driven-project-evaluator/tree/main/tools) · [passing CI](https://github.com/sherrywong0512/evidence-driven-project-evaluator/actions/workflows/validate.yml)

### [nanoGPT Learning Lab](https://github.com/sherrywong0512/nanoGPT)

**Reproducible learning and evaluation tooling built on Andrej Karpathy's nanoGPT.**

- Added a CLI that records configuration, environment, Git state, data hashes, logs, metrics, summaries, and checkpoints for each experiment.
- Added controlled CPU experiments, artifact-consistency checks, a generated evidence dashboard, and integration tests.
- Preserved the upstream training code unchanged and documented the boundary between upstream work, AI assistance, and my own learning evidence.
- Evidence: [experiment report](https://github.com/sherrywong0512/nanoGPT/blob/master/docs/experiment-report.md) · [tests](https://github.com/sherrywong0512/nanoGPT/tree/master/tests) · [passing CI](https://github.com/sherrywong0512/nanoGPT/actions/workflows/ci.yml) · [v1.0 tag](https://github.com/sherrywong0512/nanoGPT/tree/v1.0)

### [Evidence-grounded research adapter](https://github.com/sherrywong0512/open_deep_research)

**A contribution to LangChain's open-deep-research fork that turns research output into reviewable due-diligence evidence.**

- Separates research candidates from verified quotations and requires explicit human review before promotion.
- Preserves observed source URLs, rejects unsafe URLs and incomplete evidence, and checks that excerpts are grounded in fetched content.
- Includes adapters, pinned public fixtures, examples, and focused tests.
- Merged into this portfolio fork's `main` branch after 27 focused tests passed locally and in GitHub Actions; it is not presented as an upstream LangChain contribution.
- Evidence: [design and usage](https://github.com/sherrywong0512/open_deep_research#fork-focus-diligence-evidence-packages) · [tests](https://github.com/sherrywong0512/open_deep_research/tree/main/tests) · [passing CI](https://github.com/sherrywong0512/open_deep_research/actions/workflows/diligence-evidence-tests.yml) · [reviewed change](https://github.com/sherrywong0512/open_deep_research/pull/1)

## Additional work

- [Evidence-first investment research workflow](https://github.com/sherrywong0512/ai-berkshire-sherry) — a fork experiment with evidence contracts, report audits, adversarial review, and a three-case blind evaluation.

## How I work

```text
real problem → explicit evidence contract → smallest useful workflow
→ tests and adversarial review → documented limits → next iteration
```

I care about the boundary between a convincing AI demo and a system people can responsibly use: provenance, failure handling, evaluation, human judgment, and clear ownership of AI-assisted work.

### ✨ What I'm exploring

- AI-native products: from a real need to a testable MVP
- Agents and automation for research, operations, and everyday decision-making
- Reusable tools and methods shaped by entrepreneurial judgment and user empathy
- The ways AI is changing products, industries, and the opportunities available to small teams

### 🔍 Questions I care about

- Where can AI create meaningful leverage, and where does human judgment matter most?
- How do we move from an impressive demo to a product people genuinely rely on?
- How can small teams use AI to build with more clarity, care, and momentum?

### 🌱 What you'll find here

- AI-native product and workflow experiments
- Agent and automation practices
- Notes on entrepreneurship in the AI era
- Research, reflections, and reusable tools

> I believe AI’s value goes beyond improving efficiency. It can redefine how value is created—and enable more people to create it.

Based in Singapore · Open to AI Agent, AI product, and applied-AI opportunities.

---

## 中文

我是一名 AI 产品与应用实践者，关注如何把新技术转化为真正可用、可验证、可持续迭代的工作流与产品。

我的创业与业务实践经历，让我始终从真实问题出发：问题是否成立？用户会不会使用？流程能否跑通？一件事能否不再只靠某个人硬扛，而成为可以持续生长的系统？

现在，我正把这些经验带入 AI 时代，专注于构建**证据可追溯、决策可检查、边界可解释**的 AI Agent 与智能工作流，并在产品、研究与智能工作流的交汇处持续学习、构建与实验。

这里的项目不以“用了多少 Agent”为成果，而以可复现运行、测试、证据链、人工复核边界和对失败条件的说明作为验证。代表项目包括原料机会研究 Agent Skill、证据驱动项目评估 Agent、nanoGPT 可复现实验室，以及深度研究证据适配器。

### ✨ 我正在探索

- 从真实需求走向可验证 MVP 的 AI-native 产品
- 用 Agent 与自动化改善研究、运营和日常决策
- 将创业中的判断、用户视角与执行经验沉淀为可复用的方法和工具
- AI 如何改变产品、行业，以及小团队能够创造的机会

### 🔍 我关心的问题

- AI 在哪里能带来真正的杠杆，又在哪里最需要人的判断？
- 一个令人惊艳的 Demo，如何变成用户真正愿意依赖的产品？
- 小团队如何借助 AI，以更清晰、更从容的方式创造新业务？

### 🌱 这里会持续更新

- AI-native 产品与工作流实验
- Agent 与自动化实践
- AI 时代的创业思考
- 研究、复盘与可复用工具

> 我相信，AI 的价值不止在于提高效率，更在于可以重新定义价值创造的方式，并让更多人拥有创造价值的能力。
