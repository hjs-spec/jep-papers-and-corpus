---
language: en
license: apache-2.0
tags:
  - ai-governance
  - accountability
  - protocol
  - jep
  - hjs
  - jac
  - coe
pretty_name: JEP Papers and Evaluation Corpus
---

# JEP Papers and Evaluation Corpus

Research papers and evaluation materials for the JEP/HJS/JAC/COE accountability framework.

## Papers

| 论文 | 文件 | 定位 |
|------|------|------|
| **A Theory of Target-Fact Determinability in Finite Causal Event Systems** | `causal-observability-paper.pdf` | 数学基础层 |
| **Judgment, Delegation, Termination, Verification: A Minimal Grammar for AI Accountability** | `four-primitives-paper.pdf` | 协议架构层 (JEP) |
| **HJS: An Accountability Layer for AI Agents (v0.4)** | `draft-wang-hjs-accountability-04.pdf` | 记录隐私层 (前身) |
| **JAC: Judgment Accountability Chain** | `draft-wang-jac-01.pdf` | 因果链层 |
| **COE: Cognition-Oriented Emergence** | `draft-wang-coe-00.pdf` | 认知共识层 |

## Evaluation Corpus

`jep_scenario_corpus_v01.json` — 24 scenario units (92 event points) for expressive adequacy testing.

**Coverage**:
- Agent-assisted research (6 scenarios)
- Multi-agent task execution (6 scenarios)
- Agent-mediated customer support (4 scenarios)
- Agent-based procurement (4 scenarios)
- Human-supervised autonomous operations (4 scenarios)

**Coding Target**:
- Coverage rate &gt; 90%
- Residual Other &lt; 10%
- Intercoder agreement (Cohen's kappa) ≥ 0.75

## Interactive Implementations

- [causal-observability-demo](https://huggingface.co/spaces/cognitiveemergencelab/causal-observability-demo) — 数学检验器
- [jep-spec](https://huggingface.co/spaces/cognitiveemergencelab/jep-spec) — 协议编码器
- [hjs-archive](https://huggingface.co/spaces/cognitiveemergencelab/hjs-archive) — 历史参考实现
- [jac-core-demo](https://huggingface.co/spaces/cognitiveemergencelab/jac-core-demo) — 因果链演示
- [coe-core-demo](https://huggingface.co/spaces/cognitiveemergencelab/coe-core-demo) — 共识引擎

## License

Apache-2.0

## Author

Cognitive Emergence Lab / Human Judgment Systems Foundation