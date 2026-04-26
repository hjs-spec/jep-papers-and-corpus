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

| Paper | File | Positioning |
|-------|------|-------------|
| **A Theory of Target-Fact Determinability in Finite Causal Event Systems** | `causal-observability-paper.pdf` | Mathematical Foundation Layer |
| **Judgment, Delegation, Termination, Verification: A Minimal Grammar for AI Accountability** | `four-primitives-paper.pdf` | Protocol Architecture Layer (JEP) |
| **HJS: An Accountability Layer for AI Agents (v0.4)** | `draft-wang-hjs-accountability-04.pdf` | Record & Privacy Layer (Predecessor) |
| **JAC: Judgment Accountability Chain** | `draft-wang-jac-01.pdf` | Causality Chain Layer |
| **COE: Cognition-Oriented Emergence** | `draft-wang-coe-00.pdf` | Cognitive Consensus Layer |

## Evaluation Corpus

`jep_scenario_corpus_v01.json` — 24 scenario units (92 event points) for expressive adequacy testing.

**Coverage**:
- Agent-assisted research (6 scenarios)
- Multi-agent task execution (6 scenarios)
- Agent-mediated customer support (4 scenarios)
- Agent-based procurement (4 scenarios)
- Human-supervised autonomous operations (4 scenarios)

**Coding Target**:
- Coverage rate > 90%
- Residual Other < 10%
- Intercoder agreement (Cohen's kappa) ≥ 0.75

## Interactive Implementations

- [causal-observability-demo](https://huggingface.co/spaces/cognitiveemergencelab/causal-observability-demo) — Mathematical Inspector
- [jep-spec](https://huggingface.co/spaces/cognitiveemergencelab/jep-spec) — Protocol Encoder
- [hjs-archive](https://huggingface.co/spaces/cognitiveemergencelab/hjs-archive) — Historical Reference Implementation
- [jac-core-demo](https://huggingface.co/spaces/cognitiveemergencelab/jac-core-demo) — Causality Chain Demo
- [coe-core-demo](https://huggingface.co/spaces/cognitiveemergencelab/coe-core-demo) — Consensus Engine

## License

Apache-2.0

## Author

Cognitive Emergence Lab / Human Judgment Systems Foundation
