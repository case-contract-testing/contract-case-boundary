# @contract-case/case-boundary

[![Build and test](https://github.com/case-contract-testing/contract-case-boundary/actions/workflows/build-and-test.yml/badge.svg?branch=main)](https://github.com/case-contract-testing/contract-case-boundary/actions/workflows/build-and-test.yml)
[![Known Vulnerabilities](https://snyk.io/test/github/case-contract-testing/contract-case-boundary/badge.svg?targetFile=package.json)](https://snyk.io/test/github/case-contract-testing/contract-case-boundary?targetFile=package.json)
[![npm](https://img.shields.io/npm/v/@contract-case/case-boundary.svg?label=case-boundary%3A%20npm)](https://www.npmjs.com/package/@contract-case/case-boundary)
![Maven Central](https://img.shields.io/maven-central/v/io.contract-testing.contractcase/case_boundary?label=case_boundary%3A%20maven)

This is the [JSii](https://aws.github.io/jsii/user-guides/lib-author/toolchain/jsii/) layer that is part of the exported interface for ContractCase.

However, because of [a bug preventing servers from running](https://github.com/aws/jsii/issues/4133), communication with wrapper libraries is provided by @contract-case/case-connector instead.

* If you're looking looking to use ContractCase for testing, use one of the DSL packages - [start here](https://case.contract-testing.io/docs/intro).
* If you're writing a wrapper for ContractCase in a new language, use [@contract-case/case-connector](https://www.npmjs.com/package/@contract-case/case-connector).
* Use this package directly ONLY if you are writing a VERY custom wrapper for ContractCase. Feel free to open an issue to discuss your use case.

# Why isn't this in the monorepo? 

Case-Boundary is extracted from the monorepo because of [an npm bug](https://github.com/npm/cli/issues/3466) that causes JSii to be [unable to include bundled packages in a monorepo](https://github.com/aws/jsii/issues/4132).


