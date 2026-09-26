# JEP Papers and Scenario Corpus

Research papers and an exploratory scenario corpus for the JEP / HJS / JAC protocol stack.

This repository is **supporting research material**. It is not the normative JEP specification, not the JEP conformance suite, and not an implementation repository.

---

## Current Protocol Context

Current protocol requirements and runnable entry points are maintained centrally:

| Need | Source |
|---|---|
| Core specification, profiles and conformance | [JEP Core](https://github.com/hjs-spec/jep-core) — current Core 0.7 |
| Runnable example | [Quickstart](https://github.com/hjs-spec/jep-quickstart) |
| Implementation and delivery status | [Repository directory](https://github.com/hjs-spec/.github/blob/main/PROJECTS.md) |
| Archive/evidence companion | [HJS public draft](https://datatracker.ietf.org/doc/draft-wang-hjs-accountability/) |
| Declared dependency companion | [JAC public draft](https://datatracker.ietf.org/doc/draft-wang-jac/) |

Paper editions and corpus records retain their original version context. The older [0.6 demo](https://huggingface.co/spaces/yuqiangJEP/jep-v06-spec-demo/tree/main) and [0.6 dataset](https://huggingface.co/datasets/yuqiangJEP/jep-v06-conformance-suite) are historical resources, not the current Core 0.7 conformance entry.

---

## Repository Role

This repository contains:

* research papers related to judgment events, accountability receipts, and causal observability;
* an exploratory scenario corpus for evaluating J/D/T/V primitive coverage;
* supporting documentation for corpus interpretation and version relationships.

This repository does **not** define:

* JEP-Core semantics;
* HJS receipt semantics;
* JAC chain semantics;
* conformance requirements;
* legal liability;
* factual truth;
* governance or regulatory conclusions.

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

### Target Determinability under Partial Causal Observation

**A Faithful Reduction Framework — Revision 01**

Studies when available observations determine a target and what additional information is needed to resolve target-relevant ambiguity.

[Read Revision 01 on Zenodo](https://zenodo.org/records/22673663)

[Repository PDF](papers/causal-observability-paper.pdf)

### Judgment, Delegation, Termination, Verification

**Toward a Minimal Accountability Grammar for Human-AI Agent Decision Chains — Revision 01**

Proposes a candidate vocabulary for recording judgment, delegation, termination, and verification events. Expressive adequacy and conditional minimality remain research hypotheses.

Recording authorization or termination does not itself enforce the corresponding action. Verification establishes the results of specified checks, not external truth or legal liability.

[Read Revision 01 on Zenodo](https://zenodo.org/records/22716894)

[Repository PDF](papers/four-primitives-paper.pdf)

### Version Guidance

The Zenodo links above identify specific revised editions. Repository PDF filenames do not establish their revision; check the version printed inside each document before citing it.

These papers provide research context. Current protocol requirements are defined by the normative drafts linked above.

---

## Scenario Corpus

[Browse the scenario corpus](corpus/jep_scenario_corpus_v01.json)

The corpus is an exploratory scenario set for evaluating whether J/D/T/V primitives can describe common decision, delegation, verification, termination, and accountability situations.

Current corpus status:

```text
24 scenarios
exploratory
non-normative
not a conformance suite
```

For interpretation guidance, see the [Corpus Coding Guide](docs/CORPUS-CODING-GUIDE.md).

---

## Relationship to Conformance

This repository is **not** the official conformance suite.

Use [Core's current conformance entry](https://github.com/hjs-spec/jep-core#validate-locally) for versioned schemas, signed/invalid vectors, canonicalization fixtures and validation metadata. The separate [0.6 dataset](https://huggingface.co/datasets/yuqiangJEP/jep-v06-conformance-suite) remains historical.

Use this repository for:

* research background;
* scenario analysis;
* primitive coverage exploration;
* conceptual evaluation.

For historical context and source precedence, see [Version Relationship](docs/VERSION-RELATIONSHIP.md).

---

## Boundary Statement

A scenario corpus can help evaluate expressive coverage.

It does not prove:

* protocol correctness;
* implementation conformance;
* legal responsibility;
* factual causality;
* regulatory compliance;
* complete-log availability.

A paper can motivate architecture.

It does not replace the normative protocol drafts.

---

## Suggested Citation

```text
JEP Papers and Scenario Corpus, hjs-spec, research supporting material for the JEP / HJS / JAC protocol stack.
```

When citing an individual paper, use the authors, title, and version-specific DOI from its publication record.

---

## License and Legal Notice

Internet-Draft documents, if quoted or excerpted, are governed by the IETF Trust Legal Provisions and BCP 78 / BCP 79.

Research papers, corpus data, examples, and supporting files are provided under the license stated in this repository.

See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for additional notes.
