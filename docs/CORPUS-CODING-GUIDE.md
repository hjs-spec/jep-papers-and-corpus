# Corpus Coding Guide

This guide describes how to interpret and annotate the exploratory JEP scenario corpus.

## Purpose

The corpus supports investigation of whether judgment-related situations can be represented using four candidate event primitives:

| Primitive | Meaning      |
| --------- | ------------ |
| J         | Judgment     |
| D         | Delegation   |
| T         | Termination  |
| V         | Verification |

The corpus is research material. Its annotations are not protocol events, conformance results, or evidence that the four primitives form a minimal or universally sufficient vocabulary.

## What Reviewers Examine

For each scenario, reviewers may examine:

* whether a judgment or decision-related commitment appears;
* whether bounded authority is delegated;
* whether termination, revocation, expiry, or withdrawal appears;
* whether an assessment or verification activity appears;
* which details can be represented using J/D/T/V;
* which details require additional context, application rules, or other representations;
* whether HJS evidence-lifecycle material or JAC declared dependencies may be relevant.

A scenario does not need to contain all four primitives. Reviewers should record ambiguous or unsuccessful mappings.

## Suggested Annotation Fields

The following are optional review fields, not a required corpus schema or a JEP event format.

| Field                   | What to Record                                                                           |
| ----------------------- | ---------------------------------------------------------------------------------------- |
| Scenario reference      | The identifier of the scenario reviewed                                                  |
| Candidate primitives    | The proposed J/D/T/V mapping                                                             |
| Supporting details      | The scenario text supporting each proposed mapping                                       |
| Uncertainty             | Missing information, ambiguity, or unresolved interpretation                             |
| Representation gaps     | Details the proposed mapping does not preserve                                           |
| Additional dependencies | Required application rules, authority information, evidence, or companion-layer concepts |
| Alternatives            | Simpler or competing representations, if examined                                        |
| Review status           | Proposed, disputed, revised, or unresolved                                               |

Distinguish information stated in the scenario from assumptions introduced by the reviewer.

## Three Separate Activities

### Semantic Annotation

Identify candidate judgment, delegation, termination, and verification activities in the scenario.

This records an interpretation of the scenario.

### Protocol Encoding

Construct concrete events against a specified protocol version, including required fields and relationships.

A semantic annotation alone does not establish that a valid encoding has been produced.

### Technical Validation

Check the encoded events using the applicable schemas, canonicalization rules, signature procedures, and conformance artifacts.

The exploratory corpus does not perform these checks merely by labeling a scenario.

## Interpretation Boundaries

A successful mapping supports only the claim that the reviewed scenario can be represented under the stated interpretation and encoding assumptions.

It does not by itself establish:

* universal expressive coverage;
* primitive minimality or uniqueness;
* signature or event-hash validity;
* implementation conformance;
* factual truth or causal correctness;
* valid authority or consent;
* legal liability or regulatory compliance.

Labeling an activity as Verification does not establish that its conclusion is correct. Recording Delegation or Termination does not itself enforce a grant, revocation, or physical action.

Expressive adequacy and minimality require separate evaluation, including explicit encoding rules, independently defined scenarios, representation gaps, and fair comparisons with alternatives.

## Related Guidance

* [Repository README](../README.md)
* [Version Relationship](VERSION-RELATIONSHIP.md)

