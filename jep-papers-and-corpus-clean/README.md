# JEP Papers and Scenario Corpus

Research papers and an exploratory scenario corpus for the JEP / HJS / JAC protocol stack.

This repository is **supporting research material**. It is not the normative JEP specification, not the JEP conformance suite, and not an implementation repository.

---

## Current Protocol Context

Current public version line:

| Layer | Current Version | Repository |
|---|---|---|
| JEP | v0.6 | https://github.com/hjs-spec/jep-v06 |
| JEP API | v0.6 | https://github.com/hjs-spec/jep-api |
| HJS | v0.5 | https://github.com/hjs-spec/hjs-05 |
| JAC | v0.5 | https://github.com/hjs-spec/jac-agent-02 |

Public drafts:

- JEP-Core: https://datatracker.ietf.org/doc/draft-wang-jep-judgment-event-protocol/
- JEP-Profiles: https://datatracker.ietf.org/doc/draft-wang-jep-profiles/
- JEP-Conformance: https://datatracker.ietf.org/doc/draft-wang-jep-conformance/
- HJS: https://datatracker.ietf.org/doc/draft-wang-hjs-accountability/
- JAC: https://datatracker.ietf.org/doc/draft-wang-jac/

Public resources:

- JEP v0.6 Spec Demo: https://huggingface.co/spaces/yuqiangJEP/jep-v06-spec-demo/tree/main
- JEP v0.6 Conformance Suite: https://huggingface.co/datasets/yuqiangJEP/jep-v06-conformance-suite

---

## Repository Role

This repository contains:

- research papers related to judgment events, accountability receipts, and causal observability;
- an exploratory scenario corpus for evaluating J/D/T/V primitive coverage;
- supporting documentation for corpus interpretation and version relationships.

This repository does **not** define:

- JEP-Core semantics;
- HJS receipt semantics;
- JAC chain semantics;
- conformance requirements;
- legal liability;
- factual truth;
- governance or regulatory conclusions.

---

## Contents

```text
papers/
  causal-observability-paper.pdf
  four-primitives-paper.pdf

corpus/
  jep_scenario_corpus_v01.json

docs/
  CORPUS-CODING-GUIDE.md
  VERSION-RELATIONSHIP.md

LICENSE
NOTICE.md
README.md
```

---

## Papers

### Causal Observability Paper

```text
papers/causal-observability-paper.pdf
```

Explores how declared dependency structures, observability limits, and event chains relate to accountability infrastructure.

### Four Primitives Paper

```text
papers/four-primitives-paper.pdf
```

Explores the four-event primitive model around Judgment, Delegation, Termination, and Verification.

---

## Scenario Corpus

```text
corpus/jep_scenario_corpus_v01.json
```

The corpus is an exploratory scenario set for evaluating whether J/D/T/V primitives can describe common decision, delegation, verification, termination, and accountability situations.

Current corpus status:

```text
24 scenarios
exploratory
non-normative
not a conformance suite
```

For interpretation guidance, see:

```text
docs/CORPUS-CODING-GUIDE.md
```

---

## Relationship to Conformance

This repository is **not** the official conformance suite.

The public JEP v0.6 conformance dataset is maintained here:

https://huggingface.co/datasets/yuqiangJEP/jep-v06-conformance-suite

Use that dataset for:

- schemas;
- signed vectors;
- invalid cases;
- canonicalization fixtures;
- profile examples;
- validation metadata.

Use this repository for:

- research background;
- scenario analysis;
- primitive coverage exploration;
- conceptual evaluation.

---

## Boundary Statement

A scenario corpus can help evaluate expressive coverage.

It does not prove:

- protocol correctness;
- implementation conformance;
- legal responsibility;
- factual causality;
- regulatory compliance;
- complete-log availability.

A paper can motivate architecture.

It does not replace the normative protocol drafts.

---

## Suggested Citation

```text
JEP Papers and Scenario Corpus, hjs-spec, research supporting material for the JEP / HJS / JAC protocol stack.
```

---

## License and Legal Notice

Internet-Draft documents, if quoted or excerpted, are governed by the IETF Trust Legal Provisions and BCP 78 / BCP 79.

Research papers, corpus data, examples, and supporting files are provided under the license stated in this repository.

See `NOTICE.md` for additional notes.
