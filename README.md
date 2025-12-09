# SCA-XCheck: Benchmark & Assessment of Three Static Analysis Tools

**Under Construction**

This repository is home to SCA-XCheck. Within the framework we are soon to establish within the confines of this repository, we aim to assess three static analysis tools: CppCheck, Sparse and Clang-Tidy.

## Fairness

Our assessment is *fair* or in the least, it aims to be! We cast our net across the wild borough of this domain, with the following approach to the concept of 'fairness':

- Contextual Evaluation: We won't just evaluate tools in 'one' context. One tool might be better at analysis of an OS kernel, whilst another could excel at CI/CD integration.
- Charitable Configuration: We'll make sure how we configure the tool reflects the intended use case.
- Scope-Appropriate Testing: Test cases are tagged with applicability metadata. If a test requires C++ support, and the tool is not all that well-funded in analysis of C++, we'll make note of it.
- Transparent Limitations: Every limit imposed by a tool shall be documented.

## Rigor

We'll follow a certain *rigor* in our assessment.

- Systematicity: We'll make sure we document every step of the test.
- Statistical Validity: We'll follow statistical sciences in our test.
- Seeking the Threat: We'll look for *specifically* dangerous code!

## Reproducibility

We need to be able to reproduce our claims, so:

- Version Catalogue: We'll catalogue the exact version of the tool we used.
- Environment Specifity: We'll note down our environment in which we executed the test.
- Automation: We'll make sure most of our toolchain automatically executes the test.
- Available Data: We'll collect from available data, for example, open-source codebases.




