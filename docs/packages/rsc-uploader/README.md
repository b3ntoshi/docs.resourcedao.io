<!-- omit in toc -->
# @resourcedao/rsc-uploader
### Uploads file to RSC's Arweave Nodes.

[![GitHub Workflow Status (main)](https://img.shields.io/github/workflow/status/jhildenbiddle/docsify-plugin-runkit/Build/main?label=checks&style=flat-square)]()
[![Codacy grade](https://img.shields.io/codacy/grade/e9c2a9504211450ab39e0d72a1158a47.svg?style=flat-square)]()

?> To install our private packages you need a RSC key to decrypt our packs sent from RSC Storage, ask a DAO member how to obtain

<!-- omit in toc -->

## Features
- Uploads files to Arweave
- Routes through RSC Arweave nodes

## Installation

```terminal
npm install @resourcedao/rsc-uploader
or
npx install @resourcedao/rsc-uploader
or
yarn install @resourcedao/rsc-uploader
```

## Usage

```javascript
import rscUploader from '@resourcedao/rsc-uploader';

rscUploader({
    key: 'Your ID key'
})

```

<script async defer src="https://buttons.github.io/buttons.js"></script>