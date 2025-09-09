<!--

This source file is part of the Stanford Spezi open-source project

SPDX-FileCopyrightText: 2022 Stanford University and the project authors (see CONTRIBUTORS.md)

SPDX-License-Identifier: MIT

-->

### Stanford Spezi

[Spezi](https://github.com/StanfordSpezi/Spezi) is an open-source framework for rapid development of modern, interoperable digital health applications. It is built on an ecosystem of modules that exchange data using health standards such as HL7® FHIR®.

> [!NOTE]  
> Stanford Spezi can be used to build mobile applications (iOS and Android), web services to store health data and interface with electronic health records, and web frontend applications. All use a common set of modules to simplify software development and improve reusability across systems.

The following modules provide an overview of patient- and user-facing functionalities that can be implemented with Spezi to support research studies, electronic health record integration, and artificial intelligence–enabled systems:

<table style="width: 80%">
  <tr>
    <td align="center" width="33.33333%">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziConsent/main/Sources/SpeziConsent/SpeziConsent.docc/Resources/Consent1.png#gh-light-mode-only" alt="Screenshot displaying the UI of the consent module" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziConsent/main/Sources/SpeziConsent/SpeziConsent.docc/Resources/Consent1~dark.png#gh-dark-mode-only" alt="Screenshot displaying the UI of the consent module" width="80%"/>
    </td>
    <td align="center" width="33.33333%">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziDevices/main/Sources/SpeziDevicesUI/SpeziDevicesUI.docc/Resources/PairedDevices.png#gh-light-mode-only" alt="Screenshot displaying Spezi Devices and Bluetooth pairing user interface" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziDevices/main/Sources/SpeziDevicesUI/SpeziDevicesUI.docc/Resources/PairedDevices~dark.png#gh-dark-mode-only" alt="Screenshot displaying Spezi Devices and Bluetooth pairing user interface" width="80%"/>
    </td>
    <td align="center" width="33.33333%">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziQuestionnaire/main/Sources/SpeziQuestionnaire/SpeziQuestionnaire.docc/Resources/Overview.png#gh-light-mode-only" alt="Screenshot displaying the UI of the questionnaire module" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziQuestionnaire/main/Sources/SpeziQuestionnaire/SpeziQuestionnaire.docc/Resources/Overview~dark.png#gh-dark-mode-only" alt="Screenshot displaying the UI of the questionnaire module" width="80%"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziOnboarding">
        <code>Spezi Onboarding</code>
      </a> and
      <a href="https://github.com/StanfordSpezi/SpeziConsent">
        <code>Spezi Consent</code>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziBluetooth">
        <code>Spezi Bluetooth</code>
      </a> and
      <a href="https://github.com/StanfordSpezi/SpeziDevices">
        <code>Spezi Devices</code>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziQuestionnaire">
        <code>Spezi Questionnaire</code>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziAccount/main/Sources/SpeziAccount/SpeziAccount.docc/Resources/AccountSetup.png#gh-light-mode-only" alt="Screenshot displaying the account setup view with email and password prompt and Sign In with Apple button" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziAccount/main/Sources/SpeziAccount/SpeziAccount.docc/Resources/AccountSetup~dark.png#gh-dark-mode-only" alt="Screenshot displaying the account setup view with email and password prompt and Sign In with Apple button" width="80%"/>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziViews/main/Sources/SpeziValidation/SpeziValidation.docc/Resources/Validation.png#gh-light-mode-only" alt="Three different text fields showing validation errors with Spezi Validation" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziViews/main/Sources/SpeziValidation/SpeziValidation.docc/Resources/Validation~dark.png#gh-dark-mode-only" alt="Three different text fields showing validation errors with Spezi Validation" width="80%"/>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziLLM/main/Sources/SpeziLLMLocal/SpeziLLMLocal.docc/Resources/ChatView.png#gh-light-mode-only" alt="Chat view of a locally executed LLM using the Spezi LLM module" width="80%"/>
      <img src="https://raw.githubusercontent.com/StanfordSpezi/SpeziLLM/main/Sources/SpeziLLMLocal/SpeziLLMLocal.docc/Resources/ChatView~dark.png#gh-dark-mode-only" alt="Chat view of a locally executed LLM using the Spezi LLM module" width="80%"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziAccount">
        <code>Spezi Account</code>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziViews">
        <code>Spezi Views</code>
      </a>, including
      <a href="https://swiftpackageindex.com/StanfordSpezi/SpeziViews/documentation/spezivalidation">
        <code>SpeziValidation</code>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/StanfordSpezi/SpeziLLM">
        <code>Spezi LLM</code>
      </a>
    </td>
  </tr>
</table>

> [!NOTE]  
> The best way to get started with Spezi for mobile application development is by using the [Spezi Template Application](https://github.com/StanfordSpezi/SpeziTemplateApplication).  
> It integrates a wide range of modules and demonstrates their usage in a simple and extensible application.

We are always looking for open source collaborators. Please take a look at the [Code of Conduct](https://github.com/StanfordSpezi/.github/blob/main/CODE_OF_CONDUCT.md) and [Contributing Guidelines](https://github.com/StanfordSpezi/.github/blob/main/CONTRIBUTING.md) for more information.
For more information, check out our website at [spezi.stanford.edu](https://spezi.stanford.edu).


![Spezi Footer](https://raw.githubusercontent.com/StanfordSpezi/.github/main/assets/Footer.png#gh-light-mode-only)
![Spezi Footer](https://raw.githubusercontent.com/StanfordSpezi/.github/main/assets/Footer~dark.png#gh-dark-mode-only)
