<!-- omit in toc -->
# @resourcedao/rsc-user-verify
### user's crypto address and twitter account

[![GitHub Workflow Status (main)](https://img.shields.io/github/workflow/status/jhildenbiddle/docsify-plugin-runkit/Build/main?label=checks&style=flat-square)]()
[![Codacy grade](https://img.shields.io/codacy/grade/e9c2a9504211450ab39e0d72a1158a47.svg?style=flat-square)]()

?> To install our private packages you need a RSC key to decrypt our packs sent from RSC Storage, ask a DAO member how to obtain

<!-- omit in toc -->

## Installation

```terminal
npm install @resourcedao/rsc-user-verify
or
npx install @resourcedao/rsc-user-verify
or
yarn install @resourcedao/rsc-user-verify
```

## Usage

```javascript
import verifyUserClient from '@resourcedao/rsc-user-verify'

const twitterConfig = {
  bearer_token: process.env.BEARER_TOKEN,
}

const adminAddress = process.env.ARWEAVE_ADDRESS;
const arweaveKeyfile = process.env.ARWEAVE_KEY;

const client = new verifyUserClient(twitterConfig, adminAddress, arweaveKeyfile);
```

<script async defer src="https://buttons.github.io/buttons.js"></script>