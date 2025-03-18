<p align="center">
  <h1 align="center">
    <picture>
      <!-- Replace with your own logo if available -->
      <img width="250" alt="My Privacy Protocol icon" src="https://raw.githubusercontent.com/myusername/myproject/main/assets/my-logo.svg">
    </picture>
  </h1>
  <p>Created by Advaita, Rahul, Anushka</p>
</p>

<p align="center">
  <a href="https://github.com/myusername/myproject" target="_blank">
    <img src="https://img.shields.io/badge/project-MyPrivacyProtocol-blue.svg?style=flat-square">
  </a>
  <a href="/LICENSE">
    <img alt="GitHub license" src="https://img.shields.io/github/license/myusername/myproject.svg?style=flat-square">
  </a>
  <a href="https://github.com/myusername/myproject/actions?query=workflow%3Aproduction">
    <img alt="GitHub Workflow test" src="https://img.shields.io/github/actions/workflow/status/myusername/myproject/production.yml?branch=main&label=test&style=flat-square&logo=github">
  </a>
  <a href="https://coveralls.io/github/myusername/myproject">
    <img alt="Coveralls" src="https://img.shields.io/coveralls/github/myusername/myproject?style=flat-square&logo=coveralls">
  </a>
  <a href="https://deepscan.io/dashboard#view=project&tid=YOUR_TEAM_ID&pid=YOUR_PROJECT_ID&bid=YOUR_BRANCH_ID">
    <img src="https://deepscan.io/api/teams/YOUR_TEAM_ID/projects/YOUR_PROJECT_ID/branches/YOUR_BRANCH_ID/badge/grade.svg" alt="DeepScan grade">
  </a>
  <a href="https://eslint.org/">
    <img alt="Linter eslint" src="https://img.shields.io/badge/linter-eslint-8080f2?style=flat-square&logo=eslint">
  </a>
  <a href="https://prettier.io/">
    <img alt="Code style prettier" src="https://img.shields.io/badge/code%20style-prettier-f8bc45?style=flat-square&logo=prettier">
  </a>
  <img alt="Repository top language" src="https://img.shields.io/github/languages/top/myusername/myproject?style=flat-square">
  <a href="https://www.gitpoap.io/gh/myusername/myproject" target="_blank">
    <img src="https://public-api.gitpoap.io/v1/repo/myusername/myproject/badge">
  </a>
  <a href="http://commitizen.github.io/cz-cli/">
    <img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-586D76?style=flat-square">
  </a>
</p>

<div align="center">
  <h4>
    <a href="/CONTRIBUTING.md">
      👥 Contributing
    </a>
    <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
    <a href="/CODE_OF_CONDUCT.md">
      🤝 Code of Conduct
    </a>
    <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
    <a href="https://github.com/myusername/myproject/issues">
      🔎 Issues
    </a>
    <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
    <a href="https://t.me/myprojectchat">
      🗣️ Chat &amp; Support
    </a>
    <span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
    <a href="https://docs.myprivacyprotocol.dev">
      💻 API Reference
    </a>
  </h4>
</div>

| MyPrivacyProtocol is a generic privacy layer I developed. Leveraging zero-knowledge technology, it enables users to prove their membership in groups and send messages—ranging from votes to endorsements—off-chain or across multiple EVM-compatible blockchains without compromising personal identity. |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

The heart of MyPrivacyProtocol lies in its [circuit logic](/packages/circuits/scheme.png). In addition, I provide [Solidity contracts](/packages/contracts) and JavaScript libraries to streamline both off-chain proof generation and on-chain/off-chain verification. To learn more about this project, visit [docs.myprivacyprotocol.dev](https://docs.myprivacyprotocol.dev).

> [!IMPORTANT]  
> I invite you to contribute and share your ideas to help MyPrivacyProtocol grow and improve. Your feedback is invaluable!

## 📦 Packages

<table>
  <tr>
    <th>Package</th>
    <th>Version</th>
    <th>Downloads</th>
  </tr>
  <tr>
    <td>
      <a href="/packages/core">
        @myprivacyprotocol/core
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/core">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/core.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/core">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/core.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/contracts">
        @myprivacyprotocol/contracts
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/contracts">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/contracts.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/contracts">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/contracts.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/identity">
        @myprivacyprotocol/identity
      </a>
      <a href="https://docs.myprivacyprotocol.dev/modules/_myprivacyprotocol_identity">
        (docs)
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/identity">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/identity.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/identity">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/identity.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/group">
        @myprivacyprotocol/group
      </a>
      <a href="https://docs.myprivacyprotocol.dev/modules/_myprivacyprotocol_group">
        (docs)
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/group">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/group.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/group">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/group.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/proof">
        @myprivacyprotocol/proof
      </a>
      <a href="https://docs.myprivacyprotocol.dev/modules/_myprivacyprotocol_proof">
        (docs)
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/proof">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/proof.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/proof">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/proof.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/data">
        @myprivacyprotocol/data
      </a>
      <a href="https://docs.myprivacyprotocol.dev/modules/_myprivacyprotocol_data">
        (docs)
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/data">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/data.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/data">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/data.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/hardhat">
        @myprivacyprotocol/hardhat
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/hardhat">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/hardhat.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/hardhat">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/hardhat.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/cli">
        @myprivacyprotocol/cli
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/cli">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/cli.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/cli">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/cli.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="/packages/utils">
        @myprivacyprotocol/utils
      </a>
      <a href="https://docs.myprivacyprotocol.dev/modules/_myprivacyprotocol_utils">
        (docs)
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/utils">
        <img src="https://img.shields.io/npm/v/@myprivacyprotocol/utils.svg?style=flat-square" alt="NPM version" />
      </a>
    </td>
    <td>
      <a href="https://npmjs.org/package/@myprivacyprotocol/utils">
        <img src="https://img.shields.io/npm/dm/@myprivacyprotocol/utils.svg?style=flat-square" alt="Downloads" />
      </a>
    </td>
  </tr>
</table>

## 🛠 Install

Clone this repository:

```bash
git clone https://github.com/myusername/myproject.git
