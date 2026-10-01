# JEP Papers and Scenario Corpus

Read research on verifiable event records and target determinability, or explore
the scenario corpus.

This repository is **supporting research material**. It is not the normative JEP specification, not the JEP conformance suite, and not an implementation repository.

---

## Current Protocol Context

Current protocol requirements and runnable entry points are maintained centrally:

| Need | Source |
|---|---|
| Core specification, profiles and conformance | [JEP Core](https://github.com/hjs-spec/jep-core) — current Core 0.7 |
| Verify a signed sample | [Packaged Core example](https://github.com/hjs-spec/jep-core#verify-your-first-event) |
| Implementation and delivery status | [Repository directory](https://github.com/hjs-spec/.github/blob/main/PROJECTS.md) |

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

For implementation tests, use [Core’s BYOI guide](https://github.com/hjs-spec/jep-core/blob/main/docs/BYOI-CONFORMANCE.md).
For paper editions and source precedence, see [Version Relationship](docs/VERSION-RELATIONSHIP.md).

---

## Boundary Statement

The corpus explores expressive coverage. It does not establish protocol correctness,
implementation conformance, factual causality or legal conclusions. Paper claims
remain subject to the assumptions and evidence of the cited edition.

---

## Suggested Citation

```text
JEP Papers and Scenario Corpus, hjs-spec, research papers and exploratory scenario data.
```

When citing an individual paper, use the authors, title, and version-specific DOI from its publication record.

---

## License and Legal Notice

Internet-Draft documents, if quoted or excerpted, are governed by the IETF Trust Legal Provisions and BCP 78 / BCP 79.

Research papers, corpus data, examples, and supporting files are provided under the license stated in this repository.

See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for additional notes.
