# Welcome to the swiyu Public Beta Trust Infrastructure ecosystem

![github-banner](https://github.com/swiyu-admin-ch/swiyu-admin-ch.github.io/blob/main/assets/images/github-banner.jpg)

## Introduction

The Federal Act on Electronic Identity and Other Electronic Credentials (BGEID) that was adopted by the Council of States and the National Council on December 20th 2024 sets the foundation for the establishment of the Swiss Trust Infrastructure.  

The Swiss Trust Infrastructure based on the BGEID ensures that data handling and storage comply with strict legal safeguards like data minimization and decentralization. Citizens have been actively engaged throughout the project, with significant input from stakeholders across civil society, government, and industry to ensure the Swiss Trust Infrastructure is taking expectations from the public into account. The system design prioritizes privacy, user autonomy, and accessibility to garner widespread support and adoption. As one aspect of the Swiss Trust Infrastructure, it will provide a secure, state-recognized digital identity, the e-ID that fosters public confidence while aligning with Switzerland’s democratic values and participatory decision-making process.

The BGEID aims to address foundational identity and trust needs for public and private services in Switzerland with an approach that is built around the model of an Identity Wallet App (e.g. the federally provided swiyu wallet) where other means of identification and authentication can also be stored, managed and utilized. The Swiss Trust Infrastructure is thus going beyond the provisioning of the e-ID alone. Next to the provision of an e-ID for all Swiss nationals, inhabitants and residents, the initiative provides a Trust Infrastructure to enable an ecosystem for both the public and private sector. The [e-iD website](https://www.eid.admin.ch/en) contains more general information as well as an introduction to [Public Beta](https://www.eid.admin.ch/en/public-beta-e) for private individuals, issuers and verifiers.

## Public Beta

The Public Beta environment is designed to test and refine the e-ID technology stack. Participants will be able to explore and experiment with various components, including:

- **swiyu Base Registry**: Entities can onboard, update, or offboard as issuers and verifiers within the ecosystem. The base registry will manage the public keys as part of the diddoc required for ecosystem interactions. Status lists containing information related to credential validity can be managed. 

- **swiyu Trust Registry**: Entities can prove and maintain their status as verified issuers or verifiers, ensuring additional trust within the ecosystem. Users will be able to see the verification status of issuers and verifiers in their wallets and verifiers are able to validate the trust-status of the issuers.

- **swiyu Generic Issuer**: Entities can issue, revoke, suspend, and reactivate Verifiable Credentials (VCs), using the generic reference issuer implementation provided by the federal government. Please ensure to follow the specifications.

- **swiyu Generic Verifier**: Entities can integrate the reference verifier implementation to verify VCs, ensuring cryptographic integrity and validity according to their specific needs.

- **swiyu App**: Users will be able to download the swiyu Public Beta wallet, request Beta-ID credentials for testing purpose, manage their VCs and interact with the ecosystem.

## Technical documentation and specifications

All the technical documentations are published on the [swiyu technical documentation website](https://swiyu-admin-ch.github.io/). There you find an overview of our [technology stack](https://swiyu-admin-ch.github.io/technology-stack/) and the [specifications](https://swiyu-admin-ch.github.io/specifications/) how the different standards have to be implemented. For issuers and verifiers we created so called [cookbooks](https://swiyu-admin-ch.github.io/cookbooks/) - these are step-by-step instructions on how to onboard to the base- and trust-registry, how to set up a verifiable credential, and other use cases.

## Open Source & Community

Public Beta is a critical milestone on the path to the final e-ID and its trust infrastructure, laying the groundwork for the productive environments that will follow. We welcome contributions from the community in a variety of forms. You'll find the code of the apps, services, and libraries in the different [repositories](https://github.com/orgs/swiyu-admin-ch/repositories). Please refer to CONTRIBUTING.md in the respective repository for further information.

We make the [presentations from the participation meetings](https://github.com/swiyu-admin-ch/community/tree/main/meetings/) available to the interested community and provide a space for [discussions on topics such as technology and governance](https://github.com/orgs/swiyu-admin-ch/discussions).   

