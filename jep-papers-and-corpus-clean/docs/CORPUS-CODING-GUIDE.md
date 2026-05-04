# Corpus Coding Guide

This guide describes how to interpret the exploratory JEP scenario corpus.

## Purpose

The corpus is designed to test whether the four JEP primitives can describe a broad range of judgment-related situations.

The four primitives are:

| Primitive | Meaning |
|---|---|
| J | Judgment |
| D | Delegation |
| T | Termination |
| V | Verification |

## What the Corpus Tests

The corpus can be used to explore:

- whether a scenario contains a judgment act;
- whether authority or task delegation appears;
- whether termination, revocation, expiry, or withdrawal appears;
- whether verification appears;
- whether events can be decomposed into J/D/T/V structures;
- whether HJS receipt or evidence-lifecycle material may be relevant;
- whether JAC declared dependency chains may be relevant.

## What the Corpus Does Not Test

The corpus does not test:

- signature validity;
- JSON Schema validity;
- JCS canonicalization;
- detached JWS behavior;
- event hash correctness;
- implementation conformance;
- legal liability;
- factual truth;
- regulatory compliance.

## Suggested Coding Fields

For each scenario, reviewers may optionally annotate:

```json
{
  "scenario_id": "S001",
  "contains_judgment": true,
  "contains_delegation": true,
  "contains_termination": false,
  "contains_verification": true,
  "primary_primitives": ["D", "J", "V"],
  "possible_hjs_objects": ["behavior-record", "receipt-manifest"],
  "possible_jac_edges": ["delegated-from", "verified-by"],
  "notes": "Exploratory annotation only."
}
```

## Interpretation Rule

A scenario being expressible in J/D/T/V terms does not prove that JEP determines legal or factual outcomes.

It only indicates that the scenario may be represented as a sequence of signed judgment-related events.
