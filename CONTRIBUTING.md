<!--

This source file is part of the Stanford Spezi open-source project

SPDX-FileCopyrightText: 2022 Stanford University and the project authors (see CONTRIBUTORS.md)

SPDX-License-Identifier: MIT

-->

# Contributing Guidelines

Thank you for contributing to the Stanford Spezi open-source project! We value the time and effort you invest in the open-source project!

The keywords "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

We REQUIRED using [GitHub Discussions](https://docs.github.com/en/discussions) at [https://github.com/orgs/StanfordSpezi/discussions](https://github.com/orgs/StanfordSpezi/discussions) for any discussions about the project.
You MUST follow our [Code of Conduct](https://github.com/StanfordSpezi/.github/blob/main/CODE_OF_CONDUCT.md).

We REQUIRED using the [Github Flow](https://guides.github.com/introduction/flow/index.html) for all code-related contributions.
GitHub discussions SHALL be the best way to brainstorm your suggestions. 
GitHub issues SHALL be the best way to document decisions or bugs.
Pull requests SHALL be the best way to propose changes to the codebase.

## GitHub Account & Commit Signing

Each contribution to a Spezi repository REQUIRES [a GitHub account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).
We RECOMMEND to [add your full name](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/personalizing-your-profile#changing-your-profile-name), [a representative profile picture](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/personalizing-your-profile#changing-your-profile-picture), and [your preferred pronoums](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/personalizing-your-profile#adding-pronouns-to-your-profile) to your GitHub Account to make it easier to address you and recognize you across commits.

In addition, all commits to Spezi repositories MUST be signed.
[You can learn more about commit signature verification and how to set it up in the GitHub documentation.](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification).

> [!IMPORTANT]  
> Be sure to set up commit signature verification **before** you make your first commit to a Stanford Spezi repository or a fork you plan to use to contribute to a Stanford Spezi repository.

## Your first contribution to a Spezi Project

Stanford Spezi consits of a wide varity of projets in different programming languages.
While many things are common to all the different programming languages and setups some specific subsystems require

### Swift-based Spezi Projects

Spezi has a great collection of Swift Package-based modules: https://swiftpackageindex.com/StanfordSpezi.

"Swift packages are reusable components of Swift, Objective-C, Objective-C++, C, or C++ code that developers can use in their projects." [Swift Packages - Apple Documentation]. Contributing to Spezi requires a fundamental understanding of the structure of a Swift Package. Please take a look at the Creating a standalone Swift package with Xcode article by Apple detailing the structure of a Swift Package. Each Spezi Module contains a Swift Package including the Package.swift file at the root of the repository.

You can open a Swift Package in Xcode by opening the Package.swift file with Xcode. All Swift Packages are localized (learn more at Localizing package resources - Apple Documentation) and some Packages bundle resources such as JSON files and images (Bundling resources with a Swift package - Apple Documentation).

All Spezi Modules contain a testing setup, it is essential to test all the functionality and run those tests during the development process. You can learn more about running tests in Xcode: Running tests and interpreting results - Apple Documentation.

All Spezi Modules that contain user interface elements contain a UI (user interface) test application that allows us to write UI test for the packages and test out user interfaces in a small example application. You can find it in the Tests/UITests folder and we recommend to work in this project when developing on a Spezi package that contains a user interface.

## Documentation

Every new contribution MUST be properly documented.
All documentation MUST conform to our [Documentation Guide](https://swiftpackageindex.com/stanfordspezi/spezi/documentation/spezi/documentation-guide)

## Testing

Every new contribution MUST be properly tested and automatically verified using unit tests, user interface (UI) tests, and our continuous integration (CI) setup using GitHub Actions.

## Licensing

Your submissions MUST be published and conform to the license currently used in the respective repository.

## Attributions

We use the [REUSE Software Conventions](https://reuse.software) to structure our attributions and contributor lists.

Each file MUST contain the following header information with `Spezi` being replaced with the project name and [`MIT` with the SPDX License Identifier](https://spdx.org/ids).
```
This source file is part of the Stanford Spezi open-source project

SPDX-FileCopyrightText: 2022 Stanford University and the project authors (see CONTRIBUTORS.md)

SPDX-License-Identifier: MIT
```

As referenced in the copyright text, we list all contributors in the CONTRIBUTORS.md at the root of every repository.
Each contributor SHOULD add themselves to the CONTRIBUTORS.md in a pull request with a sizable and meaningful contribution to the project.
The addition and final decision to be added to the CONTRIBUTORS.md is up to the Spezi core team.

If your code is based on another source, you MUST add a reference to the original source code to the specific code (e.g., using a comment) and make sure that the license of the original source allows the usage under the license used in the project.

## Bug Reporting

We use GitHub issues to track work items. Report a bug SHALL be done by opening a new issue using the bug issue template.

## Support Policy

Please refer to our [Support Policy](https://github.com/StanfordSpezi/.github/blob/main/SUPPORT.md) for information about getting support. 

## Security Policy

For security and vulnerability-related issues, please refer to our [Support Policy](https://github.com/StanfordSpezi/.github/blob/main/SUPPORT.md).
