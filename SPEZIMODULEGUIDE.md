<!--

This source file is part of the Stanford Spezi open-source project

SPDX-FileCopyrightText: 2022 Stanford University and the project authors (see CONTRIBUTORS.md)

SPDX-License-Identifier: MIT

-->

# Spezi Module Guide

This document defines the requirements for a Spezi Module and hints and examples on how to best structure your Spezi Module.
The keywords "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

To be featured by the Spezi team, a module MUST conform to this guide.
The definitive endorsement or feature of a Spezi module is determined by the Spezi core team.
A package SHOULD be submitted for consideration by sharing it in the [Show & Tell section of the Stanford Spezi Discussions forum](https://github.com/orgs/StanfordSpezi/discussions/categories/show-and-tell).

The module MUST conform to this guide within two months after changes have been published to be considered in conformance with this guide.

Check out the [Swift Package Template](https://github.com/StanfordBDHG/SwiftPackageTemplate) as an example of a repository meeting the requirements of this document, including a continuous integration (CI) setup using [GitHub Actions](https://github.com/features/actions).


## Repository Setup

A Spezi module MUST be in full conformance to the GitHub Community Standards, checked by the insights tab of your repository, e.g., the [Spezi Community Standards Insights](https://github.com/StanfordSpezi/Spezi/community).
Feel free to link and use the Spezi community guidelines and other community standards of Spezi. P
lease ensure you reference and credit the Spezi team if you reuse any setup.
You can learn more about open-source best practices at the [Open Source Guides page](https://opensource.guide).

The repository MUST follow the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) with automated safeguards before merging the code as defined in the sections below.

The Spezi module MUST use [semantic versioning](https://semver.org) and MUST have an initial version tagged using [GitHub releases](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases).

The repository MUST use a comprehensive `.gitignore` file at the root of the repo to ignore files that should not be committed in the repo, e.g., [shown in the Spezi repository]( https://github.com/StanfordSpezi/Spezi/blob/main/.gitignore).

It is RECOMMENDED to use a `CONTRIBUTORS.md` file at the root of the repo to list the contributors to the Spezi module, e.g., [shown in the Spezi repository](https://github.com/StanfordSpezi/Spezi/blob/main/CONTRIBUTORS.md).
It is RECOMMENDED to use a `CITATION.cff` file at the root of the repo to make it [possible to cite the repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files), e.g., [shown in the Spezi repository](https://github.com/StanfordSpezi/Spezi/blob/main/CITATION.cff).
It is RECOMMENDED to use a tool to automatically generate digital object identifiers (DOIs) to release, e.g., using [zenodo.org](https://zenodo.org).


## Spezi Usage

A Spezi module MUST support the latest major Spezi version within two months after the release.
The module MUST use Spezi built-in features and integrate into the ecosystem of modules in the [Stanford Spezi GitHub organization](https://github.com/StanfordSpezi).
It is RECOMMENDED to contribute features to existing Spezi modules if they fit within the feature scope rather than creating a new module.

Different distinct functionalities under the umbrella of a Spezi module SHOULD be separated out into different targets.


## License & Open Source

The module MUST use an [open-source license](https://choosealicense.com).
It SHOULD use the [MIT license](https://choosealicense.com/licenses/mit/).

The repository MUST conform to the [REUSE specification](https://reuse.software/spec/).
The conformance MUST be automatically checked in accordance to automated checks in the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) in a pull request (PR) and on the main branch.
This can be done, e.g., using the [REUSE tool](https://github.com/fsfe/reuse-tool) and the [Stanford BDHG REUSE reusable workflow](https://github.com/StanfordBDHG/.github#reuse).

It is RECOMMENDED to copy the license in, e.g., a `LICENSE.md` file to the root of the repo to ensure that [GitHub can detect the license](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).

The repository SHOULD accept outside contributions and SHOULD review, accept, or decline PRs and issues in a timely manner.
Stale projects MAY not be considered in conformance with the Spezi module guidelines.


## Code Style

The Spezi module MUST have a comprehensive and detailed style guide defined by a configuration file and tool.
It is RECOMMENDED to use [swiftlint](https://github.com/realm/SwiftLint) for Swift-related code style checks.

It is RECOMMENDED using the [Stanford Spezi swiftlint configuration](https://github.com/StanfordSpezi/Spezi/blob/main/.swiftlint.yml).
Changes to the configuration MAY be possible and are judged by the Spezi core team. 

The code MUST conform to the defined code style.
The conformance MUST be automatically checked in accordance with automated checks in the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) in a pull request (PR) and on the main branch.
This can be done, e.g., using [swiftlint](https://github.com/realm/SwiftLint), the [Stanford BDHG SwiftLint GitHub Action](https://github.com/marketplace/actions/swiftlint-tool), and/or the [Stanford BDHG REUSE reusable workflow](https://github.com/StanfordBDHG/.github#reuse).


## Testing

The Spezi module MUST incorporate an automated testing setup, including unit tests and user interface (UI) tests if applicable.

The project code coverage MUST be automatically reported, e.g., using a tool like [codecov.io](https://about.codecov.io).
The project MUST have a code coverage of at least 70% of the lines of code, excluding tests and examples.
It is RECOMMENDED that at least 80% of the lines of code are covered using automated tests.

The conformance MUST be automatically checked in accordance with automated checks in the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) in a pull request (PR) and on the main branch.
It is RECOMMENDED using [GitHub Actions](https://github.com/features/actions) and [codecov.io](https://about.codecov.io).
The [Stanford BDHG Test Using Xcodebuild or Run Fastlane reusable workflow](https://github.com/StanfordBDHG/.github#test-using-xcodebuild-or-run-fastlane) and [Stanford BDHG Merge and Upload Coverage Report reusable workflow](https://github.com/StanfordBDHG/.github#merge-and-upload-coverage-report) MAY be used to automate your setup..


## Documentation

A module MUST conform to the [Spezi Documentation Guide](https://github.com/StanfordSpezi/.github/blob/main/DOCUMENTATIONGUIDE.md).
The documentation MUST be hosted and accessible based on the content of the repository.
It is RECOMMENDED using the [Swift Package Index](https://swiftpackageindex.com).
It is RECOMMENDED to use a `.spi.yml` file at the root of the repo to [configure the Swift Package Index setup](https://blog.swiftpackageindex.com/posts/the-swift-package-index-metadata-file-first-steps/) e.g., [shown in the Spezi repository](https://github.com/StanfordSpezi/Spezi/blob/main/.spi.yml).
