# Version Relationship

This repository contains supporting research papers and an exploratory scenario corpus for the JEP / HJS / JAC protocol stack.

Current protocol version lines and public entry points are listed in the [repository README](../README.md#current-protocol-context).

## Sources and Their Roles

| Question                                 | Source to Consult                                                                              |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------- |
| What does a protocol version require?    | The applicable protocol specification and its referenced profiles and conformance requirements |
| What does an implementation actually do? | Its versioned source code, configuration, and test results                                     |
| What does a research paper claim?        | The specific paper edition, including its assumptions, proofs, limitations, and corrections    |
| What does the scenario corpus explore?   | The corpus records and the [Corpus Coding Guide](CORPUS-CODING-GUIDE.md)                       |

Implementation behavior does not automatically redefine protocol requirements. A discrepancy between code and the applicable specification should be investigated and resolved explicitly.

Research papers can motivate protocol design, but they do not replace normative specifications. Protocol adoption or implementation success does not by itself establish a paper's research hypotheses.

## Separate Version Systems

The following identifiers belong to different version systems:

* protocol release versions;
* individual Internet-Draft revision numbers;
* paper revision labels;
* Zenodo publication version numbers;
* repository commits and tags.

Matching numbers do not establish compatibility, and different numbers do not necessarily indicate a conflict.

For example, a paper labeled **Revision 01** may appear as **v2** on Zenodo. Check the document and publication metadata together.

## Paper Editions and Repository Copies

The [Papers section](../README.md#papers) links to specific revised editions.

PDFs stored in this repository may differ from those editions. Check the revision printed inside each document; the filename alone does not establish its version.

When citing a paper, identify the edition actually used and its version-specific DOI. Preserve historical citations when they refer to claims or events from an earlier edition.

## Historical Materials

Earlier protocol terminology, version references, and exploratory descriptions remain part of the research history.

Their presence does not establish compatibility with a current implementation or specification. Any compatibility claim should identify the relevant versions and the checks performed.

## Corpus and Conformance

The scenario corpus is exploratory research material. It is not a protocol conformance suite and does not establish primitive minimality or universal expressive coverage.

For conformance artifacts, use the resources linked in the [README](../README.md#relationship-to-conformance) and check their scope against the protocol version being evaluated.

Passing a particular test suite establishes only the results of the checks it performs.

